# The end of Dig Dug.

Chances are, your Dig Dug page is full of random attempts at getting things to cooperate.  Some successful, and some not, but either way, it's a collection of your efforts so far this semester.  We want to see what you've accomplished (or at least tried).  At the end of this exercise, you'll submit your final version of your Dig Dug pages.  But first...

## One last thing...

You probably have a Description List element in your page that doesn't look like much... Just a weirdly indented list of Categories and Values.  It turns out that Description Lists are kind of notoriously difficult to style... In part because they allow for some unusual structures (including multiple `<dd>`s connected to multiple `<dt>`s).  

But if you keep your code fairly simple, here are three different CSS blocks that you can try out with your page.  Each uses a different approach.  One with floats, One with flexbox, and One without either.  Try each one and keep one you like.

```
dt {
    float: left;
    clear: left;
    width: 6rem;
    text-align:right;
    margin-right:1em;
    font-weight: bold;
    color: blueviolet;
   }
dd {
    margin-left: 7rem;
    padding-bottom: 0.5rem;
   }	
```

```
dl {
    display: flex;
    flex-flow: row wrap;
    border: solid #333;
    border-width: 1px 1px 0 0;
   }
dt {
    flex-basis: 20%;
    padding: 2px 4px;
    background: #333;
    text-align: right;
    color: #fff;
   }
dd {
    flex-basis: 70%;
    flex-grow: 1;
    margin: 0;
    padding: 2px 4px;
    border-bottom: 1px solid #333;
   }
```

```
dl dd {
    display: inline;
    margin: 0;
   }
dl dd:after {
    display: block;
    content: '';
   }
dl dt {
    display: inline-block;
    min-width: 100px;
   }
```

## Submit your work.
1.	Upload it to one (or both if you want) of your banjo accounts in the 235 directory.  You can leave it in the ‘game’ directory or you can make a new directory.
2.	You should zip up your complete game directory (with images, css, second html page, favicons, etc).
3.	Go to myCourses and submit the zip file to the Group Assignment titled “HTML ICE Work”
4.	In the Comments field, supply the URL to the page live in someone’s banjo account.




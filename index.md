# __Web Developement Road Map__
## __This is a Complete Web Development Road Map__

>All The Documentation is written in this page : [Web-BootCamp](https://zakariarhiba.github.io/Web-BootCamp)

_learn basics of web developement such us :_
* HTML
* CSS
* JavaScript
* BootStrap
* and more...
___
### __The best way to learn Web developement__
For me the best way that's worked and when I started doing it that's help me to see some progress and I'm be able to develop some stuff from zero by the following :

* First I recommend to start with the basics and the fundamentals of everything that's this Documentation provide

* Don't try to remembre everything, just focus on understand the concepts and how to use the technologies 

 * Start building projects, That's the goal of writing this documentation, It's give you a amazing projects that's you can do with basic understanding that's makes you learn more and be able to build projects on your own

#### __References :__
* [DevDocs documentation](https://devdocs.io/)
* [MDN Documentation](https://developer.mozilla.org/)
* [W3school](https://www.w3schools.com/)
* [The Complete Web Development BootCamp By Angela Yu](https://www.youtube.com/playlist?list=PLmv0h_u-BMKtON5uMdSz4_4zwnd2gyXNq)

___

# **HTML Introduction** 

First we begin our journey by introduce some basics html tags such as heading and paragraph, also we see the difference between end tags and self end tags.

### The HTML structure is describe as the following: 

```HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <!--
     Here we write the description of the page 
     such as title, icon, style sheet links and more   
    -->
</head>
<body>
    <!-- Here where we write the content of the page-->
</body>
</html>
```
### The HTML comments are written as :
```HTML
<!DOCTYPE html>
<html lang="en">
<body>
    <!-- This is a comments-->
</body>
</html>
```
>The comments are not have any effect of the codes, you can use them to descripe what are you doing in the code if some other personne read your code or maybe you gonna return to your code after a while and try to remembre what you do.

### **To follow this Documentation is order as follow :**

At every file of those I descripe all what's necessary in the Html comments make sure to read them, if you have any question or you want a personal tutoring visit my portfolio to contact me : [Rhiba Zakaria porfolio](https://zak-rhiba.codes)

* [Html Introduction](html_Introduction.html)

* [Old Personal Website exemple](FirstPage.html)

* [More HTML Elements](FirstPage1.html)

* [Using Tables for layout](FirstPage2.html)

* [Form elements](Contact.html)

### Now you know all what you need to start building wonderful project, you're challenge now is to recreate your own resume, be creative and feel free to use documenation it's your angel !

#### Here you'll find my own version if you want to get inspire: 

* [Final Project](index.html)

___

# **CSS - cascading style sheets**

*In this Section we'll introduce the basics CSS Syntax and learn how to use it, the beautifull thing is that we'll learn CSS by practice it on our personal page that we build in HTML Section Check it out.*

## **CSS Introduction**

They are 3 main ways we can implement css in html :  

* First we can add css at each element as an attribute as the following :

```HTML
<body style="background-color: #E9DAC1;">
```
In this exemple we add a background color to the body element, by that this background's gonna apply at all the elements that's inside the body element see the effect in this [Exemple](index.html).

* Second way is by written the css code in the in the style element on the head element of HTML :

```HTML
<!DOCTYPE html>
    <html lang="en">
    <head>
        <style>
            /* 
                here we write the css code 
            */
        </style>
    </head>
    <body>
        <!-- page elements -->
    </body>
    </html>
```
#### CSS Comment :

```CSS
/* This is a css comment */     
```
### CSS Syntax :
```CSS
selector {
      proprety : value;
    }    
```

>You can use also id or class to apply styles instead of element tag

* Finally we can create an externele file with .css extension and link it with the html code as we did in our [personal page](index.html).

#### To link the style.css in html write in the above element in the head of html :

```HTML
<!DOCTYPE html>
<html>
    <head>
        <link rel="stylesheet" href="style.css">
    </head>
<body>
    <h1>This is a heading</h1>
    <p>This is a paragraph.</p>
</body>
</html>
```

### **First CSS Challenge**

*Now we know all what we need to start our journey with css, and remember documentation its our lovely friend who's gonna be always for help*

as first challenge I want you to apply the same style of all the pages for our personal page and change the headings colors for exemple.

> The solution its availble on the project itself, but practice it before you see it.

### **Selectors**

In HTML we have two selectors 

* ID
* CLASS

The id  attribute its used for a single item, if you want to apply a style or use it in js, we'll discuss that later

```HTML
 <!-- This is an exemple of how to use id -->
 <h1 id="heading">RHIBA Zakaria</h1>
```

The class attribute its used for a groups of items that you wants them to behave with same styles or actions

```HTML
 <!-- This is an exemple of how to use class -->
 <h1 class="persons">RHIBA Zakaria</h1>
```

### **CSS Selectors Syntax**

Here I'm written the tree different syntax of how to use selecters :

* HTML Tags:

```CSS
h1{
    color: #54BAB9;
}
```

* Id attribute:

```CSS
#heading {
    color: #F94892;
}
```

* CLass attribute:

```CSS
.heading{
    background-color: #F94892;
}
```

#### Sudo Class 

Sudo Class it's descripe the stat of the elements, for exemple we use if we hover an image we change it's background color : 

```CSS
img:hover {
    background-color: gold;
}
```

___

Congrats ! Now we know all what we need to start create an awesome profissonal page for twenty's instead of ninety's 

___

For Personal Coashing or if you have any Question or Collaborate feel free to visit my portfolio and contact me 

> you can visit my protfolio over here :
[Rhiba Zakaria porfolio](https://zak-rhiba.codes)

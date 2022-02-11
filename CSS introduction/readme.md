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

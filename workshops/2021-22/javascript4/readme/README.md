
# Workshop 5: Voice Recognition

Today, we will learn how to implement voice recognition in JavaScript using the library p5.js! This has a wide variety of applications and can be included in many projects. 

### Step 1: Setting Up The Coder

First, log onto your repl.it account and create a new HTML/JS/CSS repl. This should give you a base project with a basic `index.html`. 
In the `<head>`, copy the following lines of code in.
```html
<script src="https://cdn.jsdelivr.net/npm/p5@1.4.0/lib/p5.js"></script>
<script src="https://cdn.jsdelivr.net/gh/IDMNYU/p5.js-speech@0.0.3/lib/p5.speech.js"></script>
<script src="https://cdn.jsdelivr.net/npm/p5@1.4.0/lib/addons/p5.sound.js"></script>
```
This will import the necessary libraries we need for this project: p5 and p5.speech. 
p5.sound (the last one) is optional. Only include it if you are going to play sound/audio files in your project. 

Make sure your `index.html` file is linked to your `script.js` file, and then we're ready to begin!

### Step 2: Setting up the HTML File 

After creating the repl, you should see the following on your page:

```html
<!DOCTYPE html>
<html>
    <head>
    </head>
    <body>
    </body>
</html>
```
This is the backbone of the HTML file that will contain the rest of the code. 

Make sure to save as you go along by clicking `file` and `save` or use the shortcut <kbd>Ctrl+s</kbd>. 

You can preview the page by clicking `Preview` on the top bar and then selecting `Live Preview File`.

#### Side Notes:
Repl automatically saves your code so you don’t have to worry about losing your work.

You can press the Run tab at the top of your screen at any point to test run the code that you have.

### Step 3: Adding Text

We can now begin to add text to your website. HTML has numerous different formats for text, accessed through the use of different elements. 

Heading elements are used to create headers and are denoted by: `<h1>`, `<h2>`, `<h3>` … `<h6>`

There is also a paragraph element, which is used to create paragraph text. It is accessed through `<p>` 

Text must be written in between a starting tag (ex: `<h1>`) and an ending tag (ex: `</h1>` in order to be displayed on your page. 

Try to add some text to your page! An example is shown below. 


```html
<!DOCTYPE html>
<html>
    <head>
    </head>
    <body>
        <p>This is a paragraph about my website!</p> <!--paragraph-->
        <h2>Favorite Foods</h2> <!--Heading 2-->
        <p>This is a paragraph about my favorite foods!</p> <!--paragraph-->
        <h2>Favorite Color</h2> <!--Heading 2-->
        <p>This is a paragraph about my favorite color!</p> <!--paragraph-->
    </body>
</html>
```
  
### Step 4: Formats

Although there are several ways you can stylize your text directly through HTML with the use of tags, it is still rather limited. 

We will go over how to further expand your options with the use of CSS in future workshops.
  
`<b>` - Bold text <br>
`<strong>` - Important text <br>
`<em>` - Emphasized text <br>

* although these first 3 have the same default display, they have different semantics on a page 

`<i>` - Italic text <br>
`<mark>` - Marked/highlighted text <br>
`<small>` - Smaller text <br>
`<sub>` - Subscript text <br>
`<sup>` - Superscript text <br>
`<del>` - Deleted text <br>
`<ins>` - Inserted text <br>

### Step 5: Lists

Lists are another element that can be used to format text in HTML.
  
Unordered lists are used to display items as bullet points. 
The unordered list tag is `<ul>` and each list item is then prefaced with the tag `<li>`


```html
<!DOCTYPE html>
<html>
    <head>
    </head>
    <body>
        <!-- Unordered List-->
        <ul>
          <li>Red</li>
          <li>Orange</li>
          <li>Yellow</li>
          <li>Green</li>
        </ul>
    </body>
</html>
```

Ordered lists are used to display items in a numbered list. 
The ordered list tag is `<ol>` and like the unordered list, each list item must have the tag `<li>` before it.

```html
<!DOCTYPE html>
<html>
    <head>
    </head>
    <body>
        <!--Ordered List-->
        <ol>
          <li>Science</li>
          <li>Math</li>
          <li>English</li>
          <li>Social Studies</li>
        </ol>
    </body>
</html>
```

### Step 6: Pictures

Images and GIFs are added in HTML with the <img> tag

It is formatted as `<img src = “...” alt = “...” style = “...”>` 

The src attribute is the source of the image, which can be either a URL or a file path of the image. 

The alt attribute is the alternative for if the image is not able to be displayed. 
It is usually set as what the image is supposed to be. 

The style attribute modifies the shape of the image using `width:` and `height:`, as well as its position on the screen with `float:`.

```html
<!DOCTYPE html>
<html>
    <head>
    </head>
    <body>
      <img src="baby.gif" alt="Photo of Infant" style="float:right;width:50px;height:50px;">
    </body>
</html>
```

### Step 7: Put it all together!

Now it's time to combine all of these steps and create a personal website on your own!

### Challenge

Try to add a navigation bar to your website! You can use the internet or other resources as a guide.

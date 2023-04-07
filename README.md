# HTML 

Hyper Text Markup Language

**Code Editors**

 - [Visual Studio Code](https://code.visualstudio.com/)
 - [ATOM](https://github.blog/2022-06-08-sunsetting-atom/)
 - [BRACKETS](http://brackets.io/)
 - [PhpStorm](https://soft98.ir/software/programming/3845-phpstorm)
 - [Notepad++](https://notepad-plus-plus.org/downloads/)

**Tag**

```html
<tagname> Content goes here... </tagname>

<html> HTML document content </html>
```
  **Introduction to the HTML document**
  
All HTML documents must start with a `<!DOCTYPE>` declaration.

```html
<!doctype html>
```

## HTML Document structure

Simple HTML document

```html
<!doctype html>
<html lang="en" dir="rtl">
    <head>
    </head>
	    
    <body>
    </body>
</html>
```
head: _Search engine information structure_ body: _User information structure_

## HTML document title

The `<title>` tag defines the title of the document. The title must be text-only, and it is shown in the browser's title bar or in the page's tab.

```html
<!doctype html>
<html>
    <head>
	<title> webdenj website </title>
    </head>
    <body>
    </body>
</html>
```
## HTML content

The `<body>` tag defines the document's body. There can only be one `<body>` element in an HTML document.

```html
<!doctype html>
<html>
    <head>
	<title> webdenj website </title>
    </head>
    <body>
	This is my website
    </body>
</html>
```

## Heading Tags

The `<h1>` to `<h6>` tags are used to define HTML headings.

```html
<h1>heading1</h1>
<h2>heading2</h2>
<h3>heading3</h3>
<h4>heading4</h4>
<h5>heading5</h5>
<h6>heading6</h6>
```

## Paragraph Tag

```html
<p>This is first paragraph</p>
<p>This is second paragraph</p>
<p>This is third paragraph</p>
```
## Important Tags
The `<strong>` tag is used to define text with strong importance. The content inside is typically displayed in **bold**.

```html
<h2>webdenj</h2>

<p>Lorem ipsum dolor sit amet consectetur <strong>adipisicing elit</strong> Provident obcaecati suscipit</p>
```

> Note : Use the  `<b>`  tag to specify bold text without any extra importance!

The `<em>` tag is used to define emphasized text. The content inside is typically displayed in _italic_.

```html
<h2>webdenj</h2>

<p>Lorem ipsum dolor sit amet consectetur <em>adipisicing elit</em> Provident obcaecati suscipit</p>
```

## Break line Tag
The `<br>` tag inserts a single line break.

```html
My name is Amir <br> I am Programmer
```

## Horizontal Tag
The `<hr>` tag defines a thematic break in an HTML page

```html
My name is Amir<hr> I am Programmer
```

## Comment in HTML
You can add comments to your HTML source by using the following syntax:

```html
<!-- This is a comment -->  
<p>This is a paragraph.</p>  
<!-- Remember to add more information here -->
```	
## Image Tag
The `<img>` tag is used to embed an image in an HTML page.

```html
<img src="webdenj.png" alt="webdenj.png" width="200" height="50" />
```
## List Tag

**Order lists** An ordered list starts with the `<ol>` tag. Each list item starts with the `<li>` tag.

```html
<ol>
<li>Home</li>
<li>About Us</li>
<li>News</li>
<li>Contact Us</li>
</ol>
```

**Unorder list** An unordered list starts with the `<ul>` tag. Each list item starts with the `<li>` tag.

```html
<ul>
<li>Home</li>
<li>About Us</li>
<li>News</li>
<li>Contact Us</li>
</ul>
```

## Link tag

The `<a>` tag defines a hyperlink, which is used to link from one page to another.

```html
<a href="http://google.com"> Go to Google</a>
```

A linked page is normally displayed in the current browser window, unless you specify another target.

```html
<a href="http://google.com" target="_blank"> Go to Google</a>
```
The `rel` attribute specifies the relationship between the current document and the linked document.
 
 ```html
<a rel="nofollow" href="http://google.com" target="_blank"> Go to Google</a>
```

> **Tip:** Search engines can use this attribute to get more information about a link!
## Table Tag

The `<table>` tag defines an HTML table. An HTML table consists of one `<table>` element and one or more `<tr>`  `<th>` and `<td>` elements.

```html
<table>  
   <tr>  
       <th>Name</th>  
       <th>Family</th> 
       <th>Age</th>  
   </tr>  
   <tr>  
       <td>Amir</td>  
       <td>Zamani</td>  
       <td>30</td>
   </tr>
   <tr>  
       <td>Ali</td>  
       <td>Mohammadi</td>  
       <td>25</td>
   </tr>  
</table>
```
An HTML table with a `<thead>` and `<tbody>` element:

```html
<table>
    <thead>  
        <tr>  
            <th>Name</th>  
            <th>Family</th> 
            <th>Age</th>  
        </tr>
    </thead> 
    <tbody>
        <tr>  
            <td>Amir</td>  
            <td>Zamani</td>  
            <td>30</td>
        </tr>
        <tr>  
            <td>Ali</td>  
            <td>Mohammadi</td>  
            <td>25</td>
        </tr>
    </tbody> 
    </table>
```
## Video Tag

The HTML `<video>` element is used to show a video on a web page.

```html
<video width="320"  height="240"  controls>  
	<source src="movie.mp4"  type="video/mp4">  
	<source src="movie.ogg"  type="video/ogg">  
Your browser does not support the video tag.  
</video>
```

To start a video automatically, use the `autoplay` attribute:

```html
<video width="320"  height="240"  autoplay>  
	<source src="movie.mp4"  type="video/mp4">  
	<source src="movie.ogg"  type="video/ogg">  
Your browser does not support the video tag.  
</video>
```

## Audio Tag

The HTML  `<audio>`  element is used to play an audio file on a web page.

```html
<audio controls>  
	<source src="horse.ogg"  type="audio/ogg">  
	<source src="horse.mp3"  type="audio/mpeg">  
Your browser does not support the audio element.  
</audio>
```

To start an audio file automatically, use the `autoplay` attribute:

```html
<audio controls autoplay>  
	<source src="horse.ogg"  type="audio/ogg">  
	<source src="horse.mp3"  type="audio/mpeg">  
Your browser does not support the audio element.  
</audio>
```
	
## Forms
An HTML form is used to collect user input. The user input is most often sent to a server for processing.

```html
<form action="http://gitmag.ir" method="GET">
...
</form>
```

**Input tag** One of the most used form element is the `<input>` element. The `<input>` element can be displayed in several ways, depending on the `type` attribute.

```html
<form>
    <label for="fname">First name:</label><br>  
    <input type="text" id="fname" name="fname"><br><br>
    <label for="lname">Last name:</label><br>  
    <input type="text" id="lname" name="lname"><br><br>
</form>
```

`<input type="submit">` defines a button for **submitting** form data to a **form-handler**:

```html
<form>
    <label for="fname">First name:</label><br>  
    <input type="text" id="fname" name="fname"><br><br>
    <label for="lname">Last name:</label><br>  
    <input type="text" id="lname" name="lname"><br><br>
    <input type="submit" value="Submit">
</form>
```

`<input type="checkbox">` defines a **checkbox**:

```html
<form>
    <label for="fname">First name:</label><br>  
    <input type="text" id="fname" name="fname"><br><br>
    <label for="lname">Last name:</label><br>  
    <input type="text" id="lname" name="lname"><br><br>
    <label for="RememberMe">Remember Me</label>
    <input type="checkbox" id="RememberMe" name="lname"><br><br> 
    <input type="submit" value="Submit">
</form>
```

`<input type="radio">` defines a **radio button**:

```html
<form>  
     <input type="radio" id="html" name="fav_language" value="HTML">  
     <label for="html">HTML</label><br>  
     <input type="radio" id="css" name="fav_language" value="CSS">  
     <label for="css">CSS</label><br>  
     <input type="radio" id="javascript" name="fav_language" value="JavaScript">  
     <label for="javascript">JavaScript</label>  
</form>
```

**Textarea tag** The `<textarea>` element defines a multi-line input field (a text area):

```html
<textarea name="message" rows="10" cols="30">  
	The cat was playing in the garden.  
</textarea>
```

## id Attribute

The HTML `id` attribute is used to specify a unique id for an HTML element.

```html
<html>
    <head>
    <style>
        .my-paragraphs {
           font-family: Arial;
           color: red;
         }
    </style>
    <body>
       <p id="my-paragraphs">This is the first paragraph.</p>
       <p class="my-paragraphs">This is the second paragraph.</p>
    </body>
</html>
```

## class Attribute

The HTML `class` attribute is used to specify a class for an HTML element.

```html
<html>
    <head>
    <style>
        .my-paragraphs {
           font-family: Arial;
           color: red;
         }
    </style>
    <body>
       <p class="my-paragraphs">This is the first paragraph.</p>
       <p class="my-paragraphs">This is the second paragraph.</p>
    </body>
</html>
```
## iFream Tag

The HTML `<iframe>` tag specifies an inline frame.

```html
<iframe src="url"  frameborder="0"></iframe>
```
The height and width are specified in pixels by default:

```html
<iframe src="https://webdenj.com"  height="200"  width="300"  frameborder="0"></iframe>
```

## div  Tag
The `<div>` tag defines a division or a section in an HTML document.

```html
<div>
    <h2>webdenj.com</h2>
    <p>This is a paragraph</p>
</div> 
```

A `<div>` section in a document styled with CSS:

```html
<html>
    <head>
    <style>
    #header{
        border : 2px solid black;
        margin: 20px;
        padding: 20px;
    }
    
    #content{
        border : 2px solid red;
        margin: 20px;
        padding: 20px;
    }
    
    #footer{
        border : 2px solid yellow;
        margin: 20px;
        padding: 20px;
    }
    </style>
    </head>
    <body>
    
        <div id="header">
            <h2>header</h2>
            <p>website header</p>
        </div> 
    
        <div id="content">
            <h3>content</h3>
            <p>content section website</p>
        </div>
    
        <div id="footer">
            <p>Copyright 1999-2023</p>
        </div>
    
    </body>
</html>
```


## Span Tag

The `<span>` tag is an inline container used to mark up a part of a text, or a part of a document.

    <p>Lorem ipsum dolor sit amet,<span style="color:red">consectetur</span> adipiscing elit.</p>
    
## Semantic Tag

```html
<div  id="header">
    <h2>webdenj</h2>
    <div  id="nav">
	    <ul>
		<li>Item 1</li>
		<li>Item 2</li>
	    </ul>
    </div>

</div>
<div  class="main">
    <div  id="article"></div>
    <div  id="aside"></div>
</div>

<div  id="footer">
    <p>Copyright 1999-2023</p>
</div>
```
    
A semantic element clearly describes its meaning to both the browser and the developer.

```html
<header>
    <h2>webdenj</h2>
    <nav>
        <ul>
	    <li>Item 1</li>
            <li>Item 2</li>
	</ul>
   </nav>
</header>

<div  class="main">
        <article>
	    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
	</article>
    <aside></aside>
</div>

<footer>
	<p>Copyright 1999-2023</p>
</footer>
```

## Section Tag
The `<section>` tag defines a section in a document.

```html
<section>
     <h2>webdenj website</h2>
     <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
</section>
```

## Article Tag

The `<article>` tag specifies independent, self-contained content.

```html

<h1>webdenj</h1>

<article>
     <h2>webdenj website</h2>
     <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
</article>
```

## Meta tags

The `<meta>` tag defines metadata about an HTML document. Metadata is data (information) about data.

```html
<head>  
    <meta charset="UTF-8">  
    <meta name="description" content="Free Web tutorials">  
    <meta name="keywords" content="HTML, CSS, JavaScript">  
    <meta name="author" content="John Doe">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
```

> keywords: _Define keywords for search engines_ description: _Define a description of your web page_ author: _Define the author of a page_

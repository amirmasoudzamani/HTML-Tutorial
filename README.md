# HTML 
**Code Editors**

 - [Visual Studio Code](https://code.visualstudio.com/)
 - [ATOM](https://github.blog/2022-06-08-sunsetting-atom/)
 - [BRACKETS](http://brackets.io/)
 - [Notepad++](https://notepad-plus-plus.org/downloads/)


Hyper Text Markup Language


**Tag**

```html
<tagname> Content </tagname>

<html> HTML document content </html>

<tagname />

<img />
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
	     <title> CodeExplore </title>
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
	     <title> CodeExplore </title>
    </head>
    <body>
	     This is my website
    </body>
</html>
```
## Break line Tag
The `<br>` tag inserts a single line break.

```html
My name is John <br> Im Programmer
```

## Horizontal Tag
The `<hr>` tag defines a thematic break in an HTML page

```html
My name is John<hr> Im Programmer
```
## Paragraph Tag

The HTML `<p>` element defines a paragraph.

```html
<p>This is first paragraph</p>
<p>This is second paragraph</p>
<p>This is third paragraph</p>
```

### Paragraph Editable
```html
<p contenteditable="true">This is first paragraph</p>
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

## Formatting tags

Formatting elements were designed to display special types of text:

`<b>` - Bold text 
`<strong>` - Important text 
`<i>` - Italic text 
`<small>` - Smaller text ...

```html
<p>
	In publishing and <b>graphic design</b>, Lorem ipsum is a placeholder text commonly used to demonstrate the visual form of a document or a typeface without relying on <strong>meaningful content</strong>.
</p>
<p>
	Lorem ipsum may be used as a <small>placeholder</small> before <i>final copy is available</i>.
</p>
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
<img src="https://codeexplore.ir/wp-content/uploads/2024/07/mobile-logo.png" loading="lazy" alt="CodeExplore Logo" width="200" height="100" />
```
## List Tag

**Order lists** An ordered list starts with the `<ol>` tag. Each list item starts with the `<li>` tag.

```html
<ol type="1" >
	<li>Home</li>
	<li>About Us</li>
	<li>News</li>
	<li>Contact Us</li>
</ol>
```

**Unorder list** An unordered list starts with the `<ul>` tag. Each list item starts with the `<li>` tag.

```html
<ul type="none" >
	<li>Home</li>
	<li>About Us</li>
	<li>News</li>
	<li>Contact Us</li>
</ul>
```
**Description lists** A description list is a list of terms, with a description of each term.
The `<dl>` tag defines the description list, the `<dt>` tag defines the term (name), and the `<dd>` tag describes each term:

```html 
<dl>
	 <dt>HTML</dt>
	  <dd>» Front-End</dd>
	 <dt>CSS</dt>
	  <dd>» Front-End</dd>
	 <dt>PHP</dt>
	  <dd>» Back-End</dd>
</dl>
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

> Target attribute values:
>  _self: _Opens the linked document in the same frame as it was clicked (**this is default**)_ 
>  _blank: _Opens the linked document in a new window or tab_
>  _parent: _Opens the linked document in the parent frame_ 
>  _top: _Opens the linked document in the full body of the window_ 


The `rel` attribute specifies the relationship between the current document and the linked document.

 
 ```html
<a rel="nofollow" href="http://google.com" target="_blank"> Go to Google</a>
<a rel="author" href="http://codeexplore.ir" target="_blank"> Go to CodeExplore</a>
```

> Search engines can use this attribute to get more information about a link!
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
       <td>Mohammad</td>  
       <td>Hosseini</td>  
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
            <td>Mohammad</td>  
            <td>Hosseini</td>  
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
	Your browser does not support the video tag.  
</video>
```

To start a video automatically, use the `autoplay` attribute:

```html
<video width="320"  height="240"  autoplay>  
	<source src="movie.mp4"  type="video/mp4">    
	Your browser does not support the video tag.  
</video>
```

## Audio Tag

The HTML  `<audio>`  element is used to play an audio file on a web page.

```html
<audio controls>    
	<source src="audio.mp3"  type="audio/mpeg">  
	Your browser does not support the audio element.  
</audio>
```

To start an audio file automatically, use the `autoplay` attribute:

```html
<audio controls autoplay>    
	<source src="audio.mp3"  type="audio/mpeg">  
	Your browser does not support the audio element.  
</audio>
```
	
## Forms
An HTML form is used to collect user input. The user input is most often sent to a server for processing.


```html
<form action="#" method="GET">
...
</form>
```

**Input tag** One of the most used form element is the `<input>` element. The `<input>` element can be displayed in several ways, depending on the `type` attribute.

```html
<label for="fname">First name:</label>  
<input type="text" id="fname" name="fname">
```

> text: _Displays a single-line text input field_  
> radio: _Displays a radio button (for selecting one of many choices)_  
> checkbox: _Displays a checkbox (for selecting zero or more of many choices)_  
> submit: Displays a submit button (for submitting the form)_ 
> button: _Displays a clickable button_  
> color: _Displays a color picker_ 
> file: _ Display a "Browse" button for file uploads._

`<input type="submit">` defines a button for **submitting** form data to a **form-handler**:

```html
<input type="submit" value="Submit">
```

**Textarea tag** The `<textarea>` element defines a multi-line input field (a text area):

```html
<textarea name="message" rows="10" cols="30">  
	The cat was playing in the garden.  
</textarea>
```
**Select tag** The `<select>` element defines a drop-down list:
```html
<select name="cars" multiple>  
    <option value="volvo">Volvo</option>  
    <option value="benz">Benz</option>  
    <option value="fiat">Fiat</option>  
    <option value="audi">Audi</option>  
</select>
```

`<input type="checkbox">` defines a **checkbox**:

```html
<label for="RememberMe">Remember Me</label>
<input type="checkbox" id="RememberMe" name="remember">
```

`<input type="radio">` defines a **radio button**:

```html 
<label for="html">HTML</label>
<input type="radio" id="html" name="fav_language" value="HTML">
<label for="css">CSS</label>    
<input type="radio" id="css" name="fav_language" value="CSS">
<label for="javascript">JavaScript</label>     
<input type="radio" id="javascript" name="fav_language" value="JavaScript">  
```
 `<input type="color">` defines a color picker.
```html
<label for="favcolor">Select your favorite color:</label>
<input type="color" id="favcolor" name="favcolor">
```
`<input type="file">` defines a file-select field and a "Browse" button for file uploads.

```html
<label for="myfile">Select a file:</label>  
<input type="file"  id="myfile"  name="myfile" accept="jpg" multiple>
```
## iFrame Tag

The HTML `<iframe>` tag specifies an inline frame.

```html
<iframe src="url"  frameborder="0"></iframe>
```
The height and width are specified in pixels by default:

```html
<iframe src="https://www.wikipedia.org/"  width="300" height="200" frameborder="0"></iframe>
```
## id Attribute

The HTML `id` attribute is used to specify a unique id for an HTML element.

```html
<h2 id="title">CodeExplore</h2>
<p id="caption">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Ad temporibus voluptatum consectetur maiores dignissimos reiciendis itaque placeat nobis recusandae alias!</p>
<hr>
<h3>CodeExplore</h3>
<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Natus minus beatae error minima, doloremque fugit neque at quam!</p>
```

## class Attribute

The HTML `class` attribute is used to specify a class for an HTML element.

```html
<h2 class="title">CodeExplore</h2>
<p class="caption">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Ad temporibus voluptatum consectetur maiores dignissimos reiciendis itaque placeat nobis recusandae alias!</p>
<hr>
<h3 class="title">CodeExplore</h3>
<p class="caption">Lorem ipsum dolor sit amet consectetur adipisicing elit. Natus minus beatae error minima, doloremque fugit neque at quam!</p>
```

> The class attribute can be used on any HTML element.

## divider  Tag
The `<div>` tag defines a division or a section in an HTML document.

```html
<div id="header"> Website Header </div>
<div id="navbar"> Website Navbar </div>
<div id="main">
    <div id="sidbar"> Website Sidebar </div>
    <div id="content"> Website Content </div>
</div>
<div id="footer"> Website Footer </div>
```

## Span Tag

The `<span>` tag is an inline container used to mark up a part of a text, or a part of a document.

```html
<p>Lorem ipsum dolor sit amet,<span style="color:red">consectetur</span> adipiscing elit.</p>
```
## Semantic Tags

A semantic element clearly describes its meaning to both the browser and the developer.

```html
<header> Website Header </header>
<nav> Website navbar </nav>
<main>
    <aside>Website Sidebar</aside>
    <sction>Section</sction>
    <article>Article</article>
</main>
<footer>Website Footer</footer>
```
**Other semantic elements**
```html
<details>
    <summary>Learn more</summary>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
</details>

<figure>
    <img src="./mobile-logo.png" alt="CodeExplore Logo" width="200px" height="200px"/>
    <figcaption>CodeExplore Website Logo</figcaption>
</figure>

<p>Lorem ipsum dolor sit amet <mark>consectetur</mark> adipisicing elit.</p>

<p>Event Date: <time datetime="2025-02-02T20:00:00">Feb2,2025-10:00</time></p>
```

## Section Tag
The `<section>` tag defines a section in a document.

```html
<section>
     <h2>CodeExplore website</h2>
     <p>Learn, enjoy and stay up to date with the CodeExplore.</p>
</section>
```

## Article Tag

The `<article>` tag specifies independent, self-contained content.

```html
<h1>CodeExplore</h1>

<article>
     <h2>CodeExplore website</h2>
     <p>Learn, enjoy and stay up to date with the CodeExplore.</p>
</article>
```

## Canvas Tag
The HTML `<canvas>` element is used to draw graphics, on the fly, via JavaScript.

```html
<canvas id="myCanvas" width="200" height="100" style="border:1px solid #000000;">
    Your browser does not support the HTML canvas tag.
</canvas>
<script>
        var canvas = document.getElementById("myCanvas");
        var ctx = canvas.getContext("2d");

        // Draw a red rectangle
        ctx.fillStyle = "#FF0000";
        ctx.fillRect(20, 20, 150, 75);
</script>
```
The `<canvas>` element is only a contai‍‍ner for graphics. You must use JavaScript to actually draw the graphics.

## Functional tags
Learn tags such as ‍‍`progress`, `base`, `acronym`, `dialog`, and `datalist` in this section
```html
<label for="file">Upload progress file:</label>
<progress id="file" value="32" max="100">32%</progress>
```
```html
<!DOCTYPE html>
<html lang="en" dir="ltr">
    <head>
        <base href="https://codeexplore.ir/">
    </head>
    <body>
        <img src="mobile-logo.png" alt="CodeExplore Logo">
        <a href="about-us">About us</a>      
    </body>
</html>
```
```html
<p>
     <acronym title="World Health Organization">WHO</acronym> 
     It is an international organization that works to improve global health.
</p>
```
```html
<p title="Free Web tutorials">CodeExplore</p>
```
```html
<dialog open>This is an open dialog window</dialog>
```
```html
<form action="#" method="get">
    <label for="browser">Choose your browser from the list:</label>
    <input list="browsers" name="browser" id="browser">
    <datalist id="browsers">
      <option value="Edge">
      <option value="Firefox">
      <option value="Chrome">
      <option value="Opera">
      <option value="Safari">
    </datalist>
    <input type="submit">
</form>
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
    <link rel="icon" type="image/x-icon" href="./mobile-logo.png">
</head>
```

> description: _Define a description of your web page_
>  keywords: _Define keywords for search engines_  
> author: _Define the author of a page_
> viewport: _Setting the viewport to make your website look good on all devices_

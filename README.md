# HTML 

Hyper Text Markup Language

**Code Editor**
[Visual Studio Code](https://code.visualstudio.com/)

**Tag**

```html
<tagname> Content goes here... </tagname>
    
<html> HTML document content </html>
```
  **Introduction to the HTML document**
  
All HTML documents must start with a `<!DOCTYPE>` declaration.

    <!doctype html>

## HTML Document structure

Simple HTML document

    <!doctype html>
	<html>
	    <head>
	    </head>
	    
		<body>
	    </body>
	</html>

head: _Search engine information structure_ body: _User information structure_

## HTML document title

The `<title>` tag defines the title of the document. The title must be text-only, and it is shown in the browser's title bar or in the page's tab.

    <!doctype html>
		<html>
		    <head>
				<title> webdenj website </title>
		    </head>
	    <body>
	    </body>
	</html>

## HTML content

The `<body>` tag defines the document's body. There can only be one `<body>` element in an HTML document.

    <!doctype html>
	<html>
	    <head>
			<title> webdenj website </title>
	    </head>
	    <body>
			This is my website
	    </body>
	</html>

## Heading Tags

The `<h1>` to `<h6>` tags are used to define HTML headings.

    <h1>heading1</h1>
	<h2>heading2</h2>
	<h3>heading3</h3>
	<h4>heading4</h4>
	<h5>heading5</h5>
	<h6>heading6</h6>

## Paragraph Tag

    <p>This is first paragraph</p>
	<p>This is second paragraph</p>
	<p>This is third paragraph</p>

## Break line Tag
The `<br>` tag inserts a single line break.

    My name is Amir <br> I am Programmer

## Horizontal Tag
The `<hr>` tag defines a thematic break in an HTML page

    My name is Amir<hr> I am Programmer

## Comment in HTML
You can add comments to your HTML source by using the following syntax:

    <!-- This is a comment -->  
	<p>This is a paragraph.</p>  
	<!-- Remember to add more information here -->
	
## Image Tag
The `<img>` tag is used to embed an image in an HTML page.

    <img src="webdenj.png" alt="webdenj.png" width="200" height="50" />
    
## List Tag

**Order lists** An ordered list starts with the `<ol>` tag. Each list item starts with the `<li>` tag.

    <ol>
        <li>Home</li>
        <li>About Us</li>
        <li>News</li>
        <li>Contact Us</li>
    </ol>
**Unorder list** An unordered list starts with the `<ul>` tag. Each list item starts with the `<li>` tag.

    <ul>
        <li>Home</li>
        <li>About Us</li>
        <li>News</li>
        <li>Contact Us</li>
    </ul>
    
## Link tag

The `<a>` tag defines a hyperlink, which is used to link from one page to another.

    <a href="http://google.com"> Go to Google</a>
A linked page is normally displayed in the current browser window, unless you specify another target.

    <a href="http://google.com" target="_blank"> Go to Google</a>
    
## Table Tag

The `<table>` tag defines an HTML table. An HTML table consists of one `<table>` element and one or more `<tr>`  `<th>` and `<td>` elements.

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
	
## Video Tag

The HTML `<video>` element is used to show a video on a web page.

    <video width="320"  height="240"  controls>  
		<source src="movie.mp4"  type="video/mp4">  
		<source src="movie.ogg"  type="video/ogg">  
	Your browser does not support the video tag.  
	</video>
To start a video automatically, use the `autoplay` attribute:

    <video width="320"  height="240"  autoplay>  
		<source src="movie.mp4"  type="video/mp4">  
		<source src="movie.ogg"  type="video/ogg">  
	Your browser does not support the video tag.  
	</video>
	
## Audio Tag

The HTML  `<audio>`  element is used to play an audio file on a web page.

    <audio controls>  
		<source src="horse.ogg"  type="audio/ogg">  
		<source src="horse.mp3"  type="audio/mpeg">  
	Your browser does not support the audio element.  
	</audio>
To start an audio file automatically, use the `autoplay` attribute:

    <audio controls autoplay>  
		<source src="horse.ogg"  type="audio/ogg">  
		<source src="horse.mp3"  type="audio/mpeg">  
	Your browser does not support the audio element.  
	</audio>
	
## Forms
An HTML form is used to collect user input. The user input is most often sent to a server for processing.

    <form action="http://gitmag.ir" method="GET">
        ...
    </form>

**Input tag** One of the most used form element is the `<input>` element. The `<input>` element can be displayed in several ways, depending on the `type` attribute.

    <label for="fname">First name:</label>  
	<input type="text" id="fname" name="fname">
	
**Textarea tag** The `<textarea>` element defines a multi-line input field (a text area):

    <textarea name="message" rows="10" cols="30">  
    The cat was playing in the garden.  
	</textarea>
	
**Select tag** The `<select>` element defines a drop-down list:

    <select name="cars">  
        <option value="volvo">Volvo</option>  
        <option value="benz">Benz</option>  
        <option value="fiat">Fiat</option>  
        <option value="audi">Audi</option>  
    </select>
    
## id Attribute

The HTML `id` attribute is used to specify a unique id for an HTML element.

    <html>
    <head>
    <style>
    #html{
      background-color: #F15C2A;
      color: white;
      margin: 20px;
      padding: 20px;
    }
    
    #css{
      background-color: #019ED9;
      color: white;
      margin: 20px;
      padding: 20px;
    }
    </style>
    </head>
    <body>
    
    <div id="html">
    <h2>HTML</h2>
    <p>Hyper Text Markup Language</p>
    </div> 
    
    <div id="css">
    <h2>CSS</h2>
    <p>Stylesheet Language</p>
    </div>
    
    </body>
    </html>

## class Attribute

The HTML `class` attribute is used to specify a class for an HTML element.

    <html>
    <head>
    <style>
    .Front{
      background-color: #EFEFEF;
	  color: black;
	  margin: 20px;
	  padding: 20px;
    }
    </style>
    </head>
    <body>
    
    <div class="Front">
    <h2>HTML</h2>
    <p>Hyper Text Markup Language</p>
    </div> 
    
    <div class="Front">
    <h2>CSS</h2>
    <p>Stylesheet Language</p>
    </div>
    
    </body>
    </html>

## iFream Tag

The HTML `<iframe>` tag specifies an inline frame.

    <iframe src="url"  frameborder="0"></iframe>
    
The height and width are specified in pixels by default:

    <iframe src="https://webdenj.com"  height="200"  width="300"  frameborder="0"></iframe>

## div  Tag
The `<div>` tag defines a division or a section in an HTML document.

    <div>
	    <h2>webdenj.com</h2>
	    <p>This is a paragraph</p>
    </div> 
    
A `<div>` section in a document styled with CSS:

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



## Span Tag

The `<span>` tag is an inline container used to mark up a part of a text, or a part of a document.

    <p>Lorem ipsum dolor sit amet,<span style="color:red">consectetur</span> adipiscing elit.</p>
    
## Semantic Tag


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
    
A semantic element clearly describes its meaning to both the browser and the developer.

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

## Section Tag
The `<section>` tag defines a section in a document.

    <section>
		<h2>webdenj website</h2>
		<p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
	</section>

## Article Tag

The `<article>` tag specifies independent, self-contained content.

    <h1>webdenj</h1>

	<article>
		<h2>webdenj website</h2>
		<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
	</article>

## Meta tags

The `<meta>` tag defines metadata about an HTML document. Metadata is data (information) about data.

    <head>  
        <meta charset="UTF-8">  
        <meta name="description" content="Free Web tutorials">  
        <meta name="keywords" content="HTML, CSS, JavaScript">  
        <meta name="author" content="John Doe">  
    </head>

> keywords: _Define keywords for search engines_ description: _Define a description of your web page_ author: _Define the author of a page_

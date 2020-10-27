# HTML, CSS
## 1. HTML
### Tag (There are two types of tag)
+ Metadata elements, including:  
  1. \<html>, contains all the other element and specify the HTML standard.
  2. \<head>, contains information about the pages: title, script, CSS.  
  3. \<title> specify the title of the webpage, must be nested in the \<head> tag  
+ Sectioning elements, including:  
  1. \<body> contains all the items(all the section elemets) seen on the page.  
  2. \<h1>, ..., \<h6> , diiferent levels of header
  3. \<div>, define section of the webpage, useful for CSS.

### Sematic or style HTML Tags (formating text)
-  \<b>, \<em> (bold and italic)


### Adding Media (image, video and audio) and Links
- Diiferent media has different tags  
  1. img tag: \<img src = "website" />. No ending tag, source required, width optional.
  2. anchor tag< \<a href = ""> link text \</a>

### IMG and photo storage
+ Usage Rights for Images/Photos
  1. Some images are copyrighted. OK for no commercial, personal usage
  2. Some are public domain
  3. Storage and hosting concern (Show the pic could be expensive, server or storage cost).
  4. Inline or Hot linking.(link pic from another web page ). For personal web page, copyrights usually OK. Using anonymous.

### List and tables
+ HTML text content
  1. More than \<p>
  2. List and tables
    1. unordered list: \<ul> (CSS change the shape bullet ).
      + There must be \<li> elements inside \<ul>
      + Anything could be put in between \<li> tag.
    2. ordered list
      + \<ol> require \<li> elements.
      + automatic numbering
+ We can compose HTML elements, for example: nested list. Put \<ul> in \<li> tag and the shape of bullet will be changed.  
+ HTML Table
  1. HTML table elements.
    + table tag: \<table>
    + row tag:  \<tr>
    + header tag: \<th>
    + table data tag: \<td>. Image, list or a variety of other things could be put into the \<td> tag.

###  HTML5 \<Canavas> 
+ Used to draw graphics

## 2. Styling a web page with CSS

### How CSS Is Used to Design Web Pages
 + Viewing and Experiencing Web Page.  
  Web Page may be display differently
  . View on different device

+ Web page Accessibility.  
  Work to ensure web page accessible

+ From HTML Toward CSS.
 + html
    1. Specify document content
    2. Specify some formating:
    Header, List, Table.
    3. Display image
 + CSS, Cascade style system
    1. specifies look and formating
    2. Seperates content from presentation


+ CSS Basics  
 Seperating content from presentation, Maintainablity, Reusability

 1. Why CSS?
 2. CSS can change the style of elements  
 eg: \<h1> blue and centered.  
 JS code ends with ; like C. eg: h1 { color: blue;}.
 3. Do not try to remember CSS, instead look them up.
 4. How to select some elements?
 (3 ways)
    +  Class: named styles
      1. HTML,   
      \<li class = "foodli">
      2. CSS,  
      .foodli  { any code you want }
    + ID: name one elements
      1. HTML,
       \<img src = "" id = "food" />
      2. CSS,  
       #food { any code you want }
   + CSS: Combinator (Select by relationship)
     Style \<li> inside of \<ul>  
  5. Class and ID: Name and reuse.
    * reuse as needed.
    + Many elements in one page
    + Across page
    + Name and reusing  recurring concept in CS.

+ Color and names in CSS.  
   Could be spicified using both number (RGB 255\*255*255) and name ( support 140 color names).


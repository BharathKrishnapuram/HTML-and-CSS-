  HTML Basic Structure

The basic structure of any HTML document is as follows:
<!DOCTYPE html>
<html>
  <head></head>
  <body>
    Your code goes here
  </body>
</html>
HTML Elements
1. Heading Element
The HTML "h1" element defines a main heading.
<h1>Tourism</h1>
2. Paragraph Element
The HTML "p" element defines a paragraph.
<p>Plan your trip wherever you want to go</p>
3. Button Element
The HTML "button" element defines a button.
<button>Get Started</button>
4. Container Element
The HTML "div" element defines a container.
<div>
  <h1>Tourism</h1>
  <p>Plan your trip wherever you want to go</p>
  <button>Get Started</button>
</div>
5. Image Element
The HTML "img" element defines an Image.
Syntax:
<img src="IMAGE_URL"/>
5.1. The "src" Attribute
The HTML Attribute "src" specifies the path (URL) of the Image.
<img  src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tajmahal-img.png"
/>
6. Anchor Element
The HTML "a" element defines a Hyperlink.
We use Hyperlinks to navigate to other web resources or a specific element within the HTML document. They are also called links.
Syntax:
<a href="URL">Content</a>
6.1. HTML "href" Attribute
The HTML "href" Attribute specifies the URL/ path of the page where the link goes to.
<a href="https://www.ccbp.in/">Explore CCBP 4.0 Certification Programs</a>
6.2. Different ways to use the "Anchor" Element
6.2.1. Navigate within the same HTML document
• The HTML anchor "a" element can also be used to navigate to different sections within the same HTML document.
• Add an HTML "id" attribute to the section that you want to navigate to. Provide the hash symbol "#", and the value of the "id" attribute of that section as a value to the link's HTML "href" attribute.
Note:
While navigating to a particular section within the same HTML document, the content of that section doesn't start from the starting of a page when

1. It has less content to fill the Viewport height and there are no sections after it.

2. The content of that section and the content of the sections after it has less content to fill the Viewport height.
6.2.2. HTML Image Element as Link
    <a href="https://www.ccbp.in/">
        <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/learn-technologies-img.png" />
    </a>
7. Void Elements
The HTML elements that only have a start tag and do not contain content or end tag are called as Void Elements.
Syntax:
<tag />
For example, the HTML "img" element.
<img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tajmahal-img.png"/>
8. Line Break Element
The HTML "br" element helps to break the text and continue it in the next line.
<p>
  Twinkle, twinkle, little star, <br />
  How I wonder what you are!
</p>
9. Horizontal Rule Element
The HTML "hr" element inserts a horizontal line and helps to separate the content.
<h1 class="heading">
  Twinkle Twinkle Little Star
</h1>
<hr />
<p>
  Twinkle, twinkle, little star.
</p>
<hr />
10. HTML Lists
The List is a way to group related pieces of information so that they are easy to read and understand.
For example, Shopping list, Todo list, etc.
There are mainly two types of Lists available in HTML.
• Unordered List • Ordered List
11. Unordered List
It is a collection of related items that have no special order or sequence.
For example, List of Hobbies
• Painting • Reading Books • Playing the Guitar
The Unordered List starts with "<ul>" tag. It wraps around all the list items and each list item starts with the "<li>" tag.
<ul>
  <li>Painting</li>
  <li>Reading Books</li>
</ul>
By default, list items in the Unordered List are marked with bullets.
11.1. Styling Unordered List
The CSS "list-style-type" property is used to style the List.
.unordered-square-list {
  list-style-type: square;
}
You can use one of the below values of the CSS "list-style-type" property to style the Unordered List.
Values: square, circle, disc, none
12. Ordered List
It is a collection of related items that follow some order or have a sequence.
For example, Web Technologies
1.	HTML
2.	CSS
3.	JavaScript
The Ordered List starts with "<ol>" tag. It wraps around all the list items and each list item starts with the "<li>" tag.
<ol>
  <li>Go through the HTML elements and CSS properties</li>
  <li>Complete the Todolist Coding Practice</li>
  <li>Go through the Bootstrap Concepts</li>
</ol>
By default, list items in the Ordered List are marked with numbers.
12.1. Styling Ordered List
The CSS "list-style-type" property is used to style the List.
.ordered-lower-roman-list {
  list-style-type: lower-roman;
}
You can use one of the below values of the CSS "list-style-type" property to style the Ordered List.
Values: upper-alpha, lower-alpha, upper-roman, lower-roman, decimal, none

HTML Attributes
1. HTML "id" Attribute
The HTML "id" attribute specifies a unique id for an HTML element. The value of the "id" attribute must be unique within the HTML document.
<div id="section1">Section 1</div>
Warning:
1. The CCBP UI kit works only if the value of the HTML `id` attribute of the container section has the prefix as `section`.
2. So, the id which we specify for any section should always contain its prefix as `section` if you are using CCBP UI Kit.
2. HTML "onclick" Attribute
The "onclick" event occurs when the user clicks on an HTML Element.
<button class="btn btn-primary" onclick="display('section3')">
  Go to Section 3
</button>
The value of an HTML "onclick" attribute should be enclosed in double-quotes and the value inside the brackets of "display()" should be enclosed in single quotes.
3. The "src" Attribute
The HTML Attribute "src" specifies the path (URL) of the Image.
<img
  src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tajmahal-img.png"
/>
4. HTML "href" Attribute
The HTML "href" Attribute specifies the URL/ path of the page where the link goes to.
<a href="https://www.ccbp.in/">Explore CCBP 4.0 Certification Programs</a>
5. HTML "target" Attribute
The HTML "target" Attribute specifies where to open the linked web resource.
<a href="https://www.ccbp.in/" target="_blank">Explore CCBP 4.0 Certification Programs</a>
CSS Syntax
selector {
  property1: value1;
  property2: value2;
}

CSS Text Properties
1. Text Align
The CSS "text-align" property specifies the horizontal alignment of the text in an HTML element.
.h-center {
  text-align: center;
}
Value	Description
center	Aligns the text to the center
left	Aligns the text to the left
right	Aligns the text to the right
2. Color
The CSS "color" property specifies the color of the text.
.main-heading {
  color: blue;
}
.paragraph {
  color: grey;
}
2.1. Sample Colors
Values: blue, grey, lightblue, orange, red, green
2.2. Hex Code
CSS Colors can be represented in multiple ways:
• Color names • Hex Code • HSL • RGB and many more...
Since few colors have the Color names, Hex Codes make a good alternative to pick a wide variety of colors.
Some of the Color names and their Hex Codes are:
Color Name	Hex Code
orange	#ffa500
red	#ff0000
blue	#0000ff
green	#008000
-	#012d36
-	#432711
-	#25b1cc
.button {
  background-color: #25b1cc;
}
2.2.1 How to pick a color using Hex Code
The color picker lets you pick a color among the approximately 16,777,216 colors available.
One of the simplest ways to access a color picker is:
• Type color picker in the Google Search bar and search it.
 
3. Font Family
The CSS "font-family" property specifies the font for an element.
@import url("https://fonts.googleapis.com/css2?family=Bree+Serif&family=Caveat:wght@400;700&family=Lobster&family=Monoton&family=Open+Sans:ital,wght@0,400;0,700;1,400;1,700&family=Playfair+Display+SC:ital,wght@0,400;0,700;1,700&family=Playfair+Display:ital,wght@0,400;0,700;1,700&family=Roboto:ital,wght@0,400;0,700;1,400;1,700&family=Source+Sans+Pro:ital,wght@0,400;0,700;1,700&family=Work+Sans:ital,wght@0,400;0,700;1,700&display=swap");
.main-heading {
  font-family: "Roboto";
}
.paragraph {
  font-family: "Roboto";
}
You can use one of the below values of the "font-family" property,
Value
 
Note:
1. To use font families, you need to import their style sheets into your CSS file.
2. There shouldn't be any spelling mistakes in the values of the `font-family` property.
3. There must be quotations around the value of the `font-family` property.
4. Font Size
The CSS "font-size" property specifies the size of the font.
.main-heading {
  font-size: 36px;
}
.paragraph {
  font-size: 28px;
}
Note:
1. You must add `px` after the number in the value of the `font-size` property.
2. There shouldn't be any space between the number and `px`.
3. There shouldn't be any quotations around the value of the `font-size` property.
5. Font Style
The CSS "font-style" property specifies the font style for a text.
You can use one of the below values of the "font-style" property,
Value: normal,italic,oblique
.main-heading {
  font-style: italic;
}
.paragraph {
  font-style: normal;
}
Note:
1. There shouldn't be any spelling mistakes in the values of the `font-style` property.
2. There shouldn't be any quotations around the value of the `font-style` property.
6. Font Weight
The CSS "font-weight" property specifies how thick or thin characters in text should be displayed.
.main-heading {
  font-weight: bold;
}
.paragraph {
  font-weight: 200;
}
You can use one of the below values of the "font-weight" property,
Values: normal, bold, bolder, lighter, 100, 200, 300, 400, 500, 600, 700, 800, 900
Note:
1. There shouldn't be any spelling mistakes in the values of the `font-weight` property.
2. There shouldn't be any quotations around the value of the `font-weight` property.
3. The numerical values given to the `font-weight` property must be in the range from `100` to `900` and should be the multiples of `100`.
7. Text Decoration
The CSS "text-decoration" property specifies the decoration added to the text.
.main-heading {
  text-decoration: underline;
}
.paragraph {
  text-decoration: overline;
}
You can use one of the below values of the "text-decoration" property,
Value	Description
underline	Underline the text
line-through	Strike through the text
overline	Overline the text
Note:
1. There shouldn't be any spelling mistakes in the values of the `text-decoration` property.
2. There shouldn't be any quotations around the value of the `text-decoration` property.
3. Ensure that `text-decoration` and `line-through` are hyphenated.

CSS Background Properties
1. Background Color
The CSS "background-color" property specifies the background color of an HTML element.
.card {
  background-color: lightblue;
}
2. Background Image
The CSS "background-image" property specifies the background image of an HTML element.
.card {
  background-image: url("https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/ocean.jpg");
}
Value	Description
url (URL)	The URL to the image.
Warning:
1. The background image takes the height of the content of an HTML element if you don't specify the height to it.
2. The URL given to the `background-image` must be a valid URL to display the image.
3. Background Size
The CSS "background-size" property specifies the size of the background image of an HTML element.
.card {
  background-size: cover;
}
Value	Description
cover	Scales the image to the smallest size while maintaining the same aspect ratio (width/height) and covers the entire width and height even if the image is cropped.
Note:
Aspect Ratio is the ratio of the width and height (width/height) of an image.

CSS Box Properties
1. Height
The CSS "height" property specifies the height of an HTML element.
.card {
  height: 200px;
}
2. Width
The CSS "width" property specifies the width of an HTML element.
.card {
  width: 250px;
}
3. Border Width
The CSS "border-width" property specifies the width of the border for all four sides of an HTML element.
.button {
  border-width: 2px;
}
The CSS Property and value pair "border-width: 0px;" removes the border of an HTML element.
Warning:
Specifying the CSS `border-style` property for an HTML element is mandatory. Otherwise, the CSS properties like `border-color`, `border-width` will not appear in the browser. The HTML `button` element is an exception as it appears with a border in the browser by default.
4. Border Radius
The CSS "border-radius" property specifies the roundness of the corners of an HTML element.
.button {
  border-radius: 20px;
}
You can use the below CSS properties to round a specific corner of an HTML element.
Properties: border-top-left-radius, border-top-right-radius, border-bottom-left-radius, border-bottom-right-radius
Quick Tip:
Specifying the background color for an HTML element makes the border radius more visible.
5. Border Color
The CSS "border-color" property specifies the color of the border for all four sides of an HTML element.
.button {
  border-color: orange;
}
Warning:
Specifying the CSS `border-style` property for an HTML element is mandatory. Otherwise, the CSS properties like `border-color`, `border-width` will not appear in the browser. The HTML `button` element is an exception as it appears with a border in the browser by default.
6. Border Style
The CSS "border-style" property specifies the style of the border for all four sides of an HTML element.
.button {
  border-style: dashed;
}
You can use one of the below values of the CSS "border-style" property.
Value: dotted, dashed, solid, none (default)
7. Padding
The CSS "padding" property specifies the space around the content of an HTML element.
.card {
  padding: 10px;
}
8. Margin
The CSS "margin" property specifies the space around the four sides of an HTML element.
.card-container {
  margin: 10px;
}
You can use the below CSS properties to apply a margin on the specific side of an HTML element,
Properties: margin-top, margin-right, margin-bottom, margin-left


Viewport
The browser's viewport is the area of the window in which web content can be seen.
1. Viewport Height
The CSS Viewport Height "vh" Unit equals to 1% of the height of the Viewport (browser window size).
.card {
  height: 50vh;
}
Note:
The height `100vh` sets an HTML element to the entire height of the Viewport (browser window size).
2. Viewport Width
The CSS Viewport Width "vw" Unit equals to 1% of the width of the Viewport (browser window size).
.card {
  width: 100vw;
}
Note:
The width `100vw` sets an HTML element to the entire width of the Viewport (browser window size).

Reusability
1. Reusability of CSS Rulesets
If we want the same style for multiple HTML elements, we can write the CSS Ruleset once and use it for different HTML elements.
.button {
  width: 138px;
  height: 36px;
  border-width: 0px;
  border-radius: 10px;
}
<button class="button">Get Started</button>
<button class="button">Visit Now</button>
2. Multiple class names as an HTML attribute value
We can provide multiple class names separated by space as a value to the HTML class attribute.
Syntax:
<tag class = "name1 name2 name3 name4 ...">Content</tag>
HTML attribute value: name1 name2 name3 name4 ...
class names: name1, name2, name3, and name4
.button {
  width: 138px;
  height: 36px;
  border-width: 0px;
  border-radius: 10px;
}
.button-green {
  background-color: #8cc63f;
}
<button class="button button-green">Get Started</button>
Bootstrap
Bootstrap is a large collection of predefined reusable Code Snippets written in HTML, CSS, and Javascript. The Code Snippets include Buttons, Cards, Carousels, etc.
How to use Bootstrap?
To use the Code Snippets provided by Bootstrap, we need to add the below piece of code within the HTML head element. We call it BootstrapCDN.
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous"/>
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>

Flexbox Properties
1. Flexbox Container
The Bootstrap class name d-flex defines a Flexbox Container. The direct HTML elements in the Flexbox Container are called flex items.
<div class="d-flex">
  <div>
    <h1>Tourism</h1>
    <p>Plan your trip.</p>
    <button>Get Started</button>
  </div>
</div>
•	The HTML container element with the class="d-flex" is a Flexbox Container.
•	The HTML container element div in Flexbox Container is a flex item. Because it is directly inside the Flexbox Container.
•	The HTML main heading, paragraph, and button elements are not flex items. Because these elements are not directly inside the Flexbox Container.
Note:
Wrapping HTML elements in the Flexbox Container is mandatory to apply other flex properties.</MultiLineNote>
2. Flex Direction
The Flex Direction specifies the direction of the flex items in the Flexbox Container.
Class Name	Direction of the flex items in a Flexbox Container
flex-row	Horizontal
flex-column	Vertical
2.1. flex-row
The Bootstrap class name "flex-row" is used to move the flex items horizontally in the Flexbox Container.
<div class="d-flex flex-row">
  <div>
    <h1>Tourism</h1>
    <p>Plan your trip.</p>
    <button>Get Started</button>
  </div>
</div>
2.2. flex-column
The Bootstrap class name "flex-column" is used to move the flex items vertically in the Flexbox Container.
<div class="d-flex flex-column">
  <div>
    <h1>Tourism</h1>
    <p>Plan your trip.</p>
    <button>Get Started</button>
  </div>
</div>
Note:
The Bootstrap class name `flex-row` is the default Flex Direction for the Flexbox Container. So, once `d-flex` is specified, all the flex items in the Flexbox Container display horizontally.
3. Justify Content
The Justify Content specifies the alignment of flex items along the Flex Direction in a Flexbox Container.
3.1. justify-content-start
The Bootstrap class name "justify-content-start" is used to align the flex items at the start of the Flexbox Container either horizontally or vertically based on the Flex Direction.
Flex Direction	Alignment of flex items in a Flexbox Container
flex-row	Align flex items horizontally to the left
flex-column	Align flex items vertically to the top
<div class="d-flex flex-column justify-content-start">
  <div>
    <h1>Tourism</h1>
    <p>Plan your trip.</p>
    <button>Get Started</button>
  </div>
</div>
3.2. justify-content-center
The Bootstrap class name "justify-content-center** is used to align the flex items at the center of the Flexbox Container either horizontally or vertically based on the Flex Direction.
Flex Direction	Alignment of flex items in a Flexbox Container
flex-row	Align flex items horizontally to the center
flex-column	Align flex items vertically to the center
<div class="d-flex flex-column justify-content-center">
  <div>
    <h1>Tourism</h1>
    <p>Plan your trip.</p>
    <button>Get Started</button>
  </div>
</div>
3.3. justify-content-end
The Bootstrap class name "justify-content-end" is used to align the flex items at the end of the Flexbox Container either horizontally or vertically based on the Flex Direction.
Flex Direction	Alignment of flex items in a Flexbox Container
flex-row	Align flex items horizontally to the right
flex-column	Align flex items vertically to the bottom
<div class="d-flex flex-column justify-content-end">
  <div>
    <h1>Tourism</h1>
    <p>Plan your trip.</p>
    <button>Get Started</button>
  </div>
</div>
3.4. justify-content-between
The Bootstrap class name "justify-content-between" is used to get equal space between the HTML elements.
<div class="d-flex flex-column justify-content-between">
  <div>
    <h1>Tourism</h1>
    <p>Plan your trip.</p>
    <button>Get Started</button>
  </div>
</div>
Predefined Styles in Bootstrap
1. Button
The Bootstrap class "btn" is used to style the HTML "button" element.
<button class="btn">Submit</button>
To apply different background colors to the HTML "button" element, you can use the below bootstrap classes.
class names: btn-primary, btn-secondary, btn-success, btn-danger, btn-info, btn-dark, btn-warning, btn-light
Bootstrap provides us different types of buttons. One of them is Outline buttons, that don't have a background color.
To add the outline buttons in our HTML document, just replace "btn" in the above classes with the "btn-outline".
for example,
button Class name	outline button class name
btn-primary	btn-outline-primary
btn-secondary	btn-outline-secondary
btn-success	btn-outline-success
btn-danger	btn-outline-danger
<button class="btn btn-primary">Get Started</button>
<button class="btn btn-outline-primary">Get Started</button>
Note:
By default, Bootstrap class name `btn` has no background color.
2. Text colors
To apply different colors to the text, you can use the below bootstrap classes.
class names: text-primary, text-warning, text-secondary, text-success, text-danger, text-dark, text-white
<h1 class="text-primary">Tourism</h1>
3. Text transform
To apply different cases like upper case, lower case etc to the text, you can use the below bootstrap classes.
class names: text-lowercase, text-uppercase, text-capitalize
<p class="text-lowercase">PLAN your TRIP wherever YoU wAnT to GO.</p>
4. Background colors
To apply different background colors to an HTML element, you can use the below bootstrap classes.
class names: bg-primary, bg-warning, bg-secondary, bg-success, bg-danger, bg-info, bg-dark, bg-white
<div class="bg-warning"><h1>Tourism</h1></div>
Bootstrap provides us with many predefined class names. Some of them are:
class names: card, carousel, alert, alert-success, alert-link, bg-danger, card-body and many more...
You can find the list of class names provided by the bootstrap here
Warning:
Using predefined bootstrap class names as a selector in our CSS Ruleset may give unexpected results.



Bootstrap Components
Carousel
The Carousel is a slideshow for cycling through images, text, etc. Slides will change every few seconds.
To add the Carousel to our Favourite Place Detailed View Section Page, we used Bootstrap Carousel Component with the Indicators.
You can add the different images in the Carousel by changing the image URL in the value of the HTML src attribute.
<img
  class="d-block w-100"
  src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tajmahal-c1-img.png"
  alt="...">
/>
You can find the Bootstrap Carousel code here
Note:
1. To use multiple Carousels in the same HTML document, we have to provide a unique id to each Carousel.

2. So while adding a new Carousel, you need to change the id of the Carousel. Else, the Carousel controls don’t work.

Bootstrap Utilities
Embed
The given code snippet is the Youtube embed code provided by Bootstrap. You can add the different Youtube Videos by changing the Video ID in the value of the HTML "src" attribute.
The Video ID is in between the "https://www.youtube.com/embed/" and "?rel=0".
<div class="embed-responsive embed-responsive-16by9">
  <iframe
    class="embed-responsive-item"
    src="https://www.youtube.com/embed/49HTIoCccDY?rel=0"
    allowfullscreen
  ></iframe>
</div>
Note:
1. Be careful while pasting the video ID. The video ID must be in between the `https://www.youtube.com/embed/` and `?rel=0`. You won't get the video if any character is missed in the value of the HTML `src` attribute.

2. To embed the Youtube Videos in a smaller size, replace the class name embed-responsive-16by9 with embed-responsive-1by1 in the Bootstrap Video Embed Code. You can find the reference [here](https://getbootstrap.com/docs/4.5/utilities/embed/#aspect-ratios)

CCBP UI Kit
It is a collection of reusable code snippets similar to Bootstrap. It is specially designed for CCBP training.
1. Adding CCBP UI Kit to the Web Page
<!DOCTYPE html>
<html>
  <head>
    ...
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    ...
  </head>
  <body>
    <script type="text/javascript" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/js/ccbp-ui-kit.js"></script>
  </body>
</html>
The CCBP UI Kit Script Code should be placed just before the HTML "body" end tag.
2. Display Utility
It is a reusable code snippet to display or hide Section Containers based on user actions.
You can find the Display Utility code here
More Details
1. Getting URLs for Your Images
You can get the URLs to your images using Cloudinary. Cloudinary lets you easily upload the images and provide the image URLs.
Cloudinary Website URL: https://cloudinary.com/
Note:
To Sign up, copy the Cloudinary Website URL and open in new tab.
2. Install Visual Studio Code
•	Windows Operating System
•	Ubuntu/Linux Operating System (Watch only for 2 minutes)
•	Mac Operating System (Watch only for 2 minutes 30 seconds)
3. Linking HTML and CSS Files
We use the HTML link element to link the HTML and CSS files. It is a void element.
Syntax:
<link rel="stylesheet" href="tourism.css">
Note
You need to add the HTML `link` element in the HTML `head` element.
4. HTML Image vs CSS Background Image
Ways to add Images in Website:
•	HTML Image
•	CSS Background Image
When to use HTML Image:
•	When there are no content or HTML elements over the Image.
•	When Image is a part of the content on a page.
When to use CSS Background Image:
•	When Image is not a part of the content on a page.
•	When there are content or HTML elements over the Image.
5. CSS Margin vs CSS Padding
 

When to use CSS Padding:
•	To specify the space around the four sides of the content of an HTML element.
•	To add the space between the content and border of an HTML element.
When to use CSS Margin:
•	To specify the space around the four sides of an HTML element.
•	To add the space between HTML elements.
For example, let's take an HTML button element.
<button class="button">View More</button>
.button {
  padding: 20px;
  margin: 15px;
}



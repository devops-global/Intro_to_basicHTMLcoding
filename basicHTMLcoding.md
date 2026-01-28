What is HTML?
•	HTML stands for Hyper Text Markup Language
•	HTML is the standard markup language for creating Web pages
•	HTML describes the structure of a Web page
•	HTML consists of a series of elements
•	HTML elements tell the browser how to display the content
•	HTML elements label pieces of content


HTML Sessions Material

HTML Documents
HTML documents start with a document type declaration: <!DOCTYPE html>.
The HTML document itself begins with <html> and ends with </html>.
The visible part of the HTML document is between <body> and </body>.
Let us provide you with an example: 
<!DOCTYPE html>
<html>
<body>

<h1>Omololu International School</h1>
<p>I am a proud student at Omololu International School. The world is our classroom.</</p>

</body>
</html>

Useful Explanations:
The <!DOCTYPE> Declaration
The <!DOCTYPE> declaration represents the document type, and it also helps browsers to display web pages correctly.
It must only appear once, at the top of the page (before any HTML tags).
The <!DOCTYPE> declaration is not case sensitive.


HTML Headings
HTML headings are defined with the <h1> to <h6> tags.
<h1> defines the most important heading. <h6> defines the least important heading.

HTML Paragraphs
HTML paragraphs are defined with the <p> tag.

HTML Links
HTML links are defined with the <a> tag:
Let us provide you with an example: 
<a href="https://omololuschool.org">My School</a>
The link's destination is specified in the href attribute. 
Attributes are used to provide additional information about HTML elements.
You will learn more about attributes later in the HTML session.




HTML Images
HTML images are defined with the <img> tag.
The source file (src), alternative text (alt), width, and height are provided as attributes: for example: 
<img src="oisLogo.jpeg" alt="Omololu International School" width="200" height="229">
The src attribute tells the web browser where to look for the image. In the example above, the code assumes that the image file in located in the same folder as the html file. If the image file was located elsewhere you would need to specific the full path of the image file: an example of this would be: 
<img src="https://images.squarespace-cdn.com/content/v1/65316cbd0791df2c11ffcfb6/478b05a3-de8f-4db3-b64c-c2fd93a974b3/Omololu+Full+Logo.jpeg?format=1500w" alt="Omololu International School" width="200" height="229">









HTML Elements
An HTML element is defined by a start tag, some content, and an end tag.
The HTML element is everything from the start tag to the end tag, for example: 
<p>I am a proud student at Omololu International School. The world is our classroom.</p>

Useful explanations: 

1.	<p> is equal to the START TAG
2.	The text which reads: “I am a proud student at Omololu International School. The world is our classroom.” is equal to the ELEMENT CONTENT
3.	</p> is equal to the END TAG.

IMPORTANT TO NOTE: 
Some HTML elements have no content (like the <br> element). These elements are called empty elements. Empty elements do not have an end tag!

Web Browsers
The purpose of a web browser (Chrome, Edge, Firefox, Safari) is to read HTML documents and display them correctly.
A browser does not display the HTML tags, but uses them to determine how to display the document
HTML Page Structure
The image illustration below represents a visualization of an HTML page structure
 
Notes: 
1.	The content inside the <title> element will be shown in the browser's title bar or in the page's tab.
2.	The content inside the <body> section will be displayed in a browser.




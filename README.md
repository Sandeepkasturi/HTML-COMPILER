# HTML-COMPILER
HTML integrated web compiler by using javascript and HTML
This is an example of a simple HTML Live Editor.

The code starts with a <!DOCTYPE html> and <html> tags, which define the document type and the structure of the HTML page respectively.

Then, inside the <body> tag, there's an <h1> heading with the text "HTML Live Editor"

Then, there's a <textarea> element with an id attribute of "html-input" which is used for the user to input HTML code.

Following the <textarea> element, there's a <button> element that contains the text "Update Preview" and has an onclick attribute that calls the updatePreview() function. This button is used to update the live preview of the HTML code.

After that, there's a <div> element with an id attribute of "html-preview" which is used to hold the live preview of the HTML code.

Finally, there's a <script> block, which contains JavaScript code. The script starts by getting references to the textarea and preview div using document.getElementById and assigns them to the htmlInput and htmlPreview constants respectively.

Then, it defines a function updatePreview() that updates the live preview. Inside the function, it sets the innerHTML of the htmlPreview div to the value of the htmlInput textarea. This way, when the user types HTML code in the textarea and clicks the "Update Preview" button, the function will execute and will update the live preview with the HTML code that the user has typed.

It's important to note that this is just a basic example and it doesn't include any security measures, error handling, and other advanced features, and it's also important to sanitize user input to prevent any potential security vulnerabilities like cross-site scripting(XSS) attacks.

FINALLY ,
  This code creates an HTML live editor that allows the user to input HTML code and preview the output in real-time. Here is a step by step explanation of the code:

The first line specifies the document type as HTML.
The <html> tag denotes the start of an HTML document.
The <head> tag contains meta information about the document, such as the title which is "Redeem_Tech-Editor"
Inside the head tag a style tag is used and .container{display: flex;flex-direction: row;} is used to define a class for the parent container. It sets the display to flex and flex-direction to row, this is used to split the display for html-input and html-preview into two equal parts.
#html-input, #html-preview {width: 55%;} is used to define classes for the input and preview elements, it sets the width of both the elements to 55%.
The <body> tag contains the visible content of the document.
Inside the body, <h1>HTML Live Editor</h1> is used to create a heading with text "HTML Live Editor"
<div class="container"> is used to define a container with class 'container' which is defined in the stylesheet
Inside the container, a <textarea> element is created with an id "html-input" and some attributes like size, rows, cols, and font-size.
A <div> element is created with an id "html-preview" and some attributes like font-size which is used to hold the live preview of the HTML code.
<legend> is used to create a caption for the html-preview div, it also contains a button with text "Run" which will run the code and update the preview.
In the script section, const htmlInput = document.getElementById('html-input'); is used to get the reference of the textarea element and store it in a variable htmlInput
const htmlPreview = document.getElementById('html-preview'); is used to get the reference of the preview div and store it in a variable htmlPreview
function updatePreview() is used to define a function that updates the code

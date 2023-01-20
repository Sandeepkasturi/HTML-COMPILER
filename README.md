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


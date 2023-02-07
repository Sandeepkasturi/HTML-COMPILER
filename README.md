# HTML-COMPILER
HTML integrated web compiler by using javascript and HTML
This is an example of a simple HTML Live Editor.

This is a JavaScript code that creates a live preview of HTML and CSS code. The code consists of two textarea elements, one for the user to input HTML code and another for the user to input CSS code.

The align attribute in the body element is used to align the content of the body to the center of the page.

The div element with class container and a border of 5 is used to group the textarea elements and add a border to them.

The cols, rows, size, and spellcheck attributes are used to set the properties of the textarea elements, and the style attribute is used to set the font size.

The "COMPILE" button triggers the updatePreview() function when clicked. The function uses the value property of the textarea elements to retrieve the user's inputted HTML and CSS code.

Before displaying the preview, the function checks if the HTML code is complete (i.e., if it starts with <html> and ends with </body>). If it is not complete, an error message is displayed. If everything is in order, a new window is opened, and the HTML and CSS code is written to it, producing the live preview.




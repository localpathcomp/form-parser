# form-parser
Simple JS class for form processing

Begin by adding a CSS selector class to each form you would like to process. Ensure each form has the correct method and action on it. Import the class as a JS module into your project. Call the constructor function passing the string CSS selector. Next call the init method. The module is now listening for any form submissions in your document. It will parse your input fields and send them to your server, upon success it will clear the form and form data object. On error it will log and error object.

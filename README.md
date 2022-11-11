# OVERVIEW
This is a simple react application that demonstrates a handled form control textarea element.
It also shows how the data can be previewed or cleard just by a single click.
The web application was built with Create-react-app, bootstrap and html.

# COMMANDS
A user is able to input data directly into the textarea.
A user is able to preview data using the "Preview Data" button.
A user is also able to delete data using the "Clear Data" button.

# FUNCTIONALITY
It tracks the number of characters and words a user has entered using the javascript length and split() methods.
Extra spaces before or after words are handled as invalid and removed using the javascript trim() methods.
Some elements are conditionally rendered depending on the total number of characters and words entered by the user and whether they are handled as valid characters or words.
Conditional element rendering are also accompanied by matching color changes.

# TESTING
Before starting to enter data, notice that the placeholder texts are prepopulated in the textarea.
Try entering some data into the text area and observe the rendered elements and the color.
Try entering between 1-100 characters and observe the colour change and rendered elements.
Attempt entering more than 100 characters and observe the color change.
Try entering multiple empty spaces and observe the colour changes and rendered elements.
Try entering only empty spaces and observe the colour changes and rendered elements.
Observe the counters in each case.


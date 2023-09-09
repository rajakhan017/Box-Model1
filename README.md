# Box-Model1
This README provides an overview of the HTML and CSS code provided, explaining its structure, styling, and the purpose of different elements and classes.
## HTML Structure
The HTML structure consists of an HTML5 document with a <head> and a <body> section. It includes links to an external CSS file named "style.css" for styling.
head> Section
• meta> tags define the character set and the initial viewport scale.
• The title of the webpage is set to "Box Model."
body> Section
• A div> with a class of "main" serves as the main container for the content.
• It's positioned relative to its parent and is shifted 25% down and 30% to the left.
• The red border adds a visual boundary.
• display: flex and related properties are used for layout control.
• Inside the "main" container, there is a <div> with a class of "content" that contains various boxes.
• This div uses flex properties to arrange its children in a column layout.
![image](https://github.com/rajakhan017/Box-Model1/assets/135150598/a2aa847b-7a6c-4e70-8aa0-f06d139e22a4)
## CSS Styling
Global Styles
• The universal selector * is used to reset margins and paddings to zero and set the box-sizing to "border-box."
• The body element takes up the full viewport width and height (100vw and 100vh).
### Main Container 
• Positioned relative to its parent with specific dimensions and a red border.
• Utilizes flex properties to center its content both horizontally and vertically.
### Content Container 
• Positioned within the main container, taking up most of its height.
• Utilizes flex properties to arrange its children in a column layout with a 12px gap.
### Box Elements 
• Both boxes have red borders and some padding.
• box1 has a heading element (h1) with the text "I'm a box."
• box2 contains a paragraph (p) with placeholder text.
### List 
• An unordered list (ul>) with red borders and padding.
• Each list item (<li) also has red borders and padding.
• Demonstrates that lists and list items are also affected by the box model.
![image](https://github.com/rajakhan017/Box-Model1/assets/135150598/d5ddf0bc-c025-4900-86c8-ec85f60e3380)
## Additional Elements
• The paragraph at the end of the content contains text with inline elements.
• An input button and an anchor link, both styled with red borders and padding.
### Summary
This HTML and CSS code showcase the concept of the box model in web development.
Different elements and classes are used to demonstrate how the box model properties, such as margins, borders, padding, and dimensions, affect the layout and appearance of elements on a webpage.
The provided code can be a useful reference for understanding and experimenting with the box model in CSS.
## Hosted Link
you cn access this from here: https://rajakhan017.github.io/Box-Model1/


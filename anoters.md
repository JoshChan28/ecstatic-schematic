#Just some notes in markdown instead of html

###CSS notes
<body style = "Takes css code"> </body>
- HTML brackets with css within the brackets
- Use MDN for documentation on css
- background-color: #####; --> Sets background color of an element.
  - If in the body tag, then whole body is changed, if in a table, only table is changed
  - Use colorhunt.co for color codes - If using hex codes, must have # at the front

- Changing style of horizontal rules - We can't change the inside of box, but we can change the border. If we want to create a single line, turn borders of bottom and sides off
#### External CSS - For changing styles for all pages on the website
- Have a folder in same dir for css stuffs
- A file within that folder for css code styles.CSS
- pointers that start with `/` mean starting from the root. Pointers for folders/files in same dir just point to name of folder/file `css/styles.CSS`
- selector {property:value;}
- We can split up tags into classes which we can specify individually.
- We can also use IDs to select aspects instead of tags or cclasses
- ID's and class are more specific than tags - ID can only be used in one place to identify elements that are unique on one page
- classes can be used to group of related items, ID's are for one item only
- Items can have multiple classes class="fistClass secondClass"
- Sudo classes may be used to change the item when in different states (When you hover your mouse over it, it chagnes color)
- Padding - Distance from text to borders
- border - widtch of the border around box
- maring - distance around the border to seperate divs

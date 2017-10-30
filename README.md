# The 3 languages of the web in action

A simple CSS-only 3-tab layout is provided, with a tab for HTML5, CSS and JavaScript.

Use this to add 5 things you know about each language to each section, actually using that language in the process!

## Stage 1

Add 5 different pieces of information about each language using the following elements:

- Add the HTML5 items in a **table**
- Add the CSS items in an **unordered list**
- Add the Javascript items in a **definition list**

## Stage 2

Style each of the three language sections differently using CSS:

- Use alternate colours for the table rows (`tr`) and style the `td` tags in the table head (`th`) tag separately. Use `border-collapse` to close the gaps between the table rows
- Style the unordered list `ul` so that there are no bullet points and no margin or padding
- give the `li` tags some padding of your own choice
- Set a `border-top` property above each `li` tag and a final `border-bottom` to the `last-child`
- Style the definition term (`dt`) and definition description (`dd`) items separately

## Stage 3

Take and store user input from JavaScript, and create new DOM nodes

- Delete the definition list and create a `form` with an `input type="text"` field and an `input type="submit"` button
- review `getElementById` and `eventListener` from the local storage exercise
- use Javascript to **capture items** from user input into the form field, and **add a new paragraph** each time.
- Use `localStorage.setItem("item-name", "value from form field");` to store the data

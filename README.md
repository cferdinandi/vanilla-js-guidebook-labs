# The Vanilla JS Guidebook Labs
Practice the vanilla JavaScript techniques you learned in the guide.

## Selectors

1. Get the first element that has a class of `.bg-red` and a `[data-sandwich]` value of `tuna`.
2. Get the all of the `<divs>` that have a `[data-sandwich]` value of `ham`.
3. Log the results of both to the console.


## Loops

1. Get the all of the `<divs>` that have a `[data-sandwich]` value of `ham`.
2. Loop through each one and log it in the console.


## Classes

1. Get the all of the `<divs>` that have a `[data-sandwich]` value of `ham`.
2. Loop through each one.
3. If it has a class of `.bg-red`, remove it.
3. If it has a class of `.bg-blue`, change it to `.bg-red`.
5. If it has a class of `.bg-navy`, change it to `.bg-green`.


## Styles

1. Get the all of the `<divs>`.
2. Loop through each one.
3. Check the element's height.
4. If it's less than `25px`, set the `background-color` to `darkslategrey`.
5. If it's greater than or equal to `25px`, set the `background-color` to `purple`.


## Attributes

1. Get all `<divs>`.
2. Loop through each one.
3. If it has an attribute of `[data-sandwich]`, give it a class of `.bg-green`.
4. If the `[data-sandwich]` attribute is `ham`, remove all classes.


## Event Listeners

1. Listen for `click` events.
2. If the clicked element has a data attribute of `[data-click-me]`:
    a. Change the `background-color` to the value of `[data-click-me]`.
    b. Update the value of `[data-click-me]` to the previous background color.


## HTML

1. Get the first element with an attribute of `[data-snack]` equal to `chips`.
2. Add to the existing HTML with a short note about chips.


## Forms

1. Get all form elements.
2. If the form is a text input, change the type to `password`.
3. if the form is a checkbox, check it.
4. If it's a radio button, check if it's the selected option. If it is, log the value in the console.
5. If it's a textarea, give it a value.


## Traversing Up the DOM

1. Get the element with an ID of `#d3`.
2. Get all of the elements parents.
3. Add the `.bg-green` class to all of them until you get to the `document.body`.


## Traversing Down the DOM

1. Get the element with an ID of `#wrapper`.
2. Get all of the direct decendants only.
3. Log the decendants in the console


## Traversing Sideways in the DOM

1. Get the list item with an ID of #item-3
2. Get all of that list item's siblings
3. Log the siblings in the console


## Merging Arrays and Objects

1. Add two of your favorite books to the array of books.
2. Add a new key, `balloons`, to the `partyList` object, with a balloon color
3. Merge the `partyListUpdated` object with the `partyList` object, and don't loose any of the keys or values.
4. Log `books` and the complete party list to the console.


## Viewport

1. Whenever a div with the .find-me class enters the viewport, change it's background color to `purple` and it's color to white.


## Distances

1. Get every element on the page with a class of `.find-me`.
2. For each element, calculate it's distance from the top of the page.
3. Log that distance in the console.


## Ajax/HTTP

1. Get the `[data-photo-album]` container from the DOM.
2. Get photos from https://jsonplaceholder.typicode.com/.
3. Display the first 10 photos in the photo album container (nothing fancy, just one after the other).

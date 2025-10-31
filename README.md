# DOM Create & Delete Project

## Overview
In this assignment, you will create the JavaScript for a simple shopping list application.  
The HTML and CSS are already provided for you — **you must not modify them manually.**  
All behavior should be added dynamically with JavaScript.

You’ll use JavaScript to:
- Add new items to the shopping list.
- Remove items from the list when the “Remove” button is clicked.

---

## Goals
By the end of this assignment, your app should:
1. Let users type a new item into the text box.
2. Add that item to the list when they click the “Add” button.
3. Allow users to remove items from the list by clicking their “Remove” button.

---

## Instructions

### 1. Create a Function to Add Items
Write a function that will:
- Read the text the user types into the input box.
- Use the `<template>` tag (already in the HTML) to create a copy of a list item.
- Fill in the item’s text.
- Add a “click” event listener to the remove button inside that new item.
- Append the finished item to the shopping list container (`#shopping-list`).

Give this function a clear name, such as `createItem()`.

---

### 2. Create a Function to Remove Items
Write a second function that removes an item when the remove button is clicked.

This function should:
- Remove the item’s container element from the list.

Give this function a name like `removeShoppingListItem()`.

---

### 3. Connect the Add Button
Use `addEventListener()` to connect your "Add" button to the function that creates new items.

You’ll need to:
- Select the "Add" button that’s inside the form.
- Attach a click event listener that calls your function from Step 1.

**Note:**  
The form is already set up in HTML. You should not add new IDs or modify the structure manually — only select what already exists.

---

## Constraints
- Do **not** edit the HTML or CSS files.
- Do **not** add new IDs manually.
- You **may** add or modify classes dynamically using JavaScript.
- All behavior must come from your JavaScript file.


# Grocery Store List Application

A simple and intuitive grocery list web application that allows users to keep track of items they need to buy.

## Description

This application provides a user-friendly interface for managing a grocery shopping list. Users can check off items as they purchase them, with visual feedback showing which items have been bought.

## Features

- Clean and responsive design
- Interactive checkboxes to mark items as purchased
- Visual indication of purchased items (text strikethrough and reduced opacity)
- Simple and intuitive user interface
- Mobile-friendly layout

## Technologies Used

- HTML5
- CSS3
- JavaScript

## How to Use

1. Open [index.html](file:///Users/sergeiievlev/Documents/vscode/WWW/intro/index.html) in any modern web browser
2. Browse through the grocery items listed
3. Click on the checkbox next to each item to mark it as purchased
4. When an item is checked, it will appear with a strikethrough and reduced opacity
5. Uncheck an item to revert it to its original state

## WWW Bootcamp Exercise

As part of the WWW Bootcamp curriculum, students are tasked with enhancing this application by adding a "Clear List" button with the following functionality:

### Required Enhancement
Students need to add a button that:
1. Clears all checked items
2. Resets all items to their original state (no strikethrough, full opacity)

### Implementation Details
The teacher's version includes a "Clear List" button that:
- Has the ID `clear-list`
- Is positioned below the instruction paragraph
- When clicked, iterates through all checkboxes and:
  - Unchecks any checked boxes
  - Removes strikethrough styling from labels
  - Restores full opacity to labels

Students should implement this functionality using JavaScript event listeners and DOM manipulation techniques learned in the course.

## Project Structure
```bash
├── index.html # Main HTML file containing the application 
└── README.md # This file
```


## Application Details

The grocery list includes the following items:
- Apples (🍎)
- Bananas (🍌)
- Oranges (🍊)
- Potatoes (🥔)
- Milk (🥛)

## Styling

The application features:
- Warm, off-white background (`#fffaf0`)
- Red accent color for headings and buttons (`#e74c3c`)
- Responsive design that works on both desktop and mobile devices
- Visual feedback when interacting with elements

## Browser Support

This application works with all modern browsers that support:
- Basic HTML5
- CSS3
- JavaScript ES6+

## License

This project is open source and available under the MIT License.
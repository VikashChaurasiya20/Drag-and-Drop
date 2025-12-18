# Drag & Drop Utility

A simple web-based Drag and Drop utility where users can drag an image into different white boxes.

## Description

This project demonstrates a basic drag-and-drop implementation using  HTML, CSS, and JavaScript. Users can drag the image (YouTube logo) from one box and drop it into any of the available empty white boxes.

## Features

- **Draggable Element**: An image that can be picked up and moved.
- **Drop Zones**: Multiple white boxes that accept the dropped element.
- **Visual Feedback**:
    - **Hold**: Border changes when dragging starts.
    - **Hover**: Dashed border appears when hovering over a valid drop zone.
    - **Hide**: The element briefly hides from its original position during the drag.

## Technologies Used

- **HTML5**: Structure of the page.
- **CSS3**: Styling for the boxes and drag effects.
- **JavaScript**: Logic for drag events (`dragstart`, `dragend`, `dragover`, `dragenter`, `dragleave`, `drop`).

## Installation and Usage

1.  Clone the repository or download the files.
2.  Open the `project.html` file in any modern web browser.
3.  Click and hold the image to drag it.
4.  Drop it into any of the white boxes.

## File Structure

- `project.html`: Main HTML file containing the layout.
- `style.css`: Styles for the body, boxes, and drag states (`.hold`, `.dashed`, `.hide`).
- `index.js`: JavaScript event listeners handling the drag-and-drop logic.
- `youtube.jpg`: The image asset used for dragging.

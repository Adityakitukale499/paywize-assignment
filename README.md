# Paywize Assignment

A canvas-based desktop drawing web-application that allows users to create and manipulate digital artwork using a variety of tools like freehand sketches, lines, rectangles, and text. The web-application offers flexible customization options for each tool, making it a versatile platform for creative projects.

## Introduction

This web-application provides an intuitive drawing experience with the following features:

- **Freehand Drawing:** Sketch freely on the canvas.
- **Shape Drawing:** Create lines and rectangles, with the ability to resize them.
- **Text Input:** Add and position text on the canvas.
- **Tool Customization:** Customize tools with options like color, roughness, size, stroke width, and more.
- **Eraser Tool:** Easily remove unwanted parts of your drawing.
- **Clear All:** Quickly clear the entire canvas.
- **Undo/Redo:** Undo or redo actions to correct mistakes.

### Known Issues

- **Rectangle Deletion:** Deleting drawings within rectangles currently removes the rectangle first, followed by the inner elements. It's recommended to move the rectangle before deleting it. This issue will be addressed soon.
- **Text Tool Focus:** There are focus issues with the text tool, which will be fixed in an upcoming update.

## Used Technologies

This project is built using the following technologies:

- **HTML**
- **JavaScript**
- **Vite + ReactJS**
- **SASS**
- **Vercel** (for deployment)

## Libraries

The following libraries are used in this project:

- **Perfect-freehand**
- **Roughjs**

## Installation

- First, clone the project:

```sh
git clone
```

- Then, start the project on localhost:

```bash
# install dependencies with npm
npm install

# serve at localhost:5173
npm run dev
```

<br>
- After running these commands, the web-application will be available at http://localhost:5173 .
<br>

# Previews

<center>

## Canvas

<p align="center">
<img src="assets/canvas-preview.png" alt="canvas" width="800"/>
</p>

</center>
# paywize-assignment

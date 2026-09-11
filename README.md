# Interactive Square Grid Editor

A simple web-based image editing tool that allows users to upload an image, divide it into a customizable square grid, and interactively rearrange and rotate individual tiles.

## Features

* Upload an image directly from your device
* Customize the number of **Rows** and **Columns**
* Generate a square tile grid from the uploaded image
* Select individual grid tiles
* Rotate tiles using the **R** key
* Rearrange tiles using **drag and drop**
* Download the edited image
* Works directly in the browser
* No external software or installation required

## How It Works

1. Upload an image using the file upload option.
2. Set the desired number of rows and columns.
3. Click **Generate Grid**.
4. Select a tile by clicking on it.
5. Press **R** to rotate the selected tile.
6. Drag and drop tiles to swap their positions.
7. Click **Download Image** to save the final result.

## Technologies Used

* **HTML5** – Structure of the application
* **CSS3** – Styling and layout
* **JavaScript** – Grid generation, tile manipulation, rotation, drag-and-drop, and image processing
* **HTML Canvas API** – Image rendering and exporting

## Project Structure

```text
Interactive-Square-Grid-Editor/
│
├── index.html
└── README.md
```

## Usage

Simply open `index.html` in a modern web browser.

No server or additional dependencies are required.

## Controls

| Action           | Control              |
| ---------------- | -------------------- |
| Upload Image     | File Upload          |
| Change Grid Size | Rows / Columns       |
| Generate Grid    | Generate Grid button |
| Select Tile      | Left Click           |
| Rotate Tile      | Press `R`            |
| Rearrange Tile   | Drag and Drop        |
| Save Result      | Download Image       |

## Use Cases

This project can be useful for:

* Image puzzle creation
* Tile-based image manipulation
* Interactive image experiments
* Learning HTML Canvas
* Learning JavaScript drag-and-drop functionality
* Understanding basic image processing in the browser

## Future Improvements

* Add more rotation controls
* Add tile flipping
* Add undo/redo functionality
* Add zoom and pan controls
* Add support for non-square grids
* Add puzzle-solving mode
* Add multiple image formats and export options

## License

This project is open for educational and personal use.

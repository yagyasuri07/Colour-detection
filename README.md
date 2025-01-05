# COLOR_DETECTION

This repository hosts the Color Detection App, a web-based tool for identifying colors in an uploaded image. Built using Python and Streamlit, the app provides a user-friendly interface for exploring RGB values, color names, and corresponding hexadecimal codes by selecting specific points in an image.

## Technology Stack

- Python Libraries:
  - pandas: For handling CSV files.
  - numpy: For image processing.
  - streamlit: For creating the web interface.
  - Pillow: For handling image uploads.
  - plotly.express: For interactive image rendering.

## Features

Upload Images: Supports image formats like .jpg, .jpeg, and .png.
Color Detection: Identifies the closest color name based on RGB values.
Hex Code Display: Shows the hex code of the detected color.
Interactive Visualization: Uses Plotly for rendering the uploaded image interactively.
User Inputs: Allows users to provide coordinates to detect specific colors in the image.
Live Color Preview: Displays a visual representation of the detected color.

## Usage

1. Launch the App: Open the app in your browser after running the Streamlit command.
2. Upload an Image: Use the Upload Image button to load your image.
3. Provide Coordinates: Enter the X and Y coordinates to select a pixel from the image.
4. Detect Color: Click the Detect Color button to view the detected color name, RGB values, and hex code.
5. Visual Feedback: The app displays a live color preview for better visualization.

# Gradient Builder

## Overview
The Gradient Builder is a web-based tool that allows users to create customizable CSS gradients. Users can adjust various properties such as gradient type, colors, angle, position, and intensity. The generated CSS code is displayed and can be copied for easy use in web projects.

## Features
- Choose between **Linear, Radial, and Conic gradients**
- Select two colors using a color picker
- Adjust gradient **angle** (for linear and conic gradients)
- Modify **position X and Y** (for radial and conic gradients)
- Control **intensity** (opacity) of the gradient
- Automatically generate CSS code for the applied gradient
- **Copy CSS** code to clipboard with a button click

## Technologies Used
- **HTML**: Structure of the webpage
- **CSS**: Styling and layout
- **JavaScript**: Interactive controls and dynamic gradient generation

## How to Use
1. Open the `index.html` file in a web browser.
2. Select the **Gradient Type** from the dropdown.
3. Choose **Color 1** and **Color 2** using the color pickers.
4. Adjust the **Angle** slider (for linear and conic gradients).
5. Modify the **Position X** and **Position Y** sliders (for radial and conic gradients).
6. Adjust the **Intensity** slider to control gradient opacity.
7. The gradient preview updates dynamically in the main content area.
8. The **CSS code** is displayed in the sidebar.
9. Click the **"Copy CSS"** button to copy the gradient code for use in your projects.

## Code Breakdown
- **HTML**: Defines the UI structure with a sidebar for controls and a main content area for gradient preview.
- **CSS**: Styles the layout, sidebar, and interactive elements.
- **JavaScript**:
  - Listens for user input changes.
  - Converts HEX colors to RGBA format.
  - Updates the gradient dynamically based on user selections.
  - Copies the generated CSS to the clipboard.

## Future Enhancements
- Add more color stops for multi-color gradients.
- Support for repeating gradients.
- Export gradients as image files.
- Save and load custom gradient presets.




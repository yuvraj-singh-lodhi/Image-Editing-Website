# Image Editor 

This is a simple Javascript image editor that allows users to apply filters and transformations to an image.

## Features

- Load image from local device  
- Apply filters - brightness, saturation, inversion, grayscale
- Rotate and flip image  
- Reset filters
- Save edited image

## Usage

To use the editor: 

- Click "Choose Image" and select an image from your local device
- Edit image using the sidebar options
  - Apply filters by selecting filter type and adjusting the slider value
  - Rotate using the rotate buttons
  - Flip horizontal or vertical using the flip buttons   
- Click "Save Image" to download the edited image
- Click "Remove Image" to remove the current image
- Click "Reset Filters" to reset to original image state

### Filters

The editor allows you to adjust the following filters:

**Brightness** - Makes the image brighter or darker

**Saturation** - Increases or decreases color intensity

**Inversion** - Inverts the image colors

**Grayscale** - Removes color and makes the image gray

### Rotate & Flip  

You can rotate the image 90 degrees left or right.

Flipping will mirror the image vertically or horizontally.

## Live Demo

You can test the live demo of the image editor here:

https://yuvraj-singh-lodhi.github.io/Image-Editing-Website/

## Development

The editor is built using:

- HTML
- CSS  
- Javascript

The main JS logic is contained in `script.js`. This handles loading the image, applying filters and transformations, and saving the image. 

`index.html` contains the UI markup.

`styles.css` handles styling and layout.

### Running Locally

To run the editor locally, open the `index.html` file in your browser.

## Credits

- [BoxIcons](https://boxicons.com/) and [FontAwesome](https://fontawesome.com/) for icons

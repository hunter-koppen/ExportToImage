## ExportToImage
This module contains a javascript action that take a classname and converts everything on the page inside the class to an image.

## Features
- Easily target the right spot on the page with a classname
- Convert to .png
- Provide a name for the image

## Dependencies
- dom-to-image library (provided by the module)

## Usage
Simply create a nanoflow and add the js action to the flow. Provide the classname to export to the image. The javascript action already saves the image.

If you wish to immediately download the exported image, simply call a microflow from the nanoflow which contains the JS action and then use the download file activity.

## Issues, suggestions and feature requests
https://github.com/hunter-koppen/ExportToImage/issues
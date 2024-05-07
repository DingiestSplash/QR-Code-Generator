
# QR Code Generator
This Node.js script prompts the user to input a URL and generates a QR code for the URL. Additionally, it saves the URL to a text file.

## Getting Started
Follow these instructions to get a copy of the project up and running on your local machine.

## Prerequisites
* Node.js installed on your machine.
* npm (Node Package Manager) comes with Node.js installation.

### Install dependencies:
npm i inquirer qr-image

## Usage
* Run the script: node index.js
* Enter the URL when prompted.
* The script will generate a QR code for the URL and save it as qr_img.png. The entered URL will also be saved to URL.txt.

## Built With
* inquirer - A collection of common interactive command line user interfaces.
* qr-image - A QR code and bar code generator.
* fs - Node.js file system module. 

### Acknowledgments
* John Resig for creating the [inquirer](https://www.npmjs.com/package/inquirer) library.
* Alexey Ten for creating the [qr-image](https://www.npmjs.com/package/qr-image) library.

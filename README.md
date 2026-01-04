
The QR Code Generator is a Node.js command-line tool that converts a user-provided URL into a QR code image, simplifying the process of generating scannable QR codes for URLs.

Usage
Before using the QR Code Generator, ensure that you have Node.js installed on your system.


Navigate to the project directory.
cd qr-code-generator-nodejs
Install project dependencies.
npm install
Generate QR Codes
Run the generator from the command line.

node index.js
Follow the prompts to input the URL you want to convert into a QR code.

The resulting QR code image will be saved as "your-qr.png" in the project directory.

Dependencies
This project relies on the following dependencies:

inquirer: For user input prompts.
qr-image: For QR code generation.

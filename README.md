Description

The QR Code Generator is a Node.js command-line tool that converts a user-provided URL into a QR code image. It simplifies the process of generating scannable QR codes for URLs using a simple terminal-based interface.

Usage

Before using the QR Code Generator, make sure Node.js (v18 or higher) is installed on your system.

Clone and Set Up

Clone this repository to your local machine.

git clone https://github.com/AnushaBhavani1/QR_Code_Generator.git


Navigate to the project directory.

cd QR_Code_Generator


Install the project dependencies.

npm install

Generate QR Codes

Run the generator from the command line.

node qr.js


Follow the prompt to enter the URL you want to convert into a QR code.

Output

The generated QR code image will be saved as qr_img.png.

The entered URL will be saved in URL.txt.

Both files are created in the project directory.

Dependencies

This project uses the following dependencies.

inquirer – for taking user input from the command line
qr-image – for generating QR code images

Requirements

Node.js v18 or higher
Terminal that supports interactive input such as VS Code Terminal, Command Prompt, or Git Bash

Enjoy

Enjoy generating QR codes quickly and easily using this Node.js command-line tool.

# QR Code Generator

This project is a Node.js application that serves as a QR code generator. It utilizes the `inquirer`, `qr-image`, and `fs` npm packages to accomplish the following tasks:

1. Prompt the user to enter a URL.
2. Generate a QR code image based on the user-entered URL.
3. Save the user input to a text file.

## Installation

To run this project, ensure you have Node.js installed on your system. Then, follow these steps:

1. Clone the repository to your local machine.
2. Navigate to the project directory in your terminal.
3. Run `npm install` to install the required dependencies.

## Usage

To use this application, follow these steps:

1. Run the application using `node index.js`.
2. You will be prompted to type in your URL.
3. Enter your URL and press Enter.
4. A QR code image will be generated based on your URL and saved as `qr_img.png`.
5. Your URL will also be saved in a text file named `URL.txt`.

## Dependencies

This project relies on the following npm packages:

- `inquirer`: Used to prompt users for input in the terminal.
- `qr-image`: Used to generate QR code images based on user input.
- `fs`: A native Node.js module used to interact with the file system.

Make sure these dependencies are installed in your environment before running the project.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request on the project's GitHub repository.

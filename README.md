# Image to PDF Converter

This project is a simple web application that allows users to convert multiple image files into a single PDF document. It utilizes HTML, CSS, and JavaScript to provide a user-friendly interface and perform the conversion.

## How to Use

1. Open the `index.html` file in a web browser.
2. Click on the "Choose File" button or drag and drop image files into the designated area.
3. Select one or multiple image files from the file dialog.
4. Click the "Convert to PDF" button.
5. Once the conversion is complete, a download link for the generated PDF will appear.
6. Click on the "Download PDF" link to save the PDF file to your device.

## Dependencies

The project requires the following dependencies:

- [jsPDF](https://cdnjs.cloudflare.com/ajax/libs/jspdf/1.5.3/jspdf.debug.js) (included via CDN): A JavaScript library for generating PDF files.

## Project Structure

The project consists of the following files:

- `index.html`: The main HTML file that contains the structure and elements of the web application.
- `style.css`: The CSS file that defines the styling for the web application.
- `script.js`: The JavaScript file that handles the image-to-PDF conversion and interaction logic.

## CSS Styles

The `style.css` file contains CSS styles for the web application. It defines the following styles:

- `body`: Sets the background color and general font styles.
- `.container`: Defines the container for the main content with a specified width and background color.
- `h1`: Styles the heading element with a specific font size and alignment.
- `input[type="file"]`: Styles the file input element with a margin.
- `#convertBtn`: Styles the convert button with specific padding, font size, background color, and hover effect.
- `#output`: Styles the output div with margin, padding, background color, and border.

## JavaScript Functions

The `script.js` file contains JavaScript functions that handle the image-to-PDF conversion and display of the download link. It defines the following functions:

- `convertToPDF()`: This function is called when the "Convert to PDF" button is clicked. It reads the selected image files, converts them to a PDF document using jsPDF, and saves the PDF file. It also calls the `displayDownloadLink()` function to display the download link.
- `displayDownloadLink(filename)`: This function is called after the PDF conversion is complete. It creates a download link with the specified filename and appends it to the output div.

Please make sure to include the required dependencies and ensure that the file paths in the HTML file are correct for the project to function properly.

# QR Code Generator using Python

This is a simple QR Code generator application created using Python. It allows you to generate QR codes for text or URLs and save them as image files.

## Prerequisites
Before using this application, make sure you have the following installed:
- Python (version 3.7 or later)
- `qrcode` library
- `tkinter` library (included in most Python distributions)

## How to Use
1. Clone this repository to your local machine or download the code.

2. Open the terminal/command prompt and navigate to the directory where you have saved the code.

3. Run the following command to execute the application:

   ```
   python qr_code_generator.py
   ```

   Replace `qr_code_generator.py` with the name of the Python script if it's different.

4. The application will open, and you can use it to generate QR codes.

## Application Features

### Generate QR Code
- Enter the text or URL you want to encode in the QR code in the "Enter the text/URL" field.
- Enter the location where you want to save the QR code image in the "Enter the location to save the QR Code" field.
- Enter the name you want to give to the QR code image in the "Enter the name of the QR Code" field.
- Enter the size of the QR code (1 to 40, with 1 being 21x21) in the "Enter the size" field.

### Saving QR Code
- Click the "Generate Code" button to generate and save the QR code.
- The application will create a QR code image with the specified content and save it in the location you provided.
- You will receive a pop-up message confirming that the QR code has been saved successfully.

## Note
- Make sure to specify a valid size for the QR code, as the size can impact the amount of data the code can store and its visual appearance.

Feel free to customize the code and use it for your QR code generation needs. If you encounter any issues or have suggestions for improvement, please don't hesitate to open an issue or contribute to the project.

Happy coding!

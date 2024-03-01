# ARCBM (A Really Crappy Bio Maker)

## Overview:
ARCBM is a simple PyQt5 application designed by [Don Michael Tranquada](https://github.com/YanKuwada). It allows users to create personal bios with fields for personal information, education, work experience, and the option to upload an image.

## Usage:
1. **Launching the Application**: To run the application, simply execute the `ARCBM.exe` file. Upon launch, the application window will appear with various input fields for creating a personal bio.

2. **Entering Information**: Fill in the required fields such as first name, last name, date of birth, email, phone number, education, and work experience. 

3. **Uploading an Image**: Click on the "Upload Image" button to select and upload an image file (supported formats: jpg, jpeg, png). The uploaded image will be displayed in the application window.

4. **Saving Data**:
   - Press `Ctrl + S` to quickly save the entered data.
   - Press `Ctrl + Q` to exit the application.
   - Press `Ctrl + F` to toggle fullscreen mode.

5. **Saving Options**:
   - When you click on the "Save Data" button, a prompt will appear asking if you want to create a new personal file or append the data to the ARCBM database.
   - Click "New" to create a new personal file with the entered data.
   - Click "Append" to add the data to the ARCBM database.

6. **Handling Image Upload Issue**:
   - After uploading an image, the position of the "Save Data" button may shift down. To fix this issue, exit fullscreen mode (`Ctrl + F`) and re-enter fullscreen mode.

## Important Details:
- **Keyboard Shortcuts**:
  - `Ctrl + S`: Save data.
  - `Ctrl + Q`: Quit the application.
  - `Ctrl + F`: Toggle fullscreen mode.

- **Image Upload Issue**:
  - After uploading an image, the position of the "Save Data" button may shift down. To fix this, exit and re-enter fullscreen mode.

## Author:
This application was created by [Don Michael Tranquada](https://github.com/YanKuwada) of ODCS1.

## Dependencies:
- PyQt5
- openpyxl
- shutil

## Notes:
- Ensure that the `arcbm.ico` file (application icon) and the font file (`MinecraftRegular-Bmg3.otf`) are available in the specified locations.
- The ARCBM database and image directory are created automatically if they do not exist.
- Supported image formats for upload: jpg, jpeg, png.

## Support:
For any inquiries or support, please contact Don Michael Tranquada at [email@example.com].

---

**Disclaimer**: This application is created for educational purposes only. The author holds no responsibility for any misuse or unintended use of this software.

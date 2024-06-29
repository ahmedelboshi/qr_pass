# Private Pass QR

## Overview

Private Pass QR is a tool for securely storing your passwords and data within an encrypted QR code. It allows users to generate and decode QR codes, ensuring that their sensitive information remains private and under their control.

## Features

- **Generate Encrypted QR Codes:** Securely store your passwords and data inside an encrypted QR code.
- **Decode QR Codes:** Easily decode your encrypted QR codes by providing the master password.
- **Password Strength Meter:** Assess the strength of your passwords.
- **Generate Passwords:** Automatically generate strong passwords.
- **Responsive Design:** Optimized for both desktop and mobile devices.

## How to Use

### Generate QR Code

1. **Add Data:**
   - Click the `GENERATE QR` button to switch to generation mode.
   - Click the `+` button to add a new input group for each password or data you want to store.
   - Enter a title and the corresponding password or data.
   - Repeat for each piece of data you want to include.

2. **Set Master Password:**
   - Enter a master password in the "MASTER PASSWORD" field. This password will be used to encrypt your data.

3. **Generate QR Code:**
   - Click the `GENERATE QR` button to create the QR code.
   - The generated QR code will be displayed on the right side of the screen.

### Decode QR Code

1. **Switch to Decode Mode:**
   - Click the `READ QR` button to switch to decode mode.

2. **Upload QR Code:**
   - Click the `Choose Qr image File` button and select the QR code image file.

3. **Enter Master Password:**
   - Enter the master password that was used to encrypt the data.

4. **Decode QR Code:**
   - Click the `Decode QR Code` button to decrypt and display your stored data.

## Technical Details

### Dependencies

- **CryptoJS:** For encrypting and decrypting data.
- **QRCode.js:** For generating QR codes.
- **jsQR:** For decoding QR codes.
- **Alpine.js:** For managing UI state.

### File Structure

- `index.html`: The main HTML file containing the structure and layout of the tool.
- `styles.css`: Custom CSS for styling the tool.
- `script.js`: JavaScript file containing logic for QR code generation, decryption, and password strength assessment.

### JavaScript Functions

- `ui()`: Manages the UI state (decode mode).
- `passwordManager()`: Handles the core functionality, including adding input groups, generating passwords, and generating/decrypting QR codes.
- `displayQRCode(input)`: Displays the selected QR code image for decoding.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contact

For any questions or issues, please contact [support@privatepassqr.com](mailto:support@privatepassqr.com).

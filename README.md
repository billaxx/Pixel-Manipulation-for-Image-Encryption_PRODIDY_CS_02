# Image Encryption Tool

This is a simple image encryption tool written in Python. It uses basic pixel manipulation to encrypt and decrypt images. 

## Features

- Encrypts images by modifying pixel values using a user-provided key.
- Decrypts images using the same key.

## Requirements

- Python 3.x
- Pillow library (Python Imaging Library)

## Installation

1. Clone the repository or download the script.
2. Install the required library:
   ```bash
   pip install pillow
Usage
Run the script in a Python environment:

bash
Copy code
python image_encryption_tool.py
Encrypting an Image
Select option 1 in the menu.
Provide:
Path to the input image (e.g., example.jpg).
Path to save the encrypted image (e.g., encrypted_image.png).
An integer key for encryption (e.g., 123).
Decrypting an Image
Select option 2 in the menu.
Provide:
Path to the encrypted image (e.g., encrypted_image.png).
Path to save the decrypted image (e.g., decrypted_image.png).
The same integer key used for encryption.
Example
Encrypting:
bash
Copy code
Enter your choice (1/2): 1
Enter the path of the image to encrypt: input.jpg
Enter the path to save the encrypted image: encrypted_image.png
Enter the encryption key (integer): 123
Encrypted image saved to encrypted_image.png
Decrypting:
bash
Copy code
Enter your choice (1/2): 2
Enter the path of the encrypted image: encrypted_image.png
Enter the path to save the decrypted image: output.jpg
Enter the decryption key (integer): 123
Decrypted image saved to output.jpg
Notes
The encryption and decryption keys must match for successful decryption.
The encrypted image is stored as a .png file by default.
License
This project is licensed under the MIT License.

yaml
Copy code

---

This tool ensures simplicity while demonstrating basic image encryption techniques. Let me know if you'd like enhancements, such as GUI support or additional features!







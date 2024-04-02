# Image Steganography Tool
This is a Python script that enables hiding messages within images using steganography techniques. The script allows you to encode messages into images and decode hidden messages from images.

#Prerequisites
Make sure you have the following installed:

Python (version 3.x)
Pillow library (can be installed via pip install Pillow)
Other dependencies (will be installed with Pillow)

#Usage
Clone the repository or download the steganography.py file.
Open a terminal or command prompt.
Navigate to the directory containing the steganography.py file.
Run the script using Python: python steganography.py

#Encoding a Message
Choose option 1 to encode a message.
Enter the message you want to hide.
Enter the path to the cover image (the image in which you want to hide the message).
If you wish to encrypt the message, provide a password when prompted.

#Decoding a Message
Choose option 2 to decode a message from an image.
Enter the path to the stego image (the image containing the hidden message).
If the message was encrypted, provide the password when prompted.

#Notes
The cover image must be in PNG format.
Password protection is optional. If you choose to encrypt the message, you'll need to provide the same password during decoding.
Ensure that the message fits within the image dimensions to avoid errors.
The script may print status messages and warnings during execution.

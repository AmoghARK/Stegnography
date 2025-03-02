# Stegnography
**Steganography** is the practice of hiding secret data within an ordinary file, such as an image, audio, or video, to conceal its existence. **Image steganography** embeds hidden messages within image pixels using techniques like **LSB (Least Significant Bit) substitution**, where pixel values are slightly altered, making changes imperceptible.

need to run python 3
encrypt py and decrypt py need cv2 library

solution:
pip install opencv-python

1. Encrypting a Message
To hide a secret message in an image:
python encrypt.py

Steps:
i. The script will ask for the image file (mypic.png).
ii. Enter the secret message you want to hide.
iii. Provide a password for security.
iv. The encrypted image is saved as encryptedImage.png

2. Decrypting a Message
To retrieve the hidden message from the encrypted image:
python decrypt.py

Steps:
i. The script reads encryptedImage.png
ii. You must enter the correct password.
iii. If the password matches, the hidden message is displayed.

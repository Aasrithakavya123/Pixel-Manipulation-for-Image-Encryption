Image Encryption Tool
This tool allows users to encrypt and decrypt images using basic pixel manipulation techniques.

Features
   Encryption: Encrypt images by applying a key to pixel values.
   Decryption: Decrypt previously encrypted images using the same key.
   Supported Formats: Works with common image formats supported by Pillow (Python Imaging Library).
Requirements
  Python 3.x
  Pillow (Python Imaging Library)
Usage
1.Run the script
2.Follow the prompts to either encrypt or decrypt an image:

  Enter 'E' for encryption or 'D' for decryption.
  Provide the path to the input image.
  Specify the output path for the encrypted or decrypted image.
  Enter an integer key for encryption or decryption.
Encrypt an image:
  Do you want to (E)ncrypt or (D)ecrypt an image? E
  Enter the path of the image: #path of original image
  Enter the path to save the output image: #path of  output encrypt image
  Enter a key (integer value): 10
  Image encrypted and saved to /path/to/output/encrypted_image.jpg
Decrypt an image:
  Do you want to (E)ncrypt or (D)ecrypt an image? D
  Enter the path of the image: #path of original image
  Enter the path to save the output image: #path of  output decrypt image
  Enter a key (integer value): 10
  Image decrypted and saved to /path/to/output/decrypted_image.jpg

  

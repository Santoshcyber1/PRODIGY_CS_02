# PRODIGY_CS_02
How It Works:
Encryption:

Load the image using Pillow.
Convert the image into a numpy array to manipulate pixel values directly.
Swap the red and blue channels of each pixel.
Add 50 to each pixel value (and use modulo 256 to ensure values remain within valid range).
Save the encrypted image.
Decryption:

Load the encrypted image.
Subtract 50 from each pixel value (and use modulo 256 to ensure values remain within valid range).
Swap the red and blue channels back to their original positions.
Save the decrypted image.
Note:
Make sure to replace path_to_your_image.jpg with the path to the image you want to encrypt and decrypt.
This is a simple example. For stronger encryption, more complex algorithms and methods can be used.

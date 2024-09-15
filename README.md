# Image Encryption and Decryption Using Key-based Pixel Substitution

## Overview
This project implements a basic image encryption and decryption algorithm using a randomly generated key. The key is used to substitute the pixel values of an image, rendering it encrypted. The decryption process reverses the substitution, restoring the original image. This technique can be used to protect image data through simple cryptographic methods.

## Features
- Load and display an image using Matplotlib.
- Encrypt the image by substituting pixel values using a key.
- Decrypt the image to restore the original pixel values.
- Display the original, encrypted, and decrypted images for comparison.

## How it Works
1. **Encryption**: 
   - A 256-value key is randomly generated and used to map each pixel value (for R, G, and B channels) to a new value.
   - The result is an encrypted image that visually appears altered.

2. **Decryption**: 
   - The decryption process uses the same key to reverse the substitution and restore the original image.

## Dependencies
- Python 3.x
- NumPy
- Matplotlib

Install the required libraries using:
```bash
pip install numpy matplotlib

# PixelCrypt

This project implements **Image Steganography** using the **Least Significant Bit (LSB)** technique to hide text messages within images. It allows users to encode secret messages into an image file and decode them.

## Overview
Steganography is a method of hiding secret data within an ordinary, non-secret object, like an image. This project uses Java to embed and extract messages from images, enhancing privacy by obscuring the fact that communication is taking place.

## Features
- **LSB Encoding and Decoding**: Hides messages within images by modifying the least significant bits of pixels.
- **Encryption with AES**: Uses AES encryption for added message security.
- **Pixel Randomization**: Randomizes pixels to prevent detection of the hidden data.
  
## Setup
1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/Image-Steganography.git
    cd Image-Steganography
    ```

2. **Requirements**:
    - Java (tested with Java 11+)
    - Java ImageIO library

3. **Running the Program**:
   Compile the program:
   ```bash
   javac -d bin src/*.java

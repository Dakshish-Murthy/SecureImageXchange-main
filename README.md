# Image Encryption and Decryption Web Application

A web-based tool to securely encrypt and decrypt image files using cryptographic algorithms. Protecting sensitive images by encrypting them and retrieve them back with the decryption feature.

---

## Overview 

This project demonstrates the principles of cryptography and network security through the implementation of image encryption and decryption using the Data Encryption Standard (DES) algorithm. The project focuses on securing image files by transforming them into an encrypted format that can only be decrypted by authorized users possessing the correct key.

By leveraging DES, the project highlights practical applications of symmetric-key cryptography, providing an understanding of its workings, strengths, and limitations.

---

## Features

- *Encryption of Image Files*: Encrypt uploaded image files with a cryptographic algorithm to secure them.
   - ![alt text](<WhatsApp Image 2024-11-18 at 14.01.41_362b5d14.jpg>)
- *Decryption of Image Files*: Decrypt the previously encrypted image to retrieve the original.
   - ![alt text](<WhatsApp Image 2024-11-18 at 14.01.43_daee2fe9.jpg>)
   - ![alt text](<WhatsApp Image 2024-11-18 at 14.01.42_fcb32432.jpg>)
- *User-Friendly Interface*: Easy-to-use interface for seamless interaction.
- *File Integrity*: Ensures that the decrypted image is identical to the original image file.
- *Cross-Platform Support*:


---

![alt text](image.png)


## How it Works

1. Input Image File:
  - The user provides an image file to encrypt along with a symmetric key.

2. Encryption Process:

  - The image file is read as binary data.
  - DES algorithm encrypts the binary data using the provided key.
  - The encrypted data is saved as a .bin file.

3. Decryption Process:

  - The encrypted file is read as binary data.
  - DES algorithm decrypts the binary data using the same key.
  - The decrypted data is saved as the original image format.

4. Validation:

  - The decrypted image is verified against the original to ensure integrity.  

---



## Security Benefits

1. Confidentiality:

  - Prevents unauthorized access to the image content during transmission or storage.

2. Symmetric Key Cryptography:

  - Uses a single shared key for both encryption and decryption, making it efficient for large file 
  encryption.

3. Data Integrity:

  - Ensures that the image remains unaltered and decrypts accurately to its original state.
  
4. Real-World Relevance:

  - Provides insight into the practical challenges and solutions in secure data transmission.

5. Compliance:

  - Demonstrates adherence to classic cryptographic standards like DES for academic and practical learning.

---

## Future Enhancements 

  - Upgrade to stronger encryption standards like AES.
  - Implement graphical user interface (GUI) for improved usability.
  - Add support for encrypting and decrypting other file types.
  - Enhance the security of key management using hybrid cryptographic methods

---


## Team Members 
- S Dakshish Murthy (22bcs102)
- Harsh Chawla (22bcs045)
- Priyansh (22bcs091)
- Swaraj Rajesh Karvande (22bcs128)

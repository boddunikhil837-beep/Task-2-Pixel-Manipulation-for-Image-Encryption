# 🔐 Pixel Manipulation for Image Encryption

## 📌 Project Overview

**Pixel Manipulation for Image Encryption** is a Python-based project that demonstrates how an image can be protected by modifying its pixel values.

The project uses **pixel manipulation techniques** to encrypt an image and then reverse the process to decrypt it using a key.

## 🎯 Objectives

* Understand how digital images are represented as pixels.
* Learn basic image encryption techniques.
* Modify pixel values using a secret key.
* Encrypt and decrypt images using Python.
* Understand the importance of image security.

## 🛠️ Technologies Used

* **Python 3**
* **Pillow (PIL)** – Image processing library
* **NumPy** – Pixel array manipulation

## 📂 Project Structure

```text
Pixel-Manipulation-for-Image-Encryption/
│
├── image_encrypt.py
├── input.jpg
├── encrypted_image.png
├── decrypted_image.png
└── README.md
```

## ⚙️ How It Works

The project follows these basic steps:

```text
Original Image
      ↓
Read Image Pixels
      ↓
Apply Encryption Key
      ↓
Modify Pixel Values
      ↓
Encrypted Image
      ↓
Apply Same Key
      ↓
Restore Pixel Values
      ↓
Decrypted Image
```

### 🔒 Encryption

1. The input image is loaded using Pillow.
2. Pixel values are converted into an array.
3. A secret key is applied to the pixel values.
4. The modified pixels are saved as an encrypted image.

### 🔓 Decryption

1. The encrypted image is loaded.
2. The same key is applied in reverse.
3. Original pixel values are restored.
4. The decrypted image is saved.

## 📥 Installation

Install Python and then install the required libraries:

```bash
pip install pillow numpy
```

## ▶️ How to Run

Run the Python program using:

```bash
python image_encrypt.py
```

Make sure your input image is placed in the project folder.

## 📊 Example

**Input:**

```text
input.jpg
```

**Output:**

```text
encrypted_image.png
decrypted_image.png
```

The encrypted image should appear visually distorted or different from the original image, while the decrypted image should reproduce the original image when the correct key is used.

## 🔑 Security Note

This project is intended for **educational purposes** and demonstrates basic pixel manipulation. It should not be considered a replacement for modern, professionally designed image-encryption algorithms such as AES.

## 🚀 Future Improvements

* Add a graphical user interface (GUI).
* Allow users to enter their own encryption key.
* Support multiple image formats.
* Add stronger cryptographic algorithms.
* Add password-based encryption.

## 👨‍💻 Author

**Nikhil Boddu**

## 📄 License

This project is created for educational and learning purposes.

 

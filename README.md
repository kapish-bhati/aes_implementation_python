AES Implementation in Python 🔐

This repository contains a custom implementation of the **Advanced Encryption Standard (AES)** algorithm in Python. The AES algorithm is a symmetric encryption standard widely used across the globe for secure data transmission.

🚀 Features

- Complete AES Encryption & Decryption
- Supports 128-bit key size (AES-128)
- Implements all AES stages:
  - Key Expansion
  - AddRoundKey
  - SubBytes
  - ShiftRows
  - MixColumns

📁 Project Structure
aes_implementation_python/
│
├── aes.py               # Main AES encryption and decryption logic

├── key_expansion        # Key expansion routines

├── mix_columns          # MixColumns and InvMixColumns operations

├── shift_rows           # ShiftRows and InvShiftRows functions

├── sub_bytes            # SubBytes and InvSubBytes operations

├── sbox                 # AES S-box and Inverse S-box

├── main                 # Sample usage / Entry point

└── README.md            # Project documentation



🛠️ How to Run
Clone the Repository:

Copy

git clone https://github.com/kapish-bhati/aes_implementation_python.git

cd aes_implementation_python


Run the Program:

Copy
python main.py


✅ Requirements
Python 3.x (tested on Python 3.10+)

No external libraries required

📚 Educational Purpose
This project is intended for learning and demonstration purposes. It breaks down the inner workings of AES so students and enthusiasts can understand each stage of the encryption pipeline.

⚠️ Warning: Do not use this implementation in production. It is not optimized for performance or security and lacks proper padding, secure key handling, etc.

🧑‍💻 Author
Kapish Bhati
📧 kapishbhati0316@gmail.com
🔗 LinkedIn kapish-bhati

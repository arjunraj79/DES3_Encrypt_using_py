# Triple DES Image Encryption

This project demonstrates how to encrypt and decrypt an image using the **Triple DES (3DES)** encryption algorithm in Python. The encrypted image is stored as a binary file, and the decrypted image is restored from this binary file.
## Video Demo
[https://drive.google.com/file/d/1eAWFNDEqN_H-x7PpLpPKYi7hN5uMPoHm/view?usp=sharing](url)
## Features
- Encrypt an image using Triple DES.
- Save the encrypted data in a binary file.
- Decrypt the binary file back into the original image.

## Requirements
To run this project, you need the following installed:
- **Python 3.x**: Download it from [python.org](https://www.python.org/downloads/)
- **Pillow**: For image processing.
- **PyCryptodome**: For cryptographic algorithms like Triple DES.

### Install Required Libraries:
In the project folder, run the following command to install the necessary Python libraries:

```bash
pip install pillow pycryptodome
```

### Then import DES3 for Encryption and md5 for key.

###  Cipher with integration of Triple DES key, MODE_EAX for Confidentiality & Authentication and nonce for generating random / pseudo random number which is used for authentication protocol.

### Place an image in the directory of the folder or any path is okay.

### Run des3.py file 
```bash
    python des3.py 
```

### Enter your choice to encrypt or decrypt , after encryption to decrypt it run the file again using the code and enter the choice again.

### How It Works
#### Triple DES Encryption:
- Triple DES (3DES) is a symmetric key encryption algorithm that applies the DES algorithm three times to each data block.
- A 24-byte secret key is required for encryption. If the key is shorter, it is padded, and if it's longer, it is truncated.
#### Steps in the Script:
- Convert Image to Bytes: The image is read and converted to byte format.
- Encrypt Image: Using Triple DES (3DES), the image bytes are encrypted with a secret key.
- Save Encrypted Data: The encrypted data, along with a nonce (used in encryption), is saved to a binary file.
- Decrypt Image: The encrypted data is decrypted back into the original image bytes.
- Save Decrypted Image: The decrypted image is saved in the original format (PNG).

### Thank you for using this project, and if you need any further assistance, feel free to reach out.
### — Arjun Raj

# Simple File Encryption Decryption

## Introduction
This is simple file encryption and decryption code which encrypts all the files present in the folder the code is run from, and generates a key.key file which stores the decryption key and once the decryption code is run, all the encrypted files gets decrypted with the key present in key.key file.
<br>
***NOTE: This provides an overview of how ransomware attacks works***

## Requirements
```bash
pip install cryptography
```

## Usage
1. Clone this repository in a **New folder**.
2. Add any file you want to add in the folder.
3. Add any filename of the file that is present in the folder that you don't want to be encrypted in this portion<br>
<code>if file == "encrypt.py" or file == "key.key" or file == "decrypt.py":</code>
4. Repeat step 3 for decrypt.py file too.
5. Make any file that you want to encrypt or you can make changes to previous files too.
6. Voila you are ready to run the code.

## Author
- [diwas7777](https://github.com/diwas7777)

# CODTECH-TASK4
BUILD A TOOL TO ENCRYPT AND
DECRYPT FILES USING ADVANCED
ALGORITHMS LIKE AES-256.
# PERSONAL DETAILS:
NAME:HARILAL.P

DURATION: February 5th to March 5th 2025

COMPANY: CODTECH IT SOLUTIONS

Intern ID: CT08QRM

DOMAIN: CYBER SECURITY & ETHICAL HACKING

MENTOR: NEELA SANTHOSH KUMAR
# OVERVIEW:
This python based tool is used to encrypt and descrypt files using advanced algorithms like AES-256.

# Features
* AES-256 Encryption – Uses Advanced Encryption Standard (AES) with 256-bit keys for robust security.
* Salt Protection – Adds a random salt to protect against brute-force attacks.
* IV (Initialization Vector) for CBC Mode – Ensures unique encryption each time.
* Padding Mechanism – Handles files of any size by adding PKCS7 padding.
* Password-Based Encryption – Users can encrypt/decrypt files using a password instead of a fixed key.
* Command-Line Interface (CLI) – Easily encrypt or decrypt files using simple terminal commands.
* Secure Key Derivation – Uses PBKDF2-HMAC-SHA256 to generate encryption keys from passwords.

# Encypt proccess:
1.Reads the input file.
2.Generates a random 16-byte salt and 16-byte IV.
3.Derives a 256-bit encryption key from the password and salt.
4.Uses AES-256 (CBC mode) to encrypt the file contents.
5.Saves the salt + IV + encrypted data to the output file.

# Decryption Process
1.Reads the salt + IV + encrypted data from the file.

2.Derives the 256-bit key using the password and extracted salt.

3.Uses AES-256 (CBC mode) to decrypt the file.

4.Removes padding to restore the original content.

5.Saves the decrypted data to the output file.

# How It Works
1.User provides a password to encrypt or decrypt files.
2.A 16-byte random salt is generated and stored with the encrypted file.
3.The PBKDF2 key derivation function hashes the password and salt to generate a 256-bit key.
4.The tool uses AES-256 in CBC mode with a random IV (Initialization Vector).
5.The file is padded to fit AES's 16-byte block size before encryption.
6.The ciphertext, IV, and salt are saved to the output file.
7.During decryption, the process is reversed, ensuring accurate recovery of the original file.




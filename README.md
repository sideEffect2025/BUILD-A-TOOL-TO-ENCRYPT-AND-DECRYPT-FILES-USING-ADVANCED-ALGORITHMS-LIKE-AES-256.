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
Generates a random 16-byte salt and 16-byte IV.
Derives a 256-bit encryption key from the password and salt.
Uses AES-256 (CBC mode) to encrypt the file contents.
Saves the salt + IV + encrypted data to the output file.

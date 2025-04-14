# Secure Data Encryption System

## Overview
The **Secure Data Encryption System** is a simple application built with **Streamlit**, **Python**, and **Cryptography** that allows users to securely store and retrieve encrypted data using a unique passkey. The system uses AES encryption for securing the data and provides a user-friendly interface for storing and accessing encrypted information.

## Features
- **Data Encryption**: Encrypts and stores sensitive data securely.
- **Data Decryption**: Allows users to retrieve encrypted data using the correct passkey.
- **Password Strength Checker**: Encourages users to set strong passwords by displaying a strength indicator.
- **Login System**: Simple login feature to access the retrieval functionality after a set number of failed attempts.
- **Responsive UI**: The application is designed to be mobile and desktop-friendly with an attractive and professional user interface.

## Technologies Used
- **Python**: The main programming language.
- **Streamlit**: Used to build the user interface.
- **Cryptography**: For encrypting and decrypting the stored data.
- **Hashlib**: Used to securely hash the passkey for comparison.
- **Regex**: For validating password strength.

## Requirements
Before running the application, ensure you have the following Python packages installed:

- **streamlit**: Web application framework for building the UI.
- **cryptography**: To perform data encryption and decryption.
- **hashlib**: For hashing passkeys.
- **re**: For password strength validation.

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/secure-data-encryption-system.git
   cd secure-data-encryption-system

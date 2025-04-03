# Playfair Cipher

This is a Python implementation of the Playfair cipher for encryption and decryption.

## How to Use
1. Run the script.
2. Enter a keyword to generate the cipher matrix.
3. Choose between encryption or decryption.

# Product Cipher Implementation

This project implements encryption and decryption using:
- **Caesar Cipher** (Substitution)
- **Rail Fence Cipher** (Transposition)
- **Playfair Cipher** (if included)

## Usage
Run `cipher.py` and choose:
- `1` for Encryption
- `2` for Decryption
- `3` to Exit

## How It Works
1. **Caesar Cipher** shifts letters by a given number.
2. **Rail Fence Cipher** rearranges letters in a zig-zag pattern.
3. **Product Cipher** combines both for extra security.

## Example:
```python
Enter choice: 1
Enter Plain text: HELLO WORLD
Enter shift key: 3
Enter Rail Fence key: 2
Encrypted text: KHOOR ZRUOG

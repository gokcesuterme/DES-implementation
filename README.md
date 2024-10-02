*********************************************************************
************* Writen and Coded by Gökçesu Terme *********************
*********************************************************************
DES and CTR Mode Encryption/Decryption

This program is a simple implementation of the DES encryption algorithm and CTR mode.

Requirements

To compile and run this program, you need to have a C# compiler like `csc` (comes with .NET SDK) installed on your system. i.e Rider

How to Compile and Run

!! NOTE all the plain text ciphertext you want to apply decryption or encryption your input should be in 64 bit binary format 

the main is inside the Program.cs file
Navigate to the directory containing the program files in your terminal or command prompt and use the following command to compile:

```
csc Program.cs
```

The program will prompt you to choose between Regular DES (r) or CTR mode (c).

### For Regular DES:

1. Enter 'r' for Regular DES mode.
2. Choose to encrypt (e) or decrypt (d).
3. Enter the plaintext (for encryption) or ciphertext (for decryption) as a 64-bit binary string.
4. Enter the key as a 64-bit binary string.

### For CTR Mode:

1. Enter 'c' for CTR mode.
2. Enter the IV as a 64-bit binary string.
3. Choose to encrypt (e) or decrypt (d).
4. Enter the plaintext (for encryption) or ciphertext (for decryption) as a 64-bit binary string.
5. Enter the key as a 64-bit binary string.

## Sample Inputs for testing 

- Sample plaintext (64-bit): `0010101010111101001000110110001001100110011110000110100101100110`
- Sample key (64-bit): `0001001100110100010101110111100110011011101111001101111111110001`
- Sample IV (64-bit for CTR mode): `1100110010101100101010101100110010101010110011001010101011001100`

Use the above binary strings as inputs to test the program's encryption and decryption functionalities.

To exit the program, enter 'x'.

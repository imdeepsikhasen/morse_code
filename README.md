# Morse Code Generator 
This Python program is a Morse Code Generator that allows users to encrypt text into Morse code and decrypt Morse code back into plain text.

## Features
Encryption: Convert plain text into Morse code.
Decryption: Convert Morse code back into plain text.

## How It Works
Morse Code Reference
The program uses a dictionary (MORSE_CODE_DICT) to map characters (A-Z, 0-9) to their respective Morse code representations.

## Encryption
Each letter of the input text is converted into its corresponding Morse code.
Spaces are preserved in the output.

## Decryption
The program splits Morse code into words and letters, decodes each Morse sequence back into plain text, and reconstructs the original message.

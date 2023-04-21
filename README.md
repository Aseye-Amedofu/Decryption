# Decryption
A code to decrypt encrypted text using Caesar's Cipher. The Caesar Cipher is a simple substitution cipher that replaces each letter in the plaintext with a letter a fixed number of positions down the alphabet.

# Required
To use this code, user must have Python3 (version lower than 3.10) installed

# Application
Upon running the code, it prompts the user to enter the ciphertext to be decrypted. Based on the possible shifts of the alphabets, the cipher text is then decrypted and result is produced. 

For example, if the ciphertext is XYZABCDEFGHIJKLMNOPQRST, and we know that the plaintext is ABCDEFGHIJKLMNOPQRSTUVWXYZ, then the script will try to shift the alphabet by 23 positions (since X in the ciphertext corresponds to A in the plaintext).

After trying all possible shifts, the script will output the decrypted message, which should be the plaintext ABCDEFGHIJKLMNOPQRSTUVWXYZ.

# License
This code is released under the MIT License. See the LICENSE file for more details.
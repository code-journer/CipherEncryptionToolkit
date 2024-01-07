# CipherEncryptionToolkit

**Description:** <br>
This program provides users the ability to encrypt/decrypt messages using various classical ciphers.  Initially featuring the Caesar Cipher, the project aims to expand and include the Vigenère and RSA ciphers.  User can input a message and select the desired encryption method and parameters to securely transform the text.<br><br>
**Start Date:** January 7, 2024<br>
**IDE:** PyCharm<br>
**Topic:** Python Programming, Cryptography, Encryption<br>
## **Author:** Eric Cantrell <br><br>

**___Caesar Cipher:___** <br>
**Type:** Substitution cipher.<br>
**Description:** <br>
Shifts each letter in the plaintext by a fixed number of places down or up the alphabet. For example, with a shift of 1, 'A' would become 'B', 'B' would become 'C', etc.<br>
**Usefulness:** <br>
It's straightforward to understand and implement, making it a good starting point for beginners in cryptography. However, it's not secure for serious use.

**___Vigenère Cipher:___**<br>
**Type:** Polyalphabetic substitution cipher.<br>
**Description:** <br>
Uses a keyword to determine the shift for each letter in the plaintext. This method is a series of Caesar ciphers with different shift values based on the letters of a keyword.<br>
**Usefulness:** <br>
More secure than a simple Caesar cipher due to its use of multiple alphabets. It's a good next step to understand more complex encryption methods.

**___RSA___** (Rivest-Shamir-Adleman):<br>
**Type:** Asymmetric key cipher.<br>
**Description:** <br>
One of the first public-key cryptosystems and widely used for secure data transmission. It relies on practical difficulty of factoring the product of two large prime numbers.<br>
**Usefulness:** <br>
It's a fundamental encryption method used in many secure communications. Understanding RSA is crucial for anyone looking to understand modern cryptography.

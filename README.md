### Cryptography

Is the practice of protecting data and keep it private and secure from unintended parties

* * *

### Plaintext

Is data that's readable and understandable

#### Example

*   Hello World

* * *

### Ciphertext

Is a series of characters that humans cannot make any sense of it (Not readable and understandable)

#### Example

*   Olssv Dvysk

* * *

### Secret-Key

Is a piece of information that is used to encrypt and decrypt

* * *

### Cryptography Types

#### Encryption & Decryption

It is for maintaining data confidentiality

*   Encryption: is converting plaintext into ciphertext using a secret key
*   Decryption: is convert the ciphertext back to the plain text using the same secret key

#### Encoding & Decoding

It is for maintaining data usability

*   Encoding: is converting plaintext into a different format using a publicly available scheme
*   Decoding: is converting format back into plaintext using the publicly available scheme

#### Obfuscation & De-Obfuscation

It prevents people from understanding the data

*   Obfuscation: is converting plaintext into a format that's difficult to understand
*   De-Obfuscation: revert the format back into plaintext

#### Hashing

Is mapping data to a fixed-length value

* * *

### Encryption Types

*   Symmetric: is using one key for encryption and decryption  
    *   DES
    *   RC4
    *   AES
*   Asymmetric: is using one key for encryption (Called public key) and another key for decryption (Called private key) - or vice versa
    *   Rivest-Shamir-Adleman (RSA)
    *   Elliptic Curve Digital Signature Algorithm (ECDSA)
    *   Digital Signature Algorithm (DSA)
    *   Diffie-Hellman key agreement protocol

* * *

### Encoding Types

*   URL Encoding
    *   Hello World
    *   Hello%20World
*   Unicode Encoding
    *   00000000: 74 65 73 74 test
    *   00000000: f09d978d f09d96be f09d978c f09d978d  𝗍𝖾𝗌𝗍
*   Hex Encoding
    *   Hello World
    *   48656c6c6f20576f726c64

* * *

### Hashing Types

*   Multiplication Method
*   Mid Square Method
*   Folding Method

* * *

### Cipher

Also called encryption algorithms are methods of converting plaintext into garbled data

*   Pigpen
    *   Is a geometric substitution cipher where geometric symbols are used as ciphertext
*   Morse
    *   A method made up of dots and dashes which used to encode messages
*   Caesar
    *   Is a substitution cipher where a fixed number shifts letters to the left. The original letters are called plaintext, and the replaced letters are called ciphertext. This cipher was named after Julius Caesar, who used it with a shift of 3. A becomes D, B becomes E, and so on
*   Base64
    *   Is a method of converting binary data to printable ASCII characters using a scheme of 64 characters
*   Vigenère
    *   Is a polyalphabetic substitution cipher that uses a 26×26 table A to Z called Tableau (Each row will be shifted one position to the left). This cipher needs a secret key, which will be used in the header row, and it will be repeated to match the length of the message that needs to be encrypted

* * *

### Cryptanalysis

The practice of deciphering a ciphertext without knowing the secret key

* * *

### Digital signatures

An authentication mechanism that used to validate the authenticity and integrity of a data

*   Simple Electronic Signatures (SES)
*   Advanced Electronic Signatures (AES)
*   Qualified Electronic Signatures (QES)

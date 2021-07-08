# CalfCrypt_public (alias CC)

It is a standalone, easy to use, small, performant, ~~portable~~ and efficient program to encrypt and decrypt files on you computer.
To use it, download and click on CalfCrypt.exe. (It may not work because it is written in machine code for my machine).
Then follow the instructions on the terminal.

It is written by 19 year old Michael Baram, living in Belgium (for the time being...).

## Specifications
#### Algorithms
- **AES** (Rijndael) 
  - Key size : 256 bits
  - Block size : 128 bits
  - CBC (IV : 0x30*16) 
- **PBKDF2 - SHA-256** Key generation
  - Salt : "michael baram"
  - Iteration count : **????**
  - Password : chosen by user
- **PKCS#7** Padding

#### Features
- Recursively encrypts/decrypts files
- Stores text output in a text file
- Displays the number of files and the total number of bytes encrypted or decrypted as well as the time spent to perform the tasks
- Displays detailed errors if needed
- Data loss prevention : the user has to clearly elect to delete any file
- Protects agains padding oracle attack on CBC encryption
- The user can choose to run the tests only
- The user can choose to store the key in a text file


>The journey is the reward - S.J.

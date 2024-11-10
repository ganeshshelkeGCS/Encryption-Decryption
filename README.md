# Encryption-Decryption using C++
Encryption is the process by which a readable message is convertedd to an unreadable form to prevent unauthorized parties from reading it. Decryption ia the process of converting an encrypted message back to its original(readable) format.

# Encryption Algorithms  & Decryption algorithm
1. Symmetric Key Algorithms
   1.1 AES (Advanced Encryption Standard): Widely used and very secure, with key sizes of 128, 192, and 256 bits.
   1.2 DES (Data Encryption Standard): An older standard with a 56-bit key, now considered insecure.
   1.3 3DES (Triple DES): A more secure version of DES, applying DES encryption three times.
   1.4 Blowfish: A fast and flexible cipher with key lengths from 32 to 448 bits, used in some software and hardware.
   Twofish: An enhancement of Blowfish, used in certain software for its high speed and flexibility.
2. Asymmetric Key Algorithms
   2.1 RSA (Rivest–Shamir–Adleman): One of the first public-key cryptosystems, used for secure data transmission.
   2.2 ECC (Elliptic Curve Cryptography): Uses elliptic curves for encryption,strong security with smaller keys.
   2.3 DSA (Digital Signature Algorithm): Primarily used for digital signatures, the Digital Signature Standard.
   2.4 Diffie-Hellman: Often used to securely exchange keys over a public network.
3. Hashing Algorithms
   3.1 SHA-1: SHA-1 was widely used for SSL/TLS certificates and software verification. 
   3.2 SHA-2: (Secure Hash Algorithm 2): A family of hash functions (SHA-224, SHA-256, SHA-384, and SHA-512).
   3.3 SHA-3: The latest SHA family, built as a backup to SHA-2 (SHA3-224, SHA3-256, SHA3-384, SHA3-512).
   3.4 MD5 (Message Digest 5): An older hash function, now considered weak and prone to collisions.
   3.5 RIPEMD-160: A 160-bit hashing algorithm, designed as an alternative to MD5 and SHA.

Character Encoding and Decoding Instructions:
Compile the code using g++:
D:\Projects\Encryption-Decryption-C++> g++ main.cpp encryption.cpp -o run

Run the program:
D:\Projects\Encryption-Decryption-C++> run
Enter the file name: The program will ask for the file name where you want to encrypt or decrypt the content.

Enter the file name: input.txt
Select the operation: You can choose to either encrypt or decrypt the file.

Enter e for encryption.
Enter d for decryption. Example for encryption:

Encrypt (e) or Decrypt (d): e
Encryption completed successfully.
Run the program again for decryption: To decrypt the file, you run the program again with the encrypted file:

D:\Projects\Encryption-Decryption-C++> run
Enter the encrypted file name:

Enter the file name: encrypted_input.txt
Choose to decrypt: Enter d to decrypt the file:

Encrypt (e) or Decrypt (d): d
Decryption completed successfully.


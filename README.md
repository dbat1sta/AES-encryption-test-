# AES-encryption-test-
Assignment for applied crypto course



How to Compile and Run the Code:
The code is written in Python and doesn't require compilation. However, ensure that you have Python installed on your system.

To run the code, open a terminal or command prompt, navigate to the directory containing the code, and execute the following command:

bash
Copy code
python filename.py
Replace filename.py with the actual name of your Python script.

The code includes test cases to demonstrate encryption and decryption using the provided AES implementation. The test cases are located at the end of the script within the if __name__ == "__main__": block.

Additional Material
I primarily used the information provided in the code comments and the AES algorithm specifications. No additional external resources were consulted during the development of this code.

Test Cases from Appendix C
The provided test cases from Appendix C of the NIST Special Publication 800-38A for AES encryption (encryption only) have been implemented and tested. The test cases are as follows:

Test Vector C.1

Plaintext: 00112233445566778899aabbccddeeff
Key: 000102030405060708090a0b0c0d0e0f
Expected Ciphertext: 69c4e0d86a7b0430d8cdb78070b4c55a
Test Vector C.2

Plaintext: 00112233445566778899aabbccddeeff
Key: 000102030405060708090a0b0c0d0e0f1011121314151617
Expected Ciphertext: dda97ca4864cdfe06eaf70a0ec0d7191
Test Vector C.3

Plaintext: 00112233445566778899aabbccddeeff
Key: 000102030405060708090a0b0c0d0e0f101112131415161718191a1b1c1d1e1f
Expected Ciphertext: 8ea2b7ca516745bfeafc49904b496089

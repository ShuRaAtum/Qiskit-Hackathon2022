# Qiskit-Hackathon 2022

## Main Contribution?

## Classical Differential Cryptanalysis
Symmetric key cryptography is based on the safety of generating ciphertext in which plaintext information is completely lost by receiving plaintext and a key and repeating encryption operations. It should not be possible to obtain any information about the plaintext from the ciphertext. In this case, the safety depends only on the information of the key. Differential attacks aim to eliminate key information in the encryption process of symmetric key ciphers as one of the cryptographic analyses.

Differential attack is an attack technique that can be used in Chosen Plaintext Attack.
In the case of modern encryption, after dividing plaintext into small data units, substitution and permutation are repeatedly applied to make decryption difficult. Because this substitution process is non-linear, there was no proper attack method other than a brute force attack.


|in/out|0|1|2|3|4|5|6|7|8|9|a|b|c|d|e|f|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|0|**16**|0|0|0|0|0|0|0|0|0|0|0|0|0|0|0|
|1|0|4|0|2|2|2|0|2|0|0|0|2|0|0|2|0|
|2|0|0|0|0|0|0|0|0|**6**|0|0|2|0|**6**|2|0|
|3|0|0|0|2|0|0|2|0|0|2|2|2|4|2|0|0|
|4|0|0|0|0|0|0|0|4|0|0|0|0|4|0|0|**8**|
|5|0|0|2|0|2|0|0|0|2|2|0|2|2|0|4|0|
|6|0|2|**6**|0|2|0|0|2|0|0|0|0|0|0|0|4|
|7|0|2|0|4|2|2|2|0|0|0|2|0|2|0|0|0|
|8|0|2|2|0|0|0|0|0|**6**|0|4|2|0|0|0|0|
|9|0|0|0|2|0|0|2|0|0|4|0|2|0|0|2|4|
|a|0|0|4|0|0|**6**|2|0|0|2|2|0|0|0|0|0|
|b|0|2|2|2|2|0|2|2|0|0|0|2|0|0|2|0|
|c|0|0|0|0|2|2|2|**6**|0|0|0|0|0|4|0|0|
|d|0|2|0|4|2|0|4|0|0|2|0|0|2|0|0|0|
|e|0|0|0|0|0|4|0|0|0|2|**6**|0|0|2|2|0|
|f|0|2|0|0|2|0|0|0|2|2|0|2|2|2|2|0|

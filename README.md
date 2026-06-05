🧪 Task 1 - AES256 Encryption with GPG
Objective

Decrypt an AES256 encrypted file using GPG and recover the plaintext.

Command Used
gpg --output decrypted.txt --decrypt quote01.txt.gpg
Result
Do not waste time idling or thinking after you have set your goals.
Miyamoto Musashi
Key Takeaway

GPG can be used to encrypt and decrypt files using symmetric encryption algorithms such as AES256.

🧪 Task 2 - AES256-CBC with OpenSSL
Objective

Decrypt an AES256-CBC encrypted file using OpenSSL.

Command Used
openssl aes-256-cbc -d -in quote02 -out message.txt
Result
The true science of martial arts means practicing them in such a way that they will be useful at any time...
Key Takeaway

AES-CBC mode requires both the encryption key and proper initialization vectors for secure operation.

🧪 Task 3 - CAMELLIA256 Encryption
Objective

Decrypt a CAMELLIA256 encrypted file using GPG.

Command Used
gpg --output quote03message.txt --decrypt quote03.txt.gpg
Result
You must understand that there is more than one path to the top of the mountain.
Key Takeaway

CAMELLIA is a symmetric encryption algorithm comparable to AES and is supported by GPG.

🧪 Task 4 - RSA Key Analysis
Objective

Inspect RSA private key components and understand RSA structure.

Command Used
openssl rsa -in private-key-bob.pem -text -noout
Findings
Parameter	Value
Key Size	2048 bits
Prime p (last byte)	e7
Prime q (last byte)	27
Key Takeaway

RSA security relies on the mathematical difficulty of factoring the product of two large prime numbers.

🧪 Task 5 - Diffie-Hellman Parameters
Objective

Inspect Diffie-Hellman parameters and determine key properties.

Command Used
openssl dhparam -in dhparams.pem -text -noout
Findings
Parameter	Value
Prime Size	4096 bits
Last Byte	4f
Generator	2
Key Takeaway

Diffie-Hellman allows two parties to securely establish a shared secret over an untrusted network.

🧪 Task 6 - SHA256 Hashing
Objective

Generate SHA256 hashes and observe integrity changes.

Command Used
sha256sum order.json
Original Hash
2c34b68669427d15f76a1c06ab941e3e6038dacdfb9209455c87519a3ef2c660
Modified File Hash
11faeec5edc2a2bad82ab116bbe4df0f4bc6edd96adac7150bb4e6364a238466
Key Takeaway

Even a small change in a file causes a completely different hash value.

🧪 Task 7 - HMAC Authentication
Objective

Generate an HMAC using SHA256.

Command Used
openssl dgst -sha256 -hmac 3RfDFz82 order.txt
Result
c7e4de386a09ef970300243a70a444ee2a4ca62413aeaeb7097d43d2c5fac89f
Key Takeaway

HMAC combines a cryptographic hash function with a secret key to verify both integrity and authenticity.

🧪 Task 8 - X.509 Certificate Analysis
Objective

Inspect a digital certificate and identify key attributes.

Command Used
openssl x509 -in cert.pem -text
Findings
Parameter	Value
Public Key Size	4096 bits
Valid Until	2039
Algorithm	RSA
Signature	SHA256WithRSAEncryption
Key Takeaway

Digital certificates bind public keys to identities and form the basis of TLS/HTTPS security.

🧪 Task 9 - Password Hash Cracking
Objective

Recover the plaintext password from an MD5 hash.

Hash
3fc0a7acf087f549ac2b266baf94b8b1
Recovered Password
qwerty123
Key Takeaway

MD5 is no longer considered secure for password storage due to its speed and susceptibility to cracking attacks.

🏆 Skills Demonstrated
GPG Decryption
OpenSSL Usage
AES Encryption
CAMELLIA Encryption
RSA Analysis
Diffie-Hellman
SHA256 Hashing
HMAC Generation
Certificate Inspection
Password Hash Analysis
Linux Command Line
Cryptographic Fundamentals
📚 Tools Used
Kali Linux
OpenSSL
GPG
SHA256SUM
Nano
TryHackMe AttackBox
🎓 Room Completion

Platform: TryHackMe
Room: Introduction to Cryptography
Status: ✅ Completed
Tasks Completed: 9/9
Points Earned: 120

Author

Assan J.

# Cryptographic-File-System-
SYMMETRIC CRYPTOGRAPHY USING XOR CIPHER IN 8086
Securing data is an essential task in creating any file system, and cryptography is
widely used in data security. The XOR cipher is a simple, inexpensive, robust
cipher that is very useful in cryptography, because it has a balanced output, i.e., the
ciphertext output can be very randomly 0 or 1, based on the plain text and key.
This is not the case with other operations like AND, OR, etc. The XOR cipher has
been used in computer malware, to prevent reverse engineering of the code.
Further, it is frequently used in multiple different levels in algorithms like DES
and AES. DES uses multiple rounds of XOR, along with other cryptographic
mathematical functions, to secure data, and it is also a symmetric key
cryptographic algorithm.
Using assembly language in the field of security is crucial, because as already
mentioned, it is essential for security experts to understand how computer malware
and file system security works, and train for it constantly. Further, assembly
language interacts with the system on the architectural level, so developing
security mechanisms in ALP is very important.
In our project, we have developed an algorithm to use the XOR cipher with a
given key. As 8086 is a microprocessor and not a microcontroller, it does not have
its own filing system, and hence we have to use DOS BOX, to access the input file
and create the output file with the hashed output. The key that the user provides
will be repeated until the length of the string is matched, and then the output shall
be XORed. There will be a more extensive explanation of this in the
implementation part of our study.
 
Flowchart:

![image](https://github.com/aparnasahu5/Cryptographic-File-System-/assets/95071662/1bb20f12-e0ab-4bbd-bd62-7f7dfc96454d)

Screenshots of the Machine Code:

![image](https://github.com/aparnasahu5/Cryptographic-File-System-/assets/95071662/c454cbdc-43c4-4390-9e5d-9c430db44c48)

![image](https://github.com/aparnasahu5/Cryptographic-File-System-/assets/95071662/02e38e75-fe37-41c1-a3a0-fa35d2ed72a0)

![image](https://github.com/aparnasahu5/Cryptographic-File-System-/assets/95071662/cfe43b9b-85b1-4575-aeeb-8034edc1a11f)

RESULTS:
The results of our code were fast, and accurate. On executing the code, the result
was an output file with the XORed output. The code runs accurately for multiple
test cases.

![image](https://github.com/aparnasahu5/Cryptographic-File-System-/assets/95071662/864762c2-93a0-4d62-ad0f-6092dfaabe77)

![image](https://github.com/aparnasahu5/Cryptographic-File-System-/assets/95071662/50a012d4-d626-46e5-b2a1-5316ececdf54)

![image](https://github.com/aparnasahu5/Cryptographic-File-System-/assets/95071662/a01f813f-2e86-4094-b666-a4190c0437db)

DONE BY
APARNA SAHU - 19BCE2125

# Cryptography Hacks

## Substitution Ciphers

### Monoalphabetic Substitution Ciphers



#### ROT13 (Rotate by 13 Place)

A Simple letter substitution cipher that replaces a letter with the 13th letter after it.

|      |       |
| ---- |:-----:|
|   A  |   N   |
|   B  |   O   |
|   C  |   P   |
|   D  |   Q   |
|   E  |   R   |
|   F  |   S   |
|   G  |   T   |
|   H  |   U   |
|   I  |   V   |
|   J  |   W   |
|   K  |   X   |
|   L  |   Y   |
|   M  |   Z   |

Example: `PASSWORD` == `CNFFJBEQ`

Linux Command: `echo CNFFJBEQ | tr '[A-Za-z]' 'M-ZA-Nm-za-n'`


#### Caesar Cipher
It is a type of substitution cipher in which each letter in the plaintext is 'shifted' a certain number of places down the alphabet

EXAMPLE: SHIFT 1
|      |       |
| ---- |:-----:|
|   A  |   B   |
|   B  |   C   |
|   C  |   D   |
|   D  |   E   |
|   E  |   F   |
|   F  |   G   |
|   G  |   H   |
|   H  |   I   |
|   I  |   J   |
|   J  |   K   |
|   K  |   L   |
|   L  |   M   |
|   M  |   N   |
|   N  |   O   |
|   O  |   P   |
|   P  |   Q   |
|   Q  |   R   |
|   R  |   S   |
|   S  |   T   |
|   T  |   U   |
|   U  |   V   |
|   V  |   W   |
|   W  |   X   |
|   X  |   Y   |
|   Y  |   Z   |
|   Z  |   A   |

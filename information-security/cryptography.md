### Definitions of Cryptography

## Some Common Terms

### Algorithm
Set of Mathematical rules used in encryption & decryption.

### Cipher
This is another name of algorithm.

### Cryptography
Science of writing and transmitting data in form that is only available of intended individuals.

### Cryptosystem
System of hardware & software that works in combination to convert plaintext into cyphertext or vice-versa.

### Entity Authentication
Proving the identity of the entity that sent a message.

### Decipher
Act of tranforming the data into a readable format.

### Key
Secret sequence of bits and instructions that governs the act of encryption and decryption.

### Keyspace
A range of possible values to construct keys.

### Plaintext (cleartext)
Is the data in readable format.

### Reciept
The acknowledgement of message reception.

### Work Factor
Estimated time, effort, and resources required to break a cryptosystem.

### Classification of the field of Cryptography

## Cryptology
### Cryptography
- Symmetric Ciphers
  - Block Cyphers
  - Stream Cyphers
- Asymmetric Ciphers
- Protocols
### Cryptanalysis

## One-Time Pad
- Encryption scheme (aka Vernam Cipher).
- Unbreakable if properly implemented.
- Invented by Gilbert Vernam in 1917.

### Encoding in One-Time Pad
- Uses a pad made up of random values instead of shifting aplhabets.
- Message is converted into bits and bits are randomised then using one-time pad constructed from them.
- It uses binary mathematic function XOR.
- Here, message and key bits are XORed and resulting bits form ecnrypted data.

### Decoding in One-Time Pad
- User must have that one time pad.
- The XOR process is then reversed (run again) to obtain the message.

### Requirements:
Each pad scheme must be:
- Made up of truly random values.
- Used only one time.
- Securely distributed to its destination.
- Secure at sender and receiver's site.
- At least as long as the message.

## Steganography
- Steganography is a method of hiding the data into another media types so that the actual data is concealed.
- Only sender and reciever are aware of that hidden data.
- Data is only hidden, not encrypted.

### Encrypting
- Message embedding requires the use of Least Significant Bit (LSB).
- Many types of files have some bits which can be altered without noticeable visible changes.
- Those bits can be modified to store message.
- Most suitable files to hide data can be high resolution images or high bit-rate audio files.
- No any increment in file size is noticeable as well.
- This can be used to hide images in images.

### Digital Watermarking
- The logo is embedded and visible to allow others not to copy the material which does not belong to them.
- This type fo steganography is reffered to as Digital Rights Management (DRM).

## Types of Ciphers
### Symmetric Encryption Ciphers have two types:
- Substitution
  - They replace bits, characters, and blocks with different ones.
  - In the Caesar cipher, each letter is replaced with the letter three places beyond it. The key is 'Shift up three'.
  - Substitutions used nowadays are very complex compared to this.
- Transportation
  - The values are scrambled or put into another order.
  - Key determines the positions the values are moved to.
Symmetric algorithms employed today use both long sequences of complicated substitutions and transpositions on messages.
- Consider algorithm a box of boxes, each box has own set of mathematical rules.
- If each of our messages always go through the same boxes and values, the evildoer can easily figure out the process.
- To foil the evildoer, we use the key which defines from which boxes and values will the message pass.
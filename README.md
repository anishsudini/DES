# DES
DES Encryption &amp; Decryption (Supports Text and Image (.ppm file type))

The three commands below specify the exact command-line syntax for invoking encryption and decryption.

	1. python3 DES.py -e message.txt key.txt encrypted.txt
 	2. python3 DES.py -d encrypted.txt key.txt decrypted.txt
  	3. python3 DES.py -i image.ppm key.txt image_enc.ppm

• Encryption (indicated with the -e argument in line 1)
	
 	– perform DES encryption on the plaintext in message.txt using the key in key.txt, and write the ciphertext to a file called encrypted.txt
 	– You can assume that message.txt and key.txt contain text strings (i.e. ASCII characters)
	– However, the final ciphertext should be saved as a single-line hex string

• Decryption (indicated with the -d argument in line 2)
    
	– perform DES decryption on the ciphertext in encrypted.txt using the key in key.txt, and write the recovered plaintext to decrypted.txt

• Image Encryption (indicated with the -i argument in line 3)
    
	– perform DES encryption on a .ppm file type image using the key in key.txt, and writes the encrypted image file to image_enc.ppm

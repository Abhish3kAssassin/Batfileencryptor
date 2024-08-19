# Batfileencryptor


How the Code Works:
XOR Encryption: The function xor_encrypt_decrypt performs XOR encryption by applying the XOR operation to each character in the input data with the provided key.
File Handling:
The encrypt_bat_file function reads the content of the .bat file, encrypts it using the XOR method, and writes the result to a new file.
The decrypt_bat_file function reads the encrypted file, decrypts it using the same XOR method, and writes the decrypted content to another file.
Important Notes:
Key Consistency: The same key must be used for both encryption and decryption.
Character Encoding: The XOR operation is performed on the ASCII value of each character, which works fine for simple text files. However, this method may not be suitable for non-text binary files without modifications.
You can customize the key and the file paths as per your requirements.

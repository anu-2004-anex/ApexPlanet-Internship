## OpenSSL Encryption & Decryption

echo "hello apexplanet" > msg.txt

# Encrypt
openssl enc -aes-256-cbc -salt -in msg.txt -out encrypted.txt

# Decrypt
openssl enc -aes-256-cbc -d -in encrypted.txt -out decrypted.txt

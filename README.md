# Password encription-and-decription
# The Caesar cipher is a straightforward encryption technique where each letter in the plaintext is "shifted" a certain number of places down or up the alphabet.
# Round-Robin Approach: After 'z', the alphabet wraps around to 'a'. This is known as a round-robin or cyclic approach.
# Encrypt Function: For each character, the function shifts it by s positions, wrapping around using modulo arithmetic.
# Decrypt Function: Reverses the shift by encrypting with 26 - s.
# Example Usage: Encrypts and then decrypts a sample password.

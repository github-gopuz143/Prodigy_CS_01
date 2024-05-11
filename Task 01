import string

def check():
    notice = input("press 'e' to encrypt, 'd' to decrypt and 'q' to quit:  ")
    if notice.lower() == 'e':
        return encrypt()
    elif notice.lower() == 'd':
        return decrypt()
    elif notice.lower() == 'q':
        return exit()
    else:
        print('Invalid Choice, Try Again')
        return check()
def caesar(text, shift, alphabet):

    def shift_alphabet(alphabet):
        return alphabet[shift:] + alphabet[:shift]

    shifted_alphabets = tuple(map(shift_alphabet, alphabet))
    final_alphabet = ''.join(alphabet)
    final_shifted_alphabets = ''.join(shifted_alphabets)
    table = str.maketrans(final_alphabet, final_shifted_alphabets)
    return text.translate(table)

def encrypt():
    phrase = input("Enter the message to Encrypt")

    def shift_alphabet(alphabet):
        return alphabet[shift:] + alphabet[:shift]

    shifted_alphabets = tuple(map(shift_alphabet, alphabet))
    final_alphabet = ''.join(alphabet)
    final_shifted_alphabets = ''.join(shifted_alphabets)
    table = str.maketrans(final_alphabet, final_shifted_alphabets)
    return text.translate(table)

def encrypt():
    phrase = input("Enter the message to Encrypt")
    print(caesar(phrase, 9, [string.ascii_lowercase, string.ascii_uppercase,string.digits, string.punctuation]))
    check()

def decrypt():
    phrase = input("Enter the message to Decrypt")
    print(caesar(phrase, 6, [string.ascii_lowercase, string.ascii_uppercase,string.digits, string.punctuation]))
    check()


if __name__ == '__main__':
    print("*** WELCOME TO PRODIGY_01 PRESENTED BY GOPIKA ***")
    print("*** DOMAIN - CYBERSECURITY INTERN *** ")
    print("This program has representing the task_01 Caesar cipher encryption and decryption.")
    print("In encryption, each letter in the plaintext is shifted a certain number of places down the alphabet.")
    print("In decryption, the process is reversed to reveal the original message.")
    print()
    check()

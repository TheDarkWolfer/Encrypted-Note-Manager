# Encrypted-Note-Manager
A notepad, but all the notes are encrypted with Fernet keys ^^

###What it does :
It uses Fernet keys to encrypt the content of text files, so that you have a CLI-based notepad
that will never store the decrypted contents of your notepads in clear. You can carry around the 
decryption key with yourself, and the program has some nifty safety features, such as : 
-Checksum verification : the program stores an encrypted checksum that detects whether or not the program has been tampered with.
-Password hashing : you'll need a password to access the program (alongside your key), and said password will be hashed, and said hash encrypted.
-"Nuke" feature : if you ever need to erase traces of this program, you can choose to nuke it, where it will shred itself, and crash the computer, leaving as little traces as I know how to.

Oh and if you're wondering, the default password is "changeme"


Hope you can use it wisely ^v^

To do later : 
-[ ] Make the config file's encryption key user-specific
-[x] Let the user change their password

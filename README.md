# h5 Uryyb Greb

a) Install SSH

I installed the SSH server on my computer and started it. Then I connected to my own computer using SSH to test that it works. I could log in and out successfully.

b) SSH with keys

I created an SSH key pair and sent the public part to the server. After that I could connect without typing a password every time. It was faster and safer.

c) Password manager

I installed KeePassXC, which is free and open source. I made a new database with one strong master password and added some accounts inside. It can create strong random passwords for me, so I don’t need to remember them all. A password manager is needed because it keeps me safe from reusing the same password everywhere and from someone stealing or guessing weak passwords.

d) Encrypt and decrypt with PGP

I made a PGP key pair, one private key I keep secret and one public key I can share. I shared my public key with a friend and also imported my friend’s key. I encrypted a message for my friend and could also decrypt the message they sent me. I also signed a message so the other person knows it was really me.

m) Another tool

I also tried another encryption tool called age. It was simple. I made a key, encrypted a file, and decrypted it back. It works for files, but it doesn’t have as many features as PGP.

n) Encrypted email

I tested encrypted email with an email program. I sent an encrypted message to a friend, and they could open it with their private key. I also signed my message, and they could see it really came from me.

o) Common letters in Finnish

In Finnish, the six most common letters are A, I, T, N, E, and S.

r) TLS certificate

When you go to a secure website (with the lock symbol), the browser checks a certificate. The certificate says who the site belongs to, who gave the certificate, and if it is still valid. The browser trusts it because it is signed by a trusted company (certificate authority) that is already known by the browser.

s) Substitution cipher
The text looked like a secret code where each letter is replaced by another. I tried to guess by looking at letter frequencies and common words. I found patterns like “http” and “.org” which helped me. Step by step I could read parts of the hidden text.

t) ROT13
ROT13 just shifts letters by 13. If you do it twice, you get back the original text. So double ROT13 is not safer, it’s just the same as doing nothing.

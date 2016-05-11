# SimpleCipher
Basic text encryption/decryption script that employs letter/word reversal and a Caesarian cipher.

A few weeks ago, I received a message via Etsy that consisted of just a bunch of 1's and 0's broken up into 8-character blocks. I recognized that it was ASCII text since almost all the blocks began with "0100" and "0101". After converting the binary data to text, I was left with a cryptogram. However, the punctuation was all wrong: there was obviously an email address embedded in the cryptogram, but it was written backwards, with three characters followed by a dot, then five letters, an @ symbol, and then a bunch more letters. I reversed the phrase and used a cryptogram solver to uncover the message. It turns out that the letters were simply shifted, so that 'A' mapped to 'N', 'B' to 'O', 'C' to 'P', etc. This is called a Caesarian cipher.

After decoding the message, I composed a reply, encrypted it through the reverse process, and emailed it to the address provided in the message. A few days later, I got a response, again encrypted in the same fashion!

Instead of manually decoding and encoding these messages, I decided to write a simple script to do it for me. This project also served as an introduction to JavaScript for me.

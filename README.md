# encryption-and-decryption-using-ecc-algorithm

What it does: 
We accept a user input image. The image is then transformed using our
hardest-ever yet beautiful algorithm (ECC algorithm) and encoded into a Golden
Record which is the only unique disk in the world. Even the same picture would
be rendered into two different disks if a different person conducts the encryption,
and each picture would have a unique private key associated with it. Of course,
with our beautiful algorithm, we are able to translate the message engraving on
the disk and transform it back into the original image. Come with your lovely
picture and get your disk like a voyager!

Advantages of Elliptic Curve Cryptography:
• Public-key cryptography works using algorithms that are easy to process
in one direction and difficult to process in the reverse direction. For
example, RSA relies on the fact that multiplying prime numbers to get a
larger number is easy, while factoring huge numbers back to the original
primes is much more difficult.
• However, to remain secure, RSA needs keys that are 2048 bits or longer.
This makes the process slow, and it also means that key size is important.
• Size is a serious advantage of elliptic curve cryptography, because it
translates into more power for smaller, mobile devices. It’s far simpler and
requires less energy to factor than it is to solve for an elliptic curve discrete
logarithm, so for two keys of the same size, RSA’s factoring encryption is
more vulnerable.
• Using ECC, you can achieve the same security level using smaller keys. In
a world where mobile devices must do more and more cryptography with
less computational power, ECC offers high security with faster, shorter
keys compared to RSA.

RSA Key Length(bit) | ECC Key Length(bit)
  
  1024 | 160
  
  2048 | 224
  
  3072 | 256
  
  7680 | 384
  
  15360 | 521

# Public Key Encryption Lesson

## What This Is

This website lets students generate their own RSA Public & Private keys, then has some embedded programs that let them encrypt and decrypt messages using public and private RSA keys. They start by picking 2 prime numbers, which is the foundation that lets them choose a public key. After these 3 choices, they have a working RSA public key pair (a public modulus and a public key) which they can use to encrypt. The website also automatically generates their secret key, which they can use to decrypt.

## Play With It

[Open the Website](https://mathymcmatherson.github.io/public-key-encryption/)

## How Does It Work?

RSA Encryption is a public algorithm. [This video offers a pretty good explanation](https://www.youtube.com/watch?v=wXB-V_Keiu8) that you could watch to better understand RSA. I don't show this to students - there are other videos I use with students instead (linked below).

## How I've Used it In The Classroom

I have [This Worksheet](https://docs.google.com/document/d/1Y2xhTrO7WxPHc1U3h73Cbc7ulikK95JoCVJtJxi-FOY/edit?usp=sharing) that I use along with the in-class website, and I have students work in pairs. We also watch some of the Encryption videos linked below. They start by generating their public & private key, they posting their _public_ information to a shared Padlet site. Once enough people have posted their information, students start sending the first 3 digits of their phone number to other pairs in the class. They use the _other people's_ public information to encrypt and send the message. As they start receiving messages, they use _their own_ private key to decrypt the messages.

At some point, hopefully without anyone noticing, I change a few of the public keys on the Padlet site to match my public key. Eventually students realize that their decryption isn't working properly, then hopefully they notice that it's because their key on the Padlet site isn't correct anymore. We talk as a class about how this happened, then use it to introduce the concept of Digital Certificates and watch the last part of the [Code.org HTTPS video](https://www.youtube.com/watch?v=kBXQZMmiA4s&t=280) that discusses this.

At the end of the day, I tell students that the goal is _not_ to have mastered the particulars of this algorithm, but rather to see how data can be encrypted relatively simply and yet be guaranteed of its security, and the process for encrypting & decrypting using public keys - use _their_ public key to encrypt, then they use _their_ private key to decrypt.

## Why I Like It
- There's lots of movement and talking as students create & pass messages
- The setup doesn't take a ton of time - pick 2 prime numbers, then start encrypting
- This is both a pro and a con: students are doing an algorithm that they don't totally understand. This can be unsatisfying as a participant, but it lets me focus on the bigger-picture concepts behind public key encryption without getting bogged-down by mastering the algorithm
- It's _real_. It's _really_ RSA, which is used in modern cryptography
- There are lots of great video resources that support this kind of lesson - see below

## Resources
- [In-Class Worksheet to Go With Website - can be done on Google Classroom](https://docs.google.com/document/d/1Y2xhTrO7WxPHc1U3h73Cbc7ulikK95JoCVJtJxi-FOY/edit?usp=sharing)
- [Art of the Problem (first half is best)](https://www.youtube.com/watch?v=YEBfamv-_do)
- [Nova Video](https://www.youtube.com/watch?v=q6FanLhvsEs)
- [Code.org Encryption Video](https://www.youtube.com/watch?v=ZghMPWGXexs)
- [Code.org HTTPS Video (starts at 4:40)](https://www.youtube.com/watch?v=kBXQZMmiA4s&t=280)
- [Code.org Modulo Clock Widget](https://studio.code.org/s/csp4-2019/stage/9/puzzle/5)

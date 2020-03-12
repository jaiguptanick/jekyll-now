---
layout: post
title: <u> Ctflearn Cryptography(Easy) Writeups </u>
published: true
---
CTFlearn (Capture The Flag) writeups, code snippets, notes, scripts for beginners..



## Character Encoding
---
`In the computing industry, standards are established to facilitate information interchanges among American coders. Unfortunately, I've made communication a little bit more difficult. Can you figure this one out? 41 42 43 54 46 7B 34 35 43 31 31 5F 31 35 5F 55 35 33 46 55 4C 7D.`

This level is pretty simple; the flag is just converted into hex.

``` Flag- ABCTF{45C1115U53FUL} ```

## Hextroadinary
---
`Meet ROXy, a coder obsessed with being exclusively the worlds best hacker. She specializes in short cryptic hard to decipher secret codes. The below hex values for example, she did something with them to generate a secret code, can you figure out what? Your answer should start with 0x.
0xc4115 0x4cf8`

ROX indicates XOR i.e perform XOR operation on these two strings to get the flag.
Use this [tool](https://xor.pw/) to perform XOR on the strings.

```Flag- c0ded ```

## Base 2 2 the 6
---
`There are so many different ways of encoding and decoding information nowadays... One of them will work! Q1RGe0ZsYWdneVdhZ2d5UmFnZ3l9`

As the challange name suggest it is converted into base64 encoding.

```Flag- CTF{FlaggyWaggyRaggy}```
## BruXOR
`There is a technique called bruteforce. Message: q{vpln'bH_varHuebcrqxetrHOXEj No key! Just brute .. brute .. brute ... :D`

This level again requires brute-forcing XOR. This online [tool](https://gchq.github.io/CyberChef/) can easily do this with the key 17.
![img](https://github.com/jaiguptanick/writeup/blob/master/images/1_bruXOR_1.PNG "img1")


## Reverse Polarity
`I got a new hard drive just to hold my flag, but I'm afraid that it rotted. What do I do? The only thing I could get off of it was this: 01000011010101000100011001111011010000100110100101110100010111110100011001101100011010010111000001110000011010010110111001111101`

This level can be solved by just converting the Binary to Text.
``` Flag-CTF{Bit_Flippin} ```





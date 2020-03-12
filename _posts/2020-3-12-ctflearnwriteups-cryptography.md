---
layout: post
title: <u> Ctflearn Writeups </u>
published: true
---

#  <u>Cryptography(Easy) writeups</u>
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

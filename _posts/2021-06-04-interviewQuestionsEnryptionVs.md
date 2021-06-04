---
layout: post
title: "Encryption vs Encoding vs Hashing vs Obfuscation vs Signing"
subheading: Possible interview question for IT-Sec role
author: Reza Asif
categories: crypthography
banner: https://images.unsplash.com/photo-1553849261-7d16840a2eca?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=2700&q=80
tags: [security, encryption, interview]
sidebar: []
---

There are many ways to alter a given text. This "text" I am speaking about is a representative of data, which ich basically an enumeration of bits.<br><br>

Based on the motivation, there are multiple option to alter it.
For instance, let us have a look on the basics:<br><br>

<b>Enryption:<b/><br><br>
To encrypt data, you will require a (secret) key. You can use the key to enrypt your input (plaintext) and can generate an output (cyphertext).
One major benefit is, that you can decrypt the ciphertext by using the same secret key and retrieve the input back. Encrpyted data can be read in theory, but practically it bit or the text will be senseless.<br><br>

#give examples<br><br>

<b>Encoding:<b/><br><br>
Just like encryption, you can alter you data using encoding, but there is no key necessary. This approach is comparable to tranlation of a spoken language (e.g. tranlation form english to german). You will just change the format in which data is presented in, the content stays same. This is usefull for e.g. modern cpus, which work more efficient with hex values than binaries.

#give example<br><br>

<b>Hashing<b/><br><br>

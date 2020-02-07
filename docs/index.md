---
title: "Crytpo challenge Game01"
layout: home

author_profile: true

tags:
    - aws
    - gameday
    - awsgameday
    - unicorns
    - crypto
    - cryptography

description: "Crytpo challenge game01"

---

## Mini-game crypto-challenge

![Four-rotor-enigma.jpg](/assets/images/Four-rotor-enigma.jpg "Four-rotor-enigma, Image credits wikipedia")

### Welcome and version

Welcome to the crypto-challenge version `v2 machine: nzv-09p6186nnp1781870`

First of all, can you find where the challenge is?

All I can say is that the you will run in in the `us-east-1` region.

You also need something from this page. Maybe you read it already.

If you need a hint to decypher it... "Julius Caesar, was a Roman dictator..."

### When you find it

When you find it, ssh into to it and them game begins! Note the login messange.

Can you now find the password that decrypts the first file to reveal the hidden message?

### How files were encrypted and how to decrypt them

Files were encrypted like this:

`gpg --cipher-algo AES256 --symmetric --output file01.encrypted file01`

When you find the password for the next file, use the command like this:

`gpg --output file{01..05} -—decrypt file{01..05}.encrypted`

Then you will be asked for a password.
Type it in to decrypt the file and reveal the next hidden message.

If you need to clear the gpg cache, in case you put a wrong password you might need to run this command `echo RELOADAGENT | gpg-connect-agent`

### Password have the full names of the services

(it not fun if you brute-force it, but is possible)

The passwords to decrypt the files needs the AWS or Amazon full names of the services.

Spaces matter. New lines matter. Everything matters!

- e.g. "Where would you store object files with 99.999999999% (11 9's) of durability?"

- Password answer would be: `Amazon Simple Storage Service`

### Best of luck

We wish you the best of good luck!

---

## Find more about AWS GameDay

[AWS GameDay](https://aws.amazon.com/gameday/)

[www.real-unicorns.com](https://www.real-unicorns.com)

---

Cryptographic game was created by [Antonio Feijao UK](https://www.linkedin.com/in/antoniofeijaouk/), AWS Solutions Architect for Amazon Web Services EMEA SARL, UK.

If you enjoy the game, please leave some feedback in [here](https://feedback.aws.amazon.com/?ea=feijao&fn=Antonio&ln=Feijao).

Thank you,
AF

SilverKey
=========

A implementation of Licence key mechanism to sell my
commercial software.

Why I named it to Silver Key?
-----------------------------

This project is an product at my research stage of
encroyption and certification protocol. Some commercial
software author sell his product by relese an licence key to
identify certain custome. And I already learned a few
knowlege of how digital certification works? So I guess I
should implemant my ways of License key mechanism.

I named this project as Silver Key, because it stands for
wealth and noble. I wish I can sell my product by generate
an silver key to every customer. That's exciting, huh.

Now, talking some Physics, following information from Elements 
period table.

Sliver's general properties:

| Name                   | Silver                     |
| symbol                 | Ag                         |
| number                 | 47                         |
| Element category       | transition metal           |
| Group                  | 11                         |
| period                 | 5                          |
| block                  | d                          |
| Standard Atomic Weight | 107.8682                   |
| Electron configuration | [Kr]4d^10 5s^1 2 8 18 18 1 |
| Phase                  | Solid                      |
| Density                | 10.49 g/cm^3               |
| Melting point          | 1234.93K                   |


How Silver Key(or Licence key) works?
-------------------------------------

In this section, I should illustrate an step by step manual
to describe hwo Silver key works in his way.

1. The potential customer contact with my selling
machine(maybe an websit), regist an accout, and post his
identity information, like his nickname, email address.

2. My sale machine wait the customer to pay the bill, after
confirmed the bill, then it generate a Silver key according
his identify information, store this key into customer's
account, maybe it send an email to customer by attaching the
Silver Key.

3. Customer got the Silver Key. He download the commercial
software, and install the software properly by input his
Silver Key.

4. Customer can enjoy that software now.

Silver key should based on public/private key encryption algorithm.
First, I should generate a pair of pub/priv keys, the public key
should be contained in my commercial software. I should keep 
the private key as secret.

The sale machine first generate a hash string according to 
the identity information(nickname, email address), then
use private key to encrypt the hash string to get ciphertext.
I guess the Silver key is append the ciphertext to the hash string.

The verification process is as the following:
The customer received the Silver key and input the key into software,
the commercial software decrypt the ciphertext by the public key 
which stored inside, and then compare the decryption string with the hash
string.

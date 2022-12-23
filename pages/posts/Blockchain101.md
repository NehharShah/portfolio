---
title: Blockchain 101
date: 2022/11/01
description: Introduction to Blockchain
tag: Blockchain
author: You
---

# Blockchain 101

If the internet enables connectivity, Blockchain enables trust and transparency.

Blockchain represents a distributed ledger that records transactions between two entities in a verifiable and permanent way through the use of cryptography. Herein it is based on Cryptography and Human Logic.

Blockchain is a program that holds conditions and describes how to improve respective conditions according to inputs that are received. These inputs are called transactions. A blockchain architecture has the following components:

1. Cryptography

2. P2P Network

3. Consensus Mechanism

4. Ledger

5. Validity Rules

Rules to transfer information within the digital world are: 

1. Authentic Identification

2. Non-repudiation

3. Integrity

4. Confidentiality

What is cryptography and why is it important for a blockchain let's look into it !!

## Cryptography
Cryptography is communication in the presence of adversaries. 

In Greek, the word Cryptography (Kportwy panon) means hidden writing.

Cryptography has been used since time immemorial by various parties interested in hiding their messages from adversaries and preventing adversaries from forging a message purportedly coming from the original sender.

Until the middle of the 20th century, all cryptography relied on the symmetric key paradigm. To get the message at the end, the sender and receiver must own the same secret key. In the 1970s, several groups of researchers achieved a remarkable breakthrough and discovered asymmetric key cryptography. Now, a sender can use the receiver's public key, readily available to all, to encrypt the message, while the receiver can use his/her secret (or private) key to decrypt it. Conversely, the sender can use his/her secret key to sign a message, which anyone can verify by applying his/her public key.

## Encryption
Encryption is a codification of an input. Information demands that only when the applicable key is used, the content can be deciphered. Encryption happens when the sender sends input and decryption happens only at the receiver end.

There are two types of encryption 

1. Symmetric Key Encryption

2. Asymmetric Key Encryption

Blockchain technology mostly uses an Asymmetric Key Encryption tool. Asymmetric uses two interrelated keys. One key is a Public Key and the other is a Private Key. The public key is used for encryption and the private key is for decryption. 

1. Public Key: The sender and receiver have access and it is shared amongst the shareholders.

2. Private Key: It keeps confidential details for the owner. It is impossible to find the pairing of the private key that is used for the public key addition.

## Hashing
Every blockchain network uses hashing to provide Data Integrity. In Blockchain Networks, Public Keys are useful in creating a secure reference about the identity of users or entities. Secured references include "who owns what" and "who is who" in the peer-to-peer network. This identity is more important in Public Blockchains. 

1. Hashing in Cryptocurrency networks is used for the following purposes: 

2. Encoding the Wallet address 

3. Encoding the Wallet transactions 

4. Verifying the wallet balances 

## Proof of Work 

Hashing techniques are used in creating blocks. They use the Secure Hashing Algorithm (SHA) with 256 - a bit key length. SHA generates a fixed-length hash code to variable-length input from the user. The strength of the hash function is unidirectional i.e. hash output ‘h’ can be produced but the input for h cannot be reconstructed. This powerful feature makes SHA-256 an ideal choice for use in Blockchain Technology. New algorithms like Zero-Knowledge Proof and Ring Signatures, are also being tried for Privacy-preserving functionality in Blockchain through Layer 2 network platforms.

### Properties:
1. Infeasible to find Private keys from Public keys.

2. All valid signatures verify.

3. Signatures are impossible to forge.

4. If the Public Key is forgotten or removed, it can be restored by the Private Key.

### Keccak-256:
1. Keccak256 is a cryptographic function built into solidity smart contract implementation. 

2. This function takes in any amount of input and converts it to a unique 32-byte hash. 

3. The sample contract below takes a text value, a number, and an Ethereum address and converts it to a unique 32-byte hash using Keccak 256.

4. It nevertheless can also be used for authentication, (authenticated) encryption, and pseudo-random number generation.

### Resources:
1. Bitcoin Whitepaper: https://bitcoin.org/bitcoin.pdf

2. Ethereum Whitepaper: https://ethereum.org/en/whitepaper/

In the next article, we will be deep diving into the topics of blockchain.

I would be pleased to have a conversation with anyone interested to know more about blockchain.

Contact: nehhartechnologist@gmail.com
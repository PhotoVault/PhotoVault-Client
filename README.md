# PhotoVault-Client
## Overview
Client code for PhotoVault, a FLOSS alternative to SnapChat which uses PGP for encryption.
## Philosophy
When dealing with potentially personal information, user privacy is of the utmost importance. With proprietary messaging systems, it's impossible to know how your data is being used. By using completely open server and app technology, one can be certain that their data isn't being used commercially or for unethical purposes. In addition, it allows users to be confident that their data is being treated securely using up to date encryption methods that prevent even the server from reading the contents of messages.
# Core Client functionality
* Handle logging in to server
* Take pictures and encrypt them using a public key retrieved from the server
* Receive images from the server and decrypt them using a public key
* Automatically destroy images after a period of time (ala SnapChat)
* Generate private/public keypair
## Potential Client features
* Image filters
* Secure messaging using text chat
## TODO
Basically everything
## Disclaimer
This is my first time doing Android App Development. There will certainly be things which are done in a sub-par way. I am 100% open to suggestions - either open an issue or a a PR if you feel like fixing it yourself and I'll be more than happy to take advice.

cryptolexy
==========

The project's aim is to enable encryption for all the words you write in order to communicate with others.

First things first: we need to get the requirements written down. 

# Why hide things?

If we were not upset by the government knowing what we do there would not be so many articles and buzz about the matter. I believe it is wrong for the government to find out so much and I am not alone.

# What can not be hidden

We have no control over infrastructure. Most people will not be able to conceal when they go online and where it happened. Neither will mobile communication be concealable. Not who you call, for how long, when you did it and where you were when you did.

There are many other things I am sure. 

# What can be hidden

But you can hide the content of your communication and I think we all should. Because until we all do, communications will be wide open. Every time someone replies unencrypted, the whole history will be uncovered.

First objectives are

* eMail
* short messages

In a second step maybe we could hide

* spoken communication
* video communication

# requirements

## Infrastructure

In order to encrypt and decrypt information the only way I know is by sharing a public key with the world and keeping a private key private. Hence the need for a key sharing infrastructure.

### sharing the public keys

That is the easy part. A server who knows to serve the right key for the right eMail should do the job.

### keeping the private keys private

That is the difficult part. You can not trust people to keept their private keys secure and they will not trust anyone to keep an eye on them in their stead. Here is the first big question: 

under what conditions would you trust an organization with your private key?

#### propositions

The things I can offer:

* a Switzerland based foundation 
* a system to ensure no human being has ever access to the key
* a system to unlock your private key when you loose your password
* ensure that the password for the certificate is long and secure
* ensure that you don't need to remember your password


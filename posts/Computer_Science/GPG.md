---
title: What is PGP/GPG, why should you use it, and how.
---

This post is primarly for the non-tech saavy, in the hope that they will have a better grasp of what PGP is, but also, perhaps, use it. 
 

### ELI5 - What does PGP stand for and how does it work? 

#### GPG stands for "Pretty Good Privacy". 
... and GPG, or GnuPG (GNU Privacy Guard), is one of the implementations of the PGP standard, and is a strong alternative to the official PGP software.
In other words, GPG is PGP.

#### What is it? 
First, let me tell you what it is *not*. 

Imagine you have a box, and you want to put something private in it. Something that only a few selected people would be allowed to see. If you would want to send that box to someone, you'd probably add a lock to it. But in order for the people you trust to open that box, you'd need to send its key along with it, perhaps by taping it under the box. 

If someone steals the box, it won't be long until they could open and access its content.

PGP fixes this. In this analogy, PGP is a box. Not with one, but two locks; each of which has its own key. The "public key" can only be used to lock the box, and can be given it to anyone that asks for it (mine is [here](https://slim.page/pgp/publickey_contactcs.asc)!). The "private key" can only be used to unlock the box. You must keep that one for yourself. 

If you were to send a private message, you'd tell your friend to get a box with these two locks. Your friend would send you that box along with the public key. You'd put the message in the box, lock it with the public key and send it away. Your friend would then be the only one to be able to open the box, as they are the only one to have the private key.


### Why would you want to use PGP/GPG ? 

First, let me tell you what 'traditional' emails *don't* do.

Traditional emails don't guarantee the sender's identity and can't completely detect whether an email is really sent by the sender it claims to be (heard of phishing emails?). Traditional emails also travel and are stored in plain text.  This means that anyone managing a server or the network can read (and possibly modify) the email. The recipient can't be completely sure the content of the email they receive hasn't been modified along the way. It's quite analogous to sending a postcard by postmail. Any information written on it should be regarded as publicaly accessible, and possibly modified. 

PGP/GPG solves a lot of these issues. It is useful for privacy, security and authenticity. Privacy and security, because you can prevent anyone from accessing content you don't want to share. This doesn't only apply to highly critical businesses, journalists and activists, but also to people like you & I. Authenticity, because when you 'lock' (aka. encrypt) your data with PGP, it digitally signs that information. So, if an email recipient is not sure about the identity of its sender, they can use a digital signature in conjunction with PGP to verify their identity.
 

#### So it's just *pretty good* privacy?

PGP/GPG allows for data encryption and signing, which solve all three issues I mentioned above. However, it doesn’t provide full privacy. Some parts of the message are still public, such as headers (which include information on who sent it, when they sent it, and possibly where did they send it from). 

#### Why doesn't everybody use it? 

I don’t quite know. My take is that most people aren't concerned about their online privacy enough. It's not a feature set by default in any email service I know of, so no one knows about it. Maybe it is perceived as too difficult to use?
However, it’s not really difficult to get started with, and when you are up and running, it is really easy to use.

### How can you install PGP.
check again soon.
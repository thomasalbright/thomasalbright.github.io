---
layout: post
title:  "Protecting sensitive data in Evernote"
date:   2013-03-01 13:01:00
categories: personal-security
---

Today, [Evernote had a minor security breach](http://evernote.com/corp/news/password_reset.php). If you store sensitive data on Evernote (or any other cloud service, for that matter), you should encrypt it *before* storing, in a way that not even somebody at Evernote can see it.

Encrypting Text
---------------

For text, Evernote has built-in support for encryption. It’s done differently in the different Evernote clients, but it is generally pretty simple. On a Mac, you highlight the text you want to encrypt, right-click, select “Encrypt selected text", and follow the prompts.

![Encrypt selected text]({{ site.url }}/assets/evernote-encrypt-text.png)

Afterwards, the text can only be decrypted if you enter the password. Not even somebody working at Evernote can read what it says.

![Encrypted text]({{ site.url }}/assets/evernote-encrypted-text.png)

Encrypting Attached Files
-------------------------

Evernote does not have any built-in support for encrypting attached files, so you need to encrypt them before you put them into Evernote.

This is really easy to do with PDF’s. Most viewers have an option to encrypt (password-protect) a file when you click “Save As". Here are [instructions for how encrypt a PDF](http://adobe.ly/ZVroSc%20) using Adobe Reader. Usually, Evernote’s built-in PDF viewer will let you decrypt the PDF and read it right in Evernote.

However, it can be more complicated to encrypt other file types. There are many tools that can help you do this (OpenSSL & GNUPrivacyGuard are a couple), but they all require you to export your attachment from Evernote in order to actually read it.

Hopefully, Evernote will add support for encrypting/decrypting file attachments someday.

---
title: "LastPass was breached. Are Password Managers safe?"
excerpt_separator: "<!--more-->"
classes: wide
categories:
  - Cybersecurity
tags:
  - Passwords, Cyber Hygiene
---

I've been a proponent of password managers for many years and have constantly been preaching to people that they need to embrace them. Obviously the question of keeping all your eggs in one basket can cause heart palpitations but the alternatives, such as an excel spreadsheet, give others more comfort.

What are some of the benefits of a password manager beyond just a "Secured Vault"? Here are some additional functions:

- Notification of breached sites where you have an account:
Associating the login site URL with your password in the record also allows some password managers to inform you if those sites have been breached and to change your password immediately.
- Autogeneration of secure passphrases:
This ensures a unique and long password every time.
- Some (most?) now have integrated 2FA TOTP. Now instead of going to Google Authenticator or Authy you have all your codes in one place.
- Web browser modules for auto-input of your password - so you don't have to type it all in.
- It verifies you are at the right website before filling it in:
Acting as an additional set of eyes, if you click on a link (say in a phishing email) password managers can inform you that that is not the genuine site and refuse to fill in your credentials.
- Auto-backup and synchronization of your passwords on multiple devices:
Good password managers can keep an offline copy so you always have access and they enforce strict and hardened encryption algorithms. 

One additional added benefit: If you are on vacation and an account is hacked or you're breached some other you could be faced with a race to lock your other accounts. I have friends that still use written logs (unhackable, yes) however they are located at their home and inaccessible if they are not. Waiting til you get home to login to all your critical accounts while fighting off a hacker isn't a situation you want to be in.

Although the [LastPass breach](https://www.theverge.com/2022/12/28/23529547/lastpass-vault-breach-disclosure-encryption-cybersecurity-rebuttal) was probably the worst thing someone who is skeptical of password managers would fear, the issue is _not_ with the concept of an encrypted password vault but rather the execution of the application by the vendor which failed. Until the death of the password comes about there really is no better way to store credentials _that is user friendly_ and ensuring user friendliness, simplicity is important in ensuring integrity when creating a secure digital footprint. 

## Let's Debunk The Myths
From my reading and discussions with people who are not in cybersecurity the concept of a single file protected under a master password (ie putting all your eggs in one basket) can sound scary. But let's look at the alternatives:
### The Journal
Ok, so maybe it's not a 'little black book' but let's just say it's a piece of paper, a notebook stashed somewhere or in a vault. The pro's are it's the best offline method of recording passwords but let's be honest: are you really going to record long, complex passowrds by handwriting? The most important concept is to 

## Someone is Targeting You, Personally
In email parlance this is called _Spear Phishing_. If you're a C suite executive, high profile public figure, government official or some 007 working for MI6 well, you've got bigger issues and yes, a password manager is still a viable solution with a particular tweek (as referenced before this is something I'd discuss later).

## Why Not Just Use a Password Protected Excel Spreadsheet?
If Excel actually used strong encryption wouldn't everyone just use it? The algorithms implemented by password managers are much more hardened however most password managers are not huge in size. If you were to do the same to encrypt an Excel spreadsheet of say ten thousand lines of multiple columns the time it could take to open (and subsequently save) that spreadsheet would depend upon how fast your computer is - thus it could take a while. Spreadsheet security was never meant to be that hardened.

## Types of Password Managers
The most common type that people are familiar with are the ones in the cloud. This includes 1Password and Bitwarden (The two I would personally recommend as of this writing). However there are _roll-you-own_ which involve standing up your own personal KeePass database and requires a bit more technological know-how. This certainly avoids the problems of the cloud (a la LastPass) but you'll need to be a bit more saavy and willing to devote some time to for care and feeding.
Some password managers are just literally disseminating your own backups or clones of your password database to the devices you want to. I tend to create new accounts at a sad but certainly alarming rate so common updates which requires constant duplication are not for those that wish to be involved in a high-mainteance relationship.

## So Which Ones Do I Recommend?
This is an ever changing list and evolving but for now the ones I've recommended are:

- 1Password
- Bitwarden
- ProtonPass

I think Keypass deserves a mention as it's an open source password manager. Worth looking into if you are ok with having a more hands-on approach to backing up, managing and having a more rudimentary password manager however it is a You Break It You Fix It application and I don't typically recommend it for the non-techie.

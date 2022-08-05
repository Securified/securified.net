---
title: "A Smörgåsbord of Messengers"
date: "2022-08-03"
# description: "Messengers/texting showdown."
# tags: ["signal", "messengers", "texting"]
# ShowToc: true
# cover:
#     image: "poster.png"
#     alt: "messenger-comparison" # alt text
#     relative: false # when using page bundles set this to true
#     hidden: false 
summary: "Privacy and security focused messenger showdown."
---

![Alt text](/img/poster.png)

{{< lead >}}
TL;DR: Signal is the best messenger/calling app. Every other messenger has design flaws that affect user security and privacy. Signal is widely regarded as the most secure and private messenger currently available.
{{< /lead >}}

---

### What Makes a Good Messenger 

A messenger that respects user privacy and is secure by modern standards, needs to meet a few criteria:

1. The messenger should not collect data about it's users beyond what is required to function.

2. [End-to-end encryption](https://www.ibm.com/topics/end-to-end-encryption) needs to be used to ensure messages/calls can not be viewed by anyone other than intended recipients. 

3. The [cryptography](https://www.fortinet.com/resources/cyberglossary/what-is-cryptography) used for the end-to-end encryption needs to be implemented properly using audited, reputable, and verifiable protocols. 

<!-- (see why [privacy matters](https://www.schneier.com/essays/archives/2006/05/the_eternal_value_of.html)). -->
<!-- and [zero-knowledge encryption](https://tresorit.com/blog/zero-knowledge-encryption/) -->
4. Message/call [metadata](https://hls.harvard.edu/dept/its/what-is-metadata/) should be protected and private.  

3. It needs to be secure and private by [*default*]({{< ref "bydefault.md" >}}).

4. Governments should not be able to force those running the messenger to break the encryption or [backdoor](https://en.wikipedia.org/wiki/Backdoor_(computing)) the software. 

1. It should support basic features: messaging, voice calling, video calling, and file sending.

1. Being [open source](https://www.redhat.com/en/topics/open-source/what-is-open-source) is an additional plus.

Many messengers meet some of these criteria, but not all. 

---

### Signal Messenger 

[Signal](https://signal.org) is a cross-platform end-to-end encrypted messaging/calling app. It can be installed on phones and computers and supports instant messaging, voice calls, video calls, sending files, taking/sending pictures/videos snapchat style, and much [more](https://support.signal.org/hc/en-us/sections/360001602792-Signal-Messenger-Features).  


Signal [does not track its users](https://signal.org/legal/#privacy-policy). The only info Signal knows about you is the [*phone number*](https://yewtu.be/watch?v=Nj3YFprqAr8&t=894s) used to register, the account *registration date*, and the *last time you used Signal*.


Signal is open and transparent about what government requests [they receive](https://signal.org/bigbrother/). It is open source and all of its code is freely viewable [here](https://github.com/signalapp). Signal is ran by the 501(c)(3) non-profit [Signal Foundation](https://signalfoundation.org/), and is funded by [donations and grants](https://www.signal.org/donate/). It has been independently [audited](https://eprint.iacr.org/2016/1013.pdf) by third party companies to check for vulnerabilities and to verify trustworthiness.


#### Some of the features Signal has:

- [End-to-end encryption](https://www.ibm.com/topics/end-to-end-encryption): Ensures message/call content can not be viewed by any unintended parties, including the Signal Foundation itself. It uses the audited and reputable [Signal Protocol](https://engineering.mindlinksoft.com/end-to-end-encryption-with-the-signal-protocol/) developed by the Signal Foundation for end-to-end encryption. 

- [Perfect Forward Secrecy](https://www.signal.org/blog/asynchronous-security/): This ensures that if the [encryption key](https://medium.com/codeclan/what-are-encryption-keys-and-how-do-they-work-cc48c3053bd6) of one message is compromised, other messages can not be decrypted and viewed with that same key.

- [Sealed Sender](https://signal.org/blog/sealed-sender/): This is used to conceal [metadata](https://hls.harvard.edu/dept/its/what-is-metadata/). Signal protects metadata better than all other messengers. 

- [Safety Numbers](https://support.signal.org/hc/en-us/articles/360007060632): Used to verify you are communicating with who you think you are. 

- [Private Groups](https://signal.org/blog/signal-private-group-system/): A private group chat/calling system. The Signal Foundation has no record of who is in a group chat/call, the name of the group, or the group avatar. This is in stark contrast to other messengers where all this is viewable by the service.


#### Signal and Phone Numbers 

<!-- Signal is based in the US where privacy laws [are not strong](https://en.wikipedia.org/wiki/Patriot_Act).  -->

Signal requires a phone number for registration and use. This raises a privacy concern for some as anyone you message in Signal can see your phone number. This can be partially solved by using a [burner phone](https://www.howtogeek.com/712588/what-is-a-burner-phone-and-when-should-you-use-one/) or [VoIP](https://www.voip.com/) number when registering with Signal. Signal has said they are working on adding usernames that may replace phone numbers.


{{< alert "circle-info" >}}
Enable registration lock and [set a pin](https://support.signal.org/hc/en-us/articles/360007059792-Registration-Lock) in Signal. This will require a pin to be entered before the same number can be registered with Signal again, helping to prevent your Signal account from getting stolen. 

Due to the secure way Signal has been designed, messages are not backed up or stored on the Signal servers. This means when installing Signal on a different device, you will need to [transfer](https://support.signal.org/hc/en-us/articles/360007059752-Backup-and-Restore-Messages) messages to the new devices.
{{< /alert >}}

<!-- A few recommendations with Signal; In settings, turn off "Generate link previews". This prevents websites from receiving info about you when a link is sent in Signal.
https://therecord.media/fbi-document-shows-what-data-can-be-obtained-from-encrypted-messaging-apps/
See what others have to say about signal
https://www.appsverse.com/blog/why-signal-is-the-best-app-for-private-messaging/
https://restoreprivacy.com/secure-encrypted-messaging-apps/signal/
https://nerdschalk.com/is-signal-the-best-app-for-privacy/
Signal doesnt store messages on servers, only when they are waiting to send them to you -->
---



<!-- https://www.washingtonpost.com/world/national-security/nsa-surveillance-program-reaches-into-the-past-to-retrieve-replay-phone-calls/2014/03/18/226d2646-ade9-11e3-a49e-76adc9210f19_story.html -->

<!-- https://www.securemessagingapps.com/ -->




### Texting/SMS

[SMS](https://en.wikipedia.org/wiki/SMS)/[MMS](https://en.wikipedia.org/wiki/Multimedia_Messaging_Service) (commonly referred to as "texting"), and phone calling is the most common form of communication, but it is neither [secure](https://www.howtogeek.com/709373/why-sms-text-messages-arent-private-or-secure/) nor [private](https://www.usatoday.com/story/tech/columnist/2016/04/16/texting-texts-security-hacking/83118320/).

<!-- The most common form of communication, [SMS](https://en.wikipedia.org/wiki/SMS)/[MMS](https://en.wikipedia.org/wiki/Multimedia_Messaging_Service) (commonly referred to as "texting") and phone calling is neither [secure](https://www.howtogeek.com/709373/why-sms-text-messages-arent-private-or-secure/) nor [private](https://www.usatoday.com/story/tech/columnist/2016/04/16/texting-texts-security-hacking/83118320/). -->


Your [cell carrier](https://en.wikipedia.org/wiki/List_of_United_States_wireless_communications_service_providers) can read your messages/phone calls due to the lack of [end-to-end encryption](https://www.ibm.com/topics/end-to-end-encryption). Some carriers encrypt part of the journey the message/call data takes, but only between the [phone and cell tower](https://www.rokacom.com/are-text-messages-encrypted]). They then decrypt the data at the cell tower and are able to view its content. They [store](https://www.nbcnews.com/technolog/how-long-do-wireless-carriers-keep-your-data-120367) this decrypted message/phone data for varying lengths of time, up to [seven years](https://news.law.fordham.edu/jcfl/2016/06/02/cell-phone-forensics-powerful-tools-wielded-by-federal-investigators/).


{{< alert "circle-info" >}}
Every second your phone is online and connected to a cell tower your cell carrier is [aware of your location](https://www.nytimes.com/2018/05/10/technology/cellphone-tracking-law-enforcement.html) to within [~100 meters](https://www.hgexperts.com/expert-witness-articles/cell-phone-triangulation-the-basics-36172). This valuable location data is [sold](https://www.howtogeek.com/402043/can-anyone-really-track-my-phones-precise-location/) to bounty hunters, advertising agencies, and the government. 
{{< /alert >}}


Texting is especially susceptible to [sim swapping](https://cybersecurityventures.com/sim-swap-fraud-the-latest-battle-in-the-war-for-your-identity/). This is where a cybercriminal gets control of your cellphone number through social engineering. What is social engineering? Cisco [defines it as](https://www.cisco.com/c/en/us/products/security/what-is-social-engineering.html):

> At its core, social engineering is not a cyber attack. Instead, social engineering is all about the psychology of persuasion: It targets the mind like your old school grifter or con man. The aim is to gain the trust of targets, so they lower their guard, and then encourage them into taking unsafe actions such as divulging personal information or clicking on web links or opening attachments that may be malicious. 

Sim swapping attacks can be devastating, leading to [drained bank accounts](https://threatpost.com/sharp-sim-swapping-spike-losses/178358/), stolen tax returns, and identity theft. The FBI Internet Crime Complaint Center received complaints totaling losses of [$68 million](https://www.ic3.gov/Media/Y2022/PSA220208) in 2021 due to sim swapping. These losses are due to many online account using sms for signing-in, multifactor, and/or password resets. Once an attacker has control of your phone number, that can use it receive [password reset links](https://privacypros.io/u2f/sim-swapping/) for these accounts.

Unfortunately there are no good safeguards your can put up to protect from sim swapping. This is why text-based authentication and multifactor should be completely avoided. An account secured with sms MFA is hardly any better than not having any MFA. 

{{< lead >}}
Please, do not use text or phone based sign-in or multifactor authentication to secure any accounts of importance. 
{{< /lead >}}

---

### iMessage

[iMessage](https://support.apple.com/messages) is an instant messenger owned by [Apple](https://www.apple.com/) that supports instant messaging, voice/video calling, and file sending.

The first knock against it is that it is not cross platform, it is only available on Apple devices. It is also closed source, does not have [perfect forward secrecy](https://plzh4x.me/2018/04/07/cryptanalysis-of-the-imessage-protocol/), does not [protect metadata](https://appleinsider.com/articles/16/09/29/apple-acknowledges-tracking-imessage-metadata-and-sharing-it-with-law-enforcement) and shares the metadata they collect with law-enforcement.

While iMessage does have end-to-end encryption, it has been implemented [poorly](https://plzh4x.me/2018/04/07/cryptanalysis-of-the-imessage-protocol/) and is not secure. To make matters worse, if iMessage is being backed up with iCloud (which it is by default), Apple is able to see the backed-up messages. This is because iCloud backups are not [end-to-end encrypted](https://www.howtogeek.com/710509/apples-imessage-is-secure...-unless-you-have-icloud-enabled/). The reason iCloud backup does not have end-to-end encryption? Because the [fbi complained](https://www.reuters.com/article/us-apple-fbi-icloud-exclusive/exclusive-apple-dropped-plan-for-encrypting-backups-after-fbi-complained-sources-idUSKBN1ZK1CT) when Apple was going to enable it. :unamused:

Apple has tried backdooring iMessage by adding a client side [scanning service](https://www.schneier.com/blog/archives/2021/08/apple-adds-a-backdoor-to-imesssage-and-icloud-storage.html) to iMessage that would scan messages for "bad" material and report it. Although not currently implemented, there has been talk again about adding it. 

While iMessage is convenient on apple devices, it should not be used due to its many downsides, poor encryption and lack of cross-platform support.  

---

### Whatsapp

[Whatsapp](https://www.whatsapp.com/) is a instant messenger owned by the data harvester/ad tech company Meta (Facebook's new parent company). It supports instant messaging, voice/video calling, and file sending. 

Although Whatsapp has end-to-end encryption and is not able to view message contents, metadata is [tracked](https://www.getsession.org/blog/whatsapp-privacy-policy) aggressively. Their [privacy policy](https://www.whatsapp.com/legal/privacy-policy/?lang=en) shows that Whatsapp has been incorporated into the massive data harvesting operation of their parent company, Facebook.

Here is just *some* of the data they say they [collect](https://www.whatsapp.com/legal/privacy-policy/?lang=en)
from their privacy policy:

> ..we collect information about your activity on our Services..this includes information about your activity..log files, and diagnostic, crash, website, and performance logs and reports..when you registered to use our Services; the features you use like our messaging, calling, Status, groups (including group name, group picture, group description), payments or business features; profile photo, "about" information; whether you are online, when you last used our Services (your "last seen"); and when you last updated your "about" information..device and connection-specific information when you install, access, or use our Services. This includes information such as hardware model, operating system information, battery level, signal strength, app version, browser information, mobile network, connection information (including phone number, mobile operator or ISP), language and time zone, IP address, device operations information, and identifiers..precise location information from your device.. [and] ..cookies..

Facebook markets Whatsapp as a privacy messenger, but after looking at their privacy policy, it clearly is not.

Further, a propublica [article](https://www.propublica.org/article/how-facebook-undermines-privacy-protections-for-its-2-billion-whatsapp-users) talks about the monitoring and censorship that Whatsapp does on messages:

> WhatsApp has more than 1,000 contract workers.. [who] ..use special Facebook software to sift through millions of private messages, images and videos. They pass judgment on whatever flashes on their screen..
>
>The workers have access to only a subset of WhatsApp messages — those flagged by users and automatically forwarded to the company as possibly abusive. The review is one element in a broader monitoring operation in which the company also reviews material that is not encrypted, including data about the sender and their account.

[$19 billion](https://www.investopedia.com/articles/personal-finance/040915/how-whatsapp-makes-money.asp) is how much Facebook payed for Whatsapp in 2014. Yet, Whatsapp is free to download and does not have ads. In order to make Whatsapp profitable, Facebook collects data about its over 2 billion users and sells ads about the data it collects.  

Whatsapp, marketed as a privacy focused messenger is not private in the slightest. It heavily tracks its users and is invaluable to Facebook data harvesting. Whatsapp should be avoided.

---

### Telegram

[Telegram](https://telegram.org/) is a cross-platform instant messenger based in [Dubai](https://telegram.org/faq#q-where-is-telegram-based), United Arab Emirates. It supports instant messaging, voice/video calling, and file sending.

Telegram does not use end-to-end encryption by [default](https://telegram.org/faq#q-why-not-just-make-all-chats-secret), therefore the Telegram servers, and anyone able to capture messages, are able to view the message contents. There is a feature called [Secret Chats](https://telegram.org/faq#secret-chats) that enables end-to-end encryption, but only for the chat it was enabled for. The encryption used is their own custom un-audited [protocol](https://core.telegram.org/mtproto) that has had major flaws in the past, and many cryptographers call ["weird"](https://buttondown.email/cryptography-dispatches/archive/cryptography-dispatches-the-most-backdoor-looking/).  

Telegram collects metadata about their users according to their [privacy policy](https://telegram.org/privacy#5-2-safety-and-security):

> ..we may collect metadata such as your IP address, devices and Telegram apps you've used, history of username changes, etc. If collected, this metadata can be kept for 12 months maximum. 

Like Signal, a phone number is used for registering and signing in. Unlike Signal, the server code is [not](https://telegram.org/faq#q-can-i-get-telegram-39s-server-side-code) open source.

Telegram is not recommended due to end-to-end encryption not being enabled by default, its metadata collection and the un-audited custom protocol they use.

---

### Session

[Session](https://getsession.org/) is an up and coming messenger that has many promising features, but is not yet ready for general use. 

A few things currently wrong with it are that it doesn't have perfect forward secrecy, message delivery is slow and unreliable, it is based in Australia where encryption/privacy laws are bad, and it is based on their own weird [cryptocurrency/blockchain](https://oxen.io/) and [onion network](https://lokinet.org/).

<!-- --- -->

<!-- ## *Coming Soon* -->

<!-- ### Facebook Messenger -->
<!-- Add links to facebook being evil 
Facebook is a terrible company and should be avoided. -->
<!-- privacy policy says they track -->

<!-- ### Snapchat -->
<!-- stores all content -->

<!-- ### WeChat -->
<!-- chinese owned and operated.
All data is visible to them -->

<!-- ### Threema -->
<!-- [Threema](https://threema.ch/en/)

Is not free -->

<!-- ### Wickr -->
<!-- [Wickr](https://wickr.com/)

Owned by amazon  -->

<!-- ### Wire -->
<!-- [Wire](https://wire.com) does not protect metadata. It keeps a [list](https://www.vice.com/en_us/article/gvzw5x/secure-messaging-app-wire-stores-everyone-youve-ever-contacted-in-plain-text) of everyone you have contacted in an unencrypted document.  -->

<!-- ### Element/Matrix -->
 <!-- Bad metadata protection
Encryption needs to be enabled 
decentralized  -->

---

### Conclusion

Not all messengers are created equal; Many should be avoided outright. Some more messengers to not use due to bad security and privacy are Facebook Messenger (even worse security than Whatsapp), Snapchat (bad privacy, snaps not actually deleted, lacking encryption), WeChat (Chinese have access to everything sent) and Marco Polo (lacking encryption, share personal data with third parties). 

Signal is different. It has been designed from the ground up taking great care to protect user security and privacy through technological means. While not perfect, it is the current best option for a private and secure messenger. 
<!-- Many others have come to the same conclusion. -->

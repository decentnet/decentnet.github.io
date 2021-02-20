# DecentNet

## Anonymity networks

- [Tor](https://www.torproject.org/)
- [I2P](https://geti2p.net/)

Anonymity networks hide your IP address, letting you access the internet anonymously, securely, uncensored.
On Tor, exit nodes let you access the normal internet (clearnet). Both on Tor and I2P you can access hidden services (onions, eepsites) that are only accessible through these anonymity networks. This is preferable to clearnet sites because of increased security. Host your existing website on Tor/I2P as well!
Tor uses volunteer routers to route your traffic through multiple hops before you reach your destination, while on I2P everyone is a router. This makes I2P suitable for file sharing. Torrents inside I2P are only accessible through I2P; I2P has its own torrent trackers and communities. You could run decentralized nodes inside I2P for technologies that require a lot of traffic (cryptocurrency full nodes, IPFS).
These networks are a free, open source alternatives to VPNs; Tor lets you access the clearnet, I2P allows you filesharing.
Anonymity networks are the pillars of internet freedom. Many of the decentralized technologies lack privacy, leak your IP address to other peers. You can combine anonymity networks with decentralized technologies to access them anonymously. Host nodes on these networks!

- Browsers: [Tor Browser](https://www.torproject.org/), [Firefox](https://firefox.com/) [with privacy add-ons, settings](https://www.privacytools.io/browsers/#addons)
- Operating systems: [Tails](https://tails.boum.org/), [Whonix](https://www.whonix.org/), [more](https://www.privacytools.io/operating-systems/#os)

## File sharing, hosting, other networks

- [Dat/Hypercore, Beaker Browser](https://beakerbrowser.com/)
- [IPFS](https://ipfs.io/)

With Dat and IPFS you can share files, websites in a peer-to-peer network similar to torrent. You can share your files with a few clicks/commands, others can download the files from you, they can pin your files so others can access those files from them. Pinning services can host your files so they are always available.
On IPFS, gateways ensure connection to IPFS files/websites even from the clearnet.
You can share static websites and blogs on IPFS and Dat for free. If your website gets popular, it may remain in circulation forever.

-Static website generators: [Jekyll](https://jekyllrb.com/), [Hugo](https://gohugo.io/), many others
- Worthy mentions: [BitTorrent](https://en.wikipedia.org/wiki/Bittorrent), [IOTA](https://github.com/iotaledger), [Zeronet](https://zeronet.io/), [Freenet](https://freenetproject.org/), [Yggdrasil](https://yggdrasil-network.github.io/), [Cjdns](https://github.com/cjdelisle/cjdns/), [ENS](https://ens.domains/), WWW, [more](https://www.privacytools.io/software/networks/)

## Social networks

- [Scuttlebutt, SSB, Manyverse](https://scuttlebutt.nz/)

Scuttlebutt is a peer-to-peer social network.
It works even if you’re offline. You store your and your friends’ data on your device, and share it to other peers when you meet face-to-face via a common Wi-Fi network or Bluetooth, or optionally on pub servers. You can browse the feed when you’re offline, you can post and comment, and it syncs when you next meet someone with Scuttlebutt, or when you’re online. If your friend has data about others, he shares that data with you.
It works even in rural places that don’t have internet.
When you first open the program, it creates a public and a private key for you. You are identified by your public key (and by your non-unique name). You can’t migrate your keys right now, at least not easily.
It being peer-to-peer means you can never delete the data you shared, so be careful what you post.

- [Pleroma](https://pleroma.social/)
- Mastodon

Mastodon is the biggest decentralized social network out there. Pleroma is the lightweight version of Mastodon. They are alternatives to Twitter.
Distributed instances share users’ data amongst themselves. Users can seamlessly communicate between instances, they can follow each other, reply to each others’ tweets.
The Mastodon website and most popular instances are heavily censored, don’t trust them. The website doesn’t list free-speech Mastodon instances. Censored instances block free-speech instances on instance-level, which means no one can access these instances and their users from them. They heavily censor their own users, and block everyone who disagree with them.
Mastodon is open source and federated, which means you can still use it, but you must search for free-speech instances, and study their about/rules pages before you sign up. Or host your own. If you’re annoyed by users, block them yourself, don’t trust SJW admins/moderators to censor everything.

- Other Fediverse/ActivityPub-compatible networks: [GNU Social](https://gnusocial.network/), [Friendica](https://friendi.ca/), [Diaspora](https://diasporafoundation.org/), [more](https://fediverse.party/), [more](https://www.privacytools.io/providers/social-networks/)
- Worthy mentions: [Aether](https://getaether.net/)
- [PeerTube](https://joinpeertube.org/)
- [LBRY](https://lbry.com/)

Decentralized video-sharing platforms.
PeerTube uses the ActivityPub system to federate instances around the world.
LBRY is still in beta, right now it’s pretty centralized, but everyone can host instances. LBRY gives users the ability to donate cryptocurrency to channels, and channels to monetize their content.
Both platforms let users seed videos they are watching or they downloaded, similar to torrent.

- Worthy mentions: [BitChute](https://www.bitchute.com/), [DTube](https://about.d.tube/)

## Communication, messaging, encryption

- E-mail

E-mail is a pretty flawed system. Most people use it unencrypted. It’s bad for privacy. In theory it’s possible for attackers to intercept e-mails in plain text. Headers are unencrypted. It is pretty centralized, Gmail controls most user e-mails. It’s hardly free and it’s hard to sign up with providers; big providers steal all your data and require de-anonymization for sign up, privacy providers limit free users, or require payment.
It has a good concept though. It’s asynchronous, popular, serious, well supported, easy to use. E-mail addresses last forever, or at least for a long time. Websites use it for identification and communication with their users.
Finding a free, decentralized alternative to e-mail is important for internet freedom.

- [Bitmessage](https://github.com/Bitmessage/PyBitmessage)
- [I2P-Bote](https://github.com/i2p/i2p.i2p-bote)

Bitmessage and I2P-Bote are decentralized, serverless, peer-to-peer alternatives to e-mail. They are asynchronous, encrypted, all messages are stored and distributed by all peers, and only the recipient can decrypt their messages. There are no servers for which you have to pay with money or your data, you don’t have to sign up with nor trust providers. They are run by the community, they work like torrent.
I2P-Bote uses the I2P anonymity network by default, Bitmessage can work through Tor or clearnet.

- [OpenPGP, GnuPG](https://gnupg.org/)

PGP lets you create a public-private keypair. You give out your public key, your private key is a secret. Others who know your public key can encrypt data so only you can decrypt it.
PGP is a good way to mitigate some of the issues with e-mail. You encrypt the messages with the recipient’s public key, and even if the message gets caught or the e-mail provider gets compromised, they can’t decrypt your e-mails.
PGP is pretty popular. It’s easy to use. A lot of software support it, there are a lot of libraries that implement it. On the darknet, you should encrypt all your messages, but even on clearnet you should use it for normal messaging to dodge mass surveillance. OpenPGP and GPG are the open source implementations of PGP.
You may not want to type your real life name and e-mail address when creating a keypair.
PGP let’s you sign text/files with your private key, so everyone knows that they belonged to you. It’s really popular among software developers to sign software releases so users know the binaries came from the developers and haven’t been tempered with. You should always verify software you install, keep developers’ public keys handy on your keyring.
PGP is a good way to identify yourself. They may take away your access to your e-mail address, but they can’t take away your private keys. Websites should identify their users by PGP, at least as a backup for e-mail.

- [VeraCrypt](https://veracrypt.fr/)

VeraCrypt is free software to encrypt files inside a volume or whole partitions with a strong password or pass-phrase. You should encrypt everything.

- Other useful tools: [KeePass](https://keepass.info/), [BleachBit](https://www.bleachbit.org/), [DBAN](https://en.wikipedia.org/wiki/Darik's_Boot_and_Nuke), [andOTP](https://f-droid.org/en/packages/org.shadowice.flocke.andotp/)

- [IRC](https://en.wikipedia.org/wiki/Internet_Relay_Chat)
- [XMPP/Jabber](https://xmpp.org/)

IRC is the one of the oldest chat protocols out there. It’s still pretty popular and supported. Simple, easy to use. You chat with many people in chat rooms. You can’t receive messages while you’re offline though.
Some IRC clients may leak data about you, so be careful what you use. [HexChat](https://hexchat.github.io/) is a recommended client.
IRC servers are not federated, but there are many different servers.
XMPP is another old protocol. A lot of support, libraries, clients; many software use it. XMPP is federated. Extensions make it suitable for different needs. The [OTR](https://otr.cypherpunks.ca/) and [OMEMO](https://omemo.top/) extensions let you encrypt your messages; use them for secure communication.
IRC and XMPP are popular on the darknet; anonymity networks hide your IP from the servers, so it’s a good way to connect.

- XMPP clients: [Gajim](https://gajim.org/), [Pidgin](https://pidgin.im/), [Converse.js](https://omemo.top/#Converse.js)
- [Matrix, Riot.im/Element](https://element.io/)

Newer decentralized, federated chat protocol. FOSS alternative to Discord. Popular, has big communities with big chat rooms. You can receive messages while offline, you can see room history. Suitable for private messaging too. You can use the built-in end-to-end encryption for private messages and private group chats.

- Other messaging applications: [Briar](https://briarproject.org/), [Retroshare](https://retroshare.cc/), [Signal](https://signal.org/), [more](https://www.privacytools.io/software/real-time-communication/)
- Worthy mentions: [OpenBazaar](https://en.wikipedia.org/wiki/OpenBazaar)

Alternative physical networks

- Mesh networks

If you are cut off from the internet, there’s still a chance to connect with others. You can connect Wi-Fi routers and devices to form a mesh network where each node relays packets. You can use old, inexpensive Wi-Fi routers, and you can build or buy antennas that work for longer ranges.

- Worthy mentions: [Hyperboria](https://hyperboria.net/), [Althea](https://althea.net/), [LibreRouter](https://librerouter.org/), [LibreMesh](https://libremesh.org/), [SNET](https://en.wikipedia.org/wiki/Internet_in_Cuba#SNET), [NanoStation](https://www.ui.com/airmax/nanostationm/), [Freifunk](https://en.wikipedia.org/wiki/Freifunk)
- [LoRa, LoRaWAN](https://en.wikipedia.org/wiki/LoRa)

LoRa is a long range wireless network technology which uses free radio frequencies. It’s longer range than Wi-Fi, usually kilometers. Low power, low cost, has support for Arduino, Raspberry Pi and the like. Good for DIY IoT projects. Has really low bandwidth though, and it’s further regulated in Europe.

[Meshtastic](https://www.meshtastic.org/) is a mesh of small LoRa devices that connect to your phone. You can send text messages to your friends without connecting to mobile service providers that can monitor your location and communications. Could be a good way to avoid surveillance, as an “underground” communication channel, or if you want to connect with friends even if you don’t have an internet connection. The project is still in beta, might not be secure, and if you want to use it you might want to use better encryption and turn off location.

[DisasterRadio](https://disaster.radio/) is LoRa mesh focused on emergency communications.

[Ham radio](https://en.wikipedia.org/wiki/Amateur_radio)

Most radio frequencies are regulated, you can only use them with license, which means de-anonymization. Usually used to transmit audio, but there are projects to transmit data, like e-mail ([Winlink](https://www.winlink.org/)). Can have really long ranges, some setups link over continents, or connect to space stations.

- [Sneakernet](https://en.wikipedia.org/wiki/Sneakernet)

You don’t have internet, or it’s really slow, you don’t have mesh: you get a hard drive or some other media, fill it with data and pass it around with friends. You copy the hard drive, you distribute it. In Cuba, [“El Paquete Semanal”](https://en.wikipedia.org/wiki/El_Paquete_Semanal) is a one terabyte package containing pirated content distributed weekly.

## Cryptocurrencies

- [Bitcoin](https://en.wikipedia.org/wiki/Bitcoin)
- [Ethereum](https://www.ethereum.org/)
- [IOTA](https://www.iota.org/)
- [Nano currency/RaiBlocks](https://nano.org/)
- [Monero](https://getmonero.org/)
- [Zcash](https://z.cash/)
- many others

Cryptocurrency is money that is not controlled by governments. You can do transactions online in a decentralized way.
You control everything about your money, your private keys are the only way you can access your money, so keep them safe, keep them private, back them up multiple times, on multiple location, on paper, [on steel](http://jesblogfnk2boep4.onion/stories/diy-cryptosteel-capsule.html). There are many scams, be careful with your money.
It can be anonymous, although governments passed regulations to de-anonymize all its users. You should use decentralized exchanges that don’t enforce KYC, that don’t control your money, use cryptocurrency ATMs that don’t require KYC, use privacy coins, use coin mixers, track what data is associated with which addresses, and never give out your real life information. Centralized exchanges either force KYC on sign-up, or when they encounter “suspicious” activities, so your money’s never safe. They steal your money if they think at any point it was associated with whatever they think is “criminal activity”.
Cryptocurrency should be decentralized, anonym, private, fungible, not controlled by anyone, not regulated, FOSS, secure; code is law. You should try to avoid technologies that violate these principles.
Bitcoin is the first, the biggest.
Ethereum lets you create decentralized applications with code that runs on the blockchain. Be careful, Ethereum Foundation did steal money from so-called “hackers”.
IOTA and Nano currency are fee-less.
IOTA lets your decentralized applications store data and communicate through the Tangle. They have libraries for JavaScript (and other languages), so you can access the Tangle right in the browser. Be careful, IOTA is in beta, is centralized; its wallet was recently compromised and IOTA Foundation is planning to sacrifice fungibility and de-anonymize victims.
Normally with cryptocurrencies the transactions are public, which makes it hard to stay private. Privacy coins like Monero and Zcash have private transactions that hide who sent money to whom, making them private, anonym, fungible. Monero is private by default.

## Resources

- [PrivacyTools](https://www.privacytools.io/)
- [Redecentralize.org’s list](https://github.com/redecentralize/alternative-internet)

Donate

Liked the website, want to support me? [Send donations to my cryptocurrency addresses](https://decentnet.github.io/about.html#donate).

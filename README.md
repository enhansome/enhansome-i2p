# Awesome I2P with stars

> A curated list of awesome I2P implementations, libraries, resources, projects, and shiny things.
> Inspired by [awesome-tor](https://github.com/ajvb/awesome-tor) ⭐ 509 | 🐛 3 | 📅 2023-09-03 and [awesome-cpp](https://github.com/fffaraz/awesome-cpp) ⭐ 73,056 | 🐛 310 | 📅 2026-08-22 and other [Awesome Lists](https://github.com/topics/awesome).
>
> I2P is an anonymous overlay network - a network within a network. It is intended to protect communication from dragnet surveillance and monitoring by third parties such as ISP's.
>
> I2P is used by many people who care about their privacy: activists, oppressed people, journalists and whistleblowers, as well as the average person.
>
> Check [status page](STATUSES.md) to know current projects state.

## Contents

* [Implementations](#implementations)
  * [I2P (Java)](#i2p)
  * [I2Pd (C++)](#i2pd)
  * [Unfinished](#unfinished)
* [Projects using I2P](#projects-using-i2p)
  * [Automation](#automation)
  * [Cryptocurrencies](#cryptocurrencies)
  * [Docker](#docker)
  * [Email](#email)
  * [Forum / Blog](#forum--blog)
  * [Files / Sharing](#files--sharing)
  * [Messaging](#messaging)
  * [Tools](#tools)
  * [Torrents](#torrents)
  * [Web](#web)
* [Libraries](#libraries)
  * [BOB](#bob)
  * [SAM](#sam)
  * [Other](#other)
* [Resources](#resources)
  * [Documentation](#documentation)
  * [Guides](#guides)
  * [Publications](#publications)
  * [Websites](#websites)
* [Contributing](#contributing)

## Implementations

### I2P

* [I2P](https://github.com/i2p/i2p.i2p) ⭐ 2,690 | 🐛 16 | 🌐 Java | 📅 2026-08-31 - The first implementation. Written in Java. Android release of the I2P router: [Google Play](https://play.google.com/store/apps/details?id=net.i2p.android), [F-Droid](https://f-droid.org/packages/net.i2p.android.router/).
* [I2P+](https://gitlab.com/i2pplus/I2P.Plus/) - I2P+ is a soft-fork of the Java I2P Anonymizing Network Layer.

### I2Pd

* [I2Pd](https://github.com/PurpleI2P/i2pd) ⭐ 4,185 | 🐛 162 | 🌐 C++ | 📅 2026-08-31 - A C++ implementation of a I2P router. Android release of the I2Pd router: [F-Droid](https://f-droid.org/packages/org.purplei2p.i2pd/).
* [Kovri](https://gitlab.com/kovri-project/kovri) - The Kovri I2P Router Project, a fork of I2Pd by the Monero project.

### Unfinished

* [ire](https://github.com/str4d/ire) ⭐ 159 | 🐛 19 | 🌐 Rust | 📅 2023-02-04 - I2P router implementation in Rust.
* [go-i2p](https://github.com/hkparker/go-i2p) ⭐ 116 | 🐛 12 | 🌐 Go | 📅 2023-03-06 - A pure Go implementation of the I2P router.
* [i2p-cs](https://github.com/PeterZander/i2p-cs) ⭐ 36 | 🐛 3 | 🌐 C# | 📅 2023-05-30 - I2P router in C#.
* [ri2p](https://github.com/ChristopherBilg/ri2p) ⭐ 20 | 🐛 4 | 🌐 Rust | 📅 2023-08-21 - Rust implementation of the i2p client/server/router protocols.
* [i2pcpp](https://github.com/majestrate/i2pcpp) ⭐ 19 | 🐛 0 | 🌐 C++ | 📅 2015-02-21 - I2P C++ implementation.
* [i2pd-rs](https://github.com/jacklund/i2pd-rs) ⭐ 14 | 🐛 0 | 🌐 Rust | 📅 2017-04-07 - I2P Daemon written in Rust.
* [i2p-lite](https://github.com/i2p-lite/i2p-lite) ⭐ 11 | 🐛 0 | 🌐 C | 📅 2017-11-14 - I2P router implementation in C11.

## Projects using I2P

### Automation

* [anonym8](https://github.com/HiroshiManRise/anonym8) ⭐ 324 | 🐛 21 | 🌐 Shell | 📅 2022-09-26 - Sets Transparent proxy tunnel through Tor, I2P, Privoxy, Polipo and modify DNS; Include Anonymizing Relay Monitor (arm), macchanger and wipe (Cleans ram/cache & swap-space) features, ID spoofing has never been so easy.
* [i2pbootstrap](https://github.com/TheTinHat/i2pbootstrap) ⭐ 19 | 🐛 1 | 🌐 Shell | 📅 2018-03-22 - I2P Bootstrap script to automate much of the router setup process on remote servers.
* [cookbook-nginx-i2p](https://github.com/i2phosts/cookbook-nginx-i2p) ⭐ 3 | 🐛 0 | 🌐 Ruby | 📅 2016-12-21 - This Chef cookbook contains i2p-specifig config for logging i2p-desthashes. For ruby.
* [i2phosts](https://github.com/mikalv/i2phosts) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2017-03-07 - Automatic I2P Hosts synchronization I2P to Internet.

### Cryptocurrencies

* [bitcoin](https://github.com/bitcoin/bitcoin) ⭐ 90,057 | 🐛 714 | 🌐 C++ | 📅 2026-08-31 - Bitcoin Core. More info [here](https://github.com/bitcoin/bitcoin/blob/master/doc/i2p.md) ⭐ 90,057 | 🐛 714 | 🌐 C++ | 📅 2026-08-31.
* [monero](https://github.com/monero-project/monero) ⭐ 10,811 | 🐛 697 | 🌐 C++ | 📅 2026-08-28 - Monero: the secure, private, untraceable cryptocurrency. It is open-source and accessible to all. With Monero, you are your own bank. Only you control and are responsible for your funds. Your accounts and transactions are kept private from prying eyes.
* [GOSTCoin](https://github.com/GOSTSec/gostcoin) ⭐ 49 | 🐛 28 | 🌐 C++ | 📅 2026-07-12 - GOSTCoin (GST) is a digital currency based on blockchain technology. It allows instant payments worldwide with focus on privacy and security of its users.
* [anoncoin](https://github.com/Anoncoin/anoncoin) ⭐ 42 | 🐛 15 | 🌐 C++ | 📅 2020-12-24 - Anoncoin (ANC) is a peer-to-peer digital cryptocurrency that focuses on privacy and anonymity for its users. Created in June 2013, it is the first and only currency to have built-in support for both the I2P darknet and Tor network that conceal the IP address of the user.

### Docker

* [i2pd-docker](https://github.com/hexaedron/i2pd-docker) ⭐ 19 | 🐛 0 | 🌐 Shell | 📅 2017-11-20 - Dockerfile and some scripts to run I2Pd in a container.
* [i2p-docker](https://github.com/hkparker/i2p-docker) ⭐ 17 | 🐛 3 | 🌐 Dockerfile | 📅 2021-01-30 - Java I2P router in Docker.
* [i2pd](https://ghcr.io/purplei2p/i2pd) - Official I2Pd docker image.
* [meeh/i2p.i2p](https://hub.docker.com/r/meeh/i2p.i2p/) - Prebuilt I2P docker image.
* [meeh/i2pd](https://hub.docker.com/r/meeh/i2pd/) - Prebuilt I2Pd docker image.

### Email

* [i2p.i2p-bote](https://github.com/i2p/i2p.i2p-bote) ⚠️ Archived - I2P-Bote is a plugin for I2P that allows users to send and receive emails while preserving privacy. It does not need a mail server because emails are stored in a distributed hash table. They are automatically encrypted and digitally signed, which ensures no one but the intended recipient can read the email, and third parties cannot forge them.
* [bdsmail](https://github.com/majestrate/bdsmail) ⭐ 39 | 🐛 3 | 🌐 Go | 📅 2024-06-03 - Brain Dead Simple Mail Server.
* [pboted](https://github.com/PurpleBote/pboted) ⭐ 24 | 🐛 2 | 🌐 C++ | 📅 2023-07-08 - Standalone C++ client for I2P/Bote e-mail exchange protocol.
* [i2pboted](https://github.com/majestrate/i2pboted) ⭐ 7 | 🐛 0 | 🌐 Go | 📅 2017-10-26 - Go implementation of I2P/Bote.

### Forum / Blog

* [i2p.syndie](https://github.com/i2p/i2p.syndie) ⚠️ Archived - Syndie is an open source system for operating distributed forums, offering a secure and consistent interface to various anonymous and non-anonymous content networks.
* [railroad](https://github.com/eyedeekay/railroad) ⭐ 14 | 🐛 4 | 🌐 Go | 📅 2024-02-01 - A simple, single-user, self-hosted blogging system for I2P.
* [cliqueclique](https://github.com/redhog/cliqueclique) ⭐ 9 | 🐛 0 | 🌐 JavaScript | 📅 2013-04-06 - P2P forum on top of I2P.
* [syndie-core](https://github.com/kpetku/syndie-core) ⭐ 6 | 🐛 8 | 🌐 Go | 📅 2023-02-25 - CLI, network, and database backend for syndie-gui.
* [syndie-gui](https://github.com/kpetku/syndie-gui) ⭐ 3 | 🐛 7 | 🌐 Go | 📅 2023-03-06 - Syndie GUI frontend for syndie-core.

### Files / Sharing

* [muwire](https://github.com/zlatinb/muwire) ⭐ 204 | 🐛 53 | 🌐 Groovy | 📅 2025-01-01 - MuWire file sharing client for I2P.
* [i2pfsd](https://github.com/i2pfs/i2pfsd) ⭐ 5 | 🐛 0 | 🌐 Go | 📅 2018-06-19 - I2P-based high available shared filesystem server.
* [tahoe-lafs-i2p](https://github.com/chris-barry/tahoe-lafs-i2p) - Tahoe-LAFS is a Free and Open decentralized cloud storage system. It distributes your data across multiple servers. Even if some of the servers fail or are taken over by an attacker, the entire file store continues to function correctly, preserving your privacy and security.

### Messaging

* [i2pchat](https://github.com/hypnosis-i2p/i2pchat) ⚠️ Archived - I2PChat. Previously I2P Qt Messenger.
* [MaladaN-Messenger-Client](https://github.com/MaladaN/MaladaN-Messenger-Client) ⚠️ Archived - An end to end encrypted Messenger that uses the signal protocol over the I2P network.
* [MaladaN-Messenger-Server](https://github.com/MaladaN/MaladaN-Messenger-Server) ⚠️ Archived - MaladaN Messenger Server end, for messaging using the signal protocol through I2P.

### Tools

* [i2pd-tools](https://github.com/PurpleI2P/i2pd-tools) ⭐ 162 | 🐛 10 | 🌐 C++ | 📅 2026-05-22 - Some useful tools for I2P.
* [pyreseeder](https://github.com/PurpleI2P/pyseeder) ⭐ 40 | 🐛 0 | 🌐 Python | 📅 2025-02-21 - Reseed data managment tools for I2P.
* [transi2p](https://github.com/rbif/transi2p) ⭐ 35 | 🐛 3 | 🌐 Python | 📅 2024-03-09 - Transparent proxying for I2P and forwarding other addresses to Tor or clearnet.
* [i2p-tools](https://github.com/MDrollette/i2p-tools) ⚠️ Archived - This tool provides a secure and efficient reseed server for the I2P network. There are several utility commands to create, sign, and validate SU3 files.
* [i2p-tools](https://github.com/majestrate/i2p-tools) ⭐ 18 | 🐛 1 | 🌐 C | 📅 2017-05-07 - Assorted I2P tools and scripts.
* [I2PMonitor](https://github.com/miximka/I2PMonitor) ⚠️ Archived - I2P monitor and control application for Mac OS X.
* [i2p-reseeder](https://github.com/torbjo/i2p-reseeder) ⭐ 7 | 🐛 2 | 🌐 Python | 📅 2015-03-23 - I2P Reseeder written in Python (WSGI).
* [i2p-control](https://github.com/eyedeekay/i2p-control) ⭐ 4 | 🐛 1 | 🌐 Go | 📅 2024-07-08 - Go terminal application for talking to i2pcontrol.
* [i2pberry](https://github.com/barrygolden/i2pberry) - I2Pberry - I2P for the Raspberry Pi.
* [i2spy](https://github.com/chris-barry/i2spy) - Takes stats from many I2P nodes, and holds them in a centralized location.
* [si-i2p-plugin](https://github.com/eyedeekay/si-i2p-plugin) - An experimental approach to provide a destination-isolating mechanism for http-over-i2p.

### Torrents

* [XD](https://github.com/majestrate/XD) ⭐ 275 | 🐛 29 | 🌐 Go | 📅 2026-08-30 - BitTorrent Client written in Go.
* [Transmission-I2P](https://github.com/l-n-s/transmission-i2p) ⭐ 42 | 🐛 1 | 🌐 C | 📅 2018-01-06 - Anonymous torrent client Transmission-I2P.
* [samtracker](https://github.com/eyedeekay/samtracker) ⭐ 4 | 🐛 0 | 🌐 Go | 📅 2022-08-29 - HTTP Bittorrent tracker with automatic port-forwarding to I2P.

### Web

* [i2pdbrowser](https://github.com/PurpleI2P/i2pdbrowser) ⭐ 804 | 🐛 15 | 🌐 HTML | 📅 2025-03-08 - I2Pd browser bundle.
* [darkweb-everywhere](https://github.com/chris-barry/darkweb-everywhere) ⚠️ Archived - HTTPS Everywhere rulesets for hidden services and eepsites.
* [i2pd-webui](https://github.com/l-n-s/i2pd-webui) ⭐ 25 | 🐛 0 | 🌐 CSS | 📅 2017-08-27 - Fancy I2Pd web user interface.
* [i2pjump](https://github.com/robertfoss/i2pjump) ⭐ 14 | 🐛 0 | 🌐 Python | 📅 2022-02-24 - I2P jump service. A sort of slave DNS server for I2P.
* [py-i2phosts](https://github.com/i2phosts/py-i2phosts) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2022-07-25 - py-i2phosts is a hostnames registration engine for I2P.
* [i2p.to-web](https://github.com/hilbix/i2p.to-web) ⭐ 9 | 🐛 0 | 🌐 PHP | 📅 2012-11-22 - Web portion of i2p.to, an I2P inProxy.
* [specter](https://github.com/SpecterBrowser/specter) ⭐ 8 | 🐛 0 | 🌐 C++ | 📅 2025-08-08 - Easy to use secure I2Pd browser
* [fl](https://gitlab.com/opennota/fl) - Reverse proxy to Flibusta via Tor or I2P.

## Libraries

### BOB

* [i2p.rb](https://github.com/dryruby/i2p.rb) ⚠️ Archived - I2P.rb is a Ruby library for interacting with the I2P anonymity network. SAM and BOB.
* [txi2p](https://github.com/str4d/txi2p) ⭐ 15 | 🐛 3 | 🌐 Python | 📅 2022-08-02 - I2P bindings for Twisted. SAM and BOB.
* [bobcpp](https://gitlab.com/rszibele/bobcpp) - C++ BOB library.

### SAM

* [libtorrent-rasterbar](https://github.com/arvidn/libtorrent) ⭐ 6,044 | 🐛 249 | 🌐 C++ | 📅 2026-08-30 - libtorrent is a popular C++ BitTorrent library that has support for I2P.
* [i2p-rs](https://github.com/i2p/i2p-rs) ⭐ 106 | 🐛 6 | 🌐 Rust | 📅 2025-07-17 - Rust client library for interacting with I2P.
* [node-i2p](https://github.com/redhog/node-i2p) ⭐ 46 | 🐛 4 | 🌐 JavaScript | 📅 2018-01-29 - NodeJS api for communicating over I2P (SAMv3 client).
* [i2plib](https://github.com/l-n-s/i2plib) ⭐ 42 | 🐛 1 | 🌐 Python | 📅 2019-02-05 - Python bindings for SAMv3.
* [i2psam](https://github.com/i2p/i2psam) ⭐ 42 | 🐛 4 | 🌐 C++ | 📅 2025-07-17 - C++ SAMv3 library.
* [goSam](https://github.com/cryptix/goSam) ⭐ 41 | 🐛 2 | 🌐 Go | 📅 2019-12-23 - A Go library for using the I2P Simple Anonymous Messaging (SAM version 3.0) bridge.
* [libsam3](https://github.com/i2p/libsam3) ⭐ 37 | 🐛 10 | 🌐 C | 📅 2026-01-14 - C SAMv3 library.
* [i2p.rb](https://github.com/dryruby/i2p.rb) ⚠️ Archived - I2P.rb is a Ruby library for interacting with the I2P anonymity network. SAM and BOB.
* [i2p-sam](https://github.com/diva-exchange/i2p-sam) ⭐ 20 | 🐛 2 | 🌐 TypeScript | 📅 2026-08-02 - TypeScript. I2P SAM: peer-to-peer communication between applications over I2P.
* [haskell-network-anonymous-i2p](https://github.com/solatis/haskell-network-anonymous-i2p) ⭐ 17 | 🐛 1 | 🌐 Haskell | 📅 2015-06-01 - Haskell API for I2P anonymous networking.
* [i2p.socket](https://github.com/majestrate/i2p.socket) ⭐ 17 | 🐛 4 | 🌐 Python | 📅 2018-01-01 - drop in python socket module that uses I2P.
* [txi2p](https://github.com/str4d/txi2p) ⭐ 15 | 🐛 3 | 🌐 Python | 📅 2022-08-02 - I2P bindings for Twisted. SAM and BOB.
* [i2pdotnet](https://github.com/SamuelFisher/i2pdotnet) ⭐ 10 | 🐛 0 | 🌐 C# | 📅 2017-07-09 - .NET library for using the I2P Simple Anonymous Messaging (SAM v3.0) bridge.
* [solitude](https://github.com/syvita/solitude) ⭐ 7 | 🐛 5 | 🌐 Rust | 📅 2022-03-12 - I2P SAMv3 library in Rust (WIP).
* [I2PSharp](https://github.com/MohA39/I2PSharp) ⭐ 6 | 🐛 0 | 🌐 C# | 📅 2024-10-16 - C# library implementation of the I2P SAM v3.3 protocol.
* [php-sam](https://github.com/theimpossibleastronaut/php-sam) ⭐ 4 | 🐛 0 | 🌐 PHP | 📅 2026-02-12 - Basic SAMv3 implementation in PHP.
* [Jsam](https://github.com/eyedeekay/Jsam) - A Java library for i2p's SAM API.
* [Py2p](https://i2pgit.org/robin/Py2p) - Python interface to I2P.
* [i2plib-fork](https://codeberg.org/weko/i2plib-fork) - Fork of i2plib with some fixes and bb32 support.
* [mooni2p](https://notabug.org/tmpid1/mooni2p) - Lua library for working with the I2P network

### Other

* [libtorrent-i2p](https://github.com/l-n-s/libtorrent-i2p) ⭐ 7 | 🐛 0 | 📅 2016-08-17 - libtorrent modified to download torrents anonymously.
* [libsyndie](https://github.com/kpetku/libsyndie) ⭐ 5 | 🐛 2 | 🌐 Go | 📅 2022-08-13 - Syndie library written in Go (see also: syndie-gui or syndie-core).
* [samrtc](https://github.com/eyedeekay/samrtc) - webRTC over I2P via SAM.

## Resources

### Documentation

* [geti2p.net/spec](https://geti2p.net/spec) - I2P Specification Documents.
* [bote.readthedocs.io](https://bote.readthedocs.io) - I2P/Bote Protocol Specification.

### Guides

* [tutorial-darknet](https://github.com/Kakuye/tutorial-darknet) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2017-05-25 - Follow up files/scripts for I2Pd+VPN+Ubuntu remote I2P router setup.

### Publications

* [Peer Profiling and Selection in the I2P Anonymous Network](https://geti2p.net/_static/pdf/I2P-PET-CON-2009.1.pdf)
* [Anonymity Techniques - Usability Tests of Major Anonymity Networks](https://people.torproject.org/~karsten/petcon-proceedings-2009.1.pdf)
* [Darknets and hidden servers: Identifying the true IP/network identity of I2P service hosts](http://www.irongeek.com/downloads/Identifying%20the%20true%20IP%20of%20I2P%20service%20hosts.pdf)
* [Privacy-Implications of Performance-Based Peer Selection by Onion-Routers: A Real-World Case Study using I2P](https://gnunet.org/sites/default/files/herrmann2011mt.pdf)
* [I2P Usability vs. Tor Usability A Bandwidth and Latency Comparison](http://userpage.fu-berlin.de/~semu/docs/2011_seminar_ehlert_i2p.pdf)
* [Monitoring the I2P network](http://hal.inria.fr/inria-00632259/PDF/TMA2012-LNCS.pdf)
* [I2P's Usage Characterization](https://hal.inria.fr/hal-00744902/PDF/TMA2012-LNCS.pdf)
* [A survey on solutions and main free tools for privacy enhancing Web communications](https://www.freehaven.net/anonbib/cache/Ruiz-Martinez_2012.pdf)
* [A Bird's Eye View on the I2P Anonymous File-sharing Environment](http://hal.inria.fr/hal-00744919/PDF/A_Birda_s_Eye_View_on_the_I2P_Anonymous_0AFile-sharing_Environment_0A.pdf)
* [Improving Content Availability in the I2P Anonymous File-Sharing Environment](http://hal.inria.fr/hal-00744922/PDF/Improving_Content_Availability_in_the_I2P_0AAnonymous_File-Sharing_Environment_0A.pdf)
* [Practical Attacks Against the I2P Network](https://wwwcip.informatik.uni-erlangen.de/~spjsschl/i2p.pdf)

### Websites

* [geti2p.net](https://geti2p.net/) - The Invisible Internet Project Website.
* [i2pd.website](https://i2pd.website/) - I2Pd Website.
* [i2pforum.net](https://i2pforum.net/) - The I2P forum.

## Contributing

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.
Thanks to all [contributors](https://github.com/mikalv/awesome-i2p/graphs/contributors) ⭐ 290 | 🐛 1 | 📅 2025-08-30!

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-31._

# asterisk

Introduction to Asterisk
----------------------------------------

Asterisk is a software implementation of a telephone private branch exchange (PBX). It allows telephones interfaced with a variety of hardware technologies to make calls to one another, and to connect to telephony services, such as the public switched telephone network (PSTN) and voice over Internet Protocol (VoIP) services. Its name comes from the asterisk symbol "*".



The Asterisk software includes many features available in commercial and proprietary PBX systems: voice mail, conference calling, interactive voice response (phone menus), and automatic call distribution. Users can create new functionality by writing dial plan scripts in several of Asterisk's own extensions languages, by adding custom loadable modules written in C, or by implementing Asterisk Gateway Interface (AGI) programs using any programming language capable of communicating via the standard streams system (stdin and stdout) or by network TCP sockets.

Asterisk supports several standard voice over IP protocols, including the Session Initiation Protocol (SIP), the Media Gateway Control Protocol (MGCP), and H.323. Asterisk supports most SIP telephones, acting both as registrar and back-to-back user agent. It can serve as a gateway between IP phones and the public switched telephone network (PSTN) via T- or E-carrier interfaces or analog FXO cards. The Inter-Asterisk eXchange (IAX) protocol, RFC 5456, native to Asterisk, provides efficient trunking of calls between Asterisk PBX systems, in addition to distributing some configuration logic. Many VoIP service providers support it for call completion into the PSTN, often because they themselves have deployed Asterisk or offer it as a hosted application. Some telephones also support the IAX protocol.

By supporting a variety of traditional and VoIP telephony services, Asterisk allows deployers to build telephone systems, or migrate existing systems to new technologies. Some sites are using Asterisk to replace proprietary PBXes, others provide additional features, such as voice mail or voice response menus, or virtual call shops, or to reduce cost by carrying long-distance calls over the Internet (toll bypass).

In addition to VoIP protocols, Asterisk supports traditional circuit-switching protocols such as ISDN and SS7. This requires appropriate hardware interface cards, marketed by third-party vendors. Each protocol requires the installation of software modules. In Asterisk release 14 the Opus audio codec is supported. 

Resource: https://en.wikipedia.org/wiki/Asterisk_(PBX)

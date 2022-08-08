# <img src="http://i.imgur.com/RSUlFRa.gif" width="150" alt="HEP">

### Full-Stack Applications
* [HOMER](http://github.com/sipcapture/homer) - HOMER is a robust, carrier-grade, scalable SIP Capture system and VoiP Monitoring Application based on HEP/EEP encapsulation, ready to process & store insane amounts of signaling, logs and statistics with instant indexing, search, end-to-end analysis and protocol drill-down capabilities, built on top of OpenSIPS or Kamailio as Capture Servers.
* [HEPIC](http://hepic.tel) - HEPIC is a stand-alone HEP/EEP centric real-time packet capture framework, with protocol agnostic indexing and highly-scalable correlation, media analytics, exporting and customization capabilities for advanced usage and integrations with 3rd party VoIP/RTC platforms and services.
* [SIP3](http://sip3.io) - Troubleshoot and Monitor your VoIP and RTC traffic real-time

### HEP Server Applications
* [HEPlify-server](https://github.com/sipcapture/heplify-server) - HEPlify-Server is a stand-alone HOMER Capture Server developed in Go, optimized for speed and simplicity. Distributed as a single binary ready to capture TCP/TLS/UDP HEP encapsulated packets from heplify or any other HEP enabled agent or platform, indexing to database using H5 or H7 table format, producing basic usage metrics timeseries and providing users with simple, basic options for correlation and tagging inline.
* [HEPop](https://github.com/sipcapture/hepop) - HEPop is a stand-alone HEP Capture Server developed in NodeJS, designed to prototype different backends for HOMER7 and emitting Metrics to external backends such as InfluxDB and Prometheus.
* [OpenSIPS](https://opensips.org) - OpenSIPS is a GPL implementation of a multi-functionality SIP Server with deep HEP support providing Server, [Client](http://www.opensips.org/html/docs/modules/2.2.x/siptrace.html) and [Switch/Proxy](https://github.com/sipcapture/homer/wiki/Examples%3A-opensips-hepswitch) features to forge and manipulate HEP packets.
* [Kamailio](https://github.com/kamailio/kamailio) - The Kamailio SIP server is designed for scalability, targeting large deployments (e.g. for IP telephony operators or carriers, which have a large subscriber base or route a big volume of calls) providing [Server](https://www.kamailio.org/docs/modules/5.0.x/modules/sipcapture.html) and [Client](https://www.kamailio.org/docs/modules/5.0.x/modules/siptrace.html) features to mirror HEP packets.

### Native Client Applications
* [Asterisk](https://github.com/sipcapture/homer/wiki/Examples%3A-Asterisk) - Asterisk is an Open Source PBX and telephony toolkit. It is, in a sense, middleware between Internet and telephony channels on the bottom, and Internet and telephony applications at the top. Asterisk 12 and higher ship with native HEP encapsulation support (res_hep) and are able to natively mirror SIP and RTCP packets to a HEP/EEP Collector such as HOMER.
* [FreeSwitch](https://github.com/sipcapture/homer/wiki/Examples%3A-FreeSwitch) - FreeSWITCH™ is an open source Real-Time communications platform written in C from the ground up with a modular and extensible architecture, shipping with a natively integrated HEP-EEP Capture Agent designed to work with HOMER.
* [OpenSIPS](https://opensips.org) - OpenSIPS is a GPL implementation of a multi-functionality SIP Server with deep HEP support providing Server, [Client](http://www.opensips.org/html/docs/modules/2.2.x/siptrace.html) and [Switch/Proxy](https://github.com/sipcapture/homer/wiki/Examples%3A-opensips-hepswitch) features to forge and manipulate HEP packets.
* [Kamailio](https://github.com/kamailio/kamailio) - The Kamailio SIP server is designed for scalability, targeting large deployments (e.g. for IP telephony operators or carriers, which have a large subscriber base or route a big volume of calls) providing [Server](https://www.kamailio.org/docs/modules/5.0.x/modules/sipcapture.html) and [Client](https://www.kamailio.org/docs/modules/5.0.x/modules/siptrace.html) features to mirror HEP packets.
* [repro](http://www.resiprocate.org/About_Repro) - the SIP proxy of the [reSIProcate project](http://www.resiprocate.org) has integrated HEP support, supports a wide range of SIP RFCs and is one of the easiest SIP proxies to get started with (see the [RTC Quick Start guide](https://rtcquickstart.org)).
* [reConServer](http://www.resiprocate.org/Recon_Overview) - the SBC / B2BUA of the [reSIProcate project](http://www.resiprocate.org) has integrated HEP support, supports a wide range of SIP RFCs and is one of the easiest SBCs to get started with for simple projects requiring a full SIP feature set like TLS and SRTP.
* [Drachtio](https://drachtio.org) - An high-performance and easily-configured SIP server (written in C++), and a Node.js framework that enables applications to control the server and implement application logic. 
* [RTP:Engine](https://github.com/sipwise/rtpengine) - The Sipwise NGCP rtpengine is a proxy for RTP traffic and other UDP based media traffic. It's meant to be used with the Kamailio SIP proxy and forms a drop-in replacement for any of the other available RTP and media proxies, support sending RTCP stats to Homer via HEP.
  * [Speech-to-Text](https://github.com/sipcapture/homer/wiki/Examples%3A-RTPEngine-speech) - RTPEngine Speech-to-Text NodeJS Spooler using the Bing Speech API and HEP Output.

### Stand-Alone Client Applications
* [CaptAgent](https://github.com/sipcapture/captagent) - CaptAgent is a modular packet capture agent/probe for RT protocols with bleeding edge HEP support.
* [HEPlify](https://github.com/sipcapture/heplify) - heplify is captagents little brother. While it offers a compareable performance the design goal was simplicity. It's a single binary which you can run to capture packets and send them to Homer. Right now heplify is able to send SIP, correlated RTCP, RTCPXR and very basic DNS, LOG or TLS handshakes into HOMER.
* [sngrep](https://github.com/irontec/sngrep) - sngrep is a tool for displaying SIP calls message flows from terminal with native HEP-EEP client and relay capabilities.
* [sipgrep](https://github.com/sipcapture/sipgrep) - sipgrep is a tool for displaying and troubleshoot SIP signaling over IP networks in console, with native HEP-EEP client and relay capabilities.
* [captagent-js](https://github.com/sipcapture/captagent-js) - Basic HEP Agent in NodeJS using HEP-js npm module.
* [RTPAgent](mailto:sales@qxip.net) - Advanced HEP Agent with in-line RTP Analyzer and Recorder
* [HEPjack](https://github.com/sipcapture/HEPjack.js) - Elegantly Sniff Forward-Secrecy TLS/SIP to HEP at the source using Frida

### Gateway Applications
* [paStash](https://github.com/sipcapture/pastash) - PaStasH (pastaʃ'ʃ-utta) is a NodeJS multi I/O processor supporting ingestion, decoding, interpolation and correlation of data - be it logs, packets, events and beyond. PaStash supports the Logstash configuration format and delivers cross-functionality comparable to "Beats" with custom modules, providing a flexible and agnostig data pipelining tool, including [HEP-EEP](https://github.com/sipcapture/paStash/blob/master/docs/outputs/hep.md) output support.
* [horaclifix](https://github.com/negbie/horaclifix) - horaclifix sends IPFIX messages from Oracle SBC's into Homer as HEP-EEP
* [HEPfix.js](https://github.com/sipcapture/hepfix.js) - NodeJS IPFIX adaptor for HOMER/HEP and Oracle Acme Packet SBCs
* [HEPSwitch](https://github.com/lmangani/docker-hepswitch) - Docker container providing HEP/EEP Routing and Switching out-of-the-box.

### Tools
* [HEPgen.js](https://github.com/sipcapture/hepgen.js) - HEPgen is a NodeJS HEP Packet Generator for SIP-less Devs and Unit Testing
* [HEP Wireshark](https://github.com/sipcapture/hep-wireshark) - HEP-EEP Wireshark Dissector as a LUA plugin
* [HEPipe.js](https://github.com/sipcapture/hepipe.js) - Pipe arbitrary data rows (logs, events, cdrs, esl, etc) to HEP Server (NodeJS)
* [HEPipe C](https://github.com/sipcapture/hepipe) - Pipe arbitrary data rows (logs, events, cdrs, esl, etc) to HEP Server (C)
* [HEPgen-bash](https://github.com/sipcapture/hepgen-bash) - HEP generator written in bash
* [hammerHEP](https://github.com/negbie/hammerHEP) - HEP Server stress-tool in Go

### Cloud - PaaS
* [sipcapture.io](https://sipcapture.io) - Hosted and Maintained versions of HOMER and HEPIC straight from its makers.

### Network Applications
* [nDPI](https://github.com/ntop/nDPI) - Network Deep-Packet Inspection library from ntop, supporting HEP/EEP protocol recognition and tagging.
* [Corelatus](https://github.com/matthiasl/Corelatus-GTH-example-code/tree/eep_hec) - E1/T1 extractions using HEP/EEP.
* [Cubro](https://packagecloud.io/qxip/cubro-pub) - EXA8 Packages including HEPlify, HEPAgent, CaptAgent and more using HEP/EEP.

### Libraries and Code Examples
  * [C](https://github.com/sipcapture/hep-c)
  * [Java](https://github.com/sipcapture/hep-java)
  * [Javascript](https://github.com/sipcapture/hep-js)
  * [Go](https://github.com/sipcapture/hep-go)
  * [Perl](https://github.com/sipcapture/hep-perl)
  * [Python](https://github.com/sipcapture/hep-python)
  * [Erlang](https://github.com/sipcapture/hep-erlang)

# Curated list of awesome **free** (mostly open source) forensic analysis tools and resources.

- [Awesome Forensics ](#awesome-forensics)
  - [Collections](#collections)
  - [Tools](#tools)
    - [Distributions](#distributions)
    - [Frameworks](#frameworks)
    - [Live Forensics](#live-forensics)
    - [IOC Scanner](#ioc-scanner)
    - [Acquisition](#acquisition)
    - [Imaging](#imaging)
    - [Carving](#carving)
    - [Memory Forensics](#memory-forensics)
    - [Network Forensics](#network-forensics)
    - [Windows Artifacts](#windows-artifacts)
      - [NTFS/MFT Processing](#ntfsmft-processing)
    - [OS X Forensics](#os-x-forensics)
    - [Mobile Forensics](#mobile-forensics)
    - [Docker Forensics](#docker-forensics)
    - [Internet Artifacts](#internet-artifacts)
    - [Timeline Analysis](#timeline-analysis)
    - [Disk image handling](#disk-image-handling)
    - [Decryption](#decryption)
    - [Management](#management)
    - [Picture Analysis](#picture-analysis)
    - [Metadata Forensics](#metadata-forensics)
    - [Steganography](#steganography)
  - [Learn Forensics](#learn-forensics)
    - [CTFs and Challenges](#ctfs-and-challenges)
  - [Resources](#resources)
    - [Web](#web)
    - [Blogs](#blogs)
    - [Books](#books)
    - [File System Corpora](#file-system-corpora)
    - [Twitter](#twitter)
    - [Other](#other)
    - [Labs](#labs)
  - [Anti Forensics](#anti-forensics)


---

## Collections

- [AboutDFIR – The Definitive Compendium Project](https://aboutdfir.com) - Collection of forensic resources for learning and research. Offers lists of certifications, books, blogs, challenges and more
- [DFIR.Training](https://www.dfir.training/) - Database of forensic resources focused on events, tools and more
- :star: [ForensicArtifacts.com Artifact Repository](https://github.com/ForensicArtifacts/artifacts) - Machine-readable knowledge base of forensic artifacts

## Tools

- [Forensics tools on Wikipedia](https://en.wikipedia.org/wiki/List_of_digital_forensics_tools)
- [Eric Zimmerman's Tools](https://ericzimmerman.github.io/#!index.md)

### Distributions

- [bitscout](https://github.com/vitaly-kamluk/bitscout) - LiveCD/LiveUSB for remote forensic acquisition and analysis
- [Remnux](https://remnux.org/) - Distro for reverse-engineering and analyzing malicious software
- [SANS Investigative Forensics Toolkit (sift)](https://github.com/teamdfir/sift) - Linux distribution for forensic analysis
- [Tsurugi Linux](https://tsurugi-linux.org/) - Linux distribution for forensic analysis
- [WinFE](https://www.winfe.net/home) - Windows Forensics enviroment

### Frameworks

- :star:[Autopsy](http://www.sleuthkit.org/autopsy/) - SleuthKit GUI
- [dexter](https://github.com/coinbase/dexter) - Dexter is a forensics acquisition framework designed to be extensible and secure
- [dff](https://github.com/arxsys/dff) - Forensic framework
- [Dissect](https://github.com/fox-it/dissect) - Dissect is a digital forensics & incident response framework and toolset that allows you to quickly access and analyse forensic artefacts from various disk and file formats, developed by Fox-IT (part of NCC Group).
- [hashlookup-forensic-analyser](https://github.com/hashlookup/hashlookup-forensic-analyser) - A tool to analyse files from a forensic acquisition to find known/unknown hashes from [hashlookup](https://www.circl.lu/services/hashlookup/) API or using a local Bloom filter.
- [IntelMQ](https://github.com/certtools/intelmq) - IntelMQ collects and processes security feeds
- [Kuiper](https://github.com/DFIRKuiper/Kuiper) - Digital Investigation Platform
- [Laika BOSS](https://github.com/lmco/laikaboss) - Laika is an object scanner and intrusion detection system
- [PowerForensics](https://github.com/Invoke-IR/PowerForensics) - PowerForensics is a framework for live disk forensic analysis
- [TAPIR](https://github.com/tap-ir/tapir) - TAPIR (Trustable Artifacts Parser for Incident Response) is a multi-user, client/server, incident response framework
- :star: [The Sleuth Kit](https://github.com/sleuthkit/sleuthkit) - Tools for low level forensic analysis
- [turbinia](https://github.com/google/turbinia) - Turbinia is an open-source framework for deploying, managing, and running forensic workloads on cloud platforms
- [IPED - Indexador e Processador de Evidências Digitais](https://github.com/sepinf-inc/IPED) - Brazilian Federal Police Tool for Forensic Investigations
- [Wombat Forensics](https://github.com/pjrinaldi/wombatforensics) - Forensic GUI tool

### Live Forensics

- [grr](https://github.com/google/grr) - GRR Rapid Response: remote live forensics for incident response
- [Linux Expl0rer](https://github.com/intezer/linux-explorer) - Easy-to-use live forensics toolbox for Linux endpoints written in Python & Flask
- [mig](https://github.com/mozilla/mig) - Distributed & real time digital forensics at the speed of the cloud
- [osquery](https://github.com/osquery/osquery) - SQL powered operating system analytics
- [POFR](https://github.com/gmagklaras/pofr) - The Penguin OS Flight Recorder collects, stores and organizes for further analysis process execution, file access and network/socket endpoint data from the Linux Operating System.
- [UAC](https://github.com/tclahr/uac) - UAC (Unix-like Artifacts Collector) is a Live Response collection script for Incident Response that makes use of native binaries and tools to automate the collection of AIX, Android, ESXi, FreeBSD, Linux, macOS, NetBSD, NetScaler, OpenBSD and Solaris systems artifacts.

### IOC Scanner

- [Fastfinder](https://github.com/codeyourweb/fastfinder) - Fast customisable cross-platform suspicious file finder. Supports md5/sha1/sha256 hashes, literal/wildcard strings, regular expressions and YARA rules
- [Fenrir](https://github.com/Neo23x0/Fenrir) - Simple Bash IOC Scanner
- [Loki](https://github.com/Neo23x0/Loki) - Simple IOC and Incident Response Scanner
- [Redline](https://fireeye.market/apps/211364) - Free endpoint security tool from FireEye
- [THOR Lite](https://www.nextron-systems.com/thor-lite/) - Free IOC and YARA Scanner
- [recon](https://github.com/rusty-ferris-club/recon) - Performance oriented file finder with support for SQL querying, index and analyze file metadata with support for YARA.

### Acquisition

- [Acquire](https://github.com/fox-it/acquire) - Acquire is a tool to quickly gather forensic artifacts from disk images or a live system into a lightweight container
- [artifactcollector](https://github.com/forensicanalysis/artifactcollector) - A customizable agent to collect forensic artifacts on any Windows, macOS or Linux system
- [ArtifactExtractor](https://github.com/Silv3rHorn/ArtifactExtractor) - Extract common Windows artifacts from source images and VSCs
- [AVML](https://github.com/microsoft/avml) - A portable volatile memory acquisition tool for Linux
- [Belkasoft RAM Capturer](https://belkasoft.com/ram-capturer) - Volatile Memory Acquisition Tool
- [CrowdResponse](https://www.crowdstrike.com/resources/community-tools/crowdresponse/) - A static host data collection tool by CrowdStrike
- [DFIR ORC](https://dfir-orc.github.io/) - Forensics artefact collection tool for systems running Microsoft Windows
- [FastIR Collector](https://github.com/SekoiaLab/Fastir_Collector) - Collect artifacts on windows
- [FireEye Memoryze](https://fireeye.market/apps/211368) - A free memory forensic software 
- [LiME](https://github.com/504ensicsLabs/LiME) - Loadable Kernel Module (LKM), which allows the acquisition of volatile memory from Linux and Linux-based devices, formerly called DMD
- [Magnet RAM Capture](https://www.magnetforensics.com/resources/magnet-ram-capture/) - A free imaging tool designed to capture the physical memory 
- [unix_collector](https://github.com/op7ic/unix_collector) - A live forensic collection script for UNIX-like systems as a single script.
- [Velociraptor](https://github.com/Velocidex/velociraptor) - Velociraptor is a tool for collecting host based state information using Velocidex Query Language (VQL) queries
- [WinTriage](https://www.securizame.com/wintriage-the-triage-tool-for-windows-dfirers/) - Wintriage is a live response tool that extracts Windows artifacts. It must be executed with local or domain administrator privileges and recommended to be done from an external drive.

### Imaging

- [dc3dd](https://sourceforge.net/projects/dc3dd/) - Improved version of dd
- [dcfldd](https://dcfldd.sourceforge.net/) - Different improved version of dd (this version has some bugs!, another version is on github [adulau/dcfldd](https://github.com/adulau/dcfldd))
- [FTK Imager](https://www.exterro.com/ftk-imager) - Free imageing tool for windows
- :star: [Guymager](https://guymager.sourceforge.io/) - Open source version for disk imageing on linux systems

### Carving

- [bstrings](https://github.com/EricZimmerman/bstrings) - Improved strings utility
- [bulk_extractor](https://github.com/simsong/bulk_extractor) - Extracts information such as email addresses, creditcard numbers and histrograms from disk images
- [floss](https://github.com/mandiant/flare-floss) - Static analysis tool to automatically deobfuscate strings from malware binaries
- :star: [photorec](https://www.cgsecurity.org/wiki/PhotoRec) - File carving tool
- [swap_digger](https://github.com/sevagas/swap_digger) - A bash script used to automate Linux swap analysis, automating swap extraction and searches for Linux user credentials, Web form credentials, Web form emails, etc.

### Memory Forensics

- [inVtero.net](https://github.com/ShaneK2/inVtero.net) - High speed memory analysis framework
  developed in .NET supports all Windows x64, includes code integrity and write support
- [KeeFarce](https://github.com/denandz/KeeFarce) - Extract KeePass passwords from memory
- [MemProcFS](https://github.com/ufrisk/MemProcFS) - An easy and convenient way of accessing physical memory as files a virtual file system.
- [Rekall](https://github.com/google/rekall) - Memory Forensic Framework
- [volatility](https://github.com/volatilityfoundation/volatility) - The memory forensic framework
- [VolUtility](https://github.com/kevthehermit/VolUtility) - Web App for Volatility framework

### Network Forensics

- [Kismet](https://github.com/kismetwireless/kismet) - A passive wireless sniffer
- [NetworkMiner](https://www.netresec.com/?page=Networkminer) - Network Forensic Analysis Tool
- :star: [WireShark](https://www.wireshark.org/) - A network protocol analyzer

### Windows Artifacts

- [Beagle](https://github.com/yampelo/beagle) -  Transform data sources and logs into graphs
- [FRED](https://www.pinguin.lu/fred) - Cross-platform microsoft registry hive editor
- [Hayabusa](https://github.com/Yamato-Security/hayabusa) - A a sigma-based threat hunting and fast forensics timeline generator for Windows event logs.
- [LastActivityView](https://www.nirsoft.net/utils/computer_activity_view.html) - LastActivityView by Nirsoftis a tool for Windows operating system that collects information from various sources on a running system, and displays a log of actions made by the user and events occurred on this computer. 
- [LogonTracer](https://github.com/JPCERTCC/LogonTracer) - Investigate malicious Windows logon by visualizing and analyzing Windows event log
- [python-evt](https://github.com/williballenthin/python-evt) - Pure Python parser for classic Windows Event Log files (.evt)
- [RegRipper3.0](https://github.com/keydet89/RegRipper3.0) - RegRipper is an open source Perl tool for parsing the Registry and presenting it for analysis
- [RegRippy](https://github.com/airbus-cert/regrippy) - A framework for reading and extracting useful forensics data from Windows registry hives


#### NTFS/MFT Processing

- [MFT-Parsers](http://az4n6.blogspot.com/2015/09/whos-your-master-mft-parsers-reviewed.html) - Comparison of MFT-Parsers
- [MFTEcmd](https://binaryforay.blogspot.com/2018/06/introducing-mftecmd.html) - MFT Parser by Eric Zimmerman
- [MFTExtractor](https://github.com/aarsakian/MFTExtractor) - MFT-Parser
- [NTFS journal parser](http://strozfriedberg.github.io/ntfs-linker/)
- [NTFS USN Journal parser](https://github.com/PoorBillionaire/USN-Journal-Parser)
- [RecuperaBit](https://github.com/Lazza/RecuperaBit) - Reconstruct and recover NTFS data
- [python-ntfs](https://github.com/williballenthin/python-ntfs) - NTFS analysis

### OS X Forensics

- [APFS Fuse](https://github.com/sgan81/apfs-fuse) - A read-only FUSE driver for the new Apple File System
- [mac_apt (macOS Artifact Parsing Tool)](https://github.com/ydkhatri/mac_apt) - Extracts forensic artifacts from disk images or live machines
- [MacLocationsScraper](https://github.com/mac4n6/Mac-Locations-Scraper) - Dump the contents of the location database files on iOS and macOS
- [macMRUParser](https://github.com/mac4n6/macMRU-Parser) - Python script to parse the Most Recently Used (MRU) plist files on macOS into a more human friendly format
- [OSXAuditor](https://github.com/jipegit/OSXAuditor)
- [OSX Collect](https://github.com/Yelp/osxcollector)

### Mobile Forensics

- [Andriller](https://github.com/den4uk/andriller) - A software utility with a collection of forensic tools for smartphones
- [ALEAPP](https://github.com/abrignoni/ALEAPP) - An Android Logs Events and Protobuf Parser
- [ArtEx](https://www.doubleblak.com/index.php) - Artifact Examiner for iOS Full File System extractions
- [iLEAPP](https://github.com/abrignoni/iLEAPP) - An iOS Logs, Events, And Plists Parser
- [iOS Frequent Locations Dumper](https://github.com/mac4n6/iOS-Frequent-Locations-Dumper) - Dump the contents of the StateModel#.archive files located in /private/var/mobile/Library/Caches/com.apple.routined/
- [MEAT](https://github.com/jfarley248/MEAT) - Perform different kinds of acquisitions on iOS devices
- [MobSF](https://github.com/MobSF/Mobile-Security-Framework-MobSF) - An automated, all-in-one mobile application (Android/iOS/Windows) pen-testing, malware analysis and security assessment framework capable of performing static and dynamic analysis.
- [OpenBackupExtractor](https://github.com/vgmoose/OpenBackupExtractor) - An app for extracting data from iPhone and iPad backups.


### Docker Forensics

- [dof (Docker Forensics Toolkit)](https://github.com/docker-forensics-toolkit/toolkit) - Extracts and interprets forensic artifacts from disk images of Docker Host systems
- [Docker Explorer](https://github.com/google/docker-explorer) Extracts and interprets forensic artifacts from disk images of Docker Host systems

### Internet Artifacts

- [ChromeCacheView](https://www.nirsoft.net/utils/chrome_cache_view.html) - A small utility that reads the cache folder of Google Chrome Web browser, and displays the list of all files currently stored in the cache
- [chrome-url-dumper](https://github.com/eLoopWoo/chrome-url-dumper) - Dump all local stored infromation collected by Chrome
- [hindsight](https://github.com/obsidianforensics/hindsight) - Internet history forensics for Google Chrome/Chromium
- [IE10Analyzer](https://github.com/moaistory/IE10Analyzer) - This tool can parse normal records and recover deleted records in WebCacheV01.dat.
- [unfurl](https://github.com/obsidianforensics/unfurl) - Extract and visualize data from URLs
- [WinSearchDBAnalyzer](https://github.com/moaistory/WinSearchDBAnalyzer) - This tool can parse normal records and recover deleted records in Windows.edb.

### Timeline Analysis

- [DFTimewolf](https://github.com/log2timeline/dftimewolf) - Framework for orchestrating forensic collection, processing and data export using GRR and Rekall
- :star: [plaso](https://github.com/log2timeline/plaso) - Extract timestamps from various files and aggregate them
- [Timeline Explorer](https://binaryforay.blogspot.com/2017/04/introducing-timeline-explorer-v0400.html) - Timeline Analysis tool for CSV and Excel files. Built for SANS FOR508 students
- [timeliner](https://github.com/airbus-cert/timeliner) - A rewrite of mactime, a bodyfile reader
- [timesketch](https://github.com/google/timesketch) - Collaborative forensic timeline analysis

### Disk image handling

- [Disk Arbitrator](https://github.com/aburgh/Disk-Arbitrator) - A Mac OS X forensic utility designed to help the user ensure correct forensic procedures are followed during imaging of a disk device
- [imagemounter](https://github.com/ralphje/imagemounter) - Command line utility and Python package to ease the (un)mounting of forensic disk images
- [libewf](https://github.com/libyal/libewf) - Libewf is a library and some tools to access the Expert Witness Compression Format (EWF, E01)
- [PancakeViewer](https://github.com/forensicmatt/PancakeViewer) - Disk image viewer based in dfvfs, similar to the FTK Imager viewer
- [xmount](https://www.pinguin.lu/xmount) - Convert between different disk image formats

### Decryption

- [hashcat](https://hashcat.net/hashcat/) - Fast password cracker with GPU support
- [John the Ripper](https://www.openwall.com/john/) - Password cracker

### Management

- [dfirtrack](https://github.com/dfirtrack/dfirtrack) - Digital Forensics and Incident Response Tracking application, track systems
- [Incidents](https://github.com/veeral-patel/incidents) - Web application for organizing non-trivial security investigations. Built on the idea that incidents are trees of tickets, where some tickets are leads

### Picture Analysis

- [Ghiro](http://www.getghiro.org/) - A fully automated tool designed to run forensics analysis over a massive amount of images
- [sherloq](https://github.com/GuidoBartoli/sherloq) - An open-source digital photographic image forensic toolset

### Metadata Forensics

- [ExifTool](https://exiftool.org/) by Phil Harvey
- [FOCA](https://github.com/ElevenPaths/FOCA) - FOCA is a tool used mainly to find metadata and hidden information in the documents

### Steganography

- [Sonicvisualizer](https://www.sonicvisualiser.org)
- [Steghide](https://github.com/StefanoDeVuono/steghide) - is a steganography program that hides data in various kinds of image and audio files
- [Wavsteg](https://github.com/samolds/wavsteg) - is a steganography program that hides data in various kinds of image and audio files
- [Zsteg](https://github.com/zed-0xff/zsteg) - A steganographic coder for WAV files

## Learn Forensics

- [Forensic challenges](https://www.amanhardikar.com/mindmaps/ForensicChallenges.html) - Mindmap of forensic challenges
- [OpenLearn](https://www.open.edu/openlearn/science-maths-technology/digital-forensics/content-section-0?active-tab=description-tab) - Digital forensic course
- [Training material](https://www.enisa.europa.eu/topics/training-and-exercises/trainings-for-cybersecurity-specialists/online-training-material/technical-operational) - Online training material by European Union Agency for Network and Information Security for different topics (e.g. [Digital forensics](https://www.enisa.europa.eu/topics/training-and-exercises/trainings-for-cybersecurity-specialists/online-training-material/technical-operational#digital_forensics), [Network forensics](https://www.enisa.europa.eu/topics/training-and-exercises/trainings-for-cybersecurity-specialists/online-training-material/technical-operational#network_forensics))

### CTFs and Challenges

- [BelkaCTF](https://belkasoft.com/ctf) - CTFs by Belkasoft
- [Champlain College DFIR CTF](https://champdfa-ccsc-sp20.ctfd.io)
- [CyberDefenders](https://cyberdefenders.org/blueteam-ctf-challenges/?type=ctf) 
- [DefCon CTFs](https://archive.ooo) - archive of DEF CON CTF challenges.
- [Forensics CTFs](https://github.com/apsdehal/awesome-ctf/blob/master/README.md#forensics)
- [MagnetForensics CTF Challenge](https://www.magnetforensics.com/blog/magnet-weekly-ctf-challenge/)
- [MalwareTech Challenges](https://www.malwaretech.com/challenges)
- [MalwareTraffic Analysis](https://www.malware-traffic-analysis.net/training-exercises.html)
- [MemLabs](https://github.com/stuxnet999/MemLabs)
- [NW3C Chanllenges](https://nw3.ctfd.io)
- [Precision Widgets of North Dakota Intrusion](https://betweentwodfirns.blogspot.com/2017/11/dfir-ctf-precision-widgets-of-north.html)
- [ReverseEngineering Challenges](https://challenges.re)

## Resources

### Web

- [ForensicsFocus](https://www.forensicfocus.com/)
- [Insecstitute Resources](https://resources.infosecinstitute.com/)
- [SANS Digital Forensics](https://www.sans.org/digital-forensics-incident-response/)


### Blogs

- [FlashbackData](https://www.flashbackdata.com/blog/)
- [Netresec](https://www.netresec.com/index.ashx?page=Blog)
- [SANS Forensics Blog](https://www.sans.org/blog/?focus-area=digital-forensics)
- [SecurityAffairs](https://securityaffairs.co/) - blog by Pierluigi Paganini
- [thisweekin4n6.wordpress.com](thisweekin4n6.wordpress.com) - Weekly updates for forensics
- [Zena Forensics](https://blog.digital-forensics.it/)

### Books

*more at [Recommended Readings](http://dfir.org/?q=node/8) by Andrew Case*

- [Network Forensics: Tracking Hackers through Cyberspace](https://www.pearson.com/en-us/subject-catalog/p/Davidoff-Network-Forensics-Tracking-Hackers-through-Cyberspace/P200000009228) - Learn to recognize hackers’ tracks and uncover network-based evidence
- [The Art of Memory Forensics](https://www.memoryanalysis.net/amf) - Detecting Malware and Threats in Windows, Linux, and Mac Memory
- [The Practice of Network Security Monitoring](https://nostarch.com/nsm) - Understanding Incident Detection and Response

### File System Corpora

- [Digital Forensic Challenge Images](https://www.ashemery.com/dfir.html) - Two DFIR challenges with images
- [Digital Forensics Tool Testing Images](https://sourceforge.net/projects/dftt/)
- [The CFReDS Project](https://cfreds.nist.gov)
  - [Hacking Case (4.5 GB NTFS Image)](https://cfreds.nist.gov/Hacking_Case.html)

### Twitter

- [@4n6ist](https://twitter.com/4n6ist)
- [@AppleExaminer](https://twitter.com/AppleExaminer) - Apple OS X & iOS Digital Forensics
- [@carrier4n6](https://twitter.com/carrier4n6) - Brian Carrier, author of Autopsy and the Sleuth Kit
- [@forensikblog](https://twitter.com/forensikblog) - Computer forensic geek
- [@HECFBlog](https://twitter.com/HECFBlog) - SANS Certified Instructor
- [@Hexacorn](https://twitter.com/Hexacorn) - DFIR+Malware
- [@hiddenillusion](https://twitter.com/hiddenillusion)
- [@iamevltwin](https://twitter.com/iamevltwin) - Mac Nerd, Forensic Analyst, Author & Instructor of SANS FOR518
- [@jaredcatkinson](https://twitter.com/jaredcatkinson) - PowerShell Forensics
- [@maridegrazia](https://twitter.com/maridegrazia) - Computer Forensics Examiner
- [@sleuthkit](https://twitter.com/sleuthkit)
- [@williballenthin](https://twitter.com/williballenthin)
- [@XWaysGuide](https://twitter.com/XWaysGuide)
- [@inginformatico](https://twitter.com/inginformatico) - DFIR analyst and enthusiast

### Other

- [/r/computerforensics/](https://www.reddit.com/r/computerforensics/) - Subreddit for computer forensics
- [ForensicPosters](https://github.com/Invoke-IR/ForensicPosters) - Posters of file system structures
- [SANS Posters](https://www.sans.org/posters/) - Free posters provided by SANS

### Labs

- [BlueTeam.Lab](https://github.com/op7ic/BlueTeam.Lab) - Blue Team detection lab created with Terraform and Ansible in Azure.

-------

## Anti-Forensics

### System/Digital Image

- [Afflib](https://github.com/sshock/AFFLIBv3) : An extensible open format for the storage of disk images and related forensic.information.
- [Air-Imager](https://sourceforge.net/projects/air-imager/) : A GUI front-end to dd/dc3dd designed for easily creating forensic images.
- [Bmap-tools](https://github.com/intel/bmap-tools) : Tool for copying largely sparse files using information from a block map file.
- [dd]() : The dd command allows you to copy all or part of a disk.
  - [Dc3dd](https://doc.ubuntu-fr.org/dc3dd) : A patched version of dd that includes a number of features useful for computer forensics.
  - [Dcfldd](https://doc.ubuntu-fr.org/dcfldd) : DCFL (DoD Computer Forensics Lab), a dd replacement with hashing.
- [ddrescue](https://doc.ubuntu-fr.org/ddrescue) : GNU data recovery tool.
- [Dmg2img](https://github.com/Lekensteyn/dmg2img) : A CLI tool to uncompress Apple's compressed DMG files to the HFS+ IMG format.
- [Frida](https://github.com/frida/frida) : Dynamic instrumentation toolkit for developers, reverse-engineers, and security researchers.
  - [Fridump](https://github.com/Nightbringer21/fridump) : A universal memory dumper using Frida.
- [Imagemounter](https://github.com/ralphje/imagemounter) : Command line utility and Python package to ease the (un)mounting of forensic disk images.

### Recovering tool / Memory Extraction

- [Extundelete](http://extundelete.sourceforge.net/) : Utility for recovering deleted files from ext2, ext3 or ext4 partitions by parsing the journal.
- [Foremost](https://github.com/korczis/foremost) : A console program to recover files based on their headers, footers, and internal data structures.
- [MagicRescue](https://github.com/jbj/magicrescue) : Find and recover deleted files on block devices.
- [MemDump](https://github.com/kost/memdump) : Dumps system memory to stdout, skipping over holes in memory maps.
- [MemFetch](https://github.com/citypw/lcamtuf-memfetch) : Simple utility that can be used to dump process memory of any userspace process running on the system without affecting its execution.
- [Mxtract](https://github.com/rek7/mXtract) : Memory Extractor & Analyzer.
- [Recoverjpeg](https://github.com/samueltardieu/recoverjpeg) : Recover jpegs from damaged devices.
- [SafeCopy](https://doc.ubuntu-fr.org/safecopy) : A disk data recovery tool to extract data from damaged media.
- [Scrounge-Ntfs](https://github.com/lcorbasson/scrounge-ntfs) : Data recovery program for NTFS file systems.
- [TestDisk & PhotoRec](https://github.com/cgsecurity/testdisk) : TestDisk checks the partition and boot sectors of your disks. It is very useful in recovering lost partitions. PhotoRec is file data recovery software designed to recover lost pictures from digital camera memory or even hard disks. It has been extended to search also for non audio/video headers.

### Analysis / Gathering tool (Know your ennemies)

- [Autopsy](https://github.com/sleuthkit/autopsy) : The forensic browser. A GUI for the Sleuth Kit.
- [Bulk-extractor](https://github.com/simsong/bulk_extractor) : Bulk Email and URL extraction tool.
- [captipper](https://github.com/omriher/CapTipper) : Malicious HTTP traffic explorer tool.
- [Chromefreak](https://github.com/OsandaMalith/ChromeFreak) : A Cross-Platform Forensic Framework for Google Chrome.
- [SkypeFreak](https://github.com/OsandaMalith/SkypeFreak) : A Cross Platform Forensic Framework for Skype.
- [Dumpzilla](https://github.com/Busindre/dumpzilla) : A forensic tool for firefox.
- [Emldump](https://github.com/DidierStevens/DidierStevensSuite/blob/master/emldump.py) : Analyze MIME files.
- [Galleta](https://sourceforge.net/projects/odessa/files/Galleta/) : Examine the contents of the IE's cookie files for forensic purposes.
- [Guymager](https://guymager.sourceforge.io/) : A forensic imager for media acquisition.
- [Indxparse](https://github.com/williballenthin/INDXParse) : A Tool suite for inspecting NTFS artifacts.
- [IOSforensic](https://github.com/Flo354/iOSForensic) : iOS forensic tool.
- [IPBA2](https://github.com/PicciMario/iPhone-Backup-Analyzer-2) : IOS Backup Analyzer.
- [Iphoneanalyzer](https://github.com/foreni-packages/iphoneanalyzer) : Allows you to forensically examine or recover date from in iOS device.
- [LiMEaide](https://github.com/kd8bny/LiMEaide) : Remotely dump RAM of a Linux client and create a volatility profile for later analysis on your local host.
- [MboxGrep](https://sourceforge.net/projects/mboxgrep/) : A small, non-interactive utility that scans mail folders for messages matching regular expressions. It does matching against basic and extended POSIX regular expressions, and reads and writes a variety of mailbox formats.
- [Mobiusft](https://www.nongnu.org/mobiusft/) : An open-source forensic framework written in Python/GTK that manages cases and case items, providing an abstract interface for developing extensions.
- [Naft](https://blog.didierstevens.com/programs/network-appliance-forensic-toolkit/) : Network Appliance Forensic Toolkit.  
[Networkminer](https://www.netresec.com/?page=Networkminer) A Network Forensic Analysis Tool for advanced Network Traffic Analysis, sniffer and packet analyzer.
- [Nfex](https://github.com/deadbits/nfex) : A tool for extracting files from the network in real-time or post-capture from an offline tcpdump pcap savefile.
- [Ntdsxtract](https://github.com/csababarta/ntdsxtract) [windows]: Active Directory forensic framework.
- [Pasco](http://b2b-download.mcafee.com/products/tools/foundstone/pasco.zip) : Examines the contents of Internet Explorer's cache files for forensic purposes.                                          |
- [PcapXray](https://github.com/Srinivas11789/PcapXray) : Network Forensics Tool - To visualize a Packet Capture offline as a Network Diagram including device identification, highlight important communication and file extraction
- [ReplayProxy](https://github.com/sparrowt/replayproxy) : Forensic tool to replay web-based attacks (and also general HTTP traffic) that were captured in a pcap file.
- [Pdfbook-analyzer](https://sourceforge.net/projects/pdfbook/) : Utility for facebook memory forensics.
- [Pdfid](https://github.com/DidierStevens/DidierStevensSuite/blob/master/pdfid.py) : Scan a file to look for certain PDF keywords.
- [PdfResurrect](https://github.com/enferex/pdfresurrect) : A tool aimed at analyzing PDF documents.  
- [Peepdf](https://github.com/jesparza/peepdf) : A Python tool to explore PDF files in order to find out if the file can be harmful or not.
- [Pev](https://github.com/merces/pev) : Command line based tool for PE32/PE32+ file analysis.
- [Rekall](https://github.com/google/rekall) : Memory Forensic Framework.
- [Recuperabit](https://github.com/Lazza/RecuperaBit) : A tool for forensic file system reconstruction.  
- [Rifiuti2](https://github.com/abelcheung/rifiuti2) : A rewrite of rifiuti, a great tool from Foundstone folks for analyzing Windows Recycle Bin INFO2 file.
- [Rkhunter](http://rkhunter.sourceforge.net/) : Checks machines for the presence of rootkits and other unwanted tools.
- [Sleuthkit](https://github.com/sleuthkit/sleuthkit) : A library and collection of command line digital forensics tools that allow you to investigate volume and file system data.
- [Swap-digger](https://github.com/sevagas/swap_digger) : A tool used to automate Linux swap analysis during post-exploitation or forensics.
- [Vinetto](https://sourceforge.net/projects/vinetto/) : A forensics tool to examine Thumbs.db files.
- [Volafox](https://github.com/n0fate/volafox) : macOS Memory Analysis Toolkit.
- [Volatility](https://github.com/volatilityfoundation/volatility) : Advanced memory forensics framework.
- [Xplico](https://github.com/xplico/xplico) : Internet Traffic Decoder. Network Forensic Analysis Tool (NFAT).

### Data tampering

- [Exiftool](https://github.com/qazbnm456/awesome-web-security) : Reader and rewriter of EXIF informations that supports raw files.
- [Exiv2](https://github.com/Exiv2/exiv2) : Exif, Iptc and XMP metadata manipulation library and tools.
- [nTimetools](https://github.com/limbenjamin/nTimetools) : Timestomper and Timestamp checker with nanosecond accuracy for NTFS volumes.
- [Scalpel](https://github.com/sleuthkit/scalpel) : An open source data carving tool.
- [SetMace](https://github.com/jschicht/SetMace) : Manipulate timestamps on NTFS.

### Hiding process

- [Harness](https://github.com/droberson/harness) : Execute ELFs in memory.
- [Unhide](http://www.unhide-forensics.info/?Linux:Download) : A forensic tool to find processes hidden by rootkits, LKMs or by other techniques.  
- [Kaiser](https://github.com/ntraiseharderror/kaiser) : File-less persistence, attacks and anti-forensic capabilities (Windows 7 32-bit).  
- [Papa Shango](https://github.com/droberson/papa-shango) : Inject code into running processes with ptrace().
- [Saruman](https://github.com/elfmaster/saruman) : ELF anti-forensics exec, for injecting full dynamic executables into process image (With thread injection).

### Cleaner / Data Destruction / Wiping / FileSystem

- [BleachBit](https://github.com/bleachbit/bleachbit) : System cleaner for Windows and Linux.
- [ChainSaw](https://github.com/Inffinite/ChainSaw) : ChainSaw automates the process of shredding log files and bash history from a system. It is a tool that cleans up the bloody mess you left behind when you went for a stroll behind enemy lines.
- [Clear-EventLog](https://learn.microsoft.com/powershell/module/microsoft.powershell.management/clear-eventlog?view=powershell-5.1) : Powershell Command. Clears all entries from specified event logs on the local or remote computers.
- [DBAN](https://sourceforge.net/projects/dban/) : Darik's Boot and Nuke ("DBAN") is a self-contained boot image that securely wipes the hard disks of most computers. DBAN is appropriate for bulk or emergency data destruction.
- [delete-self-poc](https://github.com/LloydLabs/delete-self-poc) : A way to delete a locked file, or current running executable, on disk.
- [Forensia](https://github.com/PaulNorman01/Forensia) : Anti Forensics Tool For Red Teamers, Used For Erasing Footprints In The Post Exploitation Phase.
- [Hdpram](https://doc.ubuntu-fr.org/hdparm) : get/set hard disk parameters.
- [LogKiller](https://github.com/Rizer0/Log-killer) : Clear all your logs in linux/windows servers.
- [Meterpreter > clearev](https://github.com/rapid7/metasploit-payloads) : The meterpreter clearev command will clear the Application, System, and Security logs on a Windows system.
- [NTFS-3G](https://github.com/tuxera/ntfs-3g) : NTFS-3G Safe Read/Write NTFS Driver.
- [Nuke My LUKS](https://github.com/juliocesarfort/nukemyluks) : Network panic button designed to overwrite with random data the LUKS header of computers in a LAN.
- [Permanent-Eraser](https://github.com/edenwaith/Permanent-Eraser) : Secure file erasing utility for macOS.
- [Shred](https://doc.ubuntu-fr.org/shred) : Overwrite a file to hide its contents, and optionally delete it.
- [Silk-guardian](https://github.com/NateBrune/silk-guardian) : An anti-forensic kill-switch that waits for a change on your usb ports and then wipes your ram, deletes precious files, and turns off your computer.
- [Srm](https://sourceforge.net/projects/srm/) : Srm is a command-line compatible rm which overwrites file contents before unlinking.
- [Wipe](https://github.com/berke/wipe) : A Unix tool for secure deletion.
- [Wipedicks](https://github.com/Drewsif/wipedicks) : Wipe files and drives securely with randoms ASCII dicks.
- [wiper](https://github.com/r3nt0n/wiper) : Toolkit to perform secure destruction of sensitive virtual data, temporary files and swap memories.

### Password and Login

- [chntpw](https://doc.ubuntu-fr.org/tutoriel/chntpw) : Offline NT Password Editor - reset passwords in a Windows NT SAM user database file.
- [lazagne](https://github.com/AlessandroZ/LaZagne) : An open source application used to retrieve lots of passwords stored on a local computer.
- [Mimipenguin](https://github.com/huntergregal/mimipenguin) : A tool to dump the login password from the current linux user.

### Encryption / Obfuscation

- [BurnEye](https://github.com/packz/binary-encryption/tree/master/binary-encryption/burneye-stripped) : ELF encryption program.
- [cryptsetup](https://gitlab.com/cryptsetup/cryptsetup) : Utility used to conveniently set up disk encryption based
on the DMCrypt kernel module.
  - [cryptsetup-nuke-password](https://salsa.debian.org/pkg-security-team/cryptsetup-nuke-password) : Configure a special "nuke password" that
    can be used to destroy the encryption keys required to unlock the encrypted partitions.
- [ELFcrypt](https://github.com/droberson/ELFcrypt) : ELF crypter.
- [FreeOTFE](https://sourceforge.net/projects/freeotfe.mirror/) : A free "on-the-fly" transparent disk encryption program for PC & PDAs.
- [Midgetpack](https://github.com/arisada/midgetpack) : Midgetpack is a multiplatform secure ELF packer.
- [panic_bcast](https://github.com/niklasfemerstrand/panic_bcast) : Decentralized opsec panic button operating over UDP broadcasts and HTTP. Provides automatic ejection of encrypted drives as a safe-measure against cold-boot attacks.
- [Sherlocked](https://github.com/elfmaster/sherlocked) : Universal script packer-- transforms any type of script into a protected ELF executable, encrypted with anti-debugging.
  - [suicideCrypt](https://github.com/MonolithInd/suicideCrypt) : A toolset for creating cryptographically strong volumes that destroy themselves upon tampering (event) or via issued command.
- [Tchunt-ng](https://github.com/antagon/TCHunt-ng) : Reveal encrypted files stored on a filesystem.
- [TrueHunter](https://github.com/adoreste/truehunter) : Detect TrueCrypt containers using a fast and memory efficient approach.

### Policies / Logging (Event) / Monitoring

- [Auditpol](https://docs.microsoft.com/en-gb/windows-server/administration/windows-commands/auditpol) : Displays information about and performs functions to manipulate audit policies in Windows.
- [evtkit](https://github.com/yarox24/evtkit) : Fix acquired .evt - Windows Event Log files (Forensics) [windows]
- [Grokevt](https://github.com/ecbftw/grokevt) : A collection of scripts built for reading Windows® NT/2K/XP/2K eventlog files. [windows]
- [Lfle](https://github.com/williballenthin/LfLe) : Recover event log entries from an image by heurisitically looking for record structures.  
- [python-evtx](https://github.com/williballenthin/python-evtx) : A tool to parse the Windows XML Event Log (EVTX) format.
- [USBGuard](https://usbguard.github.io/) : Software framework for implementing USB device authorization policies (what kind of USB devices are authorized) as well as method of use policies (how a USB device may interact with the system).
- [wecutil](https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/wecutil) : Enables you to create and manage subscriptions to events that are forwarded from remote computers. The remote computer must support the WS-Management protocol. [windows]
- [Wevtutil](https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/wevtutil) : Enables you to retrieve information about event logs and publishers. You can also use this command to install and uninstall event manifests, to run queries, and to export, archive, and clear logs (windows server).

### Steganography

- [AudioStego](https://github.com/danielcardeenas/AudioStego) : Hides text or files inside audio files and retrieve them automatically.
- [ChessSteg](https://github.com/jes/chess-steg) : Steganography in chess games.
- [Cloakify](https://github.com/TryCatchHCF/Cloakify) : Transforms any filetype into a list of harmless-looking strings. This lets you hide the file in plain sight, and transfer the file without triggering alerts.
- [Jsteg](https://github.com/lukechampine/jsteg) : jsteg is a package for hiding data inside jpeg files.
- [Mp3nema](https://github.com/enferex/mp3nema) : A tool aimed at analyzing and capturing data that is hidden between frames in an MP3 file or stream, otherwise noted as "out of band" data.
- [PacketWhisper](https://github.com/TryCatchHCF/PacketWhisper) : Stealthily exfiltrate data and defeat attribution using DNS queries and text-based steganography.
- [steg86](https://github.com/woodruffw/steg86) : Format-agnostic steganographic tool for x86 and AMD64 binaries. You can use it to hide information in compiled programs, regardless of executable format (PE, ELF, Mach-O, raw, &c).
- [steganography](https://github.com/7thSamurai/steganography) : Simple C++ Image Steganography tool to encrypt and hide files insde images using Least-Significant-Bit encoding.
- [Steganography](https://github.com/ragibson/Steganography) : Least Significant Bit Steganography for bitmap images (.bmp and .png), WAV sound files, and byte sequences.
- [StegaStamp](https://github.com/tancik/StegaStamp) : Invisible Hyperlinks in Physical Photographs.
- [StegCloak](https://github.com/KuroLabs/stegcloak) : Hide secrets with invisible characters in plain text securely using passwords.
- [Stegdetect](https://github.com/abeluck/stegdetect) : Automated tool for detecting steganographic content in images.
- [StegFS](https://github.com/albinoloverats/stegfs) : A FUSE based steganographic file system.
- [Steghide](http://steghide.sourceforge.net/) : Steganography program that is able to hide data in various kinds of image- and audio-files.
- [Stegify](https://github.com/DimitarPetrov/stegify) : Go tool for LSB steganography, capable of hiding any file within an image.
- [Stego](https://github.com/ajmwagar/stego) : stego is a steganographic swiss army knife.
  - [StegoGAN](https://github.com/DAI-Lab/SteganoGAN) : A tool for creating steganographic images using adversarial training.
- [stego-toolkit](https://github.com/DominicBreuker/stego-toolkit) : This project is a Docker image useful for solving Steganography challenges as those you can find at CTF platforms.
- [StegoVeritas](https://github.com/bannsec/stegoVeritas) : Yet another Stego Tool.
- [tweetable-polyglot-png](https://github.com/DavidBuchanan314/tweetable-polyglot-png) : Pack up to 3MB of data into a tweetable PNG polyglot file.

### Malware / AV

- [Malheur](https://github.com/rieck/malheur) : A tool for the automatic analyze of malware behavior.
- [MalwareDetect](https://github.com/rfxn/linux-malware-detect) : Submits a file's SHA1 sum to VirusTotal to determine whether it is a known piece of malware.

### OS/VM

- [HiddenVM](https://github.com/aforensics/HiddenVM) : Use any desktop OS without leaving a trace.  
- [Tails](https://tails.boum.org/index.en.html) : portable operating system that protects against surveillance and censorship.

### Hardware

- [BusKill](https://github.com/BusKill/buskill-app) : BusKill is an hardware and software project that uses a hardware tripwire/dead-man-switch to trigger a computer to lock or shutdown if the user is physically separated from their machine.
- [Day Tripper](https://github.com/dekuNukem/daytripper) : Hide-My-Windows Laser Tripwire.
- [DoNotDisturb](https://github.com/objective-see/DoNotDisturb) : Security tool for macOS that aims to detect unauthorized physical access to your laptop.
- [Silk Guardian](https://github.com/NateBrune/silk-guardian) : Anti-forensic kill-switch that waits for a change on your usb ports and then wipes your ram, deletes precious files, and turns off your computer.
- [USB Kill](https://github.com/hephaest0s/usbkill) : Anti-forensic kill-switch that waits for a change on your USB ports and then immediately shuts down your computer.
- [USB Death](https://github.com/trpt/usbdeath) : Anti-forensic tool that writes udev rules for known usb devices and do some things at unknown usb insertion or specific usb device removal.
- [xxUSBSentinel](https://github.com/thereisnotime/xxUSBSentinel) : Windows anti-forensics USB monitoring tool.

### Android App

- [Lockup](https://github.com/levlesec/lockup) : A proof-of-concept Android application to detect and defeat some of the Cellebrite UFED forensic toolkit extraction techniques.
- [Ripple](https://github.com/guardianproject/ripple) : A "panic button" app for triggering a "ripple effect" across apps that are set up to respond to panic events.

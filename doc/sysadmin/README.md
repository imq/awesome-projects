- [Sysadmin-Software](#sys-software)
    - [Automation](#automation)
    - [Backups](#backups)
    - [Build and software organization tools](#build-and-software-organization-tools)
    - [ChatOps](#chatops)
    - [Client management](#client-management)
    - [Cloning](#cloning)
    - [Cloud Computing](#cloud-computing)
    - [Cloud Orchestration](#cloud-orchestration)
    - [Code Review](#code-review)
    - [Configuration Management Database](#configuration-management-database)
    - [Configuration Management](#configuration-management)
    - [Continuous Integration & Continuous Deployment](#continuous-integration--continuous-deployment)
    - [Control Panels](#control-panels)
    - [Databases](#databases)
    - [Deployment Automation](#deployment-automation)
    - [Diagramming](#diagramming)
    - [Distributed Filesystems](#distributed-filesystems)
    - [DNS - Servers](#dns---servers)
    - [DNS - Control Panels](#dns---control-panels)
    - [DNS - Domain Management](#dns---domain-management)
    - [Editors](#editors)
    - [Identity Management](#identity-management)
    - [Identity Management - LDAP](#identity-management---ldap)
    - [Identity Management - Tools and web interfaces](#identity-management---tools-and-web-interfaces)
    - [Identity Management - Single Sign-On SSO](#identity-management---single-sign-on-sso)
    - [IT Asset Management](#it-asset-management)
    - [Log Management](#log-management)
    - [Mail Clients](#mail-clients)
    - [Monitoring](#monitoring)
    - [Status Pages](#status-pages)
    - [Metric & Metric Collection](#metric--metric-collection)
    - [Network Configuration Management](#network-configuration-management)
    - [Newsletters](#newsletters)
    - [Packaging](#packaging)
    - [Project Management](#project-management)
    - [Queuing](#queuing)
    - [Router](#router)
    - [Remote Management](#remote-management)
    - [Service Discovery](#service-discovery)
    - [Software Containers](#software-containers)
    - [Troubleshooting](#troubleshooting)
    - [Version control](#version-control)
    - [Virtualization](#virtualization)
    - [VPN](#vpn)
    - [Web](#web)
    - [SSH](#apps)
      - [`.ssh/config`](#sshconfig)
      - [Tools using the *SSH* protocol](#tools-using-the-ssh-protocol)
      - [Servers](#servers)
      - [Network](#network)
      - [Multiplexers](#multiplexers)
      - [SSH Keys / Authentication](#ssh-keys--authentication)
      - [SSH agent](#ssh-agent)
      - [Tools](#tools)
      - [Automation](#automation)
      - [Web](#web)
      - [Testing / Honeypots](#testing--honeypots)
      - [Alternatives to SSH](#alternatives-to-ssh)
    - [Libraries](#libraries)
    - [Resources](#resources)
      - [Tutorials](#tutorials)
      - [Security](#security)
      - [Blogs](#blogs)
      - [Books](#books)
      - [Communities / Forums](#communities--forums)
      - [Newsletters](#newsletters)
      - [Repositories](#repositories)
      - [Websites](#websites)
- [DevOps](#devops)
  - [Cloud Platforms](#cloud-platforms)
  - [Open Source Cloud Platforms](#open-source-cloud-platforms)
  - [Operating Systems](#operating-systems)
  - [Distributed Filesystems](#distributed-filesystems)
  - [Applications Platforms](#applications-platforms)
  - [Container Image Registry](#container-image-registry)
  - [Automation & Orchestration](#automation--orchestration)
  - [Continuous Integration & Delivery](#continuous-integration--delivery)
  - [Source Code Management](#source-code-management)
  - [Web Servers](#web-servers)
  - [SSL](#ssl)
  - [Databases](#databases)
  - [Observability and Monitoring](#observability--monitoring)
  - [Service Discovery & Service Mesh](#service-discovery--service-mesh)
  - [Chaos Engineering](#chaos-engineering)
  - [API Gateway](#api-gateway)
  - [Code review](#code-review)
  - [Distributed messaging](#distributed-messaging)
  - [Programming Languages](#programming-languages)
  - [Chat and ChatOps](#chat-and-chatops)
  - [Secret Management](#secret-management)
  - [Sharing](#sharing)

--------------------
## SSH Contents

## Apps

### `.ssh/config`

* [`assh`](https://github.com/moul/assh) [![stars](https://img.shields.io/github/stars/moul/advanced-ssh-config.svg?style=social&label=stars)](https://github.com/moul/advanced-ssh-config) - Transparent wrapper (ProxyCommand) that adds regex, aliases, gateways, includes, dynamic hostnames to *SSH* and `ssh-config`. _Previously: `advanced-ssh-config`_
* [storm](https://github.com/emre/storm) [![stars](https://img.shields.io/github/stars/emre/storm.svg?style=social&label=stars)](https://github.com/emre/storm) - Manage your *SSH* like a boss.
* [ansible-ssh-config](https://github.com/gaqzi/ansible-ssh-config) [![stars](https://img.shields.io/github/stars/gaqzi/ansible-ssh-config.svg?style=social&label=stars)](https://github.com/gaqzi/ansible-ssh-config) - Letting *Ansible* manage `ssh_config`.
* [ec2ssh](https://github.com/mirakui/ec2ssh) [![stars](https://img.shields.io/github/stars/mirakui/ec2ssh.svg?style=social&label=stars)](https://github.com/mirakui/ec2ssh) - A `ssh_config` manager for *AWS EC2*.
* [ssh-config](https://github.com/dbrady/ssh-config) [![stars](https://img.shields.io/github/stars/dbrady/ssh-config.svg?style=social&label=stars)](https://github.com/dbrady/ssh-config) - A tool to help manage your `.ssh/config` file.

### Tools using the *SSH* protocol

* [scp](http://linux.die.net/man/1/scp) - Secure remote file copy utility over *SSH*.
* [rsync](https://rsync.samba.org) - Fast incremental transfer utility that supports *SSH*.
* [sftp](https://en.wikipedia.org/wiki/SSH_File_Transfer_Protocol) - File transfer protocol over *SSH*.
* [curl](http://curl.haxx.se) - Command line tool and library to transfer data (support `sftp`).

### Servers

* [sshportal](https://github.com/moul/sshportal) [![stars](https://img.shields.io/github/stars/moul/sshportal.svg?style=social&label=stars)](https://github.com/moul/sshportal) - simple, fun, and transparent SSH (& Telnet) Bastion Server
* [ssh2docker](https://github.com/moul/ssh2docker) [![stars](https://img.shields.io/github/stars/moul/ssh2docker.svg?style=social&label=stars)](https://github.com/moul/ssh2docker) - *SSH* server to Docker containers.
* [ssh-proxy](https://github.com/ml-tooling/ssh-proxy) [![stars](https://img.shields.io/github/stars/ml-tooling/ssh-proxy.svg?style=social&label=stars)](https://github.com/ml-tooling/ssh-proxy) - Dockerized SSH bastion to proxy SSH connections to arbitrary containers.
* [whosthere](https://github.com/FiloSottile/whosthere) [![stars](https://img.shields.io/github/stars/FiloSottile/whosthere.svg?style=social&label=stars)](https://github.com/FiloSottile/whosthere) - A *SSH* server that knows who you are. `$ ssh whoami.filippo.io`.
* [sshfront](https://github.com/gliderlabs/sshfront) [![stars](https://img.shields.io/github/stars/gliderlabs/sshfront.svg?style=social&label=stars)](https://github.com/gliderlabs/sshfront) - Programmable *SSH* frontend.
* [ssh-chat](https://github.com/shazow/ssh-chat) [![stars](https://img.shields.io/github/stars/shazow/ssh-chat.svg?style=social&label=stars)](https://github.com/shazow/ssh-chat) - Chat over *SSH*.
* [sshcommand](https://github.com/dokku/sshcommand) [![stars](https://img.shields.io/github/stars/dokku/sshcommand.svg?style=social&label=stars)](https://github.com/dokku/sshcommand) - Turn *SSH* into a thin client specifically for your app.
* [sshmuxd](https://github.com/joushou/sshmuxd) [![stars](https://img.shields.io/github/stars/joushou/sshmuxd.svg?style=social&label=stars)](https://github.com/joushou/sshmuxd) - `sshmux` frontend.
* [x84](https://github.com/jquast/x84) [![stars](https://img.shields.io/github/stars/jquast/x84.svg?style=social&label=stars)](https://github.com/jquast/x84) - A *python* `telnet`/`ssh` server for modern *UTF-8* and classic *cp437* network virtual terminals. In spirit of classic software such as *ami/x*, *teleguard*, *renegade*, *iniquity*.
* [teleport](https://github.com/gravitational/teleport) [![stars](https://img.shields.io/github/stars/gravitational/teleport.svg?style=social&label=stars)](https://github.com/gravitational/teleport) - Modern *SSH* server for clusters and teams.
* [ShellHub](https://github.com/shellhub-io/shellhub) [![stars](https://img.shields.io/github/stars/shellhub-io/shellhub.svg?style=social&label=stars)](https://github.com/shellhub-io/shellhub) - A *SSH* gateway for remotely accessing any Linux device behind firewall and NAT.

### Network

* [Mosh](https://mosh.mit.edu) - The mobile shell.
* [sshfs](https://github.com/libfuse/sshfs) [![stars](https://img.shields.io/github/stars/libfuse/sshfs.svg?style=social&label=stars)](https://github.com/libfuse/sshfs) - Filesystem client based on the *SSH* File Transfer Protocol.
* [ngrok](https://github.com/inconshreveable/ngrok) [![stars](https://img.shields.io/github/stars/inconshreveable/ngrok.svg?style=social&label=stars)](https://github.com/inconshreveable/ngrok) - Introspected tunnels to localhost.
* [localtunnel](https://github.com/progrium/localtunnel) [![stars](https://img.shields.io/github/stars/progrium/localtunnel.svg?style=social&label=stars)](https://github.com/progrium/localtunnel) - Expose localhost servers to the Internet.
* [sshuttle](https://github.com/sshuttle/sshuttle) [![stars](https://img.shields.io/github/stars/sshuttle/sshuttle.svg?style=social&label=stars)](https://github.com/sshuttle/sshuttle) - Transparent proxy server that works as a poor man's *VPN*. Forwards over `ssh`. Doesn't require admin. Works with *Linux* and *MacOS*. Supports *DNS tunneling*.
* [sshttp](https://github.com/stealth/sshttp) [![stars](https://img.shields.io/github/stars/stealth/sshttp.svg?style=social&label=stars)](https://github.com/stealth/sshttp) - *SSH*/*HTTP(S)* multiplexer. Run a webserver and a `sshd` on the same port w/o changes.
* [switcher](https://github.com/jamescun/switcher) [![stars](https://img.shields.io/github/stars/jamescun/switcher.svg?style=social&label=stars)](https://github.com/jamescun/switcher) - Run *SSH* and *HTTP(S)* on the same port.
* [sslh](https://github.com/yrutschle/sslh) [![stars](https://img.shields.io/github/stars/yrutschle/sslh.svg?style=social&label=stars)](https://github.com/yrutschle/sslh) - Applicative Protocol Multiplexer (i.e: *SSH* + *HTTPS*).
* [tund](https://github.com/aphyr/tund) [![stars](https://img.shields.io/github/stars/aphyr/tund.svg?style=social&label=stars)](https://github.com/aphyr/tund) - *SSH* reverse tunnel daemon.
* [autossh](http://www.harding.motd.ca/autossh/) - Automatically respawn *SSH* session after network interruption.
* [wssh](https://github.com/aluzzardi/wssh) [![stars](https://img.shields.io/github/stars/aluzzardi/wssh.svg?style=social&label=stars)](https://github.com/aluzzardi/wssh) - *SSH* to WebSockets Bridge.
* [docker-volume-sshfs](https://github.com/vieux/docker-volume-sshfs) [![stars](https://img.shields.io/github/stars/vieux/docker-volume-sshfs.svg?style=social&label=stars)](https://github.com/vieux/docker-volume-sshfs) - `sshfs` docker volume plugin.
* [quicssh](https://github.com/moul/quicssh) [![stars](https://img.shields.io/github/stars/moul/quicssh.svg?style=social&label=stars)](https://github.com/moul/quicssh) - QUIC proxy for SSH
* [sshpiper](https://github.com/tg123/sshpiper) [![stars](https://img.shields.io/github/stars/tg123/sshpiper.svg?style=social&label=stars)](https://github.com/tg123/sshpiper) - The missing reverse proxy for ssh scp.
* [sshhub](https://sshhub.de) - Web Service: access your SSH servers behind firewalls (ssh-teamviewer).

### Multiplexers

* [tmux](https://tmux.github.io) - Terminal multiplexer.
* [clusterssh](https://github.com/duncs/clusterssh) [![stars](https://img.shields.io/github/stars/duncs/clusterssh.svg?style=social&label=stars)](https://github.com/duncs/clusterssh) - Cluster admin via *SSH*.
* [tmux-cssh](https://github.com/dennishafemann/tmux-cssh) [![stars](https://img.shields.io/github/stars/dennishafemann/tmux-cssh.svg?style=social&label=stars)](https://github.com/dennishafemann/tmux-cssh) - `tmux` with a *ClusterSSH*-like behavior.
* [tm](https://github.com/Ganneff/tm) [![stars](https://img.shields.io/github/stars/Ganneff/tm.svg?style=social&label=stars)](https://github.com/Ganneff/tm) - `tmux` manager / helper.
* [i2cssh](https://github.com/wouterdebie/i2cssh) [![stars](https://img.shields.io/github/stars/wouterdebie/i2cssh.svg?style=social&label=stars)](https://github.com/wouterdebie/i2cssh) - `csshX` like *SSH* tool for *iTerm2*.
* [ClusterSSH](http://sourceforge.net/projects/clusterssh/) - Controls a number of `xterm` windows via a single graphical console.

### *SSH* keys / Authentication

* [authy-ssh](https://github.com/authy/authy-ssh) [![stars](https://img.shields.io/github/stars/authy/authy-ssh.svg?style=social&label=stars)](https://github.com/authy/authy-ssh) - Easy *two-factor* authentication for *SSH* servers.
* [github-auth](https://github.com/chrishunt/github-auth) [![stars](https://img.shields.io/github/stars/chrishunt/github-auth.svg?style=social&label=stars)](https://github.com/chrishunt/github-auth) - *SSH* key management for GitHub users.
* [cipherhub](https://github.com/substack/cipherhub) [![stars](https://img.shields.io/github/stars/substack/cipherhub.svg?style=social&label=stars)](https://github.com/substack/cipherhub) - Encrypt messages based on *SSH* public keys with easy import from GitHub.
* [Slack notifications](http://www.ryanbrink.com/slack-ssh-session-notifications/) ([archived version](https://web.archive.org/web/20160505202303/http://www.ryanbrink.com/slack-ssh-session-notifications/)) - Guide to setup Slack notifications (can be modified for other services).
* [totp-ssh-fluxer](https://github.com/benjojo/totp-ssh-fluxer) [![stars](https://img.shields.io/github/stars/benjojo/totp-ssh-fluxer.svg?style=social&label=stars)](https://github.com/benjojo/totp-ssh-fluxer) - A way to make sure your `sshd` port changes every 30 seconds.
* [github-keygen](https://github.com/dolmen/github-keygen) [![stars](https://img.shields.io/github/stars/dolmen/github-keygen.svg?style=social&label=stars)](https://github.com/dolmen/github-keygen) - Easy creation of secure *SSH* configuration for your GitHub account(s).
* [kr](https://github.com/KryptCo/kr) [![stars](https://img.shields.io/github/stars/dolmen/github-keygen.svg?style=social&label=stars)](https://github.com/KryptCo/kr) - Kr agent that route access request to the paired mobile phone where Kryptonite is installed.
* [ServerAuth](https://serverauth.com) - Automatically sync SSH access across servers
* [HIBA](https://github.com/google/hiba) [![stars](https://img.shields.io/github/stars/google/hiba.svg?style=social&label=stars)](https://github.com/google/hiba) - Central management of access to a fleet of machines without pushing authorized_users files.

### *SSH* agent

* [ssh-ident](https://github.com/ccontavalli/ssh-ident) [![stars](https://img.shields.io/github/stars/ccontavalli/ssh-ident.svg?style=social&label=stars)](https://github.com/ccontavalli/ssh-ident) - Different agents and different keys for different projects, with `ssh`.
* [oh-my-zsh/plugins/ssh-agent](https://github.com/robbyrussell/oh-my-zsh) [![stars](https://img.shields.io/github/stars/robbyrussell/oh-my-zsh.svg?style=social&label=stars)](https://github.com/robbyrussell/oh-my-zsh) - `ssh-agent` plugin for `zsh`.
* [sshecret](https://github.com/thcipriani/sshecret) - Automatically create and manage multiple agents for multiple keys.

### Tools

* [xxh](https://github.com/xxh/xxh) [![stars](https://img.shields.io/github/stars/xxh/xxh.svg?style=social&label=stars)](https://github.com/xxh/xxh) - Bring your favorite shell wherever you go through the ssh.
* [sshrc](https://github.com/danrabinowitz/sshrc) [![stars](https://img.shields.io/github/stars/danrabinowitz/sshrc.svg?style=social&label=stars)](https://github.com/danrabinowitz/sshrc) - Bring your `.bashrc`, `.vimrc`, etc. with you when you `ssh`.
* [kyrat](https://github.com/fsquillace/kyrat) [![stars](https://img.shields.io/github/stars/fsquillace/kyrat.svg?style=social&label=stars)](https://github.com/fsquillace/kyrat) - SSH wrapper script that brings your dotfiles always with you on Linux and OSX.
* [ssh-vault](https://github.com/ssh-vault/ssh-vault) [![stars](https://img.shields.io/github/stars/ssh-vault/ssh-vault.svg?style=social&label=stars)](https://github.com/ssh-vault/ssh-vault) - encrypt/decrypt files using ssh keys
* [ssh-ping](https://github.com/vaporup/ssh-tools) [![stars](https://img.shields.io/github/stars/vaporup/ssh-tools.svg?style=social&label=stars)](https://github.com/vaporup/ssh-tools) - check if host is reachable using ssh_config
* [SSHPry v2](https://github.com/nopernik/SSHPry2.0) [![stars](https://img.shields.io/github/stars/nopernik/SSHPry2.0.svg?style=social&label=stars)](https://github.com/nopernik/SSHPry2.0) - Spy & Control os SSH Connected client's TTY
* [redial](https://github.com/taypo/redial) [![stars](https://img.shields.io/github/stars/taypo/redial?style=social)](https://github.com/taypo/redial) - Terminal Based SSH Session Manager for Unix Systems

### Automation

* [Ansible](https://github.com/ansible/ansible) [![stars](https://img.shields.io/github/stars/ansible/ansible.svg?style=social&label=stars)](https://github.com/ansible/ansible) - App deployment, configuration management and orchestration over *SSH*.
* [rtop](https://github.com/rapidloop/rtop) [![stars](https://img.shields.io/github/stars/rapidloop/rtop.svg?style=social&label=stars)](https://github.com/rapidloop/rtop) - Interactive, remote system monitoring tool based on *SSH*.
* [DSH - Dancer's shell / distributed shell](https://www.netfort.gr.jp/~dancer/software/dsh.html.en) - Wrapper for executing multiple remote shell commands from one command line.
* [parallel-ssh](https://github.com/ParallelSSH/parallel-ssh) [![stars](https://img.shields.io/github/stars/ParallelSSH/parallel-ssh.svg?style=social&label=stars)](https://github.com/ParallelSSH/parallel-ssh) - Provides parallel versions of OpenSSH and related tools.
* [SSH Power Tool](https://code.google.com/p/sshpt/) - Execute commands and upload files to many servers simultaneously without using pre-shared keys.

### Web

* [Secure Shell chrome extension](https://chrome.google.com/webstore/detail/secure-shell/pnhechapfaindjhompbnflcldabbghjo?hl=en)
* [GateOne](https://github.com/liftoff/GateOne) [![stars](https://img.shields.io/github/stars/liftoff/GateOne.svg?style=social&label=stars)](https://github.com/liftoff/GateOne) - HTML5-powered terminal emulator and *SSH* client.
* [KeyBox](https://github.com/skavanagh/KeyBox) [![stars](https://img.shields.io/github/stars/skavanagh/KeyBox.svg?style=social&label=stars)](https://github.com/skavanagh/KeyBox) - Web-based *SSH* console that centrally manages administrative access to systems.
* [Apache Guacamole](https://guacamole.incubator.apache.org/) - Apache Guacamole is a HTML5 based clientless remote desktop gateway. It supports standard protocols like VNC, RDP, and SSH.
* [SSHmon](https://github.com/hpello/sshmon) [![stars](https://img.shields.io/github/stars/hpello/sshmon.svg?style=social&label=stars)](https://github.com/hpello/sshmon) - Real-time GUI to monitor SSH connections and establish port forwardings.

### Testing / Honeypots

* [ssh-hammer](https://github.com/shazow/ssh-hammer) [![stars](https://img.shields.io/github/stars/shazow/ssh-hammer.svg?style=social&label=stars)](https://github.com/shazow/ssh-hammer) - *SSH* load testing tool.
* [kippo](https://github.com/desaster/kippo) [![stars](https://img.shields.io/github/stars/desaster/kippo.svg?style=social&label=stars)](https://github.com/desaster/kippo) - *SSH* Honeypot.
* [cowrie](https://github.com/micheloosterhof/cowrie) [![stars](https://img.shields.io/github/stars/micheloosterhof/cowrie.svg?style=social&label=stars)](https://github.com/micheloosterhof/cowrie) - *SSH* Honeypot (based on kippo).
* [sshmitm](http://linux.die.net/man/8/sshmitm) - *SSH* monkey-in-the-middle.
* [ssh-audit](https://github.com/arthepsy/ssh-audit) [![stars](https://img.shields.io/github/stars/arthepsy/ssh-audit.svg?style=social&label=stars)](https://github.com/arthepsy/ssh-audit) - A tool for *SSH* server auditing.
* [sshesame](https://github.com/jaksi/sshesame) [![stars](https://img.shields.io/github/stars/jaksi/sshesame.svg?style=social&label=stars)](https://github.com/jaksi/sshesame) - A fake SSH server that lets everyone in and logs their activity.


### Alternatives to *SSH*

* [GoTTY](https://github.com/yudai/gotty) [![stars](https://img.shields.io/github/stars/yudai/gotty.svg?style=social&label=stars)](https://github.com/yudai/gotty) - Share your terminal as web application.
* [telnet](http://www.telnet.org/htm/faq.htm) - An unencrypted network protocol and an application used to connect to remote computers and issue commands.
* [ttyd](https://github.com/tsl0922/ttyd) [![stars](https://img.shields.io/github/stars/tsl0922/ttyd.svg?style=social&label=stars)](https://github.com/tsl0922/ttyd) - Share your terminal over the web.
* [rsh](https://en.wikipedia.org/wiki/Remote_Shell) - An unencrypted network protocol and application used to connect to remote computers and issue commands.

## Libraries

* C/C++
  * [libssh](https://www.libssh.org) - The *SSH* library.
* Golang
  * [crypto/ssh](https://godoc.org/golang.org/x/crypto/ssh) - Built-in *SSH* client and server library.
  * [sftp](https://github.com/pkg/sftp) [![stars](https://img.shields.io/github/stars/pkg/sftp.svg?style=social&label=stars)](https://github.com/pkg/sftp) - *SFTP* support for the go.crypto/ssh package.
  * [go-sshkit](https://github.com/shazow/go-sshkit) [![stars](https://img.shields.io/github/stars/shazow/go-sshkit.svg?style=social&label=stars)](https://github.com/shazow/go-sshkit) - Toolkit for building *SSH* servers and clients in Go.
  * [Socker](https://github.com/cosiner/socker) [![stars](https://img.shields.io/github/stars/cosiner/socker.svg?style=social&label=stars)](https://github.com/cosiner/socker) - Library for Go to simplify the use of *SSH*.
  * [go-sshkeys](https://github.com/moul/go-sshkeys) - Golang SSH Keys manipulation library
* Java
  * [jsch](http://www.jcraft.com/jsch/) - Pure *java*, *BSD* licensed, *SSH2* client library.
* Javascript/Node.js
  * [ssh2](https://github.com/mscdex/ssh2) [![stars](https://img.shields.io/github/stars/mscdex/ssh2.svg?style=social&label=stars)](https://github.com/mscdex/ssh2) - *SSH2* client and server modules written in pure *JavaScript* for *node.js*.
* Python
  * [paramiko](https://github.com/paramiko/paramiko) [![stars](https://img.shields.io/github/stars/paramiko/paramiko.svg?style=social&label=stars)](https://github.com/paramiko/paramiko) - Native *Python* *SSHv2* protocol library.
* Ruby
  * [net-ssh](https://github.com/net-ssh/net-ssh) [![stars](https://img.shields.io/github/stars/net-ssh/net-ssh.svg?style=social&label=stars)](https://github.com/net-ssh/net-ssh) - Pure *Ruby* implementation of an *SSH* (protocol 2) client.

--------------------
## Software

### Automation

**[`^        back to top        ^`](#sys-software)**

*Automation build.*

- [Apache Ant](https://ant.apache.org/) - Automation build tool, similar to make, written in Java.
- [Apache Maven](http://maven.apache.org/) - Build automation tool mainly for Java.
- [Bazel](http://www.bazel.io/) - Google's build system.
- [Bolt](https://puppet.com/products/bolt) - You can use Bolt to run one-off tasks, scripts to automate the provisioning and management of some nodes, you can use Bolt to move a step beyond scripts, and make them shareable.
- [GNU Make](http://www.gnu.org/software/make/) - The most popular automation build tool for many purposes.
- [Gradle](http://gradle.org/) - Another build automation system.
- [Rake](https://github.com/ruby/rake) - Build automation tool similar to Make, written in and extensible in Ruby.


### Backups

**[`^        back to top        ^`](#sys-software)**

*Backup software.* Also see [Restic's list of Linux backup software](https://github.com/restic/others).

- [Amanda](http://www.amanda.org/) - Client-server model backup tool.
- [Backupninja](https://0xacab.org/liberate/backupninja) - Lightweight, extensible meta-backup system.
- [BackupPC](https://backuppc.github.io/backuppc/) - BackupPC is a high-performance system for backing up to disk.
- [Bareos](http://www.bareos.org/en/) - A fork of Bacula backup tool.
- [Barman](http://www.pgbarman.org) - Backup and Recovery Manager for disaster recovery of PostgreSQL servers.
- [BorgBackup](https://github.com/borgbackup/borg) - A fork of [Attic](https://attic-backup.org) deduplicating backup program written in Python.
- [Burp](http://burp.grke.org/) - Network backup and restore program.
- [DREBS](https://github.com/dojo4/drebs) - AWS EBS backup script that supports strategies.
- [Dar](http://dar.linux.free.fr/) - Which stands for Disk ARchive, is a robust and rich featured archiving and backup software of the tar style. ([Source Code](https://github.com/Edrusb/DAR)) `GPL-2.0` `C++`
- [Duplicati](http://www.duplicati.com) - Multiple backends, encryption, web-ui and multi-OS backup tool.
- [Duplicity](http://duplicity.nongnu.org/) - Encrypted bandwidth-efficient backup using the rsync algorithm.
- [Elkarbackup](https://github.com/elkarbackup/elkarbackup) - Backup solution based on RSnapshot with a simple web interface
- [rclone](https://rclone.org/) - a command line program to sync files and directories to and from several cloud storage systems/providers.
- [Rdiff-backup](http://www.nongnu.org/rdiff-backup/) - An easy A remote incremental backup of all your files.
- [Restic](https://restic.net/) - Secure, remote backup tool. Designed to be easy, fast, verifiable and efficient.
- [Rsnapshot](http://rsnapshot.org/) - Filesystem Snapshotting Utility.
- [Shield](https://github.com/starkandwayne/shield) - A pluggable architecture for backup and restore of database systems.
- [Snebu](http://www.snebu.com/) – Snapshot backup with global multi-client deduplication and transparent compression.
- [UrBackup](http://www.urbackup.org/) - Another client-server backup system.
- [ZBackup](http://zbackup.org/) - A versatile deduplicating backup tool.


### Build and software organization tools

**[`^        back to top        ^`](#sys-software)**

*Build and software organization tools.*

- [EasyBuild](https://easybuild.readthedocs.org/en/latest/) - EasyBuild builds software and modulefiles for High Performance Computing (HPC) systems in an efficient way.
- [environment-modules Lmod](https://www.tacc.utexas.edu/research-development/tacc-projects/lmod) - Lmod is a Lua based module system that easily handles the MODULEPATH Hierarchical problem.
- [HPCBIOS](http://hpcbios.readthedocs.org/en/latest/) - HPCBIOS is an effort to setup a common, well-documented and reproducible, environment spanning across multiple HPC systems & sites, *inclusive* of documentation.
- [Spack](https://spack.io/) - A flexible package manager that supports multiple versions, configurations, platforms, and compilers.


### ChatOps

**[`^        back to top        ^`](#sys-software)**

*Conversation-driven development and management. See https://www.reddit.com/r/chatops for more information.*

- [Eggdrop](http://www.eggheads.org/) - The oldest Internet Relay Chat (IRC) bot still in active development. ([Source Code](https://github.com/eggheads/eggdrop)) `GPL-2.0` `C`
- [Errbot](http://errbot.io/) - a plugin based chatbot designed to be easily deployable, extensible and maintainable. ([Source Code](https://github.com/errbotio/errbot)) `GPL-3.0` `Python`
- [Hubot](https://hubot.github.com/) - A customizable, life embetterment robot. ([Source Code](https://github.com/hubotio/hubot)) `MIT` `Nodejs`


### Client management

**[`^        back to top        ^`](#sys-software)**

Managing software on desktop computers.

_See also: [IT Asset Management](#it-asset-management)_

- [Chocolatey](https://chocolatey.org/) – The package manager for Windows. ([Source Code](https://github.com/chocolatey/choco)) `Apache-2.0` `C#/PowerShell`


### Cloning

**[`^        back to top        ^`](#sys-software)**

*Cloning software.*

- [Clonezilla](http://clonezilla.org/) - Partition and disk imaging/cloning program. ([Source Code](https://clonezilla.org/downloads/src/)) `GPL-2.0/Other` `Perl/Shell/Other`
- [Fog](https://www.fogproject.org/) - Cloning/imaging solution/rescue suite. ([Sorce Code](https://github.com/FOGProject/fogproject)) `GPL-3.0` `PHP/Shell`


### Cloud Computing

**[`^        back to top        ^`](#sys-software)**

- [CloudStack](http://cloudstack.apache.org/) - Cloud computing software for creating, managing, and deploying infrastructure cloud services. ([Source Code](https://github.com/apache/cloudstack))
- [Cobbler](http://cobbler.github.io/) - Cobbler is a Linux installation server that allows for rapid setup of network installation environments. ([Source Code](https://github.com/cobbler/cobbler))
- [Mesos](http://mesos.apache.org/) - Develop and run resource-efficient distributed systems.
- [OpenNebula](http://opennebula.org/) - User-driven cloud management platform for sysadmins and devops.
- [Openshift](http://www.openshift.org) - PaaS product from Red Hat.
- [OpenStack](https://www.openstack.org/) - Build private and public clouds.
- [The Foreman](http://theforeman.org/) - Complete lifecycle management tool for physical and virtual servers. FOSS.
- [Tsuru](https://tsuru.io) - Tsuru is an extensible Platform as a Service software.


### Cloud Orchestration

**[`^        back to top        ^`](#sys-software)**

- [BOSH](http://bosh.io/docs/) - IaaS orchestration platform originally written for deploying and managing Cloud Foundry PaaS, but also useful for general purpose distributed systems.
- [Cloud Foundry](https://www.cloudfoundry.org/) - A Platform-as-a-Service suite to provide the orchestration services that make distributed apps a powerhouse of awesomeness.
- [Cloudify](http://getcloudify.org/) - TOSCA-based cloud orchestration software platform written in Python and YAML.
- [CloudSlang](http://www.cloudslang.io/) - Flow-based orchestration tool for managing deployed applications, with Docker capabilities.
- [Genesis](https://github.com/starkandwayne/genesis) - A template framework for multi-environment BOSH deployments.
- [Juju](https://jujucharms.com/) - Cloud orchestration tool which manages services as charms, YAML configuration and deployment script bundles.
- [Kubernetes](http://kubernetes.io/) - Orchestration system for Docker containers - ([Source Code](https://github.com/kubernetes/kubernetes), [Documentation](http://kubernetes.io/docs/)) `Apache-2.0` `Go`
- [MCollective](https://puppet.com/mcollective) - Ruby framework to manage server orchestration, developed by Puppet labs.
- [Nomad](https://www.nomadproject.io) - Simple and flexible orchestrator for Docker, Podman, executables, Java, and QEMU - ([Source Code](https://github.com/hashicorp/nomad), [Documentation](https://www.nomadproject.io/docs)) `MPL-2.0` `Go`
- [Overcast](http://andrewchilds.github.io/overcast/) - Deploy VMs across different cloud providers, and run commands and scripts across any or all of them in parallel via SSH.
- [Rundeck](http://rundeck.org/) - Simple orchestration tool.
- [Salt](http://saltstack.com/) - Fast, scalable and flexible systems management software written in Python/ZeroMQ.
- [Spruce](https://github.com/geofffranks/spruce) - A tool that merges separate YAML files into one.  Works well with [Genesis](https://github.com/starkandwayne/genesis).
- [StackStorm](https://stackstorm.com/) - Event Driven Operations and ChatOps platform for infrastructure management. Written in Python.
- [Terraform](https://www.terraform.io/) - Terraform works with many cloud providers and creates infrastructure from code.


### Code Review

**[`^        back to top        ^`](#sys-software)**

*Web Based collaborative code review system.*

- [Gerrit](https://www.gerritcodereview.com/) - Based on the Git version control, it facilitates software developers to review modifications to the source code and approve or reject those changes.
- [Phabricator](http://phabricator.org/) - Code review tool build by facebook and used by WikiMedia, FB, dropbox etc. Comes with an integrated wiki, bug tracker, VC integration and a CLI tool called arcanist.
- [Review Board](https://www.reviewboard.org/) - Available as free software under the MIT License.


### Configuration Management Database

**[`^        back to top        ^`](#sys-software)**

Configuration management database (CMDB) software.

_See also: [IT Asset Management]([Ralph](#it-asset-management))_

- [Collins](http://tumblr.github.io/collins/) - At Tumblr, it's the infrastructure source of truth and knowledge.
- [i-doit](http://www.i-doit.org/) - IT Documentation and CMDB.
- [iTop](http://www.combodo.com/itop-193) - Complete ITIL web based service management tool.
- [netbox](https://github.com/digitalocean/netbox) - IP address management (IPAM) and data center infrastructure management (DCIM) tool


### Configuration Management

**[`^        back to top        ^`](#sys-software)**

*Configuration management tools.*

- [Ansible](http://www.ansible.com/) -  It's written in Python and manages the nodes over SSH.
- [CFEngine](https://cfengine.com/) - Lightweight agent system. Configuration state is specified via a declarative language.
- [Chef](https://www.chef.io/chef/) - It's written in Ruby and Erlang and uses a pure-Ruby DSL.
- [Pallet](http://palletops.com/) - Infrastructure definition, configuration and management via a Clojure DSL.
- [Puppet](https://puppet.com/) - It's written in Ruby and uses Puppet's declarative language or a Ruby DSL.
- [Salt](http://saltstack.com/) - It's written in Python.


### Continuous Integration & Continuous Deployment

**[`^        back to top        ^`](#sys-software)**

*Continuous integration/deployment software.*

- [Buildbot](http://buildbot.net/) - Python-based toolkit for continuous integration. ([Source Code](https://github.com/buildbot/buildbot)) `GPL-2.0` `Python`
- [CapsuleCD](https://analogj.github.io/capsulecd-slides/) - CD script for automating package/library releases (npm, cookbooks, gems, pip, jars, etc). ([Source Code](https://github.com/AnalogJ/capsulecd)) `MIT` `Go`
- [CDS](https://ovh.github.io/cds/) - Enterprise-Grade Continuous Delivery & DevOps Automation Open Source Platform. ([Source Code](https://github.com/ovh/cds)) `BSD-3-Clause` `Go`
- [Concourse](https://concourse-ci.org/) - Concourse is a CI tool that treats pipelines as first class objects and containerizes every step along the way. ([Demo](https://ci.concourse-ci.org/), [Source Code](https://github.com/concourse/concourse)) `Apache-2.0` `Go`
- [drone](https://drone.io/) - Drone is a Continuous Delivery platform built on Docker, written in Go. ([Source Code](https://github.com/drone/drone)) `Apache-2.0` `Go`
- [Factor](http://www.factor.io/) - Programmatically define and run workflows to connect configuration management, source code management, build, continuous integration, continuous deployment and communication tools. ([Source Code](https://github.com/factor-io/factor)) `MIT` `Ruby`
- [GitLab CI](https://about.gitlab.com/gitlab-ci/) - Gitlab's built-in, full-featured CI/CD solution. ([Source Code](https://gitlab.com/gitlab-org/gitlab-ce)) `MIT` `Ruby`
- [GoCD](http://www.go.cd/) - Continuous delivery server. ([Source Code](https://github.com/gocd/gocd)) `Apache-2.0` `Java/Ruby`
- [GolangCI](https://golangci.com/) - Open Source automated code review service for Go integrated with GitHub pull requests. ([Source Code](https://github.com/golangci/golangci)) `AGPL-3.0` `Go`
- [Jenkins](https://jenkins-ci.org/) - Continuous Integration Server. ([Source Code](https://github.com/jenkinsci/jenkins/)) `MIT` `Java`
- [Laminar](http://laminar.ohwg.net) - Fast, lightweight, simple and flexible Continuous Integration. ([Source Code](https://github.com/ohwgiles/laminar)) `GPL-3.0` `C++`
- [PHP Censor](https://github.com/php-censor/php-censor) - Open source self-hosted continuous integration server for PHP projects. `BSD-2-Clause` `PHP`
- [PHPCI](https://www.phptesting.org/) - Free and open source continuous integration specifically designed for PHP. ([Source Code](https://github.com/block8/phpci)) `BSD-2-Clause` `PHP`
- [Strider](http://strider-cd.github.io/) - Open Source Continuous Deployment / Continuous Integration platform. ([Source Code](https://github.com/Strider-CD/strider)) `MIT` `Nodejs`
- [werf](https://werf.io/) - Open Source CI/CD tool for building Docker images and deploying to Kubernetes via GitOps. ([Source Code](https://github.com/werf/werf)) `Apache-2.0` `Go`
- [Woodpecker](https://woodpecker-ci.org/) - Community fork of Drone that uses Docker containers. ([Source Code](https://github.com/woodpecker-ci/woodpecker)) `Apache-2.0` `Go`


### Control Panels

**[`^        back to top        ^`](#sys-software)**

*Web hosting and server or service control panels.*

- [Ajenti](http://ajenti.org/) - Control panel for Linux and BSD. ([Source Code](https://github.com/ajenti/ajenti)) `MIT` `Python/Shell`
- [Cockpit](http://cockpit-project.org/) - web-based graphical interface for servers. ([Source Code](https://github.com/cockpit-project/cockpit)) `LGPL-2.1` `C`
- [Froxlor](https://froxlor.org/) - Lightweight server management software with Nginx and PHP-FPM support. ([Source Code](https://github.com/Froxlor/Froxlor/)) `GPL-2.0` `PHP`
- [ISPConfig](http://www.ispconfig.org) - Manage Linux servers directly through your browser. ([Source Code](https://git.ispconfig.org/ispconfig/ispconfig3)) `BSD-3-Clause` `PHP`
- [Sentora](http://sentora.org/) - Open-Source Web hosting control panel for Linux, BSD (fork of ZPanel). ([Source Code](https://github.com/sentora/sentora-core)) `GPL-3.0` `PHP`
- [VestaCP](http://vestacp.com/) - Open-Source hosting control panel. ([Source Code](https://github.com/serghey-rodin/vesta)) `GPL-3.0` `PHP/Shell/Other`
- [Virtualmin](http://www.virtualmin.com/) - Powerful and flexible web hosting control panel for Linux and BSD systems. ([Source Code](https://github.com/virtualmin)) `GPL-3.0` `Shell/Perl/Other`
- [Webmin](http://www.webmin.com/) - Web-based interface for system administration for Unix. ([Source Code](https://github.com/webmin/webmin)) `BSD-3-Clause` `Perl`


### Databases

**[`^        back to top        ^`](#sys-software)**

*Database servers.*

**Please visit [dbdb.io - Database of Databases](https://dbdb.io/)**


### Deployment Automation

**[`^        back to top        ^`](#sys-software)**

*Tools and scripts to support deployments to your servers.*

- [Capistrano](http://capistranorb.com/) - Deploy your application to any number of machines simultaneously, in sequence or as a rolling set via SSH (rake based).
- [Fabric](http://www.fabfile.org/) - Python library and cli tool for streamlining the use of SSH for application deployment or systems administration tasks.
- [Mina](http://nadarei.co/mina/) - Really fast deployer and server automation tool (rake based).
- [munki](https://www.munki.org/munki/) - Webserver-based repository of packages and package metadata, that allows macOS administrators to manage software installs.
- [Vlad the Deployer](https://github.com/seattlerb/vlad) - Deployment automation (rake based).


### Diagramming

**[`^        back to top        ^`](#sys-software)**

*Tools used to create diagrams of networks, flows, etc.*

- [Diagrams.net](https://app.diagrams.net/) - A.K.A. [Draw.io](https://app.diagrams.net/). Easy to use Diagram UI with a plethora of templates.
- [DrawThe.Net](http://go.drawthe.net/) - Javascript tool that uses a YAML-formatted input to programmatically create large, complex, and visually solid diagrams.
- [Mermaid](https://mermaid-js.github.io/mermaid-live-editor/) - Javascript module with a unique, easy, shorthand syntax. Integrates into several other tools like Grafana.


### Distributed Filesystems

**[`^        back to top        ^`](#sys-software)**

*Network distributed filesystems.*

- [Ceph](http://ceph.com/) - Distributed object store and file system.
- [DRBD](http://drbd.linbit.com/) - Distributed Replicated Block Device.
- [GlusterFS](http://www.gluster.org/) - Scale-out network-attached storage file system.
- [Go IPFS](https://github.com/ipfs/go-ipfs) - Implementation of [IPFS](http://ipfs.io/), a global, versioned, peer-to-peer filesystem that seeks to connect all computing devices with the same system of files.
- [HDFS](http://hadoop.apache.org/) - Distributed, scalable, and portable file-system written in Java for the Hadoop framework.
- [LeoFS](http://leo-project.net) - Unstructured object/data storage and a highly available, distributed, eventually consistent storage system.
- [Lustre](http://lustre.org/) - Parallel distributed file system, generally used for large-scale cluster computing.
- [Minio](https://minio.io/) - Minio is an open source object storage server compatible with Amazon S3 APIs. ([Source Code](https://github.com/minio/minio)) `AGPL-3.0` `Go`
- [MooseFS](http://www.moosefs.org/) - Fault tolerant, network distributed file system.
- [OpenAFS](http://www.openafs.org/) - Distributed network file system with read-only replicas and multi-OS support.
- [Perkeep](https://perkeep.org/) (née Camlistore) - A set of open source formats, protocols, and software for modeling, storing, searching, sharing and synchronizing data.
- [SheepDog](https://sheepdog.github.io/sheepdog/) - A distributed Blockdevice, Rest, QEMU and distributed Filesystem storage.
- [Swift](http://docs.openstack.org/developer/swift/) - A highly available, distributed, eventually consistent object/blob store.
- [TahoeLAFS](https://tahoe-lafs.org/trac/tahoe-lafs) - secure, decentralized, fault-tolerant, peer-to-peer distributed data store and distributed file system.
- [XtreemFS](http://www.xtreemfs.org/) - XtreemFS is a fault-tolerant distributed file system for all storage needs.


### DNS - Servers

**[`^        back to top        ^`](#sys-software)**

*DNS servers.*

- [Bind](https://www.isc.org/downloads/bind/) - The most widely used name server software.
- [CoreDNS](https://coredns.io/) - Flexible DNS server written on Go.
- [Designate](https://wiki.openstack.org/wiki/Designate) - DNS REST API that support several DNS servers as its backend.
- [djbdns](http://cr.yp.to/djbdns.html) - A collection of DNS applications, including tinydns.
- [dnsmasq](http://www.thekelleys.org.uk/dnsmasq/doc.html) - A lightweight service providing DNS, DHCP and TFTP services to small-scale networks.
- [Knot](https://www.knot-dns.cz/) - High performance authoritative-only DNS server.
- [NSD](http://www.nlnetlabs.nl/projects/nsd/) - Authoritative only, high performance, simple name server.
- [PowerDNS](https://www.powerdns.com/) - DNS server with a variety of data storage back-ends and load balancing features.
- [Unbound](http://unbound.net/) - Validating, recursive, and caching DNS resolver.
- [Yadifa](http://www.yadifa.eu/) - Lightweight authoritative Name Server with DNSSEC capabilities powering the .eu top-level domain.


### DNS - Control Panels

**[`^        back to top        ^`](#sys-software)**

*DNS server control panels.*

- [Atomia DNS](http://atomiadns.com/) - DNS management system.
- [nsedit](https://github.com/tuxis-ie/nsedit) - nsedit is a DNS editor for PowerDNS, working with PowerDNS's new API.
- [PDNS Gui](https://github.com/odoucet/pdns-gui) - WebGUI which aids in administering domains and records for PowerDNS with MySQL.
- [Pi-hole](https://pi-hole.net/) - A blackhole for Internet Advertisements with a gui for managing and monitoring
- [Poweradmin](http://www.poweradmin.org/) - Friendly web-based DNS administration tool for PowerDNS server.


### DNS - Domain Management

**[`^        back to top        ^`](#sys-software)**

*Domain management.*

- [DNSControl](https://stackexchange.github.io/dnscontrol/) - Synchronize your DNS to multiple providers from a simple DSL. ([Source Code](https://github.com/StackExchange/dnscontrol)) `MIT` `Go/Docker`
- [DomainMOD](https://domainmod.org) - Manage your domains and other internet assets in a central location. ([Source Code](https://github.com/domainmod/domainmod.git)) `GPL-3.0` `PHP`
- [octoDNS](https://github.com/github/octodns) - DNS as code - Tools for managing DNS across multiple providers. `MIT` `Python`


### Editors

**[`^        back to top        ^`](#sys-software)**

*Open source code editors.*

- [Atom Community](https://github.com/atom-community/atom) - A fork of [atom](https://github.com/atom/atom) A hackable text editor from Github.
- [Brackets](http://brackets.io/) - Code editor for web designers and front-end developers.
- [Eclipse](http://www.eclipse.org/) - IDE written in Java with an extensible plug-in system.
- [Geany](http://www.geany.org/) - GTK2 text editor.
- [GNU Emacs](http://www.gnu.org/software/emacs/) - An extensible, customizable text editor-and more.
- [Haroopad](http://pad.haroopress.com/) - Markdown editor with live preview.
- [ICEcoder](https://icecoder.net/) - Code editor awesomeness, built with common web languages.
- [jotgit](https://github.com/jdleesmiller/jotgit) - Git-backed real-time collaborative code editing.
- [KDevelop](https://www.kdevelop.org/) - IDE by the people behind KDE.
- [Micro](https://micro-editor.github.io/) - A modern and intuitive terminal-based text editor
- [Nano](http://nano-editor.org) - Easy to use, customizable text editor.
- [Notepad++](https://notepad-plus-plus.org/) - GPLv2 multi-language editor with syntax highlighting for Windows.
- [TextMate](https://github.com/textmate/textmate/) - A graphical text editor for OS X.
- [Vim](http://www.vim.org) - A highly configurable text editor built to enable efficient editing.
- [VSCodium](https://github.com/VSCodium/vscodium) - An open source cross-platform extensible code editor based on [VS Code by Microsoft](https://code.visualstudio.com/) removing their non-free additions.


### Identity Management

**[`^        back to top        ^`](#sys-software)**

*LDAP servers and other tools to manage accounts and identities.*


### Identity Management - LDAP

**[`^        back to top        ^`](#sys-software)**

- [389 Directory Server](https://www.port389.org/) - Enterprise-class Open Source LDAP server for Linux. ([Source Code](https://github.com/389ds/389-ds-base)) `GPL-3.0` `C`
- [Apache Directory Server](https://directory.apache.org/apacheds/) - Extensible and embeddable directory server, certified LDAPv3 compatible, with Kerberos 5 and Change Password Protocol support, triggers, stored procedures, queues and views. ([Source Code](https://github.com/apache/directory-server)) `Apache-2.0` `Java`
- [FreeIPA](https://www.freeipa.org/) - Integrated security information management solution combining Linux (Fedora), 389 Directory Server, Kerberos, NTP, DNS, and Dogtag Certificate System (web interface and command-line administration tools). ([Source Code](https://pagure.io/freeipa)) `GPL-3.0` `Python/C/JavaScript`
- [FreeRADIUS](https://freeradius.org/) - Multi-protocol policy server (radiusd) that implements RADIUS, DHCP, BFD, and ARP and associated client/PAM library/Apache module. ([Source Code](https://github.com/FreeRADIUS/freeradius-server)) `GPL-2.0` `C`
- [lldap](https://github.com/nitnelave/lldap) - Light (simplified) LDAP implementation with a simple, intuitive web interface and GraphQL support. `GPL-3.0` `Rust`
- [OpenLDAP](https://www.openldap.org/) - Open-source implementation of the Lightweight Directory Access Protocol (server, libraries and clients). ([Source Code](https://git.openldap.org/openldap/openldap)) `OLDAP-2.8` `C`


### Identity Management - Tools and web interfaces

**[`^        back to top        ^`](#sys-software)**

- [BounCA](https://bounca.org/) - A personal SSL Key / Certificate Authority web-based tool for creating self-signed certificates.
- [easy-rsa](https://github.com/OpenVPN/easy-rsa) - bash script to build and manage a PKI CA.
- [Fusion Directory](https://www.fusiondirectory.org) - Improve the Management of the services and the company directory based on OpenLDAP.
- [Indieauth](https://indieauth.com/) - Sign in with your domain name (using the rel-me-auth protocol).
- [LDAP Account Manager (LAM)](https://www.ldap-account-manager.org/lamcms/) - Web frontend for managing entries (e.g. users, groups, DHCP settings) stored in an LDAP directory.
- [Libravatar](https://www.libravatar.org/) - Libravatar is a service which delivers your avatar (profile picture) to other websites.
- [OpenID Connect](http://openid.net/developers/libraries/) - A Simple Identity layer on top of OAuth 2.0.
- [OSIAM](http://osiam.github.io/) - Secure identity management solution providing REST based services for authentication and authorization.
- [Pomerium](https://www.pomerium.io/) - An identity and context aware access-proxy inspired by BeyondCorp.
- [Samba](https://www.samba.org/) – Active Directory and CIFS protocol implementation.
- [Smallstep Certificates](https://smallstep.com/certificates/) - A private certificate authority (X.509 & SSH) and related tools for secure automated certificate management.
- [ZITADEL](https://github.com/caos/zitadel) - Cloud-native Identity & Access Management solution providing a platform for secure authentication, authorization and identity management.


### Identity Management - Single Sign-On (SSO)

**[`^        back to top        ^`](#sys-software)**

- [Authelia](https://www.authelia.com/) - The Single Sign-On Multi-Factor portal for web apps. ([Source Code](https://github.com/authelia/authelia)) `Apache-2.0` `Go`
- [KeyCloak](https://www.keycloak.org) - Open Source Identity and Access Management. ([Source Code](https://github.com/keycloak/keycloak)) `Apache-2.0` `Java`


### IT Asset Management

**[`^        back to top        ^`](#sys-software)**

*IT Assets Management software.*

- [GLPI](https://www.glpi-project.org/) - Information Resource-Manager with an additional Administration Interface. ([Source Code](https://github.com/glpi-project/glpi))
- [OCS Inventory NG](https://ocsinventory-ng.org/) - Asset management and deployment solution for all devices in your IT Department. ([Source Code](https://github.com/OCSInventory-NG)) `GPL-2.0` `PHP/Perl`
- [OPSI](http://www.opsi.org) - Hardware and software inventory, client management, deployment, and patching for Linux and Windows. ([Source Code](https://github.com/opsi-org/)) `GPL-3.0/AGPL-3.0` `OVF/Python`
- [RackTables](http://racktables.org/) - Datacenter and server room asset management like document hardware assets, network addresses, space in racks, networks configuration. ([Source Code](https://github.com/RackTables/racktables), [Demo](https://www.racktables.org/demo.php)) `GPL-2.0` `PHP`
- [Ralph](https://ralph.allegro.tech/) - Asset management, DCIM and CMDB system for large Data Centers as well as smaller LAN networks. ([Source Code](https://github.com/allegro/ralph), [Demo](https://github.com/allegro/ralph#live-demo)) `Apache-2.0` `Python/Docker`
- [Snipe IT](https://snipeitapp.com/) - Asset & license management software. ([Source Code](https://github.com/snipe/snipe-it)) `AGPL-3.0` `PHP`


### Log Management

**[`^        back to top        ^`](#sys-software)**

*Log management tools: collect, parse, visualize ...*

- [Elasticsearch](https://www.elastic.co/) - A Lucene Based Document store mainly used for log indexing, storage and analysis.
- [Fluentd](http://www.fluentd.org/) - Log Collector and Shipper.
- [Flume](https://flume.apache.org/) - Distributed log collection and aggregation system.
- [GoAccess](http://goaccess.io/) - Real-time web log analyzer and interactive viewer that runs in a terminal or through the browser. ([Source Code](https://github.com/allinurl/goaccess)) `MIT` `C`
- [Graylog](https://www.graylog.org/) - Pluggable Log and Event Analysis Server with Alerting options.
- [Hindsight](http://mozilla-services.github.io/hindsight/) - Stream processing system which may be used for log aggregation (Replaces Heka).
- [Kibana](https://www.elastic.co/products/kibana) - Visualize logs and time-stamped data.
- [Logstash](https://www.elastic.co/products/logstash) - Tool for managing events and logs.
- [Loki](https://grafana.com/oss/loki/) - horizontally-scalable, highly-available, multi-tenant log aggregation system inspired by Prometheus.
- [Octopussy](http://www.octopussy.pm) - Log Management Solution (Visualize / Alert / Report).


### Mail Clients

**[`^        back to top        ^`](#sys-software)**

- [Claws Mail](http://www.claws-mail.org/) - Old school email client (and news reader), based on GTK+. ([Source Code](https://git.claws-mail.org/?p=claws.git;a=tree))
- [ImapSync](http://imapsync.lamiral.info/) – Simple IMAP migration tool for copying mailboxes to other servers. ([Source Code](https://github.com/imapsync/imapsync))
- [Mutt](http://www.mutt.org/) - Small but very powerful text-based mail client. ([Source Code](https://gitlab.com/muttmua/mutt))
- [Sylpheed](http://sylpheed.sraoss.jp/en/) – Still developed predecessor to Claws Mail, lightweight mail client. ([Source Code](https://github.com/sylpheed-mail/sylpheed))
- [Thunderbird](https://www.thunderbird.net/) - Free email application that's easy to set up and customize. ([Source Code](https://hg.mozilla.org/comm-central/file))


### Monitoring

**[`^        back to top        ^`](#sys-software)**

*Monitoring software.*

- [Adagios](http://adagios.org/) - Web based Nagios interface for configuration and monitoring (replacement to the standard interface), and a REST interface. ([Source Code](https://github.com/opinkerfi/adagios)) `AGPL-3.0` `Docker/Python`
- [Alerta](https://alerta.io/) - Distributed, scaleable and flexible monitoring system. ([Source Code](https://github.com/alerta/alerta)) `Apache-2.0` `Python`
- [Bloonix](https://bloonix-monitoring.org/) - Bloonix is a monitoring solution that helps businesses to ensure high availability and performance. ([Source Code](https://github.com/bloonix)) `GPL-3.0` `Perl`
- [Bosun](http://bosun.org/) - Monitoring and alerting system by Stack Exchange ([Source Code](https://github.com/bosun-monitor/bosun)) `MIT` `Go`
- [Cabot](http://cabotapp.com/) - Monitoring and alerts, similar to PagerDuty. ([Source Code](https://github.com/arachnys/cabot)) `MIT` `Python`
- [Cacti](http://www.cacti.net) - Web-based network monitoring and graphing tool. ([Source Code](https://github.com/Cacti/cacti)) `GPL-2.0` `PHP`
- [cadvisor](https://github.com/google/cadvisor) - Analyzes resource usage and performance characteristics of running containers ([Source Code](https://github.com/google/cadvisor)) `Apache-2.0` `Go`
- [checkmk](https://checkmk.com/) - Comprehensive solution for monitoring of applications, servers, and networks. ([Source Code](https://github.com/tribe29/checkmk)) `Python/PHP`
- [EdMon](https://github.com/Edraens/EdMon) - A command-line monitoring application helping you to check that your hosts and services are available, with notifications support. `MIT` `Java`
- [eZ Server Monitor](http://www.ezservermonitor.com) - A lightweight and simple dashboard monitor for Linux, available in Web and Bash application. ([Source Code](https://github.com/shevabam/ezservermonitor-web)) `GPL-3.0` `PHP/Shell`
- [Healthchecks](https://healthchecks.io/docs/self_hosted/) - Monitoring for cron jobs, background services and scheduled tasks. ([Source Code](https://github.com/healthchecks/healthchecks)) `BSD-3-Clause` `Python`
- [Icinga](https://www.icinga.com/) - Nagios fork that has since lapped nagios several times. Comes with the possibility of clustered monitoring. ([Source Code](https://github.com/Icinga/icinga2)) `GPL-2.0` `C++`
- [LibreNMS](http://www.librenms.org) - Fully featured network monitoring system that provides a wealth of features and device support. ([Source Code](https://github.com/librenms/librenms)) `GPL-3.0` `PHP`
- [Linux Dash](https://github.com/afaqurk/linux-dash) - A low-overhead monitoring web dashboard for a GNU/Linux machine. `MIT` `Nodejs/Go/Python/PHP`
- [Monit](http://mmonit.com/monit/#home) - Small utility for managing and monitoring Unix systems. ([Source Code](https://bitbucket.org/tildeslash/monit/src/master/)) `AGPL-3.0` `C`
- [Munin](http://munin-monitoring.org/) - Networked resource monitoring tool. ([Source Code](https://github.com/munin-monitoring/munin)) `GPL-2.0` `Perl/Shell`
- [Naemon](http://www.naemon.org/) - Network monitoring tool based on the Nagios 4 core with performance enhancements and new features. ([Source Code](https://github.com/naemon/naemon-core)) `GPL-2.0` `C`
- [Nagios](https://www.nagios.org/) - Computer system, network and infrastructure monitoring software application. ([Source Code](https://github.com/NagiosEnterprises/nagioscore)) `GPL-2.0` `C`
- [Netdata](https://www.netdata.cloud/) - Distributed, real-time, performance and health monitoring for systems and applications. Runs on Linux, FreeBSD, and MacOS. ([Source Code](https://github.com/netdata/netdata)) `GPL-3.0` `C`
- [NetXMS](https://www.netxms.org/) - Open Source network and infrastructure monitoring and management. ([Source Code](https://github.com/netxms/netxms)) `LGPL-3.0/GPL-3.0` `Java/C++/C`
- [Observium](http://www.observium.org/) - SNMP monitoring for servers and networking devices. Runs on linux.
- [OMD](http://omdistro.org/) - The Open Monitoring Distribution.
- [Performance Co-Pilot](http://pcp.io) - Lightweight, distributed system performance and analysis framework.
- [PHP Server Monitor](https://www.phpservermonitor.org/) - Open source tool to monitor your servers and websites. ([Source Code](https://github.com/phpservermon/phpservermon))
- [PhpSysInfo](https://phpsysinfo.github.io/phpsysinfo/) - A customizable PHP script that displays information about your system nicely. ([Source Code](https://github.com/phpsysinfo/phpsysinfo))
- [pyDash](https://k3oni.github.io/pydash/) - Small web-based monitoring dashboard for linux. ([Source Code](https://gitlab.com/k3oni/pydash))
- [Riemann](http://riemann.io/) - Flexible and fast events processor allowing complex events/metrics analysis. ([Source Code](https://github.com/riemann/riemann))
- [rtop](https://github.com/rapidloop/rtop) - an interactive, remote system monitoring tool based on SSH. ([Source Code](https://github.com/rapidloop/rtop))
- [Scrutiny](https://github.com/AnalogJ/scrutiny) - Hard Drive S.M.A.R.T Monitoring, Historical Trends & Real World Failure Thresholds 
- [Sensu](https://sensu.io/) - Monitoring tool for ephemeral infrastructure and distributed applications. ([Source Code](https://github.com/sensu/sensu-go))
- [Status](https://github.com/dani3l0/Status) - Simple and lightweight system monitoring tool for small homeservers with a pleasant web interface. ([Demo](https://status-ksk5.onrender.com/)) `MIT` `Python`
- [Thruk](http://www.thruk.org/) - Multibackend monitoring web interface with support for Naemon, Nagios, Icinga and Shinken. ([Source Code](https://github.com/sni/Thruk))
- [Zabbix](http://www.zabbix.com/) - Enterprise-class software for monitoring of networks and applications. ([Source Code](https://git.zabbix.com/projects/ZBX/repos/zabbix/browse))


### Status Pages

**[`^        back to top        ^`](#sys-software)**

**Please visit [awesome-selfhosted/Status / Uptime Pages](https://github.com/awesome-selfhosted/awesome-selfhosted#status--uptime-pages)**


### Metric & Metric Collection

**[`^        back to top        ^`](#sys-software)**

*Metric gathering and display software.*

* Collectors only
  - [Collectd](http://collectd.org/) - System statistic collection daemon.
  - [Collectl](http://collectl.sourceforge.net/) - High precision system performance metrics collecting tool.
  - [Diamond](https://github.com/python-diamond/Diamond) - Python based statistic collection daemon.
  - [Statsd](https://github.com/etsy/statsd/) - Application statistic listener.
  - [tcollector](http://opentsdb.net/docs/build/html/user_guide/utilities/tcollector.html) - System statistic collection daemon written in Python for OpenTSDB
  - [Telegraf](https://github.com/influxdata/telegraf) - The plugin-driven server agent for collecting & reporting metrics.

* Dashboards
  - [Dashing](http://dashing.io/) - Ruby gem that allows for rapid statistical dashboard development. An all HTML5 approach allows for big screen displays in data centers or conference rooms.
  - [Facette](http://facette.io) - Time series data visualization and graphing software written in Go.
  - [Freeboard](https://github.com/Freeboard/freeboard) - A damn-sexy front-end real-time dashboard for the internet of things. Transforms raw JSON into delicious UI.
  - [Ganglia](http://ganglia.sourceforge.net/) - High performance, scalable RRD based monitoring for grids and/or clusters of servers. Compatible with Graphite using a single collection process.
  - [Grafana](http://grafana.org/) - A Graphite & InfluxDB Dashboard and Graph Editor.
  - [RRDtool](http://oss.oetiker.ch/rrdtool/) - Industry standard, high performance data logging and graphing system for time series data.

* Storage
  - [InfluxDB](https://influxdb.com/) - Distributed time series database with no external dependencies.
  - [KairosDB](https://github.com/kairosdb/kairosdb) - Fast distributed scalable time series database, fork of OpenTSDB 1.x.
  - [OpenTSDB](http://opentsdb.net/) - Store and server massive amounts of time series data without losing granularity.

* Packages
  - [Graphite](http://graphite.readthedocs.org/en/latest/) - Scalable graphing server.
  - [Packetbeat](https://www.elastic.co/products/beats) - Captures network traffic and displays it in a custom Kibana dashboard for easy viewing.
  - [Prometheus](http://prometheus.io/) - Service monitoring system and time series database.
  - [VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics) - Service monitoring system and time series database.


### Network Configuration Management

**[`^        back to top        ^`](#sys-software)**

*Network configuration management tools.*

- [GNS3](https://www.gns3.com/) - Graphical network simulator that provides a variety of virtual appliances. ([Source Code](https://github.com/GNS3/gns3-gui/)) `GPL-3.0` `Python`
- [OpenWISP](https://openwisp.org/) - Open Source Network Management System for OpenWRT based routers and access points. ([Demo](https://openwisp.org/demo.html), [Source Code](https://github.com/openwisp)) `GPL-3.0` `Python` 
- [Oxidized](https://github.com/ytti/oxidized) - Network device configuration backup tool. `Apache-2.0` `Ruby`
- [phpIPAM](http://phpipam.net/) - Open source IP address management with PowerDNS integration. ([Source Code](https://github.com/phpipam/phpipam)) `GPL-3.0` `PHP`
- [RANCID](http://www.shrubbery.net/rancid/) - Monitor network devices configuration and maintain history of changes. ([Source Code](https://github.com/haussli/rancid)) `BSD-3-Clause` `Perl/Shell`
- [rConfig](http://www.rconfig.com/) - Network device configuration management tool. ([Source Code](https://github.com/rconfig/rconfig)) `GPL-3.0` `PHP`



### Newsletters

**[`^        back to top        ^`](#sys-software)**

*Newsletter software.*

- [DadaMail](http://dadamailproject.com/) - Mailing List Manager, written in Perl.
- [Lewsnetter](https://github.com/bborn/lewsnetter) - E-mail marketing application (create and send e-mail newsletter via SES). Includes subscription management, delivery, bounce and complaint notification, templates, and some stats.
- [LibreMailer](https://github.com/averna-syd/LibreMailer) - Libre Mailer is a modest and simple web based email marketing application.
- [phpList](https://www.phplist.com/) - Newsletter manager written in PHP.


### Packaging

**[`^        back to top        ^`](#sys-software)**

- [aptly](https://www.aptly.info/) - Swiss army knife for Debian repository management. ([Source Code](https://github.com/aptly-dev/aptly)) `MIT` `Go`
- [fpm](https://github.com/jordansissel/fpm) - Versatile multi format package creator.
- [omnibus-ruby](https://github.com/chef/omnibus) - Full stack, cross distro packaging software (Ruby).
- [packman](http://packman.readthedocs.org) - Full stack, cross distro packaging software (Python).
- [tito](https://github.com/dgoodwin/tito) - Builds RPMs for git-based projects.


### Project Management

**[`^        back to top        ^`](#sys-software)**

*Web-based project management and bug tracking systems*

**Please visit [awesome-selfhosted/Project Management](https://github.com/awesome-selfhosted/awesome-selfhosted#project-management)**


### Queuing

**[`^        back to top        ^`](#sys-software)**

- [ActiveMQ](https://activemq.apache.org/) - Java message broker.
- [BeanstalkD](http://kr.github.io/beanstalkd/) - A simple, fast work queue.
- [Gearman](http://gearman.org/) - Fast multi-language queuing/job processing platform.
- [Kafka](http://kafka.apache.org) - Extremely high performance publish/subscribe message system.
- [NSQ](http://nsq.io/) - A realtime distributed messaging platform.
- [RabbitMQ](http://www.rabbitmq.com/) - Robust, fully featured, cross distro queuing system.
- [ZeroMQ](http://zeromq.org/) - Lightweight queuing system.


### Remote Management

**[`^        back to top        ^`](#sys-software)**

- [Remmina](http://www.remmina.org/wp/) - A Feature rich remote desktop application for linux  and other unixes.
- [Tiger VNC](http://tigervnc.org/) - TigerVNC is a high-performance, platform-neutral implementation of VNC (Virtual Network Computing), a client/server application that allows users to launch and interact with graphical applications on remote machines.
- [X2go](http://wiki.x2go.org/doku.php) - X2Go is an open source remote desktop software for Linux that uses the NX technology protocol.


### Router

* [DD-WRT](https://dd-wrt.com/) - A Linux-based firmware for wireless routers and access points, originally designed for the Linksys WRT54G series. ([Source Code](https://svn.dd-wrt.com/)) `GPL-2.0` `C` 
* [OpenWrt](https://openwrt.org/) - A Linux-based router featuring Mesh networking, IPS via snort and AQM among many other features. ([Source Code](https://git.openwrt.org/openwrt/openwrt.git)) `GPL-2.0` `C`
* [OPNsense](https://opnsense.org/) - An open source FreeBSD-based firewall and router with traffic shaping, load balancing, and virtual private network capabilities. ([Source Code](https://github.com/opnsense)) `BSD-2-Clause` `C` `PHP`

### Service Discovery

**[`^        back to top        ^`](#sys-software)**

- [Consul](https://www.consul.io/) - Consul is a tool for service discovery, monitoring and configuration.
- [Doozerd](https://github.com/ha/doozerd) - Doozer is a highly-available, completely consistent store for small amounts of extremely important data.
- [etcd](https://github.com/coreos/etcd) - distributed K/V-Store, authenticating via SSL PKI and a REST HTTP Api for shared configuration and service discovery.
- [ZooKeeper](http://zookeeper.apache.org/) - ZooKeeper is a centralized service for maintaining configuration information, naming, providing distributed synchronization, and providing group services.


### Software Containers

**[`^        back to top        ^`](#sys-software)**

*Operating system–level virtualization.*

- [Docker Compose](https://docs.docker.com/compose/) - Define and run multi-container Docker applications.
- [Docker Swarm](https://docs.docker.com/engine/swarm/) - Manage cluster of Docker Engines.
- [Docker](http://www.docker.com/) - Platform for developers and sysadmins to build, ship, and run distributed applications.
- [LXC](https://linuxcontainers.org/lxc/) - Userspace interface for the Linux kernel containment features.
- [LXD](https://linuxcontainers.org/lxd/) – a container "hypervisor" and a better UX for LXC.
- [OpenVZ](http://openvz.org) - Container-based virtualization for Linux.
- [Podman](https://podman.io) - Daemonless container engine for developing, managing, and running OCI Containers on your Linux System. Containers can either be run as root or in rootless mode. Simply put: `alias docker=podman`. ([Source Code](https://github.com/containers/podman)) `Apache-2.0` `Go`
- [Portainer](https://portainer.io/) - Simple management UI for Docker.
- [systemd-nspawn](https://www.freedesktop.org/software/systemd/man/systemd-nspawn.html) - Lightweight, chroot-like, environment to run an OS or command directly under systemd. ([Source Code](https://github.com/systemd/systemd)) `GPL-2.0` `C`


### Troubleshooting

**[`^        back to top        ^`](#sys-software)**

*Troubleshooting Tools.*

- [grml](https://grml.org) – bootable Debian Live CD with powerful CLI tools.
- [mitmproxy](http://mitmproxy.org/) - A Python tool used for intercepting, viewing and modifying network traffic. Invaluable in troubleshooting certain problems.
- [mtr](https://www.bitwizard.nl/mtr/) - Network utility that combines traceroute and ping.
- [perf-tools](https://github.com/brendangregg/perf-tools) - Performance analysis tools based on Linux perf_events (aka perf) and ftrace.
- [Sysdig](http://www.sysdig.org/) - Capture system state and activity from a running Linux instance, then save, filter and analyze.
- [Wireshark](https://www.wireshark.org/) - The world's foremost network protocol analyzer.


### Version control

**[`^        back to top        ^`](#sys-software)**

*Software versioning and revision control.*

- [Darcs](http://darcs.net/) - Patch-based distributed version control (more info: [wiki](http://darcs.net/Theory/PekkaPatchTheory))
- [Fossil](http://www.fossil-scm.org/) - Distributed version control with built-in wiki and bug tracking.
- [Git](http://git-scm.com/) - Distributed revision control and source code management (SCM) with an emphasis on speed.
- [GNU Bazaar](http://bazaar.canonical.com/) - Distributed revision control system sponsored by Canonical.
- [Mercurial](https://www.mercurial-scm.org/) - Another distributed revision control.
- [Subversion](http://subversion.apache.org/) - Client-server revision control system.


### Virtualization

**[`^        back to top        ^`](#sys-software)**

*Virtualization software.*

- [Archipel](http://archipelproject.org/) - XMPP based virtualization management platform.
- [ConVirt](http://www.convirture.com/products_opensource.php) - Provides the core functionality for centrally managing your KVM or Xen virtualized environment.
- [Ganeti](http://www.ganeti.org/) - Cluster virtual server management software tool built on top of KVM and Xen.
- [KVM](http://www.linux-kvm.org) - Linux kernel virtualization infrastructure.
- [OpenNebula](http://opennebula.org/) - Flexible enterprise cloud made simple.
- [OpenNode](http://opennodecloud.com) - Builds open-source infrastructure management software and implements cloud systems.
- [oVirt](http://www.ovirt.org/) - Manages virtual machines, storage and virtual networks.
- [Packer](https://www.packer.io/) - A tool for creating identical machine images for multiple platforms from a single source configuration.
- [Proxmox VE](https://www.proxmox.com/proxmox-ve) - Virtualization management solution.
- [QEMU](http://www.qemu.org/) - QEMU is a generic machine emulator and virtualizer.
- [Vagrant](https://www.vagrantup.com/) - Tool for building complete development environments.
- [VirtualBox](https://www.virtualbox.org/) - Virtualization product from Oracle Corporation.
- [XCP-ng](http://www.xcp-ng.org/) - Based on Citrix XenServer, XCP-ng is a fully open source virtualization platform.
- [Xen](http://www.xenproject.org/) - Virtual machine monitor for 32/64 bit Intel / AMD (IA 64) and PowerPC 970 architectures.


### VPN

**[`^        back to top        ^`](#sys-software)**

*VPN software.*

- [Dockovpn](https://dockovpn.io) - Out-of-the-box stateless dockerized OpenVPN server which starts in less than 2 seconds.
- [Firezone](https://www.firez.one/) - WireGuard based VPN Server and Firewall. 
- [Headscale](https://github.com/juanfont/headscale) - Self-hostable fork of [Tailscale](https://tailscale.com), cross-platform clients, simple to use, built-in (currently experimental) monitoring tools. 
- [Nebula](https://github.com/slackhq/nebula) - A scalable p2p VPN with a focus on performance, simplicity and security.
- [ocserv](http://www.infradead.org/ocserv/) - Cisco AnyConnect-compatible VPN server
- [OpenVPN](https://community.openvpn.net) - Uses a custom security protocol that utilizes SSL/TLS for key exchange.
- [PiVPN](https://www.pivpn.io/) - The simplest way to setup and manage a VPN, designed for Raspberry Pi. ([Source Code](https://github.com/pivpn/pivpn)) `MIT` `Shell`
- [Pritunl](http://pritunl.com/) - OpenVPN based solution. Easy to set up.
- [SoftEther](https://www.softether.org/) - Multi-protocol software VPN with advanced features
- [Sshuttle](https://github.com/sshuttle/sshuttle) - transparent proxy server that works as a poor man's VPN.
- [strongSwan](https://www.strongswan.org/) - Complete IPsec implementation for Linux.
- [tinc](http://www.tinc-vpn.org/) - Distributed p2p VPN.
- [WireGuard](https://www.wireguard.com/) - Very fast VPN based on elliptic curve and public key crypto.
- [VyOS](https://vyos.io/) - open source network OS that runs on a wide range of hardware, virtual machines, and cloud providers.
- [Algo](https://github.com/trailofbits/algo) - set up a personal VPN in the cloud.
- [Streisand](https://github.com/StreisandEffect/streisand) - sets up a new VPN service nearly automatically.
- [Freelan](https://github.com/freelan-developers/freelan) - a peer-to-peer, secure, easy-to-setup, multi-platform, open-source, highly-configurable VPN software.
- [Firezone](https://www.firezone.dev/) - Self-hosted VPN server using WireGuard. Supports MFA, SSO, and has easy deployment options.

### Web

**[`^        back to top        ^`](#sys-software)**

*Web servers.*

- [Algernon](http://algernon.roboticoverlords.org/) - Web/application server that supports Lua, live-reload, templates, Sass and HTTP/2.
- [Apache](http://httpd.apache.org/) - A robust, commercial-grade, featureful implementation of an HTTP (Web) server.
- [Caddy](https://caddyserver.com/) - Lightweight, general-purpose web server supporting HTTP/2, automatic TLS and easy configuration. Written in Go.
- [Cherokee](http://cherokee-project.com/) - Lightweight, high-performance web server/reverse proxy.
- [Hiawatha](https://www.hiawatha-webserver.org/) - Prioritises security, simplicity and performance.
- [Lighttpd](http://www.lighttpd.net/) - Web server more optimized for speed-critical environments.
- [Nginx](http://nginx.org/) - Reverse proxy, load balancer, HTTP cache, and web server.
- [uWSGI](https://github.com/unbit/uwsgi/) - The uWSGI project aims at developing a full stack for building hosting services.

*Web Performance.*

- [HAProxy](http://www.haproxy.org/) - Software based load Balancing, SSL offloading and performance optimization, compression, and general web routing.
- [Traefik](https://traefik.io/) - Traefik is a leading modern reverse proxy and load balancer.
- [Varnish](https://www.varnish-cache.org/) - HTTP based web application accelerator focusing on optimizing caching and compression.

-------------------
## Resources

### Tutorials

* [How to use *SSH* to Connect to a Remote Server](https://www.digitalocean.com/community/tutorials/how-to-use-ssh-to-connect-to-a-remote-server-in-ubuntu)
* [Best practices](https://blog.0xbadc0de.be/archives/300)
* [Granting Temporary Access to Your Servers (Using Signed *SSH* Keys)](http://linux-audit.com/granting-temporary-access-to-servers-using-signed-ssh-keys/)
* [How to SSH login without a password](https://www.rosehosting.com/blog/ssh-login-without-password-using-ssh-keys/)
* [Gist: SSH Recipes](https://gist.github.com/mjalajel/beaa91a5f8d04ebb464c2c28da01406a) - Collection of recipes for writing awesome ssh config files.

### Security

* [01/14/2016](https://web.nvd.nist.gov/view/vuln/detail?vulnId=CVE-2016-0777) - Integer Overflow `CVE 2016 077[7-8]`.
* [Security/Guidelines/OpenSSH - MozillaWiki](https://wiki.mozilla.org/Security/Guidelines/OpenSSH) - `sshd\_config` for `6.7+`, `5.3`.
* [Applied-Crypto-Hardening](https://github.com/BetterCrypto/Applied-Crypto-Hardening) [![stars](https://img.shields.io/github/stars/BetterCrypto/Applied-Crypto-Hardening.svg?style=social&label=stars)](https://github.com/BetterCrypto/Applied-Crypto-Hardening) - `sshd\_config` for `6.X`

## External links

Various resources, such as books, websites and articles, for improving your skills and knowledge.

## Blogs

- [Code as Craft](https://codeascraft.com/) - Etsy's Ops blog, lots of technical posts.
- [DevOpsGuys](http://blog.devopsguys.com/) - Devops consultants who blog about operations.
- [Rackspace Developers](https://developer.rackspace.com/blog/) - Slightly biased blog with lots of Devops Topics.
- [RoseHosting Blog](https://www.rosehosting.com/blog/) - Linux tutorials for installing and configuring various software through the Linux command line. Guides and introductions to different Linux technologies and applications. Tips and tricks you can do via the Linux command line and more.

## Books

*Sysadmin related books.*

- [The Linux Command Line](http://linuxcommand.org/tlcl.php) - A book about the Linux command line by William Shotts.

*Books focused on DevOps, DevSecOps and Site Reliability Engineering.*

- [Effective DevOps: Building a Culture of Collaboration, Affinity, and Tooling at Scale](http://shop.oreilly.com/product/0636920039846.do)
- [Continuous Delivery: Reliable Software Releases through Build, Test, and Deployment Automation](https://www.oreilly.com/library/view/continuous-delivery-reliable/9780321670250/)
- [Hands-On Security in DevOps](https://www.packtpub.com/networking-and-servers/hands-security-devops)
- [Site Reliability Engineering](https://landing.google.com/sre/books/)
- [The Site Reliability Workbook](https://landing.google.com/sre/books)
- [Infrastructure as Code: Managing Servers in the Cloud](http://shop.oreilly.com/product/0636920039297.do)
- [The DevOps Handbook](https://www.oreilly.com/library/view/the-devops-handbook/9781457191381/)
- [DevOps Roadmap](https://roadmap.sh/devops)


## Communities / Forums

*For the social people.*

- [ArsTechnica OpenForum](http://arstechnica.com/civis/) – IT Forum which is attached to a large news site.
- [Reddit](https://www.reddit.com) - Really, really large bulletin board system.
  - [/r/Linux](https://www.reddit.com/r/linux) - News and information about Linux.
  - [/r/LinuxQuestions](https://www.reddit.com/r/linuxquestions)
  - [/r/SysAdmin](https://www.reddit.com/r/sysadmin/)
- [Spiceworks Community](https://community.spiceworks.com/start) – General enterprise IT news and small articles.
- [StackExchange Network](https://stackexchange.com/sites#technology) – Q&A communities.
  - [Server Fault](https://serverfault.com/) – StackExchange community for system and network administrators.


## Newsletters

- [Servers for Hackers](https://serversforhackers.com/) - Newsletter for programmers who find themselves needing to know their way around a server.
- [Web Operations Weekly](http://webopsweekly.com/) - A weekly newsletter on Web operations, infrastructure, performance, and tooling, from the browser down to the metal.


## Repositories

*Software package repositories.*

- [AlternativeTo](http://alternativeto.net) - Find alternatives to software you know and discover new software.
- [deb.sury.org](https://deb.sury.org/) - Repository with LAMP updated packages for Debian and Ubuntu.
- [ElRepo](http://elrepo.org/tiki/tiki-index.php) - Community Repo for Enterprise Linux (RHEL, CentOS, etc).
- [EPEL](https://fedoraproject.org/wiki/EPEL) - Repository for RHEL and compatibles (CentOS, Scientific Linux).
- [IUS](https://ius.io/) - Community project that provides RPM packages for newer versions of select software for Enterprise Linux distributions.
- [Remi](http://rpms.famillecollet.com/) - Repository with LAMP updated packages for RHEL/Centos/Fedora.
- [Software Collections](https://www.softwarecollections.org) - Community Release of [Red Hat Software Collections](https://access.redhat.com/documentation/en/red-hat-software-collections/). Provides updated packages of Ruby, Python, etc. for CentOS/Scientific Linux 6.x.


## Websites

*Useful sysadmin related websites.*

- [ArchWiki](https://wiki.archlinux.org/) – Arch Linux Wiki which has really nice written articles valid for other distros.
- [Gentoo Wiki](https://wiki.gentoo.org/) - Gentoo Linux Wiki with a lot in-detail description of Linux components.
- [Awesome SysAdmin @ LibHunt](https://sysadmin.libhunt.com) - Your go-to SysAdmin Toolbox. Based on the list here.
- [Ops School](http://www.opsschool.org) - Comprehensive program that will help you learn to be an operations engineer.
- [Digital Ocean Tutorials](https://www.digitalocean.com/community/tutorials) - A surprisingly vast resource for getting the basics of certain applications, tools, or even systems administration topics.

### Conferences

- [DevOpsCon](https://devopscon.io/)
- [AWS re:Invent](https://reinvent.awsevents.com/)
- [DevSecOps](https://www.devseccon.com/)
- [ADDO](https://www.alldaydevops.com/)
- [DevOpsConnect](https://www.devopsconnect.com/)
- [@Scale](https://atscaleconference.com/)
- [devopsdays](https://devopsdays.org/)
- [DevOps Enterprise Summit](https://events.itrevolution.com/)


---

## Cloud Platforms

*Public and Private Cloud Platforms.*

- [Amazon Web Services (AWS)](https://aws.amazon.com/) - Cloud Computing Services.
- [Google Cloud Platform (GCP)](https://cloud.google.com/) - Cloud Computing Services.
- [Azure](https://azure.microsoft.com/) - Cloud Computing Platform & Services.
- [Alibaba Cloud](https://us.alibabacloud.com/) - integrated suite of cloud products and services.
- [Oracle Cloud](https://www.oracle.com/cloud/) - comprehensive and fully integrated stack of cloud applications and platform services.
- [DigitalOcean](https://www.digitalocean.com/) - helping developers easily build, test, manage, and scale applications of any size.
- [Scaleway](https://www.scaleway.com/) - single way to create, deploy and scale your infrastructure in the cloud.
- [Vultr](https://www.vultr.com/) - easily deploy cloud servers, bare metal, and storage worldwide.
- [VMware Cloud](https://cloud.vmware.com/) - run, manage, connect and protect all of your apps on any cloud.
- [IBM Cloud](https://www.ibm.com/cloud) - tools, data & APIs to make AI real now.
- [Stackpath](https://www.stackpath.com/) - platform of computing infrastructure and services built at the edge of the cloud.
- [Linode](https://www.linode.com/) - accelerate innovation in the cloud, virtual computing must be more accessible, affordable, and simple.

## Open Source Cloud Platforms

*Private, Public and Hybrid open source Cloud Platforms.*

- [Openstack](https://www.openstack.org/) - open source software for creating private and public clouds.
- [Apache CloudStack](https://cloudstack.apache.org/) - designed to deploy and manage large networks of virtual machines.
- [OpenNebula](https://opennebula.org/) - build Private Clouds and manage Data Center virtualization based on KVM, LXD and VMware.
- [Eucalyptus](https://www.eucalyptus.cloud/) - building AWS-compatible private and hybrid clouds.
- [DC/OS](https://dcos.io/) - distributed operating system based on the Apache Mesos distributed systems kernel.
- [Apache Mesos](http://mesos.apache.org/) - program against your datacenter like it’s a single pool of resources.
- [Localstack](https://github.com/localstack/localstack) - fully functional local AWS cloud stack. Develop and test your cloud & Serverless apps offline.

## Operating Systems

*Operating Systems - Server Platform.*

- [Ubuntu](https://ubuntu.com/)
- [CentOS](https://www.centos.org/)
- [CoreOS](http://coreos.com/) - the pioneering lightweight container host.
- [OSv](http://osv.io/) - versatile modular unikernel designed to run unmodified Linux applications securely on micro-VMs in the cloud.
- [Rancher OS](https://rancher.com/rancher-os) - a lightweight, secure Linux distribution, built from containers to run containers well.
- [Atomic](http://www.projectatomic.io/) - use immutable infrastructure to deploy and scale your containerized applications.
- [Photon](https://github.com/vmware/photon) - Linux container host optimized for cloud-native applications, cloud platforms, and VMware infrastructure.

## Distributed Filesystems

*Network distributed filesystems.*

- [Ceph](https://ceph.io/) - highly scalable object, block and file-based storage under one whole system.
- [Gluster](https://www.gluster.org/) - free and open source software scalable network filesystem.
- [LINBIT](https://www.linbit.com/en/) - create, remove, and replicate block storage devices for datacenter scale environments.
- [XtreemFS](http://www.xtreemfs.org/) - fault-tolerant distributed file system for all storage needs.
- [min.io](https://min.io/) - high performance, distributed object storage system.

## Applications Platforms

*Applications management platforms, Containers platform and Containers management.*

- [Openshift](https://www.openshift.com/) - the Kubernetes platform for big ideas.
- [Dokku](http://dokku.viewdocs.io/dokku/) - helps you build and manage the lifecycle of applications.
- [Flynn](https://flynn.io/) - open source platform (PaaS) for running applications in production.
- [Docker](https://www.docker.com/) - create, deploy, and run applications by using containers.
- [Docker Compose](https://github.com/docker/compose) - define and run multi-container applications with Docker.
- [Docker Swarm](https://github.com/docker/swarm) - Docker-native clustering system.
- [Kubernetes](https://kubernetes.io/) - automating deployment, scaling, and management of containerized applications.
- [LXC](https://linuxcontainers.org/) - lets Linux users easily create and manage system or application containers.
- [Rancher](https://rancher.com/) - lets you deliver Kubernetes-as-a-Service.
- [OpenVz](https://openvz.org/) - container-based virtualization for Linux.
- [Singularity](https://sylabs.io/singularity/) - run the application from the local environment to the cloud.
- [AppScale](https://github.com/AppScale/appscale) - easy-to-manage serverless platform for building and running scalable web and mobile applications.
- [Kata Containers](https://katacontainers.io/) - building lightweight virtual machines that seamlessly plug into the containers ecosystem.
- [K3S](https://k3s.io/) - The certified Kubernetes distribution built for IoT and Edge computing.
- [Podman](https://github.com/containers/podman) - a tool for managing OCI containers and pods.

## Container Image Registry

*Container Image registry.*

- [Quay](https://www.projectquay.io/) - container image registry that enables you to build, organize, distribute, and deploy containers.
- [Dockyard](https://github.com/Huawei/dockyard) - Container & Artifact Repository.
- [Harbor](https://goharbor.io/) - an open source trusted cloud native registry project that stores, signs, and scans content.

## Automation & Orchestration

*Tools for automation, orchestration, deployment, provisioning and configuration management.*

- [Ansible](https://www.ansible.com/) - simple IT automation platform that makes your applications and systems easier to deploy.
- [Salt](https://www.saltstack.com/) - automate the management and configuration of any infrastructure or application at scale.
- [Puppet](https://puppet.com/) - unparalleled infrastructure automation and delivery.
- [Chef](https://www.chef.io/) - automate infrastructure and applications.
- [Juju](https://jaas.ai/) - simplifies how you configure, scale and operate today's complex software.
- [Rundeck](https://www.rundeck.com/) - Runbook Automation For Modernizing Your Operations.
- [StackStorm](https://stackstorm.com/) - connects all your apps, services, and workflows. Automate DevOps your way.
- [Bosh](https://www.cloudfoundry.org/bosh/) - release engineering, deployment, and lifecycle management of complex distributed systems.
- [Cloudify](https://cloudify.co/) - Connect, Control, & Automate from core to edge: unlimited locations, clouds and devices.
- [Tsuru](https://tsuru.io/) - an extensible and open source Platform as a Service software.
- [Fabric](http://www.fabfile.org/) - high level Python library designed to execute shell commands remotely over SSH.
- [Capistrano](https://capistranorb.com/) - A remote server automation and deployment tool.
- [Mina](http://nadarei.co/mina/) - really fast deployer and server automation tool.
- [Terraform](https://www.terraform.io/) - use Infrastructure as Code to provision and manage any cloud, infrastructure, or service.
- [Pulumi](https://www.pulumi.com/) - modern infrastructure as code platform that allows you to use familiar programming languages and tools to build, deploy, and manage cloud infrastructure.
- [Packer](https://www.packer.io/) - build Automated Machine Images.
- [Vagrant](https://www.vagrantup.com/) - Development Environments Made Easy.
- [Foreman](https://theforeman.org/) - complete lifecycle management tool for physical and virtual servers.
- [Nomad](https://learn.hashicorp.com/nomad) - deploy and Manage Any Containerized, Legacy, or Batch Application.
- [Marathon](https://mesosphere.github.io/marathon/) - a production-grade container orchestration platform for DC/OS and Apache Mesos.
- [Atlantis](https://github.com/runatlantis/atlantis) - Terraform Pull Request Automation.
- [OctoDNS](https://github.com/github/octodns) - managing DNS across multiple providers. DNS as code.
- [ManageIQ](https://www.manageiq.org/) - Manage containers, virtual machines, networks, and storage from a single platform.
- [Ignite](https://github.com/weaveworks/ignite) -  Open Source Virtual Machine (VM) manager with a container UX and built-in GitOps management.
- [Spacelift](https://spacelift.io/) - Flexible orchestration solution for IaC development.
- [Atlantis](https://www.runatlantis.io/) - Terraform Pull Request Automation.
- [Stacktape](https://stacktape.com) - Developer-friendly Infrastructure as a Code framework built on top of AWS.

## Continuous Integration & Delivery

*Continuous Integration, Continuous Delivery and Continuous Delivery. GitOps*

- On premises
  - [Buildbot](http://buildbot.net/) - automate all aspects of the software development cycle.
  - [Gitlab CI](https://about.gitlab.com/product/continuous-integration/) - pipelines build, test, deploy, and monitor your code as part of a single, integrated workflow.
  - [Jenkins](http://jenkins-ci.org/) - automation server for building, deploying and automating any project.
  - [Drone](https://github.com/drone/drone) - a Container-Native, Continuous Delivery Platform.
  - [Concourse](https://concourse-ci.org/) - pipeline-based continuous thing-doer.
  - [Spinnaker](https://www.spinnaker.io/) - fast, safe, repeatable deployments for every Enterprise.
  - [goCD](https://www.gocd.org/) - Delivery and Release Automation server.
  - [Teamcity](https://www.jetbrains.com/teamcity/) - enterprise-level CI and CD.
  - [Bamboo](https://www.atlassian.com/software/bamboo) - tie automated builds, tests, and releases together in a single workflow.
  - [Integrity](http://integrity.github.io/) - Continuous Integration server.
  - [Zuul](https://zuul-ci.org/) - drives continuous integration, delivery, and deployment systems with a focus on project gating.
  - [Argo](https://argoproj.github.io/) - Open Source Kubernetes native workflows, events, CI and CD.
  - [Strider](https://strider-cd.github.io/) - Continuous Deployment/Continuous Integration platform.
  - [Evergreen](https://github.com/evergreen-ci/evergreen) - A Distributed Continuous Integration System from MongoDB.
  - [werf](https://werf.io/) - Open Source CI/CD tool for building Docker images & deploying them to Kubernetes using a GitOps approach.
  - [Flux](https://github.com/fluxcd/flux) - automatically ensures that the state of your Kubernetes cluster matches the configuration you’ve supplied in Git.
  - [Flagger](https://github.com/weaveworks/flagger) - progressive delivery Kubernetes operator (Canary, A/B Testing and Blue/Green deployments).
  - [Tekton](https://tekton.dev/) - powerful and flexible open-source framework for creating CI/CD systems.
  - [PipeCD](https://pipecd.dev/) - Continuous Delivery for Declarative Kubernetes, Serverless and Infrastructure Applications.
  - [Gitploy](https://www.gitploy.io/) - Build the deployment system around GitHub in minutes.
- Public Services
  - [Travis CI](https://travis-ci.org/) - easily sync your projects, you’ll be testing your code in minutes.
  - [Circle CI](https://circleci.com/) - powerful CI/CD pipelines that keep code moving.
  - [Bitrise](https://www.bitrise.io/) - CI/CD for mobile applications.
  - [Buildkite](https://buildkite.com/) - run fast, secure, and scalable continuous integration pipelines on your own infrastructure.
  - [Cirrus CI](https://cirrus-ci.org/) - continuous integration system built for the era of cloud computing.
  - [Codefresh](https://codefresh.io/) - GitOps automation platform for Kubernetes apps.
  - [Github actions](https://github.com/features/actions) - GitHub Actions makes it easy to automate all your software workflows, now with world-class CI/CD.
  - [Kraken CI](https://kraken.ci/) - modern CI/CD, open-source, on-premise system that is highly scalable and focused on testing.
  - [Earthly](https://earthly.dev/) - Develop CI/CD pipelines locally and run them anywhere.

## Source Code Management

*Source Code management, Git-repository manager, Version Control. Some of them include [Code review](#code-review).*

- [Github](https://github.com/) - helps developers store and manage their code, as well as track and control changes to their code.
- [Gitlab](https://gitlab.com/) - entire DevOps lifecycle in one application.
- [Bitbucket](https://bitbucket.org/product/) - gives teams one place to plan projects, collaborate on code, test, and deploy
- [Phabricator](https://github.com/phacility/phabricator/) - a collection of web applications which help software companies build better software.
- [Gogs](https://gogs.io/) - a painless self-hosted Git service.
- [Gitea](https://gitea.io/) - a painless self-hosted Git service.
- [Gitblit](https://github.com/gitblit/gitblit) - pure Java Git solution for managing, viewing, and serving Git repositories.

## Web Servers

*Web servers and reverse proxy.*

- [Nginx](http://nginx.org/) - high performance load balancer, web server and reverse proxy.
- [Apache](http://httpd.apache.org/) - web server and reverse proxy.
- [Caddy](https://caddyserver.com/) - web server with automatic HTTPS.
- [Cherokee](http://cherokee-project.com/) - highly concurrent secured web applications.
- [Lighttpd](http://www.lighttpd.net/) - optimized for speed-critical environments while remaining standards-compliant, secure and flexible.
- [Uwsgi](https://github.com/unbit/uwsgi/) - application server container.

## SSL

*Tools for automating the management of SSL certificates.*

- [Certbot](https://github.com/certbot/certbot) - automate using Let’s Encrypt certificates on manually-managed websites to enable HTTPS.
- [Let’s Encrypt](https://letsencrypt.org/) - free, automated, and open Certificate Authority.
- [Cert Manager](https://github.com/jetstack/cert-manager) - K8S add-on to automate the management and issuance of TLS certificates from various issuing sources.

## Databases

*Relational (SQL) and non-relational (NoSQL) databases.*

- Relational (SQL)
  - [PostgreSQL](https://www.postgresql.org/) - powerful, open source object-relational database system.
  - [MySQL](https://www.mysql.com/) - open-source relational database management system.
  - [MariaDB](https://mariadb.org/) - fast, scalable and robust, with a rich ecosystem of storage engines, plugins and many other tools.
  - [SQLite](https://sqlite.org/) - small, fast, self-contained, high-reliability, full-featured, SQL database engine.
- Non-relational (NoSQL)
  - [Casandra](http://cassandra.apache.org/) - manage massive amounts of data, fast, without losing sleep.
  - [Apache HBase](http://hbase.apache.org/) - distributed, versioned, non-relational database.
  - [Couchdb](https://couchdb.apache.org/) - database that completely embraces the web.
  - [Elasticsearch](https://www.elastic.co/products/elasticsearch) - distributed, RESTful search and analytics engine capable of addressing a growing number of use cases.
  - [MongoDB](https://www.mongodb.com/) - general purpose, document-based, distributed database built for modern applications.
  - [Rethinkdb](https://github.com/rethinkdb/rethinkdb) - open-source database for the realtime web.
  - Key-Value
    - [Couchbase](https://www.couchbase.com/) - distributed  multi-model NoSQL document-oriented database that is optimized for interactive applications.
    - [Leveldb](https://github.com/google/leveldb) - fast key-value storage library.
    - [Redis](https://redis.io/) - in-memory data structure store, used as a database, cache and message broker.
    - [RocksDB](https://rocksdb.org/) - a library that provides an embeddable, persistent key-value store for fast storage.
    - [Etcd](https://github.com/etcd-io/etcd) - distributed reliable key-value store for the most critical data of a distributed system.

## Observability & Monitoring

*Observability, Monitoring, Metrics/Metrics collection and Alerting tools.*

- [Sensu](https://sensu.io/) - Simple. Scalable. Multi-cloud monitoring.
- [Alerta](https://github.com/alerta/alerta) - scalable, minimal configuration and visualization monitoring system.
- [Cabot](https://github.com/arachnys/cabot) - self-hosted, easily-deployable monitoring and alerts service.
- [Amon](https://github.com/amonapp/amon) - modern server monitoring platform.
- [Flapjack](https://flapjack.io/) - monitoring notification routing + event processing system.
- [Icinga](https://icinga.com/) - monitors availability and performance, gives you simple access to relevant data and raises alerts.
- [Monit](https://mmonit.com/monit/#home) - managing and monitoring Unix systems.
- [Naemon](http://www.naemon.org/) - fast, stable and innovative while giving you a clear view of the state of your network and applications.
- [Nagios](https://www.nagios.org/) - computer-software application that monitors systems, networks and infrastructure.
- [Sentry](https://sentry.io/welcome/) - error monitoring that helps all software teams discover, triage, and prioritize errors in real-time.
- [Shinken](http://www.shinken-monitoring.org/) - monitoring framework.
- [Zabbix](https://www.zabbix.com/) - mature and effortless monitoring solution for network monitoring and application monitoring.
- [Glances](https://github.com/nicolargo/glances) - monitoring information through a curses or Web based interface.
- [Healthchecks](https://github.com/healthchecks/healthchecks) - cron monitoring tool.
- [Bolo](http://bolo.niftylogic.com/) - building distributed, scalable monitoring systems.
- [cAdvisor](https://github.com/google/cadvisor) - analyzes resource usage and performance characteristics of running containers.
- [ElastiFlow](https://github.com/robcowart/elastiflow) - network flow monitoring (Netflow, sFlow and IPFIX) with the Elastic Stack.
- [Co-Pilot](https://pcp.io/) - system performance analysis toolkit.
- Metrics/Metrics collection
  - [Thundra Foresight](https://www.thundra.io/foresight) - visibility into CI pipeline by spotting test failures in no time.
  - [Prometheus](https://prometheus.io/) - power your metrics and alerting with a leading open-source monitoring solution.
  - [Collectd](https://github.com/collectd/collectd) - the system statistics collection daemon.
  - [Facette](https://github.com/facette/facette) - time series data visualization software.
  - [Grafana](https://grafana.com/) - analytics & monitoring solution for every database.
  - [Graphite](https://graphite.readthedocs.io/en/latest/) - store numeric time-series data and render graphs of this data on demand.
  - [Influxdata](https://www.influxdata.com/) - time series database.
  - [Netdata](https://www.netdata.cloud/) - instantly diagnose slowdowns and anomalies in your infrastructure.
  - [Freeboard](https://github.com/Freeboard/freeboard) - real-time dashboard builder for IOT and other web mashups.
- Logs Management
  - [Anthracite](https://github.com/Dieterbe/anthracite) - an event/change logging/management app.
  - [Graylog](https://github.com/Graylog2/graylog2-server) - free and open source log management.
  - [Logstash](https://www.elastic.co/products/logstash#) - collect, parse, transform logs.
  - [Fluentd](https://www.fluentd.org/) - data collector for unified logging layer.
  - [Flume](https://flume.apache.org/) - distributed, reliable, and available service for efficiently collecting, aggregating, and moving logs.
  - [Heka](https://hekad.readthedocs.io/en/latest/#) - stream processing software system.
  - [Kibana](https://www.elastic.co/products/kibana) - explore, visualize, discover data.
  - [Loki](https://github.com/grafana/loki) - horizontally-scalable, highly-available, multi-tenant log aggregation system inspired by Prometheus.
- Status
  - [Cachet](https://github.com/CachetHQ/Cachet) - beautiful and powerful open source status page system.

## Service Discovery & Service Mesh

*Service Discovery, Service Mesh and Failure detection tools.*

- [Consul](https://www.hashicorp.com/products/consul/) - connect and secure any service.
- [Serf](https://www.serf.io/) - decentralized cluster membership, failure detection, and orchestration.
- [Doozerd](https://github.com/ha/doozerd) - a consistent distributed data store.
- [Zookeeper](http://zookeeper.apache.org/) - centralized service for configuration, naming, providing distributed synchronization, and more.
- [Etcd](https://etcd.io/) - distributed, reliable key-value store for the most critical data of a distributed system.
- [Istio](https://istio.io/) - connect, secure, control, and observe services.
- [Kong](https://konghq.com/products/kong-gateway/kong-proxy) - deliver performance needed for microservices, service mesh, and cloud native deployments.
- [Linkerd](https://github.com/linkerd/linkerd2) - service mesh for Kubernetes and beyond.

## Chaos Engineering

*The discipline of experimenting on a distributed system in order to build confidence in the system's capability to withstand turbulent conditions in production.*

- [Chaos Toolkit](https://github.com/chaostoolkit) - the Open Source Platform for Chaos Engineering.
- [Chaos Monkey](https://github.com/Netflix/chaosmonkey) - a resiliency tool that helps applications tolerate random instance failures.
- [Toxiproxy](https://github.com/Shopify/toxiproxy) - simulate network and system conditions for chaos and resiliency testing.
- [Pumba](https://github.com/alexei-led/pumba) - chaos testing, network emulation and stress testing tool for containers.

## API Gateway

*API Gateway, Service Proxy and Service Management tools.*

- [API Umbrella](https://apiumbrella.io/#) - proxy that sits in front of your APIs.
- [Ambassador](https://www.getambassador.io/) - Kubernetes-Native API Gateway built on the Envoy Proxy.
- [Kong](https://konghq.com/) - connect all your microservices and APIs with the industry’s most performant, scalable and flexible API platform.
- [Tyk](https://tyk.io/) - API and service management platform.
- [Cilium](https://github.com/cilium/cilium) - API aware networking and security using BPF and XDP.
- [Gloo](https://github.com/solo-io/gloo) - feature-rich, Kubernetes-native ingress controller, and next-generation API gateway.
- [Envoy](https://www.envoyproxy.io/) - cloud-native high-performance edge/middle/service proxy.
- [Traefik](https://traefik.io/) - reverse proxy and load balancer for HTTP and TCP-based applications.
- [Nginx](https://nginx.org/) - high performance reverse proxy.

## Code review

*Code review. A few of the [Source Code Management](#source-code-management) tools have built-in code review features.*

- [Gerrit](https://www.gerritcodereview.com/) - web-based team code collaboration tool.
- [Review Board](https://www.reviewboard.org/) - web-based collaborative code review tool.

## Distributed messaging

*Distributed messaging platforms and Queues software.*

- [Rabbitmq](https://www.rabbitmq.com/) - message broker.
- [Kafka](http://kafka.apache.org/) - building real-time data pipelines and streaming apps.
- [Activemq](http://activemq.apache.org/) - Multi-Protocol messaging.
- [Beanstalkd](https://beanstalkd.github.io/) - simple, fast work queue.
- [NSQ](https://nsq.io/) - realtime distributed messaging platform.
- [Celery](http://www.celeryproject.org/) - asynchronous task queue/job queue based on distributed message passing.
- [Faktory](https://github.com/contribsys/faktory) - repository for background jobs within your application.
- [Nats](https://nats.io/) - simple, secure and high performance open source messaging system.
- [RestMQ](http://restmq.com/) - message queue which uses HTTP as transport.
- [Dkron](https://github.com/distribworks/dkron) - distributed, fault tolerant job scheduling system.
- [KubeMQ](https://kubemq.io/) - Kubernetes-native messaging platform.

## Programming Languages

*Programming languages.*

- [Python](https://www.python.org/) - programming language that lets you work quickly and integrate systems more effectively.
- [Ruby](https://www.ruby-lang.org/) - a dynamic, open source programming language with a focus on simplicity and productivity.
- [Go](https://golang.org/) - an open source programming language that makes it easy to build simple, reliable, and efficient software.

## Chat and ChatOps

*Chat and ChatOps.*

- [Rocket](https://rocket.chat/) - open source team communication.
- [Mattermost](https://mattermost.com/) - messaging platform that enables secure team collaboration.
- [Zulip](https://zulipchat.com/) - real-time chat with an email threading model.
- [Riot](https://about.riot.im/) - a universal secure chat app entirely under your control.
- ChatOps:
  - [CloudBot](https://github.com/CloudBotIRC/CloudBot) - simple, fast, expandable, open-source Python IRC Bot.
  - [Hubot](https://hubot.github.com/) - a customizable life embetterment robot.
  - [Lita](https://www.lita.io/) - a robot companion for your company's chat room.

## Secret Management

*Security as code, sensitive credentials and secrets need to be managed, security, maintained and rotated using automation.*

- [Sops](https://github.com/mozilla/sops) - simple and flexible tool for managing secrets.
- [Vault](https://www.hashicorp.com/products/vault/) - manage secrets and protect sensitive data.
- [Keybase](https://keybase.io/) - end-to-end encrypted chat and cloud storage system.
- [Vault Secrets Operator](https://github.com/ricoberger/vault-secrets-operator) - create Kubernetes secrets from Vault for a secure GitOps based workflow.
- [Git Secret](https://github.com/sobolevn/git-secret) - a bash-tool to store your private data inside a git repository.

## Sharing

*A collection of tools to help with sharing knowledge and telling the story.*

- [Gitbook](https://github.com/GitbookIO/gitbook) - modern documentation format and toolchain using Git and Markdown.
- [Docusaurus](https://github.com/facebook/docusaurus) - easy to maintain open source documentation websites.
- [Docsify](https://github.com/docsifyjs/docsify/) - a magical documentation site generator.
- [MkDocs](https://github.com/mkdocs/mkdocs/) - project documentation with Markdown.


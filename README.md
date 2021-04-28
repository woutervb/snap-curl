[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-white.svg)](https://snapcraft.io/curl)

Introduction
============

This is the repository that contains the `snapcraft.yaml` file that is used to build the snap version of curl.

Features
========

The snap version of curl, is compiled with the following features enabled:

Protocols:

* dict
* file
* ftp
* ftps
* gopher
* http
* https
* imap
* imaps
* ldap
* ldaps
* mqtt
* pop3
* pop3s
* rtmp
* rtsp
* scp
* sftp
* smv
* smbs
* smtp
* smtps
* telnet
* tftp

And Features:

* alt-svc
* AsynchDNS
* brotli
* GSS-API
* HTTP2
* HTTPS-proxy
* IDN
* IPv6
* Kerneros
* Largefile
* libz
* NTLM
* NTLM_WB
* PSL
* SPNEGO
* SSL
* TLS_SRP
* UnixSockets

Installation
============

At the moment the snap is not released to stable, pending feedback on performance and features, as I am not able to test all of them. This means installation has to be done in the following way:

    snapcraft install curl --channel edge

At a later stage, when a stable release is present this document will be updated to include details on how to do an installation from stable, and on how to switch channels.

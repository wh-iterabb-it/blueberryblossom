blueberryblossom
=========

[![Greenkeeper badge](https://badges.greenkeeper.io/wh-iterabb-it/blueberryblossom.svg)](https://greenkeeper.io/)
[![Travis Badge](https://travis-ci.org/wh-iterabb-it/blueberryblossom.svg?branch=master)](https://travis-ci.org/wh-iterabb-it/blueberryblossom)
[![Dependency Status](https://img.shields.io/david/wh-iterabb-it/blueberryblossom.svg?style=flat)](https://david-dm.org/wh-iterabb-it/blueberryblossom#info=Dependencies)
[![devDependency Status](https://img.shields.io/david/dev/wh-iterabb-it/blueberryblossom.svg?style=flat)](https://david-dm.org/wh-iterabb-it/blueberryblossom#info=devDependencies)
[![codecov](https://codecov.io/gh/wh-iterabb-it/blueberryblossom/branch/master/graph/badge.svg)](https://codecov.io/gh/wh-iterabb-it/blueberryblossom)


### Description:

Blueberryblossom is a small scale honeypot designed to be deployed on a raspberry pi and be easily provisioned to write logs to a 3rd party MongoDB instance.

### Documentation

We are going to try to emulate a few basic ports grouped around common scanning schemes.

 * CounterStrike Server Scan
    - Port(s): 27015,27020
    - Protocol: tcp/udp
 * DNS Scan
    - Port(s): 53
    - Protocol: UDP
 * Dockerd Scan
    - Port(s): 2375
    - Protocol: TCP
 * Elasticsearch Scan
    - Port(s): 9200
    - Protocol: TCP
 * FTP Scan
    - Port(s): 20, 21
    - Protocol: TCP
 * HTTP Alt Scan
    - Port(s): 8080
    - Protocol: TCP
 * IMAP Scan
    - Port(s): 143, 993
    - Protocol: TCP
 * LDAP Scan
    - Port(s): 389, 636
    - Protocol: TCP
 * Memcached Scan
    - Port(s): 11211
    - Protocol: TCP
 * MongoDB Scan
    - Port(s): 27017
    - Protocol: TCP
 * MSSQL Scan
    - Port(s): 1433
    - Protocol: TCP
 * MySQL Scan
    - Port(s): 3306, 33060
    - Protocol: TCP
 * Ping Scan
    - Port(s): 22
    - Protocol: TCP, UDP
 * POP3 Scan
    - Port(s): 110, 995
    - Protocol: TCP
 * Postgres Scan
    - Port(s): 5432
    - Protocol: TCP
 * RDP Scan
    - Port(s): 3389
    - Protocol: TCP
 * Redis Scan
    - Port(s): 6379, 6380
    - Protocol: TCP
 * SMB Scan
    - Port(s): 139, 445
    - Protocol: TCP
 * SMTP Scan
    - Port(s): 25, 465, 587, 2525
    - Protocol: TCP
 * SOCKS Proxy Scan
    - Port(s):
    - Protocol:
 * SSDP/UPNP Scan
    - Port(s):
    - Protocol:
 * SSH Scan
    - Port(s): 22
    - Protocol: TCP
 * Telnet Scan
    - Port(s): 23
    - Protocol: TCP
 * VNC Scan
    - Port(s): 5900
    - Protocol: TCP
 * VOIP Scan
    - Port(s): 5060/5004
    - Protocol: TCP/UDP
 * Web Scan
    - Port(s): 80
    - Protocol:


### Installation

```
npm install
```
### Example Usage

Basic usage
```
npm run start
```

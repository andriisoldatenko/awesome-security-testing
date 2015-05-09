# Awesome Security testing collection
A collection of awesome Security testing resources

>[Security testing](http://en.wikipedia.org/wiki/Security_testing) is a process intended to reveal flaws in the security mechanisms of an information system that protect data and maintain functionality as intended. Due to the logical limitations of security testing, passing security testing is not an indication that no flaws exist or that the system adequately satisfies the security requirements.

>Typical security requirements may include specific elements of confidentiality, integrity, authentication, availability, authorization and non-repudiation. Actual security requirements tested depend on the security requirements implemented by the system. Security testing as a term has a number of different meanings and can be completed in a number of different ways. As such a Security Taxonomy helps us to understand these different approaches and meanings by providing a base level to work from.

[Nmap](https://nmap.org/) - ("Network Mapper") is a free and open source (license) utility for network discovery and security auditing. 
Typical example:
```bash
$ nmap -A -T4 scanme.nmap.org
Starting Nmap 6.47 ( http://nmap.org ) at 2015-05-09 16:01 EEST
Nmap scan report for scanme.nmap.org (45.33.32.156)
Host is up (0.20s latency).
rDNS record for 45.33.32.156: li982-156.members.linode.com
Not shown: 996 closed ports
PORT      STATE SERVICE       VERSION
22/tcp    open  ssh           (protocol 2.0)
| ssh-hostkey:
|   1024 ac:00:a0:1a:82:ff:cc:55:99:dc:67:2b:34:97:6b:75 (DSA)
|   2048 20:3d:2d:44:62:2a:b0:5a:9d:b5:b3:05:14:c2:a6:b2 (RSA)
|_  256 96:02:bb:5e:57:54:1c:4e:45:2f:56:4c:4a:24:b2:57 (ECDSA)
80/tcp    open  http          Apache httpd 2.4.7 ((Ubuntu))
|_http-title: Go ahead and ScanMe!
9929/tcp  open  nping-echo    Nping echo
31337/tcp open  ssl/ncat-chat Ncat chat (users: nobody)
| ssl-cert: Subject: commonName=localhost
| Not valid before: 2015-04-16T04:34:45+00:00
|_Not valid after:  2016-04-15T04:34:45+00:00
1 service unrecognized despite returning data. If you know the service/version, please submit the following fingerprint at http://www.insecure.org/cgi-bin/servicefp-submit.cgi :
SF-Port22-TCP:V=6.47%I=7%D=5/9%Time=554E0547%P=x86_64-apple-darwin14.3.0%r
SF:(NULL,29,"SSH-2\.0-OpenSSH_6\.6\.1p1\x20Ubuntu-2ubuntu2\r\n");

Service detection performed. Please report any incorrect results at http://nmap.org/submit/ .
Nmap done: 1 IP address (1 host up) scanned in 38.83 seconds
```





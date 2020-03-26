---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I’m a PhD student of Computer Science Department at [University of California, Los Angeles (UCLA)](http://www.ucla.edu), under the supervision of [Prof. Lixia Zhang](http://web.cs.ucla.edu/~lixia/old-papers.html). Before coming to UCLA, I recevied my Bachelor degree on Electronic and Information Science and Technology from [Sichuan University](http://www.scu.edu.cn). Currently my reseach interests are [Named Data Networking (NDN)](https://named-data.net) and Internet of Things, specifically:

* Lightweight Protocols for Named Data Networking of Things
* Resilient and Secure Smart Home Systems


## Education 
-----------------
* Fall 2019 - Now, Ph.D. student, Computer Science Department, UCLA
* Fall 2015 - Spring 2019, College of Electrnoics and Information Engineering, Sichuan University

## Tools
-----------------
**[NDN-Lite](https://github.com/named-data-iot/ndn-lite)**  

The NDN-Lite library implements the Named Data Networking Stack with the high-level application support functionalities and low-level OS/hardware adaptations for Internet of Things (IoT) scenarios. The library is written in standard C and requires a minimum version of C11 (ISO/IEC 9899:2011).  

**[Named Data Networking Neighbor Discovery (NDND)](https://github.com/Zhiyi-Zhang/NDND)**  

Named Data Networking proposes a fundamental change to the Internet’s architecture, moving from a point-to-point to a data-centric model. NDN can run over layer 2 (WiFi, Bluetooth, etc) or over TCP/UDP/IP. When running over IP, NDN hosts need a way of automatically discovering and establishing connectivity with each other. This project provides an implementation of NDN Neighbor Discovery service, which uses a rendezvous server to allow NDN hosts in the same network to discover each other and automatically establish NDN connectivity by creating UDP/IP tunnels among them.
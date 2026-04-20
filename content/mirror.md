---
title: Mirror
---

## About

The UMBC Linux Users Group operates a high-performance public mirror service dedicated to supporting the broader free and open-source software community. Our mirror provides fast, reliable access to popular Linux distributions and packages hosted within UMBC's datacenter.

The mirror runs on robust server hardware generously donated by members of our community and is managed by our dedicated sysadmin team. By maintaining this service, we aim to reduce bandwidth costs for the FOSS ecosystem while providing students and developers with quick local access to essential Linux resources.

**Access the mirror:**

- **HTTPS:** [https://mirror.lug.umbc.edu](https://mirror.lug.umbc.edu)
- **HTTP:** [http://mirror.lug.umbc.edu](https://mirror.lug.umbc.edu)
- **RSYNC:** rsync://mirror.lug.umbc.edu

Uptime information can be found at https://uptime.blahaj.uno/status/lug

## Supported Distributions

We currently maintain synced mirrors of the following Linux distributions, with updates synced periodically throughout the day:

| Distribution      | Coverage                        |
|-------------------|---------------------------------|
| **Arch Linux**    | Full repository                 |
| **Debian**        | Full repository                 |
| **Ubuntu**        | Packages & Release ISO images   |
| **Linux Mint**    | Packages & ISO images           |
| **Manjaro**       | *In Progress*                   |
| **EndeavourOS**   | Full repository                 |
| **Puppy Linux**   | Full distribution archive       |
| **EasyOS**        | Full distribution archive       |
| **Fatdog**        | Full distribution archive       |
| **Kali Linux**    | *In Progress*                   |
| **Alpine**        | *In Progress*                   |

All repositories are synchronized automatically using the [archvsync](https://salsa.debian.org/mirror-team/archvsync) tool suite maintained by the Debian community.

## Infrastructure

Our mirror service is powered by enterprise-grade hardware:

**Primary Server:** Dell R710
- **CPU:** 2x Intel Xeon X5660 (12 cores, 24 threads total)
- **Memory:** 160GB DDR3
- **Operating System** Proxmox Virtual Environment
- **Storage:** 12TB+ of dedicated mirror storage
  - 6x SAS hard drives (4TB & 8TB)
  - 1TB SATA SSD for hypervisor
  - 512Gb NVMe read cache for performance optimization
  
**Router:** Dell Optiplex 7010
- **CPU:** Intel Core i7-3770 (4 cores, 8 threads)
- **Memory:** 16GB DDR3
- **Operating System** OPNsense

**Network:** 5 Gigabit uplink  
**Location:** UMBC Departmental Computer Room

![UMBC LUG Server Rack - August 2025](/images/Rack-2026-03.jpg)

## History

**October 2023** - Sean Stultz (then LUG President) proposes establishing a community mirror service

**January 2025** - Alex Merryman commits to launching the mirror and begins acquiring hardware through community donations

**April 2025** - Initial outreach to UMBC's Division of Information Technology (DoIT)

**May 2025** - Formal approval obtained from DoIT to host infrastructure in the campus datacenter

**June 2025** - Server installed and setup in the UMBC datacenter

**August 2025** - Mirror enters beta operation with initial distribution repositories

**February 2026** - Full sysadmin team onboarded for ongoing operations and maintenance

## Project Team

**Project Founders & Current Leadership:**
- Alex Merryman, LUG President
- Danielle Esposito, LUG Vice President

**Community Hardware Contributors:**
- Alex Merryman
- Danielle Esposito
- AJ Angarita
- LMN1460
- Ryan Cather

**System Administration Team**
- Hamza Asher Alneam
- Heath Long
- Isaac De Silva

**Community Supporters**
- Sean Stultz | LUG
- Ryan Cather | SAD
- Geoff Weiss | CSEE
- Timothy Boyle | DoIT
- Tim Champ | DoIT
- Ray Soellner | DoIT
- Maya Larson | Advisor

This project wouldn't exist without the generous donations of hardware and time from our community members.

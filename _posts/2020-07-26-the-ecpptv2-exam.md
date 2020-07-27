---
layout: post
title: The eCPPTv2 Exam
comments: true
tags: ecppt
---

Last week, I took the [eCPPTv2](https://www.elearnsecurity.com/certification/ecpptv2/) exam and passed. This post covers my experience with the PTP (Penetration Testing Professional) course and the corresponding eCPPT exam.

### Tools
The following is a list of tools and applications I used while working through the PTP course and taking the eCPPT exam.

* [OneNote](https://onenote.com/) is my go-to notetaking tool. It's where I stored all of my PTP/eCPPT notes
* [VirtualBox](https://www.virtualbox.org/) is the virtualization platform I ran Kali Linux with
* [Kali Linux](https://www.kali.org/) is the pentesting Linux distro that eLearnSecurity recommends

### The Course
PTP covers (mostly) everything a student needs to know to pass the exam. There are several sections:

* System Security
* Network Security
* PowerShell for Pentesters (Elite only)
* Linux Exploitation
* Web App Security
* Wi-Fi Security
* Ruby and Metasploit (Elite only)

I studied every section except for Wi-Fi Security. The two "Elite only" sections are extra information, which is good to know on the exam, but a student can pass without them. I had bought the Elite version of PTP mainly for extra lab time (120 hours total). By the time I took the exam, I had used up over 76 hours of it.

Each module is comprised of several chapters. Each chapter has its own slide deck. These slides can be downloaded if the student has the Elite version of PTP, if not, they can be read through the HTML5 player. Most of these chapters also have a video (or more), and have a corresponding lab environment (or multiple). 

eLearnSecurity takes a guided approach to learning. The slides help introduce new concepts to the student. The videos then reinforce those concepts by presenting a walkthrough or tutorial. Finally, the student can play around in the labs to fully grasp these concepts.

Each lab environment comes with a PDF explaining the scenario: which netblocks are in scope, what tools to use, and what tasks the student should complete while working in the lab. Some labs are walkthroughs, where the student is guided through each task (without spoiling the lab). Others are "blind", providing no assistance on how to go about each task. Solutions are provided for each lab, if a student is stuck or in need of help.

I supplemented PTP with some TryHackMe boxes, most of them dealing with buffer overflows. See [references](#references).

### The Exam
The exam is 14 days long: 7 days for the actual penetration test, and 7 days for reporting.

I found the exam challenging, for reasons I can't say here. But it was fun -- I never got bored while hacking away at the environment.

The report is the most important part of the exam. A test-taker can root all of the machines, but fail the exam if they do not report properly. Test-takers can submit their report anytime before the end of the 14th day. It can take up to 30 days for eLearnSecurity to pass or fail a student after their submission. 

I submitted my report, which was about 40 pages long, at the end of the 7th day. I based my report off of [Heath Adam's Pentest Report Template](https://github.com/hmaverickadams/TCM-Security-Sample-Pentest-Report), and included all of the content that the Letter of Engagement said should be in the report. I received a response in less than a day stating that I had passed. :)

Tips:
* Screenshot (or capture) everything while hacking away in the exam environment
* Prepare a report template chosen before the exam
* Create a cheat sheet (or find one) filled with one liners and commands that are good-to-know
* Remember that there is more than one way to do something -- keep trying
* Know how to pivot

### References
TryHackMe machines:
* [Gatekeeper](https://tryhackme.com/room/gatekeeper)
* [Brainpan](https://tryhackme.com/room/brainpan)
* [Brainstorm](https://tryhackme.com/room/brainstorm)
* and all of the other machines on the [OSCP](https://tryhackme.com/path/outline/OSCP) path

Pivoting:
* [Exploring Hidden Networks with Double Pivoting](https://pentest.blog/explore-hidden-networks-with-double-pivoting/)
* [Tunneling and Pivoting](https://0xdf.gitlab.io/2019/01/28/pwk-notes-tunneling-update1.html)

Cheat sheets:
* [eCPPT Field Guide](https://drive.google.com/file/d/1wC7RMTrWjt74rO8u4X-zM89T_hZzF_A5/)
* [Reverse Shells](http://pentestmonkey.net/cheat-sheet/shells/reverse-shell-cheat-sheet)

### Final Thoughts
I'm glad I had the opportunity to study PTP and take the eCPPT exam. I think I might go through PWK and attempt the OSCP... but that's for another day.

![eCPPT Certificate](/media/eCPPT_cert.png)

Thanks for reading.

---
title: Empire Hacking
subtitle: Past Presentations from our Meetups
layout: default
permalink: /archive/
---

## Speak at a Meetup

You could be listed here! [Submit your talk now](/about/#speak-at-a-meetup).

## October 2017

### Understanding Windows Defender’s JS Engine 
Windows Defender’s MsMpEng.dll implements the core of Defender’s functionality in an enormous 10+ MB, 45,000+ function DLL. In this presentation, we’ll look at the ~1,200 functions that make up Defender’s in-house developed JavaScript engine, which is used for analyzing potentially malicious JS. Defender implements a full JS engine, while being significantly simpler than the engines found in modern web browsers, so it is an interesting and relatively tractable target for reverse engineering from binary. Alexei Bulazel is a security researcher at River Loop Security, and a graduate of RPI where he worked on anti-emulation techniques for malware.

### Post-Exploitation on Kubernetes 
Kubernetes has become the de facto system for container orchestration. It makes scaling and deploying containers much easier, but there's a lot left to consider from the security perspective. This talk focuses on post-exploitation techniques and will cover pivoting, persistence, and data exfiltration as they are done on Kubernetes. Omar is a security engineer at Etsy.

## August 2017

Empire Hacking hosted end-of-summer presentations from a group of interns from around NYC. 

* Kareem El-Faramawi, Trail of Bits
* JP Smith, Trail of Bits
* Theofilos Petsios, Trail of Bits
* Spencer Michaels, NCC Group
* Joel Margolis, NCC Group
* Jules Denardou, Datadog
* Aleksey and Ofer, HYPR
* Kimberly Hou, MongoDB

## June 2017

### Lessons in PL Theory: Modern type systems
JP Smith, a security engineering intern at Trail of Bits, discussed modern type systems and their applications to security. He covered dependent types and their applications enforcing strong invariants at compile time. Then, he reviewed how affine types can be used for better memory safety in languages like Rust.

### True facts about the qmail source code  
qmail is extraordinary in that it was written in C, implements a complex protocol, and has had no impactful security bugs for over 10 years. Mark has reviewed the qmail source code for a project at Trail of Bits and will share several of the idiosyncrasies and interesting details he has found. Mark Mossberg is a security engineer at Trail of Bits.

### Smart uses for dumb fuzzing 
MongoDB's homegrown JavaScript fuzzer has proven itself to be the most prolific bug hunter, responsible for finding around 250 bugs over the course of two release cycles. The fuzzer is "dumb" in the sense that it mostly isn't aware of any MongoDB; In this talk, Robert Guo will discuss how we made MongoDB's fuzzer "dumb" and why this seemingly counter-intuitive strategy is successful. Additionally, we'll demonstrate how dumb fuzzing allowed us to conduct a thorough testing of a number of new projects quickly with very little extra work.  Robert Guo is a software engineer on MongoDB's developer productivity team.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">CS class or <a href="https://twitter.com/EmpireHacking">@EmpireHacking</a> <a href="https://twitter.com/Etsy">@Etsy</a> <a href="https://t.co/4ukGGJFsi5">pic.twitter.com/4ukGGJFsi5</a></p>&mdash; Pete Taylor (@taylopet) <a href="https://twitter.com/taylopet/status/874766775887556608">June 13, 2017</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

## April 2017

### Intro to Rust Lightning Talk 
Efe Alatan, a senior at NYU Tandon, gave a brief overview Rust.

### Dissecting a Fingerprint Sensor
Daniel Lawson hacked a fingerprint sensor 10 ways from Sunday and shared his findings with us. All bugs identified were reported the vendor and are in the process of being fixed. Dan is a security consultant at MWR.

### Transport Layer Security 1.3 
The protocol that protects most of the Internet secure connections is getting the biggest ever revamp, and is losing a round-trip. We will explore differences between TLS 1.3 and previous versions in detail, focusing on the security improvements of the new protocol as well as some of the challenges we face around securely implementing new features such as 0-RTT resumption. At Cloudflare we will be the first to deploy TLS 1.3 on a wide scale, and we’ll be able to discuss the insights we gained while implementing and deploying this protocol. Nick Sullivan is the head of cryptography at Cloudflare.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Getting ready for tonight <a href="https://twitter.com/Work_Bench">@work_bench</a> <a href="https://t.co/AtCp7vTLjq">pic.twitter.com/AtCp7vTLjq</a></p>&mdash; Empire Hacking (@EmpireHacking) <a href="https://twitter.com/EmpireHacking/status/851917544206348291">April 11, 2017</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

## February 2017

### Manticore Demo 
Mark Mossberg of Trail of Bits gave a short demo of Manticore, a ruthlessly effective hybrid symbolic-concrete (“concolic”) execution system that scales to large programs with numerous dependencies, complex interaction, and manual setup. Manticore is being prepared for a public release in March. 

### Bootstrapping a slightly more secure laptop 
Heads is an open source custom firmware and OS configuration for laptops and servers that aims to provide slightly better physical security and protection for data on the system. Unlike Tails, which aims to be a stateless OS that leaves no trace on the computer of its presence, Heads is intended to store data and state. It targets specific models of commodity hardware and takes advantage of lessons learned from vulnerability research. This talk provides an overview of Heads, a demo of installing it on a Thinkpad, and a tour of the attacks that it protects against. Presented by Trammell Hudson. 

### When Bad Things Happen to Good Computers 
We discuss the current state-of-the-art in the field of electromagnetic fault injection (EMFI) and our on-going research into the matter. We present motivational examples show-casing the potential capabilities of EMFI techniques against secure embedded hardware. We also discuss the draw-backs of traditional EMFI techniques and hard physical limitations of such techniques in its current incarnation. Lastly, we informally unveil our soon-to-be-open-sourced BadFET, a high-powered nano-second zero-recovery time multiple firing EMP system, and yes, it will probably kill you if you touched it. Presented by Ang Cui and Rick Housley of Red Balloon Security.

## December 2016

### Be a Binary Rockstar: An Intro to Program Analysis with Binary Ninja 
Many static analyses, such as LLVM passes, depend on the ability to compile source code and cannot operate on binaries. Binary Ninja offers a new Intermediate Language (IL) that makes running such analyses on binaries much easier. I will describe how to use the Binary Ninja IL to automatically discover memory corruption vulnerabilities in binary code, and introduce the concepts of variable analysis, abstract interpretation, and integer range analysis in the process. Presented by Sophia D'Antoine of Trail of Bits.

### Shuffler: Fast and Deployable Continuous Code Re-Randomization 
Just-In-Time ROP (JIT-ROP) techniques, where an attacker uses a memory disclosure vulnerability to discover code gadgets at runtime are particularly pernicious. We designed a code-reuse defense, called Shuffler, which continuously re-randomizes code locations on the order of milliseconds, introducing a real-time deadline on the attacker. Shuffler focuses on being fast, self-hosting, and nonintrusive to the end user. Evaluation shows that Shuffler defends against all known forms of code reuse, including ROP, direct JIT-ROP, indirect JIT-ROP, and Blind ROP. Presented by David Williams-King, a PhD student at Columbia University.

## October 2016

### Differential Fuzzing with LLVM's LibFuzzer 
We extended libFuzzer to support differential fuzzing of applications of similar functionality (e.g., SSL libraries) and developed a set of new metrics to guide input generation, particularly retrofitted towards differential testing. We'll be doing a demo of the engine and present some of the bugs we found. Presented by Theofilos Petsios and Adrian Tang, PhD candidates at Columbia University.

### Firing Rounds at the Analysis Shooting Gallery 
DARPA spent hundreds of thousands of my tax dollars creating small C and C++ programs that include exploitable software flaws. We took those programs, ported them to Linux and OS X, and used them as a shooting gallery for static and dynamic analysis tools. Let’s see where each tool excels and where each tool fails. Presented by Ryan Stortz, a principal security researcher at Trail of Bits.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Lots of new faces at our meeting last week with almost 100 total attendees. Here&#39;s some feedback we received: <a href="https://t.co/jBtv9e3wzA">pic.twitter.com/jBtv9e3wzA</a></p>&mdash; Empire Hacking (@EmpireHacking) <a href="https://twitter.com/EmpireHacking/status/788061374127730688">October 17, 2016</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

## August 2016

### ProtoFuzz: A Google Protocol Buffers Message Generator
Yan Ivnitskiy, a Principal Security Engineer at Trail of Bits, presented [ProtoFuzz](https://github.com/trailofbits/protofuzz), a generic fuzzer for Google’s Protocol Buffers format. Instead of defining a new fuzzer generator for custom binary formats, protofuzz automatically creates a fuzzer based on the same format definition that programs use. ProtoFuzz is implemented as a stand-alone Python3 program.

### Dash: A Web-based tool for Writing Shellcode
Pete Markowsky, a security researcher from NYC, presented [Dash](https://github.com/pmarkowsky/dash), a simple Python Flask-based web application for reading and writing assembly. Think of it as a REPL for various assembly languages. Dash explores how one might design an IDE for writing shellcode.

### Algo: A 1-click IPSEC VPN in the Cloud 
Dan Guido, CEO of Trail of Bits, presented [Algo VPN](https://github.com/trailofbits/algo), a set of Ansible scripts that simplifies the setup of an IPSEC VPN. It contains the most secure defaults available, works with common cloud providers, and does not require client software on most devices.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">cool hacking meetup in NYC <a href="https://t.co/cpRKELA9p3">https://t.co/cpRKELA9p3</a>  <a href="https://twitter.com/dguido">@dguido</a> <a href="https://t.co/gUMFoyrEp7">https://t.co/gUMFoyrEp7</a></p>&mdash; Elissa Shevinsky (@ElissaBeth) <a href="https://twitter.com/ElissaBeth/status/764545955664318464">August 13, 2016</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

## June 2016

### Doorman: An OSQuery Fleet Manager
OSQuery turns operating system information into a format that can be queried using standard SQL-based statements. But once you’ve got that data, how do you search it? Until now, you’d have to engineer your own front-end management console. Enter [Doorman](https://github.com/mwielgoszewski/doorman). This simple web interface allows you to manage your entire fleet of OSQuery machines. In this Empire Hacking talk, Marcin Wielgoszewski, a security engineer, demonstrated how Doorman works, and answered questions about its deployment and use.

### Tidas: Passwordless Auth with the Secure Enclave
Nick Esposito, a Senior Software Engineer at Trail of Bits, discussed the design of [Tidas](https://blog.trailofbits.com/2016/06/28/start-using-the-secure-enclave-crypto-api/), a solution for password-free authentication for iOS software developers. Tidas takes advantage of our unique capability to generate and store ECC keys inside the Secure Enclave.

### Beyond Corp: Lessons learned from 5 years of endpoint attestation
An increasingly mobile workforce and the ubiquity of attacks on client platforms limit the effectiveness of the traditional corporate network perimeter-security model. Beyond Corp is a broad effort to re-architect the delivery of Google corporate computing services, removing privileges granted solely on the basis of network address. The underlying architecture relies on a model of machine identity, authentication, and state-aware authorization to provide differential to services. August Huber, a data defender at Google, discussed the background of the work, general approach, challenges encountered, and future directions.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">We just broke our pre-registration record (75 hackers)! Come see BeyondCorp, Tidas, and Doorman tomorrow <a href="https://twitter.com/Spotify">@Spotify</a> <a href="https://t.co/tlBDTOu5md">https://t.co/tlBDTOu5md</a></p>&mdash; Empire Hacking (@EmpireHacking) <a href="https://twitter.com/EmpireHacking/status/739844573732687873">June 6, 2016</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

## April 2016

### Putting the Hype in Hypervisor
Brandon Falk, a software security researcher, operating system developer and fuzzing enthusiast, presented various ways of gathering code coverage information without binary modification and how to use code coverage to direct fuzzing.

### Crypto Challenges and Fails
Ben Agre, a computer security consultant, distinguished successful crypto challenges from failures through the lens of challenges offered by RSA, Telegram, and several smaller examples.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Great week: Hanging out at the NCC NYC office, going to <a href="https://twitter.com/EmpireHacking">@EmpireHacking</a>, and seeing David Gilmour at MSG tonight!</p>&mdash; David Schuetz (@DarthNull) <a href="https://twitter.com/DarthNull/status/719500863040069632">April 11, 2016</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

## February 2016

### Reversing Engineering the Tytera MD380 2-way Radio
Travis Goodspeed, a neighbor, explained how the handheld digital radio used for the Digital Mobile Radio (DMR) protocol was jailbroken to allow for patching and firmware extraction, as well as the tricks used to patch the firmware for new features, such as promiscuous mode and a secondary application.

### The Mobile Application Security Toolkit (MAST)
Sophia D'Antoine addressed the design of the Mobile Application Security Toolkit (MAST) which ties together jailbreak detection, anti-debugging, and anti-reversing in LLVM for protection of iOS applications.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">not much worst than being in new york but not being able to attend <a href="https://twitter.com/EmpireHacking">@EmpireHacking</a> . will have to catch the next one! <a href="https://twitter.com/hashtag/infosec?src=hash">#infosec</a> <a href="https://twitter.com/nysecsec">@nysecsec</a></p>&mdash; geminiimatt/&#39;mateo&#39; (@geminiimatt) <a href="https://twitter.com/geminiimatt/status/697209141039910913">February 10, 2016</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

## December 2015

### Exploiting Out-of-Order Execution for Covert Cross-VM Communication
Sophia D'Antoine, one of our security engineers, demonstrated a novel [side channel](https://blog.trailofbits.com/2015/07/21/hardware-side-channels-in-the-cloud/) that exploits out-of-order execution to enable cross-VM communication.

### Experiments building and visualizing hypergraphs of security data
Richard Lethin, President of Reservoir Labs, discussed data structures and algorithms that enable the representation and analysis of big data (such as security logs) as hypergraphs.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Packed house tonight! <a href="https://t.co/wCDxoyW2zQ">pic.twitter.com/wCDxoyW2zQ</a></p>&mdash; Empire Hacking (@EmpireHacking) <a href="https://twitter.com/EmpireHacking/status/674372987047583744">December 8, 2015</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

## October 2015

### The PointsTo Use-After-Free Detector
Peter Goodman, our very own dynamic binary translator, presented the design of [PointsTo](https://blog.trailofbits.com/2016/03/09/the-problem-with-dynamic-program-analysis/), an LLVM-based static analysis system that automatically finds use-after-free vulnerabilities in large codebases.

### Protecting Virtual Function Calls in COTS C++ Binaries
Aravind Prakash, an assistant professor in the Dept. of Computer Science at Binghamton University, showed how [vfGuard](https://scholar.google.com/citations?view_op=view_citation&hl=en&oe=ASCII&user=GqFjHVAAAAAJ&sortby=pubdate&citation_for_view=GqFjHVAAAAAJ:IjCSPb-OGe4C) protects virtual function calls in C++ from control subversion attacks.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Definitely enjoyed <a href="https://twitter.com/EmpireHacking">@EmpireHacking</a> prog analysis talks tonight, thanks <a href="https://twitter.com/dguido">@dguido</a> for making this happen! I&#39;ll be there next time with more Q&#39;s!</p>&mdash; Julien Vanegue (@jvanegue) <a href="https://twitter.com/jvanegue/status/654109659155050496">October 14, 2015</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

## August 2015

### Exploiting the Nintendo 3DS
Luke Arntson, a hobbyist security researcher, reverse engineer, and hardware hacker, highlighted the origins of the Nintendo DS Profile exploit, the obfuscated Gateway browser exploit, and the payloads used by both.

### Trail of Bits Cyber Grand Challenge (CGC) Demo
Ryan Stortz, one of our security engineers, described the high-level architecture of the system we built to fight and destroy insecure software as part of a DARPA competition, how [well](http://blog.trailofbits.com/2015/07/15/how-we-fared-in-the-cyber-grand-challenge/) it worked, and difficulties we overcame during the development process.

### OS X Malware
Jay Little, another of our security engineers, gave a code review of Hacking Team’s OS X kernel rootkit in just 10 minutes.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Loving this turbo talk on OS X Malware! Helpful &amp; Jay Little = hilarious! launchd my new friend. <a href="https://twitter.com/EmpireHacking">@empirehacking</a> <a href="http://t.co/hpKsDtSmRf">pic.twitter.com/hpKsDtSmRf</a></p>&mdash; geminiimatt/&#39;mateo&#39; (@geminiimatt) <a href="https://twitter.com/geminiimatt/status/631257633345925120">August 12, 2015</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

## June 2015

### Offense at Scale
Chris Rohlf from Yahoo discussed the effects of scale on vulnerability research, fuzzing and real attack campaigns.

### Automatically proving program termination (and more!)
Dr. Byron Cook, Professor of Computer Science at University College London, shared research advances that have led to [practical tools](http://mmjb.github.io/T2/) for automatically proving program termination and related properties.

### Cellular Baseband Exploitation
Nick DePetrillo, one of our principal security engineers, explored the challenges of reliable, large-scale cellular baseband exploitation.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">&quot;Halting problem? What halting problem?&quot; Byron Cook at <a href="https://twitter.com/EmpireHacking">@EmpireHacking</a>, basically.</p>&mdash; Jan Schaumann (@jschauma) <a href="https://twitter.com/jschauma/status/608419777376301056">June 9, 2015</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

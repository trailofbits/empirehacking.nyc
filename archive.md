---
title: Empire Hacking
subtitle: Past Presentations from our Meetups
layout: default
permalink: /archive/
---

## Speak at a Meetup

You could be listed here! [Submit your talk now](/about/#speak-at-a-meetup).

## June 2020

### Detecting transaction displacement attacks with Manticore
In a transaction displacement attack, an attacker inserts their transaction ahead of a legitimate one, to steal rewards associated with the legitimate transaction. Transaction displacement attacks can be subtle, and designing a smart contract API that avoids them is not easy. This talk will describe recent work on a displacement attack detector for Manticore, Trail of Bits' symbolic execution tool. Sam Moelius is a security engineer at Trail of Bits.

### Language-Based Reverse Engineering: a Vision for the Future
Reverse engineering, vulnerability hunting, and exploit development all require a large amount of logical reasoning alongside application-specific (e.g., protocol) understanding. Program analyses should perform logical reasoning for us. But applying that logical reasoning alongside the application-specific reasoning is challenging in practice. This is because analysis tools (such as pointer analyses, etc..) often use complex models built on the idea that require expert understanding (such as abstract interpretation). Thus, such an approach requires expert security understanding, application-specific (e.g., protocol), and the ability to re-engineer analysis tools. In this talk, I will share a broad vision for language-based reverse engineering, a paradigm that uses language-based techniques to describe exploits in a way that allows leveraging these tools without building custom program analyses from the ground up. I will describe several concrete examples involving declarative programming and symbolic execution. Kristopher Micinski is an assistant professor at Syracuse University.

## April 2020

### Enarx - Secured, Attested Execution on Any Cloud
Enarx makes it simple to deploy confidential workloads to a variety of TEEs in the public cloud by handling deployment and attestation. Enarx is CPU-architecture independent and enables the same application code to be deployed across multiple targets, abstracting away issues such as cross-compilation and differing attestation mechanisms between the hardware vendors of available TEEs. Enarx uses WebAssembly to offer developers a wide range of compatible language choices for workloads, eliminating the need to rewrite the application for a particular TEE’s platform or SDK. Our work is currently underway on AMD’s SEV and Intel’s SGX hardware. The Enarx project is open source and looking to expand our community involvement. Lily Sturmann and Mark Bestavros are Security Engineers at Red Hat in Boston.

### Computers and Humans Should break Things Together
When it comes to finding deep vulnerabilities the best tool isn't AFL or OSS-Fuzz, it's a security engineer with too much free time. Where do our automated tools fall short? What can be done about it? Tonight, Carson is going to try and convince you that one solution is that computers and humans should break things together. Over the past year Trail of Bits has been doing research on how to make program analysis tools more human centric, which allows humans to help their tools dig deeper into programs and discover new classes of vulnerabilities. Bring your own beer, it's bug finding time. Carson Harmon is a Security Engineer at Trail of Bits.

## February 2020

### A Day in the Life of an Engineering Intern
During her fall internship Rachel worked on implementing macaroons into Warehouse, the codebase that powers PyPI. Macaroons are fast, flexible and secure alternatives to cookies. She also revisited the osquery support for insights about a system’s Google Chrome extensions by adding test cases, bug fixing, and enhancing related capability. Her talk will cover contributions to the deployment of macaroons on PyPI and support for Chrome extensions on osquery. Rachel Cipkins is an undergraduate student at Stevens Institute of Technology (B.S Computer Science 2022) and an engineering intern at Trail of Bits.

### Encrypted Search: from Research to Real-World Systems
The problem of designing end-to-end encrypted systems has driven the cryptography research community to study the problem of "searching on encrypted data" for about two decades. This sub-area of cryptography, known as Encrypted Search, has grown tremendously and several approaches have been proposed to encrypt databases, outsource them, and perform encrypted queries on them. In this talk, we will cover the state of the art in Encrypted Search. We will review different cryptographic primitives, their advantages, limitations, and readiness for real-world deployment. Evan Sultanik is a security engineer at Trail of Bits. Tarik Moataz is co-founder and CTO of Aroki Systems (https://aroki.com) and a visiting scientist at Brown University. His research includes major advances in encrypted search that have appeared at the top cryptography conferences, including IACR CRYPTO, Eurocrypt, Asiacrypt and Real-World Crypto.

## December 2019

### Real-Time Cryptocurrency Exchange Using Trusted Hardware:
Tesseract is a secure real-time cryptocurrency exchange service. Existing centralized exchange designs are vulnerable to theft of funds, while decentralized exchanges cannot offer real-time cross-chain trades. All currently deployed exchanges are also vulnerable to frontrunning attacks. Tesseract overcomes these flaws and achieves a best-of-both-worlds design by using a trusted execution environment. It supports not only real-time cross-chain cryptocurrency trades, but also secure tokenization of assets pegged to cryptocurrencies. For instance, Tesseract-tokenized bitcoins can circulate on the Ethereum blockchain for use in smart contracts. Yan Ji is a PhD student at Cornell University.

<blockquote class="twitter-tweet"><p lang="en" dir="ltr"><a href="https://twitter.com/iseriohn42?ref_src=twsrc%5Etfw">@iseriohn42</a> presented on Tesseract, a secure real-time cryptocurrency exchange, at <a href="https://twitter.com/EmpireHacking?ref_src=twsrc%5Etfw">@EmpireHacking</a>. <br><br>Work by Iddo Bentov, herself, <a href="https://twitter.com/0xFanZhang?ref_src=twsrc%5Etfw">@0xFanZhang</a>, Yunqi Li, Xueyuan Zhao, <a href="https://twitter.com/ethlorenz?ref_src=twsrc%5Etfw">@ethlorenz</a>, <a href="https://twitter.com/phildaian?ref_src=twsrc%5Etfw">@phildaian</a>, and <a href="https://twitter.com/AriJuels?ref_src=twsrc%5Etfw">@AriJuels</a>. <br><br>Slides <a href="https://t.co/dcRyzYg1e7">https://t.co/dcRyzYg1e7</a> and paper <a href="https://t.co/TDPAHXxYkq">https://t.co/TDPAHXxYkq</a></p>&mdash; IC3 (@initc3org) <a href="https://twitter.com/initc3org/status/1204905992573607936?ref_src=twsrc%5Etfw">December 11, 2019</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

### The Treachery of Files, and Two New Tools that Tame It:
Parsing is hard, even when a file format is well specified. But when the specification is ambiguous, it leads to unintended and strange parser and interpreter behaviors that make file formats susceptible to security vulnerabilities. What if we could automatically generate a “safe” subset of any file format, along with an associated, verified parser? This talk explores that question, provides examples of malicious files, examines some troublesome parsers, and introduces two new tools for reverse engineering files and parsers. PolyFile is a tool for exploring the contents and structure of files to detect funky file tricks like steganography, polyglots, and chimeras. PolyTracker can instrument parsers to perform efficient universal taint tracking, to associate which bytes of the input file are operated on by which functions. Used in conjunction, these tools will permit us to specify safer subsets of file formats. Evan Sultanik is a security engineer at Trail of Bits.

<iframe width="560" height="315" src="https://www.youtube.com/embed/LqRbfzhcI5g" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## October 2019

### Lightning Talks:
* Dan Goetzel on the Cyber NYC Inventor to Founder Accelerator
* Jessica Nelson on the NYC chapter of Women in Cybersecurity (WiCyS)
* Rachel Cipkins (ToB) on replacing cookies with macaroons on PyPi

### How to build the ultimate malvertising payload
This presentation will be framed from the point of view of a malvertiser, or threat actor that is trying to leverage digital advertising in order to spread malware or conduct fraud. We focus on the iterative approach an attacker like this would take in order to optimize their client-side payload and tactics in order to maximize the success of their campaigns.
Jerome Dangu, CTO and Co-founder, and Eliya Stein, Security Engineer at Confiant.

### ZombieLoad: Cross-Privilege-Boundary Data Sampling
Our analysis shows that faulting load instructions may transiently dereference unauthorized destinations previously brought into the fill buffer by the current or a sibling logical CPU. We discuss ZombieLoad’s effectiveness in a multitude of practical attack scenarios across CPU privilege rings, OS processes, virtual machines, and SGX enclaves. We mention both short and long-term mitigation approaches and arrive at the conclusion that disabling hyperthreading is the only possible workaround to prevent this extremely powerful attack on current processors.
Daniel Moghimi is working toward a Doctorate at Worcester Polytechnic Institute (WPI).

## August 2019

Empire Hacking hosted end-of-summer presentations from a group of interns:

Intern speakers included:
* George Litvinov (Confiant) on malvertising
* Michael Rosenberg (Trail of Bits) on the MLS end-to-end encrypted group chat protocol
* Aditi Gupta (Trail of Bits) on rewriting binary cryptographic libraries
* Henry Wildermuth (Trail of Bits) on automating analysis from KRF
* Anne Ouyang (Trail of Bits) on a TLA+ specification for CBC Casper
* Alan Cao (Trail of Bits) on ensemble fuzzing with DeepState
* Sai Vegasena (Trail of Bits) on symbolically executing binaries with klee-native
* Jim Miller (Trail of Bits) on multi-party computation on machine learning
* Roy Ragsdale (Trail of Bits/Army Cyber) on measuring fuzzer performance

## June 2019

### Fuck RSA
RSA no longer sparks joy. It is an intrinsically fragile crypto system containing countless foot-guns which the average software engineer cannot be expected to avoid. Bad parameters are extremely difficult - if not impossible - to check, and its relatively poor performance encourages developers to take risky shortcuts. Even worse, padding oracle attacks remain rampant 20 years after Bleichenbacher's seminal paper. Folks, it's time to accept it - the only way to securely use RSA is to not use it at all. Ben Perez is a Security Engineer at Trail of Bits.

<iframe width="560" height="315" src="https://www.youtube.com/embed/lElHzac8DDI" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Clinical Computer Security for Victims of Intimate Partner Violence
Digital insecurity in the face of targeted, persistent attacks increasingly leaves victims in debilitating or even life-threatening situations. We propose an approach to helping victims, what we call clinical computer security, and explore it in the context of intimate partner violence (IPV). An initial field study with 44 IPV survivors showed how our new procedures and tools help victims discover account compromise, exploitable misconfigurations, and potential spyware. We further motivate the need for clinical approaches to computer security for at-risk communities. Sam Havron is a PHD student at Cornell Tech.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Thanks <a href="https://twitter.com/SamHavron?ref_src=twsrc%5Etfw">@SamHavron</a> for your talk at <a href="https://twitter.com/EmpireHacking?ref_src=twsrc%5Etfw">@EmpireHacking</a> and for helping Victims of Intimate Partner Violence with technical solutions <a href="https://t.co/N3Q3dKf9ON">pic.twitter.com/N3Q3dKf9ON</a></p>&mdash; Dennis Roellke (@dns43) <a href="https://twitter.com/dns43/status/1138637896020373505?ref_src=twsrc%5Etfw">June 12, 2019</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<iframe width="560" height="315" src="https://www.youtube.com/embed/YsFZ3OxwWN0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## April 2019

### Detect security bugs with Facebook's Infer
In this lightning talk we will demonstrate how to find security bugs through advanced linting and data flow analysis using Facebook's open source Infer static analysis tool. We will demonstrate on the osquery project and how you can statically protect against user input flowing to dangerous APIs. The talk will be very practical and focused on examples of bugs you can detect. We will also show real bugs Infer has found in osquery in the past. Infer checks for null pointer exceptions, resource leaks, annotation reachability, missing lock guards, and concurrency race conditions in Android and Java code. Infer checks for null pointer dereferences, memory leaks, coding conventions and unavailable API’s in C/C++ and iOS. Teddy Reed is a member of the Product Security team at Facebook.

### Peer reviewing the CBC Casper family of consensus protocols
Jude review the CBC Casper family of consensus protocols published by "Ethereum Research." He will describe why the definitions and proofs provided in the paper result in neither theoretically nor practical treatment of Byzantine fault-tolerance and considering liveness without correctness is a fundamentally incorrect approach. He will also discuss whether Casper provides meaningful safety guarantees for blockchains or if the approach is applicable to scaling blockchains at all. Jude Nelson, a Blockstack Engineering Partner, earned his Ph.D. in computer science at Princeton and worked as a core member of PlanetLab, which received the ACM Test of Time Award for enabling planetary scale experimentation and deployment. His research covered wide-area storage systems and CDNs. He has 10+ years of Vim usage.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Great talk at <a href="https://twitter.com/EmpireHacking?ref_src=twsrc%5Etfw">@empirehacking</a> by <a href="https://twitter.com/JudeCNelson?ref_src=twsrc%5Etfw">@JudeCNelson</a> exposing the flawed Byzantine fault tolerance of the CBC Casper protocol family suite. Proofs in distributed systems should be considering liveness and safety together for any useful result to hold. <a href="https://t.co/vFQGbrSoUA">https://t.co/vFQGbrSoUA</a></p>&mdash; Julien Vanegue (@jvanegue) <a href="https://twitter.com/jvanegue/status/1115781807461498885?ref_src=twsrc%5Etfw">April 10, 2019</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

### How Etsy mitigates account take over (ATO)
A rash of recent database breaches has flooded the web with billions of plaintext credentials. Password reuse renders these secrets especially valuable to financial fraudsters, who leverage them to access users' various online accounts, and to then abuse the payment instruments - credit cards, money transfer systems such as PayPal, and bank accounts - therein. This type of attack, called account takeover (ATO), has risen sharply in volume and sophistication since 2016. Etsy, an online platform comprised of 2M active sellers and 37M active buyers, is an enticing ATO target thanks to the prevalence of listings with high resale value, and because two-sided marketplaces are generally conducive to money laundering schemes. This talk details how Etsy's Security Engineering team has evolved its ATO detection and remediation systems over the last several years, first addressing mechanisms for defending against automated ATO campaigns, and then describing how we have productionized machine learning to successfully surface subtle, manual instances of ATO. Shayne Barr is a developer on Etsy's Security Engineering team.

## February 2019

### Who's afraid of fault injection in kernelspace?
We'll cover the basics of fault injection, along with improving the state of fault injection testing by moving away from traditional injection techniques, like LD_PRELOAD and dynamic instrumentation, and into kernelspace syscall interception. We will demo a new tool, KRF, that uses kernelspace fault injection and crash real-world applications with it. William Woodruff is a security engineer at Trail of Bits.

### Low level debugging with Pwndbg
We will discuss Pwndbg, a plugin for GDB that is useful for debugging assembly code, reverse engineering, and exploit development. Dominik Czarnota is a security engineer at Trail of Bits.

## December 2018 (Ethereum Edition)

See our full, post-event writeup including videos on the [Trail of Bits blog](https://blog.trailofbits.com/2019/01/18/empire-hacking-ethereum-edition-2/).

### Anatomy of an Unsafe Smart Contract Programming Language
This talk dissects Solidity: the most popular smart contract programming language. Various examples of its unsafe behavior are discussed, demonstrating that even an experienced, competent programmer can easily shoot themselves in the foot. These serve as a cautionary tale of how not to create a programming language and toolchain, particularly one that shall be trusted with hundreds of millions of dollars in cryptocurrency. The talk is concluded with a retrospective of how some of these issues could have been avoided, and what we can do to make smart contract development more secure moving forward. Evan Sultanik is a security engineer from Trail of Bits.

### Asset Insecurities: Evaluating Digital Asset Security Fundamentals
Spend a couple minutes learning about digital asset security ecosystem problems as faced at Coinbase scale. This will be a jaunt through insecure supply chain, the difference between a protocol white paper and the actual implementation, and a couple other things that’ll bite you if you’re not paying attention. Shamiq herds cryptokitties, security engineers and developers at Coinbase as Head of Application Security. In his spare time, he loves to eat cheese and chocolate.

### Designing the Gemini dollar: a regulated, upgradeable, transparent stablecoin
A regulated stablecoin requires important design decisions. How can you make your contracts upgradeable when many rely on them? How can you manage keys that protect the underlying assets? And how can you do this all completely transparently? In this talk, we explain the design decisions that went into the Gemini dollar, and compare and contrast with other possible implementations. Brandon Arvanaghi is a security engineer at Gemini Trust.

### Property testing with Echidna and Manticore for secure smart contracts
Property-based testing is an incredibly simple and powerful tool for bug discovery, but despite its efficacy, it's almost unheard of in the smart contract development community. This talk will introduce the concept of property-based testing, discuss strategies for picking good properties and testing them thoroughly, then go into how to apply these ideas to smart contracts specifically. We'll discuss the use of both Manticore and Echidna for testing, and look at real bugs these tools can find in production code. JP Smith is a security engineer from Trail of Bits.

### Contract upgrade risks and remediations
A popular trend in smart contract design is to promote the development of upgradable contracts. Existing techniques to upgrade contracts have flaws, increase the complexity of the contract significantly, and ultimately introduce bugs. We will detail our analysis of existing smart contract upgrade strategies, describe the weaknesses we have observed in practice, and provide recommendations for contracts that require upgrades. Josselin Feist is a security engineer at Trail of Bits.

### Failures in On-Chain Privacy
Many, including Satoshi, believed cryptocurrencies provided privacy for payments. In reality, cryptocurrency is Twitter for your bank account. Worse, the current set of decoy transaction–based approaches commonly believed to provide privacy—including coinjoin and cryptonote/Monero—provide fundamentally flawed privacy protections. Where did we go wrong? This talk covers how to critically evaluate the privacy provided by any proposed protocol for payment privacy. Through a series of thought experiments, it outlines three plausible attacks on existing decoy-based schemes. These issues show the unintuitive nature of privacy protections, as well as the need to both evaluate protocols in the context of real world threats, and use approaches with formal and peer reviewed privacy guarantees such as Zcash. Ian Miers is a post-doctoral associate at Cornell Tech.

### Secure Micropayment Protocols
Sending cryptocurrency micropayment transactions that must be confirmed on a blockchain is impractical today due to transaction fees that can exceed the value being sent. Instead, we can use micropayment protocols that only rely on the blockchain for settlement and disputes to minimize on-chain fees. In this talk, we will describe and compare different approaches to constructing secure micropayment protocols on top of Ethereum including probabilistic micropayments and payment channels. Furthermore, we will highlight the difficulties and considerations in implementing these types of protocols given the increased reliance on correct and timely client behavior to prevent the loss of funds. Yondon Fu is a software engineer and researcher at Livepeer.

### How To Build an Enterprise-Grade Mainnet Ethereum Client
The byzantine environment of the Ethereum mainnet is fraught with challenges for aspiring hackers seeking to publish a compatible client. This talk highlights the trials and tribulations of implementing a client capable of handily dispatching the adversarial events and actors of the sprawling P2P ecosystem that comprises the Ethereum blockchain’s world-wide compute network. The uniquely modular nature of the Pantheon codebase and it’s suitability for enterprise application will be treated in detail. The session will conclude with a brief sketch of the road ahead for Pantheon with an eye towards the Ethereum Enterprise Alliance and the forthcoming updates that comprise the broad strokes of the Ethereum 2.0 specification. S. Matthew English is a PegaSys protocol engineer and Pantheon core dev.

### Simple is hard: Making your awesome security thing usable
If the security assumptions of blockchain systems fail even a little, they provide very little value. They also have a high barrier to entry and are hard to use. But wait, people already don’t use security tools — how isn’t this the worst of all possible worlds? We’ll talk about some precedents from infosec history and how we might be able to avoid “Your elections are fine as long as you use The New PGP on The Blockchain” in favor of helping people build cool things that really do solve longstanding problems in novel ways. Patrick Nielsen and Amber Baldet are founders of Clovyr.

### Like it or not, blockchain voting is here to stay
I’m going to talk about how blockchain voting apps received serious pushback from academics who study voting security, but that West Virginia used the Voatz app for some counties during primaries, used it in almost half the state in the midterm election, and is pleased with how it went. Voatz is already in talks with other states and is hoping for up to 20 states to use it by 2020. And several other countries are testing different blockchain voting apps. Kevin Collier is the cybersecurity correspondent at BuzzFeed News, where he covers cyberwar, hackers, election security, disinformation efforts, tech companies, and hacking laws. Prior to BuzzFeed, Kevin covered cybersecurity at Vocativ and the Daily Dot, and has written for Politico, Gizmodo, The Daily Beast, and NY Mag. A native of West Virginia, he lives in Brooklyn.

## October 2018

### An extremely brief overview of post-quantum cryptography
Currently, one of the most exciting and talked-about topics in cryptography is the move to post-quantum cryptosystems. This talk will cover what constitutes being "post-quantum," the domains of cryptography in which that's relevant, and a few of the current most exciting ideas in the space. JP Smith is a cryptography engineer at Trail of Bits.

### A Software-testing Case Study on Ethereum Smart Contracts
We’ll review a function called ‘batchTransfer’ in one of the Gemini dollar smart contracts and use it as a case study for software testing in the setting of Ethereum smart contracts. Specifically, we’ll review two versions of this function, the second of which rectifies unintended edge-case behavior in the first. The main focus of this talk will be on the use of two tools, Manticore and Echidna, and how they were used to specify correctness properties about the ‘batchTransfer’ function. We’ll conclude with some remarks on the relative strengths of these tools, as well as their advantages over example-based unit testing. Daniel James is a security engineer at Gemini Trust.

## August 2018

Empire Hacking hosted end-of-summer presentations from a group of interns from around NYC.

Intern speakers included:
* James Wang, Trail of Bits
* Aditi Gupta, Trail of Bits
* Guillaume Fournier, DataDog
* Dennis Roellke, Siemens
* Nicholas O'Brien, Facebook
* Momopranto Amin, Facebook
* Sohum Sontakke, Etsy

## June 2018

### Server-side Spreadsheet Injections
CSV injection and client-side Excel DDE attacks are well-known in the security community. This talk explores and demonstrates new ways spreadsheet formulas can be used to exploit servers and cloud platforms supported by spreadsheet technology. By injecting formulas into server-side services and without client interaction, we will demonstrate how we have stolen sensitive data, inserted backdoors, and obtained remote code execution during client engagements. Jake Miller is a security consultant at Bishop Fox.

### Three Super Features That Could Transform Osquery
Not all features are created equal. Most features improve functionality. However, some features expand a tool’s ability so completely that the baseline product becomes something entirely new. We call these features Super Features. In this talk, we’ll review a feature wishlist gathered from interviews with 5 Silicon Valley tech teams who use osquery. From these, we’ll identify the Super Features - features that, if built, would fundamentally change the value proposition of osquery for the better. Then, we’ll discuss how Trail of Bits plans to make these osquery Super Features a reality. Lauren Pearl is the head of strategy and operations at Trail of Bits.

## April 2018

### Attacking Browser-Based Ethereum Wallets
Browser-based Ethereum wallets are currently one of the only ways to interact with dApps in the Ethereum network. While they are innovative in nature, many of these wallets expose their users to a wide attack surface. Further, they provide information to sites you probably don’t want them knowing. In this talk, I go over the attack surface of all these wallet softwares, how they can be exploited, and how the risks can be mitigated. Brandon Arvanaghi is a security engineer at Gemini.

### Blackhat Ethereum
In the blockchain, there are no secrets. Every transaction is logged and everyone has a copy of all of the code. Nearly all of this code can only be analyzed through reverse engineering. Over the past year, we've seen enterprising hackers use flaws in smart contracts to whisk away millions. This was made possible thanks to Ethereum, the technology that powers cryptocats, and Solidity, a high level language that describes Ethereum's Turing complete smart contracts. This talk will introduce smart contract security, present common vulnerability classes, and demonstrate how to reverse engineer EVM code to identify these vulnerabilities. The talk will also present tools to support vulnerability discovery in EVM code and Solidity. Ryan Stortz and Jay Little are security engineers at Trail of Bits.

## February 2018

### Privacy on the blockchain: insights from 3 leading projects
Projects like Enigma and Keep are developing solutions to keep sensitive data private but useful on the blockchain. Doing so would be a leap forward for dApps and a provide a stronger bridge to enterprise users. What are the key problems and which of these solutions is likely to succeed?
Ana De Sousa is a consultant and analyst focused on commercial applications of blockchain technology. Previously, she led analytics teams at LinkedIn and AT Kearney. She's delighted to finally put her BA in Economics to use.

### Containers aka crazy user space fun
Like the movie Plan 9 from outer space, this talk will cover containers from user space. What are they? Where did they come from? How much koolaid is involved in adopting them into your life... Come for the jokes, stay for the interesting technical details.
Jess Frazelle works at Microsoft on open source, containers, and Linux. She has been a maintainer of Docker, contributor to RunC, Kubernetes and Golang as well as other projects. She loves all things involving Linux namespaces and cgroups and is probably most well known for running desktop applications in containers and her work on making containers secure.

## December 2017

### Past, Present, and Future of Ethereum and its Security
John Maurelian of Consensys Diligence will discuss his highlights of the latest developments in Ethereum security. Many new projects, papers, and tools were released at Devcon3 that demand attention from those concerned with Ethereum security.

### Building the Quorum Blockchain
Amber Baldet and Brian Schroeder of the Enterprise Ethereum Alliance will discuss blockchain threat modeling, confidential transactions, and zero-knowledge proofs. All the tech that makes the Quorum permissioned blockchain possible!

### Learn Ethereum security through Capture the Flag
Sophia D'Antoine of Trail of Bits will discuss recent CTF competitions that have featured Solidity and Ethereum challenges, and the tools required to exploit them.

### Automatic Bug Finding for the Blockchain
Mark Mossberg of Trail of Bits will discuss practical symbolic execution of EVM bytecode with Manticore. Mark recently completed a smart contract audit where Manticore was used to find subtle numerical issues of high severity.

### Lightning talk: Addressing infosec needs with blockchain technology
Paul Makowski will discuss PolySwarm, an upcoming cybersecurity-focused Ethereum token, and how it aligns incentives and addresses deficiencies in the threat intelligence industry.

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

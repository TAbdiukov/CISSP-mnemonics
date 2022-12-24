# CISSP-YA-mnemonics

Yet another set of CISSP mnemonics

# Domain 1

## Must-know

ALE = ARO x SLE  
ALE CAUSES AROSLE  

(up my) SLEAV-EF  
SLE = AV x EF  

## Qualitative & quatitative risk analysis

(no memory device here, more of an explanation)

* Qualitative - based on guestimates, inference and basic algoriths e.g. FAIR method (probability / impact) or ALE CAUSES AROSLE

* Quantitative - **better**, based on experience and statistics

* Combination - balanced

## Laws and regulations

* SOX (Sarbanes Oxley, 2002) - [say in British accent] ENRON really SOX. It's transaction flow really SOX.

* Gramm-Leach-Bliley Act (GLBA) - banks, lenders, insurance. Think about some **fat banker** Gramm (or Graham)
![Banker](https://upload.wikimedia.org/wikipedia/commons/thumb/a/a3/The_Banker%2C_by_Isidor_Kaufmann.jpg/201px-The_Banker%2C_by_Isidor_Kaufmann.jpg)

* COPPA - Protects minors 13 or younger online. If you are an **online pedo**, then you **cop it**

* FERPA - Protects Student data for over 18. Think about Phineas and **FerP**. They have to grow up eventually and go to college. It would be really unfortunate for Phineas and **FerP** fans if **FerP**'s student card is leaked to public!

![Ferp grown up imagery](https://i.imgur.com/9EmTji7m.jpg)

However, student ID leak [won't trigger data breach laws](https://www.theaustralian.com.au/the-oz/news/student-grades-and-ids-have-been-stolen-from-an-elite-australian-uni/news-story/1ddc0401bb2d91e58d430ef8d6939edf)

* **GISMA - Superseded by FISMA** in 2000

* FISMA - **U.S. Government information security** is under **prisma**. [NIST SP 800-53 is used for FISMA]

* PCI DSS - Credit Card Security - Visa, MasterCard and American Express. What else is a card other than a credit card? - Your PCI card.

* Digital Millenium **Copyright** Act (DMCA) - **Copyright**. Who hadn't heard of the DMCA strikes on Youtube? 

### U.S. Privacy

* 4th Amendment in American Constitution grants right to privacy

* Computer Fraud and Abuse Act - CFAA 1986 - **First** major legistlation to fight cybercrime. Think: **CFAA - F for First**.

#### EPCA, CALEA, USA PATRIOT ACT

* Electronic Communications Privacy Act - EPCA 1986 - Makes it illegal to invade electronic privacy of an individual.
* Communication Assurance for Law Enforcement Act - CALEA 1994 - Amends EPCA to make wiretaps possible for law enforcement, regardless of technology used.
* USA PATRIOT ACT of **2001** - Broadened wiretapping authorizations, no thanks to 9/11 in 2001.

Think of EPCA and CALEA - as a seed and a flower. Yes, calea is a plant, but let's make CALEA a CAULIPOWER with sour taste. EPCA grows into CALEA flower. Then terrorists come, and the garden of CALEA has to be destroyed. Like the privacy had to be destroyed.

### U.S. Import and Export

* Export Administration Regulation (EAR) - restricting export of **civilian items that may have military applications**, such as **EARphones**.
* International Traffic in Arms Regulations (ITAR) - restricting export of **war items**. Think "**ITAR is war**". Russia has a century-old **pro-war** newsagency of **[ITAR-TASS](https://www.britannica.com/topic/ITAR-TASS)**, and when Russia started its **full-scale war**, U.S. already had Russia added to [ITAR list](https://www.federalregister.gov/documents/2021/03/18/2021-05530/international-traffic-in-arms-regulations-addition-of-russia).

### Personal information

* P**I**I - Personal **ID** information 
* P**H**I - Personal **Health** Information
* P**C**I - **Credit card**. **PCI** DSS applies


### U.S. Healthcare

* **H**IPAA - **Health privacy and security** regulations in case you get **HIPAAtitis**
* **HITECH** - **Hospitals security** go hi-tech!

### EU

* GDPR - EU Privacy Laws. No known mnemonic

## Security and Risk in the U.S.

* US**PT**O - **P**atents and **T**rademarks - (US Parent & Trademark Office)
* LO**C** - **C**opyright - (Library of Congress)
* **Bank** - **bank**ing breach - (per PCI DSS)

* U.S. **C**ode(x) - **C**riminal and **C**ivil Law
* Code of **Federal** Regulations - Administrative Law on Federal scale

## Risk 

![Roku](https://image.roku.com/developer_channels/prod/81b0180e7b151201a10d7006b048ccbc0ea5695d8fd20d78462d2a13a99f3485.png)

Mnemonic: Risk T.V.

Risk = Threat x Vulnerability


## Risk - RMF - NIST SP 800-37

* [Useful nist.gov illustration](https://csrc.nist.gov/projects/risk-management/about-rmf)

### Steps

1. Prepare.
2. Categorize (systems)
3. Select (controls) [for systems]
4. Implement (controls) [+documentation]
5. Assess (controls) [take a step back]
6. Authorize (controls) [stamp of approval]
7. Monitor.

### Mnemonic device 1

PC SIA AM (PC of SIA in ArMenia)

[For SIA to run a rogue PC in Armenia is pretty RISKy]

![https://img.youtube.com/vi/JKbVmjan3bQ/mqdefault.jpg](https://img.youtube.com/vi/JKbVmjan3bQ/mqdefault.jpg)

### Mnemonic device 2

PCS IAAM (PC's I aam)

[Being non-human is RISKy]

## BCP and DRP

DRP is a subset of BCP

* BCP - Business
* DRP - Technical

### NIST SP 800-34

DC I DD PP

[NSFL but rememberable memorization trick](https://pastebin.com/raw/fnFEP8cT), oh boy will you need DRP and thus BCP after this

* Develop (policy)
* Conduct BIA (Business Impact Analysis)
* Identify (preventative controls)
* Develop DRP strategies
* Develop IT contingency (plan)
* Plan Training
* Plan maintenance

#### BIA process

(No known memory device, just needs to be understood)

1) Project Planning and Development
2) Data collection
3) Criticalicality Assessment
4) Vulnerability assessment

## Recovery acronyms

* RPO - Recovery **Point** Objective - time period: From last (known good) scheduled backup to disaster (from past to present). **Point** - think about last known good configuration for Windows,

![XP](https://social.technet.microsoft.com/Forums/getfile/931978)

* RTO - Recovery **Time** Objective - time period: from disaster to recovery, if all goes well (from present to the future).

* WRT - How much **work** for **technical** staff to reconfigure everything after recovery.

* MTD - Maximum tolerable downtime for **business**. For CISSP: MTD = RTO + WRT. In reality, YMMV.



# Domain 2

## Data roles

* Data **O**wner - (responsible) **O**verall 
* Data **P**rocessor - **P**rocesses **P**assed-on (database)

* Data **C**ustodian - (responsible for) **C**omputer (with database)
* Data **S**teward - (responsible for) **S**yndicate data *everyday* ["Syndicate" as in "Business", so responsible for business data.]

* **A**dministrators - **A**ssign permissions to **A**ccounts

## Data remanence

CISSPrep has a great mnemonic,

To memorize this, repeat the phrase “Cow, Pig, Sow,” or “CP SOW.”  Repeat it again and think of a farm you visited or one that you saw in a movie.  Now repeat the following mnemonic:

* **C**learing Can (be recovered)

* **P**urging is **P**ermanent

* **S**anitizing is the **S**ame (as purging)

* **O**verwriting with **O**h's.

* **W**iping is **W**riting (overwriting, that is)

Notice how the letters match to help you remember.  It seems silly, yes, but this is the key.  

So here’s the phrase to keep repeating, once again:

Cow Pig Sow; CPSOW, **Clearing Can, Purging is Permanent, Sanitizing Same, Overwriting Oh’s, Wiping is Writing.**  Repeat this over and over, and consider copying it onto a memorization sheet.




## Scoping, tailoring and supplementation

* Scoping - removing security controls that don't apply. 
* Tailoring - tweaking little details of applied security controls to better suit your organisation.
* Supplementation - Specify used product names. For example, replace "OS" with "Windows".

There are two mnemonic devices.

### First

Think about a digital telescope pointing at the stars. 

* When you **Scope**, you zoom-in, and you **no longer see stars you are not interested in**
* When you **Tailor**, you **tweak your zoom to see stars clearer**  
* When you **Supplement**, you take a photo of the galaxy, print it out, and then in the photo, **circle and name each star with a pen**.

### Second

* **Scoping** is **Subtracting** (controls)
* **Tailoring** is **Tweaking** (controls)
* **Supplementing** is **Specifying** (names)

# Domain 3

## Must-know

### Security rings,

(Zero) KODU - Kernel, OS, Drivers, Userspace

### Information flow security models

[Bell-LaPadula, Biba, Brewer-Nash (Chinese Wall), Clack-Wilson](https://github.com/TheRealBenForce/cissp-mnemonics#domain-3-security-engineering)

#### Properties

[Information flow security models' properties](https://github.com/DerreckM/CISSP-Mnemonics#confidentiality-and-integrity-models)

## Firefighting systems

* **D**ry pipe - **D**ry (steam)
* **W**et pipe - **W**ater
* **Deluge** - **Deluxe** (volume)
* Pre-action - **pre**load once fire, **action** once confirmed

## Fire Extinguishers

Type | Application
---- | ----
A | Ash, almanac
B | Bubble, BOil Oil
C | Circuits, CRT
D | Dent, Dural, Duraluminium
K | Kitchen

## Card types

* Magnetic - low security
* Proximity - signal can be stolen
* RFID - Distance
* Microchip / SmartCard - Secure

## Compliance

* **Ass**urance - **Ass**ert (security of product)
* **C**ertification - **C**ompliance according to **c**ompany's **c**ompliance security officer. Certification is towards assurance

* **Ver**ification - Third-party obser**ver**'s report
* **V**alidate - (just a sanity check, need to think of a mnemonic) 

* **Acc**reditation - **Ac**e's **C**ompliance (senior manager)

* **Accept**ance - **Accept**

 
## IPSec

So to remember IPSec, one needs to remember the following memory device: "IPSec is 2". What is 2?

* 2 of IPSec: **IP** + **Sec**

* 2 of Encapsulating Security Payload (ESP): **Confidentality** + **Integrity**
* 2 of **Authentication** header (AH): "**Authentication**" + **Integrity**

## System Modes

From least secure to most secure:

Multilevel > Compartmented > System-High > Dedicated  
M > C > S > D 

Make up a story, e.g. "MC gives you a porn SD card."

![128gb](https://i.ytimg.com/vi/BrcBKpE9aQg/mqdefault.jpg)


Progression of requirements for ALL information (therefore, next entry would apply for SOME information),

NDA > Clearance > Formal Approval > Need-to-know

N>C>F>N -> NoiCy FaN [in the background]

Example: Compartmented - NDA for ALL info, Clearance for ALL information, Formal approval for SOME information, Need-to-know for some information.
  
## Access Control Models

* **D**iscretionary - **D**ata owner **d**iscerns **d**irectly. [thus ACLs are in use]

* Non-discretionary - everything more streamlined:
	* **M**andatory (MAC) - **M**ilitary, and therefore strict and not scalable. Enforced by the OS. Clearances, formal approvals and need-to-know apply.

	All other options are easier to remember,
	* Attribute (ABAC) / Policy (PBAC) - attribute/policy - high-level rules, flexible use of attributes, location and environment.
	* Role-based (RBAC) - role
	* Rule-based (RuBAC) - rule - dumb rules for robots. example: firewalls
		* Risk-based (~~RiBAC~~ RBA, subtype of RuBAC) - risk. For example, IP from China increases risk score.
	
### Related concepts

* ACLs - Access Control **Lists**. Blacklists or whitelists. Focus on Objects. Used in DAC.
* Capability table - Used for subjects in DAC. `sudoers` file is an example of Capability table.
* AC Matrix - 2D matrix with subjects and objects in DAC/MAC.
* **L**attice model - matrix of **L**abels on objects and subjects in MAC

	
## TSSEC, ITSEC, Common Criteria

### TSSEC
* TSSEC - "Orange book" - U.S. Standard 

![Orange book](https://upload.wikimedia.org/wikipedia/commons/thumb/4/4f/Orange-book-small.PNG/180px-Orange-book-small.PNG)

Recall [Star-Spangled Banner](https://www.youtube.com/watch?v=FqxJ_iuBPCs),

> O say can you see  
> By the **dawn's early light,**  
> What so proudly we hailed  
> **At the twilights last gleaming?**  

What colour comes to mind?

![Twilight USA](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c6/Twilight%27s_last_gleaming_%28Ipernity-47381384%29.jpg/320px-Twilight%27s_last_gleaming_%28Ipernity-47381384%29.jpg)

### ITSEC

ITSEC - EU Standard

*i***T-Systems** are European

### Common Criteria

Common Criteria - CC - Are superseding globally

## Common criteria - EAL

Start-from 1 - 3-2-1

FSM - SS - F

Function > Structure > Method >> Semiformal > Semiformal-verified >> Formal

# Domain 4

![Protocols](https://cybercoastal.com/wp-content/uploads/2021/08/Screenshot-73.png)

## TCP/IP Model

![Difference](https://www.networkstraining.com/wp-content/uploads/2022/09/osi-tcpip.png)

An amazing mnemonic from CISSPrep,

The TCP/IP model on the right side can be memorized by saying/writing “**N2, A3**,” with “IT” in the middle, or “**NitA**”, which could be someone’s name.  

**NOTE**: The mnemonic is to apply from bottom to the top.

## Authentication protocols

*(typically)*

* Kerberos - for Microsoft Windows
* RADIUS - for VPN
* TACACS+ - for Cisco

Mnemonic device - made up a little story: You send documents from Microsoft Windows via VPN to a mainframe serviced by Cisco. The corresponding authentication protocols would go in the alphabetical order.

### Kerberos

![Cerberus](https://static.wikia.nocookie.net/ageofempires/images/a/a5/TitanGreekIcon.png)

Heads/Steps: Authentication (KDC), Authorization (TGS gives TGT Ticket), Acceptance

KATANA: KDC Authenticates, TGS Authorizes, nginx accepts.
(You can use KATANA to chop off Kerberos's heads)

## SSL vs TLS

For CISSP: SSL is outdated and TLS is to be used.

## Virtual networking

VX**LAN** for **LAN**, SD**WAN** for **WAN**

## VoIP and VPN

For CISSP: VoIP doesn't mix with VPN

## Routing protocols

* distance-vector - Shortest path
* Link state - Best bandwidth link

## NAC systems

Note: They use **Risk** BAC, as they evaluate **risk**

* Pre-admit - Checks happen BEFORE admission
* Postadmission - Checks happen AFTER admission
* Client-based - Stateful
* Clientless - Stateless

## *Casts

Mnemonic device: They go in reserve alphabetical order

* Unicast - One
* Multicast - Many specific
* Broadcast - All

## Dial-Up

[Dial-Up refresher](https://www.dialupsound.com/)

* PPP (point-to-point protocol) - IP over telephone

### Authentication protocols (AP's)

* **P**-**AP** (PAP), - Insecure, **P** for **P**athetic
* **CH**-**AP** (CHAP) - Secure, uses **CH**ecksums (hash functions)
* **MS**-CHAP - Microsoft-improved CHAP. Even more secure, uses **CH**ecksums (hash functions)

## *EAP

* EAP - Original protocol that started its family. Outdated
* LEAP - Lightweight, Cisco proprietary, no longer secure
* PEAP - Protected EAP. For CISSP purposes, "good enough". Uses TLS.
* MS-PEAP - Microsoft's improvement on PEAP, even better than PEAP
* EAP-TLS - Secure, but difficult to implement due to additional prerequisites

## Bluetooth

* Bluejack - Jack sends annoying messages
* Bluesnarf - snatch data
* Bluebugging - bug to gain remote access

Bluetooth "authZ" is 4-digits.

## internet storage

* FCoE - Fiber and maybe Ethernet
* iSCSI - IP/Ethernet 

## Private IP ranges

* Class A: 10.0.0.0 – 10.255.255.255
* Class B: 172.16.0.0 – 172.31.255.255
* Class C: 192.168.0.0 – 192.168.255.255

## Private IP ranges and subnet masks

Easy trick: class letter defines the number of 255's from left to right. For example, class B (2) would have 255.255.0.0

## Fraggle, Smurf

* Fraggle - CHARGEN
* Smurf - ICMP

## FTP, SSH, Telnet

Memory device - They are in alphabetic order,

* 20-21 - FTP
* 22 - SSH
* 23 - Telnet

Fragile CHARGE, Smurf Is CIMP

![simp](https://static.wikia.nocookie.net/smurfs/images/2/29/Enamoredsmurf.gif)

## Port status

Mnemonic device: This information is VERY obvious, so what do I say? Of Course! Or OFC:

* Open - Worst
* Filtered - OK
* Closed - Best

# Domain 5

## Must-know

Retinal = anal

## Authentication problems

![meme](https://datavizblog.files.wordpress.com/2014/05/type-i-and-type-ii-errors-simplified.jpg)

* FRR - Type 1 Error
* FAR - Type 2 Error
* CER - Intersection between FAR and FRR. Optimal configuration.

Mnemonic device: FRR FAR, CER (meaning [Freier](https://en.wiktionary.org/wiki/Freier#Noun)'s far, sire)

## More about AAA protocols

* RADI**U**S - **U**DP, can extraordinarily support TLS over TCP, only encrypts passwords. Like it is for VPNs, not a single sign-on
* **T**ACACS+ - **T**CP
* Kerberos - symmetric AES encryption everywhere, but unique system.

### *Open* / Third-party logon

Think: Google, Github, Microsoft logon.

* Open**ID** - **Id**entity -> Authentication
* OAuth - (stands for) Open Authorization

**Note**: In real life, these protocols are used vis-a-vis.

### XML-based-languages

* SAML - AuthN and AuthZ, open source, good for ADFS.
* SPML - Service provisioning
* XACML - Access control
* SOAP - messaging over network

## PRivileges

* **P**ermissions - for **P**C (for example, execute permissions on files in Linux)
* **R**ights - for **R**eal-life (for example, right to bear arms)

* **PR**ivileges = **P**ermissions + **R**ights

# Domain 6

## SOC

### Related meme

[![Money](https://i.ytimg.com/vi/KdftbYqA_VQ/mqdefault.jpg)](https://www.youtube.com/watch?v=KdftbYqA_VQ)

**Point is**: Money, then assurance

### Mnemonic

Adapted from CISSPrep,

* SOC 1 - **F**inance **F**irst
* SOC 2 - **T**rust Second/**T**rust is **T**wo
* SOC 3 - SOC 2 lite for public eyes.

## SOC Type

* Type 1 - One point in time
* Type 2 - Two points - timeline

## Testing

### Target

* Static - Code
* Dynamic - Runtime

### Labour

* Unit - Automated 
* Manual - Manual

### Coverage

* Use cases - How can it be used
* Misuse cases - How can it be misused

### Devops

*Wikipedia is wrong about this one (according to ISC2 )*

* Regression testing - Is there regression after the last change?
* Non-regression testing - Did last change have its supposed improvement effect.

### Network access

* Authenticated - intranet
* Unauthenticated - externally facing targets only

## Testing coverages

* Test coverage - potential uses
* Code coverage - % of code executed in tests
	* Function - **functions** work and return results
	* Statement - **line** of code
	* Condition - code executed under every **input**
	* Branch - every **IF-THEN-ELSE** condition can be executed.

# Domain 7

## Must-know

DRMRRRL

## Information lifecycle

CCS UAD

Before use: Create, Categorize, Store
Afterwards: Use, Archive, Destroy

## Evidence

### By format

* Real - Real physical Objects
* Documentary - Docs
* Testimonial - Witness

### By reliability

* Primary - Originals
* Secondary - Certified copies

### By quality

* Hearsay - "he said she said" - bad

* Direct - Very good
* Corroborative - Supportive

* Conclusive - so good, that we can adjourn court after it.


## Backups

* Full - full
* Differential - diff (delta) from full
* Incremental - increments from last increment, thus the total number of increments will be high

## Security encounters

* Security Event - Anything worthwhile logging for security. For example: OS reboot, browser crash
* Security Incident - Whatever breaches security policy and threatens organisation
* Security Intrusion/Breach - Security defenses breached

## Terms

* UCITA - Law governing business transactions
* UEBA = Bossware. Whichever boss uses UEBA is an [ueban](https://www.urbandictionary.com/define.php?term=ueban)

### Media

HSM - Move data from SSD to HDD or LTO to increase MTBF

## MTT

* MTTF - Failure
* MTTR - Repair. Similar to WRT
* MTBF - Between failures. MTBF = MTTF + MTTR

## NAS vs SAN

Trick is: to read from right to left,

* NAS - Storage in network
* SAN - Network of storages


## RAID

### RAID operations

* Mirroring - Redundancy
* Striping - Speed

Remember this array,

0 | 1
---- | -----
M | S

MS - in alphabetical order, also means "Microsoft"

### Basic

* RAID 0 - **M**irroring - 2x redundancy
* RAID 1 - **S**triping - 2x speed

### Speed over reliability

* RAID 2 - Byte Striping for speed
* RAID 3 - Block Striping for speed. Block is bigger than byte, therefore RAID 3 > RAID 2.

### Error-corrective

* RAID 5 - Data and parity striped
* RAID 6 - Same as RAID 5, but configuration is safer with little overhead over RAID 5

### Nested

![raid-100](https://hardwaresfera.com/wp-content/uploads/2021/02/raid-100.jpg)

*RAID 100*

The trick is to read nested RAID from bottom to the top. First digit from the **left** defines the drive level,

* RAID 01 - (At drive level) **0** Mirroring, (At drive-set level) **1** Striping

* RAID 10 - (At drive level) **1** Striping, (At drive-set level) **0** Mirroring

Let's try one more for fun,

* RAID 100 - (At drive level) **1** Striping, (At drive-set level) **0** Mirroring, (At set of drive-sets level) **0** Mirroring


# Domain 8

## SDLC

CISSPrep has a great mnemonic,

[![CISSPrep](https://i.ytimg.com/vi/i7NYS5Lw3UA/mqdefault.jpg)](https://www.youtube.com/watch?v=i7NYS5Lw3UA)

Please Fry Some Dead Animals To Catch The Right Man

Prep: PFS  
Dev: DA  
Post-dev: TCT  
EOL: RM

## Software Assurance During Acquisition Phases

CISSPrep has an OK mnemonic,

[![CISSPrep](https://i.ytimg.com/vi/6RoUCNc6TP4/mqdefault.jpg)](https://www.youtube.com/watch?v=6RoUCNc6TP4)



# Domain 9 (meta-domain)

![World 9-1](https://mario.wiki.gallery/images/7/7d/SMB_NES_World_9-1_Title_Card.png)

## Regarding sources

No source is perfect, including this one. Everyone makes mistakes, and I witnessed several contradicting opinions online about some hot topics (especially about Access Control Models, due dilligence vs due care, DR). The *trick* is to consult multiple sources.

For CISSP, the right way is (ISC)2 way (and to give credit, they are *at least* almost always right). 

I recommend

### №1

* Official (ISC)2 CISSP publications

### Other mnemonic repositories

* [DerreckM/CISSP-Mnemonics](https://github.com/DerreckM/CISSP-Mnemonics)
* [TheRealBenForce/cissp-mnemonics](https://github.com/TheRealBenForce/cissp-mnemonics)
## (ISC)² Code Of Ethics

### Code

* Protect society, the common good, necessary public trust and confidence, and the infrastructure.
* Act honorably, honestly, justly, responsibly, and legally.
* Provide diligent and competent service to principals.
* Advance and protect the profession.

### Memorization

1) Protect (commonwealth)
2) Act (well)
3) Provide (service)
4) Advance (profession)

### Shortcuts

P-A-P-A

The descriptions get shorter every time

### A little comic

Story of a "PAPA" man following Code

![Protect](https://cdn4.iconfinder.com/data/icons/business-businessman-employee-workers/289/employee-life-style-004-128.png)
![Act](https://cdn0.iconfinder.com/data/icons/positive-character-traits-alphabet-h/271/positive-h003-128.png)
![Provide](https://cdn1.iconfinder.com/data/icons/actions-alphabet-i-set-3-of-10/231/actions-I-3-3-128.png)
![Advance](https://cdn4.iconfinder.com/data/icons/positive-character-traits-alphabet-c-part-2/325/positive-Cset2003-128.png)

(icons from Iconfinder, used for educational purposes)

## You got this.

[Why you will pass the CISSP](https://www.youtube.com/watch?v=v2Y6Zog8h2A)

[![CISSPrep](https://i.ytimg.com/vi/v2Y6Zog8h2A/mqdefault.jpg)](https://www.youtube.com/watch?v=v2Y6Zog8h2A)

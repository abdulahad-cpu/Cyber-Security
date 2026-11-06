# 1. LINUX — FUNDAMENTALS

# 1. 🐧 Introduction to Linux

## 📖 What is Linux?

Linux হলো একটি Open-source, Unix-like Operating System-এর Kernel। এটি কম্পিউটারের Hardware এবং Software-এর মধ্যে যোগাযোগ ও resource management-এর কাজ করে।

সহজভাবে বললে, আমরা যখন কোনো Application চালাই, তখন Linux Kernel সেই Application-কে CPU, RAM, Storage এবং অন্যান্য Hardware ব্যবহার করতে সাহায্য করে।

**একটি গুরুত্বপূর্ণ বিষয়:**

Linux বলতে সাধারণত আমরা সম্পূর্ণ Operating System বুঝি। কিন্তু প্রযুক্তিগতভাবে Linux হলো Kernel। Kernel-এর সঙ্গে বিভিন্ন System Utilities, Libraries, Desktop Environment এবং অন্যান্য Software যুক্ত হয়ে একটি সম্পূর্ণ Linux Operating System তৈরি হয়।

## 🕰️ History of Linux (Brief History)

### 🖥️ Unix (1969)

- ১৯৬৯ সালে AT&T Bell Labs-এ Ken Thompson, Dennis Ritchie এবং তাঁদের সহকর্মীরা Unix তৈরি করেন।
- Unix ছিল একটি Multiuser এবং Multitasking Operating System।
- Unix-এর Design পরবর্তীতে অনেক Operating System-কে প্রভাবিত করে।

### 🛠️ GNU Project (1983)

- ১৯৮৩ সালে Richard Stallman GNU Project শুরু করেন।
- এর উদ্দেশ্য ছিল একটি সম্পূর্ণ Free এবং Open-source Unix-like Operating System তৈরি করা।
- GNU Project অনেক গুরুত্বপূর্ণ Software তৈরি করে, যেমন GCC, Bash এবং GNU Core Utilities।
- তবে GNU Project-এর নিজস্ব Kernel সম্পূর্ণ হতে সময় লাগছিল।

### 🐧 Linux Kernel (1991)

- ১৯৯১ সালে Linus Torvalds Linux Kernel তৈরি শুরু করেন।
- তিনি তখন University of Helsinki-এর একজন ছাত্র ছিলেন।
- প্রথমদিকে এটি ছিল একটি ব্যক্তিগত Project।
- পরবর্তীতে Internet-এর মাধ্যমে অন্য Developers-রা এতে অবদান রাখতে শুরু করেন।
- Linux Kernel Open-source হওয়ার কারণে পৃথিবীর বিভিন্ন Developer এটি উন্নত করতে থাকেন।

### 🔗 GNU/Linux

GNU Project-এর Software এবং Linux Kernel একসঙ্গে ব্যবহার করে একটি সম্পূর্ণ Operating System তৈরি করা সম্ভব হয়।

এ কারণেই প্রযুক্তিগতভাবে অনেক সময় একে GNU/Linux বলা হয়।

**বর্তমানে Linux Server, Supercomputer, Android, Embedded System এবং Cybersecurity-এর বিভিন্ন ক্ষেত্রে ব্যবহৃত হচ্ছে।**

## ⭐ Important Features of Linux

### 🔓 1. Open Source

Linux-এর Source Code সবার জন্য উন্মুক্ত। License-এর শর্ত মেনে যে কেউ এটি দেখতে, পরিবর্তন করতে এবং বিতরণ করতে পারে।

### 👥 2. Multiuser

একই System-এ একাধিক User Account থাকতে পারে। প্রত্যেক User-এর আলাদা File এবং Permission থাকতে পারে।

### ⚙️ 3. Multitasking

একই সময়ে একাধিক Process চালানো যায়।

উদাহরণ: Browser, Terminal এবং File Manager একসঙ্গে চালানো।

### 💻 4. Portable

Linux বিভিন্ন Hardware Architecture-এ চালানো যায়। যেমন x86-64 এবং ARM।

### 🔐 5. Security and Permissions

Linux-এ User, Group এবং File Permission-এর মাধ্যমে Access Control করা হয়।

এটি System Security-এর একটি গুরুত্বপূর্ণ অংশ।

### 🛡️ 6. Stability

Linux Server-এ ব্যাপকভাবে ব্যবহৃত হয়, কারণ সঠিকভাবে Configure এবং Maintain করলে এটি দীর্ঘ সময় নির্ভরযোগ্যভাবে চলতে পারে।

### 🎨 7. Customization

Desktop Environment থেকে শুরু করে Kernel পর্যন্ত প্রয়োজন অনুযায়ী অনেক কিছু পরিবর্তন করা যায়।

## 🛡️ Why Linux is Important for Cybersecurity?

1. **Networking:** Network Interface, IP Address, Routing এবং Network Services সম্পর্কে কাজ করা যায়।
2. **Penetration Testing:** বিভিন্ন Security Testing Tool Linux-এ ব্যবহার করা যায়।
3. **System Administration:** User, Group, Permission এবং Process Management শেখা যায়।
4. **Scripting:** Bash এবং Python দিয়ে বিভিন্ন কাজ Automate করা যায়।
5. **Server Security:** Linux Server কীভাবে কাজ করে এবং কীভাবে Secure করতে হয়, তা শেখা যায়।
6. **Log Analysis:** System Log এবং Application Log বিশ্লেষণ করা যায়।
7. **Open Source Tools:** অনেক Cybersecurity Tool Linux-এ তৈরি ও ব্যবহার করা হয়।

**মনে রাখবে:** Cybersecurity শেখার জন্য শুধু Kali Linux ব্যবহার করলেই হবে না। Linux Operating System-এর ভিতরের বিষয়গুলো বুঝতে হবে।

---

# 2. 📦 Distributions of Linux

## 📖 What is a Linux Distribution?

Linux Distribution বা Distro হলো Linux Kernel-এর সঙ্গে বিভিন্ন Software, System Utilities, Package Manager এবং Configuration Tools যুক্ত করে তৈরি একটি সম্পূর্ণ Operating System।

সহজভাবে বললে, Linux Kernel একই থাকতে পারে, কিন্তু তার সঙ্গে কোন Software, Desktop Environment এবং Package Management System ব্যবহার করা হচ্ছে, তার ওপর ভিত্তি করে বিভিন্ন Linux Distribution তৈরি হয়।

প্রতিটি Distribution-এর নিজস্ব উদ্দেশ্য এবং বৈশিষ্ট্য রয়েছে।

## 🌳 Major Linux Distribution Families

Linux-এর অনেক Distribution রয়েছে। এগুলোর মধ্যে কিছু Distribution অন্য Distribution-এর ওপর ভিত্তি করে তৈরি।

### 🟠 1. Debian Family

**Debian** একটি জনপ্রিয় এবং Community-driven Linux Distribution।

এর ওপর ভিত্তি করে অনেক Distribution তৈরি হয়েছে।

- Package Manager: APT
- Package Format: `.deb`
- Stability এবং Reliability-এর জন্য পরিচিত।

**Important Distros:**

- Debian: Stable এবং General-purpose Operating System।
- Ubuntu: Debian-based, Beginner-friendly এবং Desktop ও Server-এ জনপ্রিয়।
- Linux Mint: Beginner-friendly Desktop Distribution।
- Kali Linux: Cybersecurity এবং Penetration Testing-এর জন্য তৈরি।
- Parrot OS: Security Testing, Digital Forensics এবং Privacy-focused কাজের জন্য তৈরি।
- Pop!_OS: Desktop এবং Development-focused Distribution।

**Cybersecurity Connection:**

Kali Linux এবং Parrot OS Debian-এর ওপর ভিত্তি করে তৈরি। তাই এদের Package Management-এ APT ব্যবহার করা হয়।

উদাহরণ:

```
sudo apt update
sudo apt install nmap
```

### 🔴 2. Red Hat Family

Red Hat Family মূলত Enterprise এবং Server Environment-এ বেশি ব্যবহৃত হয়।

- Package Manager: DNF (বর্তমান Fedora/RHEL-based systems)
- Package Format: `.rpm`

**Important Distros:**

- Red Hat Enterprise Linux (RHEL): Enterprise Environment-এর জন্য Commercial Distribution।
- Fedora: Community-driven, নতুন Technology এবং Software-এর জন্য পরিচিত।
- Rocky Linux: RHEL-compatible Enterprise Linux।
- AlmaLinux: RHEL-compatible Enterprise Linux।
- CentOS Stream: RHEL-এর সঙ্গে সম্পর্কিত একটি continuously delivered Distribution।

**Cybersecurity Connection:**

Enterprise Server Security, System Administration এবং Linux Server Management শেখার ক্ষেত্রে এই Family গুরুত্বপূর্ণ।

### 🔵 3. Arch Linux Family

Arch Linux একটি Lightweight এবং Highly Customizable Distribution।

- Package Manager: Pacman
- Package Format: `.pkg.tar.zst`
- Rolling Release Model ব্যবহার করে।

**Important Distros:**

- Arch Linux: Advanced User-দের জন্য Minimal এবং Customizable Distribution।
- Manjaro: Arch-based, তুলনামূলকভাবে সহজ ব্যবহারযোগ্য।
- EndeavourOS: Arch-based, সহজ Installation-এর সুবিধাসহ।

**Cybersecurity Connection:**

Arch Linux ব্যবহার করলে Linux Configuration, Package Management এবং System Customization সম্পর্কে ভালো ধারণা তৈরি হতে পারে।

### 🟢 4. SUSE Family

SUSE Family মূলত Enterprise এবং Professional Server Environment-এ ব্যবহৃত হয়।

**Important Distros:**

- SUSE Linux Enterprise (SLE): Enterprise Environment-এর জন্য।
- openSUSE Leap: Stable এবং Enterprise-oriented।
- openSUSE Tumbleweed: Rolling Release Distribution।
- Package Manager: Zypper
- Package Format: `.rpm`

### ⚙️ 5. Independent Distributions

কিছু Distribution অন্য কোনো প্রধান Distribution-এর ওপর সরাসরি ভিত্তি করে তৈরি হয়নি।

**Important Distros:**

- Slackware: পুরোনো এবং Unix-like Design অনুসরণকারী Distribution।
- Gentoo: Source-based এবং Highly Customizable Distribution।
- Alpine Linux: Lightweight এবং Security-focused Design-এর জন্য পরিচিত; Container Environment-এ জনপ্রিয়।
- NixOS: Declarative Configuration এবং Reproducible System Management-এর জন্য পরিচিত।
- Void Linux: Independent এবং Lightweight Distribution।

## 🎯 Special Purpose Linux Distributions

কিছু Distribution নির্দিষ্ট কাজের জন্য তৈরি করা হয়েছে।

### 🐉 1. Kali Linux

- Developer: Offensive Security
- Base: Debian
- Main Purpose: Penetration Testing এবং Security Auditing।
- Common Tools: Nmap, Burp Suite, Wireshark, Metasploit।

এটি Cybersecurity Lab-এর জন্য একটি গুরুত্বপূর্ণ Distribution।

### 🦜 2. Parrot Security OS

- Base: Debian
- Main Purpose: Penetration Testing, Digital Forensics এবং Privacy।
- Security এবং Privacy-focused Tools রয়েছে।

### 🕵️ 3. Tails

- Base: Debian
- Main Purpose: Privacy এবং Anonymity।
- Tor Network-এর মাধ্যমে Internet Traffic পরিচালনার জন্য তৈরি।

### 🏴 4. BlackArch

- Base: Arch Linux
- Main Purpose: Penetration Testing এবং Security Research।
- অনেক Security Tool-এর Collection রয়েছে।

### 🔒 5. Qubes OS

- Main Purpose: Security through Isolation।
- বিভিন্ন কাজকে আলাদা Virtual Machine বা Quarantine Environment-এ চালানোর ব্যবস্থা করে।

## 📊 Important Differences Between Linux Distributions

| Distribution | Base | Package Manager | Main Purpose |
| --- | --- | --- | --- |
| Debian | Independent | APT | Stability |
| Ubuntu | Debian | APT | General Purpose |
| Kali Linux | Debian | APT | Penetration Testing |
| Parrot OS | Debian | APT | Security & Privacy |
| Fedora | Independent | DNF | Modern Desktop & Server |
| RHEL | Independent | DNF | Enterprise |
| Arch Linux | Independent | Pacman | Customization |
| Manjaro | Arch | Pacman | Desktop |
| openSUSE | Independent | Zypper | Desktop & Enterprise |
| Alpine | Independent | APK | Lightweight & Containers |

**Note:** Distribution-এর Family এবং Package Manager-এর মধ্যে সম্পর্ক বুঝte hobe। একই Family-এর Distribution হলেও কিছু Configuration এবং Version-এর পার্থক্য থাকতে পারে।

---

# 3. 🏗️ Linux Architecture

## 📖 What is Linux Architecture?

Linux Architecture বলতে Linux Operating System-এর বিভিন্ন Component কীভাবে একসঙ্গে কাজ করে, তার Structure-কে বোঝায়।

## 🧩 Main Components of Linux Architecture

Linux Architecture-কে সহজভাবে কয়েকটি Layer-এ ভাগ করা যায়।

### 💻 1. Hardware Layer

এটি হলো কম্পিউটারের Physical Components।

উদাহরণ:

- CPU
- RAM
- HDD / SSD
- Keyboard
- Mouse
- Network Interface Card (NIC)
- GPU

Hardware সরাসরি Application-এর সঙ্গে কাজ করে না। Hardware Resource ব্যবহারের জন্য Operating System-এর প্রয়োজন হয়।

### 🧠 2. Kernel Layer

Kernel হলো Operating System-এর সবচেয়ে গুরুত্বপূর্ণ অংশ।

এটি Hardware এবং User Space Software-এর মধ্যে যোগাযোগ স্থাপন করে।

Linux Kernel-এর প্রধান কাজগুলো:

**Process Management:**

কোন Process কখন CPU ব্যবহার করবে, তা নিয়ন্ত্রণ করে।

**Memory Management:**

কোন Process কতটুকু Memory ব্যবহার করবে, তা পরিচালনা করে।

**Device Management:**

Hardware Device-এর সঙ্গে যোগাযোগ পরিচালনা করে।

**File System Management:**

File এবং Directory সংরক্ষণ ও পরিচালনায় সাহায্য করে।

**Network Management:**

Network Communication এবং Networking Stack পরিচালনা করে।

**Security and Access Control:**

User Permission এবং বিভিন্ন Security Mechanism প্রয়োগে ভূমিকা রাখে।

### 🔗 3. System Call Interface

Application এবং User Space-এর Software সরাসরি Kernel-এর সব কাজ করতে পারে না।

তাদের Kernel-এর Services ব্যবহার করার জন্য System Call করতে হয়।

উদাহরণ:

- `open()` → File খোলার জন্য।
- `read()` → File বা Data পড়ার জন্য।
- `write()` → Data লেখার জন্য।
- `fork()` → নতুন Process তৈরি করার জন্য।
- `execve()` → একটি Process-এর Program চালু বা প্রতিস্থাপন করার জন্য।
- `socket()` → Network Communication-এর Socket তৈরি করার জন্য।

**সহজ উদাহরণ:**

তুমি যখন কোনো Program দিয়ে একটি File খুলো, তখন Program প্রয়োজন অনুযায়ী Kernel-এর কাছে File Access-এর জন্য System Call করতে পারে।

### 📚 4. System Libraries

System Libraries হলো এমন কিছু Collection of Functions, যা Application-কে বিভিন্ন System Service ব্যবহার করতে সাহায্য করে।

উদাহরণ:

- glibc (GNU C Library)

একটি Program অনেক সময় সরাসরি System Call না করে Library Function ব্যবহার করে। সেই Library Function প্রয়োজন অনুযায়ী System Call করতে পারে।

### ⌨️ 5. Shell

Shell হলো একটি Command Interpreter।

এটি User-এর দেওয়া Command বুঝে প্রয়োজন অনুযায়ী Program বা System Service চালাতে সাহায্য করে।

উদাহরণ:

- Bash
- Zsh
- Fish

তুমি Kali Linux Terminal-এ যখন লিখো:

```
mkdir notes
```

তখন Shell Command-টি বুঝে `mkdir` Program চালায়। প্রয়োজন অনুযায়ী সেই Program Kernel-এর Service ব্যবহার করে Directory তৈরি করে।

**মনে রাখবে:** Terminal এবং Shell এক জিনিস নয়।

- Terminal: Command লেখার এবং Output দেখার Interface।
- Shell: Command Interpret এবং Execute করার Environment।

### 🛠️ 6. System Utilities

System Utilities হলো বিভিন্ন কাজের জন্য তৈরি Command এবং Program।

উদাহরণ:

- `ls` → File এবং Directory দেখায়।
- `mkdir` → Directory তৈরি করে।
- `cp` → File Copy করে।
- `ps` → Running Process দেখায়।
- `grep` → Text Search করে।

এগুলো Linux System ব্যবহার এবং পরিচালনা করতে সাহায্য করে।

### 🖥️ 7. User Applications

এগুলো হলো User-এর প্রয়োজন অনুযায়ী ব্যবহৃত বিভিন্ন Application।

উদাহরণ:

- Firefox
- VS Code
- Burp Suite
- Wireshark
- Nmap

এগুলো User Space-এ চলে এবং প্রয়োজন অনুযায়ী Kernel-এর Services ব্যবহার করে।

## 🗺️ Linux Architecture Diagram

![image.png](1%20LINUX%20%E2%80%94%20FUNDAMENTALS/image.png)

```
        USER
          |
          v
  +-------------------+
  |   Applications    |
  | Firefox, Nmap     |
  +-------------------+
          |
          v
  +-------------------+
  |  Shell & System   |
  |     Utilities     |
  +-------------------+
          |
          v
  +-------------------+
  |  System Libraries |
  |  System Call API  |
  +-------------------+
          |
          v
  +-------------------+
  |   LINUX KERNEL    |
  |                   |
  | Process Management|
  | Memory Management |
  | File System       |
  | Network Stack     |
  | Device Drivers    |
  +-------------------+
          |
          v
  +-------------------+
  |     HARDWARE      |
  | CPU, RAM, SSD, NIC|
  +-------------------+
```

এটি একটি Simplified Conceptual Diagram। বাস্তবে Shell, System Utilities এবং Applications সবসময় একই সরল ধারায় Kernel-এর সঙ্গে যোগাযোগ করে না।

## 🔐 User Space vs Kernel Space

Linux-এ সাধারণভাবে দুই ধরনের Execution Space রয়েছে।

### 👤 1. User Space

এখানে সাধারণ Application এবং User Program চলে।

উদাহরণ:

- Firefox
- Bash
- Nmap
- Wireshark

User Space-এর Program সরাসরি Kernel-এর Privileged Operation করতে পারে না। প্রয়োজন হলে System Call-এর মাধ্যমে Kernel-এর Service নেয়।

### 🧠 2. Kernel Space

এখানে Linux Kernel চলে।

Kernel-এর Privileged Access থাকে, যার মাধ্যমে এটি Hardware এবং System Resources পরিচালনা করে।

**Difference:**

| User Space | Kernel Space |
| --- | --- |
| সাধারণ Application চলে | Kernel চলে |
| Limited Privileges | High Privileges |
| System Call ব্যবহার করে | Hardware ও System Resources পরিচালনা করে |
| Application Crash হলে সাধারণত Kernel সচল থাকে | Kernel Failure পুরো System-কে প্রভাবিত করতে পারে |

## ⚙️ Linux Kernel Architecture Types

Linux Kernel মূলত Monolithic Kernel Architecture অনুসরণ করে।

তবে Linux একটি Modular Monolithic Kernel।

**Monolithic Kernel:**

Kernel-এর অনেক গুরুত্বপূর্ণ Service একই Kernel Space-এ চলে।

**Modular:**

প্রয়োজন অনুযায়ী Kernel Module Load এবং Unload করা যায়।

উদাহরণ:

- Device Driver
- Network-related Modules
- Filesystem Modules

এতে Kernel-এর কিছু Functionality Module হিসেবে যুক্ত করা সম্ভব হয়।

**Cybersecurity Connection:**

Linux Architecture বোঝা Cybersecurity-এর জন্য গুরুত্বপূর্ণ, কারণ:

1. Process এবং Memory কীভাবে কাজ করে তা বোঝা যায়।
2. User Space এবং Kernel Space-এর পার্থক্য বোঝা যায়।
3. Privilege এবং Permission সম্পর্কে পরিষ্কার ধারণা তৈরি হয়।
4. System Call কীভাবে কাজ করে তা বোঝা যায়।
5. Kernel-level Security এবং System Vulnerability সম্পর্কে শেখার ভিত্তি তৈরি হয়।

---

# 4. 🚀 Applications of Linux

Linux শুধু একটি Desktop Operating System নয়। এটি পৃথিবীর বিভিন্ন গুরুত্বপূর্ণ Technology এবং Infrastructure-এ ব্যবহৃত হয়।

![image.png](1%20LINUX%20%E2%80%94%20FUNDAMENTALS/image%201.png)

## 🖥️ 1. Server Administration

Linux Web Server, Database Server এবং File Server পরিচালনায় ব্যাপকভাবে ব্যবহৃত হয়।

উদাহরণ:

- Apache
- Nginx
- MySQL
- PostgreSQL

## 🛡️ 2. Cybersecurity

Cybersecurity Professional-রা বিভিন্ন Security-related কাজের জন্য Linux ব্যবহার করেন।

উদাহরণ:

- Penetration Testing
- Network Analysis
- Vulnerability Assessment
- Digital Forensics
- Security Auditing

Tools: Nmap, Wireshark, Burp Suite, Metasploit।

## 💻 3. Software Development

Developers-রা Linux ব্যবহার করে বিভিন্ন ধরনের Software তৈরি করেন।

উদাহরণ:

- C / C++ Development
- Python Development
- Web Development
- Backend Development

GCC, G++, Git এবং বিভিন্ন Development Tools Linux-এ ব্যবহার করা যায়।

## ☁️ 4. Cloud Computing

Cloud Infrastructure এবং Cloud Server পরিচালনায় Linux ব্যাপকভাবে ব্যবহৃত হয়।

উদাহরণ:

- AWS
- Microsoft Azure
- Google Cloud

## 🚀 5. Supercomputers

বিশ্বের অধিকাংশ Supercomputer Linux-based Operating System ব্যবহার করে।

কারণ Linux High Performance Computing এবং Large-scale Workload পরিচালনায় উপযোগী।

## 📱 6. Mobile Operating Systems

Android Linux Kernel-এর ওপর ভিত্তি করে তৈরি।

তবে Android সাধারণ Desktop Linux Distribution নয়। এটি Linux Kernel-এর সঙ্গে Android-specific Framework এবং Runtime ব্যবহার করে।

## 📡 7. Embedded Systems and IoT

ছোট ছোট Electronic Device এবং Smart Device-এ Linux ব্যবহার করা হয়।

উদাহরণ:

- Smart TV
- Router
- Raspberry Pi
- IoT Devices
- Network Appliances

## 🐳 8. Containers and Virtualization

Linux Container Technology এবং Virtualization Environment-এ গুরুত্বপূর্ণ ভূমিকা রাখে।

উদাহরণ:

- Docker
- Podman
- KVM

এগুলো Software Deployment, Isolation এবং Resource Management-এ ব্যবহৃত হয়।

## 🌐 9. Networking

অনেক Router, Firewall, Network Appliance এবং Network Server Linux ব্যবহার করে।

Linux-এর Networking Tools দিয়ে Network Configuration, Monitoring এবং Troubleshooting করা যায়।

## 📋 Quick Summary

| Field | Linux-এর ব্যবহার |
| --- | --- |
| Cybersecurity | Penetration Testing, Security Analysis |
| Server | Web Server, Database Server |
| Development | Programming, Software Development |
| Cloud | Cloud Infrastructure |
| Supercomputing | High Performance Computing |
| Mobile | Android Kernel |
| IoT | Smart Devices, Embedded Systems |
| Networking | Router, Firewall, Network Services |
| Virtualization | KVM, Containers |

**Final Note:**

Linux শেখার মূল উদ্দেশ্য শুধু Command ব্যবহার শেখা নয়। Linux কীভাবে কাজ করে, কীভাবে Hardware পরিচালনা করে, কীভাবে Process চালায় এবং কীভাবে Network Communication করে—এসব বোঝাই হলো Linux Fundamentals শেখার আসল উদ্দেশ্য।
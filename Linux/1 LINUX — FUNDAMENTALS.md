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

![image.png](data:image/jpeg;base64,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)
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

# Midterm Project

by [Benedict Alam](https://www.facebook.com/benedict.alam) and [Alliah Jane Arevalo](https://www.facebook.com/alliaharevalo)

# Kali Linux Applications

Kali Linux is a popular Linux distribution widely used for penetration testing, digital forensics, and security research. It comes pre-installed with numerous tools categorized into various domains, including Information Gathering, Vulnerability Analysis, Exploitation Tools, and more.

## 01 - Information Gathering

## Introduction
Information Gathering is a critical process across diverse domains like cybersecurity, market research, and intelligence analysis. It involves gathering relevant data from various sources to gain insights, make informed decisions, and manage risks effectively. The introduction highlights its importance and outlines the upcoming exploration of techniques, tools, and methodologies. Topics include open-source intelligence (OSINT), network reconnaissance, and social engineering, aiming to empower professionals with essential skills for navigating complex and data-rich environments.

## Table of Contents

1. [Nmap](#nmap)
2. [Recon-ng](#recon-ng)
3. [theHarvester](#theharvester)
4. [Metagoofil](#metagoofil)
5. [Shodan](#shodan)
6. [Maltego](#maltego)
7. [SpiderFoot](#spiderfoot)
8. [Photon](#photon)
9. [Osmedeus](#osmedeus)
10. [Sublist3r](#sublist3r)

## Information Gathering

### Nmap
- **Description**: Nmap is a powerful network scanning tool used to discover hosts and services on a computer network, thus creating a "map" of the network.
- **Usage**: `nmap [scan type] [target]`
- **Documentation**: [Nmap Documentation](https://nmap.org/docs.html)

### Recon-ng
- **Description**: Recon-ng is a full-featured web reconnaissance framework that provides a powerful environment for conducting open-source reconnaissance quickly and thoroughly.
- **Usage**: `recon-ng`
- **Documentation**: [Recon-ng Wiki](https://github.com/lanmaster53/recon-ng/wiki)

### theHarvester
- **Description**: TheHarvester is a tool for gathering information from public sources (search engines, shodan, pgp, etc.) about a target company, individuals, or group.
- **Usage**: `theharvester -d [domain] -b [source]`
- **Documentation**: [theHarvester Documentation](https://github.com/laramies/theHarvester)

### Metagoofil
- **Description**: Metagoofil is a tool for extracting metadata of public documents (pdf, doc, xls, ppt, etc.) available in the target domain.
- **Usage**: `metagoofil -d [domain] -t [filetype] -o [output directory]`
- **Documentation**: [Metagoofil GitHub](https://github.com/laramies/metagoofil)

### Shodan
- **Description**: Shodan is a search engine for Internet-connected devices. It lets you find specific types of computers, including webcams, routers, servers, and more.
- **Usage**: Web Interface ([Shodan](https://www.shodan.io/))
- **Documentation**: [Shodan Documentation](https://help.shodan.io/)

### Maltego
- **Description**: Maltego is an interactive data mining tool that renders directed graphs for link analysis. It is used to gather information about people, companies, and other entities.
- **Usage**: Graphical Interface
- **Documentation**: [Maltego Documentation](https://docs.maltego.com/)

### SpiderFoot
- **Description**: SpiderFoot is an open-source intelligence automation tool. It automates the process of collecting intelligence from various sources.
- **Usage**: `spiderfoot -l [logfile] -o [output directory]`
- **Documentation**: [SpiderFoot Documentation](https://github.com/smicallef/spiderfoot)

### Photon
- **Description**: Photon is a web crawler designed to search and extract metadata out of websites.
- **Usage**: `photon -u [URL] -l [number of threads] -o [output directory]`
- **Documentation**: [Photon GitHub](https://github.com/s0md3v/Photon)

### Osmedeus
- **Description**: Osmedeus is an open-source automated tool for reconnaissance and vulnerability scanning.
- **Usage**: `osmedeus.py -t [target] -m [module]`
- **Documentation**: [Osmedeus GitHub](https://github.com/j3ssie/Osmedeus)

### Sublist3r
- **Description**: Sublist3r is a python tool designed to enumerate subdomains of websites using OSINT.
- **Usage**: `sublist3r -d [domain]`
- **Documentation**: [Sublist3r GitHub](https://github.com/aboul3la/Sublist3r)

These are just some of the many Information Gathering tools available in Kali Linux. Each tool has its own specific use cases and methods of operation. It's important to thoroughly understand each tool and its capabilities before using them in any security assessments or penetration tests.


## 02 - Vulnerability Analysis

## Introduction

Vulnerability Analysis tools in Kali Linux are crucial for identifying security weaknesses in systems, networks, and applications. These tools help security professionals assess and prioritize potential vulnerabilities, allowing them to take appropriate measures to mitigate risks and strengthen security posture.

## Table of Contents

1. [OpenVAS](#openvas)
2. [Nessus](#nessus)
3. [Nexpose](#nexpose)
4. [Nikto](#nikto)
5. [VulnWhisperer](#vulnwhisperer)
6. [Vuls](#vuls)
7. [Vulnerable Docker VM](#vulnerable-docker-vm)

## OpenVAS

- **Description**: OpenVAS (Open Vulnerability Assessment System) is a comprehensive vulnerability scanning tool that detects security issues in target systems. It provides a range of features including remote network security auditing, centralized vulnerability management, and web-based user interface.
- **Usage**: Start OpenVAS by running `openvas-start`, then access the web interface using a browser.
- **Documentation**: [OpenVAS Documentation](https://www.openvas.org/docs.html)

## Nessus

- **Description**: Nessus is a widely-used vulnerability scanner that identifies vulnerabilities, policy violations, and malware in various systems and applications. It offers comprehensive scanning capabilities, including plugin-based scanning, asset discovery, and report generation.
- **Usage**: Install and configure Nessus, then access the web interface using a browser.
- **Documentation**: [Nessus Documentation](https://docs.tenable.com/nessus/)

## Nexpose

- **Description**: Nexpose, now known as Rapid7 InsightVM, is an advanced vulnerability management solution that helps organizations assess and prioritize security risks. It offers vulnerability scanning, asset discovery, risk assessment, and remediation tracking capabilities.
- **Usage**: Install and configure Nexpose, then access the web interface using a browser.
- **Documentation**: [Rapid7 InsightVM Documentation](https://docs.rapid7.com/insightvm/)

## Nikto

- **Description**: Nikto is a web server scanner that performs comprehensive tests against web servers to identify potential vulnerabilities and misconfigurations. It checks for common security issues such as outdated software versions, exposed directories, and insecure configurations.
- **Usage**: Run `nikto -h [target]` to scan a target web server.
- **Documentation**: [Nikto Documentation](https://cirt.net/Nikto2)

## VulnWhisperer

- **Description**: VulnWhisperer is a tool designed to automate the process of collecting and correlating vulnerability scan results from various sources such as Nessus, OpenVAS, and Nexpose. It consolidates vulnerability data into a unified format for easier analysis and reporting.
- **Usage**: Install VulnWhisperer and configure it to integrate with vulnerability scanners.
- **Documentation**: [VulnWhisperer GitHub Repository](https://github.com/HASecuritySolutions/VulnWhisperer)

## Vuls

- **Description**: Vuls (Vulnerability Scanner) is an open-source vulnerability scanner that performs automated security assessments of Linux and FreeBSD systems. It scans for vulnerabilities in operating systems, libraries, and application packages, providing detailed reports and remediation recommendations.
- **Usage**: Install Vuls and configure it to scan target systems.
- **Documentation**: [Vuls Documentation](https://vuls.io/docs/en/)

## Vulnerable Docker VM

- **Description**: Vulnerable Docker VM is a pre-configured virtual machine environment containing intentionally vulnerable components and applications. It serves as a practice environment for security professionals to learn and test various exploitation techniques and vulnerability assessment tools.
- **Usage**: Download and deploy the Vulnerable Docker VM in a virtualization platform such as VMware or VirtualBox.
- **Documentation**: [Vulnerable Docker VM GitHub Repository](https://github.com/madhuakula/docker-vulnerable-environment)

## Conclusion

Vulnerability Analysis tools play a critical role in assessing and mitigating security risks in systems and networks. The tools mentioned above provide security professionals with the necessary capabilities to identify vulnerabilities, prioritize remediation efforts, and strengthen overall security posture.


## 03 - Web Application Analysis

## Introduction

Web application analysis is a crucial aspect of cybersecurity, focusing on identifying and mitigating vulnerabilities in web applications. Kali Linux provides a wide range of tools specifically designed for analyzing and testing the security of web applications. This documentation provides an overview of these tools along with their descriptions and usage instructions.

## Table of Contents

1. [Burp Suite](#burp-suite)
2. [OWASP ZAP](#owasp-zap)
3. [SQLMap](#sqlmap)
4. [Nikto](#nikto)
5. [Wfuzz](#wfuzz)
6. [Arachni](#arachni)
7. [Skipfish](#skipfish)
8. [DirBuster](#dirbuster)
9. [Gobuster](#gobuster)
10. [XSStrike](#xsstrike)

## 1. Burp Suite

- **Description**: Burp Suite is an integrated platform for performing security testing of web applications. It provides various tools for manual and automated testing, including scanning, crawling, and vulnerability detection.
- **Usage**: Launch Burp Suite from the application menu or command line.
- **Documentation**: [Burp Suite Documentation](https://portswigger.net/burp/documentation)

## 2. OWASP ZAP

- **Description**: OWASP ZAP (Zed Attack Proxy) is an open-source web application security scanner used for finding vulnerabilities in web applications. It offers automated scanning, as well as a variety of tools for manual testing.
- **Usage**: Launch OWASP ZAP from the application menu or command line.
- **Documentation**: [OWASP ZAP Documentation](https://www.zaproxy.org/docs/)

## 3. SQLMap

- **Description**: SQLMap is a powerful tool for automated SQL injection and database takeover attacks. It is used to detect and exploit SQL injection vulnerabilities in web applications.
- **Usage**: Run SQLMap from the command line with appropriate parameters.
- **Documentation**: [SQLMap Documentation](https://sqlmap.org/documentation/)

## 4. Nikto

- **Description**: Nikto is a web server scanner that performs comprehensive tests against web servers to identify potential vulnerabilities, misconfigurations, and security loopholes.
- **Usage**: Execute Nikto from the command line with the target URL.
- **Documentation**: [Nikto Documentation](https://cirt.net/Nikto2)

## 5. Wfuzz

- **Description**: Wfuzz is a web application brute forcer used for finding hidden files, directories, and parameters by fuzzing web applications.
- **Usage**: Run Wfuzz from the command line with appropriate options and parameters.
- **Documentation**: [Wfuzz Documentation](https://github.com/xmendez/wfuzz/wiki)

## 6. Arachni

- **Description**: Arachni is a feature-rich, modular, and high-performance web application security scanner framework. It is designed to identify security issues in web applications.
- **Usage**: Launch Arachni from the command line with the target URL.
- **Documentation**: [Arachni Documentation](https://www.arachni-scanner.com/documentation/)

## 7. Skipfish

- **Description**: Skipfish is an active web application security reconnaissance tool. It is used to scan web applications for security vulnerabilities and generates comprehensive reports.
- **Usage**: Execute Skipfish from the command line with the target URL.
- **Documentation**: [Skipfish Documentation](https://tools.kali.org/web-applications/skipfish)

## 8. DirBuster

- **Description**: DirBuster is a multi-threaded web application brute-forcer used for identifying hidden directories and files within a web server.
- **Usage**: Launch DirBuster from the application menu or command line.
- **Documentation**: [DirBuster Documentation](https://www.owasp.org/index.php/Category:OWASP_DirBuster_Project)

## 9. Gobuster

- **Description**: Gobuster is a directory and file brute-forcing tool similar to DirBuster but with more speed and flexibility.
- **Usage**: Run Gobuster from the command line with appropriate options and parameters.
- **Documentation**: [Gobuster Documentation](https://github.com/OJ/gobuster)

## 10. XSStrike

- **Description**: XSStrike is a cross-site scripting (XSS) detection and exploitation framework. It is used to find and exploit XSS vulnerabilities in web applications.
- **Usage**: Execute XSStrike from the command line with the target URL.
- **Documentation**: [XSStrike Documentation](https://github.com/s0md3v/XSStrike)



## 04 - Database Assessment

## Introduction

Database assessment is a critical aspect of cybersecurity, especially when it comes to identifying vulnerabilities and ensuring data integrity within an organization. Kali Linux offers a wide range of tools specifically designed for database assessment, including scanning for vulnerabilities, exploiting weaknesses, and performing various database-related tasks. This documentation provides an overview of the database assessment tools available in Kali Linux, along with descriptions and usage instructions for each tool.

## Table of Contents

1. [SQLMap](#sqlmap)
2. [SQLNinja](#sqlninja)
3. [SQLMate](#sqlmate)
4. [NoSQLMap](#nosqlmap)
5. [SQLBrute](#sqlbrute)
6. [MDBTools](#mdbtools)
7. [Fierce](#fierce)
8. [Blind-SQL-Injector](#blind-sql-injector)

## 1. SQLMap

- **Description**: SQLMap is an automatic SQL injection and database takeover tool. It is used to detect and exploit SQL injection vulnerabilities in web applications.
- **Usage**: `sqlmap [options]`
- **Documentation**: [SQLMap Documentation](https://github.com/sqlmapproject/sqlmap)

## 2. SQLNinja

- **Description**: SQLNinja is a tool used to exploit SQL Server injection vulnerabilities. It allows attackers to take full control of SQL Server databases.
- **Usage**: `sqlninja [options]`
- **Documentation**: [SQLNinja Documentation](https://github.com/xxgrunge/sqlninja)

## 3. SQLMate

- **Description**: SQLMate is a lightweight SQL injection tool that can detect and exploit SQL injection vulnerabilities in web applications.
- **Usage**: `sqlmate [options]`
- **Documentation**: [SQLMate Documentation](https://github.com/UltimateHackers/sqlmate)

## 4. NoSQLMap

- **Description**: NoSQLMap is an automated tool designed to detect and exploit NoSQL injection vulnerabilities in web applications and web services.
- **Usage**: `nosqlmap [options]`
- **Documentation**: [NoSQLMap Documentation](https://github.com/codingo/NoSQLMap)

## 5. SQLBrute

- **Description**: SQLBrute is a tool used for blind SQL injection attacks. It can be used to enumerate databases, tables, and columns in a blind SQL injection scenario.
- **Usage**: `sqlbrute [options]`
- **Documentation**: [SQLBrute Documentation](https://github.com/xxgrunge/sqlbrute)

## 6. MDBTools

- **Description**: MDBTools is a set of utilities for interacting with Microsoft Access databases (MDB files) without using the Microsoft Access application.
- **Usage**: Various commands for interacting with MDB files.
- **Documentation**: [MDBTools Documentation](https://github.com/brianb/mdbtools)

## 7. Fierce

- **Description**: Fierce is a DNS reconnaissance tool for locating non-contiguous IP space. It can be used to discover domain names and associated IP addresses.
- **Usage**: `fierce [options]`
- **Documentation**: [Fierce Documentation](https://github.com/mschwager/fierce)

## 8. Blind-SQL-Injector

- **Description**: Blind-SQL-Injector is a Python-based SQL injection tool that performs blind SQL injection attacks against web applications.
- **Usage**: `blind-sql-injector [options]`
- **Documentation**: [Blind-SQL-Injector Documentation](https://github.com/UltimateHackers/blind-sql-injector)

## Conclusion

This documentation provides an overview of the database assessment tools available in Kali Linux, including SQL injection detection and exploitation, NoSQL injection detection, Microsoft Access database manipulation, and DNS reconnaissance. These tools are essential for assessing the security of databases and web applications, helping organizations identify and remediate potential vulnerabilities.


## 05 - Password Attacks

## Introduction

Kali Linux is renowned for its extensive arsenal of tools for penetration testing and ethical hacking. In the realm of password attacks, Kali Linux offers a diverse range of tools designed to crack passwords, perform brute-force attacks, and exploit vulnerabilities in authentication systems. This documentation provides an overview of the password attack tools available in Kali Linux along with descriptions and usage instructions.

## Table of Contents

1. [John the Ripper](#john-the-ripper)
2. [Hashcat](#hashcat)
3. [Hydra](#hydra)
4. [Medusa](#medusa)
5. [CeWL](#cewl)
6. [Crunch](#crunch)
7. [RainbowCrack](#rainbowcrack)
8. [Patator](#patator)
9. [THC-Hydra](#thc-hydra)

## 1. John the Ripper

- **Description**: John the Ripper is a fast password cracker, currently available for many flavors of Unix, macOS, Windows, DOS, BeOS, and OpenVMS. Its primary purpose is to detect weak Unix passwords.
- **Usage**: 
  - To crack passwords using default settings: `john [file]`
  - To specify the format of the hash: `john --format=[format] [file]`
- **Documentation**: [John the Ripper Documentation](https://www.openwall.com/john/doc/)

## 2. Hashcat

- **Description**: Hashcat is the world's fastest and most advanced password recovery utility, supporting five unique modes of attack for over 200 highly-optimized hashing algorithms.
- **Usage**: `hashcat [options] hashfile [dictionary]`
- **Documentation**: [Hashcat Documentation](https://hashcat.net/hashcat/)

## 3. Hydra

- **Description**: Hydra is a parallelized login cracker which supports numerous protocols to attack.
- **Usage**: `hydra -l [username] -P [password list] [target] [service]`
- **Documentation**: [Hydra Documentation](https://github.com/vanhauser-thc/thc-hydra)

## 4. Medusa

- **Description**: Medusa is a speedy, parallel, and modular login brute-force attack tool.
- **Usage**: `medusa -h [host] -U [username file] -P [password file] -M [module]`
- **Documentation**: [Medusa Documentation](https://github.com/jmk-foofus/medusa)

## 5. CeWL

- **Description**: CeWL is a ruby app which spiders a given URL to a specified depth, optionally following external links, and returns a list of words which can then be used for password attacks.
- **Usage**: `cewl [options] [URL]`
- **Documentation**: [CeWL Documentation](https://github.com/digininja/CeWL)

## 6. Crunch

- **Description**: Crunch is a wordlist generator where you can specify a standard character set or a character set you specify. crunch can generate all possible combinations and permutations.
- **Usage**: `crunch [min length] [max length] [character set] -o [output file]`
- **Documentation**: [Crunch Documentation](https://tools.kali.org/password-attacks/crunch)

## 7. RainbowCrack

- **Description**: RainbowCrack is a general propose implementation of Philippe Oechslin's faster time-memory trade-off technique. It crack hashes with rainbow tables.
- **Usage**: `rtgen [options]`
- **Documentation**: [RainbowCrack Documentation](https://tools.kali.org/password-attacks/rainbowcrack)

## 8. Patator

- **Description**: Patator is a multi-purpose brute-forcer, with a modular design and a flexible usage.
- **Usage**: `patator [module] [options]`
- **Documentation**: [Patator Documentation](https://github.com/lanjelot/patator)

## 9. THC-Hydra

- **Description**: THC-Hydra is a fast network logon cracker which supports many different services.
- **Usage**: `hydra [options] [service]://[target]`
- **Documentation**: [THC-Hydra Documentation](https://github.com/vanhauser-thc/thc-hydra)



## 06 - Wireless Attacks

## Introduction

Wireless attacks are a crucial aspect of penetration testing and cybersecurity assessments, especially with the increasing prevalence of wireless networks. Kali Linux provides a comprehensive suite of tools specifically designed for assessing the security of wireless networks. This documentation aims to provide an overview of the wireless attack tools available in Kali Linux, along with their descriptions and usage instructions.

## Table of Contents

1. [Aircrack-ng](#1-aircrack-ng)
2. [Reaver](#2-reaver)
3. [Wireshark](#3-wireshark)
4. [Kismet](#4-kismet)
5. [WiFite](#5-wifite)

## 1. Aircrack-ng

- **Description**: Aircrack-ng is a powerful suite of tools used for auditing wireless networks. It includes tools for packet capturing, packet analysis, network injection, and password cracking.
- **Usage**: Various commands for different attacks, e.g., `airmon-ng`, `aireplay-ng`, `aircrack-ng`.
- **Documentation**: [Aircrack-ng Documentation](https://www.aircrack-ng.org/documentation.html)

## 2. Reaver

- **Description**: Reaver is a brute force attack tool specifically designed to exploit vulnerabilities in Wi-Fi Protected Setup (WPS). It attempts to recover WPA/WPA2 passphrase keys.
- **Usage**: `reaver -i [interface] -b [BSSID]`
- **Documentation**: [Reaver GitHub Repository](https://github.com/t6x/reaver-wps-fork-t6x)

## 3. Wireshark

- **Description**: Wireshark is a popular network protocol analyzer that can be used for analyzing wireless network traffic. It is capable of capturing and displaying data packets in real-time.
- **Usage**: Launch via command line or graphical interface.
- **Documentation**: [Wireshark User Guide](https://www.wireshark.org/docs/wsug_html_chunked/)

## 4. Kismet

- **Description**: Kismet is a wireless network detector, sniffer, and intrusion detection system. It can detect hidden networks, monitor packet transmissions, and identify rogue access points.
- **Usage**: `kismet` to launch the application.
- **Documentation**: [Kismet Documentation](https://www.kismetwireless.net/documentation.shtml)

## 5. WiFite

- **Description**: WiFite is a tool designed for automated wireless auditing. It can perform various attacks such as capturing handshakes, deauthentication attacks, and brute force attacks on Wi-Fi passwords.
- **Usage**: Launch via command line.
- **Documentation**: [WiFite GitHub Repository](https://github.com/derv82/wifite2)

This documentation provides an overview of some of the key wireless attack tools available in Kali Linux. For more detailed information on each tool and their usage, please refer to their respective documentation links provided.


## 07 - Reverse Engineering

## Introduction

Reverse engineering is the process of analyzing a software system to understand its internal functioning, design, and implementation details. In Kali Linux, various tools are available for reverse engineering tasks, including analyzing binaries, disassembling code, and debugging applications. This documentation provides an overview of the reverse engineering tools included in Kali Linux along with their descriptions and usage instructions.

## Table of Contents

1. [Radare2](#radare2)
2. [Ghidra](#ghidra)
3. [IDA Pro](#ida-pro)
4. [OllyDbg](#ollydbg)
5. [Binary Ninja](#binary-ninja)
6. [Hopper Disassembler](#hopper-disassembler)
7. [Angr](#angr)
8. [GDB](#gdb)
9. [Immunity Debugger](#immunity-debugger)
10. [X64dbg](#x64dbg)

## 1. Radare2

- **Description**: Radare2 is an open-source reverse engineering framework that provides a set of tools for binary analysis, disassembly, debugging, and exploitation.
- **Usage**: `r2 [file]` to start analysis.
- **Documentation**: [Radare2 Documentation](https://radare.gitbooks.io/radare2book/content/)

## 2. Ghidra

- **Description**: Ghidra is a software reverse engineering (SRE) framework developed by the NSA. It offers features such as disassembly, decompilation, scripting, and collaboration.
- **Usage**: Launch via command line or graphical interface.
- **Documentation**: [Ghidra Documentation](https://ghidra-sre.org/)

## 3. IDA Pro

- **Description**: IDA Pro is a commercial disassembler and debugger widely used for reverse engineering tasks. It supports various architectures and file formats.
- **Usage**: Launch via graphical interface.
- **Documentation**: [IDA Pro Documentation](https://www.hex-rays.com/products/ida/support/)

## 4. OllyDbg

- **Description**: OllyDbg is a 32-bit assembler-level debugger for Microsoft Windows. It is commonly used for dynamic analysis and debugging of binary executables.
- **Usage**: Launch via graphical interface.
- **Documentation**: [OllyDbg Documentation](https://tuts4you.com/download.php?view.4196)

## 5. Binary Ninja

- **Description**: Binary Ninja is a reverse engineering platform that provides a powerful interface for analyzing binaries. It offers features such as disassembly, graph visualization, and scripting.
- **Usage**: Launch via graphical interface.
- **Documentation**: [Binary Ninja Documentation](https://docs.binary.ninja/)

## 6. Hopper Disassembler

- **Description**: Hopper Disassembler is a reverse engineering tool that allows users to disassemble, decompile, and debug binary executables. It supports multiple platforms and architectures.
- **Usage**: Launch via graphical interface.
- **Documentation**: [Hopper Disassembler Documentation](https://www.hopperapp.com/documentation/)

## 7. Angr

- **Description**: Angr is a binary analysis framework that automates reverse engineering tasks such as symbolic execution, constraint solving, and program analysis.
- **Usage**: Use Python scripts to interact with the framework.
- **Documentation**: [Angr Documentation](https://docs.angr.io/)

## 8. GDB

- **Description**: GDB, or the GNU Debugger, is a powerful command-line debugger for various programming languages. It is commonly used for debugging and analyzing binary executables.
- **Usage**: `gdb [executable]` to start debugging.
- **Documentation**: [GDB Documentation](https://www.gnu.org/software/gdb/documentation/)

## 9. Immunity Debugger

- **Description**: Immunity Debugger is a powerful debugger for analyzing malware and performing reverse engineering tasks. It offers features such as scriptable Python plugins and debugging of multi-threaded applications.
- **Usage**: Launch via graphical interface.
- **Documentation**: [Immunity Debugger Documentation](https://www.immunityinc.com/products/debugger/)

## 10. X64dbg

- **Description**: X64dbg is an open-source, cross-platform debugger for Windows binaries. It offers features such as disassembly, debugging, and plugin support.
- **Usage**: Launch via graphical interface.
- **Documentation**: [X64dbg Documentation](https://x64dbg.com/docs/)

## 08 - Exploitation Tools

## Introduction

Kali Linux is renowned for its extensive collection of exploitation tools, which are used by security professionals and ethical hackers for discovering and exploiting vulnerabilities in target systems. This documentation aims to provide an overview of the exploitation tools available in Kali Linux, including their descriptions and usage instructions.

## Table of Contents

1. [Metasploit Framework](#metasploit-framework)
2. [ExploitDB](#exploitdb)
3. [Armitage](#armitage)
4. [Shellter](#shellter)
5. [Veil](#veil)
6. [BeEF](#beef)
7. [Empire](#empire)
8. [OWASP ZSC](#owasp-zsc)
9. [CrackMapExec](#crackmapexec)
10. [Responder](#responder)
11. [PowerSploit](#powersploit)
12. [RouterSploit](#routersploit)
13. [EternalBlue](#eternalblue)

## 1. Metasploit Framework

- **Description**: A powerful penetration testing framework that enables users to develop, test, and execute exploits against target systems.
- **Usage**: Access via command line or web interface.
- **Documentation**: [Metasploit Framework Documentation](https://metasploit.help.rapid7.com/docs/getting-started)

## 2. ExploitDB

- **Description**: A comprehensive database of exploits and vulnerable software, regularly updated with new exploits.
- **Usage**: Access via web browser or CLI tools.
- **Documentation**: [ExploitDB Documentation](https://www.exploit-db.com/)

## 3. Armitage

- **Description**: A graphical cyber attack management tool that integrates with Metasploit for easier exploitation.
- **Usage**: Launch via command line or graphical interface.
- **Documentation**: [Armitage Documentation](https://www.fastandeasyhacking.com/)

## 4. Shellter

- **Description**: A dynamic shellcode injection tool that can bypass antivirus and other security measures.
- **Usage**: Command-line interface for injecting shellcode into existing Windows executables.
- **Documentation**: [Shellter Documentation](https://www.shellterproject.com/)

## 5. Veil

- **Description**: A framework for generating undetectable payload executables for bypassing antivirus.
- **Usage**: Command-line interface for generating payloads and encrypting them.
- **Documentation**: [Veil Documentation](https://github.com/Veil-Framework/Veil)

## 6. BeEF

- **Description**: The Browser Exploitation Framework used for launching client-side attacks.
- **Usage**: Access the web interface after starting the BeEF service.
- **Documentation**: [BeEF Documentation](https://github.com/beefproject/beef)

## 7. Empire

- **Description**: A post-exploitation framework that includes a variety of modules for Windows and macOS exploitation.
- **Usage**: Command-line interface for launching attacks and managing compromised systems.
- **Documentation**: [Empire Documentation](https://github.com/EmpireProject/Empire)

## 8. OWASP ZSC

- **Description**: A tool for generating shellcodes and obfuscating them to bypass security solutions.
- **Usage**: Command-line interface for generating and encoding shellcodes.
- **Documentation**: [OWASP ZSC Documentation](https://github.com/zscproject/OWASP-ZSC)

## 9. CrackMapExec

- **Description**: A swiss army knife for pentesting Windows/Active Directory environments.
- **Usage**: Command-line interface for enumerating and exploiting Windows hosts.
- **Documentation**: [CrackMapExec Documentation](https://github.com/byt3bl33d3r/CrackMapExec)

## 10. Responder

- **Description**: A tool for LLMNR, NBT-NS, and MDNS poisoning and WPAD rogue server attacks.
- **Usage**: Command-line interface for sniffing and poisoning network traffic.
- **Documentation**: [Responder Documentation](https://github.com/lgandx/Responder)

## 11. PowerSploit

- **Description**: A collection of Microsoft PowerShell modules that can be used to aid penetration testers during all phases of an assessment.
- **Usage**: Import modules into PowerShell and execute various attack techniques.
- **Documentation**: [PowerSploit Documentation](https://github.com/PowerShellMafia/PowerSploit)

## 12. RouterSploit

- **Description**: A framework for exploiting embedded devices such as routers, cameras, and IoT devices.
- **Usage**: Command-line interface for scanning and exploiting vulnerabilities in embedded devices.
- **Documentation**: [RouterSploit Documentation](https://github.com/threat9/routersploit)

## 13. EternalBlue

- **Description**: An exploit developed by the NSA, which targets a vulnerability in Microsoft's SMBv1 protocol.
- **Usage**: Included in Metasploit and other exploitation frameworks for launching attacks against vulnerable systems.
- **Documentation**: [EternalBlue Exploit Documentation](https://www.rapid7.com/db/modules/exploit/windows/smb/ms17_010_eternalblue)

## 09 - Sniffing & Spoofing

## Introduction

Sniffing and spoofing are common techniques used in cybersecurity for network analysis, monitoring, and manipulation. Sniffing involves intercepting and logging network traffic, while spoofing involves impersonating other devices or users on a network. Kali Linux provides a variety of tools for sniffing and spoofing that are essential for security professionals, penetration testers, and network administrators.

This documentation provides an overview of the sniffing and spoofing tools available in Kali Linux, along with their descriptions and usage instructions.

## Table of Contents

1. [Wireshark](#wireshark)
2. [Ettercap](#ettercap)
3. [Tcpdump](#tcpdump)
4. [Scapy](#scapy)
5. [dsniff](#dsniff)
6. [Bettercap](#bettercap)

## 1. Wireshark

- **Description**: Wireshark is a popular network protocol analyzer used for capturing and analyzing network traffic in real-time.
- **Usage**: Launch Wireshark from the terminal or graphical interface.
- **Documentation**: [Wireshark Documentation](https://www.wireshark.org/docs/)

## 2. Ettercap

- **Description**: Ettercap is a comprehensive suite for man-in-the-middle attacks on LAN. It supports active and passive dissection of many protocols.
- **Usage**: Run `ettercap -G` for graphical mode or `ettercap [options]` for command-line mode.
- **Documentation**: [Ettercap Documentation](https://www.ettercap-project.org/docs.html)

## 3. Tcpdump

- **Description**: Tcpdump is a command-line packet analyzer. It allows the user to display TCP/IP and other packets being transmitted or received over a network.
- **Usage**: `tcpdump [options]`
- **Documentation**: [Tcpdump Manpage](https://www.tcpdump.org/manpages/tcpdump.1.html)

## 4. Scapy

- **Description**: Scapy is a powerful interactive packet manipulation program and library.
- **Usage**: Use Scapy's interactive shell or in scripts to craft and send packets.
- **Documentation**: [Scapy Documentation](https://scapy.readthedocs.io/en/latest/)

## 5. dsniff

- **Description**: dsniff is a collection of tools for network auditing and penetration testing. It includes various sniffing and spoofing tools like arpspoof, dnsspoof, etc.
- **Usage**: Various commands like `arpspoof`, `dnsspoof`, etc.
- **Documentation**: [dsniff Documentation](https://www.monkey.org/~dugsong/dsniff/)

## 6. Bettercap

- **Description**: Bettercap is a powerful, flexible, and portable tool created to perform various types of Man-In-The-Middle attacks against a network.
- **Usage**: Run `bettercap` to start Bettercap.
- **Documentation**: [Bettercap Documentation](https://www.bettercap.org/docs/)

## 10 - Post Exploitation

## Introduction

Post exploitation refers to the phase of a penetration test or cyber attack where an attacker gains access to a system or network and then proceeds to maintain control, gather information, escalate privileges, and perform various malicious activities. Kali Linux provides a range of post exploitation tools to assist security professionals, penetration testers, and ethical hackers in understanding and mitigating post exploitation threats.

## Table of Contents

1. [Meterpreter](#meterpreter)
2. [Empire](#empire)
3. [PowerSploit](#powersploit)
4. [Mimikatz](#mimikatz)
5. [PowerUp](#powerup)
6. [Pupy](#pupy)
7. [Veil](#veil)
8. [Backdoor-Factory](#backdoor-factory)
9. [Weevely](#weevely)
10. [Windows Exploit Suggester](#windows-exploit-suggester)
11. [Chisel](#chisel)

## 1. Meterpreter

- **Description**: Meterpreter is an advanced, dynamically extensible payload that operates over TCP/IP sockets or HTTP. It provides a command line from which you can perform many tasks on the compromised host.
- **Usage**: Meterpreter is part of the Metasploit Framework and can be accessed after successful exploitation of a system using Metasploit.
- **Documentation**: [Meterpreter Documentation](https://www.offensive-security.com/metasploit-unleashed/meterpreter-basics/)

## 2. Empire

- **Description**: Empire is a pure PowerShell post-exploitation agent built on cryptologically-secure communications and a flexible architecture. Empire allows you to run PowerShell agents without needing PowerShell on the system.
- **Usage**: Launch via command line or web interface.
- **Documentation**: [Empire Documentation](https://github.com/EmpireProject/Empire)

## 3. PowerSploit

- **Description**: PowerSploit is a collection of Microsoft PowerShell modules that can help attackers perform reconnaissance and post-exploitation activities.
- **Usage**: Import modules into PowerShell or execute scripts directly.
- **Documentation**: [PowerSploit GitHub Repository](https://github.com/PowerShellMafia/PowerSploit)

## 4. Mimikatz

- **Description**: Mimikatz is a tool that can extract plaintext passwords, hash dumps, and Kerberos tickets from memory or disk, as well as perform pass-the-hash, pass-the-ticket, and overpass-the-hash attacks.
- **Usage**: Execute the Mimikatz binary or use the Mimikatz module in Meterpreter.
- **Documentation**: [Mimikatz GitHub Repository](https://github.com/gentilkiwi/mimikatz)

## 5. PowerUp

- **Description**: PowerUp is a PowerShell tool designed to automate the discovery of common Windows privilege escalation vectors.
- **Usage**: Import the PowerUp module into PowerShell and run various commands.
- **Documentation**: [PowerUp GitHub Repository](https://github.com/PowerShellEmpire/PowerTools/tree/master/PowerUp)

## 6. Pupy

- **Description**: Pupy is an open-source, cross-platform (Windows, Linux, OSX, Android) remote administration and post-exploitation tool mainly written in Python.
- **Usage**: Deploy agents on target systems and interact with them using the Pupy shell.
- **Documentation**: [Pupy GitHub Repository](https://github.com/n1nj4sec/pupy)

## 7. Veil

- **Description**: Veil is a post-exploitation framework that integrates with Metasploit and enables generation of undetectable payload executables through obfuscation and evasion techniques.
- **Usage**: Generate payloads using the Veil-Evasion tool.
- **Documentation**: [Veil GitHub Repository](https://github.com/Veil-Framework/Veil)

## 8. Backdoor-Factory

- **Description**: Backdoor-Factory is a tool for generating various types of shellcode backdoors to manipulate and patch PE, ELF, Mach-O binaries.
- **Usage**: Run the backdoor-factory script with appropriate parameters.
- **Documentation**: [Backdoor-Factory GitHub Repository](https://github.com/secretsquirrel/the-backdoor-factory)

## 9. Weevely

- **Description**: Weevely is a web shell management tool that enables remote access to servers via webshell payloads.
- **Usage**: Generate webshell payloads and interact with compromised servers.
- **Documentation**: [Weevely GitHub Repository](https://github.com/epinna/weevely3)

## 10. Windows Exploit Suggester

- **Description**: Windows Exploit Suggester is a tool developed in Python and designed to identify potential vulnerabilities on a target Windows system.
- **Usage**: Run the Windows Exploit Suggester script with the appropriate input.
- **Documentation**: [Windows Exploit Suggester GitHub Repository](https://github.com/AonCyberLabs/Windows-Exploit-Suggester)

## 11. Chisel

- **Description**: Chisel is a fast TCP tunnel over HTTP that can be used for various purposes, including post-exploitation activities.
- **Usage**: Run Chisel with the appropriate parameters to establish a tunnel.
- **Documentation**: [Chisel GitHub Repository](https://github.com/jpillora/chisel)

## 11 - Forensics

## Introduction

Kali Linux provides a comprehensive suite of tools for digital forensics and incident response purposes. These tools are essential for analyzing and investigating security incidents, recovering data, and uncovering evidence in forensic investigations. This documentation aims to provide an overview of the forensic tools available in Kali Linux along with their descriptions and usage instructions.

## Table of Contents

1. [Autopsy](#autopsy)
2. [Volatility](#volatility)
3. [Foremost](#foremost)
4. [dd](#dd)
5. [Sleuth Kit](#sleuth-kit)
6. [Scalpel](#scalpel)
7. [Bulk Extractor](#bulk-extractor)
8. [Photorec](#photorec)
9. [Wireshark](#wireshark)
10. [Ghidra](#ghidra)

## 1. Autopsy

- **Description**: Autopsy is a graphical interface digital forensic tool used for analyzing hard drives and smartphones.
- **Usage**: Launch `autopsy` from the terminal.
- **Documentation**: [Autopsy User Guide](https://www.sleuthkit.org/autopsy/docs/user-docs/4.19.1/index.html)

## 2. Volatility

- **Description**: Volatility is a framework used to extract digital artifacts from volatile memory (RAM) samples.
- **Usage**: `volatility [command] [options]`
- **Documentation**: [Volatility Documentation](https://github.com/volatilityfoundation/volatility/wiki)

## 3. Foremost

- **Description**: Foremost is a digital forensics tool used for file recovery.
- **Usage**: `foremost [options]`
- **Documentation**: [Foremost README](https://github.com/korczis/foremost/blob/master/README.md)

## 4. dd

- **Description**: dd is a command-line utility for disk cloning and data recovery.
- **Usage**: `dd [options]`
- **Documentation**: [dd Man Page](https://man7.org/linux/man-pages/man1/dd.1.html)

## 5. Sleuth Kit

- **Description**: The Sleuth Kit (TSK) is a collection of command-line tools for digital investigation.
- **Usage**: Various tools such as `fsstat`, `fls`, `icat`.
- **Documentation**: [The Sleuth Kit Documentation](https://www.sleuthkit.org/sleuthkit/docs/)

## 6. Scalpel

- **Description**: Scalpel is a file carving tool used for data recovery.
- **Usage**: `scalpel [options]`
- **Documentation**: [Scalpel GitHub](https://github.com/sleuthkit/scalpel)

## 7. Bulk Extractor

- **Description**: Bulk Extractor is a digital forensics tool that extracts information from disk images.
- **Usage**: `bulk_extractor [options]`
- **Documentation**: [Bulk Extractor User Guide](https://github.com/simsong/bulk_extractor/wiki)

## 8. Photorec

- **Description**: Photorec is a file data recovery software designed to recover lost files including video, documents, and archives from hard disks, CD-ROMs, and lost pictures from digital camera memory.
- **Usage**: `photorec [options]`
- **Documentation**: [Photorec Documentation](https://www.cgsecurity.org/wiki/PhotoRec)

## 9. Wireshark

- **Description**: Wireshark is a network protocol analyzer used for network troubleshooting, analysis, software, and protocol development.
- **Usage**: Launch via command line or graphical interface.
- **Documentation**: [Wireshark User Guide](https://www.wireshark.org/docs/)

## 10. Ghidra

- **Description**: Ghidra is a software reverse engineering (SRE) framework developed by the NSA.
- **Usage**: Launch via command line or graphical interface.
- **Documentation**: [Ghidra Documentation](https://ghidra-sre.org/)

## 12 - Reporting Tools

## Introduction

Kali Linux is a powerful distribution widely used by security professionals and penetration testers for various cybersecurity assessments. In addition to its extensive collection of penetration testing tools, Kali Linux also includes several reporting tools. These reporting tools are essential for organizing, analyzing, and presenting the results of security assessments, making them valuable assets for professionals in the field.

This documentation provides an overview of the reporting tools available in Kali Linux, offering insights into their functionalities, usage, and links to further documentation.

## Table of Contents

1. [Dradis](#dradis)
2. [MagicTree](#magictree)
3. [Other Reporting Tools](#other-reporting-tools)

## 1. Dradis <a name="dradis"></a>

- **Description**: Dradis is a collaboration and reporting tool used to generate security reports. It allows security professionals to organize findings, evidence, and notes in a centralized location, facilitating team collaboration and report generation.
- **Usage**: Access Dradis via a web browser after starting the Dradis service.
- **Documentation**: [Dradis Documentation](https://dradisframework.com/ce/documentation/index.html)

## 2. MagicTree <a name="magictree"></a>

- **Description**: MagicTree is a penetration testing reporting tool that organizes and manages data collected during security assessments. It provides a graphical interface for visualizing and analyzing findings, facilitating the creation of comprehensive reports.
- **Usage**: Launch MagicTree from the terminal using the `magictree` command.
- **Documentation**: [MagicTree Documentation](https://www.paterva.com/web7/buy/magic-tree.php)

## 3. Other Reporting Tools <a name="other-reporting-tools"></a>

- **Description**: In addition to Dradis and MagicTree, Kali Linux includes various other reporting tools that can be used for specific purposes. These tools may include custom scripts, frameworks, or utilities designed to assist in generating and presenting security assessment reports.

## 13 - Social Engineering Tools

## Introduction

Social engineering is a technique used to manipulate individuals into divulging confidential information, performing actions, or compromising security measures. In cybersecurity, social engineering attacks often exploit human psychology rather than technical vulnerabilities. Kali Linux includes a variety of tools specifically designed for social engineering assessments, enabling security professionals to simulate and test the effectiveness of these attacks.

## Table of Contents

1. [Social Engineer Toolkit (SET)](#social-engineer-toolkit-set)
2. [BeEF (Browser Exploitation Framework)](#beef-browser-exploitation-framework)

## 1. Social Engineer Toolkit (SET)

- **Description**: The Social Engineer Toolkit (SET) is a framework used for various social engineering attacks, including phishing, credential harvesting, and payload delivery. It provides a user-friendly interface for crafting and executing attacks against targets.
  
- **Usage**: Launch SET by running `setoolkit` in the terminal.

- **Documentation**: [SET Documentation](https://github.com/trustedsec/social-engineer-toolkit)

## 2. BeEF (Browser Exploitation Framework)

- **Description**: BeEF is a powerful browser exploitation framework that focuses on client-side attacks. It allows security professionals to assess the security posture of web browsers by exploiting vulnerabilities in client-side scripts and plugins.
  
- **Usage**: After starting the BeEF service, access the web interface to interact with targeted web browsers.

- **Documentation**: [BeEF Documentation](https://beefproject.com/docs/)
 
## Summary Conclusion

Thorough documentation of Kali Linux applications serves as a cornerstone for empowering users with the knowledge and understanding needed to maximize the potential of their tools. By providing clear, concise, and comprehensive guidance, developers and contributors not only facilitate ease of use but also foster a vibrant community of learning and collaboration. Through continuous improvement and commitment to excellence in documentation, Kali Linux remains at the forefront of innovation in the realm of ethical hacking and cybersecurity, enabling users to navigate the complexities of the digital landscape with confidence and proficiency.


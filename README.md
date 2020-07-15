## Advanced Windows exploit development resources

Some resources, links, books, and papers related to mostly Windows Internals and anything Windows kernel related. Mostly talks and videos that I enjoyed watching. 

**⚠️ These are all resources that I have personally used and gone through**

## Really important resources

- [terminus project](http://terminus.rewolf.pl/terminus/)
- [React OS Win32k](https://reactos.org/wiki/Techwiki:Win32k)
- [Geoff Chappell - Kernel-Mode Windows](https://www.geoffchappell.com/studies/windows/km/index.htm)
- [HEVD Vulnerable driver](https://github.com/hacksysteam/HackSysExtremeVulnerableDriver)
- [FLARE Kernel Shellcode Loader](https://github.com/fireeye/flare-kscldr)
- [Vergilius - Undocumented kernel structures](https://www.vergiliusproject.com/)
- [Windows X86-64 System Call Table](https://j00ru.vexillium.org/syscalls/nt/64/)
- [Vulnerable Driver Megathread](https://www.unknowncheats.me/forum/anti-cheat-bypass/334557-vulnerable-driver-megathread.html)

## Must watch / read (if you could chose a few) - all time favorites

- [ ⭐ Kernel Mode Threats and Practical Defenses](https://www.youtube.com/watch?v=BBJgKuXzfwc)
- [ ⭐ Morten Schenk - Taking Windows 10 Kernel Exploitation to the next level](https://youtu.be/33Jr1wkaCmQ)
- [ ⭐ The Life & Death of Kernel Object Abuse](https://youtu.be/_u7d9kLdi0c)
- [ ⭐ Windows 10 Mitigation Improvements](https://youtu.be/gCu2GQd0GSE)

## Windows Rootkits

**Talks / video recordings**

- [11 part playlist -  Rootkits: What they are, and how to find them](https://www.youtube.com/watch?v=ewNo_poX7bA&list=PLF58FB7BCB20ED11A)
- [Hooking Nirvana](https://www.youtube.com/watch?v=pHyWyH804xE)
- [Alex Ionescu - Advancing the State of UEFI Bootkits](https://www.youtube.com/watch?v=dpG97TBR3Ys)
- [BlueHat v18 || Return of the kernel rootkit malware (on windows 10)](https://youtu.be/qVIxFfXpyNc)
- [Numchecker: A System Approach for Kernel Rootkit Detection](https://www.youtube.com/watch?v=TgMsMwsfoQ0)
- [DEF CON 26  - Ring 0 Ring 2 Rootkits Bypassing Defenses](https://www.youtube.com/watch?v=7AEMxaZhdLU)
- [Black Hat Windows 2001 - Kernel Mode Rootkits](https://www.youtube.com/watch?v=99Znv6tgYS0)
- [Black Hat Windows 2004 - DKOM (Direct Kernel Object Manipulation)](https://www.youtube.com/watch?v=1Ie20b5IGgY)
- [RTFM SigSegv1 - From corrupted memory dump to rootkit detection](https://www.youtube.com/watch?v=hlhM_q3ZHfQ)

**Articles / papers**

- [Dissecting Turla Rootkit Malware Using Dynamic Analysis](https://www.lastline.com/labsblog/dissecting-turla-rootkit-malware-using-dynamic-analysis/)
- [A quick insight into the Driver Signature Enforcement](https://j00ru.vexillium.org/2010/06/insight-into-the-driver-signature-enforcement/)
- [WINDOWS DRIVER SIGNING BYPASS BY DERUSB](http://www.sekoia.fr/blog/windows-driver-signing-bypass-by-derusbi/)
- [A Basic Windows DKOM Rootkit](https://blog.landhb.dev/posts/v9eRa/a-basic-windows-dkom-rootkit-pt-1/)
- [Manipulating ActiveProcessLinks to Hide Processes in Userland](https://ired.team/miscellaneous-reversing-forensics/windows-kernel/manipulating-activeprocesslinks-to-unlink-processes-in-userland)

## Windows kernel mitigations

**Talks / video recordings**

- [BlueHat v18 || Hardening hyper-v through offensive security research](https://www.youtube.com/watch?v=8RCH0vFxWT4)
- [BYPASS CONTROL FLOW GUARD COMPREHENSIVELY - this is cfg not kCFG](https://www.blackhat.com/docs/us-15/materials/us-15-Zhang-Bypass-Control-Flow-Guard-Comprehensively-wp.pdf)
- [BlueHat v18 || Mitigation Bypass: The Past, Present, and Future](https://www.youtube.com/watch?v=WsoFmN3oDw8)
- [Windows Offender Reverse Engineering Windows Defender's Antivirus Emulator](https://www.youtube.com/watch?v=LvW68czaEGs)
- [Windows 10 Mitigation Improvements (really good talk)](https://www.youtube.com/watch?v=gCu2GQd0GSE)
- [Overview of Windows 10 Requirements for TPM, HVCI and SecureBoot](https://www.youtube.com/watch?v=v149T7p4XLA)
- [Examining the Guardians of Windows 10 Security - Chuanda Ding](https://www.youtube.com/watch?v=a0AB76YNMlQ)
- [Analysis of the Attack Surface of Windows 10 Virtualization-Based Security](https://www.youtube.com/watch?v=_646Gmr_uo0)
- [A Dive in to Hyper-V Architecture & Vulnerabilities](https://www.youtube.com/watch?v=2bK_rC81_Eo)
- [the last kaslr leak](https://www.youtube.com/watch?v=PTnuwchEci0)
- [BlueHat v18 || A mitigation for kernel toctou vulnerabilities](https://www.youtube.com/watch?v=YGkhK55jitE)
- [REcon 2013 - I got 99 problems but a kernel pointer ain't one ](https://www.youtube.com/watch?v=5HbmpPBKVFg)
- [SMEP: What is it, and how to beat it on Windows](https://j00ru.vexillium.org/2011/06/smep-what-is-it-and-how-to-beat-it-on-windows/)
- [BlueHat IL 2020 - David Weston - Keeping Windows Secure](https://www.youtube.com/watch?v=NlfZG2wTPZU)
- [Advancing Windows Security — David Weston](https://www.youtube.com/watch?v=FJnGA4XRaq4)
- [OffensiveCon18 - The Evolution of CFI Attacks and Defenses](https://www.youtube.com/watch?v=oOqpl-2rMTw)

**Articles / papers**

**General mitigation papers**

- [Hardening Windows 10 with zero-day exploit mitigations](https://www.microsoft.com/security/blog/2017/01/13/hardening-windows-10-with-zero-day-exploit-mitigations/)
- [TAKING WINDOWS 10 KERNEL EXPLOITATION TO THE NEXT LEVEL](https://www.blackhat.com/docs/us-17/wednesday/us-17-Schenk-Taking-Windows-10-Kernel-Exploitation-To-The-Next-Level%E2%80%93Leveraging-Write-What-Where-Vulnerabilities-In-Creators-Update-wp.pdf)

**kASLR**

- [KASLR Bypass Mitigations in Windows 8.1](https://www.crowdstrike.com/blog/kaslr-bypass-mitigations-windows-81/)
- [Devlopment of a new Windows 10 KASLR bypass - in one winDBG command](https://www.offensive-security.com/vulndev/development-of-a-new-windows-10-kaslr-bypass-in-one-windbg-command/)

**SMEP**

- [Bypassing Intel SMEP on Windows 8 x64 Using Return-oriented Programming](http://blog.ptsecurity.com/2012/09/bypassing-intel-smep-on-windows-8-x64.html)
- [Return Oriented Programming Tutorial](https://rstforums.com/forum/topic/106553-rop-for-smep-bypass/)
- [Stack Buffer Overflow (SMEP Bypass)](https://www.abatchy.com/2018/01/kernel-exploitation-4)
- [Windows 10 x64 and Bypassing SMEP](https://connormcgarr.github.io/x64-Kernel-Shellcode-Revisited-and-SMEP-Bypass/)
- [SMEP: What is it, and how to beat it on Windows](https://j00ru.vexillium.org/2011/06/smep-what-is-it-and-how-to-beat-it-on-windows/)

**CET**

- [Security Analysis of Processor Instruction Set Architecture for Enforcing Control-Flow Integrity](https://dl.acm.org/doi/pdf/10.1145/3337167.3337175)
- [A Technical Look at Intel’s Control-flow Enforcement Technology](https://software.intel.com/content/www/us/en/develop/articles/technical-look-control-flow-enforcement-technology.html)
- [Control-flow Enforcement Technology Specification](https://software.intel.com/sites/default/files/managed/4d/2a/control-flow-enforcement-technology-preview.pdf)
- [Intel CET Answers Call to Protect Against Common Malware Threats](https://newsroom.intel.com/editorials/intel-cet-answers-call-protect-common-malware-threats/)
- [R.I.P ROP: CET Internals in Windows 20H1](https://windows-internals.com/cet-on-windows/)

## Windows kernel shellcode

**Articles / papers**

- [Loading Kernel Shellcode](https://www.fireeye.com/blog/threat-research/2018/04/loading-kernel-shellcode.html)
- [Windows Kernel Shellcodes - a compendium](https://www.matteomalvica.com/blog/2019/07/06/windows-kernel-shellcode/)
- [Windows Kernel Shellcode on Windows 10 – Part 1](https://improsec.com/tech-blog/windows-kernel-shellcode-on-windows-10-part-1)
- [Windows Kernel Shellcode on Windows 10 – Part 2](https://improsec.com/tech-blog/windows-kernel-shellcode-on-windows-10-part-2)
- [Windows Kernel Shellcode on Windows 10 – Part 3](https://improsec.com/tech-blog/windows-kernel-shellcode-on-windows-10-part-3)
- [Panic! At The Kernel - Token Stealing Payloads Revisited on Windows 10 x64 and Bypassing SMEP](https://connormcgarr.github.io/x64-Kernel-Shellcode-Revisited-and-SMEP-Bypass/)
- [Token Abuse for Privilege Escalation in Kernel](https://ired.team/miscellaneous-reversing-forensics/windows-kernel/how-kernel-exploits-abuse-tokens-for-privilege-escalation)
- [Introduction to Shellcode Development](https://owasp.org/www-pdf-archive/Introduction_to_shellcode_development.pdf)
- [Introduction to Windows shellcode development – Part 1](https://securitycafe.ro/2015/10/30/introduction-to-windows-shellcode-development-part1/)
- [DoublePulsar Initial SMB Backdoor Ring 0 Shellcode Analysis](https://zerosum0x0.blogspot.com/2017/04/doublepulsar-initial-smb-backdoor-ring.html)
- [Exploring Injected Threads](https://ired.team/miscellaneous-reversing-forensics/get-injectedthread#injecting-shellcode)

## Windows kernel exploitation

**Talks / video recordings**

- [HITB2016AMS - Kernel Exploit Hunting And Mitigation](https://www.youtube.com/watch?v=nvI6w8aW-4Q)
- [Ilja van Sprundel: Windows drivers attack surface](https://www.youtube.com/watch?v=qk-OI8Z-1To)
- [REcon 2015 - This Time Font hunt you down in 4 bytes](https://www.youtube.com/watch?v=uvy5BF1Nlio)
- [Exploiting a Windows 10 PagedPool off-by-one overflow (WCTF 2018)](https://j00ru.vexillium.org/2018/07/exploiting-a-windows-10-pagedpool-off-by-one/)
- [Windows kernel exploitation techniques - Adrien Garin - LSE Week 2016](https://www.youtube.com/watch?v=f8hTwFpRphU)
- [Hackingz Ze Komputerz - Exploiting CAPCOM.SYS - Part 1](https://www.youtube.com/watch?v=pJZjWXxUEl4)
- [Hackingz Ze Komputerz - Exploiting CAPCOM.SYS - Part 2](https://www.youtube.com/watch?v=UGWqq5kTiso)
- [The 3 Way06 Practical Windows Kernel Exploitation](https://www.youtube.com/watch?v=hUCmV7uT29I)
- [Reverse Engineering and Bug Hunting on KMDF Drivers](https://www.youtube.com/watch?v=puNkbSTQtXY)
- [Binary Exploit Mitigation and Bypass History - not just kernel ](https://vimeo.com/379935124) 
- [Morten Schenk - Taking Windows 10 Kernel Exploitation to the next level](https://www.youtube.com/watch?v=Gu_5kkErQ6Y)
- [REcon 2015 - Reverse Engineering Windows AFD.sys](https://www.youtube.com/watch?v=2sPNUpfTJ5A)
- [Windows Kernel Graphics Driver Attack Surface](https://www.youtube.com/watch?v=uzPTyXQ1Oys)
- [Understanding TOCTTOU in the Windows Kernel Font Scaler Engine](https://www.youtube.com/watch?v=61K3kqTRbzU)
- [Black Hat USA 2013 - Smashing The Font Scaler Engine in Windows Kernel](https://www.youtube.com/watch?v=efgoislKd8Q)

**Articles / papers**

- [Kernel Exploit Sample Hunting and Mining Contents](https://d3gpjj9d20n0p3.cloudfront.net/fortiguard/research/Kernel%20Exploit%20Hunting%20and%20Mitigation-WP.pdf)
- [The entire GreyHatHacker site has great writeups](https://www.greyhathacker.net/) 
- [BlueKeep: A Journey from DoS to RCE (CVE-2019-0708)](https://www.malwaretech.com/2019/09/bluekeep-a-journey-from-dos-to-rce-cve-2019-0708.html)
- [Exploiting SMBGhost (CVE-2020-0796) for a Local Privilege Escalation](https://blog.zecops.com/vulnerabilities/exploiting-smbghost-cve-2020-0796-for-a-local-privilege-escalation-writeup-and-poc/)
- [Windows Drivers are True’ly Tricky](https://googleprojectzero.blogspot.com/2015/10/windows-drivers-are-truely-tricky.html)
- [Taking apart a double zero-day sample discovered in joint hunt with ESET](https://www.microsoft.com/security/blog/2018/07/02/taking-apart-a-double-zero-day-sample-discovered-in-joint-hunt-with-eset/)
- [Sharks in the Pool :: Mixed Object Exploitation in the Windows Kernel Pool](https://srcincite.io/blog/2017/09/06/sharks-in-the-pool-mixed-object-exploitation-in-the-windows-kernel-pool.html)
- [Kernel Pool Overflow Exploitation in Real World: Windows 10](https://www.gatewatcher.com/en/news/blog/kernel-pool-overflow-exploitation-in-real-world-windows-10)
- [Kernel Pool Overflow Exploitation in Real World - Windows 7](https://www.gatewatcher.com/en/news/blog/kernel-pool-overflow-exploitation-in-real-world-windows-7)
- [Kernel Pool Exploitation on Windows 7](https://www.exploit-db.com/docs/english/16032-kernel-pool-exploitation-on-windows-7.pdf)
- [Easy local Windows Kernel exploitation](https://media.blackhat.com/bh-us-12/Briefings/Cerrudo/BH_US_12_Cerrudo_Windows_Kernel_WP.pdf)
- [Exploiting CVE-2014-4113](https://labs.f-secure.com/assets/BlogFiles/mwri-lab-exploiting-cve-2014-4113.pdf)
- [Pwn2Own 2014 - AFD.sys Dangling Pointer Vulnerability](https://www.siberas.de/papers/Pwn2Own_2014_AFD.sys_privilege_escalation.pdf)
- [Symantec Endpoint protection 0day](https://www.offensive-security.com/vulndev/symantec-endpoint-protection-0day/)
- [Analysing the NULL SecurityDescriptor kernel exploitation mitigation in the latest Windows 10 v1607 Build 14393](https://labs.nettitude.com/blog/analysing-the-null-securitydescriptor-kernel-exploitation-mitigation-in-the-latest-windows-10-v1607-build-14393/)
- [nt!_SEP_TOKEN_PRIVILEGES - Single Write EoP Protect](https://www.exploit-db.com/docs/english/41924-nt!_sep_token_privileges---single-write-eop-protect.pdf)
- [Token Abuse for Privilege Escalation in Kernel](https://ired.team/miscellaneous-reversing-forensics/windows-kernel/how-kernel-exploits-abuse-tokens-for-privilege-escalation)

## Windows kernel GDI exploitation

**Talks / video recordings**

- [Abusing GDI for ring0 exploit primitives Evolution](https://www.youtube.com/watch?v=ruuVkTuNUSc)
- [Demystifying Windows Kernel Exploitation by Abusing GDI Objects](https://www.youtube.com/watch?v=2chDv_wTymc)
- [CommSec D1 - The Life & Death of Kernel Object Abuse](https://www.youtube.com/watch?v=_u7d9kLdi0c)
- [Kernel Object Abuse by Type Isolation](https://www.youtube.com/watch?v=kOV-Y9HcJWM)

**Articles / papers**

- [Turning CVE-2017-14961 into full arbitrary read / write with PALETTE objects](https://web.archive.org/web/20191220090640/http://theevilbit.blogspot.com/2017/11/turning-cve-2017-14961-ikarus-antivirus.html)
- [Zero-day exploit (CVE-2018-8453) used in targeted attacks](https://securelist.com/cve-2018-8453-used-in-targeted-attacks/88151/)
- [The zero-day exploits of Operation WizardOpium](https://securelist.com/the-zero-day-exploits-of-operation-wizardopium/97086/)
- [Windows 0-day exploit CVE-2019-1458 used in Operation WizardOpium](https://securelist.com/windows-0-day-exploit-cve-2019-1458-used-in-operation-wizardopium/95432/)
- [Abusing GDI Objects for ring0 Primitives Revolution](https://sensepost.com/blog/2017/abusing-gdi-objects-for-ring0-primitives-revolution/)
- [https://www.coresecurity.com/core-labs/articles/abusing-gdi-for-ring0-exploit-primitives](https://www.coresecurity.com/core-labs/articles/abusing-gdi-for-ring0-exploit-primitives)
- [A Tale Of Bitmaps: Leaking GDI Objects Post Windows 10 Anniversary Edition](https://labs.f-secure.com/archive/a-tale-of-bitmaps/)
- [CSW2017 Peng qiu shefang zhong win32k dark_composition](https://www.slideshare.net/CanSecWest/csw2017-peng-qiushefangzhong-win32k-darkcompositionfinnalfinnalrmmark)
- [Kernel Exploitation -> GDI Bitmap Abuse (Win7-10 32/64bit)](https://www.fuzzysecurity.com/tutorials/expDev/21.html)

## Windows kernel Win32k.sys research

**Talks / video recordings**

- [BlackHat 2011 - Kernel Attacks Through User-Mode Callbacks](https://www.youtube.com/watch?v=EkGDSqpfzgg)

**Articles / papers**

- [CVE-2020-1054 Analysis](https://0xeb-bp.github.io/blog/2020/06/15/cve-2020-1054-analysis.html)
- [TFW you-get-really-excited-you-patch-diffed-a-0day-used-in-the-wild-but-then-find-out-it-is-the-wrong-vuln](https://googleprojectzero.blogspot.com/2020/04/tfw-you-get-really-excited-you-patch.html)
- [One Bit To Rule A System: Analyzing CVE-2016-7255 Exploit In The Wild](https://blog.trendmicro.com/trendlabs-security-intelligence/one-bit-rule-system-analyzing-cve-2016-7255-exploit-wild/)
- [Reverse Engineering the Win32k Type Isolation Mitigation](https://blog.quarkslab.com/reverse-engineering-the-win32k-type-isolation-mitigation.html)
- [A new exploit for zero-day vulnerability CVE-2018-8589](https://securelist.com/a-new-exploit-for-zero-day-vulnerability-cve-2018-8589/88845/)
- [Detecting and mitigating elevation-of-privilege exploit for CVE-2017-0005](https://www.microsoft.com/security/blog/2017/03/27/detecting-and-mitigating-elevation-of-privilege-exploit-for-cve-2017-0005/)
- [Exploring CVE-2015-1701 — A Win32k Elevation of Privilege Vulnerability Used in Targeted Attacks
](https://blog.trendmicro.com/trendlabs-security-intelligence/exploring-cve-2015-1701-a-win32k-elevation-of-privilege-vulnerability-used-in-targeted-attacks/)
- [Exploiting the win32k!xxxEnableWndSBArrows use-after-free](https://www.nccgroup.trust/globalassets/our-research/uk/blog-post/2015-07-07_-_exploiting_cve_2015_0057.pdf)
- [New zero-day vulnerability CVE-2019-0859 in win32k.sys](https://securelist.com/new-win32k-zero-day-cve-2019-0859/90435/)
- [Windows zero‑day CVE‑2019‑1132 exploited in targeted attacks](https://www.welivesecurity.com/2019/07/10/windows-zero-day-cve-2019-1132-exploit/)
- [Windows Kernel Local Denial-of-Service #1: win32k!NtUserThunkedMenuItemInfo](https://j00ru.vexillium.org/2017/02/windows-kernel-local-denial-of-service-1/)
- [Windows Kernel Local Denial-of-Service #2: win32k!NtDCompositionBeginFrame](https://j00ru.vexillium.org/2017/02/windows-kernel-local-denial-of-service-2/)
- [Windows Kernel Local Denial-of-Service #4: nt!NtAccessCheck and family](https://j00ru.vexillium.org/2017/04/windows-kernel-local-denial-of-service-4/)
- [Windows Kernel Local Denial-of-Service #5: win32k!NtGdiGetDIBitsInternal](https://j00ru.vexillium.org/2017/04/windows-kernel-local-denial-of-service-5/)
- [Windows win32k.sys menus and some “close, but no cigar” bugs](https://j00ru.vexillium.org/2013/09/windows-win32k-sys-menus-and-some-close-but-no-cigar-bugs/)
- [Windows Kernel Internals - Win32K.sys](http://pasotech.altervista.org/windows_internals/Win32KSYS.pdf)

## Windows Kernel logic bugs

**Talks / video recordings**

- [Get Off the Kernel if You Can't Drive - DEF CON 27 Conference](https://www.youtube.com/watch?v=tzWq5iUiKKg)

**Articles / papers**

- [A vulnerable driver: lesson almost learned](https://securelist.com/elevation-of-privileges-in-namco-driver/83707/)
- [CVE-2020-12138 - Privilege Escalation in ATI Technologies Inc. Driver atillk64.sys](https://h0mbre.github.io/atillk64_exploit/)
- [CVE-2019-18845 - Viper RGB Driver Local Privilege Escalation](https://www.activecyber.us/activelabs/viper-rgb-driver-local-privilege-escalation-cve-2019-18845)
- [CVE-2020-8808 - CORSAIR iCUE Driver Local Privilege Escalation](https://www.activecyber.us/activelabs/corsair-icue-driver-local-privilege-escalation-cve-2020-8808)
- [Logic bugs in Razer rzpnk.sys](https://www.fuzzysecurity.com/tutorials/expDev/23.html)
- [Dell SupportAssist Driver - Local Privilege Escalation](http://dronesec.pw/blog/2018/05/17/dell-supportassist-local-privilege-escalation/)
- [MSI ntiolib.sys/winio.sys local privilege escalation](http://blog.rewolf.pl/blog/?p=1630)
- [CVE-2019-8372 - Local Privilege Elevation in LG Kernel Driver](http://www.jackson-t.ca/lg-driver-lpe.html)
- [Reading Physical Memory using Carbon Black's Endpoint driver](https://billdemirkapi.me/Reading-Physical-Memory-using-Carbon-Black/)
- [ASUS UEFI Update Driver Physical Memory Read/Write](https://codeinsecurity.wordpress.com/2016/06/12/asus-uefi-update-driver-physical-memory-readwrite/)
- [Privilege escalation vulnerabilities found in over 40 Windows Drivers](https://mspoweruser.com/privilege-escalation-vulnerabilities-found-in-over-40-windows-drivers/)
- [Blackat - KERNEL MODE THREATS AND PRACTICAL DEFENSES](https://i.blackhat.com/us-18/Thu-August-9/us-18-Desimone-Kernel-Mode-Threats-and-Practical-Defenses.pdf)
- [Weaponizing vulnerable driver for privilege escalation— Gigabyte Edition!](https://medium.com/@fsx30/weaponizing-vulnerable-driver-for-privilege-escalation-gigabyte-edition-e73ee523598b)

## Windows kernel driver development

**Talks / video recordings**

- [Windows Kernel Programming - 14 part playlist](https://youtu.be/XUlbYRFFYf0)
- [Windows Driver Development - 19 part playlist](https://youtu.be/T5VtaP-wtkk)
- [Developing Kernel Drivers with Modern C++ - Pavel Yosifovich](https://www.youtube.com/watch?v=AsSMKL5vaXw)

**Articles / papers**

- [Winsock Kernel Overview Topics](https://docs.microsoft.com/en-us/windows-hardware/drivers/network/introduction-to-winsock-kernel)
- [Driver Development Part 1: Introduction to Drivers](https://www.codeproject.com/Articles/9504/Driver-Development-Part-1-Introduction-to-Drivers)
- [Driver Development Part 2: Introduction to Implementing IOCTLs](https://www.codeproject.com/Articles/9575/Driver-Development-Part-2-Introduction-to-Implemen)
- [Driver Development Part 3: Introduction to driver contexts](https://www.codeproject.com/Articles/9636/Driver-Development-Part-3-Introduction-to-driver-c)
- [Driver Development Part 4: Introduction to device stacks](https://www.codeproject.com/Articles/9766/Driver-Development-Part-4-Introduction-to-device-s)
- [Creating IOCTL Requests in Drivers](https://docs.microsoft.com/en-us/windows-hardware/drivers/kernel/creating-ioctl-requests-in-drivers)
- [Windows Drivers Part 2: IOCTLs](https://cylus.org/windows-drivers-part-2-ioctls-c678526f90ae)
- [Sending Commands From Your Userland Program to Your Kernel Driver using IOCTL](https://ired.team/miscellaneous-reversing-forensics/windows-kernel/sending-commands-from-userland-to-your-kernel-driver-using-ioctl)

## Windows internals

**Talks / video recordings**

- [Pluralsight - Windows Internals 1](https://www.pluralsight.com/courses/windows-internals)
- [Pluralsight - Windows Internals 2](https://www.pluralsight.com/courses/windows-internals2)
- [Pluralsight - Windows Internals 3](https://www.pluralsight.com/courses/windows-internals-3)
- [Pluralsight - Windows 10 Internals: Systems and Processes](https://www.pluralsight.com/courses/windows-10-internals-threads-memory-security)
- [Pluralsight - Windows 10 Internals - Threads, Memory and Security](https://www.pluralsight.com/courses/windows-10-internals-system-processes)
- [Alex Ionescu Insection: AWEsomely Exploiting Shared Memory Objects](https://vimeo.com/133292423)
- [Windows Internals](https://www.youtube.com/watch?v=vz15OqiYYXo)
- [Windows 10 Segment Heap Internals](https://www.youtube.com/watch?v=hetZx78SQ_A)
- [Windows Kernel Vulnerability Research and Exploitation - Gilad Bakas](https://www.youtube.com/watch?v=aRZ5Wi-NWXs)
- [NIC 5th Anniversary - Windows 10 internals](https://youtu.be/ffYiIUOUAUs)
- [Black Hat USA 2012 - Windows 8 Heap Intervals](https://www.youtube.com/watch?v=XxlzK0CLFN0)

**Articles / papers**

- [Whitepaper - WINDOWS 10 SEGMENT HEAP INTERNALS](https://www.blackhat.com/docs/us-16/materials/us-16-Yason-Windows-10-Segment-Heap-Internals-wp.pdf)
- [The Quest for the SSDTs](https://www.codeproject.com/Articles/1191465/The-Quest-for-the-SSDTs)
- [System Service Descriptor Table - SSDT](https://ired.team/miscellaneous-reversing-forensics/windows-kernel/glimpse-into-ssdt-in-windows-x64-kernel)
- [Interrupt Descriptor Table - IDT](https://ired.team/miscellaneous-reversing-forensics/windows-kernel/interrupt-descriptor-table-idt)
- [Exploring Process Environment Block](https://ired.team/miscellaneous-reversing-forensics/exploring-process-environment-block)
- [Windows Pool Manager](https://www.osr.com/nt-insider/2014-issue1/windows-pool-manager/)
- [Parsing PE File Headers with C++](https://ired.team/miscellaneous-reversing-forensics/pe-file-header-parser-in-c++)
- [Digging Into Handles, Callbacks & ObjectTypes](https://rayanfam.com/topics/reversing-windows-internals-part1/)

## Advanced Windows debugging

**Talks / video recordings**

- [Hacking Livestream #28: Windows Kernel Debugging Part I](https://www.youtube.com/watch?v=s5gOW-N9AAo)
- [Hacking Livestream #29: Windows Kernel Debugging Part II](https://www.youtube.com/watch?v=4Xo_FAx6P0A)
- [Hacking Livestream #30: Windows Kernel Debugging Part III](https://www.youtube.com/watch?v=7zTtVYjjquA)
- [WinDbg Basics for Malware Analysis](https://www.youtube.com/watch?v=QuFJpH3My7A)
- [Windows Debugging and Troubleshooting](https://www.youtube.com/watch?v=2rGS5fYGtJ4) 
- [CNIT 126 10: Kernel Debugging with WinDbg](https://www.youtube.com/watch?v=8sVZsxoCpSc)
- [Windows Kernel Debugging Part I](https://www.youtube.com/watch?v=s5gOW-N9AAo)
- [Microsoft Patch Analysis for Exploitation](https://www.youtube.com/watch?v=xMMQnok44IY)
- [Windows Kernel Debugging Fundamentals](https://app.pluralsight.com/library/courses/windows-debugging-fundamentals)

**Articles / papers**

- [Debug Tutorial Part 1: Beginning Debugging Using CDB and NTSD](https://www.codeproject.com/Articles/6469/Debug-Tutorial-Part-1-Beginning-Debugging-Using-CD)
- [Debug Tutorial Part 2: The Stack](https://www.codeproject.com/Articles/6470/Debug-Tutorial-Part-2-The-Stack)
- [Debug Tutorial Part 3: The Heap](https://www.codeproject.com/Articles/6489/Debug-Tutorial-Part-3-The-Heap)
- [Debug Tutorial Part 4: Writing WINDBG Extensions](https://www.codeproject.com/Articles/6522/Debug-Tutorial-Part-4-Writing-WINDBG-Extensions)
- [Debug Tutorial Part 5: Handle Leaks](https://www.codeproject.com/Articles/6988/Debug-Tutorial-Part-5-Handle-Leaks)
- [Debug Tutorial Part 6: Navigating The Kernel Debugge](https://www.codeproject.com/Articles/7913/Debug-Tutorial-Part-6-Navigating-The-Kernel-Debugg)
- [Debug Tutorial Part 7: Locks and Synchronization Objects](https://www.codeproject.com/Articles/7919/Debug-Tutorial-Part-7-Locks-and-Synchronization-Ob)
- [Getting Started with WinDbg - kernelmode](https://docs.microsoft.com/en-us/windows-hardware/drivers/debugger/getting-started-with-windbg--kernel-mode-)
- [Windows Debuggers: Part 1: A WinDbg Tutorial](https://www.codeproject.com/Articles/6084/Windows-Debuggers-Part-1-A-WinDbg-Tutorial#_Toc64133674)

## 0days - APT advanced malware research

**Talks / video recordings**

- [W32.Duqu: The Precursor to the Next Stuxnet](https://www.youtube.com/watch?v=SbkXffokmPE)
- [Kernel Mode Threats and Practical Defenses](https://www.youtube.com/watch?v=BBJgKuXzfwc)
- [Selling 0-Days to Governments and Offensive Security Companies](https://www.youtube.com/watch?v=ZDHHGZlEfsQ)

**Articles / papers**

- [AcidBox: Rare Malware Repurposing Turla Group Exploit Targeted Russian Organizations](https://unit42.paloaltonetworks.com/acidbox-rare-malware/)
- [The zero-day exploits of Operation WizardOpium](https://securelist.com/the-zero-day-exploits-of-operation-wizardopium/97086/)
- [Zero-day exploit (CVE-2018-8453) used in targeted attacks](https://securelist.com/cve-2018-8453-used-in-targeted-attacks/88151/)
- [EternalBlue – Everything There Is To Know](https://research.checkpoint.com/2017/eternalblue-everything-know/)
- [Digging Into a Windows Kernel Privilege Escalation Vulnerability: CVE-2016-7255](https://www.mcafee.com/blogs/other-blogs/mcafee-labs/digging-windows-kernel-privilege-escalation-vulnerability-cve-2016-7255/)

## Video game cheating (kernel mode stuff sometimes)

**Talks / video recordings**

- [Unveiling the Underground World of Anti-Cheats](https://www.youtube.com/watch?v=yJHyHU5UjTg)

**Articles / papers**

- [drvmap - driver manual mapper using capcom](https://www.unknowncheats.me/forum/anti-cheat-bypass/252685-drvmap-driver-manual-mapper-using-capcom.html)
- [All methods of retrieving unique identifiers(HWIDs) on your PC](https://www.unknowncheats.me/forum/anti-cheat-bypass/333662-methods-retrieving-unique-identifiers-hwids-pc.html)
- [Driver aka Kernel Mode cheating](https://www.unknowncheats.me/forum/anti-cheat-bypass/271733-driver-aka-kernel-mode.html)

## Hyper-V and VM / sandbox escape 

**Talks / video recordings**

- [Vulnerability Exploitation In Docker Container Environments](https://www.youtube.com/watch?v=77-jaeUKH7c)
- [Modern Exploitation of the SVGA Device for Guest-to-Host Escapes](https://www.youtube.com/watch?v=Y-G2WJ2cBKE)
- [REcon 2014 - Breaking Out of VirtualBox through 3D Acceleration](https://www.youtube.com/watch?v=i29bAx6W1uI)
- [36C3 - The Great Escape of ESXi](https://www.youtube.com/watch?v=XHDwsvywX50)
- [BlueHat v18 || Straight outta VMware](https://www.youtube.com/watch?v=o36N5wi_ZFs)
- [Hardening hyper-v through offensive security research](https://www.youtube.com/watch?v=8RCH0vFxWT4)
- [A Driver in to Hyper v Architecture&Vulnerabilities](https://www.youtube.com/watch?v=p28eTnKo8sw)
- [The HyperV Architecture and its Memory Manager](https://recon.cx/media-archive/2017/mtl/recon2017-mtl-10-andrea-allievi-The-HyperV-Architecture-and-its-Memory-Manager.mp4)
- [Ring 0 to Ring -1 Exploitation with Hyper-V IPC](https://www.youtube.com/watch?v=_NaRZvrs8xY)
- [Exploiting the Hyper-V IDE Emulator to Escape the Virtual Machine](https://www.youtube.com/watch?v=50xxJEODO3M)
- [A Dive in to Hyper-V Architecture & Vulnerabilities](https://www.youtube.com/watch?v=2bK_rC81_Eo)

**Articles / papers**

- [Hyper-V memory internals. EXO partition memory access](https://hvinternals.blogspot.com/2020/06/hyper-v-memory-internals-exo-partition.html)
- [Ventures into Hyper-V - Fuzzing hypercalls](https://labs.f-secure.com/blog/ventures-into-hyper-v-part-1-fuzzing-hypercalls)
- [Fuzzing para-virtualized devices in Hyper-V](https://msrc-blog.microsoft.com/2019/01/28/fuzzing-para-virtualized-devices-in-hyper-v/)
- [First Steps in Hyper-V Research](https://msrc-blog.microsoft.com/2018/12/10/first-steps-in-hyper-v-research/)
- [Windows Sandbox Attack Surface Analysis](https://googleprojectzero.blogspot.com/2015/11/windows-sandbox-attack-surface-analysis.html)

## Fuzzing

**Talks / video recordings**

- [HITBGSEC 2016 - Fuzzing The Windows Kernel](https://www.youtube.com/watch?v=X3YlDHTL5mA)
- [Windows Kernel Vulnerability Research and Exploitation](https://www.youtube.com/watch?v=aRZ5Wi-NWXs)
- [Bugs on the Windshield: Fuzzing the Windows Kernel](https://www.youtube.com/watch?v=-BkjkimINC8)
- [Windows Kernel Fuzzing for Intermediate Learners ](https://www.youtube.com/watch?v=wnNyPcerjJo)
- [Windows Kernel Fuzzing For Beginners - Ben Nagy](https://www.youtube.com/watch?v=FY-33TUKlqY)
- [Disobey 2018 - Building Windows Kernel fuzzer ](https://www.youtube.com/watch?v=mpXQvto4Vy4)
- [For The Win: The Art Of The Windows Kernel Fuzzing ](https://www.youtube.com/watch?v=9FPuKfwucsw)
- [RECON 2019 - Vectorized Emulation Putting it all together](https://www.youtube.com/watch?v=x4LPhwbTs9E)

**Articles / papers**

- [A year of Windows kernel font fuzzing #1: the results](https://googleprojectzero.blogspot.com/2016/06/a-year-of-windows-kernel-font-fuzzing-1_27.html)
- [A year of Windows kernel font fuzzing #2: the techniques](https://googleprojectzero.blogspot.com/2016/07/a-year-of-windows-kernel-font-fuzzing-2.html)

## Windows browser exploitation

**Talks / video recordings**

- [Digging for IE11 Sandbox Escapes Part 1](https://www.youtube.com/watch?v=q9dnYno_Moc)

## Favorite books of mine

- Windows Internals, Part 1 (Pavel Yosifovich, and some others)
- Windows 10 System Programming, Part 1 (Pavel Yosifovich)
- Windows 10 System Programming, Part 2 (Pavel Yosifovich)
- Windows Kernel Programming (Pavel Yosifovich)
- Rootkits: Subverting the Windows Kernel 
- The Rootkit Arsenal
- Intel® 64 and IA-32 Architectures Software Developer Manuals

## Related certifications and courses

**Courses**
- Advanced Windows Exploitation (AWE)
- Sans 660
- Sans 760
- Corelan "Bootcamp" training
- Corelan "Advanced" training

**Certifications**
- Offensive Security Exploitation Expert (OSEE)
- Giac GXPN

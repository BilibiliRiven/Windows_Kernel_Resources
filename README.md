# Windows_Kernel_Resources

> 在学习Windows kernel时搜集到的资源列表

## Learn Windows

### Books

- 《寒江独钓——Windows内核安全编程》
- 《天书夜读——从汇编语言到Windows内核编程》
- 《Windows内核情景分析》上下册
- 《Windows驱动开发技术详解》
- 《深入解析Windows操作系统(第6版)》上下册

### Source Code

- 【The Windows Research Kernel AKA WRK】
  - [download](https://github.com/zhuhuibeishadiao/ntoskrnl)
- 【ReactOS：A free Windows-compatible Operating System】
  - [download](https://github.com/reactos/reactos)

### Windows iso

- https://msdn.itellyou.cn/
- https://next.itellyou.cn/
- https://en.wikipedia.org/wiki/Windows_10_version_history：Win10版本关系



### Windows Design

- 【Windows结构设计】
  - [中文博客](https://r00tk1ts.github.io/2017/12/19/Windows%E6%9E%B6%E6%9E%84%E8%AE%BE%E8%AE%A1/)

### Windows Structure

- 【terminus】：很好的Windows结构搜索网页
  - [page link](http://terminus.rewolf.pl/terminus/)
- 【关键的windows内核数据结构一览(上)】
  - [中文博客](https://r00tk1ts.github.io/2018/01/08/%E5%85%B3%E9%94%AE%E7%9A%84Windows%E5%86%85%E6%A0%B8%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84%E4%B8%80%E8%A7%88%EF%BC%88%E4%B8%8A%EF%BC%89/)
- 【关键的windows内核数据结构一览(下)】
  - [中文博客](https://r00tk1ts.github.io/2018/01/14/%E5%85%B3%E9%94%AE%E7%9A%84Windows%E5%86%85%E6%A0%B8%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84%E4%B8%80%E8%A7%88%EF%BC%88%E4%B8%8B%EF%BC%89/)
- 【Catalog of key Windows kernel data structures】
  - [English Blog](https://codemachine.com/articles/kernel_structures.html)
- 【Object】
  - [object categories](https://docs.microsoft.com/zh-cn/windows/win32/sysinfo/object-categories)
  - [user Object](https://docs.microsoft.com/zh-cn/windows/win32/sysinfo/user-objects)
  - [gdi Object](https://docs.microsoft.com/zh-cn/windows/win32/sysinfo/gdi-objects)
  - [kernel Object](https://docs.microsoft.com/zh-cn/windows/win32/sysinfo/kernel-objects?redirectedfrom=MSDN)
  - [Windows Object Header](https://codemachine.com/articles/object_headers.html)



## Windows Kernel Exploit

### KB and Patch

- https://msrc.microsoft.com/update-guide/：官方KB对应补丁信息
- https://bugs.hacking8.com/tiquan/：根据KB补丁号或者systeminfo查找对应的exp
- 【Extracting and Diffing Windows Patches in 2020】： 通过Windows更新提取和分析补丁（含代码）
  -  [English Blog](https://wumb0.in/extracting-and-diffing-ms-patches-in-2020.html)

### Tools & Docs

- 【Windbg】：windows kernel调试工具
  - [download](https://docs.microsoft.com/zh-cn/windows-hardware/drivers/debugger/debugger-download-tools)
  - [getting-started-with-windows-debugging](https://docs.microsoft.com/en-us/windows-hardware/drivers/debugger/getting-started-with-windows-debugging)
  - [Getting Started with WinDbg (User-Mode)](https://docs.microsoft.com/en-us/windows-hardware/drivers/debugger/getting-started-with-windbg)
  - [Getting Started with WinDbg (Kernel-Mode)](https://docs.microsoft.com/en-us/windows-hardware/drivers/debugger/getting-started-with-windbg--kernel-mode-)
  - [my-personal-cheat-sheet-for-using-windbg-for-kernel-debugging](https://laptrinhx.com/my-personal-cheat-sheet-for-using-windbg-for-kernel-debugging-1997973673/)
  - [Windbg加载用户层、内核层pdb文件](https://blog.csdn.net/forchoosen/article/details/107441660)
- 【Windbg Preview】：windows kernel调试工具(美观)
  - [download](https://www.microsoft.com/en-us/p/windbg-preview/)
  - [Debugging Using WinDbg Preview](https://docs.microsoft.com/en-us/windows-hardware/drivers/debugger/debugging-using-windbg-preview)
- 【dbgview】：windows调试工具，捕获调试信息，用于Guest
  - [download](https://docs.microsoft.com/en-us/sysinternals/downloads/debugview)
  - [Document help DebugView](https://documentation.help/DebugView/)
  - [Using DbgView To Capture Debug Traces From An Application](http://nutsaboutnets.com/faqs/dbgview/)
  - [Using DebugView to see debug output in real-time](https://tedgustaf.com/blog/2011/use-debugview-to-view-debug-output-from-asp-net-web-application/)
- 【OSRLoader】：驱动管理工具（安装，启动，暂停，卸载）
  - [download](https://www.osronline.com/article.cfm%5earticle=157.htm)
- 【VirtualKD】：双机调试工具，较老，不支持最新版VMWare
  - [download](https://sysprogs.com/legacy/virtualkd/)
- 【VirtualKD-Redux】：双机调试工具，支持最新版本VMWare
  - [download](https://github.com/4d61726b/VirtualKD-Redux)
- 【accesschk】
  - [download](https://docs.microsoft.com/en-us/sysinternals/downloads/accesschk)
- 【oleview】
  - [download](https://github.com/tyranid/oleviewdotnet)
- 【process monitor】
  - [download](https://docs.microsoft.com/en-us/sysinternals/downloads/procmon)
- 【Windows-Kernel-Explorer】
  - [download](https://github.com/AxtMueller/Windows-Kernel-Explorer/)
- 【sandbox-attacksurface-analysis-tools】
  - [download](https://github.com/googleprojectzero/sandbox-attacksurface-analysis-tools)
- 【SystemExplorer】
  - [download](https://github.com/zodiacon/SystemExplorer)
- 【ProcessHacker】
  - [download](https://processhacker.sourceforge.io/downloads.php)
- 【drmemory】
  - [download](https://github.com/DynamoRIO/drmemory)
- 【openark】：一款Windows平台上的开源Ark工具. Ark是Anti-Rootkit（对抗恶意程序）的简写, OpenArk目标成为逆向工程师、编程人员的工具，同时也能为那些希望清理恶意软件的用户服务
  - [download](https://github.com/BlackINT3/OpenArk)

- 【FourEye】：exe、shellcode免杀
  - [download](https://github.com/lengjibo/FourEye)



### Blogs && Talks && Workstation

- 【Windows 提权总结】
  - [中文博客](https://www.cnblogs.com/-mo-/p/12718115.html) 
- 【Level Up! Practical Windows Privilege Escalation - Andrew Smith】
  - [Youtube](https://www.youtube.com/watch?v=PC_iMqiuIRQ)
- 【I Got 99 Problem But a Kernel Pointer Ain’t One】
  - [English pdf](https://recon.cx/2013/slides/Recon2013-Alex%20Ionescu-I%20got%2099%20problems%20but%20a%20kernel%20pointer%20ain't%20one.pdf)
- 【The Life And Death of Kernel Object Abuse】
  - [English pdf](https://conference.hitb.org/hitbsecconf2018ams/materials/D1%20COMMSEC%20-%20Saif%20Elsherei%20and%20Ian%20Kronquist%20-%20The%20Life%20&%20Death%20of%20Kernel%20Object%20Abuse.pdf)
- 【A Window into Ring0】
  - [English pdf](https://labs.f-secure.com/assets/BlogFiles/mwri-steelcon-2017-samdb-a-window-into-ring0.pdf)
- 【Taking-Windows-10-Kernel-Exploitation-To-The-Next-Level–Leveraging-Write-What-Where-Vulnerabilities-In-Creators-Update-wp】
  - [English pdf](https://www.blackhat.com/docs/us-17/wednesday/us-17-Schenk-Taking-Windows-10-Kernel-Exploitation-To-The-Next-Level%E2%80%93Leveraging-Write-What-Where-Vulnerabilities-In-Creators-Update-wp.pdf)
  - [中文 pdf](https://bbs.pediy.com/thread-227102.htm)
- 【Easy local Windows Kernel exploitation】
  - [English pdf](https://paper.bobylive.com/Meeting_Papers/BlackHat/USA-2012/BH_US_12_Cerrudo_Windows_Kernel_WP.pdf)

## Learn Exploit

### HEVD

- 【HackSysExtremeVulnerableDriver】：windows内核利用技术学习项目
  - [download](https://github.com/hacksysteam/HackSysExtremeVulnerableDriver)
- 【HEVD StackOverflow】：
  - [HEVD内核漏洞之栈溢出](https://bbs.pediy.com/thread-252775.htm)
  - [HEVD栈溢出](https://50u1w4y.github.io/site/HEVD/stackoverflow/)
  - [Windows Kernel Exploitation Tutorial Part 2: Stack Overflow](https://rootkits.xyz/blog/2017/08/kernel-stack-overflow/)
- 【HEVD ArbitraryWrite】：
  - [HEVD内核漏洞之任意地址覆盖](https://bbs.pediy.com/thread-253848.htm)
  - [HEVD 任意地址覆盖](https://50u1w4y.github.io/site/HEVD/arbitraryWrite/)
  - [Windows Kernel Exploit 内核漏洞学习(3)-任意内存覆盖漏洞](https://bbs.pediy.com/thread-252506.htm)
  - [Windows Kernel Exploitation Tutorial Part 3: Arbitrary Memory Overwrite (Write-What-Where)](https://rootkits.xyz/blog/2017/09/kernel-write-what-where/)
- 【HEVD ArbitrayWrite BitMap】:
  - [bitmap 任意地址写漏洞利用](https://50u1w4y.github.io/site/HEVD/bitmap)
  - [Windows Kernel Exploit Part 5](https://paper.seebug.org/876/)
- 【Writeup综合】
  - [www漏洞从win7-win10](https://thunderjie.github.io/2019/08/19/www%E6%BC%8F%E6%B4%9E%E4%BB%8Ewin7-win10/)
  - [thunderjie 的 writeup](https://thunderjie.github.io/2019/06/28/Windows-Kernel-Exploit/)
  - [50u1w4y 的 writeup](https://50u1w4y.github.io/site/HEVD/homePage/)
  - [Saturn35 的 writeup](https://bbs.pediy.com/user-831334.htm)
  - [rootkit 的 writeup](https://rootkits.xyz/blog/)
  - [Thunder J 的 writeup](https://bbs.pediy.com/user-home-825245.htm)
  - [fuzzing security 的 writeup](https://www.fuzzysecurity.com/tutorials.html)
- 【Exp综合】
  - https://github.com/h0mbre/Windows-Exploits/tree/162dfd45d284556b47739835116a962177b243b0/Exploit-Code/HEVD
  - https://github.com/GradiusX/HEVD-Python-Solutions
  - https://github.com/dhn/OSEE/tree/master/Kernel_Exploitation/HEVD
  - https://github.com/ThunderJie/Windows-Kernel-Exploit

### Token Abuse

- 【windows-privilege-abuse-auditing-detection-and-defense】：windows token利用
  - [English Blog](https://medium.com/palantir/windows-privilege-abuse-auditing-detection-and-defense-3078a403d74e)

### GDI Abuse

#### BitMap  RS1(v1607)前

- 【Windows GDI BitMap】
  - [中文博客](https://kernel32.org/posts/windows-gdi-bitmap/)
  - [English Blog](https://www.fuzzysecurity.com/tutorials/expDev/21.html)
- 【Bitmap轶事：Windows 10纪念版后的GDI对象泄露】
  - [中文博客](https://r00tk1ts.github.io/2018/03/21/Bitmaps%E8%BD%B6%E4%BA%8B%EF%BC%9AWindows%2010%E7%BA%AA%E5%BF%B5%E7%89%88%E5%89%8D%E7%9A%84GDI%E5%AF%B9%E8%B1%A1%E6%B3%84%E9%9C%B2/) 
  - [English Blog](https://labs.mwrinfosecurity.com/blog/a-tale-of-bitmaps/)
- 【Abusing GDI objects: Bitmap object’s size in the kernel pool】
  - [English Blog](http://theevilbit.blogspot.com/2017/10/abusing-gdi-objects-bitmap-objects-size.html)

- 【ring0层exp原语之滥用GDI】
  - [中文博客](https://r00tk1ts.github.io/2018/01/15/ring0%E5%B1%82exp%E5%8E%9F%E8%AF%AD%E4%B9%8B%E6%BB%A5%E7%94%A8GDI/)

#### Accelerator Table RS1(v1607)

- 【RS1 下 bitmap 的替代方法】
  - [中文博客](https://50u1w4y.github.io/site/HEVD/bitmapReplace_RS1/)
- 【Windows10 v1607内核提权技术的发展——利用AcceleratorTable】
  - [中文博客](https://www.anquanke.com/post/id/168356)

#### HMValidateHandle RS2(v1703)

- 【Windows10 v1703基于桌面堆泄露的内核提权技术】
  - [中文博客](https://www.anquanke.com/post/id/168441)



#### Palette RS3 (v1709)

- 【Windows10 v1709特权提升：GDI Palette滥用】
  - [中文博客](https://www.anquanke.com/post/id/168572)



#### Others

- 【GDI魔术:漏洞利用中的利器】
  - [中文pdf](http://www.vxjump.net/files/seccon/exp-in-gdi.pdf)
- 【Abusing GDI for ring0 exploit primitives:Reloaded】
  - [English pdf](https://www.coresecurity.com/sites/default/files/private-files/publications/2016/10/Abusing-GDI-Reloaded-ekoparty-2016_0.pdf)
- 【Abusing GDI for ring0 exploit primitives: Evolution】
  - [English Blog](https://labs.bluefrostsecurity.de/files/Abusing_GDI_for_ring0_exploit_primitives_Evolution_Slides.pdf)
- 【滥用GDI对象】
  - [中文博客](https://saturn35.com/2019/07/25/20190725-1/)
- 【www漏洞从win7-win10】
  - [中文博客](https://thunderjie.github.io/2019/08/19/www%E6%BC%8F%E6%B4%9E%E4%BB%8Ewin7-win10/)



### Pool

- 【Windows内核池喷射的乐趣】
  - [中文博客](https://www.anquanke.com/post/id/86896)
  - [English Blog](https://theevilbit.blogspot.com/2017/09/pool-spraying-fun-part-1.html)
- 【Windows kernel pool spraying fun - Part 1 - Determine kernel object size】
  - [English Blog](https://theevilbit.blogspot.com/2017/09/pool-spraying-fun-part-1.html)
- 【Windows kernel pool spraying fun - Part 2 - More objects】
  - [English Blog](https://theevilbit.blogspot.com/2017/09/windows-kernel-pool-spraying-fun-part-2.html)
- 【Windows kernel pool spraying fun - Part 3 - Let's make holes】
  - [English Blog](https://theevilbit.blogspot.com/2017/09/windows-kernel-pool-spraying-fun-part-3.html)
- 【Windows kernel pool spraying fun - Part 4 - object & pool headers, kex & putting it all together】
  - [English Blog](https://theevilbit.blogspot.com/2017/09/windows-kernel-pool-spraying-fun-part-4.html)
- 【Kernel Pool Exploitation on Windows 7】
  - [English paper](https://www.exploit-db.com/docs/english/16032-kernel-pool-exploitation-on-windows-7.pdf)

### Kernel Address Leaks

- 【Windows Kernel Address Leaks】
  - [Code](https://github.com/sam-b/windows_kernel_address_leaks)


### Potato

- 【Potato家族本地提权细节】
  - [中文博客](https://xz.aliyun.com/t/7776)

### 利用历史

- 【猫鼠游戏：Windows内核提权样本狩猎思路分享】
  - [中文博客](https://www.anquanke.com/post/id/235716)

### 保护绕过

- 【SMEP和SMAP绕过】
  - [中文博客](https://bbs.pediy.com/thread-261744.htm)
- 【Windows 10 x64上令牌窃取有效载荷问题，并绕过SMEP 上】
  - [中文博客](https://www.4hou.com/posts/21y1)
- 【Windows 10 x64上令牌窃取有效载荷问题，并绕过SMEP 下】
  - [中文博客](https://www.4hou.com/posts/4YAV)
- 【Windows SMEP Bypass U=S】
  - [English pdf](https://www.coresecurity.com/sites/default/files/2020-06/Windows%20SMEP%20bypass%20U%20equals%20S_0.pdf)

## CVE and Exploits

- https://github.com/SecWiki/windows-kernel-exploits
- https://github.com/nu11secur1ty/Windows10Exploits
- https://github.com/abatchy17/WindowsExploits
- https://github.com/Ascotbe/Kernelhub
- https://github.com/WindowsExploits/Exploits
- https://github.com/Heptagrams/Heptagram/tree/master/Windows/Elevation
- https://github.com/Al1ex/WindowsElevation
- https://github.com/nomi-sec/PoC-in-GitHub

## Paper

- 【Abusing Token Privileges For EoP】：windows token 利用文章（含代码）
  - [Paper](https://github.com/hatRiot/token-priv/blob/master/abusing_token_eop_1.0.txt)
  - [Code](https://github.com/hatRiot/token-priv)
- 【Bugs on the Windshield: Fuzzing the Windows Kernel】：Windows kernel fuzz
  - [English Blog](https://research.checkpoint.com/2020/bugs-on-the-windshield-fuzzing-the-windows-kernel/)
  - [Paper](https://github.com/yoava333/presentations/blob/master/Fuzzing%20the%20Windows%20Kernel%20-%20OffensiveCon%202020.pdf)

- 【NTFUZZ: Enabling Type-Aware Kernel Fuzzing on Windows with Static Binary Analysis(S& P 2021)】：Windows kernel Fuzz



## Other Resources

- https://labs.f-secure.com
- https://3gstudent.github.io/3gstudent.github.io:有很多从渗透测试角度审视的Windows下提权方法
- https://github.com/3gstudent/Pentest-and-Development-Tips:列举了Windows下渗透测试的Tips
- https://r00tk1ts.github.io/tags/windows-kernel/
- https://guide.offsecnewbie.com: 见过的最全面的总结
- https://github.com/ExpLife0011/awesome-windows-kernel-security-development
- https://github.com/sam-b/windows_kernel_resources
- https://github.com/itm4n：itm4n大佬，有很多windows分析工具，博客里也有很多干货
- https://github.com/sailay1996/awesome_windows_logical_bugs
- https://github.com/topics/windows-privilege-escalation
- http://www.fuzzysecurity.com/tutorials/16.html

## 待整理

• [*Windows, Tools*] gtworek/Priv2Admin: [
https://github.com/gtworek/Priv2Admin](https://github.com/gtworek/Priv2Admin)

  ・ Priv2Admin：在 Windows 中利用漏洞提权。 – [potato](https://sec.today/user/dc071663-2f31-4d9f-928e-150b2cafeef3/pushes/)

• Windows Privileges: [
https://speakerdeck.com/fr0gger/windows-privileges](https://speakerdeck.com/fr0gger/windows-privileges)

  ・ 【图片】有关 Windows privileges 的备忘录。 – [potato](https://sec.today/user/dc071663-2f31-4d9f-928e-150b2cafeef3/pushes/)

https://wadcoms.github.io/

Attack Detection Fundamentals 2021: Windows - Lab #2: [
https://labs.f-secure.com/blog/attack-detection-fundamentals-2021-windows-lab-2/](https://labs.f-secure.com/blog/attack-detection-fundamentals-2021-windows-lab-2/)

  ・ Attack Detection Fundamentals 2021 Windows Lab #2 ：引入其它绕过防御的技术优化 payload。 – [potato](https://sec.today/user/dc071663-2f31-4d9f-928e-150b2cafeef3/pushes/)



• Attack Detection Fundamentals 2021: Windows - Lab #1: [
https://labs.f-secure.com/blog/attack-detection-fundamentals-2021-windows-lab-1/](https://labs.f-secure.com/blog/attack-detection-fundamentals-2021-windows-lab-1/)

  ・ Attack Detection Fundamentals 2021 Windows Lab #1：构建一个可以绕过最常见保护机制的原始 payload。 – [potato](https://sec.today/user/dc071663-2f31-4d9f-928e-150b2cafeef3/pushes/)



• Attack Detection Fundamentals 2021: Windows - Lab #3: [
https://labs.f-secure.com/blog/attack-detection-fundamentals-2021-windows-lab-3/](https://labs.f-secure.com/blog/attack-detection-fundamentals-2021-windows-lab-3/)

  ・ Attack Detection Fundamentals 2021 Windows Lab #3：借助 API HOOK 针对使用远程桌面连接的用户劫持纯文本凭据。 – [potato](https://sec.today/user/dc071663-2f31-4d9f-928e-150b2cafeef3/pushes/)



• Attack Detection Fundamentals 2021: Windows - Lab #4: [
https://labs.f-secure.com/blog/attack-detection-fundamentals-2021-windows-lab-4/](https://labs.f-secure.com/blog/attack-detection-fundamentals-2021-windows-lab-4/)

  ・ Attack Detection Fundamentals 2021 Windows Lab #4：窃取目标用户的 Chrome 浏览器中的 cookie，并探索如何检测这类可疑的劫持行为。 – [potato](https://sec.today/user/dc071663-2f31-4d9f-928e-150b2cafeef3/pushes/)



[*Windows*] Analysis of a Windows IPv6 Fragmentation Vulnerability: CVE-2021-24086: [
http://blog.quarkslab.com/analysis-of-a-windows-ipv6-fragmentation-vulnerability-cve-2021-24086.html](http://blog.quarkslab.com/analysis-of-a-windows-ipv6-fragmentation-vulnerability-cve-2021-24086.html)

  ・ CVE-2021-24086 漏洞原理分析。CVE-2021-24086 是 Windows IPv6 协议栈存在一处拒绝服务漏洞，远程攻击者可通过向存在此漏洞的系统发送特制数据包，导致目标系统拒绝服务（蓝屏）。 – [potato](https://sec.today/user/dc071663-2f31-4d9f-928e-150b2cafeef3/pushes/)

• Attack Surface Reduction: [
https://github.com/commial/experiments/tree/master/windows-defender/ASR](https://github.com/commial/experiments/tree/master/windows-defender/ASR)

  ・ 揭秘 Windows 减少攻击面（ASR：attack surface reduction）的细节。 – [potato](https://sec.today/user/dc071663-2f31-4d9f-928e-150b2cafeef3/pushes/)
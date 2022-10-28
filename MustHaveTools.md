# Kali linux (SO)

# Metasploitable (32bits for low mm use)

# Nmap Important!
          #-----------------------------#
          #         *Kali               #
          #   scripts -> nmap           #
          #   /usr/share/nmap/scripts   #
          #-----------------------------#
         
         
# Ngrok (like ddns but littlebit diferente)           

# links :
          https://linuxhint.com/top-25-best-kali-linux-tools/



# 1. Fluxion

          Wi-Fi is growing more popular each year, making it a more attractive target of opportunity for hackers. That's why pen testers must have the capacity to test Wi-Fi networks for security leaks.

          Fluxion is a Wi-Fi analyzer specializing in MITM WPA attacks and lets you scan wireless networks. Pen testers use Fluxion to search for security flaws in corporate and personal networks. However, unlike similar Wi-Fi cracking tools, Fluxion does not launch time-consuming brute force cracking attempts.

          Instead, Fluxion creates an MDK3 process that forces all users on the targeted network to lose authentication or deauthenticate. Once this is accomplished, the user is prompted to connect to a false access point, requiring entering the Wi-Fi password. Then, the program reports the password to the pen tester to gain access.
                 
# 2. John the Ripper

          John the Ripper gets points for a creative name. This hacker’s resource is a multi-platform cryptography testing tool that works equally well on Linux, Windows, macOS, and Unix. It enables system administrators and security penetration testers to test the strength of any system password by launching brute force attacks. Additionally, John the Ripper can be used to test encryptions like DES, SHA-1, and many others.

          Its ability to change password decryption methods is set automatically and contingent on the detected algorithms.

          John the Ripper is a free tool, licensed and distributed under the GPL license, and ideal for anyone who wants to test their organization’s password security.

          John the Ripper’s chief advantages include:

          Brute force testing and dictionary attacks
          Compatibility with most operating systems and CPU architectures
          Running automatically by using crons
          Allowing Pause and Resume options for any scan
          It lets hackers define custom letters while building dictionary attack lists
          It allows brute force customization rules
   
# 3. Lynis
          Lynis is most likely one of the most comprehensive tools available for cybersecurity compliance (e.g., PCI, HIPAA, SOx), system auditing, system hardening, and testing. In addition, thanks to its numerous capabilities, Lynis also functions as an effective platform for vulnerability scanning and penetration testing.

          This Kali Linux tool’s main features include:

          Open source and free, with commercial support available.
          Simple installation from the Github repository.
          It runs on multiple platforms (BSD, macOS, Linux, BSD, AIX, and more).
          It can run up to 300 security tests on the remote host.
          Its output report is shared on-screen and features suggestions, warnings, and any critical security issues found on the machine.
          
# 4. Metasploit Framework
          Remote computing is on the rise thanks to more people working from home. Metasploit Framework, or MSF for short, is a Ruby-based platform used by ethical hackers to develop, test, and execute exploits against remote hosts. Metasploit includes a complete collection of security tools intended for penetration testing, plus a powerful terminal-based console known as msfconsole, which lets you find targets, exploit security flaws, launch scans, and collect all relevant available data.

          Available for Windows and Linux, MSF is most likely one of the most potent security auditing Kali Linux tools freely available for cybersecurity professionals.

          Metasploit Framework’s features include:

          Network enumeration and discovery
          Evading detection on remote hosts
          Exploiting development and execution
          Scanning remote targets
          Exploiting vulnerabilities and collecting valuable data 
        
# 5. Nikto
          Nikto enables ethical hackers and pen testers to conduct a complete web server scan to discover security vulnerabilities and related flaws. This scan collects results by detecting default file names, insecure file and app patterns, outdated server software, and server and software misconfigurations.

          Written in Perl, Nikto complements OpenVAS and other vulnerability scanners. In addition, it features support for host-based authentication, proxies, SSL encryption, and more.

          Nikto’s primary features include:

          Scanning multiple ports on a server.
          Providing IDS evasion techniques.
          Outputting results into TXT, XML, HTML, NBE or CSV.
          Apache and cgiwrap username enumeration.
          Identifying installed software via headers, files, and favicons.
          Scanning specified CGI directories.
          Using custom configuration files.        
          
          
# 6. Nmap
          Nmap is the most well-known network mapper tool in IT circles. It lets you discover active hosts within any network and gain additional information related to penetration testing, such as existing open ports.

          Nmap main features include:

          Host discovery, which identifies hosts in any network
          Port scanning lets you enumerate open ports on either a local or remote host
          OS detection helps gather operating system and hardware info about any connected device
          App version detection lets you determine the application name and version numbers
          Scriptable interaction extends the Nmap default capabilities by using the Nmap Scripting Engine (or NSE)
          
# 7. Skipfish
          Skipfish is a Kali Linux tool like WPScan, but instead of only focusing on WordPress, Skipfish scans many web applications. Skipfish acts as an effective auditing tool for crawling web-based data, giving pen testers a quick insight into how insecure any app is.

          Skipfish performs recursive crawl and dictionary-based tests over all URLs, using its recon capabilities. The crawl creates a digital map of security checks and their results.

          Noteworthy Skipfish features include:

          Automated learning capabilities.
          Differential security checks.
          Easy to use.
          A low false positive ratio.
          The ability to run high-speed security checks, with over 200 requests per second.
          
# 8. Social Engineering Toolkit
          If you are ever interested in hacking social network accounts, we have just the tool for you! The Social Engineering Toolkit, also known as SET, is an open-source Python-based penetration testing framework that helps you quickly and easily launch social-engineering attacks. It runs on Linux and Mac OS X.

          SET is an indispensable Kali Linux tool for hackers and pen testers interested in working with social engineering.

          Here are the kinds of attacks you can launch with the Social Engineering Toolkit:

          Wi-Fi AP-based attacks, which redirect or intercept packets from Wi-Fi network users
          SMS and email attacks, here, which attempt to trick and generate fake emails to harvest social credentials
          Web-based attacks, which lets hackers clone a web page to drive real users by DNS spoofing and phishing attacks
          Creation of payloads (.exe), which creates a malicious .exe file that, once executed, compromises the system of any user who clicks on it

# 9. MacChanger
          There are several reasons changing the MAC address is important, I use MacChanger while pentesting a wireless network with MAC filtering enabled and have to assign an approved MAC address to the wireless adapter. Or just literally to change to a random MAC while pentesting. 
          
# 10. ProxyChains
          Proxychains cover and handle whatever job. Add command “proxychains” for every job, that means we enable Proxychains service. For example i want to trigger ProxyChain to cover NMAP. The command is:

          ~$ proxychains nmap 74.125.68.101 -v -T4
          But, before you use ProxyChains, you need to configure it first, adding proxy IP and other things, see full tutorial about ProxyChains here: https://linuxhint.com/proxychains-tutorial/
          

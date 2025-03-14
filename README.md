# GlitchOS

# Pentesting & Security Tools Project

## Overview
In this project, I have gathered a variety of tools that are useful for penetration testing (pentesting) and cybersecurity. The goal was to enhance the performance of a Windows environment by incorporating some very useful default tools and improving its security capabilities. This setup is specifically tailored towards data protection and pentesting. The following tools have been included in this setup:

## Tools Included

### 1. **Metasploit Framework**
   **Command:** `msfconfig.bat`
   - **Description:** Metasploit is one of the most widely used tools for penetration testing and security research. It provides a comprehensive environment for developing and executing exploit code against remote target machines.

### 2. **Aircrack-ng**
   **Command:** `aircrack-ng`
   - **Description:** Aircrack-ng is a set of tools for auditing wireless networks. It focuses on key recovery, monitoring, packet injection, and cracking WEP and WPA-PSK keys.

### 3. **Hashcat**
   **Path:** `tools\hashcat6.2.6\cmd`
   **Command:** `hashcat.exe --help`
   - **Description:** Hashcat is a powerful password recovery tool that supports various hash algorithms and provides high performance for cracking encrypted password hashes.

### 4. **DirBuster**
   - **Description:** DirBuster is a tool used to brute force directories and file names on web servers. It helps discover hidden resources and attack vulnerable systems.

### 5. **SQLmap**
   - **Description:** SQLmap is an automated tool for SQL injection and database takeover. It helps penetration testers discover and exploit SQL injection vulnerabilities in web applications.

### 6. **OWASP ZAP (Zed Attack Proxy)**
   - **Description:** OWASP ZAP is an open-source web application security scanner. It helps identify security vulnerabilities in web applications during development or testing phases.

### 7. **Obsidian**
   - **Description:** Obsidian is a powerful knowledge management and note-taking tool. It can help organize and document the results of pentests or security research.

### 8. **WinRAR**
   - **Description:** WinRAR is a file compression tool that can be useful for managing compressed files, such as payloads or archives containing exploit code.

### 9. **Visual Studio Code**
   - **Description:** Visual Studio Code is a source code editor that supports various programming languages. It is useful for writing and debugging scripts used in pentesting.

### 10. **WSL (Windows Subsystem for Linux) - Kali Linux**
   **Credentials:** User: `user`, Password: `123`
   - **Description:** WSL allows you to run a Linux distribution alongside your Windows environment. Kali Linux is a Debian-based distribution used for penetration testing and digital forensics.

### 11. **ScreenBlur**
   **Path:** `C:\Program Files\ScreenBlur 2.0.12`
   - **Description:** ScreenBlur is a privacy tool that automatically blurs your screen to protect sensitive information from prying eyes.

### 12. **Brave Browser**
   - **Description:** Brave is a privacy-focused web browser that blocks ads, trackers, and provides a faster browsing experience.

   **Extensions in Brave:**

   1. **GPS Spoofing**  
      - **Description:** This extension allows you to spoof your GPS location, making it appear as though you are browsing from a different geographic region. It is useful for privacy and testing location-based services.

   2. **X-Forwarded-For Spoofing**  
      - **Description:** This extension helps modify the HTTP request headers to add or change the `X-Forwarded-For` header, allowing you to spoof the originating IP address for testing purposes. It’s useful in bypassing geo-restrictions or evading IP-based tracking.

   3. **DarkReader**  
      - **Description:** DarkReader enables dark mode for websites, making them easier on the eyes during nighttime browsing. It’s also useful in reducing eye strain during long sessions of pentesting and research.

   4. **Cookies Quick Manager**  
      - **Description:** This extension provides an easy interface for managing cookies stored by websites. It allows you to view, delete, and modify cookies, which can be crucial for testing web application security and tracking user sessions.

   5. **Advanced Switcher Agent**  
      - **Description:** This extension allows you to change your browser’s user agent string quickly. It's useful for testing how websites react to different browsers and devices, helping with web application security testing and evading detection.

### 13. **Everything**
   - **Description:** Everything is a search tool that helps quickly find files on your system, which can be useful for locating files during security assessments.

### 14. **GitHubLab**
   - **Description:** GitHubLab is a tool for managing and interacting with Git repositories. It can be used to track and share pentesting scripts or findings.

### 15. **Mullvad Browser**
   - **Description:** Mullvad Browser is a privacy-focused browser developed by Mullvad VPN, aimed at enhancing anonymity during browsing.

### 16. **Nmap**
   - **Description:** Nmap is a powerful network scanner used for network discovery and vulnerability scanning. It helps identify open ports and potential weaknesses in target systems.

### 17. **Session**
   - **Description:** Session is a secure messaging app designed for privacy, which can be useful for communicating with your team during security assessments.

### 18. **Telegram**
   - **Description:** Telegram is a popular messaging app that offers end-to-end encryption and can be used for secure communication.

### 19. **VLC Media Player**
   - **Description:** VLC is a versatile media player that supports almost all audio and video file formats. It's useful for multimedia-related tasks during pentesting, like reviewing video files from surveillance cameras.

### 20. **x86dbg**
   - **Description:** x86dbg is a debugger for x86 architecture, used to analyze and reverse engineer binaries during pentesting and malware analysis.

### 21. **Sublime Text**
   - **Description:** Sublime Text is a sophisticated text editor that can be used for scripting and coding tasks, such as creating exploit code or analyzing files.

### 22. **AnyDesk**
   - **Description:** AnyDesk is a remote desktop software that allows you to connect to and control other computers from a distance. It can be useful for performing remote penetration tests or troubleshooting systems securely.

### 23. **VeraCrypt**
   - **Description:** VeraCrypt is an open-source disk encryption software that can create a virtual encrypted disk or encrypt entire drives. It’s essential for ensuring that sensitive data remains secure during penetration tests or security audits.

### 23. **Quasar RAT v1.4.1**
   - **Description:** Quasar is an open-source Remote Access Trojan that allows remote control of systems. It is useful for conducting penetration tests or security audits, ensuring that sensitive data remains secure during the process.

### 24.  **Snaffler**
   - **Description:** Snaffler is an open-source tool used for capturing and analyzing network traffic. It is commonly employed during penetration tests or security audits to monitor and assess the security of network communications, ensuring data is protected.

   you can shek the tuto in this link : https://github.com/SnaffCon/Snaffler

### 25. **PYbot Botnet**
   - **Description:** PYbot is an open-source Python-based botnet system, designed for conducting Denial of Service (DoS) attacks. It comprises a connect-and-control (C&C) server and bot malware script. The botnet allows the launching of various types of flooding attacks, such as TCP SYN Floods, UDP Floods, HTTP GET Floods, and more. While it demonstrates how a basic botnet operates, its use for malicious purposes, such as illegal DDoS attacks, is strictly prohibited. The repository is primarily educational, providing insights into network security vulnerabilities.

   you can shek the tuto in this link : https://github.com/wodxgod/PYbot

### 26. **WinDefenderKiller**
   - **Description:** WinDefenderKiller is an open-source C++ tool designed to permanently disable Windows Defender by modifying registry keys. This tool exploits specific vulnerabilities within the Windows operating system to bypass security measures and deactivate Windows Defender, allowing potentially harmful activities like downloading malware to proceed undetected. While this tool is often used in security research and penetration testing, its usage for malicious purposes is strictly illegal and unethical. It is provided for educational purposes to demonstrate how certain registry changes can affect system security.

   - **YouTube Video:** [Watch here](https://youtu.be/67-rp3Y16k8)

   - **How to Compile:**
     To compile the code, use the following command:

     ```bash
     └─# x86_64-w64-mingw32-g++ -O2 disableWinDef.cpp -o winDefKiller -I/usr/share/mingw-w64/include -L/usr/lib -s -ffunction-sections -fdata-sections -Wno-write-strings -fno-exceptions -fmerge-all-constants -static-libstdc++ -static-libgcc -fpermissive -Wnarrowing -fexceptions
     ```

   - **Functionality:**
     After compiling and executing the tool, it permanently disables Windows Defender, making the system vulnerable to malicious software. Upon restarting the machine, the changes remain in effect, as shown in the accompanying images, and security software like **Mimikatz** will no longer be detected by Windows Defender.



### 27. **Windows MAS AIO**
   - **Command:** `irm https://get.activated.win | iex`
   - **Description:** Windows MAS AIO (All-in-One) is a script designed to easily activate certain features or optimizations on Windows. It's commonly used by cybersecurity professionals to tailor the operating system for audits or pentests. It helps facilitate the installation of various necessary security tools in one place.

### 28. **Explorer++**
   - **Description:** Explorer++ is a lightweight, open-source file manager for Windows, offering a faster and more fluid interface compared to the native Windows File Explorer. It's useful for navigating and managing files during security audits or penetration tests.

### 29. **Burp Suite**
   - **Description:** Burp Suite is a suite of tools used for testing the security of web applications. It's widely used to detect vulnerabilities like SQL injections, XSS (Cross-Site Scripting), or authentication issues. It enables both manual and automated scanning for security weaknesses in web apps.

### 30. **Mysterium Dark**
   - **Description:** Mysterium Dark is a tool that allows you to connect to an anonymous VPN network. It’s a decentralized platform that ensures secure and private browsing, useful for masking your identity during penetration tests or researching targets.

### 31. **Eraser**
   - **Description:** Eraser is an open-source tool for securely erasing files and folders, ensuring that deleted data cannot be recovered. It uses multiple data erasure techniques, making it essential for security tests that involve sensitive data.

### 32. **NetLimiter**
   - **Description:** NetLimiter is a tool that allows you to control and monitor network traffic on your system. It can be used to limit the bandwidth of specific applications or to monitor network activity. This is particularly useful during penetration testing to observe how systems react to specific network loads.

### 33. **KeePass**
   - **Description:** KeePass is an open-source password manager that securely stores passwords and other sensitive information. It encrypts passwords with powerful algorithms, ensuring the security of your data during penetration tests or security audits.

### 34. **Kleopatra**
   - **Description:** Kleopatra is a certificate and key management tool for encrypting communications and managing keys. It’s useful for cybersecurity professionals who need to manage public/private keys or establish secure connections via PGP (Pretty Good Privacy).

### 35. **Optimizer**
   - **Link:** [Download](https://github.com/hellzerg/optimizer/releases/tag/16.7)
   - **Description:** Optimizer is an open-source tool designed to improve Windows performance by removing unnecessary files, clearing caches, and disabling unnecessary processes. This ensures that your system is fast and responsive, essential for performing penetration tests on a smooth-running machine.



## Conclusion
This setup is specifically crafted to improve the performance of Windows systems while providing powerful tools for pentesting and security analysis. With these tools, you can perform penetration testing, security audits, and improve data protection on your systems.


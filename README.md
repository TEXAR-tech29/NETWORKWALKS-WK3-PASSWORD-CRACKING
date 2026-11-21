# NETWORKWALKS-WK3-PASSWORD-CRACKING

Week 3 Cybersecurity Internship Project — Password Cracking with John the Ripper (JTR), Johnny, NetworkWalks Tools, and AI-Assisted Security Tools.

Project Overview
This project focused on understanding password security and password recovery through two required practical modules and one optional project.

The exercises involved using John the Ripper (JTR) and its graphical interface, Johnny, on Windows; NetworkWalks' online Hash Calculator and Password Cracker tools; and an AI-assisted password-cracking workflow using Claude Desktop, Hexstrike MCP, and John the Ripper in Kali Linux.

The objective was to understand how password hashes are extracted and how password-cracking tools can be used in authorized security testing to demonstrate password strength and weaknesses.

The optional project also provided an opportunity to explore how AI assistants and MCP integrations can interact with existing cybersecurity tools.

Modules Completed
WK3-PM1: Password Cracking with John the Ripper (JTR) and Johnny.
WK3-PM2: Password Cracking with NetworkWalks Tools.
WK3 Optional Project: AI-Assisted Password Cracking with John the Ripper (JTR), Claude Desktop, and Hexstrike MCP.
Tools and Technologies Used
Tool	Purpose
John the Ripper (JTR)	Password security testing and password recovery
Johnny	Graphical interface for John the Ripper
NetworkWalks Hash Calculator	Extracting password hashes from protected PDF files
NetworkWalks Password Cracker	Testing password hashes against available wordlists
Claude Desktop	AI assistant used to interact with the MCP-integrated tools
Hexstrike MCP	MCP server used to connect the AI assistant with cybersecurity tools
Kali Linux	Environment used for the optional AI-assisted project
pdf2john.pl	Extracting crackable password hashes from PDF files
RockYou Wordlist	Dictionary used for password recovery
Windows PC	Environment used for the first JTR practical exercise
Tasks Completed
1. WK3-PM1 — Password Cracking with JTR
Objective: Recover the passwords of the provided protected PDF files using John the Ripper and Johnny on Windows.

Activities performed:

Downloaded and configured Johnny on my Windows PC.
Obtained the provided password-protected PDF files.
Used the File Conversion Tool to extract password hashes.
Saved the extracted hash in a text file named hash1.txt.
Opened the hash file using Johnny.
Started a new password recovery attack.
Successfully recovered the password of the first PDF.
Repeated the process for the second and third PDF files.
Result: Successfully recovered the passwords of all three provided PDF files.

2. WK3-PM2 — Password Cracking with NetworkWalks Tools
Objective: Use NetworkWalks online tools to extract and recover the password of a protected PDF file.

Activities performed:

Opened NetworkWalks Hash Calculator.
Uploaded the provided password-protected PDF file.
Extracted and copied its password hash.
Opened NetworkWalks Password Cracker.
Submitted the extracted hash.
Observed the password-cracking process.
Result: The Password Cracker processed 91 out of 100 available wordlists and successfully recovered the correct password.

3. WK3 Optional Project — AI-Assisted Password Cracking with JTR
Objective: Explore an AI-assisted approach to password cracking by integrating Claude Desktop with Hexstrike MCP and using John the Ripper in Kali Linux to recover the password of a provided protected PDF file.

This was my first experience using an AI-assisted workflow for password cracking, making it a particularly valuable learning experience.

Activities performed:

1. Environment Setup and Integration

Set up Hexstrike MCP with Claude Desktop.
Downloaded and configured the required components in Kali Linux.
Encountered several installation, configuration, and integration challenges.
Continued troubleshooting until the components were successfully integrated.
Used Claude Desktop to check whether John the Ripper was installed and verify its version through the Hexstrike MCP server.
2. PDF Hash Extraction

Downloaded the provided password-protected PDF from Google Drive.
Renamed the file hash3.networkwalks_flag1.pdf.
Used the AI-assisted workflow to extract its crackable password hash with pdf2john.pl.
3. Wordlist Preparation

Requested the use of the RockYou wordlist for the password-recovery process.
Located the compressed wordlist at /usr/share/wordlists/rockyou.txt.gz.
Decompressed it and prepared the resulting rockyou.txt file for use by John the Ripper.
4. Password Recovery

Used Claude Desktop through Hexstrike MCP to initiate the John the Ripper operation.
Supplied the extracted PDF hash and RockYou wordlist.
Executed the dictionary-based password-recovery process.
John the Ripper successfully recovered the password.
5. Password Verification

Copied the recovered password.
Used it to open the original protected PDF.
Successfully verified that the document opened.
Result: Successfully recovered and verified the password of the provided PDF using John the Ripper with the RockYou wordlist through an AI-assisted workflow.

Technical Note: Claude Desktop served as the AI interface, while Hexstrike MCP provided the integration with the cybersecurity tools. John the Ripper performed the actual password-recovery operation using the extracted hash and wordlist.

Key Observations
Password-protected files can contain hashes that can be extracted for authorized security testing.
Password-recovery tools can test password strength using different wordlists.
Weak or commonly used passwords may be recovered more easily.
John the Ripper and Johnny provide practical ways to understand password security.
Online password-cracking tools can demonstrate the password-recovery process without requiring local installation.
AI assistants integrated through MCP can help orchestrate existing cybersecurity tools and workflows.
Successful integration requires proper configuration, troubleshooting, and verification.
What I Learned
Through these practical modules and the optional project, I gained hands-on experience with password recovery, password security testing, and AI-assisted cybersecurity workflows.

I learned how to:

Extract password hashes from protected PDF files.
Load extracted hashes into Johnny and perform password-recovery attacks.
Use NetworkWalks' online Hash Calculator and Password Cracker.
Understand how wordlists are used during password-cracking attempts.
Configure Hexstrike MCP and integrate it with Claude Desktop.
Verify tool availability and versions through an MCP integration.
Use pdf2john.pl to extract crackable hashes from PDF files.
Locate and prepare the RockYou wordlist.
Orchestrate John the Ripper through an AI-assisted workflow.
Troubleshoot setup and integration issues.
The optional project was particularly meaningful because it was my first experience using an AI-assisted approach to password cracking. I faced several challenges during the setup, but continued troubleshooting and trying again until everything worked together.

Most importantly, these exercises helped me understand why strong, unique passwords are important and how password security assessments can help identify weak passwords before they become a security risk.

Evidence and Documentation
Screenshots documenting the practical steps and observed results are organized in the Evidence directory:

WK3-PM1-JTR/ — Evidence of the John the Ripper and Johnny exercises.
WK3-PM2-NETWORKWALKS-TOOLS/ — Evidence of the NetworkWalks online tools exercise.
WK3-OPTIONAL-AI-ASSISTED-JTR/ — Evidence of the Hexstrike MCP setup, tool verification, hash extraction, AI-assisted execution, and successful PDF verification.
Ethical Considerations
All activities were conducted as part of an authorized educational internship exercise using the provided lab files and tools.

Password-cracking techniques should only be used on files, systems, and password hashes for which proper authorization has been granted.

Sensitive information, including recovered passwords, actual hash values, and original protected PDF files, is intentionally excluded from this public documentation.

Acknowledgment
This project was completed as part of the NetworkWalks Cybersecurity Internship 2026.

Special thanks to NetworkWalks and my instructor Waqas Karim CCIE for providing the learning resources, practical exercises, optional challenges, and guidance throughout the internship.

Week 3 completed! Continuing to learn, practice, explore new technologies, and build my cybersecurity skills, one project at a time, By the grace of God

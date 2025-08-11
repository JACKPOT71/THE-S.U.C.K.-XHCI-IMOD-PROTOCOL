The S.U.C.K XHCI Protocol 🚀

A FortKnight's Legacy by JACKPOT_ZB

Welcome to the "eXtreme Hardware Control Interface" (XHCI) Overdrive Protocol! This script is a powerful tool for hardware enthusiasts and power users looking to unlock full, unrestricted Read/Write access to their system's XHCI (USB 3.x) controller. It automates the entire process of system modification and tool installation, giving you raw access to the metal.

Find us on Discord: https://discord.gg/xtgBxkpc2x


⚠️ CRITICAL WARNING ⚠️

This script makes deep, invasive modifications to your Windows operating system and directly interacts with your hardware. Disabling core security features and writing to hardware registers can lead to system instability, data corruption, security vulnerabilities, or even permanent hardware damage.

USE ENTIRELY AT YOUR OWN RISK!

It is STRONGLY recommended to create a full system backup or a system restore point before running this tool. This script is intended only for tweakers, researchers, and experts who fully understand the risks and consequences of their actions.

✨ Features

One-Click Deployment: A single batch file to execute the entire chain of operations. No manual installation or configuration is needed.

Robust Administrator Check: The process requires administrative privileges to modify the system registry and install software.

Security Bypass: Automatically disables the Windows VulnerableDriverBlocklistEnable feature, clearing the path for the necessary low-level driver.

Silent & Automated Installation: Installs the required RW-Everything utility completely in the background without any user prompts.

Persistent Domination: Sets up a PowerShell script that runs at every startup, ensuring your IMOD modifications survive reboots and are always active.

Clean-Up & Vanish: After execution, the script cleans up all temporary installation files, leaving no trace but the mod itself.

Detailed Feedback (Implicit): The commands run in sequence to ensure each stage is complete before the next begins.

🚀 How to Use

Download: Download the XHCI IMOD Full RW.bat file.

Run as Administrator:

Right-click on the .bat file.

Select "Run as administrator". This is mandatory for the script to function.

Wait: The script will run in the background. It needs a few moments to download and install the required components.

Reboot: After the script has finished, a reboot is recommended to ensure the persistence mechanism is active for the next session.

For Maximum Control (Context)

Some low-level operations require the highest privileges. This script automates gaining the necessary access by modifying system settings. Be aware that this is a high-risk operation.

🛠️ Mission Protocol Overview

[STAGE A] INFILTRATE REGISTRY: The protocol's first action is to modify the Windows Registry to set VulnerableDriverBlocklistEnable to 0. This disables a key system protection to allow the required driver to load.

[STAGE B] ACQUIRE ASSETS: The script uses Curl to download the SetupRwX64.exe installer and the core XHCI-IMOD-Full-RW.ps1 PowerShell payload from their servers.

[STAGE C] SILENT DEPLOYMENT: The RW-Everything utility is installed silently (/VERYSILENT) into your Program Files. This is the engine that enables direct hardware access.

[STAGE D] ESTABLISH PERSISTENCE: A shortcut to the PowerShell payload is placed in the user's Startup folder. This ensures that every time you log in, your XHCI IMOD modifications are re-applied with a Bypass execution policy.

[STAGE E] SANITIZE & EVACUATE: All temporary files are deleted, leaving the system clean. The operation is complete.

[Q] QUIT PROGRAM: The script automatically terminates after completing its mission.

Credits: I don't know exactly but i think it was Kizzimo who share this the first time. Thanks a lot for your work mate.

Welcome to the Xbox One Bliss Hack GFL_Tech Modchip wiki!

First we need to give credit where it is due. "Markus 'doom' Gaasedelen" Thank you for your work on the discovery of this vulnerability.

Bliss Hack Modchip Project - Xbox One Brought to you by GFL_Tech

Welcome to the official repository tracking the hardware development of the Bliss Hack Modchip for the Xbox One. After 12 years of locked-down security, the Xbox One has finally been cracked via the "Bliss" exploit. An official mod chip has not been made or worked on. This page is an attempt at taking a swing at the project so that we can archive and preserve this console in an age of digital content and subscriptions. Follow us here and on Youtube for updates and progress. This repository is the central hub for the open-source hardware modchip being designed by GFL_Tech. Our goal is to translate this complex software/hardware exploit into a reliable, easy-to-install hardware solution for the retro and homebrew community.

Disclaimer READ THIS BEFORE PROCEEDING: This project is strictly for educational, homebrew, and archival purposes. Modifying your console will carry a high risk of hardware bans from Xbox Live or damage to your device. We do not support piracy. GFL_Tech and the contributors are not responsible for bricked consoles, burnt components, or banned accounts. Proceed at your own risk and always double-check your work! This is my first GitHub Project (We may be less organized but are open to feedback)

Current Progress: Planning

[x] Understanding the hack (Roadmap for prototype Github)

[x] Unbox a Day One Edition Xbox One (2013 Test subject)

[] Circuit design (3 Required signals + Reset automation)

[] Code for automation and timing tests

[] Build the circuit and test functionality

[] Validate success of EFUSE digital signal

[] Test and sweep glitch timing from EFUSE Sidechannel trigger (MPU)

[] Validate timing for repeatability & prep for PC Hijack from EMMC DAT0 signal

[] Sweep and text PC Hijack glitch timings

[] Finalize a rough timing profile and circuit PCB that successfully performs Bliss Hack (Speed isnt the goal "Yet")

[] Release first revision of physical attack for additional external support and development (Move on to V2 with tighter timings and more refined design)

Planned Features -Consistent Boot Times: Automates the Bliss exploit chain for reliable boot sequences. -QSB (Quick Solder Board) Architecture: Custom-designed to sit flush on the motherboard, minimizing messy wire runs and making installation cleaner. -100% Open Source: All Gerber files, schematics, and injection code will be fully open-sourced upon version 1.0 completion.

Follow the Journey? Want to see the smoke, the failures, and the eventual successes? The entire development process, including deep dives into the Xbox One's architecture and the Bliss exploit, is being documented on YouTube!

Subscribe and watch the progress: GFL_Tech on YouTube (http://www.youtube.com/@GFL_Tech)

However, if you are an experienced hardware reverse engineer or developer looking to collaborate on timing glitches or payload optimization, please open an Issue with the tag [DEV COLLAB] and a brief summary of your background.

Shoutout to "Markus 'doom' Gaasedelen" who originally discovered the Bliss vulnerability. We are just building the bridge!

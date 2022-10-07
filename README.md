# Awesome School Exploits [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
__Pull Requests/Contributions are more than welcome, and we would love all the help we could get from those.__
When submitting an exploit, make sure to follow the [contribution guidelines](#contribution-guidelines)
- [Filter Bypasses](#filter-bypasses)
    - __[Ranking](#ranking)__
    - [Extension-based blocking](#extension-based-blocking)
    - [IStealYourDNS](#istealyourdns)
- [Program Blocker Bypassing](#program-blocker-bypassing)
    - [Windows .exe Unblock](#windows-exe-unblock)
- [Monitoring Software Disabling](#monitoring-software-disabling)
    - [Disabling LanSchool Air](#disable-lanschool-air)
- [Proxy Sources](#proxy-sources)
    - [Holy Unblocker](#holy-unblocker)
    - [Node Unblocker](#node-unblocker)
- [Game Hacks](#game-hacks)
    - [Blooket](#blooket)
    - [Gimkit](#gimkit)
- [Other](#other)
    - [Disable Extensions](#disable-extensions)
---

## Filter Bypasses
Tools that allow you to bypass filters, monitoring software, etc

### Ranking
**This is a list of methods sorted by easiest to use/most working to hardest to use/least working. In some instances, you may need to combine a few methods to truly unblock everything.**
1. [Extension-based blocking](#extension-based-blocking)
2. [IStealYourDNS](#istealyourdns)

### Extension-based Blocking
**Use the [Disable Extensions](#disable-extensions) exploit to turn off filtering systems that rely on an extension to block websites.**

### IStealYourDNS
**This exploit involves changing your DNS settings to bypass network-wide filters. If your school also uses (an) extension(s), you'll want to also use the [Disable Extensions](#disable-extensions) exploit. Also, you'll have to do this for every network you connect to.**
1. Open your Wifi's DNS settings [chromebook howto](https://www.howtogeek.com/204672/how-to-change-the-dns-server-on-a-chromebook/)
2. Set your primary DNS to `72.5.33.65` and your secondary DNS to `1.1.1.1`

## Program Blocker Bypassing

### Windows .exe Unblock
**This only works if PowerShell is not blocked. Shoutout to `Citrik🗿#4600` on Discord.**
1. Download the `.exe` file to your Downloads folder
2. Open `Windows PowerShell`
3. Run `cd Downloads` (or whichever folder your `.exe` file is located in)
3. Run `Copy .\filename C:\Windows\Temp\filename` replacing `filename` with the name of your file.
4. Run `C:\Windows\Temp\filename` replacing `filename` with the name of your file.
5. The program will open.

## Monitoring Software Disabling

### Disable LanSchool Air
**This is also possible using the "Disabling Extensions" exploit, however Ingot doesn't support apps, so you'll need to use the Basic GUI instead. Follow these steps each time you login:**
1. Login, and wait for the LanSchool Air app to load
2. Open a new tab and go to `chrome://serviceworker-internals/`
3. On all the scopes that start with `chrome-extension://`, press the "Unregister" button
4. Forcibly close LanSchool by right clicking the app on the bottom appbar and pressing "Close"
5. As usual, LanSchool will reopen, however, it won't be connected and will say "Not Connected" in bottom left corner 

## Proxy Sources

### [Holy Unblocker](https://github.com/holy-unblocker/website-aio)
Holy Unblocker is a secure web proxy service supporting numerous sites while concentrating on detail with design, mechanics, and features. Bypass web filters regardless of whether it is an extension or network-based.

### [Node Unblocker](https://github.com/nfriedly/node-unblocker)
Web proxy for evading internet censorship, and general-purpose Node.js library for proxying and rewriting remote webpages

## Game Hacks

### [Blooket](https://github.com/therealgliz/blooket-hacks)
List of JavaScript scripts to run as a bookmarklets that'll enhance Blooket gameplay with cheats.

### [GimKit](https://github.com/rxzyx/GimKit-Hacks)
List of JavaScript scripts to run as a bookmarklets that'll enhance GimKit gameplay with cheats.

## Other

### Disable Extensions
**Follow the instructions here: https://github.com/3kh0/ext-remover**

We recommend using the Ingot GUI as it provides the best user experience.
---

## Contribution Guidelines
1. Exploits that require downgrading your software version are not permitted. We apologize, but these methods are risky, as administrators are notified when a chromebook is unenrolled.
2. Make sure to use proper grammar and add your exploit to the navigation also

# Awesome School Exploits [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
__Pull Requests/Contributions are more than welcome, and we would love all the help we could get from those.__
When submitting an exploit, make sure to follow the [contribution guidelines](#contribution-guidelines)
- [Filter Bypasses](#filter-bypasses)
    - [Disabling LanSchool Air](#disable-lanschool-air)
    - [Lightspeed Filter Agent](#lightspeed-filter-agent)
    - [FortiClient Chromebook WebFilter Extension](#forticlient-chromebook-webfilter-extension)
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

### Disable LanSchool Air
**Follow these steps each time you login:**
1. Login, and wait for the LanSchool Air app to load
2. Open a new tab and go to `chrome://serviceworker-internals/`
3. On all the scopes that start with `chrome-extension://`, press the "Unregister" button
4. Forcibly close LanSchool by right clicking the app on the bottom appbar and pressing "Close"
5. As usual, LanSchool will reopen, however, it won't be connected and will say "Not Connected" in bottom left corner 

### Lightspeed Filter Agent
**Use the [Disable Extensions](#disable-extensions) exploit to turn off the Lightspeed Filter Agent extension.**

### FortiClient Chromebook WebFilter Extension
**Use the [Disable Extensions](#disable-extensions) exploit to turn off the FortiClient Chromebook WebFilter Extension extension.**

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

---

## Contribution Guidelines
1. Exploits that require downgrading your software version are not permitted. We apologize, but these methods are risky, as administrators are notified when a chromebook is unenrolled.
2. Make sure to use proper grammar and add your exploit to the navigation also

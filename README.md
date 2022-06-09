# Brave Browser Privacy
![Brave stable](https://badgen.net/badge/Brave/MIT/orange?icon=github)

![Brave_logo svg](https://user-images.githubusercontent.com/80682093/166717179-6d7b3beb-70df-42ea-b472-9907b060998b.png)

**OBJECTIVE**: Make Brave Browser More Private!

_**Note**: This guide is made for the desktop version of Brave._

_**Warning**: This guide is not necessary to follow, Brave is already configured for privacy by default, you may use Brave with the default settings, this is to implement while needing additional privacy._

_💡 **Tip**: You can create two profiles in Brave, one with the default settings and the other with this guide's mentioned settings!_

# Steps:

- Open 'Brave', click on the 'Hamburger menu'. ![Screenshot 2022-02-09 201415](https://user-images.githubusercontent.com/80682093/153224634-6215009f-f4ef-4b9d-b67b-54ee80f60b5d.png)

- Go to 'Settings'.

- Under 'Shields' < 'Trackers & ads blocking', select `Aggressive` and in 'Fingerprinting blocking', select `Strict, may break sites`.

- Under 'Social media blocking', disable `Allow Google login buttons on third party sites`, `Allow Facebook logins and embedded posts` and `Allow Twitter embedded tweets`.

**Caution**: This will break the ability of third party sites to log in with Google and Facebook.

- Under 'Privacy and security' < 'WebRTC IP handling policy', select `Disable non-proxified UDP` (disables the possibility to leak your IP address even when you're using a VPN).

- Under 'Privacy and security', disable `Automatically send daily usage ping to Brave` and `Help improve Brave's features and performance`.

- Under 'Privacy and security' < 'Clear browsing data', select `On exit`, and select everything.

- Under 'Privacy and security' < 'Cookies and other site data', turn `Clear cookies and site data when you close all windows` and `Send a "Do Not Track" request with your browsing traffic` on.

- Under 'Privacy and security' < 'Security' < 'Use secure DNS', select `with` < `Cloudflare (1.1.1.1)`, makes difficult for your ISP from keeping an eye on you, but doesn't stops it fully (it's the fastest DNS, you may select any other).

**Tip**: For a more privacy friendly DNS choice, look at [AdGuard DNS](https://adguard.com/en/adguard-dns/overview.html) or [ControlD](https://controld.com/free-dns).

- Under 'Search engine' select `DuckDuckGo` or `Startpage` (or any other [privacy-friendly](https://itsfoss.com/privacy-search-engines/) search engine).

- Under 'Additional settings' < 'Autofill' < 'Passwords', turn off `Offer to save passwords` and `Auto Sign-in` (use a separate password manager for this purpose).

These all will give you the most control for your privacy.

# Fingerprint

You must be asking wouldn't changing these settings will make your browser fingerprint unique? And I expect you to ask this question, but Brave has already solved this problem by '[Fingerprint Randomization](https://brave.com/privacy-updates-3/)', which makes you appear differently to websites over Brave restart. So you can be assured that you wouldn't be uniquely identified or tracked.

For additional information, take a look at [Brave's Fingerprinting Protections](https://github.com/brave/brave-browser/wiki/Fingerprinting-Protections).

# Other Important Implementations

- Don't enable 'Sync'.

- Don't enable 'Rewards'.

- Don't enable 'Brave News'. 

# Extensions

**1.** [uBlock Origin](https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm) is a wide spectrum efficient blocker, that can be used to block JavaScript, trackers, ads, WebRTC leaks, mitigate fingerprinting and more.

# Why Not Any Other Web Browser?

Great question! You may think for 'Hardened Firefox', but Firefox is really insecure. Apart from this, hardening has fingerprinting drawbacks. 

See this 👉 https://madaidans-insecurities.github.io/firefox-chromium.

Brave is the closest web browser to both privacy and security. 

# Is It Necessary?

No, it's completely optional. Brave works well-enough out of the box. In fact, most browsers work best when not configured to avoid fingerprinting. Even Apple and The Tor Project don't recommend changing any settings in Safari and Tor Browser respectively. I don't necessarily recommend changing these settings or even installing any extensions (as extensions posses a privacy and/or a security risk), because on Brave you're already good to go with the default settings!

# Others

A research study analyzing browser privacy by Professor Douglas J. Leith of the University of Dublin reported that Brave had the highest level of privacy of the browsers tested. Brave did not have, "any use of identifiers allowing tracking of IP address overtime, and no sharing of the details of web pages visited with backend servers." The test was conducted on the default settings of all the tested web browsers.

Complete PDF of the study 👉 https://www.scss.tcd.ie/Doug.Leith/pubs/browser_privacy.pdf.

# Thanks!

Thank you for having a look here!

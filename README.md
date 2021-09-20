# Brave Browser Privacy
![Brave stable](https://badgen.net/badge/Brave/GPLv3/orange?icon=github)

![Screenshot (81)](https://user-images.githubusercontent.com/80682093/133772923-c8e0ba30-ea04-45f3-b23b-91f52ad68c30.png)

**OBJECTIVE**: Make Brave Browser More Private & Secure!

_📝 **Note**: This guide is made for the desktop version of Brave._ 

# Steps:

**1.** Open 'Brave', click on the 'Hamburger menu'. ![Screenshot (13)](https://user-images.githubusercontent.com/80682093/132233765-59e71737-4c82-432e-9b34-06259a763c23.png)

**2.** Go to 'Settings'.

**3.** Under 'Get started' < 'On startup', select `Open the New Tab page`.

**4.** Under 'Shields' < 'Trackers & ads blocking', select `Aggressive` and in 'Fingerprinting blocking', select `Strict, may break sites`.

**5.** Under 'Privacy and security' < 'WebRTC IP handling policy', select `Disable non-proxified UDP` (disables the possibility to leak your IP address even when you're using a VPN).

**6.** Under 'Privacy and security', disable `Automatically send daily usage ping to Brave` and `Help improve Brave's features and performance`.

**7.** Under 'Privacy and security' < 'Clear browsing data', select `On exit`, and select everything.

**8.** Under 'Privacy and security' < 'Cookies and other site data', turn `Clear cookies and site data when you close all windows` and `Send a "Do Not Track" request with your browsing traffic` on.

**9.** Under 'Privacy and security' < 'Security' < 'Use secure DNS', select `with` < `Cloudflare (1.1.1.1)`, makes difficult for your ISP from keeping an eye on you, but doesn't stops it fully (it's the fastest DNS, you may select any other).

**10.** Under 'Search engine' select `DuckDuckGo` (or any other [privacy-friendly](https://itsfoss.com/privacy-search-engines/) search engine).

**11.** Under 'Additional settings' < 'Autofill' < 'Passwords', turn off `Offer to save passwords` and `Auto Sign-in` (use a separate password manager for this purpose).

These all will give you the most control for your privacy.

# Fingerprint

You must be asking wouldn't changing these settings will make your browser fingerprint unique? And I expect you to ask this question, but Brave has already solved this problem by '[Fingerprint Randomization](https://brave.com/privacy-updates-3/)', which changes your browser fingerprint periodically. So you can be assured that you wouldn't be uniquely identified or tracked.

# Other Important Implementations

**1.** Don't enable 'Sync'.

**2.** Don't enable 'Rewards'.

**3.** Don't enable 'Brave Today'. 

# Extensions

**1.** [Privacy Badger](https://chrome.google.com/webstore/detail/privacy-badger/pkehgijcmpdhfbdbbnkijodmdjhbjlgp) for blocking trackers which Brave didn't blocked.

**2.** [HTTPS Everywhere](https://chrome.google.com/webstore/detail/https-everywhere/gcbommkclmclpchllfjekcdonpmejbdp) to automatically upgrade to the HTTPS version of sites, which Brave doesn't upgrades (enable `Encrypt All Sites Eligible is ON`).

**3.** [Decentraleyes](https://chrome.google.com/webstore/detail/decentraleyes/ldpochfccmkkmhdbclfhpagapcfdljkj) for blocking Content Delievery Networks.

# Why Not Any Other Web Browser?

Great question! You may think for 'Hardened Firefox', but Firefox is really insecure.

See this 👉 https://nihal247.github.io/firefox's-insecurity. Apart from the insecurity, tweaking a lot of settings to 'harden' it, just makes you stand out in the crowd by making your browser fingerprint more unique. Hence, drastically reducing privacy!

Brave is the closest web browser to both privacy and security. 

# Is It Necessary?

No. Brave works well-enough out of the box. In fact, most browsers work best when not configured to avoid fingerprinting. Even Apple and The Tor Project don't recommend changing any settings in Safari and Tor Browser respectively. I don't necessarily recommend changing these settings or even installing any extensions, because on Brave you're already good to go with the default settings!

# Others

A research study analyzing browser privacy by Professor Douglas J. Leith of the University of Dublin reported that Brave had the highest level of privacy of the browsers tested. Brave did not have, "any use of identifiers allowing tracking of IP address overtime, and no sharing of the details of web pages visited with backend servers." The test was conducted on the default settings of all the tested web browsers.

Complete PDF of the study 👉 https://www.scss.tcd.ie/Doug.Leith/pubs/browser_privacy.pdf

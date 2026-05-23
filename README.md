# 🔍 OSINT Resources for Digital Investigators

A curated collection of open source intelligence tools, websites, and resources organized by category. Built for investigators and security researchers conducting structured, reproducible OSINT operations.

> This repository is actively maintained and updated as new tools are vetted.

---

## Legend

| Symbol | Meaning |
|--------|---------|
| 🆓 | Free |
| 💰 | Paid or freemium |
| 📝 | Registration required |
| ⚠️ | May not function on restricted networks |
| 🔧 | Requires local installation |

---

## Table of Contents

- [Search Engines](#search-engines)
- [Username & Identity](#username--identity)
- [Social Networks](#social-networks)
- [Email Address](#email-address)
- [Domain & IP](#domain--ip)
- [People Search](#people-search)
- [Phone Numbers](#phone-numbers)
- [Geolocation](#geolocation)
- [Dark Web](#dark-web)
- [Blockchain & Cryptocurrency](#blockchain--cryptocurrency)
- [Image & Video Analysis](#image--video-analysis)
- [Public Records](#public-records)
- [Cyber Threat Intelligence](#cyber-threat-intelligence)
- [Documentation & Evidence Capture](#documentation--evidence-capture)

---

## Search Engines

| Tool | Description | Tags |
|------|-------------|------|
| <a href="https://www.google.com" target="_blank" rel="noopener noreferrer">Google</a> | Primary search engine. Supports advanced operators and dorking | 🆓 |
| <a href="https://www.bing.com" target="_blank" rel="noopener noreferrer">Bing</a> | Microsoft search engine. Useful for results not indexed by Google | 🆓 |
| <a href="https://www.duckduckgo.com" target="_blank" rel="noopener noreferrer">DuckDuckGo</a> | Privacy-focused. No personalized results, useful for neutral searches | 🆓 |
| <a href="https://www.yandex.com" target="_blank" rel="noopener noreferrer">Yandex</a> | Russian search engine. Strong for reverse image search and Eastern European content | 🆓 |
| <a href="https://www.baidu.com" target="_blank" rel="noopener noreferrer">Baidu</a> | Chinese search engine. Useful for subjects with ties to China | 🆓 |
| <a href="https://www.startpage.com" target="_blank" rel="noopener noreferrer">Startpage</a> | Returns Google results anonymously | 🆓 |
| <a href="https://ahmia.fi" target="_blank" rel="noopener noreferrer">Ahmia</a> | Surface web index of Tor hidden services | 🆓 |
| <a href="https://www.shodan.io" target="_blank" rel="noopener noreferrer">Shodan</a> | Search engine for internet-connected devices and exposed services | 💰 📝 |
| <a href="https://censys.io" target="_blank" rel="noopener noreferrer">Censys</a> | Internet-wide scanning and device enumeration | 💰 📝 |
| <a href="https://grep.app" target="_blank" rel="noopener noreferrer">Grep.app</a> | Search across public GitHub repositories | 🆓 |

---

## Username & Identity

### Username Search Engines

| Tool | Description | Tags |
|------|-------------|------|
| <a href="https://whatsmyname.app" target="_blank" rel="noopener noreferrer">WhatsMyName</a> | Search a username across 270+ platforms simultaneously | 🆓 |
| <a href="https://namechk.com" target="_blank" rel="noopener noreferrer">Namechk</a> | Check username availability and presence across 100+ platforms | 🆓 |
| <a href="https://namecheckup.com" target="_blank" rel="noopener noreferrer">NameCheckup</a> | Username and domain availability check across major platforms | 🆓 |
| <a href="https://lullar-com-3.appspot.com" target="_blank" rel="noopener noreferrer">Lullar</a> | Search a username across social networks and forums | 🆓 |
| <a href="https://instantusername.com" target="_blank" rel="noopener noreferrer">Instant Username Search</a> | Real-time check of username availability across platforms | 🆓 |
| <a href="https://blackbird-osint.herokuapp.com" target="_blank" rel="noopener noreferrer">Blackbird (web)</a> | Search username on 574+ websites. Web interface available | 🆓 |
| <a href="https://www.idcrawl.com" target="_blank" rel="noopener noreferrer">IDCrawl</a> | Search name or username across social networks. Good general starting point | 🆓 |
| <a href="https://sherlockeye.io" target="_blank" rel="noopener noreferrer">SherlockEye</a> | Search username across platforms and surface associated profiles | 🆓 |
| <a href="https://www.user-searcher.com" target="_blank" rel="noopener noreferrer">User Searcher</a> | Search username across 2000+ websites | 🆓 |

### Platform-Specific Direct Lookups *(Manual URL — replace username)*

| Tool | Description | Tags |
|------|-------------|------|
| <a href="https://x.com/USERNAME" target="_blank" rel="noopener noreferrer">X / Twitter</a> | Direct profile lookup. Replace USERNAME in URL | 🆓 |
| <a href="https://www.instagram.com/USERNAME" target="_blank" rel="noopener noreferrer">Instagram</a> | Direct profile lookup | 🆓 |
| <a href="https://www.tiktok.com/@USERNAME" target="_blank" rel="noopener noreferrer">TikTok</a> | Direct profile lookup | 🆓 |
| <a href="https://www.facebook.com/USERNAME" target="_blank" rel="noopener noreferrer">Facebook</a> | Direct profile lookup | 🆓 |
| <a href="https://www.reddit.com/user/USERNAME" target="_blank" rel="noopener noreferrer">Reddit</a> | Direct profile lookup | 🆓 |
| <a href="https://www.snapchat.com/@USERNAME" target="_blank" rel="noopener noreferrer">Snapchat</a> | Direct profile lookup | 🆓 |
| <a href="https://www.youtube.com/USERNAME" target="_blank" rel="noopener noreferrer">YouTube</a> | Direct channel lookup | 🆓 |
| <a href="https://medium.com/@USERNAME" target="_blank" rel="noopener noreferrer">Medium</a> | Direct profile lookup | 🆓 |
| <a href="https://linktr.ee/USERNAME" target="_blank" rel="noopener noreferrer">Linktree</a> | Check if subject uses Linktree to aggregate their links | 🆓 |
| <a href="https://tinder.com/@USERNAME" target="_blank" rel="noopener noreferrer">Tinder</a> | Direct profile lookup | 🆓 |
| <a href="https://www.google.com/search?q=%22USERNAME@gmail.com%22OR%22USERNAME@yahoo.com%22OR%22USERNAME@hotmail.com%22OR%22USERNAME@protonmail.com%22" target="_blank" rel="noopener noreferrer">Google Email Search (M)</a> | Google search for common email variants of a username. Replace USERNAME | 🆓 |

### Username Change History & Tracking

| Tool | Description | Tags |
|------|-------------|------|
| <a href="https://github.com/travisbrown/memory.lol" target="_blank" rel="noopener noreferrer">Memory.lol</a> | Historical screen names for Twitter/X accounts | 🆓 |
| <a href="https://spoonbill.io" target="_blank" rel="noopener noreferrer">Spoonbill</a> | Track bio, location, and username changes on Twitter/X | 🆓 |

### Additional Username & Profile Search

| Tool | Description | Tags |
|------|-------------|------|
| <a href="https://checkusernames.com/" target="_blank" rel="noopener noreferrer">CheckUsernames</a> | Check username availability across social networks and major platforms | 🆓 |
| <a href="https://pickuki.com" target="_blank" rel="noopener noreferrer">Pickuki — Instagram Profile Search</a> | Browse and search public Instagram profiles without an account | 🆓 |
| <a href="https://instahunt.co" target="_blank" rel="noopener noreferrer">InstaHunt — Instagram Search</a> | Search Instagram by name or username without logging in | 🆓 |
| <a href="https://codeofaninja.com/tools/find-instagram-user-id" target="_blank" rel="noopener noreferrer">Code of Ninja — Instagram ID Finder</a> | Find the numeric Instagram user ID from a username. Useful for account pivot | 🆓 |
| <a href="https://peekyou.com/" target="_blank" rel="noopener noreferrer">PeekYou — People Search</a> | US people search aggregating social profiles, public records, and web presence | 🆓 |
| <a href="https://www.osintcombine.com/instagram-explorer" target="_blank" rel="noopener noreferrer">OSINT Combine — Instagram Explorer</a> | Search and analyze public Instagram accounts by username or profile | 🆓 |

---

## Email Address

### Breach & Leak Search

| Tool | Description | Tags |
|------|-------------|------|
| <a href="https://haveibeenpwned.com" target="_blank" rel="noopener noreferrer">Have I Been Pwned</a> | Check if an email appears in known data breaches. Gold standard for breach checks | 🆓 |
| <a href="https://www.hudsonrock.com/threat-intelligence-cybercrime-tools" target="_blank" rel="noopener noreferrer">HudsonRock Cavalier</a> | Search infostealer-compromised credentials by email or domain. Checks stealer logs, not just breach dumps | 🆓 |
| <a href="https://dehashed.com" target="_blank" rel="noopener noreferrer">DeHashed</a> | Search 15B+ leaked records by email, username, IP, or name. Requires account for full results | 🆓 💰 |
| <a href="https://intelx.io" target="_blank" rel="noopener noreferrer">Intelligence X (IntelX)</a> | Search dark web leaks, breaches, and public sources by email. Covers Tor, I2P, and data dumps | 🆓 💰 |
| <a href="https://leakix.net/search" target="_blank" rel="noopener noreferrer">LeakIX</a> | Search leaked and exposed data indexed from internet services. More infrastructure-focused than email-centric | 🆓 |
| <a href="https://breach.vip" target="_blank" rel="noopener noreferrer">breach.vip</a> | Quick breach lookup by email address. Lightweight tool for fast checks | 🆓 |
| <a href="https://scamsearch.io" target="_blank" rel="noopener noreferrer">Scam Search</a> | Search email addresses across known scam databases. Useful for fraud investigations | 🆓 |

### Email Search & Account Discovery

| Tool | Description | Tags |
|------|-------------|------|
| <a href="https://tools.epieos.com/email.php" target="_blank" rel="noopener noreferrer">Epieos</a> | Find social accounts, Google profile, and services linked to an email. Based on Holehe methodology | 🆓 💰 |
| <a href="https://www.osint.industries" target="_blank" rel="noopener noreferrer">OSINT Industries</a> | Search email against 200+ services to find linked accounts. Comprehensive account enumeration | 💰 📝 |
| <a href="https://hunter.io/email-verifier" target="_blank" rel="noopener noreferrer">Hunter.io</a> | Verify if an email is deliverable and find associated domain info. Also identifies company email formats | 🆓 💰 |
| <a href="https://thatsthem.com/email" target="_blank" rel="noopener noreferrer">ThatsThem</a> | Reverse email lookup for name, address, phone, and social profiles. Primarily US; limited Canadian data | 🆓 |
| <a href="https://www.skymem.info" target="_blank" rel="noopener noreferrer">Skymem</a> | Find email addresses associated with a domain or person | 🆓 |
| <a href="https://www.voilanorbert.com" target="_blank" rel="noopener noreferrer">VoilaNorbert</a> | Find professional email addresses by name and company domain | 🆓 💰 |
| <a href="https://www.email-format.com" target="_blank" rel="noopener noreferrer">Email Format</a> | Reveals common email format patterns used by companies. Useful for identifying corporate targets | 🆓 |
| <a href="https://metricsparrow.com/toolkit/email-permutator/" target="_blank" rel="noopener noreferrer">Email Permutator</a> | Generate possible email permutations for a given name and domain | 🆓 |

### Email Verification

| Tool | Description | Tags |
|------|-------------|------|
| <a href="https://reacher.email" target="_blank" rel="noopener noreferrer">Reacher</a> | Real-time email verification — checks if inbox is active | 🆓 💰 |
| <a href="https://emailrep.io" target="_blank" rel="noopener noreferrer">EmailRep</a> | Email reputation scoring — age, breach status, deliverability | 🆓 |
| <a href="https://www.mailboxvalidator.com/demo" target="_blank" rel="noopener noreferrer">MailboxValidator</a> | Check if email is valid, disposable, or a known spam address | 🆓 |
| <a href="https://disposable-emails.github.io" target="_blank" rel="noopener noreferrer">Disposable Emails Registry</a> | Check if an email domain is a known throwaway/disposable provider. Useful for screening suspicious contacts | 🆓 |

### Social & Google Account Pivot

| Tool | Description | Tags |
|------|-------------|------|
| <a href="https://epieos.com" target="_blank" rel="noopener noreferrer">Epieos (Google pivot)</a> | Find Google profile, photo, and Maps reviews linked to a Gmail address. Pivots Gmail → Google Maps activity | 🆓 |
| <a href="https://github.com/mxrch/GHunt" target="_blank" rel="noopener noreferrer">GHunt (web demo)</a> | Investigate Google accounts via email. Web-based limited demo available; full tool requires local install | 🆓 🔧 |
| <a href="https://en.gravatar.com/emails" target="_blank" rel="noopener noreferrer">Gravatar</a> | Check if an email has a Gravatar profile image attached | 🆓 |
| <a href="https://whoisology.com" target="_blank" rel="noopener noreferrer">Whoisology</a> | Reverse WHOIS by email — find domains registered to the same email address | 🆓 💰 |

### Mail Blacklists & Security

| Tool | Description | Tags |
|------|-------------|------|
| <a href="https://mxtoolbox.com" target="_blank" rel="noopener noreferrer">MxToolbox</a> | Check mail server blacklist status and SPF/DKIM/DMARC records | 🆓 |

---

*Sections in progress: Social Networks, Domain & IP, People Search, Phone Numbers, Geolocation, Dark Web, Blockchain & Cryptocurrency, Image & Video Analysis, Public Records, Cyber Threat Intelligence, Documentation & Evidence Capture.*

---

## Contributing

This repository reflects tools that have been reviewed for investigative applicability. If you have suggestions, open an issue or submit a pull request.

---

## Disclaimer

All tools and resources listed are for lawful, ethical open source intelligence gathering only. Users are responsible for ensuring their activities comply with applicable laws and organizational policies.

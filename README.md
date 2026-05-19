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
| [Google](https://www.google.com) | Primary search engine. Supports advanced operators and dorking | 🆓 |
| [Bing](https://www.bing.com) | Microsoft search engine. Useful for results not indexed by Google | 🆓 |
| [DuckDuckGo](https://www.duckduckgo.com) | Privacy-focused. No personalized results, useful for neutral searches | 🆓 |
| [Yandex](https://www.yandex.com) | Russian search engine. Strong for reverse image search and Eastern European content | 🆓 |
| [Baidu](https://www.baidu.com) | Chinese search engine. Useful for subjects with ties to China | 🆓 |
| [Startpage](https://www.startpage.com) | Returns Google results anonymously | 🆓 |
| [Ahmia](https://ahmia.fi) | Surface web index of Tor hidden services | 🆓 |
| [Shodan](https://www.shodan.io) | Search engine for internet-connected devices and exposed services | 💰 📝 |
| [Censys](https://censys.io) | Internet-wide scanning and device enumeration | 💰 📝 |
| [Grep.app](https://grep.app) | Search across public GitHub repositories | 🆓 |

---

## Email Address

### Breach & Leak Search

| Tool | Description | Tags |
|------|-------------|------|
| [Have I Been Pwned](https://haveibeenpwned.com) | Check if an email appears in known data breaches. Gold standard for breach checks | 🆓 |
| [HudsonRock Cavalier](https://www.hudsonrock.com/threat-intelligence-cybercrime-tools) | Search infostealer-compromised credentials by email or domain. Checks stealer logs, not just breach dumps | 🆓 |
| [DeHashed](https://dehashed.com) | Search 15B+ leaked records by email, username, IP, or name. Requires account for full results | 🆓 💰 |
| [Intelligence X (IntelX)](https://intelx.io) | Search dark web leaks, breaches, and public sources by email. Covers Tor, I2P, and data dumps | 🆓 💰 |
| [LeakIX](https://leakix.net/search) | Search leaked and exposed data indexed from internet services. More infrastructure-focused than email-centric | 🆓 |
| [breach.vip](https://breach.vip) | Quick breach lookup by email address. Lightweight tool for fast checks | 🆓 |
| [Scam Search](https://scamsearch.io) | Search email addresses across known scam databases. Useful for fraud investigations | 🆓 |

### Email Search & Account Discovery

| Tool | Description | Tags |
|------|-------------|------|
| [Epieos](https://tools.epieos.com/email.php) | Find social accounts, Google profile, and services linked to an email. Based on Holehe methodology | 🆓 💰 |
| [OSINT Industries](https://www.osint.industries) | Search email against 200+ services to find linked accounts. Comprehensive account enumeration | 💰 📝 |
| [Hunter.io](https://hunter.io/email-verifier) | Verify if an email is deliverable and find associated domain info. Also identifies company email formats | 🆓 💰 |
| [ThatsThem](https://thatsthem.com/email) | Reverse email lookup for name, address, phone, and social profiles. Primarily US; limited Canadian data | 🆓 |
| [Skymem](https://www.skymem.info) | Find email addresses associated with a domain or person | 🆓 |
| [VoilaNorbert](https://www.voilanorbert.com) | Find professional email addresses by name and company domain | 🆓 💰 |
| [Email Format](https://www.email-format.com) | Reveals common email format patterns used by companies. Useful for identifying corporate targets | 🆓 |
| [Email Permutator](https://metricsparrow.com/toolkit/email-permutator/) | Generate possible email permutations for a given name and domain | 🆓 |

### Email Verification

| Tool | Description | Tags |
|------|-------------|------|
| [Reacher](https://reacher.email) | Real-time email verification — checks if inbox is active | 🆓 💰 |
| [EmailRep](https://emailrep.io) | Email reputation scoring — age, breach status, deliverability | 🆓 |
| [MailboxValidator](https://www.mailboxvalidator.com/demo) | Check if email is valid, disposable, or a known spam address | 🆓 |
| [Disposable Emails Registry](https://disposable-emails.github.io) | Check if an email domain is a known throwaway/disposable provider. Useful for screening suspicious contacts | 🆓 |

### Social & Google Account Pivot

| Tool | Description | Tags |
|------|-------------|------|
| [Epieos (Google pivot)](https://epieos.com) | Find Google profile, photo, and Maps reviews linked to a Gmail address. Pivots Gmail → Google Maps activity | 🆓 |
| [GHunt (web demo)](https://github.com/mxrch/GHunt) | Investigate Google accounts via email. Web-based limited demo available; full tool requires local install | 🆓 🔧 |
| [Gravatar](https://en.gravatar.com/emails) | Check if an email has a Gravatar profile image attached | 🆓 |
| [Whoisology](https://whoisology.com) | Reverse WHOIS by email — find domains registered to the same email address | 🆓 💰 |

### Mail Blacklists & Security

| Tool | Description | Tags |
|------|-------------|------|
| [MxToolbox](https://mxtoolbox.com) | Check mail server blacklist status and SPF/DKIM/DMARC records | 🆓 |

---

*Sections in progress: Username & Identity, Social Networks, Domain & IP, People Search, Phone Numbers, Geolocation, Dark Web, Blockchain & Cryptocurrency, Image & Video Analysis, Public Records, Cyber Threat Intelligence, Documentation & Evidence Capture.*

---

## Contributing

This repository reflects tools that have been reviewed for investigative applicability. If you have suggestions, open an issue or submit a pull request.

---

## Disclaimer

All tools and resources listed are for lawful, ethical open source intelligence gathering only. Users are responsible for ensuring their activities comply with applicable laws and organizational policies.

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
- [Image & Video Analysis](#image--video-analysis)

> Planned sections (not yet published): Geolocation, Dark Web, Blockchain & Cryptocurrency, Public Records, Cyber Threat Intelligence, Documentation & Evidence Capture.

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

## Social Networks

### Multi-Platform

| Tool | Description | Tags |
|------|-------------|------|
| <a href="https://www.social-searcher.com" target="_blank" rel="noopener noreferrer">Social Searcher</a> | Real-time search of hashtags and usernames across multiple platforms | 🆓 |
| <a href="https://www.idcrawl.com" target="_blank" rel="noopener noreferrer">IDCrawl</a> | Search name across major social networks | 🆓 |
| <a href="https://www.smat-app.com" target="_blank" rel="noopener noreferrer">SMAT App</a> | Disinformation tracker — monitors Gab, Parler, 4chan, Telegram, Gettr, Bitchute, TikTok. Useful for extremism and disinformation investigations | 🆓 |
| <a href="https://castrickclues.com" target="_blank" rel="noopener noreferrer">Castrick Clues</a> | Find social media accounts using email, username, or phone | 🆓 |
| <a href="https://epieos.com" target="_blank" rel="noopener noreferrer">Epieos</a> | Search social accounts linked to an email or phone number | 🆓 💰 |

### Facebook

| Tool | Description | Tags |
|------|-------------|------|
| <a href="https://www.facebook.com/login/identify?ctx=recover" target="_blank" rel="noopener noreferrer">Facebook Account Recovery</a> | Enter phone or email to find associated Facebook account. No login required. Primary method for email/phone → FB account | 🆓 |
| <a href="https://www.whopostedwhat.com" target="_blank" rel="noopener noreferrer">Who Posted What?</a> | Search Facebook posts by keyword and date range | 🆓 |
| <a href="https://www.fbdownloader.com" target="_blank" rel="noopener noreferrer">Facebook Video Downloader</a> | Download public Facebook videos by URL | 🆓 |
| <a href="https://haveibeenzuckered.com" target="_blank" rel="noopener noreferrer">HaveIBeenZuckered</a> | Check if a phone number is in the 533M Facebook data breach | 🆓 |
| <a href="https://graph.tips/beta/" target="_blank" rel="noopener noreferrer">Sowdust FB Graph Search</a> | Simplified interface for Facebook search after Graph Search closure | 🆓 |

### Instagram

| Tool | Description | Tags |
|------|-------------|------|
| <a href="https://inflact.com/instagram-viewer/profile/" target="_blank" rel="noopener noreferrer">Inflact Anonymous Viewer</a> | View public Instagram profiles anonymously | 🆓 |
| <a href="https://storysaver.net" target="_blank" rel="noopener noreferrer">StorySaver</a> | Download public Instagram stories, highlights, and videos | 🆓 |
| <a href="https://iganony.net" target="_blank" rel="noopener noreferrer">IgAnony</a> | View public Instagram profiles, stories, and posts anonymously | 🆓 |
| <a href="https://dumpoir.com" target="_blank" rel="noopener noreferrer">Dumpoir</a> | Anonymously view and download Instagram stories | 🆓 |

### Snapchat

| Tool | Description | Tags |
|------|-------------|------|
| <a href="https://www.osintcombine.com/snapchat-multi-viewer" target="_blank" rel="noopener noreferrer">OSINT Combine — Snapchat Multi-Viewer</a> | View multiple Snapchat map locations simultaneously | 🆓 |

### Twitter / X

| Tool | Description | Tags |
|------|-------------|------|
| <a href="https://twitter.com/search-advanced" target="_blank" rel="noopener noreferrer">Twitter Advanced Search</a> | Search by keyword, account, date range, and location | 🆓 |
| <a href="https://twitter.com/search?q=geocode%3ALAT%2CLNG%2CRADIUSkm" target="_blank" rel="noopener noreferrer">Twitter Location Search (M)</a> | Geofenced tweet search. Replace LAT/LNG/RADIUS in URL. Location can be faked | 🆓 |
| <a href="https://nitter.net/" target="_blank" rel="noopener noreferrer">Nitter</a> | View Twitter/X profiles without an account or JavaScript enabled. Useful for anonymous browsing | 🆓 |
| <a href="http://geosocialfootprint.com/" target="_blank" rel="noopener noreferrer">GeoSocial Footprint</a> | Visualize the geographic footprint of a Twitter account from geotagged tweets | 🆓 |
| <a href="https://socialbearing.com/" target="_blank" rel="noopener noreferrer">Socialbearing</a> | Twitter analytics — tweet frequency, engagement, hashtag analysis | 🆓 |
| <a href="https://tweepdiff.com" target="_blank" rel="noopener noreferrer">TweepDiff</a> | Compare followers and following between two Twitter accounts | 🆓 |

### Telegram

| Tool | Description | Tags |
|------|-------------|------|
| <a href="https://cse.google.com/cse?cx=006368593537057042503:efxu7xprihg" target="_blank" rel="noopener noreferrer">Telegago (Google CSE)</a> | Google-powered search for public and private Telegram channels | 🆓 |
| <a href="https://tgstat.com" target="_blank" rel="noopener noreferrer">TGstat</a> | Search Telegram channels; channel analytics and archives | 🆓 |
| <a href="https://telesearch.me" target="_blank" rel="noopener noreferrer">TeleSearch</a> | Search Telegram channels, groups, and bots by keyword | 🆓 |
| <a href="https://intelx.io/tools?tab=telegram" target="_blank" rel="noopener noreferrer">Intelligence X Telegram Search</a> | Google-based Telegram search via IntelX | 🆓 |
| <a href="https://tgramsearch.com" target="_blank" rel="noopener noreferrer">Telegram Channel Finder</a> | Search catalogue of 700,000+ Telegram channels | 🆓 |

### Reddit

| Tool | Description | Tags |
|------|-------------|------|
| <a href="https://atomiks.github.io/reddit-user-analyser/" target="_blank" rel="noopener noreferrer">Reddit User Analyser</a> | Analyse a Reddit user account — post history, activity, word frequency | 🆓 |
| <a href="https://pullpush.io" target="_blank" rel="noopener noreferrer">Pullpush.io</a> | Retrieve deleted or removed Reddit posts and comments | 🆓 |
| <a href="https://redditcommentsearch.com" target="_blank" rel="noopener noreferrer">Reddit Comment Search</a> | Search a user's full comment history | 🆓 |
| <a href="https://www.redective.com" target="_blank" rel="noopener noreferrer">Redective</a> | Reddit profile analysis — active hours, word frequency | 🆓 |
| <a href="https://archive.4plebs.org" target="_blank" rel="noopener noreferrer">4plebs Archive</a> | Searchable archive of 4chan boards | 🆓 |
| <a href="https://www.unddit.com/" target="_blank" rel="noopener noreferrer">Unddit</a> | Recover deleted Reddit posts and comments using Pushshift archives | 🆓 |
| <a href="https://removeddit.net" target="_blank" rel="noopener noreferrer">Removeddit</a> | Retrieve deleted Reddit content via alternative Pushshift front-end | 🆓 |
| <a href="https://www.osintcombine.com/reddit-post-analyser" target="_blank" rel="noopener noreferrer">OSINT Combine — Reddit Post Analyzer</a> | Analyze a Reddit user's post history, subreddit activity, and posting patterns | 🆓 |
| <a href="https://redditsearch.io" target="_blank" rel="noopener noreferrer">Reddit Search (redditsearch.io)</a> | Advanced Reddit full-text search across all subreddits | 🆓 |

### YouTube

| Tool | Description | Tags |
|------|-------------|------|
| <a href="https://mattwright324.github.io/youtube-geofind/" target="_blank" rel="noopener noreferrer">YouTube Geofind (mattwright324)</a> | Search YouTube videos by geographic coordinates | 🆓 |
| <a href="https://mattw.io/youtube-geofind/location" target="_blank" rel="noopener noreferrer">YouTube Geofind (mattw.io)</a> | Find geotagged YouTube videos by location coordinates. Companion tool to the above | 🆓 |
| <a href="https://mattw.io/youtube-metadata/" target="_blank" rel="noopener noreferrer">YouTube Metadata</a> | Extract detailed metadata from YouTube video URLs | 🆓 |
| <a href="https://citizenevidence.amnestyusa.org" target="_blank" rel="noopener noreferrer">Amnesty YouTube Dataviewer</a> | Reverse image search of video frames; returns exact upload time | 🆓 |
| <a href="https://hadzy.com" target="_blank" rel="noopener noreferrer">Hadzy — YouTube Comments</a> | Search and analyse YouTube video comments | 🆓 |

### Video Downloading & Frame Analysis

| Tool | Description | Tags |
|------|-------------|------|
| <a href="https://github.com/yt-dlp/yt-dlp#installation" target="_blank" rel="noopener noreferrer">yt-dlp</a> | Command-line tool to download videos from YouTube and 1000+ sites. Best for court-ready downloads | 🆓 🔧 |
| <a href="https://y2mate.com" target="_blank" rel="noopener noreferrer">y2mate</a> | Browser-based YouTube video and audio downloader. No install required | 🆓 |
| <a href="https://watchframebyframe.com" target="_blank" rel="noopener noreferrer">Watch Frame by Frame</a> | Play YouTube videos frame by frame for image analysis and timestamp verification | 🆓 |

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

## Domain & IP

### WHOIS & Domain Registration

| Tool | Description | Tags |
|------|-------------|------|
| <a href="https://viewdns.info" target="_blank" rel="noopener noreferrer">ViewDNS.info</a> | Multi-tool — WHOIS, reverse IP, DNS records, IP history | 🆓 |
| <a href="https://who.is" target="_blank" rel="noopener noreferrer">Who.is</a> | Domain WHOIS lookup | 🆓 |
| <a href="https://whois.domaintools.com" target="_blank" rel="noopener noreferrer">DomainTools WHOIS</a> | WHOIS lookup with historical data | 🆓 💰 |
| <a href="https://whoisology.com" target="_blank" rel="noopener noreferrer">Whoisology</a> | Reverse WHOIS — find all domains registered to an email or name | 🆓 💰 |
| <a href="https://www.whoxy.com" target="_blank" rel="noopener noreferrer">Whoxy</a> | Reverse WHOIS by email, name, company, or phone | 🆓 |
| <a href="https://lookup.icann.org/en/lookup" target="_blank" rel="noopener noreferrer">ICANN Lookup</a> | Official ICANN domain registration lookup. Authoritative source | 🆓 |
| <a href="https://centralops.net/co/DomainDossier.aspx" target="_blank" rel="noopener noreferrer">Domain Dossier</a> | Comprehensive domain report — WHOIS, DNS, traceroute, spam data | 🆓 |
| <a href="https://www.ip2whois.com" target="_blank" rel="noopener noreferrer">IP2WHOIS</a> | WHOIS lookup by domain or IP | 🆓 |
| <a href="https://whois.cira.ca" target="_blank" rel="noopener noreferrer">CIRA WHOIS (.ca)</a> | Official .ca domain WHOIS via the Canadian Internet Registration Authority. Authoritative for .ca domains | 🆓 |
| <a href="https://whois.arin.net/ui/" target="_blank" rel="noopener noreferrer">ARIN WHOIS</a> | American Registry for Internet Numbers — IP block ownership lookup. North American IP allocations | 🆓 |

### IP Address Lookup

| Tool | Description | Tags |
|------|-------------|------|
| <a href="https://www.ipaddress.com" target="_blank" rel="noopener noreferrer">IPAddress.com</a> | IP lookup — geolocation, ISP, hostname | 🆓 |
| <a href="https://dnschecker.org" target="_blank" rel="noopener noreferrer">DNSChecker</a> | DNS propagation check and IP/domain lookup | 🆓 |
| <a href="https://www.ip-lookup.org/location" target="_blank" rel="noopener noreferrer">IP-Lookup.org</a> | IP geolocation lookup | 🆓 |
| <a href="https://www.iplocation.net/ip-lookup" target="_blank" rel="noopener noreferrer">IPLocation.net</a> | IP geolocation with multiple provider results | 🆓 |
| <a href="https://www.maxmind.com/en/home" target="_blank" rel="noopener noreferrer">MaxMind GeoIP</a> | IP geolocation and intelligence. Industry standard | 🆓 💰 |
| <a href="https://ipinfo.io/" target="_blank" rel="noopener noreferrer">IPinfo.io</a> | IP geolocation, ASN, ISP, hostname lookup. Clean UI and API | 🆓 💰 |
| <a href="https://www.shodan.io" target="_blank" rel="noopener noreferrer">Shodan</a> | Search internet-connected devices, open ports, and services by IP | 💰 📝 |

### DNS Analysis

| Tool | Description | Tags |
|------|-------------|------|
| <a href="https://dnsdumpster.com" target="_blank" rel="noopener noreferrer">DNSDumpster</a> | DNS reconnaissance — find subdomains, MX, TXT, NS records | 🆓 |
| <a href="https://completedns.com/dns-history/" target="_blank" rel="noopener noreferrer">DNS History (CompleteDNS)</a> | Historical DNS records by domain | 🆓 |
| <a href="https://securitytrails.com/dns-trails" target="_blank" rel="noopener noreferrer">SecurityTrails</a> | Current and historical DNS, WHOIS, and IP data | 🆓 💰 |
| <a href="https://mxtoolbox.com" target="_blank" rel="noopener noreferrer">MxToolbox DNS</a> | DNS, MX, blacklist, and mail server analysis | 🆓 |
| <a href="https://dnsviz.net" target="_blank" rel="noopener noreferrer">DNSViz</a> | Visual DNSSEC analysis tool | 🆓 |
| <a href="https://dnslytics.com/reverse-analytics" target="_blank" rel="noopener noreferrer">DNSlytics — Reverse Analytics</a> | Find websites sharing the same Google Analytics or AdSense tracking ID | 🆓 |

### Certificate Search

| Tool | Description | Tags |
|------|-------------|------|
| <a href="https://crt.sh" target="_blank" rel="noopener noreferrer">crt.sh</a> | Search SSL/TLS certificate transparency logs by domain. Reveals subdomains via cert history | 🆓 |
| <a href="https://www.certkit.io/tools/ct-logs/" target="_blank" rel="noopener noreferrer">CertKit CT Log Search</a> | Fast certificate transparency search | 🆓 |
| <a href="https://search.censys.io" target="_blank" rel="noopener noreferrer">Censys</a> | Search internet-connected devices and TLS certificates | 💰 📝 |

### Website Analysis

| Tool | Description | Tags |
|------|-------------|------|
| <a href="https://builtwith.com" target="_blank" rel="noopener noreferrer">BuiltWith</a> | Identify technology stack of any website | 🆓 |
| <a href="https://www.wappalyzer.com" target="_blank" rel="noopener noreferrer">Wappalyzer</a> | Identify CMS, analytics, and technology used by a site | 🆓 |
| <a href="https://www.spyonweb.com" target="_blank" rel="noopener noreferrer">SpyOnWeb</a> | Find related websites sharing the same analytics or ad tracking ID | 🆓 |
| <a href="https://analyzeid.com" target="_blank" rel="noopener noreferrer">AnalyzeID</a> | Find other websites owned by the same person via shared tracking IDs | 🆓 |
| <a href="https://urlscan.io" target="_blank" rel="noopener noreferrer">URLScan.io</a> | Scan and analyse a URL — screenshot, tech stack, network requests | 🆓 |
| <a href="https://www.virustotal.com" target="_blank" rel="noopener noreferrer">VirusTotal</a> | Analyze suspicious URLs, domains, and IPs for malware and threats | 🆓 |
| <a href="https://securityheaders.com/" target="_blank" rel="noopener noreferrer">SecurityHeaders.com</a> | Analyze HTTP response headers of any website for security configuration | 🆓 |
| <a href="https://faviconhash.com/" target="_blank" rel="noopener noreferrer">Faviconhash</a> | Generate and search favicon hashes to pivot on web infrastructure. Useful for infrastructure attribution | 🆓 |

### Web History & Archiving

| Tool | Description | Tags |
|------|-------------|------|
| <a href="https://web.archive.org" target="_blank" rel="noopener noreferrer">Wayback Machine</a> | Archived snapshots of websites going back decades | 🆓 |
| <a href="https://archive.today" target="_blank" rel="noopener noreferrer">Archive.today</a> | Manually archive a webpage; retrieve archived copies. Captures Facebook and Instagram pages | 🆓 |
| <a href="https://cachedview.com" target="_blank" rel="noopener noreferrer">CachedView</a> | View cached versions of web pages | 🆓 |

### IP Reputation & Threat Intelligence

| Tool | Description | Tags |
|------|-------------|------|
| <a href="https://greynoise.io/" target="_blank" rel="noopener noreferrer">GreyNoise Intelligence</a> | Identifies IPs that mass-scan the internet. Separates background noise from targeted activity | 🆓 💰 |
| <a href="https://talosintelligence.com/reputation_center/" target="_blank" rel="noopener noreferrer">Cisco Talos IP Reputation</a> | Check IP and domain reputation against Cisco Talos threat intelligence | 🆓 |
| <a href="https://getipintel.net/" target="_blank" rel="noopener noreferrer">getipintel.net</a> | API to check if an IP is a proxy, VPN, or Tor exit node | 🆓 |
| <a href="https://spur.us" target="_blank" rel="noopener noreferrer">Spur.us</a> | Identify VPNs, proxies, and residential proxy networks by IP address. Strong VPN/proxy identification | 🆓 💰 |
| <a href="https://urlhaus.abuse.ch/browse/" target="_blank" rel="noopener noreferrer">URLhaus (abuse.ch)</a> | Database of malicious URLs. Check if a domain/URL is flagged for malware distribution | 🆓 |
| <a href="https://www.zoomeye.org/" target="_blank" rel="noopener noreferrer">ZoomEye</a> | Chinese equivalent of Shodan. Search internet-connected devices and services. Useful for Chinese infrastructure | 🆓 💰 |
| <a href="https://criminalip.io" target="_blank" rel="noopener noreferrer">Criminal IP</a> | OSINT-based cyber threat intelligence for IP and domain investigation | 🆓 💰 |
| <a href="https://ps3cfw.com" target="_blank" rel="noopener noreferrer">ps3CFW — CloudFlare Resolver</a> | Attempts to uncover real IP addresses behind Cloudflare protection. Also flags VPNs. Verify lawful use in jurisdiction | 🆓 |
| <a href="https://metadefender.opswat.com/" target="_blank" rel="noopener noreferrer">MetaDefender Cloud</a> | Scan files, IPs, URLs, and domains against multiple threat intelligence sources | 🆓 |
| <a href="https://community.riskiq.com/login" target="_blank" rel="noopener noreferrer">RiskIQ Community Edition</a> | Attack surface intelligence — passive DNS, certificates, web components | 🆓 📝 |

---

## People Search

### General People Search

| Tool | Description | Tags |
|------|-------------|------|
| <a href="https://www.truepeoplesearch.com" target="_blank" rel="noopener noreferrer">TruePeopleSearch</a> | Search by name, address, or phone for US individuals. Primarily US; limited Canadian coverage | 🆓 |
| <a href="https://www.fastpeoplesearch.com" target="_blank" rel="noopener noreferrer">FastPeopleSearch</a> | Name, phone, and address search. Primarily US | 🆓 |
| <a href="https://nuwber.com" target="_blank" rel="noopener noreferrer">Nuwber</a> | People search by name, phone, email, or address. Primarily US | 🆓 💰 |
| <a href="https://radaris.com" target="_blank" rel="noopener noreferrer">Radaris</a> | Aggregates public records and social profiles. Primarily US and Canada | 🆓 💰 |
| <a href="https://webmii.com" target="_blank" rel="noopener noreferrer">WebMii</a> | Aggregates web presence and social profiles. Global coverage | 🆓 |
| <a href="https://www.idcrawl.com" target="_blank" rel="noopener noreferrer">IDCrawl</a> | Search name or username across social networks and public data. Global | 🆓 |
| <a href="https://www.zabasearch.com" target="_blank" rel="noopener noreferrer">ZabaSearch</a> | US people search using public records. US only | 🆓 |
| <a href="https://www.social-searcher.com" target="_blank" rel="noopener noreferrer">Social Searcher</a> | Search a name or keyword across social platforms in real time. Global | 🆓 |
| <a href="https://www.spokeo.com" target="_blank" rel="noopener noreferrer">Spokeo</a> | People search by name, email, phone — public record aggregator. Primarily US | 💰 |
| <a href="https://pipl.com" target="_blank" rel="noopener noreferrer">Pipl</a> | Professional identity resolution tool used by investigators. Global; requires account | 💰 📝 |
| <a href="https://www.cyberbackgroundchecks.com" target="_blank" rel="noopener noreferrer">CyberBackgroundChecks</a> | Background check and people search. US primarily | 🆓 💰 |
| <a href="https://www.familytreenow.com" target="_blank" rel="noopener noreferrer">FamilyTreeNow</a> | Genealogy and people search using public records. US primarily; useful for historical connections | 🆓 |
| <a href="https://cipher387.github.io/osintmap/" target="_blank" rel="noopener noreferrer">Worldwide OSINT Tools Map</a> | Interactive map of white/yellow pages and people search tools by country. Useful for country-specific directories | 🆓 |
| <a href="https://www.canada411.ca" target="_blank" rel="noopener noreferrer">Canada 411</a> | Canadian residential and business phone/address directory. Primary directory for Canadian lookups | 🆓 |

### Court Records & Criminal History

| Tool | Description | Tags |
|------|-------------|------|
| <a href="https://www.judyrecords.com" target="_blank" rel="noopener noreferrer">Judyrecords</a> | Free nationwide search of 400M+ US court cases. US only | 🆓 |
| <a href="https://unicourt.com" target="_blank" rel="noopener noreferrer">UniCourt</a> | US federal and state court record search. US only | 🆓 💰 |
| <a href="https://pacer.uscourts.gov" target="_blank" rel="noopener noreferrer">PACER (US Federal Courts)</a> | Official US federal court records repository. Paid per page; US federal only | 💰 📝 |
| <a href="https://aleph.occrp.org" target="_blank" rel="noopener noreferrer">OCCRP Aleph</a> | Search public records, leaks, and court data from 236 sources. Global; strong for financial and organized crime research. Apply for full access | 🆓 📝 |
| <a href="https://www.opensanctions.org/search" target="_blank" rel="noopener noreferrer">OpenSanctions</a> | Search international sanctions lists and politically exposed persons. Global | 🆓 |

### Social Media People Search

| Tool | Description | Tags |
|------|-------------|------|
| <a href="https://www.facebook.com/login/identify?ctx=recover" target="_blank" rel="noopener noreferrer">Facebook Account Recovery Search</a> | Enter phone or email to find associated Facebook account. Does not require login. Useful for linking phone/email to FB | 🆓 |
| <a href="https://inflact.com/instagram-viewer/profile/" target="_blank" rel="noopener noreferrer">Anonymous Instagram Viewer</a> | View public Instagram profile anonymously without an account. Global | 🆓 |
| <a href="https://myspace.com/search/people?q=" target="_blank" rel="noopener noreferrer">Myspace Search</a> | Search legacy Myspace profiles — still useful for old usernames. Append name to URL | 🆓 |
| <a href="https://www.linkedin.com/search/results/people/" target="_blank" rel="noopener noreferrer">LinkedIn</a> | Search professional profiles by name, company, location. Global | 🆓 💰 |
| <a href="https://www.skype.com/en/" target="_blank" rel="noopener noreferrer">Skype Search</a> | Search Skype by name, email, or phone number. Requires Skype account | 🆓 📝 |
| <a href="https://bellingcat.github.io/name-variant-search/" target="_blank" rel="noopener noreferrer">Bellingcat Name Variant Search</a> | Generate name variant spellings for cross-cultural searches. Useful for translated/transliterated names | 🆓 |

---

## Phone Numbers

### Reverse Phone Lookup

| Tool | Description | Tags |
|------|-------------|------|
| <a href="https://www.phonevalidator.com/index.aspx" target="_blank" rel="noopener noreferrer">Phone Validator</a> | Accurate phone lookup; carrier, line type, owner name. Strong US/Canada coverage | 🆓 |
| <a href="https://numpi.com" target="_blank" rel="noopener noreferrer">Numpi</a> | Reverse phone lookup and carrier identification. Global | 🆓 |
| <a href="https://nuwber.com" target="_blank" rel="noopener noreferrer">Nuwber Phone Lookup</a> | Reverse lookup by phone — returns name and address. Primarily US | 🆓 💰 |
| <a href="https://www.whoseno.com" target="_blank" rel="noopener noreferrer">WhoSeNo</a> | Reverse phone number lookup. Global | 🆓 |
| <a href="https://www.freecarrierlookup.com" target="_blank" rel="noopener noreferrer">FreeCarrierLookup</a> | Returns carrier name and line type (landline/mobile/VoIP). US and Canada | 🆓 |
| <a href="https://www.truecaller.com" target="_blank" rel="noopener noreferrer">TrueCaller</a> | Global caller ID and spam database. Particularly strong in South Asia. Do not grant contact list access | 🆓 |
| <a href="https://www.getcontact.com" target="_blank" rel="noopener noreferrer">GetContact</a> | Crowdsourced caller ID — reveals how contacts are saved by others. Do not grant contact list access | 🆓 |
| <a href="https://www.canada411.ca" target="_blank" rel="noopener noreferrer">Canada 411</a> | Canadian residential and business directory by phone number. Primary Canadian phone lookup | 🆓 |
| <a href="https://thatsthem.com/reverse-phone-lookup" target="_blank" rel="noopener noreferrer">ThatsThem Phone Lookup</a> | Reverse phone lookup — name, address, email. Primarily US | 🆓 |
| <a href="https://www.reversephonecheck.com" target="_blank" rel="noopener noreferrer">Reverse Phone Check</a> | Lookup name and address from phone number. US primarily | 🆓 |
| <a href="https://spydialer.com" target="_blank" rel="noopener noreferrer">Spy Dialer</a> | Retrieve voicemail greeting and owner name for cell numbers. US primarily | 🆓 |
| <a href="https://www.usphonebook.com" target="_blank" rel="noopener noreferrer">USPhoneBook</a> | Reverse phone and address lookup. US only | 🆓 |

### WhatsApp & Messaging Platform Checks

| Tool | Description | Tags |
|------|-------------|------|
| <a href="https://whatsapp.checkleaked.cc" target="_blank" rel="noopener noreferrer">WhatsApp CheckLeaked</a> | Check if a phone number has a WhatsApp account; view profile photo. Global | 🆓 |
| <a href="https://watools.io" target="_blank" rel="noopener noreferrer">WATools.io</a> | Check if number is on WhatsApp; download profile picture. Global | 🆓 💰 |
| <a href="https://2chat.co/tools/whatsapp-checker" target="_blank" rel="noopener noreferrer">2Chat WhatsApp Checker</a> | Verify if a phone number is registered on WhatsApp. Global | 🆓 |
| <a href="https://github.com/bellingcat/telegram-phone-number-checker" target="_blank" rel="noopener noreferrer">Bellingcat Phone → Telegram</a> | Check if a phone number is linked to a Telegram account. GitHub-based; web demo may be available | 🆓 🔧 |

### Carrier & Line Type

| Tool | Description | Tags |
|------|-------------|------|
| <a href="https://www.twilio.com/docs/lookup/v2-api" target="_blank" rel="noopener noreferrer">Twilio Lookup (API)</a> | Lookup carrier, line type, and location. Global; approximately $0.01–0.02 per lookup. Requires free account | 🆓 💰 📝 |
| <a href="https://www.freecarrierlookup.com" target="_blank" rel="noopener noreferrer">FreeCarrierLookup</a> | Returns carrier and landline/mobile/VoIP type. US and Canada | 🆓 |

### Canadian Carrier & Number Lookups

| Tool | Description | Tags |
|------|-------------|------|
| <a href="https://www.cnac.ca/co_codes/co_code_lookup.htm" target="_blank" rel="noopener noreferrer">Canadian Numbering Administration (CNAC)</a> | Lookup Canadian phone number carrier and NPA-NXX code. Official CRTC-recognized database. Authoritative Canadian carrier lookup | 🆓 |
| <a href="https://www.npanxxsource.com/" target="_blank" rel="noopener noreferrer">NANPA NXX Source</a> | North American Numbering Plan carrier and number portability data | 🆓 |
| <a href="https://phonelookup.lexisnexisrisk.com/welcome" target="_blank" rel="noopener noreferrer">LexisNexis Phone Lookup (LE Only)</a> | Law enforcement-only free phone lookup. Canada/US. Use LE institutional email to register | 🆓 📝 |
| <a href="https://nationalnanpa.com/enas/npa_query.do" target="_blank" rel="noopener noreferrer">Area Code Lookup — NANPA</a> | Official NANPA area code and NPA query tool. North America | 🆓 |
| <a href="https://gsmarena.com" target="_blank" rel="noopener noreferrer">GSM Arena — Device Database</a> | Identify mobile device models by specs. Useful for identifying device from IMEI/photos | 🆓 |
| <a href="https://phonescoop.com" target="_blank" rel="noopener noreferrer">Phone Scoop — Device Database</a> | Mobile phone specifications and model identification database | 🆓 |

---

## Image & Video Analysis

### Reverse Image Search

| Tool | Description | Tags |
|------|-------------|------|
| <a href="https://lens.google.com" target="_blank" rel="noopener noreferrer">Google Lens</a> | Upload or paste image for reverse search. Best general coverage | 🆓 |
| <a href="https://yandex.com/images" target="_blank" rel="noopener noreferrer">Yandex Images</a> | Strong reverse image search, particularly for Eastern European content. Often finds results Google misses | 🆓 |
| <a href="https://tineye.com" target="_blank" rel="noopener noreferrer">TinEye</a> | Reverse image search with date-of-first-appearance tracking | 🆓 |
| <a href="https://www.bing.com/images" target="_blank" rel="noopener noreferrer">Bing Visual Search</a> | Microsoft's reverse image search | 🆓 |
| <a href="https://rootabout.com" target="_blank" rel="noopener noreferrer">RootAbout</a> | Reverse image search on the Internet Archive. Finds images removed from live web | 🆓 |
| <a href="http://karmadecay.com" target="_blank" rel="noopener noreferrer">KarmaDecay</a> | Reverse image search specifically for Reddit | 🆓 |

### Facial Recognition

| Tool | Description | Tags |
|------|-------------|------|
| <a href="https://pimeyes.com" target="_blank" rel="noopener noreferrer">PimEyes</a> | Face search engine across public web. Privacy-sensitive — use in accordance with applicable law | 🆓 💰 |
| <a href="https://search4faces.com" target="_blank" rel="noopener noreferrer">Search4Faces</a> | Reverse face search in VKontakte, Odnoklassniki, and TikTok databases. Strongest for Russian-language platforms | 🆓 |
| <a href="https://facecheck.id" target="_blank" rel="noopener noreferrer">FaceCheck.ID</a> | Facial recognition search across the public internet | 🆓 💰 |

### Image Metadata & Forensics

| Tool | Description | Tags |
|------|-------------|------|
| <a href="https://jimpl.com" target="_blank" rel="noopener noreferrer">Jimpl EXIF Viewer</a> | Online EXIF/metadata viewer for photos | 🆓 |
| <a href="https://www.metadata2go.com" target="_blank" rel="noopener noreferrer">Metadata2go</a> | Extract metadata from photos and videos online | 🆓 |
| <a href="http://fotoforensics.com" target="_blank" rel="noopener noreferrer">FotoForensics</a> | Error Level Analysis and other forensic tools for image authenticity | 🆓 |
| <a href="https://29a.ch/photo-forensics/" target="_blank" rel="noopener noreferrer">Forensically</a> | Web-based image forensics — clone detection, noise analysis, ELA | 🆓 |
| <a href="https://exifeditor.io" target="_blank" rel="noopener noreferrer">ExifEditor.io</a> | View, edit, and analyze EXIF metadata in the browser | 🆓 |
| <a href="https://exif.tools" target="_blank" rel="noopener noreferrer">Exif.tools</a> | Online EXIF metadata extractor supporting a wide range of file types | 🆓 |
| <a href="https://exifdata.com" target="_blank" rel="noopener noreferrer">EXIF Data Viewer</a> | View and download EXIF metadata from uploaded images | 🆓 |
| <a href="https://exiftool.org/" target="_blank" rel="noopener noreferrer">ExifTool (Phil Harvey)</a> | Industry-standard metadata reader/writer. Most comprehensive EXIF tool. Command-line | 🆓 🔧 |

### AI Image Detection

| Tool | Description | Tags |
|------|-------------|------|
| <a href="https://www.aiornot.com" target="_blank" rel="noopener noreferrer">AI or Not</a> | Detect if an image was AI-generated | 🆓 |
| <a href="https://hivemoderation.com/ai-generated-content-detection" target="_blank" rel="noopener noreferrer">Hive AI Content Detection</a> | Detect AI-generated images and text | 🆓 |
| <a href="https://gptzero.me" target="_blank" rel="noopener noreferrer">GPTZero</a> | Detect AI-generated text content | 🆓 |

### Geolocation from Images

| Tool | Description | Tags |
|------|-------------|------|
| <a href="https://www.suncalc.org" target="_blank" rel="noopener noreferrer">SunCalc</a> | Estimate time of day and date from shadow direction in photos | 🆓 |
| <a href="https://geospy.web.app" target="_blank" rel="noopener noreferrer">GeoSpy</a> | AI-based geolocation estimation from image content | 🆓 |
| <a href="https://geohints.com" target="_blank" rel="noopener noreferrer">GeoHints</a> | Reference for identifying locations via traffic lights, bollards, road signs. Manual reference tool | 🆓 |
| <a href="https://calculator.ipvm.com" target="_blank" rel="noopener noreferrer">IPVM Camera Calculator</a> | Simulate camera viewing angles for geolocation from surveillance imagery | 🆓 |
| <a href="https://peakvisor.com" target="_blank" rel="noopener noreferrer">PeakVisor</a> | Mountain identification from photos using terrain profiles | 🆓 |

### Video Tools

| Tool | Description | Tags |
|------|-------------|------|
| <a href="https://citizenevidence.amnestyusa.org" target="_blank" rel="noopener noreferrer">Amnesty YouTube Dataviewer</a> | Extract video stills for reverse image search; returns exact upload timestamp | 🆓 |
| <a href="https://mattw.io/youtube-metadata/" target="_blank" rel="noopener noreferrer">YouTube Metadata</a> | Full metadata extraction from YouTube videos | 🆓 |
| <a href="https://mattwright324.github.io/youtube-geofind/" target="_blank" rel="noopener noreferrer">YouTube Geofind</a> | Search YouTube videos by GPS coordinates | 🆓 |

### Image Editing & Utilities

| Tool | Description | Tags |
|------|-------------|------|
| <a href="https://irfanview.com" target="_blank" rel="noopener noreferrer">IrfanView</a> | Free image viewer with batch processing, metadata viewing, and format conversion. Windows primarily | 🆓 🔧 |
| <a href="https://remove.bg" target="_blank" rel="noopener noreferrer">Remove.bg</a> | AI-powered background removal from images. Useful for subject isolation | 🆓 💰 |
| <a href="https://huggingface.co/spaces/felixrosberg/face-swap" target="_blank" rel="noopener noreferrer">Face Swap Tool (HuggingFace)</a> | AI face-swap tool for understanding and testing deepfake/morphing capabilities. Use only for lawful investigative purposes | 🆓 |

### Intimate Image Removal Resources

| Tool | Description | Tags |
|------|-------------|------|
| <a href="https://www.stopncii.org/" target="_blank" rel="noopener noreferrer">StopNCII</a> | Hash-based system preventing spread of non-consensual intimate images across participating platforms | 🆓 |
| <a href="https://takeitdown.ncmec.org/" target="_blank" rel="noopener noreferrer">Take It Down (NCMEC)</a> | NCMEC service removing intimate images of minors using hash matching. US-based but global platform participation | 🆓 |
| <a href="https://needhelpnow.ca" target="_blank" rel="noopener noreferrer">NeedHelpNow.ca</a> | Canadian resource for removing intimate images. Tailored for Canadian cases. Supported by MediaSmarts | 🆓 |

---

## Contributing

This repository reflects tools that have been reviewed for investigative applicability. If you have suggestions, open an issue or submit a pull request.

---

## Disclaimer

All tools and resources listed are for lawful, ethical open source intelligence gathering only. Users are responsible for ensuring their activities comply with applicable laws and organizational policies.

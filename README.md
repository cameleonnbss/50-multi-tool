# 🔍 Multi Tool V5 — By camzzz

> OSINT / Network / Phone / Mail / Breach — 44+ modules
> https://github.com/cameleonnbss
> 
> <img width="1186" height="1039" alt="image" src="https://github.com/user-attachments/assets/dd19b91a-ccae-4644-9a42-9eb92e6e2bd7" />


---

## 📋 Description

Multi Tool V5 is a terminal-based OSINT and network reconnaissance toolkit written in Python.
It includes 44+ modules covering IP analysis, phone number intelligence, email OSINT,
data breach search, username tracking, subdomain discovery, and much more.

**For educational and research purposes only.**
**Do NOT use on systems or people without explicit authorization.**

---

## ⚡ Quick Start

```bash
git clone https://github.com/cameleonnbss/50-multi-tool
cd 50-multi-tool
pip install -r requirements.txt
python multitool_v5.py
```

---

## 🛠️ Installation

### 1 — Clone the repository

```bash
git clone https://github.com/cameleonnbss/50-multi-tool
cd 50-multi-tool
```

### 2 — Install dependencies

```bash
pip install -r requirements.txt
```

### 3 — Run

```bash
python multitool_v5.py
```

---

## 📦 Requirements

| Package    | Purpose                        |
|------------|--------------------------------|
| colorama   | Terminal colours and styling   |
| requests   | HTTP requests / API calls      |
| Pillow     | Image EXIF metadata extraction |

Install with:

```bash
pip install colorama requests Pillow
```

---

## 🗂️ Modules

### 🌐 Network / IP
| # | Module | Description |
|---|--------|-------------|
| 1 | IP Info & Tracker | Own IP / any IP / reputation / range scanner |
| 2 | DNS Lookup | A, MX, NS, TXT, AAAA, CAA, SOA, CNAME |
| 3 | Port Scanner | Common / 1-1024 / custom range |
| 4 | Geo IP Tracker | Country, city, ISP, ASN, map links |
| 5 | Network Info | Local machine + public IP |
| 6 | WHOIS / Reverse DNS | Domain WHOIS + IP reverse lookup |
| 7 | Subdomain Finder | 80+ common subdomain wordlist |
| 8 | ASN / BGP Lookup | Prefix info via BGPView API |
| 9 | Quick Recon | All-in-one domain scan |
| 10 | IP Range Scanner | Scan full /24 subnet for live hosts |

### 🌍 Web / Domain
| # | Module | Description |
|---|--------|-------------|
| 11 | HTTP Header Inspector | Full headers + security audit |
| 12 | SSL Certificate Inspector | Subject, issuer, SANs, expiry |
| 13 | Tech Detector | 30+ CMS / frameworks detection |
| 14 | URL Redirect Tracer | Full redirect chain |
| 15 | Robots / Sitemap Reader | robots.txt + sitemap.xml |
| 16 | Wayback Machine | Latest snapshot info |
| 17 | Wayback URL Extractor | 100 historical URLs via CDX API |
| 18 | Google Dork Generator | 18 pre-built dorks |
| 19 | Advanced Dork Builder | Custom dork constructor |
| 20 | File / Doc OSINT | PDF, DOC, XLS, ENV, SQL, BAK... |

### 📱 Phone / Mail / Breach
| # | Module | Description |
|---|--------|-------------|
| 21 | Phone Number Info | Country, region, timezone, format, FR line type, validity, 14 OSINT links |
| 22 | Mail / Email OSINT | Full analysis, domain DNS, format guesser, header analyser, disposable checker |
| 23 | Breach Search Engine | ZSearcher.fr, OathNet.org, HIBP API, all 20 breach DBs, password k-anonymity |
| 24 | Username Tracker | 55 platforms scanned in parallel |
| 25 | Profile Builder | Name + username + email search links |
| 26 | Reverse Image Search | Google, Bing, Yandex, TinEye, SauceNAO |
| 27 | Social Media Search | 12 platforms |
| 28 | Public Records Search | 10 people-finder services |
| 29 | Paste Search | Pastebin, Gist, Grep.app, Psbdmp |

### 🔬 Intel / Advanced
| # | Module | Description |
|---|--------|-------------|
| 30 | Shodan / Censys Links | Shodan, Censys, ZoomEye, Greynoise, OTX... |
| 31 | CVE / Vuln Search | NVD, Exploit-DB, Snyk, GitHub Advisories |
| 32 | Archive & Screenshot Links | Wayback, Archive.ph, screenshot services |
| 33 | OSINT Framework Navigator | 20 key OSINT resources |
| 34 | Dark Web Search Links | Ahmia, DarkSearch, clearnet indexes |
| 35 | Public Camera Feeds | Shodan dorks + Google dorks + directories |

### 🔐 Password / Hash
| # | Module | Description |
|---|--------|-------------|
| 40 | Password Generator / Tester | Generate + strength test + HIBP check |
| 41 | Hash Tools | MD5, SHA1, SHA256, SHA512, Base64, Hex |
| 42 | Metadata Extractor | EXIF data + GPS from images |

---

## 🔑 Breach Search Engines

This tool integrates the following **legal** breach search services:

| Service | URL | Scope |
|---------|-----|-------|
| **ZSearcher.fr** | https://zsearcher.fr/ | French specialised engine |
| **OathNet.org** | https://oathnet.org/ | International aggregator |
| **HaveIBeenPwned** | https://haveibeenpwned.com/ | Email breach check (k-anonymity) |
| DeHashed | https://dehashed.com/ | International |
| IntelX | https://intelx.io/ | International |
| LeakCheck | https://leakcheck.io/ | International |
| BreachDirectory | https://breachdirectory.org/ | International |
| Snusbase | https://snusbase.com/ | International |
| Grep.app | https://grep.app/ | Code search |
| And 12 more... | — | See module 23 |

> The HIBP password check uses **k-anonymity** — only the first 5 characters
> of the SHA1 hash are sent. Your password **never leaves your device**.

---

## 📞 Phone Number Intelligence

Module 21 supports **70+ country codes** with:

- Country, region, timezone
- Local number format
- 🇫🇷 **France details** — line type (06/07 mobile, 01-09 fixed, 08 premium, 09 VoIP)
- Mobile operator hints (Orange, SFR, Bouygues, Free)
- Validity check (digit count per country)
- 14 OSINT search links

---

## 📧 Email OSINT

Module 22 includes 4 sub-tools:

1. **Full email analysis** — MD5/SHA1/SHA256 hashes, Gravatar, domain DNS, MX records, breach links, social links
2. **Email format guesser** — generates 14 possible formats from first/last/domain
3. **Email header analyser** — paste raw email headers to extract IPs, mailer, SPF, DKIM
4. **Disposable mail checker** — 40+ known temp mail domains

---

## ✨ Features

- Opening animation with matrix rain, skull flicker, boot sequence, glitch effects
- Rainbow ASCII art on every screen
- "By camzzz" on every module
- Loading bars, spinners, glitch text animations
- Multi-colour interface (not just green)
- Multithreaded scanning (port scanner, username tracker, subdomain finder)
- Works on Windows and Linux

---

## ⚠️ Disclaimer

This tool is for **educational and authorized security research only**.

- Do NOT use it on systems you do not own
- Do NOT use it to harass or stalk individuals
- Respect the terms of service of all third-party services
- The author is not responsible for any misuse

---

## 👨‍💻 Author

**camzzz**

- Discord: `cameleonmortis`
- GitHub: https://github.com/cameleonnbss/50-multi-tool

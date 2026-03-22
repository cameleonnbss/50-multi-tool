# 🔍 Multi Tool V7 — By camzzz

> https://github.com/cameleonnbss

```
==================================================================================================
/*  _____                                                      _____  */
/* ( ___ )                                                    ( ___ ) */
/*  |   |~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~|   |  */
/*  |   |   _________ _____ ___  ____________                  |   |  */
/*  |   |  / ___/ __ `/ __ `__ \/_  /_  /_  /                  |   |  */
/*  |   | / /__/ /_/ / / / / / / / /_/ /_/ /_                  |   |  */
/*  |   | \___/\__,_/_/ /_/ /_/_/___/___/___/_              __ |   |  */
/*  |   |    ____ ___  __  __/ / /_(_)     / /_____  ____  / / |   |  */
/*  |   |   / __ `__ \/ / / / / __/ /_____/ __/ __ \/ __ \/ /  |   |  */
/*  |   |  / / / / / / /_/ / / /_/ /_____/ /_/ /_/ / /_/ / /   |   |  */
/*  |   | /_/ /_/ /_/\__,_/_/\__/_/      \__/\____/\____/_/    |   |  */
/*  |___|~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~|___|  */
/* (_____)                                                    (_____) */

  C A M Z Z Z   M U L T I - T O O L  ·  V 7  ·  9 0 +  M O D U L E S
==================================================================================================
```

> **OSINT / Network / Phone / Mail / Breach / Pentest / AI — 90+ modules**
> By camzzz — Discord: `cameleonmortis` — GitHub: https://github.com/cameleonnbss/50-multi-tool

---

## 🇬🇧 English

### What is this?
camzzz multi-tool is a terminal-based OSINT and network reconnaissance toolkit written in Python.
V7 includes **90+ modules** covering IP analysis, phone number intelligence, email OSINT,
data breach search with real API integrations, username tracking, web vulnerability scanning,
traceroute, banner grabbing, WiFi scanning, an integrated free AI assistant, and much more.

Compatible with **Windows**, **Linux** .

**For educational and authorized security research purposes only.**
**Do NOT use on systems or people without explicit authorization.**
**The author is not responsible for any misuse.**

---

### 🪟 Install on Windows

**1 — Install Python (if not already installed)**
Download Python 3.10+ from https://www.python.org/downloads/windows/
Make sure to check **"Add Python to PATH"** during installation.

**2 — Download the tool**
```bat
git clone https://github.com/cameleonnbss/50-multi-tool
cd 50-multi-tool
```
Or download the ZIP directly from GitHub and extract it.

> The main file is `Multi-Tool.py` — rename it or run it directly.

**3 — Install dependencies**
```bat
pip install -r requirements.txt
```

**4 — Run**
```bat
python Multi-Tool.py
```

> **Tip:** Run CMD as Administrator if you encounter permission issues.

---

### 🐧 Install on Linux

**1 — Install Python and pip**
```bash
# Debian / Ubuntu / Kali
sudo apt update && sudo apt install python3 python3-pip git -y

# Arch / Manjaro
sudo pacman -S python python-pip git

# Fedora / CentOS
sudo dnf install python3 python3-pip git -y
```

**2 — Clone and install**
```bash
git clone https://github.com/cameleonnbss/50-multi-tool
cd 50-multi-tool
pip install -r requirements.txt
```

**3 — Run**
```bash
python3 camzzz_v7.py
```

---

### 🔧 Install optional OSINT tools (for options 80–85)
```bash
sudo apt install python3-pip -y
sudo pip3 install holehe sherlock-project h8mail maigret theHarvester
```

---

---

## 🇫🇷 Français

### C'est quoi ?
camzzz multi-tool est un outil OSINT et reconnaissance réseau en terminal, écrit en Python.
La V7 contient **90+ modules** : analyse IP, intelligence téléphonique, OSINT email,
recherche dans les fuites de données avec vraies intégrations API, tracking de usernames,
scan de vulnérabilités web, traceroute, banner grabbing, WiFi, une IA intégrée gratuite, et plus.

Compatible **Windows**, **Linux** .

**Uniquement pour des usages éducatifs et de recherche en sécurité autorisée.**
**N'utilise pas cet outil sur des systèmes ou des personnes sans autorisation explicite.**
**L'auteur décline toute responsabilité en cas de mauvaise utilisation.**

---

### 🪟 Installation sur Windows

**1 — Installer Python**
Télécharge Python 3.10+ sur https://www.python.org/downloads/windows/
Coche **"Add Python to PATH"** pendant l'installation.

**2 — Télécharger l'outil**
```bat
git clone https://github.com/cameleonnbss/50-multi-tool
cd 50-multi-tool
```
> Le fichier principal est `Multi-Tool.py`

**3 — Installer les dépendances**
```bat
pip install -r requirements.txt
```

**4 — Lancer**
```bat
python camzzz_v7.py
```

---

### 🐧 Installation sur Linux

```bash
# Debian / Ubuntu / Kali
sudo apt update && sudo apt install python3 python3-pip git -y
git clone https://github.com/cameleonnbss/50-multi-tool
cd 50-multi-tool
sudo apt install python3-requests python3-colorama python3-pil -y
python3 Multi-Tool.py
```

```bash
# Arch / Manjaro
sudo pacman -S python python-pip git
git clone https://github.com/cameleonnbss/50-multi-tool
cd 50-multi-tool
sudo pacman -S python-requests python-colorama -y
python3 Multi-Tool.py
```

```bash
# Fedora / CentOS
sudo dnf install python3 python3-requests python3-colorama git -y
git clone https://github.com/cameleonnbss/50-multi-tool
cd 50-multi-tool
python3 Multi-Tool.py
```

---

### 🔧 Outils OSINT optionnels (options 80–85)
```bash
sudo apt install python3-pip -y
sudo pip3 install holehe sherlock-project h8mail maigret theHarvester
```

---

---

## 🗂️ Modules (90+)

### 🌐 Network / IP (1–10)
| # | Module | Description |
|---|--------|-------------|
| 1 | IP Info & Tracker | Own IP / any IP / reputation / /24 range scanner |
| 2 | DNS Lookup | A, MX, NS, TXT, AAAA, CAA, SOA, CNAME |
| 3 | Port Scanner | Common / 1-1024 / custom range, multithreaded |
| 4 | Geo IP Tracker | Country, city, ISP, ASN, Google Maps |
| 5 | Network Info | Local machine + public IP + ISP |
| 6 | WHOIS / Reverse DNS | Domain WHOIS + IP reverse lookup |
| 7 | Subdomain Finder | 120+ wordlist + passive links (crt.sh, Shodan...) |
| 8 | ASN / BGP Lookup | Prefix info via BGPView |
| 9 | Quick Recon | All-in-one domain scan |
| 10 | IP Range Scanner | Full /24 subnet for live hosts |

### 🌍 Web / Domain (11–20)
| # | Module | Description |
|---|--------|-------------|
| 11 | HTTP Header Inspector | Full headers + security audit |
| 12 | SSL Certificate Inspector | Subject, issuer, SANs, expiry, protocol, cipher |
| 13 | Tech Detector | 30+ CMS / framework detection |
| 14 | URL Redirect Tracer | Full redirect chain |
| 15 | Robots / Sitemap Reader | robots.txt + sitemap.xml |
| 16 | Wayback Machine | Latest snapshot info |
| 17 | Wayback URL Extractor | 100 historical URLs via CDX API |
| 18 | Google Dork Generator | 18 pre-built dorks for a domain |
| 19 | Advanced Dork Builder | Custom dorks: site/inurl/intitle/intext/ext |
| 20 | File / Doc OSINT | PDF, DOC, XLS, ENV, SQL, BAK, ZIP… |

### 📱 Phone / Mail / Breach (21–32)
| # | Module | Description |
|---|--------|-------------|
| 21 | Phone Number Info | 70+ countries, FR line type, validity, OSINT links |
| 22 | Phone Social Scanner | 30+ links — WhatsApp, Telegram, TrueCaller, social, leaks |
| 23 | Mail / Email OSINT | Analysis, DNS, format guesser, header analyser, disposable |
| 24 | Email Account Checker | Tests 17 platforms for existing account |
| 25 | Breach Search Engine | ZSearcher / OathNet / HIBP + 8 option sub-menu |
| 26 | Username Tracker | 55+ platforms, multithreaded |
| 27 | Profile Builder | Name + username + email search links |
| 28 | Reverse Image Search | Google, Yandex, TinEye, SauceNAO |
| 29 | Social Media Search | 12 platforms |
| 30 | Public Records Search | 10 people-finder services |
| 31 | Paste Search | Pastebin, Gist, Grep.app, Psbdmp, GitHub |
| 32 | Public Camera Feeds | Shodan dorks + Google dorks + directories |

### 🔬 New Tools — Network / Advanced (40–49)
| # | Module | Description |
|---|--------|-------------|
| 40 | Traceroute | Pure Python — Windows (tracert) + Linux |
| 41 | Banner Grabber | Grab service banners on any port |
| 42 | MAC Vendor Lookup | Identify hardware manufacturer from MAC address |
| 43 | HTTP Method Tester | Test GET/POST/PUT/DELETE/TRACE/OPTIONS — detects dangerous methods |
| 44 | CORS Checker | Detect CORS misconfigurations |
| 45 | Tor Exit Node Check | Check if an IP is a Tor exit node |
| 46 | DNS Brute Force (ext.) | 120+ wordlist + passive sources |
| 47 | Dark Web Search Links | Ahmia, DarkSearch, clearnet indexes |
| 48 | Dark Web Search | Query clearnet dark web engines |
| 49 | ASN / BGP Lookup | (alias 8) |

### 🛡️ Pentest / Vuln / Scan (50–56)
| # | Module | Description |
|---|--------|-------------|
| 50 | Web Vuln Scanner | 20 passive checks: headers, sensitive files, tech, dirs |
| 51 | Firewall / WAF Detector | 14 WAFs, CDN, bot protection, SSL, score /100 |
| 52 | WiFi Scanner | Nearby networks + security analysis (Win/Linux/Android) |
| 53 | File Scanner | Static AV: hashes, suspicious strings, entropy, VT link |
| 54 | OSINT Dork Builder | Advanced AI-style dork builder by name/email/phone/domain |
| 55 | CORS Checker | (alias 44) |
| 56 | HTTP Method Tester | (alias 43) |

### 🔐 Password / Hash / Tools (60–68)
| # | Module | Description |
|---|--------|-------------|
| 60 | Password Generator / Tester | Generate + strength test + HIBP k-anonymity |
| 61 | Hash Tools | MD5/SHA1/SHA256/SHA512/Base64/Hex + crack links |
| 62 | Metadata Extractor | EXIF + GPS from images |
| 63 | Shodan / Censys Links | Shodan, Censys, ZoomEye, Greynoise, OTX, FOFA, BinaryEdge |
| 64 | CVE / Vuln Search | NVD, Exploit-DB, Snyk, GitHub Advisories, PacketStorm |
| 65 | Archive Links | Wayback, Archive.ph, Google Cache |
| 66 | OSINT Framework Navigator | 20 key OSINT resources |
| 67 | URL Redirect Tracer | (alias 14) |
| 68 | Dark Web Search | (alias 47) |

### 🔑 APIs with Free Tier (70–71)
| # | Module | Description |
|---|--------|-------------|
| 69 | XposedOrNot API | Free, no key — email breach + pastes + analytics |
| 70 | LeakCheck API | 7.5B+ records, 3000+ bases — free 50 req/month |
| 71 | BreachDirectory API | Via RapidAPI — email/username/IP/domain |

### 🤖 Open Source OSINT Tools (80–85)
| # | Module | Description |
|---|--------|-------------|
| 80 | Hub Open Source Tools | Central menu + one-line install all |
| 81 | Holehe | Check email on 120+ sites via password reset |
| 82 | h8mail | Breach hunting — supports HIBP, LeakCheck, Snusbase |
| 83 | Sherlock | Username on 400+ platforms — most known tracker |
| 84 | theHarvester | Email/subdomain/IP recon from Google, Bing, Shodan, crt.sh |
| 85 | Maigret | Username on 3000+ sites — generates HTML reports |

### 🤖 Integrated AI (90)
| # | Module | Description |
|---|--------|-------------|
| 90 | OpenRouter IA | Free AI assistant — no credit card — 7 free models |

**Available free models (option 7 to switch):**
- `openrouter/free` — Auto, always picks best available free model
- `meta-llama/llama-3.3-70b-instruct:free` — Llama 3.3 70B by Meta
- `mistralai/mistral-7b-instruct:free` — Mistral 7B
- `qwen/qwen2.5-72b-instruct:free` — Qwen 2.5 72B
- `google/gemma-3-12b-it:free` — Gemma 3 by Google
- `deepseek/deepseek-r1:free` — DeepSeek R1
- `nousresearch/hermes-3-llama-3.1-405b:free` — Hermes 3 405B

**AI modes:**
1. Free chat
2. Analyse email / username OSINT
3. Analyse breach results
4. Explain a cyber / network concept
5. Analyse an IP / domain
6. Generate a full OSINT report (.txt)

### ⚙️ Config & Extras (98–99)
| # | Module | Description |
|---|--------|-------------|
| 98 | API Key Manager | Add/view/reset all API keys — auto-saved to config.ini |
| 99 | Contact | Discord + GitHub |

---

## 🔑 API Keys (all free tiers)

All keys are configured **once** via option **98** and auto-saved in `config.ini` — never asked again.

| Service | URL | Free Tier |
|---------|-----|-----------|
| **LeakCheck** | https://leakcheck.io | 50 req/month |
| **BreachDirectory** | https://rapidapi.com/rohan-patra/api/breachdirectory | 50 req/month |
| **Shodan** | https://account.shodan.io | Limited free |
| **Hunter.io** | https://hunter.io | 25 req/month |
| **VirusTotal** | https://www.virustotal.com | 500 req/day |
| **OpenRouter** | https://openrouter.ai | Free, no credit card |
| **XposedOrNot** | https://xposedornot.com | Free, no key needed |
| **HIBP Passwords** | https://haveibeenpwned.com | Free, k-anonymity |

---

## 📦 What's new in V7 vs V5

| Feature | V5 | V7 |
|---------|----|----|
| Modules | 53 | 90+ |
| Windows support | ✅ | ✅ (improved) |
| Linux support | ✅ | ✅ |
| Auto-install deps | ❌ | ✅ |
| API key manager | ❌ | ✅ auto-saved |
| Traceroute | ❌ | ✅ |
| Banner grabbing | ❌ | ✅ |
| MAC vendor lookup | ❌ | ✅ |
| HTTP method tester | ❌ | ✅ |
| CORS checker | ❌ | ✅ |
| Tor exit check | ❌ | ✅ |
| XposedOrNot API | ❌ | ✅ |
| LeakCheck API | ❌ | ✅ |
| BreachDirectory API | ❌ | ✅ |
| Holehe integration | ❌ | ✅ |
| Sherlock integration | ❌ | ✅ |
| h8mail integration | ❌ | ✅ |
| Maigret integration | ❌ | ✅ |
| theHarvester integration | ❌ | ✅ |
| Integrated AI | ❌ | ✅ OpenRouter (free) |

---

## 👨‍💻 Author

**camzzz**
- Discord: `cameleonmortis`
- GitHub: https://github.com/cameleonnbss/50-multi-tool

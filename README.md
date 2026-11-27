[![OSINT Course Banner](https://raw.githubusercontent.com/jericho1965-droid/osint_course/main/osint_banner.jpeg)](https://raw.githubusercontent.com/jericho1965-droid/osint_course/main/osint_banner.jpeg)

# 🔍 OSINT – Practical Handbook | Interactive Course

An interactive Open Source Intelligence (OSINT) course: a comprehensive learning path comprising **16 lessons**, self-assessment quizzes, practical tools, Python scripts, and advanced open-source analysis techniques, in full compliance with Italian and European legal and ethical frameworks.

## 📖 Course Book

The complete printed/digital handbook accompanying this course is available on Amazon:

[![Course Book on Amazon](https://img.shields.io/badge/Amazon-Buy%20the%20Book-orange?style=for-the-badge&logo=amazon&logoColor=white)](https://www.amazon.it/dp/B0HP6MQP3R)

## 📚 Course Structure

The course comprises 16 progressive modules designed to guide students from theoretical foundations to advanced digital reconnaissance techniques. Each lesson ends with a quiz: a score of at least **75%** is required to unlock the next lesson.

1. **Introduction to OSINT:** open-source intelligence, critical thinking, and cognitive bias mitigation.
2. **The Intelligence Cycle:** the five stages of the analytical process, requests for information (RFI), and collection plan management.
3. **Search Engines and Dorks:** advanced use of Google, Bing, Yandex, DuckDuckGo (!bang), Shodan, Censys, URLScan, and VirusTotal.
4. **Username Research:** nickname anatomy, reuse patterns, enumeration tools (WhatsMyName, Maigret, BlackBird), and email hypothesis generation.
5. **Email and Associated Profiles:** email structure, header analysis, signup checks (Holehe), breach intelligence (IntelX, LeakCheck), and pivoting.
6. **Telephone Identification and B2B:** E.164 format, caller ID services (Truecaller, GetContact), batch list analysis, and B2B corporate reconnaissance.
7. **Telegram:** bots, users, groups and channels, invitation link searches, TGStat, tools such as Telepathy and TeleRecon, scraping and regulations, and ID analysis.
8. **Reverse Image Search and Image Analysis:** reverse image searches, facial recognition, EXIF data, and steganography.
9. **Facebook OSINT:** recursive searches, Sowsearch, dorks, Facebook IDs, Ads Library, Marketplace, sock puppets, and ethics.
10. **Python for OSINT:** analytical tools, automation, and advanced data usage.
11. **SIGINT: Aircraft:** ADS-B tracking, official and unofficial databases, incidents, airports, pilot licenses, and cargo tracking.
12. **Social Engineering:** persuasion and elicitation techniques, human needs, and defenses.
13. **Corporate Intelligence and Public Registers:** Italian Business Register, Land Registry, PRA, ANAC, VIES, OpenCorporates, corporate investigation methodology, and indicators of shell companies.
14. **Technical Intelligence: Domains and Infrastructure:** WHOIS, DNS records, Certificate Transparency (crt.sh), lawful use of Shodan and Censys, and pivoting.
15. **Cryptocurrencies and Blockchain:** pseudonymity, block explorers, clustering, mixers and privacy coins, and legal aspects.
16. **OPSEC, Evidence, and Reporting:** environment separation, hashes and chain of custody, source verification, report structure, and ethical principles.

## 🛠️ Included Tools and Scripts

The course provides ready-to-use Python 3 scripts (using only the standard library or official libraries) to automate data collection and management:

- `diario_osint.py`: investigation log with automatic UTC timestamps and SHA-256 evidence hashes (screenshots).
- `collection_plan.py`: structured collection plan (EEI) management using JSON files.
- `google_dork_builder.py`: guided advanced search query builder.
- `shodan_osint.py`: queries the official Shodan API.
- `urlscan_osint.py`: automates searches and scans on URLScan.io.
- `virustotal_osint.py`: domain and IP address analysis using VirusTotal.
- `censys_osint.py`: host and TLS certificate searches on Censys.
- `wmn_check.py`: username checks based on the WhatsMyName dataset.
- `maigret_launcher.py`: launches Maigret and manages its reports.
- `email_generator.py`: generates corporate and personal email hypotheses with Gravatar/HIBP checks.
- `hunter_verify.py`: Hunter.io API integration for email address verification.
- `numverify_lookup.py` and `batch_carrier_lookup.py`: telephone carrier lookup tools.
- `normalize_phones.py`: normalizes large lists of telephone numbers to international E.164 format.

## ⚖️ Legal and Ethical Framework

Each lesson includes dedicated regulatory compliance sections. OSINT activities in Italy and the European Union must strictly comply with:

- **GDPR (EU Regulation 2016/679):** personal data processing, data minimization, and purpose limitation.
- **Italian Privacy Code (Legislative Decree 196/2003, as amended):** penalties relating to unlawful processing or fraudulent acquisition of data.
- **Italian Criminal Code:** strict limits concerning unauthorized access to computer systems (Article 615-ter), impersonation (Article 494), unlawful interception (Article 617-quater), and stalking (Article 612-bis).

> **The analyst's golden rule:** lawful does not automatically mean public, and collecting information never authorizes access to protected systems or infringement of the privacy of investigation subjects.

## 🤝 How to Contribute

Read `CONTRIBUTING.md` for guidelines on submitting pull requests or reporting issues. Please also comply with `CODE_OF_CONDUCT.md` and `SECURITY.md`.

## 🚀 Getting Started

1. Clone or download the repository to your working environment (a dedicated Linux virtual machine, such as Trace Labs OSINT VM or CSI Linux, is recommended).
2. Open `index.html` in your preferred browser to access the interactive learning platform, quizzes, and assessments.
3. Configure an isolated browser with privacy extensions (e.g., uBlock Origin) and maintain strict operational security (OPSEC).

**Translation status:** The English documentation is available. The translated interactive HTML course is not yet published.

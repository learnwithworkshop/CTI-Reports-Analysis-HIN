# Recommended CTI Tools & Platforms

## Threat Intelligence Platforms

### Commercial
- **CrowdStrike Falcon** - Endpoint protection and threat intelligence
- **Mandiant Intelligence** - Threat investigation and intelligence
- **Recorded Future** - Intelligence platform with dark web monitoring
- **AlienVault OTX** - Open threat exchange platform
- **ThreatConnect** - Intelligence operations, collaboration, analyst workflows
- **Cyble Vision** - AI-native, surface/deep/dark web monitoring, brand & attack surface
- **CloudSEK XVigil** - Digital risk monitoring, AI risk prediction
- **Microsoft Defender Threat Intelligence** - Integration with Microsoft ecosystem, broad coverage
- **Palo Alto Networks (Cortex / Unit 42)** - WildFire integration, strong network security tie-in
- **Anomali** - Threat intelligence management, sharing
- **Cyware (CTIX / Intel Exchange)** - Automation, sharing, SOC integration
- **Feedly Threat Intelligence** - Curated feeds aur research ke liye accha.
- **EclecticIQ Platform** - STIX/TAXII based advanced platform.
- **Group-IB** - Strong in attribution aur digital threat intelligence.
- **Bitsight** - Cyber risk ratings aur intelligence.
- **ThreatQuotient (ThreatQ)** - Flexible TIP for analysts.
- **Flare** - Infostealer aur identity-focused intelligence.
- **Cyberint** - Targeted business risk intelligence.
- **Kaspersky Threat Intelligence** - Detailed feeds aur portal.

### Open Source
- **MISP** - Malware Information Sharing Platform
- **Shodan** - Search engine for internet-connected devices
- **Censys** - Public certificates and network data
- **OpenCTI** - STIX2-based knowledge graph, rich visualizations, entity linking (actors, campaigns, TTPs), connectors (MISP, MITRE, VirusTotal etc.)
- **Yeti** - IOC + TTP repository, auto-enrichment (geolocation, domain resolve), analyst-friendly
- **CIF (Collective Intelligence Framework)** - Threat feed aggregation, scoring, querying
- **GOSINT (Open Source Framework for Intelligence Collection)** - OSINT collection & processing
- **TypeDB CTI** - Knowledge graph database (STIX2 schema), complex queries & insights
- **OpenTAXII** - TAXII server for sharing
  
  ## Anya Notable Open-Source Tools & Feeds:
  - **TheHive + Cortex** - Case management + analyzers (often used with MISP/OpenCTI).
  - **Harpoon** - CLI tool for OSINT enrichment (MISP, VT, Shodan etc.).
  - **AlienVault OTX** - Free community-driven IOC sharing (pulses).
  - **Abuse.ch (ThreatFox, URLhaus, MalwareBazaar)** - High-quality malware & IOC feeds.
  - **Pulsedive** - Free community IOC database with risk scoring.
 
## Quick Notes:
MISP sabse zyada widespread hai sharing aur operational use ke liye (NATO roots, bahut communities).
OpenCTI modern knowledge graph aur visualization ke liye best hai — kai log dono ko saath use karte hain (MISP se data ingest karke OpenCTI mein analyze).
Yeh platforms self-hosted hain, isliye server, maintenance aur Python skills chahiye. Community support acchi hai.
Feeds ko in platforms mein integrate karke powerful stack bana sakte ho (e.g., OTX + Abuse.ch + MITRE ATT&CK).

Commercial se compare karein toh yeh cost-effective hain lekin expert analysis, dark web coverage aur polished UI kam hoti hai. Agar aap India-based ho toh local communities ya CERT-In feeds bhi add kar sakte ho.
  
## Analysis Tools

### Malware Analysis
1. Open-Source / Free Tools
   -**Ghidra** - NSA ka tool, disassembly, decompilation, scripting Deep reverse engineering
   -**x64dbg** - Windows debugger, breakpoints, scripting(Manual dynamic analysis)
   -**Cuckoo Sandbox** - Behaviour monitoring, API calls, network traffic(Automated dynamic analysis)
   -**CAPE Sandbox** - Unpacking focus, especially ransomware(Advanced unpacking)
   -**Radare2 (r2)** - Multi-architecture, powerful CLI(Advanced static + dynamic)
   -**YARA** - Custom rules for malware detection/classification(IOC & family identification|)
   -**Volatility 3** - RAM dump analysis(Post-infection analysis)
   -**PeStudio** - PE header, imports, strings, anomalies(Quick Windows executable check)
   -**Process Monitor (ProcMon)** - Real-time file/registry/process activity(Behaviour tracking)
   -**Wireshark** - Packet capture & analysis(Network behaviour)
   -**ClamAV** - Signature-based detection(Bulk scanning)
   -**Detect It Easy (DIE)** - Identifies packers & compilers(Initial static triage)
   -**REMnux** - Pre-installed malware analysis tools(Full analysis environment)

  ## Anya Notable Open-Source:
  -**Binary Ninja** - Community edition limited
  -**Cutter** - Radare2 GUI
  -**Malware Analyzer** - AI-powered multi-platform
  -**TheHive + Cortex** - with analyzers

2. Paid / Commercial Tools & Platforms
   
- **VirusTotal** - Multi-vendor malware scanning
- **Any.run** - Interactive malware sandbox
- **Hybrid Analysis** - Behavioral malware analysis
- **Joe Sandbox** - Deep analysis (Win, Linux, macOS, Android, iOS)(Paid (Pro/Enterprise))
- **VMRay Analyzer** - Hypervisor-based, evasion-resistant(Enterprise)
- **Intezer** - Genetic code analysis, similarity matching(Paid)
- **ReversingLabs** - Titanium platform, massive scale, file reputation( Enterprise)
- **IDA Pro + Hex-Rays** -Industry standard decompiler(Expensive license)
- **Mandiant (Google)** - Deep expertise & sandboxing(Enterprise)
- **Cylance / BlackBerry** - ML-driven static & dynamic(Enterprise)

### OSINT Tools
1. Open-Source / Free OSINT Tools

- **whois** - Domain registration lookup
- **nslookup** - DNS resolution
- **theHarvester** - Email and subdomain enumeration
- **Shodan** - IP and port scanning
- **SpiderFoot** - 200+ modules, auto OSINT across sources(Automated deep recon)
- **Recon-ng** - Modular, many modules for recon(Advanced users & pentesters)
- **Maltego (Community)** - Graphical mapping of entities & relationships(Investigations & pivoting)
- **Censys** - Hosts, certs, services scanning( Asset discovery)
- **Amass** -- In-depth subdomain & DNS recon(Bug bounty & recon)
- **PhoneInfoga** - Carrier, location, online footprints(People & contact tracing)
- **Mitaka** - Quick lookup for IOCs, URLs, IPs, emails(Fast daily checks)
- **urlscan.io** - Website scanning & screenshots(Malicious site checking)
- **crt.sh** -  Subdomains via SSL certs(Passive subdomain recon)
- **Google Dorks / GHDB** - Advanced search operators.
- **Have I Been Pwned** - Breach checking.
- **AbuseIPDB, CentralOps, MXToolbox**- 
- ** AlienVault OTX** -   (limited free).
- **BGPView, SecurityTrails** - Threat sharing.
  
2. Paid / Commercial OSINT Platforms
- **altego (Pro/Enterprise)** - Advanced transforms, team collaboration(Professional investigations)
- **ShadowDragon** -  Deep social & dark web focus, link analysis(Law enforcement & intel)
- **Recorded Future** - AI-powered, massive data, real-time alerts(Enterprise threat intel)
- **Babel Street / Babel X** -- Multi-source search & monitoring(Government & enterprises)
- **Intelligence X** - Search engine for dark web, archives, leaks(Deep & dark web intel)
- **SEON** - Digital footprint & fraud prevention(Fraud & KYC)
- **Cyble ODIN** - Attack surface & exposed assets(Cybersecurity teams)
- **Hunchly** - Investigation capture & case management(OSINT investigators)
- **Flashpoint (Echosec)** -  Dark web & forums monitoring(Threat actors tracking)
- **Lampyre** - Data analysis & visualization(Analysts)
- Anya Notable:
- **Talkwalker / Hootsuite** - Social monitoring
- **Dataminr, Fivecast, Ontic** - Enterprise real-time
- **OSINT Industries** -  User-friendly platform

### YARA & Detection
- **YARA** - Pattern matching and malware identification
- **YARA-X** - Faster, safer, better error reporting(Malware classification & scanning)
- **SIGMA** - Generic detection rule format
- **Suricata** - Network threat detection engine
- **yarGen** - Automatic YARA rule creation from malware samples(Quick rule writing)
- **YARA-Forge** - High-quality, standardized public rules(Ready-to-use rule sets)
- **Loki** -  IOC + YARA scanner (Python)(Lightweight threat hunting)
- **THOR Lite** -  Free multi-platform IOC + YARA scanner(Enterprise-ready free scanning)
- **YaraManager / YaraGuardian** - Web-based or Django rule management(Organizing large rule sets)
- **FLOSS (Mandiant)** -  Extracts obfuscated strings for YARA rules(Rule creation from packed malware)
- **yaraQA** -  Checks rules for performance & false positives(Rule testing)
- **Panopticon** -  Analyzes YARA rule performance(Optimizing rules)
- Popular Rule Repositories:

- Yara-Rules/rules (GitHub)
- InQuest Awesome-YARA
- Nextron signature-base
- Malpedia
## Other Malware / IOC Detection Tools (Open-Source)
- **ClamAV** - Signature-based scanning, daemon mode(File & email scanning)
- **YARA + Sigma** - YARA (files) + Sigma (logs)(Multi-layer detection)
- **Suricata / Snort** - Rule-based network detection(Network threats)
- **Volatility 3** -  Memory malware detection(Post-breach analysis)
- **Cuckoo / CAPE Sandbox** -  Sandbox + YARA integration(Dynamic detection)
- **Detect It Easy (DIE)** - Packers, compilers, anomalies(Initial triage)
- **PeStudio** - PE file anomalies & indicators(Windows executables)

## Resources

- MITRE ATT&CK Framework
- NVD (National Vulnerability Database)
- CVE Details
- SecurityTrails
- Whois Lookup

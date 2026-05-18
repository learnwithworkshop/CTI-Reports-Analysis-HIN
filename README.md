# CTI Reports Analysis (Hinglish) 🛡️🔍

**Cyber Threat Intelligence (CTI) Analysis** repository mein aapka swagat hai. Yeh project top cybersecurity firms (CrowdStrike, Mandiant, wagerah) ke technical reports ko analyze aur samajhne ke liye hai.

## 📋 Vishay-Suchi (Table of Contents)
- [Lakshya](#lakshya)
- [Repository Structure](#repository-structure)
- [Mukhya Features](#mukhya-features)
- [Report Ke Kategori](#report-ke-kategori)
- [Kaise Istemaal Karen](#kaise-istemaal-karen)
- [Yogdan Dena](#yogdan-dena)
- [License](#license)

## 🎯 Lakshya (Objective)

Sirf reports padh lena kaafi nahi hai. Yeh repository complex vendor reports ko actionable intelligence mein convert karta hai:

- **Core Attack Vectors:** Samjhiye ki breaches kaise hote hain
- **Vulnerability Mapping:** Incidents ko specific CVEs (Common Vulnerabilities aur Exposures) se link karna
- **TTPs (Tactics, Techniques, Procedures):** Attacker ke behavior ko MITRE ATT&CK framework se map karna
- **Actionable Advice:** Security teams ke liye practical recommendations
- **IoCs (Indicators of Compromise):** Reports se technical indicators nikalna
- **Threat Actor Profiling:** Attacker ke motivations aur capabilities samjhna

## 📁 Repository Ki Banawat (Repository Structure)

```
CTI-Reports-Analysis-HIN/
├── README.md                                    # Main documentation
├── CONTRIBUTING.md                              # Yogdan ke guidelines
├── LICENSE                                      # License information
│
├── 📂 Duniya Ke Top CTI Companies/
│   ├── 📂 Tier 1 (Nation-State & APT Focused)/
│   │   ├── README.md
│   │   ├── 🔴 CrowdStrike Reports/
│   │   │   ├── Operation Aurora
│   │   │   ├── Falcon Intelligence Insights
│   │   │   └── [Aur Reports]
│   │   ├── 🟠 Mandiant Reports/
│   │   │   ├── M-Trends Reports
│   │   │   ├── APT Threat Reports
│   │   │   └── [Aur Reports]
│   │   └── 🟡 Aur Tier 1 Companies/
│   │       ├── SANS Institute
│   │       ├── Recorded Future
│   │       └── [Aur Companies]
│   │
│   ├── 📂 Tier 2 (Malware & Incident Response)/
│   │   ├── README.md
│   │   ├── Proofpoint Reports/
│   │   ├── Sophos Reports/
│   │   ├── Palo Alto Networks Reports/
│   │   └── [Aur Companies]
│   │
│   └── 📂 Risk Monitoring Companies/
│       ├── README.md
│       ├── Digital Risk Protection (DRP) Reports/
│       ├── External Attack Surface Management (EASM) Reports/
│       └── [Aur Services]
│
├── 📂 Analysis Templates/
│   ├── Report_Analysis_Template.md
│   ├── TTP_Mapping_Template.md
│   ├── CVE_Analysis_Template.md
│   └── IoC_Extraction_Template.md
│
├── 📂 MITRE ATT&CK Framework/
│   ├── Tactics_Overview.md
│   ├── Techniques_Database.md
│   └── Mapping_Examples.md
│
├── 📂 CVE Database/
│   ├── CVE_2024_Reports.md
│   ├── CVE_2025_Reports.md
│   └── Critical_Vulnerabilities.md
│
├── 📂 Threat Actors/
│   ├── APT_Groups.md
│   ├── Threat_Actor_Profiles.md
│   └── TTPs_by_Group.md
│
├── 📂 IoCs (Indicators of Compromise)/
│   ├── IP_Addresses.md
│   ├── Domains.md
│   ├── File_Hashes.md
│   └── Email_Indicators.md
│
├── 📂 Tools & Resources/
│   ├── Recommended_Tools.md
│   ├── OSINT_Resources.md
│   ├── Analysis_Scripts/
│   │   ├── ioc_extractor.py
│   │   ├── mitre_mapping.py
│   │   └── report_parser.py
│   └── Resources_Links.md
│
├── 📂 Case Studies/
│   ├── High_Profile_Breaches.md
│   ├── Supply_Chain_Attacks.md
│   ├── Ransomware_Campaigns.md
│   └── Nation_State_Operations.md
│
└── 📂 Quick Reference/
    ├── Glossary.md
    ├── Common_TTPs_Cheatsheet.md
    ├── CVE_Severity_Guide.md
    └── Attribution_Indicators.md
```

## 🌟 Mukhya Features

✅ **Deep Report Analysis** - Major cybersecurity reports ka comprehensive analysis

✅ **MITRE ATT&CK Mapping** - Tactics aur techniques ko threat actor behavior se map karna

✅ **CVE Intelligence** - Vulnerability analysis aur exploitation patterns

✅ **IoC Extraction** - Reports se actionable indicators of compromise nikalna

✅ **Threat Actor Profiles** - APT groups aur threat actors ke baare mein detailed information

✅ **Case Studies** - Real-world breaches aur campaigns ka analysis

✅ **Quick Reference Guides** - Common TTPs aur attack patterns ko jaldi dhundna

## 📊 Report Ke Kategori

### Tier 1 Companies (Nation-State & APT Focused)
- **CrowdStrike** - Falcon Intelligence, Threat Intelligence Reports
- **Mandiant** - M-Trends, APT Threat Reports
- **SANS Institute** - Threat Research
- **Recorded Future** - Threat Intelligence Platform

### Tier 2 Companies (Malware & Incident Response)
- **Proofpoint** - Threat Research
- **Sophos** - Security Reports
- **Palo Alto Networks** - Threat Intelligence
- **Microsoft Security** - Threat Analysis Reports

### Risk Monitoring Companies (External Threat Focus)
- **Digital Risk Protection (DRP)** Companies
- **External Attack Surface Management (EASM)** Providers

## 🚀 Kaise Istemaal Karen

### Security Professionals Ke Liye
1. Specific company/report folder mein jaiye
2. Analysis document ko padh liye
3. TTP mapping ko MITRE ATT&CK ke saath check kariye
4. Extracted IoCs ko apne environment mein review kariye
5. Recommendations ko apni security posture mein lagaiye

### Researchers Ke Liye
1. Case studies ko research references ke taur par istemaal kariye
2. Threat actor profiles ko analyze kariye
3. Multiple reports ko cross-reference kariye
4. Naye findings ko contribute kariye

### Students/Learners Ke Liye
1. Quick reference guides se shuru kariye
2. Glossary terms ko padh liye
3. Case studies aur examples se seekhiye
4. Apne analysis ke liye templates istemaal kariye

## 📚 Shuruwat Kaise Karen

```bash
# Repository ko clone kariye
git clone https://github.com/learnwithworkshop/CTI-Reports-Analysis-HIN.git

# Repo mein jaiye
cd CTI-Reports-Analysis-HIN

# Alag alag report categories explore kariye
ls -la "Duniya Ke Top CTI Companies/"
```

## 🤝 Yogdan Dena (Contributing)

Yogdan swagat hai! [CONTRIBUTING.md](CONTRIBUTING.md) ko dekh liye guidelines ke liye:
- Naye report analyses add karna
- Corrections ya updates submit karna
- Naye sections ya improvements ka suggestion dena
- Analysis template format ko follow karna

## 📖 Mukhya Resources

- [MITRE ATT&CK Framework](https://attack.mitre.org/)
- [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework)
- [CVE Details](https://www.cvedetails.com/)
- [Shodan](https://www.shodan.io/)
- [VirusTotal](https://www.virustotal.com/)

## 📝 Disclaimer

Yeh repository sirf educational aur authorized security research ke liye hai. Hamesha ensure kariye ki aapke paas proper authorization hai security analysis ya testing karne se pehle.

## ⭐ Support

Agar aapko yeh repository helpful laga, toh please:
- ⭐ Is repository ko star kariye
- 🔄 Apne network mein share kariye
- 💬 Feedback aur suggestions dijiye
- 🐛 Kisi bhi issue ya inaccuracy ki report kariye

## 📄 License

Yeh project MIT License ke under licensed hai - [LICENSE](LICENSE) file ko dekh liye details ke liye.

---

**Last Updated:** May 18, 2026

**Maintained by:** [@learnwithworkshop](https://github.com/learnwithworkshop)

**Sawal Ya Suggestions?** Ek issue open kariye ya discussion shuru kariye!

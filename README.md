# CTI-Reports-Analysis-HIN

# CTI Reports Analysis (English) 🛡️🔍

Welcome to the **Cyber Threat Intelligence (CTI) Analysis** repository. This project is dedicated to dissecting and analyzing technical reports from top cybersecurity firms (CrowdStrike, Mandiant, SANS, Proofpoint, and others).

## 📋 Table of Contents
- [Objective](#objective)
- [Repository Structure](#repository-structure)
- [Key Features](#key-features)
- [Report Categories](#report-categories)
- [How to Use](#how-to-use)
- [Contributing](#contributing)
- [License](#license)

## 🎯 Objective

The goal is to move beyond just reading reports. This repository breaks down complex vendor reports into actionable intelligence:

- **Core Attack Vectors:** Understanding how breaches originate
- **Vulnerability Mapping:** Linking incidents to specific CVEs (Common Vulnerabilities and Exposures)
- **TTPs (Tactics, Techniques, Procedures):** Mapping actor behavior to the MITRE ATT&CK framework
- **Actionable Advice:** Practical security recommendations for defense teams
- **IoCs (Indicators of Compromise):** Extracting technical indicators from reports
- **Threat Actor Profiling:** Understanding adversary motivations and capabilities

## 📁 Repository Structure

```
CTI-Reports-Analysis-EN/
├── README.md                                    # Main documentation
├── CONTRIBUTING.md                              # Contribution guidelines
├── LICENSE                                      # License information
│
├── 📂 Top Global CTI Companies/
│   ├── 📂 Tier 1 (Nation-State & APT Focused)/
│   │   ├── README.md
│   │   ├── 🔴 CrowdStrike Reports/
│   │   │   ├── Operation Aurora
│   │   │   ├── Falcon Intelligence Insights
│   │   │   └── [Additional Reports]
│   │   ├── 🟠 Mandiant Reports/
│   │   │   ├── M-Trends Reports
│   │   │   ├── APT Threat Reports
│   │   │   └── [Additional Reports]
│   │   └── 🟡 Other Tier 1 Companies/
│   │       ├── SANS Institute
│   │       ├── Recorded Future
│   │       └── [Additional Companies]
│   │
│   ├── 📂 Tier 2 (Malware & Incident Response)/
│   │   ├── README.md
│   │   ├── Proofpoint Reports/
│   │   ├── Sophos Reports/
│   │   ├── Palo Alto Networks Reports/
│   │   └── [Additional Companies]
│   │
│   └── 📂 Risk Monitoring Companies/
│       ├── README.md
│       ├── Digital Risk Protection (DRP) Reports/
│       ├── External Attack Surface Management (EASM) Reports/
│       └── [Additional Services]
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
│   ���── IP_Addresses.md
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

## 🌟 Key Features

✅ **Deep Report Analysis** - Comprehensive breakdowns of major cybersecurity reports

✅ **MITRE ATT&CK Mapping** - Tactics and techniques mapped to threat actor behaviors

✅ **CVE Intelligence** - Vulnerability analysis and exploitation patterns

✅ **IoC Extraction** - Actionable indicators of compromise from reports

✅ **Threat Actor Profiles** - Detailed information on APT groups and threat actors

✅ **Case Studies** - Analysis of real-world breaches and campaigns

✅ **Quick Reference Guides** - Fast lookup for common TTPs and attack patterns

## 📊 Report Categories

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

## 🚀 How to Use

### For Security Professionals
1. Navigate to the specific company/report folder
2. Read the analysis document
3. Check the TTP mapping to MITRE ATT&CK
4. Review extracted IoCs for your environment
5. Apply recommendations to your security posture

### For Researchers
1. Use case studies for research references
2. Analyze threat actor profiles
3. Cross-reference multiple reports
4. Contribute new findings

### For Students/Learners
1. Start with quick reference guides
2. Read glossary terms
3. Study case studies and examples
4. Use templates for your own analysis

## 📚 Getting Started

```bash
# Clone the repository
git clone https://github.com/learnwithworkshop/CTI-Reports-Analysis-EN.git

# Navigate to the repo
cd CTI-Reports-Analysis-EN

# Explore different report categories
ls -la "Top Global CTI Companies/"
```

## 🤝 Contributing

Contributions are welcome! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on:
- Adding new report analyses
- Submitting corrections or updates
- Suggesting new sections or improvements
- Following the analysis template format

## 📖 Key Resources

- [MITRE ATT&CK Framework](https://attack.mitre.org/)
- [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework)
- [CVE Details](https://www.cvedetails.com/)
- [Shodan](https://www.shodan.io/)
- [VirusTotal](https://www.virustotal.com/)

## 📝 Disclaimer

This repository is for educational and authorized security research purposes only. Always ensure you have proper authorization before conducting any security analysis or testing.

## ⭐ Support

If you find this repository helpful, please:
- ⭐ Star this repository
- 🔄 Share it with your network
- 💬 Leave feedback and suggestions
- 🐛 Report any issues or inaccuracies

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Last Updated:** May 16, 2026

**Maintained by:** [@learnwithworkshop](https://github.com/learnwithworkshop)

**Questions or Suggestions?** Open an issue or start a discussion!

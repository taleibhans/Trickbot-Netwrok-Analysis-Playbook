# TrickBot Malware Network Analysis  
**Author:** Talei Ibhanesebhor  

This project is a full malware network investigation focused on **TrickBot**, one of the most advanced modular banking trojans and enterprise-targeting malware strains.  
It demonstrates my skills across **network forensics, malware traffic analysis, Zeek log investigation, and SOC-style reporting.**

I created this project to show employers that I can analyze **real-world malware traffic**, extract Indicators of Compromise, identify C2 behavior, and document findings professionally—exactly what is required in SOC, Blue Team, Detection Engineering, and Digital Forensics roles.

---

## 🔥 Why TrickBot?

TrickBot is **not basic malware**.  
It is complex and enterprise-focused, making this an excellent project for my cybersecurity portfolio.

Some key characteristics:

- multi-stage infection
- encrypted command-and-control (TLS)
- stealthy persistence mechanisms
- modular architecture (banking module, worm module, reconnaissance module)
- long-lived sessions and periodic beaconing
- lateral movement behavior in corporate networks

Choosing TrickBot shows that I can handle **high-complexity, real-world threats**, not just beginner malware samples.

---

## 🧰 Tools & Techniques Used

### **Tools**
- Wireshark  
- Zeek (Bro)  
- Suricata-style rule logic  
- Python (for IOC extraction & traffic analysis)
- VirusTotal / AbuseIPDB for enrichment

### **Skills Demonstrated**
- Identifying malware beaconing behavior  
- Detecting encrypted C2 channels  
- Parsing and analyzing Zeek logs  
- Extracting domains, IPs, JA3 hashes, URIs  
- Reconstructing an incident timeline  
- Writing a complete SOC-ready malware report  
- Pattern recognition across network flows  

---

## 📁 Repository Structure

```
pcap/               → Original TrickBot PCAP  
logs/               → Raw Zeek connection logs  
zeek/               → Parsed protocol-specific logs  
analysis/           → My manual findings  
scripts/            → Automation for IOC extraction & beacon detection  
report/             → Full SOC-style incident report  
```

---

## 📑 Final Deliverables

### **Full Investigation Report**  
`/report/TrickBot_Network_Analysis_Report.md`

Contains:

- Executive summary  
- Infection chain  
- C2 traffic investigation  
- Timeline reconstruction  
- IOCs (IP, domain, JA3, URL patterns)  
- Detection recommendations  
- MITRE ATT&CK mapping  

### **IOC Extraction Script**  
`scripts/extract_iocs.py`

Parses Zeek logs to extract:
- domains  
- IPs  
- JA3 hashes  
- suspicious URIs  

### **Beaconing Detector**  
`scripts/beacon_detector.py`

Detects periodic traffic patterns typical of TrickBot C2.

---

## 🎯 Purpose of This Project

This project demonstrates my readiness for:

- SOC Analyst  
- Cybersecurity Analyst  
- Threat Hunter (Junior)  
- Malware Analyst (Foundational)  
- Blue Team roles  

It shows that I can handle:

- complex real malware  
- encrypted command traffic  
- datasets much larger than entry-level samples  
- real investigation processes  

This project is intentionally **advanced**, representing enterprise-grade malware analysis.

---

## 🚀 Next Steps (Future Enhancements)

I plan to add:

- A Suricata detection rule based on traffic patterns  
- Sigma-style detections for failed TrickBot modules  
- A full dashboard in Splunk or Elastic  
- A YARA rule for extracted artifacts  


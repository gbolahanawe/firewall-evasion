# Firewall and IDS Evasion Lab

This lab demonstrates techniques attackers use to evade network-level detection systems such as firewalls and IDS/IPS. It includes Nmap scan obfuscation using fragmentation, decoy IPs, and custom packet lengths.

## 🔍 Target Setup

- **Victim IP**: `172.16.50.55`
- **IDS/Firewall**: Snort/Suricata or pfSense

## 🛠 Techniques Explored

- Packet Fragmentation
- Decoy IP Spoofing
- Custom Packet Length Manipulation

## 📂 Files

- `fragmentation-technique.md`: Using `nmap -f`
- `decoy-scan.md`: Using `nmap -D`
- `data-length-manipulation.md`: Using `nmap --data-length`
- `screenshots/`: Evidence and results of detection/evasion

## 👨‍💻 Author

Gbolahan Awe – Junior Penetration Tester | Cybersecurity Researcher  
🔗 [LinkedIn](https://www.linkedin.com/in/gbolahan-awe) | 📧 gbolahan.awe@gmail.com

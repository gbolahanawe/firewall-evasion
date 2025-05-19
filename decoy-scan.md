# Evasion with Decoy IPs

The `-D` option in Nmap makes it look like the scan came from multiple IPs.

### 🔧 Command
```bash
nmap -D RND:10 172.16.50.55
```

This sends packets from 10 random spoofed IP addresses.

### 🎯 Goal

- Obfuscate the true origin of the scan.
- Confuse IDS and log correlation mechanisms.

### 🛡️ Mitigation

- Monitor for abnormal patterns from unrelated IPs.
- Use anomaly-based detection and session correlation.

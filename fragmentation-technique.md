# Evasion with Packet Fragmentation

Fragmentation breaks the payload into smaller pieces to evade signature-based detection.

### 🔧 Command
```bash
nmap -f 172.16.50.55
```

### 📝 Notes

- This uses 8-byte fragments per packet.
- Many IDS systems reassemble packets; legacy or misconfigured ones may miss payloads.

### ✅ Observation

Check with `tcpdump` or `Wireshark`:
```bash
sudo tcpdump -i eth0 host 172.16.50.55
```

### 📉 Mitigation

- Enable packet reassembly and fragment detection in IDS.
- Use Suricata’s `frag3` preprocessor or Snort’s fragment handling.

# Evasion via Packet Data Length Manipulation

Modifying the packet size can evade simplistic pattern matchers.

### 🔧 Command
```bash
nmap --data-length 50 172.16.50.55
```

This appends 50 bytes of random data to each probe.

### 🧠 Use Case

- Attempt to evade simple length-based rules in IDS.
- Modify signature recognition in deep packet inspection.

### 🛡️ Mitigation

- Enforce standard MTU and packet normalization.
- Log and flag oversized or inconsistent probe packets.

# 📊 ScottsTechX htop

<p align="center">
  <img src="https://img.shields.io/badge/htop-System-Monitor-00ff88?style=for-the-badge&logo=linux&logoColor=black" alt="htop"/>
  <img src="https://img.shields.io/badge/Open-Source-00ff88?style=for-the-badge&logo=github&logoColor=black" alt="Open Source"/>
</p>

> **Interactive process viewer — real-time CPU/memory stats with color-coded display.**

---

## ⚡ What It Does

htop is an interactive process viewer that displays CPU and memory usage in real-time with color-coded bars. Better than top — scrollable, killable, and sortable.

## 🚀 Quick Usage

```bash
# Start htop
htop

# Start with specific sort
htop -s PERCENT_CPU

# Show only user processes
htop -u fredscotts

# Tree view (process hierarchy)
htop -t

# Batch mode (for scripting)
htop -b -n 1 > process_snapshot.txt
```

## 🛡 Security Use

```bash
# Watch for suspicious processes
htop -u root

# Check network connections
htop then press 't' for tree, 'n' for network

# Kill suspicious process
# F9 -> signal -> SIGKILL
```

---

MIT © 2026

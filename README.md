## My YARA Threat Hunting Journey  
**Detecting Malware with Custom Rules**  
_By Manish Rawat_

---

## 🔍 The Story Behind This Repo

I recently explored the power of **YARA** — a tool that helps cybersecurity professionals detect malware using pattern-based rules. As part of a practical lab (TryHackMe’s *Intro to YARA* room), I learned how to write YARA rules, understand different hunting styles, and scan real files for malware patterns.

This repo is where I’ll continue documenting that journey, share useful rules, and encourage others to start experimenting with YARA too.

---

## ✨ What I Did

- 🧪 **Wrote my first YARA rule** to detect a hidden flag inside a file using a string pattern like `"THM{}"`.
- 🔍 Built rules that require **multiple strings to be present** in a file (e.g., "Yet another", "Ridiculous acronym").
- 📁 Ran YARA via PowerShell over real folders and found **malware-like files with embedded flags**.
- 🔐 Learned about **false positives**, string matching types, and how to tune a rule for better accuracy.

---

## 🚀 Key Takeaways

- YARA is like a powerful search engine for malware patterns.
- You can write simple rules based on known strings, and scan entire directories for matching files.
- Threat hunting doesn’t always need a SIEM — tools like YARA make it **accessible for learners** and solo defenders.

---

## 🛠 Tools Used

- [YARA](https://github.com/VirusTotal/yara) (pattern matching engine)
- PowerShell (to run rules on Windows)
- TryHackMe labs (*Intro to YARA*)
- Realistic malware simulation for safe detection

---

## 📖 Read My Blog

Want the full breakdown of how YARA works and how I approached threat hunting step-by-step?

👉 [Read the blog here]((https://medium.com/@maxxrawat007/from-clueless-to-clued-in-how-yara-helps-you-hunt-malware-like-a-pro-d8076c681fe1?source=friends_link&sk=d705e36439b8e580fec5b0ae2945a824))

---

## 💼 Open to Remote Roles

I’m currently open to **remote opportunities** in cybersecurity, especially roles in:

- Threat Hunting  
- Detection Engineering  
- SOC & Blue Team  
- Malware Analysis  

Feel free to connect or reach out!

---

## 🏷️ Hashtags

`#CyberSecurity` `#YARA` `#ThreatHunting` `#MalwareDetection`  
`#BlueTeam` `#OpenToWork` `#RemoteWork` `#InfoSec`

---

Thanks for reading and stay curious! 🚀

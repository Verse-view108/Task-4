# Task-4
# Password Security & Authentication Analysis
Overview
This is a hands-on learning path for understanding password storage, cracking weak passwords, and building strong authentication practices.
Focus: Ethical self-study only (personal lab, self-generated hashes).
Primary tools: Hashcat (GPU-fast) + John the Ripper (Jumbo – versatile)
Goal: Learn defense by understanding offense.
Tools Used / Installed (on Windows via Terminal)

Hashcat v7.1.2
→ Installed via Scoop (scoop install hashcat)
→ Removed on request (scoop uninstall hashcat)
John the Ripper Jumbo
→ Official Windows binary download recommended (not in default Scoop buckets)
→ URL: https://www.openwall.com/john/k/john-1.9.0-jumbo-1-win64.7z
→ Extraction: 7z x or Expand-Archive
Wordlists
→ rockyou.txt downloaded via PowerShell (Invoke-WebRequest)
Hash generation helpers
→ certutil (built-in Windows)
→ Python + bcrypt / argon2-cffi (if installed)

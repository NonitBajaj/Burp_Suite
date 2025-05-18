🔐 Burp Suite Wordlists
Welcome to the Burp Suite Wordlists repository – a curated collection of powerful and practical wordlists crafted to boost your efficiency in web application and API testing using Burp Suite.

📦 What's Inside?
This repo includes categorized wordlists tailored for:

📂 Folder	📝 Purpose
directories/	Common directory and file names for content discovery (/admin, /backup, /config.js, etc.)
parameters/	Fuzzing for hidden or vulnerable GET/POST parameters (debug, cmd, user, etc.)
auth/	Username and password combos for brute-forcing logins
apis/	Common API endpoints and verbs for API enumeration
lfi-rfi/	Payloads for Local/Remote File Inclusion fuzzing
sqli-xss/	Basic and advanced SQLi/XSS payloads for input testing
headers/	Fuzzing uncommon or sensitive HTTP headers
csrf/	Token names and CSRF-relevant parameter guesses
extensions/	File extensions for file upload and bypass testing

💡 Why Use These?
These wordlists are built for use in:

🔍 Burp Suite Intruder

🧪 Burp Suite Repeater (for manual fuzzing)

🧰 Extensions like Turbo Intruder or Param Miner

They are optimized for:

Bug bounty hunting

CTFs & training labs (like DVWA, Juice Shop, WebGoat)

Real-world engagements with live targets

⚙️ How to Use with Burp Suite
Go to Intruder > Payloads tab

Choose a position to fuzz

Click Load and select the desired .txt file from this repo

Adjust your attack type and hit Start attack

For Turbo Intruder users, load any wordlist directly using Python script variables.

📁 Structure Sample
bash
Copy
Edit
burp-wordlists/
├── directories/common-dirs.txt
├── parameters/api-params.txt
├── auth/user-pass-small.txt
├── lfi-rfi/lfi-basic.txt
├── sqli-xss/xss-payloads.txt
└── headers/common-headers.txt
📢 Contributions Welcome!
Got a killer payload or a better list? PRs are welcome!

📜 Disclaimer
This repository is for educational and authorized testing only. Always get permission before using these wordlists against any system you don't own.


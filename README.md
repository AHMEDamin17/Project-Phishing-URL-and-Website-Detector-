Phishing URL & Website Detector 🛡️

Client-side URL analysis tool that flags risky patterns with a transparent scoring breakdown.


Overview

Phishing attacks are a common threat online. This project helps analyze URLs to detect potentially suspicious characteristics, such as:

Suspicious domains or subdomains

Use of URL shorteners

Misspelled or look-alike brand names

Common phishing keywords (e.g., verify, login, free gift)

Non-HTTPS URLs

The tool provides a safety score (0–100) and a breakdown of detected issues for learning purposes.

Features

✅ Runs entirely in the browser (no backend needed)

✅ Highlights URL risks with a detailed, transparent scoring system

✅ Identifies common phishing patterns and risky TLDs

✅ Includes sample suspicious URLs for testing

✅ Copyable report for documentation or learning

Demo

You can try it locally:

Clone the repository:

git clone https://github.com/yourusername/phishing-url-detector.git


Open index.html in a browser.

Usage

Paste a URL into the input box.

Click Analyze URL (or press Enter).

Review:

Safety score

Red flags and warnings

Normalized URL

Optional: Copy the analysis breakdown for documentation.

Tip: You can paste raw domains like paypa1-login.security-check.com. The tool will normalize them.

How it Works

HTTPS check – warns if the URL is not secure.

Host analysis – detects IP addresses, excessive subdomains, hyphens, and homoglyph tricks.

TLD & URL shorteners – flags frequently abused domains and shorteners.

Keyword analysis – looks for common phishing lure terms.

Brand similarity – warns about typosquatting or look-alike domains.

Query parameter inspection – detects redirect parameters often used in phishing.

Contributing

Contributions are welcome if they improve educational value or usability:

Fork the repository

Create a branch: git checkout -b feature-name

Commit changes: git commit -m "Add feature"

Push to branch: git push origin feature-name

Open a Pull Request

License
Use responsibly for learning, awareness, and research purposes only.

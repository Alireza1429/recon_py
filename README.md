# recon_py
py-recon — Python reconnaissance toolkit combining a depth-limited web crawler, subdomain scanner, WHOIS lookup, and email/phone extractor.
Crawls sites (BFS), extracts page titles, Gmail addresses and Iranian phone numbers, resolves IPs, checks common ports, and appends results to `ipsocket.txt`.
Run with `python pyrecon.py --domain example.com` (uses `wordlist.txt` for subdomains); depth, timeouts and files can be adjusted in the script.
Use only for authorized security research, audits, and learning — do not scan targets without explicit permission.


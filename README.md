# Resilient Malware Detection over DNS-over-HTTPS (DoH)
#Project Status: Literature Review Phase

This repository documents my journey of building a robust malware detection system for DNS-over-HTTPS (DoH) traffic that remains effective even under adversarially generated evasive attacks.

Instead of starting directly with code, this repository first focuses on:

1)Understanding the problem deeply

2)Reviewing existing research

3)Identifying gaps

4)Designing a clear research roadmap

#Background

What is DNS?

DNS (Domain Name System) translates human-readable domain names (e.g., google.com) into IP addresses.

What is DoH?

DNS over HTTPS (DoH) encrypts DNS queries using HTTPS, improving privacy and preventing surveillance.

Then what is the problem?

While DoH protects privacy, it also allows malware to hide its communication with attackers, bypassing traditional network security tools.

---
layout: page
title: IPv6 Website Fingerprinting
description: Does IPv6 make IP-based website fingerprinting easier? (PoPETs 2026)
importance: 1
category: past
---

Encrypted DNS and ECH hide domain names, but a network observer can still see which IP addresses a user connects to.
In IPv4, many websites share one address, which limits what those addresses reveal.
IPv6 has enough addresses to give every domain its own, so many expected fingerprinting to become much easier.

We tested this on more than half a million dual-stack websites using active DNS measurements, Web crawling and entropy based analysis.

**Findings**

- Websites that still depend on some IPv4-only resources are easy to fingerprint: close to 94% accuracy over both IPv4 and IPv6.
- Fully dual-stack websites are much harder: accuracy drops to 56% over IPv4 and 45% over IPv6.
- The risk depends on how hosting providers deploy IPv6 and whether they co-locate domains, not on IPv6 itself.

This work was done at Stony Brook University with Michalis Polychronakis, Theophilus A. Benson (CMU) and Nguyen Phong Hoang (UBC), and was supported by a 2025 Pulse IPv6 Research Fellowship from the Internet Society.

[Paper](https://petsymposium.org/popets/2026/popets-2026-0109.pdf) ·
[Code and data pipeline](https://github.com/sumeer2602/ipv6-web-fingerprinting-pipeline) ·
[ISOC Pulse blog post](https://pulse.internetsociety.org/en/blog/2026/04/more-space-less-privacy-ip-based-website-fingerprinting-in-ipv6/)

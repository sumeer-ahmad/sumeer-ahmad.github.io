---
layout: page
title: ECH in Practice
description: How much privacy Encrypted Client Hello gives users
importance: 2
category: current
---

Encrypted Client Hello (ECH) hides the name of the website a user visits inside the TLS handshake.
How much it actually protects depends on how it is deployed.

This project asks two questions:

- **Anonymity in practice.** An observer still sees the outer server name and IP address. How many websites share them, and how large is the crowd a user hides in?
- **Integrity of ECH configurations.** Browsers get ECH keys from DNS (HTTPS and SVCB records). Do open resolvers around the world deliver these records intact, or are they stripped or modified along the way?

A paper is under review.

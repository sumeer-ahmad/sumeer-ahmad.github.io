---
layout: page
title: CamSniff
description: Inferring human presence from encrypted IoT camera traffic
importance: 3
category: past
---

Wireless security cameras encrypt their video, but their traffic patterns still leak information.
CamSniff shows that an eavesdropper on the local network can tell when someone is at home.

- Built a model that finds the IP address of an IoT camera on a WPA3 network, using ARP spoofing and flow level features with Random Forest and XGBoost (92% success rate).
- Wrote fingerprinting rules over encrypted TCP, HTTP and STUN flows that detect motion events with over 95% accuracy, revealing human presence.

Stony Brook University.

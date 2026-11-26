---
layout: page
title: Hidden Dependencies in NPM
description: A measurement study of the NPM software supply chain
importance: 4
category: past
---

Packages often pull in code that never appears in their declared dependencies.
This project measured how common these hidden dependencies are and what risk they carry.

- Analyzed the top 50K NPM packages.
- Found that 53% of hidden packages carried security risks and 32% were affected by supply chain vulnerabilities.
- Proposed dynamic debloating, which reduced the package attack surface by 70%.

NC State University and LUMS.

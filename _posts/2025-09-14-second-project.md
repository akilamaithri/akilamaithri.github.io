---
layout: post
usehighlight: true
tags: [RMIT, PaperProject]
comments: true
title: Second Time Lucky?
datee: 2025-09-14
---

After fiddling around with Indirect Prompt Injection and failing at homomorphic encryption, I have fallen on track to utilize AI Agents and IoT as a test bed to prevent semantic threats in highly critical environments such as hospitals.

The problem is that this creates a new attack surface where semantic threats bypass traditional encryption-blind defenses. In high-reliability sectors like healthcare, an attacker can manipulate agent intent without being detected. Current frameworks fail because they cannot correlate what an agent intends to do with the actual network consequences.

I am proposing a cross-layer defense architecture that correlates decrypted agent intent with encrypted network results. To make this work on light 6G IoT gateways, I use a quantized edge Transformer and a Heterogeneous GraphSAGE encoder. This allows for efficient unsupervised anomaly detection by linking agent behavior directly to network signatures.

We have validated this theory and the ML workflow using a production-scale dataset of healthcare actuation sessions. The results show significant improvements over existing baselines in detecting novel semantic attacks.
---
layout: post
usehighlight: true
tags: [RMIT, PaperProject]
comments: true
title: New Year, New Project. 
datee: 2026-01-01
---
Tentative Title: Topology-Aware Differential Privacy for Privacy-Preserving Consensus in Autonomous Edge Networks

I'm focused on solving a fundamental conflict in autonomous edge networking: how to ensure a large group of distributed agents can agree on a common task (consensus) while protecting each agent's local, private data. 

The problem is that in real-world, peer-to-peer network's (e.g., swarms of drones or autonomous vehicles) connections are constantly changing (high churn). Traditional privacy-preserving techniques fail here; their fixed-noise approach either allows data to leak when the network is highly connected or injects too much noise, preventing the agents from ever reaching a necessary agreement when the network is fragmented. 

My thinking for the solution is to make the privacy mechanism aware of the network topology. I propose a new approach where each agent autonomously senses its dynamic importance in the network and adjusts its privacy protection accordingly. By linking the level of noise directly to an agent's topological influence, we can protect the most exposed data points while maintaining the network's overall ability to rapidly converge.

But we need to proove this theory mathematically, as well as empirically using a ML workflow. 
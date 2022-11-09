---
title: "PLC-Sleuth: Detecting and Localizing PLC Intrusions Using Control Invariants"
collection: publications
permalink: /publication/RAID-20/
excerpt: '> *The 23rd International Symposium on Research in Attacks, Intrusions and Defenses (RAID 2020)*<br>***Zeyu Yang**, Liang He, Peng Cheng, Jiming Chen, David K.Y. Yau and Linkang Du*.'
<!-- date: 2020-10-01 -->
venue: 'Online'
#paperurl: ''
#citation: ''
---
- [Download paper](https://www.usenix.org/conference/raid2020/presentation/yang)

- [Presentation video](https://www.youtube.com/watch?v=cWcqw7IljlU)

Conference:
===
*The 23rd International Symposium on Research in Attacks, Intrusions and Defenses (RAID 2020)*  

Authors: 
===
***Zeyu Yang**, Liang He, Peng Cheng, Jiming Chen, David K.Y. Yau and Linkang Du*.

Abstract:    
===
Trustworthy Programmable Logic Controllers (PLCs) are the ground of control systems, which are however, vulnerable to a variety of cyber attacks, especially for networked control systems. To mitigate this issue, we design PLC-Sleuth, a novel non-invasive intrusion detection/localization system for PLCs, grounding on a set of control invariants — i.e., the correlations between sensor readings and the concomitantly triggered PLC commands — that exist pervasively in all control systems. Specifically, taking the system’s Supervisory Control and Data Acquisition log as input, PLC-Sleuth abstracts/identifies the system’s control invariants as a control graph using data-driven structure learning, and then monitors the weights of graph edges to detect anomalies thereof, which is in turn, a sign of intrusion. We have implemented and evaluated PLC-Sleuth using both a prototype of Secure Ethanol Distillation System (SEDS) and a realistically simulated Tennessee Eastman (TE) process.
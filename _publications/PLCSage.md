---
title: "Detecting PLC Intrusions Using Control Invariants"
collection: publications
permalink: /publication/PLCSage/
excerpt: '> *IEEE Internet of Things Journal, 2022*<br>***Zeyu Yang**, Liang He, Hua Yu, Chengcheng Zhao, Peng Cheng and Jiming Chen*.'
date: Apr. 2022
venue: '--'
#paperurl: ''
#citation: ''
---
- [Download paper]
<!-- (https://ieeexplore.ieee.org/abstract/document/9749129) -->

Transaction:
===
*IEEE Internet of Things Journal, 2020, 65(10): 4348--4355*  

Authors: 
===
***Zeyu Yang**, Liang He, Hua Yu, Chengcheng Zhao, Peng Cheng and Jiming Chen*.

Abstract: 
===
Programmable Logic Controllers (PLCs), i.e., the core of control systems, are well-known to be vulnerable to a variety of cyber attacks. To mitigate this issue, we design PLC-Sleuth, a novel non-invasive intrusion detection/ localization system for PLCs, which is built on a set of control invariants -- i.e., the correlations between sensor readings and the concomitantly triggered PLC commands -- that exist pervasively in all control systems. Specifically, taking the system's Supervisory Control and Data Acquisition log as input, PLC-Sleuth abstracts/identifies the system's control invariants as a control graph using data-driven structure learning, and then monitors the weights of graph edges to detect anomalies thereof, which is in turn, a sign of intrusion. We have implemented and evaluated PLC-Sleuth using both a platform of Ethanol Distillation System (EDS) and a realistically simulated Tennessee Eastman (TE) process. The results show that PLC-Sleuth can: (i) identify control invariants with 100%/98.11% accuracy for EDS/TE, (ii) detect PLC intrusions with 98.33%/0.85% true/false positives for EDS and 100%/0% true/false positives for TE, and (iii) localize intrusions with 93.22%/96.76% accuracy for EDS/TE.

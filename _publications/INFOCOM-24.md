---
title: "Reverse Engineering Industrial Protocols Driven By Control Fields"
collection: publications
permalink: /publication/INFOCOM-24/
excerpt: '> *INFOCOM 2024*<br>*Zhen Qin, **Zeyu Yang**, Yangyang Geng, Xin Che, Tianyi Wang, Hengye Zhu, Peng Cheng, Jiming Chen*.'
date: May. 2024
venue: '--'
#paperurl: ''
#citation: ''
---
- [Download paper]
<!-- (./files/PLCSage.pdf) -->

Transaction:
===
*INFOCOM 2024* 

Authors: 
===
*Zhen Qin, **Zeyu Yang**, Yangyang Geng, Xin Che, Tianyi Wang, Hengye Zhu, Peng Cheng, Jiming Chen*.

Abstract: 
===
Industrial protocols are widely used in Industrial Control Systems (ICSs) to network physical devices, thus playing a crucial role in securing ICSs. However, most commercial industrial protocols are proprietary and owned by their vendors, which impedes the implementation of protections against cyber threats. In this paper, we design REInPro to Reverse Engineer Industrial Protocols. REInPro is inspired by the fact that the structure of industrial protocols can be determined by a particular field referred to control field. By applying a probabilistic model of network traffic behavior, REInPro automatically identifies the control field and groups the associated network traffic into clusters. REInPro then infers critical semantics of industrial protocols by differentiating the features of corresponding protocol fields. We have experimentally implemented and evaluated REInPro using 8 different industrial protocols across 6 Programmable Logic Controllers (PLCs) belonging to 5 original equipment manufacturers. The experimental results show REInPro to reverse-engineer the formats and semantics of industrial protocols with an average correctness/perfection of 0.70/0.58 and 0.96/0.39.
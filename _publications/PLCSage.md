---
title: "Mismatched Control and Monitoring Frequencies: Vulnerability, Attack, and Mitigation"
collection: publications
permalink: /publication/PLCSage/
excerpt: '> *IEEE Transactions on Dependable and Secure Computing, 2024*<br>***Zeyu Yang**, Liang He, Peng Cheng and Jiming Chen*.'
date: Apr. 2024
venue: '--'
#paperurl: ''
#citation: ''
---
- [Download paper]
<!-- (https://ieeexplore.ieee.org/abstract/document/9749129) -->

Transaction:
===
*IEEE Transactions on Dependable and Secure Computing, 2024*  

Authors: 
===
***Zeyu Yang**, Liang He, Peng Cheng and Jiming Chen*.

Abstract: 
===
Stealthy attacks manipulate the operation of Industrial Control Systems (ICSs) without being undetected, allowing persistent manipulation of system operation and thus the potential to cause destructive damage. This paper introduces a new vulnerability of ICS that can be exploited to mount stealthy attacks without requiring any domain knowledge. This vulnerability is caused by a common practice in system monitoring, i.e., the SCADA monitors ICS operation at a much lower frequency than system execution, causing a loss of precision when the SCADA tries to cross-validate the issued control commands using the collected sensory data. Exploiting this vulnerability, an attack called PLC-SAGE is designed to stealthily manipulate the system operation by identifying and injecting malicious control commands that will not be concluded as abnormal by the SCADA. This paper further discusses a preferred ICS engineering practice and an attestation strategy to mitigate the above vulnerability and protect ICS from PLC-SAGE. Both PLC-SAGE and the proposed mitigations have been experimentally validated on two ICS platforms.

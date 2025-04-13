---
title: "New threat on formal verification for neural networks: example and fault tolerance"
collection: publications
category: conferences
permalink: /publication/2022-06-10-Conference-Safeprocess-new-threat-on-formal-verification-for-NN
excerpt: 'This article details a new threat on formal verification for neural networks'
date: 2022-06-10
venue: '11th IFAC Symposium on Fault Detection, Supervision and Safety for Technical Processes (SAFEPROCESS 2022)'
paperurl: 'https://doi.org/10.1016/j.ifacol.2022.07.197'
citation: ' Augustin Viot, Benjamin Lussier, Walter Schön, Armando Tacchella, Stéphane Geronimi. New Threat on Formal Verification for Neural Networks: Example and Fault Tolerance. 11th IFAC Symposium on Fault Detection, Supervision and Safety for Technical Processes (SAFEPROCESS 2022), Jun 2022, Pafos, Cyprus. pp.623-630, ⟨10.1016/j.ifacol.2022.07.197⟩. ⟨hal-03823896⟩'
---

This article details a new threat to NN formal verification that is well known in the formal verification of classical systems: errors in the learned model of a NN could cause the NN to pass formal verification on a property while violating the same property in real life. The solution to this threat for classical systems (which is expert reviews) is inadequate for NN due to their lack of explainability. Here, we propose a detection and recovery mechanism to tolerate it. This mechanism is based on a mathematical diversification of the system's model and the online verification of the formal safety properties. It was successfully implemented and validated on an application example, which, to our knowledge, is one of the most concrete NN formal verification in the literature: the Adaptive Cruise Control function of an autonomous car.

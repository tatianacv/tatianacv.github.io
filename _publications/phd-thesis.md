---
title: "Towards Automated Evolution of Imperative Deep Learning Programs"
collection: publications
category: thesis
permalink: /publication/phd-thesis
excerpt: 'This dissertation addresses a significant knowledge gap in understanding the practical application of hybridization in real-world DL systems. Without these insights, DL systems risk inefficiency, fragility, and high maintenance costs. This work presents an in-depth analysis of hybridization, focusing on its challenges, evolution, and usage patterns, and offers actionable recommendations, best practices, and anti-patterns for developers. Additionally, I develop an automated refactoring tool to analyze DL program source code, assess the suitability of hybridization, and optimize its application.'
date: 2025-09-30
venue: 'PhD thesis, City University of New York (CUNY) Graduate Center, 365 5th Ave, New York, NY 10016'
paperurl: 'http://academicworks.cuny.edu/gc_etds/6444'
citation: 'Tatiana Castro Vélez. Towards Automated Evolution of Imperative Deep Learning Programs. PhD thesis, City University of New York (CUNY) Graduate Center, 365 5th Ave, New York, NY 10016, September 2025.'
---
Software engineering (SE) is increasingly intersecting with data-centric domains such as machine learning (ML) and deep learning (DL). Similar to bugs in traditional software systems, defects can emerge in ML and DL systems. ML, including DL, systems are now widespread and rely on dynamic models defined by input data. Developers face the challenge of building dependable systems while addressing the demand for scalable software.

Efficiency is essential to support responsiveness with respect to ever-growing datasets. Traditional DL frameworks achieve scalability through deferred execution, enabling symbolic, graph-based deep neural network (DNN) computation. While efficient, this approach is error-prone, cumbersome, and difficult to debug. In contrast, imperative DL frameworks that encourage eager execution offer a more intuitive, and less error-prone development experience, but sacrifice scalability and efficiency.

Hybrid approaches, now integrated into mainstream DL frameworks, aim to balance this tradeoff by executing imperative DL programs as static graphs at run-time. However, these approaches require complex metadata and face limitations with native program constructs. Ensuring safe, accurate, and efficient graph execution demands careful consideration to avoid performance bottlenecks and maintain semantic correctness.

This dissertation addresses a significant knowledge gap in understanding the practical application of hybridization in real-world DL systems. Without these insights, DL systems risk inefficiency, fragility, and high maintenance costs. This work presents an in-depth analysis of hybridization, focusing on its challenges, evolution, and usage patterns, and offers actionable recommendations, best practices, and anti-patterns for developers. Additionally, I develop an automated refactoring tool to analyze DL program source code, assess the suitability of hybridization, and optimize its application.
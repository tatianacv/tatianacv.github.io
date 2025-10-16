---
title: "Challenges in migrating imperative Deep Learning programs to graph execution: An empirical study."
collection: publications
category: conferences
permalink: /publication/challenges-imperative-graph
excerpt: 'We conduct a data-driven analysis of challenges—and resultant bugs—involved in writing reliable yet performant imperative DL code by studying 250 open-source projects, consisting of 19.7 MLOC, along with 470 and 446 manually examined code patches and bug reports, respectively.'
date: 2022-05-01
venue: '2022 International Conference on Mining Software Repositories (MSR)'
paperurl: 'https://academicworks.cuny.edu/hc_pubs/698/'
slidesurl: 'https://www.slideshare.net/slideshow/challenges-in-migrating-imperative-deep-learning-programs-to-graph-execution-an-empirical-study/251707530'
citation: 'Tatiana Castro Vélez, Raffi Khatchadourian, Mehdi Bagherzadeh, and Anita Raja. Challenges in migrating imperative Deep Learning programs to graph execution: An empirical study. In International Conference on Mining Software Repositories, MSR ’22, pages 469–481, New York, NY, USA, May 2022. IEEE/ACM, ACM. (45/138; 32.6% acceptance rate).'
---
Efficiency is essential to support responsiveness w.r.t. ever-growing datasets, especially for Deep Learning (DL) systems. DL frameworks have traditionally embraced deferred execution-style DL code that supports symbolic, graph-based Deep Neural Network (DNN) computation. While scalable, such development tends to produce DL code that is error-prone, non-intuitive, and difficult to debug. Consequently, more natural, less error-prone imperative DL frameworks encouraging eager execution have emerged at the expense of run-time performance. While hybrid approaches aim for the "best of both worlds," the challenges in applying them in the real world are largely unknown. We conduct a data-driven analysis of challenges—and resultant bugs—involved in writing reliable yet performant imperative DL code by studying 250 open-source projects, consisting of 19.7 MLOC, along with 470 and 446 manually examined code patches and bug reports, respectively. The results indicate that hybridization: (i) is prone to API misuse, (ii) can result in performance degradation—the opposite of its intention, and (iii) has limited application due to execution mode incompatibility. We put forth several recommendations, best practices, and anti-patterns for effectively hybridizing imperative DL code, potentially benefiting DL practitioners, API designers, tool developers, and educators.

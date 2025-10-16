---
title: "Towards safe automated refactoring of imperative Deep Learning programs to graph execution."
collection: publications
category: conferences
permalink: /publication/towards-automated-refactoring
excerpt: 'We present our ongoing work on automated refactoring that assists developers in specifying whether and how their otherwise eagerly-executed imperative DL code could be reliably and efficiently executed as graphs while preserving semantics.'
date: 2023-09-01
venue: 'NIER track of the IEEE/ACM International Conference on Automated Software Engineering (ASE)'
paperurl: 'https://academicworks.cuny.edu/hc_pubs/813/'
slidesurl: 'https://www.slideshare.net/slideshow/towards-safe-automated-refactoring-of-imperative-deep-learning-programs-to-graph-execution-260934612/260934612'
bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
citation: 'Raffi Khatchadourian, Tatiana Castro Vélez, Mehdi Bagherzadeh, Nan Jia, and Anita Raja. Towards safe automated refactoring of imperative Deep Learning programs to graph execution. In International Conference on Automated Software Engineering, ASE ’23, pages 1800–1802. IEEE, September 2023. NIER track. (25/70; 35.7% acceptance rate).'
---
Efficiency is essential to support responsiveness w.r.t. ever-growing datasets, especially for Deep Learning (DL) systems. DL frameworks have traditionally embraced deferred execution-style DL code—supporting symbolic, graph-based Deep Neural Network (DNN) computation. While scalable, such development is error-prone, non-intuitive, and difficult to debug. Consequently, more natural, imperative DL frameworks encouraging eager execution have emerged at the expense of run-time performance. Though hybrid approaches aim for the "best of both worlds," using them effectively requires subtle considerations to make code amenable to safe, accurate, and efficient graph execution. We present our ongoing work on automated refactoring that assists developers in specifying whether and how their otherwise eagerly-executed imperative DL code could be reliably and efficiently executed as graphs while preserving semantics. The approach, based on a novel imperative tensor analysis, will automatically determine when it is safe and potentially advantageous to migrate imperative DL code to graph execution and modify decorator parameters or eagerly executing code already running as graphs. The approach is being implemented as a PyDev Eclipse IDE plug-in and uses the WALA Ariadne analysis framework. We discuss our ongoing work towards optimizing imperative DL code to its full potential.
---
title: "Hybridize Functions: A tool for automatically refactoring imperative Deep Learning programs to graph execution."
collection: publications
category: tools
permalink: /publication/hybridize-functions-tool
excerpt: 'We discuss the engineering aspects of a refactoring tool that automatically determines when it is safe and potentially advantageous to migrate imperative DL code to graph execution and vice-versa.'
date: 2025-05-01
venue: 'Artur Boronat and Gordon Fraser, editors, Fundamental Approaches to Software Engineering (FASE)'
paperurl: 'https://academicworks.cuny.edu/hc_pubs/835/'
slidesurl: 'https://www.slideshare.net/slideshow/hybridize-functions-a-tool-for-automatically-refactoring-imperative-deep-learning-programs-to-graph-execution/278800464'
citation: 'Raffi Khatchadourian, Tatiana Castro Vélez, Mehdi Bagherzadeh, Nan Jia, and Anita Raja. Hybridize Functions: A tool for automatically refactoring imperative Deep Learning programs to graph execution. In Artur Boronat and Gordon Fraser, editors, Fundamental Approaches to Software Engineering, FASE ’25, pages 89–100, Cham, May 2025. ETAPS, Springer Nature Switzerland. (11/31; 35% acceptance rate). EAPLS Distinguished Paper Award.'
---
Efficiency is essential to support responsiveness w.r.t. ever-growing datasets, especially for Deep Learning (DL) systems. DL frameworks have traditionally embraced deferred execution-style DL code—supporting symbolic, graph-based Deep Neural Network (DNN) computation. While scalable, such development is error-prone, non-intuitive, and difficult to debug. Consequently, more natural, imperative DL frameworks encouraging eager execution have emerged but at the expense of run-time performance. Though hybrid approaches aim for the "best of both worlds," using them effectively requires subtle considerations to make code amenable to safe, accurate, and efficient graph execution—avoiding performance bottlenecks and semantically inequivalent results. We discuss the engineering aspects of a refactoring tool that automatically determines when it is safe and potentially advantageous to migrate imperative DL code to graph execution and vice-versa.
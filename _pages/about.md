---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am Hsin-Yuan Huang (pronounced as "Shin Yuan Huan", 黃信元), a Ph.D. student at Caltech advised by <a href="https://scholar.google.com/citations?user=xmOSptwAAAAJ&hl=en" target="_blank">John Preskill</a> and <a href="https://scholar.google.com/citations?user=IGDs4HwAAAAJ&hl=en" target="_blank">Thomas Vidick</a>. I also go by the name Robert.

## Research Interest:

I work on the interplay between quantum physics and computer science (information theory, machine learning, complexity theory).
Some problems I think about:
* How to learn and make predictions in a quantum-mechanical world?
* Could quantum machines learn faster and predict more accurately?
* How can machine learning advance quantum technology and fundamental physics?
* What are the fundamental limits in learning with classical and quantum machines?

<center>
<img src="assets/img/Intelligence.jpg"
     alt="Cartoon depiction of intelligence"
     style="text-align:center; width:50%; border-radius:15%; padding-top:15px; padding-bottom:1px" />
</center>

## Publications:

<a href="https://scholar.google.com/citations?user=2y5YF-gAAAAJ&hl=en" target="_blank">Google Scholar</a> provides a full list under chronological/citations order.

### >> Machine learning, quantum physics, and quantum advantage

Can classical machine learning models solve challenging problems in physics that no classical algorithms could solve? By solve, we consider the ability to provide solutions in polynomial time. We prove the affirmative in the following paper. See <a href="https://twitter.com/RobertHuangHY/status/1408230497512087554" target="_blank">my 13 tweets</a> for a summary.

* **H.-Y. Huang**, R. Kueng, G. Torlai, V. V. Albert, J. Preskill. *Provably efficient machine learning for quantum many-body problems*. <a href="https://youtu.be/W-vGcWZYQeA" target="_blank">Talk at Simons Institute</a>, <a href="https://www.youtube.com/watch?v=d1_hBEJQUSA&t=1202s&ab_channel=MunichCenterforQuantumScience%26Technology" target="_blank">QIP 2021</a>, <a href="https://arxiv.org/abs/2106.12627" target="_blank">arXiv (2021)</a>.

But why could machine learning algorithms be significantly more efficient than non-machine-learning algorithms? The main idea is that generalizing from training data can be much easier than computing answers from the ground up. In the following work with <a href="https://quantumai.google/" target="_blank">Google Quantum AI</a>, we study how such a fact impacts quantum advantage in machine learning.

* **H.-Y. Huang**, M. Broughton, M. Mohseni, R. Babbush, S. Boixo, H. Neven, J. R. McClean. *Power of data in quantum machine learning*. <a href="https://www.nature.com/articles/s41467-021-22539-9" target="_blank">Nature Communications (Featured in Quantum)</a>, <a href="https://www.youtube.com/watch?v=d1_hBEJQUSA&t=1202s&ab_channel=MunichCenterforQuantumScience%26Technology" target="_blank">QIP 2021</a>, <a href="https://ai.googleblog.com/2021/06/quantum-machine-learning-and-power-of.html" target="_blank">Google AI blog</a>, <a href="https://blog.tensorflow.org/2020/11/characterizing-quantum-advantage-in.html" target="_blank">TensorFlow blog</a>, <a href="https://arxiv.org/abs/2011.01938" target="_blank">arxiv (2020)</a>.

Furthermore, we show that for a wide range of learning problems in quantum physics, there is a fundamental limit to quantum advantage in prediction performance.
We also identify learning problems with exponential quantum advantage without relying on any conjecture.
The results are presented in the following work.

* **H.-Y. Huang**, R. Kueng, J. Preskill. *Information-theoretic bounds on quantum advantage in machine learning*. <a href="https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.126.190505" target="_blank">Physical Review Letters (Editor's Suggestion)</a>, <a href="https://www.youtube.com/watch?v=d1_hBEJQUSA&t=1202s&ab_channel=MunichCenterforQuantumScience%26Technology" target="_blank">QIP 2021</a>, <a href="https://quantumfrontiers.com/2021/06/02/peeking-into-the-world-of-quantum-intelligence/" target="_blank">IQIM blog -- Quantum Frontiers</a>, <a href="https://arxiv.org/abs/2101.02464" target="_blank">arXiv (2021)</a>.

An invited perspective article that summarizes these ideas in the context of quantum chemistry and presents future directions:

* J. R. McClean, N. C. Rubin, J. Lee, M. P. Harrigan, T. E. O'Brien, R. Babbush, W. J. Huggins, **H.-Y. Huang**. *What the foundations of quantum computer science teach us about chemistry*. <a href="https://arxiv.org/abs/2106.03997" target="_blank">arXiv (2021)</a>.

### >> Classical shadows of quantum states

Classical shadow is an efficient representation of quantum many-body system that can be easily constructed in experiments.
Storing full description of a quantum system requires an exponential amount of classical memory (exponential in the number of qubits).
But classical shadow only require a linear (or polynomial) amount of classical memory.
See <a href="https://en.wikipedia.org/wiki/Classical_shadow" target="_blank">the wiki page</a>, <a href="https://pennylane.ai/qml/demos/tutorial_classical_shadows.html" target="_blank">a nice tutorial in PennyLane</a>, or <a href="https://www.youtube.com/watch?v=NXejv2wVwas&t=2553s&ab_channel=SimonsInstitute" target="_blank">a great talk by John Preskill</a> for more details.

We proposed the idea of classical shadow in the following Nature Physics article.

* **H.-Y. Huang**, R. Kueng, J. Preskill.
*Predicting many properties in a quantum system from very few measurements*.
<a href="https://www.nature.com/articles/s41567-020-0932-7" target="_blank">Nature Physics</a>, QIP 2020, <a href="https://phys.org/news/2020-07-method-properties-complex-quantum.html" target="_blank">Phys.org</a>, <a href="https://arxiv.org/abs/2002.08953" target="_blank">arXiv (2020)</a>.

We wrote a follow-up work that can make classical shadows even more efficient. The key idea is to derandomize the randomization construction in the original classical shadow.

* **H.-Y. Huang**, R. Kueng, J. Preskill. *Efficient estimation of Pauli observables by derandomization*. <a href="https://journals.aps.org/prl/accepted/59079YdcPa91f38e74884b01c88074c23995b9082" target="_blank">Physical Review Letters</a>, TQC 2021, <a href="https://arxiv.org/abs/2103.07510" target="_blank">arXiv (2020)</a>.

The following work demonstrates that classical shadows can be easily applied to existing experimental platforms.

* A. Elben, R. Kueng, **H.-Y. Huang**, R. van Bijnen, C. Kokail, M. Dalmonte, P. Calabrese, B. Kraus, J. Preskill, P. Zoller, B. Vermersch.
*Mixed-state entanglement from local randomized measurements*.
<a href="https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.125.200501" target="_blank">Physical Review Letters</a>, <a href="https://arxiv.org/abs/2007.06305" target="_blank">arXiv (2020)</a>.

### >> Many-body quantum chaos

What are some salient features of chaotic many-body systems? The following works with condensed matter physicists make progress in answering this question. In particular, we show that most wavefunctions can individually generate state design by performing measurements on the subsystem. A state design is an ensemble of quantum states that are *uniformly distributed* in the quantum Hilbert space.

* J. Cotler<sup>$\dagger$</sup>, D. Mark<sup>$\dagger$</sup>, **H.-Y. Huang**<sup>$\dagger$</sup> (co-first author), F. Hernandez, J. Choi, A. L. Shaw, M. Endres, S. Choi. *Emergent quantum state designs from individual many-body wavefunctions*. <a href="https://arxiv.org/abs/2103.03536" target="_blank">arXiv (2021)</a>.

We experimentally verify this observation. And utilize this concept to perform benchmarking in a Rydberg atom system.

* J. Choi, A. Shaw, I. Madjarov, X. Xie, J. Covey, J. Cotler, D. Mark, **H.-Y. Huang**, A. Kale, H. Pichler, F. Brandao, S. Choi, M. Endres. *Emergent Randomness and Benchmarking from Many-Body Quantum Chaos*. <a href="https://arxiv.org/abs/2103.03535" target="_blank">arXiv (2021)</a>.

### >> Quantum simulation and quantum algorithm

Quantum simulation is an important application of quantum computers. In the first work, we provide a tight analysis to study one of the simplest yet strongest simulation method, Trotterization / Product formula, for simulating interacting electrons.

* Y. Su, **H.-Y. Huang**, E. Campbell. *Nearly-tight Trotterization of interacting electrons*. Quantum, <a href="https://www.youtube.com/watch?v=NMc6PLOCU4g&t=39s&ab_channel=MunichCenterforQuantumScience%26Technology" target="_blank">QIP 2021</a>, <a href="https://arxiv.org/abs/2012.09194" target="_blank">arXiv (2020)</a>.

Randomness has recently been used to speed up quantum simulation algorithms. We provide a comprehensive analysis using random matrix theory, a fascinating topic in mathematics that has been contributed by <a href="https://scholar.google.com/citations?user=i4_3daEAAAAJ&hl=en" target="_blank">Joel Tropp</a> and others.

* C.-F. Chen<sup>$\dagger$</sup>, **H.-Y. Huang**<sup>$\dagger$</sup> (co-first author), R. Kueng, J. Tropp.
*Concentration for random product formulas*.
TQC 2021, <a href="https://arxiv.org/abs/2008.11751" target="_blank">arXiv (2020)</a>.

In this work, we look at how near-term quantum computers could be used to solve linear systems of equations. The method we proposed comes with rigorous guarantee. But the usefulness of quantum computers in real world problems is not yet conclusive.

* **H.-Y. Huang**, K. Bharti, P. Rebentrost.
*Near-term quantum algorithms for linear systems of equations*.
<a href="https://arxiv.org/abs/1909.07344" target="_blank">arXiv (2019)</a>.

* * *

### >> Deep learning for question answering

During undergraduate, I spent a summer at <a href="https://www.microsoft.com/en-us/research/lab/microsoft-research-ai/" target="_blank">Microsoft Research</a> working on designing deep learning models to perform questions answering (also known as machine comprehension). We were at the top of the <a href="https://rajpurkar.github.io/SQuAD-explorer/" target="_blank">leaderboard</a> back in the days.

* **H.-Y. Huang**, C. Zhu, Y. Shen, W. Chen. *FusionNet: Fusing via Fully-aware attention with application to machine comprehension*.
ICLR 2018, <a href="https://arxiv.org/abs/1711.07341" target="_blank">arXiv (2017)</a>.

After a year, I did a follow-up work at <a href="https://allenai.org/" target="_blank">Allen Institute of AI</a> that considers question answering in a conversational environment.

* **H.-Y. Huang**, E. Choi, W. Yih.
*FlowQA: grasping flow in history for conversational machine comprehension*.
ICLR 2019, <a href="https://arxiv.org/abs/1810.06683" target="_blank">arXiv (2018)</a>.

### >> Classical machine learning

In my first year of undergraduate, I started doing research in machine learning with <a href="https://scholar.google.com/citations?user=SLMkts8AAAAJ&hl=en" target="_blank">Chih-Jen Lin</a>. The following works marked the beginning of my research career. The first work studies recommendation systems using matrix factorization. The second work studies a basic task in autoML on choosing between linear and kernel classifiers.

* H.-F. Yu, **H.-Y. Huang**, I. S. Dhillon, C.-J. Lin. *A unified algorithm for one-class structured matrix factorization with side information*. AAAI 2017, <a href="https://www.csie.ntu.edu.tw/~cjlin/papers/ocmf-side/biased-leml-aaai-with-supp.pdf" target="_blank">Paper link</a>.

* **H.-Y. Huang**, C.-J. Lin. *Linear and kernel classification: When to use which?* SDM 2016, <a href="https://www.csie.ntu.edu.tw/~cjlin/papers/kernel-check/kcheck.pdf" target="_blank">Paper link</a>.

### >> Bioinformatics

During high school (2013-2014), I analyzed protein-protein interaction networks and developed models for the evolutions of protein networks.

* C.-Y. Chen, A. Ho, **H.-Y. Huang**, H.-F. Juan and H.-C. Huang. *Dissecting the human protein-protein interaction network via phylogenetic decomposition*.
<a href="https://www.nature.com/articles/srep07153" target="_blank">Scientific Reports</a>.

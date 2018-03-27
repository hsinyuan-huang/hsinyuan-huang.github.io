---
layout: post
title:  "Machine Reading Comprehension"
date:   2018-02-05
excerpt: "<strong>H.-Y. Huang</strong>, C. Zhu, Y. Shen, W. Chen. FusionNet: Fusing via Fully-aware Attention with Application to Machine Comprehension. Sixth International Conference on Learning Representations (ICLR 2018)."
feature_fig: <figure><img src="https://momohuang.github.io/assets/img/FusionNet/fusionnet.jpg"></figure>
research: true
tag:
- Research Project
- Question Answering
- Natural language processing
- Machine learning
comments: true
---

<figure>
	<img src="{{site.url}}/assets/img/FusionNet/fusionnet.jpg">
</figure>
<P align="right"><strong>*This work is done during internship at Microsoft AI+Research, Redmond, USA.</strong></P>

<center>
	<a href="{{site.url}}/assets/img/FusionNet/FusionNet.pdf" target="_blank" class="btn">
		<span style="font-size: 120%;">
		PDF Publication
		</span>
	</a>
	&nbsp;
	<a href="https://arxiv.org/abs/1711.07341" target="_blank" class="btn">
		<span style="font-size: 120%;">
		arXiv Publication
		</span>
	</a>
	&nbsp;
	<a href="https://github.com/momohuang/FusionNet-NLI" target="_blank" class="btn">
		<span style="font-size: 120%;">
		GitHub Code
		</span>
	</a>
</center>

<p>The goal is for machines to <strong>read and understand</strong>
an arbitrarily-given context (such as an article from the Wikipedia)
and <strong>answers questions</strong> about the given context.
In order to achieve this, we need to give machine the ability to think about the question when reading the context.
This is performed through <strong>attention</strong>, attending to relevant part in the question
as we read through the context.
A key concept in this work is that when humasn focus our attention, we take into account different levesl of meaning.
Sometimes we look for the exact details, did this event happen in 2016 or 2017?
Sometimes we think more abstractly and treat 2016, 2017, -37, 3.14159 all as just numbers.
<br>&nbsp;&nbsp;&nbsp;&nbsp;
Motivated from this concept, we propose a light-weight enhancement for attention, <strong>fully-aware attention</strong>,
and an end-to-end neural architecture, <strong>FusionNet</strong>, as illustrated above.
The performance improved significantly by replacing standard attention with fully-aware attention.
At the end of my internship (Sep 20th, 2017), we achieved a <strong>new state-of-the-art</strong> on
the <a href="https://rajpurkar.github.io/SQuAD-explorer/" target="_blank">Stanford Question Answering Dataset (SQuAD)</a>.
Furthermore, we improved the previous best-reported number by <strong>+5%</strong> on
<a href="https://worksheets.codalab.org/worksheets/0xc86d3ebe69a3427d91f9aaa63f7d1e7d/" target="_blank">
an adversarial dataset for machine comprehension</a>. Furthermore, it also shows decent improvement when applied
on natural language inference task.</p>
<p><u>Publication:</u><br><strong>H.-Y. Huang</strong>, C. Zhu, Y. Shen, W. Chen. FusionNet: Fusing via Fully-aware Attention with Application to Machine Comprehension. Sixth International Conference on Learning Representations (ICLR 2018).</p>

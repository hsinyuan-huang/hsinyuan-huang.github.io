---
layout: post
title:  "Implicit-Feedback Recommender System"
date:   2017-05-08
excerpt: "H.-F. Yu, <strong>H.-Y. Huang</strong>, I. S. Dhillon, C.-J. Lin. A Unified Algorithm for One-class Structured Matrix Factorization with Side Information. AAAI Conference on Artificial Intelligence (AAAI 2017)."
feature_fig: <figure><img src="https://momohuang.github.io/assets/img/ImpRecSys/imp_feed_RecSys.jpg"></figure>
research: true
tag:
- Research Project
- Recommender system
- Data mining
- Machine learning
comments: true
---

<figure>
	<img src="{{site.url}}/assets/img/ImpRecSys/imp_feed_RecSys.jpg">
</figure>

<center>
	<a href="{{ site.url }}/assets/img/ImpRecSys/biased-leml.pdf" target="_blank" class="btn">
		<span style="font-size: 120%;">
		PDF Publication
		</span>
	</a>
	&nbsp;
	<a href="{{ site.url }}/assets/img/ImpRecSys/biased-leml-supp.pdf" target="_blank" class="btn">
		<span style="font-size: 120%;">
		Supplementary
		</span>
	</a>
	&nbsp;
	<a href="https://www.csie.ntu.edu.tw/~cjlin/papers/ocmf-side/" target="_blank" class="btn">
		<span style="font-size: 120%;">
		Experimental Code
		</span>
	</a>
</center>

<p>The goal of recommendation system is to create an algorithm that is capable of learning to give accurate recommendation to the users, such as music recommendation on iTunes, or movie recommendation on Netflix. Most traditional approaches exploit <strong>user on item ratings</strong> (e.g., 1 to 5 stars) to learn a good recommendation. But in practice, people don't often leave a rating after watching a movie, making the traditional approach less useful. In this work, we assume a more natural case where only <strong>boolean ratings</strong> are present (e.g., user A watched item B or not), and develop effective algorithm to give accurate recommendation.<br>&nbsp;&nbsp;&nbsp;&nbsp;
The scenario can be illustrated by the above figure. To solve this problem, an approach is to learn a <strong>latent vector</strong> for each people and item, where the inner-product of the latent vectors characterize the inclination of the user on the item.
Therefore to accurately <strong>predict human preference</strong>, we have to find the best latent representation for the users and the items.
In this work, we proposed a general framework for incorporating feature information (e.g. the age and nationality of users or the characteristic of the item) and graph information (e.g. the Facebook friends relationship of the users) to learn a better representation.
Furthermore, we investigate the use of <strong>general convex loss</strong> (where we are the first to design efficient optimization method for losses other than the square loss), and found that classification loss can find a more <strong>accurate latent representation</strong>, leading to substantially improved performance.</p>
<p><u>Publication:</u><br>H.-F. Yu, <strong>H.-Y. Huang</strong>, I. S. Dhillon, C.-J. Lin. A Unified Algorithm for One-class Structured Matrix Factorization with Side Information. AAAI Conference on Artificial Intelligence (AAAI 2017).</p>

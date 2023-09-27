---
title: "Overcoming popularity bias in adversarial pairwise learning for fashion recommendations"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-1
date: 2023-09-18
venue: 'Fifth Workshop on Recommender Systems in Fashion'
citation: 'Mario Mallea, Ricardo Ñanculef, Denis Parra'
---

https://fashionxrecsys.github.io/fashionxrecsys-2023/

**Abstract:** Generative adversarial training has recently raised significant interest in recommender systems. Adversarial pairwise learning, in particular, has led toward methods to select and create unobserved training samples that generalize user preferences, increasing the accuracy and robustness of collaborative filtering (CF) models. Despite this success, adversarial pairwise learning has not been analyzed in order to recommend long-tail and cold-start items, as well as their ability to promote novelty and diversity. These concerns are crucial for modern fashion recommender systems.
 
This paper investigates adversarial pairwise learning in fashion data sparsity scenarios in which most items are consumed by only a few users (long-tail items), and there is a substantial proportion of items without interactions (cold-start items). We found that adversarial pairwise sampling increases the bias of CF models toward popular items, resulting in under-recommendation of relevant but less popular long-tail items, poor cold start performance, and low aggregate diversity, i.e., unfair coverage of items among recommendation lists. To address these problems, we propose a multi-modal extension of adversarial pairwise learning that incorporates text and visual attributes about the items in addition to user-item interaction data. As in the original model, our approach relies on a minimax game. A generative model proposes items for a user considering her visual and textual preferences. Then, a collaborative critic discriminates the suggested items from those already consumed by the user. We focus on learning how the extra item attributes correlate with the users' preferences compared to classic pairwise learning alternatives. 

We conduct experiments on three variants of a challenging fashion dataset in which more than $99.99\%$ of the user-item interactions are unknown, and around $2/3$ of the items have less than $5$ interactions. We found that our multi-modal adversarial pairwise approach achieves better results than the well-known pairwise alternative in the most complex scenario: the recommendation of new items. Furthermore, the proposed adversarial framework successfully leverages content to make more diverse and novel recommendations. 

Our code is publicly available on GitHub.


# Acknowledgement

<img width="856" alt="image" src="https://github.com/MariodotR/MarioMallea.github.io/assets/70358709/36316a89-8a32-48a0-bf91-50381331049c">


<!---
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
paperurl: 'http://academicpages.github.io/files/paper1.pdf'
[//]: #( [Download paper here](http://academicpages.github.io/files/paper1.pdf) )
[//]: #(Recommended citation: Your Name, You. (2009). "Paper Title Number 1." <i>Journal 1</i>. 1(1).)
-->



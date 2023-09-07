---
title: "Enhancing intra-modal similarity in a cross-modal triplet loss"
collection: publications
permalink: /publication/2010-10-01-paper-title-number-2
excerpt: 'This paper is about the number 2. The number 3 is left for future work.'
date: 2010-10-01
venue: 'Journal 1'
paperurl: 'http://academicpages.github.io/files/paper2.pdf'
citation: 'Mario Mallea, [Ricardo Ñanculef](https://scholar.google.com/citations?hl=es&user=hndLsckAAAAJ&view_op=list_works&sortby=pubdate), Mauricio Araya'
---

https://ds2023.inesctec.pt/

**Abstract:** Cross-modal retrieval requires building a common latent space
that captures and correlates information from different data modalities,
usually images and texts. Cross-modal training based on the triplet loss
with hard negative mining is a state-of-the-art technique to address
this problem. This paper shows that such approach is not always ef-
fective in handling intra-modal similarities. Specifically, we found that
this method can lead to inconsistent similarity orderings in the latent
space, where intra-modal pairs with unknown ground-truth similarity are
ranked higher than cross-modal pairs representing the same concept. To
address this problem, we propose two novel loss functions that leverage
intra-modal similarity constraints available in a training triplet but not
used by the original formulation. Additionally, this paper explores the
application of this framework to unsupervised image retrieval problems,
where cross-modal training can provide the supervisory signals that are
otherwise missing in the absence of category labels. Up to our knowledge,
we are the first to evaluate cross-modal training for intra-modal retrieval
without labels.
We present comprehensive experiments on MS-COCO and Flickr30K,
demonstrating the advantages and limitations of the proposed meth-
ods in cross-modal and intra-modal retrieval tasks in terms of perfor-
mance and novelty measures. Our code is publicly available on GitHub

<!---
This paper is about the number 2. The number 3 is left for future work.

[Download paper here](http://academicpages.github.io/files/paper2.pdf)

Recommended citation: Your Name, You. (2010). "Paper Title Number 2." <i>Journal 1</i>. 1(2).
-->

# ColdRoute

ColdRoute: Effective Routing of Cold Questions in Stack Exchange Sites

> Routing questions in Community Question Answer services such as Stack Exchange sites is a well-studied problem. Yet, cold-start—a phenomena observed when a new question is posted is not well addressed by existing approaches. Additionally, cold questions posted by new askers present significant challenges to state-of-the-art approaches. We propose ColdRoute to address these challenges. ColdRoute is able to handle the task of routing cold questions posted by new or existing askers to matching experts. Specifically, we use Factorization Machines on the one-hot encoding of critical features such as question tags and compare our approach to well-studied techniques such as CQARank and semantic matching (LDA, BoW, and Doc2Vec). Using data from eight stack exchange sites, we are able to improve upon the routing metrics (Precision@1, Accuracy, MRR) over the state-of-the-art models such as semantic matching by 159.5%, 31.84%, and 40.36% for cold questions posted by existing askers, and 123.1%, 27.03%, and 34.81% for cold questions posted by new askers respectively.

* Journal Track of European Conference on Machine Learning and Principles and Practice of Knowledge Discovery in Databases (ECML PKDD) 2018
* [arXiv](https://arxiv.org/abs/1807.00462)
* [Springer](https://link.springer.com/article/10.1007%2Fs10618-018-0577-7)
* [Slides for ECML PKDD 2018 Presentation](https://www.dropbox.com/s/upqynsfc4ivpzjc/Slides_ECMLPKDD_2018_ColdRoute.pdf?dl=0)

Code for preprocessing Stack Exchange sites is available: [PyStack](https://github.com/zhenv5/PyStack)

We are actively working on publishing other parts of our code.

### Consider to cite our paper

* [Download Bib](https://citation-needed.springer.com/v2/references/10.1007/s10618-018-0577-7?format=bibtex&flavour=citation)

> @Article{Sun2018,
author="Sun, Jiankai
and Vishnu, Abhinav
and Chakrabarti, Aniket
and Siegel, Charles
and Parthasarathy, Srinivasan",
title="ColdRoute: effective routing of cold questions in stack exchange sites",
journal="Data Mining and Knowledge Discovery",
year="2018",
month="Jun",
day="29",
abstract="Routing questions in Community Question Answer services such as Stack Exchange sites is a well-studied problem. Yet, cold-start---a phenomena observed when a new question is posted is not well addressed by existing approaches. Additionally, cold questions posted by new askers present significant challenges to state-of-the-art approaches. We propose ColdRoute to address these challenges. ColdRoute is able to handle the task of routing cold questions posted by new or existing askers to matching experts. Specifically, we use Factorization Machines on the one-hot encoding of critical features such as question tags and compare our approach to well-studied techniques such as CQARank and semantic matching (LDA, BoW, and Doc2Vec). Using data from eight stack exchange sites, we are able to improve upon the routing metrics (Precision@1, Accuracy, MRR) over the state-of-the-art models such as semantic matching by 159.5, 31.84, and 40.36{\%} for cold questions posted by existing askers, and 123.1, 27.03, and 34.81{\%} for cold questions posted by new askers respectively.",
issn="1573-756X",
doi="10.1007/s10618-018-0577-7",
url="https://doi.org/10.1007/s10618-018-0577-7"
}


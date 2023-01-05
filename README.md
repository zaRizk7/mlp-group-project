# MLP Group Project

## Key Steps
1. Understanding literature
2. Finalise title

## Existing Methods
* State-of-the-art - Few-shot learning (MAML), semi-supervised learning (e.g. FixMatch), Self-supervised learning (DINO)
* Older methods - Siamese Network (FSL), Prototype Network (SSL), SimCLR (SelfSL), Pseudo labelling (SemiSL)

## Common Datasets
* Usually - Binary classification
* Previous work - Multi-class classification (Only 250 data points)
* Thoughts: could train on binary classification, then do transfer learning to train on previous dataset

## Task
* Previous dataset - Glaucoma Severity Detection
  * Disclaimer: Likely change
 * Motivation: 
   * Medical image are expensive to be labelled. 
   * Incorporating learning methods like FSL, SemiSL, or SelfSL that is good on datasets that has few annotation can be useful.
* Reading new papers might mean we identify new task

## State-of-the-art method
* Model Agnostic Meta Learning (Few-Shot Learning)
* FixMatch (Semi-Supervised Learning)
* DINO, SimCLRv2 (Self-Supervised Learning)
* Q: HOW STATE OF THE ART ARE THESE?
* Q: Too easy, perfect, too difficult?

## Metrics
* Task-dependent
* To be discussed later.

## Responsibilities (for now)
1. Understanding review papers: all read
2. Understanding research papers: divide responsibilities

## References
### Review Paper
1. A Comprehensive Survey of Few-shot Learning: Evolution, Applications, Challenges, and Opportunities (2022)
  * URL: https://arxiv.org/pdf/2205.06743.pdf
2. A Review of Generalized Zero-Shot Learning Methods (2022)
  * URL: https://arxiv.org/pdf/2011.08641.pdf
4. Self-Supervised Representation Learning: Introduction, Advances and Challenges (2021)
  * URL: https://arxiv.org/pdf/2110.09327.pdf
5. Meta-Learning in Neural Networks: A Survey (2020)
  * URL: https://arxiv.org/pdf/2004.05439.pdf
6. Generalizing from a Few Examples: A Survey on Few-shot Learning (2019)
  * URL: https://dl.acm.org/doi/pdf/10.1145/3386252
### Research Paper
TBD

# Compression Mechanisms

# Current Pipeline Setup
1. https://arxiv.org/pdf/2007.11797.pdf It shows that we can jointly optimze the accuracy of downstream task and the size of the bottleneck layer. A proof-of-concept paper.

2. https://arxiv.org/pdf/2108.11898.pdf Image feature distillation. Suppose the original pipeline is input->feature A->output. The system uses a student autoencoder network to transform input->feature A to input->z->feature and minimize size of z (after entropy encoding) during training. 

3. https://dl.acm.org/doi/pdf/10.1145/3527155 Summary of recent advances of split computing and early exit. Contains three tables listing recent work in split computing, bottleneck injection, and early exits.

4. https://dl.acm.org/doi/10.1145/3093337.3037698 Neurosurgeon ASPLOS 2017. On split computing

5. https://arxiv.org/pdf/2008.06402.pdf Need to read

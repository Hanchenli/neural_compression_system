# Compression Mechanisms

# Current Pipeline Setup
1. https://arxiv.org/pdf/2007.11797.pdf It shows that we can jointly optimze the accuracy of downstream task and the size of the bottleneck layer. A proof-of-concept paper.

2. https://arxiv.org/pdf/2108.11898.pdf Image feature distillation. Suppose the original pipeline is input->feature A->output. The system uses a student autoencoder network to transform input->feature A to input->z->feature and minimize size of z (after entropy encoding) during training. 

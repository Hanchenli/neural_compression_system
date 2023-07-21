# Compression Mechanisms
1. https://arxiv.org/pdf/2107.12038.pdf GAN for video compresison. Not read

2. https://arxiv.org/pdf/2305.18231.pdf Diffusion for image compression. Not read

3. https://openaccess.thecvf.com/content/CVPR2023/papers/Agustsson_Multi-Realism_Image_Compression_With_a_Conditional_Generator_CVPR_2023_paper.pdf Similar to 2 but not diffusion. Not read

# Current Pipeline
1. https://arxiv.org/pdf/2007.11797.pdf It shows that we can jointly optimze the accuracy of downstream task and the size of the bottleneck layer. A proof-of-concept paper.

2. https://arxiv.org/pdf/2108.11898.pdf Image feature distillation. Suppose the original pipeline is input->feature A->output. The system uses a student autoencoder network to transform input->feature A to input->z->feature and minimize size of z (after entropy encoding) during training. 

3. https://dl.acm.org/doi/pdf/10.1145/3527155 Summary of recent advances of split computing and early exit. Contains three tables listing recent work in split computing, bottleneck injection, and early exits.

4. https://dl.acm.org/doi/10.1145/3093337.3037698 Neurosurgeon ASPLOS 2017. On split computing. Not read

5. https://arxiv.org/pdf/2008.06402.pdf Need to read

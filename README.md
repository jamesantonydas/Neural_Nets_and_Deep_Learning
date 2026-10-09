# Dilated Convolutional Neural Networks
Traditional Convolutional Neural Networks (CNNs) downsample feature maps using pooling layers or strided convolutions to aggregate contextual information. However, this loss of spatial resolution is detrimental for dense prediction tasks such as semantic segmentation. 

**Dilated Convolutions** address this issue by introducing spaces (zeros) between kernel elements, enabling exponential expansion of receptive fields across network layers without decreasing spatial resolution or increasing computational complexity/parameter count.

This repository contains research analysis, conceptual explanations, and architectural implementations based on the task **Convolutional Neural Networks via Dilated Convolutions** for the course *DLBDSNNDL01-01: Neural Nets and Deep Learning* 

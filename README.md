# Fast-SCNN: Fast Semantic Segmentation Network

A PyTorch implementation of Fast-SCNN: Fast Semantic Segmentation Network from the paper by Rudra PK Poudel, Stephan Liwicki.

### Abstract

The encoder-decoder framework is state-of-the-art for offline semantic image segmentation. Since the rise in autonomous systems, real-time computation is increasingly desirable. In this paper, we introduce fast segmentation convolutional neural network (Fast-SCNN), an above realtime semantic segmentation model on high resolution image data (1024 × 2048px) suited to efficient computation on embedded devices with low memory. Building on existing two-branch methods for fast segmentation, we introduce our ‘learning to downsample’ module which computes lowlevel features for multiple resolution branches simultaneously. Our network combines spatial detail at high resolution with deep features extracted at lower resolution, yielding an accuracy of 68.0% mean intersection over union at 123.5 frames per second on Cityscapes. We also show that large scale pre-training is unnecessary. We thoroughly validate our metric in experiments with ImageNet pre-training and the coarse labeled data of Cityscapes. Finally, we show even faster computation with competitive results on subsampled inputs, without any network modifications.

`Currently, the repo has only the model. I will soon add the training code too.

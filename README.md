# EAPNet
Abstract
Recent studies witnessed that attention mechanisms achieve impressive performance in computer vision task. Current attention mechanism based segmentation methods differ with each other in position and form of the attention mechanism, and perform differently in practice. This paper firstly introduces the effectiveness of multi-scale context features and attention mechanisms in segmentation tasks. We find that multi-scale and channel attention can play a vital role in constructing effective context features. Based on this analysis, this paper proposes an efficient attention pyramid network (EAPNet) for semantic segmentation. Specifically, to efficient handle the problem of segmenting objects at multiple scales, we design modules which employ atrous convolution with channel attention in cascade or in parallel to capture multi-scale context by using multiple atrous rates. Furthermore, we propose a residual attention fusion block (RAFB), whose purpose is to simultaneously focus on meaningful feature maps and spatial location information. At the same time, we will explore different channel attention modules and spatial attention modules, and describe their impact on network performance. We empirically evaluate our EAPNet on two semantic segmentation datasets ,including PASCAL VOC 2012 and Cityscapes datasets. Experimental results show that without MS COCO pre-training and any post-processing, EAPNet achieved 81.7$\%$ mIoU on the PASCAL VOC 2012 validation set. With deeplabv3+ as the benchmark, EAPNet improve the model performance of more than 1.50$\%$ mIoU.
The code will be open source later.

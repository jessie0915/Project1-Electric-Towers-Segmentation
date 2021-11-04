# Project1-Electric-Towers-Segmentation
## Electric Towers Segmentation by Unsupervised Domain Adaptation Approach
For the smart drone application of automatic electric tower (e-tower) inspection, electric tower segmentation is required for positioning and detecting targets. However, it suffered from the lack of ground truth problem while segmented by deep learning approach. Therefore, large simulated e-tower dataset which generated from the projections of 3D models is feed into the segmentation model for supervised learning. Next, we may suffer from the domain shift problem while the distribution of real data is far away from the distribution of synthetic data. An unsupervised domain adaptation method was implemented for improving the segmented results on real images of e-towers. All results show that it’s an opportunity to segment real e-tower images by simulated e-towers if we trained GAN model carefully.


![15_DLP2020_poster](/picture/15_DLP2020_poster.jpg "15_DLP2020_poster")

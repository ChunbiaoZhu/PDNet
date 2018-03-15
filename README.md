## PDNet: Prior-Model Guided Depth-enhanced Network for Salient Object Detection




|  ![ICME 2018 logo][logo-ICME] | Paper accepted at [IEEE International Conference on Multimedia and Expo (ICME) 2018](http://www.icme2018.org/) July 23-27, 2018 San Diego, USA. |
|:-:|---|

[logo-ICME]: https://github.com/ChunbiaoZhu/PDNet/blob/master/icme.png "ICME 2018 logo"




## Abstract

Fully convolutional neural networks (FCNs) have shown outstanding
performance in many computer vision tasks including
salient object detection. However, there still remains two
issues needed to be addressed in deep learning based saliency
detection. One is the lack of tremendous amount of annotated
data to train a network. The other is the lack of robustness
for extracting salient objects in images containing complex
scenes. In this paper, we present a new architecture􀀀PDNet, a
robust prior-model guided depth-enhanced network for RGBD
salient object detection. In contrast to existing works, in
which RGB-D values of image pixels are fed directly to a network,
the proposed architecture is composed of a master network
for processing RGB values, and a sub-network making
full use of depth cues and incorporate depth-based features
into the master network. To overcome the limited size of the
labeled RGB-D dataset for training, we employ a large conventional
RGB dataset to pre-train the master network, which
proves to contribute largely to the final accuracy. Extensive
evaluations over five benchmark datasets demonstrate that our
proposed method performs favorably against the state-of-theart
approaches.

 


## Framework
![QFramework saliency detection](https://github.com/ChunbiaoZhu/PDNet/blob/master/framework.png)


## Code & Results

Source code is available! You can download in [here](https://github.com/cai199626/PDNet)

If you use this code.

Please cite as:

PDNet: Prior-Model Guided Depth-enhanced Network for Salient Object Detection.
Chunbiao Zhu, Xing Cai, Kan Huang, Thomas.H Li and Ge Li
IEEE International Conference on Multimedia and Expo (ICME) 2018.

## SSD Dataset
The dataset proposed in our paper is one of our contributions to the research community, which public at ICCVW 2017. This dataset is collected for saliency evaluation on stereo images, and contain a variety of challenging cases.

You can download in [here](https://github.com/ChunbiaoZhu/TPPF)

If you use this dataset.

Please cite as:

G. Li and C. Zhu, “A three-pathway psychobiological
framework of salient object detection using stereoscopic
technology,” in 2017 ICCVW, Oct 2017, pp. 3008–3014.


## Acknowledgements

This work was supported by the grant of National Natural Science Foundation of China (No.U1611461), Shenzhen Peacock Plan (20130408-183003656), and Science and Technology Planning Project of Guangdong Province, China (No. 2014B090910001).


## Contact

If you have any general doubt about our work or code which may be of interest for other researchers, please use the [public issues section](https://github.com/ChunbiaoZhu/PDNet/issues) on this github repo. Alternatively, drop us an e-mail at <mailto:zhuchunbiao@pku.edu.cn>.



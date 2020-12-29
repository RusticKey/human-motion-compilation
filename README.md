# Human Motion and Novel View Synthesis Compilation

## What is this?
  This project page is a collection of papers (and possibly code) that has something to do with human motion and novel view synthesis in 2D and 3D space. There are two major classes of methods when doing it in 2D space:
  * Spatial Transformation (using flow information, etc)
  * Conditioned Generation (pose label map, etc)
  
Papers are also split into several sub-categories (ones with the project page):
  * Novel View Synthesis - This category is about rendering/generating an image of a human within another pose, may be a single picture or a video
  * Motion Retargeting, Representation, Continuation - This category is about the modeling of human motion as well as skeletal prediction. May also include temporally-coherent pose estimation
  * 3D Human Digitization - From a(n ideally) single image, this category deals with 3D human generation along with texture and/or shape inference from unseen angles
 
 Papers that do not have first-party implementations are put into another category with two sub-categories:
  * Architectural - Contribution is mainly about architecture
  * Representation - Contribution is related to information representation, spatial representation, or feature extraction methods
  
  This project page is only intended to supplement my studies and research where everything is (hopefully nicely) organized into one place. 
  
---
## Papers with Project Pages

### Human Novel View Synthesis
* [**[ICCV 2019]** Everybody Dance Now](https://carolineec.github.io/everybody_dance_now/)
* [**[ICCV 2019]** Liquid Warping GAN: A Unified Framework for Human Motion Imitation, Appearance Transfer and Novel View Synthesis](https://svip-lab.github.io/project/impersonator.html)
* [**[CVPR 2019]** Progressive Pose Attention for Person Image Generation](https://github.com/tengteng95/Pose-Transfer)
* [**[NeurIPS 2019]** First Order Motion Model for Image Animation](https://github.com/AliaksandrSiarohin/first-order-model)
* [**[CVPR 2020]** Deep Image Spatial Transformation for Person Image Generation](https://renyurui.github.io/GFLA-web/)
* [**[Under Review IEEE TPAMI 2020]** Liquid Warping GAN with Attention: A Uniﬁed Framework for Human Image Synthesis](https://www.impersonator.org/work/impersonator-plus-plus.html)

### Human Motion Representation, Retargeting, Continuation
* [**[CVPR 2020]** Dynamic Multiscale Graph Neural Networks for 3D Skeleton-Based Human Motion Prediction](https://github.com/limaosen0/DMGNN)
* [**[CVPR 2020]** TransMoMo: Invariance-Driven Unsupervised Video Motion Retargeting](https://yzhq97.github.io/transmomo/)
* [**[CVPR 2020]** Attention Mechanism Exploits Temporal Contexts: Real-time 3D Human Pose Reconstruction](https://sites.google.com/a/udayton.edu/jshen1/cvpr2020)
* [**[SIGGRAPH 2020]** XNect: Real-time Multi-Person 3D Motion Capture with a Single RGB Camera](https://gvv.mpi-inf.mpg.de/projects/XNect/)
* [**[IEEE FnG+TBIOM 2020]** Head2Head: Video-based Neural Head Synthesis](https://github.com/michaildoukas/head2head)
* [**[NeurIPS 2020]** Residual Force Control for Agile Human Behavior Imitation and Extended Motion Synthesis](https://www.ye-yuan.com/rfc/)

### 3D Human Digitization
* [**[ICCV 2019]** DeepHuman: 3D Human Reconstruction from a Single Image](http://www.liuyebin.com/deephuman/deephuman.html)
* [**[ICCV 2019]** PIFu: Pixel-Aligned Implicit Function for High-Resolution Clothed Human Digitization](https://shunsukesaito.github.io/PIFu/)
* [**[CVPR 2019]** Photo Wake-Up: 3D Character Animation from a Single Photo](https://grail.cs.washington.edu/projects/wakeup/)
* [**[CVPR 2020]** PIFuHD: Multi-Level Pixel-Aligned Implicit Function for High-Resolution 3D Human Digitization](https://shunsukesaito.github.io/PIFuHD/)
* [**[CVPR 2020]** CAPE: Clothed Auto-Person Encoding](https://github.com/QianliM/CAPE)
* [**[NeurIPS 2020]** Geo-PIFu: Geometry and Pixel Aligned Implicit Functions for Single-view Human Reconstruction](https://github.com/simpleig/Geo-PIFu)

### Datasets
* [Human3.6M](http://vision.imar.ro/human3.6m/description.php)
* [Mixamo](https://www.mixamo.com/#/)
* [THuman](https://github.com/ZhengZerong/DeepHuman/tree/master/THUmanDataset)
* [DFAUST](https://dfaust.is.tue.mpg.de/)
---
## Papers without first-party implementations
Third party implementations (if any) will be put in second-order bullet points
### Architectural / Training
* [**[arXiv 2020]** Human Motion Transfer from Poses in the Wild](https://arxiv.org/pdf/2004.03142.pdf)
* [**[ICCVW 2019]** Dance Dance Generation](https://openaccess.thecvf.com/content_ICCVW_2019/papers/HBU/Zhou_Dance_Dance_Generation_Motion_Transfer_for_Internet_Videos_ICCVW_2019_paper.pdf)
### Representation
* [**[CVPR 2018]** Synthesizing Images of Humans in Unseen Poses](https://openaccess.thecvf.com/content_cvpr_2018/papers/Balakrishnan_Synthesizing_Images_of_CVPR_2018_paper.pdf)
* [**[CVPR 2019]** Coordinate-based Texture Inpainting for Pose-Guided Human Image Generation](https://openaccess.thecvf.com/content_CVPR_2019/papers/Grigorev_Coordinate-Based_Texture_Inpainting_for_Pose-Guided_Human_Image_Generation_CVPR_2019_paper.pdf)
* [**[arXiv 2020]** Human Motion Transfer with 3D Constraints and Detail Enhancement](https://arxiv.org/abs/2003.13510)
---
## Literature
Papers that are important for human motion and novel view synthesis tasks
* [Self-Attention GAN](https://arxiv.org/abs/1805.08318)
* [pix2pix](https://phillipi.github.io/pix2pix/) and [pix2pixHD](https://github.com/NVIDIA/pix2pixHD)
* [vid2vid](https://github.com/NVIDIA/vid2vid)

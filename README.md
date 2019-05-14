# Awesome-Image-Tagging
A paper list of awesome Image Tagging I've read

## Image Tagging (Multi-label Image Classification)
Describe an image using tags. Tags can be objects, situation, and user generated tags.

* WARP
  - [Y Gong, Y Jia, T Leung, A Toshev, S loffe. Deep Convolutional Ranking for Multilabel Image Annotation. arXiv:1312.4894](https://arxiv.org/abs/1312.4894)  
  - propose WARP loss for multi-label image annotation.

* CNN-RNN
  - [J Wang, Y Yang, J Mao, Z Huang, C Huang, W Xu. CNN-RNN: A Unified Framework for Multi-Label Image Classification. CVPR 2016](https://www.cv-foundation.org/openaccess/content_cvpr_2016/html/Wang_CNN-RNN_A_Unified_CVPR_2016_paper.html)  
  - utilize RNN combined with CNN to learn a joint image-label embedding to characterize the semantic label dependency as well as the image-label relevance.

* S-CNN-RNN
  - [F Liu, T Xiang, TM Hospedales, W Yang, C Sun. Semantic Regularisation for Recurrent Image Annotation](https://arxiv.org/abs/1611.05490)  
  - using a semantically regularised embedding layer as the interface between the CNN and RNN. simple modification to CNN-RNN?

* Multi-label Triplet Embeddings
  - [Z Seymour, ZM Zhang. Multi-label Triplet Embeddings for Image Annotation from User-Generated Tags. ICMR 2018](https://dl.acm.org/citation.cfm?id=3206061)
  
* Multi-Modal Multi-Scale Deep Learning for Large-Scale Image Annotation
  - [Yulei Niu, Zhiwu Lu, Ji-Rong Wen, Tao Xiang, Shih-Fu Chang. Multi-Modal Multi-Scale Deep Learning for Large-Scale Image Annotation. IEEE TIP 2019](https://arxiv.org/abs/1709.01220)
  - using noisy tags + label quantity prediction network
  
* Attend and Imagine
  - [Fan Lyu, Qi Wu, Fuyuan Hu, Qingyao Wu, Mingkui Tan. Attend and Imagine: Multi-label Image Classification with Visual Attention and Recurrent Neural Networks. IEEE Transactions on Multimedia 2019.01](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8624407)
  - Attention + RNN

## Zero-shot Image Tagging
Annotate an image by unseen tags. It means 'unseen at the training stage'.

* HierSE
  - [X Li, S Liao, W Lan, X Du, G Yang. Zero-shot Image Tagging by Hierarchical Semantic Embedding. SIGIR 2015](https://dl.acm.org/citation.cfm?id=2767773)

* Fast0Tag
  - [Y Zhang, B Gong, M Shah. Fast Zero-shot Image Tagging. CVPR 2016](https://arxiv.org/abs/1605.09759)
  
* Deep Multiple Instance Learning
  - [S Rahman, S Khan. Deep Multiple Instance Learning for Zero-shot Image Tagging. ECCV 2018](https://arxiv.org/abs/1803.06051)

## Diverse Image Annotation
Describe an image using a limited numbers of tags, whereby the retrieved tags need to cover as much useful information about the image as possible. (by Diverse Image Annotation, CVPR 2017)

* DIA
  - [B Wu, F Jia, W Liu, B Ghanem. Diverse Image Annotation. CVPR 2017](https://ivul.kaust.edu.sa/Documents/Publications/2017/Diverse%20Image%20Annotation.pdf)
* D2IA-GAN
  - [B Wu, W Chen, P Sun, W Liu, B Ghanem, S Lyu. Tagging like humans : Diverse and Distinct Image Annotation. CVPR 2018](https://arxiv.org/abs/1804.00113)

## Notice
This repository is just made for my own studying, so there may be incorrect information.<br>
Also, I regard 'image tagging', 'image annotation', 'multi-label image classification' as same task (actually may be little bit different) in this repository.<br>
Thank you!<br><br>

Email: kabbi159@gmail.com

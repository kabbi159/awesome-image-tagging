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

## To Read (CVPR 2019 Accepted Paper List)
I am so excited to read awesome CVPR 2019 aceepted papers about Image Tagging. Also, it is surprising that many papers on Image Tagging has accepted this year.

* Weakly Supverised Deep Image Hashing through Tag Embeddings
  - [Vijetha Gattupalli, Yaoxin Zhuo, Baoxin Li. Weakly Supervised Deep Image Hashing through Tag Embeddings. CVPR 2019](https://arxiv.org/pdf/1806.05804.pdf)

* Metatdata Neighbourhood Graph Co-Attention Networks
  - Junjie Zhang, Qi Wu, Jian Zhang, Chunhua Shen, Jianfeng Lu. Mind Your Neighbours: Image Annotation with Metadata Neighbourhood Graph Co-Attention Networks. CVPR 2019 (No arxiv Yet!)
  - Looks like follow-up paper ['Love Thy Neighbors: Image Annotation by Exploiting Image Metatda' by Justin Johson, Lamberto Ballan, Li Fei-Fei](https://cs.stanford.edu/people/jcjohns/papers/iccv15/JohnsonICCV2015.pdf)

* Graph Convolutional Networks (GCN)
  - [Zhao-Min Chen, Xiu-Shen Wei, Peng Wang, Yanwen Guo. Multi-Label Image Recognition with Graph Convolutional Networks. CVPR 2019](https://arxiv.org/pdf/1904.03582.pdf)

* Learning with Partial Labels + Graph Neural Network (GNN)
  - [Thibaut Durand, Nazanin Mehrasa, Greg Mori. Learning a Deep ConvNet for Multi-label Classification with Partial Labels. CVPR 2019](https://arxiv.org/pdf/1902.09720.pdf)
  
* Visual Attention Consistency under Image Transforms
  - Hao Guo, Kang Zheng, Xiaochuan Fan, Hongkai Yu, Song Wang. Visual Attention Consistency under Image Transforms for Multi-label Image Classification. CVPR 2019 (No arxiv Yet!)
  
* LaSO(Label-Set Operations networks) : few-shot learning
  - [Amit Alfassy, Leonid Karlinsky, Ami Aides et al. LaSO: Label-Set Operations networks for multi-label few-shot learning. CVPR 2019](https://arxiv.org/pdf/1902.09811.pdf)



## Notice
This repository is just made for my own studying, so there may be incorrect information.<br>
Also, I regard 'image tagging', 'image annotation', 'multi-label image classification' as same task (actually may be little bit different) in this repository.<br>

*I'd appreciate it if everybody could reccommend me image tagging paper that I can read.<br>*
Thank you!<br><br>

Email: kabbi159@gmail.com

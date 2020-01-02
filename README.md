# Awesome-Image-Tagging
A paper list of awesome Image Tagging I've read

## Image Tagging (Multi-label Image Classification)
Describe an image using tags. Tags can be objects, situation, and user generated tags.

* WARP
  - **Deep Convolutional Ranking for Multilabel Image Annotation** [[paper]](https://arxiv.org/abs/1312.4894)<br>
  Y Gong, Y Jia, T Leung, A Toshev, S loffe<br>
  arXiv:1312.4894   
  - propose WARP loss for multi-label image annotation.

* CNN-RNN
  - **CNN-RNN: A Unified Framework for Multi-Label Image Classification** [[paper]](https://www.cv-foundation.org/openaccess/content_cvpr_2016/html/Wang_CNN-RNN_A_Unified_CVPR_2016_paper.html)<br>
  J Wang, Y Yang, J Mao, Z Huang, C Huang, W Xu<br>
  IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2016   
  - utilize RNN combined with CNN to learn a joint image-label embedding to characterize the semantic label dependency as well as the image-label relevance.

* S-CNN-RNN
  - **Semantic Regularisation for Recurrent Image Annotation** [[paper]](https://arxiv.org/abs/1611.05490)<br>
  F Liu, T Xiang, TM Hospedales, W Yang, C Sun<br>
  IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2017
  - using a semantically regularised embedding layer as the interface between the CNN and RNN. simple modification to CNN-RNN?

* Multi-label Triplet Embeddings
  - **Multi-label Triplet Embeddings for Image Annotation from User-Generated Tags** [[paper]](https://dl.acm.org/citation.cfm?id=3206061)<br>
  Z Seymour, ZM Zhang<br>
  ACM International Conference on Multimedia Retrieval (ICMR), 2018
  
* Knowledge Distillation from Weakly-Supervised Detection
  - **Multi-Label Image Classification via Knowledge Distillation from Weakly-Supervised Detection** [[paper]](https://arxiv.org/abs/1809.05884)<br>
  Yongcheng Liu, Lu Sheng, Jing Shao, Junjie Yan, Shiming Xiang, Chunhong Pan<br>
  ACM International Conference on Multimedia (ACM MM), 2018
  
* Multi-Modal Multi-Scale Deep Learning for Large-Scale Image Annotation
  - **Multi-Modal Multi-Scale Deep Learning for Large-Scale Image Annotation** [[paper]](https://arxiv.org/abs/1709.01220)<br>
  Yulei Niu, Zhiwu Lu, Ji-Rong Wen, Tao Xiang, Shih-Fu Chang<br>
  IEEE Transactions on Image Processing (TIP), 2019
  - using noisy tags + label quantity prediction network
  
* Attend and Imagine
  - **Attend and Imagine: Multi-label Image Classification with Visual Attention and Recurrent Neural Networks** [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8624407)<br>
  Fan Lyu, Qi Wu, Fuyuan Hu, Qingyao Wu, Mingkui Tan<br>
  IEEE Transactions on Multimedia, 2019
  - Attention + RNN

## Zero-shot Image Tagging
Annotate an image by unseen tags. It means 'unseen at the training stage'.

* HierSE
  - **Zero-shot Image Tagging by Hierarchical Semantic Embedding** [[paper]](https://dl.acm.org/citation.cfm?id=2767773)<br>
  X Li, S Liao, W Lan, X Du, G Yang<br>
  38th Annual ACM SIGIR Conference on Research & Development on Information Retrieval (SIGIR), 2015

* Fast0Tag
  - **Fast Zero-shot Image Tagging**  [[paper]](https://arxiv.org/abs/1605.09759)<br>
  Y Zhang, B Gong, M Shah<br>
  IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2016
  
* Deep Multiple Instance Learning
  - **Deep Multiple Instance Learning for Zero-shot Image Tagging** [[paper]](https://arxiv.org/abs/1803.06051)<br>
  S Rahman, S Khan<br>
  15th European Conference on Computer Vision (ECCV), 2018

## Diverse Image Annotation
Describe an image using a limited numbers of tags, whereby the retrieved tags need to cover as much useful information about the image as possible. (by Diverse Image Annotation, CVPR 2017)

* DIA
  - **Diverse Image Annotation** [[paper]](https://ivul.kaust.edu.sa/Documents/Publications/2017/Diverse%20Image%20Annotation.pdf)<br>
  B Wu, F Jia, W Liu, B Ghanem<br>
  IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2017
* D2IA-GAN
  - **Tagging like humans : Diverse and Distinct Image Annotation** [[paper]](https://arxiv.org/abs/1804.00113)<br>
  B Wu, W Chen, P Sun, W Liu, B Ghanem, S Lyu<br>
  IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2018

## CVPR 2019 Accepted Paper List
I am so excited to read awesome CVPR 2019 aceepted papers about Image Tagging. Also, it is surprising that many papers on Image Tagging has accepted this year.

* Weakly Supverised Deep Image Hashing through Tag Embeddings
  - **Weakly Supervised Deep Image Hashing through Tag Embeddings** [[paper]](https://arxiv.org/pdf/1806.05804.pdf)<br>
  Vijetha Gattupalli, Yaoxin Zhuo, Baoxin Li<br>
  IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2019

* Metatdata Neighbourhood Graph Co-Attention Networks
  - **Mind Your Neighbours: Image Annotation with Metadata Neighbourhood Graph Co-Attention Networks** [[paper]](http://openaccess.thecvf.com/content_CVPR_2019/papers/Zhang_Mind_Your_Neighbours_Image_Annotation_With_Metadata_Neighbourhood_Graph_Co-Attention_CVPR_2019_paper.pdf)<br>
  Junjie Zhang, Qi Wu, Jian Zhang, Chunhua Shen, Jianfeng Lu<br>
  IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2019
  - Looks like follow-up paper ['Love Thy Neighbors: Image Annotation by Exploiting Image Metatda' by Justin Johson, Lamberto Ballan, Li Fei-Fei](https://cs.stanford.edu/people/jcjohns/papers/iccv15/JohnsonICCV2015.pdf)

* Graph Convolutional Networks (GCN)
  - **Multi-Label Image Recognition with Graph Convolutional Networks** [[paper]](https://arxiv.org/pdf/1904.03582.pdf)<br>
  Zhao-Min Chen, Xiu-Shen Wei, Peng Wang, Yanwen Guo<br>
  IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2019

* Learning with Partial Labels + Graph Neural Network (GNN)
  - **Learning a Deep ConvNet for Multi-label Classification with Partial Labels** [[paper]](https://arxiv.org/pdf/1902.09720.pdf)<br>
  Thibaut Durand, Nazanin Mehrasa, Greg Mori<br>
  IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2019
  
* Visual Attention Consistency under Image Transforms
  - **Visual Attention Consistency under Image Transforms for Multi-label Image Classification** [[paper]](http://openaccess.thecvf.com/content_CVPR_2019/papers/Guo_Visual_Attention_Consistency_Under_Image_Transforms_for_Multi-Label_Image_Classification_CVPR_2019_paper.pdf)<br>
  Hao Guo, Kang Zheng, Xiaochuan Fan, Hongkai Yu, Song Wang<br>
  IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2019
  
* LaSO(Label-Set Operations networks) : few-shot learning (**oral paper**)
  - **LaSO: Label-Set Operations networks for multi-label few-shot learning** [[paper]](https://arxiv.org/pdf/1902.09811.pdf)<br>
  Amit Alfassy, Leonid Karlinsky, Ami Aides, Joseph Shtok, Sivan Harary, Rogerio Feris, Raja Giryes, Alex M. Bronstein<br>
  IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2019

## ICCV 2019 Accepted Paper List
[[accepted paper list]](http://iccv2019.thecvf.com/program/main_conference)

* Learning Semantic-Specific Graph Representation
  - **Learning Semantic-Specific Graph Representation for Multi-Label Image Recognition** [[paper]](http://openaccess.thecvf.com/content_ICCV_2019/papers/Chen_Learning_Semantic-Specific_Graph_Representation_for_Multi-Label_Image_Recognition_ICCV_2019_paper.pdf)<br>
  Tianshui Chen, Muxin Xu, Xiaolu Hui, Hefeng Wu, Liang Lin<br>
  In Proceedings of IEEE International Conference on Computer Vision (ICCV), 2019

## Notice
This repository is just made for my own studying, so there may be incorrect information.<br>
Also, I regard 'image tagging', 'image annotation', 'multi-label image classification' as same task (actually may be little bit different) in this repository.<br>

*I'd appreciate it if everybody could reccommend me image tagging paper that I can read.<br>*
현재는 이 쪽 분야의 paper를 read up 하고 있지는 않지만, ICCV 2019 paper까지는 올려보고자 합니다.<br>
Thank you!<br><br>

Email: kabbi159@gmail.com

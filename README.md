# DUT-USEG

> [**An Underwater Image Semantic Segmentation Method Focusing on Boundaries and a Real Underwater Scene Semantic Segmentation Dataset**](https://arxiv.org/abs/2108.11727)           
> [Zhiwei Ma](https://arxiv.org/search/cs?searchtype=author&query=Ma%2C+Z), [Haojie Li](https://arxiv.org/search/cs?searchtype=author&query=Li%2C+H), [Zhihui Wang](https://arxiv.org/search/cs?searchtype=author&query=Wang%2C+Z), [Dan Yu](https://arxiv.org/search/cs?searchtype=author&query=Yu%2C+D), [Tianyi Wang](https://arxiv.org/search/cs?searchtype=author&query=Wang%2C+T), [Yingshuang Gu](https://arxiv.org/search/cs?searchtype=author&query=Gu%2C+Y), [Xin Fan](https://arxiv.org/search/cs?searchtype=author&query=Fan%2C+X), [Zhongxuan Luo](https://arxiv.org/search/cs?searchtype=author&query=Luo%2C+Z)  
> ChinaMM 2021

Introduction
-----------------
With the development of underwater object grabbing technology, underwater object recognition and segmentation of high accuracy has become a challenge. The existing underwater object detection technology can only give the general position of an object, unable to give more detailed information such as the outline of the object, which seriously affects the grabbing efficiency. To address this problem, we label and establish the first underwater semantic segmentation dataset of real scene(DUT-USEG:DUT Underwater Segmentation Dataset). The DUT- USEG dataset includes 6617 images, 1487 of which have semantic segmentation and instance segmentation annotations, and the remaining 5130 images have object detection box annotations. Based on this dataset, we propose a semi-supervised underwater semantic segmentation network focusing on the boundaries(US-Net: Underwater Segmentation Network). By designing a pseudo label generator and a boundary detection subnetwork, this network realizes the fine learning of boundaries between underwater objects and background, and improves the segmentation effect of boundary areas. Experiments show that the proposed method improves by 6.7% in three categories of holothurian, echinus, starfish in DUT-USEG dataset, and achieves state-of-the-art results.

Dataset
---------------
DUT-USEG download link: [BaiduYun](https://pan.baidu.com/s/1reLIM-qEO6GNgBiDRQ5XDg) Key: i6sp
Citation
---------------
```
@misc{2108.11727,
Author = {Zhiwei Ma and Haojie Li and Zhihui Wang and Dan Yu and Tianyi Wang and Yingshuang Gu and Xin Fan and Zhongxuan Luo},
Title = {An Underwater Image Semantic Segmentation Method Focusing on Boundaries and a Real Underwater Scene Semantic Segmentation Dataset},
Year = {2021},
Eprint = {arXiv:2108.11727},
} 
```

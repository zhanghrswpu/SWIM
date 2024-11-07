# SWIM: SWIM: Sliding-Window Model Contrast for Federated Learning

> Heng-Ru Zhang, Rui Chen, Shi-Huai Wen, Xiao-Qiang Bian


## Abstract
In federated learning, data heterogeneity leads to significant differences in the local models learned by the clients, thereby affecting the performance of the global model. 
To address this issue, contrast federated learning algorithms increase the comparison of positive and negative samples on the clients, bringing the
local models closer to the global model. 
However, existing methods take the global model as the positive sample and the previous round of local models as the negative sample, resulting in insufficient utilization of historical local models. In this paper, we propose SWIM: Sliding-WIndow Model contrast method, which introduces more rounds of local models. 
First, we design and utilize a sliding window mechanism for collecting client representations of historical local models. Subsequently, we employ the cosine distance function as a discriminator to distinguish them into positive and negative samples. In addition, we introduce a dynamic coefficient that balances the federated classification learning and feature learning tasks. 
By adjusting the dynamic coefficient at different training rounds, the global model becomes more focused on feature learning in the early stages and classification learning in the later stages. 
Experiments are compared with four stateof-the-art federated learning algorithms on three datasets. The results show that the proposed algorithm outperforms the four state-of-the-art algorithms in terms of accuracy.
[[paper]](https://www.sciencedirect.com/science/article/pii/S0167739X24005545?dgcid=author). 

## Citation

Please cite our paper if you find this code useful for your research.

```

```

## Acknowledgement

I would like to express my sincere appreciation to the authors of the [GitHub - QinbinLi/MOON: Model-Contrastive Federated Learning (CVPR 2021)](https://github.com/QinbinLi/MOON)) for their substantial contributions. 

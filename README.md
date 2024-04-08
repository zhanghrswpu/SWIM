# SWIM: SWIM: Sliding-Window Model Contrast for Federated Learning

> Heng-Ru Zhang, Rui Chen, Shi-Huai Wen, Xiao-Qiang Bian


## Abstract
In federated learning, data heterogeneity results from the non-independent and non-identically distributed nature of data.
Contrast federated learning algorithms correct the local training of clients through the difference between model representations to alleviate data heterogeneity.
When updating the local model, they take the global model as a positive sample and the previous round of local models as a negative sample.
This strategy of selecting positive and negative samples is somewhat arbitrary, and the comparison of historical local models has not been fully utilized.
In this paper, we propose a SWIM: Sliding-Window Model Contrast method, which improves the effectiveness of federated contrastive learning by introducing more rounds of local models.
On the one hand, we design a sliding window mechanism for collecting client representations of historical local models.
Subsequently, we employ the cosine distance function as a discriminator to distinguish them into positive and negative samples.
On the other hand, we introduce a dynamic coefficient that balances the federal classification learning and feature learning tasks.
By adjusting the dynamic coefficient at different training rounds, the global model becomes more focused on feature learning in the early stages and classification learning in the later stages.
Experiments are compared with four state-of-the-art federated learning algorithms on three datasets.
Results show the proposed algorithm is superior in terms of four algorithms.
[[paper]](). 

## Citation

Please cite our paper if you find this code useful for your research.

```

```

## Acknowledgement

I would like to express my sincere appreciation to the authors of the [GitHub - QinbinLi/MOON: Model-Contrastive Federated Learning (CVPR 2021)](https://github.com/QinbinLi/MOON)) for their substantial contributions. 

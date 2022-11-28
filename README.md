# link-prediction-graphsage

The project uses pairwise learning for neural link prediction(PLNLP) framework for predicting drug-drug interactions(DDI) on OGB-ddi dataset.

## Key points
1. Encoder : Graph Neural Netwrom with graphSAGE layers.

2. Link prediction : Multi layer perceptron with single output

3. Loss function : Instead of minimizing cross entropy loss the framework minimizes auc loss.


## Loss Curve
<img src="img/loss-curve-ddi.png" width="500"/>


## Metric Curve
<img src="img/Hits@20-curve-ddi.png" width="500"/>

## References
1. [Wang, Zhitao, et al. "Pairwise Learning for Neural Link Prediction." arXiv preprint arXiv:2112.02936 (2021)](https://arxiv.org/pdf/2112.02936.pdf).
2. [Online link prediction](https://medium.com/stanford-cs224w/online-link-prediction-with-graph-neural-networks-46c1054f2aa4)
3. [Hamilton, Will, Zhitao Ying, and Jure Leskovec. "Inductive representation learning on large graphs." Advances in neural information processing systems 30 (2017).](https://proceedings.neurips.cc/paper/2017/hash/5dd9db5e033da9c6fb5ba83c7a7ebea9-Abstract.html)





# Graph Contrastive Anomaly Detection Based on Beta Wavelet Multi-GNNs




### Overview

<p align = "justify"> 
Graph anomaly detection (GAD) serves to distinct unusual patterns markedly differ from the norm. Recently, the integration of graph neural networks (GNNs) and contrastive learning for GAD has attracted significant attention. Graph contrastive anomaly detection (GCAD) techniques have primarily emphasized enhancing detection capabilities by integrating multiscale comparison modules. However, as the general backbone of GCAD methods, GNNs derive node representations by smoothing signals from neighboring nodes, which may lead to indistinguishable representations for anomalous nodes. Furthermore, detection outcomes often lack stability due to the inherent randomness of the GCAD pipeline. In our study, we tackle these challenges by proposing a novel approach BWMGNN-GCAD, termed Beta Wavelet Kernel GNN (BWGNN), coupled with a Multi-GNN module. BWGNN mitigates the low-pass issue inherent in traditional GNNs, while employing multiple GNNs enhances result stability. Experiments performed on three popular datasets demonstrate that our method outperforms current state-of-the-art techniques. Ablation studies further confirm that the BWMGNN-GCAD methodology, leveraging multiple GNN modules, significantly boosts detection efficacy. Our research underscores the potential efficacy of employing multiple neural networks and graph augmentation techniques in anomaly detection tasks.


### Requirements

The proposed BWMGNN-GCAD is implemented with python 3.7 on a NVIDIA 3090 GPU. 

- torch==1.10.2
- dgl==0.4.1
- numpy==1.19.2

### Quick Start

python run
run_loop.py

### Citation

If you find this project useful for your research, please cite your paper with the following BibTeX entry.

```
@inproceedings{BWMGNN-GCAD,
  title={Graph Contrastive Anomaly Detection Based on Beta Wavelet Multi-GNNs},
  author={Song, Yifan and Yang Yu and Liu Kangzheng and Zhao Feng},
  booktitle={Proc. of APWeb-WAIM},
  year={2025}
}
```
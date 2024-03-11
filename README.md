# OpenIMR
The PyTorch implementation of OpenIMR.

OpenIMR is proposed for open-world semi-supervised learning on graph data.

# Overview
You can enter the folder `run/` and then run run_ours.sh (run_ours_large.sh) for open-world semi-supervised learning on the Coauthor CS dataset (ogbn-arxiv dataset).

Specifically, the repository is organized as follows:

* `losses/` contains the implementation of supervised contrastive loss, which can be used for implementing the proposed PLCL loss.

* `networks/` contains the implementation of a GAT backbone.

* `networks_large/` contains the implementation of a GAT backbone for large graph datasets.
 
* `util.py` is used for loading and pre-processing the dataset, and also includes the functions for computing metrics.

* `train_ours.py` is used for implementing the pipeline of OpenIMR.

* `train_ours_large.py` is used for implementing the pipeline of OpenIMR for large graph datasets.
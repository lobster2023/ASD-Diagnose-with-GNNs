![MWU-test-GCN_1](https://github.com/lobster2023/ASD-Diagnose-with-GNNs/assets/133120607/f583da9d-31d0-40a7-97db-bd589f9d3eb6)# ASD-Diagnose-with-GNNs

This repository includes four GNN models of ASD Diagnose: GCN, GAT, ChebyNet and graphSAGE, two plotting codes and the MWU test code. The Python file ending with loss is the model that introduces the Wasserstein Graph Distance.

Both CPU and GPU environments are supported.

## Requirements

Recommended version:

* **Python**: python 3.7 
* **torch**: torch 1.12.0

## Explanation of Figures

In order to facilitate the reader's comprehension of the article, we have organized the key charts and placed them below for your convenience：
### Figure 1: The overall framework of the proposed model. It consists of three modules.
![model](https://github.com/lobster2023/ASD-Diagnose-with-GNNs/assets/133120607/fd9a7606-cdfd-4a8e-8705-5d3eff93902f)

### Figure 2: ROC curve for GCN, GAT, ChebyNet and graphSAGE.
![roc](https://github.com/lobster2023/ASD-Diagnose-with-GNNs/assets/133120607/64e3e045-aac1-4c79-8c84-4e81d8cb8525)

### Figure 3: Hyper-parameter 𝑎 search.
![para_new](https://github.com/lobster2023/ASD-Diagnose-with-GNNs/assets/133120607/1f77c961-7553-4d4d-a2fc-d6ddf27f6605)

### Figure 4: Mann-Whitney U test of 90 functional areas from the ASD group (orange) and the control group (blue).
![MWU-test-GCN_1](https://github.com/lobster2023/ASD-Diagnose-with-GNNs/assets/133120607/881d8b02-3f52-4bd4-a6b1-361edd79f00b)
![MWU-test-GCN_2](https://github.com/lobster2023/ASD-Diagnose-with-GNNs/assets/133120607/60d6c74d-6b13-4ee6-a04b-a2763d959c25)


### Figure 5: ASD related brain regions visualization. The left (right) panel shows the significant regions of the left (right) half of the brain from the lateral and dorsal views. And the middle panel displays the top 15 regions from the medial view.
![brainRegions](https://github.com/lobster2023/ASD-Diagnose-with-GNNs/assets/133120607/a767db45-88b7-40c0-bc43-e683d09293a9)











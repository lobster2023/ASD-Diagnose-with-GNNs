# ASD-Diagnose-with-GNNs

This repository includes four GNN models of ASD Diagnose: GCN, GAT, ChebyNet and graphSAGE, two plotting codes and the MWU test code. The Python file ending with loss is the model that introduces the Wasserstein Graph Distance.

Both CPU and GPU environments are supported.

## Requirements

Recommended version:

* **Python**: python 3.7 
* **torch**: torch 1.12.0

## Explanation of Figures

In order to facilitate the reader's comprehension of the article, we have organized the key charts and placed them below for your convenience：
### Figure 1: The overall framework of the proposed model. It consists of three modules.
![model-框架](https://github.com/lobster2023/ASD-Diagnose-with-GNNs/assets/133120607/d5a4ab48-09cd-4853-86af-54d3f914b32b)

### Figure 2: ROC curve for GCN, GAT, ChebyNet and graphSAGE (from top to bottom).
![GCN_roc](https://github.com/lobster2023/ASD-Diagnose-with-GNNs/assets/133120607/8d62223a-d812-4beb-a7a5-bf1f04116f11)
![image](https://github.com/lobster2023/ASD-Diagnose-with-GNNs/assets/133120607/39aa4e2a-e454-4e95-a0a3-07470f6ba030)
![ChebNet_roc](https://github.com/lobster2023/ASD-Diagnose-with-GNNs/assets/133120607/85e2373c-0787-458f-9e16-17f30858702e)
![GraphSAGE_roc](https://github.com/lobster2023/ASD-Diagnose-with-GNNs/assets/133120607/23f3925b-0bcf-48e9-8e96-edfab7bcb72f)

### Figure 3: Hyper-parameter 𝑎 search.
![parameter](https://github.com/lobster2023/ASD-Diagnose-with-GNNs/assets/133120607/51dae7a5-46f8-466d-b171-d2002ebe3d22)

### Figure 4: Mann-Whitney U test of 90 functional areas from the ASD group (orange) and the control group (blue). The second figure is for single functional area as an example. 
![MWU-test-all](https://github.com/lobster2023/ASD-Diagnose-with-GNNs/assets/133120607/ef105ad4-57b1-428b-b0a0-1660af8cd2ed)
![MWU-test-single](https://github.com/lobster2023/ASD-Diagnose-with-GNNs/assets/133120607/9b58906f-a0ed-4917-b264-7b86a18b4258)

### Figure 5: ASD related brain regions visualization. The left (right) panel shows the significant regions of the left (right) half of the brain from the lateral and dorsal views. And the middle panel displays the top 15 regions from the medial view.
![brainRegions](https://github.com/lobster2023/ASD-Diagnose-with-GNNs/assets/133120607/a767db45-88b7-40c0-bc43-e683d09293a9)











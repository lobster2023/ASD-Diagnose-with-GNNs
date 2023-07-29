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

### Figure 2: ROC curve for GCN, GAT, ChebyNet and graphSAGE.
![roc](https://github.com/lobster2023/ASD-Diagnose-with-GNNs/assets/133120607/64e3e045-aac1-4c79-8c84-4e81d8cb8525)

### Figure 3: Hyper-parameter 𝑎 search.
![para_new](https://github.com/lobster2023/ASD-Diagnose-with-GNNs/assets/133120607/1f77c961-7553-4d4d-a2fc-d6ddf27f6605)

### Figure 4: Mann-Whitney U test of 90 functional areas from the ASD group (orange) and the control group (blue).
![t-test_vector_all_GAT_1](https://github.com/lobster2023/ASD-Diagnose-with-GNNs/assets/133120607/2e364177-6ef7-46d6-bfa3-5763cd02d7dd)
![t-test_vector_all_GAT_2](https://github.com/lobster2023/ASD-Diagnose-with-GNNs/assets/133120607/d5b15c0b-3ef2-4c7f-8877-5ccb7181ae8d)
![t-test_vector_all_GAT_3](https://github.com/lobster2023/ASD-Diagnose-with-GNNs/assets/133120607/d1a3b711-c966-4d04-822a-934b0f8ccc57)
![t-test_vector_all_GAT_4](https://github.com/lobster2023/ASD-Diagnose-with-GNNs/assets/133120607/095bebf4-9697-41fb-82df-06d406749960)
![t-test_vector_all_GAT_5](https://github.com/lobster2023/ASD-Diagnose-with-GNNs/assets/133120607/205d7dbf-50b9-4d82-9615-f4dfc2dad5fb)

### Figure 5: ASD related brain regions visualization. The left (right) panel shows the significant regions of the left (right) half of the brain from the lateral and dorsal views. And the middle panel displays the top 15 regions from the medial view.
![brainRegions](https://github.com/lobster2023/ASD-Diagnose-with-GNNs/assets/133120607/a767db45-88b7-40c0-bc43-e683d09293a9)











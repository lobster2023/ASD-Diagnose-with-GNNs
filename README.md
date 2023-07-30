# ASD-Diagnose-with-GNNs

This repository includes four GNN models of ASD Diagnose: GCN, GAT, ChebyNet and graphSAGE, two plotting codes and the MWU test code. The Python file ending with "+loss" is the model that introduces the Wasserstein Graph Distance.

Both CPU and GPU environments are supported.

## Requirements

Recommended version:

* **Python**: python 3.7 
* **torch**: torch 1.12.0

## Explanation of Figures

Our key charts are placed below：
### Figure 1: The overall framework of the proposed model. It consists of three modules.
![model](https://github.com/lobster2023/ASD-Diagnose-with-GNNs/assets/133120607/fd9a7606-cdfd-4a8e-8705-5d3eff93902f)

### Figure 2: ROC curve for GCN, GAT, ChebyNet and graphSAGE.
![roc](https://github.com/lobster2023/ASD-Diagnose-with-GNNs/assets/133120607/64e3e045-aac1-4c79-8c84-4e81d8cb8525)

### Figure 3: Hyper-parameter 𝑎 search.
![para_new](https://github.com/lobster2023/ASD-Diagnose-with-GNNs/assets/133120607/1f77c961-7553-4d4d-a2fc-d6ddf27f6605)

### Figure 4: Mann-Whitney U test of 90 functional areas from the ASD group (orange) and the control group (blue).
![MWU-test-GCN_1](https://github.com/lobster2023/ASD-Diagnose-with-GNNs/assets/133120607/a822caee-c8a3-47b3-a54f-05bcbde9f019)
![MWU-test-GCN_2](https://github.com/lobster2023/ASD-Diagnose-with-GNNs/assets/133120607/09b92ee6-7a25-4e3b-bfb3-fdf0dfd1a925)
![MWU-test-GCN_3](https://github.com/lobster2023/ASD-Diagnose-with-GNNs/assets/133120607/91cf3b18-3b81-4af8-ad2b-2ce7d51fae5c)
![MWU-test-GCN_4](https://github.com/lobster2023/ASD-Diagnose-with-GNNs/assets/133120607/bf47b5a9-78c6-4bd2-8964-5c213df546a9)
![MWU-test-GCN_5](https://github.com/lobster2023/ASD-Diagnose-with-GNNs/assets/133120607/aada798a-7461-4301-adb6-f5abfa523d6e)

### Figure 5: ASD related brain regions visualization. The left (right) panel shows the significant regions of the left (right) half of the brain from the lateral and dorsal views. And the middle panel displays the top 15 regions from the medial view.
![brainRegions](https://github.com/lobster2023/ASD-Diagnose-with-GNNs/assets/133120607/a767db45-88b7-40c0-bc43-e683d09293a9)











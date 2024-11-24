# 
## Description

This is a fork of the RecZoo recommendation tasks repository.

Most main contributions were made in [the main ultragcn code](./matching/gnn/UltraGCN/main.py).

For the sake of fork etiquette, most of the unexplored original code was left untouched. Relevant code is nested under [UltraGCN](./matching/gnn/UltraGCN).

## Experimentation

See [the original documentation](./matching/gnn/UltraGCN/README.md) for execution instructions.
Final modifications were tested on the amazonbooks dataset. See [appropriate config file](./matching/gnn/UltraGCN/config/ultragcn_amazonbooks_m1.ini) for usage reference.

## Base Model

|                 Model                  | Publication                                                                                                                                                                                                                                       
|:--------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
|    [UltraGCN](https://github.com/reczoo/RecZoo/tree/main/matching/gnn/UltraGCN) | Kelong Mao, Jieming Zhu, Xi Xiao, Biao Lu, Zhaowei Wang, Xiuqiang He. [UltraGCN: Ultra Simplification of Graph Convolutional Networks for Recommendation](https://arxiv.org/pdf/2110.15114.pdf), in CIKM 2021.                                                              

# MGSF
Multi-Grained Selection and Fusion for Fine-Grained Image Representation.(IJCNN 2020)

# Introduction
How to learn a good fine-grained image representation is a key problem for fine-grained tasks. Most previous supervised methods suffer from insufficient training data, which require laborious annotations of fine-grained objects. In this paper, we propose an annotation-free method for fine-grained image representation, dubbed Multi-Grained Selection and Fusion (MGSF). The proposed MGSF extracts two types of visual features, i.e., fine-grained discriminative features that highlight informative convolutional parts by spatial selection and channel selection, and coarse-grained scene-level features that provide context information for fine-grained objects. Extensive experiments in fine-grained image retrieval demonstrate the superiority of our proposed representation compared with the state-of-the-art approaches on several fine-grained datasets.

# Datasets
CUB200 
Standford Dogs 
Oxford Flowers 
Oxford Pets 
FGVC-Aircrafts 
Standford Cars

# Results
|  | CUB200        | Standford Dogs | Oxford Flowers | Oxford Pets   | FGVC\-Aircrafts | Standford Cars |
|-----------|---------------|----------------|----------------|---------------|-----------------|----------------|
|  mAP \(%\)| top\-1 |top\-5 | top\-1| top\-5  | top\-1| top\-5  | top\-1| top\-5 | top\-1 |top\-5   | top\-1| top\-5  |
| MGSF      | 62\.34 |67\.79 | 75\.82| 80\.18  | 81\.38| 82\.89    | 88\.80 |90\.60   | 52\.69 |58\.31   | 39\.14| 46\.16  |


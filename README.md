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
|           | CUB200  |        | Standford Dogs |         | Oxford Flowers |        | Oxford Pets |        | FGVC\-Aircrafts |        | Standford Cars |        |
|-----------|---------|--------|----------------|---------|----------------|--------|-------------|--------|-----------------|--------|----------------|--------|
| mAP \(%\) | top\-1  | top\-5 | top\-1         | top\-5  | top\-1         | top\-5 | top\-1      | top\-5 | top\-1          | top\-5 | top\-1         | top\-5 |
| MGSF      | 62\.34  | 67\.79 | 75\.82         | 80\.18  | 81\.38         | 82\.89 | 88\.8       | 90\.6  | 52\.69          | 58\.31 | 39\.14         | 46\.16 |



<table>
    <tr>
        <td></td>
        <td colspan="2">CUB200</td>
        <td colspan="2">Standford Dogs</td>
        <td colspan="2">Oxford Flowers</td>
        <td colspan="2">Oxford Pets</td>
        <td colspan="2">FGVC-Aircrafts</td>
        <td colspan="2">Standford Cars</td>
    </tr>
    
    <tr>
        <td>mAP(%)</td>
        <td>top-1</td>
        <td>top-5</td>
        <td>top-1</td>
        <td>top-5</td>
        <td>top-1</td>
        <td>top-5</td>
        <td>top-1</td>
        <td>top-5</td>
        <td>top-1</td>
        <td>top-5</td>
        <td>top-1</td>
        <td>top-5</td>    
    </tr>
    
    <tr>
        <td>MGSF</td>
        <td>62.34</td>
        <td>67.79</td>
        <td>75.82</td>
        <td>80.18</td>
        <td>81.38</td>
        <td>82.89</td>
        <td>88.80</td>
        <td>90.60</td>
        <td>52.69</td>
        <td>58.31</td>
        <td>39.14</td>
        <td>46.16</td>
    </tr>
</table>

<table>
   <tr>
      <td></td>
        <td colspan="2">CUB200</td>
        <td colspan="2">Standford Dogs</td>
        <td colspan="2">Oxford Flowers</td>
        <td colspan="2">Oxford Pets</td>
        <td colspan="2">FGVC-Aircrafts</td>
        <td colspan="2">Standford Cars</td>
   </tr>
   <tr>
      <td>mAP (%)</td>
      <td>top-1</td>
      <td>top-5</td>
      <td>top-1</td>
      <td>top-5</td>
      <td>top-1</td>
      <td>top-5</td>
      <td>top-1</td>
      <td>top-5</td>
      <td>top-1</td>
      <td>top-5</td>
      <td>top-1</td>
      <td>top-5</td>
   </tr>
   <tr>
      <td>MGSF</td>
      <td>62.34 </td>
      <td>67.79</td>
      <td>75.82</td>
      <td>80.18 </td>
      <td>81.38 </td>
      <td>82.89</td>
      <td>88.8</td>
      <td>90.6</td>
      <td>52.69</td>
      <td>58.31</td>
      <td>39.14</td>
      <td>46.16</td>
   </tr>
   <tr>
      <td></td>
   </tr>
</table>


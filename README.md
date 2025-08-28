# Bicycle Risk Area Analysis Using Semantic Segmentation Models  
## A Comparative Study of Seoul Mapo-gu and Gyeonggi Bundang-gu

**Author**: Eunjin Lee  
**Date**: December 20, 2023  


## Overview
This project explores the use of **semantic segmentation models** to quantitatively analyze bicycle safety within urban environments. Road scene images are classified using a **Mask2Former** model pretrained on Cityscapes, and the results are combined with spatial analysis techniques to derive a **Bicycle Safety Score (BSS)**.  

The analysis focuses on two representative regions in South Korea: **Seoul Mapo-gu** and **Gyeonggi Bundang-gu**. By leveraging Google Street View imagery and road network data, the study identifies spatial patterns of bicycle safety and highlights the differences between the two areas.  


## Highlights
- **Data Collection**: Road coordinates extracted from V-World (Digital Twin Korea) at ~30m intervals; Google Street View API used to gather street-level imagery.  
- **Method**: Semantic segmentation via **Mask2Former** to detect key classes related to safety and risk.  
- **Results**:  
  - Mapo-gu achieved a higher average BSS (49.90) compared to Bundang-gu (1.00).  
  - Median BSS values were similar between the two areas (0.11 vs. 0.08).  
  - Normalized scores also indicated slightly safer conditions in Mapo-gu.  
- **Insight**: Contrary to expectations, Mapo-gu’s narrower streets showed higher bicycle safety scores than Bundang-gu’s wider, apartment-heavy layout.  


## Notes
- **Keywords**: Spatial Analysis, Semantic Segmentation, Bicycle Safety, Deep Learning, Risk Mapping  
- **Tools & Skills**: Python, PyTorch, Google Street View API, QGIS  

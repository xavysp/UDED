# UDED: Unified Dataset for Edge Detection

This dataset is a collection of 1, 2, or 3 images from:
BIPED, BSDS500, BSDS300, DIV2K, WIRE-FRAME, CID,
CITYSCAPES, ADE20K, MDBD, NYUD, THANGKA, PASCAL-Context,
SET14, URBAN10, and the camera-man image. The image 
selection process consists on computing the Inter-Quartile
Range (IQR) intensity value on all the images, images 
larger than 720×720 pixels were not considered. In dataset
whose images are in HR, they were cut. 
*We thank all the datasets owners to make them public.*
This dataset is just for Edge Detection
not contour nor Boundary tasks.

## How to evaluate UDED

...In construction but images are ready to download...

## Benchmarking

Please, check the Leaderboard [here](https://paperswithcode.com/sota/edge-detection-on-uded).

## Clarification
This repository has been released for research and academic
purpose. If the authors of the different datasets cited
above do not wish their images to be included in UDED,
we will remove them immediately.


## Citation

If you like UDED, why not starring the project on GitHub!

[![GitHub stars](https://img.shields.io/github/stars/xavysp/UDED.svg?style=social&label=Star&maxAge=3600)](https://GitHub.com/xavysp/UDED/stargazers/)

Please cite our Dataset if you find helpful in your academic/scientific publication,
```
@INPROCEEDINGS{soria2023teed,
  author={Soria, Xavier and Li, Yachuan and Rouhani, Mohammad and Sappa, Angel D.},
  booktitle={2023 IEEE/CVF International Conference on Computer Vision Workshops (ICCVW)}, 
  title={Tiny and Efficient Model for the Edge Detection Generalization}, 
  year={2023},
  volume={},
  number={},
  pages={1356-1365},
  doi={10.1109/ICCVW60793.2023.00147}}
```


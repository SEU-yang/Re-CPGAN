# Re-CPGAN


Code for Recursive Copy and Paste GAN: Face Hallucination from Shaded Thumbnails (TPAMI 2021). 

Link: https://ieeexplore.ieee.org/document/9361225

## Prerequisites:

Requirements: Python=3.6 and Pytorch>=1.0.0

### 

1. Install Pytorch

2. Prepare Dataset  (I am using Multi-PIE and CelebA as the training set.)

## Train: 

python train.py

Change the option in train.py to set the dataset's directory. 

## Test

python test.py

## Citation

If you find Re-CPGAN useful in your research, please consider citing:
```
@ARTICLE{9361225,
  author={Y. {Zhang} and I. {Tsang} and Y. {Luo} and C. {Hu} and X. {Lu} and X. {Yu}},
  journal={IEEE Transactions on Pattern Analysis and Machine Intelligence}, 
  title={Recursive Copy and Paste GAN: Face Hallucination from Shaded Thumbnails}, 
  year={2021},
  volume={},
  number={},
  pages={1-1},
  doi={10.1109/TPAMI.2021.3061312}}

```

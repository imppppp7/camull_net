# camull-net
An implementation of the Cambridge 3D convolutional network for the classification of Alzheimer's disease. This architecture is described in the following paper 
https://www.sciencedirect.com/science/article/abs/pii/S105381191930031X

Features
-3D seperable convolution
-Multiple concurrent data streams
  -MRI Data
  -Clinical Data
  
| Library      | Version     | Purpose     |
| :------------- | :----------: | -----------: |
|  Pytorch | 1.4.0   | Deep learning library for tensor transformations    |
| Numpy  | 1.18.1 | Datascience library for creating and manipulating arrays in python \| |
  
Requirements
- Deep learning library for tensor transformations
Numpy 1.18.1- Datascience library for creating and manipulating arrays in python
Pandas 0.25.3- Datascience library for examining and preprocessing medical data.
Nibabel 3.0.0- Library for loading in MRI scans into python
Tqdm 4.42.1- library for outputting progress to the console.

To read an explanation on this checkout this medium article. 
https://medium.com/@hextra_19712/deep-learning-for-alzheimers-classification-57611161e442?sk=ebc8035cead352f51f7d0e105a69a6c7

!(image)[https://i.gyazo.com/1b655be7b33cff82372088abdbf8eb4c.png]

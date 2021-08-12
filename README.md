# Within this repo are the 6 different colab notebooks used for Monument Monitor experimental AI work

## Models
[1s](https://github.com/Rosie-Brigham/colab-gists/blob/main/model_1s.ipynb) - First model made with tensorflow. Off the shelf model using semantic segmentation and ADE20k dataset
[2s](https://github.com/Rosie-Brigham/colab-gists/blob/main/model_2s.ipynb) - Second segmentation model - uses transfer learning
[3s](https://github.com/Rosie-Brigham/colab-gists/blob/main/model_3s.ipynb) - Third segmentation model - uses transfer learning with different configuration to model two 
[1c](https://github.com/Rosie-Brigham/colab-gists/blob/main/model_1c.ipynb) - First classification model for water levels, using Alexnet
[2c](https://github.com/Rosie-Brigham/colab-gists/blob/main/model_2c.ipynb) - Second (better) classification model for water levels using pre-trained GoogleNet
[3c](https://github.com/Rosie-Brigham/colab-gists/blob/main/model_3c.ipynb) - This classification model, that looks creates classifier for all MM case study sites using images submitted up until 1st Feb 2021.

|Model Number |	1s |	2s |	3s |	1c |	2c |	3c |
|------|--------|----|-----|-----|-----|-----|-----|
|Architecture	| DeepLabv3+	| ResNet101 |	ResNet101 |	AlexNet |	GoogLeNet |	ResNet18 |
|Analysis | type |	Segmentation | Segmentation | Segmentation	| Classification	| Classification | Classification|
|Focus|	Area of water pooling	|Area of water pooling	|Area of water pooling	|Level of water pooling	|Level of water pooling	|Identification of site|
|Validation and learning loss tracked	|False	|False	|True	|True |	True	|True|


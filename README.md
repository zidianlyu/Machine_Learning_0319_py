# Paint As Artist

## Painting Neural Style Machine Learning

### Compile
```Python
bash run.sh
```

### Setup
* VGG 19
  - for training purpose with pre-trained model
* Tensorflow 1.0.1
  - framework to train models

### Library & Package
- numpy
- scipy


### Original Paint
#### picture credit to Ming Li

- pattern

  <img src="https://github.com/zidianlyu/Paint_As_Artists/blob/master/examples/2-style2.jpg" align="center" width="700" >

- source input

  <img src="https://github.com/zidianlyu/Paint_As_Artists/blob/master/examples/3-content.jpg" align="center" width="700" >


- source output

  <img src="https://github.com/zidianlyu/Paint_As_Artists/blob/master/examples/3-style-0313.jpg" align="center" width="700" >

### Summary
- Extracted deep visual features from a pre-trained VGG ImageNet and trained models on Tensorflow framework
- Improved model performance by using dating transforms, algorithm tuning and ensemble methods

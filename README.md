# TextCNN

TextCNN 模型代码

实现基于：
[https://github.com/Shawn1993/cnn-text-classification-pytorch](https://github.com/Shawn1993/cnn-text-classification-pytorch)

# Requirements
pytorch==1.3.1
torchtext==0.4.0


# Train
`python main.py -train`

# Test
`python main.py -test -snapshot *.pt`

# Predict
`python main.py -predict -snapshot *.pt`
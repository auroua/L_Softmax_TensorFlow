# L_Softmax_TensorFlow
TensorFlow version of L_SoftMax.
### Results:
![results](imgs/Figure_1.png)

I found `prelu` is quite stable than `relu`, so I used `prelu` as paper said.
### Reference:
* [mx-lsoftmax](https://github.com/luoyetx/mx-lsoftmax)
* [Large-Margin Softmax Loss for Convolutional Neural Networks](https://arxiv.org/pdf/1612.02295.pdf)
### Contribution
This is mainly implemented by `py_func`, which is quite slow. If any have implemented a `tf op`, pull request is warmly welcome.
# face-recognition
Face recognition using Keras(tensorflow, python).

## Contents

### Utils

#### Image Augmentation

- [x] Random augmentation for landmark detection

#### Layers

- [x] DisturbLabel

#### Face Alignment

- [x] Insightface
- [x] GoldenRatio
- [x] Custom Implementations

#### TFRecords

- [ ] Widerface to TFRecords converter
- [ ] VggFace2 to TFRecords converter
- [ ] COFW to TFRecords converter

#### Loss Functions

##### Feature Extraction

- [x] ArcFace
- [x] CombinedMargin
- [x] SphereFace(A-Softmax)
- [ ] Center
- [x] CosFace

##### Landmark Detection

- [ ] EuclideanDistance(with different norms)

### Pretrained Models

#### Face Detection

- [ ] SSD
- [ ] MTCNN

#### Face Feature Extraction

- [x] MobileFaceNet
- [ ] SqueezeNet
- [x] MobileNet
- [ ] MobileNetV2
- [ ] DenseNet

#### Facial Landmark Detection

- [ ] SqueezeNet
- [ ] MobileNet
- [ ] MobileNetV2
- [ ] DenseNet

## References

|                              |                                                                                                                                                                                                                                            |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| WiderFace                    | Yang, Shuo, Ping Luo, Chen Change Loy, and Xiaoou Tang. “WIDER FACE: A Face Detection Benchmark.” ArXiv:1511.06523 [Cs], November 20, 2015. <https://arxiv.org/abs/1511.06523>                                                             |
| ArcFace                      | Deng, Jiankang, Jia Guo, Niannan Xue, and Stefanos Zafeiriou. “ArcFace: Additive Angular Margin Loss for Deep Face Recognition.” ArXiv:1801.07698 [Cs], January 23, 2018. <https://arxiv.org/abs/1801.07698>                               |
| MobileFaceNet                | Chen, Sheng, Yang Liu, Xiang Gao, and Zhen Han. “MobileFaceNets: Efficient CNNs for Accurate Real-Time Face Verification on Mobile Devices.” CoRR abs/1804.07573 (2018). <http://arxiv.org/abs/1804.07573>                                 |
| VggFace2                     | Cao, Qiong, Li Shen, Weidi Xie, Omkar M. Parkhi, and Andrew Zisserman. “VGGFace2: A Dataset for Recognising Faces across Pose and Age.” ArXiv:1710.08092 [Cs], October 23, 2017. <http://arxiv.org/abs/1710.08092>                         |
| DenseNet                     | G. Huang, Z. Liu, L. van der Maaten, and K. Q. Weinberger, “Densely Connected Convolutional Networks,” arXiv:1608.06993 [cs], Jan. 2018. <http://arxiv.org/abs/1608.06993>                                                                 |
| GoldenRatio (face alignment) | M. Hassaballah, K. Murakami, and S. Ido, “Face detection evaluation: a new approach based on the golden ratio,” SIViP, vol. 7, no. 2, pp. 307–316, Mar. 2013. <http://link.springer.com/10.1007/s11760-011-0239-3>                         |
| SqueezeNet                   | F. N. Iandola, S. Han, M. W. Moskewicz, K. Ashraf, W. J. Dally, and K. Keutzer, “SqueezeNet: AlexNet-level accuracy with 50x fewer parameters and <0.5MB model size,” arXiv:1602.07360 [cs], Feb. 2016.  <http://arxiv.org/abs/1602.07360> |
| MobileNet                    | A. G. Howard et al., “MobileNets: Efficient Convolutional Neural Networks for Mobile Vision Applications,” arXiv:1704.04861 [cs], Apr. 2017. <http://arxiv.org/abs/1704.04861>                                                             |
| MobileNetV2                  | M. Sandler, A. Howard, M. Zhu, A. Zhmoginov, and L.-C. Chen, “MobileNetV2: Inverted Residuals and Linear Bottlenecks,” arXiv:1801.04381 [cs], Jan. 2018. <http://arxiv.org/abs/1801.04381>                                                 |
| CosFace                      | H. Wang et al., “CosFace: Large Margin Cosine Loss for Deep Face Recognition,” arXiv:1801.09414 [cs], Jan. 2018. <http://arxiv.org/abs/1801.09414>                                                                                         |
| SphereFace                   | W. Liu, Y. Wen, Z. Yu, M. Li, B. Raj, and L. Song, “SphereFace: Deep Hypersphere Embedding for Face Recognition,” arXiv:1704.08063 [cs], Apr. 2017. <http://arxiv.org/abs/1704.08063>                                                      |
| Bottleneck (layer)           | K. He, X. Zhang, S. Ren, and J. Sun, “Deep Residual Learning for Image Recognition,” arXiv:1512.03385 [cs], Dec. 2015. <http://arxiv.org/abs/1512.03385>                                                                                   |
| MS-Celeb-1M                  | Y. Guo, L. Zhang, Y. Hu, X. He, and J. Gao, “MS-Celeb-1M: A Dataset and Benchmark for Large-Scale Face Recognition,” arXiv:1607.08221 [cs], Jul. 2016. <http://arxiv.org/abs/1607.08221>                                                   |

## Links

|                        |                                                               |
| ---------------------- | ------------------------------------------------------------- |
| Insightface            | <https://github.com/deepinsight/insightface>                  |
| Tensorflow             | <https://github.com/tensorflow/tensorflow>                    |
| Tensorflow-Addons      | <https://github.com/tensorflow/addons>                        |
| Insightface-DatasetZoo | <https://github.com/deepinsight/insightface/wiki/Dataset-Zoo> |

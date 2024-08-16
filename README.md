
# **Defect Analysis of 3D Printed Objects Using Transfer Learning Approaches**

# **基于迁移学习方法的3D打印对象缺陷分析**

## **Abstract / 摘要**

Additive manufacturing (AM) is rapidly gaining traction across diverse industries, including healthcare, aerospace, and automotive, due to its ability to enhance production efficiency. However, a critical challenge in AM is the early detection of defects, which can significantly reduce production costs and improve productivity. Addressing this need, our study explored the effectiveness of machine learning (ML) approaches, focusing on transfer learning (TL) models, for defect detection in 3D-printed objects. We utilized a range of TL models such as Visual Geometry Group (VGG)-16, Inception-Residual Network (InceptionResNet)-V2, Residual Network (ResNet)-50, Mobile Network (MobileNet)-V2, VGG19, ResNet101, Extreme Inception (Xception), Efficient Network (EfficientNet)-B0, EfficientNetB7, EfficientNetV2M (EfficientNetV2M), and Neural Architecture Search Network Large (NASNetLarge), analyzing images of 3D-printed objects across three datasets using various statistical measures.

增材制造（AM）由于其提升生产效率的能力，在医疗、航空航天和汽车等多个行业迅速获得了广泛应用。然而，AM 的一个关键挑战是缺陷的早期检测，这可以显著降低生产成本并提高生产力。为解决这一需求，我们的研究探讨了机器学习（ML）方法的有效性，重点关注迁移学习（TL）模型在 3D 打印对象缺陷检测中的应用。我们利用了一系列 TL 模型，如视觉几何组（VGG）-16、Inception-Residual 网络（InceptionResNet）-V2、残差网络（ResNet）-50、移动网络（MobileNet）-V2、VGG19、ResNet101、极限 Inception（Xception）、高效网络（EfficientNet）-B0、EfficientNetB7、EfficientNetV2M（EfficientNetV2M）和神经架构搜索网络 Large（NASNetLarge），通过各种统计测量对三个数据集的 3D 打印对象图像进行了分析。

An ablation study was also conducted using Adaptive Moment Estimation (Adam), Stochastic Gradient Descent (SGD), and Root Mean Square Propagation (RMSprop) optimizers. We identified that TL models such as VGG16, MobileNetV2, InceptionResNetV2, and NASNetLarge significantly outperform others, especially when optimized with Adam and RMSprop. Conversely, models like EfficientNetB0, EfficientNetB7, and EfficientNetV2M exhibited lower performance when paired with the SGD optimizer. Additionally, Local Interpretable Model-agnostic Explanations (LIME)-based approaches were used to provide explanations of the models' predictions. These findings offer substantial insights into model optimization and integration, aiming to enhance AM product quality through advanced image-based monitoring and inspection.

我们还进行了消融研究，使用了自适应矩估计（Adam）、随机梯度下降（SGD）和均方根传播（RMSprop）优化器。我们发现，像 VGG16、MobileNetV2、InceptionResNetV2 和 NASNetLarge 等 TL 模型显著优于其他模型，特别是在使用 Adam 和 RMSprop 优化器时表现更佳。相反，EfficientNetB0、EfficientNetB7 和 EfficientNetV2M 等模型在与 SGD 优化器配对时表现较差。此外，我们还使用了基于局部可解释模型无关解释（LIME）的方法来解释模型的预测。这些发现为模型优化和集成提供了重要的见解，旨在通过先进的基于图像的监控和检查来提高 AM 产品的质量。

<p align="center">
  <img src="https://github.com/mahsan2/AM3d/blob/main/figure/Proposedmethods3.PNG" alt="Flow diagram of the proposed transfer learning-based approaches with frozen pre-trained weights and updated layers for defect analysis">
  <br><strong>Flow diagram of the proposed transfer learning-based approaches with frozen pre-trained weights and updated layers for defect analysis / 提出的迁移学习方法的流程图，展示了冻结的预训练权重和更新的层用于缺陷分析</strong>
</p>

## **Citation / 引用**

If you use this dataset, please cite the following paper:

```bibtex
@article{ahsan2024defect,
  title={Defect analysis of 3D printed object using transfer learning approaches},
  author={Ahsan, Md Manjurul and Raman, Shivakumar and Liu, Yingtao and Siddique, Zahed},
  journal={Expert Systems with Applications},
  volume={253},
  pages={124293},
  year={2024},
  publisher={Elsevier}
}
```

**Paper link:** [https://doi.org/10.1016/j.eswa.2024.124293](https://doi.org/10.1016/j.eswa.2024.124293)

**Dataset link:** https://github.com/mahsan2/AMdataset

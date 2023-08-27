# cib_yzsbjc
## 参考网址
1. 印章检测+印章文字检测+印章文字识别 https://gitee.com/paddlepaddle/PaddleOCR/blob/release/2.6/applications/
2. 印章文字检测与识别综述https://zhuanlan.zhihu.com/p/526481349
3. 印章检测+识别 github开源代码https://github.com/NephrenCake/SealOcr/tree/master
4. 印章检测实战：https://zhuanlan.zhihu.com/p/605752446
5. 有非常多参考资料的项目（数据集、算法）：https://github.com/PaddlePaddle/PaddleOCR/tree/release/2.6
6. 印章检测数据集(只有圆章，数量很大)：https://aistudio.baidu.com/datasetdetail/154271
7. 印章检测数据集(有圆章和方章，共三百张)：https://aistudio.baidu.com/datasetdetail/177475



## 实现思路
数据集：真实样本做测试集，训练数据自己构造（印章+文档随机匹配生成）
真实样本（检测）：https://aistudio.baidu.com/datasetdetail/177475
印章生成：https://gitee.com/Jackie_zzq/SealUtil
印章检测（目标检测）+印章文字识别（Img2Seq）

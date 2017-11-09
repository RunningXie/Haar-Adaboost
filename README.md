**基于Haar特征值的Adaboost人脸识别**
可以直接使用：python faceDetection.py someImage.pgm --show=True --save=False -- saveInfo=False运行

### 文件描述:
* weakClassifier.py : 弱分类器
* faceDetection.py  : 主函数，其中calAndSaveFeatures()是用于计算弱分类器的
* haar.py           : 计算Haar特征
* image.py          : 加载图片，计算积分图
* setting.py        : 配置文件
* detector.py       : 生成扫描窗口
* feature.py        : 存储，加载训练图片的特征值文件
* model.py          : 存储，加载计算软分类器的结果
* adaboost.py       : 强分类器
* haar.py           : 计算几种Harr特征值
* image.py          : 加载，显示图片

---

#  上海垃圾分类识别 #



## 应用程序简介
   本应用程序是一个垃圾分类自动识别的Android应用程序，可以运行于Android7及之后的Android手机上。本项目是上海永昌私立学校余乐洋同学申报的2019年上海青少年科技创新网[www.shssp.org](http://www.shssp.org) 第一批通过项目，得到了上海青少年科学社和永昌私立学校的大力支持和帮助。该项目主要依据上海市绿化和市容管理局的生活垃圾分类标准，运用人工智能深度学习技术，通过拍照和图片自动识别垃圾类别，指导人们准确地进行垃圾分类，养成精准垃圾分类的行为习惯，促进生活垃圾分类绿色工程的有效实施。
 
## 技术简介
  本应用程序主要是使用Google Tensorflow lite量化模型[Inception_V3_quant](https://storage.googleapis.com/download.tensorflow.org/models/tflite_11_05_08/inception_v3_quant.tgz)，利用迁移学习，对于上海市绿化和市容管理局规定的常用生活垃圾进行高效自动识别，方便人们的使用。


## 使用界面

1. 主界面
<div align=center><img width="360" height="540" src="https://github.com/rovinyu/Garbageclassifier_release/blob/master/png/main.png"/></div>

2. 可回收物列表
<div align=center><img width="360" height="540" src="https://github.com/rovinyu/Garbageclassifier_release/blob/master/png/recyclable.png"/></div>

3. 干垃圾列表
<div align=center><img width="360" height="540" src="https://github.com/rovinyu/Garbageclassifier_release/blob/master/png/residual.png"/></div>

4. 湿垃圾列表
<div align=center><img width="360" height="540" src="https://github.com/rovinyu/Garbageclassifier_release/blob/master/png/household.png"/></div>

5. 有害垃圾列表
<div align=center><img width="360" height="540" src="https://github.com/rovinyu/Garbageclassifier_release/blob/master/png/hazardous.png"/></div>

6. 输入识别结果示例
<div align=center><img width="360" height="540" src="https://github.com/rovinyu/Garbageclassifier_release/blob/master/png/input_identifying.png"/></div>

7. 拍照识别结果示例
<div align=center><img width="360" height="540" src="https://github.com/rovinyu/Garbageclassifier_release/blob/master/png/capture_identifying.png"/></div>

8. 图片识别结果实例
<div align=center><img width="360" height="540" src="https://github.com/rovinyu/Garbageclassifier_release/blob/master/png/photo_identifying.png"/></div>

## 致谢
  感谢复旦大学田红军老师的指点和帮助，感谢上海青少年科学社和永昌私立学习的大力支持。
  另外，您在使用过程中遇到任何问题或者有好的建议，随时与我们联系：[ytg@sina.com]

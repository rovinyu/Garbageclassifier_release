#  上海垃圾分类识别 #



## 应用程序简介
   本应用程序是一个垃圾分类自动识别的Android应用程序，可以运行于Android7及之后的Android手机上。本项目是上海永昌私立学校余乐洋同学申报的2019年上海青少年科技创新网 （ www.shssp.org ）第一批通过项目，得到了上海青少年科学社和永昌私立学校的大力支持和帮助。该项目主要依据上海市绿化和市容管理局的生活垃圾分类标准，运用人工智能深度学习技术，通过拍照和图片自动识别垃圾类别，指导人们准确地进行垃圾分类，养成精准垃圾分类的行为习惯，促进生活垃圾分类绿色工程的有效实施。
 
## 技术简介
  本应用程序主要是使用Google Tensorflow lite量化模型Inception_V3_quant，利用迁移学习，对于上海市绿化和市容管理局规定的常用生活垃圾进行高效自动识别，方便人们的使用。


## 使用界面

1. 如果不是对APK size有极致的需求，请不要把`resources.arsc`添加进`compressFilePattern`. ([#84](https://github.com/shwenzhang/AndResGuard/issues/84) [#233](https://github.com/shwenzhang/AndResGuard/issues/233))
2. 对于发布于Google Play的APP，建议不要使用7Zip压缩，因为这个会导致Google Play的优化Patch算法失效. ([#233](https://github.com/shwenzhang/AndResGuard/issues/233))


## 致谢
  感谢复旦大学田红军老师的指点和帮助，感谢上海青少年科学社和永昌私立学习的大力支持。

# hand-detection-2class-MobilenetV1-SSD
MobilenetV1-SSDで訓練した手検出(Open/Close)のモデル(TensorflowLite、Tensorflowjs、CoreML)です。

以下の2種類（開いた手(Open)、閉じた手(Close)）の検出を行います。

![2020-04-08 (11)](https://user-images.githubusercontent.com/37477845/78701044-4a068d80-7941-11ea-89a7-492272546afc.png)

![2020-04-08 (12)](https://user-images.githubusercontent.com/37477845/78701047-4bd05100-7941-11ea-96dc-3aabaa955926.png)

# Requirement
 
* Tensorflow 1.4.0
* Tensorflowjs 1.4.0

※バージョンが少々古いため注意

# Note
本モデルは[IBM Cloud Annotations](https://cloud.annotations.ai/)を利用して作成しています。

また、Tensorflowjs版のモデルは、以下のGithub Pagesから動作確認することが出来ます。※PCでの閲覧を推奨

https://kazuhito00.github.io/hand-detection-2class-MobilenetV1-SSD/

# Contents
本リポジトリには以下のモデルが含まれます。

* model

　　TensorflowのFrozenモデル
 
　　※訓練時のTensorflowのバージョンが低いため、バージョンが合わないと動作しない可能性があります)
* model_android

　　Tensorflow Liteのモデル
 
　　以下のリポジトリのソースコードで動作確認が可能です。
 
　　　Python：https://github.com/cloud-annotations/object-detection-python
  
　　　Android：https://github.com/cloud-annotations/object-detection-android
* model_ios

　　Tensorflow CoreMLモデル
 
　　以下のリポジトリのソースコードで動作確認が可能です。

　　　iOS：https://github.com/cloud-annotations/object-detection-ios
* model_web

　　Tensorflowjsのモデル
 
　　以下のリポジトリのソースコードで動作確認が可能です。

　　　REACT：https://github.com/cloud-annotations/object-detection-react

# Author
高橋かずひと(https://twitter.com/KzhtTkhs)
 
# License 
hand-detection-2class-MobilenetV1-SSD is under [MIT license](https://en.wikipedia.org/wiki/MIT_License).

# Cloud Annotations(object-detection-react) License 
Copyright (c) 2019 Nick Bourdakos

object-detection-react is under [MIT license](https://en.wikipedia.org/wiki/MIT_License).


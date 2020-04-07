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

# Contents
本リポジトリには以下のモデルが含まれます。

* model
　TensorflowのFrozenモデル
　※訓練時のTensorflowのバージョンが低いため、バージョンが合わないと動作しない可能性があります)
* model_android
　Tensorflow Liteのモデル
* model_ios	Initial
　Tensorflow CoreMLモデル
* model_web
　Tensorflowjsのモデル

https://kazuhito00.github.io/hand-detection-2class-MobilenetV1-SSD/


# Author
高橋かずひと(https://twitter.com/KzhtTkhs)
 
# License 
object-detection-bbox-art is under [MIT license](https://en.wikipedia.org/wiki/MIT_License).

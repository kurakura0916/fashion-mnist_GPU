# fashion-mnist_GPU

## 概要
Google Colaboratoryを用いて、fashion mnistデータセットをGPUで学習（CNN）を実行してみる。


## 結果
LeNetのアーキテクチャーを用いて、epoch5,000、バッチサイズ100で学習を行った。
学習終了までの経過時間を計測。

CPUの場合：2025.22 [s]
GPUの場合：540.269 [s]

## データセット
fashoin mnist

- 訓練データ：(60000, 1, 28, 28)
- テストデータ：(10000, 1, 28, 28)

## フレームワーク
chainer 4.2.0

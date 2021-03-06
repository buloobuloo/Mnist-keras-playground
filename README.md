Keras-MNist實作
====
## Keras-MNist introduce
1.介紹Mnist資料形式<br>
2.轉成one-not code形式
## Keras-MNist MLP256/MLP1000
訓練節點分為256與1000<br>
<img src="https://github.com/buloobuloo/Mnist-keras-playground/blob/master/IMG/%E6%88%AA%E5%9C%96%202020-05-15%20%E4%B8%8B%E5%8D%882.31.25.png" width="400"><img src="https://github.com/buloobuloo/Mnist-keras-playground/blob/master/IMG/%E6%88%AA%E5%9C%96%202020-05-15%20%E4%B8%8B%E5%8D%883.13.03.png" width="400"><br>
訓練圖表：<br>
256節點<br>
<img src="https://github.com/buloobuloo/Mnist-keras-playground/blob/master/IMG/mlp256.png">
<img src="https://github.com/buloobuloo/Mnist-keras-playground/blob/master/IMG/mlp256t.png"><br>
1000節點<br>
<img src="https://github.com/buloobuloo/Mnist-keras-playground/blob/master/IMG/%E6%88%AA%E5%9C%96%202020-05-15%20%E4%B8%8B%E5%8D%883.13.15.png"><img src="https://github.com/buloobuloo/Mnist-keras-playground/blob/master/IMG/%E6%88%AA%E5%9C%96%202020-05-15%20%E4%B8%8B%E5%8D%883.13.20.png"><br>
256節點準確度：0.980400025844574 1000節點準確度：0.9796<br>
## 加入dropout Keras-MNist Dropout
加入Dropout:<br>
<img src="https://github.com/buloobuloo/Mnist-keras-playground/blob/master/IMG/%E6%88%AA%E5%9C%96%202020-05-15%20%E4%B8%8B%E5%8D%883.22.34.png"><br>
訓練圖表：<br>
<img src="https://github.com/buloobuloo/Mnist-keras-playground/blob/master/IMG/%E6%88%AA%E5%9C%96%202020-05-15%20%E4%B8%8B%E5%8D%883.22.42.png"><img src="https://github.com/buloobuloo/Mnist-keras-playground/blob/master/IMG/%E6%88%AA%E5%9C%96%202020-05-15%20%E4%B8%8B%E5%8D%883.22.46.png"><br>
精確度：0.9802<br>
## Keras-MNist CNN
利用CNN做訓練：<br>
<img src="https://github.com/buloobuloo/Mnist-keras-playground/blob/master/IMG/%E6%88%AA%E5%9C%96%202020-05-15%20%E4%B8%8B%E5%8D%883.23.06.png"><br>
訓練圖表：<br>
<img src="https://github.com/buloobuloo/Mnist-keras-playground/blob/master/IMG/%E6%88%AA%E5%9C%96%202020-05-15%20%E4%B8%8B%E5%8D%883.23.16.png"><img src="https://github.com/buloobuloo/Mnist-keras-playground/blob/master/IMG/%E6%88%AA%E5%9C%96%202020-05-15%20%E4%B8%8B%E5%8D%883.23.21.png"><br>
精確度：0.99350000000000005<br>
預測結果：<br>
<img src="https://github.com/buloobuloo/Mnist-keras-playground/blob/master/IMG/%E6%88%AA%E5%9C%96%202020-05-15%20%E4%B8%8B%E5%8D%882.32.00.png">

# Deep Learning Study Group

# 目的:
使用Pytorch, Tensorflow進行Deep Learning的實務學習
# 方法:
實務cases實作, 每週實體聚會討論交流, 隨時線上討論.
# 時程:
+ [X] Pytorch 入門: [Tensor 操作][16], torch optim...等 **2019/4/14**
  + [X] [PyTorch的backward()相关理解(舊版pytorch，參考)][17]
  + [X] [PyTorch基礎篇-張量、模型自動更新、優化器(舊版PyTorch，參考)][18]
  + [X] [2019-0420 Slide: PyTorch - Get Started][21]@忠孝伯朗咖啡 
+ [X] Pytorch 101: Cases實作: 
  + [X] [世界人口預測 (Linear Regression)][6] **2019/5/5**
  + [X] [Stock Price (Logistic Regression)][7] **2019/5/5**
  + [X] [MNIST (Logistic Regression)][12] **2019/5/5**
  + [X] [2019-0505 Slide: PyTorch 101][23]@小樹屋-民權西路
+ [X] Pytorch 102: Cases實作: 
  + [X] [NLP: RNN (LSTM) 寫古詩][24] **2019/5/25**
  + [X] [2019-0525 Slide: PyTorch 102][25]@小樹屋-民權西路
+ [ ] Pytorch 103: Cases實作: 
  + [ ] [Time Series: RNN GDP 預測][28] **2019/6/22**
  + [ ] [Reading: Seq2seq pay Attention to Self Attention: Part 1(中文版)][29] **2019/6/22**
  + [ ] [Reading: Seq2seq pay Attention to Self Attention: Part 2(中文版)][30] **2019/6/22**
+ [ ] Paper Study: 
  + [ ] [Perceive Your Users in Depth: Learning Universal User Representations from Multiple E-commerce Tasks][27] **2019/6/22**  
+ [ ] Tensorflow Cases實作: 
  + [ ] [Common knowledge][3] **2019/6/15**
  + [ ] [Case: 玩轉IRIS資料集, 零基礎範例][5] **2019/6/15**
  + [ ] [Case: Titanic survivor (Logistic Regression)][13] **2019/6/15**
  + [ ] [Case: Credit Card Analysis (Logistic Regression to DNN)][15] **2019/6/15**
  + [ ] [Case: MNIST (RNN)][2] **2019/6/29**
  + [ ] [Case: Fashion MNIST (DNN, GRU, Dataset API)][1] **2019/6/29**
  + [ ] [Case: Fashion MNIST (Tensorflow 2.0 API)][9] **2019/6/29**
+ [ ] Milestones目標 (關鍵成果):
  + [ ] [PyTorch: Seq2Seq 實作數學加法運算 (with or without Attention)][20] **2019/6/8**
  + [ ] [PyTorch: Attention is all you need (Transformer)][4] **2019/6/22**
  + [ ] [Tensorflow: Attention is all you need (Transformer)][8] **2019/7/13**
  + [ ] [Neural Ordinary Differential Equations][14] **2019/?/?**
    + [ ] [Ref: Neural ODE & DiffEqFlux - 杜岳華 (without QA)][22]
  + [ ] 大型資料黑客松競賽 **2019/11/1**
    + [ ] Search for global hackathon: https://www.hackathon.com/
      + [ ] possible event1: https://www.hackathon.com/event/take-europe-to-the-hearts-hackathon-39909500390
      + [ ] possible event2: https://www.eventbrite.com/e/zero-waste-retail-hackathon-tickets-58778354641
      + [ ] possible event3: https://techandrelationships.org/
  

## Reference Material
+ [Tensorflow 中文教學][10]
+ [Pytorch LSTM, GRU][19]
+ [Seq2Seq with Attention 的 PyTorch 範例][32]
+ [Transformer 入門中文文章][11]
+ [NLP 新手必看！这是一份覆盖全面的基于 PyTorch 和 keras 的 NLP 学习教程][26]
+ [Deeplearning-models 大全: 含大量 Tensorflow, PyTorch 範例][31]


[1]:https://colab.research.google.com/drive/1Nn_9cdSK9yH4nWJx-vdKat8NWnmjopu0
[2]:https://colab.research.google.com/drive/18FqI18psdH30WUJ1uPd6zVgK2AwxO_Bj
[3]:https://medium.com/the-artificial-impostor/notes-understanding-tensorflow-part-1-5f0ebb253ad4
[4]:https://github.com/jadore801120/attention-is-all-you-need-pytorch
[5]:https://www.jianshu.com/p/b86c020747f9
[6]:https://github.com/ZhiqingXiao/pytorch-book/blob/master/chapter05_linear/population.ipynb
[7]:https://github.com/ZhiqingXiao/pytorch-book/blob/master/chapter06_logistic/stock_volume.ipynb
[8]:https://github.com/princewen/tensorflow_practice/tree/master/basic/Basic-Transformer-Demo
[9]:https://www.jianshu.com/p/c7a280600da8
[10]:https://github.com/Hvass-Labs/TensorFlow-Tutorials-Chinese
[11]:https://voidism.github.io/note/2019/02/05/Transformer_Intro/
[12]:https://medium.com/jovian-io/image-classification-using-logistic-regression-in-pytorch-ebb96cc9eb79
[13]:https://codability.in/a-guide-tensorflow-logistic-regression-part-6/
[14]:https://rkevingibson.github.io/blog/neural-networks-as-ordinary-differential-equations/
[15]:https://ipythonquant.wordpress.com/2018/06/20/from-logistic-regression-in-scikit-learn-to-deep-learning-with-tensorflow-a-fraud-detection-case-study-part-iii/
[16]:https://medium.com/jovian-io/pytorch-basics-tensors-and-gradients-eb2f6e8a6eee
[17]:https://blog.csdn.net/douhaoexia/article/details/78821428
[18]:https://fgc.stpi.narl.org.tw/activity/videoDetail/4b1141305d9cd231015d9d0992ef0030
[19]:https://zhuanlan.zhihu.com/p/39191116
[20]:http://zake7749.github.io/2017/09/28/Sequence-to-Sequence-tutorial/
[21]:https://docs.google.com/presentation/d/e/2PACX-1vSVi_bYmbEMRDYON1sJJZfcG2KidmPjh-X7zeoNn7s6eidzgdJgOJevW3xxE2dhO1i6qN-OBM8tnHpq/pub?start=false&loop=false&delayms=3000
[22]:https://www.youtube.com/watch?v=hAA_AfVB89M&app=desktop
[23]:https://docs.google.com/presentation/d/e/2PACX-1vRjpbhBYS6YsE_d03gDK65cWTKFsyko_2XaOCKMYWbPnjZo8eieCExmwycm7sNCuNNb0aiofW96819z/pub?start=false&loop=false&delayms=3000
[24]:https://github.com/chenyuntc/pytorch-book/tree/master/chapter9-%E7%A5%9E%E7%BB%8F%E7%BD%91%E7%BB%9C%E5%86%99%E8%AF%97(CharRNN)
[25]:https://docs.google.com/presentation/d/e/2PACX-1vRDk0aKx6IzVRYPWpwejwoucfgBsltQ_DSF1qftvzeKUGRdmsBz6MQOdLymbP_nwdYJALhG--LvFb3o/pub?start=false&loop=false&delayms=3000
[26]:https://www.leiphone.com/news/201903/lMKp1UxI4aOprIlv.html?fbclid=IwAR3zvIi_LX5KEJR0_wi9rQdH7rI60qojvZL5Qdjd_diymQU9DzatjgsMhkk
[27]:http://delivery.acm.org/10.1145/3220000/3219828/p596-ni.pdf?ip=114.36.19.203&id=3219828&acc=OPENTOC&key=4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E054E54E275136550&__acm__=1559229270_eebb4e18d2fc52764722da7a634be401
[28]:https://github.com/ZhiqingXiao/pytorch-book/tree/master/chapter09_RNN
[29]:https://medium.com/@bgg/seq2seq-pay-attention-to-self-attention-part-1-中文版-2714bbd92727
[30]:https://medium.com/@bgg/seq2seq-pay-attention-to-self-attention-part-2-中文版-ef2ddf8597a4
[31]:https://github.com/rasbt/deeplearning-models
[32]:https://github.com/bentrevett/pytorch-seq2seq/blob/master/3%20-%20Neural%20Machine%20Translation%20by%20Jointly%20Learning%20to%20Align%20and%20Translate.ipynb

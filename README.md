# paddlepaddleDemos
做了一个基于paddlepaddle的小例子

dataset:corpus.txt。中文的语料，共10种类别：'文化', '娱乐', '体育', '财经','房产', '汽车', '教育', '科技', '国际', '证券'。
运行的时候注意编码格式。
train_model.py #训练模型
infer.py #用训练好的模型进行预测。根据输入的每句中文语料，预测它所属的类别。
preprocess.py #文件的预处理，用来生成字典、训练集、测试集，创建train_reader、test_reader。

=======================未完待续=====================

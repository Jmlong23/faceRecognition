
# 实验环境


# 测试模型
测试命令：

# 训练模型转pb文件
命令： python freeze_graph.py D:/face/models/faceV5 D:/face/models/faceV5/graph.pb

# 计算两张图片之间的距离
命令：python compare.py D:\\face\\models\\faceV5\\graph.pb D:\\face\\dataset\\lfw_test\\Abel_Pacheco\\1.png D:\\face\\dataset\\lfw_test\\Abid_Hamid_Mahmud_Al-Tikriti\\1.png

# 安装最新版的flask
pip install -U https://github.com/pallets/flask/archive/master.tar.gz

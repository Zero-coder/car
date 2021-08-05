# 车辆检测+计数+车牌检测与车牌识别
一个小时内不能上传超过20个文件，慢慢更新中...

#### 介绍
基于pytorch深度学习框架，实用开源模型yolov4实现模板检测与yolov5实现车牌检测与LPRNet实现车牌检测

基于win10系统，实用anaconda配置python环境，在anaconda里面下载vscode对项目进行编辑，




#### 软件架构
![软件架构](https://images.gitee.com/uploads/images/2021/0726/124949_31173f9c_5230895.png "屏幕截图.png")
#### 安装教程
[保姆级环境配置：](https://blog.csdn.net/weixin_44791964/article/details/106037141)
#### [简洁版环境配置：]


- last.pt 权重文件太大，不能直接上传到码云，通过百度云方式分享，下载后，放入weights文件夹。
- 链接：
- 链接：https://pan.baidu.com/s/1OmMVqckyMDosopfwv52zTQ 
- 提取码：je0x
- 有码友发来这样的消息：
- ![输入图片说明](https://images.gitee.com/uploads/images/2021/0805/114018_8dfbbbd1_5230895.png "屏幕截图.png")
- 所以上传到百度云：
链接：https://pan.baidu.com/s/1sG9VdVt_HR-mi53UcII3ZA 
提取码：n7uc

编辑器我选择的是vscode，用anaconda创建虚拟python环境可以很好的分离项目，独立起来，方便。

- pytorch安装：
- 官网推荐的安装代码如下，我使用的是Cuda10的版本：


```
-  CUDA 10.0
- pip install torch===1.2.0 torchvision===0.4.0 -f https://download.pytorch.org/whl/torch_stable.html

-  CUDA 9.2
- pip install torch==1.2.0+cu92 torchvision==0.4.0+cu92 -f https://download.pytorch.org/whl/torch_stable.html

-  CPU only
- pip install torch==1.2.0+cpu torchvision==0.4.0+cpu -f https://download.pytorch.org/whl/torch_stable.html
```

- 给出网盘链接：
- 链接：https://pan.baidu.com/s/1YwcoaSRmNaeWZfHWkZ8lJg 
- 提取码：9i28
- 这样下载的速度比较慢，可以通过下载whl文件在本地进行安装。

下载完成后找到安装路径：
![输入图片说明](https://images.gitee.com/uploads/images/2021/0726/163505_a23ec979_5230895.png "屏幕截图.png")
在cmd定位过来后利用文件全名进行安装即可
![输入图片说明](https://images.gitee.com/uploads/images/2021/0726/163530_2a02cebb_5230895.png "屏幕截图.png")

安装有问题可以跳转到保姆级教程：[保姆级环境配置：](https://blog.csdn.net/weixin_44791964/article/details/106037141)
 


#### 使用说明

1.  运行detect.py：实现对 /inference/images 路径下的图片和视频进行目标检测，卡车计数，和车牌检测与识别
2.  在/inference/output 路径下可看到输出情况
![实操情况](https://images.gitee.com/uploads/images/2021/0726/125452_912b655b_5230895.png "屏幕截图.png")
#### 结果展示
![输入图片说明](https://images.gitee.com/uploads/images/2021/0726/125806_282bc84b_5230895.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0726/125821_d3b76e7b_5230895.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0726/125852_8f9547b9_5230895.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0726/125900_c0c3d530_5230895.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0726/125922_5f8e31d1_5230895.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0726/125934_4f9e2aa9_5230895.png "屏幕截图.png")
#### 欢迎交流
加了我QQ的就请不要加微信了，避免联系人冗余。
Wechat_id:wechatmaster007
在读中科院攻读nlp方向小硕一枚。

#### 小鸡汤：

很多坑要自己去踩才能成长的，动不动就把问题抛给我，我除了又成长了一遍，你们还得到了什么。
你们碰到99%的问题，通过搜索引擎都是能解决的。
要善于自己动手，发现问题不是啥本事，发现问题并解决问题才是本事。
我的代码已经写得很清楚了，在框架方向基本无误的情况下，是可以通过debug调通代码的。
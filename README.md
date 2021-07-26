# 车辆检测+计数+车牌检测

#### 介绍
基于pytorch深度学习框架，实用开源模型yolov4实现模板检测与yolov5实现车牌检测与LPRNet实现车牌检测

基于win10系统，实用anaconda配置python环境，在anaconda里面下载vscode对项目进行编辑
#### 软件架构
![软件架构](https://images.gitee.com/uploads/images/2021/0726/124949_31173f9c_5230895.png "屏幕截图.png")
#### 安装教程
[保姆级环境配置：](https://blog.csdn.net/weixin_44791964/article/details/106037141)
[简洁版环境配置：]
1.  pytorch安装：
官网推荐的安装代码如下，我使用的是Cuda10的版本：
# CUDA 10.0
pip install torch===1.2.0 torchvision===0.4.0 -f https://download.pytorch.org/whl/torch_stable.html

# CUDA 9.2
pip install torch==1.2.0+cu92 torchvision==0.4.0+cu92 -f https://download.pytorch.org/whl/torch_stable.html

# CPU only
pip install torch==1.2.0+cpu torchvision==0.4.0+cpu -f https://download.pytorch.org/whl/torch_stable.html


#### 使用说明

1.  运行detect.py：实现对 /inference/images 路径下的图片和视频进行目标检测，卡车计数，和车牌检测与识别
2.  在/inference/output 路径下可看到输出情况
![实操情况](https://images.gitee.com/uploads/images/2021/0726/125452_912b655b_5230895.png "屏幕截图.png")

#### 欢迎交流
加了我QQ的就请不要加微信了，避免联系人冗余。
Wechat_id:wechatmaster007
在读中科院攻读nlp方向小硕一枚。

#### 特技

1.  使用 Readme\_XXX.md 来支持不同的语言，例如 Readme\_en.md, Readme\_zh.md
2.  Gitee 官方博客 [blog.gitee.com](https://blog.gitee.com)
3.  你可以 [https://gitee.com/explore](https://gitee.com/explore) 这个地址来了解 Gitee 上的优秀开源项目
4.  [GVP](https://gitee.com/gvp) 全称是 Gitee 最有价值开源项目，是综合评定出的优秀开源项目
5.  Gitee 官方提供的使用手册 [https://gitee.com/help](https://gitee.com/help)
6.  Gitee 封面人物是一档用来展示 Gitee 会员风采的栏目 [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)

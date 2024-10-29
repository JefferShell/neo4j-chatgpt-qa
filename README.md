## 项目介绍

这个项目主要功能是眼镜试戴，用户可以利用此系统对眼镜进行试戴，选择最适合自己的眼镜。系统采用opencv算法做眼镜试戴，底层说使用了dlib模块做一些图特征识别，web框架为django。

## 主要功能

- 图片试戴：可以直接给demo试戴，也可以自己上传任何包含人物正脸的试戴，点击眼睛会自动带上眼睛。
- 摄像头实时试戴：打开页面后可以实时打开电脑摄像头自己拍照，拍照后点击眼睛可以正常带上眼睛。


## 技术架构

- 前端：HTML、CSS、JavaScript
- 后端：Django
- 图像识别：OpenCV、Dlib


## 使用说明

**安装依赖**

- 使用conda环境安装项目所需的依赖，如下：

```
conda create -n myenv python=3.8
conda activate myenv
pip install -r requirements.txt
```

**运行项目**

- 运行项目：`python manage.py runserver`
- 地址：`localhost:8000`

**试戴</h1>

- 打开项目网站
- 点击“试戴”按钮
- 选择图片试戴或摄像头试戴


## 联系方式 

微信号：zt745324325
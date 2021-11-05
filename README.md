# python-
基于python3的安装、环境搭建，包括tensorflow、keras、gym等（win10）

# Anaconda环境
直接下载包解压安装即可https://www.anaconda.com/download/

注意添加路径至环境变量
![image](https://user-images.githubusercontent.com/23186696/140461682-3ceba3cf-8995-47d6-9e76-cef743d4f0ac.png)

# 环境常用工具

## 使用命令行界面Prompt

在所安装软件中打开即可，可直接键入python查看当前版本

## 配置独立环境

作用类似Docker，分隔开环境，使安装配置独立，便于管理

查看当前所安装环境
```
conda info --envs
```

新添环境，并配置python版本
```
onda create --name tensorflow python=3.8
```



## 安装包



## 更换源
 
阿里云 http://mirrors.aliyun.com/pypi/simple/ 
 
中国科技大学 https://pypi.mirrors.ustc.edu.cn/simple/ 
  
豆瓣(douban) http://pypi.douban.com/simple/ 
  
清华大学 https://pypi.tuna.tsinghua.edu.cn/simple/ 
 
中国科学技术大学 http://pypi.mirrors.ustc.edu.cn/simple/

临时更换
```
pip install scrapy -i https://pypi.tuna.tsinghua.edu.cn/simple
```
设为默认
```
pip install pip -U
pip config set global.index-url https://mirrors.aliyun.com/pypi/simple/
```

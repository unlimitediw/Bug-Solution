### 已完成:
* 安装docker on ubuntu
* 安装nvidia-docker2 on ubuntu
* 安装tensorflow-gpu-jupyter,tensorflow on docker(by pull)
* 安装cuda toolkit
* 运行jupyter notebook with py2 on docker
### 待完成:
* 安装nvidia driver
* 运行jupyter notebook with py3 and tensorflow on docker

### 运行语句
* `sudo docker run -it tensorflow/tensorflow:latest-gpu-jupyter bash` 暂时还没找到内部提供jupyter链接的方法
* `sudo docker run -it -p 8888:8888 tensorflow/tensorflow:latest-gpu-jupyter` 可运行但只有py2且不可运行

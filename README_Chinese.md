# 天气大数据展示平台（[英文版Readme链接 / English Version Link](https://github.com/xiangwentao666/National-Weather-Big-Data-Display-Platform-Based-on-SpringBoot-and-Vue/blob/main/README.md)）
## 基于SpringBoot和Vue的全国天气大数据展示平台
## （代码完成于2022年11月，尽快会上传）
### 概述
这是一个基于SpringBoot和Vue的全国天气大数据展示平台的开源项目，包括两个系统：分布式天气数据采集系统和天气大数据展示系统。

#### 分布式天气数据采集系统
分布式天气数据采集系统采用Python作为客户端，SpringBoot作为服务端，服务端部署在阿里云服务器上。当客户端发起连接时，服务端从服务器的数据库获取待采集的任务并分配给连接的客户端。客户端接收到任务后执行数据采集。采集完成后，采集的数据被整理成JSON格式并传回服务器存储，随后分配下一个任务。

#### 数据分析
数据采集完成后，使用HDFS、Hadoop和Hive等技术进行数据分析。

**注意**：可以在我的GitHub仓库下载名为"weather_dataset.zip"的压缩数据文件，[这是链接](https://github.com/xiangwentao666/National-Weather-Big-Data-Display-Platform-Based-on-SpringBoot-and-Vue/blob/main/weather_dataset.zip)。

#### 通过网站应用进行数据可视化
分析完成后，使用SpringBoot和Vue对结果进行可视化展示。

*欢迎fork这个项目并积极提出issue，希望能帮到大家！*

**注**：这个项目只是**我的一门课程的作业**！

### 互动视频演示

<center>
  
  ![demo](./demo.gif)

</center>

## 其他仓库推荐
### 基于姿态估计和分割算法的智能健身指导系统.[链接](https://github.com/xiangwentao666/FitnessGuidanceSystem) 
这是一个基于MediaPipe和rPPG的健身项目，整合了骨骼关键点识别、心率检测和体能训练。开发了一个桌面应用进行锻炼，以及一个微信小程序进行健身知识问答。此外，它实现了两个平台之间的互联互通和数据交换。

**注**：只是我**个人本科毕业设计**的一部分！

<center>
  
  ![./demo.gif](https://github.com/xiangwentao666/FitnessGuidanceSystem/blob/main/ppt.gif) 

</center>

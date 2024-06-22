> # Welcome to Vulcan-Robot-Architecture Documentation!

```{toctree}
:maxdepth: 1
:caption: Vulcan-Location-Docs
pages/Visual-Odometry
pages/IMU-Odometry
pages/Wheel-Odometry
pages/Lidar-Odometry
pages/GPS-Odometry
```

## 简介

![softWare pipeline](./_static/vulcan_tree.png)

#### 这是一个个人项目，做这件事主要是出于兴趣爱好。

本仓库主要为了解决机器人的定位问题。代码主要以`Nvidia` 的 `Jetson` 平台进行实现 。为了便于个人维护，我对每一个功能都单独创建了 `cpp` 文件，这可能导致文件会有很多。其中部分算法保留了多种实现方式，您可以通过修改 `CMakelists` 根据您的使用环境选择最适合的方法。

仓库的构建，主要以三种方式呈现：

1. 传统算法实现
2. `Jetson` 调用`nvidia` 加速的传统算子实现
3. 使用网络模型推理实现

------



- [视觉里程计](./pages/Visual-Odometry.md)
- [惯性里程计](./pages/IMU-Odometry.md)
- [差速地盘里程计](./pages/Wheel-Odometry.md)
- [激光雷达里程计](./pages/Lidar-Odometry.md)
- [GPS 里程计](./pages/GPS-Odometry.md)

### 快速开始

```{note}
由于这是一个个人项目，且仅在作者下班后抽时间完成。因此可能存在一些漏洞和问题，如果您使用此代码对您的财物造成了任何损失，我深表歉意，但是我并不负责，特此声明。此项目仅为学习使用。
```
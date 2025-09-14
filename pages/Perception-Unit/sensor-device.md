# 外接设备驱动

```{toctree}
:maxdepth: 1
:glob:
Sensor-Device/spad-device
Sensor-Device/utof-device
Sensor-Device/stereo-camera
Sensor-Device/lidar-device
Sensor-Device/RTK-device
```

------

用于发布各种传感器中其对应的 `frame id` 下的原始数据。供给 `perception-app` 及其他`ros` 单元的使用。

其中包含:

- 红外 TOF 传感器
- 超声波传感器
- 双目相机传感器
- 激光雷达
- RTK 模组


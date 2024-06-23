# ROS2 package xml 模版

```{toctree}
:maxdepth: 1
:glob:
```

------

ros2 中的 `package_xml` 是用来管理 ros2 的依赖关系的。可以使用 ros 的依赖管理工具 rosdep 对 ros 包的软件进行快速安装，而 rosdep 就是根据 xml 来判断需要安装哪些第三方软件的。

- `<buildtool_depend>`：指定用于构建包的工具（例如 `ament_cmake`）。
- `<build_depend>`：在构建时需要的包（例如 `rosidl_default_generators` 和 `std_msgs`）。
- `<exec_depend>`：在运行时需要的包（例如 `rclcpp` 和 `std_msgs`）。
- `<test_depend>`：在测试时需要的包（例如 `ament_lint_auto` 和 `ament_lint_common`）。

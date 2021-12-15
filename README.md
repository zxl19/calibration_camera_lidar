# calibration_camera_lidar

## Dependency

1. [nlopt](https://github.com/stevengj/nlopt)
2. [Optional]`error while loading shared libraries: libnlopt.so.0`

    ```shell
    sudo apt-get install libnlopt0
    ```

## Reference

1. [Couldn't find executable named calibration_toolkit-Issues#7](https://github.com/XidianLemon/calibration_camera_lidar/issues/7)
2. [Stack Exchange](https://unix.stackexchange.com/questions/553239/libnlopt-so-0-cannot-open-shared-object-file)

------

从autoware分离出来的相机雷达联合标定ros包

metapackage

下到自己的工作空间中，catkin_make

然后source devel/setup.bash

新开一个终端执行roscore

当前终端执行rosrun calibration_camera_lidar calibration_toolkit

要装nlopt，上github上搜索nlopt，按照下面说的步骤装上就能用了。

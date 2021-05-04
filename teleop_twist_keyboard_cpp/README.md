# teleop_twist_keyboard_cpp
C++ Implementation of the Generic Keyboard Teleop for ROS: https://github.com/ros-teleop/teleop_twist_keyboard

## 特徴

この実装では、ロボットの速度設定を特定のキーを打つことで調整することが可能である。



## ノードの実行

$ roscore

In another terminal, run
$ rosrun teleop_twist_keyboard_cpp teleop_twist_keyboard

If you want to see the outputs, check the /cmd_vel topic
$ rostopic echo /cmd_vel
```



## 利用方法

```
Reading from the keyboard  and Publishing to Twist!
---------------------------
Moving around:
   u    i    o
   j    k    l
   m    ,    .

For Holonomic mode (strafing), hold down the shift key:
---------------------------
   U    I    O
   J    K    L
   M    <    >

t : up (+z)
b : down (-z)

anything else : stop

q/z : increase/decrease max speeds by 10%
w/x : increase/decrease only linear speed by 10%
e/c : increase/decrease only angular speed by 10%

CTRL-C to quit
```



------

[![Yeah! Buy the DRAGON a COFFEE!](./.assets/COFFEE%20BUTTON%20%E3%83%BE(%C2%B0%E2%88%87%C2%B0%5E).png)](https://www.buymeacoffee.com/methylDragon)

# teleop_key

teleop_keyはROS用の汎用キーボード操作が可能

# 実行環境

| Linux Ubuntu 16.04 LTS |                   gcc 5.4.0                    |

| Linux Ubuntu 18.04 LTS |                   gcc 5.4.0                    |

シミュレーション環境　Gazebo9

32 ビット OS での動作確認はしていないので、必要な場合はご自分で試してください。

# 実行方法

```
rosrun teleop_twist_keyboard_cpp teleop_twist_keyboard_mega
```


# 使用方法

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

# デモ動画

![teleop](https://user-images.githubusercontent.com/65348333/117125549-a3571f80-add4-11eb-8080-c72f64611139.gif)

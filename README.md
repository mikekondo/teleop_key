# teleop_key

teleop_keyはROS用の汎用キーボード操作が可能

#　使用方法

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

#　デモ動画
![teleop](https://user-images.githubusercontent.com/65348333/117125549-a3571f80-add4-11eb-8080-c72f64611139.gif)

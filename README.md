# ALSRobotJoyBit
软件包github地址为：https://github.com/alsrobot-microbit-makecode-packages/ALSRobotJoyBit
软件包修改维护人员：https://github.com/bobolx

该软件包专门为micro:bit JoyBit游戏手柄开发，硬件详细信息请访问：http://www.alsrobot.cn/goods-868.html

## 摇杆
使用rockerX()方法获取摇杆X轴的值
JoyBit.rockerX()

使用rockerY()方法获取摇杆Y轴的值
JoyBit.rockerY()

## 蜂鸣器

使用myPlayTone()方法，让手柄发出音调，音调包括：do、re、mi、fa、sol、la、si，节拍包括：1/8、1/4、1/2、1、2、4

// 播放音调do节拍为整拍
JoyBit.myPlayTone(ToneHzTable.do, BeatList.whole_beat)

## 按钮

使用btnPressed()方法获取按钮的按下、抬起状态

//手柄中间左边的按钮被按下
JoyBit.btnPressed(btnList.cleft, eventList.pressed)

//手柄中间右边的按钮抬起
JoyBit.btnPressed(btnList.cright, eventList.released)

## 支持

* for PXT/microbit

## License

MIT
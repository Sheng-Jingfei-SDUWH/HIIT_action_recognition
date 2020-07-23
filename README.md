# HIIT_action_recognition
# 算法

随机森林：详见算法说明notebook

# 小程序

名字：采集运动数据

<img src="https://s1.ax1x.com/2020/06/18/Nmn6O0.png" style="zoom:50%;" />

## 数据采集部分

<img src="https://s1.ax1x.com/2020/06/18/NmmK8s.png" style="zoom: 50%;" />

- 查看运动规范动作

- 完善动作、身高、年龄、手机系统信息

- 规范手机位置与方向

- 点击开始后语音播报倒计时，再经20秒提醒动作停止，可选择保存数据或放弃保存

  ![](https://s1.ax1x.com/2020/06/18/Nmm5sP.png)

- 六轴的数据保存到该动作对应的collection里

## 运动识别部分

<img src="https://s1.ax1x.com/2020/06/18/NmuVhQ.png" style="zoom:50%;" />

### 自由模式

<img src="https://s1.ax1x.com/2020/06/18/Nmuo4g.png" style="zoom:50%;" />

- 即停即止

- 运动过程中语音播放当前动作（当检测到运动变化时才会播放下一次）

- 运动结束后弹出框显示运动次数

  <img src="https://s1.ax1x.com/2020/06/18/NmKXzd.jpg" style="zoom: 25%;" />

- 统计累计运动时间与历史数据

  <img src="https://s1.ax1x.com/2020/06/18/NmKivR.png" style="zoom:50%;" />

### 计时模式

<img src="https://s1.ax1x.com/2020/06/18/NmMhtS.png" style="zoom:50%;" />

- 输入运动时间后根据语音提示开始、停止
- 运动过程中语音播放当前动作（当检测到运动变化时才会播放下一次）
- 运动结束后弹出框显示运动次数
- 统计累计运动时间与历史数据

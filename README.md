# ZoomSdkDemo

###Zoom集成效果

在浏览器中打开下面的超链接，录制了视频，可以很快速直接验证结果。

[点击观看](https://sabinetest.bj.bcebos.com/IMG_0548.MOV)

###Zoom使用

[点击下载](https://fir.im/d5s3)

下载安装完步骤:

1. 点击API User
2. MettingID写上 377054621  密码 asdasd
3. 主控点击Start this Meeting，参与者点击Join this meeting

# 广告队列实现

### 广告队列实现

[AdQueue.java](https://github.com/ztimc/AdQueue/blob/master/app/src/main/java/com/ztimc/adqueue/AdQueue.java)

队列只能支持指定数量的结果，并且执行任务在线程池中，保证了任务的执行是并行。

### 测试类

[MainActivity.java](https://github.com/ztimc/AdQueue/blob/master/app/src/main/java/com/ztimc/adqueue/MainActivity.java)

测试是否一直能获取广告，在log中能看到两个队列执行任务的过程。

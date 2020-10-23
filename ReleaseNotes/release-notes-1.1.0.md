# QNDroidRTCLiveDemo Release Notes for 1.1.0

## 简介

互动直播解决方案通过将七牛实时音视频、字节跳动美颜滤镜以及融云 IM 融合到一起，提供音视频直播、PK 直播、高级美颜滤镜、房间消息、刷礼物等功能，帮助开发者快速构建秀场直播等相关应用。

## 功能
- 新增问题反馈模块

## 优化
- 优化界面显示效果
- 大幅度优化资源加载速度，并添加资源加载进度展示
- 优化观众人数查看方式
- 优化 PK 处理逻辑
- 优化播放器重连逻辑

## 缺陷
- 修复个别场景下无法开启直播的问题
- 修复后置摄像头贴纸显示异常的问题
- 修复播放器偶现 open failed 的问题

## 注意事项
- 如果您使用的 rtc sdk 版本是 2.5.0+，那么为了给您提供更好的使用体验，请务必依赖如下 dns 解析库：

```java
dependencies {
    implementation 'com.qiniu:happy-dns:0.2.17'
}
```
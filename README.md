# WebRTC 远程控制系统

这是一个基于 WebRTC 的远程控制系统，支持从外网访问内网设备，完全不需要搭建服务器。

## ✨ 特点

- ✅ 完全免费
- ✅ 无需服务器
- ✅ 跨网络访问
- ✅ P2P 加密连接
- ✅ 简单易用

## 🚀 快速开始

### 被控制端设置

1. 运行 WebRTC 服务器：
   `ash
   cd F:\MyRemoteControl
   python app_webrtc.py
   `

2. 打开本网页
3. 点击"我是被控制端"
4. 生成 SDP 并发送给控制端

### 控制端设置

1. 访问本网页
2. 点击"我是控制端"
3. 粘贴 SDP 并建立连接
4. 复制应答 SDP 发回给被控制端

### 建立连接

被控制端粘贴应答 SDP 并建立连接，完成后即可远程控制！

## 📖 详细说明

请访问：https://github.com/hlh66/webrtc-remote-control

## 📄 许可证

MIT License

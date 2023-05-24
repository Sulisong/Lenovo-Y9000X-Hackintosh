# Lenovo Y9000X 2020 9750H 4K-Hackintosh
#### 介绍
安装 ALCPlugFix-Swift 来修复扬声器切换异常问题, 终端使用以下命安装或卸载 ALCPlugFix
  
```
bash -c "$(curl -fsSL https://gitee.com/YasuStudio/fix-speaker-y9000x/raw/master/FixSpeaker-Y9000X.sh)"
```
*项目修改自[Sukka 黑苹果EFI](https://github.com/SukkaW/Lenovo-Y9000X-Hackintosh)；
*OC版本为0.9.2开发版，支持Mojave & Catalina & Big Sur & Monterey & Ventura；
*使用原装的Intel AX200网卡[itlwm驱动](https://github.com/OpenIntelWireless/itlwm)；
*通过 SSDT 屏蔽自带内存条 三星PM981完全（默认位置），需加另外一张内存条；
*启用 -igfxblr 修复开机背光不亮；
*修改LauncherOption为Disabled，关闭OC引导修改bios引导排序；
 #### **配置** 
- CPU：i7-9750H
- 分辨率：4K
- 硬盘：三星PM981+970evo
- 网卡：Intel AX200
#### 安装教程
1.  F2进入BIOS关闭SecureBoot，切换硬盘模式为AHCI
2.  解锁CFG Lock（可选，谨慎操作！参考CFG Lock[解锁](https://bbs.pcbeta.com/viewthread-1845189-1-1.html)）
#### 工作
- 4k显示，背光调节正常
- 耳机，麦克风，摄像头，Wi-F
- 触控板全手势支持
- 电源管理，USB接口正常
- 读卡器
- type-c接口可以正常接U盘，接type-c扩展坞以太网卡、HDMI，DP工作正常
- 外接显示器音频输出正常
- FN热键
#### 不工作
- 指纹
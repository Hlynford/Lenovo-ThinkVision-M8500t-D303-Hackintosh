# Lenovo-ThinkVision-M8500t-D303-Hackintosh
联想ThinkVision-M8500t-D303 Catalina 10.15.5 Opencore 0.5.9黑苹果驱动


## 硬件配置

| 规格     | 详细信息                                     |
| -------- | -------------------------------------------- |
| 电脑型号 | 联想ThinkVision-M8500t-D303                           |
| 处理器   | 英特尔 酷睿 i5-4590                         |
| 硬盘     | Toshiba TR200        |
| 显卡     | Intel HD Graphics 4600 |
| 内存     | 8 GB DDR3                                 |
| 显示器   | 配套显示器                     |
| 声卡     | Realtek ALC662                              |
| 有线网卡 | Intel 1217-LM                              |


## 注意事项
- [ ] **使用DP输出，勿使用VGA输出，VGA的显示器需购买DP装VGA线**
- [ ] **BIOS中关闭快速启动**
- [ ] **BIOS修改显示设置为IGA板载，不可使用独显输出**

## 驱动情况

- [x] HD4600核显驱动正常，独显屏蔽
- [x] 有线网卡驱动正常
- [x] 双屏输出正常
- [x] USB驱动正常
- [x] 声音输出正常
- [x] 耳麦输出正常
- [x] 休眠唤醒正常

## 已知问题

- [ ] **暂未**


## 更新日志
### 2020年6月18日 Opencore 0.5.9


## 说明

1. 得到更好的显示效果，安装完成后自行开启HIDPI，使用如下一键脚本

   https://github.com/xzhih/one-key-hidpi

2. 解锁根目录权限

   ```shell
   sudo mount -uw /
   ```

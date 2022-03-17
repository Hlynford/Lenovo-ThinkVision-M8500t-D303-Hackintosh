# Lenovo-ThinkVision-M8500t-D303-Hackintosh
联想ThinkVision-M8500t-D303黑苹果驱动
## 硬件配置

| 规格     | 详细信息                                     |
| -------- | -------------------------------------------- |
| 电脑型号 | 联想ThinkVision-M8500t-D303                           |
| 处理器   | 英特尔 酷睿 i5-4590                         |
| 硬盘     | Toshiba TR200        |
| 显卡     | Intel HD Graphics 4600 |
| 内存     | 16 GB DDR3                                 |
| 显示器   | 联想配套显示器 x 2                    |
| 声卡     | Realtek ALC662 板载                              |
| 有线网卡 | Intel 1217-LM 板载                             |
| 无线网卡 | Intel AC9260 PCI-E                              |
| DP转VGA | 比亚兹 DP转VGA转接线                              |


## 注意事项
- [ ] **使用DP输出，勿使用VGA输出，VGA的显示器需购买DP装VGA线**
- [ ] **BIOS修改显示设置为IGA板载，分配内存修改为64M，不可使用独显输出**
- [ ] **BIOS需关闭串口，否则影响睡眠唤醒**

## 驱动情况
- [x] HD4600核显驱动正常，独显屏蔽
- [x] 有线网卡驱动正常
- [x] 无线网卡驱动正常（Intel无线网卡）
- [x] 蓝牙驱动正常（Intel蓝牙）
- [x] 双屏输出正常
- [x] USB驱动正常
- [x] 声音输出正常
- [x] 耳麦输出正常
- [x] 睡眠唤醒正常


## 已知问题
- [ ] **查看Releases页详细说明**

## 更新日志

### 2022年3月8日 Monterey 12.2.1 OpenCore 0.7.8

### 2020年12月16日 BigSur 11.0.1 Opencore 0.6.4

### 2020年6月18日 Catalina 10.15.5 Opencore 0.5.9

## 成品EFI查看Releases


## 说明

1. 得到更好的显示效果，安装完成后自行开启HIDPI，使用如下一键脚本，如果安装后显示输出异常，再次执行脚本关闭

   https://github.com/xzhih/one-key-hidpi

2. 解锁根目录权限

   ```shell
   sudo mount -uw /
   ```

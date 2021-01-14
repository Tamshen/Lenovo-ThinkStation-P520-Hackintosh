# Lenovo-P520-Hackintosh OC

仅作备份，OS版本：macOS Catalina 10.15.6(19G2021)

EFI来自：**pcbeta@jackliu79**  帖子：[帖子链接](http://bbs.pcbeta.com/forum.php?mod=viewthread&tid=1857515)

本EFI **pcbeta@许峰** 去除了 **dsdt**


### 配置清单

| 硬件     | 整机                                               |
| -------- | -------------------------------------------------- |
| 主板     | 联想 1036 ( C422 芯片组)                           |
| 处理器   | 英特尔 Xeon(至强) W-2150B @ 3.00GHz                |
| 内存     | 三星 ECC REG 16 GB ( DDR4 2666MHz )  * 1           |
| 硬盘1    | 西数 固态 SN750 500 GB                             |
| 硬盘2    | 西数 蓝盘 4TB                                      |
| 独立显卡 | Quadro K2000 2GB ( DDR5 )                          |
| 声卡1    | ALC662 ( 未注入 )                                  |
| 声卡2    | ALC235 ( 未注入 )                                  |
| 网卡     | 英特尔 Ethernet Connection  I219-LM / 联想         |
| 网卡2    | [PCIe]BCM943224PCIEBT2BX（支持隔空投送，信号一般） |
| 电源     | 台达 690W（电源安装设计有意思）                    |
| 光驱     | 日立-LG DVD-RAM GHC0N DVD刻录机                    |

### 小结

**整机电源和主板集成很高，坏了难搞。**

后来显卡换了3070，但双显卡3070风道不合适，MacOS没驱动，能进系统，显存8MB，转Window使用了。

3070 Cuda Vray渲图真快。

Tips：BIOS可以设置默认PCIe，切换首选显卡输出，但总感觉很麻烦和鸡肋。（看看后续有没有解决办法）


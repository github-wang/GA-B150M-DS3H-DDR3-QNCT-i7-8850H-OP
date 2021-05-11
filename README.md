# GA-B150M-DS3H-DDR3-I7-8750H-opencore
+ 主板：技嘉B150M-DS3H-DDR3-CF
+ CPU:  i7 8850h(es) 代码QNCT
+ 内存：金士顿骇客神条DDR3-1866-8G
+ 固态：西数SN550-500G
+ 有线网卡：瑞昱RTL8111
+ 声卡：Realtek® ALC887芯片，启动参数alcid=1
+ 技嘉主板bios设置显示启动独显；内建显示设为自动；
+ DeviceProperties下PciRoot(0x0)/Pci(0x2,0x0)  AAPL,ig-platform-id设为07009B3E	用于驱动显示屏时桌面iGPU，核显驱动显示；
AAPL,ig-platform-id设为0300913E	当桌面iGPU仅用于计算任务，不作为驱动显示屏时使用，可VideoProc 4K解码完全成功
+ SMBIOS 设为macmini8.1或者imac 19.2 

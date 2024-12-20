# Lenovo-V330-15IKB-Hackintosh-EFI_OpenCore

Lenovo V330-15IKB的95%完美黑果 EFI（独显除外）

在`Big Sur以上`系统测试能够正常启动，功能正常。11.0以下自测。

## 截图（macOS Sonoma 14.2.1）

![Sonoma.png](https://github.com/r1i1na/Lenovo-V330-15IKB-Hackintosh-EFI_OpenCore/blob/main/Oper.PNG)

> [!NOTE]
> 若您更改了硬件，请自行修改 EFI，仅能保证在以下配置中成功运行。

EFI文件中包括了 [Airportitlwm](https://github.com/OpenIntelWireless/itlwm)，请根据实际系统版本来替换其中的kext版本。

## 配置一览：

CPU: Intel Core i5-8250U 1.80GHz

运行内存：<br>
4GB Hyrix DDR4 2400MHz<br>8GB SAMSUNG DDR4 2400MHz

声卡：Conexant CX20751

硬盘：Lenovo SL700 M.2 SSD 256G 

显卡：<br>
Intel UHD Graphics 620<br>~~AMD Radeon 530~~ (无法驱动)

有线网卡：Realtek GBE PCIe Family Controller

无线网卡：Intel Dual-Band AC 3165（蓝牙、Wi-Fi可用，但接力等无法使用）

摄像头：Integrated Camera

驱动情况：

功能95%正常。

`独显`无法驱动。受限于Mac独显的工作原理，这是无解的。

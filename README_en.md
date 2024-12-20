# Lenovo-V330-15IKB-Hackintosh-EFI_OpenCore

95% perfect Hackintosh EFI for Lenovo V330-15IKB (except discrete graphics card)

System tests on `Big Sur and above` can boot normally and function normally. Self-test below 11.0.

## Screenshot (macOS Sonoma 14.2.1)

![Sonoma.png](https://github.com/r1i1na/Lenovo-V330-15IKB-Hackintosh-EFI_OpenCore/blob/main/Oper.PNG)

> [!NOTE]
> If you change the hardware, please modify EFI yourself. It can only be guaranteed to run successfully in the following configuration.

The EFI file includes [Airportitlwm](https://github.com/OpenIntelWireless/itlwm). Please replace the kext version according to the actual system version.

## Hardware:

CPU: Intel Core i5-8250U 1.80GHz

Memory:<br>
4GB Hyrix DDR4 2400MHz<br>8GB SAMSUNG DDR4 2400MHz

Sound card: Conexant CX20751

Hard disk: Lenovo SL700 M.2 SSD 256G

Graphics card:<br>
Intel UHD Graphics 620<br>~~AMD Radeon 530~~ (Unable to drive)

Wired network card: Realtek GBE PCIe Family Controller

Wireless network card: Intel Dual-Band AC 3165 (Bluetooth and Wi-Fi are available, but relay, etc. cannot be used)

Camera: Integrated Camera

### Drive status:

95% of the functions are operational.

`Discrete graphics card` cannot be driven. Limited by the working principle of Mac discrete graphics card, this is unsolvable.

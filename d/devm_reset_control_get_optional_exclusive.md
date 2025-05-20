# Function: <code>devm_reset_control_get_optional_exclusive</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/platform.c (ffffffff81684995)
Location: include/linux/reset.h:273
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/platform.c (ffffffff816b0f22)
Location: include/linux/reset.h:273
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/platform.c (ffffffff816c606b)
Location: include/linux/reset.h:281
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81727417)
Location: include/linux/reset.h:281
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/platform.c (ffffffff81732394)
Location: include/linux/reset.h:299
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff817989d5)
Location: include/linux/reset.h:299
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/platform.c (ffffffff81771ca0)
Location: include/linux/reset.h:293
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff817db806)
Location: include/linux/reset.h:293
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/platform.c (ffffffff81796d70)
Location: include/linux/reset.h:300
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81802baf)
Location: include/linux/reset.h:300
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/platform.c (ffffffff817d5e00)
Location: include/linux/reset.h:357
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81843f93)
Location: include/linux/reset.h:357
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/platform.c (ffffffff81806cb0)
Location: include/linux/reset.h:357
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81875903)
Location: include/linux/reset.h:357
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/platform.c (ffffffff818d7565)
Location: include/linux/reset.h:391
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8194a2fa)
Location: include/linux/reset.h:391
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/platform.c (ffffffff818e14d5)
Location: include/linux/reset.h:392
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8194fe8a)
Location: include/linux/reset.h:392
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (ffffffff81709652)
Location: include/linux/reset.h:691
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffff818c4735)
Location: include/linux/reset.h:691
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81933d41)
Location: include/linux/reset.h:691
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (ffffffff81785002)
Location: include/linux/reset.h:691
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffff8195c095)
Location: include/linux/reset.h:691
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff819d7141)
Location: include/linux/reset.h:691
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (ffffffff818bbbd5)
Location: include/linux/reset.h:711
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffff81ab5ea5)
Location: include/linux/reset.h:711
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81b39dc6)
Location: include/linux/reset.h:711
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a0a711)
Location: include/linux/reset.h:711
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffff81c3e805)
Location: include/linux/reset.h:711
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81ccf746)
Location: include/linux/reset.h:711
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a53591)
Location: include/linux/reset.h:711
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffff81ca5c95)
Location: include/linux/reset.h:711
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81d37825)
Location: include/linux/reset.h:711
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a9f341)
Location: include/linux/reset.h:711
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffff81d5a8e5)
Location: include/linux/reset.h:711
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81dedaa5)
Location: include/linux/reset.h:711
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pcie-mediatek.c (ffff80001072a60c)
Location: include/linux/reset.h:357
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_parse_port
```
```
In drivers/pci/controller/dwc/pci-imx6.c (ffff800010731718)
Location: include/linux/reset.h:357
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
```
```
In drivers/tty/serial/8250/8250_dw.c (ffff8000108919ec)
Location: include/linux/reset.h:357
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dw.c:dw8250_probe
```
```
In drivers/usb/dwc2/platform.c (ffff800010a3e488)
Location: include/linux/reset.h:357
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffff800010aba768)
Location: include/linux/reset.h:357
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/host/mmci.c (ffff800010b452a8)
Location: include/linux/reset.h:357
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:mmci_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pcie-mediatek.c (c08b5cd8)
Location: include/linux/reset.h:357
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_parse_port
```
```
In drivers/pci/controller/dwc/pci-imx6.c (c08bb4a4)
Location: include/linux/reset.h:357
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
```
```
In drivers/usb/dwc2/platform.c (c0b110e8)
Location: include/linux/reset.h:357
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (c0b99d18)
Location: include/linux/reset.h:357
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/host/mmci.c (c0c1f164)
Location: include/linux/reset.h:357
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:mmci_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/platform.c (c000000000afe3c0)
Location: include/linux/reset.h:357
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (c000000000b9dcfc)
Location: include/linux/reset.h:357
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/platform.c (ffffffe00065a38e)
Location: include/linux/reset.h:357
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffe0006bf1b8)
Location: include/linux/reset.h:357
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/platform.c (ffffffff817bf090)
Location: include/linux/reset.h:357
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/platform.c (ffffffff817fbb30)
Location: include/linux/reset.h:357
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8186adb3)
Location: include/linux/reset.h:357
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/platform.c (ffffffff81815c40)
Location: include/linux/reset.h:357
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81884d43)
Location: include/linux/reset.h:357
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
</details>
</li>
</ul>

## Differences

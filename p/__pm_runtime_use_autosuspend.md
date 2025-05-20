# Function: <code>__pm_runtime_use_autosuspend</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __pm_runtime_use_autosuspend(struct device *dev, bool use);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815578b0)
Location: drivers/base/power/runtime.c:1372
Inline: False
Direct callers:
  - block/blk-core.c:blk_pm_runtime_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/usb/core/hub.c:usb_new_device
```
**Symbols:**

```
ffffffff815578b0-ffffffff81557924: __pm_runtime_use_autosuspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __pm_runtime_use_autosuspend(struct device *dev, bool use);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815a9970)
Location: drivers/base/power/runtime.c:1376
Inline: False
Direct callers:
  - block/blk-core.c:blk_pm_runtime_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/usb/core/hub.c:usb_new_device
```
**Symbols:**

```
ffffffff815a9970-ffffffff815a99dc: __pm_runtime_use_autosuspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __pm_runtime_use_autosuspend(struct device *dev, bool use);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815d8760)
Location: drivers/base/power/runtime.c:1464
Inline: False
Direct callers:
  - block/blk-core.c:blk_pm_runtime_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/usb/core/hub.c:usb_new_device
```
**Symbols:**

```
ffffffff815d8760-ffffffff815d87cc: __pm_runtime_use_autosuspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __pm_runtime_use_autosuspend(struct device *dev, bool use);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815ed270)
Location: drivers/base/power/runtime.c:1464
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff815ed270-ffffffff815ed2dc: __pm_runtime_use_autosuspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __pm_runtime_use_autosuspend(struct device *dev, bool use);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81654620)
Location: drivers/base/power/runtime.c:1456
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81654620-ffffffff8165468c: __pm_runtime_use_autosuspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __pm_runtime_use_autosuspend(struct device *dev, bool use);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8168fd20)
Location: drivers/base/power/runtime.c:1456
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff8168fd20-ffffffff8168fd8c: __pm_runtime_use_autosuspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __pm_runtime_use_autosuspend(struct device *dev, bool use);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816b00b0)
Location: drivers/base/power/runtime.c:1463
Inline: False
Direct callers:
  - block/blk-pm.c:blk_pm_runtime_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff816b00b0-ffffffff816b011c: __pm_runtime_use_autosuspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __pm_runtime_use_autosuspend(struct device *dev, bool use);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816e9f50)
Location: drivers/base/power/runtime.c:1547
Inline: False
Direct callers:
  - block/blk-pm.c:blk_pm_runtime_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff816e9f50-ffffffff816e9fbe: __pm_runtime_use_autosuspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __pm_runtime_use_autosuspend(struct device *dev, bool use);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8170dfb0)
Location: drivers/base/power/runtime.c:1549
Inline: False
Direct callers:
  - block/blk-pm.c:blk_pm_runtime_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff8170dfb0-ffffffff8170e01e: __pm_runtime_use_autosuspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __pm_runtime_use_autosuspend(struct device *dev, bool use);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817c9300)
Location: drivers/base/power/runtime.c:1574
Inline: False
Direct callers:
  - block/blk-pm.c:blk_pm_runtime_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff817c9300-ffffffff817c936e: __pm_runtime_use_autosuspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __pm_runtime_use_autosuspend(struct device *dev, bool use);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817ddc20)
Location: drivers/base/power/runtime.c:1606
Inline: False
Direct callers:
  - block/blk-pm.c:blk_pm_runtime_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff817ddc20-ffffffff817ddc8e: __pm_runtime_use_autosuspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __pm_runtime_use_autosuspend(struct device *dev, bool use);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817c1fa0)
Location: drivers/base/power/runtime.c:1606
Inline: False
Direct callers:
  - block/blk-pm.c:blk_pm_runtime_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff817c1fa0-ffffffff817c200e: __pm_runtime_use_autosuspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __pm_runtime_use_autosuspend(struct device *dev, bool use);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8184be50)
Location: drivers/base/power/runtime.c:1642
Inline: False
Direct callers:
  - block/blk-pm.c:blk_pm_runtime_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff8184be50-ffffffff8184bebe: __pm_runtime_use_autosuspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __pm_runtime_use_autosuspend(struct device *dev, bool use);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff819918bf)
Location: drivers/base/power/runtime.c:1681
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:devm_pm_runtime_enable
Direct callers:
  - block/blk-pm.c:blk_pm_runtime_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff819917b0-ffffffff8199181f: __pm_runtime_use_autosuspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __pm_runtime_use_autosuspend(struct device *dev, bool use);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81b01ccf)
Location: drivers/base/power/runtime.c:1695
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:devm_pm_runtime_enable
Direct callers:
  - block/blk-pm.c:blk_pm_runtime_init
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_shutdown
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_remove
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81b01ba0-ffffffff81b01c0f: __pm_runtime_use_autosuspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __pm_runtime_use_autosuspend(struct device *dev, bool use);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81b4fdc6)
Location: drivers/base/power/runtime.c:1695
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:devm_pm_runtime_enable
Direct callers:
  - block/blk-pm.c:blk_pm_runtime_init
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_shutdown
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_remove
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/tty/serial/serial_port.c:serial_port_remove
  - drivers/tty/serial/serial_port.c:serial_port_probe
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81b4fc90-ffffffff81b4fcff: __pm_runtime_use_autosuspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __pm_runtime_use_autosuspend(struct device *dev, bool use);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81ba8346)
Location: drivers/base/power/runtime.c:1696
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:devm_pm_runtime_enable
Direct callers:
  - block/blk-pm.c:blk_pm_runtime_init
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_shutdown
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_remove
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/tty/serial/serial_port.c:serial_port_remove
  - drivers/tty/serial/serial_port.c:serial_port_probe
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81ba8210-ffffffff81ba827f: __pm_runtime_use_autosuspend (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __pm_runtime_use_autosuspend(struct device *dev, bool use);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffff8000108fd910)
Location: drivers/base/power/runtime.c:1549
Inline: False
Direct callers:
  - block/blk-pm.c:blk_pm_runtime_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_remove
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_remove
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe
  - drivers/mmc/core/block.c:mmc_blk_probe
  - drivers/mmc/host/mmci.c:mmci_probe
```
**Symbols:**

```
ffff8000108fd910-ffff8000108fd9c0: __pm_runtime_use_autosuspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __pm_runtime_use_autosuspend(struct device *dev, bool use);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (c09e82d8)
Location: drivers/base/power/runtime.c:1549
Inline: False
Direct callers:
  - block/blk-pm.c:blk_pm_runtime_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
  - drivers/tty/serial/omap-serial.c:serial_omap_remove
  - drivers/tty/serial/omap-serial.c:serial_omap_probe
  - drivers/tty/serial/omap-serial.c:serial_omap_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_remove
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_remove
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_probe
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_probe
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/musb/musb_core.c:musb_remove
  - drivers/usb/musb/musb_core.c:musb_init_controller
  - drivers/usb/musb/musb_core.c:musb_init_controller
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_probe
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_remove
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/mmc/core/block.c:mmc_blk_probe
  - drivers/mmc/host/mmci.c:mmci_probe
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_remove
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe
```
**Symbols:**

```
c09e82d8-c09e8338: __pm_runtime_use_autosuspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __pm_runtime_use_autosuspend(struct device *dev, bool use);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (c00000000099adb0)
Location: drivers/base/power/runtime.c:1549
Inline: False
Direct callers:
  - block/blk-pm.c:blk_pm_runtime_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
c00000000099adb0-c00000000099ae70: __pm_runtime_use_autosuspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __pm_runtime_use_autosuspend(struct device *dev, bool use);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffe00058c53e)
Location: drivers/base/power/runtime.c:1549
Inline: False
Direct callers:
  - block/blk-pm.c:blk_pm_runtime_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/block.c:mmc_blk_probe
```
**Symbols:**

```
ffffffe00058c53e-ffffffe00058c5e0: __pm_runtime_use_autosuspend (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __pm_runtime_use_autosuspend(struct device *dev, bool use);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816d3700)
Location: drivers/base/power/runtime.c:1549
Inline: False
Direct callers:
  - block/blk-pm.c:blk_pm_runtime_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/usb/core/hub.c:usb_new_device
```
**Symbols:**

```
ffffffff816d3700-ffffffff816d376e: __pm_runtime_use_autosuspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __pm_runtime_use_autosuspend(struct device *dev, bool use);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816ae9b0)
Location: drivers/base/power/runtime.c:1549
Inline: False
Direct callers:
  - block/blk-pm.c:blk_pm_runtime_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/usb/core/hub.c:usb_new_device
```
**Symbols:**

```
ffffffff816ae9b0-ffffffff816aea18: __pm_runtime_use_autosuspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __pm_runtime_use_autosuspend(struct device *dev, bool use);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81701c70)
Location: drivers/base/power/runtime.c:1549
Inline: False
Direct callers:
  - block/blk-pm.c:blk_pm_runtime_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/i2c/busses/i2c-amd-mp2-pci.c:amd_mp2_pci_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81701c70-ffffffff81701cde: __pm_runtime_use_autosuspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __pm_runtime_use_autosuspend(struct device *dev, bool use);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8171c120)
Location: drivers/base/power/runtime.c:1549
Inline: False
Direct callers:
  - block/blk-pm.c:blk_pm_runtime_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff8171c120-ffffffff8171c185: __pm_runtime_use_autosuspend (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>

# Function: <code>pm_runtime_set_autosuspend_delay</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pm_runtime_set_autosuspend_delay(struct device *dev, int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81557850)
Location: drivers/base/power/runtime.c:1351
Inline: False
Direct callers:
  - block/blk-core.c:blk_pm_runtime_init
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/sysfs.c:autosuspend_store
```
**Symbols:**

```
ffffffff81557850-ffffffff815578ad: pm_runtime_set_autosuspend_delay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pm_runtime_set_autosuspend_delay(struct device *dev, int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815a9910)
Location: drivers/base/power/runtime.c:1355
Inline: False
Direct callers:
  - block/blk-core.c:blk_pm_runtime_init
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/sysfs.c:autosuspend_store
```
**Symbols:**

```
ffffffff815a9910-ffffffff815a996d: pm_runtime_set_autosuspend_delay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pm_runtime_set_autosuspend_delay(struct device *dev, int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815d8700)
Location: drivers/base/power/runtime.c:1443
Inline: False
Direct callers:
  - block/blk-core.c:blk_pm_runtime_init
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/sysfs.c:autosuspend_store
```
**Symbols:**

```
ffffffff815d8700-ffffffff815d875d: pm_runtime_set_autosuspend_delay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pm_runtime_set_autosuspend_delay(struct device *dev, int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815ed210)
Location: drivers/base/power/runtime.c:1443
Inline: False
Direct callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/sysfs.c:autosuspend_store
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff815ed210-ffffffff815ed26d: pm_runtime_set_autosuspend_delay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pm_runtime_set_autosuspend_delay(struct device *dev, int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816545c0)
Location: drivers/base/power/runtime.c:1435
Inline: False
Direct callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/sysfs.c:autosuspend_store
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff816545c0-ffffffff8165461d: pm_runtime_set_autosuspend_delay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pm_runtime_set_autosuspend_delay(struct device *dev, int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8168fcc0)
Location: drivers/base/power/runtime.c:1435
Inline: False
Direct callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/sysfs.c:autosuspend_store
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff8168fcc0-ffffffff8168fd1d: pm_runtime_set_autosuspend_delay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pm_runtime_set_autosuspend_delay(struct device *dev, int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816b0050)
Location: drivers/base/power/runtime.c:1442
Inline: False
Direct callers:
  - block/blk-pm.c:blk_pm_runtime_init
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/sysfs.c:autosuspend_store
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff816b0050-ffffffff816b00ad: pm_runtime_set_autosuspend_delay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pm_runtime_set_autosuspend_delay(struct device *dev, int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816e9ee0)
Location: drivers/base/power/runtime.c:1526
Inline: False
Direct callers:
  - block/blk-pm.c:blk_pm_runtime_init
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/sysfs.c:autosuspend_store
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff816e9ee0-ffffffff816e9f41: pm_runtime_set_autosuspend_delay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pm_runtime_set_autosuspend_delay(struct device *dev, int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8170df40)
Location: drivers/base/power/runtime.c:1528
Inline: False
Direct callers:
  - block/blk-pm.c:blk_pm_runtime_init
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/sysfs.c:autosuspend_store
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff8170df40-ffffffff8170dfa1: pm_runtime_set_autosuspend_delay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pm_runtime_set_autosuspend_delay(struct device *dev, int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817c9290)
Location: drivers/base/power/runtime.c:1553
Inline: False
Direct callers:
  - block/blk-pm.c:blk_pm_runtime_init
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/scsi/sd.c:sd_probe
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/sysfs.c:autosuspend_store
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff817c9290-ffffffff817c92f1: pm_runtime_set_autosuspend_delay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pm_runtime_set_autosuspend_delay(struct device *dev, int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817ddbb0)
Location: drivers/base/power/runtime.c:1585
Inline: False
Direct callers:
  - block/blk-pm.c:blk_pm_runtime_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/scsi/sd.c:sd_probe
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/sysfs.c:autosuspend_store
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff817ddbb0-ffffffff817ddc11: pm_runtime_set_autosuspend_delay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pm_runtime_set_autosuspend_delay(struct device *dev, int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817c1f30)
Location: drivers/base/power/runtime.c:1585
Inline: False
Direct callers:
  - block/blk-pm.c:blk_pm_runtime_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/scsi/sd.c:sd_probe
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/sysfs.c:autosuspend_store
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff817c1f30-ffffffff817c1f91: pm_runtime_set_autosuspend_delay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pm_runtime_set_autosuspend_delay(struct device *dev, int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8184bde0)
Location: drivers/base/power/runtime.c:1621
Inline: False
Direct callers:
  - block/blk-pm.c:blk_pm_runtime_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/scsi/sd.c:sd_probe
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/sysfs.c:autosuspend_store
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff8184bde0-ffffffff8184be41: pm_runtime_set_autosuspend_delay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pm_runtime_set_autosuspend_delay(struct device *dev, int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81991750)
Location: drivers/base/power/runtime.c:1660
Inline: False
Direct callers:
  - block/blk-pm.c:blk_pm_runtime_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/scsi/sd.c:sd_probe
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/sysfs.c:autosuspend_store
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81991750-ffffffff819917ae: pm_runtime_set_autosuspend_delay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pm_runtime_set_autosuspend_delay(struct device *dev, int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81b01b30)
Location: drivers/base/power/runtime.c:1674
Inline: False
Direct callers:
  - block/blk-pm.c:blk_pm_runtime_init
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/scsi/sd.c:sd_probe
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/sysfs.c:autosuspend_store
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81b01b30-ffffffff81b01b8e: pm_runtime_set_autosuspend_delay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pm_runtime_set_autosuspend_delay(struct device *dev, int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81b4fc20)
Location: drivers/base/power/runtime.c:1674
Inline: False
Direct callers:
  - block/blk-pm.c:blk_pm_runtime_init
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/tty/serial/serial_port.c:serial_port_probe
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/scsi/sd.c:sd_probe
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/sysfs.c:autosuspend_store
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81b4fc20-ffffffff81b4fc7e: pm_runtime_set_autosuspend_delay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pm_runtime_set_autosuspend_delay(struct device *dev, int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81ba81a0)
Location: drivers/base/power/runtime.c:1675
Inline: False
Direct callers:
  - block/blk-pm.c:blk_pm_runtime_init
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/tty/serial/serial_port.c:serial_port_probe
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/scsi/sd.c:sd_probe
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/sysfs.c:autosuspend_store
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81ba81a0-ffffffff81ba81fe: pm_runtime_set_autosuspend_delay (STB_GLOBAL)
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
void pm_runtime_set_autosuspend_delay(struct device *dev, int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffff8000108fd860)
Location: drivers/base/power/runtime.c:1528
Inline: False
Direct callers:
  - block/blk-pm.c:blk_pm_runtime_init
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/sysfs.c:autosuspend_store
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe
  - drivers/mmc/core/block.c:mmc_blk_probe
  - drivers/mmc/host/mmci.c:mmci_probe
```
**Symbols:**

```
ffff8000108fd860-ffff8000108fd90c: pm_runtime_set_autosuspend_delay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pm_runtime_set_autosuspend_delay(struct device *dev, int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (c09e827c)
Location: drivers/base/power/runtime.c:1528
Inline: False
Direct callers:
  - block/blk-pm.c:blk_pm_runtime_init
  - drivers/tty/serial/omap-serial.c:serial_omap_probe
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_probe
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/sysfs.c:autosuspend_store
  - drivers/usb/musb/musb_core.c:musb_init_controller
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/mmc/core/block.c:mmc_blk_probe
  - drivers/mmc/host/mmci.c:mmci_probe
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe
```
**Symbols:**

```
c09e827c-c09e82d8: pm_runtime_set_autosuspend_delay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pm_runtime_set_autosuspend_delay(struct device *dev, int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (c00000000099ad00)
Location: drivers/base/power/runtime.c:1528
Inline: False
Direct callers:
  - block/blk-pm.c:blk_pm_runtime_init
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/sysfs.c:autosuspend_store
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
c00000000099ad00-c00000000099adb0: pm_runtime_set_autosuspend_delay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pm_runtime_set_autosuspend_delay(struct device *dev, int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffe00058c4ae)
Location: drivers/base/power/runtime.c:1528
Inline: False
Direct callers:
  - block/blk-pm.c:blk_pm_runtime_init
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/sysfs.c:autosuspend_store
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/block.c:mmc_blk_probe
```
**Symbols:**

```
ffffffe00058c4ae-ffffffe00058c53e: pm_runtime_set_autosuspend_delay (STB_GLOBAL)
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
void pm_runtime_set_autosuspend_delay(struct device *dev, int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816d3690)
Location: drivers/base/power/runtime.c:1528
Inline: False
Direct callers:
  - block/blk-pm.c:blk_pm_runtime_init
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/sysfs.c:autosuspend_store
```
**Symbols:**

```
ffffffff816d3690-ffffffff816d36f1: pm_runtime_set_autosuspend_delay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pm_runtime_set_autosuspend_delay(struct device *dev, int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816ae950)
Location: drivers/base/power/runtime.c:1528
Inline: False
Direct callers:
  - block/blk-pm.c:blk_pm_runtime_init
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/sysfs.c:autosuspend_store
```
**Symbols:**

```
ffffffff816ae950-ffffffff816ae9ab: pm_runtime_set_autosuspend_delay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pm_runtime_set_autosuspend_delay(struct device *dev, int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81701c00)
Location: drivers/base/power/runtime.c:1528
Inline: False
Direct callers:
  - block/blk-pm.c:blk_pm_runtime_init
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/sysfs.c:autosuspend_store
  - drivers/i2c/busses/i2c-amd-mp2-pci.c:amd_mp2_pci_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81701c00-ffffffff81701c61: pm_runtime_set_autosuspend_delay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pm_runtime_set_autosuspend_delay(struct device *dev, int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8171c0c0)
Location: drivers/base/power/runtime.c:1528
Inline: False
Direct callers:
  - block/blk-pm.c:blk_pm_runtime_init
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/sysfs.c:autosuspend_store
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff8171c0c0-ffffffff8171c118: pm_runtime_set_autosuspend_delay (STB_GLOBAL)
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

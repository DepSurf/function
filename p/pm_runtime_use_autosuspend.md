# Function: <code>pm_runtime_use_autosuspend</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b5ceb)
Location: include/linux/pm_runtime.h:272
Inline: True
Inline callers:
  - block/blk-core.c:blk_pm_runtime_init
```
```
In drivers/mfd/arizona-core.c (ffffffff8157db56)
Location: include/linux/pm_runtime.h:272
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/usb/core/hub.c (ffffffff81608583)
Location: include/linux/pm_runtime.h:272
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fabbb)
Location: include/linux/pm_runtime.h:278
Inline: True
Inline callers:
  - block/blk-core.c:blk_pm_runtime_init
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff8149550e)
Location: include/linux/pm_runtime.h:278
Inline: True
```
```
In drivers/mfd/arizona-core.c (ffffffff815d2ccb)
Location: include/linux/pm_runtime.h:278
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/usb/core/hub.c (ffffffff81668253)
Location: include/linux/pm_runtime.h:278
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8141451b)
Location: include/linux/pm_runtime.h:281
Inline: True
Inline callers:
  - block/blk-core.c:blk_pm_runtime_init
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff814b6ec1)
Location: include/linux/pm_runtime.h:281
Inline: True
```
```
In drivers/mfd/arizona-core.c (ffffffff815ffa0f)
Location: include/linux/pm_runtime.h:281
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/usb/core/hub.c (ffffffff81695f73)
Location: include/linux/pm_runtime.h:281
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
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
In block/blk-core.c (ffffffff8142228a)
Location: include/linux/pm_runtime.h:269
Inline: True
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff814c17fb)
Location: include/linux/pm_runtime.h:269
Inline: True
```
```
In drivers/mfd/arizona-core.c (ffffffff81613918)
Location: include/linux/pm_runtime.h:269
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/usb/core/hub.c (ffffffff816ab383)
Location: include/linux/pm_runtime.h:269
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff817278b0)
Location: include/linux/pm_runtime.h:269
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
In block/blk-core.c (ffffffff8144d10a)
Location: include/linux/pm_runtime.h:269
Inline: True
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff81501b2b)
Location: include/linux/pm_runtime.h:269
Inline: True
```
```
In drivers/mfd/arizona-core.c (ffffffff8167be29)
Location: include/linux/pm_runtime.h:269
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/usb/core/hub.c (ffffffff817167e3)
Location: include/linux/pm_runtime.h:269
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81798c26)
Location: include/linux/pm_runtime.h:269
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
In block/blk-core.c (ffffffff81480382)
Location: include/linux/pm_runtime.h:269
Inline: True
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff81530b5e)
Location: include/linux/pm_runtime.h:269
Inline: True
```
```
In drivers/mfd/arizona-core.c (ffffffff816b78e7)
Location: include/linux/pm_runtime.h:269
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/usb/core/hub.c (ffffffff81755602)
Location: include/linux/pm_runtime.h:269
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff817dba2e)
Location: include/linux/pm_runtime.h:269
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
In block/blk-pm.c (ffffffff814d5e5b)
Location: include/linux/pm_runtime.h:269
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pm_runtime_init
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff815480ee)
Location: include/linux/pm_runtime.h:269
Inline: True
```
```
In drivers/mfd/arizona-core.c (ffffffff816d8b27)
Location: include/linux/pm_runtime.h:269
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/usb/core/hub.c (ffffffff81779b32)
Location: include/linux/pm_runtime.h:269
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81802dd7)
Location: include/linux/pm_runtime.h:269
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
In block/blk-pm.c (ffffffff81501cab)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pm_runtime_init
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff81578171)
Location: include/linux/pm_runtime.h:270
Inline: True
```
```
In drivers/mfd/arizona-core.c (ffffffff8171490c)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/usb/core/hub.c (ffffffff817b7994)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff818441de)
Location: include/linux/pm_runtime.h:270
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
In block/blk-pm.c (ffffffff8151fbdb)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pm_runtime_init
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff815998f9)
Location: include/linux/pm_runtime.h:270
Inline: True
```
```
In drivers/mfd/arizona-core.c (ffffffff81738c1a)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/usb/core/hub.c (ffffffff817e8164)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81875b54)
Location: include/linux/pm_runtime.h:270
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
In block/blk-pm.c (ffffffff81580b5b)
Location: include/linux/pm_runtime.h:280
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pm_runtime_init
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff816390d9)
Location: include/linux/pm_runtime.h:280
Inline: True
```
```
In drivers/mfd/arizona-core.c (ffffffff817f6260)
Location: include/linux/pm_runtime.h:280
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/usb/core/hub.c (ffffffff818b76b4)
Location: include/linux/pm_runtime.h:280
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8194a49d)
Location: include/linux/pm_runtime.h:280
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
In block/blk-pm.c (ffffffff8159db9b)
Location: include/linux/pm_runtime.h:537
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pm_runtime_init
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff8165fbc0)
Location: include/linux/pm_runtime.h:537
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe
```
```
In drivers/mfd/arizona-core.c (ffffffff81c11496)
Location: include/linux/pm_runtime.h:537
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/usb/core/hub.c (ffffffff818c5fc4)
Location: include/linux/pm_runtime.h:537
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8195002d)
Location: include/linux/pm_runtime.h:537
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
In block/blk-pm.c (ffffffff815a47db)
Location: include/linux/pm_runtime.h:537
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pm_runtime_init
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff81642098)
Location: include/linux/pm_runtime.h:537
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe
```
```
In drivers/mfd/arizona-core.c (ffffffff81c03633)
Location: include/linux/pm_runtime.h:537
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/usb/core/hub.c (ffffffff818a92a4)
Location: include/linux/pm_runtime.h:537
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81933edf)
Location: include/linux/pm_runtime.h:537
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
In block/blk-pm.c (ffffffff8160d1cb)
Location: include/linux/pm_runtime.h:547
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pm_runtime_init
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff816b2d6a)
Location: include/linux/pm_runtime.h:547
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe
```
```
In drivers/usb/core/hub.c (ffffffff8193e1b4)
Location: include/linux/pm_runtime.h:547
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff819d72df)
Location: include/linux/pm_runtime.h:547
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
In block/blk-pm.c (ffffffff816c135b)
Location: include/linux/pm_runtime.h:580
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pm_runtime_init
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff817d6794)
Location: include/linux/pm_runtime.h:580
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe
```
```
In drivers/usb/core/hub.c (ffffffff81a961e2)
Location: include/linux/pm_runtime.h:580
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81b3a061)
Location: include/linux/pm_runtime.h:580
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
In block/blk-pm.c (ffffffff8178243b)
Location: include/linux/pm_runtime.h:584
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pm_runtime_init
```
```
In drivers/pci/pcie/portdrv.c (ffffffff818f7b88)
Location: include/linux/pm_runtime.h:584
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
```
```
In drivers/usb/core/hub.c (ffffffff81c1893a)
Location: include/linux/pm_runtime.h:584
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81ccf9e1)
Location: include/linux/pm_runtime.h:584
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
In block/blk-pm.c (ffffffff817c256b)
Location: include/linux/pm_runtime.h:584
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pm_runtime_init
```
```
In drivers/pci/pcie/portdrv.c (ffffffff8193afe1)
Location: include/linux/pm_runtime.h:584
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
```
```
In drivers/tty/serial/serial_port.c (ffffffff81ac469f)
Location: include/linux/pm_runtime.h:584
Inline: True
Inline callers:
  - drivers/tty/serial/serial_port.c:serial_port_probe
```
```
In drivers/usb/core/hub.c (ffffffff81c7f91a)
Location: include/linux/pm_runtime.h:584
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81d37ada)
Location: include/linux/pm_runtime.h:584
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
In block/blk-pm.c (ffffffff818072cb)
Location: include/linux/pm_runtime.h:582
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pm_runtime_init
```
```
In drivers/pci/pcie/portdrv.c (ffffffff81983e74)
Location: include/linux/pm_runtime.h:582
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
```
```
In drivers/tty/serial/serial_port.c (ffffffff81b1759f)
Location: include/linux/pm_runtime.h:582
Inline: True
Inline callers:
  - drivers/tty/serial/serial_port.c:serial_port_probe
```
```
In drivers/usb/core/hub.c (ffffffff81d3430b)
Location: include/linux/pm_runtime.h:582
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81dedd5a)
Location: include/linux/pm_runtime.h:582
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
In block/blk-pm.c (ffff8000106288f8)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pm_runtime_init
```
```
In drivers/pci/pcie/portdrv_pci.c (ffff800010701050)
Location: include/linux/pm_runtime.h:270
Inline: True
```
```
In drivers/mfd/arizona-core.c (ffff80001093389c)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/spi/spi-omap2-mcspi.c (ffff8000109cd96c)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e9b70)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
```
```
In drivers/usb/core/hub.c (ffff800010a17468)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffff800010aba990)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/i2c/busses/i2c-omap.c (ffff800010abb7c8)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
```
```
In drivers/i2c/busses/i2c-sprd.c (ffff800010abcf90)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe
```
```
In drivers/mmc/core/block.c (ffff800010b409e4)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_probe
```
```
In drivers/mmc/host/mmci.c (ffff800010b45708)
Location: include/linux/pm_runtime.h:270
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
In block/blk-pm.c (c07d001c)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pm_runtime_init
```
```
In drivers/pci/pcie/portdrv_pci.c (c0898df0)
Location: include/linux/pm_runtime.h:270
Inline: True
```
```
In drivers/tty/serial/omap-serial.c (c09a0178)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - drivers/tty/serial/omap-serial.c:serial_omap_probe
```
```
In drivers/mfd/arizona-core.c (c0a1677c)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/spi/spi-omap2-mcspi.c (c0ab7e7c)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0acae44)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
```
```
In drivers/net/ethernet/ti/davinci_mdio.c (c0acfe28)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_probe
```
```
In drivers/usb/core/hub.c (c0aef4e0)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/musb/musb_core.c (c0b662ec)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - drivers/usb/musb/musb_core.c:musb_init_controller
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (c0b99ee8)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/i2c/busses/i2c-imx.c (c0b9bbfc)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_probe
```
```
In drivers/i2c/busses/i2c-omap.c (c0b9ca98)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
```
```
In drivers/mmc/core/block.c (c0c1b0d0)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_probe
```
```
In drivers/mmc/host/mmci.c (c0c1f5e8)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:mmci_probe
```
```
In drivers/mmc/host/omap_hsmmc.c (c0c2b23c)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe
```
```
In drivers/mmc/host/sdhci-esdhc-imx.c (c0c2ee08)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe
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
In block/blk-pm.c (c0000000007ca404)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pm_runtime_init
```
```
In drivers/mfd/arizona-core.c (c0000000009d45d0)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/usb/core/hub.c (c000000000ad00e0)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (c000000000b9de68)
Location: include/linux/pm_runtime.h:270
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
In block/blk-pm.c (ffffffe000459dc4)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pm_runtime_init
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffe0004cfe58)
Location: include/linux/pm_runtime.h:270
Inline: True
```
```
In drivers/mfd/arizona-core.c (ffffffe0005a9608)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/usb/core/hub.c (ffffffe00063c2cc)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffe0006bf314)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/block.c (ffffffe000717c68)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_probe
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff815181bb)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pm_runtime_init
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff8158d789)
Location: include/linux/pm_runtime.h:270
Inline: True
```
```
In drivers/mfd/arizona-core.c (ffffffff816fc97a)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/usb/core/hub.c (ffffffff817a0544)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff815084cb)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pm_runtime_init
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff8157c2c9)
Location: include/linux/pm_runtime.h:270
Inline: True
```
```
In drivers/mfd/arizona-core.c (ffffffff816d078a)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/usb/core/hub.c (ffffffff817921b4)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff8151424b)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pm_runtime_init
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff8158d649)
Location: include/linux/pm_runtime.h:270
Inline: True
```
```
In drivers/mfd/arizona-core.c (ffffffff8172c0da)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/usb/core/hub.c (ffffffff817dcfe4)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/i2c/busses/i2c-amd-mp2-pci.c (ffffffff8186834c)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-mp2-pci.c:amd_mp2_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8186b004)
Location: include/linux/pm_runtime.h:270
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
In block/blk-pm.c (ffffffff8152da0b)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pm_runtime_init
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff815a7af9)
Location: include/linux/pm_runtime.h:270
Inline: True
```
```
In drivers/mfd/arizona-core.c (ffffffff8174751a)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/usb/core/hub.c (ffffffff817f72b4)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81884f94)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
</details>
</li>
</ul>

## Differences

# Function: <code>pm_runtime_dont_use_autosuspend</code>

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
In drivers/pci/pcie/portdrv_pci.c (ffffffff8149539e)
Location: include/linux/pm_runtime.h:283
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
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
In drivers/pci/pcie/portdrv_pci.c (ffffffff814b6d4e)
Location: include/linux/pm_runtime.h:286
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
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
In drivers/pci/pcie/portdrv_pci.c (ffffffff814c168e)
Location: include/linux/pm_runtime.h:274
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff817271cc)
Location: include/linux/pm_runtime.h:274
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
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
In drivers/pci/pcie/portdrv_pci.c (ffffffff815019fe)
Location: include/linux/pm_runtime.h:274
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8179904f)
Location: include/linux/pm_runtime.h:274
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
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
In drivers/pci/pcie/portdrv_pci.c (ffffffff81530a1b)
Location: include/linux/pm_runtime.h:274
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff817db5ff)
Location: include/linux/pm_runtime.h:274
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
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
In drivers/pci/pcie/portdrv_pci.c (ffffffff81547ffb)
Location: include/linux/pm_runtime.h:274
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff818029af)
Location: include/linux/pm_runtime.h:274
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
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
In drivers/pci/pcie/portdrv_pci.c (ffffffff81578090)
Location: include/linux/pm_runtime.h:275
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8184450f)
Location: include/linux/pm_runtime.h:275
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
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
In drivers/pci/pcie/portdrv_pci.c (ffffffff81599820)
Location: include/linux/pm_runtime.h:275
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81875e5f)
Location: include/linux/pm_runtime.h:275
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
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
In drivers/pci/pcie/portdrv_pci.c (ffffffff81639000)
Location: include/linux/pm_runtime.h:285
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8194a1bf)
Location: include/linux/pm_runtime.h:285
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
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
In drivers/pci/pcie/portdrv_pci.c (ffffffff8165fb10)
Location: include/linux/pm_runtime.h:550
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8194fd4f)
Location: include/linux/pm_runtime.h:550
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
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
In drivers/pci/pcie/portdrv_pci.c (ffffffff81641ff0)
Location: include/linux/pm_runtime.h:550
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81933c0f)
Location: include/linux/pm_runtime.h:550
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
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
In drivers/pci/pcie/portdrv_pci.c (ffffffff816b2cc0)
Location: include/linux/pm_runtime.h:560
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff819d703f)
Location: include/linux/pm_runtime.h:560
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
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
In drivers/pci/pcie/portdrv_pci.c (ffffffff817d66d5)
Location: include/linux/pm_runtime.h:593
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
```
```
In drivers/base/power/runtime.c (ffffffff819918bf)
Location: include/linux/pm_runtime.h:593
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:devm_pm_runtime_enable
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81b39c95)
Location: include/linux/pm_runtime.h:593
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
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
In drivers/pci/pcie/portdrv.c (ffffffff818f7c98)
Location: include/linux/pm_runtime.h:597
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_shutdown
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_remove
```
```
In drivers/base/power/runtime.c (ffffffff81b01ccf)
Location: include/linux/pm_runtime.h:597
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:devm_pm_runtime_enable
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81ccf605)
Location: include/linux/pm_runtime.h:597
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
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
In drivers/pci/pcie/portdrv.c (ffffffff8193b0f8)
Location: include/linux/pm_runtime.h:597
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_shutdown
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_remove
```
```
In drivers/tty/serial/serial_port.c (ffffffff81ac4635)
Location: include/linux/pm_runtime.h:597
Inline: True
Inline callers:
  - drivers/tty/serial/serial_port.c:serial_port_remove
```
```
In drivers/base/power/runtime.c (ffffffff81b4fdc6)
Location: include/linux/pm_runtime.h:597
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:devm_pm_runtime_enable
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81d376d5)
Location: include/linux/pm_runtime.h:597
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
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
In drivers/pci/pcie/portdrv.c (ffffffff81983f88)
Location: include/linux/pm_runtime.h:595
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_shutdown
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_remove
```
```
In drivers/tty/serial/serial_port.c (ffffffff81b17535)
Location: include/linux/pm_runtime.h:595
Inline: True
Inline callers:
  - drivers/tty/serial/serial_port.c:serial_port_remove
```
```
In drivers/base/power/runtime.c (ffffffff81ba8346)
Location: include/linux/pm_runtime.h:595
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:devm_pm_runtime_enable
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81ded955)
Location: include/linux/pm_runtime.h:595
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
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
In drivers/pci/pcie/portdrv_pci.c (ffff800010701100)
Location: include/linux/pm_runtime.h:275
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
```
```
In drivers/spi/spi-omap2-mcspi.c (ffff8000109ccc04)
Location: include/linux/pm_runtime.h:275
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_remove
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffff800010abad00)
Location: include/linux/pm_runtime.h:275
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
```
```
In drivers/i2c/busses/i2c-omap.c (ffff800010abaf24)
Location: include/linux/pm_runtime.h:275
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_remove
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
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
In drivers/pci/pcie/portdrv_pci.c (c0898d00)
Location: include/linux/pm_runtime.h:275
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
```
```
In drivers/tty/serial/omap-serial.c (c099ed3c)
Location: include/linux/pm_runtime.h:275
Inline: True
Inline callers:
  - drivers/tty/serial/omap-serial.c:serial_omap_remove
  - drivers/tty/serial/omap-serial.c:serial_omap_probe
```
```
In drivers/spi/spi-omap2-mcspi.c (c0ab5e10)
Location: include/linux/pm_runtime.h:275
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_remove
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
```
```
In drivers/net/ethernet/ti/davinci_mdio.c (c0acfc04)
Location: include/linux/pm_runtime.h:275
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_remove
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_probe
```
```
In drivers/usb/musb/musb_core.c (c0b6553c)
Location: include/linux/pm_runtime.h:275
Inline: True
Inline callers:
  - drivers/usb/musb/musb_core.c:musb_remove
  - drivers/usb/musb/musb_core.c:musb_init_controller
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (c0b9a0f4)
Location: include/linux/pm_runtime.h:275
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
```
```
In drivers/i2c/busses/i2c-imx.c (c0b9be5c)
Location: include/linux/pm_runtime.h:275
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_probe
```
```
In drivers/i2c/busses/i2c-omap.c (c0b9c830)
Location: include/linux/pm_runtime.h:275
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_remove
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
```
```
In drivers/mmc/host/omap_hsmmc.c (c0c2a984)
Location: include/linux/pm_runtime.h:275
Inline: True
Inline callers:
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_remove
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-platdrv.c (c000000000b9e150)
Location: include/linux/pm_runtime.h:275
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
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
In drivers/pci/pcie/portdrv_pci.c (ffffffe0004cfd78)
Location: include/linux/pm_runtime.h:275
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffe0006bf4f0)
Location: include/linux/pm_runtime.h:275
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
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
In drivers/pci/pcie/portdrv_pci.c (ffffffff8158d6b0)
Location: include/linux/pm_runtime.h:275
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_pci.c (ffffffff8157c1f0)
Location: include/linux/pm_runtime.h:275
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
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
In drivers/pci/pcie/portdrv_pci.c (ffffffff8158d570)
Location: include/linux/pm_runtime.h:275
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8186b30f)
Location: include/linux/pm_runtime.h:275
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
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
In drivers/pci/pcie/portdrv_pci.c (ffffffff815a7a20)
Location: include/linux/pm_runtime.h:275
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8188529f)
Location: include/linux/pm_runtime.h:275
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
```
</details>
</li>
</ul>

## Differences

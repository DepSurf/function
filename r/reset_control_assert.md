# Function: <code>reset_control_assert</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int reset_control_assert(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff814df280)
Location: drivers/reset/core.c:106
Inline: False
Direct callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
**Symbols:**

```
ffffffff814df280-ffffffff814df2a8: reset_control_assert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int reset_control_assert(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81530580)
Location: drivers/reset/core.c:162
Inline: True
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
**Symbols:**

```
ffffffff81530580-ffffffff815305eb: reset_control_assert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int reset_control_assert(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8155cb00)
Location: drivers/reset/core.c:186
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
**Symbols:**

```
ffffffff8155cb00-ffffffff8155cbb5: reset_control_assert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int reset_control_assert(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff815715d0)
Location: drivers/reset/core.c:197
Inline: True
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff815715d0-ffffffff81571650: reset_control_assert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int reset_control_assert(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff815d5ab0)
Location: drivers/reset/core.c:272
Inline: True
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff815d5ab0-ffffffff815d5be2: reset_control_assert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int reset_control_assert(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8160e800)
Location: drivers/reset/core.c:302
Inline: True
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff8160e800-ffffffff8160e919: reset_control_assert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int reset_control_assert(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8162b740)
Location: drivers/reset/core.c:302
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff8162b740-ffffffff8162b859: reset_control_assert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int reset_control_assert(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/reset/core.c (ffffffff8165f533)
Location: drivers/reset/core.c:342
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff8165f876-ffffffff8165f8c1: reset_control_assert.cold (STB_LOCAL)
ffffffff8165f500-ffffffff8165f65a: reset_control_assert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int reset_control_assert(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81681c40)
Location: drivers/reset/core.c:341
Inline: True
Direct callers:
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81681c40-ffffffff81681dbc: reset_control_assert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int reset_control_assert(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81733070)
Location: drivers/reset/core.c:343
Inline: True
Direct callers:
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81733070-ffffffff817331e8: reset_control_assert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int reset_control_assert(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8174f230)
Location: drivers/reset/core.c:417
Inline: True
Direct callers:
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff8174f230-ffffffff8174f39b: reset_control_assert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int reset_control_assert(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff817331f0)
Location: drivers/reset/core.c:441
Inline: True
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/reset/core.c:reset_control_bulk_deassert
  - drivers/reset/core.c:reset_control_bulk_assert
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff817331f0-ffffffff8173335f: reset_control_assert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int reset_control_assert(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/reset/core.c (ffffffff817b3972)
Location: drivers/reset/core.c:441
Inline: True
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/reset/core.c:reset_control_bulk_deassert
  - drivers/reset/core.c:reset_control_bulk_assert
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81cf8696-ffffffff81cf86d8: reset_control_assert.cold (STB_LOCAL)
ffffffff817b3930-ffffffff817b3ad5: reset_control_assert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int reset_control_assert(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/reset/core.c (0)
Location: drivers/reset/core.c:442
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/reset/core.c:reset_control_bulk_deassert
  - drivers/reset/core.c:reset_control_deassert
  - drivers/reset/core.c:reset_control_bulk_assert
  - drivers/reset/core.c:reset_control_assert
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81ec07a5-ffffffff81ec07e7: reset_control_assert.cold (STB_LOCAL)
ffffffff818ef720-ffffffff818ef8c7: reset_control_assert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int reset_control_assert(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/reset/core.c (0)
Location: drivers/reset/core.c:442
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/reset/core.c:reset_control_bulk_deassert
  - drivers/reset/core.c:reset_control_deassert
  - drivers/reset/core.c:reset_control_bulk_assert
  - drivers/reset/core.c:reset_control_assert
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff82094f0b-ffffffff82094f4d: reset_control_assert.cold (STB_LOCAL)
ffffffff81a47450-ffffffff81a475f7: reset_control_assert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int reset_control_assert(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/reset/core.c (0)
Location: drivers/reset/core.c:442
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/reset/core.c:reset_control_bulk_deassert
  - drivers/reset/core.c:reset_control_deassert
  - drivers/reset/core.c:reset_control_bulk_assert
  - drivers/reset/core.c:reset_control_assert
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff82115d30-ffffffff82115d72: reset_control_assert.cold (STB_LOCAL)
ffffffff81a91600-ffffffff81a917ac: reset_control_assert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int reset_control_assert(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/reset/core.c (0)
Location: drivers/reset/core.c:442
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/reset/core.c:reset_control_bulk_deassert
  - drivers/reset/core.c:reset_control_deassert
  - drivers/reset/core.c:reset_control_bulk_assert
  - drivers/reset/core.c:reset_control_assert
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff821f3a37-ffffffff821f3a79: reset_control_assert.cold (STB_LOCAL)
ffffffff81ae3f70-ffffffff81ae411c: reset_control_assert (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int reset_control_assert(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffff80001084d048)
Location: drivers/reset/core.c:341
Inline: True
Direct callers:
  - drivers/pinctrl/sunxi/pinctrl-sun6i-a31-r.c:sun6i_a31_r_pinctrl_probe
  - drivers/pinctrl/sunxi/pinctrl-sun8i-a23-r.c:sun8i_a23_r_pinctrl_probe
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_suspend_noirq
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_suspend_noirq
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_assert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_assert_core_reset
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_1_0
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_a80_mmc_config_clk_probe
  - drivers/clk/sunxi-ng/ccu-sun8i-de2.c:sunxi_de2_clk_probe
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_on
  - drivers/tty/serial/8250/8250_dw.c:dw8250_remove
  - drivers/tty/serial/8250/8250_dw.c:dw8250_probe
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_remove
  - drivers/ata/libahci_platform.c:ahci_platform_disable_resources
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/host/mmci_stm32_sdmmc.c:mmci_sdmmc_set_pwrreg
```
**Symbols:**

```
ffff80001084d048-ffff80001084d1f8: reset_control_assert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int reset_control_assert(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (c09594c4)
Location: drivers/reset/core.c:341
Inline: True
Direct callers:
  - arch/arm/mach-meson/platsmp.c:meson8b_smp_boot_secondary
  - arch/arm/mach-meson/platsmp.c:meson8_smp_boot_secondary
  - arch/arm/mach-rockchip/platsmp.c:pmu_set_power_domain
  - drivers/bus/ti-sysc.c:sysc_remove
  - drivers/bus/ti-sysc.c:sysc_probe
  - drivers/bus/ti-sysc.c:sysc_init_module
  - drivers/bus/ti-sysc.c:sysc_runtime_suspend
  - drivers/bus/ti-sysc.c:sysc_runtime_suspend
  - drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_padctl_legacy_remove
  - drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_padctl_legacy_probe
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_suspend
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_suspend
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_power_off
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_suspend_noirq
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_suspend_noirq
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_assert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_assert_core_reset
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_1_0
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_remove
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_probe
  - drivers/clk/tegra/clk-dfll.c:tegra_dfll_unregister
  - drivers/clk/tegra/clk-dfll.c:dfll_init
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_probe
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_on
  - drivers/soc/tegra/pmc.c:tegra_powergate_init
  - drivers/soc/tegra/pmc.c:tegra_genpd_power_off
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_remove
  - drivers/ata/libahci_platform.c:ahci_platform_disable_resources
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/host/mmci_stm32_sdmmc.c:mmci_sdmmc_set_pwrreg
  - drivers/clocksource/dw_apb_timer_of.c:timer_get_base_and_rate
```
**Symbols:**

```
c09594c4-c09596c4: reset_control_assert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int reset_control_assert(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (c0000000008eb5d0)
Location: drivers/reset/core.c:341
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_remove
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
c0000000008eb5d0-c0000000008eb858: reset_control_assert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int reset_control_assert(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffe00052c790)
Location: drivers/reset/core.c:341
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_remove
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffe00052c790-ffffffe00052c8a6: reset_control_assert (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int reset_control_assert(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff816476c0)
Location: drivers/reset/core.c:341
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
**Symbols:**

```
ffffffff816476c0-ffffffff8164783c: reset_control_assert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int reset_control_assert(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81627b20)
Location: drivers/reset/core.c:341
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/net/phy/mdio_device.c:mdio_device_reset
```
**Symbols:**

```
ffffffff81627b20-ffffffff81627c9c: reset_control_assert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int reset_control_assert(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81675a80)
Location: drivers/reset/core.c:341
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81675a80-ffffffff81675bfc: reset_control_assert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int reset_control_assert(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff816900e0)
Location: drivers/reset/core.c:341
Inline: True
Direct callers:
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff816900e0-ffffffff8169025c: reset_control_assert (STB_GLOBAL)
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

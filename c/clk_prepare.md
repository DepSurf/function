# Function: <code>clk_prepare</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int clk_prepare(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816e57b0)
Location: drivers/clk/clk.c:658
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/usb/phy/phy-generic.c:usb_gen_phy_init
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
**Symbols:**

```
ffffffff816e57b0-ffffffff816e57de: clk_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int clk_prepare(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8174a670)
Location: drivers/clk/clk.c:578
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
**Symbols:**

```
ffffffff8174a670-ffffffff8174a69d: clk_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int clk_prepare(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81532ef0)
Location: drivers/clk/clk.c:578
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
**Symbols:**

```
ffffffff81532ef0-ffffffff81532f1d: clk_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int clk_prepare(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81546410)
Location: drivers/clk/clk.c:578
Inline: True
Direct callers:
  - drivers/clk/clk-bulk.c:clk_bulk_prepare
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
  - drivers/i2c/busses/i2c-designware-platdrv.c:i2c_dw_plat_prepare_clk
```
**Symbols:**

```
ffffffff81546410-ffffffff81546448: clk_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int clk_prepare(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815a9730)
Location: drivers/clk/clk.c:641
Inline: True
Direct callers:
  - drivers/clk/clk-bulk.c:clk_bulk_prepare
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
  - drivers/i2c/busses/i2c-designware-platdrv.c:i2c_dw_plat_prepare_clk
```
**Symbols:**

```
ffffffff815a9730-ffffffff815a9768: clk_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int clk_prepare(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815e1e30)
Location: drivers/clk/clk.c:798
Inline: True
Direct callers:
  - drivers/clk/clk-bulk.c:clk_bulk_prepare
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_attach_clk
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_prepare_clk
```
**Symbols:**

```
ffffffff815e1e30-ffffffff815e1e5d: clk_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int clk_prepare(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815fbfe0)
Location: drivers/clk/clk.c:809
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/clk/clk-bulk.c:clk_bulk_prepare
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_attach_clk
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_prepare_clk
```
**Symbols:**

```
ffffffff815fbfe0-ffffffff815fc00d: clk_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int clk_prepare(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8162ec30)
Location: drivers/clk/clk.c:930
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/clk/clk-bulk.c:clk_bulk_prepare
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_attach_clk
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
**Symbols:**

```
ffffffff8162ec30-ffffffff8162ec62: clk_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int clk_prepare(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81650760)
Location: drivers/clk/clk.c:938
Inline: True
Direct callers:
  - drivers/clk/clk-bulk.c:clk_bulk_prepare
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_attach_clk
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
**Symbols:**

```
ffffffff81650760-ffffffff81650792: clk_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int clk_prepare(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81700350)
Location: drivers/clk/clk.c:942
Inline: True
Direct callers:
  - drivers/clk/clk-bulk.c:clk_bulk_prepare
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_attach_clk
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
**Symbols:**

```
ffffffff81700350-ffffffff81700384: clk_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int clk_prepare(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8171d890)
Location: drivers/clk/clk.c:936
Inline: True
Direct callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
  - drivers/clk/clk-bulk.c:clk_bulk_prepare
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_attach_clk
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
**Symbols:**

```
ffffffff8171d890-ffffffff8171d8c4: clk_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int clk_prepare(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816fe920)
Location: drivers/clk/clk.c:936
Inline: True
Direct callers:
  - drivers/clk/clk-bulk.c:clk_bulk_prepare
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/base/power/clock_ops.c:pm_clk_resume
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_attach_clk
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
**Symbols:**

```
ffffffff816fe920-ffffffff816fe954: clk_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int clk_prepare(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81779110)
Location: drivers/clk/clk.c:936
Inline: True
Direct callers:
  - drivers/clk/clk-bulk.c:clk_bulk_prepare
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/base/power/clock_ops.c:pm_clk_resume
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_attach_clk
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
**Symbols:**

```
ffffffff81779110-ffffffff81779144: clk_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int clk_prepare(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff818af410)
Location: drivers/clk/clk.c:948
Inline: True
Direct callers:
  - drivers/clk/clk-bulk.c:clk_bulk_prepare
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/base/power/clock_ops.c:pm_clk_resume
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_attach_clk
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
**Symbols:**

```
ffffffff818af410-ffffffff818af446: clk_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int clk_prepare(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff819fb5e0)
Location: drivers/clk/clk.c:1032
Inline: True
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_get_optional_enabled
  - drivers/clk/clk-devres.c:devm_clk_get_optional_prepared
  - drivers/clk/clk-devres.c:devm_clk_get_enabled
  - drivers/clk/clk-bulk.c:clk_bulk_prepare
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/base/power/clock_ops.c:pm_clk_resume
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_attach_clk
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_gen_context
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
**Symbols:**

```
ffffffff819fb5e0-ffffffff819fb616: clk_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int clk_prepare(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a44090)
Location: drivers/clk/clk.c:1074
Inline: True
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_get_optional_enabled
  - drivers/clk/clk-devres.c:devm_clk_get_optional_prepared
  - drivers/clk/clk-devres.c:devm_clk_get_enabled
  - drivers/clk/clk-bulk.c:clk_bulk_prepare
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/base/power/clock_ops.c:pm_clk_resume
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_attach_clk
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_gen_context
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
**Symbols:**

```
ffffffff81a44090-ffffffff81a440c6: clk_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int clk_prepare(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a8fba0)
Location: drivers/clk/clk.c:1074
Inline: True
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_get_optional_enabled
  - drivers/clk/clk-devres.c:devm_clk_get_optional_prepared
  - drivers/clk/clk-devres.c:devm_clk_get_enabled
  - drivers/clk/clk-bulk.c:clk_bulk_prepare
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/base/power/clock_ops.c:pm_clk_resume
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_attach_clk
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_gen_context
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
**Symbols:**

```
ffffffff81a8fba0-ffffffff81a8fbd6: clk_prepare (STB_GLOBAL)
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
int clk_prepare(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffff8000107c0f08)
Location: drivers/clk/clk.c:938
Inline: True
Direct callers:
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_resume
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_probe
  - drivers/bus/imx-weim.c:weim_probe
  - drivers/bus/qcom-ebi2.c:qcom_ebi2_probe
  - drivers/bus/qcom-ebi2.c:qcom_ebi2_probe
  - drivers/phy/phy-xgene.c:xgene_phy_hw_init
  - drivers/phy/phy-xgene.c:xgene_phy_hw_init
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_pinctrl_probe
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_init_with_variant
  - drivers/gpio/gpio-davinci.c:davinci_gpio_irq_setup
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_resume
  - drivers/gpio/gpio-mxc.c:mxc_gpio_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_resume_noirq
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_post_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_clk_ctrl
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_clk_ctrl
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_clk_ctrl
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_clk_ctrl
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_clk_ctrl
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_probe
  - drivers/video/fbdev/amba-clcd.c:clcdfb_register
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/amba/bus.c:amba_get_enable_pclk
  - drivers/amba/bus.c:amba_pm_runtime_resume
  - drivers/clk/clk-bulk.c:clk_bulk_prepare
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_clk_probe
  - drivers/clk/imx/clk.c:imx_register_uart_clocks
  - drivers/clk/mediatek/clk-mt7622.c:mtk_pericfg_init
  - drivers/clk/mediatek/clk-mt7622.c:mtk_apmixedsys_init
  - drivers/clk/mediatek/clk-mt7622.c:mtk_apmixedsys_init
  - drivers/clk/mediatek/clk-mt7622.c:mtk_apmixedsys_init
  - drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init
  - drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init
  - drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init
  - drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init
  - drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe
  - drivers/clk/rockchip/clk.c:rockchip_clk_protect_critical
  - drivers/clk/rockchip/clk-cpu.c:rockchip_clk_register_cpuclk
  - drivers/clk/sunxi/clk-simple-gates.c:sunxi_simple_gates_setup
  - drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_mmc_reset_deassert
  - drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_mmc_reset_assert
  - drivers/clk/sunxi/clk-usb.c:sunxi_usb_reset_deassert
  - drivers/clk/sunxi/clk-usb.c:sunxi_usb_reset_assert
  - drivers/clk/sunxi-ng/ccu-sun8i-de2.c:sunxi_de2_clk_probe
  - drivers/clk/sunxi-ng/ccu-sun8i-de2.c:sunxi_de2_clk_probe
  - drivers/dma/mv_xor.c:mv_xor_probe
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_probe
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_probe
  - drivers/dma/mxs-dma.c:mxs_dma_probe
  - drivers/dma/mxs-dma.c:mxs_dma_alloc_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_asb_power_on
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_asb_power_on
  - drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pxx_req
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
  - drivers/tty/serial/8250/8250_dw.c:dw8250_runtime_resume
  - drivers/tty/serial/8250/8250_dw.c:dw8250_runtime_resume
  - drivers/tty/serial/8250/8250_dw.c:dw8250_probe
  - drivers/tty/serial/8250/8250_dw.c:dw8250_probe
  - drivers/tty/serial/8250/8250_dw.c:dw8250_set_termios
  - drivers/tty/serial/8250/8250_dw.c:dw8250_set_termios
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_runtime_resume
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_runtime_resume
  - drivers/tty/serial/8250/8250_of.c:of_serial_resume
  - drivers/tty/serial/amba-pl011.c:pl011_console_setup
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/imx.c:imx_uart_freeze
  - drivers/tty/serial/imx.c:imx_uart_suspend
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/imx.c:imx_uart_console_setup
  - drivers/tty/serial/imx.c:imx_uart_console_setup
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/msm_serial.c:msm_console_setup
  - drivers/tty/serial/msm_serial.c:msm_console_setup
  - drivers/tty/serial/msm_serial.c:msm_console_setup
  - drivers/tty/serial/msm_serial.c:msm_startup
  - drivers/tty/serial/msm_serial.c:msm_startup
  - drivers/tty/serial/msm_serial.c:msm_startup
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_probe
  - drivers/iommu/qcom_iommu.c:qcom_iommu_resume
  - drivers/iommu/qcom_iommu.c:qcom_iommu_resume
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_attach_clk
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/ata/ahci_imx.c:imx_ahci_probe
  - drivers/ata/ahci_imx.c:imx_sata_enable
  - drivers/ata/libahci_platform.c:ahci_platform_enable_clks
  - drivers/net/phy/mdio-mux-bcm-iproc.c:mdio_mux_iproc_resume
  - drivers/net/phy/mdio-mux-bcm-iproc.c:mdio_mux_iproc_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_runtime_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_runtime_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe
  - drivers/rtc/rtc-mv.c:mv_rtc_probe
  - drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_probe
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_probe
  - drivers/rtc/rtc-xgene.c:xgene_rtc_resume
  - drivers/rtc/rtc-xgene.c:xgene_rtc_probe
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_runtime_resume
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe
  - drivers/watchdog/rtd119x_wdt.c:rtd119x_wdt_probe
  - drivers/mmc/host/mmci.c:mmci_runtime_resume
  - drivers/mmc/host/mmci.c:mmci_probe
  - drivers/clocksource/timer-of.c:timer_of_init
  - drivers/clocksource/sh_cmt.c:sh_cmt_setup
  - drivers/clocksource/sh_cmt.c:sh_cmt_clock_event_resume
  - drivers/clocksource/sh_tmu.c:sh_tmu_setup
  - drivers/clocksource/timer-sp804.c:sp804_get_clock_rate
  - drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_probe
  - drivers/memory/mtk-smi.c:mtk_smi_common_resume
  - drivers/memory/mtk-smi.c:mtk_smi_common_probe
  - drivers/memory/mtk-smi.c:mtk_smi_larb_resume
```
**Symbols:**

```
ffff8000107c0f08-ffff8000107c0f60: clk_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int clk_prepare(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (c08ec058)
Location: drivers/clk/clk.c:938
Inline: True
Direct callers:
  - arch/arm/kernel/smp_twd.c:twd_local_timer_of_register
  - arch/arm/mach-mvebu/mvebu-soc-id.c:mvebu_soc_id_init
  - arch/arm/mach-mvebu/platsmp.c:armada_xp_sync_secondary_clk
  - arch/arm/mach-imx/system.c:mxc_arch_reset_init
  - arch/arm/mach-imx/mmdc.c:imx_mmdc_probe
  - arch/arm/mach-omap2/display.c:omap_dss_reset
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_resume
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_probe
  - drivers/bus/imx-weim.c:weim_probe
  - drivers/bus/qcom-ebi2.c:qcom_ebi2_probe
  - drivers/bus/qcom-ebi2.c:qcom_ebi2_probe
  - drivers/bus/ti-sysc.c:sysc_get_clocks
  - drivers/phy/marvell/phy-mvebu-sata.c:phy_mvebu_sata_power_off
  - drivers/phy/marvell/phy-mvebu-sata.c:phy_mvebu_sata_power_on
  - drivers/phy/samsung/phy-exynos5250-sata.c:exynos_sata_phy_probe
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_get_soc_data
  - drivers/pinctrl/pinctrl-rzn1.c:rzn1_pinctrl_probe
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_pinctrl_probe
  - drivers/pinctrl/mvebu/pinctrl-dove.c:dove_pinctrl_probe
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_resume
  - drivers/gpio/gpio-mxc.c:mxc_gpio_probe
  - drivers/gpio/gpio-omap.c:omap_gpio_probe
  - drivers/gpio/gpio-vf610.c:vf610_gpio_probe
  - drivers/gpio/gpio-vf610.c:vf610_gpio_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_probe
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_resume_noirq
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_post_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_probe
  - drivers/video/fbdev/amba-clcd.c:clcdfb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/amba/bus.c:amba_get_enable_pclk
  - drivers/amba/bus.c:amba_pm_runtime_resume
  - drivers/clk/clk-bulk.c:clk_bulk_prepare
  - drivers/clk/imx/clk.c:imx_register_uart_clocks
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/mediatek/clk-mt7622.c:mtk_pericfg_init
  - drivers/clk/mediatek/clk-mt7622.c:mtk_apmixedsys_init
  - drivers/clk/mediatek/clk-mt7622.c:mtk_apmixedsys_init
  - drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init
  - drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init
  - drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init
  - drivers/clk/mediatek/clk-mt7629.c:mtk_apmixedsys_init
  - drivers/clk/mediatek/clk-mt7629.c:mtk_apmixedsys_init
  - drivers/clk/mediatek/clk-mt7629.c:mtk_pericfg_init
  - drivers/clk/mediatek/clk-mt7629.c:mtk_topckgen_init
  - drivers/clk/mediatek/clk-mt7629.c:mtk_topckgen_init
  - drivers/clk/mediatek/clk-mt7629.c:mtk_topckgen_init
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe
  - drivers/clk/rockchip/clk.c:rockchip_clk_protect_critical
  - drivers/clk/rockchip/clk-cpu.c:rockchip_clk_register_cpuclk
  - drivers/clk/samsung/clk-exynos5420.c:exynos5x_clk_init
  - drivers/clk/tegra/clk.c:tegra_init_from_table
  - drivers/clk/tegra/clk-dfll.c:dfll_init
  - drivers/clk/tegra/clk-dfll.c:dfll_init
  - drivers/clk/tegra/clk-dfll.c:dfll_init
  - drivers/clk/tegra/clk-emc.c:emc_set_timing
  - drivers/clk/ti/clk.c:omap2_clk_enable_init_clocks
  - drivers/clk/ti/clk-814x.c:dm814x_adpll_enable_init_clocks
  - drivers/clk/ti/clk-7xx.c:dra7xx_dt_clk_init
  - drivers/dma/mv_xor.c:mv_xor_probe
  - drivers/dma/mxs-dma.c:mxs_dma_probe
  - drivers/dma/mxs-dma.c:mxs_dma_alloc_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_runtime_resume
  - drivers/soc/imx/gpc.c:imx6_pm_domain_power_on
  - drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pxx_req
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
  - drivers/soc/tegra/fuse/fuse-tegra30.c:tegra30_fuse_read
  - drivers/soc/tegra/fuse/fuse-tegra20.c:tegra20_fuse_read
  - drivers/soc/tegra/pmc.c:tegra_powergate_enable_clocks
  - drivers/regulator/fixed.c:reg_clock_enable
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_runtime_resume
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_runtime_resume
  - drivers/tty/serial/8250/8250_of.c:of_serial_resume
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_setup
  - drivers/tty/serial/amba-pl011.c:pl011_console_setup
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/imx.c:imx_uart_freeze
  - drivers/tty/serial/imx.c:imx_uart_suspend
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/imx.c:imx_uart_console_setup
  - drivers/tty/serial/imx.c:imx_uart_console_setup
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/msm_serial.c:msm_console_setup
  - drivers/tty/serial/msm_serial.c:msm_console_setup
  - drivers/tty/serial/msm_serial.c:msm_startup
  - drivers/tty/serial/msm_serial.c:msm_startup
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_probe
  - drivers/iommu/exynos-iommu.c:__sysmmu_enable_clocks
  - drivers/iommu/exynos-iommu.c:__sysmmu_enable_clocks
  - drivers/iommu/exynos-iommu.c:__sysmmu_enable_clocks
  - drivers/iommu/exynos-iommu.c:__sysmmu_enable_clocks
  - drivers/iommu/qcom_iommu.c:qcom_iommu_resume
  - drivers/iommu/qcom_iommu.c:qcom_iommu_resume
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_attach_clk
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/t7l66xb.c:t7l66xb_probe
  - drivers/mfd/t7l66xb.c:t7l66xb_resume
  - drivers/mfd/t7l66xb.c:t7l66xb_mmc_enable
  - drivers/mfd/tc6387xb.c:tc6387xb_mmc_enable
  - drivers/mfd/tc6387xb.c:tc6387xb_resume
  - drivers/mfd/tc6393xb.c:tc6393xb_resume
  - drivers/mfd/tc6393xb.c:tc6393xb_probe
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/omap-usb-host.c:usbhs_runtime_resume
  - drivers/mfd/omap-usb-host.c:usbhs_runtime_resume
  - drivers/mfd/omap-usb-host.c:usbhs_runtime_resume
  - drivers/mfd/omap-usb-host.c:usbhs_runtime_resume
  - drivers/mfd/omap-usb-tll.c:usbtll_omap_probe
  - drivers/ata/libahci_platform.c:ahci_platform_enable_clks
  - drivers/ata/ahci_imx.c:imx_ahci_probe
  - drivers/ata/ahci_imx.c:imx_sata_enable
  - drivers/ata/ahci_imx.c:imx8_sata_enable
  - drivers/ata/ahci_imx.c:imx8_sata_enable
  - drivers/ata/ahci_imx.c:imx8_sata_enable
  - drivers/ata/ahci_imx.c:imx8_sata_enable
  - drivers/ata/ahci_imx.c:imx8_sata_enable
  - drivers/net/ethernet/freescale/fec_main.c:fec_runtime_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_runtime_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/ti/cpts.c:cpts_create
  - drivers/usb/phy/phy-generic.c:usb_gen_phy_init
  - drivers/usb/phy/phy-generic.c:nop_set_suspend
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe
  - drivers/usb/host/ehci-exynos.c:exynos_ehci_resume
  - drivers/usb/host/ehci-exynos.c:exynos_ehci_probe
  - drivers/usb/host/ohci-exynos.c:exynos_ohci_resume
  - drivers/usb/host/ohci-exynos.c:exynos_ohci_probe
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_platform_probe
  - drivers/rtc/rtc-mv.c:mv_rtc_probe
  - drivers/rtc/rtc-omap.c:omap_rtc_probe
  - drivers/rtc/rtc-s3c.c:s3c_rtc_probe
  - drivers/rtc/rtc-s3c.c:s3c_rtc_probe
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_probe
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_probe
  - drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_probe
  - drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_probe
  - drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_probe
  - drivers/cpufreq/tegra20-cpufreq.c:tegra_cpu_init
  - drivers/cpufreq/tegra20-cpufreq.c:tegra_target_intermediate
  - drivers/cpufreq/tegra124-cpufreq.c:tegra124_cpufreq_probe
  - drivers/mmc/host/mmci.c:mmci_runtime_resume
  - drivers/mmc/host/mmci.c:mmci_probe
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_resume
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_ios
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_ios
  - drivers/mmc/host/sdhci-pltfm.c:sdhci_pltfm_resume
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_resume
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_resume
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_resume
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe
  - drivers/clocksource/timer-of.c:timer_of_init
  - drivers/clocksource/sh_cmt.c:sh_cmt_setup
  - drivers/clocksource/sh_cmt.c:sh_cmt_clock_event_resume
  - drivers/clocksource/sh_mtu2.c:sh_mtu2_setup
  - drivers/clocksource/renesas-ostm.c:ostm_init
  - drivers/clocksource/sh_tmu.c:sh_tmu_setup
  - drivers/clocksource/em_sti.c:em_sti_probe
  - drivers/clocksource/timer-orion.c:orion_timer_init
  - drivers/clocksource/exynos_mct.c:mct_init_dt
  - drivers/clocksource/arm_global_timer.c:global_timer_of_register
  - drivers/clocksource/timer-sp804.c:sp804_get_clock_rate
  - drivers/clocksource/timer-imx-tpm.c:tpm_timer_init
  - drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_probe
  - drivers/devfreq/exynos-bus.c:exynos_bus_probe
  - drivers/devfreq/event/exynos-nocp.c:exynos_nocp_probe
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_probe
  - drivers/memory/mvebu-devbus.c:mvebu_devbus_probe
  - drivers/memory/mtk-smi.c:mtk_smi_common_resume
  - drivers/memory/mtk-smi.c:mtk_smi_common_probe
  - drivers/memory/mtk-smi.c:mtk_smi_larb_resume
  - sound/soc/codecs/sgtl5000.c:sgtl5000_i2c_probe
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_probe
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_ac97_read
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_ac97_write
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_hw_params
  - sound/soc/fsl/imx-audmux.c:imx_audmux_resume
  - sound/soc/fsl/imx-audmux.c:imx_audmux_suspend
  - sound/soc/fsl/imx-audmux.c:imx_audmux_v2_configure_port
  - sound/soc/fsl/imx-audmux.c:audmux_read_file
```
**Symbols:**

```
c08ec058-c08ec098: clk_prepare (STB_GLOBAL)
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
In drivers/gpio/gpio-ftgpio010.c (c0000000008498d8)
Location: include/linux/clk.h:236
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
```
```
In drivers/pci/controller/pci-ftpci100.c (c0000000008910b4)
Location: include/linux/clk.h:236
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
```
```
In drivers/tty/serial/8250/8250_of.c (c00000000093ac54)
Location: include/linux/clk.h:236
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_of.c:of_serial_resume
```
```
In drivers/tty/serial/max310x.c (c00000000093c058)
Location: include/linux/clk.h:236
Inline: True
```
```
In drivers/tty/serial/sccnxp.c (c00000000093dd4c)
Location: include/linux/clk.h:236
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/base/regmap/regmap-mmio.c (c0000000009c0d7c)
Location: include/linux/clk.h:236
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_attach_clk
```
```
In drivers/misc/sram.c (c0000000009cabac)
Location: include/linux/clk.h:236
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/arizona-core.c (c0000000009d1d58)
Location: include/linux/clk.h:236
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/mfd/twl6040.c (c0000000009e8070)
Location: include/linux/clk.h:236
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/usb/dwc2/platform.c (c000000000afdef4)
Location: include/linux/clk.h:236
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/i2c/busses/i2c-designware-common.c (c000000000b9b90c)
Location: include/linux/clk.h:236
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_prepare_clk
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_prepare_clk
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int clk_prepare(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffe00050ebd0)
Location: drivers/clk/clk.c:938
Inline: True
Direct callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
  - drivers/pwm/pwm-sifive.c:pwm_sifive_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/clk/clk-bulk.c:clk_bulk_prepare
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_attach_clk
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/spi/spi-sifive.c:sifive_spi_probe
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
  - drivers/clocksource/timer-of.c:timer_of_init
```
**Symbols:**

```
ffffffe00050ebd0-ffffffe00050ec20: clk_prepare (STB_GLOBAL)
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
int clk_prepare(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816167c0)
Location: drivers/clk/clk.c:938
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/clk/clk-bulk.c:clk_bulk_prepare
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_attach_clk
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
**Symbols:**

```
ffffffff816167c0-ffffffff816167f2: clk_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int clk_prepare(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8160acf0)
Location: drivers/clk/clk.c:938
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/clk/clk-bulk.c:clk_bulk_prepare
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_attach_clk
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
**Symbols:**

```
ffffffff8160acf0-ffffffff8160ad22: clk_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int clk_prepare(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816445a0)
Location: drivers/clk/clk.c:938
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/clk/clk-bulk.c:clk_bulk_prepare
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_attach_clk
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
**Symbols:**

```
ffffffff816445a0-ffffffff816445d2: clk_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int clk_prepare(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8165ea50)
Location: drivers/clk/clk.c:938
Inline: True
Direct callers:
  - drivers/clk/clk-bulk.c:clk_bulk_prepare
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_attach_clk
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
**Symbols:**

```
ffffffff8165ea50-ffffffff8165ea82: clk_prepare (STB_GLOBAL)
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

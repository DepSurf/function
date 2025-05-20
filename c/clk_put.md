# Function: <code>clk_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void clk_put(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff816e3e60)
Location: drivers/clk/clkdev.c:212
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_add_alias
Direct callers:
  - drivers/base/power/clock_ops.c:__pm_clk_remove
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_free_context
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/clk/clk-devres.c:devm_clk_release
```
**Symbols:**

```
ffffffff816e3e60-ffffffff816e3e70: clk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void clk_put(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff817483a6)
Location: drivers/clk/clkdev.c:212
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_add_alias
Direct callers:
  - drivers/base/power/clock_ops.c:__pm_clk_remove
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_free_context
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/clk/clk-devres.c:devm_clk_release
```
**Symbols:**

```
ffffffff81748190-ffffffff817481a0: clk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void clk_put(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81530c16)
Location: drivers/clk/clkdev.c:212
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_add_alias
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_release
  - drivers/base/power/clock_ops.c:__pm_clk_remove
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_free_context
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
```
**Symbols:**

```
ffffffff81530a00-ffffffff81530a10: clk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void clk_put(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81544108)
Location: drivers/clk/clkdev.c:212
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_add_alias
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_release
  - drivers/clk/clk-bulk.c:clk_bulk_get
  - drivers/base/power/clock_ops.c:__pm_clk_remove
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_free_context
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
```
**Symbols:**

```
ffffffff81543ef0-ffffffff81543f00: clk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void clk_put(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff815a7218)
Location: drivers/clk/clkdev.c:212
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_add_alias
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_release
  - drivers/clk/clk-bulk.c:clk_bulk_get
  - drivers/base/power/clock_ops.c:__pm_clk_remove
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_free_context
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/opp/core.c:dev_pm_opp_put_clkname
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
```
**Symbols:**

```
ffffffff815a7000-ffffffff815a7010: clk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void clk_put(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff815ded9e)
Location: drivers/clk/clkdev.c:212
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_add_alias
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_release
  - drivers/base/power/clock_ops.c:__pm_clk_remove
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_free_context
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/opp/core.c:dev_pm_opp_put_clkname
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
```
**Symbols:**

```
ffffffff815deb80-ffffffff815deb90: clk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void clk_put(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff815f866e)
Location: drivers/clk/clkdev.c:209
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_add_alias
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_release
  - drivers/base/power/clock_ops.c:__pm_clk_remove
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_free_context
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/opp/core.c:dev_pm_opp_put_clkname
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
```
**Symbols:**

```
ffffffff815f84b0-ffffffff815f84c0: clk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void clk_put(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff8162aaff)
Location: drivers/clk/clkdev.c:115
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_add_alias
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_release
  - drivers/clk/clk-bulk.c:__clk_bulk_get
  - drivers/base/power/clock_ops.c:__pm_clk_remove
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_free_context
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/opp/core.c:dev_pm_opp_put_clkname
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
```
**Symbols:**

```
ffffffff8162a4c0-ffffffff8162a4d0: clk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void clk_put(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff8164c5cf)
Location: drivers/clk/clkdev.c:115
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_add_alias
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_release
  - drivers/clk/clk-bulk.c:__clk_bulk_get
  - drivers/base/power/clock_ops.c:__pm_clk_remove
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_free_context
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/opp/core.c:dev_pm_opp_put_clkname
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
```
**Symbols:**

```
ffffffff8164bf80-ffffffff8164bf90: clk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void clk_put(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff816fb5a2)
Location: drivers/clk/clkdev.c:115
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_add_alias
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_release
  - drivers/clk/clk-bulk.c:__clk_bulk_get
  - drivers/base/power/clock_ops.c:__pm_clk_remove
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_free_context
  - drivers/mfd/twl-core.c:clocks_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/opp/core.c:dev_pm_opp_put_clkname
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:_opp_table_kref_release
```
**Symbols:**

```
ffffffff816fb000-ffffffff816fb010: clk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void clk_put(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81717ef2)
Location: drivers/clk/clkdev.c:115
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_add_alias
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_release
  - drivers/clk/clk-bulk.c:__clk_bulk_get
  - drivers/clk/clk.c:devm_clk_release
  - drivers/base/power/clock_ops.c:__pm_clk_remove
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_free_context
  - drivers/mfd/twl-core.c:clocks_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/opp/core.c:dev_pm_opp_put_clkname
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:_opp_table_kref_release
```
**Symbols:**

```
ffffffff81717950-ffffffff81717960: clk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void clk_put(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff816f91e2)
Location: drivers/clk/clkdev.c:115
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_add_alias
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_release
  - drivers/clk/clk-bulk.c:__clk_bulk_get
  - drivers/clk/clk.c:devm_clk_release
  - drivers/base/power/clock_ops.c:__pm_clk_remove
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_free_context
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/opp/core.c:devm_pm_opp_set_clkname
  - drivers/opp/core.c:_opp_table_kref_release
```
**Symbols:**

```
ffffffff816f8c40-ffffffff816f8c50: clk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void clk_put(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81773942)
Location: drivers/clk/clkdev.c:115
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_add_alias
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_release
  - drivers/clk/clk-bulk.c:__clk_bulk_get
  - drivers/clk/clk.c:devm_clk_release
  - drivers/base/power/clock_ops.c:__pm_clk_remove
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_free_context
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/opp/core.c:devm_pm_opp_set_clkname
  - drivers/opp/core.c:_opp_table_kref_release
```
**Symbols:**

```
ffffffff81773400-ffffffff81773410: clk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void clk_put(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff818a92b1)
Location: drivers/clk/clkdev.c:115
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_add_alias
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_release
  - drivers/clk/clk-bulk.c:clk_bulk_put_all
  - drivers/clk/clk-bulk.c:__clk_bulk_get
  - drivers/clk/clk.c:devm_clk_release
  - drivers/base/power/clock_ops.c:__pm_clk_remove
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_free_context
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/opp/core.c:devm_pm_opp_set_clkname
  - drivers/opp/core.c:_opp_table_kref_release
```
**Symbols:**

```
ffffffff818a8cd0-ffffffff818a8ce6: clk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void clk_put(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff819f3f2d)
Location: drivers/clk/clkdev.c:115
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_add_alias
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_get_optional_enabled
  - drivers/clk/clk-devres.c:devm_clk_get_optional_enabled
  - drivers/clk/clk-devres.c:devm_clk_get_optional_prepared
  - drivers/clk/clk-devres.c:devm_clk_get_enabled
  - drivers/clk/clk-devres.c:devm_clk_get_enabled
  - drivers/clk/clk-devres.c:devm_clk_release
  - drivers/clk/clk-bulk.c:clk_bulk_put_all
  - drivers/clk/clk-bulk.c:__clk_bulk_get
  - drivers/clk/clk.c:devm_clk_release
  - drivers/base/power/clock_ops.c:__pm_clk_remove
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_gen_context
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_free_context
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/opp/core.c:dev_pm_opp_set_config
  - drivers/opp/core.c:_opp_clear_config
  - drivers/opp/core.c:_opp_table_kref_release
```
**Symbols:**

```
ffffffff819f3770-ffffffff819f3786: clk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void clk_put(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81a3c5ed)
Location: drivers/clk/clkdev.c:115
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_add_alias
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_get_optional_enabled
  - drivers/clk/clk-devres.c:devm_clk_get_optional_enabled
  - drivers/clk/clk-devres.c:devm_clk_get_optional_prepared
  - drivers/clk/clk-devres.c:devm_clk_get_enabled
  - drivers/clk/clk-devres.c:devm_clk_get_enabled
  - drivers/clk/clk-devres.c:devm_clk_release
  - drivers/clk/clk-bulk.c:clk_bulk_put_all
  - drivers/clk/clk-bulk.c:__clk_bulk_get
  - drivers/clk/clk.c:devm_clk_release
  - drivers/base/power/clock_ops.c:__pm_clk_remove
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_gen_context
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_free_context
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/opp/core.c:dev_pm_opp_set_config
  - drivers/opp/core.c:_opp_clear_config
  - drivers/opp/core.c:_opp_table_kref_release
```
**Symbols:**

```
ffffffff81a3be20-ffffffff81a3be36: clk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void clk_put(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81a87ead)
Location: drivers/clk/clkdev.c:115
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_add_alias
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_get_optional_enabled
  - drivers/clk/clk-devres.c:devm_clk_get_optional_enabled
  - drivers/clk/clk-devres.c:devm_clk_get_optional_prepared
  - drivers/clk/clk-devres.c:devm_clk_get_enabled
  - drivers/clk/clk-devres.c:devm_clk_get_enabled
  - drivers/clk/clk-devres.c:devm_clk_release
  - drivers/clk/clk-bulk.c:clk_bulk_put_all
  - drivers/clk/clk-bulk.c:__clk_bulk_get
  - drivers/clk/clk.c:devm_clk_release
  - drivers/base/power/clock_ops.c:__pm_clk_remove
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_gen_context
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_free_context
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/opp/core.c:dev_pm_opp_set_config
  - drivers/opp/core.c:_opp_clear_config
  - drivers/opp/core.c:_opp_table_kref_release
```
**Symbols:**

```
ffffffff81a876e0-ffffffff81a876f6: clk_put (STB_GLOBAL)
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
void clk_put(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffff8000107bb390)
Location: drivers/clk/clkdev.c:115
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_add_alias
Direct callers:
  - drivers/video/fbdev/amba-clcd.c:clcdfb_remove
  - drivers/video/fbdev/amba-clcd.c:clcdfb_register
  - drivers/video/fbdev/mx3fb.c:sdc_init_panel
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/amba/bus.c:amba_get_enable_pclk
  - drivers/amba/bus.c:amba_get_enable_pclk
  - drivers/clk/clk-devres.c:devm_clk_release
  - drivers/clk/clk-bulk.c:clk_bulk_get_all
  - drivers/clk/clk-bulk.c:__clk_bulk_get
  - drivers/clk/clk.c:of_clk_init
  - drivers/clk/clk.c:of_clk_get_parent_name
  - drivers/clk/mvebu/armada-37xx-tbg.c:armada_3700_tbg_clock_probe
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_attach_dev
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_attach_dev
  - drivers/dma/mv_xor.c:mv_xor_probe
  - drivers/dma/ipu/ipu_idmac.c:ipu_remove
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
  - drivers/soc/imx/gpcv2.c:imx_pgc_domain_remove
  - drivers/soc/imx/gpcv2.c:imx_pgc_domain_probe
  - drivers/soc/imx/gpcv2.c:imx_pgc_domain_probe
  - drivers/soc/imx/gpcv2.c:imx_pgc_domain_probe
  - drivers/soc/rockchip/pm_domains.c:rockchip_pd_attach_dev
  - drivers/base/power/clock_ops.c:__pm_clk_remove
  - drivers/base/power/clock_ops.c:of_pm_clk_add_clks
  - drivers/base/power/clock_ops.c:of_pm_clk_add_clk
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_free_context
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/syscon.c:of_syscon_register
  - drivers/ata/libahci_platform.c:ahci_platform_put_resources
  - drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_remove
  - drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_probe
  - drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_probe
  - drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/opp/core.c:dev_pm_opp_put_clkname
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
  - drivers/cpufreq/cpufreq-dt.c:cpufreq_exit
  - drivers/cpufreq/cpufreq-dt.c:cpufreq_init
  - drivers/clocksource/timer-of.c:timer_of_cleanup
  - drivers/clocksource/timer-of.c:timer_of_init
  - drivers/clocksource/timer-of.c:timer_of_init
  - drivers/clocksource/sh_cmt.c:sh_cmt_setup
  - drivers/clocksource/sh_tmu.c:sh_tmu_setup
  - drivers/clocksource/timer-sp804.c:sp804_get_clock_rate
  - drivers/clocksource/timer-sp804.c:sp804_get_clock_rate
  - drivers/clocksource/timer-sp804.c:sp804_get_clock_rate
```
**Symbols:**

```
ffff8000107babe8-ffff8000107bac14: clk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void clk_put(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (c08e720c)
Location: drivers/clk/clkdev.c:115
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_add_alias
Direct callers:
  - arch/arm/kernel/smp_twd.c:twd_local_timer_of_register
  - arch/arm/mach-mvebu/mvebu-soc-id.c:mvebu_soc_id_init
  - arch/arm/mach-imx/mach-imx6q.c:imx6q_init_machine
  - arch/arm/mach-imx/mach-imx6q.c:imx6q_init_machine
  - arch/arm/mach-omap2/io.c:omap_sdrc_init
  - arch/arm/mach-omap2/timer.c:omap_dm_timer_init_one
  - arch/arm/mach-omap2/voltage.c:omap_voltage_late_init
  - drivers/bus/ti-sysc.c:sysc_notifier_call
  - drivers/bus/ti-sysc.c:sysc_notifier_call
  - drivers/bus/ti-sysc.c:sysc_get_clocks
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_probe
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_port_clk_put
  - drivers/video/fbdev/amba-clcd.c:clcdfb_remove
  - drivers/video/fbdev/amba-clcd.c:clcdfb_probe
  - drivers/video/fbdev/mx3fb.c:__set_par
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/amba/bus.c:amba_put_disable_pclk
  - drivers/amba/bus.c:amba_get_enable_pclk
  - drivers/amba/bus.c:amba_get_enable_pclk
  - drivers/clk/clk-devres.c:devm_clk_release
  - drivers/clk/clk-bulk.c:clk_bulk_get_all
  - drivers/clk/clk-bulk.c:__clk_bulk_get
  - drivers/clk/clk.c:of_clk_init
  - drivers/clk/clk.c:of_clk_get_parent_name
  - drivers/clk/berlin/bg2.c:berlin2_clock_setup
  - drivers/clk/berlin/bg2.c:berlin2_clock_setup
  - drivers/clk/berlin/bg2q.c:berlin2q_clock_setup
  - drivers/clk/mvebu/common.c:mvebu_clk_gating_setup
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_attach_dev
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_attach_dev
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_attach_dev
  - drivers/clk/renesas/clk-mstp.c:cpg_mstp_attach_dev
  - drivers/clk/samsung/clk-exynos-clkout.c:exynos_clkout_init
  - drivers/clk/tegra/clk-emc.c:tegra_clk_register_emc
  - drivers/clk/ti/fapll.c:ti_fapll_setup
  - drivers/clk/ti/fapll.c:ti_fapll_setup
  - drivers/dma/mv_xor.c:mv_xor_probe
  - drivers/dma/ipu/ipu_idmac.c:ipu_remove
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
  - drivers/soc/imx/gpc.c:imx_gpc_probe
  - drivers/soc/imx/gpc.c:imx_pgc_power_domain_remove
  - drivers/soc/imx/gpc.c:imx_pgc_power_domain_probe
  - drivers/soc/imx/gpcv2.c:imx_pgc_domain_remove
  - drivers/soc/imx/gpcv2.c:imx_pgc_domain_probe
  - drivers/soc/imx/gpcv2.c:imx_pgc_domain_probe
  - drivers/soc/imx/gpcv2.c:imx_pgc_domain_probe
  - drivers/soc/rockchip/pm_domains.c:rockchip_pd_attach_dev
  - drivers/soc/tegra/pmc.c:tegra_powergate_init
  - drivers/soc/tegra/pmc.c:tegra_powergate_init
  - drivers/base/power/clock_ops.c:__pm_clk_remove
  - drivers/base/power/clock_ops.c:of_pm_clk_add_clks
  - drivers/base/power/clock_ops.c:of_pm_clk_add_clk
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_free_context
  - drivers/mfd/t7l66xb.c:t7l66xb_remove
  - drivers/mfd/t7l66xb.c:t7l66xb_remove
  - drivers/mfd/t7l66xb.c:t7l66xb_probe
  - drivers/mfd/t7l66xb.c:t7l66xb_probe
  - drivers/mfd/tc6387xb.c:tc6387xb_remove
  - drivers/mfd/tc6387xb.c:tc6387xb_probe
  - drivers/mfd/tc6393xb.c:tc6393xb_remove
  - drivers/mfd/tc6393xb.c:tc6393xb_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/omap-usb-tll.c:usbtll_omap_remove
  - drivers/mfd/syscon.c:of_syscon_register
  - drivers/ata/libahci_platform.c:ahci_platform_put_resources
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/power/avs/smartreflex.c:sr_set_clk_length
  - drivers/opp/core.c:dev_pm_opp_put_clkname
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
  - drivers/cpufreq/cpufreq-dt.c:cpufreq_exit
  - drivers/cpufreq/cpufreq-dt.c:cpufreq_init
  - drivers/cpufreq/mvebu-cpufreq.c:armada_xp_pmsu_cpufreq_init
  - drivers/cpufreq/mvebu-cpufreq.c:armada_xp_pmsu_cpufreq_init
  - drivers/cpufreq/mvebu-cpufreq.c:armada_xp_pmsu_cpufreq_init
  - drivers/cpufreq/omap-cpufreq.c:omap_cpu_exit
  - drivers/cpufreq/omap-cpufreq.c:omap_cpu_init
  - drivers/cpufreq/tegra20-cpufreq.c:tegra20_cpufreq_remove
  - drivers/cpufreq/tegra20-cpufreq.c:tegra20_cpufreq_remove
  - drivers/cpufreq/tegra20-cpufreq.c:tegra20_cpufreq_remove
  - drivers/cpufreq/tegra20-cpufreq.c:tegra20_cpufreq_probe
  - drivers/cpufreq/tegra20-cpufreq.c:tegra20_cpufreq_probe
  - drivers/cpufreq/tegra20-cpufreq.c:tegra20_cpufreq_probe
  - drivers/cpufreq/tegra124-cpufreq.c:tegra124_cpufreq_probe
  - drivers/cpufreq/tegra124-cpufreq.c:tegra124_cpufreq_probe
  - drivers/cpufreq/tegra124-cpufreq.c:tegra124_cpufreq_probe
  - drivers/cpufreq/tegra124-cpufreq.c:tegra124_cpufreq_probe
  - drivers/clocksource/timer-of.c:timer_of_cleanup
  - drivers/clocksource/timer-of.c:timer_of_init
  - drivers/clocksource/timer-of.c:timer_of_init
  - drivers/clocksource/sh_cmt.c:sh_cmt_setup
  - drivers/clocksource/sh_mtu2.c:sh_mtu2_setup
  - drivers/clocksource/sh_tmu.c:sh_tmu_setup
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_free
  - drivers/clocksource/timer-ti-dm.c:_omap_dm_timer_request
  - drivers/clocksource/timer-ti-dm.c:_omap_dm_timer_request
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_source
  - drivers/clocksource/timer-sp804.c:sp804_get_clock_rate
  - drivers/clocksource/timer-sp804.c:sp804_get_clock_rate
  - drivers/clocksource/timer-sp804.c:sp804_get_clock_rate
  - drivers/clocksource/timer-imx-tpm.c:tpm_timer_init
  - drivers/memory/tegra/tegra20-emc.c:tegra_emc_probe
  - drivers/memory/tegra/tegra20-emc.c:tegra_emc_probe
  - sound/soc/fsl/imx-sgtl5000.c:imx_sgtl5000_remove
  - sound/soc/fsl/imx-sgtl5000.c:imx_sgtl5000_probe
```
**Symbols:**

```
c08e6c3c-c08e6c58: clk_put (STB_GLOBAL)
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
In drivers/base/regmap/regmap-mmio.c (0)
Location: include/linux/clk.h:804
Inline: True
```
```
In drivers/mfd/twl-core.c (0)
Location: include/linux/clk.h:804
Inline: True
```
```
In drivers/mfd/syscon.c (0)
Location: include/linux/clk.h:804
Inline: True
```
```
In drivers/opp/core.c (0)
Location: include/linux/clk.h:804
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void clk_put(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffe00050a1f8)
Location: drivers/clk/clkdev.c:115
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_add_alias
Direct callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/clk/clk-devres.c:devm_clk_release
  - drivers/clk/clk-bulk.c:clk_bulk_get_all
  - drivers/clk/clk-bulk.c:__clk_bulk_get
  - drivers/clk/clk.c:of_clk_init
  - drivers/clk/clk.c:of_clk_get_parent_name
  - drivers/base/power/clock_ops.c:__pm_clk_remove
  - drivers/base/power/clock_ops.c:of_pm_clk_add_clks
  - drivers/base/power/clock_ops.c:of_pm_clk_add_clk
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_free_context
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/syscon.c:of_syscon_register
  - drivers/opp/core.c:dev_pm_opp_put_clkname
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
  - drivers/clocksource/timer-of.c:timer_of_cleanup
  - drivers/clocksource/timer-of.c:timer_of_init
  - drivers/clocksource/timer-of.c:timer_of_init
```
**Symbols:**

```
ffffffe000509c76-ffffffe000509ca0: clk_put (STB_GLOBAL)
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
void clk_put(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff8161262f)
Location: drivers/clk/clkdev.c:115
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_add_alias
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_release
  - drivers/clk/clk-bulk.c:__clk_bulk_get
  - drivers/base/power/clock_ops.c:__pm_clk_remove
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_free_context
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/opp/core.c:dev_pm_opp_put_clkname
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
```
**Symbols:**

```
ffffffff81611fe0-ffffffff81611ff0: clk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void clk_put(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81606b7f)
Location: drivers/clk/clkdev.c:115
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_add_alias
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_release
  - drivers/clk/clk-bulk.c:__clk_bulk_get
  - drivers/base/power/clock_ops.c:__pm_clk_remove
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_free_context
  - drivers/opp/core.c:dev_pm_opp_put_clkname
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
```
**Symbols:**

```
ffffffff81606530-ffffffff81606540: clk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void clk_put(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff8164040f)
Location: drivers/clk/clkdev.c:115
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_add_alias
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_release
  - drivers/clk/clk-bulk.c:__clk_bulk_get
  - drivers/base/power/clock_ops.c:__pm_clk_remove
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_free_context
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/opp/core.c:dev_pm_opp_put_clkname
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
```
**Symbols:**

```
ffffffff8163fdc0-ffffffff8163fdd0: clk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void clk_put(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff8165a75f)
Location: drivers/clk/clkdev.c:115
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_add_alias
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_release
  - drivers/clk/clk-bulk.c:__clk_bulk_get
  - drivers/base/power/clock_ops.c:__pm_clk_remove
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_free_context
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/opp/core.c:dev_pm_opp_put_clkname
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
```
**Symbols:**

```
ffffffff8165a110-ffffffff8165a120: clk_put (STB_GLOBAL)
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

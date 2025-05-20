# Function: <code>of_node_name_eq</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/imsttfb.c (0)
Location: include/linux/of.h:575
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (0)
Location: include/linux/of.h:575
Inline: True
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
In drivers/video/fbdev/imsttfb.c (0)
Location: include/linux/of.h:575
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (0)
Location: include/linux/of.h:575
Inline: True
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
In drivers/video/fbdev/imsttfb.c (0)
Location: include/linux/of.h:577
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (0)
Location: include/linux/of.h:577
Inline: True
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
In drivers/video/fbdev/imsttfb.c (0)
Location: include/linux/of.h:579
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (0)
Location: include/linux/of.h:579
Inline: True
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
In drivers/video/fbdev/imsttfb.c (0)
Location: include/linux/of.h:594
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (0)
Location: include/linux/of.h:594
Inline: True
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
In drivers/video/fbdev/imsttfb.c (0)
Location: include/linux/of.h:594
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (0)
Location: include/linux/of.h:594
Inline: True
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
In drivers/video/fbdev/imsttfb.c (0)
Location: include/linux/of.h:462
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (0)
Location: include/linux/of.h:462
Inline: True
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
In drivers/video/fbdev/imsttfb.c (0)
Location: include/linux/of.h:460
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (0)
Location: include/linux/of.h:460
Inline: True
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
In drivers/video/fbdev/imsttfb.c (0)
Location: include/linux/of.h:472
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (0)
Location: include/linux/of.h:472
Inline: True
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
In drivers/video/fbdev/imsttfb.c (0)
Location: include/linux/of.h:471
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (0)
Location: include/linux/of.h:471
Inline: True
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
bool of_node_name_eq(const struct device_node *np, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffff800010b68300)
Location: drivers/of/base.c:58
Inline: False
Direct callers:
  - drivers/pci/of.c:of_pci_find_child_device
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/max77620.c:max77620_initialise_fps
  - drivers/spi/spi.c:of_register_spi_device
  - drivers/of/base.c:of_find_node_by_name
  - drivers/of/base.c:of_find_node_by_name
  - drivers/of/base.c:of_get_child_by_name
  - drivers/of/base.c:of_get_next_cpu_node
  - drivers/of/base.c:__of_device_is_compatible
  - drivers/of/property.c:of_fwnode_graph_get_port_parent
  - drivers/of/property.c:of_fwnode_get_named_child_node
  - drivers/of/property.c:of_graph_get_next_endpoint
  - drivers/of/property.c:of_graph_get_port_by_id
  - drivers/of/address.c:of_bus_isa_match
  - drivers/of/resolver.c:of_resolve_phandles
  - drivers/of/resolver.c:of_resolve_phandles
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_edev_by_phandle
```
**Symbols:**

```
ffff800010b68300-ffff800010b683a8: of_node_name_eq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool of_node_name_eq(const struct device_node *np, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c0c4c2c0)
Location: drivers/of/base.c:58
Inline: False
Direct callers:
  - fs/pstore/ram.c:ramoops_probe
  - drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinctrl_probe
  - drivers/pci/of.c:of_pci_find_child_device
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/clk/renesas/clk-mstp.c:cpg_mstp_attach_dev
  - drivers/clk/ti/dpll.c:of_ti_omap3_dpll_setup
  - drivers/clk/ti/clkctrl.c:_ti_omap4_clkctrl_setup
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/max77620.c:max77620_initialise_fps
  - drivers/spi/spi.c:of_register_spi_device
  - drivers/net/ethernet/ti/cpsw.c:cpsw_remove_dt
  - drivers/net/ethernet/ti/cpsw.c:cpsw_probe_dt
  - drivers/of/base.c:of_find_node_by_name
  - drivers/of/base.c:of_get_child_by_name
  - drivers/of/base.c:of_get_next_cpu_node
  - drivers/of/base.c:__of_device_is_compatible
  - drivers/of/property.c:of_fwnode_graph_get_port_parent
  - drivers/of/property.c:of_fwnode_get_named_child_node
  - drivers/of/property.c:of_graph_get_next_endpoint
  - drivers/of/property.c:of_graph_get_port_by_id
  - drivers/of/address.c:of_bus_isa_match
  - drivers/of/resolver.c:of_resolve_phandles
  - drivers/of/resolver.c:of_resolve_phandles
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_edev_by_phandle
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_probe
  - drivers/memory/omap-gpmc.c:gpmc_probe_generic_child
  - drivers/memory/omap-gpmc.c:gpmc_probe_generic_child
  - drivers/memory/omap-gpmc.c:gpmc_probe_generic_child
```
**Symbols:**

```
c0c4c2c0-c0c4c340: of_node_name_eq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool of_node_name_eq(const struct device_node *np, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c000000000c40a40)
Location: drivers/of/base.c:58
Inline: False
Direct callers:
  - arch/powerpc/kernel/legacy_serial.c:find_legacy_serial_ports
  - arch/powerpc/kernel/legacy_serial.c:find_legacy_serial_ports
  - arch/powerpc/kernel/legacy_serial.c:find_legacy_serial_ports
  - arch/powerpc/kernel/legacy_serial.c:find_legacy_serial_ports
  - arch/powerpc/platforms/powernv/opal.c:opal_init
  - arch/powerpc/platforms/pseries/setup.c:pseries_init_irq
  - drivers/pci/of.c:of_pci_find_child_device
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/offb.c:offb_init_nodriver
  - drivers/tty/hvc/hvc_opal.c:hvc_opal_init_early
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/max77620.c:max77620_initialise_fps
  - drivers/spi/spi.c:of_register_spi_device
  - drivers/of/base.c:of_find_node_by_name
  - drivers/of/base.c:of_get_child_by_name
  - drivers/of/base.c:of_get_next_cpu_node
  - drivers/of/base.c:__of_device_is_compatible
  - drivers/of/property.c:of_fwnode_graph_get_port_parent
  - drivers/of/property.c:of_fwnode_get_named_child_node
  - drivers/of/property.c:of_graph_get_next_endpoint
  - drivers/of/property.c:of_graph_get_port_by_id
  - drivers/of/address.c:of_bus_isa_match
  - drivers/of/resolver.c:of_resolve_phandles
  - drivers/of/resolver.c:of_resolve_phandles
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_edev_by_phandle
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_edev_by_phandle
```
**Symbols:**

```
c000000000c40a40-c000000000c40b0c: of_node_name_eq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool of_node_name_eq(const struct device_node *np, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffffffe00071e5bc)
Location: drivers/of/base.c:58
Inline: False
Direct callers:
  - drivers/pci/of.c:of_pci_find_child_device
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/max77620.c:max77620_initialise_fps
  - drivers/spi/spi.c:of_register_spi_device
  - drivers/of/base.c:of_find_node_by_name
  - drivers/of/base.c:of_find_node_by_name
  - drivers/of/base.c:of_get_child_by_name
  - drivers/of/base.c:of_get_next_cpu_node
  - drivers/of/base.c:__of_device_is_compatible
  - drivers/of/property.c:of_fwnode_graph_get_port_parent
  - drivers/of/property.c:of_fwnode_get_named_child_node
  - drivers/of/property.c:of_graph_get_next_endpoint
  - drivers/of/property.c:of_graph_get_port_by_id
  - drivers/of/address.c:of_bus_isa_match
  - drivers/of/resolver.c:of_resolve_phandles
  - drivers/of/resolver.c:of_resolve_phandles
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_edev_by_phandle
  - drivers/devfreq/devfreq-event.c:devfreq_event_get_edev_by_phandle
```
**Symbols:**

```
ffffffe00071e5bc-ffffffe00071e644: of_node_name_eq (STB_GLOBAL)
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
In drivers/video/fbdev/imsttfb.c (0)
Location: include/linux/of.h:575
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (0)
Location: include/linux/of.h:575
Inline: True
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
In drivers/devfreq/devfreq-event.c (0)
Location: include/linux/of.h:575
Inline: True
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
In drivers/video/fbdev/imsttfb.c (0)
Location: include/linux/of.h:575
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (0)
Location: include/linux/of.h:575
Inline: True
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
In drivers/video/fbdev/imsttfb.c (0)
Location: include/linux/of.h:575
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (0)
Location: include/linux/of.h:575
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>

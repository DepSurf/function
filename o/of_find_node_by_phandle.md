# Function: <code>of_find_node_by_phandle</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct device_node *of_find_node_by_phandle(phandle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffff800010b6a030)
Location: drivers/of/base.c:1222
Inline: False
Direct callers:
  - drivers/irqchip/irq-gic-v3.c:gic_populate_ppi_partitions
  - drivers/irqchip/irq-gic-v3.c:partition_domain_translate
  - drivers/pinctrl/devicetree.c:pinctrl_dt_to_map
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_parse_functions
  - drivers/of/base.c:of_map_rid
  - drivers/of/base.c:of_parse_phandle_with_args_map
  - drivers/of/base.c:of_phandle_iterator_next
  - drivers/of/irq.c:of_irq_parse_raw
  - drivers/of/overlay.c:init_overlay_changeset
  - drivers/remoteproc/remoteproc_core.c:rproc_get_by_phandle
```
**Symbols:**

```
ffff800010b6a030-ffff800010b6a1ac: of_find_node_by_phandle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct device_node *of_find_node_by_phandle(phandle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c0c4cfe8)
Location: drivers/of/base.c:1222
Inline: False
Direct callers:
  - drivers/irqchip/irq-gic-v3.c:gic_populate_ppi_partitions
  - drivers/irqchip/irq-gic-v3.c:partition_domain_translate
  - drivers/irqchip/irq-renesas-rza1.c:rza1_irqc_probe
  - drivers/bus/mvebu-mbus.c:mvebu_mbus_dt_init
  - drivers/pinctrl/devicetree.c:pinctrl_dt_to_map
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_parse_dt
  - drivers/net/ethernet/ti/cpsw.c:cpsw_probe_dt
  - drivers/of/base.c:of_map_rid
  - drivers/of/base.c:of_parse_phandle_with_args_map
  - drivers/of/base.c:of_phandle_iterator_next
  - drivers/of/irq.c:of_irq_parse_raw
  - drivers/of/overlay.c:init_overlay_changeset
  - drivers/remoteproc/remoteproc_core.c:rproc_get_by_phandle
```
**Symbols:**

```
c0c4cfe8-c0c4d10c: of_find_node_by_phandle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct device_node *of_find_node_by_phandle(phandle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c000000000c427a0)
Location: drivers/of/base.c:1222
Inline: False
Direct callers:
  - arch/powerpc/platforms/pseries/mobility.c:pseries_devicetree_update
  - arch/powerpc/platforms/pseries/mobility.c:pseries_devicetree_update
  - arch/powerpc/platforms/pseries/mobility.c:pseries_devicetree_update
  - arch/powerpc/platforms/pseries/mobility.c:pseries_devicetree_update
  - drivers/pinctrl/devicetree.c:pinctrl_dt_to_map
  - drivers/vfio/pci/vfio_pci_nvlink2.c:vfio_pci_nvdia_v100_nvlink2_init
  - drivers/of/base.c:of_map_rid
  - drivers/of/base.c:of_parse_phandle_with_args_map
  - drivers/of/base.c:of_phandle_iterator_next
  - drivers/of/irq.c:of_irq_parse_raw
  - drivers/of/overlay.c:init_overlay_changeset
  - drivers/remoteproc/remoteproc_core.c:rproc_get_by_phandle
```
**Symbols:**

```
c000000000c427a0-c000000000c42958: of_find_node_by_phandle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct device_node *of_find_node_by_phandle(phandle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffffffe00071f256)
Location: drivers/of/base.c:1222
Inline: False
Direct callers:
  - drivers/pinctrl/devicetree.c:pinctrl_dt_to_map
  - drivers/of/base.c:of_map_rid
  - drivers/of/base.c:of_parse_phandle_with_args_map
  - drivers/of/base.c:of_phandle_iterator_next
  - drivers/of/irq.c:of_irq_parse_raw
  - drivers/of/overlay.c:init_overlay_changeset
```
**Symbols:**

```
ffffffe00071f256-ffffffe00071f35a: of_find_node_by_phandle (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>

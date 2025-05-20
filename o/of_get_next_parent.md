# Function: <code>of_get_next_parent</code>

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
struct device_node *of_get_next_parent(struct device_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffff800010b69760)
Location: drivers/of/base.c:712
Inline: False
Direct callers:
  - drivers/bus/vexpress-config.c:vexpress_config_find_prop
  - drivers/pinctrl/devicetree.c:pinctrl_dt_to_map
  - drivers/pinctrl/devicetree.c:pinctrl_dt_to_map
  - drivers/of/property.c:of_fwnode_graph_get_port_parent
  - drivers/of/property.c:of_graph_get_remote_port
  - drivers/of/address.c:of_dma_is_coherent
  - drivers/of/of_numa.c:of_node_to_nid
  - drivers/nvmem/core.c:of_nvmem_cell_get
```
**Symbols:**

```
ffff800010b69760-ffff800010b69848: of_get_next_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct device_node *of_get_next_parent(struct device_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c0c4c59c)
Location: drivers/of/base.c:712
Inline: False
Direct callers:
  - drivers/bus/vexpress-config.c:vexpress_config_find_prop
  - drivers/pinctrl/devicetree.c:pinctrl_dt_to_map
  - drivers/pinctrl/devicetree.c:pinctrl_dt_to_map
  - drivers/of/property.c:of_fwnode_graph_get_port_parent
  - drivers/of/property.c:of_graph_get_remote_port
  - drivers/of/address.c:of_dma_is_coherent
  - drivers/nvmem/core.c:of_nvmem_cell_get
```
**Symbols:**

```
c0c4c59c-c0c4c5f4: of_get_next_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct device_node *of_get_next_parent(struct device_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c000000000c40ec0)
Location: drivers/of/base.c:712
Inline: False
Direct callers:
  - arch/powerpc/kernel/prom.c:of_get_ibm_chip_id
  - arch/powerpc/mm/numa.c:of_node_to_nid
  - arch/powerpc/platforms/pseries/pci.c:pseries_root_bridge_prepare
  - arch/powerpc/platforms/pseries/msi.c:msi_quota_for_device
  - drivers/pinctrl/devicetree.c:pinctrl_dt_to_map
  - drivers/pinctrl/devicetree.c:pinctrl_dt_to_map
  - drivers/of/property.c:of_fwnode_graph_get_port_parent
  - drivers/of/property.c:of_graph_get_remote_port
  - drivers/nvmem/core.c:of_nvmem_cell_get
```
**Symbols:**

```
c000000000c40ec0-c000000000c40f74: of_get_next_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct device_node *of_get_next_parent(struct device_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffffffe00071e8da)
Location: drivers/of/base.c:712
Inline: False
Direct callers:
  - drivers/pinctrl/devicetree.c:pinctrl_dt_to_map
  - drivers/pinctrl/devicetree.c:pinctrl_dt_to_map
  - drivers/of/property.c:of_fwnode_graph_get_port_parent
  - drivers/of/property.c:of_graph_get_remote_port
  - drivers/of/address.c:of_dma_is_coherent
  - drivers/nvmem/core.c:of_nvmem_cell_get
```
**Symbols:**

```
ffffffe00071e8da-ffffffe00071e94e: of_get_next_parent (STB_GLOBAL)
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

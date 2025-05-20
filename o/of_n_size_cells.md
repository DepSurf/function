# Function: <code>of_n_size_cells</code>

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
int of_n_size_cells(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffff800010b684d8)
Location: drivers/of/base.c:104
Inline: False
Direct callers:
  - drivers/bus/fsl-mc/fsl-mc-bus.c:fsl_mc_bus_probe
  - drivers/iommu/of_iommu.c:of_get_dma_window
  - drivers/of/address.c:of_dma_get_range
  - drivers/of/address.c:of_bus_default_count_cells
```
**Symbols:**

```
ffff800010b684d8-ffff800010b68590: of_n_size_cells (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_n_size_cells(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c0c4c444)
Location: drivers/of/base.c:104
Inline: False
Direct callers:
  - drivers/iommu/of_iommu.c:of_get_dma_window
  - drivers/mtd/parsers/ofpart.c:parse_fixed_partitions
  - drivers/of/address.c:of_dma_get_range
  - drivers/of/address.c:of_bus_default_count_cells
```
**Symbols:**

```
c0c4c444-c0c4c4ec: of_n_size_cells (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_n_size_cells(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c000000000c40c90)
Location: drivers/of/base.c:104
Inline: False
Direct callers:
  - arch/powerpc/kernel/setup-common.c:smp_setup_cpu_maps
  - arch/powerpc/kernel/prom_parse.c:of_parse_dma_window
  - arch/powerpc/kernel/ima_kexec.c:get_addr_size_cells
  - arch/powerpc/mm/numa.c:parse_numa_properties
  - arch/powerpc/sysdev/xics/icp-native.c:icp_native_init_one_node
  - arch/powerpc/platforms/pseries/iommu.c:enable_ddw
  - drivers/iommu/of_iommu.c:of_get_dma_window
  - drivers/of/address.c:of_dma_get_range
  - drivers/of/address.c:of_bus_default_count_cells
```
**Symbols:**

```
c000000000c40c90-c000000000c40d70: of_n_size_cells (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int of_n_size_cells(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffffffe00071e722)
Location: drivers/of/base.c:104
Inline: False
Direct callers:
  - drivers/of/address.c:of_dma_get_range
  - drivers/of/address.c:of_bus_default_count_cells
```
**Symbols:**

```
ffffffe00071e722-ffffffe00071e798: of_n_size_cells (STB_GLOBAL)
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

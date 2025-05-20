# Function: <code>of_map_rid</code>

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
int of_map_rid(struct device_node *np, u32 rid, const char *map_name, const char *map_mask_name, struct device_node **target, u32 *id_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffff800010b6a3d8)
Location: drivers/of/base.c:2260
Inline: False
Direct callers:
  - drivers/iommu/of_iommu.c:of_fsl_mc_iommu_init
  - drivers/iommu/of_iommu.c:of_pci_iommu_init
  - drivers/of/irq.c:__of_msi_map_rid
```
**Symbols:**

```
ffff800010b6a3d8-ffff800010b6a65c: of_map_rid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_map_rid(struct device_node *np, u32 rid, const char *map_name, const char *map_mask_name, struct device_node **target, u32 *id_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c0c4d2ac)
Location: drivers/of/base.c:2260
Inline: False
Direct callers:
  - drivers/iommu/of_iommu.c:of_pci_iommu_init
  - drivers/of/irq.c:__of_msi_map_rid
```
**Symbols:**

```
c0c4d2ac-c0c4d554: of_map_rid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_map_rid(struct device_node *np, u32 rid, const char *map_name, const char *map_mask_name, struct device_node **target, u32 *id_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c000000000c42b80)
Location: drivers/of/base.c:2260
Inline: False
Direct callers:
  - drivers/iommu/of_iommu.c:of_pci_iommu_init
  - drivers/of/irq.c:__of_msi_map_rid
```
**Symbols:**

```
c000000000c42b80-c000000000c42f84: of_map_rid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int of_map_rid(struct device_node *np, u32 rid, const char *map_name, const char *map_mask_name, struct device_node **target, u32 *id_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffffffe00071f48c)
Location: drivers/of/base.c:2260
Inline: False
Direct callers:
  - drivers/of/irq.c:__of_msi_map_rid
```
**Symbols:**

```
ffffffe00071f48c-ffffffe00071f74c: of_map_rid (STB_GLOBAL)
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

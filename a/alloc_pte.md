# Function: <code>alloc_pte</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
u64 *alloc_pte(struct protection_domain *domain, long unsigned int address, long unsigned int page_size, u64 **pte_page, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8152ee20)
Location: drivers/iommu/amd_iommu.c:1150
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_map
  - drivers/iommu/amd_iommu.c:alloc_new_range
  - drivers/iommu/amd_iommu.c:__map_single
```
**Symbols:**

```
ffffffff8152ee20-ffffffff8152f060: alloc_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81583610)
Location: drivers/iommu/amd_iommu.c:1246
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
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
In drivers/iommu/amd_iommu.c (ffffffff815b0920)
Location: drivers/iommu/amd_iommu.c:1335
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815c6850)
Location: drivers/iommu/amd_iommu.c:1394
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8162d5f0)
Location: drivers/iommu/amd_iommu.c:1335
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816680e3)
Location: drivers/iommu/amd_iommu.c:1341
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81686424)
Location: drivers/iommu/amd_iommu.c:1451
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816bdcf8)
Location: drivers/iommu/amd_iommu.c:1466
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816e0eec)
Location: drivers/iommu/amd_iommu.c:1495
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81798fc0)
Location: drivers/iommu/amd/iommu.c:1452
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:iommu_map_page
```
**Symbols:**

```
ffffffff81798fc0-ffffffff8179924d: alloc_pte.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a7840)
Location: drivers/iommu/amd/iommu.c:1543
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:iommu_map_page
```
**Symbols:**

```
ffffffff817a7840-ffffffff817a7acd: alloc_pte.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/io_pgtable.c (ffffffff8178bce0)
Location: drivers/iommu/amd/io_pgtable.c:221
Inline: True
Direct callers:
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_page
```
**Symbols:**

```
ffffffff8178bce0-ffffffff8178c044: alloc_pte.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/io_pgtable.c (0)
Location: drivers/iommu/amd/io_pgtable.c:221
Inline: True
Direct callers:
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_page
```
**Symbols:**

```
ffffffff81813680-ffffffff81813a1a: alloc_pte.constprop.0 (STB_LOCAL)
ffffffff81cfea7f-ffffffff81cfeb11: alloc_pte.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/io_pgtable.c (0)
Location: drivers/iommu/amd/io_pgtable.c:195
Inline: True
Direct callers:
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_page
```
**Symbols:**

```
ffffffff819546a0-ffffffff81954a36: alloc_pte.constprop.0 (STB_LOCAL)
ffffffff81ec7292-ffffffff81ec732f: alloc_pte.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/io_pgtable.c (0)
Location: drivers/iommu/amd/io_pgtable.c:195
Inline: True
Direct callers:
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_pages
```
**Symbols:**

```
ffffffff81aba4f0-ffffffff81aba885: alloc_pte.constprop.0 (STB_LOCAL)
ffffffff82097204-ffffffff820972a1: alloc_pte.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/io_pgtable.c (0)
Location: drivers/iommu/amd/io_pgtable.c:195
Inline: True
Direct callers:
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_pages
```
**Symbols:**

```
ffffffff81b06aa0-ffffffff81b06f68: alloc_pte.constprop.0 (STB_LOCAL)
ffffffff8211819f-ffffffff82118244: alloc_pte.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/io_pgtable.c (0)
Location: drivers/iommu/amd/io_pgtable.c:195
Inline: True
Direct callers:
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_pages
```
**Symbols:**

```
ffffffff81b5aa80-ffffffff81b5af3e: alloc_pte.constprop.0 (STB_LOCAL)
ffffffff821f5e6c-ffffffff821f5f11: alloc_pte.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/riscv/mm/init.c (ffffffe000003850)
Location: arch/riscv/mm/init.c:187
Inline: True
Inline callers:
  - arch/riscv/mm/init.c:create_pgd_mapping
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
In drivers/iommu/amd_iommu.c (ffffffff816a693c)
Location: drivers/iommu/amd_iommu.c:1495
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
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
In drivers/iommu/amd_iommu.c (ffffffff8168432c)
Location: drivers/iommu/amd_iommu.c:1495
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d4bac)
Location: drivers/iommu/amd_iommu.c:1495
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816ef2ac)
Location: drivers/iommu/amd_iommu.c:1495
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>

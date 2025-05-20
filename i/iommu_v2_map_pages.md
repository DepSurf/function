# Function: <code>iommu_v2_map_pages</code>

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
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int iommu_v2_map_pages(struct io_pgtable_ops *ops, long unsigned int iova, phys_addr_t paddr, size_t pgsize, size_t pgcount, int prot, gfp_t gfp, size_t *mapped);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/io_pgtable_v2.c (0)
Location: drivers/iommu/amd/io_pgtable_v2.c:242
Inline: False
```
**Symbols:**

```
ffffffff81abb3b0-ffffffff81abb5b1: iommu_v2_map_pages (STB_LOCAL)
ffffffff820972b5-ffffffff82097301: iommu_v2_map_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int iommu_v2_map_pages(struct io_pgtable_ops *ops, long unsigned int iova, phys_addr_t paddr, size_t pgsize, size_t pgcount, int prot, gfp_t gfp, size_t *mapped);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/io_pgtable_v2.c (0)
Location: drivers/iommu/amd/io_pgtable_v2.c:236
Inline: False
```
**Symbols:**

```
ffffffff81b07ef0-ffffffff81b08108: iommu_v2_map_pages (STB_LOCAL)
ffffffff82118316-ffffffff82118362: iommu_v2_map_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int iommu_v2_map_pages(struct io_pgtable_ops *ops, long unsigned int iova, phys_addr_t paddr, size_t pgsize, size_t pgcount, int prot, gfp_t gfp, size_t *mapped);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/io_pgtable_v2.c (0)
Location: drivers/iommu/amd/io_pgtable_v2.c:236
Inline: False
```
**Symbols:**

```
ffffffff81b5bf20-ffffffff81b5c12a: iommu_v2_map_pages (STB_LOCAL)
ffffffff821f6023-ffffffff821f6076: iommu_v2_map_pages.cold (STB_LOCAL)
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
In <code>riscv64</code>: Absent ⚠️
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
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>

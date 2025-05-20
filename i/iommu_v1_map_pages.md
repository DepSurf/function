# Function: <code>iommu_v1_map_pages</code>

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
int iommu_v1_map_pages(struct io_pgtable_ops *ops, long unsigned int iova, phys_addr_t paddr, size_t pgsize, size_t pgcount, int prot, gfp_t gfp, size_t *mapped);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/io_pgtable.c (0)
Location: drivers/iommu/amd/io_pgtable.c:363
Inline: False
```
**Symbols:**

```
ffffffff81abab50-ffffffff81abaf16: iommu_v1_map_pages (STB_LOCAL)
ffffffff820972a1-ffffffff820972b5: iommu_v1_map_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int iommu_v1_map_pages(struct io_pgtable_ops *ops, long unsigned int iova, phys_addr_t paddr, size_t pgsize, size_t pgcount, int prot, gfp_t gfp, size_t *mapped);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/io_pgtable.c (0)
Location: drivers/iommu/amd/io_pgtable.c:363
Inline: False
```
**Symbols:**

```
ffffffff81b07220-ffffffff81b0762e: iommu_v1_map_pages (STB_LOCAL)
ffffffff82118244-ffffffff82118258: iommu_v1_map_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int iommu_v1_map_pages(struct io_pgtable_ops *ops, long unsigned int iova, phys_addr_t paddr, size_t pgsize, size_t pgcount, int prot, gfp_t gfp, size_t *mapped);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/io_pgtable.c (0)
Location: drivers/iommu/amd/io_pgtable.c:363
Inline: False
```
**Symbols:**

```
ffffffff81b5b1e0-ffffffff81b5b635: iommu_v1_map_pages (STB_LOCAL)
ffffffff821f5f11-ffffffff821f5f65: iommu_v1_map_pages.cold (STB_LOCAL)
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

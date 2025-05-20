# Function: <code>iommu_v1_map_page</code>

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
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int iommu_v1_map_page(struct io_pgtable_ops *ops, long unsigned int iova, phys_addr_t paddr, size_t size, int prot, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/io_pgtable.c (0)
Location: drivers/iommu/amd/io_pgtable.c:391
Inline: False
```
**Symbols:**

```
ffffffff8178c880-ffffffff8178cae8: iommu_v1_map_page (STB_LOCAL)
ffffffff81bfd60f-ffffffff81bfd649: iommu_v1_map_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int iommu_v1_map_page(struct io_pgtable_ops *ops, long unsigned int iova, phys_addr_t paddr, size_t size, int prot, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/io_pgtable.c (0)
Location: drivers/iommu/amd/io_pgtable.c:391
Inline: False
```
**Symbols:**

```
ffffffff81813f40-ffffffff818141b1: iommu_v1_map_page (STB_LOCAL)
ffffffff81cfeb11-ffffffff81cfeb5f: iommu_v1_map_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int iommu_v1_map_page(struct io_pgtable_ops *ops, long unsigned int iova, phys_addr_t paddr, size_t size, int prot, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/io_pgtable.c (0)
Location: drivers/iommu/amd/io_pgtable.c:365
Inline: False
```
**Symbols:**

```
ffffffff81954cd0-ffffffff81954fe4: iommu_v1_map_page (STB_LOCAL)
ffffffff81ec732f-ffffffff81ec7369: iommu_v1_map_page.cold (STB_LOCAL)
```
</details>
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>

# Function: <code>__arm_lpae_alloc_pages</code>

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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/io-pgtable-arm.c (ffff8000108cb370)
Location: drivers/iommu/io-pgtable-arm.c:230
Inline: True
Direct callers:
  - drivers/iommu/io-pgtable-arm.c:arm_64_lpae_alloc_pgtable_s2
  - drivers/iommu/io-pgtable-arm.c:arm_64_lpae_alloc_pgtable_s1
  - drivers/iommu/io-pgtable-arm.c:arm_lpae_split_blk_unmap
  - drivers/iommu/io-pgtable-arm.c:__arm_lpae_map
```
**Symbols:**

```
ffff8000108cb370-ffff8000108cb5cc: __arm_lpae_alloc_pages.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *__arm_lpae_alloc_pages(size_t size, gfp_t gfp, struct io_pgtable_cfg *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/io-pgtable-arm.c (c09bfee4)
Location: drivers/iommu/io-pgtable-arm.c:230
Inline: False
Direct callers:
  - drivers/iommu/io-pgtable-arm.c:arm_64_lpae_alloc_pgtable_s2
  - drivers/iommu/io-pgtable-arm.c:arm_64_lpae_alloc_pgtable_s1
  - drivers/iommu/io-pgtable-arm.c:__arm_lpae_unmap
  - drivers/iommu/io-pgtable-arm.c:__arm_lpae_map
```
**Symbols:**

```
c09bfee4-c09c00ec: __arm_lpae_alloc_pages (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>

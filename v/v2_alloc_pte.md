# Function: <code>v2_alloc_pte</code>

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
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 *v2_alloc_pte(u64 *pgd, long unsigned int iova, long unsigned int pg_size, bool *updated);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/io_pgtable_v2.c (ffffffff81abb1e0)
Location: drivers/iommu/amd/io_pgtable_v2.c:141
Inline: False
Direct callers:
  - drivers/iommu/amd/io_pgtable_v2.c:iommu_v2_map_pages
```
**Symbols:**

```
ffffffff81abb1e0-ffffffff81abb39c: v2_alloc_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u64 *v2_alloc_pte(int nid, u64 *pgd, long unsigned int iova, long unsigned int pg_size, gfp_t gfp, bool *updated);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/io_pgtable_v2.c (0)
Location: drivers/iommu/amd/io_pgtable_v2.c:135
Inline: False
Direct callers:
  - drivers/iommu/amd/io_pgtable_v2.c:iommu_v2_map_pages
```
**Symbols:**

```
ffffffff81b07c00-ffffffff81b07ed2: v2_alloc_pte (STB_LOCAL)
ffffffff821182bb-ffffffff82118316: v2_alloc_pte.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u64 *v2_alloc_pte(int nid, u64 *pgd, long unsigned int iova, long unsigned int pg_size, gfp_t gfp, bool *updated);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/io_pgtable_v2.c (0)
Location: drivers/iommu/amd/io_pgtable_v2.c:135
Inline: False
Direct callers:
  - drivers/iommu/amd/io_pgtable_v2.c:iommu_v2_map_pages
```
**Symbols:**

```
ffffffff81b5bc30-ffffffff81b5bf02: v2_alloc_pte (STB_LOCAL)
ffffffff821f5fc8-ffffffff821f6023: v2_alloc_pte.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int nid</code>
</li>
<li>
<b>Param added. </b>
<code>gfp_t gfp</code>
</li>
<li>
<b>Param reordered. </b>
<code>pgd, iova, pg_size, updated</code> ➡️ <code>nid, pgd, iova, pg_size, gfp, updated</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>

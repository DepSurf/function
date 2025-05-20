# Function: <code>iommu_tbl_range_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void iommu_tbl_range_free(struct iommu_map_table *iommu, u64 dma_addr, long unsigned int npages, long unsigned int entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iommu-common.c (ffffffff814136d0)
Location: lib/iommu-common.c:251
Inline: True
```
**Symbols:**

```
ffffffff814136d0-ffffffff8141376d: iommu_tbl_range_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void iommu_tbl_range_free(struct iommu_map_table *iommu, u64 dma_addr, long unsigned int npages, long unsigned int entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iommu-common.c (ffffffff8145b3e0)
Location: lib/iommu-common.c:251
Inline: True
```
**Symbols:**

```
ffffffff8145b3e0-ffffffff8145b47a: iommu_tbl_range_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void iommu_tbl_range_free(struct iommu_map_table *iommu, u64 dma_addr, long unsigned int npages, long unsigned int entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iommu-common.c (ffffffff81479ed0)
Location: lib/iommu-common.c:251
Inline: True
```
**Symbols:**

```
ffffffff81479ed0-ffffffff81479f6a: iommu_tbl_range_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void iommu_tbl_range_free(struct iommu_map_table *iommu, u64 dma_addr, long unsigned int npages, long unsigned int entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iommu-common.c (ffffffff814831e0)
Location: lib/iommu-common.c:251
Inline: False
```
**Symbols:**

```
ffffffff814831e0-ffffffff81483278: iommu_tbl_range_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void iommu_tbl_range_free(struct iommu_map_table *iommu, u64 dma_addr, long unsigned int npages, long unsigned int entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iommu-common.c (ffffffff814bf220)
Location: lib/iommu-common.c:252
Inline: False
```
**Symbols:**

```
ffffffff814bf220-ffffffff814bf2b8: iommu_tbl_range_free (STB_GLOBAL)
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>

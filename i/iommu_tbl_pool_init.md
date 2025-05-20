# Function: <code>iommu_tbl_pool_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void iommu_tbl_pool_init(struct iommu_map_table *iommu, long unsigned int num_entries, u32 table_shift, void (*lazy_flush)(struct iommu_map_table *), bool large_pool, u32 npools, bool skip_span_boundary_check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iommu-common.c (ffffffff81413200)
Location: lib/iommu-common.c:51
Inline: False
```
**Symbols:**

```
ffffffff81413200-ffffffff81413368: iommu_tbl_pool_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void iommu_tbl_pool_init(struct iommu_map_table *iommu, long unsigned int num_entries, u32 table_shift, void (*lazy_flush)(struct iommu_map_table *), bool large_pool, u32 npools, bool skip_span_boundary_check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iommu-common.c (ffffffff8145af20)
Location: lib/iommu-common.c:51
Inline: False
```
**Symbols:**

```
ffffffff8145af20-ffffffff8145b088: iommu_tbl_pool_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void iommu_tbl_pool_init(struct iommu_map_table *iommu, long unsigned int num_entries, u32 table_shift, void (*lazy_flush)(struct iommu_map_table *), bool large_pool, u32 npools, bool skip_span_boundary_check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iommu-common.c (ffffffff81479a10)
Location: lib/iommu-common.c:51
Inline: False
```
**Symbols:**

```
ffffffff81479a10-ffffffff81479b7a: iommu_tbl_pool_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void iommu_tbl_pool_init(struct iommu_map_table *iommu, long unsigned int num_entries, u32 table_shift, void (*lazy_flush)(struct iommu_map_table *), bool large_pool, u32 npools, bool skip_span_boundary_check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iommu-common.c (ffffffff81482d60)
Location: lib/iommu-common.c:51
Inline: False
```
**Symbols:**

```
ffffffff81482d60-ffffffff81482ecf: iommu_tbl_pool_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void iommu_tbl_pool_init(struct iommu_map_table *iommu, long unsigned int num_entries, u32 table_shift, void (*lazy_flush)(struct iommu_map_table *), bool large_pool, u32 npools, bool skip_span_boundary_check);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iommu-common.c (ffffffff814beda0)
Location: lib/iommu-common.c:52
Inline: False
```
**Symbols:**

```
ffffffff814beda0-ffffffff814bef06: iommu_tbl_pool_init (STB_GLOBAL)
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

# Function: <code>sg_alloc_table_from_pages_segment</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sg_alloc_table_from_pages_segment(struct sg_table *sgt, struct page **pages, unsigned int n_pages, unsigned int offset, long unsigned int size, unsigned int max_segment, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff816136e0)
Location: lib/scatterlist.c:565
Inline: False
```
**Symbols:**

```
ffffffff816136e0-ffffffff816137d9: sg_alloc_table_from_pages_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sg_alloc_table_from_pages_segment(struct sg_table *sgt, struct page **pages, unsigned int n_pages, unsigned int offset, long unsigned int size, unsigned int max_segment, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff816dff40)
Location: lib/scatterlist.c:565
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable
```
**Symbols:**

```
ffffffff816dff40-ffffffff816e0078: sg_alloc_table_from_pages_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sg_alloc_table_from_pages_segment(struct sg_table *sgt, struct page **pages, unsigned int n_pages, unsigned int offset, long unsigned int size, unsigned int max_segment, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff817d0040)
Location: lib/scatterlist.c:575
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable
```
**Symbols:**

```
ffffffff817d0040-ffffffff817d0105: sg_alloc_table_from_pages_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sg_alloc_table_from_pages_segment(struct sg_table *sgt, struct page **pages, unsigned int n_pages, unsigned int offset, long unsigned int size, unsigned int max_segment, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8180eec0)
Location: lib/scatterlist.c:577
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable
```
**Symbols:**

```
ffffffff8180eec0-ffffffff8180ef85: sg_alloc_table_from_pages_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sg_alloc_table_from_pages_segment(struct sg_table *sgt, struct page **pages, unsigned int n_pages, unsigned int offset, long unsigned int size, unsigned int max_segment, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81854b40)
Location: lib/scatterlist.c:578
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable
  - drivers/gpu/drm/drm_prime.c:drm_prime_pages_to_sg
```
**Symbols:**

```
ffffffff81854b40-ffffffff81854c05: sg_alloc_table_from_pages_segment (STB_GLOBAL)
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>

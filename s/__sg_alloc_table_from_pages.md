# Function: <code>__sg_alloc_table_from_pages</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int __sg_alloc_table_from_pages(struct sg_table *sgt, struct page **pages, unsigned int n_pages, unsigned int offset, long unsigned int size, unsigned int max_segment, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8148fbf0)
Location: lib/scatterlist.c:393
Inline: True
Direct callers:
  - lib/scatterlist.c:sg_alloc_table_from_pages
```
**Symbols:**

```
ffffffff8148fbf0-ffffffff8148fdd6: __sg_alloc_table_from_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int __sg_alloc_table_from_pages(struct sg_table *sgt, struct page **pages, unsigned int n_pages, unsigned int offset, long unsigned int size, unsigned int max_segment, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff814c4830)
Location: lib/scatterlist.c:381
Inline: True
Direct callers:
  - lib/scatterlist.c:sg_alloc_table_from_pages
```
**Symbols:**

```
ffffffff814c4830-ffffffff814c4a16: __sg_alloc_table_from_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int __sg_alloc_table_from_pages(struct sg_table *sgt, struct page **pages, unsigned int n_pages, unsigned int offset, long unsigned int size, unsigned int max_segment, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff814d8f20)
Location: lib/scatterlist.c:381
Inline: True
Direct callers:
  - lib/scatterlist.c:sg_alloc_table_from_pages
```
**Symbols:**

```
ffffffff814d8f20-ffffffff814d9106: __sg_alloc_table_from_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __sg_alloc_table_from_pages(struct sg_table *sgt, struct page **pages, unsigned int n_pages, unsigned int offset, long unsigned int size, unsigned int max_segment, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/scatterlist.c (0)
Location: lib/scatterlist.c:389
Inline: True
Direct callers:
  - lib/scatterlist.c:sg_alloc_table_from_pages
```
**Symbols:**

```
ffffffff815051ae-ffffffff815051c8: __sg_alloc_table_from_pages.cold (STB_LOCAL)
ffffffff81504df0-ffffffff81504fb0: __sg_alloc_table_from_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __sg_alloc_table_from_pages(struct sg_table *sgt, struct page **pages, unsigned int n_pages, unsigned int offset, long unsigned int size, unsigned int max_segment, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81522f10)
Location: lib/scatterlist.c:389
Inline: True
Direct callers:
  - lib/scatterlist.c:sg_alloc_table_from_pages
```
**Symbols:**

```
ffffffff81522f10-ffffffff815230d5: __sg_alloc_table_from_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __sg_alloc_table_from_pages(struct sg_table *sgt, struct page **pages, unsigned int n_pages, unsigned int offset, long unsigned int size, unsigned int max_segment, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815862d0)
Location: lib/scatterlist.c:389
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_alloc_table_from_pages
```
**Symbols:**

```
ffffffff815862d0-ffffffff8158650f: __sg_alloc_table_from_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct scatterlist *__sg_alloc_table_from_pages(struct sg_table *sgt, struct page **pages, unsigned int n_pages, unsigned int offset, long unsigned int size, unsigned int max_segment, struct scatterlist *prv, unsigned int left_pages, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815a33b0)
Location: lib/scatterlist.c:428
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_alloc_table_from_pages
```
**Symbols:**

```
ffffffff815a33b0-ffffffff815a37e1: __sg_alloc_table_from_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct scatterlist *__sg_alloc_table_from_pages(struct sg_table *sgt, struct page **pages, unsigned int n_pages, unsigned int offset, long unsigned int size, unsigned int max_segment, struct scatterlist *prv, unsigned int left_pages, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815a9f70)
Location: lib/scatterlist.c:428
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_alloc_table_from_pages
```
**Symbols:**

```
ffffffff815a9f70-ffffffff815aa39d: __sg_alloc_table_from_pages (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int __sg_alloc_table_from_pages(struct sg_table *sgt, struct page **pages, unsigned int n_pages, unsigned int offset, long unsigned int size, unsigned int max_segment, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffff80001062caf0)
Location: lib/scatterlist.c:389
Inline: True
Direct callers:
  - lib/scatterlist.c:sg_alloc_table_from_pages
```
**Symbols:**

```
ffff80001062caf0-ffff80001062ccf8: __sg_alloc_table_from_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __sg_alloc_table_from_pages(struct sg_table *sgt, struct page **pages, unsigned int n_pages, unsigned int offset, long unsigned int size, unsigned int max_segment, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (c07d3768)
Location: lib/scatterlist.c:389
Inline: True
Direct callers:
  - lib/scatterlist.c:sg_alloc_table_from_pages
```
**Symbols:**

```
c07d3768-c07d39d4: __sg_alloc_table_from_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __sg_alloc_table_from_pages(struct sg_table *sgt, struct page **pages, unsigned int n_pages, unsigned int offset, long unsigned int size, unsigned int max_segment, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (c0000000007cf7a0)
Location: lib/scatterlist.c:389
Inline: True
Direct callers:
  - lib/scatterlist.c:sg_alloc_table_from_pages
```
**Symbols:**

```
c0000000007cf7a0-c0000000007cfa44: __sg_alloc_table_from_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __sg_alloc_table_from_pages(struct sg_table *sgt, struct page **pages, unsigned int n_pages, unsigned int offset, long unsigned int size, unsigned int max_segment, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffe00045cce0)
Location: lib/scatterlist.c:389
Inline: True
Direct callers:
  - lib/scatterlist.c:sg_alloc_table_from_pages
```
**Symbols:**

```
ffffffe00045cce0-ffffffe00045ce5c: __sg_alloc_table_from_pages (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int __sg_alloc_table_from_pages(struct sg_table *sgt, struct page **pages, unsigned int n_pages, unsigned int offset, long unsigned int size, unsigned int max_segment, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8151b4f0)
Location: lib/scatterlist.c:389
Inline: True
Direct callers:
  - lib/scatterlist.c:sg_alloc_table_from_pages
```
**Symbols:**

```
ffffffff8151b4f0-ffffffff8151b6b5: __sg_alloc_table_from_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __sg_alloc_table_from_pages(struct sg_table *sgt, struct page **pages, unsigned int n_pages, unsigned int offset, long unsigned int size, unsigned int max_segment, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8150b7e0)
Location: lib/scatterlist.c:389
Inline: True
Direct callers:
  - lib/scatterlist.c:sg_alloc_table_from_pages
```
**Symbols:**

```
ffffffff8150b7e0-ffffffff8150b9a5: __sg_alloc_table_from_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __sg_alloc_table_from_pages(struct sg_table *sgt, struct page **pages, unsigned int n_pages, unsigned int offset, long unsigned int size, unsigned int max_segment, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81517580)
Location: lib/scatterlist.c:389
Inline: True
Direct callers:
  - lib/scatterlist.c:sg_alloc_table_from_pages
```
**Symbols:**

```
ffffffff81517580-ffffffff81517745: __sg_alloc_table_from_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __sg_alloc_table_from_pages(struct sg_table *sgt, struct page **pages, unsigned int n_pages, unsigned int offset, long unsigned int size, unsigned int max_segment, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81530d20)
Location: lib/scatterlist.c:389
Inline: True
Direct callers:
  - lib/scatterlist.c:sg_alloc_table_from_pages
```
**Symbols:**

```
ffffffff81530d20-ffffffff81530ee5: __sg_alloc_table_from_pages (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct scatterlist *prv</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int left_pages</code>
</li>
<li>
<b>Param reordered. </b>
<code>sgt, pages, n_pages, offset, size, max_segment, gfp_mask</code> ➡️ <code>sgt, pages, n_pages, offset, size, max_segment, prv, left_pages, gfp_mask</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>struct scatterlist *</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>

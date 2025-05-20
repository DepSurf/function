# Function: <code>alloc_contig_pages</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *alloc_contig_pages(long unsigned int nr_pages, gfp_t gfp_mask, int nid, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812b4140)
Location: mm/page_alloc.c:8590
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
**Symbols:**

```
ffffffff812b4140-ffffffff812b4327: alloc_contig_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *alloc_contig_pages(long unsigned int nr_pages, gfp_t gfp_mask, int nid, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812bfbc0)
Location: mm/page_alloc.c:8724
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
**Symbols:**

```
ffffffff812bfbc0-ffffffff812bfda9: alloc_contig_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *alloc_contig_pages(long unsigned int nr_pages, gfp_t gfp_mask, int nid, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812c5320)
Location: mm/page_alloc.c:8953
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
**Symbols:**

```
ffffffff812c5320-ffffffff812c5530: alloc_contig_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct page *alloc_contig_pages(long unsigned int nr_pages, gfp_t gfp_mask, int nid, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81309880)
Location: mm/page_alloc.c:9216
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
**Symbols:**

```
ffffffff81309880-ffffffff81309acb: alloc_contig_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct page *alloc_contig_pages(long unsigned int nr_pages, gfp_t gfp_mask, int nid, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813720e0)
Location: mm/page_alloc.c:9268
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/kfence/core.c:param_set_sample_interval
```
**Symbols:**

```
ffffffff813720e0-ffffffff81372368: alloc_contig_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct page *alloc_contig_pages(long unsigned int nr_pages, gfp_t gfp_mask, int nid, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813ef910)
Location: mm/page_alloc.c:9442
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_fresh_hugetlb_folio
  - mm/kfence/core.c:param_set_sample_interval
```
**Symbols:**

```
ffffffff813ef910-ffffffff813efb98: alloc_contig_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct page *alloc_contig_pages(long unsigned int nr_pages, gfp_t gfp_mask, int nid, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81423480)
Location: mm/page_alloc.c:6349
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_fresh_hugetlb_folio
  - mm/kfence/core.c:param_set_sample_interval
```
**Symbols:**

```
ffffffff81423480-ffffffff8142371b: alloc_contig_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct page *alloc_contig_pages(long unsigned int nr_pages, gfp_t gfp_mask, int nid, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff814503b0)
Location: mm/page_alloc.c:6491
Inline: False
Direct callers:
  - mm/hugetlb.c:__alloc_fresh_hugetlb_folio
  - mm/kfence/core.c:kfence_init_late
  - mm/kfence/core.c:kfence_init_late
```
**Symbols:**

```
ffffffff814503b0-ffffffff8145064b: alloc_contig_pages (STB_GLOBAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
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

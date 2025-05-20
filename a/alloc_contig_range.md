# Function: <code>alloc_contig_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int alloc_contig_range(long unsigned int start, long unsigned int end, unsigned int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81197740)
Location: mm/page_alloc.c:6681
Inline: False
Direct callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/cma.c:cma_alloc
```
**Symbols:**

```
ffffffff81197740-ffffffff81197a91: alloc_contig_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int alloc_contig_range(long unsigned int start, long unsigned int end, unsigned int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811ac640)
Location: mm/page_alloc.c:7212
Inline: False
Direct callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/cma.c:cma_alloc
```
**Symbols:**

```
ffffffff811ac640-ffffffff811ac9d8: alloc_contig_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int alloc_contig_range(long unsigned int start, long unsigned int end, unsigned int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811bcc10)
Location: mm/page_alloc.c:7264
Inline: False
Direct callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/cma.c:cma_alloc
```
**Symbols:**

```
ffffffff811bcc10-ffffffff811bcfa9: alloc_contig_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int alloc_contig_range(long unsigned int start, long unsigned int end, unsigned int migratetype, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811c4de0)
Location: mm/page_alloc.c:7595
Inline: False
Direct callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/cma.c:cma_alloc
```
**Symbols:**

```
ffffffff811c4de0-ffffffff811c51f3: alloc_contig_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int alloc_contig_range(long unsigned int start, long unsigned int end, unsigned int migratetype, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d9bb0)
Location: mm/page_alloc.c:7619
Inline: False
Direct callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/cma.c:cma_alloc
```
**Symbols:**

```
ffffffff811d9bb0-ffffffff811d9fb1: alloc_contig_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int alloc_contig_range(long unsigned int start, long unsigned int end, unsigned int migratetype, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:7786
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/cma.c:cma_alloc
```
**Symbols:**

```
ffffffff811fb699-ffffffff811fb6bd: alloc_contig_range.cold.117 (STB_LOCAL)
ffffffff811fa4a0-ffffffff811fa833: alloc_contig_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int alloc_contig_range(long unsigned int start, long unsigned int end, unsigned int migratetype, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:8119
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/cma.c:cma_alloc
```
**Symbols:**

```
ffffffff8120df72-ffffffff8120df95: alloc_contig_range.cold.121 (STB_LOCAL)
ffffffff8120cc10-ffffffff8120cfbe: alloc_contig_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int alloc_contig_range(long unsigned int start, long unsigned int end, unsigned int migratetype, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:8331
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/cma.c:cma_alloc
```
**Symbols:**

```
ffffffff81274451-ffffffff81274475: alloc_contig_range.cold (STB_LOCAL)
ffffffff81272ff0-ffffffff812733af: alloc_contig_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int alloc_contig_range(long unsigned int start, long unsigned int end, unsigned int migratetype, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:8361
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/cma.c:cma_alloc
```
**Symbols:**

```
ffffffff81283268-ffffffff8128328c: alloc_contig_range.cold (STB_LOCAL)
ffffffff81281e60-ffffffff8128221f: alloc_contig_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int alloc_contig_range(long unsigned int start, long unsigned int end, unsigned int migratetype, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:8393
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_pages
```
**Symbols:**

```
ffffffff812b4960-ffffffff812b4984: alloc_contig_range.cold (STB_LOCAL)
ffffffff812b1760-ffffffff812b1a3f: alloc_contig_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int alloc_contig_range(long unsigned int start, long unsigned int end, unsigned int migratetype, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:8525
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_pages
```
**Symbols:**

```
ffffffff81be7c80-ffffffff81be7ca4: alloc_contig_range.cold (STB_LOCAL)
ffffffff812bd0e0-ffffffff812bd3c7: alloc_contig_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int alloc_contig_range(long unsigned int start, long unsigned int end, unsigned int migratetype, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:8764
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_pages
```
**Symbols:**

```
ffffffff81bd9a5c-ffffffff81bd9a9e: alloc_contig_range.cold (STB_LOCAL)
ffffffff812c1f80-ffffffff812c235e: alloc_contig_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int alloc_contig_range(long unsigned int start, long unsigned int end, unsigned int migratetype, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:9027
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_pages
```
**Symbols:**

```
ffffffff81cbd7a8-ffffffff81cbd805: alloc_contig_range.cold (STB_LOCAL)
ffffffff813058e0-ffffffff81305d45: alloc_contig_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int alloc_contig_range(long unsigned int start, long unsigned int end, unsigned int migratetype, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:9084
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_pages
```
**Symbols:**

```
ffffffff81e704cb-ffffffff81e704ee: alloc_contig_range.cold (STB_LOCAL)
ffffffff81371e10-ffffffff813720d2: alloc_contig_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int alloc_contig_range(long unsigned int start, long unsigned int end, unsigned int migratetype, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:9258
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_pages
```
**Symbols:**

```
ffffffff8206565b-ffffffff8206567e: alloc_contig_range.cold (STB_LOCAL)
ffffffff813ef630-ffffffff813ef8f2: alloc_contig_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int alloc_contig_range(long unsigned int start, long unsigned int end, unsigned int migratetype, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:6162
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_pages
```
**Symbols:**

```
ffffffff820e4e54-ffffffff820e4e77: alloc_contig_range.cold (STB_LOCAL)
ffffffff814231b0-ffffffff81423470: alloc_contig_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int alloc_contig_range(long unsigned int start, long unsigned int end, unsigned int migratetype, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:6304
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_pages
```
**Symbols:**

```
ffffffff821c1b33-ffffffff821c1b56: alloc_contig_range.cold (STB_LOCAL)
ffffffff814500e0-ffffffff814503a0: alloc_contig_range (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int alloc_contig_range(long unsigned int start, long unsigned int end, unsigned int migratetype, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff80001031a5c8)
Location: mm/page_alloc.c:8361
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_gigantic_page
  - mm/cma.c:cma_alloc
```
**Symbols:**

```
ffff80001031a5c8-ffff80001031a99c: alloc_contig_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int alloc_contig_range(long unsigned int start, long unsigned int end, unsigned int migratetype, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0534b70)
Location: mm/page_alloc.c:8361
Inline: False
Direct callers:
  - mm/cma.c:cma_alloc
```
**Symbols:**

```
c0534b70-c0534f5c: alloc_contig_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int alloc_contig_range(long unsigned int start, long unsigned int end, unsigned int migratetype, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003ed890)
Location: mm/page_alloc.c:8361
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/cma.c:cma_alloc
```
**Symbols:**

```
c0000000003ed890-c0000000003edd4c: alloc_contig_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int alloc_contig_range(long unsigned int start, long unsigned int end, unsigned int migratetype, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021fdbe)
Location: mm/page_alloc.c:8361
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/cma.c:cma_alloc
```
**Symbols:**

```
ffffffe00021fdbe-ffffffe00022008c: alloc_contig_range (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int alloc_contig_range(long unsigned int start, long unsigned int end, unsigned int migratetype, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:8361
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/cma.c:cma_alloc
```
**Symbols:**

```
ffffffff8127b8b8-ffffffff8127b8dc: alloc_contig_range.cold (STB_LOCAL)
ffffffff8127a4b0-ffffffff8127a86f: alloc_contig_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int alloc_contig_range(long unsigned int start, long unsigned int end, unsigned int migratetype, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:8361
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/cma.c:cma_alloc
```
**Symbols:**

```
ffffffff8126d798-ffffffff8126d7bc: alloc_contig_range.cold (STB_LOCAL)
ffffffff8126c3a0-ffffffff8126c75f: alloc_contig_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int alloc_contig_range(long unsigned int start, long unsigned int end, unsigned int migratetype, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:8361
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/cma.c:cma_alloc
```
**Symbols:**

```
ffffffff81279658-ffffffff8127967c: alloc_contig_range.cold (STB_LOCAL)
ffffffff81278250-ffffffff8127860f: alloc_contig_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int alloc_contig_range(long unsigned int start, long unsigned int end, unsigned int migratetype, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:8361
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/cma.c:cma_alloc
```
**Symbols:**

```
ffffffff81289248-ffffffff8128926c: alloc_contig_range.cold (STB_LOCAL)
ffffffff81287e40-ffffffff812881ff: alloc_contig_range (STB_GLOBAL)
```
</details>
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp_mask</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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

# Function: <code>swap_readpage</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int swap_readpage(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff811d2530)
Location: mm/page_io.c:324
Inline: False
Direct callers:
  - mm/swap_state.c:read_swap_cache_async
```
**Symbols:**

```
ffffffff811d2530-ffffffff811d2601: swap_readpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int swap_readpage(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff811f0130)
Location: mm/page_io.c:335
Inline: False
Direct callers:
  - mm/swap_state.c:read_swap_cache_async
```
**Symbols:**

```
ffffffff811f0130-ffffffff811f0268: swap_readpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int swap_readpage(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff81200b00)
Location: mm/page_io.c:332
Inline: False
Direct callers:
  - mm/swap_state.c:read_swap_cache_async
```
**Symbols:**

```
ffffffff81200b00-ffffffff81200c2a: swap_readpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int swap_readpage(struct page *page, bool do_poll);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff8120b780)
Location: mm/page_io.c:337
Inline: False
Direct callers:
  - mm/swap_state.c:read_swap_cache_async
```
**Symbols:**

```
ffffffff8120b780-ffffffff8120b927: swap_readpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int swap_readpage(struct page *page, bool synchronous);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff81224ca0)
Location: mm/page_io.c:350
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:do_swap_page_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:read_swap_cache_async
```
**Symbols:**

```
ffffffff81224ca0-ffffffff81224e5f: swap_readpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int swap_readpage(struct page *page, bool synchronous);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff81247240)
Location: mm/page_io.c:350
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:read_swap_cache_async
```
**Symbols:**

```
ffffffff81247240-ffffffff81247417: swap_readpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int swap_readpage(struct page *page, bool synchronous);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff8125b690)
Location: mm/page_io.c:351
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:read_swap_cache_async
```
**Symbols:**

```
ffffffff8125b690-ffffffff8125b884: swap_readpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int swap_readpage(struct page *page, bool synchronous);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff81276800)
Location: mm/page_io.c:350
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:read_swap_cache_async
```
**Symbols:**

```
ffffffff81276800-ffffffff812769e1: swap_readpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int swap_readpage(struct page *page, bool synchronous);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff812862f0)
Location: mm/page_io.c:350
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:read_swap_cache_async
```
**Symbols:**

```
ffffffff812862f0-ffffffff812864d1: swap_readpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int swap_readpage(struct page *page, bool synchronous);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff812b85b0)
Location: mm/page_io.c:353
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:swap_cluster_readahead
```
**Symbols:**

```
ffffffff812b85b0-ffffffff812b8808: swap_readpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int swap_readpage(struct page *page, bool synchronous);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff812c3c80)
Location: mm/page_io.c:375
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:swap_cluster_readahead
```
**Symbols:**

```
ffffffff812c3c80-ffffffff812c3ee1: swap_readpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int swap_readpage(struct page *page, bool synchronous);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff812caa10)
Location: mm/page_io.c:356
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:swap_cluster_readahead
```
**Symbols:**

```
ffffffff812caa10-ffffffff812cacd2: swap_readpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int swap_readpage(struct page *page, bool synchronous);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff8130fa20)
Location: mm/page_io.c:356
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:swap_cluster_readahead
```
**Symbols:**

```
ffffffff8130fa20-ffffffff8130fcd7: swap_readpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int swap_readpage(struct page *page, bool synchronous, struct swap_iocb **plug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_io.c (0)
Location: mm/page_io.c:448
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:swap_cluster_readahead
```
**Symbols:**

```
ffffffff81e70aa0-ffffffff81e70aba: swap_readpage.cold (STB_LOCAL)
ffffffff8137a420-ffffffff8137a732: swap_readpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int swap_readpage(struct page *page, bool synchronous, struct swap_iocb **plug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_io.c (0)
Location: mm/page_io.c:448
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:swap_cluster_readahead
```
**Symbols:**

```
ffffffff82065a88-ffffffff82065aa2: swap_readpage.cold (STB_LOCAL)
ffffffff813f7ec0-ffffffff813f8220: swap_readpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void swap_readpage(struct page *page, bool synchronous, struct swap_iocb **plug);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_io.c (0)
Location: mm/page_io.c:496
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:swap_cluster_readahead
```
**Symbols:**

```
ffffffff820e5267-ffffffff820e5282: swap_readpage.cold (STB_LOCAL)
ffffffff8142afb0-ffffffff8142b225: swap_readpage (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int swap_readpage(struct page *page, bool synchronous);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffff8000103208e0)
Location: mm/page_io.c:350
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:read_swap_cache_async
```
**Symbols:**

```
ffff8000103208e0-ffff800010320b5c: swap_readpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int swap_readpage(struct page *page, bool synchronous);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (c05392dc)
Location: mm/page_io.c:350
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:read_swap_cache_async
```
**Symbols:**

```
c05392dc-c05395a8: swap_readpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int swap_readpage(struct page *page, bool synchronous);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (c0000000003f5bb0)
Location: mm/page_io.c:350
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:read_swap_cache_async
```
**Symbols:**

```
c0000000003f5bb0-c0000000003f5ed8: swap_readpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int swap_readpage(struct page *page, bool synchronous);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffe000221f50)
Location: mm/page_io.c:350
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:read_swap_cache_async
```
**Symbols:**

```
ffffffe000221f50-ffffffe000222146: swap_readpage (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int swap_readpage(struct page *page, bool synchronous);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff8127e940)
Location: mm/page_io.c:350
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:read_swap_cache_async
```
**Symbols:**

```
ffffffff8127e940-ffffffff8127eb21: swap_readpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int swap_readpage(struct page *page, bool synchronous);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff81270770)
Location: mm/page_io.c:350
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:read_swap_cache_async
```
**Symbols:**

```
ffffffff81270770-ffffffff81270951: swap_readpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int swap_readpage(struct page *page, bool synchronous);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff8127c6e0)
Location: mm/page_io.c:350
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:read_swap_cache_async
```
**Symbols:**

```
ffffffff8127c6e0-ffffffff8127c8c1: swap_readpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int swap_readpage(struct page *page, bool synchronous);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff8128c2b0)
Location: mm/page_io.c:350
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:read_swap_cache_async
```
**Symbols:**

```
ffffffff8128c2b0-ffffffff8128c491: swap_readpage (STB_GLOBAL)
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
<code>bool do_poll</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool synchronous</code>
</li>
<li>
<b>Param removed. </b>
<code>bool do_poll</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct swap_iocb **plug</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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

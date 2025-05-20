# Function: <code>__read_swap_cache_async</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct page *__read_swap_cache_async(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct *vma, long unsigned int addr, bool *new_page_allocated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff811d2ac0)
Location: mm/swap_state.c:291
Inline: False
Direct callers:
  - mm/swap_state.c:read_swap_cache_async
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffffffff811d2ac0-ffffffff811d2bf9: __read_swap_cache_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct page *__read_swap_cache_async(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct *vma, long unsigned int addr, bool *new_page_allocated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff811f0840)
Location: mm/swap_state.c:298
Inline: False
Direct callers:
  - mm/swap_state.c:read_swap_cache_async
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffffffff811f0840-ffffffff811f09ea: __read_swap_cache_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct page *__read_swap_cache_async(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct *vma, long unsigned int addr, bool *new_page_allocated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff81201230)
Location: mm/swap_state.c:298
Inline: False
Direct callers:
  - mm/swap_state.c:read_swap_cache_async
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffffffff81201230-ffffffff812013ec: __read_swap_cache_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct page *__read_swap_cache_async(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct *vma, long unsigned int addr, bool *new_page_allocated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8120c0b0)
Location: mm/swap_state.c:316
Inline: False
Direct callers:
  - mm/swap_state.c:read_swap_cache_async
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffffffff8120c0b0-ffffffff8120c27a: __read_swap_cache_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct page *__read_swap_cache_async(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct *vma, long unsigned int addr, bool *new_page_allocated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff81225770)
Location: mm/swap_state.c:364
Inline: False
Direct callers:
  - mm/swap_state.c:do_swap_page_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:read_swap_cache_async
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffffffff81225770-ffffffff8122596b: __read_swap_cache_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct page *__read_swap_cache_async(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct *vma, long unsigned int addr, bool *new_page_allocated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff81247d10)
Location: mm/swap_state.c:377
Inline: False
Direct callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:read_swap_cache_async
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffffffff81247d10-ffffffff81247f09: __read_swap_cache_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct page *__read_swap_cache_async(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct *vma, long unsigned int addr, bool *new_page_allocated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8125c2e0)
Location: mm/swap_state.c:353
Inline: False
Direct callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:read_swap_cache_async
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffffffff8125c2e0-ffffffff8125c4e9: __read_swap_cache_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *__read_swap_cache_async(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct *vma, long unsigned int addr, bool *new_page_allocated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812774c0)
Location: mm/swap_state.c:359
Inline: False
Direct callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:read_swap_cache_async
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffffffff812774c0-ffffffff812776de: __read_swap_cache_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *__read_swap_cache_async(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct *vma, long unsigned int addr, bool *new_page_allocated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff81286fa0)
Location: mm/swap_state.c:359
Inline: False
Direct callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:read_swap_cache_async
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffffffff81286fa0-ffffffff812871c6: __read_swap_cache_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *__read_swap_cache_async(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct *vma, long unsigned int addr, bool *new_page_allocated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812b9520)
Location: mm/swap_state.c:358
Inline: False
Direct callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffffffff812b9520-ffffffff812b97bd: __read_swap_cache_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *__read_swap_cache_async(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct *vma, long unsigned int addr, bool *new_page_allocated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812c4f80)
Location: mm/swap_state.c:451
Inline: False
Direct callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffffffff812c4f80-ffffffff812c521d: __read_swap_cache_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *__read_swap_cache_async(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct *vma, long unsigned int addr, bool *new_page_allocated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812cbc30)
Location: mm/swap_state.c:422
Inline: False
Direct callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffffffff812cbc30-ffffffff812cbec0: __read_swap_cache_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct page *__read_swap_cache_async(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct *vma, long unsigned int addr, bool *new_page_allocated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap_state.c (0)
Location: mm/swap_state.c:417
Inline: False
Direct callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffffffff81cbea46-ffffffff81cbea5b: __read_swap_cache_async.cold (STB_LOCAL)
ffffffff81310da0-ffffffff81311083: __read_swap_cache_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct page *__read_swap_cache_async(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct *vma, long unsigned int addr, bool *new_page_allocated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap_state.c (0)
Location: mm/swap_state.c:425
Inline: False
Direct callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffffffff81e70bce-ffffffff81e70be3: __read_swap_cache_async.cold (STB_LOCAL)
ffffffff8137bc30-ffffffff8137c067: __read_swap_cache_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct page *__read_swap_cache_async(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct *vma, long unsigned int addr, bool *new_page_allocated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap_state.c (0)
Location: mm/swap_state.c:409
Inline: False
Direct callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffffffff82065b65-ffffffff82065b7a: __read_swap_cache_async.cold (STB_LOCAL)
ffffffff813f9570-ffffffff813f9800: __read_swap_cache_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct page *__read_swap_cache_async(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct *vma, long unsigned int addr, bool *new_page_allocated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap_state.c (0)
Location: mm/swap_state.c:413
Inline: False
Direct callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffffffff820e5300-ffffffff820e531b: __read_swap_cache_async.cold (STB_LOCAL)
ffffffff8142c2d0-ffffffff8142c5ae: __read_swap_cache_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct folio *__read_swap_cache_async(swp_entry_t entry, gfp_t gfp_mask, struct mempolicy *mpol, long unsigned int ilx, bool *new_page_allocated, bool skip_if_exists);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap_state.c (0)
Location: mm/swap_state.c:413
Inline: False
Direct callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:read_swap_cache_async
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffffffff821c2478-ffffffff821c2493: __read_swap_cache_async.cold (STB_LOCAL)
ffffffff81465a30-ffffffff81465cd1: __read_swap_cache_async (STB_GLOBAL)
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
struct page *__read_swap_cache_async(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct *vma, long unsigned int addr, bool *new_page_allocated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffff800010321a98)
Location: mm/swap_state.c:359
Inline: False
Direct callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:read_swap_cache_async
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffff800010321a98-ffff800010321ce0: __read_swap_cache_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct page *__read_swap_cache_async(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct *vma, long unsigned int addr, bool *new_page_allocated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (c053a1d0)
Location: mm/swap_state.c:359
Inline: False
Direct callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:read_swap_cache_async
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
c053a1d0-c053a3d4: __read_swap_cache_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct page *__read_swap_cache_async(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct *vma, long unsigned int addr, bool *new_page_allocated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (c0000000003f7210)
Location: mm/swap_state.c:359
Inline: False
Direct callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:read_swap_cache_async
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
c0000000003f7210-c0000000003f75a8: __read_swap_cache_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct page *__read_swap_cache_async(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct *vma, long unsigned int addr, bool *new_page_allocated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffe000222c06)
Location: mm/swap_state.c:359
Inline: False
Direct callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:read_swap_cache_async
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffffffe000222c06-ffffffe000222de0: __read_swap_cache_async (STB_GLOBAL)
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
struct page *__read_swap_cache_async(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct *vma, long unsigned int addr, bool *new_page_allocated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8127f5f0)
Location: mm/swap_state.c:359
Inline: False
Direct callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:read_swap_cache_async
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffffffff8127f5f0-ffffffff8127f816: __read_swap_cache_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *__read_swap_cache_async(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct *vma, long unsigned int addr, bool *new_page_allocated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff81271410)
Location: mm/swap_state.c:359
Inline: False
Direct callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:read_swap_cache_async
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffffffff81271410-ffffffff81271636: __read_swap_cache_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *__read_swap_cache_async(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct *vma, long unsigned int addr, bool *new_page_allocated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8127d390)
Location: mm/swap_state.c:359
Inline: False
Direct callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:read_swap_cache_async
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffffffff8127d390-ffffffff8127d5b6: __read_swap_cache_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *__read_swap_cache_async(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct *vma, long unsigned int addr, bool *new_page_allocated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8128cf60)
Location: mm/swap_state.c:359
Inline: False
Direct callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:read_swap_cache_async
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffffffff8128cf60-ffffffff8128d16d: __read_swap_cache_async (STB_GLOBAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mempolicy *mpol</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int ilx</code>
</li>
<li>
<b>Param added. </b>
<code>bool skip_if_exists</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vm_area_struct *vma</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int addr</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct page *</code> ➡️ <code>struct folio *</code>
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

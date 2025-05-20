# Function: <code>delete_from_swap_cache</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void delete_from_swap_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff811d2910)
Location: mm/swap_state.c:212
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:try_to_unuse
  - mm/memory-failure.c:me_swapcache_clean
```
**Symbols:**

```
ffffffff811d2910-ffffffff811d2974: delete_from_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void delete_from_swap_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff811f05f0)
Location: mm/swap_state.c:216
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
  - mm/memory-failure.c:me_swapcache_clean
```
**Symbols:**

```
ffffffff811f05f0-ffffffff811f0695: delete_from_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void delete_from_swap_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff81200fc0)
Location: mm/swap_state.c:218
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
  - mm/memory-failure.c:me_swapcache_clean
```
**Symbols:**

```
ffffffff81200fc0-ffffffff81201065: delete_from_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void delete_from_swap_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8120be20)
Location: mm/swap_state.c:236
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
  - mm/memory-failure.c:me_swapcache_clean
```
**Symbols:**

```
ffffffff8120be20-ffffffff8120beaf: delete_from_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void delete_from_swap_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff81225420)
Location: mm/swap_state.c:267
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
  - mm/memory-failure.c:me_swapcache_clean
```
**Symbols:**

```
ffffffff81225420-ffffffff812254ad: delete_from_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void delete_from_swap_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812479c0)
Location: mm/swap_state.c:264
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
  - mm/memory-failure.c:me_swapcache_clean
```
**Symbols:**

```
ffffffff812479c0-ffffffff81247a4d: delete_from_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void delete_from_swap_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8125bf80)
Location: mm/swap_state.c:243
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:reuse_swap_page
  - mm/memory-failure.c:me_swapcache_clean
```
**Symbols:**

```
ffffffff8125bf80-ffffffff8125c012: delete_from_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void delete_from_swap_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff81277150)
Location: mm/swap_state.c:244
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/swapfile.c:reuse_swap_page
  - mm/memory-failure.c:me_swapcache_clean
```
**Symbols:**

```
ffffffff81277150-ffffffff812771df: delete_from_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void delete_from_swap_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff81286c30)
Location: mm/swap_state.c:244
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/swapfile.c:reuse_swap_page
  - mm/memory-failure.c:me_swapcache_clean
```
**Symbols:**

```
ffffffff81286c30-ffffffff81286cbf: delete_from_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void delete_from_swap_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812b91b0)
Location: mm/swap_state.c:243
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swapfile.c:reuse_swap_page
  - mm/memory-failure.c:me_swapcache_clean
```
**Symbols:**

```
ffffffff812b91b0-ffffffff812b923f: delete_from_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void delete_from_swap_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812c4970)
Location: mm/swap_state.c:272
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swapfile.c:reuse_swap_page
  - mm/memory-failure.c:me_swapcache_clean
```
**Symbols:**

```
ffffffff812c4970-ffffffff812c49ff: delete_from_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void delete_from_swap_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812cb620)
Location: mm/swap_state.c:243
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/swapfile.c:reuse_swap_page
  - mm/memory-failure.c:me_swapcache_clean
```
**Symbols:**

```
ffffffff812cb620-ffffffff812cb6b0: delete_from_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void delete_from_swap_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff813106f0)
Location: mm/swap_state.c:240
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/swapfile.c:reuse_swap_page
  - mm/memory-failure.c:me_swapcache_clean
```
**Symbols:**

```
ffffffff813106f0-ffffffff8131079d: delete_from_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void delete_from_swap_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8137b3e0)
Location: mm/swap_state.c:245
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_swapin_folio
  - mm/swapfile.c:try_to_free_swap
  - mm/memory-failure.c:me_swapcache_clean
```
**Symbols:**

```
ffffffff8137b3e0-ffffffff8137b4bc: delete_from_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void delete_from_swap_cache(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff813f8d80)
Location: mm/swap_state.c:231
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_swapin_folio
  - mm/swapfile.c:folio_free_swap
  - mm/memory-failure.c:me_swapcache_clean
```
**Symbols:**

```
ffffffff813f8d80-ffffffff813f8e2b: delete_from_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void delete_from_swap_cache(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8142bb50)
Location: mm/swap_state.c:234
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_swapin_folio
  - mm/swapfile.c:folio_free_swap
  - mm/zswap.c:zswap_writeback_entry
  - mm/memory-failure.c:me_swapcache_clean
```
**Symbols:**

```
ffffffff8142bb50-ffffffff8142bbfb: delete_from_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void delete_from_swap_cache(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff814652b0)
Location: mm/swap_state.c:234
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_swapin_folio
  - mm/swapfile.c:folio_free_swap
  - mm/zswap.c:zswap_writeback_entry
  - mm/memory-failure.c:me_swapcache_clean
```
**Symbols:**

```
ffffffff814652b0-ffffffff81465358: delete_from_swap_cache (STB_GLOBAL)
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
void delete_from_swap_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffff8000103214f0)
Location: mm/swap_state.c:244
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/swapfile.c:reuse_swap_page
  - mm/memory-failure.c:me_swapcache_clean
```
**Symbols:**

```
ffff8000103214f0-ffff800010321600: delete_from_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void delete_from_swap_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (c0539d70)
Location: mm/swap_state.c:244
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/swapfile.c:reuse_swap_page
```
**Symbols:**

```
c0539d70-c0539e08: delete_from_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void delete_from_swap_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (c0000000003f6b30)
Location: mm/swap_state.c:244
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/swapfile.c:reuse_swap_page
  - mm/memory-failure.c:me_swapcache_clean
```
**Symbols:**

```
c0000000003f6b30-c0000000003f6c74: delete_from_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void delete_from_swap_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffe000222854)
Location: mm/swap_state.c:244
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/swapfile.c:reuse_swap_page
```
**Symbols:**

```
ffffffe000222854-ffffffe00022291a: delete_from_swap_cache (STB_GLOBAL)
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
void delete_from_swap_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8127f280)
Location: mm/swap_state.c:244
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/swapfile.c:reuse_swap_page
  - mm/memory-failure.c:me_swapcache_clean
```
**Symbols:**

```
ffffffff8127f280-ffffffff8127f30f: delete_from_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void delete_from_swap_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812710a0)
Location: mm/swap_state.c:244
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/swapfile.c:reuse_swap_page
  - mm/memory-failure.c:me_swapcache_clean
```
**Symbols:**

```
ffffffff812710a0-ffffffff81271129: delete_from_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void delete_from_swap_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8127d020)
Location: mm/swap_state.c:244
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/swapfile.c:reuse_swap_page
  - mm/memory-failure.c:me_swapcache_clean
```
**Symbols:**

```
ffffffff8127d020-ffffffff8127d0af: delete_from_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void delete_from_swap_cache(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8128cbe0)
Location: mm/swap_state.c:244
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/swapfile.c:reuse_swap_page
  - mm/memory-failure.c:me_swapcache_clean
```
**Symbols:**

```
ffffffff8128cbe0-ffffffff8128cc66: delete_from_swap_cache (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio *folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
</li>
</ul>
</details>
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

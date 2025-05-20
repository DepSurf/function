# Function: <code>add_to_swap_cache</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int add_to_swap_cache(struct page *page, swp_entry_t entry, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff811d27f0)
Location: mm/swap_state.c:119
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap
Direct callers:
  - mm/shmem.c:shmem_writepage
```
**Symbols:**

```
ffffffff811d27f0-ffffffff811d281d: add_to_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int add_to_swap_cache(struct page *page, swp_entry_t entry, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff811f05a2)
Location: mm/swap_state.c:119
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap
Direct callers:
  - mm/shmem.c:shmem_writepage
```
**Symbols:**

```
ffffffff811f04c0-ffffffff811f04ed: add_to_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int add_to_swap_cache(struct page *page, swp_entry_t entry, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff81200f72)
Location: mm/swap_state.c:121
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap
Direct callers:
  - mm/shmem.c:shmem_writepage
```
**Symbols:**

```
ffffffff81200e80-ffffffff81200ead: add_to_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int add_to_swap_cache(struct page *page, swp_entry_t entry, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8120bc60)
Location: mm/swap_state.c:140
Inline: False
Direct callers:
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:add_to_swap
```
**Symbols:**

```
ffffffff8120bc60-ffffffff8120bc9a: add_to_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int add_to_swap_cache(struct page *page, swp_entry_t entry, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff81225250)
Location: mm/swap_state.c:160
Inline: False
Direct callers:
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:add_to_swap
```
**Symbols:**

```
ffffffff81225250-ffffffff8122528a: add_to_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int add_to_swap_cache(struct page *page, swp_entry_t entry, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812477f0)
Location: mm/swap_state.c:160
Inline: False
Direct callers:
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:add_to_swap
```
**Symbols:**

```
ffffffff812477f0-ffffffff81247830: add_to_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int add_to_swap_cache(struct page *page, swp_entry_t entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8125ba80)
Location: mm/swap_state.c:113
Inline: False
Direct callers:
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:add_to_swap
```
**Symbols:**

```
ffffffff8125ba80-ffffffff8125bd7b: add_to_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int add_to_swap_cache(struct page *page, swp_entry_t entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff81276c30)
Location: mm/swap_state.c:114
Inline: False
Direct callers:
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:add_to_swap
```
**Symbols:**

```
ffffffff81276c30-ffffffff81276f3c: add_to_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int add_to_swap_cache(struct page *page, swp_entry_t entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff81286720)
Location: mm/swap_state.c:114
Inline: False
Direct callers:
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:add_to_swap
```
**Symbols:**

```
ffffffff81286720-ffffffff81286a14: add_to_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int add_to_swap_cache(struct page *page, swp_entry_t entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812b8cb0)
Location: mm/swap_state.c:113
Inline: False
Direct callers:
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:add_to_swap
```
**Symbols:**

```
ffffffff812b8cb0-ffffffff812b8f9d: add_to_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int add_to_swap_cache(struct page *page, swp_entry_t entry, gfp_t gfp, void **shadowp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812c4410)
Location: mm/swap_state.c:128
Inline: False
Direct callers:
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:add_to_swap
```
**Symbols:**

```
ffffffff812c4410-ffffffff812c4741: add_to_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int add_to_swap_cache(struct page *page, swp_entry_t entry, gfp_t gfp, void **shadowp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812cb090)
Location: mm/swap_state.c:100
Inline: False
Direct callers:
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:add_to_swap
```
**Symbols:**

```
ffffffff812cb090-ffffffff812cb3d5: add_to_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int add_to_swap_cache(struct page *page, swp_entry_t entry, gfp_t gfp, void **shadowp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap_state.c (0)
Location: mm/swap_state.c:100
Inline: False
Direct callers:
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:add_to_swap
```
**Symbols:**

```
ffffffff81cbe9f5-ffffffff81cbea32: add_to_swap_cache.cold (STB_LOCAL)
ffffffff81310070-ffffffff81310460: add_to_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int add_to_swap_cache(struct page *page, swp_entry_t entry, gfp_t gfp, void **shadowp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap_state.c (0)
Location: mm/swap_state.c:101
Inline: False
Direct callers:
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:add_to_swap
```
**Symbols:**

```
ffffffff81e70b61-ffffffff81e70bb9: add_to_swap_cache.cold (STB_LOCAL)
ffffffff8137aa90-ffffffff8137b08a: add_to_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int add_to_swap_cache(struct folio *folio, swp_entry_t entry, gfp_t gfp, void **shadowp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap_state.c (0)
Location: mm/swap_state.c:88
Inline: False
Direct callers:
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:add_to_swap
```
**Symbols:**

```
ffffffff82065ab7-ffffffff82065b50: add_to_swap_cache.cold (STB_LOCAL)
ffffffff813f8650-ffffffff813f8a52: add_to_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int add_to_swap_cache(struct folio *folio, swp_entry_t entry, gfp_t gfp, void **shadowp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap_state.c (0)
Location: mm/swap_state.c:87
Inline: False
Direct callers:
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:add_to_swap
```
**Symbols:**

```
ffffffff820e5297-ffffffff820e52e4: add_to_swap_cache.cold (STB_LOCAL)
ffffffff8142b410-ffffffff8142b819: add_to_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int add_to_swap_cache(struct folio *folio, swp_entry_t entry, gfp_t gfp, void **shadowp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap_state.c (0)
Location: mm/swap_state.c:87
Inline: False
Direct callers:
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:add_to_swap
```
**Symbols:**

```
ffffffff821c240e-ffffffff821c245c: add_to_swap_cache.cold (STB_LOCAL)
ffffffff81464c00-ffffffff81464f95: add_to_swap_cache (STB_GLOBAL)
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
int add_to_swap_cache(struct page *page, swp_entry_t entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffff800010320ea8)
Location: mm/swap_state.c:114
Inline: False
Direct callers:
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:add_to_swap
```
**Symbols:**

```
ffff800010320ea8-ffff8000103212a8: add_to_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int add_to_swap_cache(struct page *page, swp_entry_t entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (c05397fc)
Location: mm/swap_state.c:114
Inline: False
Direct callers:
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:add_to_swap
```
**Symbols:**

```
c05397fc-c0539ba8: add_to_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int add_to_swap_cache(struct page *page, swp_entry_t entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (c0000000003f6350)
Location: mm/swap_state.c:114
Inline: False
Direct callers:
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:add_to_swap
```
**Symbols:**

```
c0000000003f6350-c0000000003f67cc: add_to_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int add_to_swap_cache(struct page *page, swp_entry_t entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffe0002223a2)
Location: mm/swap_state.c:114
Inline: False
Direct callers:
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:add_to_swap
```
**Symbols:**

```
ffffffe0002223a2-ffffffe0002226c0: add_to_swap_cache (STB_GLOBAL)
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
int add_to_swap_cache(struct page *page, swp_entry_t entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8127ed70)
Location: mm/swap_state.c:114
Inline: False
Direct callers:
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:add_to_swap
```
**Symbols:**

```
ffffffff8127ed70-ffffffff8127f064: add_to_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int add_to_swap_cache(struct page *page, swp_entry_t entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff81270ba0)
Location: mm/swap_state.c:114
Inline: False
Direct callers:
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:add_to_swap
```
**Symbols:**

```
ffffffff81270ba0-ffffffff81270e8e: add_to_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int add_to_swap_cache(struct page *page, swp_entry_t entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8127cb10)
Location: mm/swap_state.c:114
Inline: False
Direct callers:
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:add_to_swap
```
**Symbols:**

```
ffffffff8127cb10-ffffffff8127ce04: add_to_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int add_to_swap_cache(struct page *page, swp_entry_t entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8128c6e0)
Location: mm/swap_state.c:114
Inline: False
Direct callers:
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:add_to_swap
```
**Symbols:**

```
ffffffff8128c6e0-ffffffff8128c9cb: add_to_swap_cache (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp</code>
</li>
<li>
<b>Param removed. </b>
<code>gfp_t gfp_mask</code>
</li>
</ul>
</details>
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
<code>void **shadowp</code>
</li>
</ul>
</details>
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

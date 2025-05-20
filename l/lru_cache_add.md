# Function: <code>lru_cache_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void lru_cache_add(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8119deb0)
Location: mm/swap.c:670
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
Direct callers:
  - mm/filemap.c:add_to_page_cache_lru
  - mm/vmscan.c:putback_lru_page
```
**Symbols:**

```
ffffffff8119deb0-ffffffff8119dec0: lru_cache_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void lru_cache_add(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811b3861)
Location: mm/swap.c:429
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
Direct callers:
  - mm/filemap.c:add_to_page_cache_lru
  - mm/vmscan.c:putback_lru_page
```
**Symbols:**

```
ffffffff811b36d0-ffffffff811b36e0: lru_cache_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void lru_cache_add(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811c3ef1)
Location: mm/swap.c:430
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
Direct callers:
  - mm/filemap.c:add_to_page_cache_lru
  - mm/vmscan.c:putback_lru_page
```
**Symbols:**

```
ffffffff811c3d50-ffffffff811c3d60: lru_cache_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void lru_cache_add(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811cc2e1)
Location: mm/swap.c:441
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
Direct callers:
  - mm/filemap.c:add_to_page_cache_lru
  - mm/vmscan.c:putback_lru_page
```
**Symbols:**

```
ffffffff811cc140-ffffffff811cc150: lru_cache_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void lru_cache_add(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811e12d1)
Location: mm/swap.c:441
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
Direct callers:
  - mm/filemap.c:add_to_page_cache_lru
  - mm/vmscan.c:putback_lru_page
```
**Symbols:**

```
ffffffff811e1130-ffffffff811e1140: lru_cache_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void lru_cache_add(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff812029f1)
Location: mm/swap.c:442
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
Direct callers:
  - mm/filemap.c:add_to_page_cache_lru
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:putback_inactive_pages
```
**Symbols:**

```
ffffffff812029b0-ffffffff812029c0: lru_cache_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void lru_cache_add(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81215371)
Location: mm/swap.c:436
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
Direct callers:
  - mm/filemap.c:add_to_page_cache_lru
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:putback_inactive_pages
```
**Symbols:**

```
ffffffff81215330-ffffffff81215340: lru_cache_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void lru_cache_add(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81224d92)
Location: mm/swap.c:437
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
Direct callers:
  - mm/filemap.c:add_to_page_cache_lru
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
```
**Symbols:**

```
ffffffff81224d50-ffffffff81224d60: lru_cache_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void lru_cache_add(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81232b22)
Location: mm/swap.c:438
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
Direct callers:
  - mm/filemap.c:add_to_page_cache_lru
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
```
**Symbols:**

```
ffffffff81232ae0-ffffffff81232af0: lru_cache_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void lru_cache_add(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8125eb20)
Location: mm/swap.c:462
Inline: False
Direct callers:
  - mm/filemap.c:add_to_page_cache_lru
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/khugepaged.c:collapse_file
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff8125eb20-ffffffff8125eba1: lru_cache_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void lru_cache_add(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8126a970)
Location: mm/swap.c:454
Inline: False
Direct callers:
  - mm/filemap.c:add_to_page_cache_lru
  - mm/swap.c:lru_cache_add_inactive_or_unevictable
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/khugepaged.c:collapse_file
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff8126a970-ffffffff8126a9e8: lru_cache_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void lru_cache_add(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8126fb40)
Location: mm/swap.c:464
Inline: False
Direct callers:
  - mm/filemap.c:add_to_page_cache_lru
  - mm/swap.c:lru_cache_add_inactive_or_unevictable
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/khugepaged.c:collapse_file
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff8126fb40-ffffffff8126fbc2: lru_cache_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void lru_cache_add(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff812ace00)
Location: mm/swap.c:442
Inline: False
Direct callers:
  - mm/filemap.c:add_to_page_cache_lru
  - mm/swap.c:lru_cache_add_inactive_or_unevictable
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/khugepaged.c:collapse_file
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff812ace00-ffffffff812ace82: lru_cache_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void lru_cache_add(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff81300ad0)
Location: mm/folio-compat.c:107
Inline: False
Direct callers:
  - mm/swap.c:lru_cache_add_inactive_or_unevictable
  - mm/shmem.c:shmem_replace_page
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/khugepaged.c:collapse_file
  - mm/userfaultfd.c:mfill_atomic_install_pte
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff81300ad0-ffffffff81300b2b: lru_cache_add (STB_GLOBAL)
```
</details>
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
void lru_cache_add(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffff8000102c2ae8)
Location: mm/swap.c:438
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
Direct callers:
  - mm/filemap.c:add_to_page_cache_lru
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
```
**Symbols:**

```
ffff8000102c2a48-ffff8000102c2a74: lru_cache_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void lru_cache_add(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (c04edc64)
Location: mm/swap.c:438
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
Direct callers:
  - mm/filemap.c:add_to_page_cache_lru
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
```
**Symbols:**

```
c04edc00-c04edc1c: lru_cache_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void lru_cache_add(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (c00000000037cc08)
Location: mm/swap.c:438
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
Direct callers:
  - mm/filemap.c:add_to_page_cache_lru
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
```
**Symbols:**

```
c00000000037cb90-c00000000037cba4: lru_cache_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void lru_cache_add(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffe0001e3e00)
Location: mm/swap.c:438
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
Direct callers:
  - mm/filemap.c:add_to_page_cache_lru
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
```
**Symbols:**

```
ffffffe0001e3d96-ffffffe0001e3dc0: lru_cache_add (STB_GLOBAL)
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
void lru_cache_add(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8122b172)
Location: mm/swap.c:438
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
Direct callers:
  - mm/filemap.c:add_to_page_cache_lru
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
```
**Symbols:**

```
ffffffff8122b130-ffffffff8122b140: lru_cache_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void lru_cache_add(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8121e282)
Location: mm/swap.c:438
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
Direct callers:
  - mm/filemap.c:add_to_page_cache_lru
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
```
**Symbols:**

```
ffffffff8121e240-ffffffff8121e250: lru_cache_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void lru_cache_add(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81228f12)
Location: mm/swap.c:438
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
Direct callers:
  - mm/filemap.c:add_to_page_cache_lru
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
```
**Symbols:**

```
ffffffff81228ed0-ffffffff81228ee0: lru_cache_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void lru_cache_add(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff812382d2)
Location: mm/swap.c:438
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
Direct callers:
  - mm/filemap.c:add_to_page_cache_lru
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
```
**Symbols:**

```
ffffffff81238290-ffffffff812382a0: lru_cache_add (STB_GLOBAL)
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

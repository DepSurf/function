# Function: <code>mark_page_accessed</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void mark_page_accessed(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8119de00)
Location: mm/swap.c:605
Inline: False
Direct callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_read_iter
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_file_read_iter
  - mm/gup.c:follow_page_pte
  - mm/memory.c:unmap_page_range
  - mm/ksm.c:try_to_merge_with_ksm_page
```
**Symbols:**

```
ffffffff8119de00-ffffffff8119de98: mark_page_accessed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void mark_page_accessed(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811b3560)
Location: mm/swap.c:364
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:pagecache_get_page
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/gup.c:follow_page_pte
  - mm/memory.c:unmap_page_range
  - mm/ksm.c:try_to_merge_with_ksm_page
```
**Symbols:**

```
ffffffff811b3560-ffffffff811b36ba: mark_page_accessed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mark_page_accessed(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811c3be0)
Location: mm/swap.c:365
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:pagecache_get_page
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/gup.c:follow_page_pte
  - mm/memory.c:unmap_page_range
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff811c3be0-ffffffff811c3d3a: mark_page_accessed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mark_page_accessed(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811cbf90)
Location: mm/swap.c:376
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:pagecache_get_page
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/gup.c:follow_page_pte
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff811cbf90-ffffffff811cc0eb: mark_page_accessed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mark_page_accessed(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811e0f80)
Location: mm/swap.c:376
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:pagecache_get_page
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/gup.c:follow_page_pte
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff811e0f80-ffffffff811e10db: mark_page_accessed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mark_page_accessed(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81202810)
Location: mm/swap.c:377
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/gup.c:follow_page_pte
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff81202810-ffffffff81202952: mark_page_accessed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mark_page_accessed(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81215190)
Location: mm/swap.c:371
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/gup.c:follow_page_pte
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff81215190-ffffffff812152d2: mark_page_accessed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void mark_page_accessed(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81224bb0)
Location: mm/swap.c:372
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/gup.c:follow_page_pte
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff81224bb0-ffffffff81224d08: mark_page_accessed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mark_page_accessed(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81232940)
Location: mm/swap.c:373
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/gup.c:follow_page_pte
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff81232940-ffffffff81232a98: mark_page_accessed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mark_page_accessed(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8125fea0)
Location: mm/swap.c:422
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/gup.c:follow_page_pte
  - mm/memory.c:zap_pte_range
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff8125fea0-ffffffff8125ffc1: mark_page_accessed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mark_page_accessed(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81269600)
Location: mm/swap.c:414
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/gup.c:follow_page_pte
  - mm/memory.c:zap_pte_range
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff81269600-ffffffff81269721: mark_page_accessed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mark_page_accessed(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8126ea60)
Location: mm/swap.c:424
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_read
  - mm/filemap.c:pagecache_get_page
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/gup.c:follow_page_pte
  - mm/memory.c:zap_pte_range
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff8126ea60-ffffffff8126ec64: mark_page_accessed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mark_page_accessed(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff812abab0)
Location: mm/swap.c:402
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_read
  - mm/filemap.c:pagecache_get_page
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/gup.c:follow_page_pte
  - mm/memory.c:zap_pte_range
  - mm/ksm.c:try_to_merge_one_page
  - fs/iomap/buffered-io.c:iomap_zero_range
```
**Symbols:**

```
ffffffff812abab0-ffffffff812abcb4: mark_page_accessed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mark_page_accessed(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff81300cb0)
Location: mm/folio-compat.c:48
Inline: False
Direct callers:
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_file_read_iter
  - mm/gup.c:follow_page_pte
  - mm/memory.c:zap_pte_range
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff81300cb0-ffffffff81300d0b: mark_page_accessed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mark_page_accessed(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff8136b560)
Location: mm/folio-compat.c:42
Inline: False
Direct callers:
  - mm/gup.c:follow_page_pte
  - mm/memory.c:zap_pte_range
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff8136b560-ffffffff8136b5bb: mark_page_accessed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mark_page_accessed(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff8139d720)
Location: mm/folio-compat.c:43
Inline: False
Direct callers:
  - mm/gup.c:follow_page_pte
  - mm/memory.c:zap_pte_range
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff8139d720-ffffffff8139d78a: mark_page_accessed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mark_page_accessed(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff813c7480)
Location: mm/folio-compat.c:43
Inline: False
Direct callers:
  - mm/gup.c:follow_page_pte
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff813c7480-ffffffff813c74e7: mark_page_accessed (STB_GLOBAL)
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
void mark_page_accessed(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffff8000102c27a8)
Location: mm/swap.c:373
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/gup.c:follow_page_pte
  - mm/memory.c:unmap_page_range
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffff8000102c27a8-ffff8000102c2998: mark_page_accessed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mark_page_accessed(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (c04ed9dc)
Location: mm/swap.c:373
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:unmap_page_range
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
c04ed9dc-c04edb88: mark_page_accessed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mark_page_accessed(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (c00000000037c820)
Location: mm/swap.c:373
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/gup.c:follow_page_pte
  - mm/memory.c:zap_pte_range
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
c00000000037c820-c00000000037cb10: mark_page_accessed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mark_page_accessed(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffe0001e3b88)
Location: mm/swap.c:373
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:unmap_page_range
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffe0001e3b88-ffffffe0001e3d14: mark_page_accessed (STB_GLOBAL)
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
void mark_page_accessed(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8122af90)
Location: mm/swap.c:373
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/gup.c:follow_page_pte
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff8122af90-ffffffff8122b0e8: mark_page_accessed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mark_page_accessed(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8121e0a0)
Location: mm/swap.c:373
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/gup.c:follow_page_pte
  - mm/memory.c:zap_pte_range
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff8121e0a0-ffffffff8121e1f8: mark_page_accessed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mark_page_accessed(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81228d30)
Location: mm/swap.c:373
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/gup.c:follow_page_pte
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff81228d30-ffffffff81228e88: mark_page_accessed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mark_page_accessed(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff812380d0)
Location: mm/swap.c:373
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/gup.c:follow_page_pte
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff812380d0-ffffffff81238241: mark_page_accessed (STB_GLOBAL)
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

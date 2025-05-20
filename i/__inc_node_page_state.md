# Function: <code>__inc_node_page_state</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __inc_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811c6d10)
Location: mm/vmstat.c:341
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/swap_state.c:__add_to_swap_cache
  - mm/khugepaged.c:collapse_shmem
```
**Symbols:**

```
ffffffff811c6d10-ffffffff811c6d2f: __inc_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __inc_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811d6e30)
Location: mm/vmstat.c:341
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/swap_state.c:__add_to_swap_cache
  - mm/khugepaged.c:collapse_shmem
```
**Symbols:**

```
ffffffff811d6e30-ffffffff811d6e4f: __inc_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __inc_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811dfc90)
Location: mm/vmstat.c:341
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/page-writeback.c:account_page_dirtied
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/khugepaged.c:collapse_shmem
```
**Symbols:**

```
ffffffff811dfc90-ffffffff811dfcaf: __inc_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __inc_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811f5aa0)
Location: mm/vmstat.c:416
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/page-writeback.c:account_page_dirtied
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/khugepaged.c:collapse_shmem
```
**Symbols:**

```
ffffffff811f5aa0-ffffffff811f5abf: __inc_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __inc_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81216d20)
Location: mm/vmstat.c:416
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/page-writeback.c:account_page_dirtied
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/khugepaged.c:collapse_shmem
```
**Symbols:**

```
ffffffff81216d20-ffffffff81216d3f: __inc_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __inc_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81229c30)
Location: mm/vmstat.c:416
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/page-writeback.c:account_page_dirtied
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
**Symbols:**

```
ffffffff81229c30-ffffffff81229c4f: __inc_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __inc_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812398c0)
Location: mm/vmstat.c:417
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/page-writeback.c:account_page_dirtied
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
**Symbols:**

```
ffffffff812398c0-ffffffff812398df: __inc_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __inc_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81247bc0)
Location: mm/vmstat.c:417
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/page-writeback.c:account_page_dirtied
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff81247bc0-ffffffff81247bdf: __inc_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __inc_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81274da0)
Location: mm/vmstat.c:417
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_dirtied
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff81274da0-ffffffff81274e0c: __inc_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __inc_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8127fc50)
Location: mm/vmstat.c:424
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_dirtied
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
```
**Symbols:**

```
ffffffff8127fc50-ffffffff8127fcbc: __inc_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __inc_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81284d90)
Location: mm/vmstat.c:430
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_dirtied
```
**Symbols:**

```
ffffffff81284d90-ffffffff81284dfc: __inc_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __inc_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812c2c40)
Location: mm/vmstat.c:462
Inline: False
Direct callers:
  - mm/page-writeback.c:account_page_dirtied
```
**Symbols:**

```
ffffffff812c2c40-ffffffff812c2ce3: __inc_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __inc_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8131fe50)
Location: mm/vmstat.c:491
Inline: False
```
**Symbols:**

```
ffffffff8131fe50-ffffffff8131ff0f: __inc_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __inc_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81393980)
Location: mm/vmstat.c:482
Inline: False
```
**Symbols:**

```
ffffffff81393980-ffffffff81393a6c: __inc_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __inc_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813c6680)
Location: mm/vmstat.c:483
Inline: False
```
**Symbols:**

```
ffffffff813c6680-ffffffff813c676c: __inc_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __inc_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813f1a40)
Location: mm/vmstat.c:482
Inline: False
```
**Symbols:**

```
ffffffff813f1a40-ffffffff813f1b2c: __inc_node_page_state (STB_GLOBAL)
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
void __inc_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffff8000102dc220)
Location: mm/vmstat.c:417
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/page-writeback.c:account_page_dirtied
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffff8000102dc220-ffff8000102dc264: __inc_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __inc_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (c050219c)
Location: mm/vmstat.c:417
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/page-writeback.c:account_page_dirtied
  - mm/shmem.c:shmem_swapin_page
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
**Symbols:**

```
c050219c-c05021c0: __inc_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __inc_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (c00000000039be40)
Location: mm/vmstat.c:417
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/page-writeback.c:account_page_dirtied
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
c00000000039be40-c00000000039be68: __inc_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __inc_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffe0001f52c8)
Location: mm/vmstat.c:417
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/page-writeback.c:account_page_dirtied
  - mm/shmem.c:shmem_swapin_page
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
**Symbols:**

```
ffffffe0001f52c8-ffffffe0001f52fa: __inc_node_page_state (STB_GLOBAL)
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
void __inc_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81240210)
Location: mm/vmstat.c:417
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/page-writeback.c:account_page_dirtied
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff81240210-ffffffff8124022f: __inc_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __inc_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81233210)
Location: mm/vmstat.c:417
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/page-writeback.c:account_page_dirtied
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff81233210-ffffffff8123322f: __inc_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __inc_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8123dfb0)
Location: mm/vmstat.c:417
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/page-writeback.c:account_page_dirtied
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff8123dfb0-ffffffff8123dfcf: __inc_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __inc_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8124d6e0)
Location: mm/vmstat.c:417
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/page-writeback.c:account_page_dirtied
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff8124d6e0-ffffffff8124d6ff: __inc_node_page_state (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

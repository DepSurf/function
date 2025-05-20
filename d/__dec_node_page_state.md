# Function: <code>__dec_node_page_state</code>

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
void __dec_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811c6e50)
Location: mm/vmstat.c:385
Inline: False
Direct callers:
  - mm/filemap.c:__delete_from_page_cache
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd
```
**Symbols:**

```
ffffffff811c6e50-ffffffff811c6e6f: __dec_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __dec_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811d6f70)
Location: mm/vmstat.c:385
Inline: False
Direct callers:
  - mm/filemap.c:__delete_from_page_cache
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd
```
**Symbols:**

```
ffffffff811d6f70-ffffffff811d6f8f: __dec_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __dec_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811dfdd0)
Location: mm/vmstat.c:385
Inline: False
Direct callers:
  - mm/filemap.c:__delete_from_page_cache
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd_locked
```
**Symbols:**

```
ffffffff811dfdd0-ffffffff811dfdef: __dec_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __dec_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811f5be0)
Location: mm/vmstat.c:460
Inline: False
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd
```
**Symbols:**

```
ffffffff811f5be0-ffffffff811f5bff: __dec_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __dec_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81216e60)
Location: mm/vmstat.c:460
Inline: False
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd
```
**Symbols:**

```
ffffffff81216e60-ffffffff81216e7f: __dec_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __dec_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81229d70)
Location: mm/vmstat.c:460
Inline: False
Direct callers:
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd_locked
```
**Symbols:**

```
ffffffff81229d70-ffffffff81229d8f: __dec_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __dec_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81239a00)
Location: mm/vmstat.c:461
Inline: False
Direct callers:
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd_locked
```
**Symbols:**

```
ffffffff81239a00-ffffffff81239a1f: __dec_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __dec_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81247d00)
Location: mm/vmstat.c:461
Inline: False
Direct callers:
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd_locked
```
**Symbols:**

```
ffffffff81247d00-ffffffff81247d1f: __dec_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __dec_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81275390)
Location: mm/vmstat.c:461
Inline: False
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff81275390-ffffffff81275402: __dec_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __dec_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8127f5f0)
Location: mm/vmstat.c:470
Inline: False
Direct callers:
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_remove_file_rmap
```
**Symbols:**

```
ffffffff8127f5f0-ffffffff8127f662: __dec_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __dec_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81284760)
Location: mm/vmstat.c:476
Inline: False
```
**Symbols:**

```
ffffffff81284760-ffffffff812847d2: __dec_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __dec_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812c3400)
Location: mm/vmstat.c:522
Inline: False
```
**Symbols:**

```
ffffffff812c3400-ffffffff812c34a6: __dec_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __dec_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81320730)
Location: mm/vmstat.c:551
Inline: False
```
**Symbols:**

```
ffffffff81320730-ffffffff813207f2: __dec_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __dec_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81394550)
Location: mm/vmstat.c:538
Inline: False
```
**Symbols:**

```
ffffffff81394550-ffffffff8139463e: __dec_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __dec_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813c7060)
Location: mm/vmstat.c:539
Inline: False
```
**Symbols:**

```
ffffffff813c7060-ffffffff813c714e: __dec_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __dec_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813f1090)
Location: mm/vmstat.c:538
Inline: False
```
**Symbols:**

```
ffffffff813f1090-ffffffff813f117e: __dec_node_page_state (STB_GLOBAL)
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
void __dec_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffff8000102dc470)
Location: mm/vmstat.c:461
Inline: False
Direct callers:
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd_locked
```
**Symbols:**

```
ffff8000102dc470-ffff8000102dc4b4: __dec_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __dec_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (c050241c)
Location: mm/vmstat.c:461
Inline: True
Inline callers:
  - mm/vmstat.c:dec_node_page_state
Direct callers:
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
```
**Symbols:**

```
c05023dc-c0502400: __dec_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __dec_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (c00000000039c19c)
Location: mm/vmstat.c:461
Inline: True
Inline callers:
  - mm/vmstat.c:dec_node_page_state
Direct callers:
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd_locked
```
**Symbols:**

```
c00000000039c140-c00000000039c168: __dec_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __dec_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffe0001f55de)
Location: mm/vmstat.c:461
Inline: True
Inline callers:
  - mm/vmstat.c:dec_node_page_state
Direct callers:
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
```
**Symbols:**

```
ffffffe0001f5590-ffffffe0001f55c2: __dec_node_page_state (STB_GLOBAL)
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
void __dec_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81240350)
Location: mm/vmstat.c:461
Inline: False
Direct callers:
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd_locked
```
**Symbols:**

```
ffffffff81240350-ffffffff8124036f: __dec_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __dec_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81233350)
Location: mm/vmstat.c:461
Inline: False
Direct callers:
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd_locked
```
**Symbols:**

```
ffffffff81233350-ffffffff8123336f: __dec_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __dec_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8123e0f0)
Location: mm/vmstat.c:461
Inline: False
Direct callers:
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd_locked
```
**Symbols:**

```
ffffffff8123e0f0-ffffffff8123e10f: __dec_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __dec_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8124d820)
Location: mm/vmstat.c:461
Inline: False
Direct callers:
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd_locked
```
**Symbols:**

```
ffffffff8124d820-ffffffff8124d83f: __dec_node_page_state (STB_GLOBAL)
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

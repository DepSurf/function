# Function: <code>__lruvec_stat_mod_folio</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812f2603)
Location: include/linux/vmstat.h:612
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/page-writeback.c (ffffffff812ff2a7)
Location: include/linux/vmstat.h:612
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_account_dirtied
```
```
In mm/shmem.c (ffffffff81317b20)
Location: include/linux/vmstat.h:612
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8135abc3)
Location: include/linux/vmstat.h:606
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/page-writeback.c (ffffffff81367917)
Location: include/linux/vmstat.h:606
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_account_dirtied
```
```
In mm/shmem.c (ffffffff8138abec)
Location: include/linux/vmstat.h:606
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff813f8bf9)
Location: include/linux/vmstat.h:606
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/huge_memory.c (ffffffff81441f9c)
Location: include/linux/vmstat.h:606
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8138c5e7)
Location: include/linux/vmstat.h:612
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/page-writeback.c (ffffffff81399db7)
Location: include/linux/vmstat.h:612
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_account_dirtied
```
```
In mm/shmem.c (ffffffff813bd112)
Location: include/linux/vmstat.h:612
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/rmap.c (ffffffff8140c9ae)
Location: include/linux/vmstat.h:612
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:folio_add_new_anon_rmap
  - mm/rmap.c:folio_add_new_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
```
```
In mm/swap_state.c (ffffffff8142b9bb)
Location: include/linux/vmstat.h:612
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/huge_memory.c (ffffffff814778e3)
Location: include/linux/vmstat.h:612
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __lruvec_stat_mod_folio(struct folio *folio, enum node_stat_item idx, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814bae40)
Location: mm/memcontrol.c:899
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/page-writeback.c:folio_account_dirtied
  - mm/page-writeback.c:lruvec_stat_mod_folio
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/rmap.c:folio_remove_rmap_pmd
  - mm/rmap.c:folio_remove_rmap_pmd
  - mm/rmap.c:folio_remove_rmap_ptes
  - mm/rmap.c:folio_add_file_rmap_pmd
  - mm/rmap.c:folio_add_file_rmap_pmd
  - mm/rmap.c:folio_add_file_rmap_ptes
  - mm/rmap.c:folio_add_new_anon_rmap
  - mm/rmap.c:folio_add_new_anon_rmap
  - mm/rmap.c:folio_add_anon_rmap_pmd
  - mm/rmap.c:folio_add_anon_rmap_pmd
  - mm/rmap.c:folio_add_anon_rmap_pmd
  - mm/rmap.c:folio_add_anon_rmap_ptes
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff814bae40-ffffffff814baeff: __lruvec_stat_mod_folio (STB_GLOBAL)
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
</ul>

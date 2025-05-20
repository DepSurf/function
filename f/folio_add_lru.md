# Function: <code>folio_add_lru</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
void folio_add_lru(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81306f50)
Location: mm/swap.c:456
Inline: False
Direct callers:
  - mm/filemap.c:filemap_add_folio
  - mm/folio-compat.c:lru_cache_add
  - mm/folio-compat.c:lru_cache_add
  - mm/vmscan.c:reclaim_page_list
  - mm/shmem.c:shmem_getpage_gfp
```
**Symbols:**

```
ffffffff81306f50-ffffffff81306fd7: folio_add_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void folio_add_lru(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8136fb10)
Location: mm/swap.c:531
Inline: False
Direct callers:
  - mm/filemap.c:filemap_add_folio
  - mm/swap.c:folio_add_lru_vma
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:reclaim_folio_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_folios_to_lru
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_replace_folio
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/khugepaged.c:collapse_file
  - mm/userfaultfd.c:mfill_atomic_install_pte
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff8136fb10-ffffffff8136fbca: folio_add_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void folio_add_lru(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff813a1c50)
Location: mm/swap.c:501
Inline: False
Direct callers:
  - mm/filemap.c:filemap_add_folio
  - mm/swap.c:folio_add_lru_vma
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:reclaim_folio_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_folios_to_lru
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_replace_folio
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/migrate.c:migrate_pages_batch
  - mm/khugepaged.c:collapse_file
  - mm/userfaultfd.c:mfill_atomic_install_pte
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff813a1c50-ffffffff813a1d41: folio_add_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void folio_add_lru(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff813cb8e0)
Location: mm/swap.c:501
Inline: False
Direct callers:
  - mm/filemap.c:filemap_add_folio
  - mm/swap.c:folio_add_lru_vma
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:reclaim_folio_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_folios_to_lru
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_alloc_and_add_folio
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/migrate.c:migrate_pages_batch
  - mm/khugepaged.c:collapse_file
  - mm/userfaultfd.c:mfill_atomic_install_pte
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff813cb8e0-ffffffff813cb9cf: folio_add_lru (STB_GLOBAL)
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

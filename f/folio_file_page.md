# Function: <code>folio_file_page</code>

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
In mm/filemap.c (ffffffff812f44ab)
Location: include/linux/pagemap.h:682
Inline: True
Inline callers:
  - mm/filemap.c:read_cache_page_gfp
  - mm/filemap.c:read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
```
```
In mm/folio-compat.c (ffffffff81300a49)
Location: include/linux/pagemap.h:682
Inline: True
Inline callers:
  - mm/folio-compat.c:pagecache_get_page
```
```
In fs/verity/enable.c (ffffffff81472092)
Location: include/linux/pagemap.h:682
Inline: True
Inline callers:
  - fs/verity/enable.c:read_file_data_page
```
```
In fs/iomap/buffered-io.c (ffffffff8148b5a6)
Location: include/linux/pagemap.h:682
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_iter
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
In mm/filemap.c (ffffffff8135e5a6)
Location: include/linux/pagemap.h:679
Inline: True
Inline callers:
  - mm/filemap.c:read_cache_page_gfp
  - mm/filemap.c:read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
```
```
In mm/folio-compat.c (ffffffff8136b314)
Location: include/linux/pagemap.h:679
Inline: True
Inline callers:
  - mm/folio-compat.c:pagecache_get_page
```
```
In mm/shmem.c (ffffffff8138d8f4)
Location: include/linux/pagemap.h:679
Inline: True
Inline callers:
  - mm/shmem.c:shmem_read_mapping_page_gfp
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_fault
```
```
In mm/memory.c (ffffffff813bbcde)
Location: include/linux/pagemap.h:679
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/swap_state.c (ffffffff813f96e8)
Location: include/linux/pagemap.h:679
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/swapfile.c (ffffffff813fd14d)
Location: include/linux/pagemap.h:679
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/khugepaged.c (ffffffff81449af1)
Location: include/linux/pagemap.h:679
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff814533be)
Location: include/linux/pagemap.h:679
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff8146d4f9)
Location: include/linux/pagemap.h:679
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
```
```
In fs/verity/enable.c (ffffffff815040d8)
Location: include/linux/pagemap.h:679
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
```
```
In fs/iomap/buffered-io.c (ffffffff8151f5fb)
Location: include/linux/pagemap.h:679
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_iter
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
In mm/filemap.c (ffffffff81391346)
Location: include/linux/pagemap.h:706
Inline: True
Inline callers:
  - mm/filemap.c:read_cache_page_gfp
  - mm/filemap.c:read_cache_page_gfp
  - mm/filemap.c:read_cache_page
  - mm/filemap.c:read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
```
```
In mm/folio-compat.c (ffffffff8139d482)
Location: include/linux/pagemap.h:706
Inline: True
Inline callers:
  - mm/folio-compat.c:pagecache_get_page
```
```
In mm/shmem.c (ffffffff813c02df)
Location: include/linux/pagemap.h:706
Inline: True
Inline callers:
  - mm/shmem.c:shmem_read_mapping_page_gfp
  - mm/shmem.c:shmem_read_mapping_page_gfp
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_fault
```
```
In mm/memory.c (ffffffff813f0702)
Location: include/linux/pagemap.h:706
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/swap_state.c (ffffffff8142c374)
Location: include/linux/pagemap.h:706
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/swapfile.c (ffffffff81430457)
Location: include/linux/pagemap.h:706
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/khugepaged.c (ffffffff8147fe7e)
Location: include/linux/pagemap.h:706
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff81488fd1)
Location: include/linux/pagemap.h:706
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff814a1f2e)
Location: include/linux/pagemap.h:706
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_continue
```
```
In fs/iomap/buffered-io.c (ffffffff815576c5)
Location: include/linux/pagemap.h:706
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_iter
```
```
In fs/ext4/verity.c (ffffffff81611dc9)
Location: include/linux/pagemap.h:706
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813bb0c1)
Location: include/linux/pagemap.h:824
Inline: True
Inline callers:
  - mm/filemap.c:read_cache_page_gfp
  - mm/filemap.c:read_cache_page
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:filemap_fault
```
```
In mm/folio-compat.c (ffffffff813c71ea)
Location: include/linux/pagemap.h:824
Inline: True
Inline callers:
  - mm/folio-compat.c:pagecache_get_page
```
```
In mm/shmem.c (ffffffff813eb336)
Location: include/linux/pagemap.h:824
Inline: True
Inline callers:
  - mm/shmem.c:shmem_read_mapping_page_gfp
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_fault
```
```
In mm/memory.c (ffffffff8142008e)
Location: include/linux/pagemap.h:824
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/swap_state.c (ffffffff81466870)
Location: include/linux/pagemap.h:824
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff81468e38)
Location: include/linux/pagemap.h:824
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/khugepaged.c (ffffffff814ad712)
Location: include/linux/pagemap.h:824
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff814b8f30)
Location: include/linux/pagemap.h:824
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff814d1812)
Location: include/linux/pagemap.h:824
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_continue
```
```
In fs/ext4/verity.c (ffffffff8164ab77)
Location: include/linux/pagemap.h:824
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
```
```
In drivers/gpu/drm/drm_gem.c (ffffffff81c9bf92)
Location: include/linux/pagemap.h:824
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem.c:drm_gem_get_pages
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

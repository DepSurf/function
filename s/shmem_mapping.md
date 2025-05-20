# Function: <code>shmem_mapping</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool shmem_mapping(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811ab960)
Location: mm/shmem.c:1501
Inline: False
Direct callers:
  - mm/mincore.c:mincore_page
  - mm/madvise.c:SyS_madvise
  - mm/memcontrol.c:get_mctgt_type
```
**Symbols:**

```
ffffffff811ab960-ffffffff811ab986: shmem_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool shmem_mapping(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811c42b0)
Location: mm/shmem.c:2158
Inline: False
Direct callers:
  - mm/mincore.c:mincore_page
  - mm/madvise.c:SyS_madvise
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:get_mctgt_type
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff811c42b0-ffffffff811c42d6: shmem_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool shmem_mapping(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811d43b0)
Location: mm/shmem.c:2176
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/mincore.c:mincore_page
  - mm/madvise.c:SyS_madvise
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:get_mctgt_type
```
**Symbols:**

```
ffffffff811d43b0-ffffffff811d43d6: shmem_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool shmem_mapping(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811dcb40)
Location: mm/shmem.c:2232
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/mincore.c:mincore_page
  - mm/madvise.c:madvise_willneed
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:get_mctgt_type
```
**Symbols:**

```
ffffffff811dcb40-ffffffff811dcb56: shmem_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool shmem_mapping(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811f29f0)
Location: mm/shmem.c:2243
Inline: False
Direct callers:
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:page_cache_tree_insert
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/workingset.c:shadow_lru_isolate
  - mm/mincore.c:mincore_page
  - mm/madvise.c:madvise_willneed
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:get_mctgt_type
```
**Symbols:**

```
ffffffff811f29f0-ffffffff811f2a06: shmem_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool shmem_mapping(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81213e50)
Location: mm/shmem.c:2264
Inline: False
Direct callers:
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:page_cache_tree_insert
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/workingset.c:shadow_lru_isolate
  - mm/mincore.c:mincore_page
  - mm/madvise.c:madvise_willneed
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/memcontrol.c:get_mctgt_type
  - mm/memfd.c:memfd_file_seals_ptr
```
**Symbols:**

```
ffffffff81213e50-ffffffff81213e66: shmem_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool shmem_mapping(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81226e10)
Location: mm/shmem.c:2226
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/mincore.c:mincore_page
  - mm/madvise.c:madvise_willneed
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:get_mctgt_type
  - mm/memfd.c:memfd_file_seals_ptr
  - fs/proc/task_mmu.c:smap_gather_stats
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffffffff81226e10-ffffffff81226e26: shmem_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool shmem_mapping(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81236970)
Location: mm/shmem.c:2307
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/mincore.c:mincore_page
  - mm/madvise.c:madvise_willneed
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:get_mctgt_type
  - mm/memfd.c:memfd_file_seals_ptr
  - fs/proc/task_mmu.c:smap_gather_stats
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffffffff81236970-ffffffff81236986: shmem_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool shmem_mapping(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81244bb0)
Location: mm/shmem.c:2327
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/mincore.c:mincore_page
  - mm/madvise.c:__do_sys_madvise
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/memcontrol.c:get_mctgt_type
  - mm/memfd.c:memfd_file_seals_ptr
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffffffff81244bb0-ffffffff81244bc6: shmem_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool shmem_mapping(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81272870)
Location: mm/shmem.c:2308
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__uprobe_register
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:page_cache_delete_batch
  - mm/filemap.c:page_cache_delete
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/mincore.c:mincore_page
  - mm/madvise.c:madvise_willneed
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/memcontrol.c:get_mctgt_type
  - fs/proc/task_mmu.c:smap_gather_stats
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffffffff81272870-ffffffff81272886: shmem_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812522f6)
Location: include/linux/shmem_fs.h:71
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__uprobe_register
```
```
In mm/filemap.c (ffffffff8125afb3)
Location: include/linux/shmem_fs.h:71
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:page_cache_delete_batch
  - mm/filemap.c:page_cache_delete
```
```
In mm/truncate.c (ffffffff8126b3df)
Location: include/linux/shmem_fs.h:71
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:__invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff8127a44f)
Location: include/linux/shmem_fs.h:71
Inline: True
Inline callers:
  - mm/shmem.c:shmem_read_mapping_page_gfp
  - mm/shmem.c:shmem_zero_setup
  - mm/shmem.c:shmem_mmap
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_evict_inode
```
```
In mm/madvise.c (ffffffff812c131c)
Location: include/linux/shmem_fs.h:71
Inline: True
```
```
In mm/swap_state.c (ffffffff812c4ee5)
Location: include/linux/shmem_fs.h:71
Inline: True
Inline callers:
  - mm/swap_state.c:find_get_incore_page
```
```
In mm/huge_memory.c (ffffffff812f5cc2)
Location: include/linux/shmem_fs.h:71
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812ff2b4)
Location: include/linux/shmem_fs.h:71
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff81317b71)
Location: include/linux/shmem_fs.h:71
Inline: True
Inline callers:
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
```
In fs/proc/task_mmu.c (ffffffff813c7c17)
Location: include/linux/shmem_fs.h:71
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8183db2d)
Location: include/linux/shmem_fs.h:71
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81256256)
Location: include/linux/shmem_fs.h:71
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__uprobe_register
```
```
In mm/filemap.c (ffffffff8125ec75)
Location: include/linux/shmem_fs.h:71
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:page_cache_delete_batch
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/truncate.c (ffffffff8127058a)
Location: include/linux/shmem_fs.h:71
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:__invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff8127f58f)
Location: include/linux/shmem_fs.h:71
Inline: True
Inline callers:
  - mm/shmem.c:shmem_read_mapping_page_gfp
  - mm/shmem.c:shmem_zero_setup
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_evict_inode
```
```
In mm/madvise.c (ffffffff812c80fb)
Location: include/linux/shmem_fs.h:71
Inline: True
```
```
In mm/swap_state.c (ffffffff812cbb8c)
Location: include/linux/shmem_fs.h:71
Inline: True
Inline callers:
  - mm/swap_state.c:find_get_incore_page
```
```
In mm/huge_memory.c (ffffffff812fc12a)
Location: include/linux/shmem_fs.h:71
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81305f31)
Location: include/linux/shmem_fs.h:71
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff8131dd61)
Location: include/linux/shmem_fs.h:71
Inline: True
Inline callers:
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
```
In fs/proc/task_mmu.c (ffffffff813ce8d7)
Location: include/linux/shmem_fs.h:71
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81820cbd)
Location: include/linux/shmem_fs.h:71
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81291f09)
Location: include/linux/shmem_fs.h:72
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__uprobe_register
```
```
In mm/filemap.c (ffffffff8129c098)
Location: include/linux/shmem_fs.h:72
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:page_cache_delete_batch
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/truncate.c (ffffffff812ae213)
Location: include/linux/shmem_fs.h:72
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:__invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff812bdaef)
Location: include/linux/shmem_fs.h:72
Inline: True
Inline callers:
  - mm/shmem.c:shmem_read_mapping_page_gfp
  - mm/shmem.c:shmem_zero_setup
  - mm/shmem.c:shmem_evict_inode
```
```
In mm/madvise.c (ffffffff8130d0dc)
Location: include/linux/shmem_fs.h:72
Inline: True
```
```
In mm/swap_state.c (ffffffff81310cb4)
Location: include/linux/shmem_fs.h:72
Inline: True
Inline callers:
  - mm/swap_state.c:find_get_incore_page
```
```
In mm/huge_memory.c (ffffffff81349340)
Location: include/linux/shmem_fs.h:72
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8134fd91)
Location: include/linux/shmem_fs.h:72
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff8136b101)
Location: include/linux/shmem_fs.h:72
Inline: True
Inline callers:
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
```
In fs/proc/task_mmu.c (ffffffff8141fc37)
Location: include/linux/shmem_fs.h:72
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffff818ab4e9)
Location: include/linux/shmem_fs.h:72
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812e7728)
Location: include/linux/shmem_fs.h:73
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__uprobe_register
```
```
In mm/filemap.c (ffffffff812f2441)
Location: include/linux/shmem_fs.h:73
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__filemap_remove_folio
```
```
In mm/truncate.c (ffffffff813076c2)
Location: include/linux/shmem_fs.h:73
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pagevec
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff813198b6)
Location: include/linux/shmem_fs.h:73
Inline: True
Inline callers:
  - mm/shmem.c:shmem_read_mapping_page_gfp
  - mm/shmem.c:shmem_evict_inode
```
```
In mm/madvise.c (ffffffff8137856d)
Location: include/linux/shmem_fs.h:73
Inline: True
Inline callers:
  - mm/madvise.c:madvise_vma_behavior
```
```
In mm/swap_state.c (ffffffff8137bae6)
Location: include/linux/shmem_fs.h:73
Inline: True
Inline callers:
  - mm/swap_state.c:find_get_incore_page
```
```
In mm/huge_memory.c (ffffffff813bf70b)
Location: include/linux/shmem_fs.h:73
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/khugepaged.c (ffffffff813c7faa)
Location: include/linux/shmem_fs.h:73
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (ffffffff813d958b)
Location: include/linux/shmem_fs.h:73
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_clean
```
```
In mm/memfd.c (ffffffff813e90ac)
Location: include/linux/shmem_fs.h:73
Inline: True
Inline callers:
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
```
In fs/proc/task_mmu.c (ffffffff81497b5f)
Location: include/linux/shmem_fs.h:73
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffff819f5c81)
Location: include/linux/shmem_fs.h:73
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
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
In kernel/events/uprobes.c (ffffffff81351278)
Location: include/linux/shmem_fs.h:79
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__uprobe_register
```
```
In mm/filemap.c (ffffffff8135aa47)
Location: include/linux/shmem_fs.h:79
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__filemap_remove_folio
```
```
In mm/truncate.c (ffffffff81371824)
Location: include/linux/shmem_fs.h:79
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pagevec
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff813774ed)
Location: include/linux/shmem_fs.h:79
Inline: True
Inline callers:
  - mm/vmscan.c:should_skip_vma
```
```
In mm/shmem.c (ffffffff8138d87a)
Location: include/linux/shmem_fs.h:79
Inline: True
Inline callers:
  - mm/shmem.c:shmem_read_mapping_page_gfp
  - mm/shmem.c:shmem_evict_inode
```
```
In mm/madvise.c (ffffffff813f5cd8)
Location: include/linux/shmem_fs.h:79
Inline: True
Inline callers:
  - mm/madvise.c:madvise_vma_behavior
```
```
In mm/swap_state.c (ffffffff813f946a)
Location: include/linux/shmem_fs.h:79
Inline: True
Inline callers:
  - mm/swap_state.c:filemap_get_incore_folio
```
```
In mm/huge_memory.c (ffffffff81441c66)
Location: include/linux/shmem_fs.h:79
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:hugepage_vma_check
```
```
In mm/khugepaged.c (ffffffff8144939d)
Location: include/linux/shmem_fs.h:79
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (ffffffff8145f86b)
Location: include/linux/shmem_fs.h:79
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_clean
```
```
In mm/memfd.c (ffffffff81471027)
Location: include/linux/shmem_fs.h:79
Inline: True
Inline callers:
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
```
In fs/proc/task_mmu.c (ffffffff8152bffc)
Location: include/linux/shmem_fs.h:79
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81b73243)
Location: include/linux/shmem_fs.h:79
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
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
In kernel/events/uprobes.c (ffffffff813824e5)
Location: include/linux/shmem_fs.h:81
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__uprobe_register
```
```
In mm/filemap.c (ffffffff8138cc4c)
Location: include/linux/shmem_fs.h:81
Inline: True
Inline callers:
  - mm/filemap.c:filemap_cachestat
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__filemap_remove_folio
```
```
In mm/truncate.c (ffffffff813a3934)
Location: include/linux/shmem_fs.h:81
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:mapping_try_invalidate
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff813a93d6)
Location: include/linux/shmem_fs.h:81
Inline: True
Inline callers:
  - mm/vmscan.c:should_skip_vma
```
```
In mm/shmem.c (ffffffff813c0236)
Location: include/linux/shmem_fs.h:81
Inline: True
Inline callers:
  - mm/shmem.c:shmem_read_folio_gfp
  - mm/shmem.c:shmem_evict_inode
```
```
In mm/gup.c (ffffffff813e2703)
Location: include/linux/shmem_fs.h:81
Inline: True
Inline callers:
  - mm/gup.c:folio_fast_pin_allowed
```
```
In mm/madvise.c (ffffffff81428bb2)
Location: include/linux/shmem_fs.h:81
Inline: True
Inline callers:
  - mm/madvise.c:madvise_vma_behavior
```
```
In mm/swap_state.c (ffffffff8142c1c3)
Location: include/linux/shmem_fs.h:81
Inline: True
Inline callers:
  - mm/swap_state.c:filemap_get_incore_folio
```
```
In mm/huge_memory.c (ffffffff81477606)
Location: include/linux/shmem_fs.h:81
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:hugepage_vma_check
```
```
In mm/khugepaged.c (ffffffff8147f4e3)
Location: include/linux/shmem_fs.h:81
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (ffffffff81495a7b)
Location: include/linux/shmem_fs.h:81
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_clean
```
```
In mm/memfd.c (ffffffff814a6007)
Location: include/linux/shmem_fs.h:81
Inline: True
Inline callers:
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
```
In fs/proc/task_mmu.c (ffffffff815643bf)
Location: include/linux/shmem_fs.h:81
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81bc6ca9)
Location: include/linux/shmem_fs.h:81
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
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
In kernel/events/uprobes.c (ffffffff813ab8c5)
Location: include/linux/shmem_fs.h:101
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__uprobe_register
```
```
In mm/filemap.c (ffffffff813b6650)
Location: include/linux/shmem_fs.h:101
Inline: True
Inline callers:
  - mm/filemap.c:filemap_cachestat
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__filemap_remove_folio
```
```
In mm/truncate.c (ffffffff813cd5e4)
Location: include/linux/shmem_fs.h:101
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:mapping_try_invalidate
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff813d2dd6)
Location: include/linux/shmem_fs.h:101
Inline: True
Inline callers:
  - mm/vmscan.c:should_skip_vma
```
```
In mm/shmem.c (ffffffff813eb2f8)
Location: include/linux/shmem_fs.h:101
Inline: True
Inline callers:
  - mm/shmem.c:shmem_read_mapping_page_gfp
  - mm/shmem.c:shmem_evict_inode
```
```
In mm/gup.c (ffffffff8140cf31)
Location: include/linux/shmem_fs.h:101
Inline: True
```
```
In mm/madvise.c (ffffffff814623e2)
Location: include/linux/shmem_fs.h:101
Inline: True
Inline callers:
  - mm/madvise.c:madvise_vma_behavior
```
```
In mm/swap_state.c (ffffffff81465923)
Location: include/linux/shmem_fs.h:101
Inline: True
Inline callers:
  - mm/swap_state.c:filemap_get_incore_folio
```
```
In mm/huge_memory.c (ffffffff814a6d83)
Location: include/linux/shmem_fs.h:101
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__thp_vma_allowable_orders
```
```
In mm/khugepaged.c (ffffffff814ad513)
Location: include/linux/shmem_fs.h:101
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (ffffffff814c5251)
Location: include/linux/shmem_fs.h:101
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_clean
```
```
In mm/memfd.c (ffffffff814d6f28)
Location: include/linux/shmem_fs.h:101
Inline: True
Inline callers:
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
```
In fs/proc/task_mmu.c (ffffffff8159aa0f)
Location: include/linux/shmem_fs.h:101
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81c1b818)
Location: include/linux/shmem_fs.h:101
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
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
bool shmem_mapping(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffff8000102d7220)
Location: mm/shmem.c:2327
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/mincore.c:mincore_page
  - mm/madvise.c:__arm64_sys_madvise
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/memcontrol.c:get_mctgt_type
  - mm/memfd.c:memfd_file_seals_ptr
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffff8000102d7220-ffff8000102d725c: shmem_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool shmem_mapping(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c04ff050)
Location: mm/shmem.c:2327
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/mincore.c:mincore_page
  - mm/madvise.c:__se_sys_madvise
  - mm/memcontrol.c:get_mctgt_type
  - mm/memfd.c:__se_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
c04ff050-c04ff080: shmem_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool shmem_mapping(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c000000000397460)
Location: mm/shmem.c:2327
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/mincore.c:mincore_page
  - mm/madvise.c:__se_sys_madvise
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/memcontrol.c:get_mctgt_type
  - mm/memfd.c:memfd_file_seals_ptr
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
c000000000397460-c00000000039748c: shmem_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool shmem_mapping(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffe0001f24f4)
Location: mm/shmem.c:2327
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/mincore.c:mincore_page
  - mm/madvise.c:__se_sys_madvise
  - mm/memcontrol.c:get_mctgt_type
  - mm/memfd.c:memfd_file_seals_ptr
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffffffe0001f24f4-ffffffe0001f2524: shmem_mapping (STB_GLOBAL)
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
bool shmem_mapping(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8123d200)
Location: mm/shmem.c:2327
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/mincore.c:mincore_page
  - mm/madvise.c:__do_sys_madvise
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/memcontrol.c:get_mctgt_type
  - mm/memfd.c:memfd_file_seals_ptr
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffffffff8123d200-ffffffff8123d216: shmem_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool shmem_mapping(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81230200)
Location: mm/shmem.c:2327
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/mincore.c:mincore_page
  - mm/madvise.c:__do_sys_madvise
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/memcontrol.c:get_mctgt_type
  - mm/memfd.c:memfd_file_seals_ptr
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffffffff81230200-ffffffff81230216: shmem_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool shmem_mapping(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8123afa0)
Location: mm/shmem.c:2327
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/mincore.c:mincore_page
  - mm/madvise.c:__do_sys_madvise
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/memcontrol.c:get_mctgt_type
  - mm/memfd.c:memfd_file_seals_ptr
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffffffff8123afa0-ffffffff8123afb6: shmem_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool shmem_mapping(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8124a6b0)
Location: mm/shmem.c:2327
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/mincore.c:mincore_page
  - mm/madvise.c:__do_sys_madvise
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/memcontrol.c:get_mctgt_type
  - mm/memfd.c:memfd_file_seals_ptr
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffffffff8124a6b0-ffffffff8124a6c6: shmem_mapping (STB_GLOBAL)
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

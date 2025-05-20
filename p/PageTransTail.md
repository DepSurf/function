# Function: <code>PageTransTail</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81202748)
Location: include/linux/page-flags.h:482
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811a1cd5)
Location: include/linux/page-flags.h:561
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_contig
```
```
In mm/truncate.c (ffffffff811b43de)
Location: include/linux/page-flags.h:561
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff811c1f08)
Location: include/linux/page-flags.h:561
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/debug.c (ffffffff811d44b1)
Location: include/linux/page-flags.h:561
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/mlock.c (ffffffff811df11d)
Location: include/linux/page-flags.h:561
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/rmap.c (ffffffff811e6b71)
Location: include/linux/page-flags.h:561
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_mapped_in_vma
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory-failure.c (ffffffff81226c6c)
Location: include/linux/page-flags.h:561
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b1ae6)
Location: include/linux/page-flags.h:577
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_contig
```
```
In mm/truncate.c (ffffffff811c4a6e)
Location: include/linux/page-flags.h:577
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff811d1fd8)
Location: include/linux/page-flags.h:577
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/debug.c (ffffffff811e4506)
Location: include/linux/page-flags.h:577
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/mlock.c (ffffffff811eef34)
Location: include/linux/page-flags.h:577
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/page_vma_mapped.c (ffffffff811f6d7d)
Location: include/linux/page-flags.h:577
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff811f7f11)
Location: include/linux/page-flags.h:577
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_mapped_in_vma
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory-failure.c (ffffffff81239205)
Location: include/linux/page-flags.h:577
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b7d3a)
Location: include/linux/page-flags.h:580
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_contig
```
```
In mm/truncate.c (ffffffff811ccd4a)
Location: include/linux/page-flags.h:580
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff811daa9b)
Location: include/linux/page-flags.h:580
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/debug.c (ffffffff811ee962)
Location: include/linux/page-flags.h:580
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/mlock.c (ffffffff811f9e27)
Location: include/linux/page-flags.h:580
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/page_vma_mapped.c (ffffffff812021e9)
Location: include/linux/page-flags.h:580
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8120347b)
Location: include/linux/page-flags.h:580
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory-failure.c (ffffffff81245695)
Location: include/linux/page-flags.h:580
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811cc3a2)
Location: include/linux/page-flags.h:581
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_contig
```
```
In mm/truncate.c (ffffffff811e1fde)
Location: include/linux/page-flags.h:581
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff811f084e)
Location: include/linux/page-flags.h:581
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/debug.c (ffffffff81204dd2)
Location: include/linux/page-flags.h:581
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/mlock.c (ffffffff81212277)
Location: include/linux/page-flags.h:581
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/page_vma_mapped.c (ffffffff8121ade9)
Location: include/linux/page-flags.h:581
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8121bfbb)
Location: include/linux/page-flags.h:581
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory-failure.c (ffffffff812655a3)
Location: include/linux/page-flags.h:581
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ed75e)
Location: include/linux/page-flags.h:588
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_contig
```
```
In mm/truncate.c (ffffffff81203745)
Location: include/linux/page-flags.h:588
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff81212394)
Location: include/linux/page-flags.h:588
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/debug.c (ffffffff81225d15)
Location: include/linux/page-flags.h:588
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/mlock.c (ffffffff81232faf)
Location: include/linux/page-flags.h:588
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/page_vma_mapped.c (ffffffff8123cc39)
Location: include/linux/page-flags.h:588
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8123e049)
Location: include/linux/page-flags.h:588
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory-failure.c (ffffffff81288d2b)
Location: include/linux/page-flags.h:588
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:add_to_kill
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811fedbe)
Location: include/linux/page-flags.h:605
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_contig
```
```
In mm/truncate.c (ffffffff81216015)
Location: include/linux/page-flags.h:605
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff81223e54)
Location: include/linux/page-flags.h:605
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/debug.c (ffffffff812393d9)
Location: include/linux/page-flags.h:605
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/mlock.c (ffffffff81246782)
Location: include/linux/page-flags.h:605
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/page_vma_mapped.c (ffffffff81251109)
Location: include/linux/page-flags.h:605
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff812525dc)
Location: include/linux/page-flags.h:605
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory-failure.c (ffffffff8129dc7b)
Location: include/linux/page-flags.h:605
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:add_to_kill
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81225a15)
Location: include/linux/page-flags.h:638
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff81234459)
Location: include/linux/page-flags.h:638
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/debug.c (ffffffff8124a439)
Location: include/linux/page-flags.h:638
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/mlock.c (ffffffff81258a3d)
Location: include/linux/page-flags.h:638
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/page_vma_mapped.c (ffffffff812633e9)
Location: include/linux/page-flags.h:638
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8126476a)
Location: include/linux/page-flags.h:638
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory-failure.c (ffffffff812b8e07)
Location: include/linux/page-flags.h:638
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81233865)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff81242689)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/debug.c (ffffffff81258990)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/mlock.c (ffffffff81266f0d)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/page_vma_mapped.c (ffffffff81271b99)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff81272fda)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory-failure.c (ffffffff812cbf30)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81260f8a)
Location: include/linux/page-flags.h:670
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/debug.c (ffffffff8128757a)
Location: include/linux/page-flags.h:670
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/mlock.c (ffffffff81297183)
Location: include/linux/page-flags.h:670
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/page_vma_mapped.c (ffffffff812a21c9)
Location: include/linux/page-flags.h:670
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff812a400a)
Location: include/linux/page-flags.h:670
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
```
```
In mm/hugetlb.c (ffffffff812c4096)
Location: include/linux/page-flags.h:670
Inline: True
```
```
In mm/memory-failure.c (ffffffff813020e3)
Location: include/linux/page-flags.h:670
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:collect_procs_file
  - mm/memory-failure.c:collect_procs_anon
  - mm/memory-failure.c:dev_pagemap_mapping_shift
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
In mm/truncate.c (ffffffff8126b38a)
Location: include/linux/page-flags.h:674
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:__invalidate_mapping_pages
  - mm/truncate.c:__invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8127015e)
Location: include/linux/page-flags.h:674
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/debug.c (ffffffff81be7462)
Location: include/linux/page-flags.h:674
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/mlock.c (ffffffff812a2133)
Location: include/linux/page-flags.h:674
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/page_vma_mapped.c (ffffffff812adaf9)
Location: include/linux/page-flags.h:674
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff812af8da)
Location: include/linux/page-flags.h:674
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory-failure.c (ffffffff8130e8d8)
Location: include/linux/page-flags.h:674
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:collect_procs_file
  - mm/memory-failure.c:collect_procs_anon
  - mm/memory-failure.c:dev_pagemap_mapping_shift
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
In kernel/futex.c (ffffffff81158901)
Location: include/linux/page-flags.h:668
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In mm/truncate.c (ffffffff8127047f)
Location: include/linux/page-flags.h:668
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff81275f51)
Location: include/linux/page-flags.h:668
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/debug.c (ffffffff81bd95cf)
Location: include/linux/page-flags.h:668
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/mlock.c (ffffffff812a79c3)
Location: include/linux/page-flags.h:668
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/page_vma_mapped.c (ffffffff812b2fa1)
Location: include/linux/page-flags.h:668
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff812b4bf4)
Location: include/linux/page-flags.h:668
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory-failure.c (ffffffff81314d86)
Location: include/linux/page-flags.h:668
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:dev_pagemap_mapping_shift
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
In kernel/futex.c (ffffffff8117d808)
Location: include/linux/page-flags.h:651
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In mm/truncate.c (ffffffff812ae115)
Location: include/linux/page-flags.h:651
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff812b25ce)
Location: include/linux/page-flags.h:651
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/debug.c (ffffffff81cbbd55)
Location: include/linux/page-flags.h:651
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/mlock.c (ffffffff812e8fe3)
Location: include/linux/page-flags.h:651
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/page_vma_mapped.c (ffffffff812f4b31)
Location: include/linux/page-flags.h:651
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff812f6a44)
Location: include/linux/page-flags.h:651
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory-failure.c (ffffffff81360e26)
Location: include/linux/page-flags.h:651
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:dev_pagemap_mapping_shift
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
In kernel/futex/core.c (ffffffff811b2a70)
Location: include/linux/page-flags.h:874
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In mm/vmscan.c (ffffffff8130f3a9)
Location: include/linux/page-flags.h:874
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/debug.c (ffffffff8133697b)
Location: include/linux/page-flags.h:874
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/page_vma_mapped.c (ffffffff81357d98)
Location: include/linux/page-flags.h:874
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:vma_address
```
```
In mm/rmap.c (ffffffff8135bbe9)
Location: include/linux/page-flags.h:874
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
```
```
In mm/ksm.c (ffffffff813a04f5)
Location: include/linux/page-flags.h:874
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/memory-failure.c (ffffffff813da601)
Location: include/linux/page-flags.h:874
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
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
In kernel/futex/core.c (ffffffff811f3910)
Location: include/linux/page-flags.h:871
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In mm/vmscan.c (ffffffff8137ebcf)
Location: include/linux/page-flags.h:871
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/debug.c (ffffffff813adc11)
Location: include/linux/page-flags.h:871
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/page_vma_mapped.c (ffffffff813d31d1)
Location: include/linux/page-flags.h:871
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
```
```
In mm/rmap.c (ffffffff813d68a4)
Location: include/linux/page-flags.h:871
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
```
```
In mm/ksm.c (ffffffff8141fd03)
Location: include/linux/page-flags.h:871
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/memory-failure.c (ffffffff81460fc6)
Location: include/linux/page-flags.h:871
Inline: True
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
In kernel/futex/core.c (ffffffff81208097)
Location: include/linux/page-flags.h:855
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In mm/debug.c (ffffffff813e1fa2)
Location: include/linux/page-flags.h:855
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/page_vma_mapped.c (ffffffff814070f3)
Location: include/linux/page-flags.h:855
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:vma_address
```
```
In mm/rmap.c (ffffffff8140b3d3)
Location: include/linux/page-flags.h:855
Inline: True
Inline callers:
  - mm/rmap.c:vma_address
```
```
In mm/ksm.c (ffffffff81454917)
Location: include/linux/page-flags.h:855
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/memory-failure.c (ffffffff81497ae9)
Location: include/linux/page-flags.h:855
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs_anon
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
In mm/debug.c (ffffffff8140c7b8)
Location: include/linux/page-flags.h:885
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/page_vma_mapped.c (ffffffff81433786)
Location: include/linux/page-flags.h:885
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:vma_address
```
```
In mm/rmap.c (ffffffff81437d06)
Location: include/linux/page-flags.h:885
Inline: True
Inline callers:
  - mm/rmap.c:vma_address
```
```
In mm/ksm.c (ffffffff8148fb44)
Location: include/linux/page-flags.h:885
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/memory-failure.c (ffffffff814c71e0)
Location: include/linux/page-flags.h:885
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs_anon
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffff8000102c3d40)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffff8000102d499c)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/debug.c (ffff8000102f09ac)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/mlock.c (ffff8000102fe16c)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/page_vma_mapped.c (ffff800010307694)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffff800010308d20)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory-failure.c (ffff80001036f5b4)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/truncate.c (0)
Location: include/linux/page-flags.h:704
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/page-flags.h:704
Inline: True
```
```
In mm/debug.c (0)
Location: include/linux/page-flags.h:704
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/page-flags.h:704
Inline: True
```
```
In mm/page_vma_mapped.c (0)
Location: include/linux/page-flags.h:704
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/page-flags.h:704
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/truncate.c (c00000000037e194)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (c0000000003942a8)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/debug.c (c0000000003b5160)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/mlock.c (c0000000003c9888)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/page_vma_mapped.c (c0000000003d61c0)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (c0000000003d7f80)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory-failure.c (c000000000461118)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:add_to_kill
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/truncate.c (0)
Location: include/linux/page-flags.h:704
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/page-flags.h:704
Inline: True
```
```
In mm/debug.c (0)
Location: include/linux/page-flags.h:704
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/page-flags.h:704
Inline: True
```
```
In mm/page_vma_mapped.c (0)
Location: include/linux/page-flags.h:704
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/page-flags.h:704
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8122beb5)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff8123acd9)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/debug.c (ffffffff81250fe0)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/mlock.c (ffffffff8125f55d)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/page_vma_mapped.c (ffffffff8126a1e9)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8126b62a)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory-failure.c (ffffffff812c4510)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8121ef95)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff8122dcd9)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/debug.c (ffffffff81243f20)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/mlock.c (ffffffff8125197d)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/page_vma_mapped.c (ffffffff8125c3d9)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8125d8ca)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory-failure.c (ffffffff812b5550)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:add_to_kill
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81229c55)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff81238a79)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/debug.c (ffffffff8124ed80)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/mlock.c (ffffffff8125d2fd)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/page_vma_mapped.c (ffffffff81267f89)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff812693ca)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory-failure.c (ffffffff812c2320)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81239050)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff812480f9)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/debug.c (ffffffff8125e700)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/mlock.c (ffffffff8126cce8)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/page_vma_mapped.c (ffffffff81277909)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff81278ef5)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory-failure.c (ffffffff812d2dab)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
</details>
</li>
</ul>

## Differences

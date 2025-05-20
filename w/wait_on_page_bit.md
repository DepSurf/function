# Function: <code>wait_on_page_bit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void wait_on_page_bit(struct page *page, int bit_nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8118c910)
Location: mm/filemap.c:746
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/filemap.c:wait_on_page_read
  - mm/filemap.c:filemap_fault
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_one_page
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_getpage_gfp
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/hugetlb.c:hugetlb_fault
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:migrate_pages
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:soft_offline_page
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff8118c910-ffffffff8118c9f1: wait_on_page_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void wait_on_page_bit(struct page *page, int bit_nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8119f900)
Location: mm/filemap.c:786
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_getpage_gfp
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/hugetlb.c:hugetlb_fault
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:__migration_entry_wait
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff8119f900-ffffffff8119f9dd: wait_on_page_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void wait_on_page_bit(struct page *page, int bit_nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b0f90)
Location: mm/filemap.c:883
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:__filemap_fdatawait_range
Direct callers:
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_getpage_gfp
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/hugetlb.c:hugetlb_fault
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:__migration_entry_wait
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff811b01a0-ffffffff811b02da: wait_on_page_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void wait_on_page_bit(struct page *page, int bit_nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b83e2)
Location: mm/filemap.c:1009
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:__filemap_fdatawait_range
Direct callers:
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_getpage_gfp
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/hugetlb.c:hugetlb_fault
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:__migration_entry_wait
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff811b7680-ffffffff811b77ad: wait_on_page_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void wait_on_page_bit(struct page *page, int bit_nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ccb80)
Location: mm/filemap.c:1130
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:__filemap_fdatawait_range
Direct callers:
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_getpage_gfp
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/hugetlb.c:hugetlb_fault
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff811cb6c0-ffffffff811cb7ed: wait_on_page_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void wait_on_page_bit(struct page *page, int bit_nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811edd03)
Location: mm/filemap.c:1130
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:__filemap_fdatawait_range
Direct callers:
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_getpage_gfp
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/hugetlb.c:hugetlb_fault
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/memory-failure.c:soft_offline_page
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff811eccc0-ffffffff811ecdf1: wait_on_page_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void wait_on_page_bit(struct page *page, int bit_nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ff2bc)
Location: mm/filemap.c:1164
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:__filemap_fdatawait_range
Direct callers:
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_getpage_gfp
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/hugetlb.c:hugetlb_fault
  - mm/migrate.c:migrate_pages
  - mm/memory-failure.c:soft_offline_page
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff811fdc00-ffffffff811fde0a: wait_on_page_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void wait_on_page_bit(struct page *page, int bit_nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121631e)
Location: mm/filemap.c:1212
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:__lock_page_or_retry
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
```
**Symbols:**

```
ffffffff81214c70-ffffffff81214e68: wait_on_page_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void wait_on_page_bit(struct page *page, int bit_nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81223c2e)
Location: mm/filemap.c:1221
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:__lock_page_or_retry
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
```
**Symbols:**

```
ffffffff812224a0-ffffffff81222698: wait_on_page_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void wait_on_page_bit(struct page *page, int bit_nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81252bf5)
Location: mm/filemap.c:1196
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:__lock_page_or_retry
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
```
**Symbols:**

```
ffffffff8124faa0-ffffffff8124fae1: wait_on_page_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void wait_on_page_bit(struct page *page, int bit_nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125d7c5)
Location: mm/filemap.c:1335
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:__lock_page_or_retry
Direct callers:
  - mm/page-writeback.c:wait_on_page_writeback
  - mm/hugetlb.c:hugetlb_fault
```
**Symbols:**

```
ffffffff8125aa50-ffffffff8125aa91: wait_on_page_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void wait_on_page_bit(struct page *page, int bit_nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8126058e)
Location: mm/filemap.c:1359
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:wait_on_page_private_2
Direct callers:
  - mm/page-writeback.c:wait_on_page_writeback
  - mm/hugetlb.c:hugetlb_fault
```
**Symbols:**

```
ffffffff8125f2d0-ffffffff8125f311: wait_on_page_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void wait_on_page_bit(struct page *page, int bit_nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8129cf7f)
Location: mm/filemap.c:1414
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:wait_on_page_private_2
Direct callers:
  - mm/page-writeback.c:wait_on_page_writeback
  - mm/hugetlb.c:hugetlb_fault
```
**Symbols:**

```
ffffffff8129ba50-ffffffff8129ba91: wait_on_page_bit (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
void wait_on_page_bit(struct page *page, int bit_nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102b1638)
Location: mm/filemap.c:1221
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:__lock_page_or_retry
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
```
**Symbols:**

```
ffff8000102af888-ffff8000102af8ec: wait_on_page_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void wait_on_page_bit(struct page *page, int bit_nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04ddfd8)
Location: mm/filemap.c:1221
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:__lock_page_or_retry
```
**Symbols:**

```
c04dc00c-c04dc28c: wait_on_page_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void wait_on_page_bit(struct page *page, int bit_nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c000000000366e80)
Location: mm/filemap.c:1221
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:__lock_page_or_retry
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
```
**Symbols:**

```
c000000000364160-c000000000364480: wait_on_page_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void wait_on_page_bit(struct page *page, int bit_nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d6cdc)
Location: mm/filemap.c:1221
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:__lock_page_or_retry
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
```
**Symbols:**

```
ffffffe0001d5e1c-ffffffe0001d6032: wait_on_page_bit (STB_GLOBAL)
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
void wait_on_page_bit(struct page *page, int bit_nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121c27e)
Location: mm/filemap.c:1221
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:__lock_page_or_retry
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
```
**Symbols:**

```
ffffffff8121aaf0-ffffffff8121ace8: wait_on_page_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void wait_on_page_bit(struct page *page, int bit_nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8120f46e)
Location: mm/filemap.c:1221
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:__lock_page_or_retry
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
```
**Symbols:**

```
ffffffff8120dcf0-ffffffff8120dee2: wait_on_page_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void wait_on_page_bit(struct page *page, int bit_nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121a01e)
Location: mm/filemap.c:1221
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:__lock_page_or_retry
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
```
**Symbols:**

```
ffffffff81218890-ffffffff81218a88: wait_on_page_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void wait_on_page_bit(struct page *page, int bit_nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8122910e)
Location: mm/filemap.c:1221
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:__lock_page_or_retry
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
```
**Symbols:**

```
ffffffff81227960-ffffffff81227b76: wait_on_page_bit (STB_GLOBAL)
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

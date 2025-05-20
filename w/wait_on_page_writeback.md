# Function: <code>wait_on_page_writeback</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8118cadd)
Location: include/linux/pagemap.h:527
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff81198b8a)
Location: include/linux/pagemap.h:527
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_one_page
```
```
In mm/truncate.c (ffffffff8119e9e8)
Location: include/linux/pagemap.h:527
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff811a3260)
Location: include/linux/pagemap.h:527
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff811a94c5)
Location: include/linux/pagemap.h:527
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/swapfile.c (ffffffff811d55ea)
Location: include/linux/pagemap.h:527
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
```
In mm/migrate.c (ffffffff811f2667)
Location: include/linux/pagemap.h:527
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/memory-failure.c (ffffffff8120277c)
Location: include/linux/pagemap.h:527
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:soft_offline_page
```
```
In fs/splice.c (ffffffff8123e7d8)
Location: include/linux/pagemap.h:527
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/ext4/inode.c (ffffffff81297d97)
Location: include/linux/pagemap.h:527
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
```
In fs/ext4/move_extent.c (ffffffff812d6937)
Location: include/linux/pagemap.h:527
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
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
In mm/filemap.c (ffffffff8119fac3)
Location: include/linux/pagemap.h:504
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff811afd1f)
Location: include/linux/pagemap.h:504
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff811b4489)
Location: include/linux/pagemap.h:504
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff811b9a2c)
Location: include/linux/pagemap.h:504
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff811c1144)
Location: include/linux/pagemap.h:504
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/swapfile.c (ffffffff811f3ada)
Location: include/linux/pagemap.h:504
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
```
In mm/migrate.c (ffffffff81211f42)
Location: include/linux/pagemap.h:504
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/memory-failure.c (ffffffff81227c26)
Location: include/linux/pagemap.h:504
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
```
```
In fs/splice.c (ffffffff8126653a)
Location: include/linux/pagemap.h:504
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/ext4/inode.c (ffffffff812c52e5)
Location: include/linux/pagemap.h:504
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
```
In fs/ext4/move_extent.c (ffffffff813065c6)
Location: include/linux/pagemap.h:504
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
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
In mm/filemap.c (ffffffff811afcf8)
Location: include/linux/pagemap.h:522
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff811c03df)
Location: include/linux/pagemap.h:522
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff811c4b28)
Location: include/linux/pagemap.h:522
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff811ca09c)
Location: include/linux/pagemap.h:522
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff811d174d)
Location: include/linux/pagemap.h:522
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/swapfile.c (ffffffff8120460d)
Location: include/linux/pagemap.h:522
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
```
In mm/migrate.c (ffffffff81224110)
Location: include/linux/pagemap.h:522
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/memory-failure.c (ffffffff8123a1c1)
Location: include/linux/pagemap.h:522
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
```
```
In fs/splice.c (ffffffff8127a29a)
Location: include/linux/pagemap.h:522
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/ext4/inode.c (ffffffff812da995)
Location: include/linux/pagemap.h:522
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
```
In fs/ext4/move_extent.c (ffffffff8131c586)
Location: include/linux/pagemap.h:522
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
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
In mm/filemap.c (ffffffff811b6d82)
Location: include/linux/pagemap.h:530
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff811c859b)
Location: include/linux/pagemap.h:530
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff811ccd6d)
Location: include/linux/pagemap.h:530
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff811d2bc0)
Location: include/linux/pagemap.h:530
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff811da03a)
Location: include/linux/pagemap.h:530
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/swapfile.c (ffffffff8120fa51)
Location: include/linux/pagemap.h:530
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
```
In mm/migrate.c (ffffffff8122fab4)
Location: include/linux/pagemap.h:530
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/memory-failure.c (ffffffff81245d93)
Location: include/linux/pagemap.h:530
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
```
```
In fs/splice.c (ffffffff8128779b)
Location: include/linux/pagemap.h:530
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/ext4/inode.c (ffffffff812fe7a5)
Location: include/linux/pagemap.h:530
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
```
In fs/ext4/move_extent.c (ffffffff81315152)
Location: include/linux/pagemap.h:530
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
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
In mm/filemap.c (ffffffff811caea8)
Location: include/linux/pagemap.h:543
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff811db09d)
Location: include/linux/pagemap.h:543
Inline: True
Inline callers:
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff811e20e9)
Location: include/linux/pagemap.h:543
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff811e80f4)
Location: include/linux/pagemap.h:543
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff811efd68)
Location: include/linux/pagemap.h:543
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/swapfile.c (ffffffff8122b309)
Location: include/linux/pagemap.h:543
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
```
In mm/migrate.c (ffffffff8124d4e8)
Location: include/linux/pagemap.h:543
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/memory-failure.c (ffffffff81265db7)
Location: include/linux/pagemap.h:543
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
```
```
In fs/splice.c (ffffffff812a9cbb)
Location: include/linux/pagemap.h:543
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/ext4/inode.c (ffffffff81322f6a)
Location: include/linux/pagemap.h:543
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
```
In fs/ext4/move_extent.c (ffffffff81339914)
Location: include/linux/pagemap.h:543
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
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
In mm/filemap.c (ffffffff811ec15d)
Location: include/linux/pagemap.h:543
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff811fc54d)
Location: include/linux/pagemap.h:543
Inline: True
Inline callers:
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff8120384a)
Location: include/linux/pagemap.h:543
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff81209500)
Location: include/linux/pagemap.h:543
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff81211585)
Location: include/linux/pagemap.h:543
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/swapfile.c (ffffffff8124c771)
Location: include/linux/pagemap.h:543
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
```
In mm/migrate.c (ffffffff81270e2e)
Location: include/linux/pagemap.h:543
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/memory-failure.c (ffffffff8128a20c)
Location: include/linux/pagemap.h:543
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
```
```
In fs/splice.c (ffffffff812d170a)
Location: include/linux/pagemap.h:543
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/ext4/inode.c (ffffffff81350d43)
Location: include/linux/pagemap.h:543
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
```
In fs/ext4/move_extent.c (ffffffff81367e7e)
Location: include/linux/pagemap.h:543
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
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
In mm/filemap.c (ffffffff811fe4be)
Location: include/linux/pagemap.h:545
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff8120ee3d)
Location: include/linux/pagemap.h:545
Inline: True
Inline callers:
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff8121611a)
Location: include/linux/pagemap.h:545
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8121c1e2)
Location: include/linux/pagemap.h:545
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff81223563)
Location: include/linux/pagemap.h:545
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/swapfile.c (ffffffff81260cbb)
Location: include/linux/pagemap.h:545
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
```
In mm/migrate.c (ffffffff81285440)
Location: include/linux/pagemap.h:545
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/memory-failure.c (ffffffff8129f1b6)
Location: include/linux/pagemap.h:545
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
```
```
In fs/splice.c (ffffffff812e6b6a)
Location: include/linux/pagemap.h:545
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/ext4/inode.c (ffffffff81368ce4)
Location: include/linux/pagemap.h:545
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
```
In fs/ext4/move_extent.c (ffffffff81380300)
Location: include/linux/pagemap.h:545
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void wait_on_page_writeback(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8121e520)
Location: mm/page-writeback.c:2814
Inline: True
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_swapin_page
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/migrate.c:migrate_pages
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff8121e520-ffffffff8121e5a9: wait_on_page_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void wait_on_page_writeback(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8122bfc0)
Location: mm/page-writeback.c:2825
Inline: True
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_swapin_page
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/migrate.c:migrate_pages
  - mm/memory-failure.c:memory_failure
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff8122bfc0-ffffffff8122c049: wait_on_page_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void wait_on_page_writeback(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page-writeback.c (ffffffff81259d7a)
Location: mm/page-writeback.c:2835
Inline: True
Inline callers:
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_swapin_page
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/migrate.c:__unmap_and_move
  - mm/memory-failure.c:memory_failure
  - fs/splice.c:page_cache_pipe_buf_try_steal
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
**Symbols:**

```
ffffffff81258ba0-ffffffff81258c11: wait_on_page_writeback.part.0 (STB_LOCAL)
ffffffff81258c20-ffffffff81258c48: wait_on_page_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void wait_on_page_writeback(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81263190)
Location: mm/page-writeback.c:2827
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_swapin_page
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/migrate.c:__unmap_and_move
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:memory_failure
  - fs/splice.c:page_cache_pipe_buf_try_steal
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
**Symbols:**

```
ffffffff81263190-ffffffff81263206: wait_on_page_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void wait_on_page_writeback(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81267c40)
Location: mm/page-writeback.c:2824
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_swapin_page
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/migrate.c:__unmap_and_move
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:memory_failure
  - fs/splice.c:page_cache_pipe_buf_try_steal
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
**Symbols:**

```
ffffffff81267c40-ffffffff81267cb6: wait_on_page_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void wait_on_page_writeback(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812a46b0)
Location: mm/page-writeback.c:2879
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_swapin_page
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/migrate.c:__unmap_and_move
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:memory_failure
  - fs/splice.c:page_cache_pipe_buf_try_steal
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
**Symbols:**

```
ffffffff812a46b0-ffffffff812a4723: wait_on_page_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void wait_on_page_writeback(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff81300bf0)
Location: mm/folio-compat.c:30
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:write_cache_pages
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:memory_failure
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
**Symbols:**

```
ffffffff81300bf0-ffffffff81300c4b: wait_on_page_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void wait_on_page_writeback(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff8136b480)
Location: mm/folio-compat.c:30
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:write_cache_pages
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:memory_failure
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
**Symbols:**

```
ffffffff8136b480-ffffffff8136b4db: wait_on_page_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void wait_on_page_writeback(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff8139d620)
Location: mm/folio-compat.c:31
Inline: False
Direct callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff8139d620-ffffffff8139d68a: wait_on_page_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void wait_on_page_writeback(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff813c7380)
Location: mm/folio-compat.c:31
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff813c7380-ffffffff813c73e7: wait_on_page_writeback (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void wait_on_page_writeback(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffff8000102bacf8)
Location: mm/page-writeback.c:2825
Inline: True
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_swapin_page
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/migrate.c:migrate_pages
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffff8000102bacf8-ffff8000102badd4: wait_on_page_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void wait_on_page_writeback(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (c04e6a6c)
Location: mm/page-writeback.c:2825
Inline: True
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_swapin_page
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
  - mm/migrate.c:migrate_pages
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
c04e6a6c-c04e6b38: wait_on_page_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void wait_on_page_writeback(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (c0000000003731e0)
Location: mm/page-writeback.c:2825
Inline: True
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_swapin_page
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/migrate.c:migrate_pages
  - mm/memory-failure.c:memory_failure
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
c0000000003731e0-c0000000003732f0: wait_on_page_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void wait_on_page_writeback(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffe0001ddaf6)
Location: mm/page-writeback.c:2825
Inline: True
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_swapin_page
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/migrate.c:migrate_pages
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffe0001ddaf6-ffffffe0001ddbb6: wait_on_page_writeback (STB_GLOBAL)
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
void wait_on_page_writeback(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81224610)
Location: mm/page-writeback.c:2825
Inline: True
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_swapin_page
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/migrate.c:migrate_pages
  - mm/memory-failure.c:memory_failure
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff81224610-ffffffff81224699: wait_on_page_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void wait_on_page_writeback(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812177c0)
Location: mm/page-writeback.c:2825
Inline: True
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_swapin_page
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/migrate.c:migrate_pages
  - mm/memory-failure.c:memory_failure
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff812177c0-ffffffff81217849: wait_on_page_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void wait_on_page_writeback(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812223b0)
Location: mm/page-writeback.c:2825
Inline: True
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_swapin_page
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/migrate.c:migrate_pages
  - mm/memory-failure.c:memory_failure
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff812223b0-ffffffff81222439: wait_on_page_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void wait_on_page_writeback(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812317f0)
Location: mm/page-writeback.c:2825
Inline: True
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_swapin_page
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/migrate.c:migrate_pages
  - mm/memory-failure.c:memory_failure
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff812317f0-ffffffff8123188e: wait_on_page_writeback (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

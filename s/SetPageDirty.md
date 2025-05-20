# Function: <code>SetPageDirty</code>

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
In mm/page_io.c (ffffffff811d1f60)
Location: include/linux/page-flags.h:213
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/swap_state.c (ffffffff811d28e9)
Location: include/linux/page-flags.h:213
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap
```
```
In mm/swapfile.c (ffffffff811d49e8)
Location: include/linux/page-flags.h:213
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:try_to_unuse
```
```
In mm/frontswap.c (ffffffff811d76d6)
Location: include/linux/page-flags.h:213
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
```
```
In mm/ksm.c (ffffffff811e6dd6)
Location: include/linux/page-flags.h:213
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff811f1772)
Location: include/linux/page-flags.h:213
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_copy
```
```
In mm/memory-failure.c (ffffffff81202dfe)
Location: include/linux/page-flags.h:213
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/ext4/inline.c (ffffffff812e12e7)
Location: include/linux/page-flags.h:213
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
```
```
In fs/hugetlbfs/inode.c (ffffffff812f3747)
Location: include/linux/page-flags.h:213
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_set_page_dirty
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff81473740)
Location: include/linux/page-flags.h:213
Inline: True
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
In mm/page_io.c (ffffffff811efa5b)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swapfile.c (ffffffff811f36ce)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/frontswap.c (ffffffff811f5bf7)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
```
```
In mm/ksm.c (ffffffff81205e2d)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:try_to_merge_with_ksm_page
```
```
In mm/migrate.c (ffffffff812106b5)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812162f7)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/memory-failure.c (ffffffff812274b2)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/ext4/inline.c (ffffffff81311103)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
```
```
In fs/hugetlbfs/inode.c (ffffffff81326f07)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_set_page_dirty
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff814c1dbf)
Location: include/linux/page-flags.h:260
Inline: True
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
In mm/page_io.c (ffffffff81200404)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swapfile.c (ffffffff812041cb)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/frontswap.c (ffffffff81206727)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
```
```
In mm/ksm.c (ffffffff81217e3f)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812227ff)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812288a6)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/memory-failure.c (ffffffff81239a6d)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/ext4/inline.c (ffffffff81326fe3)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
```
```
In fs/hugetlbfs/inode.c (ffffffff8133cc77)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_set_page_dirty
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff814e3daf)
Location: include/linux/page-flags.h:270
Inline: True
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
In mm/page_io.c (ffffffff8120b034)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swapfile.c (ffffffff8120f88c)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/frontswap.c (ffffffff81211eb7)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
```
```
In mm/ksm.c (ffffffff81223a1a)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8122e290)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff81231f23)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (ffffffff81244d8b)
Location: include/linux/page-flags.h:270
Inline: True
```
```
In fs/ext4/inline.c (ffffffff812faf32)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
```
```
In fs/hugetlbfs/inode.c (ffffffff813517d7)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_set_page_dirty
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff814efb7f)
Location: include/linux/page-flags.h:270
Inline: True
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
In mm/page_io.c (ffffffff81224454)
Location: include/linux/page-flags.h:271
Inline: True
Inline callers:
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swapfile.c (ffffffff8122b132)
Location: include/linux/page-flags.h:271
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/frontswap.c (ffffffff8122c891)
Location: include/linux/page-flags.h:271
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
```
```
In mm/ksm.c (ffffffff8123f05a)
Location: include/linux/page-flags.h:271
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff81249364)
Location: include/linux/page-flags.h:271
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff81252c94)
Location: include/linux/page-flags.h:271
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/memory-failure.c (ffffffff81264c7b)
Location: include/linux/page-flags.h:271
Inline: True
```
```
In fs/ext4/inline.c (ffffffff8131f622)
Location: include/linux/page-flags.h:271
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
```
```
In fs/hugetlbfs/inode.c (ffffffff813762e7)
Location: include/linux/page-flags.h:271
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_set_page_dirty
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815246ef)
Location: include/linux/page-flags.h:271
Inline: True
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
In mm/page_io.c (ffffffff81246976)
Location: include/linux/page-flags.h:278
Inline: True
Inline callers:
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swapfile.c (ffffffff8124c399)
Location: include/linux/page-flags.h:278
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/frontswap.c (ffffffff8124f53a)
Location: include/linux/page-flags.h:278
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
```
```
In mm/ksm.c (ffffffff81262806)
Location: include/linux/page-flags.h:278
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8126cde5)
Location: include/linux/page-flags.h:278
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff81276f88)
Location: include/linux/page-flags.h:278
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/memory-failure.c (ffffffff812891f2)
Location: include/linux/page-flags.h:278
Inline: True
```
```
In fs/ext4/inline.c (ffffffff8134d67b)
Location: include/linux/page-flags.h:278
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
```
```
In fs/hugetlbfs/inode.c (ffffffff813a4bf4)
Location: include/linux/page-flags.h:278
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_set_page_dirty
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8155a43e)
Location: include/linux/page-flags.h:278
Inline: True
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
In mm/page_io.c (ffffffff8125ad96)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swapfile.c (ffffffff812608b2)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/frontswap.c (ffffffff8126348a)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
```
```
In mm/ksm.c (ffffffff81277086)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff81281611)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812887c7)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (ffffffff8129e142)
Location: include/linux/page-flags.h:287
Inline: True
```
```
In fs/ext4/inline.c (ffffffff81365812)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
```
```
In fs/hugetlbfs/inode.c (ffffffff813bd9f4)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_set_page_dirty
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff81571d4e)
Location: include/linux/page-flags.h:287
Inline: True
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
In mm/page_io.c (ffffffff81275e97)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swapfile.c (ffffffff8127a28a)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/frontswap.c (ffffffff8127e3c9)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
```
```
In mm/ksm.c (ffffffff812928e4)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8129d8a4)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812a3405)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (ffffffff812b92ed)
Location: include/linux/page-flags.h:318
Inline: True
```
```
In fs/ext4/inline.c (ffffffff8138ebed)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
```
```
In fs/hugetlbfs/inode.c (ffffffff813e82d4)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_set_page_dirty
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815a2233)
Location: include/linux/page-flags.h:318
Inline: True
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
In mm/page_io.c (ffffffff81285960)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swapfile.c (ffffffff81289d6a)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/frontswap.c (ffffffff8128de29)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
```
```
In mm/ksm.c (ffffffff812a2667)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812ad1c2)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812b4905)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (ffffffff812cb1dd)
Location: include/linux/page-flags.h:318
Inline: True
```
```
In fs/ext4/inline.c (ffffffff813a764d)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
```
```
In fs/hugetlbfs/inode.c (ffffffff81402374)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_set_page_dirty
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815c30b3)
Location: include/linux/page-flags.h:318
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817d3762)
Location: include/linux/page-flags.h:318
Inline: True
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
In mm/page_io.c (ffffffff812b7cf5)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swapfile.c (ffffffff812bcbd1)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/frontswap.c (ffffffff812c0b75)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
```
```
In mm/ksm.c (ffffffff812d6d86)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812e2d00)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812e9e81)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (ffffffff81301308)
Location: include/linux/page-flags.h:326
Inline: True
```
```
In fs/ext4/inline.c (ffffffff813f27b7)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
```
```
In fs/hugetlbfs/inode.c (ffffffff8144ff74)
Location: include/linux/page-flags.h:326
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_set_page_dirty
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8166d253)
Location: include/linux/page-flags.h:326
Inline: True
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
In mm/page_io.c (ffffffff812c33b2)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swapfile.c (ffffffff812c8701)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/frontswap.c (ffffffff812cc595)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
```
```
In mm/ksm.c (ffffffff812e2916)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812ee130)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812f5061)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (ffffffff8130d372)
Location: include/linux/page-flags.h:334
Inline: True
```
```
In fs/ext4/inline.c (ffffffff81404f07)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
```
```
In fs/hugetlbfs/inode.c (ffffffff8146c484)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_set_page_dirty
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8168d973)
Location: include/linux/page-flags.h:334
Inline: True
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
In mm/page_io.c (ffffffff812ca1b1)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swapfile.c (ffffffff812cf0be)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/frontswap.c (ffffffff812d2fc5)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
```
```
In mm/ksm.c (ffffffff812ea0a6)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812f3c20)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812fb5e9)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (ffffffff81313904)
Location: include/linux/page-flags.h:334
Inline: True
```
```
In fs/ext4/inline.c (ffffffff8140c315)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff81670663)
Location: include/linux/page-flags.h:334
Inline: True
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
In mm/shmem.c (ffffffff812bffc8)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_writepage
```
```
In mm/page_io.c (ffffffff8130f1d2)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swapfile.c (ffffffff8131465e)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/frontswap.c (ffffffff813189d8)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
```
```
In mm/ksm.c (ffffffff81331fc8)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8133e5c0)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff8134541a)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (ffffffff81360623)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/ext4/inline.c (ffffffff8145f209)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff816e4933)
Location: include/linux/page-flags.h:348
Inline: True
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
In mm/shmem.c (ffffffff8131b943)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
```
In mm/swapfile.c (ffffffff8137fc02)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_free_swap
```
```
In mm/ksm.c (ffffffff813a3326)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/huge_memory.c (ffffffff813bb831)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (ffffffff813dbe2d)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/ext4/inline.c (ffffffff814dc245)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
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
In mm/ksm.c (ffffffff81422fc7)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/huge_memory.c (ffffffff8143de44)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (ffffffff81462c02)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/ext4/inline.c (ffffffff815751f5)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
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
In mm/frontswap.c (ffffffff81434ad4)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
```
```
In mm/ksm.c (ffffffff8145801e)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/huge_memory.c (ffffffff814734c6)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (ffffffff814989d0)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
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
In mm/ksm.c (ffffffff814902db)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/memory-failure.c (ffffffff814c7f24)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
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
In virt/kvm/kvm_main.c (ffff8000100bb77c)
Location: include/linux/page-flags.h:318
Inline: True
```
```
In mm/page_io.c (ffff80001032002c)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swapfile.c (ffff800010324d1c)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/frontswap.c (ffff80001032aabc)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
```
```
In mm/ksm.c (ffff800010342050)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffff80001034f4d0)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffff800010355e1c)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (ffff80001036ed88)
Location: include/linux/page-flags.h:318
Inline: True
```
```
In fs/ext4/inline.c (ffff80001047aee0)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
```
```
In fs/hugetlbfs/inode.c (ffff8000104e1ac0)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_set_page_dirty
```
```
In drivers/video/fbdev/core/fb_defio.c (ffff80001074c1b4)
Location: include/linux/page-flags.h:318
Inline: True
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
In mm/page_io.c (c0538894)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swapfile.c (c053c7b8)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/frontswap.c (c0540a44)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
```
```
In mm/ksm.c (c0547db8)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (c0551458)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
```
```
In fs/ext4/inline.c (c063c834)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
```
```
In drivers/video/fbdev/core/fb_defio.c (c08cec18)
Location: include/linux/page-flags.h:318
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
In arch/powerpc/kernel/iommu.c (c000000000051fcc)
Location: include/linux/page-flags.h:318
Inline: True
```
```
In arch/powerpc/mm/book3s64/iommu_api.c (c0000000000a0e94)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/iommu_api.c:mm_iommu_free
```
```
In mm/page_io.c (c0000000003f4e98)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swapfile.c (c0000000003fae24)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/frontswap.c (c0000000004013f0)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
```
```
In mm/ksm.c (c00000000041f8ac)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (c00000000043191c)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (c00000000043c224)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (c00000000045f808)
Location: include/linux/page-flags.h:318
Inline: True
```
```
In fs/ext4/inline.c (c00000000059e040)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
```
```
In fs/hugetlbfs/inode.c (c00000000061d084)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_set_page_dirty
```
```
In drivers/video/fbdev/core/fb_defio.c (c0000000008ae020)
Location: include/linux/page-flags.h:318
Inline: True
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
In mm/page_io.c (ffffffe000221742)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swapfile.c (ffffffe0002253a0)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/frontswap.c (ffffffe00022966c)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
```
```
In mm/ksm.c (ffffffe000236316)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffe00023e4e0)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
```
```
In fs/ext4/inline.c (ffffffe000305562)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
```
```
In fs/hugetlbfs/inode.c (ffffffe00035499c)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_set_page_dirty
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffe0004f9d70)
Location: include/linux/page-flags.h:318
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
In mm/page_io.c (ffffffff8127dfb0)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swapfile.c (ffffffff8128234a)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/frontswap.c (ffffffff81286409)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
```
```
In mm/ksm.c (ffffffff8129ac47)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812a57a2)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812acee5)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (ffffffff812c37bd)
Location: include/linux/page-flags.h:318
Inline: True
```
```
In fs/ext4/inline.c (ffffffff8139fc2d)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
```
```
In fs/hugetlbfs/inode.c (ffffffff813fa954)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_set_page_dirty
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815b7203)
Location: include/linux/page-flags.h:318
Inline: True
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
In mm/page_io.c (ffffffff8126fde0)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swapfile.c (ffffffff81273e6a)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/frontswap.c (ffffffff81278269)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
```
```
In mm/ksm.c (ffffffff8128c807)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff81297272)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff8129df53)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (ffffffff812b47fd)
Location: include/linux/page-flags.h:318
Inline: True
```
```
In fs/ext4/inline.c (ffffffff813906bd)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
```
```
In fs/hugetlbfs/inode.c (ffffffff813eb3d4)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_set_page_dirty
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815a5fe3)
Location: include/linux/page-flags.h:318
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8177d812)
Location: include/linux/page-flags.h:318
Inline: True
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
In mm/page_io.c (ffffffff8127bd50)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swapfile.c (ffffffff8128015a)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/frontswap.c (ffffffff81284219)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
```
```
In mm/ksm.c (ffffffff81298a57)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812a35b2)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812aacf5)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (ffffffff812c15cd)
Location: include/linux/page-flags.h:318
Inline: True
```
```
In fs/ext4/inline.c (ffffffff8139d48d)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
```
```
In fs/hugetlbfs/inode.c (ffffffff813f7cd4)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_set_page_dirty
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815b7793)
Location: include/linux/page-flags.h:318
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817c85e2)
Location: include/linux/page-flags.h:318
Inline: True
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
In mm/page_io.c (ffffffff8128b930)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swapfile.c (ffffffff8128fe49)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/frontswap.c (ffffffff81293ef9)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
```
```
In mm/ksm.c (ffffffff812a883a)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812b3dc2)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812bb045)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memory-failure.c (ffffffff812d208d)
Location: include/linux/page-flags.h:318
Inline: True
```
```
In fs/ext4/inline.c (ffffffff813b19fd)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
```
```
In fs/hugetlbfs/inode.c (ffffffff8140da24)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_set_page_dirty
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815d1203)
Location: include/linux/page-flags.h:318
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817e2882)
Location: include/linux/page-flags.h:318
Inline: True
```
</details>
</li>
</ul>

## Differences

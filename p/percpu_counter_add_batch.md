# Function: <code>percpu_counter_add_batch</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void percpu_counter_add_batch(struct percpu_counter *fbc, s64 amount, s32 batch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff814815b0)
Location: lib/percpu_counter.c:82
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:wb_writeout_inc
  - mm/shmem.c:shmem_mcopy_atomic_pte
  - mm/shmem.c:shmem_mcopy_atomic_pte
  - mm/shmem.c:shmem_mcopy_atomic_pte
  - mm/shmem.c:shmem_mcopy_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_recalc_inode
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_munmap
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:move_vma
  - mm/swapfile.c:SyS_swapoff
  - mm/frontswap.c:frontswap_shrink
  - fs/file_table.c:__fput
  - fs/file_table.c:get_empty_filp
  - fs/file_table.c:get_empty_filp
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/ext4/balloc.c:ext4_claim_free_clusters
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_merged_requests
  - block/cfq-iosched.c:cfq_merged_requests
  - block/cfq-iosched.c:cfq_bio_merged
  - block/cfq-iosched.c:cfq_bio_merged
  - block/cfq-iosched.c:cfq_remove_request
  - block/cfq-iosched.c:cfq_remove_request
  - block/cfq-iosched.c:cfq_group_served
  - net/core/sock.c:sk_clone_lock
  - net/core/dst.c:dst_destroy
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_single
  - lib/flex_proportions.c:fprop_new_period
```
**Symbols:**

```
ffffffff814815b0-ffffffff81481610: percpu_counter_add_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void percpu_counter_add_batch(struct percpu_counter *fbc, s64 amount, s32 batch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff814bd3f0)
Location: lib/percpu_counter.c:83
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:wb_writeout_inc
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_recalc_inode
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_munmap
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:move_vma
  - mm/swapfile.c:SYSC_swapoff
  - mm/frontswap.c:frontswap_shrink
  - fs/file_table.c:__fput
  - fs/file_table.c:get_empty_filp
  - fs/file_table.c:get_empty_filp
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/ext4/balloc.c:ext4_claim_free_clusters
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:cfq_merged_requests
  - block/cfq-iosched.c:cfq_merged_requests
  - block/cfq-iosched.c:cfq_bio_merged
  - block/cfq-iosched.c:cfq_bio_merged
  - block/cfq-iosched.c:cfq_remove_request
  - block/cfq-iosched.c:cfq_remove_request
  - net/core/sock.c:sk_clone_lock
  - net/core/dst.c:dst_destroy
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_single
  - lib/flex_proportions.c:fprop_new_period
```
**Symbols:**

```
ffffffff814bd3f0-ffffffff814bd450: percpu_counter_add_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void percpu_counter_add_batch(struct percpu_counter *fbc, s64 amount, s32 batch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff814efc50)
Location: lib/percpu_counter.c:83
Inline: False
Direct callers:
  - kernel/fork.c:copy_mm
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:wb_writeout_inc
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_recalc_inode
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_munmap
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:mremap_to
  - mm/mremap.c:move_vma
  - mm/swapfile.c:__do_sys_swapoff
  - mm/frontswap.c:frontswap_shrink
  - fs/file_table.c:__fput
  - fs/file_table.c:get_empty_filp
  - fs/file_table.c:get_empty_filp
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/ext4/balloc.c:ext4_claim_free_clusters
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:cfq_merged_requests
  - block/cfq-iosched.c:cfq_merged_requests
  - block/cfq-iosched.c:cfq_bio_merged
  - block/cfq-iosched.c:cfq_bio_merged
  - block/cfq-iosched.c:cfq_remove_request
  - block/cfq-iosched.c:cfq_remove_request
  - net/core/sock.c:sk_clone_lock
  - net/core/dst.c:dst_destroy
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_single
  - lib/flex_proportions.c:fprop_new_period
```
**Symbols:**

```
ffffffff814efc50-ffffffff814efcac: percpu_counter_add_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void percpu_counter_add_batch(struct percpu_counter *fbc, s64 amount, s32 batch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff81503b70)
Location: lib/percpu_counter.c:82
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:wb_writeout_inc
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_recalc_inode
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:mremap_to
  - mm/mremap.c:move_vma
  - mm/swapfile.c:__do_sys_swapoff
  - mm/frontswap.c:frontswap_shrink
  - fs/file_table.c:__fput
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/ext4/balloc.c:ext4_claim_free_clusters
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - net/core/sock.c:sk_clone_lock
  - net/core/dst.c:dst_destroy
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_single
  - lib/flex_proportions.c:fprop_new_period
```
**Symbols:**

```
ffffffff81503b70-ffffffff81503bcc: percpu_counter_add_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void percpu_counter_add_batch(struct percpu_counter *fbc, s64 amount, s32 batch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff81531cc0)
Location: lib/percpu_counter.c:82
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:wb_writeout_inc
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_recalc_inode
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:mremap_to
  - mm/mremap.c:move_vma
  - mm/swapfile.c:__do_sys_swapoff
  - mm/frontswap.c:frontswap_shrink
  - fs/file_table.c:__fput
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/ext4/balloc.c:ext4_claim_free_clusters
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - net/core/sock.c:sk_clone_lock
  - net/core/dst.c:dst_destroy
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_single
  - lib/flex_proportions.c:fprop_new_period
```
**Symbols:**

```
ffffffff81531cc0-ffffffff81531d21: percpu_counter_add_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void percpu_counter_add_batch(struct percpu_counter *fbc, s64 amount, s32 batch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff81552b70)
Location: lib/percpu_counter.c:82
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:wb_writeout_inc
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_recalc_inode
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:mremap_to
  - mm/mremap.c:move_vma
  - mm/swapfile.c:__do_sys_swapoff
  - mm/frontswap.c:frontswap_shrink
  - fs/file_table.c:__fput
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/ext4/balloc.c:ext4_claim_free_clusters
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - net/core/sock.c:sk_clone_lock
  - net/core/dst.c:dst_destroy
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_single
  - lib/flex_proportions.c:fprop_new_period
```
**Symbols:**

```
ffffffff81552b70-ffffffff81552bd1: percpu_counter_add_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void percpu_counter_add_batch(struct percpu_counter *fbc, s64 amount, s32 batch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff815dbf50)
Location: lib/percpu_counter.c:82
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/page-writeback.c:__add_wb_stat
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_recalc_inode
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:mremap_to
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
  - mm/swapfile.c:__do_sys_swapoff
  - mm/frontswap.c:frontswap_shrink
  - fs/file_table.c:__fput
  - fs/file_table.c:alloc_empty_file
  - fs/fs-writeback.c:__add_wb_stat
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:invalidate_dquots
  - fs/quota/dquot.c:invalidate_dquots
  - fs/ext4/balloc.c:ext4_claim_free_clusters
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_single
  - lib/flex_proportions.c:fprop_new_period
  - net/core/sock.c:sk_clone_lock
  - net/core/dst.c:dst_destroy
  - net/core/dst.c:dst_alloc
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/mptcp/protocol.c:mptcp_v6_destroy
  - net/mptcp/subflow.c:subflow_syn_recv_sock
```
**Symbols:**

```
ffffffff815dbf50-ffffffff815dbfb1: percpu_counter_add_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void percpu_counter_add_batch(struct percpu_counter *fbc, s64 amount, s32 batch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff815f9bb0)
Location: lib/percpu_counter.c:82
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:wb_writeout_inc
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_recalc_inode
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:mremap_to
  - mm/mremap.c:move_vma
  - mm/swapfile.c:__do_sys_swapoff
  - mm/frontswap.c:frontswap_shrink
  - fs/file_table.c:__fput
  - fs/file_table.c:alloc_empty_file
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_req_free_batch
  - fs/io_uring.c:__io_free_req
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:invalidate_dquots
  - fs/quota/dquot.c:invalidate_dquots
  - fs/ext4/balloc.c:ext4_should_retry_alloc
  - fs/ext4/balloc.c:ext4_claim_free_clusters
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_add
  - fs/fuse/file.c:fuse_writepage_locked
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_single
  - lib/flex_proportions.c:fprop_new_period
  - net/core/sock.c:sk_clone_lock
  - net/core/dst.c:dst_destroy
  - net/core/dst.c:dst_alloc
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/mptcp/protocol.c:mptcp_v6_destroy
  - net/mptcp/subflow.c:subflow_syn_recv_sock
```
**Symbols:**

```
ffffffff815f9bb0-ffffffff815f9c17: percpu_counter_add_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void percpu_counter_add_batch(struct percpu_counter *fbc, s64 amount, s32 batch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff815dc7a0)
Location: lib/percpu_counter.c:82
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:wb_writeout_inc
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_recalc_inode
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:mremap_to
  - mm/mremap.c:move_vma
  - mm/swapfile.c:__do_sys_swapoff
  - mm/frontswap.c:frontswap_shrink
  - fs/file_table.c:__fput
  - fs/file_table.c:alloc_empty_file
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/io_uring.c:io_free_work
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_put_req_deferred_cb
  - fs/io_uring.c:io_submit_flush_completions
  - fs/io_uring.c:io_req_free_batch
  - fs/io_uring.c:io_req_complete_post
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:invalidate_dquots
  - fs/quota/dquot.c:invalidate_dquots
  - fs/ext4/balloc.c:ext4_should_retry_alloc
  - fs/ext4/balloc.c:ext4_claim_free_clusters
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_add
  - fs/fuse/file.c:fuse_writepage_locked
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_single
  - lib/flex_proportions.c:fprop_new_period
  - net/core/sock.c:sk_clone_lock
  - net/core/dst.c:dst_destroy
  - net/core/dst.c:dst_alloc
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/mptcp/protocol.c:mptcp_v6_destroy
  - net/mptcp/subflow.c:subflow_syn_recv_sock
```
**Symbols:**

```
ffffffff815dc7a0-ffffffff815dc7fe: percpu_counter_add_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void percpu_counter_add_batch(struct percpu_counter *fbc, s64 amount, s32 batch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff816480e0)
Location: lib/percpu_counter.c:82
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:wb_writeout_inc
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_recalc_inode
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:mremap_to
  - mm/mremap.c:move_vma
  - mm/swapfile.c:__do_sys_swapoff
  - mm/frontswap.c:frontswap_shrink
  - fs/file_table.c:__fput
  - fs/file_table.c:alloc_empty_file
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_submit_flush_completions
  - fs/io_uring.c:io_req_free_batch
  - fs/io_uring.c:__io_free_req
  - fs/io_uring.c:io_req_complete_post
  - fs/io_uring.c:io_uring_drop_tctx_refs
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:invalidate_dquots
  - fs/quota/dquot.c:invalidate_dquots
  - fs/ext4/balloc.c:ext4_should_retry_alloc
  - fs/ext4/balloc.c:ext4_claim_free_clusters
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_single
  - lib/flex_proportions.c:fprop_new_period
  - net/core/sock.c:sk_clone_lock
  - net/core/dst.c:dst_destroy
  - net/core/dst.c:dst_alloc
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/mptcp/protocol.c:mptcp_v6_destroy
```
**Symbols:**

```
ffffffff816480e0-ffffffff8164813e: percpu_counter_add_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void percpu_counter_add_batch(struct percpu_counter *fbc, s64 amount, s32 batch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff8175e5c0)
Location: lib/percpu_counter.c:82
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_account_redirty
  - mm/page-writeback.c:folio_account_cleaned
  - mm/page-writeback.c:folio_account_dirtied
  - mm/page-writeback.c:folio_account_dirtied
  - mm/page-writeback.c:wb_writeout_inc
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_folio
  - mm/shmem.c:shmem_alloc_and_acct_folio
  - mm/shmem.c:shmem_alloc_and_acct_folio
  - mm/shmem.c:shmem_alloc_and_acct_folio
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_recalc_inode
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
  - mm/swapfile.c:__do_sys_swapoff
  - fs/file_table.c:__fput
  - fs/file_table.c:alloc_empty_file
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:invalidate_dquots
  - fs/quota/dquot.c:invalidate_dquots
  - fs/ext4/balloc.c:ext4_should_retry_alloc
  - fs/ext4/balloc.c:ext4_claim_free_clusters
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:__blk_throtl_bio
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:io_uring_drop_tctx_refs
  - io_uring/io_uring.c:__io_put_task
  - lib/flex_proportions.c:__fprop_add_percpu
  - lib/flex_proportions.c:__fprop_add_percpu
  - lib/flex_proportions.c:__fprop_inc_single
  - lib/flex_proportions.c:fprop_new_period
  - net/core/sock.c:sk_clone_lock
  - net/core/dst.c:dst_destroy
  - net/core/dst.c:dst_alloc
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/mptcp/protocol.c:mptcp_v6_destroy
```
**Symbols:**

```
ffffffff8175e5c0-ffffffff8175e651: percpu_counter_add_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void percpu_counter_add_batch(struct percpu_counter *fbc, s64 amount, s32 batch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff8188bb30)
Location: lib/percpu_counter.c:82
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_account_redirty
  - mm/page-writeback.c:folio_account_cleaned
  - mm/page-writeback.c:folio_account_dirtied
  - mm/page-writeback.c:folio_account_dirtied
  - mm/page-writeback.c:wb_writeout_inc
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_alloc_and_acct_folio
  - mm/shmem.c:shmem_alloc_and_acct_folio
  - mm/shmem.c:shmem_alloc_and_acct_folio
  - mm/shmem.c:shmem_alloc_and_acct_folio
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_recalc_inode
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_set_pmd
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:do_mas_align_munmap
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/madvise.c:madvise_free_pte_range
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
  - mm/ksm.c:replace_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/userfaultfd.c:mfill_atomic_install_pte
  - fs/file_table.c:__fput
  - fs/file_table.c:alloc_empty_file
  - fs/exec.c:free_bprm
  - fs/exec.c:begin_new_exec
  - fs/exec.c:get_arg_page
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:invalidate_dquots
  - fs/quota/dquot.c:invalidate_dquots
  - fs/ext4/balloc.c:ext4_should_retry_alloc
  - fs/ext4/balloc.c:ext4_claim_free_clusters
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:__blk_throtl_bio
  - io_uring/io_uring.c:io_uring_drop_tctx_refs
  - io_uring/io_uring.c:io_task_refs_refill
  - io_uring/io_uring.c:__io_put_task
  - net/core/sock.c:sk_clone_lock
  - net/core/dst.c:dst_destroy
  - net/core/dst.c:dst_alloc
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/mptcp/protocol.c:mptcp_destroy
  - lib/flex_proportions.c:__fprop_add_percpu
  - lib/flex_proportions.c:__fprop_add_percpu
  - lib/flex_proportions.c:__fprop_inc_single
  - lib/flex_proportions.c:fprop_new_period
```
**Symbols:**

```
ffffffff8188bb30-ffffffff8188bbc1: percpu_counter_add_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void percpu_counter_add_batch(struct percpu_counter *fbc, s64 amount, s32 batch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff818cdfc0)
Location: lib/percpu_counter.c:87
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_account_redirty
  - mm/page-writeback.c:folio_account_cleaned
  - mm/page-writeback.c:folio_account_dirtied
  - mm/page-writeback.c:folio_account_dirtied
  - mm/page-writeback.c:wb_writeout_inc
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_alloc_and_acct_folio
  - mm/shmem.c:shmem_alloc_and_acct_folio
  - mm/shmem.c:shmem_alloc_and_acct_folio
  - mm/shmem.c:shmem_alloc_and_acct_folio
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_recalc_inode
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_set_pmd
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/madvise.c:madvise_free_pte_range
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
  - mm/ksm.c:replace_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/userfaultfd.c:mfill_atomic_install_pte
  - fs/file_table.c:__fput
  - fs/file_table.c:alloc_empty_file
  - fs/exec.c:free_bprm
  - fs/exec.c:begin_new_exec
  - fs/exec.c:get_arg_page
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:__ep_remove
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:quota_release_workfn
  - fs/quota/dquot.c:quota_release_workfn
  - fs/quota/dquot.c:quota_release_workfn
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:invalidate_dquots
  - fs/quota/dquot.c:invalidate_dquots
  - fs/ext4/balloc.c:ext4_should_retry_alloc
  - fs/ext4/balloc.c:ext4_claim_free_clusters
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
  - io_uring/io_uring.c:io_uring_drop_tctx_refs
  - io_uring/io_uring.c:io_task_refs_refill
  - io_uring/io_uring.c:io_put_task_remote
  - net/core/sock.c:sk_clone_lock
  - net/core/dst.c:dst_destroy
  - net/core/dst.c:dst_alloc
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/mptcp/protocol.c:mptcp_destroy
  - net/mptcp/protocol.c:mptcp_init_sock
  - lib/flex_proportions.c:__fprop_add_percpu
  - lib/flex_proportions.c:__fprop_add_percpu
  - lib/flex_proportions.c:__fprop_inc_single
  - lib/flex_proportions.c:fprop_new_period
```
**Symbols:**

```
ffffffff818cdfc0-ffffffff818ce054: percpu_counter_add_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void percpu_counter_add_batch(struct percpu_counter *fbc, s64 amount, s32 batch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff8191fa20)
Location: lib/percpu_counter.c:87
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_redirty_for_writepage
  - mm/page-writeback.c:folio_account_cleaned
  - mm/page-writeback.c:folio_account_dirtied
  - mm/page-writeback.c:folio_account_dirtied
  - mm/page-writeback.c:wb_writeout_inc
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_inode_unacct_blocks
  - mm/shmem.c:shmem_inode_unacct_blocks
  - mm/shmem.c:shmem_inode_acct_blocks
  - mm/shmem.c:shmem_inode_acct_blocks
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
  - mm/memory.c:set_pte_range
  - mm/memory.c:set_pte_range
  - mm/memory.c:do_set_pmd
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mprotect.c:mprotect_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:move_vma
  - mm/mremap.c:move_vma
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/madvise.c:madvise_free_pte_range
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
  - mm/ksm.c:replace_page
  - mm/migrate_device.c:migrate_vma_insert_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/userfaultfd.c:mfill_atomic_install_pte
  - fs/file_table.c:__fput
  - fs/file_table.c:alloc_empty_file
  - fs/exec.c:free_bprm
  - fs/exec.c:begin_new_exec
  - fs/exec.c:get_arg_page
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:__ep_remove
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:quota_release_workfn
  - fs/quota/dquot.c:quota_release_workfn
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:invalidate_dquots
  - fs/quota/dquot.c:invalidate_dquots
  - fs/ext4/balloc.c:ext4_should_retry_alloc
  - fs/ext4/balloc.c:ext4_claim_free_clusters
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
  - io_uring/io_uring.c:io_uring_drop_tctx_refs
  - io_uring/io_uring.c:io_task_refs_refill
  - io_uring/io_uring.c:io_put_task_remote
  - net/core/sock.c:sk_clone_lock
  - net/core/dst.c:dst_destroy
  - net/core/dst.c:dst_alloc
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/mptcp/protocol.c:mptcp_destroy
  - net/mptcp/protocol.c:mptcp_init_sock
  - lib/flex_proportions.c:__fprop_add_percpu
  - lib/flex_proportions.c:__fprop_add_percpu
  - lib/flex_proportions.c:__fprop_inc_single
  - lib/flex_proportions.c:fprop_new_period
```
**Symbols:**

```
ffffffff8191fa20-ffffffff8191fab4: percpu_counter_add_batch (STB_GLOBAL)
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
void percpu_counter_add_batch(struct percpu_counter *fbc, s64 amount, s32 batch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffff80001065eae8)
Location: lib/percpu_counter.c:82
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:wb_writeout_inc
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_recalc_inode
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:__arm64_sys_mremap
  - mm/mremap.c:__arm64_sys_mremap
  - mm/mremap.c:move_vma
  - mm/swapfile.c:__do_sys_swapoff
  - mm/frontswap.c:frontswap_shrink
  - fs/file_table.c:__fput
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/ext4/balloc.c:ext4_claim_free_clusters
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - net/core/sock.c:sk_clone_lock
  - net/core/dst.c:dst_destroy
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_single
  - lib/flex_proportions.c:fprop_new_period
```
**Symbols:**

```
ffff80001065eae8-ffff80001065ebec: percpu_counter_add_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void percpu_counter_add_batch(struct percpu_counter *fbc, s64 amount, s32 batch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (c0808168)
Location: lib/percpu_counter.c:82
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:wb_writeout_inc
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_recalc_inode
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:__se_sys_mremap
  - mm/mremap.c:__se_sys_mremap
  - mm/mremap.c:move_vma
  - mm/swapfile.c:__do_sys_swapoff
  - mm/frontswap.c:frontswap_shrink
  - fs/file_table.c:__fput
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/ext4/balloc.c:ext4_claim_free_clusters
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - net/core/sock.c:sk_clone_lock
  - net/core/dst.c:dst_destroy
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:fprop_reflect_period_percpu
  - lib/flex_proportions.c:__fprop_inc_single
  - lib/flex_proportions.c:fprop_new_period
```
**Symbols:**

```
c0808168-c0808224: percpu_counter_add_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void percpu_counter_add_batch(struct percpu_counter *fbc, s64 amount, s32 batch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (c000000000811480)
Location: lib/percpu_counter.c:82
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:wb_writeout_inc
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_recalc_inode
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:__se_sys_mremap
  - mm/mremap.c:__se_sys_mremap
  - mm/mremap.c:move_vma
  - mm/swapfile.c:__do_sys_swapoff
  - mm/frontswap.c:frontswap_shrink
  - fs/file_table.c:__fput
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/ext4/balloc.c:ext4_claim_free_clusters
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - net/core/sock.c:sk_clone_lock
  - net/core/dst.c:dst_destroy
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:fprop_reflect_period_percpu
  - lib/flex_proportions.c:__fprop_inc_single
  - lib/flex_proportions.c:fprop_new_period
```
**Symbols:**

```
c000000000811480-c000000000811574: percpu_counter_add_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void percpu_counter_add_batch(struct percpu_counter *fbc, s64 amount, s32 batch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffe00048c24a)
Location: lib/percpu_counter.c:82
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:wb_writeout_inc
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_recalc_inode
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:__se_sys_mremap
  - mm/mremap.c:__se_sys_mremap
  - mm/mremap.c:move_vma
  - mm/swapfile.c:__do_sys_swapoff
  - mm/frontswap.c:frontswap_shrink
  - fs/file_table.c:__fput
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/ext4/balloc.c:ext4_claim_free_clusters
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - net/core/sock.c:sk_clone_lock
  - net/core/dst.c:dst_destroy
  - net/core/dst.c:dst_init
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:fprop_reflect_period_percpu
  - lib/flex_proportions.c:__fprop_inc_single
  - lib/flex_proportions.c:fprop_new_period
```
**Symbols:**

```
ffffffe00048c24a-ffffffe00048c2fe: percpu_counter_add_batch (STB_GLOBAL)
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
void percpu_counter_add_batch(struct percpu_counter *fbc, s64 amount, s32 batch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff8154b150)
Location: lib/percpu_counter.c:82
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:wb_writeout_inc
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_recalc_inode
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:mremap_to
  - mm/mremap.c:move_vma
  - mm/swapfile.c:__do_sys_swapoff
  - mm/frontswap.c:frontswap_shrink
  - fs/file_table.c:__fput
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/ext4/balloc.c:ext4_claim_free_clusters
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - net/core/sock.c:sk_clone_lock
  - net/core/dst.c:dst_destroy
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_single
  - lib/flex_proportions.c:fprop_new_period
```
**Symbols:**

```
ffffffff8154b150-ffffffff8154b1b1: percpu_counter_add_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void percpu_counter_add_batch(struct percpu_counter *fbc, s64 amount, s32 batch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff8153b430)
Location: lib/percpu_counter.c:82
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:wb_writeout_inc
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_recalc_inode
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:mremap_to
  - mm/mremap.c:move_vma
  - mm/swapfile.c:__do_sys_swapoff
  - mm/frontswap.c:frontswap_shrink
  - fs/file_table.c:__fput
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/ext4/balloc.c:ext4_claim_free_clusters
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - net/core/sock.c:sk_clone_lock
  - net/core/dst.c:dst_destroy
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_single
  - lib/flex_proportions.c:fprop_new_period
```
**Symbols:**

```
ffffffff8153b430-ffffffff8153b491: percpu_counter_add_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void percpu_counter_add_batch(struct percpu_counter *fbc, s64 amount, s32 batch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff81546e90)
Location: lib/percpu_counter.c:82
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:wb_writeout_inc
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_recalc_inode
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:mremap_to
  - mm/mremap.c:move_vma
  - mm/swapfile.c:__do_sys_swapoff
  - mm/frontswap.c:frontswap_shrink
  - fs/file_table.c:__fput
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/ext4/balloc.c:ext4_claim_free_clusters
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - net/core/sock.c:sk_clone_lock
  - net/core/dst.c:dst_destroy
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_single
  - lib/flex_proportions.c:fprop_new_period
```
**Symbols:**

```
ffffffff81546e90-ffffffff81546ef1: percpu_counter_add_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void percpu_counter_add_batch(struct percpu_counter *fbc, s64 amount, s32 batch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff81560d70)
Location: lib/percpu_counter.c:82
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:wb_writeout_inc
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_recalc_inode
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:mmap_region
  - mm/mprotect.c:mprotect_fixup
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:mremap_to
  - mm/mremap.c:move_vma
  - mm/swapfile.c:__do_sys_swapoff
  - mm/frontswap.c:frontswap_shrink
  - fs/file_table.c:__fput
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/ext4/balloc.c:ext4_claim_free_clusters
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - net/core/sock.c:sk_clone_lock
  - net/core/dst.c:dst_destroy
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_single
  - lib/flex_proportions.c:fprop_new_period
```
**Symbols:**

```
ffffffff81560d70-ffffffff81560de8: percpu_counter_add_batch (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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

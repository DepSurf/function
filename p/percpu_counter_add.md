# Function: <code>percpu_counter_add</code>

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
In mm/shmem.c (ffffffff811a82c7)
Location: include/linux/percpu_counter.h:51
Inline: True
Inline callers:
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
```
```
In fs/file_table.c (ffffffff8120e0ff)
Location: include/linux/percpu_counter.h:51
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
  - fs/file_table.c:get_empty_filp
  - fs/file_table.c:__fput
```
```
In fs/quota/dquot.c (ffffffff812714c4)
Location: include/linux/percpu_counter.h:51
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/ext4/balloc.c (ffffffff8128f1a7)
Location: include/linux/percpu_counter.h:51
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_claim_free_clusters
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff81293b04)
Location: include/linux/percpu_counter.h:51
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff81297455)
Location: include/linux/percpu_counter.h:51
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/resize.c (ffffffff812c0c08)
Location: include/linux/percpu_counter.h:51
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/mballoc.c (ffffffff812ce488)
Location: include/linux/percpu_counter.h:51
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
```
```
In fs/ext4/extents_status.c (ffffffff812dac26)
Location: include/linux/percpu_counter.h:51
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_free_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In lib/flex_proportions.c (ffffffff813e9875)
Location: include/linux/percpu_counter.h:51
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
  - lib/flex_proportions.c:__fprop_inc_single
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_percpu_max
```
```
In net/core/sock.c (ffffffff81703ffd)
Location: include/linux/percpu_counter.h:51
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dst.c (ffffffff81723873)
Location: include/linux/percpu_counter.h:51
Inline: True
Inline callers:
  - net/core/dst.c:dst_init
  - net/core/dst.c:dst_destroy
```
```
In net/ipv4/inet_hashtables.c (ffffffff81762daf)
Location: include/linux/percpu_counter.h:51
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817648cd)
Location: include/linux/percpu_counter.h:51
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffffffff8176593b)
Location: include/linux/percpu_counter.h:51
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177cb43)
Location: include/linux/percpu_counter.h:51
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
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
In mm/shmem.c (ffffffff811c0960)
Location: include/linux/percpu_counter.h:51
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
```
```
In fs/file_table.c (ffffffff81234f93)
Location: include/linux/percpu_counter.h:51
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:get_empty_filp
  - fs/file_table.c:get_empty_filp
```
```
In fs/quota/dquot.c (ffffffff8129fe7a)
Location: include/linux/percpu_counter.h:51
Inline: True
Inline callers:
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
```
```
In fs/ext4/balloc.c (ffffffff812bca50)
Location: include/linux/percpu_counter.h:51
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_claim_free_clusters
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff812c264a)
Location: include/linux/percpu_counter.h:51
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff812c5a91)
Location: include/linux/percpu_counter.h:51
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/resize.c (ffffffff812f04d6)
Location: include/linux/percpu_counter.h:51
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/mballoc.c (ffffffff81305257)
Location: include/linux/percpu_counter.h:51
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/extents_status.c (ffffffff8130a8cd)
Location: include/linux/percpu_counter.h:51
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In lib/flex_proportions.c (ffffffff8142fef6)
Location: include/linux/percpu_counter.h:51
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_single
  - lib/flex_proportions.c:fprop_new_period
```
```
In net/core/sock.c (ffffffff8176aa5c)
Location: include/linux/percpu_counter.h:51
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dst.c (ffffffff8178d8d1)
Location: include/linux/percpu_counter.h:51
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
  - net/core/dst.c:dst_init
```
```
In net/ipv4/inet_hashtables.c (ffffffff817cf07f)
Location: include/linux/percpu_counter.h:51
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817d1015)
Location: include/linux/percpu_counter.h:51
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/tcp.c (ffffffff817d6dde)
Location: include/linux/percpu_counter.h:51
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ea46d)
Location: include/linux/percpu_counter.h:51
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
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
In mm/shmem.c (ffffffff811d0f3f)
Location: include/linux/percpu_counter.h:51
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
```
```
In fs/file_table.c (ffffffff81247b40)
Location: include/linux/percpu_counter.h:51
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:get_empty_filp
  - fs/file_table.c:get_empty_filp
```
```
In fs/quota/dquot.c (ffffffff812b5369)
Location: include/linux/percpu_counter.h:51
Inline: True
Inline callers:
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
```
```
In fs/ext4/balloc.c (ffffffff812d20a0)
Location: include/linux/percpu_counter.h:51
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_claim_free_clusters
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff812d7c7f)
Location: include/linux/percpu_counter.h:51
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff812db2c1)
Location: include/linux/percpu_counter.h:51
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/resize.c (ffffffff813064a6)
Location: include/linux/percpu_counter.h:51
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/mballoc.c (ffffffff8131b227)
Location: include/linux/percpu_counter.h:51
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/extents_status.c (ffffffff813208cd)
Location: include/linux/percpu_counter.h:51
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In lib/flex_proportions.c (ffffffff8144c126)
Location: include/linux/percpu_counter.h:51
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_single
  - lib/flex_proportions.c:fprop_new_period
```
```
In net/core/sock.c (ffffffff81797b89)
Location: include/linux/percpu_counter.h:51
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dst.c (ffffffff817bb1a1)
Location: include/linux/percpu_counter.h:51
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
  - net/core/dst.c:dst_init
```
```
In net/ipv4/inet_hashtables.c (ffffffff817fee8f)
Location: include/linux/percpu_counter.h:51
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81800ed5)
Location: include/linux/percpu_counter.h:51
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/tcp.c (ffffffff81806dfe)
Location: include/linux/percpu_counter.h:51
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81818c65)
Location: include/linux/percpu_counter.h:51
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
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
In mm/shmem.c (ffffffff811dcce0)
Location: include/linux/percpu_counter.h:52
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mcopy_atomic_pte
  - mm/shmem.c:shmem_mcopy_atomic_pte
  - mm/shmem.c:shmem_mcopy_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
```
```
In fs/file_table.c (ffffffff81253370)
Location: include/linux/percpu_counter.h:52
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:get_empty_filp
  - fs/file_table.c:get_empty_filp
```
```
In fs/quota/dquot.c (ffffffff812c1b2a)
Location: include/linux/percpu_counter.h:52
Inline: True
Inline callers:
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
```
```
In fs/ext4/balloc.c (ffffffff812e370b)
Location: include/linux/percpu_counter.h:52
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_claim_free_clusters
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/extents_status.c (ffffffff812ef855)
Location: include/linux/percpu_counter.h:52
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/ialloc.c (ffffffff812f5f40)
Location: include/linux/percpu_counter.h:52
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff812ffb81)
Location: include/linux/percpu_counter.h:52
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff8131260b)
Location: include/linux/percpu_counter.h:52
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/resize.c (ffffffff81320e50)
Location: include/linux/percpu_counter.h:52
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In net/core/sock.c (ffffffff817b577d)
Location: include/linux/percpu_counter.h:52
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dst.c (ffffffff817d99ea)
Location: include/linux/percpu_counter.h:52
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
```
```
In net/ipv4/inet_hashtables.c (ffffffff8181f12f)
Location: include/linux/percpu_counter.h:52
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81820c35)
Location: include/linux/percpu_counter.h:52
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/tcp.c (ffffffff818274e3)
Location: include/linux/percpu_counter.h:52
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81839438)
Location: include/linux/percpu_counter.h:52
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In lib/flex_proportions.c (ffffffff818ec8d6)
Location: include/linux/percpu_counter.h:52
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_single
  - lib/flex_proportions.c:fprop_new_period
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
In mm/shmem.c (ffffffff811eef8b)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
```
```
In fs/file_table.c (ffffffff81275473)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:get_empty_filp
  - fs/file_table.c:get_empty_filp
```
```
In fs/quota/dquot.c (ffffffff812e5977)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
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
```
```
In fs/ext4/balloc.c (ffffffff813080fb)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_claim_free_clusters
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/extents_status.c (ffffffff81314355)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/ialloc.c (ffffffff8131a596)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff81324391)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff81336dfa)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/resize.c (ffffffff81345586)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In net/core/sock.c (ffffffff8182dc29)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dst.c (ffffffff81854391)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
```
```
In net/ipv4/inet_hashtables.c (ffffffff8189e09f)
Location: include/linux/percpu_counter.h:53
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8189fc2c)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/tcp.c (ffffffff818a62ef)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818b8b9e)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In lib/flex_proportions.c (ffffffff819728a6)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_single
  - lib/flex_proportions.c:fprop_new_period
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
In mm/shmem.c (ffffffff8120fa9d)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
```
```
In fs/file_table.c (ffffffff8129bcf3)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:get_empty_filp
  - fs/file_table.c:get_empty_filp
```
```
In fs/quota/dquot.c (ffffffff81312ff0)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
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
```
```
In fs/ext4/balloc.c (ffffffff81335ffb)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_claim_free_clusters
```
```
In fs/ext4/extents_status.c (ffffffff8134221d)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/ialloc.c (ffffffff81348241)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/inode.c (ffffffff813525da)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff813653ec)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/resize.c (ffffffff81373650)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff81387141)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In net/core/sock.c (ffffffff81878000)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dst.c (ffffffff8189faa0)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
```
```
In net/ipv4/inet_hashtables.c (ffffffff818f2a65)
Location: include/linux/percpu_counter.h:53
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f4c88)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/tcp.c (ffffffff818fb35c)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8190e05a)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In lib/flex_proportions.c (ffffffff819cecd6)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_single
  - lib/flex_proportions.c:fprop_new_period
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
In mm/shmem.c (ffffffff812229e4)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
```
```
In fs/file_table.c (ffffffff812b09c1)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/quota/dquot.c (ffffffff81329f80)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
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
```
```
In fs/ext4/balloc.c (ffffffff8134d27b)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_claim_free_clusters
```
```
In fs/ext4/extents.c (ffffffff8135057c)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
```
In fs/ext4/extents_status.c (ffffffff81359b1d)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/ialloc.c (ffffffff813603f1)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/inode.c (ffffffff8136c168)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff8137d7ac)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/resize.c (ffffffff8138ba45)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff8139fc51)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In net/core/sock.c (ffffffff818984e2)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dst.c (ffffffff818c222f)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
```
```
In net/ipv4/inet_hashtables.c (ffffffff819204d5)
Location: include/linux/percpu_counter.h:53
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8192218a)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/tcp.c (ffffffff819292a0)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193c44a)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In lib/flex_proportions.c (ffffffff81a08196)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_single
  - lib/flex_proportions.c:fprop_new_period
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
In mm/shmem.c (ffffffff81231fe5)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
```
```
In fs/file_table.c (ffffffff812cd33f)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/quota/dquot.c (ffffffff81351af7)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
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
```
```
In fs/ext4/balloc.c (ffffffff81375c7b)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_claim_free_clusters
```
```
In fs/ext4/extents.c (ffffffff8137923e)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
```
In fs/ext4/extents_status.c (ffffffff81382b5f)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/ialloc.c (ffffffff81389571)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/inode.c (ffffffff8139573b)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff813a7368)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/resize.c (ffffffff813b6694)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813c9f41)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In net/core/sock.c (ffffffff818e2a8f)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dst.c (ffffffff8190e98f)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
```
```
In net/ipv4/inet_hashtables.c (ffffffff81982e09)
Location: include/linux/percpu_counter.h:53
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81985270)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/tcp.c (ffffffff8198c1cb)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a088b)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In lib/flex_proportions.c (ffffffff81a77ae5)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_single
  - lib/flex_proportions.c:fprop_new_period
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
In mm/shmem.c (ffffffff812400a5)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
```
```
In fs/file_table.c (ffffffff812ded5f)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/quota/dquot.c (ffffffff81369e77)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
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
```
```
In fs/ext4/balloc.c (ffffffff8138deeb)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_claim_free_clusters
```
```
In fs/ext4/extents.c (ffffffff813915ee)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
```
In fs/ext4/extents_status.c (ffffffff8139c8db)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/ialloc.c (ffffffff813a1ea6)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/inode.c (ffffffff813ae10b)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff813c01f8)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/resize.c (ffffffff813cf5c4)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813e3246)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In net/core/sock.c (ffffffff81914c6a)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dst.c (ffffffff81940fef)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
```
```
In net/ipv4/inet_hashtables.c (ffffffff819b9669)
Location: include/linux/percpu_counter.h:53
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bb360)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/tcp.c (ffffffff819c2b1b)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819d744c)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In lib/flex_proportions.c (ffffffff81aaeed5)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_single
  - lib/flex_proportions.c:fprop_new_period
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
In mm/shmem.c (ffffffff8126e949)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
```
```
In fs/file_table.c (ffffffff81315ebf)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:alloc_empty_file
```
```
In fs/quota/dquot.c (ffffffff813b1056)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
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
```
```
In fs/ext4/balloc.c (ffffffff813d940b)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_claim_free_clusters
```
```
In fs/ext4/extents.c (ffffffff813dd0ce)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
```
In fs/ext4/extents_status.c (ffffffff813e801b)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/ialloc.c (ffffffff813edfac)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/inode.c (ffffffff813fa0db)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff8140c31b)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/resize.c (ffffffff81419296)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff814307e6)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In lib/flex_proportions.c (ffffffff815e8b56)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_single
  - lib/flex_proportions.c:fprop_new_period
```
```
In net/core/sock.c (ffffffff819e71db)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aa41b9)
Location: include/linux/percpu_counter.h:53
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa6255)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/tcp.c (ffffffff81aae0f4)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac5ec8)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/mptcp/protocol.c (ffffffff81bab54b)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_v6_destroy
```
```
In net/mptcp/subflow.c (ffffffff81baef2e)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
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
In mm/shmem.c (ffffffff8127933f)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
```
```
In fs/file_table.c (ffffffff81321449)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:alloc_empty_file
```
```
In fs/io_uring.c (ffffffff813999f7)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_req_free_batch
  - fs/io_uring.c:__io_free_req
```
```
In fs/quota/dquot.c (ffffffff813c2656)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
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
```
```
In fs/ext4/balloc.c (ffffffff813eb11a)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_should_retry_alloc
  - fs/ext4/balloc.c:ext4_claim_free_clusters
```
```
In fs/ext4/extents.c (ffffffff813ee9ee)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
```
In fs/ext4/extents_status.c (ffffffff813fa31c)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/ialloc.c (ffffffff814005fd)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/inode.c (ffffffff8140c6d9)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff8141f750)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/resize.c (ffffffff8142d2a5)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff81449591)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In lib/flex_proportions.c (ffffffff8160dc06)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_single
  - lib/flex_proportions.c:fprop_new_period
```
```
In net/core/sock.c (ffffffff819e6a1f)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aae7f9)
Location: include/linux/percpu_counter.h:54
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ab08a5)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/tcp.c (ffffffff81ab8377)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad1af8)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/mptcp/protocol.c (ffffffff81bc0a03)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_v6_destroy
```
```
In net/mptcp/subflow.c (ffffffff81bc1ac7)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
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
In mm/shmem.c (ffffffff8127e32b)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
```
```
In fs/file_table.c (ffffffff813271e9)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:alloc_empty_file
```
```
In fs/io_uring.c (ffffffff813950f6)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - fs/io_uring.c:io_free_work
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_put_req_deferred_cb
  - fs/io_uring.c:io_submit_flush_completions
  - fs/io_uring.c:io_req_free_batch
  - fs/io_uring.c:io_req_complete_post
```
```
In fs/quota/dquot.c (ffffffff813c91ac)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
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
```
```
In fs/ext4/balloc.c (ffffffff813f164a)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_should_retry_alloc
  - fs/ext4/balloc.c:ext4_claim_free_clusters
```
```
In fs/ext4/extents.c (ffffffff813f4fbe)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
```
In fs/ext4/extents_status.c (ffffffff814006dc)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/ialloc.c (ffffffff81406aaa)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/inode.c (ffffffff81412859)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff8142605a)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/resize.c (ffffffff81433f6f)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff8144ef01)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In lib/flex_proportions.c (ffffffff815f1356)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_single
  - lib/flex_proportions.c:fprop_new_period
```
```
In net/ipv4/inet_hashtables.c (ffffffff81a99979)
Location: include/linux/percpu_counter.h:54
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9ba85)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/tcp.c (ffffffff81aa3671)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/mptcp/subflow.c (ffffffff81bb2410)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
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
In mm/shmem.c (ffffffff812c014e)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
```
```
In fs/file_table.c (ffffffff81374a8d)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:alloc_empty_file
```
```
In fs/eventpoll.c (ffffffff813d01a3)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
```
```
In fs/io_uring.c (ffffffff813efdac)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_submit_flush_completions
  - fs/io_uring.c:io_req_free_batch
  - fs/io_uring.c:__io_free_req
  - fs/io_uring.c:io_req_complete_post
  - fs/io_uring.c:io_uring_drop_tctx_refs
```
```
In fs/quota/dquot.c (ffffffff81419a19)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
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
```
```
In fs/ext4/balloc.c (ffffffff8144366d)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_should_retry_alloc
  - fs/ext4/balloc.c:ext4_claim_free_clusters
```
```
In fs/ext4/extents.c (ffffffff81447229)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
```
In fs/ext4/extents_status.c (ffffffff81452cec)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/ialloc.c (ffffffff8145932e)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/inode.c (ffffffff8146566c)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff81479c40)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/resize.c (ffffffff81487982)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff814a2a50)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In fs/jbd2/checkpoint.c (ffffffff814b9983)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
```
```
In lib/flex_proportions.c (ffffffff8165e4c6)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_single
  - lib/flex_proportions.c:fprop_new_period
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
In mm/shmem.c (ffffffff8131cabb)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_folio
  - mm/shmem.c:shmem_alloc_and_acct_folio
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
```
```
In fs/file_table.c (ffffffff813f388b)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:alloc_empty_file
```
```
In fs/eventpoll.c (ffffffff814588de)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
```
```
In fs/quota/dquot.c (ffffffff81490485)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
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
```
```
In fs/ext4/balloc.c (ffffffff814bf4c8)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_should_retry_alloc
  - fs/ext4/balloc.c:ext4_claim_free_clusters
```
```
In fs/ext4/extents.c (ffffffff814c3716)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
```
In fs/ext4/extents_status.c (ffffffff814d01a2)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/ialloc.c (ffffffff814d6d1e)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/inode.c (ffffffff814e4fc0)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff814fbde2)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/resize.c (ffffffff8150b23c)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff81529e86)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In fs/jbd2/checkpoint.c (ffffffff81543643)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
```
```
In io_uring/io_uring.c (ffffffff816d6524)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:io_uring_drop_tctx_refs
  - io_uring/io_uring.c:__io_put_task
```
```
In lib/flex_proportions.c (ffffffff81777c28)
Location: include/linux/percpu_counter.h:54
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_add_percpu
  - lib/flex_proportions.c:__fprop_inc_single
  - lib/flex_proportions.c:fprop_new_period
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
In kernel/events/uprobes.c (ffffffff8134fe05)
Location: include/linux/percpu_counter.h:57
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff813906c7)
Location: include/linux/percpu_counter.h:57
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_alloc_and_acct_folio
  - mm/shmem.c:shmem_alloc_and_acct_folio
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
```
```
In mm/memory.c (ffffffff813bb226)
Location: include/linux/percpu_counter.h:57
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_set_pmd
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/rmap.c (ffffffff813d9bfd)
Location: include/linux/percpu_counter.h:57
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff813f431c)
Location: include/linux/percpu_counter.h:57
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff813fd2cd)
Location: include/linux/percpu_counter.h:57
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
```
```
In mm/ksm.c (ffffffff8141f24a)
Location: include/linux/percpu_counter.h:57
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate_device.c (ffffffff81439c3c)
Location: include/linux/percpu_counter.h:57
Inline: True
```
```
In mm/huge_memory.c (ffffffff8143d787)
Location: include/linux/percpu_counter.h:57
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81445a3d)
Location: include/linux/percpu_counter.h:57
Inline: True
```
```
In mm/userfaultfd.c (ffffffff8146bdfa)
Location: include/linux/percpu_counter.h:57
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In fs/file_table.c (ffffffff8147c678)
Location: include/linux/percpu_counter.h:57
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:alloc_empty_file
```
```
In fs/exec.c (ffffffff81484711)
Location: include/linux/percpu_counter.h:57
Inline: True
Inline callers:
  - fs/exec.c:free_bprm
  - fs/exec.c:begin_new_exec
  - fs/exec.c:get_arg_page
```
```
In fs/eventpoll.c (ffffffff814e740e)
Location: include/linux/percpu_counter.h:57
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
```
```
In fs/quota/dquot.c (ffffffff81524005)
Location: include/linux/percpu_counter.h:57
Inline: True
Inline callers:
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
```
```
In fs/ext4/balloc.c (ffffffff81557428)
Location: include/linux/percpu_counter.h:57
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_should_retry_alloc
  - fs/ext4/balloc.c:ext4_claim_free_clusters
```
```
In fs/ext4/extents.c (ffffffff8155ba26)
Location: include/linux/percpu_counter.h:57
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
```
In fs/ext4/extents_status.c (ffffffff81568af2)
Location: include/linux/percpu_counter.h:57
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/ialloc.c (ffffffff8156faa3)
Location: include/linux/percpu_counter.h:57
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/inode.c (ffffffff8157e630)
Location: include/linux/percpu_counter.h:57
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff81596579)
Location: include/linux/percpu_counter.h:57
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/resize.c (ffffffff815a5e02)
Location: include/linux/percpu_counter.h:57
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff815c8816)
Location: include/linux/percpu_counter.h:57
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In fs/jbd2/checkpoint.c (ffffffff815e2583)
Location: include/linux/percpu_counter.h:57
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
```
```
In io_uring/io_uring.c (ffffffff8178a965)
Location: include/linux/percpu_counter.h:57
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_drop_tctx_refs
  - io_uring/io_uring.c:io_task_refs_refill
  - io_uring/io_uring.c:__io_put_task
```
```
In lib/flex_proportions.c (ffffffff820208f8)
Location: include/linux/percpu_counter.h:57
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_add_percpu
  - lib/flex_proportions.c:__fprop_inc_single
  - lib/flex_proportions.c:fprop_new_period
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
In kernel/events/uprobes.c (ffffffff81380fbe)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff813c2f4d)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_alloc_and_acct_folio
  - mm/shmem.c:shmem_alloc_and_acct_folio
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
```
```
In mm/memory.c (ffffffff813efd25)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_set_pmd
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/rmap.c (ffffffff8140e2dd)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff81427bb8)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff81430579)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
```
```
In mm/ksm.c (ffffffff81453d1c)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate_device.c (ffffffff8146e8d8)
Location: include/linux/percpu_counter.h:56
Inline: True
```
```
In mm/huge_memory.c (ffffffff81472e2d)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8147b09d)
Location: include/linux/percpu_counter.h:56
Inline: True
```
```
In mm/userfaultfd.c (ffffffff814a0bcb)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In fs/file_table.c (ffffffff814b11d2)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:alloc_empty_file
```
```
In fs/exec.c (ffffffff814b92f1)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - fs/exec.c:free_bprm
  - fs/exec.c:begin_new_exec
  - fs/exec.c:get_arg_page
```
```
In fs/eventpoll.c (ffffffff8151f230)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:__ep_remove
```
```
In fs/quota/dquot.c (ffffffff8155c40e)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
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
```
```
In fs/ext4/balloc.c (ffffffff8158f2a8)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_should_retry_alloc
  - fs/ext4/balloc.c:ext4_claim_free_clusters
```
```
In fs/ext4/extents.c (ffffffff81593846)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
```
In fs/ext4/extents_status.c (ffffffff815a0752)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/ialloc.c (ffffffff815a7926)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/inode.c (ffffffff815b6040)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff815ccf86)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/resize.c (ffffffff815dc672)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff8160058e)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In fs/jbd2/checkpoint.c (ffffffff81619ef3)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
```
```
In io_uring/io_uring.c (ffffffff817cb405)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_drop_tctx_refs
  - io_uring/io_uring.c:io_task_refs_refill
  - io_uring/io_uring.c:io_put_task_remote
```
```
In lib/flex_proportions.c (ffffffff820a0938)
Location: include/linux/percpu_counter.h:56
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_add_percpu
  - lib/flex_proportions.c:__fprop_inc_single
  - lib/flex_proportions.c:fprop_new_period
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
In kernel/events/uprobes.c (ffffffff813aa397)
Location: include/linux/percpu_counter.h:69
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff813e80e1)
Location: include/linux/percpu_counter.h:69
Inline: True
Inline callers:
  - mm/shmem.c:shmem_inode_unacct_blocks
  - mm/shmem.c:shmem_inode_acct_blocks
```
```
In mm/memory.c (ffffffff8141b355)
Location: include/linux/percpu_counter.h:69
Inline: True
Inline callers:
  - mm/memory.c:set_pte_range
  - mm/memory.c:set_pte_range
  - mm/memory.c:do_set_pmd
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/rmap.c (ffffffff8143ab00)
Location: include/linux/percpu_counter.h:69
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff814613cd)
Location: include/linux/percpu_counter.h:69
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff81468f1c)
Location: include/linux/percpu_counter.h:69
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
```
```
In mm/ksm.c (ffffffff8148e6bb)
Location: include/linux/percpu_counter.h:69
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate_device.c (ffffffff8149d342)
Location: include/linux/percpu_counter.h:69
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_insert_page
```
```
In mm/huge_memory.c (ffffffff814a1590)
Location: include/linux/percpu_counter.h:69
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff814b08d4)
Location: include/linux/percpu_counter.h:69
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/userfaultfd.c (ffffffff814d03d1)
Location: include/linux/percpu_counter.h:69
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In fs/file_table.c (ffffffff814e2998)
Location: include/linux/percpu_counter.h:69
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:alloc_empty_file
```
```
In fs/exec.c (ffffffff814ebae1)
Location: include/linux/percpu_counter.h:69
Inline: True
Inline callers:
  - fs/exec.c:free_bprm
  - fs/exec.c:begin_new_exec
  - fs/exec.c:get_arg_page
```
```
In fs/eventpoll.c (ffffffff81553840)
Location: include/linux/percpu_counter.h:69
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:__ep_remove
```
```
In fs/quota/dquot.c (ffffffff81592bce)
Location: include/linux/percpu_counter.h:69
Inline: True
Inline callers:
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
```
```
In fs/ext4/balloc.c (ffffffff815c7fb8)
Location: include/linux/percpu_counter.h:69
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_should_retry_alloc
  - fs/ext4/balloc.c:ext4_claim_free_clusters
```
```
In fs/ext4/extents.c (ffffffff815cc536)
Location: include/linux/percpu_counter.h:69
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
```
In fs/ext4/extents_status.c (ffffffff815d945f)
Location: include/linux/percpu_counter.h:69
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/ialloc.c (ffffffff815e0757)
Location: include/linux/percpu_counter.h:69
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/inode.c (ffffffff815eede0)
Location: include/linux/percpu_counter.h:69
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff8160587e)
Location: include/linux/percpu_counter.h:69
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/resize.c (ffffffff81614f52)
Location: include/linux/percpu_counter.h:69
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff816392de)
Location: include/linux/percpu_counter.h:69
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In fs/jbd2/checkpoint.c (ffffffff81652e53)
Location: include/linux/percpu_counter.h:69
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
```
```
In io_uring/io_uring.c (ffffffff8180f8f5)
Location: include/linux/percpu_counter.h:69
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_drop_tctx_refs
  - io_uring/io_uring.c:io_task_refs_refill
  - io_uring/io_uring.c:io_put_task_remote
```
```
In lib/flex_proportions.c (ffffffff82178918)
Location: include/linux/percpu_counter.h:69
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_add_percpu
  - lib/flex_proportions.c:__fprop_inc_single
  - lib/flex_proportions.c:fprop_new_period
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
In mm/shmem.c (ffff8000102d3354)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
```
```
In fs/file_table.c (ffff800010385544)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/quota/dquot.c (ffff800010431fa8)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
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
```
```
In fs/ext4/balloc.c (ffff800010460018)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_claim_free_clusters
```
```
In fs/ext4/extents.c (ffff800010464a60)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
```
In fs/ext4/extents_status.c (ffff80001046f830)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/ialloc.c (ffff800010475660)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/inode.c (ffff800010482b28)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffff800010496e08)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/resize.c (ffff8000104a7ef4)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffff8000104bc7c4)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In net/core/sock.c (ffff800010bad950)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dst.c (ffff800010be0ee8)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
```
```
In net/ipv4/inet_hashtables.c (ffff800010c6ada8)
Location: include/linux/percpu_counter.h:53
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6c960)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/tcp.c (ffff800010c75928)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8c260)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In lib/flex_proportions.c (ffff800010d88680)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_single
  - lib/flex_proportions.c:fprop_new_period
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
In mm/shmem.c (c04fb37c)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
```
```
In fs/file_table.c (c056e304)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/quota/dquot.c (c05fa1b8)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
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
```
```
In fs/ext4/balloc.c (c062081c)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_claim_free_clusters
```
```
In fs/ext4/extents.c (c062523c)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
```
In fs/ext4/extents_status.c (c0630dc4)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/ialloc.c (c0636dac)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/inode.c (c0643fa4)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (c0658f00)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/resize.c (c066a17c)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (c067fe34)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In net/core/sock.c (c0ccb518)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dst.c (c0cfad64)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
```
```
In net/ipv4/inet_hashtables.c (c0d79e8c)
Location: include/linux/percpu_counter.h:53
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (c0d7be58)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/tcp.c (c0d83fb0)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_ipv4.c (c0d99dc4)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In lib/flex_proportions.c (c0e834f8)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_single
  - lib/flex_proportions.c:fprop_new_period
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
In mm/shmem.c (c000000000391f10)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
```
```
In fs/file_table.c (c00000000047b4d0)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/quota/dquot.c (c000000000543228)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
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
```
```
In fs/ext4/balloc.c (c00000000057c398)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_claim_free_clusters
```
```
In fs/ext4/extents.c (c000000000582318)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
```
In fs/ext4/extents_status.c (c00000000058fcb0)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/ialloc.c (c000000000597180)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/inode.c (c0000000005a77d8)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (c0000000005c1178)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/resize.c (c0000000005d5844)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (c0000000005f2584)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In net/core/sock.c (c000000000c83250)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dst.c (c000000000cc1870)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
```
```
In net/ipv4/inet_hashtables.c (c000000000d70130)
Location: include/linux/percpu_counter.h:53
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (c000000000d72c48)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/tcp.c (c000000000d7d0dc)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_ipv4.c (c000000000d97ef0)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In lib/flex_proportions.c (c000000000ec8da8)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_single
  - lib/flex_proportions.c:fprop_new_period
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
In mm/shmem.c (ffffffe0001ee5b4)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
```
```
In fs/file_table.c (ffffffe000258218)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/quota/dquot.c (ffffffe0002ce384)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
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
```
```
In fs/ext4/balloc.c (ffffffe0002ef6cc)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_claim_free_clusters
```
```
In fs/ext4/extents.c (ffffffe0002f307a)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
```
In fs/ext4/extents_status.c (ffffffe0002fc300)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/ialloc.c (ffffffe00030105c)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/inode.c (ffffffe00030b33c)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffe00031b86e)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/resize.c (ffffffe00032844e)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffe00033850a)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In net/core/sock.c (ffffffe00073fb2c)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dst.c (ffffffe0007670d0)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
  - net/core/dst.c:dst_init
```
```
In net/ipv4/inet_hashtables.c (ffffffe0007d0abe)
Location: include/linux/percpu_counter.h:53
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d22a4)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/tcp.c (ffffffe0007d8ab4)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007eb3da)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In lib/flex_proportions.c (ffffffe0008b26ee)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_single
  - lib/flex_proportions.c:fprop_new_period
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
In mm/shmem.c (ffffffff812386f5)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
```
```
In fs/file_table.c (ffffffff812d733f)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/quota/dquot.c (ffffffff81362457)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
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
```
```
In fs/ext4/balloc.c (ffffffff813864cb)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_claim_free_clusters
```
```
In fs/ext4/extents.c (ffffffff81389bce)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
```
In fs/ext4/extents_status.c (ffffffff81394ebb)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/ialloc.c (ffffffff8139a486)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/inode.c (ffffffff813a66eb)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff813b87d8)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/resize.c (ffffffff813c7ba4)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813db826)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In net/core/sock.c (ffffffff818b4c6a)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dst.c (ffffffff818e0fbf)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
```
```
In net/ipv4/inet_hashtables.c (ffffffff819594d9)
Location: include/linux/percpu_counter.h:53
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195b1d0)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/tcp.c (ffffffff8196298b)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819772bc)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In lib/flex_proportions.c (ffffffff81a4dd25)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_single
  - lib/flex_proportions.c:fprop_new_period
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
In mm/shmem.c (ffffffff8122b71b)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
```
```
In fs/file_table.c (ffffffff812c7fbf)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/quota/dquot.c (ffffffff813530f7)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
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
```
```
In fs/ext4/balloc.c (ffffffff81376f5b)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_claim_free_clusters
```
```
In fs/ext4/extents.c (ffffffff8137a65e)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
```
In fs/ext4/extents_status.c (ffffffff8138594b)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/ialloc.c (ffffffff8138af16)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/inode.c (ffffffff8139717b)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff813a9268)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/resize.c (ffffffff813b8624)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813cc2a6)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In net/core/sock.c (ffffffff8186ebba)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dst.c (ffffffff8189adff)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
```
```
In net/ipv4/inet_hashtables.c (ffffffff81912fc9)
Location: include/linux/percpu_counter.h:53
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81914cc0)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/tcp.c (ffffffff8191c47b)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81930d7c)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In lib/flex_proportions.c (ffffffff81a0ae15)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_single
  - lib/flex_proportions.c:fprop_new_period
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
In mm/shmem.c (ffffffff81236495)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
```
```
In fs/file_table.c (ffffffff812d514f)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/quota/dquot.c (ffffffff8135ff27)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
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
```
```
In fs/ext4/balloc.c (ffffffff81383f9b)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_claim_free_clusters
```
```
In fs/ext4/extents.c (ffffffff8138752e)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
```
In fs/ext4/extents_status.c (ffffffff8139281b)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/ialloc.c (ffffffff81397ce6)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/inode.c (ffffffff813a3f4b)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff813b6038)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/resize.c (ffffffff813c5034)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813d8cc6)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In net/core/sock.c (ffffffff81905c6a)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dst.c (ffffffff81931fef)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
```
```
In net/ipv4/inet_hashtables.c (ffffffff819c3ca9)
Location: include/linux/percpu_counter.h:53
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c59a0)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/tcp.c (ffffffff819cd15b)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e1a8c)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In lib/flex_proportions.c (ffffffff81aba115)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_single
  - lib/flex_proportions.c:fprop_new_period
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
In mm/shmem.c (ffffffff81246780)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
```
```
In fs/file_table.c (ffffffff812e5fa4)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/quota/dquot.c (ffffffff813729e3)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
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
```
```
In fs/ext4/balloc.c (ffffffff81397afb)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_claim_free_clusters
```
```
In fs/ext4/extents.c (ffffffff8139b20e)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
```
In fs/ext4/extents_status.c (ffffffff813a6781)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/ialloc.c (ffffffff813abac6)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/inode.c (ffffffff813b861b)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff813cad19)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/resize.c (ffffffff813da227)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813edfa8)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In net/core/sock.c (ffffffff81926c9f)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dst.c (ffffffff819536bf)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
```
```
In net/ipv4/inet_hashtables.c (ffffffff819cd6f9)
Location: include/linux/percpu_counter.h:53
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819cf480)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/tcp.c (ffffffff819d6ceb)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819eb7bc)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In lib/flex_proportions.c (ffffffff81ac6565)
Location: include/linux/percpu_counter.h:53
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_inc_percpu_max
  - lib/flex_proportions.c:__fprop_inc_percpu
  - lib/flex_proportions.c:__fprop_inc_single
  - lib/flex_proportions.c:fprop_new_period
```
</details>
</li>
</ul>

## Differences

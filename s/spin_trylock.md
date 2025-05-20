# Function: <code>spin_trylock</code>

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
In kernel/panic.c (ffffffff8118b95e)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In kernel/signal.c (ffffffff810923ae)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - kernel/signal.c:kdb_send_sig_info
```
```
In kernel/sched/fair.c (ffffffff810be182)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - kernel/sched/fair.c:rebalance_domains
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81137a88)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:get_dap_lock
```
```
In mm/workingset.c (ffffffff811b9bef)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In mm/vmalloc.c (ffffffff811ccd46)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In fs/dcache.c (ffffffff81222b0f)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:dentry_lru_isolate_shrink
  - fs/dcache.c:dput
  - fs/dcache.c:dput
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:d_delete
```
```
In fs/inode.c (ffffffff812280d5)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In fs/ext4/balloc.c (ffffffff8128f00c)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff81292e61)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_init_inode_table
```
```
In fs/ext4/super.c (ffffffff812ba6e4)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/mballoc.c (ffffffff812cd5d1)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_free_data_callback
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
```
```
In block/blk-ioc.c (ffffffff813bed6e)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (ffffffff813d8a22)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_offline
```
```
In drivers/tty/vt/vt.c (ffffffff814f7f48)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
```
```
In drivers/char/random.c (ffffffff81515407)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
```
```
In net/core/dev.c (ffffffff817191b2)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
```
```
In net/core/netpoll.c (ffffffff81738f66)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:netpoll_send_skb_on_dev
```
```
In net/ipv4/icmp.c (ffffffff8178e5dc)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/ipmr.c (ffffffff817a8da5)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_expire_process
```
```
In net/ipv6/icmp.c (ffffffff817e7a03)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/ip6mr.c (ffffffff817f9bcd)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ipmr_expire_process
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
In kernel/signal.c (ffffffff8109550e)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - kernel/signal.c:kdb_send_sig_info
```
```
In kernel/sched/fair.c (ffffffff810c1960)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - kernel/sched/fair.c:rebalance_domains
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8113ff33)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:get_dap_lock
```
```
In mm/workingset.c (ffffffff811d3f8f)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In mm/vmalloc.c (ffffffff811e9df5)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In fs/dcache.c (ffffffff8124c8c7)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - fs/dcache.c:d_delete
  - fs/dcache.c:dentry_lru_isolate_shrink
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
```
In fs/inode.c (ffffffff81250805)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In fs/ext4/balloc.c (ffffffff812bd230)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff812c313a)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/super.c (ffffffff812ec012)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In fs/ext4/mballoc.c (ffffffff8130552f)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_free_data_callback
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In block/blk-ioc.c (ffffffff81402d43)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (ffffffff8141e779)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_offline
```
```
In drivers/tty/vt/vt.c (ffffffff8154a50f)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
```
```
In drivers/char/random.c (ffffffff815675b3)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81738771)
Location: include/linux/spinlock.h:310
Inline: True
```
```
In net/core/netpoll.c (ffffffff817a5402)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/ipv4/icmp.c (ffffffff817fbbe8)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/ipmr.c (ffffffff818165a5)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_expire_process
```
```
In net/ipv6/icmp.c (ffffffff8185685d)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff8186944d)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ipmr_expire_process
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
In kernel/signal.c (ffffffff8109a4fe)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - kernel/signal.c:kdb_send_sig_info
```
```
In kernel/sched/fair.c (ffffffff810c7950)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - kernel/sched/fair.c:rebalance_domains
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81149d23)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:get_dap_lock
```
```
In mm/workingset.c (ffffffff811e3e4f)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In fs/dcache.c (ffffffff8125f8b7)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - fs/dcache.c:d_delete
  - fs/dcache.c:dentry_lru_isolate_shrink
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
```
In fs/inode.c (ffffffff812638a5)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In fs/ext4/balloc.c (ffffffff812d2880)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff812d872a)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/super.c (ffffffff81301fd2)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In fs/ext4/mballoc.c (ffffffff8131b4f6)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_free_data_callback
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In block/blk-ioc.c (ffffffff8141ca73)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (ffffffff81439d39)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_offline
```
```
In drivers/tty/vt/vt.c (ffffffff81576d3f)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
```
```
In drivers/char/random.c (ffffffff81593ce3)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
```
```
In net/core/netpoll.c (ffffffff817d3e71)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
```
```
In net/ipv4/icmp.c (ffffffff8182cb38)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/ipmr.c (ffffffff81847d55)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_expire_process
```
```
In net/ipv6/icmp.c (ffffffff8188865f)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff8189c29d)
Location: include/linux/spinlock.h:310
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ipmr_expire_process
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
In kernel/signal.c (ffffffff8109767e)
Location: include/linux/spinlock.h:307
Inline: True
Inline callers:
  - kernel/signal.c:kdb_send_sig_info
```
```
In kernel/sched/fair.c (ffffffff810c1602)
Location: include/linux/spinlock.h:307
Inline: True
Inline callers:
  - kernel/sched/fair.c:rebalance_domains
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8114bb83)
Location: include/linux/spinlock.h:307
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:get_dap_lock
```
```
In mm/workingset.c (ffffffff811ee42f)
Location: include/linux/spinlock.h:307
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In fs/dcache.c (ffffffff8126d207)
Location: include/linux/spinlock.h:307
Inline: True
Inline callers:
  - fs/dcache.c:d_delete
  - fs/dcache.c:dentry_lru_isolate_shrink
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:d_prune_aliases
```
```
In fs/inode.c (ffffffff81271255)
Location: include/linux/spinlock.h:307
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In fs/ext4/balloc.c (ffffffff812e3f48)
Location: include/linux/spinlock.h:307
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff812f6b44)
Location: include/linux/spinlock.h:307
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff813130c4)
Location: include/linux/spinlock.h:307
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff81336f0e)
Location: include/linux/spinlock.h:307
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In block/blk-ioc.c (ffffffff8142a9e3)
Location: include/linux/spinlock.h:307
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (ffffffff814475bb)
Location: include/linux/spinlock.h:307
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_offline
```
```
In drivers/tty/vt/vt.c (ffffffff8158ac3f)
Location: include/linux/spinlock.h:307
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
```
```
In drivers/char/random.c (ffffffff815a7a38)
Location: include/linux/spinlock.h:307
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
```
```
In net/core/netpoll.c (ffffffff817f3268)
Location: include/linux/spinlock.h:307
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
```
```
In net/ipv4/icmp.c (ffffffff8184df94)
Location: include/linux/spinlock.h:307
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/ipmr.c (ffffffff8186a645)
Location: include/linux/spinlock.h:307
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_expire_process
```
```
In net/ipv6/icmp.c (ffffffff818aedb8)
Location: include/linux/spinlock.h:307
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff818c265d)
Location: include/linux/spinlock.h:307
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ipmr_expire_process
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
In kernel/signal.c (ffffffff8109e36e)
Location: include/linux/spinlock.h:318
Inline: True
Inline callers:
  - kernel/signal.c:kdb_send_sig_info
```
```
In kernel/sched/fair.c (ffffffff810c8da2)
Location: include/linux/spinlock.h:318
Inline: True
Inline callers:
  - kernel/sched/fair.c:rebalance_domains
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81158453)
Location: include/linux/spinlock.h:318
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:get_dap_lock
```
```
In mm/workingset.c (ffffffff8120477f)
Location: include/linux/spinlock.h:318
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In fs/dcache.c (ffffffff8128f5a7)
Location: include/linux/spinlock.h:318
Inline: True
Inline callers:
  - fs/dcache.c:d_delete
  - fs/dcache.c:dentry_lru_isolate_shrink
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:d_prune_aliases
```
```
In fs/inode.c (ffffffff81293b75)
Location: include/linux/spinlock.h:318
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In fs/ext4/balloc.c (ffffffff8130893a)
Location: include/linux/spinlock.h:318
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff8131b174)
Location: include/linux/spinlock.h:318
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff81337884)
Location: include/linux/spinlock.h:318
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff8135b4a0)
Location: include/linux/spinlock.h:318
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In block/blk-ioc.c (ffffffff81455bd3)
Location: include/linux/spinlock.h:318
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (ffffffff814741ab)
Location: include/linux/spinlock.h:318
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_offline
```
```
In drivers/tty/vt/vt.c (ffffffff815ef6cf)
Location: include/linux/spinlock.h:318
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
```
```
In drivers/char/random.c (ffffffff8160e338)
Location: include/linux/spinlock.h:318
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81811bad)
Location: include/linux/spinlock.h:318
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock
```
```
In net/core/netpoll.c (ffffffff8186e614)
Location: include/linux/spinlock.h:318
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
```
```
In net/ipv4/icmp.c (ffffffff818cdcb4)
Location: include/linux/spinlock.h:318
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/ipmr.c (ffffffff818eadc5)
Location: include/linux/spinlock.h:318
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_expire_process
```
```
In net/ipv6/icmp.c (ffffffff81931abb)
Location: include/linux/spinlock.h:318
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff81945f9d)
Location: include/linux/spinlock.h:318
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
In kernel/signal.c (ffffffff810a2d95)
Location: include/linux/spinlock.h:318
Inline: True
Inline callers:
  - kernel/signal.c:kdb_send_sig
```
```
In kernel/sched/fair.c (ffffffff810d085d)
Location: include/linux/spinlock.h:318
Inline: True
Inline callers:
  - kernel/sched/fair.c:rebalance_domains
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81167091)
Location: include/linux/spinlock.h:318
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:get_dap_lock
```
```
In mm/workingset.c (ffffffff8122556c)
Location: include/linux/spinlock.h:318
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In fs/dcache.c (ffffffff812b4b25)
Location: include/linux/spinlock.h:318
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate_shrink
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dentry_kill
  - fs/dcache.c:dentry_kill
  - fs/dcache.c:dentry_kill
```
```
In fs/inode.c (ffffffff812b9e85)
Location: include/linux/spinlock.h:318
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In fs/ext4/balloc.c (ffffffff813368a3)
Location: include/linux/spinlock.h:318
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff8134906c)
Location: include/linux/spinlock.h:318
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff81365de4)
Location: include/linux/spinlock.h:318
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff81389cd1)
Location: include/linux/spinlock.h:318
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In block/blk-ioc.c (ffffffff81489113)
Location: include/linux/spinlock.h:318
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (ffffffff814a89ab)
Location: include/linux/spinlock.h:318
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_free
  - block/blk-cgroup.c:blkcg_css_offline
```
```
In drivers/tty/vt/vt.c (ffffffff816284b5)
Location: include/linux/spinlock.h:318
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
```
```
In drivers/char/random.c (ffffffff81647de6)
Location: include/linux/spinlock.h:318
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8185b961)
Location: include/linux/spinlock.h:318
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock
```
```
In net/core/dev.c (ffffffff81891c6d)
Location: include/linux/spinlock.h:318
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff818bf7a7)
Location: include/linux/spinlock.h:318
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
```
```
In net/ipv4/icmp.c (ffffffff81924421)
Location: include/linux/spinlock.h:318
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/ipmr.c (ffffffff81941565)
Location: include/linux/spinlock.h:318
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_expire_process
```
```
In net/ipv6/icmp.c (ffffffff8198a571)
Location: include/linux/spinlock.h:318
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff8199d425)
Location: include/linux/spinlock.h:318
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
In kernel/signal.c (ffffffff810ab995)
Location: include/linux/spinlock.h:337
Inline: True
Inline callers:
  - kernel/signal.c:kdb_send_sig
```
```
In kernel/sched/fair.c (ffffffff810da09d)
Location: include/linux/spinlock.h:337
Inline: True
Inline callers:
  - kernel/sched/fair.c:rebalance_domains
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81173df1)
Location: include/linux/spinlock.h:337
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:get_dap_lock
```
```
In mm/workingset.c (ffffffff81238a10)
Location: include/linux/spinlock.h:337
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In fs/dcache.c (ffffffff812c9da5)
Location: include/linux/spinlock.h:337
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate_shrink
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dentry_kill
  - fs/dcache.c:dentry_kill
  - fs/dcache.c:dentry_kill
```
```
In fs/inode.c (ffffffff812cee65)
Location: include/linux/spinlock.h:337
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In fs/ext4/balloc.c (ffffffff8134db23)
Location: include/linux/spinlock.h:337
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff8136122c)
Location: include/linux/spinlock.h:337
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff8137e244)
Location: include/linux/spinlock.h:337
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff813a284b)
Location: include/linux/spinlock.h:337
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In block/blk-ioc.c (ffffffff814a2ecf)
Location: include/linux/spinlock.h:337
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (ffffffff814c3005)
Location: include/linux/spinlock.h:337
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
```
```
In drivers/tty/vt/vt.c (ffffffff81645d34)
Location: include/linux/spinlock.h:337
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
```
```
In drivers/char/random.c (ffffffff81666286)
Location: include/linux/spinlock.h:337
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8187b081)
Location: include/linux/spinlock.h:337
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock
```
```
In net/core/dev.c (ffffffff818b25c7)
Location: include/linux/spinlock.h:337
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff818e85cd)
Location: include/linux/spinlock.h:337
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
```
```
In net/ipv4/icmp.c (ffffffff81952ffc)
Location: include/linux/spinlock.h:337
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ipmr.c (ffffffff819719d5)
Location: include/linux/spinlock.h:337
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_expire_process
```
```
In net/ipv6/icmp.c (ffffffff819c0e0b)
Location: include/linux/spinlock.h:337
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff819d3f85)
Location: include/linux/spinlock.h:337
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
In kernel/signal.c (ffffffff810b0e85)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - kernel/signal.c:kdb_send_sig
```
```
In kernel/sched/fair.c (ffffffff810e13ce)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - kernel/sched/fair.c:rebalance_domains
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81180b68)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:get_dap_lock
```
```
In mm/workingset.c (ffffffff81249c70)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In fs/dcache.c (ffffffff812e6795)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate_shrink
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
```
In fs/inode.c (ffffffff812ebd65)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In fs/ext4/balloc.c (ffffffff81376509)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff8138a2d0)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff813a76d4)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff813ca6e5)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In block/blk-ioc.c (ffffffff814d0f7d)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (ffffffff814f1655)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
```
```
In drivers/tty/vt/vt.c (ffffffff8167a2b1)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
```
```
In drivers/char/random.c (ffffffff8169bf78)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff818c06e0)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock
```
```
In net/core/dev.c (ffffffff818fec51)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff81937e5f)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
```
```
In net/ipv4/icmp.c (ffffffff819b7b31)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ipmr.c (ffffffff819db155)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_expire_process
```
```
In net/ipv6/icmp.c (ffffffff81a2fb3d)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff81a42e35)
Location: include/linux/spinlock.h:346
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
In kernel/signal.c (ffffffff810b75d5)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - kernel/signal.c:kdb_send_sig
```
```
In kernel/sched/fair.c (ffffffff810eba6e)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - kernel/sched/fair.c:rebalance_domains
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8118c9d8)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:get_dap_lock
```
```
In mm/workingset.c (ffffffff812580c0)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In fs/dcache.c (ffffffff812f82f5)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate_shrink
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
```
In fs/inode.c (ffffffff812fd8b5)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In fs/ext4/balloc.c (ffffffff8138e779)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff813a2d08)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff813c0574)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff813e3a95)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In block/blk-ioc.c (ffffffff814ea33d)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (ffffffff8150ac45)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
```
```
In drivers/tty/vt/vt.c (ffffffff8169caa1)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
```
```
In drivers/char/random.c (ffffffff816beca8)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff818f31e0)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock
```
```
In net/core/dev.c (ffffffff81930f91)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff8196ad1f)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
```
```
In net/ipv4/icmp.c (ffffffff819ee831)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ipmr.c (ffffffff81a12035)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_expire_process
```
```
In net/ipv6/icmp.c (ffffffff81a6668d)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff81a79995)
Location: include/linux/spinlock.h:346
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
In kernel/signal.c (ffffffff810bf525)
Location: include/linux/spinlock.h:361
Inline: True
Inline callers:
  - kernel/signal.c:kdb_send_sig
```
```
In kernel/sched/fair.c (ffffffff810f5879)
Location: include/linux/spinlock.h:361
Inline: True
Inline callers:
  - kernel/sched/fair.c:rebalance_domains
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811a1455)
Location: include/linux/spinlock.h:361
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:get_dap_lock
```
```
In mm/workingset.c (ffffffff812868e0)
Location: include/linux/spinlock.h:361
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In fs/dcache.c (ffffffff81331225)
Location: include/linux/spinlock.h:361
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate_shrink
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dentry_kill
  - fs/dcache.c:dentry_kill
  - fs/dcache.c:dentry_kill
```
```
In fs/inode.c (ffffffff81336d25)
Location: include/linux/spinlock.h:361
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In fs/ext4/balloc.c (ffffffff813d9f34)
Location: include/linux/spinlock.h:361
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff813eee40)
Location: include/linux/spinlock.h:361
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff8140c6a4)
Location: include/linux/spinlock.h:361
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_extent
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_free_data_in_buddy
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff81430f05)
Location: include/linux/spinlock.h:361
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In block/blk-ioc.c (ffffffff815492dd)
Location: include/linux/spinlock.h:361
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (ffffffff8156bc95)
Location: include/linux/spinlock.h:361
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
```
```
In drivers/tty/vt/vt.c (ffffffff8174f161)
Location: include/linux/spinlock.h:361
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
```
```
In drivers/char/random.c (ffffffff81773975)
Location: include/linux/spinlock.h:361
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff819c8bd8)
Location: include/linux/spinlock.h:361
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock
```
```
In net/core/dev.c (ffffffff81a06202)
Location: include/linux/spinlock.h:361
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/core/netpoll.c (ffffffff81a3e832)
Location: include/linux/spinlock.h:361
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
```
```
In net/ipv4/icmp.c (ffffffff81adc5ad)
Location: include/linux/spinlock.h:361
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ipmr.c (ffffffff81b04485)
Location: include/linux/spinlock.h:361
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_expire_process
```
```
In net/ipv6/icmp.c (ffffffff81b5f03c)
Location: include/linux/spinlock.h:361
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff81b74405)
Location: include/linux/spinlock.h:361
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
In kernel/signal.c (ffffffff810ba725)
Location: include/linux/spinlock.h:362
Inline: True
Inline callers:
  - kernel/signal.c:kdb_send_sig
```
```
In kernel/sched/fair.c (ffffffff810f396f)
Location: include/linux/spinlock.h:362
Inline: True
Inline callers:
  - kernel/sched/fair.c:rebalance_domains
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8119e5a5)
Location: include/linux/spinlock.h:362
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:get_dap_lock
```
```
In mm/workingset.c (ffffffff8129094c)
Location: include/linux/spinlock.h:362
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In fs/dcache.c (ffffffff8133cbc4)
Location: include/linux/spinlock.h:362
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate_shrink
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dentry_kill
  - fs/dcache.c:dentry_kill
  - fs/dcache.c:dentry_kill
```
```
In fs/inode.c (ffffffff81342685)
Location: include/linux/spinlock.h:362
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In fs/ext4/balloc.c (ffffffff813ebbe9)
Location: include/linux/spinlock.h:362
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff814015b9)
Location: include/linux/spinlock.h:362
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff8141fb14)
Location: include/linux/spinlock.h:362
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_extent
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_free_data_in_buddy
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff81449cd5)
Location: include/linux/spinlock.h:362
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In block/blk-ioc.c (ffffffff815650e2)
Location: include/linux/spinlock.h:362
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (ffffffff815869a1)
Location: include/linux/spinlock.h:362
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
```
```
In drivers/tty/vt/vt.c (ffffffff8176a061)
Location: include/linux/spinlock.h:362
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
```
```
In drivers/char/random.c (ffffffff8178e928)
Location: include/linux/spinlock.h:362
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff819c8928)
Location: include/linux/spinlock.h:362
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock
```
```
In net/core/dev.c (ffffffff81a06e43)
Location: include/linux/spinlock.h:362
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/core/netpoll.c (ffffffff81a415d2)
Location: include/linux/spinlock.h:362
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
```
```
In net/ipv4/icmp.c (ffffffff81ae92c9)
Location: include/linux/spinlock.h:362
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ipmr.c (ffffffff81b12602)
Location: include/linux/spinlock.h:362
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_expire_process
```
```
In net/ipv6/icmp.c (ffffffff81b6d7cc)
Location: include/linux/spinlock.h:362
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff81b8317e)
Location: include/linux/spinlock.h:362
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
In kernel/signal.c (ffffffff810bc055)
Location: include/linux/spinlock.h:362
Inline: True
Inline callers:
  - kernel/signal.c:kdb_send_sig
```
```
In kernel/sched/fair.c (ffffffff810f6157)
Location: include/linux/spinlock.h:362
Inline: True
Inline callers:
  - kernel/sched/fair.c:rebalance_domains
```
```
In kernel/sched/debug.c (ffffffff81107aa8)
Location: include/linux/spinlock.h:362
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cfs_rq
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8119f295)
Location: include/linux/spinlock.h:362
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:get_dap_lock
```
```
In mm/workingset.c (ffffffff81296182)
Location: include/linux/spinlock.h:362
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In fs/dcache.c (ffffffff813430b4)
Location: include/linux/spinlock.h:362
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate_shrink
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dentry_kill
  - fs/dcache.c:dentry_kill
  - fs/dcache.c:dentry_kill
```
```
In fs/inode.c (ffffffff81348825)
Location: include/linux/spinlock.h:362
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In fs/ext4/balloc.c (ffffffff813f2129)
Location: include/linux/spinlock.h:362
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff81407b64)
Location: include/linux/spinlock.h:362
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff814263d9)
Location: include/linux/spinlock.h:362
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_free_data_in_buddy
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff8144f655)
Location: include/linux/spinlock.h:362
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In block/blk-ioc.c (ffffffff8156d752)
Location: include/linux/spinlock.h:362
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (ffffffff8158d6b1)
Location: include/linux/spinlock.h:362
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
```
```
In drivers/tty/vt/vt.c (ffffffff8174d9d1)
Location: include/linux/spinlock.h:362
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
```
```
In drivers/char/random.c (ffffffff817715a3)
Location: include/linux/spinlock.h:362
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff819ad878)
Location: include/linux/spinlock.h:362
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock
```
```
In net/core/dev.c (ffffffff819ee54c)
Location: include/linux/spinlock.h:362
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/core/netpoll.c (ffffffff81a26242)
Location: include/linux/spinlock.h:362
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
```
```
In net/ipv4/icmp.c (ffffffff81ad48eb)
Location: include/linux/spinlock.h:362
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/ipmr.c (ffffffff81affd22)
Location: include/linux/spinlock.h:362
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_expire_process
```
```
In net/ipv6/icmp.c (ffffffff81b5bb64)
Location: include/linux/spinlock.h:362
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff81b71dfe)
Location: include/linux/spinlock.h:362
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
In kernel/signal.c (ffffffff810cea45)
Location: include/linux/spinlock.h:371
Inline: True
Inline callers:
  - kernel/signal.c:kdb_send_sig
```
```
In kernel/sched/fair.c (ffffffff8110fecf)
Location: include/linux/spinlock.h:371
Inline: True
Inline callers:
  - kernel/sched/fair.c:rebalance_domains
```
```
In kernel/sched/debug.c (ffffffff81125ba8)
Location: include/linux/spinlock.h:371
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cfs_rq
```
```
In mm/workingset.c (ffffffff812d6912)
Location: include/linux/spinlock.h:371
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In fs/dcache.c (ffffffff81390b99)
Location: include/linux/spinlock.h:371
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate_shrink
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dentry_kill
  - fs/dcache.c:dentry_kill
  - fs/dcache.c:dentry_kill
```
```
In fs/inode.c (ffffffff813964b5)
Location: include/linux/spinlock.h:371
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In fs/ext4/balloc.c (ffffffff81444109)
Location: include/linux/spinlock.h:371
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff8145a42c)
Location: include/linux/spinlock.h:371
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff8147a089)
Location: include/linux/spinlock.h:371
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_discard_work
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff814a31d5)
Location: include/linux/spinlock.h:371
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In block/blk-ioc.c (ffffffff815d1d42)
Location: include/linux/spinlock.h:371
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (ffffffff815f3131)
Location: include/linux/spinlock.h:371
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
```
```
In drivers/tty/vt/vt.c (ffffffff817d1e14)
Location: include/linux/spinlock.h:371
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
```
```
In drivers/char/random.c (ffffffff817f7153)
Location: include/linux/spinlock.h:371
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81a5bdd8)
Location: include/linux/spinlock.h:371
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock
```
```
In net/core/dev.c (ffffffff81a9f7ec)
Location: include/linux/spinlock.h:371
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/core/netpoll.c (ffffffff81adafb2)
Location: include/linux/spinlock.h:371
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
```
```
In net/ipv4/icmp.c (ffffffff81b93628)
Location: include/linux/spinlock.h:371
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/ipmr.c (ffffffff81bc0e52)
Location: include/linux/spinlock.h:371
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_expire_process
```
```
In net/ipv6/icmp.c (ffffffff81c2329b)
Location: include/linux/spinlock.h:371
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff81c3c2ae)
Location: include/linux/spinlock.h:371
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
In kernel/signal.c (ffffffff810e69f5)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - kernel/signal.c:kdb_send_sig
```
```
In kernel/sched/fair.c (ffffffff8112bee9)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - kernel/sched/fair.c:rebalance_domains
```
```
In kernel/sched/build_utility.c (ffffffff811462ef)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:print_cfs_rq
```
```
In mm/workingset.c (ffffffff81335c4c)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:shadow_lru_isolate
```
```
In fs/dcache.c (ffffffff814124b4)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate_shrink
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:shrink_lock_dentry
  - fs/dcache.c:shrink_lock_dentry
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
```
In fs/inode.c (ffffffff814179c5)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In fs/ext4/balloc.c (ffffffff814bfffc)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff814d8142)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff814fc334)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_discard_allocated_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_discard_work
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff8152a687)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In block/blk-ioc.c (ffffffff8167dc04)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (ffffffff816a4688)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_unpin_online
```
```
In drivers/tty/vt/vt.c (ffffffff8190fa68)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81bcb3d8)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock
```
```
In net/core/dev.c (ffffffff81c17e99)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/core/netpoll.c (ffffffff81c5c466)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
```
```
In net/ipv4/icmp.c (ffffffff81d2455a)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/ipmr.c (ffffffff81d557c9)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_expire_process
```
```
In net/ipv6/icmp.c (ffffffff81dc01a1)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff81dda65d)
Location: include/linux/spinlock.h:357
Inline: True
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
In kernel/signal.c (ffffffff811076b5)
Location: include/linux/spinlock.h:358
Inline: True
Inline callers:
  - kernel/signal.c:kdb_send_sig
```
```
In kernel/sched/fair.c (ffffffff81155b22)
Location: include/linux/spinlock.h:358
Inline: True
Inline callers:
  - kernel/sched/fair.c:rebalance_domains
```
```
In kernel/sched/build_utility.c (ffffffff8117353f)
Location: include/linux/spinlock.h:358
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:print_cfs_rq
```
```
In mm/vmscan.c (ffffffff8137e3ec)
Location: include/linux/spinlock.h:358
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pte_range
```
```
In mm/workingset.c (ffffffff813aca4c)
Location: include/linux/spinlock.h:358
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:shadow_lru_isolate
```
```
In mm/page_alloc.c (ffffffff813ecd78)
Location: include/linux/spinlock.h:358
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
```
```
In fs/dcache.c (ffffffff8149d3c4)
Location: include/linux/spinlock.h:358
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate_shrink
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:shrink_lock_dentry
  - fs/dcache.c:shrink_lock_dentry
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
```
In fs/inode.c (ffffffff814a3165)
Location: include/linux/spinlock.h:358
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In fs/ext4/balloc.c (ffffffff8155803e)
Location: include/linux/spinlock.h:358
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff81570ec3)
Location: include/linux/spinlock.h:358
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff81596be1)
Location: include/linux/spinlock.h:358
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_discard_work
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ext4/super.c (ffffffff815c9047)
Location: include/linux/spinlock.h:358
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In security/apparmor/lsm.c (ffffffff816dae5f)
Location: include/linux/spinlock.h:358
Inline: True
Inline callers:
  - security/apparmor/lsm.c:aa_put_buffer
  - security/apparmor/lsm.c:aa_get_buffer
```
```
In block/blk-ioc.c (ffffffff8173a834)
Location: include/linux/spinlock.h:358
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (ffffffff817633d8)
Location: include/linux/spinlock.h:358
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_unpin_online
```
```
In drivers/tty/vt/vt.c (ffffffff81a6a1d7)
Location: include/linux/spinlock.h:358
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81d74c12)
Location: include/linux/spinlock.h:358
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock
```
```
In net/core/dev.c (ffffffff81dc8dc1)
Location: include/linux/spinlock.h:358
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/core/netpoll.c (ffffffff81e12b1a)
Location: include/linux/spinlock.h:358
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
```
```
In net/ipv4/icmp.c (ffffffff81eebd3a)
Location: include/linux/spinlock.h:358
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/ipmr.c (ffffffff81f1fb19)
Location: include/linux/spinlock.h:358
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_expire_process
```
```
In net/ipv6/icmp.c (ffffffff81f90911)
Location: include/linux/spinlock.h:358
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff81fac36d)
Location: include/linux/spinlock.h:358
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
In kernel/signal.c (ffffffff811139a5)
Location: include/linux/spinlock.h:359
Inline: True
Inline callers:
  - kernel/signal.c:kdb_send_sig
```
```
In kernel/sched/fair.c (ffffffff81165ca2)
Location: include/linux/spinlock.h:359
Inline: True
Inline callers:
  - kernel/sched/fair.c:rebalance_domains
```
```
In kernel/sched/build_utility.c (ffffffff8118414f)
Location: include/linux/spinlock.h:359
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:print_cfs_rq
```
```
In mm/vmscan.c (ffffffff813ae5ce)
Location: include/linux/spinlock.h:359
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pte_range
```
```
In mm/workingset.c (ffffffff813e0dec)
Location: include/linux/spinlock.h:359
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:shadow_lru_isolate
```
```
In mm/vmalloc.c (ffffffff81418421)
Location: include/linux/spinlock.h:359
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_dump_obj
```
```
In mm/page_alloc.c (ffffffff81421cda)
Location: include/linux/spinlock.h:359
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
```
```
In fs/dcache.c (ffffffff814d27e4)
Location: include/linux/spinlock.h:359
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate_shrink
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:shrink_lock_dentry
  - fs/dcache.c:shrink_lock_dentry
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
```
In fs/inode.c (ffffffff814d82b5)
Location: include/linux/spinlock.h:359
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In fs/ext4/balloc.c (ffffffff8158fd84)
Location: include/linux/spinlock.h:359
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff815a8c62)
Location: include/linux/spinlock.h:359
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff815cd4b1)
Location: include/linux/spinlock.h:359
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_discard_allocated_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_discard_work
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff81600e04)
Location: include/linux/spinlock.h:359
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In security/apparmor/lsm.c (ffffffff8171457f)
Location: include/linux/spinlock.h:359
Inline: True
Inline callers:
  - security/apparmor/lsm.c:aa_put_buffer
  - security/apparmor/lsm.c:aa_get_buffer
```
```
In block/blk-ioc.c (ffffffff81776f3c)
Location: include/linux/spinlock.h:359
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (ffffffff817a2528)
Location: include/linux/spinlock.h:359
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_unpin_online
```
```
In drivers/tty/vt/vt.c (ffffffff81ab48d7)
Location: include/linux/spinlock.h:359
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
```
```
In drivers/net/virtio_net.c (ffffffff81c564cb)
Location: include/linux/spinlock.h:359
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_poll
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81de2b5e)
Location: include/linux/spinlock.h:359
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock
```
```
In net/core/dev.c (ffffffff81e3732f)
Location: include/linux/spinlock.h:359
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/core/netpoll.c (ffffffff81e8643a)
Location: include/linux/spinlock.h:359
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
```
```
In net/ipv4/icmp.c (ffffffff81f4bb25)
Location: include/linux/spinlock.h:359
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/ipmr.c (ffffffff81f7f619)
Location: include/linux/spinlock.h:359
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_expire_process
```
```
In net/ipv6/icmp.c (ffffffff81ff1191)
Location: include/linux/spinlock.h:359
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff8200cb0d)
Location: include/linux/spinlock.h:359
Inline: True
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
In kernel/signal.c (ffffffff8111d395)
Location: include/linux/spinlock.h:359
Inline: True
Inline callers:
  - kernel/signal.c:kdb_send_sig
```
```
In kernel/sched/fair.c (ffffffff81172a02)
Location: include/linux/spinlock.h:359
Inline: True
Inline callers:
  - kernel/sched/fair.c:rebalance_domains
```
```
In kernel/sched/build_utility.c (ffffffff811927ff)
Location: include/linux/spinlock.h:359
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:print_cfs_rq
```
```
In mm/vmscan.c (ffffffff813d7c02)
Location: include/linux/spinlock.h:359
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pte_range
```
```
In mm/workingset.c (ffffffff8140b6bc)
Location: include/linux/spinlock.h:359
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:shadow_lru_isolate
```
```
In mm/vmalloc.c (ffffffff81444f71)
Location: include/linux/spinlock.h:359
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_dump_obj
```
```
In mm/page_alloc.c (ffffffff8144eb0a)
Location: include/linux/spinlock.h:359
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
```
```
In fs/dcache.c (ffffffff815051a4)
Location: include/linux/spinlock.h:359
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate_shrink
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:lock_for_kill
```
```
In fs/inode.c (ffffffff8150aa95)
Location: include/linux/spinlock.h:359
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In fs/ext4/balloc.c (ffffffff815c8913)
Location: include/linux/spinlock.h:359
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff815e1962)
Location: include/linux/spinlock.h:359
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff81605d31)
Location: include/linux/spinlock.h:359
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_discard_allocated_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_context
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_discard_work
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff81639b54)
Location: include/linux/spinlock.h:359
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In security/apparmor/lsm.c (ffffffff81752fc4)
Location: include/linux/spinlock.h:359
Inline: True
Inline callers:
  - security/apparmor/lsm.c:aa_put_buffer
  - security/apparmor/lsm.c:aa_get_buffer
```
```
In block/blk-ioc.c (ffffffff817b916c)
Location: include/linux/spinlock.h:359
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (ffffffff817e6068)
Location: include/linux/spinlock.h:359
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_unpin_online
```
```
In drivers/tty/vt/vt.c (ffffffff81b075b7)
Location: include/linux/spinlock.h:359
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
```
```
In drivers/net/virtio_net.c (ffffffff81d0cbbd)
Location: include/linux/spinlock.h:359
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_poll
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81e98c4e)
Location: include/linux/spinlock.h:359
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock
```
```
In net/core/dev.c (ffffffff81ef534f)
Location: include/linux/spinlock.h:359
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/core/netpoll.c (ffffffff81f48453)
Location: include/linux/spinlock.h:359
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
```
```
In net/ipv4/icmp.c (ffffffff82011c35)
Location: include/linux/spinlock.h:359
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/ipmr.c (ffffffff82045c99)
Location: include/linux/spinlock.h:359
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_expire_process
```
```
In net/ipv6/icmp.c (ffffffff820bed6f)
Location: include/linux/spinlock.h:359
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff820dbadd)
Location: include/linux/spinlock.h:359
Inline: True
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
In kernel/signal.c (ffff800010113a78)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - kernel/signal.c:kdb_send_sig
```
```
In kernel/sched/fair.c (ffff80001014bcbc)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - kernel/sched/fair.c:rebalance_domains
```
```
In kernel/debug/kdb/kdb_support.c (ffff800010203e28)
Location: include/linux/spinlock.h:346
Inline: True
```
```
In mm/workingset.c (ffff8000102f0014)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In fs/dcache.c (ffff8000103a5d10)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate_shrink
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
```
In fs/inode.c (ffff8000103aef44)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In fs/ext4/balloc.c (ffff8000104609dc)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffff800010473d68)
Location: include/linux/spinlock.h:346
Inline: True
```
```
In fs/ext4/mballoc.c (ffff80001049533c)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In fs/ext4/super.c (ffff8000104bcff0)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In block/blk-ioc.c (ffff8000105e86b4)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (ffff80001060e3cc)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
```
```
In drivers/tty/vt/vt.c (ffff8000108743d8)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
```
```
In drivers/tty/serial/amba-pl011.c (ffff800010896f6c)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:pl011_console_write
```
```
In drivers/tty/serial/meson_uart.c (ffff80001089ec04)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - drivers/tty/serial/meson_uart.c:meson_serial_port_write
```
```
In drivers/tty/serial/msm_serial.c (ffff8000108a3230)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:__msm_console_write
```
```
In drivers/tty/serial/owl-uart.c (ffff8000108a6edc)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - drivers/tty/serial/owl-uart.c:owl_uart_port_write
```
```
In drivers/char/random.c (ffff8000108b077c)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
```
```
In drivers/net/ethernet/smsc/smc91x.c (ffff8000109fc5e0)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffff800010b7ef08)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock
```
```
In net/core/dev.c (ffff800010bce6b0)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffff800010c11350)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
```
```
In net/ipv4/icmp.c (ffff800010ca4ad0)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ipmr.c (ffff800010ccae7c)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_expire_process
```
```
In net/ipv6/icmp.c (ffff800010d2c5f8)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6mr.c (ffff800010d43168)
Location: include/linux/spinlock.h:346
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
In kernel/signal.c (c036aa24)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - kernel/signal.c:kdb_send_sig
```
```
In kernel/sched/fair.c (c03999c4)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - kernel/sched/fair.c:rebalance_domains
```
```
In kernel/debug/kdb/kdb_support.c (c0442c44)
Location: include/linux/spinlock.h:346
Inline: True
```
```
In mm/workingset.c (c0513408)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In fs/dcache.c (c0587994)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate_shrink
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
```
In fs/inode.c (c058e4e0)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In fs/ext4/balloc.c (c06211a4)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (c0637ec8)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (c0659458)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (c0680864)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In block/blk-ioc.c (c0795068)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (c07b8d04)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
```
```
In drivers/tty/vt/vt.c (c09770fc)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
```
```
In drivers/tty/serial/amba-pl011.c (c098f624)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:pl011_console_write
```
```
In drivers/tty/serial/meson_uart.c (c0998660)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - drivers/tty/serial/meson_uart.c:meson_serial_port_write
```
```
In drivers/tty/serial/msm_serial.c (c099bfc8)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:__msm_console_write
```
```
In drivers/tty/serial/omap-serial.c (c09a0578)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - drivers/tty/serial/omap-serial.c:serial_omap_console_write
```
```
In drivers/tty/serial/owl-uart.c (c09a2800)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - drivers/tty/serial/owl-uart.c:owl_uart_port_write
```
```
In drivers/tty/serial/rda-uart.c (c09a36bc)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - drivers/tty/serial/rda-uart.c:rda_uart_port_write
```
```
In drivers/char/random.c (c09ab13c)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
```
```
In drivers/hwspinlock/hwspinlock_core.c (c0c61ac4)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock
```
```
In sound/core/pcm_native.c (c0c926d8)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - sound/core/pcm_native.c:snd_pcm_stream_group_ref
```
```
In net/core/dev.c (c0ce7f4c)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (c0d291ec)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
```
```
In net/ipv4/icmp.c (c0db0c20)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ipmr.c (c0dd665c)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_expire_process
```
```
In net/ipv6/icmp.c (c0e304ec)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6mr.c (c0e45984)
Location: include/linux/spinlock.h:346
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
In kernel/signal.c (c00000000015b6e4)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - kernel/signal.c:kdb_send_sig
```
```
In kernel/sched/fair.c (c00000000019e460)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - kernel/sched/fair.c:rebalance_domains
```
```
In kernel/debug/kdb/kdb_support.c (c00000000027e6dc)
Location: include/linux/spinlock.h:346
Inline: True
```
```
In mm/workingset.c (c0000000003b4658)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In fs/dcache.c (c00000000049f8d8)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate_shrink
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
```
In fs/inode.c (c0000000004a955c)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In fs/ext4/balloc.c (c00000000057d03c)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (c0000000005984e4)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (c0000000005c16b4)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (c0000000005f3018)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In block/blk-ioc.c (c00000000077d2cc)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (c0000000007ab82c)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
```
```
In drivers/tty/vt/vt.c (c0000000009154e4)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
```
```
In drivers/char/random.c (c000000000947514)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
```
```
In drivers/cpufreq/powernv-cpufreq.c (c000000000c1cc2c)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - drivers/cpufreq/powernv-cpufreq.c:gpstate_timer_handler
```
```
In drivers/hwspinlock/hwspinlock_core.c (c000000000c59e30)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock
```
```
In net/core/dev.c (c000000000cac2d0)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (c000000000cfdbd0)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
```
```
In net/ipv4/icmp.c (c000000000db7e54)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ipmr.c (c000000000debd10)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_expire_process
```
```
In net/ipv6/icmp.c (c000000000e5ded0)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6mr.c (c000000000e78150)
Location: include/linux/spinlock.h:346
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
In kernel/sched/fair.c (ffffffe0000f53be)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - kernel/sched/fair.c:rebalance_domains
```
```
In mm/workingset.c (ffffffe000203a26)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In fs/dcache.c (ffffffe00026c9b8)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate_shrink
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
```
In fs/inode.c (ffffffe000272d12)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In fs/ext4/balloc.c (ffffffe0002efe9c)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffe000301d66)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffe00031bb8c)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffe000338c6e)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In block/blk-ioc.c (ffffffe0004292e2)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (ffffffe00044692e)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
```
```
In drivers/tty/vt/vt.c (ffffffe000545d06)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
```
```
In drivers/tty/serial/sifive.c (ffffffe00055e078)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - drivers/tty/serial/sifive.c:sifive_serial_console_write
```
```
In drivers/char/random.c (ffffffe000563408)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffe00072d310)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock
```
```
In net/core/dev.c (ffffffe000758a94)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffe00078d4fc)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
```
```
In net/ipv4/icmp.c (ffffffe0007ffdc0)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ipmr.c (ffffffe000820f3c)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_expire_process
```
```
In net/ipv6/icmp.c (ffffffe00086c87a)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffe00087e832)
Location: include/linux/spinlock.h:346
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
In kernel/signal.c (ffffffff810b1945)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - kernel/signal.c:kdb_send_sig
```
```
In kernel/sched/fair.c (ffffffff810e5bce)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - kernel/sched/fair.c:rebalance_domains
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81184ff8)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:get_dap_lock
```
```
In mm/workingset.c (ffffffff81250710)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In fs/dcache.c (ffffffff812f08d5)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate_shrink
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
```
In fs/inode.c (ffffffff812f5e95)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In fs/ext4/balloc.c (ffffffff81386d59)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff8139b2e8)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff813b8b54)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff813dc075)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In block/blk-ioc.c (ffffffff814e291d)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (ffffffff81503225)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
```
```
In drivers/tty/vt/vt.c (ffffffff81662501)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
```
```
In drivers/char/random.c (ffffffff81684718)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81894510)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock
```
```
In net/core/dev.c (ffffffff818d0f91)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff8190acef)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
```
```
In net/ipv4/icmp.c (ffffffff8198e5d1)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ipmr.c (ffffffff819b1955)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_expire_process
```
```
In net/ipv6/icmp.c (ffffffff81a05d1d)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff81a19025)
Location: include/linux/spinlock.h:346
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
In kernel/signal.c (ffffffff810a0265)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - kernel/signal.c:kdb_send_sig
```
```
In kernel/sched/fair.c (ffffffff810d4d6e)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - kernel/sched/fair.c:rebalance_domains
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81178138)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:get_dap_lock
```
```
In mm/workingset.c (ffffffff812436a0)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In fs/dcache.c (ffffffff812e1505)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate_shrink
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
```
In fs/inode.c (ffffffff812e6ab5)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In fs/ext4/balloc.c (ffffffff813777e9)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff8138bd78)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff813a95e4)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff813ccaf5)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In block/blk-ioc.c (ffffffff814d32ad)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (ffffffff814f3705)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
```
```
In drivers/tty/vt/vt.c (ffffffff81642881)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
```
```
In drivers/char/random.c (ffffffff81662398)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8184c312)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock
```
```
In net/core/dev.c (ffffffff8188ae49)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff818c4a8a)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
```
```
In net/ipv4/icmp.c (ffffffff81948091)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ipmr.c (ffffffff8196df85)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_expire_process
```
```
In net/ipv6/icmp.c (ffffffff819c2add)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff819d5de5)
Location: include/linux/spinlock.h:346
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
In kernel/signal.c (ffffffff810b0ea5)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - kernel/signal.c:kdb_send_sig
```
```
In kernel/sched/fair.c (ffffffff810e1f9e)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - kernel/sched/fair.c:rebalance_domains
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81182dc8)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:get_dap_lock
```
```
In mm/workingset.c (ffffffff8124e4b0)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In fs/dcache.c (ffffffff812ee6e5)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate_shrink
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
```
In fs/inode.c (ffffffff812f3ca5)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In fs/ext4/balloc.c (ffffffff81384829)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff81398b48)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff813b63b4)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff813d9515)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In block/blk-ioc.c (ffffffff814de9ad)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (ffffffff814ff2b5)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
```
```
In drivers/tty/vt/vt.c (ffffffff816908e1)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
```
```
In drivers/char/random.c (ffffffff816b2ae8)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff818e8010)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock
```
```
In net/core/dev.c (ffffffff81921f91)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff8195bd1f)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
```
```
In net/ipv4/icmp.c (ffffffff819f8e71)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ipmr.c (ffffffff81a1c1f5)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_expire_process
```
```
In net/ipv6/icmp.c (ffffffff81a7079d)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff81a83aa5)
Location: include/linux/spinlock.h:346
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
In kernel/signal.c (ffffffff810b9175)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - kernel/signal.c:kdb_send_sig
```
```
In kernel/sched/fair.c (ffffffff810edb66)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - kernel/sched/fair.c:rebalance_domains
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81190708)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:get_dap_lock
```
```
In mm/workingset.c (ffffffff8125dd80)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In fs/dcache.c (ffffffff812ff325)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/dcache.c:dentry_lru_isolate_shrink
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
```
In fs/inode.c (ffffffff81305075)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In fs/ext4/balloc.c (ffffffff813983a4)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff813acf70)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff813cb0d4)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff813ee80a)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In block/blk-ioc.c (ffffffff814f77bd)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-cgroup.c (ffffffff81518425)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
```
```
In drivers/tty/vt/vt.c (ffffffff816aaed1)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
```
```
In drivers/char/random.c (ffffffff816cd038)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81904d2e)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock
```
```
In net/core/dev.c (ffffffff81943ca9)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff8197e101)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
```
```
In net/ipv4/icmp.c (ffffffff81a02de9)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ipmr.c (ffffffff81a27145)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_expire_process
```
```
In net/ipv6/icmp.c (ffffffff81a7cdbd)
Location: include/linux/spinlock.h:346
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff81a90285)
Location: include/linux/spinlock.h:346
Inline: True
```
</details>
</li>
</ul>

## Differences

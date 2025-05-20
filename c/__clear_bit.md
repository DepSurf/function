# Function: <code>__clear_bit</code>

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
In arch/x86/events/intel/core.c (ffffffff8100bbfe)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81043dae)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:__mce_disable_bank
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff8104716a)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_discover
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_discover
```
```
In arch/x86/mm/init_64.c (ffffffff8181bb4e)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
```
```
In kernel/workqueue.c (ffffffff81097e42)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/rt.c (ffffffff810c05eb)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:init_rt_rq
```
```
In mm/filemap.c (ffffffff8118dfa5)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/page_alloc.c (ffffffff81f870f6)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/page_alloc.c:init_cma_reserved_pageblock
```
```
In mm/swap.c (ffffffff8119c990)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
```
```
In mm/vmscan.c (ffffffff811a22b7)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:putback_inactive_pages
```
```
In mm/swap_state.c (ffffffff811d2bce)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff811daa75)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:huge_add_to_page_cache
```
```
In mm/slub.c (ffffffff811e9105)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_create
```
```
In fs/dcache.c (ffffffff812234b0)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/dcache.c:__d_drop
  - fs/dcache.c:__d_obtain_alias
```
```
In fs/file.c (ffffffff81229b6b)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/file.c:put_unused_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:do_dup2
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:__close_fd
  - fs/file.c:__close_fd
  - fs/file.c:__close_fd
  - fs/file.c:do_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:set_close_on_exec
```
```
In fs/mbcache.c (ffffffff8126c960)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/mbcache.c:__mb_cache_entry_find
  - fs/mbcache.c:__mb_cache_entry_find
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_entry_find_first
  - fs/mbcache.c:mb_cache_entry_free
  - fs/mbcache.c:mb_cache_entry_free
  - fs/mbcache.c:mb_cache_entry_insert
  - fs/mbcache.c:mb_cache_entry_insert
  - fs/mbcache.c:mb_cache_entry_insert
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_shrink_scan
  - fs/mbcache.c:mb_cache_shrink_scan
  - fs/mbcache.c:mb_cache_shrink_scan
  - fs/mbcache.c:mb_cache_shrink_scan
  - fs/mbcache.c:mb_cache_entry_alloc
  - fs/mbcache.c:mb_cache_entry_alloc
  - fs/mbcache.c:mb_cache_entry_alloc
  - fs/mbcache.c:mb_cache_entry_alloc
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_shrink
```
```
In fs/ext4/mballoc.c (ffffffff812ccf9d)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_clear_bits
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
```
```
In fs/fuse/dev.c (ffffffff8130ee91)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:fuse_force_forget
```
```
In fs/fuse/file.c (ffffffff81315247)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_sync_release
```
```
In fs/fuse/inode.c (ffffffff8131b573)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_put_super
```
```
In block/blk-core.c (ffffffff813b55b9)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - block/blk-core.c:blk_start_queue
  - block/blk-core.c:blk_start_queue_async
  - block/blk-core.c:blk_queue_bypass_end
```
```
In block/blk-tag.c (ffffffff813bbd29)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_free_tags
  - block/blk-tag.c:__blk_queue_free_tags
```
```
In block/blk-sysfs.c (ffffffff813bccb1)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_store_nonrot
  - block/blk-sysfs.c:queue_store_random
  - block/blk-sysfs.c:queue_store_iostats
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
```
```
In block/blk-cgroup.c (ffffffff813d8bf9)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
```
```
In lib/idr.c (ffffffff813ea044)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - lib/idr.c:idr_remove
  - lib/idr.c:idr_remove
  - lib/idr.c:ida_remove
  - lib/idr.c:ida_remove
  - lib/idr.c:ida_remove
```
```
In lib/radix-tree.c (ffffffff813ee128)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_node_rcu_free
  - lib/radix-tree.c:radix_tree_tag_clear
```
```
In drivers/gpio/gpiolib.c (ffffffff814267a7)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_priv
```
```
In drivers/iommu/amd_iommu.c (ffffffff8152e028)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:protection_domain_free
```
```
In drivers/block/loop.c (ffffffff8156e324)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_status
```
```
In drivers/block/xen-blkfront.c (ffffffff8157480d)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
```
```
In drivers/scsi/sd.c (ffffffff815ba194)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_config_discard
  - drivers/scsi/sd.c:sd_revalidate_disk
```
```
In drivers/input/input.c (ffffffff81666aec)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_keycode
```
```
In drivers/input/ff-core.c (ffffffff8166b143)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_destroy
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81670838)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/md/dm.c (ffffffff816a3475)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm.c:dm_setup_md_queue
```
```
In drivers/md/dm-table.c (ffffffff816a6c3d)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
```
In net/socket.c (ffffffff816fb9fc)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff817029ad)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - net/core/sock.c:sk_clear_memalloc
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
```
In net/netlink/af_netlink.c (ffffffff8174a321)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
```
```
In net/ipv4/tcp.c (ffffffff817681dd)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff8176aa3e)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (ffffffff81777afc)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
```
In net/unix/garbage.c (ffffffff817c26ad)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
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
In arch/x86/events/intel/core.c (ffffffff8100bd8d)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81043eee)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:__mce_disable_bank
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff810472ea)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_discover
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_discover
```
```
In arch/x86/mm/init_64.c (ffffffff81895d66)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
```
```
In kernel/workqueue.c (ffffffff8109b35b)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/rt.c (ffffffff810c4001)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/time/timer.c (ffffffff810f288a)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In mm/filemap.c (ffffffff811a1083)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/page_alloc.c (ffffffff81fb0935)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/page_alloc.c:__free_pages_bootmem
```
```
In mm/swap.c (ffffffff811b2aa1)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff811b7d8b)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:shrink_page_list
```
```
In mm/swap_state.c (ffffffff811f096f)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff811fb44d)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/slub.c (ffffffff8120c6ea)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff812123c0)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:putback_movable_page
```
```
In mm/huge_memory.c (ffffffff81217d28)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In fs/dcache.c (ffffffff8124bbc2)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:__d_drop
```
```
In fs/file.c (ffffffff81252713)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd
  - fs/file.c:__close_fd
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
```
```
In fs/mbcache.c (ffffffff81298abd)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_block
  - fs/mbcache.c:mb_cache_entry_delete_block
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/ext4/mballoc.c (ffffffff81301127)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_clear_bits
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dev.c (ffffffff81343d04)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_force_forget
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
```
```
In fs/fuse/file.c (ffffffff81349a97)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_sync_release
```
```
In fs/fuse/inode.c (ffffffff81350043)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_put_super
```
```
In block/blk-core.c (ffffffff813fc7dc)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_bypass_end
  - block/blk-core.c:blk_start_queue
  - block/blk-core.c:blk_start_queue_async
```
```
In block/blk-tag.c (ffffffff813ffb39)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_free_tags
  - block/blk-tag.c:__blk_queue_free_tags
```
```
In block/blk-sysfs.c (ffffffff81400b14)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wc_store
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_store_iostats
  - block/blk-sysfs.c:queue_store_random
  - block/blk-sysfs.c:queue_store_nonrot
```
```
In block/blk-settings.c (ffffffff81402b4c)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-settings.c:blk_queue_write_cache
```
```
In block/blk-cgroup.c (ffffffff8141e960)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
```
```
In lib/idr.c (ffffffff814308ae)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - lib/idr.c:ida_remove
  - lib/idr.c:ida_remove
  - lib/idr.c:ida_remove
  - lib/idr.c:idr_remove
  - lib/idr.c:idr_remove
```
```
In lib/radix-tree.c (ffffffff81434268)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_node_rcu_free
```
```
In drivers/gpio/gpiolib.c (ffffffff81472298)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
```
In drivers/iommu/amd_iommu.c (ffffffff81581b78)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:protection_domain_free
```
```
In drivers/block/loop.c (ffffffff815c3c22)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_status
```
```
In drivers/block/xen-blkfront.c (ffffffff815cb895)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
```
```
In drivers/scsi/sd.c (ffffffff816170be)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_config_discard
```
```
In drivers/input/input.c (ffffffff816c93e0)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_keycode
  - drivers/input/input.c:input_default_setkeycode
```
```
In drivers/input/ff-core.c (ffffffff816cb423)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_destroy
```
```
In drivers/input/keyboard/atkbd.c (ffffffff816d0b8a)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/md/dm.c (ffffffff81703d1b)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_init_normal_md_queue
```
```
In drivers/md/dm-table.c (ffffffff81706ebe)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
```
In drivers/md/dm-rq.c (ffffffff8170fbb9)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_start_queue
```
```
In net/socket.c (ffffffff8176245c)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff8176a965)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/netlink/af_netlink.c (ffffffff817b7235)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817d0ad1)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff817d4abc)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff817dbd2e)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (ffffffff817e4b20)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
```
In net/unix/garbage.c (ffffffff8182f6dd)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
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
In arch/x86/events/intel/core.c (ffffffff8100be6d)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104596e)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:__mce_disable_bank
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff81048e8a)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_discover
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_discover
```
```
In arch/x86/mm/init_64.c (ffffffff818ca486)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
```
```
In kernel/workqueue.c (ffffffff810a015b)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/rt.c (ffffffff810ca066)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/time/timer.c (ffffffff810f9a0a)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In mm/filemap.c (ffffffff811b0c83)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/page_alloc.c (ffffffff81fecc44)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/page_alloc.c:__free_pages_bootmem
```
```
In mm/swap.c (ffffffff811c3121)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff811c83d9)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:shrink_page_list
```
```
In mm/swap_state.c (ffffffff81201371)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff8120bf4d)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/slub.c (ffffffff8121e74a)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff812245af)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:putback_movable_page
```
```
In mm/huge_memory.c (ffffffff8122a2e9)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In fs/dcache.c (ffffffff8125eba2)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:__d_drop
```
```
In fs/file.c (ffffffff812659ab)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd
  - fs/file.c:__close_fd
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
```
```
In fs/mbcache.c (ffffffff812ad53b)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_block
  - fs/mbcache.c:mb_cache_entry_delete_block
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/ext4/mballoc.c (ffffffff8131719c)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_clear_bits
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dev.c (ffffffff813599ca)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_force_forget
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
```
```
In fs/fuse/file.c (ffffffff8135f3a7)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_sync_release
```
```
In fs/fuse/inode.c (ffffffff81365973)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_put_super
```
```
In block/blk-core.c (ffffffff8141617c)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_bypass_end
  - block/blk-core.c:blk_start_queue
  - block/blk-core.c:blk_start_queue_async
```
```
In block/blk-tag.c (ffffffff814193e9)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_free_tags
  - block/blk-tag.c:__blk_queue_free_tags
```
```
In block/blk-sysfs.c (ffffffff8141a744)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wc_store
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_store_iostats
  - block/blk-sysfs.c:queue_store_random
  - block/blk-sysfs.c:queue_store_nonrot
```
```
In block/blk-settings.c (ffffffff8141c6fc)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-settings.c:blk_queue_write_cache
```
```
In block/blk-cgroup.c (ffffffff81439f20)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
```
```
In lib/idr.c (ffffffff8144ca7c)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - lib/idr.c:ida_remove
  - lib/idr.c:ida_remove
  - lib/idr.c:ida_remove
  - lib/idr.c:idr_remove
  - lib/idr.c:idr_remove
```
```
In lib/radix-tree.c (ffffffff814528ce)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:radix_tree_join
```
```
In drivers/gpio/gpiolib.c (ffffffff814943b8)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
```
In drivers/iommu/amd_iommu.c (ffffffff815ade5b)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:domain_id_free
```
```
In drivers/block/loop.c (ffffffff815f2360)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_status
```
```
In drivers/block/xen-blkfront.c (ffffffff815f84b0)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
```
```
In drivers/scsi/sd.c (ffffffff816474fe)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_config_discard
```
```
In drivers/input/input.c (ffffffff816f73c0)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_keycode
  - drivers/input/input.c:input_default_setkeycode
```
```
In drivers/input/ff-core.c (ffffffff816f93d3)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_destroy
```
```
In drivers/input/keyboard/atkbd.c (ffffffff816fea6a)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/md/md.c (ffffffff8172a989)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
```
```
In drivers/md/dm.c (ffffffff81735be0)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_init_normal_md_queue
```
```
In drivers/md/dm-table.c (ffffffff81738d99)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
```
In net/socket.c (ffffffff8178f48c)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81797a85)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/netlink/af_netlink.c (ffffffff817e6cb5)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81800951)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff818047cf)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff8180bdde)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (ffffffff81814f70)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
```
In net/unix/garbage.c (ffffffff818611c9)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
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
In arch/x86/events/intel/core.c (ffffffff8100bbfc)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/kernel/ioport.c (0)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81045aae)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:__mce_disable_bank
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff81048897)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_discover
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_discover
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81901a03)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
```
```
In kernel/workqueue.c (ffffffff8109deef)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/rt.c (ffffffff810c3c82)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/irq/irqdesc.c (0)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
```
```
In kernel/time/timer.c (ffffffff810fbf3c)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/smp.c (ffffffff81113f79)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In mm/filemap.c (ffffffff811b81b3)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/page_alloc.c (ffffffff820ce89f)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/page_alloc.c:__free_pages_bootmem
```
```
In mm/swap.c (ffffffff811cb5b8)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff811d0d83)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:shrink_page_list
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
```
```
In mm/swap_state.c (ffffffff8120c21c)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff812175fd)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/slub.c (ffffffff8122a2e4)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff8122fef5)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:putback_movable_page
```
```
In mm/huge_memory.c (ffffffff81235eee)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/cma.c (0)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
```
```
In fs/dcache.c (ffffffff8126c572)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_drop
```
```
In fs/file.c (ffffffff812730f6)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd
  - fs/file.c:__close_fd
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
```
```
In fs/mbcache.c (ffffffff812ba9db)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/ext4/mballoc.c (ffffffff8130e1eb)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_clear_bits
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dev.c (ffffffff8136e1b2)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_force_forget
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
```
```
In fs/fuse/file.c (ffffffff813743d1)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
```
```
In fs/fuse/inode.c (ffffffff8137a10b)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_put_super
```
```
In block/blk-core.c (ffffffff8142375c)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_bypass_end
  - block/blk-core.c:blk_start_queue
  - block/blk-core.c:blk_start_queue_async
```
```
In block/blk-tag.c (ffffffff81427319)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_free_tags
  - block/blk-tag.c:__blk_queue_free_tags
```
```
In block/blk-sysfs.c (ffffffff81428f11)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:queue_wc_store
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_store_iostats
  - block/blk-sysfs.c:queue_store_random
  - block/blk-sysfs.c:queue_store_nonrot
```
```
In block/blk-settings.c (ffffffff8142a655)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-settings.c:blk_queue_write_cache
```
```
In block/blk-mq.c (ffffffff81430d19)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_unquiesce_queue
```
```
In block/blk-cgroup.c (ffffffff814474a9)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
```
```
In lib/iommu-common.c (0)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff8149d904)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
```
In drivers/pwm/core.c (0)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff815c3adb)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:domain_id_free
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
```
```
In drivers/block/loop.c (ffffffff81606545)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_status
```
```
In drivers/block/xen-blkfront.c (ffffffff8160c375)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
```
```
In drivers/scsi/sd.c (ffffffff8165b5e8)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_config_discard
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
```
```
In drivers/input/input.c (ffffffff8170cea4)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_keycode
  - drivers/input/input.c:input_default_setkeycode
```
```
In drivers/input/ff-core.c (ffffffff8170ef23)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_destroy
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81713e58)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/md/md.c (ffffffff81743040)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
```
```
In drivers/md/dm.c (ffffffff8174f454)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm.c:dm_create
```
```
In drivers/md/dm-table.c (ffffffff8175251f)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
```
In net/socket.c (ffffffff817ad40c)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff817b566e)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/netlink/af_netlink.c (ffffffff81806aff)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81820526)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff81824a48)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff81827f3e)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (ffffffff818351d6)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
```
In net/unix/garbage.c (ffffffff81885905)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In lib/idr.c (ffffffff818ed0cc)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - lib/idr.c:ida_remove
```
```
In lib/radix-tree.c (ffffffff818f27dc)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:radix_tree_join
  - lib/radix-tree.c:radix_tree_extend
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
In arch/x86/events/intel/core.c (ffffffff8100c072)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/kernel/ioport.c (0)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810492de)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:__mce_disable_bank
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff8104c4c7)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_discover
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_discover
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff8198ba33)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
```
```
In kernel/workqueue.c (ffffffff810a466f)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/rt.c (ffffffff810cb454)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/sched/debug.c (ffffffff810d82d1)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/irq/irqdesc.c (0)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
```
```
In kernel/time/timer.c (ffffffff8110682f)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/smp.c (ffffffff8111f509)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/bpf/devmap.c (ffffffff811af197)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:__dev_map_flush
```
```
In kernel/bpf/cpumap.c (ffffffff811b03ec)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_flush
```
```
In kernel/memremap.c (ffffffff811c92bd)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
```
```
In mm/filemap.c (ffffffff811cc8a3)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/page_alloc.c (ffffffff826d72ba)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/page_alloc.c:__free_pages_bootmem
```
```
In mm/swap.c (ffffffff811e0a60)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff811e6273)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:shrink_page_list
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
```
```
In mm/swap_state.c (ffffffff812258e0)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff812322ad)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/slub.c (ffffffff81245494)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff8124dab6)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:putback_movable_page
```
```
In mm/huge_memory.c (ffffffff81254c48)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/cma.c (0)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
```
```
In fs/dcache.c (ffffffff8128e702)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:___d_drop
```
```
In fs/file.c (ffffffff81295a26)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
```
```
In fs/mbcache.c (ffffffff812de2bb)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/ext4/mballoc.c (ffffffff813332fb)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_clear_bits
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dev.c (ffffffff81392d8f)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_force_forget
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
```
```
In fs/fuse/file.c (ffffffff81399157)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
```
```
In fs/fuse/inode.c (ffffffff8139efab)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_put_super
```
```
In block/blk-core.c (ffffffff8144ec0c)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_bypass_end
  - block/blk-core.c:blk_clear_preempt_only
  - block/blk-core.c:blk_start_queue
  - block/blk-core.c:blk_start_queue_async
```
```
In block/blk-tag.c (ffffffff814523d9)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_free_tags
  - block/blk-tag.c:__blk_queue_free_tags
```
```
In block/blk-sysfs.c (ffffffff81453ff0)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:queue_wc_store
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_store_iostats
  - block/blk-sysfs.c:queue_store_random
  - block/blk-sysfs.c:queue_store_nonrot
```
```
In block/blk-settings.c (ffffffff814559a5)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-settings.c:blk_queue_write_cache
```
```
In block/blk-mq.c (ffffffff8145b3f9)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_unquiesce_queue
```
```
In block/blk-cgroup.c (ffffffff81474089)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
```
```
In lib/iommu-common.c (0)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff814dc33d)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/pwm/core.c (0)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff8162a7db)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:domain_id_free
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
```
```
In drivers/block/loop.c (ffffffff8166e968)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_update_dio
```
```
In drivers/block/xen-blkfront.c (ffffffff81674e11)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
```
```
In drivers/scsi/sd.c (ffffffff816c4c62)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_config_discard
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
```
```
In drivers/input/input.c (ffffffff8177e0e4)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_keycode
  - drivers/input/input.c:input_default_setkeycode
```
```
In drivers/input/ff-core.c (ffffffff81780173)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_destroy
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8178509b)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/md/md.c (ffffffff817b5179)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
```
```
In drivers/md/dm-table.c (ffffffff817c4844)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
```
In net/socket.c (ffffffff8182539c)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff8182db04)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/netlink/af_netlink.c (ffffffff818857df)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8189f4e6)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff818a6826)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff818a7453)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (ffffffff818b4671)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
```
In net/unix/garbage.c (ffffffff81906ab5)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In lib/idr.c (ffffffff81973116)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - lib/idr.c:ida_remove
```
```
In lib/radix-tree.c (ffffffff81978c7c)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:radix_tree_join
  - lib/radix-tree.c:radix_tree_extend
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
In arch/x86/events/intel/core.c (ffffffff8100c7ab)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/kernel/ioport.c (0)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104bb3e)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:__mce_disable_bank
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff8104f1d2)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_discover
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_discover
```
```
In arch/x86/kernel/kvm.c (ffffffff8106ca4b)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff819e8327)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/workqueue.c (ffffffff810aac2f)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/rt.c (ffffffff810d2b35)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/sched/debug.c (ffffffff810df74e)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/irq/irqdesc.c (0)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
```
```
In kernel/time/timer.c (ffffffff811131ac)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/smp.c (ffffffff8112c83c)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/bpf/devmap.c (ffffffff811c9a95)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:__dev_map_flush
```
```
In kernel/bpf/cpumap.c (ffffffff811caeec)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_flush
```
```
In kernel/memremap.c (ffffffff811e93dd)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
```
```
In mm/filemap.c (ffffffff811ed684)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/page_alloc.c (ffffffff827016f5)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/page_alloc.c:__free_pages_bootmem
```
```
In mm/swap.c (ffffffff8120231c)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff812077e3)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:shrink_page_list
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
```
```
In mm/swap_state.c (ffffffff81247e82)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff812552fe)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/slub.c (ffffffff81269593)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff812713bb)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:putback_movable_page
```
```
In mm/cma.c (0)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
```
```
In fs/dcache.c (ffffffff812b4993)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/file.c (ffffffff812bbcb6)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
```
```
In fs/mbcache.c (ffffffff8130a4fc)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/ext4/mballoc.c (ffffffff8136148f)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_clear_bits
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dev.c (ffffffff813c29f1)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_force_forget
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
```
```
In fs/fuse/file.c (ffffffff813c7ea7)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
```
```
In fs/fuse/inode.c (ffffffff813cda61)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_sb_destroy
```
```
In block/blk-core.c (ffffffff8148171a)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_bypass_end
  - block/blk-core.c:blk_start_queue
  - block/blk-core.c:blk_start_queue_async
  - block/blk-core.c:blk_queue_flag_test_and_clear
  - block/blk-core.c:blk_queue_flag_clear
```
```
In block/blk-tag.c (ffffffff8148587d)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_free_tags
  - block/blk-tag.c:__blk_queue_free_tags
```
```
In block/blk-sysfs.c (ffffffff81486885)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_nomerges_store
```
```
In block/blk-settings.c (ffffffff81488c72)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-settings.c:blk_queue_write_cache
```
```
In block/blk-cgroup.c (ffffffff814a8529)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff8150a714)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/pwm/core.c (0)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff816687da)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:domain_id_free
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
```
```
In drivers/input/input.c (ffffffff817bf205)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_keycode
  - drivers/input/input.c:input_default_setkeycode
```
```
In drivers/input/ff-core.c (ffffffff817c1273)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_destroy
```
```
In drivers/input/keyboard/atkbd.c (ffffffff817c61fc)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In net/socket.c (ffffffff8186f34d)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81877eaf)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/netlink/af_netlink.c (ffffffff818d9196)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f3f19)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff818fb917)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff819002fe)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (ffffffff81909c91)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
```
In net/unix/garbage.c (ffffffff8195daa7)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In lib/idr.c (ffffffff819cf67f)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - lib/idr.c:ida_remove
```
```
In lib/radix-tree.c (ffffffff819d5423)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:radix_tree_join
  - lib/radix-tree.c:radix_tree_extend
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
In arch/x86/events/intel/core.c (ffffffff8100c7f4)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/kernel/ioport.c (0)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104921e)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__mce_disable_bank
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8104c8a2)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105d6c0)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/kvm.c (ffffffff810728fb)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81a23917)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/workqueue.c (ffffffff810b3caf)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/rt.c (ffffffff810dc4a5)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/sched/debug.c (ffffffff810e9ece)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/irq/irqdesc.c (0)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
```
```
In kernel/time/timer.c (ffffffff8111d4bc)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/smp.c (ffffffff8113810c)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/bpf/devmap.c (ffffffff811dd395)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:__dev_map_flush
```
```
In kernel/bpf/cpumap.c (ffffffff811de7fc)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_flush
```
```
In kernel/memremap.c (ffffffff811f9fbd)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
```
```
In mm/filemap.c (ffffffff811fec32)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/page_alloc.c (ffffffff828b8d32)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:memblock_free_pages
  - mm/page_alloc.c:memblock_free_pages
```
```
In mm/swap.c (ffffffff81214c9e)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8121a363)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:putback_inactive_pages
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
```
```
In mm/swap_state.c (ffffffff8125c464)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff812696e6)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/slub.c (ffffffff8127c66b)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff812859a5)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:putback_movable_page
```
```
In mm/cma.c (0)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
```
```
In fs/dcache.c (ffffffff812c9c13)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/file.c (ffffffff812d0f36)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
```
```
In fs/mbcache.c (ffffffff8131fcdc)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/ext4/mballoc.c (ffffffff8137973f)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_clear_bits
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dev.c (ffffffff813dc4e9)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_force_forget
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
```
```
In fs/fuse/file.c (ffffffff813e10fb)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
```
```
In fs/fuse/inode.c (ffffffff813e6e51)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_sb_destroy
```
```
In block/blk-cgroup.c (ffffffff814c23c7)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff8151fb64)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/pwm/core.c (0)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff8168710a)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:domain_id_free
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
```
```
In drivers/net/phy/phy.c (ffffffff81758599)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (ffffffff81759597)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy_device.c (ffffffff8175c633)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_remove_link_mode
  - drivers/net/phy/phy_device.c:phy_set_max_speed
  - drivers/net/phy/phy_device.c:phy_set_max_speed
  - drivers/net/phy/phy_device.c:phy_set_max_speed
  - drivers/net/phy/phy_device.c:phy_set_max_speed
```
```
In drivers/net/tun.c (ffffffff8175fed4)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
```
```
In drivers/input/input.c (ffffffff817e6665)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_keycode
  - drivers/input/input.c:input_default_setkeycode
```
```
In drivers/input/ff-core.c (ffffffff817e8763)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_destroy
```
```
In drivers/input/keyboard/atkbd.c (ffffffff817ed7cc)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In net/socket.c (ffffffff8188f80d)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff8189838f)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/dev.c (ffffffff818b7500)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
```
```
In net/netlink/af_netlink.c (ffffffff81905916)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81921a39)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff81929877)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff8192a70e)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (ffffffff81937f3f)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
```
In net/unix/garbage.c (ffffffff819925e7)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In lib/idr.c (ffffffff81a0888e)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - lib/idr.c:ida_free
```
```
In lib/radix-tree.c (ffffffff81a0d2d5)
Location: arch/x86/include/asm/bitops.h:138
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (0)
Location: arch/x86/include/asm/bitops.h:138
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
In arch/x86/events/core.c (ffffffff81006628)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_stop
```
```
In arch/x86/events/intel/core.c (ffffffff8100d03e)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104c13e)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__mce_disable_bank
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8104f47c)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81060a2c)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/smp.c (ffffffff81062b94)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:native_send_call_func_ipi
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106c9f8)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106d0f2)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
```
```
In arch/x86/kernel/kvm.c (ffffffff81076428)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81a93c43)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/workqueue.c (ffffffff810b9bbf)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/fair.c (ffffffff810e0b79)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/rt.c (ffffffff810e344e)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/sched/debug.c (ffffffff810f0cdb)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/isolation.c (ffffffff828c55b9)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In kernel/time/timer.c (ffffffff81128178)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/smp.c (ffffffff811432bf)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In mm/filemap.c (ffffffff81215f37)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffff81223dfb)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8122c6f9)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/percpu.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In mm/page_alloc.c (ffffffff828d5df5)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/swap_state.c (ffffffff8127764f)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff81284865)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/slub.c (ffffffff81295903)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
```
```
In mm/migrate.c (ffffffff812a0078)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:putback_movable_page
```
```
In mm/cma.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In mm/memremap.c (ffffffff812c2410)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In fs/file.c (ffffffff812edf45)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
```
```
In fs/ext4/mballoc.c (ffffffff813a3259)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_clear_bits
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dev.c (ffffffff81407394)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_force_forget
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
```
```
In fs/fuse/file.c (ffffffff8140cd04)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In fs/fuse/inode.c (ffffffff81412e7f)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_sb_destroy
```
```
In block/blk-cgroup.c (ffffffff814f0f03)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff8154de21)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/pwm/core.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In drivers/acpi/hmat/hmat.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8169566e)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff816be8b3)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:domain_id_free
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In drivers/net/phy/phy.c (ffffffff81794fa6)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (ffffffff81796035)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy-core.c (ffffffff817968fb)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_set_max_speed
```
```
In drivers/net/phy/phy_device.c (ffffffff81799625)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_remove_link_mode
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
```
```
In drivers/net/tun.c (ffffffff8179d65c)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In drivers/input/input.c (ffffffff8182729d)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_keycode
  - drivers/input/input.c:input_default_setkeycode
```
```
In drivers/input/ff-core.c (ffffffff81829273)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_destroy
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8182e23c)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In net/socket.c (ffffffff818d9869)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff818e2920)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/dev.c (ffffffff81903337)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
```
```
In net/netlink/af_netlink.c (ffffffff81966b55)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819843ef)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff8198c96d)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff8198d97e)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (ffffffff819996ba)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/unix/garbage.c (ffffffff819fdbd5)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (ffffffff819fedba)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In lib/idr.c (ffffffff81a7823c)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - lib/idr.c:ida_free
```
```
In lib/radix-tree.c (ffffffff81a7cc02)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
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
In arch/x86/events/core.c (ffffffff810066b8)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_stop
```
```
In arch/x86/events/intel/core.c (ffffffff8100d4ae)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104cafe)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__mce_disable_bank
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8104fdfc)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810612dc)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106e198)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106e651)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
```
```
In arch/x86/kernel/kvm.c (ffffffff81077438)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81acb523)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/workqueue.c (ffffffff810c003f)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/fair.c (ffffffff810eb209)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/rt.c (ffffffff810edddf)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:alloc_rt_sched_group
```
```
In kernel/sched/debug.c (ffffffff810fc98b)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/isolation.c (ffffffff828cdc22)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In kernel/time/timer.c (ffffffff81134118)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/smp.c (ffffffff8114edff)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In mm/filemap.c (ffffffff81223837)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffff81231b8b)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8123a919)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/percpu.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In mm/page_alloc.c (ffffffff828de269)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/swap_state.c (ffffffff81287136)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff81294405)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/slub.c (ffffffff812a56e3)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
```
```
In mm/migrate.c (ffffffff812b1418)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:putback_movable_page
```
```
In mm/cma.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In mm/memremap.c (ffffffff812d4340)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In fs/file.c (ffffffff812ffa05)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
```
```
In fs/ext4/mballoc.c (ffffffff813bc0b9)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_clear_bits
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dev.c (ffffffff8142219c)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
```
```
In block/blk-cgroup.c (ffffffff8150a100)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff8156f021)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/pwm/core.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In drivers/acpi/hmat/hmat.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff816b81fe)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff816e1c83)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:domain_id_free
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In drivers/net/phy/phy.c (ffffffff817b8b15)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (ffffffff817b99f5)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy-core.c (ffffffff817badf9)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_set_max_speed
```
```
In drivers/net/phy/phy_device.c (ffffffff817bd145)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_remove_link_mode
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
```
```
In drivers/net/tun.c (ffffffff817c10fc)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In drivers/input/input.c (ffffffff818587cd)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_keycode
  - drivers/input/input.c:input_default_setkeycode
```
```
In drivers/input/ff-core.c (ffffffff8185ac03)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_destroy
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8185fb6c)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In net/socket.c (ffffffff8190b849)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81914af0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/dev.c (ffffffff819360e7)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
```
```
In net/netlink/af_netlink.c (ffffffff8199d5d5)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bab9f)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff819c32dd)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff819c452e)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (ffffffff819d00ba)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/unix/garbage.c (ffffffff81a347c5)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (ffffffff81a359ba)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a90be9)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In lib/idr.c (ffffffff81aaf4fc)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - lib/idr.c:ida_free
```
```
In lib/radix-tree.c (ffffffff81ab3f32)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
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
In arch/x86/events/core.c (ffffffff81007818)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_stop
```
```
In arch/x86/events/intel/core.c (ffffffff8100e72f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105171e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__mce_disable_bank
  - arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff810544fc)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81066e7b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81075818)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81075b11)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
```
```
In arch/x86/kernel/kvm.c (ffffffff8107e788)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81bc3a29)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/workqueue.c (ffffffff810c774f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/fair.c (ffffffff810f5043)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/rt.c (ffffffff810f760b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - kernel/sched/rt.c:__dequeue_rt_entity
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/sched/debug.c (ffffffff811070df)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/isolation.c (ffffffff82ceefe6)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In kernel/time/timer.c (ffffffff81144299)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/smp.c (ffffffff8115f76f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In mm/filemap.c (ffffffff81250f07)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffff8125e74a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff81265394)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In mm/percpu.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In mm/page_alloc.c (ffffffff812b46a8)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_one_page
```
```
In mm/hugetlb.c (ffffffff812c77f5)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:destroy_compound_gigantic_page
```
```
In mm/slub.c (ffffffff812da2fd)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
```
```
In mm/migrate.c (ffffffff812e66d5)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:putback_movable_pages
```
```
In mm/memremap.c (ffffffff8130aa69)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - mm/memremap.c:free_devmap_managed_page
  - mm/memremap.c:free_devmap_managed_page
```
```
In fs/file.c (ffffffff81338b3b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
```
```
In fs/ext4/mballoc.c (ffffffff81407cf1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_clear_bits
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dev.c (ffffffff8146e4bc)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In block/blk-cgroup.c (ffffffff8156ae64)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In lib/bitmap.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In lib/idr.c (ffffffff815e93a8)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - lib/idr.c:ida_free
```
```
In lib/radix-tree.c (ffffffff815edf32)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff816134e1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/pwm/core.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In drivers/acpi/numa/hmat.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8176c2e0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In drivers/iommu/amd/iommu.c (ffffffff81799db7)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:protection_domain_free
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff8183722d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
```
```
In drivers/net/phy/phy.c (ffffffff8187fc5e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
```
```
In drivers/net/phy/phy-c45.c (ffffffff81880ef5)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy-core.c (ffffffff818826a5)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_set_max_speed
```
```
In drivers/net/phy/phy_device.c (ffffffff81884f45)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_remove_link_mode
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
```
```
In drivers/net/phy/linkmode.c (ffffffff81886045)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_set_pause
  - drivers/net/phy/linkmode.c:linkmode_set_pause
```
```
In drivers/net/phy/bcm84881.c (ffffffff818890f6)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/net/phy/bcm84881.c:bcm84881_get_features
  - drivers/net/phy/bcm84881.c:bcm84881_get_features
```
```
In drivers/net/tun.c (ffffffff8188ad0c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In drivers/input/input.c (ffffffff81929ae7)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_keycode
  - drivers/input/input.c:input_default_setkeycode
```
```
In drivers/input/ff-core.c (ffffffff8192d623)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_destroy
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81933c74)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In net/socket.c (ffffffff819dda39)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff819e7068)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/dev.c (ffffffff81a0ae6f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
```
```
In net/core/filter.c (ffffffff81a31a20)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/netlink/af_netlink.c (ffffffff81a7b5b4)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_clear_multicast_users
  - net/netlink/af_netlink.c:netlink_setsockopt
```
```
In net/ethtool/bitset.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa5434)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff81aae988)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff81ab326e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (ffffffff81abd106)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/unix/garbage.c (ffffffff81b295e9)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (ffffffff81b2a9a9)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_net_init
```
```
In net/packet/af_packet.c (ffffffff81b8c06a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/mptcp/protocol.c (ffffffff81bad81d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sk_clone
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
In arch/x86/events/core.c (ffffffff810068d7)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_stop
```
```
In arch/x86/events/intel/core.c (ffffffff8100db40)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_fixed
  - arch/x86/events/intel/core.c:intel_pmu_disable_fixed
  - arch/x86/events/intel/core.c:intel_pmu_disable_fixed
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810509de)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__mce_disable_bank
  - arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8105343c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810650bb)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81075e5b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81076141)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
```
```
In arch/x86/kernel/kvm.c (ffffffff8107e3b8)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81c3c95b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/workqueue.c (ffffffff810c272d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/fair.c (ffffffff810f30d5)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/rt.c (ffffffff810f580b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - kernel/sched/rt.c:__dequeue_rt_entity
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/sched/debug.c (ffffffff811058ef)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/isolation.c (ffffffff82fdb6fd)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In kernel/time/timer.c (ffffffff8114082f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/smp.c (ffffffff8115b70f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/seccomp.c (ffffffff811a381c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In mm/filemap.c (ffffffff8125b247)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffff81268999)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff81270059)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/percpu.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In mm/page_alloc.c (ffffffff812c03fe)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_one_page
```
```
In mm/hugetlb.c (ffffffff812d3365)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/slub.c (ffffffff812e6cca)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
```
```
In mm/migrate.c (ffffffff812f1b84)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:putback_movable_pages
```
```
In mm/memremap.c (ffffffff81316937)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - mm/memremap.c:free_devmap_managed_page
```
```
In fs/file.c (ffffffff813445bb)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd_get_file
  - fs/file.c:pick_file
  - fs/file.c:pick_file
  - fs/file.c:put_unused_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:alloc_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
```
```
In fs/ext4/mballoc.c (ffffffff8141a741)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_clear_bits
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dev.c (ffffffff81488c2f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_put_request
```
```
In block/blk-cgroup.c (ffffffff81585814)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In lib/bitmap.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In lib/idr.c (ffffffff8160e458)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - lib/idr.c:ida_free
```
```
In lib/radix-tree.c (ffffffff81612662)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff816383b8)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/pwm/core.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In drivers/acpi/numa/hmat.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81786e00)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In drivers/iommu/amd/iommu.c (ffffffff817a84e7)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:protection_domain_free
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff818468bf)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
```
In drivers/net/phy/phy.c (ffffffff8188e50e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
```
```
In drivers/net/phy/phy-c45.c (ffffffff8188f625)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy-core.c (ffffffff81890dd5)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_set_max_speed
```
```
In drivers/net/phy/phy_device.c (ffffffff818939c5)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_remove_link_mode
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
```
```
In drivers/net/phy/linkmode.c (ffffffff818944a5)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_set_pause
  - drivers/net/phy/linkmode.c:linkmode_set_pause
```
```
In drivers/net/phy/bcm84881.c (ffffffff81897366)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/net/phy/bcm84881.c:bcm84881_get_features
  - drivers/net/phy/bcm84881.c:bcm84881_get_features
```
```
In drivers/net/tun.c (ffffffff818989b2)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp
  - drivers/net/tun.c:tun_xdp
```
```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In drivers/input/input.c (ffffffff81931057)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_keycode
  - drivers/input/input.c:input_default_setkeycode
```
```
In drivers/input/ff-core.c (ffffffff819349f3)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_destroy
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8193aec4)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In net/socket.c (ffffffff819dd429)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff819e689e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/dev.c (ffffffff81a0c0bb)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
```
```
In net/core/filter.c (ffffffff81a2ae3c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_setsockopt
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/netlink/af_netlink.c (ffffffff81a84434)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_clear_multicast_users
  - net/netlink/af_netlink.c:netlink_setsockopt
```
```
In net/ethtool/bitset.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aafa34)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff81ab8bc8)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81ac885b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/unix/garbage.c (ffffffff81b37f19)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (ffffffff81b39339)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_net_init
```
```
In net/packet/af_packet.c (ffffffff81b9b4c7)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/mptcp/protocol.c (ffffffff81bc07d6)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sk_clone
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
In arch/x86/events/core.c (ffffffff81008bfd)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_clear_dirty_counters
  - arch/x86/events/core.c:x86_pmu_stop
```
```
In arch/x86/events/intel/core.c (ffffffff8100fecc)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105238e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__mce_disable_bank
  - arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81054d0c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106572f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810768db)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81076bd1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
```
```
In arch/x86/kernel/kvm.c (ffffffff8107f4c8)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_multi
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81c2ee37)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/workqueue.c (ffffffff810c442d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/fair.c (ffffffff810f52a5)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/rt.c (ffffffff810f7975)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/sched/debug.c (ffffffff81107990)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - kernel/sched/debug.c:update_sched_domain_debugfs
```
```
In kernel/sched/isolation.c (ffffffff831e6457)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In kernel/time/timer.c (ffffffff811419af)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/smp.c (ffffffff8115c7f5)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/seccomp.c (ffffffff811a443c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In mm/filemap.c (ffffffff8125eed7)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffff8126e830)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff812750cb)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/percpu.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In mm/page_alloc.c (ffffffff812c5b78)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_one_page
```
```
In mm/hugetlb.c (ffffffff812da0a5)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/slub.c (ffffffff812ee4ba)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
```
```
In mm/migrate.c (ffffffff812f7e99)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:putback_movable_pages
```
```
In mm/memremap.c (ffffffff8131cb87)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - mm/memremap.c:free_devmap_managed_page
```
```
In fs/file.c (ffffffff8134a95b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd_get_file
  - fs/file.c:pick_file
  - fs/file.c:pick_file
  - fs/file.c:put_unused_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:alloc_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
```
```
In fs/ext4/mballoc.c (ffffffff81420bf3)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_clear_bits
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dev.c (ffffffff8148e52f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_put_request
```
```
In block/blk-cgroup.c (ffffffff8158c7c7)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In lib/bitmap.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In lib/idr.c (ffffffff815f1ba8)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - lib/idr.c:ida_free
```
```
In lib/radix-tree.c (ffffffff815f5d42)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff8161befb)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/pwm/core.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In drivers/acpi/numa/hmat.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8176a760)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In drivers/iommu/amd/iommu.c (ffffffff8178919e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:protection_domain_free
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81829acf)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
```
In drivers/net/phy/phy.c (ffffffff81870d71)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
```
```
In drivers/net/phy/phy-c45.c (ffffffff81871f06)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy-core.c (ffffffff818736b5)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_set_max_speed
```
```
In drivers/net/phy/phy_device.c (ffffffff8187659d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_remove_link_mode
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
```
```
In drivers/net/phy/linkmode.c (ffffffff81876da5)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_set_pause
  - drivers/net/phy/linkmode.c:linkmode_set_pause
```
```
In drivers/net/phy/bcm84881.c (ffffffff81879b7d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/net/phy/bcm84881.c:bcm84881_get_features
  - drivers/net/phy/bcm84881.c:bcm84881_get_features
```
```
In drivers/net/tun.c (ffffffff8187b0f5)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp
  - drivers/net/tun.c:tun_xdp
```
```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In drivers/input/input.c (ffffffff819142d7)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_keycode
  - drivers/input/input.c:input_default_setkeycode
```
```
In drivers/input/ff-core.c (ffffffff81917d33)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_destroy
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8191dfc5)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In net/socket.c (ffffffff819c367c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff819cc6a6)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/dev.c (ffffffff819f2270)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
```
```
In net/core/filter.c (ffffffff81a12051)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_setsockopt
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/netlink/af_netlink.c (ffffffff81a6d524)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_clear_multicast_users
  - net/netlink/af_netlink.c:netlink_setsockopt
```
```
In net/ethtool/bitset.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9ad44)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff81aa3e78)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81ab3590)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/unix/garbage.c (ffffffff81b25bb1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (ffffffff81b26f1a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_net_init
```
```
In net/packet/af_packet.c (ffffffff81b8ae95)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/mptcp/protocol.c (ffffffff81bb058a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sk_clone
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb9bf3)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
```
```
In net/mptcp/sockopt.c (ffffffff81bbc0ea)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
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
In arch/x86/events/core.c (ffffffff81009a7a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_clear_dirty_counters
  - arch/x86/events/core.c:x86_pmu_stop
```
```
In arch/x86/events/intel/core.c (ffffffff8101089a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105a80e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__mce_disable_bank
  - arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8105d65c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106f82d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8108404b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff810843b1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
```
```
In arch/x86/kernel/kvm.c (ffffffff8108e23b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_multi
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81d4d538)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/workqueue.c (ffffffff810d703a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - kernel/workqueue.c:pwq_activate_inactive_work
```
```
In kernel/sched/fair.c (ffffffff8110edb4)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/rt.c (ffffffff81111fc4)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/sched/debug.c (ffffffff81125a6b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - kernel/sched/debug.c:update_sched_domain_debugfs
```
```
In kernel/sched/isolation.c (ffffffff832ca553)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In kernel/time/timer.c (ffffffff81164eec)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/smp.c (ffffffff8118194b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/seccomp.c (ffffffff811cdc0f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff8126e045)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In mm/filemap.c (ffffffff8129c2e7)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffff812ab841)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff812b23a3)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/percpu.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In mm/page_alloc.c (ffffffff8130a2d1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_one_page
```
```
In mm/hugetlb.c (ffffffff81320e62)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
```
```
In mm/slub.c (ffffffff813366e9)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
```
```
In mm/migrate.c (ffffffff81342506)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:putback_movable_pages
```
```
In mm/memremap.c (ffffffff81369ed1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - mm/memremap.c:free_devmap_managed_page
```
```
In fs/file.c (ffffffff8139870b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd_get_file
  - fs/file.c:pick_file
  - fs/file.c:pick_file
  - fs/file.c:put_unused_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:alloc_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
```
```
In fs/ext4/mballoc.c (ffffffff81473ff7)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_clear_bits
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dev.c (ffffffff814e5f9f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_put_request
```
```
In block/blk-cgroup.c (ffffffff815f1dff)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In lib/bitmap.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In lib/idr.c (ffffffff8165ed28)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - lib/idr.c:ida_free
```
```
In lib/radix-tree.c (ffffffff8166320c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff8168b294)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/pwm/core.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In drivers/acpi/numa/hmat.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff817efa33)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In drivers/iommu/amd/iommu.c (ffffffff8181109a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_free
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b550f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
```
In drivers/net/phy/phy.c (ffffffff81900ff5)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
```
In drivers/net/phy/phy-c45.c (ffffffff81902506)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy-core.c (ffffffff81903f79)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_set_max_speed
```
```
In drivers/net/phy/phy_device.c (ffffffff819071ad)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_remove_link_mode
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
```
```
In drivers/net/phy/linkmode.c (ffffffff819079b5)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_set_pause
  - drivers/net/phy/linkmode.c:linkmode_set_pause
```
```
In drivers/net/phy/bcm84881.c (ffffffff8190ac1d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/net/phy/bcm84881.c:bcm84881_get_features
  - drivers/net/phy/bcm84881.c:bcm84881_get_features
```
```
In drivers/net/tun.c (ffffffff8190c604)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp
  - drivers/net/tun.c:tun_xdp
```
```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In drivers/input/input.c (ffffffff819b63d2)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_keycode
  - drivers/input/input.c:input_default_setkeycode
```
```
In drivers/input/ff-core.c (ffffffff819b9fa3)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_destroy
```
```
In drivers/input/keyboard/atkbd.c (ffffffff819c1567)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In net/socket.c (ffffffff81a72f0c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81a7bd25)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_set_timestamping
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/dev.c (ffffffff81aa4140)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
```
```
In net/core/filter.c (ffffffff81acd37a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_setsockopt
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/netlink/af_netlink.c (ffffffff81b26ba4)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_clear_multicast_users
  - net/netlink/af_netlink.c:netlink_setsockopt
```
```
In net/ethtool/bitset.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b561b4)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff81b6008d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81b703a2)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/unix/garbage.c (ffffffff81beb2cb)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (ffffffff81bec97c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_net_init
```
```
In net/packet/af_packet.c (ffffffff81c570d8)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/mptcp/protocol.c (ffffffff81c7e444)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sk_clone
```
```
In net/mptcp/pm_netlink.c (ffffffff81c89503)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
```
```
In net/mptcp/sockopt.c (ffffffff81c8bc8a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
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
In arch/x86/events/core.c (ffffffff81009178)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_clear_dirty_counters
  - arch/x86/events/core.c:x86_pmu_stop
```
```
In arch/x86/events/intel/core.c (ffffffff81011f35)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810671db)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__mce_disable_bank
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81069e9a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8107d0d4)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8109414b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81094561)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
```
```
In arch/x86/kernel/kvm.c (ffffffff8109ebfb)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_multi
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81f1d237)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/workqueue.c (ffffffff810f0c2d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - kernel/workqueue.c:pwq_activate_inactive_work
```
```
In kernel/sched/fair.c (ffffffff8112ad02)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/build_policy.c (ffffffff8112f162)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dequeue_rt_stack
  - kernel/sched/build_policy.c:init_rt_rq
```
```
In kernel/sched/build_utility.c (ffffffff8347d6f6)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:update_sched_domain_debugfs
```
```
In kernel/irq/irqdesc.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In kernel/time/timer.c (ffffffff81198ae6)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/smp.c (ffffffff811b7f99)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/seccomp.c (ffffffff8120195d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff812bceab)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In mm/filemap.c (ffffffff812f298b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - mm/filemap.c:filemap_add_folio
```
```
In mm/swap.c (ffffffff8130566c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8130d343)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/percpu.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In mm/page_alloc.c (ffffffff81372c3a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:split_free_page
  - mm/page_alloc.c:__free_one_page
```
```
In mm/hugetlb.c (ffffffff8138dbc8)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:__prep_compound_gigantic_page
  - mm/hugetlb.c:__prep_compound_gigantic_page
  - mm/hugetlb.c:__prep_compound_gigantic_page
  - mm/hugetlb.c:__prep_compound_gigantic_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:__destroy_compound_gigantic_page
```
```
In mm/slub.c (ffffffff813a8070)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
```
```
In mm/kfence/core.c (ffffffff8349276a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_init
```
```
In mm/memremap.c (ffffffff813e7c31)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - mm/memremap.c:free_zone_device_page
```
```
In fs/file.c (ffffffff8141ae71)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd_get_file
  - fs/file.c:alloc_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
```
```
In fs/ext4/mballoc.c (ffffffff814f606f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_clear_bits
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dev.c (ffffffff815743fb)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_put_request
```
```
In block/blk-cgroup.c (ffffffff816a307d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In io_uring/io_uring.c (ffffffff816d4b18)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_sqe_files_update
  - io_uring/io_uring.c:__io_sqe_files_unregister
  - io_uring/io_uring.c:io_fixed_fd_install
```
```
In lib/bitmap.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In lib/idr.c (ffffffff8177860b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - lib/idr.c:ida_free
```
```
In lib/radix-tree.c (ffffffff8177d3bc)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - lib/radix-tree.c:node_tag_clear
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/vsprintf.c (ffffffff81784abf)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
```
```
In lib/xarray.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff817a85fd)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff817aaeb3)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linehandle_ioctl
```
```
In drivers/pwm/core.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In drivers/acpi/numa/hmat.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff818c8516)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:get_free_entries
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8192f7c7)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_set
```
```
In drivers/iommu/amd/iommu.c (ffffffff81951446)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_free
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff819feb8b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
```
In drivers/net/phy/phy.c (ffffffff81a53874)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
```
In drivers/net/phy/phy-c45.c (ffffffff81a54312)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
```
```
In drivers/net/phy/phy-core.c (ffffffff81a56a04)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_set_max_speed
```
```
In drivers/net/phy/phy_device.c (ffffffff81a5a43d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_remove_link_mode
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
```
```
In drivers/net/phy/linkmode.c (ffffffff81a5aa49)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_set_pause
  - drivers/net/phy/linkmode.c:linkmode_set_pause
```
```
In drivers/net/phy/bcm84881.c (ffffffff81a5e80a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
  - drivers/net/phy/bcm84881.c:bcm84881_get_features
  - drivers/net/phy/bcm84881.c:bcm84881_get_features
```
```
In drivers/net/tun.c (ffffffff81a601f8)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp
  - drivers/net/tun.c:tun_xdp
```
```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In drivers/input/input.c (ffffffff81b15bfd)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_keycode
  - drivers/input/input.c:input_default_setkeycode
```
```
In drivers/input/ff-core.c (ffffffff81b19fa3)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_destroy
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81b1fdaa)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In net/socket.c (ffffffff81be5799)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81befb80)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_set_timestamping
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/dev.c (ffffffff81c17eda)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/core/filter.c (ffffffff81c4ac8c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_setsockopt
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/gro.c (ffffffff81c543a3)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:napi_gro_flush
```
```
In net/netlink/af_netlink.c (ffffffff81caf8cb)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_clear_multicast_users
```
```
In net/ethtool/bitset.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce42ce)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff81ceea1d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81cff929)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/unix/garbage.c (ffffffff81d83483)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (ffffffff81d84e33)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_net_init
```
```
In net/packet/af_packet.c (ffffffff81df64bc)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/mptcp/protocol.c (ffffffff81e23855)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sk_clone
```
```
In net/mptcp/pm_netlink.c (ffffffff81e31de0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
```
```
In net/mptcp/sockopt.c (ffffffff81e3337e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:40
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
```
</details>
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/context.c (0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In kernel/workqueue.c (ffff80001011d720)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/fair.c (ffff80001014b358)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/rt.c (ffff80001014ddb8)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - kernel/sched/rt.c:__delist_rt_entity
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/sched/debug.c (ffff800010161d54)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/isolation.c (ffff800011445520)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In kernel/time/timer.c (ffff80001019eba4)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/smp.c (ffff8000101bd340)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In mm/filemap.c (ffff8000102b123c)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffff8000102c1858)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffff8000102cb868)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/percpu.c (0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In mm/page_alloc.c (ffff800011456f28)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/swap_state.c (ffff800010321c5c)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffff800010332cb8)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/slub.c (ffff800010346538)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
```
```
In mm/migrate.c (ffff8000103517c4)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:putback_movable_page
```
```
In mm/cma.c (0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In fs/file.c (ffff8000103b1070)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
```
```
In fs/ext4/mballoc.c (ffff800010492d18)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_clear_bits
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dev.c (ffff800010504e70)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
```
```
In block/blk-cgroup.c (ffff80001060cf58)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In drivers/irqchip/irq-mvebu-gicp.c (ffff800010678e84)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-gicp.c:gicp_irq_domain_free
  - drivers/irqchip/irq-mvebu-gicp.c:gicp_irq_domain_alloc
```
```
In drivers/irqchip/irq-mvebu-odmi.c (ffff8000106799f0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-odmi.c:odmi_irq_domain_free
  - drivers/irqchip/irq-mvebu-odmi.c:odmi_irq_domain_alloc
```
```
In drivers/irqchip/irq-ls-scfg-msi.c (ffff80001067b44c)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_probe
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_domain_irq_free
```
```
In drivers/gpio/gpiolib.c (ffff8000106c4f14)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
```
```
In drivers/gpio/gpiolib-of.c (0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In drivers/pwm/core.c (0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In drivers/pci/controller/pci-aardvark.c (0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In drivers/pci/controller/pci-xgene-msi.c (0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In drivers/pci/controller/pcie-iproc-msi.c (0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In drivers/pci/controller/pcie-altera-msi.c (ffff800010728250)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera-msi.c:altera_irq_domain_free
```
```
In drivers/pci/controller/pcie-mediatek.c (ffff80001072a24c)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_irq_domain_free
```
```
In drivers/pci/controller/pcie-mobiveil.c (ffff80001072bc74)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_irq_msi_domain_free
```
```
In drivers/acpi/hmat/hmat.c (0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In drivers/net/phy/phy.c (ffff8000109d14b0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (ffff8000109d2420)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy-core.c (ffff8000109d3938)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:of_set_phy_supported
  - drivers/net/phy/phy-core.c:phy_set_max_speed
```
```
In drivers/net/phy/phy_device.c (ffff8000109d6448)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_remove_link_mode
  - drivers/net/phy/phy_device.c:genphy_read_abilities
```
```
In drivers/net/tun.c (0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In drivers/input/input.c (ffff800010a98e44)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_keycode
  - drivers/input/input.c:input_default_setkeycode
```
```
In drivers/input/ff-core.c (ffff800010a9aab8)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_destroy
```
```
In drivers/input/keyboard/atkbd.c (ffff800010aa1f50)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In net/socket.c (ffff800010ba0df0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffff800010bad864)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/dev.c (ffff800010bd472c)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__napi_gro_flush_chain
```
```
In net/netlink/af_netlink.c (0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6c744)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffff800010c75fe0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffff800010c76f54)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (ffff800010c8271c)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/unix/garbage.c (ffff800010cf4e1c)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (ffff800010cf5cb8)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In net/packet/af_packet.c (ffff800010d5e2ac)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In lib/idr.c (ffff800010d893d4)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - lib/idr.c:ida_free
```
```
In lib/radix-tree.c (ffff800010d8e2b0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (0)
Location: include/asm-generic/bitops/non-atomic.h:24
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
In arch/arm/mm/dma-mapping.c (0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In arch/arm/mm/context.c (0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: False
```
```
In kernel/workqueue.c (c03717fc)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/fair.c (c0399060)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/rt.c (c039cb60)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - kernel/sched/rt.c:__delist_rt_entity
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/sched/debug.c (c03ae548)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/isolation.c (c151f640)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In kernel/time/timer.c (c03e74f4)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/smp.c (c0405518)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In mm/filemap.c (c04ddb10)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (c04ecbac)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (c04f56fc)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/percpu.c (0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In mm/page_alloc.c (c1531888)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/swap_state.c (c053a354)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/slub.c (c054b130)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
```
```
In mm/migrate.c (c0552f74)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:putback_movable_page
```
```
In mm/cma.c (0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In fs/file.c (c0590b40)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
```
```
In fs/ext4/mballoc.c (c0654048)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_clear_bits
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dev.c (c06bf75c)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_retrieve
```
```
In block/blk-cgroup.c (c07b70bc)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In drivers/irqchip/irq-alpine-msi.c (0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In drivers/irqchip/irq-armada-370-xp.c (0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In drivers/gpio/gpiolib.c (c086301c)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/gpio/gpiolib-of.c (0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In drivers/pwm/core.c (0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In drivers/pci/controller/pcie-altera-msi.c (c08b2df8)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera-msi.c:altera_irq_domain_free
```
```
In drivers/pci/controller/pcie-mediatek.c (c08b506c)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_irq_domain_free
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (c09a46c8)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In drivers/mtd/nand/raw/nand_macronix.c (c0aa7ad0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In drivers/net/phy/phy.c (c0ab9270)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (c0aba574)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy-core.c (c0abb794)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:of_set_phy_supported
  - drivers/net/phy/phy-core.c:phy_set_max_speed
```
```
In drivers/net/phy/phy_device.c (c0abdd74)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:phy_remove_link_mode
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
```
```
In drivers/net/tun.c (c0ac2834)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In drivers/input/input.c (c0b7a614)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_keycode
  - drivers/input/input.c:input_default_setkeycode
```
```
In drivers/input/ff-core.c (c0b7cac0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_destroy
```
```
In drivers/input/keyboard/atkbd.c (c0b81f4c)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In net/socket.c (c0cc30f4)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (c0ccb3f0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/dev.c (c0ceed0c)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__napi_gro_flush_chain
```
```
In net/netlink/af_netlink.c (c0d5b364)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
```
```
In net/ipv4/inet_connection_sock.c (c0d7b66c)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (c0d846c8)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (c0d8549c)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (c0d91dcc)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/unix/garbage.c (c0dfba00)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (c0dfc7f0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In net/packet/af_packet.c (c0e5cfa4)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In lib/idr.c (c0e83cc4)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - lib/idr.c:ida_free
```
```
In lib/radix-tree.c (c0e88af8)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (0)
Location: include/asm-generic/bitops/non-atomic.h:24
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
In arch/powerpc/kernel/iommu.c (c000000000052b08)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - arch/powerpc/kernel/iommu.c:iommu_init_table
```
```
In arch/powerpc/mm/slice.c (c0000000000a45e0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - arch/powerpc/mm/slice.c:slice_convert
```
```
In arch/powerpc/sysdev/msi_bitmap.c (0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In arch/powerpc/platforms/powernv/pci-ioda.c (0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In arch/powerpc/kvm/book3s_64_vio_hv.c (c000000000118f04)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_64_vio_hv.c:kvmppc_rm_h_put_tce_indirect
```
```
In arch/powerpc/kvm/book3s_hv_rm_mmu.c (c00000000011fbb4)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_h_clear_ref
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_do_h_enter
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:remove_revmap_chain
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_add_revmap_chain
```
```
In kernel/workqueue.c (c000000000165f34)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/fair.c (c00000000019d89c)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/rt.c (c0000000001a0918)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - kernel/sched/rt.c:__delist_rt_entity
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/sched/debug.c (c0000000001b7f18)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/isolation.c (c000000001369f84)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In kernel/time/timer.c (c0000000001fc55c)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/smp.c (c000000000223720)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In mm/filemap.c (c00000000036683c)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (c00000000037b610)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (c0000000003889d8)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/percpu.c (0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In mm/page_alloc.c (c000000001380158)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/swap_state.c (c0000000003f7480)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (c00000000040d7fc)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
```
```
In mm/slub.c (c000000000428564)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (c000000000437dac)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:putback_movable_page
```
```
In mm/cma.c (0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In mm/memremap.c (c00000000046d974)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In fs/dcache.c (c0000000004a119c)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:___d_drop
```
```
In fs/file.c (c0000000004acccc)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
```
```
In fs/mbcache.c (c0000000005345bc)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/ext4/mballoc.c (c0000000005bb408)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_clear_bits
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dev.c (c00000000064a0f0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
```
```
In block/blk-cgroup.c (c0000000007a9e88)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In drivers/gpio/gpiolib.c (c000000000841a90)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/gpio/gpiolib-of.c (0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In drivers/pwm/core.c (0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (c00000000093e630)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In drivers/net/phy/phy.c (c000000000a909e8)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (c000000000a923e0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy-core.c (c000000000a93e54)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:of_set_phy_supported
  - drivers/net/phy/phy-core.c:phy_set_max_speed
```
```
In drivers/net/phy/phy_device.c (c000000000a97b84)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:phy_remove_link_mode
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
```
```
In drivers/net/tun.c (c000000000a9e238)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In drivers/input/input.c (c000000000b78094)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_keycode
  - drivers/input/input.c:input_default_setkeycode
```
```
In drivers/input/ff-core.c (c000000000b7b1a0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_destroy
```
```
In drivers/input/keyboard/atkbd.c (c000000000b82d04)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In net/socket.c (c000000000c74dd0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (c000000000c83130)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/dev.c (c000000000cb3cc8)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__napi_gro_flush_chain
```
```
In net/netlink/af_netlink.c (c000000000d4878c)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
```
```
In net/ipv4/inet_connection_sock.c (c000000000d72164)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (c000000000d7da38)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (c000000000d7f1bc)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (c000000000d8e2d4)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/unix/garbage.c (c000000000e1afdc)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (c000000000e1c998)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In net/packet/af_packet.c (c000000000e970ec)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In lib/idr.c (c000000000ec9968)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - lib/idr.c:ida_free
```
```
In lib/radix-tree.c (c000000000ed0e60)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (0)
Location: include/asm-generic/bitops/non-atomic.h:24
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
In kernel/workqueue.c (ffffffe0000d6c68)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/fair.c (ffffffe0000f4be2)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/rt.c (ffffffe0000f6aa8)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - kernel/sched/rt.c:__delist_rt_entity
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/sched/debug.c (ffffffe000105b0a)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/isolation.c (ffffffe0000072ac)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In kernel/time/timer.c (ffffffe00012bd92)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/smp.c (ffffffe0001409b4)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In mm/filemap.c (ffffffe0001d6a36)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffe0001e2c7c)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffe0001ea53a)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/percpu.c (0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In mm/page_alloc.c (ffffffe000015a46)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/swap_state.c (ffffffe000222d62)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffe00022f392)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/slub.c (ffffffe000239424)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
```
```
In mm/migrate.c (ffffffe00023fad4)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:putback_movable_page
```
```
In mm/cma.c (0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In fs/file.c (ffffffe000275556)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
```
```
In fs/ext4/mballoc.c (ffffffe00031790c)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_clear_bits
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dev.c (ffffffe00037195a)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
```
```
In block/blk-cgroup.c (ffffffe000445a28)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffe0004a9580)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/gpio/gpiolib-of.c (0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In drivers/pwm/core.c (0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffe00055e3a2)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In drivers/net/phy/phy.c (ffffffe00061e01a)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (ffffffe00061ed0e)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy-core.c (ffffffe00061ffd2)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:of_set_phy_supported
  - drivers/net/phy/phy-core.c:phy_set_max_speed
```
```
In drivers/net/phy/phy_device.c (ffffffe000620fbe)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:phy_remove_link_mode
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
```
```
In drivers/net/tun.c (ffffffe000626612)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In drivers/input/input.c (ffffffe0006a8a6a)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_keycode
  - drivers/input/input.c:input_default_setkeycode
```
```
In drivers/input/ff-core.c (ffffffe0006ab570)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_destroy
```
```
In drivers/input/keyboard/atkbd.c (ffffffe0006aff26)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In net/socket.c (ffffffe000738b50)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffe00073fa3a)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/dev.c (ffffffe00075e570)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
```
```
In net/netlink/af_netlink.c (ffffffe0007b7bc6)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d2048)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffe0007d91e2)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffe0007da1be)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (ffffffe0007e49fe)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/unix/garbage.c (ffffffe000840ab0)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (ffffffe000841c1c)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
```
```
In net/packet/af_packet.c (ffffffe00089405e)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In lib/idr.c (ffffffe0008b2bce)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - lib/idr.c:ida_free
```
```
In lib/radix-tree.c (ffffffe0008b6f20)
Location: include/asm-generic/bitops/non-atomic.h:24
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (0)
Location: include/asm-generic/bitops/non-atomic.h:24
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
In arch/x86/events/core.c (ffffffff810066b8)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_stop
```
```
In arch/x86/events/intel/core.c (ffffffff8100d4ae)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104cc6e)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__mce_disable_bank
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8104fefc)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81060e5c)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106d138)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106d5f1)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
```
```
In arch/x86/kernel/kvm.c (ffffffff81076438)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81a6a393)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/workqueue.c (ffffffff810ba3af)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/fair.c (ffffffff810e5369)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/rt.c (ffffffff810e7c96)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/sched/debug.c (ffffffff810f5cbb)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/isolation.c (ffffffff828b69b2)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In kernel/time/timer.c (ffffffff8112c8c8)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/smp.c (ffffffff8114741f)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In mm/filemap.c (ffffffff8121be87)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffff8122a1db)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff81232f69)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/percpu.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In mm/page_alloc.c (ffffffff828c711d)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/swap_state.c (ffffffff8127f786)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff8128c9e5)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/slub.c (ffffffff8129dcc3)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
```
```
In mm/migrate.c (ffffffff812a99f8)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:putback_movable_page
```
```
In mm/cma.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In mm/memremap.c (ffffffff812cc920)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In fs/file.c (ffffffff812f7fe5)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
```
```
In fs/ext4/mballoc.c (ffffffff813b4699)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_clear_bits
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dev.c (ffffffff8141a77c)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
```
```
In block/blk-cgroup.c (ffffffff815026e0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff815647e1)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/pwm/core.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In drivers/acpi/hmat/hmat.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8167dc5e)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff816a76d3)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:domain_id_free
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In drivers/net/phy/phy.c (ffffffff8177d5e5)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (ffffffff8177e4c5)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy-core.c (ffffffff8177f8c9)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_set_max_speed
```
```
In drivers/net/phy/phy_device.c (ffffffff81781c15)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_remove_link_mode
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
```
```
In drivers/net/tun.c (ffffffff81785bcc)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In drivers/input/input.c (ffffffff8180d7dd)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_keycode
  - drivers/input/input.c:input_default_setkeycode
```
```
In drivers/input/ff-core.c (ffffffff8180fc13)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_destroy
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81814b7c)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In net/socket.c (ffffffff818ab849)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff818b4af0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/dev.c (ffffffff818d60b7)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
```
```
In net/netlink/af_netlink.c (ffffffff8193d445)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195aa0f)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff8196314d)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff8196439e)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (ffffffff8196ff2a)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/unix/garbage.c (ffffffff819d3e55)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (ffffffff819d504a)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a30279)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In lib/idr.c (ffffffff81a4e34c)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - lib/idr.c:ida_free
```
```
In lib/radix-tree.c (ffffffff81a52d82)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
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
In arch/x86/events/core.c (ffffffff81004dd8)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_stop
```
```
In arch/x86/events/intel/core.c (ffffffff8100bcae)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103c0ee)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__mce_disable_bank
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8103f9e1)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810512bc)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105d52b)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105da21)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
```
```
In arch/x86/kernel/kvm.c (ffffffff810663a8)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81a26855)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/workqueue.c (ffffffff810a8cef)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/fair.c (ffffffff810d4512)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/rt.c (ffffffff810d712f)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:alloc_rt_sched_group
```
```
In kernel/sched/debug.c (ffffffff810e5e7b)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/isolation.c (ffffffff828aeba8)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In kernel/time/timer.c (ffffffff8111f138)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/smp.c (ffffffff8113a6fa)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In mm/filemap.c (ffffffff8120f077)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffff8121d2fb)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff81226009)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/percpu.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In mm/page_alloc.c (ffffffff828bf842)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/swap_state.c (ffffffff812715a6)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff8127e805)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/slub.c (ffffffff8128f853)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
```
```
In mm/migrate.c (ffffffff8129b358)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:putback_movable_page
```
```
In mm/cma.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In mm/memremap.c (ffffffff812bd790)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In fs/file.c (ffffffff812e8c05)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
```
```
In fs/ext4/mballoc.c (ffffffff813a5129)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_clear_bits
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dev.c (ffffffff8140b1fc)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
```
```
In block/blk-cgroup.c (ffffffff814f2a10)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff81555631)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/acpi/hmat/hmat.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8165cd4e)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff816850c3)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:domain_id_free
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In drivers/net/phy/phy.c (ffffffff8175d3a5)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (ffffffff8175e265)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy-core.c (ffffffff8175f669)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_set_max_speed
```
```
In drivers/net/phy/phy_device.c (ffffffff817619a5)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_remove_link_mode
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
```
```
In drivers/net/tun.c (ffffffff8176551c)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In drivers/input/input.c (ffffffff817d4f4d)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_keycode
  - drivers/input/input.c:input_default_setkeycode
```
```
In drivers/input/ff-core.c (ffffffff817d7363)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_destroy
```
```
In drivers/input/keyboard/atkbd.c (ffffffff817dc2ac)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In net/socket.c (ffffffff81865799)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff8186ea40)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/dev.c (ffffffff8188fef7)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
```
```
In net/netlink/af_netlink.c (ffffffff818f6f45)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819144ff)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff8191cc3d)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff8191de8e)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (ffffffff819299fa)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/unix/garbage.c (ffffffff81990c15)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (ffffffff81991e0a)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819ed469)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In lib/idr.c (ffffffff81a0b43c)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - lib/idr.c:ida_free
```
```
In lib/radix-tree.c (ffffffff81a0fe82)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
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
In arch/x86/events/core.c (ffffffff81006678)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_stop
```
```
In arch/x86/events/intel/core.c (ffffffff8100d46e)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104caae)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__mce_disable_bank
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8104fdac)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106128c)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106d5e8)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106daa1)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
```
```
In arch/x86/kernel/kvm.c (ffffffff810763e8)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81ad67a3)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/workqueue.c (ffffffff810b990f)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/fair.c (ffffffff810e1739)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/rt.c (ffffffff810e430f)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:alloc_rt_sched_group
```
```
In kernel/sched/debug.c (ffffffff810f2ebb)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/isolation.c (ffffffff828c9856)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In kernel/time/timer.c (ffffffff8112a5e8)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/smp.c (ffffffff811452cf)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In mm/filemap.c (ffffffff81219c27)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffff81227f7b)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff81230d09)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/percpu.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In mm/page_alloc.c (ffffffff828d9e9d)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/swap_state.c (ffffffff8127d526)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff8128a7f5)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/slub.c (ffffffff8129bad3)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
```
```
In mm/migrate.c (ffffffff812a7808)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:putback_movable_page
```
```
In mm/cma.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In mm/memremap.c (ffffffff812ca730)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In fs/file.c (ffffffff812f5df5)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
```
```
In fs/ext4/mballoc.c (ffffffff813b1ef9)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_clear_bits
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dev.c (ffffffff8141691c)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
```
```
In block/blk-cgroup.c (ffffffff814fe770)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff81563351)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/pwm/core.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff816ac03e)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff816d5943)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:domain_id_free
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In drivers/net/phy/phy.c (ffffffff817ad995)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (ffffffff817ae875)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy-core.c (ffffffff817afc79)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_set_max_speed
```
```
In drivers/net/phy/phy_device.c (ffffffff817b1fc5)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_remove_link_mode
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
```
```
In drivers/net/tun.c (ffffffff817b5f7c)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In drivers/input/input.c (ffffffff8184c95d)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_keycode
  - drivers/input/input.c:input_default_setkeycode
```
```
In drivers/input/ff-core.c (ffffffff8184ed93)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_destroy
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81853cfc)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In net/socket.c (ffffffff818fc849)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81905af0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/dev.c (ffffffff819270e7)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
```
```
In net/netlink/af_netlink.c (ffffffff8198e5d5)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c51df)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff819cd91d)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff819ceb6e)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (ffffffff819da6fa)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/unix/garbage.c (ffffffff81a3e8d5)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (ffffffff81a3faca)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a9be29)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In lib/idr.c (ffffffff81aba73c)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - lib/idr.c:ida_free
```
```
In lib/radix-tree.c (ffffffff81abf172)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
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
In arch/x86/events/core.c (ffffffff810067d8)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_stop
```
```
In arch/x86/events/intel/core.c (ffffffff8100d69e)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104debe)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__mce_disable_bank
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff810511ec)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_discover
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81062847)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106f868)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106fd21)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
```
```
In arch/x86/kernel/kvm.c (ffffffff81078438)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81ae2c63)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/workqueue.c (ffffffff810c2a2f)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/fair.c (ffffffff810ed3a4)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/rt.c (ffffffff810f04a6)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/sched/debug.c (ffffffff810fdebb)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/isolation.c (ffffffff828cec08)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In kernel/time/timer.c (ffffffff81137bc8)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/smp.c (ffffffff81151eaf)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In mm/filemap.c (ffffffff81228d27)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffff812372bb)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff81240159)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/percpu.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In mm/page_alloc.c (ffffffff828df2be)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/swap_state.c (ffffffff8128d0e5)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff8129a5e3)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/slub.c (ffffffff812ab9b3)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
```
```
In mm/migrate.c (ffffffff812b7b09)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:putback_movable_page
```
```
In mm/cma.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In mm/memremap.c (ffffffff812db430)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In fs/file.c (ffffffff81306f19)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
```
```
In fs/ext4/mballoc.c (ffffffff813c6a39)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_clear_bits
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fuse/dev.c (ffffffff8142d67c)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
```
```
In block/blk-cgroup.c (ffffffff81516ba0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff8157d271)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/pwm/core.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In drivers/acpi/hmat/hmat.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff816c649e)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff816ec503)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:domain_id_free
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In drivers/net/phy/phy.c (ffffffff817c7925)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (ffffffff817c8805)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy-core.c (ffffffff817c9c09)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_set_max_speed
```
```
In drivers/net/phy/phy_device.c (ffffffff817cbf55)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_remove_link_mode
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
```
```
In drivers/net/tun.c (ffffffff817d03ec)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In drivers/input/input.c (ffffffff81867c4d)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_keycode
  - drivers/input/input.c:input_default_setkeycode
```
```
In drivers/input/ff-core.c (ffffffff8186a143)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_destroy
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8186f0cc)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In net/socket.c (ffffffff8191d849)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81926b12)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/dev.c (ffffffff81948756)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
```
```
In net/netlink/af_netlink.c (ffffffff819b0e85)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819cecaf)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp.c (ffffffff819d74ad)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff819d86fe)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (ffffffff819e437c)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/unix/garbage.c (ffffffff81a4a247)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (ffffffff81a4b60a)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81aa65e8)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
```
In lib/idr.c (ffffffff81ac6b8c)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - lib/idr.c:ida_free
```
```
In lib/radix-tree.c (ffffffff81acb642)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (0)
Location: include/asm-generic/bitops-instrumented.h:69
Inline: True
```
</details>
</li>
</ul>

## Differences

# Function: <code>raw_atomic_try_cmpxchg</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810083a8)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/alternative.c (ffffffff8213e24e)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810931db)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810969d7)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8109fa60)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810e8304)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
```
```
In kernel/fork.c (ffffffff810f2456)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
```
```
In kernel/cpu.c (ffffffff810f96f1)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:cpuhp_kick_ap_alive
  - kernel/cpu.c:cpuhp_wait_for_sync_state
```
```
In kernel/cred.c (ffffffff8113375a)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - kernel/cred.c:get_task_cred
```
```
In kernel/sched/core.c (ffffffff81144373)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_core_put
  - kernel/sched/core.c:sched_core_get
```
```
In kernel/locking/mutex.c (ffffffff8118db5e)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
```
```
In kernel/power/hibernate.c (ffffffff81194036)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernate_acquire
```
```
In kernel/irq/chip.c (ffffffff811ae211)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In kernel/module/main.c (ffffffff811da39f)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - kernel/module/main.c:module_put
  - kernel/module/main.c:try_module_get
```
```
In kernel/futex/requeue.c (ffffffff8120bd32)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - kernel/futex/requeue.c:futex_wait_requeue_pi
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81256ac2)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
```
```
In kernel/trace/ring_buffer.c (ffffffff81273bbf)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
```
```
In kernel/bpf/ringbuf.c (ffffffff813334b2)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_user_ringbuf_drain
```
```
In kernel/events/core.c (ffffffff81370ae5)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:get_pmu_ctx
```
```
In kernel/events/uprobes.c (ffffffff8137fd64)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In kernel/jump_label.c (ffffffff81385dd4)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_slow_try_dec
  - kernel/jump_label.c:static_key_fast_inc_not_disabled
```
```
In mm/filemap.c (ffffffff8138e113)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_folios_tag
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:filemap_get_entry
```
```
In mm/vmscan.c (ffffffff813a927e)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - mm/vmscan.c:should_skip_mm
  - mm/vmscan.c:isolate_lru_folios
```
```
In mm/compaction.c (ffffffff813daeb2)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff813e3ba1)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/memory.c (ffffffff813ea8de)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - mm/memory.c:remove_device_exclusive_entry
```
```
In mm/mmap.c (ffffffff8140026d)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/rmap.c (ffffffff8140ad9d)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - mm/rmap.c:set_tlb_ubc_flush_pending
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_get_anon_vma
```
```
In mm/memory_hotplug.c (ffffffff81425841)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/swapfile.c (ffffffff814329c3)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff814464f1)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - mm/hugetlb.c:get_hwpoison_hugetlb_folio
  - mm/hugetlb.c:isolate_hugetlb
```
```
In mm/ksm.c (ffffffff81452ee3)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff81469144)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - mm/migrate.c:isolate_movable_page
```
```
In mm/migrate_device.c (ffffffff8146e4f9)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_range
```
```
In mm/huge_memory.c (ffffffff8147829f)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:mm_get_huge_zero_page
```
```
In mm/memcontrol.c (ffffffff81488ee8)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff814999ae)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_any_page
```
```
In mm/page_idle.c (ffffffff814a2ad5)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_folio
```
```
In mm/memfd.c (ffffffff814a62ec)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff814a8879)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/super.c (ffffffff814b34f1)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/exec.c (ffffffff814b98d5)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
```
```
In fs/namei.c (ffffffff814c1f21)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - fs/namei.c:do_open
```
```
In fs/kernel_read_file.c (ffffffff815063d2)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file
```
```
In fs/userfaultfd.c (ffffffff815262fa)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/aio.c (ffffffff81527730)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - fs/aio.c:__get_reqs_available
```
```
In fs/verity/enable.c (ffffffff8153c015)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/mbcache.c (ffffffff8154c999)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
```
```
In fs/proc/task_mmu.c (ffffffff81565007)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff81568c36)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_read_iter
  - fs/proc/inode.c:proc_reg_llseek
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff8156ae23)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/kernfs/dir.c (ffffffff815831f8)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
  - fs/kernfs/dir.c:kernfs_get_active
```
```
In fs/ext4/balloc.c (ffffffff8158fe80)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff815a8d2d)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff815cd4e8)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_discard_allocated_blocks
  - fs/ext4/mballoc.c:ext4_discard_allocated_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_discard_work
  - fs/ext4/mballoc.c:ext4_discard_work
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff81600c24)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In fs/ext4/orphan.c (ffffffff8160fc01)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_file_add
```
```
In fs/fuse/file.c (ffffffff8165b387)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
```
```
In block/blk-mq-tag.c (ffffffff81786e5a)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_find_and_get_req
```
```
In block/blk-rq-qos.c (ffffffff8179bfc7)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
```
In block/blk-iocost.c (ffffffff817aa359)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_delay
```
```
In io_uring/timeout.c (ffffffff817d9dde)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - io_uring/timeout.c:io_link_timeout_fn
```
```
In lib/sbitmap.c (ffffffff818e5217)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_wake_up
```
```
In drivers/phy/phy-core.c (ffffffff818e9cd1)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff8192ac36)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a317d0)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
```
```
In drivers/clk/clk.c (ffffffff81a3f360)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
```
```
In drivers/xen/events/events_base.c (ffffffff81a688d1)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81aba422)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/tty/serial/serial_core.c (ffffffff81abfd90)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_put_char
  - drivers/tty/serial/serial_core.c:uart_poll_get_char
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_carrier_raised
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_icount
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_send_xchar
  - drivers/tty/serial/serial_core.c:uart_flush_buffer
  - drivers/tty/serial/serial_core.c:uart_chars_in_buffer
  - drivers/tty/serial/serial_core.c:uart_write_room
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/tty/serdev/core.c (ffffffff81adbbef)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/iommu/iommu-sva.c (ffffffff81b2a0ab)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf
```
```
In drivers/base/core.c (ffffffff81b3353e)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_release_fn
```
```
In drivers/base/power/runtime.c (ffffffff81b4fa9f)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:__rpm_put_suppliers
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/base/power/wakeup.c (ffffffff81b572e6)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In drivers/scsi/hosts.c (ffffffff81bcaba1)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/spi/spi.c (ffffffff81c2e555)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_transfer_message
```
```
In drivers/spi/spi-mem.c (ffffffff81c2fe3a)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
```
```
In drivers/cdrom/cdrom.c (ffffffff81c73c17)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81c80995)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
```
```
In drivers/usb/core/hcd.c (ffffffff81c84255)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff81c8df29)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81c9f7d5)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci.c (ffffffff81ce5fe6)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_free_dev
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81d3713f)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81d37657)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81d9dfee)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
```
In drivers/mmc/core/sdio.c (ffffffff81dc3326)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81dc4aab)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/firmware/efi/efi.c (ffffffff82148a12)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81de3288)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In net/core/dev.c (ffffffff81e2f0d3)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81fdda1f)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_update_sernum
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff82005d51)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In lib/dec_and_lock.c (ffffffff8209fb7e)
Location: include/linux/atomic/atomic-arch-fallback.h:2113
Inline: True
Inline callers:
  - lib/dec_and_lock.c:_atomic_dec_and_raw_lock_irqsave
  - lib/dec_and_lock.c:_atomic_dec_and_raw_lock
  - lib/dec_and_lock.c:_atomic_dec_and_lock_irqsave
  - lib/dec_and_lock.c:_atomic_dec_and_lock
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
In arch/x86/events/core.c (ffffffff8100dac8)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/alternative.c (ffffffff8222023e)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109a64b)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109df47)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff810a033a)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_nmi_unknown
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810a6fc5)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810f06a4)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
```
```
In kernel/fork.c (ffffffff810fc026)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
```
```
In kernel/panic.c (ffffffff810ff346)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - kernel/panic.c:panic
  - kernel/panic.c:nmi_panic
```
```
In kernel/cpu.c (ffffffff81102b01)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:cpuhp_kick_ap_alive
  - kernel/cpu.c:cpuhp_wait_for_sync_state
```
```
In kernel/sched/core.c (ffffffff81151b61)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_tick_remote
  - kernel/sched/core.c:sched_core_put
  - kernel/sched/core.c:sched_core_get
```
```
In kernel/locking/mutex.c (ffffffff8119c50e)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
```
```
In kernel/power/hibernate.c (ffffffff811a2a26)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernate_acquire
```
```
In kernel/printk/nbcon.c (ffffffff811b39b7)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - kernel/printk/nbcon.c:__nbcon_context_update_unsafe
  - kernel/printk/nbcon.c:nbcon_context_can_proceed
```
```
In kernel/irq/chip.c (ffffffff811bde11)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In kernel/module/main.c (ffffffff811f004f)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - kernel/module/main.c:module_put
  - kernel/module/main.c:try_module_get
```
```
In kernel/futex/requeue.c (ffffffff812232c7)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - kernel/futex/requeue.c:futex_wait_requeue_pi
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
```
```
In kernel/kexec_core.c (ffffffff8122cd5c)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81270982)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
```
```
In kernel/seccomp.c (ffffffff81279a3b)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - kernel/seccomp.c:recv_wait_event
  - kernel/seccomp.c:recv_wait_event
```
```
In kernel/trace/ring_buffer.c (ffffffff8128e1bf)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
```
```
In kernel/bpf/ringbuf.c (ffffffff81357ba2)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_user_ringbuf_drain
```
```
In kernel/events/core.c (ffffffff81399de5)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:get_pmu_ctx
```
```
In kernel/events/uprobes.c (ffffffff813a8fb3)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In kernel/jump_label.c (ffffffff813af294)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_slow_try_dec
  - kernel/jump_label.c:static_key_fast_inc_not_disabled
```
```
In mm/filemap.c (ffffffff813b9069)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - mm/filemap.c:next_uptodate_folio
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_folios_tag
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:filemap_get_entry
```
```
In mm/vmscan.c (ffffffff813d63f3)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_folios
```
```
In mm/compaction.c (ffffffff81404da9)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff8140e411)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/memory.c (ffffffff8141700a)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - mm/memory.c:remove_device_exclusive_entry
```
```
In mm/mmap.c (ffffffff8142cbf6)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/rmap.c (ffffffff8143be88)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_get_anon_vma
```
```
In mm/memory_hotplug.c (ffffffff81452a93)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/swapfile.c (ffffffff8146bde3)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8147ff91)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - mm/hugetlb.c:get_hwpoison_hugetlb_folio
  - mm/hugetlb.c:isolate_hugetlb
```
```
In mm/ksm.c (ffffffff8148d743)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff81498064)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - mm/migrate.c:isolate_movable_page
```
```
In mm/migrate_device.c (ffffffff8149ee89)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_range
```
```
In mm/huge_memory.c (ffffffff814a79df)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:mm_get_huge_zero_page
```
```
In mm/memcontrol.c (ffffffff814b45ed)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
```
```
In mm/memory-failure.c (ffffffff814c914e)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_any_page
```
```
In mm/page_idle.c (ffffffff814d3965)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_folio
```
```
In mm/memfd.c (ffffffff814d723c)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff814d9972)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/super.c (ffffffff814e4799)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - fs/super.c:get_bdev_super
  - fs/super.c:grab_super
```
```
In fs/exec.c (ffffffff814ebdc5)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
```
```
In fs/namei.c (ffffffff814f43e1)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - fs/namei.c:do_open
```
```
In fs/kernel_read_file.c (ffffffff8153b0f2)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file
```
```
In fs/userfaultfd.c (ffffffff8155954b)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_move
  - fs/userfaultfd.c:userfaultfd_poison
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/aio.c (ffffffff8155c570)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - fs/aio.c:__get_reqs_available
```
```
In fs/verity/enable.c (ffffffff815712f5)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/mbcache.c (ffffffff815827c9)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
```
```
In fs/proc/task_mmu.c (ffffffff8159c407)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff815a1256)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_read_iter
  - fs/proc/inode.c:proc_reg_llseek
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff815a3803)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/kernfs/dir.c (ffffffff815bbe48)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
  - fs/kernfs/dir.c:kernfs_get_active
```
```
In fs/ext4/balloc.c (ffffffff815c8a0f)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff815e19a2)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff81605d68)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_discard_allocated_blocks
  - fs/ext4/mballoc.c:ext4_discard_allocated_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_context
  - fs/ext4/mballoc.c:ext4_mb_mark_context
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_discard_work
  - fs/ext4/mballoc.c:ext4_discard_work
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff81639974)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In fs/ext4/orphan.c (ffffffff816489c1)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_file_add
```
```
In fs/fuse/file.c (ffffffff81695057)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
```
```
In block/bdev.c (ffffffff817a771d)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - block/bdev.c:bdev_thaw
```
```
In block/blk-mq-tag.c (ffffffff817c953a)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_find_and_get_req
```
```
In block/blk-rq-qos.c (ffffffff817dfa27)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
```
In block/blk-iocost.c (ffffffff817ee0e1)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_delay
```
```
In io_uring/timeout.c (ffffffff8181dfee)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - io_uring/timeout.c:io_link_timeout_fn
```
```
In lib/sbitmap.c (ffffffff8192c217)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_wake_up
```
```
In drivers/phy/phy-core.c (ffffffff81931171)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff819734c6)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a7cc40)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
```
```
In drivers/clk/clk.c (ffffffff81a8ac90)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
```
```
In drivers/xen/events/events_base.c (ffffffff81ab9bf2)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81b0d162)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/tty/serial/serial_core.c (ffffffff81b12c10)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_put_char
  - drivers/tty/serial/serial_core.c:uart_poll_get_char
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_carrier_raised
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_icount
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_send_xchar
  - drivers/tty/serial/serial_core.c:uart_flush_buffer
  - drivers/tty/serial/serial_core.c:uart_chars_in_buffer
  - drivers/tty/serial/serial_core.c:uart_write_room
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:__uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/tty/serdev/core.c (ffffffff81b2ef4f)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/iommu/iommu-sva.c (ffffffff81b8127b)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf
```
```
In drivers/base/core.c (ffffffff81b8ae7d)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_release_fn
```
```
In drivers/base/power/runtime.c (ffffffff81ba801f)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:__rpm_put_suppliers
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/base/power/wakeup.c (ffffffff81baf8d6)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In drivers/scsi/hosts.c (ffffffff81c1f7d1)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/spi/spi.c (ffffffff81ce0fa5)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_transfer_message
```
```
In drivers/spi/spi-mem.c (ffffffff81ce2cfa)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
```
```
In drivers/cdrom/cdrom.c (ffffffff81d285d7)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81d35365)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
```
```
In drivers/usb/core/hcd.c (ffffffff81d38c55)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff81d42a49)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81d5442c)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci.c (ffffffff81d9b096)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_free_dev
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81ded377)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81ded8d7)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81e55d6e)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
```
In drivers/mmc/core/sdio.c (ffffffff81e7bc06)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81e7d38b)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/firmware/efi/efi.c (ffffffff8222b432)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81e99378)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In net/core/dev.c (ffffffff81eedd53)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff820aaacf)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_update_sernum
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff820d4ba3)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In lib/dec_and_lock.c (ffffffff82177b4e)
Location: include/linux/atomic/atomic-arch-fallback.h:2122
Inline: True
Inline callers:
  - lib/dec_and_lock.c:_atomic_dec_and_raw_lock_irqsave
  - lib/dec_and_lock.c:_atomic_dec_and_raw_lock
  - lib/dec_and_lock.c:_atomic_dec_and_lock_irqsave
  - lib/dec_and_lock.c:_atomic_dec_and_lock
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

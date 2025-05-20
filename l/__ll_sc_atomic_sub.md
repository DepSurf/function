# Function: <code>__ll_sc_atomic_sub</code>

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
In arch/arm64/kernel/smp.c (ffff80001009ccf0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - arch/arm64/kernel/smp.c:handle_IPI
```
```
In arch/arm64/kernel/suspend.c (ffff8000100a6ea0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - arch/arm64/kernel/suspend.c:cpu_suspend
```
```
In kernel/fork.c (ffff8000100f4404)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/cpu.c (ffff8000100fa2bc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In kernel/exit.c (ffff8000100fad1c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/workqueue.c (ffff800010120730)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cred.c (ffff80001012d488)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/async.c (ffff80001012e948)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/ucount.c (ffff800010130338)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (ffff80001013a478)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffff80001014c4d8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (ffff80001015029c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffff800010152bc0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffff800010159fc0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/locking/spinlock.c (ffff800010da7490)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
```
```
In kernel/locking/qrwlock.c (ffff80001016c7a4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/process.c (ffff80001016ffe8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
```
```
In kernel/irq/spurious.c (ffff80001017d218)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/rcu/update.c (ffff800010189090)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_end_inkernel_boot
```
```
In kernel/rcu/srcutree.c (ffff80001018a708)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/futex.c (ffff8000101b9268)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:__unqueue_futex
```
```
In kernel/cgroup/cgroup.c (ffff8000101d720c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/cgroup/legacy_freezer.c (ffff8000101de288)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_css_offline
```
```
In kernel/debug/debug_core.c (ffff8000101f98a4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/trace/ftrace.c (ffff800010210f48)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffff80001021a6b0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_record_enable
```
```
In kernel/trace/trace.c (ffff800010221644)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:s_stop
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (ffff8000102301c0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffff800010230974)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffff800010233420)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/fgraph.c (ffff8000102380dc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In kernel/trace/trace_kdb.c (ffff800010255238)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/bpf/syscall.c (ffff80001025ff28)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_add
  - kernel/bpf/syscall.c:bpf_map_inc
```
```
In kernel/bpf/hashtab.c (ffff800010278500)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/offload.c (ffff80001028a47c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffff80001029c9c0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_migrate_context
```
```
In kernel/events/callchain.c (ffff8000102a3634)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/uprobes.c (ffff8000102a5480)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/padata.c (ffff8000102a9b50)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/padata.c:padata_find_next
```
```
In mm/filemap.c (ffff8000102aef00)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/shmem.c (ffff8000102d18f0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/backing-dev.c (ffff8000102ddba8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/mmap.c (ffff800010303868)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_link_file
  - mm/mmap.c:__remove_shared_vm_struct
```
```
In mm/mmu_gather.c (ffff800010304e50)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mprotect.c (ffff800010305688)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffff800010309bc4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In mm/swap_state.c (ffff8000103215e8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffff800010327bbc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffff80001032a524)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffff80001032b578)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_free_entry
```
```
In mm/huge_memory.c (ffff8000103562cc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffff80001035f73c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/memcontrol.c (ffff800010365fb0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
```
```
In mm/zpool.c (ffff800010372a14)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - mm/zpool.c:zpool_destroy_pool
  - mm/zpool.c:zpool_has_pool
```
```
In fs/open.c (ffff80001037dd08)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffff8000103855d8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffff8000103983a4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/fs-writeback.c (ffff8000103c7a00)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffff8000103dc058)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/notify/mark.c (ffff8000103ea65c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify.c (ffff8000103ed5cc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
```
```
In fs/mbcache.c (ffff800010424f78)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/coredump.c (ffff800010428c38)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffff80001042fbfc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In fs/kernfs/dir.c (ffff800010453790)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_activate
```
```
In fs/devpts/inode.c (ffff80001045ebf0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_kill_index
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/balloc.c (ffff8000104611e4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffff800010465984)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffff800010475c58)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffff800010477694)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffff8000104857bc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffff800010496760)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffff800010498a48)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
```
```
In fs/ext4/mmp.c (ffff800010499694)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffff8000104b8640)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/transaction.c (ffff8000104ca764)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:sub_reserved_credits
```
```
In fs/jbd2/commit.c (ffff8000104cedc4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffff8000104d0408)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/squashfs/block.c (ffff8000104d9bf0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffff8000104df3e0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffff8000104df68c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffff8000104df984)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffff8000104dfd34)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffff8000104e0060)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In fs/ecryptfs/miscdev.c (ffff8000104fdaa8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release
```
```
In ipc/util.c (ffff80001051cee0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In ipc/msg.c (ffff80001051fb98)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
```
```
In security/keys/gc.c (ffff80001052d2b8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In security/keys/keyctl.c (ffff800010532ff8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/selinux/avc.c (ffff800010547164)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_compute_av
  - security/selinux/avc.c:avc_node_kill
  - security/selinux/avc.c:avc_node_delete
```
```
In security/selinux/hooks.c (ffff80001054e3b0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_dec
```
```
In security/selinux/xfrm.c (ffff80001056bc3c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_state_free
  - security/selinux/xfrm.c:selinux_xfrm_policy_free
```
```
In security/tomoyo/common.c (ffff80001057b5e8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffff80001057e710)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffff800010580150)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_update_domain
```
```
In security/tomoyo/environ.c (ffff800010580df8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffff800010582858)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_put_name_union
  - security/tomoyo/file.c:tomoyo_put_name_union
```
```
In security/tomoyo/gc.c (ffff800010583130)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_acl
  - security/tomoyo/gc.c:tomoyo_del_acl
  - security/tomoyo/gc.c:tomoyo_del_acl
```
```
In security/tomoyo/group.c (ffff800010583c6c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffff800010584504)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/network.c (ffff800010585764)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
```
In security/tomoyo/securityfs_if.c (ffff80001058679c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffff800010587460)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_task_free
  - security/tomoyo/tomoyo.c:tomoyo_task_free
  - security/tomoyo/tomoyo.c:tomoyo_bprm_committed_creds
  - security/tomoyo/tomoyo.c:tomoyo_cred_prepare
  - security/tomoyo/tomoyo.c:tomoyo_domain
```
```
In block/blk-flush.c (ffff8000105e6ff0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (ffff8000105e8b30)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - block/blk-ioc.c:exit_io_context
```
```
In block/blk-mq.c (ffff8000105f08d0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-tag.c (ffff8000105f4398)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-iocost.c (ffff80001061556c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (ffff80001066a070)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_finish_wait
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/irqchip/irq-renesas-irqc.c (ffff800010676c50)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-irqc.c:irqc_irq_set_wake
```
```
In drivers/pci/pci.c (ffff8000106e8fbc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffff8000107092c8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
```
In drivers/pci/ats.c (ffff800010716604)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (ffff800010743ec0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
```
In drivers/acpi/apei/ghes.c (ffff8000107b00d4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
```
```
In drivers/dma/dmaengine.c (ffff8000107fd55c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/dma/ipu/ipu_idmac.c (ffff80001080d55c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:__idmac_terminate_all
```
```
In drivers/reset/core.c (ffff80001084cfb0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffff80001085d9dc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
```
In drivers/tty/vt/keyboard.c (ffff80001149327c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/tty/serial/kgdb_nmi.c (ffff8000108a86a0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_close
```
```
In drivers/tty/serial/kgdboc.c (ffff8000108a8f1c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_post_exp_handler
```
```
In drivers/iommu/arm-smmu-v3.c (ffff8000108d6128)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_detach_dev
```
```
In drivers/connector/cn_queue.c (ffff8000108dd2a0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In drivers/connector/cn_proc.c (ffff8000108de1a4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In drivers/base/dd.c (ffff8000108eaa88)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/power/runtime.c (ffff8000108fd834)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (ffff80001093e430)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_irq_set_wake
```
```
In drivers/mfd/mfd-core.c (ffff8000109408a4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/nvdimm/namespace_devs.c (ffff80001095ab70)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:deactivate_labels
```
```
In drivers/scsi/scsi_lib.c (ffff8000109770ac)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_enable_disk_events
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
```
In drivers/net/ppp/ppp_generic.c (ffff8000109fe81c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
```
```
In drivers/usb/core/hcd.c (ffff800010a1c200)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/urb.c (ffff800010a2112c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
```
```
In drivers/media/cec/cec-pin.c (ffff800010ac4a3c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/media/cec/cec-pin.c:cec_pin_thread_func
```
```
In drivers/power/reset/vexpress-poweroff.c (ffff800010aca474)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/power/reset/vexpress-poweroff.c:_vexpress_register_restart_handler
```
```
In drivers/power/supply/power_supply_core.c (ffff800010acbd98)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (ffff800010ae8000)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffff800010afddac)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stats.c (ffff800010b0de1c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In drivers/edac/edac_pci_sysfs.c (ffff800010b1426c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/mmc/core/sdio_bus.c (ffff800010b3b1c0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/firmware/arm_scmi/clock.c (ffff800010b57da4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/clock.c:scmi_clock_rate_set
```
```
In drivers/remoteproc/remoteproc_core.c (ffff800010b81188)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/ras/debugfs.c (ffff800010b9e5d8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_release
```
```
In net/core/sock.c (ffff800010bab798)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/core/sock.c:sock_kzfree_s
  - net/core/sock.c:sock_kfree_s
  - net/core/sock.c:sock_ofree
  - net/core/sock.c:sock_rfree
```
```
In net/core/skbuff.c (ffff800010bb3678)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_rmem_free
```
```
In net/core/dev.c (ffff800010bcb424)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In net/core/neighbour.c (ffff800010be64e4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_mark_dead
```
```
In net/core/filter.c (ffff800010c0225c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/core/xdp.c (ffff800010c0697c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffff800010c08318)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In net/core/sock_map.c (ffff800010c21024)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_free_elem
```
```
In net/core/bpf_sk_storage.c (ffff800010c32424)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_alloc
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
```
```
In net/sched/cls_api.c (ffff800010c427d4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_cb_destroy
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_cls_offload_cnt_update
```
```
In net/sched/act_api.c (ffff800010c473a8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In net/netlink/af_netlink.c (ffff800010c4ef60)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_timewait_sock.c (ffff800010c6be28)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6d86c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8c328)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/udp.c (ffff800010c9c698)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/igmp.c (ffff800010cb2d7c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
```
```
In net/ipv4/inet_fragment.c (ffff800010cbf2f4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffff800010ccc288)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/xfrm/xfrm_policy.c (ffff800010cdcef8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
```
```
In net/xfrm/xfrm_state.c (ffff800010ce61cc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
```
```
In net/ipv6/af_inet6.c (ffff800010cf6630)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_destroy_sock
```
```
In net/ipv6/route.c (ffff800010d0f610)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (ffff800010d1f7fc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In net/ipv6/udp.c (ffff800010d259ac)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffff800010d2a4c0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (ffff800010d32f44)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d377f4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffff800010d3ce78)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffff800010d3f014)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
```
In net/ipv6/ip6mr.c (ffff800010d44eb8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
```
```
In net/ipv6/calipso.c (ffff800010d4d5f0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
```
```
In net/ipv6/seg6_hmac.c (ffff800010d51fe8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
```
In net/packet/af_packet.c (ffff800010d577c4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mm_close
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/netlabel/netlabel_unlabeled.c (ffff800010d68ffc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/netlabel/netlabel_cipso_v4.c (ffff800010d69ea8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
```
```
In net/netlabel/netlabel_calipso.c (ffff800010d6abc8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
</details>
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

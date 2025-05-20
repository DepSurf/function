# Function: <code>__lse_atomic_sub</code>

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
In arch/arm64/kernel/smp.c (ffff80001009ce08)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - arch/arm64/kernel/smp.c:handle_IPI
```
```
In arch/arm64/kernel/suspend.c (ffff8000100a6e5c)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - arch/arm64/kernel/suspend.c:cpu_suspend
```
```
In kernel/fork.c (ffff8000100f4284)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/cpu.c (ffff8000100fa2a8)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
```
```
In kernel/exit.c (ffff8000100fa9a0)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/workqueue.c (ffff8000101205dc)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cred.c (ffff80001012d2e0)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/async.c (ffff80001012e908)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/ucount.c (ffff8000101302e4)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (ffff80001013a3f0)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffff80001014c43c)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (ffff800010150274)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffff800010152bb0)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffff800010159f50)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/locking/spinlock.c (ffff800010da7474)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
```
```
In kernel/locking/qrwlock.c (ffff80001016c748)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/process.c (ffff80001016ffd0)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
```
```
In kernel/irq/spurious.c (ffff80001017d0a8)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/rcu/update.c (ffff800010189068)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_end_inkernel_boot
```
```
In kernel/rcu/srcutree.c (ffff80001018a6e0)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/futex.c (ffff8000101b9090)
Location: arch/arm64/include/asm/atomic_lse.h:111
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
In kernel/cgroup/cgroup.c (ffff8000101d71a4)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/cgroup/legacy_freezer.c (ffff8000101de25c)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_css_offline
```
```
In kernel/debug/debug_core.c (ffff8000101f988c)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/trace/ftrace.c (ffff800010210efc)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffff80001021a660)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_record_enable
```
```
In kernel/trace/trace.c (ffff800010221590)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:s_stop
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (ffff80001023019c)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffff8000102308fc)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffff8000102333f8)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/fgraph.c (ffff800010238098)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
```
```
In kernel/trace/trace_kdb.c (ffff8000102551cc)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/bpf/syscall.c (ffff80001025fef0)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_add
  - kernel/bpf/syscall.c:bpf_map_inc
```
```
In kernel/bpf/hashtab.c (ffff8000102784b4)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/offload.c (ffff80001028a2d4)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffff80001029c8c0)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_migrate_context
```
```
In kernel/events/callchain.c (ffff8000102a35f8)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/uprobes.c (ffff8000102a5444)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/padata.c (ffff8000102a9af4)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - kernel/padata.c:padata_find_next
```
```
In mm/filemap.c (ffff8000102aeee0)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/shmem.c (ffff8000102d18b4)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/backing-dev.c (ffff8000102ddb90)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/mmap.c (ffff8000103037c4)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_link_file
  - mm/mmap.c:__remove_shared_vm_struct
```
```
In mm/mmu_gather.c (ffff800010304e38)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mprotect.c (ffff8000103053c0)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffff800010309b60)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
```
```
In mm/swap_state.c (ffff8000103215ac)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffff800010327ad4)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffff80001032a4dc)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffff80001032b4f0)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_free_entry
```
```
In mm/huge_memory.c (ffff8000103562b0)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffff80001035f58c)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/memcontrol.c (ffff800010365f88)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
```
```
In mm/zpool.c (ffff8000103729c0)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - mm/zpool.c:zpool_destroy_pool
  - mm/zpool.c:zpool_has_pool
```
```
In fs/open.c (ffff80001037dce0)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffff8000103855a4)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffff80001039831c)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/fs-writeback.c (ffff8000103c785c)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffff8000103dc028)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/notify/mark.c (ffff8000103ea60c)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify.c (ffff8000103ed5b0)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
```
```
In fs/mbcache.c (ffff800010424ee4)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/coredump.c (ffff800010428ba0)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffff80001042fadc)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
```
```
In fs/kernfs/dir.c (ffff800010453754)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_activate
```
```
In fs/devpts/inode.c (ffff80001045ebd0)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_kill_index
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/balloc.c (ffff8000104611c0)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffff80001046593c)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffff800010475ad4)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffff800010477638)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffff800010485770)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffff800010496500)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffff8000104989d4)
Location: arch/arm64/include/asm/atomic_lse.h:111
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
In fs/ext4/mmp.c (ffff800010499594)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffff8000104b8618)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/transaction.c (ffff8000104ca590)
Location: arch/arm64/include/asm/atomic_lse.h:111
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
In fs/jbd2/commit.c (ffff8000104ce22c)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffff8000104d0194)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/squashfs/block.c (ffff8000104d9bcc)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffff8000104df324)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffff8000104df5bc)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffff8000104df964)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffff8000104dfc90)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffff8000104dffc0)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In fs/ecryptfs/miscdev.c (ffff8000104fda90)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release
```
```
In ipc/util.c (ffff80001051ce3c)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
```
```
In ipc/msg.c (ffff80001051fb8c)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
```
```
In security/keys/gc.c (ffff80001052d198)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
```
```
In security/keys/keyctl.c (ffff800010532fd4)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/selinux/avc.c (ffff800010547114)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_compute_av
  - security/selinux/avc.c:avc_node_kill
  - security/selinux/avc.c:avc_node_delete
```
```
In security/selinux/hooks.c (ffff80001054e390)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_dec
```
```
In security/selinux/xfrm.c (ffff80001056bc18)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_state_free
  - security/selinux/xfrm.c:selinux_xfrm_policy_free
```
```
In security/tomoyo/common.c (ffff80001057b5bc)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffff80001057e658)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffff800010580078)
Location: arch/arm64/include/asm/atomic_lse.h:111
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
In security/tomoyo/environ.c (ffff800010580dc0)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffff800010582848)
Location: arch/arm64/include/asm/atomic_lse.h:111
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
In security/tomoyo/gc.c (ffff800010582e9c)
Location: arch/arm64/include/asm/atomic_lse.h:111
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
In security/tomoyo/group.c (ffff800010583c38)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffff8000105844e0)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/network.c (ffff800010585724)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
```
In security/tomoyo/securityfs_if.c (ffff80001058673c)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffff80001058740c)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_task_free
  - security/tomoyo/tomoyo.c:tomoyo_task_free
  - security/tomoyo/tomoyo.c:tomoyo_bprm_committed_creds
  - security/tomoyo/tomoyo.c:tomoyo_cred_prepare
  - security/tomoyo/tomoyo.c:tomoyo_domain
```
```
In block/blk-flush.c (ffff8000105e6fcc)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (ffff8000105e8af0)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - block/blk-ioc.c:exit_io_context
```
```
In block/blk-mq.c (ffff8000105f089c)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-tag.c (ffff8000105f4370)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-iocost.c (ffff8000106154bc)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (ffff80001066a054)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_finish_wait
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/irqchip/irq-renesas-irqc.c (ffff800010676c30)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-irqc.c:irqc_irq_set_wake
```
```
In drivers/pci/pci.c (ffff8000106e8fa8)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffff800010709298)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
```
In drivers/pci/ats.c (ffff8000107165ec)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (ffff800010743e74)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
```
In drivers/acpi/apei/ghes.c (ffff8000107b00c0)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
```
```
In drivers/dma/dmaengine.c (ffff8000107fd488)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/dma/ipu/ipu_idmac.c (ffff80001080d530)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:__idmac_terminate_all
```
```
In drivers/reset/core.c (ffff80001084cf64)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffff80001085d9a4)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
```
In drivers/tty/vt/keyboard.c (ffff800011493268)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/tty/serial/kgdb_nmi.c (ffff8000108a8670)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_close
```
```
In drivers/tty/serial/kgdboc.c (ffff8000108a8eb0)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_post_exp_handler
```
```
In drivers/iommu/arm-smmu-v3.c (ffff8000108d6104)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_detach_dev
```
```
In drivers/connector/cn_queue.c (ffff8000108dd280)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
```
```
In drivers/connector/cn_proc.c (ffff8000108de0bc)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
```
```
In drivers/base/dd.c (ffff8000108ea900)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/power/runtime.c (ffff8000108fd7f8)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (ffff80001093e410)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_irq_set_wake
```
```
In drivers/mfd/mfd-core.c (ffff800010940894)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/nvdimm/namespace_devs.c (ffff80001095ab38)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:deactivate_labels
```
```
In drivers/scsi/scsi_lib.c (ffff800010977090)
Location: arch/arm64/include/asm/atomic_lse.h:111
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
In drivers/net/ppp/ppp_generic.c (ffff8000109fe800)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
```
```
In drivers/usb/core/hcd.c (ffff800010a1c1b8)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/urb.c (ffff800010a210c0)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
```
```
In drivers/media/cec/cec-pin.c (ffff800010ac49a4)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - drivers/media/cec/cec-pin.c:cec_pin_thread_func
```
```
In drivers/power/reset/vexpress-poweroff.c (ffff800010aca424)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - drivers/power/reset/vexpress-poweroff.c:_vexpress_register_restart_handler
```
```
In drivers/power/supply/power_supply_core.c (ffff800010acbd78)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (ffff800010ae7f68)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffff800010afdd28)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stats.c (ffff800010b0dd38)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In drivers/edac/edac_pci_sysfs.c (ffff800010b1415c)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/mmc/core/sdio_bus.c (ffff800010b3b1b0)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/firmware/arm_scmi/clock.c (ffff800010b57d94)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/clock.c:scmi_clock_rate_set
```
```
In drivers/remoteproc/remoteproc_core.c (ffff800010b81118)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/ras/debugfs.c (ffff800010b9e5ac)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_release
```
```
In net/core/sock.c (ffff800010bab77c)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - net/core/sock.c:sock_kzfree_s
  - net/core/sock.c:sock_kfree_s
  - net/core/sock.c:sock_ofree
  - net/core/sock.c:sock_rfree
```
```
In net/core/skbuff.c (ffff800010bb3664)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_rmem_free
```
```
In net/core/dev.c (ffff800010bcb3e0)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
```
```
In net/core/neighbour.c (ffff800010be61d8)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_mark_dead
```
```
In net/core/filter.c (ffff800010c02240)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/core/xdp.c (ffff800010c068d8)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffff800010c0826c)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
```
```
In net/core/sock_map.c (ffff800010c2100c)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_free_elem
```
```
In net/core/bpf_sk_storage.c (ffff800010c3240c)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_alloc
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
```
```
In net/sched/cls_api.c (ffff800010c4275c)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_cb_destroy
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_cls_offload_cnt_update
```
```
In net/sched/act_api.c (ffff800010c47354)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
```
```
In net/netlink/af_netlink.c (ffff800010c4ee94)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_timewait_sock.c (ffff800010c6bdc4)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6d83c)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8c1fc)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/udp.c (ffff800010c9c4f4)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/igmp.c (ffff800010cb2d44)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
```
```
In net/ipv4/inet_fragment.c (ffff800010cbf254)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffff800010ccc038)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/xfrm/xfrm_policy.c (ffff800010cdce5c)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
```
```
In net/xfrm/xfrm_state.c (ffff800010ce61a0)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
```
```
In net/ipv6/af_inet6.c (ffff800010cf6624)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_destroy_sock
```
```
In net/ipv6/route.c (ffff800010d0f5c0)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (ffff800010d1f618)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
```
```
In net/ipv6/udp.c (ffff800010d25518)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffff800010d2a244)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (ffff800010d32efc)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d3779c)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffff800010d3ce08)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffff800010d3effc)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
```
In net/ipv6/ip6mr.c (ffff800010d44c54)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
```
```
In net/ipv6/calipso.c (ffff800010d4d5e4)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_opt_update
```
```
In net/ipv6/seg6_hmac.c (ffff800010d51f74)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
```
In net/packet/af_packet.c (ffff800010d577ac)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mm_close
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/netlabel/netlabel_unlabeled.c (ffff800010d68db4)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/netlabel/netlabel_cipso_v4.c (ffff800010d69e8c)
Location: arch/arm64/include/asm/atomic_lse.h:111
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
```
```
In net/netlabel/netlabel_calipso.c (ffff800010d6abac)
Location: arch/arm64/include/asm/atomic_lse.h:111
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

# Function: <code>arch_atomic_dec</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006be3)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
```
```
In arch/x86/events/intel/core.c (ffffffff8100bd55)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015596)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_put_constraint
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81016a55)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81048d76)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104b955)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_unregister_decode_chain
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff8104f3b1)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_hcpu_update
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81058ba5)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff810592db)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/ftrace.c (ffffffff81064540)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_code
  - arch/x86/kernel/ftrace.c:update_ftrace_func
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81067a74)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:longjmp_break_handler
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81081707)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In kernel/fork.c (ffffffff8108b9f0)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/fork.c:copy_mm
```
```
In kernel/exit.c (ffffffff81091ca1)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In kernel/signal.c (ffffffff8109c661)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/workqueue.c (ffffffff810acf9e)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cred.c (ffffffff810b574b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/async.c (ffffffff810b65ac)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/ucount.c (ffffffff810b7af8)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (ffffffff819ecbe8)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff810d13de)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (ffffffff810d32ce)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810d4b90)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff810da0f4)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/power/process.c (ffffffff810e8977)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
```
```
In kernel/irq/spurious.c (ffffffff810f92c6)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/rcu/update.c (ffffffff81102875)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_end_inkernel_boot
```
```
In kernel/rcu/srcutree.c (ffffffff8110390f)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/time/clocksource.c (ffffffff8111b1cc)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/futex.c (ffffffff8112a791)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:__unqueue_futex
```
```
In kernel/cgroup/cgroup.c (ffffffff8114221d)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/cgroup/freezer.c (ffffffff8114658a)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_apply_state
  - kernel/cgroup/freezer.c:freezer_css_offline
```
```
In kernel/debug/debug_core.c (ffffffff8115e867)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/watchdog_hld.c (ffffffff8116a9d5)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
```
```
In kernel/trace/ftrace.c (ffffffff811721e3)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:profile_graph_entry
```
```
In kernel/trace/ring_buffer.c (ffffffff811780cc)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_record_enable
```
```
In kernel/trace/trace.c (ffffffff8117f696)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:s_stop
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (ffffffff8118aff3)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8118be55)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8118e989)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_kdb.c (ffffffff811abd3c)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/bpf/syscall.c (ffffffff811b3611)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811c16f1)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/sockmap.c (ffffffff811d0322)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:sock_hash_delete_elem
  - kernel/bpf/sockmap.c:sock_hash_free
  - kernel/bpf/sockmap.c:bpf_tcp_close
```
```
In kernel/events/core.c (ffffffff811ddd3c)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
```
```
In kernel/events/callchain.c (ffffffff811e3445)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/uprobes.c (ffffffff811e45b7)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/padata.c (ffffffff811e7559)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_reorder
```
```
In mm/backing-dev.c (ffffffff81217a99)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/memory.c (ffffffff8122a696)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/memory.c:tlb_finish_mmu
```
```
In mm/mmap.c (ffffffff81237dcc)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_link_file
  - mm/mmap.c:__remove_shared_vm_struct
```
```
In mm/mprotect.c (ffffffff81239e02)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection
```
```
In mm/rmap.c (ffffffff8123ed3b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In mm/swapfile.c (ffffffff8124d400)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffffffff8124f492)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff8124fb14)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_free_entry
```
```
In mm/migrate.c (ffffffff8126ede1)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/migrate.c:buffer_migrate_page
```
```
In mm/huge_memory.c (ffffffff8127766c)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/memcontrol.c (ffffffff81281295)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
```
```
In mm/zpool.c (ffffffff8128bdc5)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/zpool.c:zpool_put_driver
```
```
In fs/open.c (ffffffff812951df)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff8129bd63)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff812aabe1)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/namei.c:path_openat
```
```
In fs/fs-writeback.c (ffffffff812cc74d)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff812d91d6)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/block_dev.c (ffffffff812dd46d)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_close
```
```
In fs/notify/mark.c (ffffffff812e5d54)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify.c (ffffffff812e7d7d)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
```
```
In fs/mbcache.c (ffffffff8130a24d)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/coredump.c (ffffffff8130c92f)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffffffff81311b2b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff81336dd0)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff81339d0d)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff8134828b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff8134940c)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff8135548a)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff81364bbb)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff81366a9e)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
```
```
In fs/ext4/mmp.c (ffffffff8136760f)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/jbd2/commit.c (ffffffff81395e4b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81397566)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff81398bff)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In fs/squashfs/block.c (ffffffff8139ea04)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff813a391a)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff813a3c21)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff813a3fbc)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff813a42bd)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff813a458a)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In fs/ecryptfs/miscdev.c (ffffffff813be50a)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release
```
```
In fs/fuse/dev.c (ffffffff813c02c3)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In ipc/util.c (ffffffff813d681a)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - ipc/util.c:ipc_set_key_private
  - ipc/util.c:ipc_rmid
```
```
In ipc/msg.c (ffffffff813d8b9d)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In security/keys/gc.c (ffffffff813e3aad)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In security/keys/keyctl.c (ffffffff813e8105)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/selinux/avc.c (ffffffff813f7dd2)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_update_node
  - security/selinux/avc.c:avc_node_replace
  - security/selinux/avc.c:avc_node_delete
```
```
In security/selinux/hooks.c (ffffffff813f8d15)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_dec
```
```
In security/selinux/xfrm.c (ffffffff814172d5)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In security/tomoyo/common.c (ffffffff81422a9d)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff81426ec2)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff814288d8)
Location: arch/x86/include/asm/atomic.h:106
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
In security/tomoyo/environ.c (ffffffff8142968b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff8142ac72)
Location: arch/x86/include/asm/atomic.h:106
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
In security/tomoyo/gc.c (ffffffff8142afd0)
Location: arch/x86/include/asm/atomic.h:106
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
In security/tomoyo/group.c (ffffffff8142b918)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff8142bfa0)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/network.c (ffffffff8142ce83)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
```
In security/tomoyo/securityfs_if.c (ffffffff8142db23)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8142dd7e)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_cred_free
```
```
In block/blk-flush.c (ffffffff81487c9c)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (ffffffff8148929c)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - block/blk-ioc.c:exit_io_context
```
```
In block/blk-mq.c (ffffffff8148d893)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - block/blk-mq.c:queue_set_hctx_shared
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-tag.c (ffffffff81492fbb)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-mq-sched.c (ffffffff81494c62)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In block/genhd.c (ffffffff81497b70)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - block/genhd.c:part_dec_in_flight
  - block/genhd.c:part_dec_in_flight
```
```
In drivers/pci/pci.c (ffffffff8151e59b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81537e3a)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
```
In drivers/pci/ats.c (ffffffff81543af8)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff815d721f)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_notify_nmi
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
```
```
In drivers/dma/dmaengine.c (ffffffff815e8fa0)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/reset/core.c (ffffffff8160e6b3)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff816194f9)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
```
In drivers/tty/vt/keyboard.c (ffffffff82725831)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81641e9c)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_close
```
```
In drivers/char/agp/backend.c (ffffffff8164ec0a)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_release
```
```
In drivers/char/agp/generic.c (ffffffff81651986)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816552c6)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
```
```
In drivers/connector/cn_queue.c (ffffffff8167884b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffff8167914b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In drivers/base/dd.c (ffffffff81682f96)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/runtime.c (ffffffff8168fc85)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff816955f5)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In drivers/mfd/mfd-core.c (ffffffff816c4f85)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/nvdimm/region_devs.c (ffffffff816d7038)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff816ee4f3)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_enable_disk_events
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_mq_put_budget
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8174185b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
```
```
In drivers/usb/core/hcd.c (ffffffff81759c9d)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/urb.c (ffffffff8175cf0c)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
```
```
In drivers/usb/core/driver.c (ffffffff817618f8)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
```
```
In drivers/power/supply/power_supply_core.c (ffffffff817e0de2)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (ffffffff817f52eb)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffff81808f6e)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stats.c (ffffffff81814c95)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In drivers/md/dm-rq.c (ffffffff81815a4e)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:rq_completed
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff8181b2f7)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/ras/debugfs.c (ffffffff81865cf5)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_release
```
```
In net/core/skbuff.c (ffffffff8187e3af)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In net/core/dev.c (ffffffff8188e3da)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In net/core/neighbour.c (ffffffff818a3460)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:__neigh_create
```
```
In net/core/xdp.c (ffffffff818bae0c)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_rxq_info_unreg
```
```
In net/sched/act_api.c (ffffffff818d62c7)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff818dc213)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff818f3644)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f51f8)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
```
```
In net/ipv4/inet_fragment.c (ffffffff819391ff)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff819423a7)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/xfrm/xfrm_state.c (ffffffff81953b16)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
```
```
In net/ipv6/route.c (ffffffff81971b64)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81983ba2)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81987f7a)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81993453)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff819980dd)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81999c59)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
```
In net/ipv6/ip6mr.c (ffffffff8199eaa1)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
```
```
In net/ipv6/seg6_hmac.c (ffffffff819a9ed2)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
```
In net/packet/af_packet.c (ffffffff819ad53c)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mm_close
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819bc303)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819bcfc6)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819bdd3c)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
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
In arch/x86/events/core.c (ffffffff81006b23)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
```
```
In arch/x86/events/intel/core.c (ffffffff8100bda5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015ca6)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_put_constraint
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff810171d5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In arch/x86/xen/spinlock.c (ffffffff8102aeb0)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/xen/spinlock.c:xen_qlock_wait
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81049015)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_unregister_decode_chain
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8104ca71)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_hcpu_update
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81058ce2)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105c080)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_release
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff8105e7eb)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff8105efdb)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/ftrace.c (ffffffff8106a1e0)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_code
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81088317)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In kernel/fork.c (ffffffff81094096)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In kernel/exit.c (ffffffff81099f91)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In kernel/signal.c (ffffffff810a48c6)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/workqueue.c (ffffffff810b5d7e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cred.c (ffffffff810beab2)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/async.c (ffffffff810bf83c)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/ucount.c (ffffffff810c0bf8)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (ffffffff81a27e35)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff810dacfe)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (ffffffff810dcf6e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810de9e0)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff810e3c44)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/power/process.c (ffffffff810f3f87)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
```
```
In kernel/irq/spurious.c (ffffffff81104a76)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/rcu/update.c (ffffffff8110e285)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_end_inkernel_boot
```
```
In kernel/rcu/srcutree.c (ffffffff8110f22a)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/time/clocksource.c (ffffffff81126810)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/futex.c (ffffffff811362ff)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:__unqueue_futex
```
```
In kernel/cgroup/cgroup.c (ffffffff8114dc9d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/cgroup/freezer.c (ffffffff8115212a)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_apply_state
  - kernel/cgroup/freezer.c:freezer_css_offline
```
```
In kernel/debug/debug_core.c (ffffffff8116b4f7)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/watchdog_hld.c (ffffffff811779e5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
```
```
In kernel/trace/ftrace.c (ffffffff8117f8e3)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffffffff8118548c)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_record_enable
```
```
In kernel/trace/trace.c (ffffffff8118cf74)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:s_stop
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (ffffffff81198923)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff81199873)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8119c117)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/fgraph.c (ffffffff811a0359)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In kernel/trace/trace_kdb.c (ffffffff811ba2fc)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/bpf/syscall.c (ffffffff811c1cf1)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811d2f51)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/offload.c (ffffffff811df4b5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffffffff811ee142)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
```
```
In kernel/events/callchain.c (ffffffff811f3905)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/uprobes.c (ffffffff811f4b17)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/padata.c (ffffffff811f8479)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_reorder
```
```
In mm/backing-dev.c (ffffffff8122a9a9)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/mmap.c (ffffffff8124b765)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_link_file
  - mm/mmap.c:__remove_shared_vm_struct
```
```
In mm/mmu_gather.c (ffffffff8124d0f6)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mprotect.c (ffffffff8124da2f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff812532d0)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In mm/swapfile.c (ffffffff8126180e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffffffff81263922)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff812640b4)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_free_entry
```
```
In mm/huge_memory.c (ffffffff81288e69)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memcontrol.c (ffffffff81295cc5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
```
```
In mm/zpool.c (ffffffff812a0d25)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/zpool.c:zpool_put_driver
```
```
In fs/open.c (ffffffff812a9fe7)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff812b0a25)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff812bf9c7)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/namei.c:path_openat
```
```
In fs/fs-writeback.c (ffffffff812e197d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff812ee6a6)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/block_dev.c (ffffffff812f2a4d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_close
```
```
In fs/notify/mark.c (ffffffff812fa940)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify.c (ffffffff812fc9ad)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
```
```
In fs/mbcache.c (ffffffff8131fb7d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/coredump.c (ffffffff81322264)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffffffff813286ab)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In fs/devpts/inode.c (ffffffff8134c2ae)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_kill_index
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/balloc.c (ffffffff8134e050)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff81350ead)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff8136043b)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff813615cc)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff8136d7b9)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff8137cebe)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff8137eeee)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
```
```
In fs/ext4/mmp.c (ffffffff8137fa8f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff8139c28c)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/commit.c (ffffffff813aeba1)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813b04cc)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff813b196f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In fs/squashfs/block.c (ffffffff813b7782)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff813bc71a)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff813bca21)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff813bcdbc)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff813bd0bd)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff813bd38a)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In fs/ecryptfs/miscdev.c (ffffffff813d7b4a)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release
```
```
In ipc/util.c (ffffffff813f0ea7)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - ipc/util.c:ipc_set_key_private
  - ipc/util.c:ipc_rmid
```
```
In ipc/msg.c (ffffffff813f2a1d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In security/keys/gc.c (ffffffff813fe29d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In security/keys/keyctl.c (ffffffff81402905)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/selinux/avc.c (ffffffff81413882)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_update_node
  - security/selinux/avc.c:avc_node_replace
  - security/selinux/avc.c:avc_node_delete
```
```
In security/selinux/hooks.c (ffffffff81414915)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_dec
```
```
In security/selinux/xfrm.c (ffffffff81433765)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In security/tomoyo/common.c (ffffffff8143f0fd)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff814435ca)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff81445193)
Location: arch/x86/include/asm/atomic.h:108
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
In security/tomoyo/environ.c (ffffffff81445f4b)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff81447542)
Location: arch/x86/include/asm/atomic.h:108
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
In security/tomoyo/gc.c (ffffffff8144793c)
Location: arch/x86/include/asm/atomic.h:108
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
In security/tomoyo/group.c (ffffffff81448238)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff81448893)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/network.c (ffffffff814497d3)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
```
In security/tomoyo/securityfs_if.c (ffffffff8144a47c)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8144a6e9)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_cred_free
```
```
In block/blk-flush.c (ffffffff814a1afd)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (ffffffff814a30cc)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - block/blk-ioc.c:exit_io_context
```
```
In block/blk-mq.c (ffffffff814a9ccf)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-tag.c (ffffffff814acedb)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In lib/sbitmap.c (ffffffff8150cbf3)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_finish_wait
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/pci/pci.c (ffffffff8153432b)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8154f1f3)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
```
In drivers/pci/ats.c (ffffffff8155ae78)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8156b67d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
```
In drivers/acpi/apei/ghes.c (ffffffff815f02b1)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
```
```
In drivers/dma/dmaengine.c (ffffffff81602da0)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/reset/core.c (ffffffff8162b5f3)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff81636769)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
```
In drivers/tty/vt/keyboard.c (ffffffff828dd9f6)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff8165fffc)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_close
```
```
In drivers/char/agp/backend.c (ffffffff8166cd8a)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_release
```
```
In drivers/char/agp/generic.c (ffffffff8166fcd6)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816734c6)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
```
```
In drivers/connector/cn_queue.c (ffffffff8169792b)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffff8169822b)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/base/dd.c (ffffffff816a2b80)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/power/runtime.c (ffffffff816b0015)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff816b5c65)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/mfd/mfd-core.c (ffffffff816e6375)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/nvdimm/region_devs.c (ffffffff816f8ea5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81712093)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_enable_disk_events
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_mq_put_budget
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8176596b)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
```
```
In drivers/usb/core/hcd.c (ffffffff8177e312)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/urb.c (ffffffff8178153c)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
```
```
In drivers/usb/core/driver.c (ffffffff81785f10)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
```
```
In drivers/power/supply/power_supply_core.c (ffffffff8180c422)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (ffffffff81820e7b)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffff818350ce)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stats.c (ffffffff81840ca1)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81846ae7)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/ras/debugfs.c (ffffffff818858c5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_release
```
```
In net/core/skbuff.c (ffffffff8189ef6f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_put_abort
```
```
In net/core/dev.c (ffffffff818af2ea)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In net/core/neighbour.c (ffffffff818c6669)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_for_each_release
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_flush_dev
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/core/xdp.c (ffffffff818e1e88)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
```
In net/core/sock_map.c (ffffffff818f343e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
```
In net/sched/sch_generic.c (ffffffff818f6bb0)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/cls_api.c (ffffffff81901604)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In net/sched/act_api.c (ffffffff8190220f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81908be2)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81921164)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81923428)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
```
```
In net/ipv4/inet_fragment.c (ffffffff81968dcc)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff819721a4)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197fc94)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
```
```
In net/xfrm/xfrm_state.c (ffffffff819864d6)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
```
```
In net/ipv6/route.c (ffffffff819a72b4)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In net/ipv6/udp.c (ffffffff819ba0d1)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff819be8b0)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c97f2)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff819cea6d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff819d0829)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
```
In net/ipv6/ip6mr.c (ffffffff819d5496)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e09fe)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
```
In net/packet/af_packet.c (ffffffff819e3eac)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mm_close
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f3574)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f4206)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819f4edc)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
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
In arch/x86/events/core.c (ffffffff81006d37)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
```
```
In arch/x86/events/intel/core.c (ffffffff8100c4d5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff810172ba)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_put_constraint
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81018965)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In arch/x86/xen/spinlock.c (ffffffff8102cc9f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/xen/spinlock.c:xen_qlock_wait
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104c0f5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_unregister_decode_chain
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8104f991)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_hcpu_update
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105c286)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105f594)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_release
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81061bf5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff810623eb)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/ftrace.c (ffffffff8106da50)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_code
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108bf63)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In kernel/fork.c (ffffffff8109893d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/exit.c (ffffffff8109e5b1)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/signal.c (ffffffff810a952f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/workqueue.c (ffffffff810bbbf3)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cred.c (ffffffff810c49ec)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/async.c (ffffffff810c596b)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/ucount.c (ffffffff810c6cfd)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (ffffffff810d0861)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff810e20c7)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (ffffffff810e3f2c)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810e5b60)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff810ea85b)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/power/process.c (ffffffff810fc387)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
```
```
In kernel/irq/spurious.c (ffffffff8110dc87)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/rcu/update.c (ffffffff81117985)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_end_inkernel_boot
```
```
In kernel/rcu/srcutree.c (ffffffff81118f95)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/time/clocksource.c (ffffffff81131240)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/futex.c (ffffffff81141bda)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:__unqueue_futex
```
```
In kernel/cgroup/cgroup.c (ffffffff81159a4d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8115e7c0)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
  - kernel/cgroup/legacy_freezer.c:freezer_css_offline
```
```
In kernel/debug/debug_core.c (ffffffff811782b7)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/watchdog_hld.c (ffffffff81184845)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
```
```
In kernel/trace/ftrace.c (ffffffff8118c9d6)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffffffff81192640)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_record_enable
```
```
In kernel/trace/trace.c (ffffffff8119a869)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:s_stop
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (ffffffff811a64e3)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811a74b8)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811a9d1c)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/fgraph.c (ffffffff811ae1c5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In kernel/trace/trace_kdb.c (ffffffff811c9399)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/bpf/syscall.c (ffffffff811d2341)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811e76cc)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/offload.c (ffffffff811f4ead)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffffffff81205ab5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
```
```
In kernel/events/callchain.c (ffffffff8120b6c8)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/uprobes.c (ffffffff8120c97d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/padata.c (ffffffff81210999)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_reorder
```
```
In mm/backing-dev.c (ffffffff8123a615)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/mmap.c (ffffffff8125dc2c)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_link_file
  - mm/mmap.c:__remove_shared_vm_struct
```
```
In mm/mmu_gather.c (ffffffff8125f40b)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mprotect.c (ffffffff81260047)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff81265559)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In mm/swapfile.c (ffffffff8127c84a)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffffffff8127e542)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff8127f015)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_free_entry
```
```
In mm/huge_memory.c (ffffffff812a3ad4)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memcontrol.c (ffffffff812b1d06)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
```
```
In mm/zpool.c (ffffffff812bbfa5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/zpool.c:zpool_put_driver
```
```
In fs/open.c (ffffffff812c67b7)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff812cd3aa)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff812dcb39)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/fs-writeback.c (ffffffff813000e2)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff8130fe96)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/block_dev.c (ffffffff8131437d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_close
```
```
In fs/notify/mark.c (ffffffff8131b1ce)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8131d36d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
```
```
In fs/mbcache.c (ffffffff813473e9)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/coredump.c (ffffffff81349eff)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffffffff8135022b)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In fs/devpts/inode.c (ffffffff81374c7e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_kill_index
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/balloc.c (ffffffff81376a07)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff81379ba1)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff813895bc)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff8138a65d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff81396de8)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff813a6b2e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff813a8334)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
```
```
In fs/ext4/mmp.c (ffffffff813a8eea)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff813c64f1)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/commit.c (ffffffff813d9098)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813da954)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff813dbfa3)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In fs/squashfs/block.c (ffffffff813e1f2b)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff813e6fc2)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff813e72c9)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff813e7668)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff813e7976)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff813e7c49)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In fs/ecryptfs/miscdev.c (ffffffff814024c0)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release
```
```
In ipc/util.c (ffffffff8141cc28)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In ipc/msg.c (ffffffff8141f84d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In security/keys/gc.c (ffffffff8142a8d3)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In security/keys/keyctl.c (ffffffff8142f62d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/selinux/avc.c (ffffffff814409f3)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_replace
  - security/selinux/avc.c:avc_node_delete
```
```
In security/selinux/hooks.c (ffffffff81442155)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_dec
```
```
In security/selinux/xfrm.c (ffffffff81461295)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In security/tomoyo/common.c (ffffffff8146cd7f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff814711ed)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff81472de5)
Location: arch/x86/include/asm/atomic.h:108
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
In security/tomoyo/environ.c (ffffffff81473b61)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff81475140)
Location: arch/x86/include/asm/atomic.h:108
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
In security/tomoyo/gc.c (ffffffff81475542)
Location: arch/x86/include/asm/atomic.h:108
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
In security/tomoyo/group.c (ffffffff81475e78)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff814764e0)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/network.c (ffffffff81477436)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
```
In security/tomoyo/securityfs_if.c (ffffffff8147825e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff814783cf)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_task_free
  - security/tomoyo/tomoyo.c:tomoyo_task_free
  - security/tomoyo/tomoyo.c:tomoyo_bprm_committed_creds
  - security/tomoyo/tomoyo.c:tomoyo_cred_prepare
  - security/tomoyo/tomoyo.c:tomoyo_domain
```
```
In block/blk-flush.c (ffffffff814cfc4f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (ffffffff814d118a)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - block/blk-ioc.c:exit_io_context
```
```
In block/blk-mq.c (ffffffff814d7c79)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-tag.c (ffffffff814db1e6)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In lib/sbitmap.c (ffffffff8153b373)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_finish_wait
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/pci/pci.c (ffffffff81563802)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8157f048)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
```
In drivers/pci/ats.c (ffffffff8158b0fc)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8159bb4b)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
```
In drivers/acpi/apei/ghes.c (ffffffff8162203a)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
```
```
In drivers/dma/dmaengine.c (ffffffff816354d7)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/reset/core.c (ffffffff8165eefb)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff8166a9ba)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
```
In drivers/tty/vt/keyboard.c (ffffffff828f82e0)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81695b8c)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_close
```
```
In drivers/tty/serial/kgdboc.c (ffffffff81696325)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_post_exp_handler
```
```
In drivers/char/agp/backend.c (ffffffff816a299e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_release
```
```
In drivers/char/agp/generic.c (ffffffff816a5754)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816a8fef)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
```
```
In drivers/connector/cn_queue.c (ffffffff816d04aa)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffff816d0dab)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/base/dd.c (ffffffff816db92c)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/power/runtime.c (ffffffff816e9eb4)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff816efa95)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/mfd/mfd-core.c (ffffffff8171fb05)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/nvdimm/region_devs.c (ffffffff8173252b)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff8174da33)
Location: arch/x86/include/asm/atomic.h:108
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
In drivers/net/ppp/ppp_generic.c (ffffffff817a39a2)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
```
```
In drivers/usb/core/hcd.c (ffffffff817bc892)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/urb.c (ffffffff817bf91f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
```
```
In drivers/power/supply/power_supply_core.c (ffffffff8184e0a2)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (ffffffff81863247)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffff81876ef2)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stats.c (ffffffff81883ecd)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff8188989c)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/ras/debugfs.c (ffffffff818d0035)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_release
```
```
In net/core/skbuff.c (ffffffff818e979e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_put_abort
```
```
In net/core/dev.c (ffffffff818fb122)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In net/core/neighbour.c (ffffffff81912741)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_for_each_release
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_flush_dev
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/core/xdp.c (ffffffff81930805)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In net/core/sock_map.c (ffffffff81944afd)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_free_elem
```
```
In net/sched/cls_api.c (ffffffff81962694)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In net/sched/act_api.c (ffffffff8196335d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81969d10)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81983b28)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81985dde)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/inet_fragment.c (ffffffff819cf858)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff819dbbe2)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e9963)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
```
```
In net/xfrm/xfrm_state.c (ffffffff819f02f8)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
```
```
In net/ipv6/route.c (ffffffff81a138e2)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a29220)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81a2d7e5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a383e4)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81a3d725)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a3f290)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
```
In net/ipv6/ip6mr.c (ffffffff81a443f6)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a4f63d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
```
In net/packet/af_packet.c (ffffffff81a52da0)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mm_close
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a6296e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a6367a)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a643a0)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
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
In arch/x86/events/core.c (ffffffff81006da5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
```
```
In arch/x86/events/intel/core.c (ffffffff8100c905)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff81017c6a)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_put_constraint
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff810192f5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In arch/x86/xen/spinlock.c (ffffffff8102d56f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/xen/spinlock.c:xen_qlock_wait
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104ca85)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_unregister_decode_chain
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81050321)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_hcpu_update
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105cb96)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105fcb0)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_release
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff810624a5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff81062c5b)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/ftrace.c (ffffffff8106f070)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_code
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108cbc3)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff810971d1)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff81099395)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In kernel/fork.c (ffffffff8109eef8)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/cpu.c (ffffffff810a458f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In kernel/exit.c (ffffffff810a4b32)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/workqueue.c (ffffffff810c1e93)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cred.c (ffffffff810cdafc)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/async.c (ffffffff810cea4b)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/ucount.c (ffffffff810cfdcd)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (ffffffff810da811)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff810ebfc7)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (ffffffff810eebb0)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810f0f90)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff810f622b)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/power/process.c (ffffffff811087a7)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
```
```
In kernel/irq/spurious.c (ffffffff81119f47)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/rcu/update.c (ffffffff81123d65)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_end_inkernel_boot
```
```
In kernel/rcu/srcutree.c (ffffffff81125365)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/time/clocksource.c (ffffffff8113d180)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/futex.c (ffffffff8114dc53)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:__unqueue_futex
```
```
In kernel/cgroup/cgroup.c (ffffffff811656cd)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8116a410)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
  - kernel/cgroup/legacy_freezer.c:freezer_css_offline
```
```
In kernel/debug/debug_core.c (ffffffff81184187)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/watchdog_hld.c (ffffffff811906c5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
```
```
In kernel/trace/ftrace.c (ffffffff811985d6)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffffffff8119e430)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_record_enable
```
```
In kernel/trace/trace.c (ffffffff811a6119)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:s_stop
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (ffffffff811b1cd3)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811b2ca8)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811b550c)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/fgraph.c (ffffffff811b9935)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In kernel/trace/trace_kdb.c (ffffffff811d5089)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/bpf/syscall.c (ffffffff811de8e1)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811f3e2c)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/offload.c (ffffffff81201ebd)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffffffff81212e49)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
```
```
In kernel/events/callchain.c (ffffffff812189a8)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/uprobes.c (ffffffff81219c6d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/padata.c (ffffffff8121e0de)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/padata.c:padata_find_next
```
```
In mm/backing-dev.c (ffffffff81248925)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/mmap.c (ffffffff8126c3fc)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_link_file
  - mm/mmap.c:__remove_shared_vm_struct
```
```
In mm/mmu_gather.c (ffffffff8126dc1b)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mprotect.c (ffffffff8126e937)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff81273e4e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In mm/swapfile.c (ffffffff8128c334)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffffffff8128dfa2)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff8128ea65)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_free_entry
```
```
In mm/huge_memory.c (ffffffff812b4fd4)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memcontrol.c (ffffffff812c36c2)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
```
```
In mm/zpool.c (ffffffff812cde85)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/zpool.c:zpool_put_driver
```
```
In fs/open.c (ffffffff812d81a7)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff812dedca)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff812ee688)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/fs-writeback.c (ffffffff8131285f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff81322e66)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/notify/mark.c (ffffffff8132de9a)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify.c (ffffffff813301ad)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
```
```
In fs/mbcache.c (ffffffff8135f54f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/coredump.c (ffffffff8136219f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffffffff8136853b)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In fs/devpts/inode.c (ffffffff8138cefe)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_kill_index
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/balloc.c (ffffffff8138ec77)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff813920c1)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff813a1eef)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff813a30ad)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff813af818)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff813bf9b1)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff813c11e1)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
```
```
In fs/ext4/mmp.c (ffffffff813c1e0a)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff813df8b1)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/commit.c (ffffffff813f3091)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813f49a4)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/squashfs/block.c (ffffffff813fbf5b)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff81401042)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff81401349)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff814016e8)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff814019f6)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff81401cc9)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In fs/ecryptfs/miscdev.c (ffffffff8141c3b0)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release
```
```
In ipc/util.c (ffffffff81436a78)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In ipc/msg.c (ffffffff8143966d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In security/keys/gc.c (ffffffff81444606)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In security/keys/keyctl.c (ffffffff8144938d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/selinux/avc.c (ffffffff8145a2c3)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_replace
  - security/selinux/avc.c:avc_node_kill
  - security/selinux/avc.c:avc_node_delete
```
```
In security/selinux/hooks.c (ffffffff8145bbc5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_dec
```
```
In security/selinux/xfrm.c (ffffffff8147b045)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In security/tomoyo/common.c (ffffffff81486b5f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff8148af8d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff8148cb85)
Location: arch/x86/include/asm/atomic.h:108
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
In security/tomoyo/environ.c (ffffffff8148d901)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff8148eee0)
Location: arch/x86/include/asm/atomic.h:108
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
In security/tomoyo/gc.c (ffffffff8148f2e2)
Location: arch/x86/include/asm/atomic.h:108
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
In security/tomoyo/group.c (ffffffff8148fc18)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff81490280)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/network.c (ffffffff814911d6)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
```
In security/tomoyo/securityfs_if.c (ffffffff81491f7e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff814920ef)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_task_free
  - security/tomoyo/tomoyo.c:tomoyo_task_free
  - security/tomoyo/tomoyo.c:tomoyo_bprm_committed_creds
  - security/tomoyo/tomoyo.c:tomoyo_cred_prepare
  - security/tomoyo/tomoyo.c:tomoyo_domain
```
```
In block/blk-flush.c (ffffffff814e8fa1)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (ffffffff814ea54a)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - block/blk-ioc.c:exit_io_context
```
```
In block/blk-mq.c (ffffffff814f0ff5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-tag.c (ffffffff814f4616)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-iocost.c (ffffffff8150fcac)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (ffffffff8155c153)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_finish_wait
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/pci/pci.c (ffffffff815849c2)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff815a0a88)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
```
In drivers/pci/ats.c (ffffffff815aca28)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815bd14b)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
```
In drivers/acpi/apei/ghes.c (ffffffff81643b1a)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
```
```
In drivers/dma/dmaengine.c (ffffffff816571f3)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/reset/core.c (ffffffff816815cf)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff8168d0aa)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
```
In drivers/tty/vt/keyboard.c (ffffffff829011e1)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff816b871c)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_close
```
```
In drivers/tty/serial/kgdboc.c (ffffffff816b8eb5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_post_exp_handler
```
```
In drivers/char/agp/backend.c (ffffffff816c572e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_release
```
```
In drivers/char/agp/generic.c (ffffffff816c8484)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816cbd2f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
```
```
In drivers/connector/cn_queue.c (ffffffff816f42ca)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffff816f4bcb)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/base/dd.c (ffffffff816ff8be)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/power/runtime.c (ffffffff8170df14)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/mfd/mfd-core.c (ffffffff81743dd5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81757783)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:deactivate_labels
```
```
In drivers/scsi/scsi_lib.c (ffffffff81771be3)
Location: arch/x86/include/asm/atomic.h:108
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
In drivers/net/ppp/ppp_generic.c (ffffffff817c73f2)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
```
```
In drivers/vfio/vfio.c (ffffffff817d0ea5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_release
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_add_container_user
  - drivers/vfio/vfio.c:vfio_group_add_container_user
```
```
In drivers/usb/core/hcd.c (ffffffff817ed0b2)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/urb.c (ffffffff817f029f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
```
```
In drivers/power/supply/power_supply_core.c (ffffffff8187fae2)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (ffffffff81894f77)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffff818a98ae)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stats.c (ffffffff818b5ded)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff818bb84c)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff818e108a)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff818f5c55)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/ras/debugfs.c (ffffffff81902425)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_release
```
```
In net/core/skbuff.c (ffffffff8191b90e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_put_abort
```
```
In net/core/dev.c (ffffffff8192d272)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In net/core/neighbour.c (ffffffff81944da1)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_for_each_release
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_flush_dev
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/core/xdp.c (ffffffff81962d18)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81963bc4)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In net/core/sock_map.c (ffffffff81979afd)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_free_elem
```
```
In net/sched/cls_api.c (ffffffff81995980)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_cls_offload_cnt_reset
  - net/sched/cls_api.c:tc_cls_offload_cnt_update
```
```
In net/sched/act_api.c (ffffffff81999edd)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff819a0780)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819ba317)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bc27e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/inet_fragment.c (ffffffff81a063e8)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a12b12)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a20942)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff81a271c8)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
```
```
In net/ipv6/route.c (ffffffff81a4a4d2)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a5fd7e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81a64351)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6ef2c)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81a7438e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a75f00)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
```
In net/ipv6/ip6mr.c (ffffffff81a7afe6)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a862cd)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
```
In net/packet/af_packet.c (ffffffff81a89980)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mm_close
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a9954e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a9a22a)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a9af20)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
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
In arch/x86/events/core.c (ffffffff81007e05)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
```
```
In arch/x86/events/intel/core.c (ffffffff8100e069)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_put_event_constraints
  - arch/x86/events/intel/core.c:intel_put_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101981a)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_put_constraint
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101aa55)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In arch/x86/xen/spinlock.c (ffffffff8102f69f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/xen/spinlock.c:xen_qlock_wait
```
```
In arch/x86/kernel/alternative.c (ffffffff81bbe0b2)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff810548a1)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_hcpu_update
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105fdb0)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_move_task
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810657f0)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_release
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81068473)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff81068cfb)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81094193)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff8109c500)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109ea65)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In kernel/fork.c (ffffffff810a60e1)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/cpu.c (ffffffff810ab85f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In kernel/exit.c (ffffffff810ac5ca)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/workqueue.c (ffffffff810c9a23)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cred.c (ffffffff810d799c)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/async.c (ffffffff810d890b)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/ucount.c (ffffffff810d9dc3)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (ffffffff810e3797)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff810f67d7)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
  - kernel/sched/fair.c:nohz_balance_exit_idle
```
```
In kernel/sched/rt.c (ffffffff810f8be4)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810fa3e3)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff810ffb7b)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/power/process.c (ffffffff811133a7)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
```
```
In kernel/irq/spurious.c (ffffffff81125c3b)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/spurious.c:misrouted_irq
```
```
In kernel/rcu/update.c (ffffffff81130941)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/update.c:rcu_end_inkernel_boot
```
```
In kernel/rcu/srcutree.c (ffffffff81132508)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/time/clocksource.c (ffffffff8114be60)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/futex.c (ffffffff8115d20d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:__unqueue_futex
```
```
In kernel/cgroup/cgroup.c (ffffffff811769aa)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8117bf40)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
  - kernel/cgroup/legacy_freezer.c:freezer_css_offline
```
```
In kernel/debug/debug_core.c (ffffffff81198217)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/watchdog_hld.c (ffffffff811a5265)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
```
```
In kernel/trace/ftrace.c (ffffffff811ad5a2)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_profile_alloc
```
```
In kernel/trace/ring_buffer.c (ffffffff811b67c1)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_record_enable
  - kernel/trace/ring_buffer.c:rb_remove_pages
```
```
In kernel/trace/trace.c (ffffffff811c39e1)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_set_cpumask
  - kernel/trace/trace.c:s_stop
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (ffffffff811ca455)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811cb108)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811ce23c)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/fgraph.c (ffffffff811d26d5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:ftrace_suspend_notifier_call
```
```
In kernel/trace/trace_kdb.c (ffffffff811f177a)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/bpf/hashtab.c (ffffffff81217fe6)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/offload.c (ffffffff81229389)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In kernel/events/core.c (ffffffff8123c2d9)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:exclusive_event_destroy
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
```
```
In kernel/events/callchain.c (ffffffff812446e8)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/uprobes.c (ffffffff81246050)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/watch_queue.c (ffffffff8124c942)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:free_watch
```
```
In mm/backing-dev.c (ffffffff812768a5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/mmap.c (ffffffff8129c172)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_link_file
  - mm/mmap.c:__remove_shared_vm_struct
```
```
In mm/mmu_gather.c (ffffffff8129decd)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mprotect.c (ffffffff8129f15b)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff812a44a3)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_file_rmap
```
```
In mm/swapfile.c (ffffffff812bf333)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffffffff812c0c1b)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff812c1756)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_free_entry
```
```
In mm/huge_memory.c (ffffffff812ea4ea)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memcontrol.c (ffffffff812f9f68)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
```
```
In mm/zpool.c (ffffffff8130459c)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/zpool.c:zpool_destroy_pool
  - mm/zpool.c:zpool_has_pool
```
```
In mm/mapping_dirty_helpers.c (ffffffff8130c3da)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/open.c (ffffffff8130e249)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff81315eda)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff81321422)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/namei.c:handle_truncate
```
```
In fs/fs-writeback.c (ffffffff8134c0a5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff81359e39)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/buffer.c:buffer_exit_cpu_dead
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/notify/mark.c (ffffffff81367ef0)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8136a3fd)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
```
```
In fs/io-wq.c (ffffffff8138a3ee)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/io-wq.c:__io_worker_busy
  - fs/io-wq.c:io_worker_exit
  - fs/io-wq.c:io_worker_exit
```
```
In fs/mbcache.c (ffffffff813a512f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/coredump.c (ffffffff813a8197)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffffffff813b082b)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In fs/kernfs/inode.c (ffffffff813cd554)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/devpts/inode.c (ffffffff813d834e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_kill_index
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/balloc.c (ffffffff813da229)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff813de82f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff813edff8)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff813ef27d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff813fb830)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff8140ba45)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff8140d79a)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_tind_blocks
  - fs/ext4/migrate.c:free_tind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
```
```
In fs/ext4/mmp.c (ffffffff8140e06b)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff8142c205)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/commit.c (ffffffff814406c9)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81441ea9)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:calc_chksums
```
```
In fs/jbd2/journal.c (ffffffff814480f4)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/ecryptfs/miscdev.c (ffffffff8146af50)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release
```
```
In ipc/util.c (ffffffff81486a09)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In ipc/msg.c (ffffffff81489888)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In security/keys/gc.c (ffffffff8149563d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In security/keys/keyctl.c (ffffffff8149abcb)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/selinux/avc.c (ffffffff814adaee)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_flush
  - security/selinux/avc.c:avc_node_replace
```
```
In security/selinux/hooks.c (ffffffff814aed85)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_dec
```
```
In security/selinux/xfrm.c (ffffffff814d08b1)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_state_free
  - security/selinux/xfrm.c:selinux_xfrm_policy_free
```
```
In security/tomoyo/common.c (ffffffff814dd53f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_update_manager_entry
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff814e2274)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_parse_envp
```
```
In security/tomoyo/domain.c (ffffffff814e3e63)
Location: arch/x86/include/asm/atomic.h:108
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
In security/tomoyo/environ.c (ffffffff814e49ea)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_env
```
```
In security/tomoyo/file.c (ffffffff814e6180)
Location: arch/x86/include/asm/atomic.h:108
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
In security/tomoyo/gc.c (ffffffff814e66a9)
Location: arch/x86/include/asm/atomic.h:108
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
In security/tomoyo/group.c (ffffffff814e6f38)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff814e75dd)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/network.c (ffffffff814e85a6)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
```
In security/tomoyo/securityfs_if.c (ffffffff814e934e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff814e94ef)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_task_free
  - security/tomoyo/tomoyo.c:tomoyo_task_free
  - security/tomoyo/tomoyo.c:tomoyo_bprm_committed_creds
  - security/tomoyo/tomoyo.c:tomoyo_cred_prepare
  - security/tomoyo/tomoyo.c:tomoyo_domain
```
```
In block/blk-flush.c (ffffffff81547ece)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (ffffffff815494ea)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - block/blk-ioc.c:exit_io_context
```
```
In block/blk-mq.c (ffffffff815520f8)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-tag.c (ffffffff81554c96)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-iocost.c (ffffffff81570dd2)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (ffffffff815e5bd3)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_finish_wait
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/pci/pci.c (ffffffff8162b59f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81649555)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff81666fb5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
```
```
In drivers/acpi/apei/ghes.c (ffffffff816f1978)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_rcu_free
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
```
```
In drivers/reset/core.c (ffffffff817326bf)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff8173f17a)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
```
In drivers/tty/vt/keyboard.c (ffffffff82d18504)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff8176c97c)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_close
```
```
In drivers/char/agp/backend.c (ffffffff8177a04e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_release
```
```
In drivers/char/agp/generic.c (ffffffff8177c8f4)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff817809ff)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
```
```
In drivers/connector/cn_queue.c (ffffffff817aca52)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffff817ad415)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/base/dd.c (ffffffff817b9458)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/power/runtime.c (ffffffff817c91cd)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:update_autosuspend
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff818177e3)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:deactivate_labels
```
```
In drivers/scsi/scsi_lib.c (ffffffff81834423)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_enable_disk_events
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81891d14)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
```
```
In drivers/vfio/vfio.c (ffffffff8189baf5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_release
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_add_container_user
  - drivers/vfio/vfio.c:vfio_group_add_container_user
```
```
In drivers/usb/core/hcd.c (ffffffff818bc3ce)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/urb.c (ffffffff818c034f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
```
```
In drivers/power/supply/power_supply_core.c (ffffffff8194e3d2)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (ffffffff81962477)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffff81979ade)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stats.c (ffffffff81985116)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stat_for_entry
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff8198bf97)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_main_kobj_setup
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff819b418a)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819cbccd)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/ras/debugfs.c (ffffffff819d93c5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_release
```
```
In net/core/skbuff.c (ffffffff819ed83e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_put_abort
```
```
In net/core/dev.c (ffffffff81a00882)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In net/core/neighbour.c (ffffffff81a1528a)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_for_each_release
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_alloc
  - net/core/neighbour.c:neigh_remove_one
  - net/core/neighbour.c:neigh_update_gc_list
```
```
In net/core/xdp.c (ffffffff81a360d9)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/core/sock_map.c (ffffffff81a4ea77)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_alloc_elem
  - net/core/sock_map.c:sock_hash_alloc_elem
  - net/core/sock_map.c:sock_hash_delete_elem
```
```
In net/sched/cls_api.c (ffffffff81a6d1a5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_cb_destroy
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_cls_offload_cnt_update
```
```
In net/sched/act_api.c (ffffffff81a72cad)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/sched/act_api.c:__tcf_action_put
  - net/sched/act_api.c:__tcf_action_put
```
```
In net/netlink/af_netlink.c (ffffffff81a792fb)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aa4d9b)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa6e1d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac9cfd)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/inet_fragment.c (ffffffff81af5fc9)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81b03a0c)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1312f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff81b184ca)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
```
```
In net/ipv6/route.c (ffffffff81b40eb2)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81b58886)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81b5cdc7)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b67b7f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81b6e5d5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b707da)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
```
In net/ipv6/ip6mr.c (ffffffff81b7692c)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b81539)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
```
```
In net/packet/af_packet.c (ffffffff81b84e00)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mm_close
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b9509e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b9565a)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81b96720)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
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
In arch/x86/events/core.c (ffffffff81006eb5)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
```
```
In arch/x86/events/intel/core.c (ffffffff8100d244)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_put_event_constraints
  - arch/x86/events/intel/core.c:intel_put_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/events/intel/uncore.c (ffffffff81019e95)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_put_constraint
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101af4c)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In arch/x86/xen/spinlock.c (ffffffff8103040f)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/xen/spinlock.c:xen_qlock_wait
```
```
In arch/x86/kernel/alternative.c (ffffffff81c36952)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff810537e1)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_hcpu_update
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81063aa0)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_release
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff8106a153)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff8106a94b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810936e3)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109a5c5)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In kernel/fork.c (ffffffff810a1e78)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/cpu.c (ffffffff810a70df)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In kernel/exit.c (ffffffff810a7c8a)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/workqueue.c (ffffffff810c4b73)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cred.c (ffffffff810d27cc)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/async.c (ffffffff810d3aab)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/ucount.c (ffffffff810d4f74)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (ffffffff810e12ab)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:ttwu_do_activate
```
```
In kernel/sched/fair.c (ffffffff810f4967)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
  - kernel/sched/fair.c:nohz_balance_exit_idle
```
```
In kernel/sched/rt.c (ffffffff810f6df4)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810f883a)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff810fe654)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/power/process.c (ffffffff811103f7)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
```
```
In kernel/irq/spurious.c (ffffffff8112194b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/spurious.c:misrouted_irq
```
```
In kernel/rcu/update.c (ffffffff8112c651)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/update.c:rcu_end_inkernel_boot
```
```
In kernel/rcu/srcutree.c (ffffffff8112dcf8)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/time/clocksource.c (ffffffff811482c0)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/futex.c (ffffffff811593f3)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:__unqueue_futex
```
```
In kernel/cgroup/cgroup.c (ffffffff8117368e)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81178d70)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
  - kernel/cgroup/legacy_freezer.c:freezer_css_offline
```
```
In kernel/debug/debug_core.c (ffffffff81195457)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/watchdog_hld.c (ffffffff811a225b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
```
```
In kernel/trace/ftrace.c (ffffffff811aaeb2)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_profile_alloc
```
```
In kernel/trace/ring_buffer.c (ffffffff811b4651)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_record_enable
  - kernel/trace/ring_buffer.c:rb_remove_pages
```
```
In kernel/trace/trace.c (ffffffff811c15f1)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_set_cpumask
  - kernel/trace/trace.c:s_stop
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (ffffffff811c7ac5)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811c87e8)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811cb71c)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/fgraph.c (ffffffff811cf845)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:ftrace_suspend_notifier_call
```
```
In kernel/trace/trace_kdb.c (ffffffff811f01aa)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/bpf/hashtab.c (ffffffff8121a16d)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/offload.c (ffffffff81230f19)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In kernel/events/core.c (ffffffff81246579)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:exclusive_event_destroy
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
```
```
In kernel/events/callchain.c (ffffffff8124ecb8)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/uprobes.c (ffffffff812506c0)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/watch_queue.c (ffffffff81256d82)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:free_watch
```
```
In mm/backing-dev.c (ffffffff812811a9)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_bdi_congested
```
```
In mm/mmap.c (ffffffff812a74be)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_link_file
  - mm/mmap.c:__remove_shared_vm_struct
```
```
In mm/mmu_gather.c (ffffffff812a924d)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mprotect.c (ffffffff812aa51b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff812af498)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_file_rmap
```
```
In mm/swapfile.c (ffffffff812caf2d)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffffffff812cc63b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff812cd286)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_free_entry
```
```
In mm/huge_memory.c (ffffffff812f5672)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memcontrol.c (ffffffff81305424)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
```
```
In mm/zpool.c (ffffffff8131035c)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/zpool.c:zpool_destroy_pool
  - mm/zpool.c:zpool_has_pool
```
```
In mm/mapping_dirty_helpers.c (ffffffff8131831a)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/open.c (ffffffff8131a334)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff81321464)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff8132c9c2)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/namei.c:handle_truncate
```
```
In fs/fs-writeback.c (ffffffff81358eb9)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff81367f69)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/buffer.c:buffer_exit_cpu_dead
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/notify/mark.c (ffffffff81375260)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify.c (ffffffff813774fd)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
```
```
In fs/io_uring.c (ffffffff8139ab44)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_task_cancel
  - fs/io_uring.c:__io_uring_files_cancel
  - fs/io_uring.c:io_uring_cancel_task_requests
```
```
In fs/io-wq.c (ffffffff8139b33e)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/io-wq.c:__io_worker_busy
  - fs/io-wq.c:io_worker_exit
  - fs/io-wq.c:io_worker_exit
```
```
In fs/mbcache.c (ffffffff813b5e8f)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/coredump.c (ffffffff813b9208)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffffffff813c1e2b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813c8bdb)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/kernfs/inode.c (ffffffff813df184)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/devpts/inode.c (ffffffff813e9fee)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_kill_index
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/balloc.c (ffffffff813ebefb)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff813f00d8)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff81400b9c)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff814019d1)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff8140dfa9)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff8141eee0)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff81420c00)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_tind_blocks
  - fs/ext4/migrate.c:free_tind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
```
```
In fs/ext4/mmp.c (ffffffff814214fb)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff81444f7d)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In fs/ext4/fast_commit.c (ffffffff81456ba0)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_stop_ineligible
```
```
In fs/jbd2/commit.c (ffffffff8145c8fa)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff8145e05c)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:calc_chksums
```
```
In fs/jbd2/journal.c (ffffffff81464c34)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_fc_release_bufs
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
```
```
In fs/ecryptfs/miscdev.c (ffffffff81485860)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release
```
```
In ipc/util.c (ffffffff814a40b9)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In ipc/msg.c (ffffffff814a6ec1)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In security/keys/gc.c (ffffffff814b309d)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In security/keys/keyctl.c (ffffffff814b87fb)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/selinux/avc.c (ffffffff814cb56e)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_flush
  - security/selinux/avc.c:avc_node_replace
```
```
In security/selinux/hooks.c (ffffffff814cc825)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_dec
```
```
In security/selinux/xfrm.c (ffffffff814eddc1)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_state_free
  - security/selinux/xfrm.c:selinux_xfrm_policy_free
```
```
In security/tomoyo/common.c (ffffffff814fa95f)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_update_manager_entry
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff814ff5f4)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_parse_envp
```
```
In security/tomoyo/domain.c (ffffffff81501293)
Location: arch/x86/include/asm/atomic.h:106
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
In security/tomoyo/environ.c (ffffffff81501dea)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_env
```
```
In security/tomoyo/file.c (ffffffff81503580)
Location: arch/x86/include/asm/atomic.h:106
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
In security/tomoyo/gc.c (ffffffff81503aa9)
Location: arch/x86/include/asm/atomic.h:106
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
In security/tomoyo/group.c (ffffffff81504348)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff815049ad)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/network.c (ffffffff81505926)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
```
In security/tomoyo/securityfs_if.c (ffffffff81506677)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8150680f)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_task_free
  - security/tomoyo/tomoyo.c:tomoyo_task_free
  - security/tomoyo/tomoyo.c:tomoyo_bprm_committed_creds
  - security/tomoyo/tomoyo.c:tomoyo_cred_prepare
  - security/tomoyo/tomoyo.c:tomoyo_domain
```
```
In block/blk-flush.c (ffffffff81563c47)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (ffffffff8156530a)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - block/blk-ioc.c:exit_io_context
```
```
In block/blk-mq.c (ffffffff8156e5d6)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:blk_mq_free_request
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-tag.c (ffffffff8157143c)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-iocost.c (ffffffff8158bd37)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In block/mq-deadline.c (ffffffff81592c16)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_dispatch_request
```
```
In lib/sbitmap.c (ffffffff81609f93)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_finish_wait
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/pci/pci.c (ffffffff8165129f)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81bfb88f)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff81687b95)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
```
```
In drivers/acpi/apei/ghes.c (ffffffff8170ed38)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_rcu_free
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
```
```
In drivers/reset/core.c (ffffffff8174e80f)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff8175b0aa)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
```
In drivers/tty/vt/keyboard.c (ffffffff8300617d)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff8178743c)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_close
```
```
In drivers/char/agp/backend.c (ffffffff8179470e)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_release
```
```
In drivers/char/agp/generic.c (ffffffff81795a44)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8179882f)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
```
```
In drivers/connector/cn_queue.c (ffffffff817c1622)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffff817c1fa5)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In drivers/base/dd.c (ffffffff817ce29f)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/power/runtime.c (ffffffff817ddafc)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:update_autosuspend
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81826913)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:deactivate_labels
```
```
In drivers/scsi/scsi_lib.c (ffffffff81844da3)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_enable_disk_events
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff818a0057)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
```
```
In drivers/vfio/vfio.c (ffffffff818aa705)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_release
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_add_container_user
  - drivers/vfio/vfio.c:vfio_group_add_container_user
```
```
In drivers/usb/core/hcd.c (ffffffff818c905e)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/urb.c (ffffffff818cbe2f)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81953db2)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (ffffffff81968db1)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffff8197e42b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stats.c (ffffffff819891b6)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stat_for_entry
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff8198fac7)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_main_kobj_setup
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff819b67da)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81c2ea90)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/ras/debugfs.c (ffffffff819d8725)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_release
```
```
In net/core/skbuff.c (ffffffff819ed4fe)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_put_abort
```
```
In net/core/dev.c (ffffffff81a00c92)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In net/core/neighbour.c (ffffffff81a1557a)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_for_each_release
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_alloc
  - net/core/neighbour.c:neigh_remove_one
  - net/core/neighbour.c:neigh_update_gc_list
```
```
In net/core/xdp.c (ffffffff81a384a9)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/core/sock_map.c (ffffffff81a54a57)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_alloc_elem
  - net/core/sock_map.c:sock_hash_alloc_elem
  - net/core/sock_map.c:sock_hash_delete_elem
```
```
In net/sched/cls_api.c (ffffffff81a75b55)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_cb_destroy
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_cls_offload_cnt_update
```
```
In net/sched/act_api.c (ffffffff81a7b86d)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/sched/act_api.c:__tcf_action_put
  - net/sched/act_api.c:__tcf_action_put
```
```
In net/netlink/af_netlink.c (ffffffff81a8210b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aaf3fb)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ab14a7)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ad5c45)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/inet_fragment.c (ffffffff81b02e39)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81b11b81)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b2153f)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff81b270ba)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
```
```
In net/ipv6/route.c (ffffffff81b4f972)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81b66ebb)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81b6b607)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b763ad)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81b7d08f)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b7f110)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
```
In net/ipv6/ip6mr.c (ffffffff81b856f1)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b90d79)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
```
```
In net/packet/af_packet.c (ffffffff81b94760)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mm_close
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81ba4d09)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ba52aa)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81ba6390)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
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
In arch/x86/events/core.c (ffffffff810075d5)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
```
```
In arch/x86/events/intel/core.c (ffffffff8100dee1)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_put_event_constraints
  - arch/x86/events/intel/core.c:intel_put_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101b214)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_put_constraint
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101c2fc)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In arch/x86/xen/spinlock.c (ffffffff81030f0f)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/xen/spinlock.c:xen_qlock_wait
```
```
In arch/x86/kernel/alternative.c (ffffffff81c28df5)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff810550b1)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_hcpu_update
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81064140)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_release
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff8106ac23)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff8106b38b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810940a3)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109ad85)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In kernel/fork.c (ffffffff810a286b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/cpu.c (ffffffff810a817f)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In kernel/exit.c (ffffffff810a8b6a)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/workqueue.c (ffffffff810c6409)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cred.c (ffffffff810d43ec)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/async.c (ffffffff810d5781)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/ucount.c (ffffffff810d6c53)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (ffffffff810e30c6)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:ttwu_do_activate
```
```
In kernel/sched/fair.c (ffffffff810f69d9)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
  - kernel/sched/fair.c:nohz_balance_exit_idle
```
```
In kernel/sched/rt.c (ffffffff810f8944)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810fab3a)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff81100a39)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/power/process.c (ffffffff81110e37)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
```
```
In kernel/irq/spurious.c (ffffffff81121f9b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/rcu/update.c (ffffffff8112cbb1)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/update.c:rcu_end_inkernel_boot
```
```
In kernel/rcu/srcutree.c (ffffffff8112e248)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/time/clocksource.c (ffffffff811491ab)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/futex.c (ffffffff8115b66f)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:__unqueue_futex
```
```
In kernel/cgroup/cgroup.c (ffffffff8117426e)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811798e0)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
  - kernel/cgroup/legacy_freezer.c:freezer_css_offline
```
```
In kernel/debug/debug_core.c (ffffffff81196467)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/watchdog_hld.c (ffffffff811a2f1b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
```
```
In kernel/trace/ftrace.c (ffffffff811acbfb)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffffffff811b6089)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_record_enable
  - kernel/trace/ring_buffer.c:rb_remove_pages
```
```
In kernel/trace/trace.c (ffffffff811c2621)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_set_cpumask
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (ffffffff811c938b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811c9b37)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811cca46)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/fgraph.c (ffffffff811d0b95)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:ftrace_suspend_notifier_call
```
```
In kernel/trace/trace_kdb.c (ffffffff811f10da)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/bpf/hashtab.c (ffffffff8121d918)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/offload.c (ffffffff812350af)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In kernel/events/core.c (ffffffff8124ce05)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:exclusive_event_destroy
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
```
```
In kernel/events/callchain.c (ffffffff812535c8)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/uprobes.c (ffffffff81254b50)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/watch_queue.c (ffffffff8125b21e)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:free_watch
```
```
In mm/backing-dev.c (ffffffff812862d9)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_bdi_congested
```
```
In mm/mmap.c (ffffffff812ad200)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_link_file
  - mm/mmap.c:__remove_shared_vm_struct
```
```
In mm/mmu_gather.c (ffffffff812ae6bd)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mprotect.c (ffffffff812af95b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff812b4966)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_file_rmap
```
```
In mm/page_alloc.c (ffffffff812c21ce)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/memory_hotplug.c (ffffffff81c2d6c1)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/swapfile.c (ffffffff812d1a0b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffffffff812d306b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff812d3c76)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_free_entry
```
```
In mm/hugetlb.c (ffffffff812de35e)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
```
```
In mm/mempolicy.c (ffffffff812e3258)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_migrate_pages
```
```
In mm/migrate.c (ffffffff812f8bfb)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
```
In mm/huge_memory.c (ffffffff812fbcae)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memcontrol.c (ffffffff8130acfe)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
```
```
In mm/zpool.c (ffffffff8131641c)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/zpool.c:zpool_destroy_pool
  - mm/zpool.c:zpool_has_pool
```
```
In mm/mapping_dirty_helpers.c (ffffffff8131e50a)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/open.c (ffffffff81320414)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff81327204)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff813367d5)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/namei.c:do_open
```
```
In fs/fs-writeback.c (ffffffff81360059)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff8136e959)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/buffer.c:buffer_exit_cpu_dead
  - fs/buffer.c:invalidate_bh_lrus_cpu
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/io_uring.c (ffffffff813a1de9)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_cancel
  - fs/io_uring.c:io_uring_cancel_sqpoll
  - fs/io_uring.c:io_clean_op
```
```
In fs/io-wq.c (ffffffff813a24bd)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_exit_workers
  - fs/io-wq.c:create_io_worker
  - fs/io-wq.c:create_worker_cb
```
```
In fs/mbcache.c (ffffffff813bce6f)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/coredump.c (ffffffff813c0113)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffffffff813c89eb)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813cfc1a)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/kernfs/inode.c (ffffffff813e5d10)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/devpts/inode.c (ffffffff813f0b2e)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_kill_index
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/balloc.c (ffffffff813f2429)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff813f6365)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff81407120)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff81407f13)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff81414169)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff814258ee)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff814273bb)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
```
```
In fs/ext4/mmp.c (ffffffff81427cb5)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff8144a89e)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In fs/ext4/fast_commit.c (ffffffff8145c550)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_stop_ineligible
```
```
In fs/jbd2/commit.c (ffffffff81461f64)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff814637cc)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff8146a3c4)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_fc_release_bufs
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
```
```
In fs/ecryptfs/miscdev.c (ffffffff8148b2d0)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release
```
```
In ipc/util.c (ffffffff814a9fe0)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In ipc/msg.c (ffffffff814ace11)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In security/keys/gc.c (ffffffff814b8edd)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In security/keys/keyctl.c (ffffffff814be658)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/selinux/avc.c (ffffffff814d1b9e)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_flush
  - security/selinux/avc.c:avc_node_replace
```
```
In security/selinux/hooks.c (ffffffff814d2e55)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_dec
```
```
In security/selinux/xfrm.c (ffffffff814f4b31)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_state_free
  - security/selinux/xfrm.c:selinux_xfrm_policy_free
```
```
In security/tomoyo/common.c (ffffffff8150155f)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff8150671f)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff81507d25)
Location: arch/x86/include/asm/atomic.h:106
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
In security/tomoyo/environ.c (ffffffff81508a91)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff8150a152)
Location: arch/x86/include/asm/atomic.h:106
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
In security/tomoyo/gc.c (ffffffff8150a54e)
Location: arch/x86/include/asm/atomic.h:106
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
In security/tomoyo/group.c (ffffffff8150aec8)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff8150b52d)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/network.c (ffffffff8150c466)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
```
In security/tomoyo/securityfs_if.c (ffffffff8150d1b7)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8150d34f)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_task_free
  - security/tomoyo/tomoyo.c:tomoyo_task_free
  - security/tomoyo/tomoyo.c:tomoyo_bprm_committed_creds
  - security/tomoyo/tomoyo.c:tomoyo_cred_prepare
  - security/tomoyo/tomoyo.c:tomoyo_domain
```
```
In block/blk-flush.c (ffffffff8156c3c7)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (ffffffff8156d97a)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - block/blk-ioc.c:exit_io_context
```
```
In block/blk-mq.c (ffffffff81576181)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:blk_mq_free_request
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-tag.c (ffffffff8157946c)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-iocost.c (ffffffff81592bf7)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (ffffffff815ed023)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_finish_wait
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/pci/pci.c (ffffffff81633cf1)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81bed71b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8166a805)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
```
```
In drivers/acpi/apei/ghes.c (ffffffff816efe6c)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_rcu_free
```
```
In drivers/xen/events/events_base.c (ffffffff81717971)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
```
```
In drivers/reset/core.c (ffffffff8173232b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff8173ef4a)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
```
In drivers/tty/vt/keyboard.c (ffffffff83210d08)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff8176adac)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_close
```
```
In drivers/char/agp/backend.c (ffffffff817773de)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_release
```
```
In drivers/char/agp/generic.c (ffffffff81778704)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8177b54f)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
```
```
In drivers/connector/cn_queue.c (ffffffff817a4af2)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffff817a541b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In drivers/base/dd.c (ffffffff817b1d85)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/power/runtime.c (ffffffff817c1e7c)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:update_autosuspend
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81809b73)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:deactivate_labels
```
```
In drivers/scsi/scsi_lib.c (ffffffff81827f33)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_enable_disk_events
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81882b67)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
```
```
In drivers/vfio/vfio.c (ffffffff8188dea5)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_release
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_add_container_user
  - drivers/vfio/vfio.c:vfio_group_add_container_user
```
```
In drivers/usb/core/hcd.c (ffffffff818ac68e)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/urb.c (ffffffff818af44f)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81937c42)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (ffffffff8194ce71)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffff8196225b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stats.c (ffffffff8196d893)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stat_for_entry
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81974182)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff8199af8a)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81c20d07)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/ras/debugfs.c (ffffffff819be8a5)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_release
```
```
In net/core/skbuff.c (ffffffff819d5779)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In net/core/dev.c (ffffffff819e7462)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In net/core/neighbour.c (ffffffff819fc0da)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_for_each_release
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_alloc
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/core/xdp.c (ffffffff81a1f2e0)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/core/sock_map.c (ffffffff81a50677)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
```
In net/sched/cls_api.c (ffffffff81a5f2a2)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_cb_destroy
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_cls_offload_cnt_update
```
```
In net/sched/act_api.c (ffffffff81a6457d)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/sched/act_api.c:__tcf_action_put
  - net/sched/act_api.c:__tcf_action_put
```
```
In net/netlink/af_netlink.c (ffffffff81a6b1f3)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81a9a70b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9c7e5)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac0ca5)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/inet_fragment.c (ffffffff81aee730)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81b00430)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0f163)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff81b14cda)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
```
```
In net/ipv6/route.c (ffffffff81b3d6a2)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81b55091)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81b59951)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b64dde)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81b6bc29)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b6df50)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
```
In net/ipv6/ip6mr.c (ffffffff81b74275)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b7ff80)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
```
```
In net/packet/af_packet.c (ffffffff81b83840)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mm_close
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b93b4f)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b9440b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81b95520)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
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
In arch/x86/events/core.c (ffffffff81007e75)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
```
```
In arch/x86/events/intel/core.c (ffffffff8100e605)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_put_event_constraints
  - arch/x86/events/intel/core.c:intel_put_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101db54)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_put_constraint
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101f434)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In arch/x86/xen/spinlock.c (ffffffff810360af)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/xen/spinlock.c:xen_qlock_wait
```
```
In arch/x86/kernel/alternative.c (ffffffff81d46f85)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8105da23)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_hcpu_update
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106e130)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_release
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff810755a3)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff81075eeb)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810a3ea3)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810ab065)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In kernel/cpu.c (ffffffff810b9c2f)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In kernel/workqueue.c (ffffffff810d90c9)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
```
```
In kernel/async.c (ffffffff810e89a1)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/core.c (ffffffff810f9ad3)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:ttwu_do_activate
```
```
In kernel/sched/fair.c (ffffffff81110913)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
  - kernel/sched/fair.c:nohz_balance_exit_idle
```
```
In kernel/sched/rt.c (ffffffff81113f24)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff81115b7a)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff8111cadf)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/power/process.c (ffffffff81130923)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
```
```
In kernel/printk/printk.c (ffffffff811393af)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In kernel/irq/spurious.c (ffffffff8114254b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/rcu/update.c (ffffffff8114d8b1)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/update.c:rcu_end_inkernel_boot
```
```
In kernel/rcu/srcutree.c (ffffffff8114f705)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/time/clocksource.c (ffffffff8116d345)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/futex.c (ffffffff811801ad)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:__unqueue_futex
```
```
In kernel/cgroup/cgroup.c (ffffffff8119b2fe)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811a1200)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
  - kernel/cgroup/legacy_freezer.c:freezer_css_offline
```
```
In kernel/debug/debug_core.c (ffffffff811bf407)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/watchdog_hld.c (ffffffff811cc74b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
```
```
In kernel/trace/ftrace.c (ffffffff811d685b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffffffff811e02c7)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_record_enable
  - kernel/trace/ring_buffer.c:rb_remove_pages
```
```
In kernel/trace/trace.c (ffffffff811ed2a6)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_set_cpumask
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (ffffffff811f4dba)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811f562a)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811f9195)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/fgraph.c (ffffffff811fd7d5)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:ftrace_suspend_notifier_call
```
```
In kernel/trace/trace_kdb.c (ffffffff8122219c)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/trace/trace_dynevent.c (ffffffff812223fd)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/trace/trace_dynevent.c:trace_event_dyn_put_ref
```
```
In kernel/bpf/hashtab.c (ffffffff81256a02)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/offload.c (ffffffff8126f1df)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In kernel/events/core.c (ffffffff81289637)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:exclusive_event_destroy
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
```
```
In kernel/events/callchain.c (ffffffff8128ef08)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/uprobes.c (ffffffff81290590)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/watch_queue.c (ffffffff8129701e)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:free_watch
```
```
In mm/page-writeback.c (ffffffff812a826a)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/backing-dev.c (ffffffff812c556b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_bdi_congested
```
```
In mm/mmap.c (ffffffff812ee946)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mmu_gather.c (ffffffff812efe5d)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mprotect.c (ffffffff812f11a3)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff812f6546)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_file_rmap
```
```
In mm/page_alloc.c (ffffffff81305b54)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/memory_hotplug.c (ffffffff81d4bf93)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/swapfile.c (ffffffff81317164)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffffffff81318a7b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff81319926)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_free_entry
```
```
In mm/mempolicy.c (ffffffff8132a644)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_migrate_pages
```
```
In mm/migrate.c (ffffffff8134325b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
```
In mm/huge_memory.c (ffffffff81345aa1)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memcontrol.c (ffffffff81353414)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
```
```
In mm/zpool.c (ffffffff81362599)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/zpool.c:zpool_destroy_pool
  - mm/zpool.c:zpool_has_pool
```
```
In mm/secretmem.c (ffffffff81366335)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_release
```
```
In mm/mapping_dirty_helpers.c (ffffffff8136b8ea)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/open.c (ffffffff8136d9d3)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff81374aab)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff813841b5)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/namei.c:do_open
```
```
In fs/fs-writeback.c (ffffffff813b0651)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/fs-writeback.c:cleanup_offline_cgwb
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/buffer.c (ffffffff813bd7e5)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/buffer.c:buffer_exit_cpu_dead
  - fs/buffer.c:invalidate_bh_lrus_cpu
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:__bforget
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/userfaultfd.c (ffffffff813d5e7e)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/io_uring.c (ffffffff81cc5e96)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_cancel_generic
  - fs/io_uring.c:io_clean_op
```
```
In fs/io-wq.c (ffffffff813f171b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/io-wq.c:create_io_worker
  - fs/io-wq.c:create_worker_cont
  - fs/io-wq.c:io_queue_worker_create
  - fs/io-wq.c:create_worker_cb
  - fs/io-wq.c:io_worker_cancel_cb
```
```
In fs/mbcache.c (ffffffff8140ca2f)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/coredump.c (ffffffff8140ff43)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffffffff81419153)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81420ff7)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/kernfs/inode.c (ffffffff81437890)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/devpts/inode.c (ffffffff81442a1e)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_kill_index
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/balloc.c (ffffffff814436a3)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_should_retry_alloc
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff81448bf0)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff8145995e)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff8145a823)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff814674c9)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff8147953f)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff8147b04b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
```
```
In fs/ext4/mmp.c (ffffffff8147b995)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff8149e35f)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff814b745a)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff814b8d5d)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff814c0b24)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_fc_release_bufs
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
```
```
In fs/ecryptfs/miscdev.c (ffffffff814e2b00)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release
```
```
In fs/fuse/inode.c (ffffffff814f5dd9)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_sync_fs_writes
```
```
In ipc/util.c (ffffffff81502490)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In ipc/msg.c (ffffffff815052fc)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In security/keys/gc.c (ffffffff8151170d)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In security/keys/keyctl.c (ffffffff81517078)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/selinux/avc.c (ffffffff8152a92f)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_flush
  - security/selinux/avc.c:avc_node_replace
```
```
In security/selinux/hooks.c (ffffffff8152bb15)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_dec
```
```
In security/selinux/xfrm.c (ffffffff8154f511)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_state_free
  - security/selinux/xfrm.c:selinux_xfrm_policy_free
```
```
In security/tomoyo/common.c (ffffffff8155cb7f)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff8156361f)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff81564f32)
Location: arch/x86/include/asm/atomic.h:106
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
In security/tomoyo/environ.c (ffffffff81565d11)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff8156775d)
Location: arch/x86/include/asm/atomic.h:106
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
In security/tomoyo/gc.c (ffffffff81567bde)
Location: arch/x86/include/asm/atomic.h:106
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
In security/tomoyo/group.c (ffffffff81568668)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff81568d89)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/network.c (ffffffff81569f3e)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
```
In security/tomoyo/securityfs_if.c (ffffffff8156ad05)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8156ae8f)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_task_free
  - security/tomoyo/tomoyo.c:tomoyo_task_free
  - security/tomoyo/tomoyo.c:tomoyo_bprm_committed_creds
  - security/tomoyo/tomoyo.c:tomoyo_cred_prepare
  - security/tomoyo/tomoyo.c:tomoyo_domain
```
```
In block/blk-flush.c (ffffffff815d0867)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (ffffffff815d1f6a)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - block/blk-ioc.c:exit_io_context
```
```
In block/blk-mq.c (ffffffff815dad45)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:blk_mq_free_request
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-tag.c (ffffffff815de6ac)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-iocost.c (ffffffff815fa095)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (ffffffff81659f43)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_finish_wait
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/pci/pci.c (ffffffff816a3eb3)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81ce8445)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff816deae2)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
```
```
In drivers/acpi/apei/ghes.c (ffffffff81769f22)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_rcu_free
```
```
In drivers/xen/events/events_base.c (ffffffff81795004)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
```
```
In drivers/reset/core.c (ffffffff817b2b1a)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff817bf6da)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
```
In drivers/tty/vt/keyboard.c (ffffffff832f9e53)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff817f047c)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_close
```
```
In drivers/char/agp/backend.c (ffffffff817fd17e)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_release
```
```
In drivers/char/agp/generic.c (ffffffff817fe5b1)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff818015ef)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
```
```
In drivers/connector/cn_queue.c (ffffffff81830472)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffff81830d9b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In drivers/base/dd.c (ffffffff8183b354)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/runtime.c (ffffffff8184bd2c)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:update_autosuspend
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81894023)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:deactivate_labels
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b3893)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_enable_disk_events
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81914507)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
```
```
In drivers/vfio/vfio.c (ffffffff819214e5)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_release
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_add_container_user
  - drivers/vfio/vfio.c:vfio_group_add_container_user
```
```
In drivers/usb/core/hcd.c (ffffffff819416de)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/urb.c (ffffffff8194459f)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
```
```
In drivers/power/supply/power_supply_core.c (ffffffff819dbf12)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (ffffffff819f4874)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/md/md.c:md_release
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffff81a0939b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stats.c (ffffffff81a16135)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stat_for_entry
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81a1ce82)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81a478ca)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d326f3)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/ras/debugfs.c (ffffffff81a6de35)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_release
```
```
In net/core/skbuff.c (ffffffff81a853d9)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In net/core/dev.c (ffffffff81a97e52)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In net/core/neighbour.c (ffffffff81aae141)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_for_each_release
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_alloc
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/core/xdp.c (ffffffff81ad3570)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/core/sock_map.c (ffffffff81b09205)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
```
In net/sched/cls_api.c (ffffffff81b18492)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_cb_destroy
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_cls_offload_cnt_update
```
```
In net/sched/act_api.c (ffffffff81b1d98d)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/sched/act_api.c:__tcf_action_put
  - net/sched/act_api.c:__tcf_action_put
```
```
In net/netlink/af_netlink.c (ffffffff81b24813)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81b55b7b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b57ec2)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81b7eae1)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba5797)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/inet_fragment.c (ffffffff81baeae0)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/fib_rules.c (ffffffff81bbcdc9)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_delete
```
```
In net/ipv4/ipmr.c (ffffffff81bc2520)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd2563)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff81bd8d0a)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
```
```
In net/ipv6/route.c (ffffffff81c03ee2)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81c1db6a)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81c20f7a)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2d01d)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81c33a9c)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81c35e55)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
```
In net/ipv6/ioam6.c (ffffffff81c39ab0)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/ip6mr.c (ffffffff81c3eb24)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81c4b820)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
```
```
In net/packet/af_packet.c (ffffffff81c4f910)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mm_close
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81c602ef)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81c60bab)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81c61d20)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
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
In arch/x86/events/core.c (ffffffff810073d5)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
```
```
In arch/x86/events/intel/core.c (ffffffff8100f997)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_put_event_constraints
  - arch/x86/events/intel/core.c:intel_put_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/events/intel/uncore.c (ffffffff810205b4)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_put_constraint
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81022184)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In arch/x86/xen/spinlock.c (ffffffff8103beaf)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/xen/spinlock.c:xen_qlock_wait
```
```
In arch/x86/kernel/alternative.c (ffffffff81f15541)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8106a113)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_hcpu_update
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8107b960)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_release
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81084008)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff81084aca)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810b85af)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810c0ab5)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In kernel/cpu.c (ffffffff810d0737)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In kernel/async.c (ffffffff81103401)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/core.c (ffffffff8111601f)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:ttwu_do_activate
```
```
In kernel/sched/fair.c (ffffffff8112cab4)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
  - kernel/sched/fair.c:nohz_balance_exit_idle
```
```
In kernel/sched/build_policy.c (ffffffff81136758)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:rq_offline_dl
  - kernel/sched/build_policy.c:rq_offline_rt
```
```
In kernel/sched/build_utility.c (ffffffff81148ef4)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:cpupri_set
```
```
In kernel/power/process.c (ffffffff81152193)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
```
```
In kernel/printk/printk.c (ffffffff8115bc25)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In kernel/irq/spurious.c (ffffffff81165f6c)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/rcu/update.c (ffffffff811745df)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/update.c:rcu_end_inkernel_boot
```
```
In kernel/rcu/srcutree.c (ffffffff81175b28)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier_one_cpu
```
```
In kernel/time/clocksource.c (ffffffff811a0f1d)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/futex/core.c (ffffffff811b32c6)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_q_unlock
  - kernel/futex/core.c:__futex_unqueue
```
```
In kernel/futex/requeue.c (ffffffff811b64bb)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/futex/requeue.c:futex_wait_requeue_pi
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
```
```
In kernel/cgroup/cgroup.c (ffffffff811cb4dc)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811d1aae)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
  - kernel/cgroup/legacy_freezer.c:freezer_css_offline
```
```
In kernel/debug/debug_core.c (ffffffff811f2847)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/watchdog_hld.c (ffffffff81200653)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
```
```
In kernel/trace/ftrace.c (ffffffff8120ba57)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffffffff812174e6)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_record_enable
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:rb_remove_pages
```
```
In kernel/trace/trace.c (ffffffff8122541d)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_set_cpumask
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (ffffffff8122def1)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8122eeac)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:func_prolog_preempt_disable
```
```
In kernel/trace/trace_functions_graph.c (ffffffff81233015)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/fgraph.c (ffffffff812380e5)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:ftrace_suspend_notifier_call
```
```
In kernel/trace/trace_kdb.c (ffffffff81261ec0)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/trace/trace_dynevent.c (ffffffff8126219d)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/trace/trace_dynevent.c:trace_event_dyn_put_ref
```
```
In kernel/bpf/hashtab.c (ffffffff8129f3bf)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/offload.c (ffffffff812be487)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In kernel/events/core.c (ffffffff812dce7f)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:exclusive_event_destroy
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
```
```
In kernel/events/callchain.c (ffffffff812e3e2a)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/uprobes.c (ffffffff812e539e)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/watch_queue.c (ffffffff812ed688)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:free_watch
```
```
In mm/page-writeback.c (ffffffff813008fb)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_end_writeback
```
```
In mm/vmscan.c (ffffffff81310d9e)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_throttle
```
```
In mm/mmap.c (ffffffff81351d62)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mmu_gather.c (ffffffff8135333c)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/rmap.c (ffffffff8135c3f8)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_file_rmap
```
```
In mm/page_alloc.c (ffffffff81371d99)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_contig_migrate_range
```
```
In mm/memory_hotplug.c (ffffffff81f1b9c3)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/swapfile.c (ffffffff813828a1)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffffffff81384109)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff81384c85)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_free_entry
```
```
In mm/mempolicy.c (ffffffff81399f87)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_migrate_pages
```
```
In mm/migrate.c (ffffffff813b5a88)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
```
In mm/huge_memory.c (ffffffff813bbb90)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memcontrol.c (ffffffff813cdf44)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
```
```
In mm/zpool.c (ffffffff813df002)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/zpool.c:zpool_destroy_pool
  - mm/zpool.c:zpool_has_pool
```
```
In mm/secretmem.c (ffffffff813e3355)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_release
```
```
In mm/mapping_dirty_helpers.c (ffffffff813e9a6e)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/open.c (ffffffff813eba27)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff813f38a9)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff81405301)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/namei.c:do_open
```
```
In fs/fs-writeback.c (ffffffff814353db)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/fs-writeback.c:cleanup_offline_cgwb
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/buffer.c (ffffffff814439c5)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/buffer.c:buffer_exit_cpu_dead
  - fs/buffer.c:invalidate_bh_lrus_cpu
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:bh_lru_install
  - fs/buffer.c:__bforget
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/userfaultfd.c (ffffffff8145e346)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/mbcache.c (ffffffff81481ba9)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_or_get
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/coredump.c (ffffffff814858f5)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffffffff8148fb9a)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81498e8d)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/kernfs/inode.c (ffffffff814b2608)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/devpts/inode.c (ffffffff814be7ae)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_kill_index
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/balloc.c (ffffffff814bf504)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_should_retry_alloc
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff814c5a30)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff814d765d)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff814d8573)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff814e70cc)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff814f5b3a)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff814fd49f)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
```
```
In fs/ext4/mmp.c (ffffffff814fde83)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff81524965)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff81540f99)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff815429b8)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff8154b3bc)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_fc_release_bufs
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
```
```
In fs/ecryptfs/miscdev.c (ffffffff81570dea)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release
```
```
In fs/fuse/inode.c (ffffffff81584ba5)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_sync_fs_writes
```
```
In ipc/util.c (ffffffff81593d1b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In ipc/msg.c (ffffffff81596cc9)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In security/keys/gc.c (ffffffff815a39fd)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In security/keys/keyctl.c (ffffffff815a99aa)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/selinux/avc.c (ffffffff815c02f8)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_flush
  - security/selinux/avc.c:avc_node_replace
```
```
In security/selinux/hooks.c (ffffffff815c1825)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_dec
```
```
In security/selinux/xfrm.c (ffffffff815e87e1)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_state_free
  - security/selinux/xfrm.c:selinux_xfrm_policy_free
```
```
In security/tomoyo/common.c (ffffffff815f7c8c)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff815fe757)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff816006ed)
Location: arch/x86/include/asm/atomic.h:106
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
In security/tomoyo/environ.c (ffffffff816015b0)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff81603307)
Location: arch/x86/include/asm/atomic.h:106
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
In security/tomoyo/gc.c (ffffffff816037fe)
Location: arch/x86/include/asm/atomic.h:106
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
In security/tomoyo/group.c (ffffffff816042e4)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff81604aca)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/network.c (ffffffff81605dce)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
```
In security/tomoyo/securityfs_if.c (ffffffff81606d58)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff81606f1f)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_task_free
  - security/tomoyo/tomoyo.c:tomoyo_task_free
  - security/tomoyo/tomoyo.c:tomoyo_bprm_committed_creds
  - security/tomoyo/tomoyo.c:tomoyo_cred_prepare
  - security/tomoyo/tomoyo.c:tomoyo_domain
```
```
In block/blk-mq.c (ffffffff81688561)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/blk-mq.c:blk_mq_dispatch_wake
```
```
In block/blk-iocost.c (ffffffff816ac34f)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In io_uring/io_uring.c (ffffffff81e92c10)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_clean_op
```
```
In io_uring/io-wq.c (ffffffff816da805)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - io_uring/io-wq.c:create_io_worker
  - io_uring/io-wq.c:create_worker_cont
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:create_worker_cb
  - io_uring/io-wq.c:io_worker_cancel_cb
```
```
In lib/sbitmap.c (ffffffff81772673)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_finish_wait
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/pci/pci.c (ffffffff817c6267)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81eaf4c5)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff81816002)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
```
```
In drivers/acpi/apei/ghes.c (ffffffff8189f298)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_rcu_free
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
```
```
In drivers/xen/events/events_base.c (ffffffff818cdcbc)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
```
```
In drivers/reset/core.c (ffffffff818ee50a)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_reset
```
```
In drivers/tty/tty_buffer.c (ffffffff818fbbfa)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
```
In drivers/tty/vt/keyboard.c (ffffffff834b26b7)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81930859)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_close
```
```
In drivers/char/agp/backend.c (ffffffff8193c0ce)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_release
```
```
In drivers/char/agp/generic.c (ffffffff8193db6e)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81940c4a)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
```
```
In drivers/connector/cn_queue.c (ffffffff8197173e)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffff819721f9)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In drivers/base/dd.c (ffffffff8197d8e4)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/runtime.c (ffffffff8199166b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:update_autosuspend
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff819ddf03)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:deactivate_labels
```
```
In drivers/cxl/core/suspend.c (ffffffff819f63a5)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/cxl/core/suspend.c:cxl_mem_active_dec
```
```
In drivers/scsi/scsi_lib.c (ffffffff819fea43)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_enable_disk_events
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a67ef5)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
```
```
In drivers/usb/core/hcd.c (ffffffff81a99e81)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/urb.c (ffffffff81a9ccef)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81b3fa12)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (ffffffff81b5d803)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/md/md.c:md_release
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffff81b72c13)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stats.c (ffffffff81b7f4bf)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stat_for_entry
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81b85f69)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81bb5849)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81efebdd)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/ras/debugfs.c (ffffffff81bdec95)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_release
```
```
In drivers/hte/hte.c (ffffffff81be4b45)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/hte/hte.c:hte_ts_put
```
```
In net/core/skbuff.c (ffffffff81bfb4b9)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In net/core/dev.c (ffffffff81c0f830)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In net/core/neighbour.c (ffffffff81c28769)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_alloc
  - net/core/neighbour.c:neigh_mark_dead
```
```
In net/core/xdp.c (ffffffff81c50e2b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In net/core/sock_map.c (ffffffff81c8f295)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
```
In net/sched/cls_api.c (ffffffff81c9f205)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_cb_destroy
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_cls_offload_cnt_update
```
```
In net/sched/act_api.c (ffffffff81ca56be)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/sched/act_api.c:__tcf_action_put
  - net/sched/act_api.c:__tcf_action_put
```
```
In net/netlink/af_netlink.c (ffffffff81cadeb6)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce5ed3)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81d0f317)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/fib_semantics.c (ffffffff81d38143)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/inet_fragment.c (ffffffff81d41dcf)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In net/ipv4/fib_rules.c (ffffffff81d51439)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_delete
```
```
In net/ipv4/ipmr.c (ffffffff81d572cc)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d68275)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff81d6f7e8)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
```
```
In net/ipv6/udp.c (ffffffff81dba189)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81dbdd3a)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dca400)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81dd1314)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81dd38d5)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
```
In net/ipv6/ioam6.c (ffffffff81dd77df)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81ddd61e)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:mif6_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81deb1fb)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81df0380)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mm_close
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81e0289b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81e030ec)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81e0435a)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
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
In arch/x86/events/core.c (ffffffff81008c55)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
```
```
In arch/x86/events/intel/core.c (ffffffff810133c7)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_put_event_constraints
  - arch/x86/events/intel/core.c:intel_put_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/events/intel/uncore.c (ffffffff81024ed4)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_put_constraint
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81026d44)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In arch/x86/xen/spinlock.c (ffffffff8104473f)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/xen/spinlock.c:xen_qlock_wait
```
```
In arch/x86/kernel/alternative.c (ffffffff820bca17)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81079ec3)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_hcpu_update
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108cd50)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_release
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81096e98)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff81097e9e)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810d3e2f)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810dcc35)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In kernel/cpu.c (ffffffff810ef017)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In kernel/async.c (ffffffff81128a91)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/core.c (ffffffff8113d4b6)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:ttwu_do_activate
```
```
In kernel/sched/fair.c (ffffffff811567a4)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
  - kernel/sched/fair.c:nohz_balance_exit_idle
```
```
In kernel/sched/build_policy.c (ffffffff81160d88)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:rq_offline_dl
  - kernel/sched/build_policy.c:rq_offline_rt
```
```
In kernel/sched/build_utility.c (ffffffff81177794)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:cpupri_set
```
```
In kernel/printk/printk.c (ffffffff8118e645)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In kernel/irq/spurious.c (ffffffff8119a05c)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/rcu/update.c (ffffffff811ac005)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_end_inkernel_boot
```
```
In kernel/rcu/srcutree.c (ffffffff811ac9b8)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier_one_cpu
```
```
In kernel/time/clocksource.c (ffffffff811e07d6)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/futex/core.c (ffffffff811f4206)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_q_unlock
  - kernel/futex/core.c:__futex_unqueue
```
```
In kernel/futex/requeue.c (ffffffff811f75fb)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/futex/requeue.c:futex_wait_requeue_pi
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
```
```
In kernel/cgroup/cgroup.c (ffffffff8120e93c)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/debug/debug_core.c (ffffffff81239607)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/watchdog_hld.c (ffffffff81248333)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
```
```
In kernel/trace/ftrace.c (ffffffff812544a6)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffffffff8126092a)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_record_enable
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:rb_remove_pages
```
```
In kernel/trace/trace.c (ffffffff8127065c)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_set_cpumask
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (ffffffff81279d91)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8127aece)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:func_prolog_preempt_disable
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8127f7a5)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/fgraph.c (ffffffff81284e95)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:ftrace_suspend_notifier_call
```
```
In kernel/trace/trace_kdb.c (ffffffff812b35d3)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/trace/trace_dynevent.c (ffffffff812b393d)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/trace/trace_dynevent.c:trace_event_dyn_put_ref
```
```
In kernel/bpf/hashtab.c (ffffffff812f8857)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In kernel/bpf/offload.c (ffffffff8132181c)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In kernel/events/core.c (ffffffff81343c12)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:exclusive_event_destroy
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
```
```
In kernel/events/callchain.c (ffffffff8134c53a)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/hw_breakpoint.c (ffffffff8134da13)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff8134ed4e)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/watch_queue.c (ffffffff81357a58)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:free_watch
```
```
In mm/page-writeback.c (ffffffff8136b1d5)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_end_writeback
```
```
In mm/vmscan.c (ffffffff81384279)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_throttle
```
```
In mm/mmap.c (ffffffff813cb949)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_expand
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mmu_gather.c (ffffffff813cd5fc)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/rmap.c (ffffffff813d8137)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_rmap
```
```
In mm/page_alloc.c (ffffffff813ef579)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_contig_migrate_range
```
```
In mm/memory_hotplug.c (ffffffff820c3953)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/swapfile.c (ffffffff813fc847)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffffffff81401c0c)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff81402945)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_free_entry
```
```
In mm/mempolicy.c (ffffffff81419fb5)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_migrate_pages
```
```
In mm/migrate.c (ffffffff81435b88)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
```
In mm/memcontrol.c (ffffffff81453027)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
```
```
In mm/zpool.c (ffffffff81465d42)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/zpool.c:zpool_destroy_pool
  - mm/zpool.c:zpool_create_pool
  - mm/zpool.c:zpool_has_pool
```
```
In mm/secretmem.c (ffffffff8146ace5)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_release
```
```
In mm/mapping_dirty_helpers.c (ffffffff81471aae)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/open.c (ffffffff81473f58)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff8147c663)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff8148f751)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/namei.c:do_open
```
```
In fs/fs-writeback.c (ffffffff814c343b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/fs-writeback.c:cleanup_offline_cgwb
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/buffer.c (ffffffff814d2f15)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/buffer.c:buffer_exit_cpu_dead
  - fs/buffer.c:invalidate_bh_lrus_cpu
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:bh_lru_install
  - fs/buffer.c:__bforget
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/userfaultfd.c (ffffffff814edfd7)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/coredump.c (ffffffff815190ba)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffffffff815236aa)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8152d1fc)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/kernfs/inode.c (ffffffff81549188)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/devpts/inode.c (ffffffff8155663e)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_kill_index
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/balloc.c (ffffffff81557464)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_should_retry_alloc
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8155dfb0)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff815703d4)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff8157133e)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff81580a8e)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff8158fdda)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff81597c6b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
```
```
In fs/ext4/mmp.c (ffffffff81598674)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff815c1dda)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff815dfa47)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff815e16c4)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff815eb060)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_fc_release_bufs
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
```
```
In fs/ecryptfs/miscdev.c (ffffffff81615efa)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release
```
```
In fs/fuse/inode.c (ffffffff8162ad15)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_sync_fs_writes
```
```
In ipc/util.c (ffffffff8163c6c1)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In security/keys/gc.c (ffffffff8164d68d)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In security/keys/keyctl.c (ffffffff81653c0a)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/selinux/avc.c (ffffffff8166c838)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_flush
  - security/selinux/avc.c:avc_node_replace
```
```
In security/selinux/hooks.c (ffffffff8166de35)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_dec
```
```
In security/selinux/xfrm.c (ffffffff81697ff1)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_state_free
  - security/selinux/xfrm.c:selinux_xfrm_policy_free
```
```
In security/tomoyo/common.c (ffffffff816a88ac)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff816af5d7)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff816b162d)
Location: arch/x86/include/asm/atomic.h:106
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
In security/tomoyo/environ.c (ffffffff816b2560)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff816b4497)
Location: arch/x86/include/asm/atomic.h:106
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
In security/tomoyo/gc.c (ffffffff816b49be)
Location: arch/x86/include/asm/atomic.h:106
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
In security/tomoyo/group.c (ffffffff816b5514)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff816b5dca)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/network.c (ffffffff816b71de)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
```
In security/tomoyo/securityfs_if.c (ffffffff816b8298)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff816b84af)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_task_free
  - security/tomoyo/tomoyo.c:tomoyo_task_free
  - security/tomoyo/tomoyo.c:tomoyo_bprm_committed_creds
  - security/tomoyo/tomoyo.c:tomoyo_cred_prepare
  - security/tomoyo/tomoyo.c:tomoyo_domain
```
```
In block/blk-mq.c (ffffffff81746a15)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/blk-mq.c:blk_mq_dispatch_wake
```
```
In block/blk-iocost.c (ffffffff8176b339)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In io_uring/io_uring.c (ffffffff81792798)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_clean_op
  - io_uring/io_uring.c:io_eventfd_signal
```
```
In io_uring/io-wq.c (ffffffff817a68f5)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - io_uring/io-wq.c:create_io_worker
  - io_uring/io-wq.c:create_worker_cont
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:create_worker_cb
  - io_uring/io-wq.c:io_worker_cancel_cb
```
```
In lib/sbitmap.c (ffffffff818a2ecf)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_finish_wait
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/pci/pci.c (ffffffff818e35c7)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8190cc92)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff81945262)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
```
```
In drivers/acpi/apei/ghes.c (ffffffff819e72b8)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_rcu_free
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
```
```
In drivers/xen/events/events_base.c (ffffffff81a1f2dc)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
```
```
In drivers/reset/core.c (ffffffff81a4611a)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_reset
```
```
In drivers/tty/tty_buffer.c (ffffffff81a55004)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
```
In drivers/tty/vt/keyboard.c (ffffffff83eecd4a)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81a8ed59)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_close
```
```
In drivers/char/agp/backend.c (ffffffff81a9c96e)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_release
```
```
In drivers/char/agp/generic.c (ffffffff81a9ea9e)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81aa2c9a)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
```
```
In drivers/connector/cn_queue.c (ffffffff81adc93e)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffff81add4a9)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In drivers/base/dd.c (ffffffff81aead94)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/runtime.c (ffffffff81b01a3b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:update_autosuspend
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81b597e3)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:deactivate_labels
```
```
In drivers/cxl/core/suspend.c (ffffffff81b739a5)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/cxl/core/suspend.c:cxl_mem_active_dec
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b7d043)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_enable_disk_events
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfbad5)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff81c1e3d4)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/urb.c (ffffffff81c21d0f)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81cd5f82)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (ffffffff81cf7493)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/md/md.c:md_release
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffff81d0fa0f)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stats.c (ffffffff81d1cd8f)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stat_for_entry
```
```
In drivers/md/dm-io-rewind.c (ffffffff81d1fe48)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/md/dm-io-rewind.c:dm_io_rewind
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81d252e9)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81d5a089)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d7855d)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/ras/debugfs.c (ffffffff81d8a125)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_release
```
```
In drivers/hte/hte.c (ffffffff81d90c04)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - drivers/hte/hte.c:hte_ts_put
```
```
In net/core/skbuff.c (ffffffff81daa1e9)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In net/core/dev.c (ffffffff81dbf43a)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In net/core/neighbour.c (ffffffff81ddb381)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_alloc
  - net/core/neighbour.c:neigh_mark_dead
```
```
In net/core/xdp.c (ffffffff81e06511)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In net/core/sock_map.c (ffffffff81e4a4f5)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_alloc_elem
  - net/core/sock_map.c:sock_hash_alloc_elem
  - net/core/sock_map.c:sock_hash_delete_elem
```
```
In net/sched/cls_api.c (ffffffff81e5eca5)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_cb_destroy
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_cls_offload_cnt_update
```
```
In net/sched/act_api.c (ffffffff81e621ce)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/sched/act_api.c:__tcf_action_put
  - net/sched/act_api.c:__tcf_action_put
```
```
In net/netlink/af_netlink.c (ffffffff81e6b4ee)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea9113)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ed4e77)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/fib_semantics.c (ffffffff81f009a3)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0ac4e)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In net/ipv4/fib_rules.c (ffffffff81f1b2a9)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_delete
```
```
In net/ipv4/ipmr.c (ffffffff81f20969)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f3334a)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff81f3af88)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
```
```
In net/ipv6/udp.c (ffffffff81f8a239)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81f8e24a)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9b360)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81fa290d)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81fa4eb5)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
```
In net/ipv6/ioam6.c (ffffffff81fa91fe)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81faf7be)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:mif6_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81fbee41)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81fc44cd)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mm_close
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81fd778b)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81fd804c)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81fd933a)
Location: arch/x86/include/asm/atomic.h:106
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
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
In arch/x86/events/core.c (ffffffff81008485)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
```
```
In arch/x86/events/intel/core.c (ffffffff81012a57)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_put_event_constraints
  - arch/x86/events/intel/core.c:intel_put_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/events/intel/uncore.c (ffffffff81024dd4)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_put_constraint
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81026d24)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In arch/x86/xen/spinlock.c (ffffffff8104487f)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - arch/x86/xen/spinlock.c:xen_qlock_wait
```
```
In arch/x86/kernel/alternative.c (ffffffff8213e287)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8107c173)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_hcpu_update
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108fea0)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81099f7c)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff8109af47)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810d720f)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810e8215)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In kernel/cpu.c (ffffffff810fafc7)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In kernel/async.c (ffffffff81135f41)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/core.c (ffffffff81150ff8)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:ttwu_do_activate
```
```
In kernel/sched/fair.c (ffffffff81166824)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/build_policy.c (ffffffff811714d8)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:rq_offline_dl
  - kernel/sched/build_policy.c:rq_offline_rt
```
```
In kernel/sched/build_utility.c (ffffffff811883e6)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:cpupri_set
```
```
In kernel/printk/printk.c (ffffffff8119ffa5)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In kernel/irq/spurious.c (ffffffff811abc19)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/rcu/update.c (ffffffff811bdf25)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_end_inkernel_boot
```
```
In kernel/rcu/srcutree.c (ffffffff811be830)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier_one_cpu
```
```
In kernel/time/clocksource.c (ffffffff811f4cda)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/futex/core.c (ffffffff81208996)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_q_unlock
  - kernel/futex/core.c:__futex_unqueue
```
```
In kernel/futex/requeue.c (ffffffff8120bd95)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/futex/requeue.c:futex_wait_requeue_pi
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
```
```
In kernel/cgroup/cgroup.c (ffffffff8122433c)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/debug/debug_core.c (ffffffff81250617)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/watchdog_perf.c (ffffffff8125f64e)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/watchdog_perf.c:watchdog_hardlockup_disable
```
```
In kernel/trace/ftrace.c (ffffffff8126b396)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffffffff812778fa)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_record_enable
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:rb_remove_pages
```
```
In kernel/trace/trace.c (ffffffff812878d3)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_set_cpumask
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (ffffffff812917d1)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff812929ee)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:func_prolog_preempt_disable
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8129c335)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/fgraph.c (ffffffff812a1b2e)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:ftrace_suspend_notifier_call
```
```
In kernel/trace/trace_kdb.c (ffffffff812d5ea3)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/trace/trace_dynevent.c (ffffffff812d620d)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/trace/trace_dynevent.c:trace_event_dyn_put_ref
```
```
In kernel/bpf/hashtab.c (ffffffff81326957)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In kernel/bpf/devmap.c (ffffffff8134d9d2)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_delete_elem
```
```
In kernel/bpf/offload.c (ffffffff813518fc)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In kernel/events/core.c (ffffffff81374c9b)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:exclusive_event_destroy
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
```
```
In kernel/events/callchain.c (ffffffff8137d58a)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/hw_breakpoint.c (ffffffff8137e68c)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff8137feee)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/watch_queue.c (ffffffff813892ba)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:free_watch
```
```
In mm/page-writeback.c (ffffffff8139d352)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_end_writeback
```
```
In mm/vmscan.c (ffffffff813b5d17)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_throttle
```
```
In mm/mmap.c (ffffffff81400166)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_complete
  - mm/mmap.c:vma_complete
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mmu_gather.c (ffffffff81401f5c)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/rmap.c (ffffffff8140ca58)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_rmap
```
```
In mm/page_alloc.c (ffffffff814230e9)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_contig_migrate_range
```
```
In mm/memory_hotplug.c (ffffffff82147735)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/swapfile.c (ffffffff8142fc54)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffffffff81434b9c)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff81435e05)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_free_entry
```
```
In mm/mempolicy.c (ffffffff8144d33b)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_migrate_pages
```
```
In mm/migrate.c (ffffffff8146b869)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
```
In mm/memcontrol.c (ffffffff81488c7d)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
```
```
In mm/zpool.c (ffffffff8149b7b2)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - mm/zpool.c:zpool_destroy_pool
  - mm/zpool.c:zpool_create_pool
  - mm/zpool.c:zpool_has_pool
```
```
In mm/secretmem.c (ffffffff8149fb75)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_release
```
```
In mm/mapping_dirty_helpers.c (ffffffff814a63fd)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/open.c (ffffffff814a879b)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff814b1224)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff814c1f3d)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - fs/namei.c:do_open
```
```
In fs/fs-writeback.c (ffffffff814f881b)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - fs/fs-writeback.c:cleanup_offline_cgwb
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/buffer.c (ffffffff81509922)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - fs/buffer.c:buffer_exit_cpu_dead
  - fs/buffer.c:invalidate_bh_lrus_cpu
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:bh_lru_install
  - fs/buffer.c:__bforget
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/userfaultfd.c (ffffffff815244ba)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/coredump.c (ffffffff815509b8)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffffffff8155b269)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - fs/quota/dquot.c:quota_release_workfn
  - fs/quota/dquot.c:quota_release_workfn
```
```
In fs/proc/task_mmu.c (ffffffff81564f2a)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/kernfs/inode.c (ffffffff81580d6b)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/devpts/inode.c (ffffffff8158e3fe)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_kill_index
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/balloc.c (ffffffff8158f2e4)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_should_retry_alloc
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff81595dcc)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff815a82b9)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff815a90b1)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff815b803e)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff815c724c)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff815ce6d4)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
```
```
In fs/ext4/mmp.c (ffffffff815cf143)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff815f955a)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff8161751b)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81618ece)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff81622ad0)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_fc_release_bufs
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
```
```
In fs/ecryptfs/miscdev.c (ffffffff8164df8a)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release
```
```
In fs/fuse/inode.c (ffffffff81662f35)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_sync_fs_writes
```
```
In ipc/util.c (ffffffff81674e28)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In security/keys/gc.c (ffffffff81685e2d)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In security/keys/keyctl.c (ffffffff8168c4c2)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/selinux/avc.c (ffffffff816a507f)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_compute_av
  - security/selinux/avc.c:avc_ss_reset
  - security/selinux/avc.c:avc_node_replace
```
```
In security/selinux/hooks.c (ffffffff816a6505)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_dec
```
```
In security/selinux/xfrm.c (ffffffff816d04d1)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_state_free
  - security/selinux/xfrm.c:selinux_xfrm_policy_free
```
```
In security/tomoyo/common.c (ffffffff816e12ec)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff816e7ff8)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff816ea03d)
Location: arch/x86/include/asm/atomic.h:58
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
In security/tomoyo/environ.c (ffffffff816eaf50)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff816ece57)
Location: arch/x86/include/asm/atomic.h:58
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
In security/tomoyo/gc.c (ffffffff816ed482)
Location: arch/x86/include/asm/atomic.h:58
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
In security/tomoyo/group.c (ffffffff816edef4)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff816ee7da)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/network.c (ffffffff816efbbe)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
```
In security/tomoyo/securityfs_if.c (ffffffff816f0c68)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff816f0e7f)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_task_free
  - security/tomoyo/tomoyo.c:tomoyo_task_free
  - security/tomoyo/tomoyo.c:tomoyo_bprm_committed_creds
  - security/tomoyo/tomoyo.c:tomoyo_cred_prepare
  - security/tomoyo/tomoyo.c:tomoyo_domain
```
```
In block/blk-mq.c (ffffffff81783c75)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/blk-mq.c:blk_mq_dispatch_wake
```
```
In block/blk-iocost.c (ffffffff817aa419)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In io_uring/io_uring.c (ffffffff817d350c)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_eventfd_signal
  - io_uring/io_uring.c:io_clean_op
```
```
In io_uring/io-wq.c (ffffffff817e7868)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - io_uring/io-wq.c:create_io_worker
  - io_uring/io-wq.c:create_worker_cont
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:create_worker_cb
  - io_uring/io-wq.c:io_worker_cancel_cb
```
```
In lib/sbitmap.c (ffffffff818e53bf)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_finish_wait
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/pci/pci.c (ffffffff81926a17)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81950312)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff819898a2)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a2f9c8)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_rcu_free
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
```
```
In drivers/xen/events/events_base.c (ffffffff81a68488)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
```
```
In drivers/reset/core.c (ffffffff81a902ca)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_reset
```
```
In drivers/tty/tty_buffer.c (ffffffff81a9f5e4)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
```
In drivers/tty/vt/keyboard.c (ffffffff83712a0a)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81ada509)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_close
```
```
In drivers/char/agp/backend.c (ffffffff81ae82ce)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_release
```
```
In drivers/char/agp/generic.c (ffffffff81aea414)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81aee56a)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
```
```
In drivers/connector/cn_queue.c (ffffffff81b2abae)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffff81b2b719)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In drivers/base/dd.c (ffffffff81b39094)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/runtime.c (ffffffff81b4fb65)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:update_autosuspend
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81bacd43)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:deactivate_labels
```
```
In drivers/cxl/core/suspend.c (ffffffff81bc7115)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/cxl/core/suspend.c:cxl_mem_active_dec
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd0dc3)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_enable_disk_events
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c61065)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff81c852c4)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/urb.c (ffffffff81c88c8f)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81d3df82)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (ffffffff81d5ed93)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/md/md.c:md_release
```
```
In drivers/md/dm.c (ffffffff81d78e2d)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stats.c (ffffffff81d85faf)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stat_for_entry
```
```
In drivers/md/dm-io-rewind.c (ffffffff81d8903a)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/md/dm-io-rewind.c:dm_io_rewind
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81d8e528)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81dc4a29)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de649d)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/ras/debugfs.c (ffffffff81df8725)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_release
```
```
In drivers/hte/hte.c (ffffffff81dfee95)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/hte/hte.c:hte_ts_put
```
```
In net/core/skbuff.c (ffffffff81e18f89)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In net/core/dev.c (ffffffff81e2f0ea)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In net/core/neighbour.c (ffffffff81e4be56)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_alloc
  - net/core/neighbour.c:neigh_mark_dead
```
```
In net/core/xdp.c (ffffffff81e78db0)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In net/core/sock_map.c (ffffffff81ea5c05)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_alloc_elem
  - net/core/sock_map.c:sock_hash_alloc_elem
  - net/core/sock_map.c:sock_hash_delete_elem
```
```
In net/sched/cls_api.c (ffffffff81eb73a5)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_cb_destroy
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_cls_offload_cnt_update
```
```
In net/sched/act_api.c (ffffffff81ebdb1e)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - net/sched/act_api.c:__tcf_action_put
  - net/sched/act_api.c:__tcf_action_put
```
```
In net/netlink/af_netlink.c (ffffffff81ec7533)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f079a3)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81f33b62)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/fib_semantics.c (ffffffff81f60423)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6a79a)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In net/ipv4/fib_rules.c (ffffffff81f7af19)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_delete
```
```
In net/ipv4/ipmr.c (ffffffff81f81189)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f926e6)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff81f9a9a8)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
```
```
In net/ipv6/udp.c (ffffffff81fe9e78)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81feea30)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffc767)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff820031b0)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff82005775)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
```
In net/ipv6/ioam6.c (ffffffff82009b9a)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff8200ff5e)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:mif6_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff8201fa68)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In net/packet/af_packet.c (ffffffff82025500)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mm_close
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff8205347a)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff82053d3c)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
```
```
In net/netlabel/netlabel_calipso.c (ffffffff8205500a)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
```
In net/xdp/xskmap.c (ffffffff8206d174)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_sock_delete
```
```
In net/handshake/request.c (ffffffff82092d9c)
Location: arch/x86/include/asm/atomic.h:58
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
In arch/x86/events/core.c (ffffffff8100dba5)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
```
```
In arch/x86/events/intel/core.c (ffffffff81018377)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_put_event_constraints
  - arch/x86/events/intel/core.c:intel_put_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/events/intel/uncore.c (ffffffff8102af34)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_put_constraint
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8102ce84)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In arch/x86/xen/spinlock.c (ffffffff8104adaf)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - arch/x86/xen/spinlock.c:xen_qlock_wait
```
```
In arch/x86/kernel/alternative.c (ffffffff82220277)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81097230)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff810a17ac)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff810a2625)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810dfa6f)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810f03a5)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In kernel/cpu.c (ffffffff81104467)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In kernel/async.c (ffffffff811410f1)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/core.c (ffffffff8115cd8a)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:ttwu_do_activate
```
```
In kernel/sched/fair.c (ffffffff81173564)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/build_policy.c (ffffffff8117ede8)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:rq_offline_dl
  - kernel/sched/build_policy.c:rq_offline_rt
  - kernel/sched/build_policy.c:pick_next_task_rt
  - kernel/sched/build_policy.c:dequeue_task_rt
```
```
In kernel/sched/build_utility.c (ffffffff81196cc6)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:cpupri_set
```
```
In kernel/printk/printk.c (ffffffff811af005)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In kernel/irq/spurious.c (ffffffff811bb819)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/rcu/update.c (ffffffff811ce445)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_end_inkernel_boot
  - kernel/rcu/update.c:rcu_end_inkernel_boot
```
```
In kernel/rcu/srcutree.c (ffffffff811ced50)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier_one_cpu
```
```
In kernel/rcu/tree.c (ffffffff811d2110)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_nocb_bypass_lock
  - kernel/rcu/tree.c:param_set_do_rcu_barrier
```
```
In kernel/time/clocksource.c (ffffffff8120ae31)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/futex/core.c (ffffffff8121f826)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_q_unlock
  - kernel/futex/core.c:__futex_unqueue
```
```
In kernel/futex/requeue.c (ffffffff8122332a)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/futex/requeue.c:futex_wait_requeue_pi
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
```
```
In kernel/cgroup/cgroup.c (ffffffff8123c02c)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/debug/debug_core.c (ffffffff8126a467)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/watchdog_perf.c (ffffffff8127965e)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/watchdog_perf.c:watchdog_hardlockup_disable
```
```
In kernel/trace/ftrace.c (ffffffff81285846)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffffffff812905c9)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_subbuf_order_set
  - kernel/trace/ring_buffer.c:ring_buffer_subbuf_order_set
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_record_enable
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:rb_remove_pages
```
```
In kernel/trace/trace.c (ffffffff812a2be3)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_set_cpumask
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (ffffffff812acde1)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff812ae0d7)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:func_prolog_preempt_disable
```
```
In kernel/trace/trace_functions_graph.c (ffffffff812b7a15)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/fgraph.c (ffffffff812bd25e)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:ftrace_suspend_notifier_call
```
```
In kernel/trace/trace_kdb.c (ffffffff812f39b3)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/trace/trace_dynevent.c (ffffffff812f3d1d)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/trace/trace_dynevent.c:trace_event_dyn_put_ref
```
```
In kernel/bpf/hashtab.c (ffffffff8134afa2)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In kernel/bpf/devmap.c (ffffffff81374ef2)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_delete_elem
```
```
In kernel/bpf/offload.c (ffffffff81378ddc)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In kernel/events/core.c (ffffffff8139dfcb)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:exclusive_event_destroy
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:unaccount_event
```
```
In kernel/events/callchain.c (ffffffff813a67ea)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/hw_breakpoint.c (ffffffff813a78ec)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff813a916e)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/watch_queue.c (ffffffff813b2d0c)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:free_watch
```
```
In mm/page-writeback.c (ffffffff813c70ee)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_end_writeback
```
```
In mm/vmscan.c (ffffffff813debd7)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_throttle
```
```
In mm/mmap.c (ffffffff8142c786)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_complete
  - mm/mmap.c:vma_complete
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mmu_gather.c (ffffffff8142e5ac)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/rmap.c (ffffffff8143a464)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (ffffffff81450019)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_contig_migrate_range
```
```
In mm/memory_hotplug.c (ffffffff82229f6d)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/swapfile.c (ffffffff8146973f)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/zswap.c (ffffffff8146f8d6)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_free_entry
```
```
In mm/hugetlb.c (ffffffff8147daff)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/mempolicy.c (ffffffff81486e10)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_migrate_pages
```
```
In mm/migrate.c (ffffffff8149a844)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
```
In mm/memcontrol.c (ffffffff814b82fd)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
```
```
In mm/zpool.c (ffffffff814caeb2)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - mm/zpool.c:zpool_destroy_pool
  - mm/zpool.c:zpool_create_pool
  - mm/zpool.c:zpool_has_pool
```
```
In mm/secretmem.c (ffffffff814cf2c5)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_release
```
```
In mm/mapping_dirty_helpers.c (ffffffff814d734d)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/open.c (ffffffff814d9878)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff814e2a5b)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff814f43fd)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - fs/namei.c:do_open
```
```
In fs/fs-writeback.c (ffffffff8152d019)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - fs/fs-writeback.c:cleanup_offline_cgwb
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/buffer.c (ffffffff8153e752)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - fs/buffer.c:buffer_exit_cpu_dead
  - fs/buffer.c:invalidate_bh_lrus_cpu
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:bh_lru_install
  - fs/buffer.c:__bforget
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/userfaultfd.c (ffffffff81558ce5)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/coredump.c (ffffffff81586849)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffffffff8159224b)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8159b9e9)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/kernfs/inode.c (ffffffff815b97e7)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/devpts/inode.c (ffffffff815c712e)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_kill_index
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/balloc.c (ffffffff815c7ff4)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_should_retry_alloc
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff815cea7c)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff815e1076)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff815e2310)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff815f0dde)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff81604bc2)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff81606f54)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
```
```
In fs/ext4/mmp.c (ffffffff816079db)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff816320ea)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff8165033a)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81651d8d)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff8165bb2f)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_fc_release_bufs
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
```
```
In fs/ecryptfs/miscdev.c (ffffffff816874ea)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release
```
```
In fs/fuse/inode.c (ffffffff8169caa4)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_sync_fs_writes
```
```
In ipc/util.c (ffffffff816b11e8)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In security/keys/gc.c (ffffffff816c224d)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In security/keys/keyctl.c (ffffffff816c89c2)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/selinux/avc.c (ffffffff816e1ad3)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_compute_av
  - security/selinux/avc.c:avc_ss_reset
  - security/selinux/avc.c:avc_node_replace
```
```
In security/selinux/hooks.c (ffffffff816e2fc5)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_dec
```
```
In security/selinux/xfrm.c (ffffffff8170caf1)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_state_free
  - security/selinux/xfrm.c:selinux_xfrm_policy_free
```
```
In security/tomoyo/common.c (ffffffff8171df6c)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff81724d08)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff81726d4d)
Location: arch/x86/include/asm/atomic.h:58
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
In security/tomoyo/environ.c (ffffffff81727d20)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff81729c27)
Location: arch/x86/include/asm/atomic.h:58
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
In security/tomoyo/gc.c (ffffffff8172a252)
Location: arch/x86/include/asm/atomic.h:58
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
In security/tomoyo/group.c (ffffffff8172acc4)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff8172b5aa)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/network.c (ffffffff8172c98e)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
```
In security/tomoyo/securityfs_if.c (ffffffff8172da38)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8172dc4f)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_task_free
  - security/tomoyo/tomoyo.c:tomoyo_task_free
  - security/tomoyo/tomoyo.c:tomoyo_bprm_committed_creds
  - security/tomoyo/tomoyo.c:tomoyo_cred_prepare
  - security/tomoyo/tomoyo.c:tomoyo_domain
```
```
In block/bdev.c (ffffffff817a84c3)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - block/bdev.c:bdev_freeze
```
```
In block/blk-mq.c (ffffffff817c5fbc)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/blk-mq.c:blk_mq_dispatch_wake
```
```
In block/blk-iocost.c (ffffffff817ee0f5)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In io_uring/io_uring.c (ffffffff8181731c)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_eventfd_signal
  - io_uring/io_uring.c:io_clean_op
```
```
In io_uring/io-wq.c (ffffffff8182d676)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - io_uring/io-wq.c:create_io_worker
  - io_uring/io-wq.c:create_worker_cont
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:create_worker_cb
  - io_uring/io-wq.c:io_worker_cancel_cb
```
```
In lib/sbitmap.c (ffffffff8192c3bf)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_finish_wait
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/pci/pci.c (ffffffff8196f1b7)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81999742)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff819d37b2)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a7ad08)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_rcu_free
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
```
```
In drivers/xen/events/events_base.c (ffffffff81ab9a04)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
```
```
In drivers/reset/core.c (ffffffff81ae2d0a)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_reset
```
```
In drivers/tty/tty_buffer.c (ffffffff81af1fe1)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
```
In drivers/tty/vt/keyboard.c (ffffffff8394642a)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81b2d809)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_close
```
```
In drivers/char/agp/backend.c (ffffffff81b3b73e)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_release
```
```
In drivers/char/agp/generic.c (ffffffff81b3d8a4)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81b41aaa)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
```
```
In drivers/connector/cn_queue.c (ffffffff81b81e5e)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffff81b82c75)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In drivers/base/dd.c (ffffffff81b90b54)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/runtime.c (ffffffff81ba80e5)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:update_autosuspend
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81c01083)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:deactivate_labels
```
```
In drivers/cxl/core/suspend.c (ffffffff81c1bc85)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/cxl/core/suspend.c:cxl_mem_active_dec
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c25a33)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_enable_disk_events
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
```
```
In drivers/gpu/drm/drm_file.c (ffffffff81c97c4e)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_file.c:drm_open
```
```
In drivers/gpu/drm/drm_vblank.c (ffffffff81cb528b)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_vblank_on
  - drivers/gpu/drm/drm_vblank.c:drm_vblank_get
  - drivers/gpu/drm/drm_vblank.c:drm_vblank_enable
```
```
In drivers/accel/drm_accel.c (ffffffff81cbcce6)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/accel/drm_accel.c:accel_open
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d17a35)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff81d39cc4)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/urb.c (ffffffff81d3d6df)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81df48d2)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (ffffffff81e15ad3)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/md/md.c:md_release
```
```
In drivers/md/dm.c (ffffffff81e2ffbe)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stats.c (ffffffff81e3d6ef)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stat_for_entry
```
```
In drivers/md/dm-io-rewind.c (ffffffff81e4077a)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/md/dm-io-rewind.c:dm_io_rewind
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81e45e3c)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81e7d309)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e9c67d)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/ras/debugfs.c (ffffffff81eaee35)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_release
```
```
In drivers/hte/hte.c (ffffffff81eb6185)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - drivers/hte/hte.c:hte_ts_put
```
```
In net/core/skbuff.c (ffffffff81ed6419)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In net/core/dev.c (ffffffff81eedd6a)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In net/core/neighbour.c (ffffffff81f0ab66)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_alloc
  - net/core/neighbour.c:neigh_mark_dead
```
```
In net/core/xdp.c (ffffffff81f38c80)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In net/core/sock_map.c (ffffffff81f686c5)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_alloc_elem
  - net/core/sock_map.c:sock_hash_alloc_elem
  - net/core/sock_map.c:sock_hash_delete_elem
```
```
In net/sched/cls_api.c (ffffffff81f7a15b)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_cb_destroy
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_cls_offload_cnt_update
```
```
In net/sched/act_api.c (ffffffff81f80c0e)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - net/sched/act_api.c:__tcf_action_put
  - net/sched/act_api.c:__tcf_action_put
```
```
In net/netlink/af_netlink.c (ffffffff81f8a873)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81fbe1fa)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fcbd03)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ff9cd6)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/fib_semantics.c (ffffffff820269f3)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/inet_fragment.c (ffffffff82030e4a)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In net/ipv4/fib_rules.c (ffffffff82041619)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_delete
```
```
In net/ipv4/ipmr.c (ffffffff82047809)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/xfrm/xfrm_policy.c (ffffffff82060456)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff82067d08)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
```
```
In net/ipv6/ip6_output.c (ffffffff820842d6)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In net/ipv6/udp.c (ffffffff820b7cfa)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff820bc606)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820c9a9f)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff820d1f81)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff820d4585)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
```
In net/ipv6/ioam6.c (ffffffff820d8b3a)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff820deeee)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:mif6_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff820eeb98)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff82125c7a)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff82126515)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
```
```
In net/netlabel/netlabel_calipso.c (ffffffff821278e4)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
```
In net/xdp/xskmap.c (ffffffff82141014)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
Inline callers:
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_sock_delete
```
```
In net/handshake/request.c (ffffffff8216964c)
Location: arch/x86/include/asm/atomic.h:58
Inline: True
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006da5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
```
```
In arch/x86/events/intel/core.c (ffffffff8100c905)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff81017c6a)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_put_constraint
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff810192f5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In arch/x86/xen/spinlock.c (ffffffff8102d6cf)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/xen/spinlock.c:xen_qlock_wait
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104cbf5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_unregister_decode_chain
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81050421)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_hcpu_update
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105c716)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105f830)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_release
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81062025)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff8106274b)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/ftrace.c (ffffffff8106e010)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_code
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108bb83)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In kernel/fork.c (ffffffff81098818)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/cpu.c (ffffffff8109deaf)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In kernel/exit.c (ffffffff8109e452)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/workqueue.c (ffffffff810bc203)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cred.c (ffffffff810c7e7c)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/async.c (ffffffff810c8dcb)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/ucount.c (ffffffff810ca14d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (ffffffff810d4cc1)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff810e6127)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (ffffffff810e83bc)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810ea390)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff810ef62b)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/power/process.c (ffffffff811018e7)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
```
```
In kernel/irq/spurious.c (ffffffff81112527)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/rcu/update.c (ffffffff8111c345)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_end_inkernel_boot
```
```
In kernel/rcu/srcutree.c (ffffffff8111d945)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/time/clocksource.c (ffffffff81135930)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/futex.c (ffffffff81146273)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:__unqueue_futex
```
```
In kernel/cgroup/cgroup.c (ffffffff8115dced)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81162a30)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
  - kernel/cgroup/legacy_freezer.c:freezer_css_offline
```
```
In kernel/debug/debug_core.c (ffffffff8117c7a7)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/watchdog_hld.c (ffffffff81188ce5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
```
```
In kernel/trace/ftrace.c (ffffffff81190bf6)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffffffff81196a50)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_record_enable
```
```
In kernel/trace/trace.c (ffffffff8119e739)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:s_stop
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (ffffffff811aa2f3)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811ab2c8)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811adb2c)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/fgraph.c (ffffffff811b1f55)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In kernel/trace/trace_kdb.c (ffffffff811cd6a9)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/bpf/syscall.c (ffffffff811d6f01)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811ec44c)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/offload.c (ffffffff811fa4dd)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffffffff8120b499)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
```
```
In kernel/events/callchain.c (ffffffff81210ff8)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/uprobes.c (ffffffff812122bd)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/padata.c (ffffffff8121672e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/padata.c:padata_find_next
```
```
In mm/backing-dev.c (ffffffff81240f75)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/mmap.c (ffffffff81264a4c)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_link_file
  - mm/mmap.c:__remove_shared_vm_struct
```
```
In mm/mmu_gather.c (ffffffff8126626b)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mprotect.c (ffffffff81266f87)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff8126c49e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In mm/swapfile.c (ffffffff81284914)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffffffff81286582)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff81287045)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_free_entry
```
```
In mm/huge_memory.c (ffffffff812ad5b4)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memcontrol.c (ffffffff812bbca2)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
```
```
In mm/zpool.c (ffffffff812c6465)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/zpool.c:zpool_put_driver
```
```
In fs/open.c (ffffffff812d0787)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff812d73aa)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff812e6c68)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/fs-writeback.c (ffffffff8130ae3f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff8131b446)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/notify/mark.c (ffffffff8132647a)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8132878d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
```
```
In fs/mbcache.c (ffffffff81357b2f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/coredump.c (ffffffff8135a77f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffffffff81360b1b)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In fs/devpts/inode.c (ffffffff813854de)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_kill_index
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/balloc.c (ffffffff81387257)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8138a6a1)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff8139a4cf)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff8139b68d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff813a7df8)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff813b7f91)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff813b97c1)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
```
```
In fs/ext4/mmp.c (ffffffff813ba3ea)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff813d7e91)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/commit.c (ffffffff813eb671)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813ecf84)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/squashfs/block.c (ffffffff813f453b)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff813f9622)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff813f9929)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff813f9cc8)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff813f9fd6)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff813fa2a9)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In fs/ecryptfs/miscdev.c (ffffffff81414990)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release
```
```
In ipc/util.c (ffffffff8142f058)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In ipc/msg.c (ffffffff81431c4d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In security/keys/gc.c (ffffffff8143cbe6)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In security/keys/keyctl.c (ffffffff8144196d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/selinux/avc.c (ffffffff814528a3)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_replace
  - security/selinux/avc.c:avc_node_kill
  - security/selinux/avc.c:avc_node_delete
```
```
In security/selinux/hooks.c (ffffffff814541a5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_dec
```
```
In security/selinux/xfrm.c (ffffffff81473625)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In security/tomoyo/common.c (ffffffff8147f13f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff8148356d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff81485165)
Location: arch/x86/include/asm/atomic.h:108
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
In security/tomoyo/environ.c (ffffffff81485ee1)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff814874c0)
Location: arch/x86/include/asm/atomic.h:108
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
In security/tomoyo/gc.c (ffffffff814878c2)
Location: arch/x86/include/asm/atomic.h:108
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
In security/tomoyo/group.c (ffffffff814881f8)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff81488860)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/network.c (ffffffff814897b6)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
```
In security/tomoyo/securityfs_if.c (ffffffff8148a55e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8148a6cf)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_task_free
  - security/tomoyo/tomoyo.c:tomoyo_task_free
  - security/tomoyo/tomoyo.c:tomoyo_bprm_committed_creds
  - security/tomoyo/tomoyo.c:tomoyo_cred_prepare
  - security/tomoyo/tomoyo.c:tomoyo_domain
```
```
In block/blk-flush.c (ffffffff814e1581)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (ffffffff814e2b2a)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - block/blk-ioc.c:exit_io_context
```
```
In block/blk-mq.c (ffffffff814e95d5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-tag.c (ffffffff814ecbf6)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-iocost.c (ffffffff8150828c)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (ffffffff81554743)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_finish_wait
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/pci/pci.c (ffffffff81578ee2)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81594298)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
```
In drivers/pci/ats.c (ffffffff815a01f8)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815b129b)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
```
In drivers/dma/dmaengine.c (ffffffff8161d093)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/reset/core.c (ffffffff8164704f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff81652b2a)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
```
In drivers/tty/vt/keyboard.c (ffffffff828e89c9)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_start
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff8167e17c)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_close
```
```
In drivers/tty/serial/kgdboc.c (ffffffff8167e915)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_post_exp_handler
```
```
In drivers/char/agp/backend.c (ffffffff8168b17e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_release
```
```
In drivers/char/agp/generic.c (ffffffff8168ded4)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8169177f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
```
```
In drivers/connector/cn_queue.c (ffffffff816b9aba)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffff816ba3bb)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/base/dd.c (ffffffff816c50ae)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/power/runtime.c (ffffffff816d3664)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/mfd/mfd-core.c (ffffffff81701e75)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8170be73)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:deactivate_labels
```
```
In drivers/scsi/scsi_lib.c (ffffffff817262d3)
Location: arch/x86/include/asm/atomic.h:108
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
In drivers/net/ppp/ppp_generic.c (ffffffff8178bed2)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
```
```
In drivers/usb/core/hcd.c (ffffffff817a5492)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/urb.c (ffffffff817a867f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81828052)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (ffffffff8183adf7)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffff8184f72e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stats.c (ffffffff8185bc6d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff818616cc)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81884a4a)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81896f85)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/ras/debugfs.c (ffffffff818a1855)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_release
```
```
In net/core/skbuff.c (ffffffff818bb90e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_put_abort
```
```
In net/core/dev.c (ffffffff818cd272)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In net/core/neighbour.c (ffffffff818e4d71)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_for_each_release
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_flush_dev
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/core/xdp.c (ffffffff81902ce8)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81903b94)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In net/core/sock_map.c (ffffffff8191996d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_free_elem
```
```
In net/sched/cls_api.c (ffffffff819357f0)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_cls_offload_cnt_reset
  - net/sched/cls_api.c:tc_cls_offload_cnt_update
```
```
In net/sched/act_api.c (ffffffff81939d4d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff819405f0)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8195a187)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195c0ee)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/inet_fragment.c (ffffffff819a6188)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff819b23d2)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/xfrm/xfrm_policy.c (ffffffff819bffd2)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff819c6858)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
```
```
In net/ipv6/route.c (ffffffff819e9b62)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In net/ipv6/udp.c (ffffffff819ff40e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81a039e1)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0e5bc)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81a13a1e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a15590)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
```
In net/ipv6/ip6mr.c (ffffffff81a1a676)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a2595d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
```
In net/packet/af_packet.c (ffffffff81a29010)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mm_close
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a388de)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a395ba)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a3a2b0)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
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
In arch/x86/events/core.c (ffffffff810054c5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
```
```
In arch/x86/events/intel/core.c (ffffffff8100b105)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff810170ba)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_put_constraint
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff810186c5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103bfa5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_unregister_decode_chain
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8103fa81)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_hcpu_update
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104c8e6)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8104fb60)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_release
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff810523d9)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff81052ae5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/ftrace.c (ffffffff8105e430)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_code
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8107a6a3)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In kernel/fork.c (ffffffff81087282)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/cpu.c (ffffffff8108c8cf)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In kernel/exit.c (ffffffff8108ce71)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/workqueue.c (ffffffff810aaa93)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cred.c (ffffffff810b669c)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/async.c (ffffffff810b75eb)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/ucount.c (ffffffff810b8967)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (ffffffff810c3311)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff810d52c7)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (ffffffff810d7f70)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810da3c0)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff810df69b)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/power/process.c (ffffffff810f1ca7)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
```
```
In kernel/irq/spurious.c (ffffffff81103247)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/rcu/update.c (ffffffff8110d425)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_end_inkernel_boot
```
```
In kernel/rcu/srcutree.c (ffffffff8110e9e5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/rcu/tree.c (ffffffff8110f4d0)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_nocb_bypass_lock
```
```
In kernel/time/clocksource.c (ffffffff81128339)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/futex.c (ffffffff8113957d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:__unqueue_futex
```
```
In kernel/cgroup/cgroup.c (ffffffff81150fcd)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81155c80)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
  - kernel/cgroup/legacy_freezer.c:freezer_css_offline
```
```
In kernel/debug/debug_core.c (ffffffff8116f947)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/watchdog_hld.c (ffffffff8117be25)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
```
```
In kernel/trace/ftrace.c (ffffffff811837b9)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffffffff81189d40)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_record_enable
```
```
In kernel/trace/trace.c (ffffffff8119178d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:s_stop
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (ffffffff8119d258)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8119e5d1)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811a0973)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/fgraph.c (ffffffff811a4d65)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In kernel/trace/trace_kdb.c (ffffffff811c0479)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/bpf/syscall.c (ffffffff811c9cc1)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811df1dc)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/offload.c (ffffffff811ed22d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffffffff811fe269)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
```
```
In kernel/events/callchain.c (ffffffff81203d88)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/uprobes.c (ffffffff8120504d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/padata.c (ffffffff8120948e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/padata.c:padata_find_next
```
```
In mm/backing-dev.c (ffffffff81233f75)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/mmap.c (ffffffff81256e6c)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_link_file
  - mm/mmap.c:__remove_shared_vm_struct
```
```
In mm/mmu_gather.c (ffffffff8125868b)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mprotect.c (ffffffff812590a7)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff8125e50e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In mm/swapfile.c (ffffffff81276784)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffffffff812783e2)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff81278ea5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_free_entry
```
```
In mm/huge_memory.c (ffffffff8129e53b)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memcontrol.c (ffffffff812ace02)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
```
```
In mm/zpool.c (ffffffff812b74a5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/zpool.c:zpool_put_driver
```
```
In fs/open.c (ffffffff812c1407)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff812c802a)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff812d78a8)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/fs-writeback.c (ffffffff812fba59)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff8130bfe6)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/notify/mark.c (ffffffff8131701a)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8131932d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
```
```
In fs/mbcache.c (ffffffff813487df)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/coredump.c (ffffffff8134b429)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffffffff813517bb)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In fs/devpts/inode.c (ffffffff81375f6e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_kill_index
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/balloc.c (ffffffff81377ce7)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8137b131)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff8138af5f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff8138c11d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff81398888)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff813a8a21)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff813aa251)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
```
```
In fs/ext4/mmp.c (ffffffff813aae7a)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff813c8911)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/commit.c (ffffffff813dc0f1)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813dda04)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/squashfs/block.c (ffffffff813e4fbb)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff813ea0a2)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff813ea3a9)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff813ea748)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff813eaa56)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff813ead29)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In fs/ecryptfs/miscdev.c (ffffffff81405410)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release
```
```
In ipc/util.c (ffffffff8141fad8)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In ipc/msg.c (ffffffff814226cd)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In security/keys/gc.c (ffffffff8142d656)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In security/keys/keyctl.c (ffffffff814323dd)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/selinux/avc.c (ffffffff814432f3)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_replace
  - security/selinux/avc.c:avc_node_kill
  - security/selinux/avc.c:avc_node_delete
```
```
In security/selinux/hooks.c (ffffffff81444be5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_dec
```
```
In security/selinux/xfrm.c (ffffffff81464045)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In security/tomoyo/common.c (ffffffff8146fb5f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff81473f8d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff81475b85)
Location: arch/x86/include/asm/atomic.h:108
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
In security/tomoyo/environ.c (ffffffff81476901)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff81477ee0)
Location: arch/x86/include/asm/atomic.h:108
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
In security/tomoyo/gc.c (ffffffff814782e2)
Location: arch/x86/include/asm/atomic.h:108
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
In security/tomoyo/group.c (ffffffff81478c18)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff81479280)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/network.c (ffffffff8147a1d6)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
```
In security/tomoyo/securityfs_if.c (ffffffff8147af7e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8147b0ef)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_task_free
  - security/tomoyo/tomoyo.c:tomoyo_task_free
  - security/tomoyo/tomoyo.c:tomoyo_bprm_committed_creds
  - security/tomoyo/tomoyo.c:tomoyo_cred_prepare
  - security/tomoyo/tomoyo.c:tomoyo_domain
```
```
In block/blk-flush.c (ffffffff814d1f11)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (ffffffff814d34ba)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - block/blk-ioc.c:exit_io_context
```
```
In block/blk-mq.c (ffffffff814d9b45)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-tag.c (ffffffff814dd146)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-iocost.c (ffffffff814f873c)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (ffffffff815449c3)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_finish_wait
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/pci/pci.c (ffffffff81567622)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81583428)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
```
In drivers/pci/ats.c (ffffffff8158f388)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815a042b)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
```
In drivers/dma/dmaengine.c (ffffffff81611783)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/reset/core.c (ffffffff816274af)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff81632f6a)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
```
In drivers/tty/vt/keyboard.c (ffffffff828e012c)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_start
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff8165d26c)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_close
```
```
In drivers/tty/serial/kgdboc.c (ffffffff8165da05)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_post_exp_handler
```
```
In drivers/char/agp/backend.c (ffffffff81668b7e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_release
```
```
In drivers/char/agp/generic.c (ffffffff8166b8c4)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8166f16f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
```
```
In drivers/connector/cn_queue.c (ffffffff816976fa)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffff81697ffb)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/base/dd.c (ffffffff816a032e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/power/runtime.c (ffffffff816ae924)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/mfd/mfd-core.c (ffffffff816d5c85)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816df8f3)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:deactivate_labels
```
```
In drivers/scsi/scsi_lib.c (ffffffff816ff703)
Location: arch/x86/include/asm/atomic.h:108
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
In drivers/net/ppp/ppp_generic.c (ffffffff81774ca2)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
```
```
In drivers/vfio/vfio.c (ffffffff8177af55)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_release
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_add_container_user
  - drivers/vfio/vfio.c:vfio_group_add_container_user
```
```
In drivers/usb/core/hcd.c (ffffffff81796f89)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/urb.c (ffffffff8179a08f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
```
```
In drivers/power/supply/power_supply_core.c (ffffffff817ef6e2)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (ffffffff81802467)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffff81816d3e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stats.c (ffffffff8182323d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81828c7c)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/hv/channel.c (ffffffff818519d7)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/hv/channel.c:vmbus_reset_channel_cb
```
```
In drivers/hv/channel_mgmt.c (ffffffff81852588)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/hv/channel_mgmt.c:vmbus_onoffer
  - drivers/hv/channel_mgmt.c:vmbus_onoffer
  - drivers/hv/channel_mgmt.c:vmbus_onoffer
```
```
In drivers/ras/debugfs.c (ffffffff8185cfc5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_release
```
```
In net/core/skbuff.c (ffffffff8187584e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_put_abort
```
```
In net/core/dev.c (ffffffff81887302)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In net/core/neighbour.c (ffffffff8189ebb1)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_for_each_release
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_flush_dev
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/core/xdp.c (ffffffff818bcb18)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff818bd9c4)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In net/core/sock_map.c (ffffffff818d371d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_free_elem
```
```
In net/sched/cls_api.c (ffffffff818ef2f0)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_cls_offload_cnt_reset
  - net/sched/cls_api.c:tc_cls_offload_cnt_update
```
```
In net/sched/act_api.c (ffffffff818f384d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff818fa0e0)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81913c77)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81915bde)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/inet_fragment.c (ffffffff8195fc48)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff8196ea02)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197cdc2)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff81983648)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
```
```
In net/ipv6/route.c (ffffffff819a6922)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In net/ipv6/udp.c (ffffffff819bc1ce)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff819c07a1)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cb37c)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff819d07de)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff819d2350)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
```
In net/ipv6/ip6mr.c (ffffffff819d7436)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e271d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
```
In net/packet/af_packet.c (ffffffff819e6200)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mm_close
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f54fe)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f61da)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819f6ed0)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
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
In arch/x86/events/core.c (ffffffff81006d65)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
```
```
In arch/x86/events/intel/core.c (ffffffff8100c8c5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff81017c2a)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_put_constraint
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff810192b5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In arch/x86/xen/spinlock.c (ffffffff8102d52f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/xen/spinlock.c:xen_qlock_wait
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104ca35)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_unregister_decode_chain
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff810502d1)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_hcpu_update
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105cb46)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105fc60)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_release
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81062445)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff81062bfb)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/ftrace.c (ffffffff8106e4c0)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_code
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108bb33)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In kernel/fork.c (ffffffff810987c8)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/cpu.c (ffffffff8109de5f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In kernel/exit.c (ffffffff8109e402)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/workqueue.c (ffffffff810bb763)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cred.c (ffffffff810c73cc)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/async.c (ffffffff810c82fb)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/ucount.c (ffffffff810c967d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (ffffffff810d1b01)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff810e24f7)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (ffffffff810e50e0)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810e74c0)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff810ec75b)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/power/process.c (ffffffff810fec77)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
```
```
In kernel/irq/spurious.c (ffffffff81110417)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/rcu/update.c (ffffffff8111a235)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_end_inkernel_boot
```
```
In kernel/rcu/srcutree.c (ffffffff8111b835)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/time/clocksource.c (ffffffff81133650)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/futex.c (ffffffff81144123)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:__unqueue_futex
```
```
In kernel/cgroup/cgroup.c (ffffffff8115babd)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81160800)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
  - kernel/cgroup/legacy_freezer.c:freezer_css_offline
```
```
In kernel/debug/debug_core.c (ffffffff8117a577)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/watchdog_hld.c (ffffffff81186ab5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
```
```
In kernel/trace/ftrace.c (ffffffff8118e9c6)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffffffff81194820)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_record_enable
```
```
In kernel/trace/trace.c (ffffffff8119c509)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:s_stop
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (ffffffff811a80c3)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811a9098)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811ab8fc)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/fgraph.c (ffffffff811afd25)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In kernel/trace/trace_kdb.c (ffffffff811cb479)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/bpf/syscall.c (ffffffff811d4cd1)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811ea21c)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/offload.c (ffffffff811f82ad)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffffffff81209239)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
```
```
In kernel/events/callchain.c (ffffffff8120ed98)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/uprobes.c (ffffffff8121005d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/padata.c (ffffffff812144ce)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/padata.c:padata_find_next
```
```
In mm/backing-dev.c (ffffffff8123ed15)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/mmap.c (ffffffff812627ec)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_link_file
  - mm/mmap.c:__remove_shared_vm_struct
```
```
In mm/mmu_gather.c (ffffffff8126400b)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mprotect.c (ffffffff81264d27)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff8126a23e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In mm/swapfile.c (ffffffff81282724)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffffffff81284392)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff81284e55)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_free_entry
```
```
In mm/huge_memory.c (ffffffff812ab3c4)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memcontrol.c (ffffffff812b9ab2)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
```
```
In mm/zpool.c (ffffffff812c4275)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/zpool.c:zpool_put_driver
```
```
In fs/open.c (ffffffff812ce597)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff812d51ba)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff812e4a78)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/fs-writeback.c (ffffffff81308c2f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff81318f16)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/notify/mark.c (ffffffff81323f4a)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8132625d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
```
```
In fs/mbcache.c (ffffffff813555ff)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/coredump.c (ffffffff8135824f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffffffff8135e5eb)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In fs/devpts/inode.c (ffffffff81382fae)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_kill_index
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/balloc.c (ffffffff81384d27)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff81388001)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff81397d2f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff81398eed)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff813a5658)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff813b57f1)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff813b7021)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
```
```
In fs/ext4/mmp.c (ffffffff813b7c4a)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff813d5321)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/commit.c (ffffffff813e89f1)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813ea304)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/squashfs/block.c (ffffffff813f18bb)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff813f69a2)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff813f6ca9)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff813f7048)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff813f7356)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff813f7629)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In fs/ecryptfs/miscdev.c (ffffffff81411d10)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release
```
```
In ipc/util.c (ffffffff8142b1f8)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In ipc/msg.c (ffffffff8142dded)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In security/keys/gc.c (ffffffff81438d86)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In security/keys/keyctl.c (ffffffff8143db0d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/selinux/avc.c (ffffffff8144e943)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_replace
  - security/selinux/avc.c:avc_node_kill
  - security/selinux/avc.c:avc_node_delete
```
```
In security/selinux/hooks.c (ffffffff81450245)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_dec
```
```
In security/selinux/xfrm.c (ffffffff8146f6c5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In security/tomoyo/common.c (ffffffff8147b1df)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff8147f60d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff81481205)
Location: arch/x86/include/asm/atomic.h:108
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
In security/tomoyo/environ.c (ffffffff81481f81)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff81483560)
Location: arch/x86/include/asm/atomic.h:108
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
In security/tomoyo/gc.c (ffffffff81483962)
Location: arch/x86/include/asm/atomic.h:108
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
In security/tomoyo/group.c (ffffffff81484298)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff81484900)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/network.c (ffffffff81485856)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
```
In security/tomoyo/securityfs_if.c (ffffffff814865fe)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8148676f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_task_free
  - security/tomoyo/tomoyo.c:tomoyo_task_free
  - security/tomoyo/tomoyo.c:tomoyo_bprm_committed_creds
  - security/tomoyo/tomoyo.c:tomoyo_cred_prepare
  - security/tomoyo/tomoyo.c:tomoyo_domain
```
```
In block/blk-flush.c (ffffffff814dd611)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (ffffffff814debba)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - block/blk-ioc.c:exit_io_context
```
```
In block/blk-mq.c (ffffffff814e5665)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-tag.c (ffffffff814e8c86)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-iocost.c (ffffffff8150431c)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (ffffffff81550483)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_finish_wait
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/pci/pci.c (ffffffff81578712)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff815947d8)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
```
In drivers/pci/ats.c (ffffffff815a0778)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815b182b)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
```
In drivers/acpi/apei/ghes.c (ffffffff8163795a)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
```
```
In drivers/dma/dmaengine.c (ffffffff8164b033)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/reset/core.c (ffffffff8167540f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff81680eea)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
```
In drivers/tty/vt/keyboard.c (ffffffff828fc504)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff816ac55c)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_close
```
```
In drivers/tty/serial/kgdboc.c (ffffffff816accf5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_post_exp_handler
```
```
In drivers/char/agp/backend.c (ffffffff816b93ee)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_release
```
```
In drivers/char/agp/generic.c (ffffffff816bc144)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816bf9ef)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
```
```
In drivers/connector/cn_queue.c (ffffffff816e7f8a)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffff816e888b)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/base/dd.c (ffffffff816f357e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/power/runtime.c (ffffffff81701bd4)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/mfd/mfd-core.c (ffffffff81737295)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8174ac43)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:deactivate_labels
```
```
In drivers/scsi/scsi_lib.c (ffffffff817650a3)
Location: arch/x86/include/asm/atomic.h:108
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
In drivers/net/ppp/ppp_generic.c (ffffffff817bc272)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
```
```
In drivers/vfio/vfio.c (ffffffff817c5d25)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_release
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_add_container_user
  - drivers/vfio/vfio.c:vfio_group_add_container_user
```
```
In drivers/usb/core/hcd.c (ffffffff817e1f32)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/urb.c (ffffffff817e511f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81874f92)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (ffffffff8188a427)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffff8189ed5e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stats.c (ffffffff818ab29d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff818b0cfc)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff818d5eea)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/ras/debugfs.c (ffffffff818f2e45)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_release
```
```
In net/core/skbuff.c (ffffffff8190c90e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_put_abort
```
```
In net/core/dev.c (ffffffff8191e272)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In net/core/neighbour.c (ffffffff81935da1)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_for_each_release
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_flush_dev
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/core/xdp.c (ffffffff81953d18)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81954bc4)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In net/core/sock_map.c (ffffffff8196aafd)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_free_elem
```
```
In net/sched/cls_api.c (ffffffff81986980)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_cls_offload_cnt_reset
  - net/sched/cls_api.c:tc_cls_offload_cnt_update
```
```
In net/sched/act_api.c (ffffffff8198aedd)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81991780)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/netfilter/nf_conntrack_core.c (ffffffff8199ccb7)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_free
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_alloc
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_alloc
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819c4957)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c68be)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/inet_fragment.c (ffffffff81a10a28)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a1cc72)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2aa52)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff81a312d8)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
```
```
In net/ipv6/route.c (ffffffff81a545e2)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a69e8e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81a6e461)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7903c)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81a7e49e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a80010)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
```
In net/ipv6/ip6mr.c (ffffffff81a850f6)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a903dd)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
```
In net/packet/af_packet.c (ffffffff81a94bc0)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mm_close
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81aa478e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81aa546a)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81aa6160)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
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
In arch/x86/events/core.c (ffffffff81006ec5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
```
```
In arch/x86/events/intel/core.c (ffffffff8100caf5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff81017e6a)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_put_constraint
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff810194f5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In arch/x86/xen/spinlock.c (ffffffff8102e31f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/xen/spinlock.c:xen_qlock_wait
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104de45)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_unregister_decode_chain
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81051711)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_hcpu_update
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105e068)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810611c0)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_release
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81063a05)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff810641bb)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/ftrace.c (ffffffff81070740)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_code
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108de93)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff81097bfd)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109a865)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In kernel/fork.c (ffffffff810a03ef)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/cpu.c (ffffffff810a5d4f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In kernel/exit.c (ffffffff810a6317)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/workqueue.c (ffffffff810c3b5d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cred.c (ffffffff810cf89c)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/async.c (ffffffff810d082b)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/ucount.c (ffffffff810d1bcb)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (ffffffff810dc4c1)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff810ee09c)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (ffffffff810f1077)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810f2480)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff810f779b)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/power/process.c (ffffffff81109f47)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
```
```
In kernel/irq/spurious.c (ffffffff8111b997)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/rcu/update.c (ffffffff81125985)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_end_inkernel_boot
```
```
In kernel/rcu/srcutree.c (ffffffff81126a95)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/time/clocksource.c (ffffffff81140070)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/futex.c (ffffffff811501a6)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:__unqueue_futex
```
```
In kernel/cgroup/cgroup.c (ffffffff81168ba2)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8116db70)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
  - kernel/cgroup/legacy_freezer.c:freezer_css_offline
```
```
In kernel/debug/debug_core.c (ffffffff81187ea7)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/watchdog_hld.c (ffffffff81194405)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
```
```
In kernel/trace/ftrace.c (ffffffff8119c556)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffffffff811a2430)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_record_enable
```
```
In kernel/trace/trace.c (ffffffff811aa1a9)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:s_stop
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (ffffffff811b5e73)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811b6ed8)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811b97cc)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/fgraph.c (ffffffff811bdd95)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In kernel/trace/trace_kdb.c (ffffffff811d96d9)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/bpf/syscall.c (ffffffff811e3001)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811f85fc)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/offload.c (ffffffff81206620)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffffffff81217fc9)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
```
```
In kernel/events/callchain.c (ffffffff8121dca8)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/uprobes.c (ffffffff8121f07d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/padata.c (ffffffff8122250e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - kernel/padata.c:padata_find_next
```
```
In mm/backing-dev.c (ffffffff8124e445)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/mmap.c (ffffffff812721ac)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_link_file
  - mm/mmap.c:__remove_shared_vm_struct
```
```
In mm/mmu_gather.c (ffffffff812739cb)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mprotect.c (ffffffff812746c1)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff81279bae)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In mm/swapfile.c (ffffffff8129240b)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffffffff81294372)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff81294af5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_free_entry
```
```
In mm/huge_memory.c (ffffffff812bb714)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memcontrol.c (ffffffff812ca142)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
```
```
In mm/zpool.c (ffffffff812d4e95)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - mm/zpool.c:zpool_put_driver
```
```
In fs/open.c (ffffffff812df3a7)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff812e6000)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff812f59f8)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/fs-writeback.c (ffffffff8131a8c8)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff8132ab46)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/notify/mark.c (ffffffff81335c78)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8133807d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
```
```
In fs/mbcache.c (ffffffff81368bdf)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/coredump.c (ffffffff8136b981)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffffffff81370fa6)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In fs/devpts/inode.c (ffffffff81396ace)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_kill_index
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/balloc.c (ffffffff813988a7)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8139bd01)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff813ac670)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff813ad30d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff813b9d98)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff813ca475)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff813cbd31)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
```
```
In fs/ext4/mmp.c (ffffffff813cc94d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff813ea5a4)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/commit.c (ffffffff813fe249)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813ffc5c)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/squashfs/block.c (ffffffff814074bf)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff8140c632)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff8140c939)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff8140ccd8)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff8140cfe6)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff8140d2b9)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In fs/ecryptfs/miscdev.c (ffffffff81427980)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release
```
```
In ipc/util.c (ffffffff814420f0)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In ipc/msg.c (ffffffff8144484a)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In security/keys/gc.c (ffffffff8144fef6)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In security/keys/keyctl.c (ffffffff81454c97)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/selinux/avc.c (ffffffff81465d23)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_replace
  - security/selinux/avc.c:avc_node_kill
  - security/selinux/avc.c:avc_node_delete
```
```
In security/selinux/hooks.c (ffffffff814676e5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_dec
```
```
In security/selinux/xfrm.c (ffffffff81486f35)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In security/tomoyo/common.c (ffffffff81492dcf)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff8149713d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff81498d75)
Location: arch/x86/include/asm/atomic.h:108
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
In security/tomoyo/environ.c (ffffffff81499b11)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff8149b0f0)
Location: arch/x86/include/asm/atomic.h:108
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
In security/tomoyo/gc.c (ffffffff8149b50b)
Location: arch/x86/include/asm/atomic.h:108
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
In security/tomoyo/group.c (ffffffff8149bdd8)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff8149c440)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/network.c (ffffffff8149d396)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
```
In security/tomoyo/securityfs_if.c (ffffffff8149e13e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8149e2af)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_task_free
  - security/tomoyo/tomoyo.c:tomoyo_task_free
  - security/tomoyo/tomoyo.c:tomoyo_bprm_committed_creds
  - security/tomoyo/tomoyo.c:tomoyo_cred_prepare
  - security/tomoyo/tomoyo.c:tomoyo_domain
```
```
In block/blk-flush.c (ffffffff814f6471)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (ffffffff814f7a2a)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - block/blk-ioc.c:exit_io_context
```
```
In block/blk-mq.c (ffffffff814fe5c5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-tag.c (ffffffff81501c26)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-iocost.c (ffffffff8151d8cc)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (ffffffff8156a2c3)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_finish_wait
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/pci/pci.c (ffffffff81592bd2)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff815aec58)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
```
In drivers/pci/ats.c (ffffffff815baba8)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815cb29b)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
```
In drivers/acpi/apei/ghes.c (ffffffff81651ca4)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
```
```
In drivers/dma/dmaengine.c (ffffffff816655d3)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/reset/core.c (ffffffff8168fa6f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff8169b53a)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
```
In drivers/tty/vt/keyboard.c (ffffffff82902235)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff816c69bc)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_close
```
```
In drivers/tty/serial/kgdboc.c (ffffffff816c7155)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_post_exp_handler
```
```
In drivers/char/agp/backend.c (ffffffff816d39be)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_release
```
```
In drivers/char/agp/generic.c (ffffffff816d6a34)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816d9fbf)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
```
```
In drivers/connector/cn_queue.c (ffffffff8170268a)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffff81702f8b)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/base/dd.c (ffffffff8170ddae)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/power/runtime.c (ffffffff8171c094)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In drivers/mfd/mfd-core.c (ffffffff817526d5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff817660c3)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:deactivate_labels
```
```
In drivers/scsi/scsi_lib.c (ffffffff81780733)
Location: arch/x86/include/asm/atomic.h:108
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
In drivers/net/ppp/ppp_generic.c (ffffffff817d6612)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
```
```
In drivers/vfio/vfio.c (ffffffff817dffc5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_release
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_add_container_user
  - drivers/vfio/vfio.c:vfio_group_add_container_user
```
```
In drivers/usb/core/hcd.c (ffffffff817fc222)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/urb.c (ffffffff817ff37f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
```
```
In drivers/media/cec/cec-pin.c (ffffffff8188c2b4)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/media/cec/cec-pin.c:cec_pin_thread_func
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81890935)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (ffffffff818a928b)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffff818b86ee)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stats.c (ffffffff818c74cf)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff818ccf8c)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff818f2a0a)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819076e5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/ras/debugfs.c (ffffffff81913ee5)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_release
```
```
In net/core/skbuff.c (ffffffff8192da4e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_put_abort
```
```
In net/core/dev.c (ffffffff8193f902)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In net/core/neighbour.c (ffffffff819574dc)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_for_each_release
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_flush_dev
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/core/xdp.c (ffffffff819754ac)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff8197687d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In net/core/sock_map.c (ffffffff8198cf6d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_free_elem
```
```
In net/sched/cls_api.c (ffffffff819a6b60)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_cls_offload_cnt_reset
  - net/sched/cls_api.c:tc_cls_offload_cnt_update
```
```
In net/sched/act_api.c (ffffffff819ad73d)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff819b4215)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819ce3d3)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819d040e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1b2b0)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a27bcd)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a3600b)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3cbd8)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
```
```
In net/ipv6/route.c (ffffffff81a605d2)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a7649e)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81a7a9ef)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a857fa)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81a8ad3f)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a8c9c0)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
```
In net/ipv6/ip6mr.c (ffffffff81a91a11)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9cff0)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
```
In net/packet/af_packet.c (ffffffff81aa0d20)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mm_close
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81ab0b24)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ab180a)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81ab2500)
Location: arch/x86/include/asm/atomic.h:108
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
</details>
</li>
</ul>

## Differences

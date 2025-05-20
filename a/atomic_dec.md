# Function: <code>atomic_dec</code>

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
In arch/x86/events/core.c (ffffffff8100604e)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
```
```
In arch/x86/events/intel/core.c (ffffffff8100b583)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff81016222)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_put_constraint
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101817c)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff81047681)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_hcpu_update
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff8104fc01)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff810501f5)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/ftrace.c (ffffffff8105ad44)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:update_ftrace_func
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_code
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff8105efb7)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:longjmp_break_handler
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81074902)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In kernel/fork.c (ffffffff8107ec4b)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff81082457)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/signal.c (ffffffff8108ce22)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/kmod.c (ffffffff81096992)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/workqueue.c (ffffffff8109a288)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:worker_thread
```
```
In kernel/pid.c (ffffffff8109e208)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:pidmap_init
```
```
In kernel/cred.c (ffffffff810a2296)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/async.c (ffffffff810a2f85)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/core.c (ffffffff8181f961)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule_timeout
```
```
In kernel/sched/fair.c (ffffffff810b478d)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_cpu_sd_state_idle
  - kernel/sched/fair.c:trigger_load_balance
```
```
In kernel/sched/rt.c (ffffffff810c0447)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810c1b85)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff810c420d)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/power/process.c (ffffffff810cdc07)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
```
```
In kernel/irq/spurious.c (ffffffff810dd2eb)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/spurious.c:note_interrupt
```
```
In kernel/rcu/update.c (ffffffff810e3229)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_unexpedite_gp
```
```
In kernel/time/clocksource.c (ffffffff810f8472)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/futex.c (ffffffff810ff95c)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/futex.c:__unqueue_futex
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
```
```
In kernel/cgroup.c (ffffffff8111546c)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/cgroup.c:css_free_work_fn
```
```
In kernel/cgroup_freezer.c (ffffffff81119bc2)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_css_offline
  - kernel/cgroup_freezer.c:freezer_apply_state
```
```
In kernel/debug/debug_core.c (ffffffff8112f6e7)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff811321a7)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In kernel/trace/ftrace.c (ffffffff81140da9)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:profile_graph_entry
```
```
In kernel/trace/ring_buffer.c (ffffffff81146284)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_record_enable
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
```
```
In kernel/trace/trace.c (ffffffff8114bc03)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:s_stop
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (ffffffff81156955)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8115711b)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
```
```
In kernel/trace/trace_functions_graph.c (ffffffff81159689)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_return
```
```
In kernel/trace/trace_kdb.c (ffffffff8116cbce)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/events/core.c (ffffffff81179f76)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
```
```
In kernel/events/callchain.c (ffffffff8118610d)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/uprobes.c (ffffffff81186eca)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/padata.c (ffffffff81189b82)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_reorder
```
```
In mm/swap.c (ffffffff8119d3aa)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
```
```
In mm/backing-dev.c (ffffffff811ae158)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
  - mm/backing-dev.c:bdi_unregister
```
```
In mm/mmap.c (ffffffff811c3ff5)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - mm/mmap.c:__remove_shared_vm_struct
  - mm/mmap.c:__vma_link_file
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
```
In mm/frontswap.c (ffffffff811d76e8)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff811d8637)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - mm/zswap.c:zswap_free_entry
```
```
In mm/migrate.c (ffffffff811f0f2d)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - mm/migrate.c:buffer_migrate_page
```
```
In mm/memcontrol.c (ffffffff811fb87d)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
```
```
In mm/zpool.c (ffffffff812042f9)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - mm/zpool.c:zpool_put_driver
```
```
In fs/open.c (ffffffff81209948)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/open.c:vfs_truncate
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
```
```
In fs/file_table.c (ffffffff8120e560)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff8121abdd)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/namei.c:path_openat
```
```
In fs/fs-writeback.c (ffffffff81236755)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff81242692)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_read_sync
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:write_boundary_block
```
```
In fs/block_dev.c (ffffffff81248e2d)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_close
```
```
In fs/notify/mark.c (ffffffff812504b2)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff8125190c)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81252318)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81252820)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
```
```
In fs/mbcache.c (ffffffff8126c7da)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/mbcache.c:__mb_cache_entry_find
  - fs/mbcache.c:mb_cache_entry_get
```
```
In fs/coredump.c (ffffffff8126f512)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffffffff81271644)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff8128fda7)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff81292e52)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff81295cd9)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/ext4/inode.c:bput_one
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
```
```
In fs/ext4/extents.c (ffffffff812c2cb5)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_find_extent
```
```
In fs/ext4/migrate.c (ffffffff812cc247)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/ext4/migrate.c:update_ind_extent_range
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/mballoc.c (ffffffff812cd8b3)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/ext4/mmp.c (ffffffff812d7f58)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/indirect.c (ffffffff812d8558)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/jbd2/commit.c (ffffffff812ea424)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff812eba7e)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff812ed764)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
```
```
In fs/ecryptfs/miscdev.c (ffffffff8130bcba)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release
```
```
In fs/fuse/dev.c (ffffffff8130dd0b)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:__fuse_get_req
```
```
In ipc/msg.c (ffffffff813259ea)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - ipc/msg.c:freeque
  - ipc/msg.c:do_msgrcv
```
```
In ipc/namespace.c (ffffffff8132eba6)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
```
```
In security/keys/gc.c (ffffffff8132ee15)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
```
```
In security/keys/keyctl.c (ffffffff81332be0)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/selinux/avc.c (ffffffff8134024b)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_delete
  - security/selinux/avc.c:avc_node_replace
  - security/selinux/avc.c:avc_update_node
```
```
In security/selinux/hooks.c (ffffffff813419f9)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_dec
```
```
In security/selinux/xfrm.c (ffffffff8135cc8e)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_free
```
```
In security/tomoyo/common.c (ffffffff81367dfc)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff8136c3ae)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff8136d67b)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_assign_domain
```
```
In security/tomoyo/environ.c (ffffffff8136ea27)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff8136ee02)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_put_name_union
  - security/tomoyo/file.c:tomoyo_put_name_union
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_write_file
```
```
In security/tomoyo/gc.c (ffffffff8136ff2e)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_del_acl
  - security/tomoyo/gc.c:tomoyo_del_acl
  - security/tomoyo/gc.c:tomoyo_del_acl
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/tomoyo/group.c (ffffffff81370b47)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff813711d4)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/network.c (ffffffff8137216c)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
```
In security/tomoyo/securityfs_if.c (ffffffff81372fc9)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff81373082)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_cred_free
```
```
In block/bio.c (ffffffff813b072c)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_end_io_acct
```
```
In block/blk-core.c (ffffffff813ba644)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
```
```
In block/blk-ioc.c (ffffffff813bf00c)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - block/blk-ioc.c:exit_io_context
```
```
In block/blk-merge.c (ffffffff813c1925)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
```
```
In block/blk-mq.c (ffffffff813c2fdd)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_free_request
```
```
In block/blk-mq-tag.c (ffffffff813c75d9)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In drivers/pci/pci.c (ffffffff81437fec)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8144cc73)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
```
```
In drivers/pci/ats.c (ffffffff81455e17)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff814b59c8)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_notify_nmi
```
```
In drivers/dma/dmaengine.c (ffffffff814bdf99)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/tty/tty_buffer.c (ffffffff814eaa4c)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
```
In drivers/tty/vt/keyboard.c (ffffffff814f1cb8)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
  - drivers/tty/vt/keyboard.c:kbd_init
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff8151029c)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_close
```
```
In drivers/char/agp/backend.c (ffffffff8151b00e)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_release
```
```
In drivers/char/agp/generic.c (ffffffff8151dfb5)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8152182e)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
```
```
In drivers/connector/cn_queue.c (ffffffff81541724)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffff81542029)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
```
```
In drivers/base/dd.c (ffffffff8154bc3f)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/runtime.c (ffffffff81557818)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
```
```
In drivers/mfd/mfd-core.c (ffffffff8158a692)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/nvdimm/core.c (ffffffff81596b77)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nd_iostat_end
  - drivers/nvdimm/core.c:nd_iostat_end
```
```
In drivers/nvdimm/region_devs.c (ffffffff8159a2d5)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_notify_driver_action
```
```
In drivers/scsi/scsi_lib.c (ffffffff815ada5f)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_enable_disk_events
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
```
```
In drivers/net/phy/phy.c (ffffffff815ea9e7)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_change
  - drivers/net/phy/phy.c:phy_change
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff815f4f1d)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
```
```
In drivers/usb/core/hcd.c (ffffffff8160ce67)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/urb.c (ffffffff8160fd8e)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
```
```
In drivers/usb/core/driver.c (ffffffff81613c0b)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
```
```
In drivers/power/power_supply_core.c (ffffffff8167eea2)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - drivers/power/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (ffffffff81693715)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
```
```
In drivers/md/dm.c (ffffffff816a01e9)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
  - drivers/md/dm.c:rq_completed
  - drivers/md/dm.c:rq_completed
```
```
In drivers/md/dm-stats.c (ffffffff816ad441)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In drivers/ras/debugfs.c (ffffffff816f3fb9)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_release
```
```
In net/core/sock.c (ffffffff81701829)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
```
```
In net/core/datagram.c (ffffffff8170de06)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
```
```
In net/core/neighbour.c (ffffffff81727637)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:__neigh_create
```
```
In net/netlink/af_netlink.c (ffffffff81749e00)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_mm_close
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inetpeer.c (ffffffff81757c96)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_putpeer
```
```
In net/ipv4/inet_hashtables.c (ffffffff817622ff)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81763664)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81765244)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp_output.c (ffffffff8177769a)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
```
```
In net/ipv4/raw.c (ffffffff817843de)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff8178688d)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_unhash
```
```
In net/ipv4/arp.c (ffffffff8178d5a6)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/igmp.c (ffffffff817951cb)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_stop_timer
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
```
```
In net/ipv4/inet_fragment.c (ffffffff817a1e3f)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff817a71f9)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
```
In net/xfrm/xfrm_state.c (ffffffff817b8e16)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_state_update
```
```
In net/unix/af_unix.c (ffffffff817bfd77)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_bind
```
```
In net/ipv6/addrconf.c (ffffffff817ca46a)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/ip6_fib.c (ffffffff817db8e8)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
```
```
In net/ipv6/ndisc.c (ffffffff817deca9)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/udp.c (ffffffff817e231e)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff817e630d)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (ffffffff817e96e1)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_added
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:ipv6_mc_down
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817f02c8)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff817f42dd)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff817f5f82)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
```
```
In net/ipv6/ip6mr.c (ffffffff817f8219)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/ipv6/xfrm6_policy.c (ffffffff817fc282)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818024c7)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81802b10)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mm_close
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff8180f6c3)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81810336)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
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
In arch/x86/events/core.c (ffffffff8100631e)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
```
```
In arch/x86/events/intel/core.c (ffffffff8100b643)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015bb5)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_put_constraint
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff810173dc)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff81047771)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_hcpu_update
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff8104fd7b)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff81050375)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/ftrace.c (ffffffff8105b3f0)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_code
  - arch/x86/kernel/ftrace.c:update_ftrace_func
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff8105ede7)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:longjmp_break_handler
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81075ef4)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In kernel/fork.c (ffffffff8108091b)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In kernel/exit.c (ffffffff81085492)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/signal.c (ffffffff8108fff2)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/kmod.c (ffffffff81099d56)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/workqueue.c (ffffffff8109d95d)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
```
```
In kernel/pid.c (ffffffff81fa562d)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/pid.c:pidmap_init
  - kernel/pid.c:alloc_pid
```
```
In kernel/cred.c (ffffffff810a5a31)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/async.c (ffffffff810a6688)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/core.c (ffffffff8189a061)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule_timeout
```
```
In kernel/sched/fair.c (ffffffff810c1d40)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_cpu_sd_state_idle
```
```
In kernel/sched/rt.c (ffffffff810c4a8d)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810c5f01)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff810c7efd)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/power/process.c (ffffffff810d2749)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
```
```
In kernel/irq/spurious.c (ffffffff810e2d54)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/rcu/update.c (ffffffff810e8fd9)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_unexpedite_gp
```
```
In kernel/time/clocksource.c (ffffffff810ff6e2)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/futex.c (ffffffff81109120)
Location: arch/x86/include/asm/atomic.h:101
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
In kernel/cgroup.c (ffffffff8111f0d3)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/cgroup.c:css_free_work_fn
```
```
In kernel/cgroup_freezer.c (ffffffff81121b83)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_apply_state
  - kernel/cgroup_freezer.c:freezer_css_offline
```
```
In kernel/debug/debug_core.c (ffffffff811379d7)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff8113a535)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In kernel/trace/ftrace.c (ffffffff8114a75a)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:profile_graph_entry
```
```
In kernel/trace/ring_buffer.c (ffffffff8114ec45)
Location: arch/x86/include/asm/atomic.h:101
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
In kernel/trace/trace.c (ffffffff81154615)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:s_stop
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (ffffffff811611d3)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff81161daf)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811641d9)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_kdb.c (ffffffff8117a0a4)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/bpf/syscall.c (ffffffff8118141a)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811860f1)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/core.c (ffffffff81193279)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
```
```
In kernel/events/callchain.c (ffffffff8119837a)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/uprobes.c (ffffffff811993de)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/padata.c (ffffffff8119c266)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_reorder
```
```
In mm/oom_kill.c (ffffffff811a4f88)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In mm/backing-dev.c (ffffffff811c754b)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
  - mm/backing-dev.c:bdi_unregister
```
```
In mm/mmap.c (ffffffff811e37ea)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_link_file
  - mm/mmap.c:__remove_shared_vm_struct
```
```
In mm/rmap.c (ffffffff811e8182)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In mm/frontswap.c (ffffffff811f5b4c)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff811f6780)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - mm/zswap.c:zswap_free_entry
```
```
In mm/migrate.c (ffffffff81211174)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - mm/migrate.c:buffer_migrate_page
```
```
In mm/huge_memory.c (ffffffff812166e5)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/memcontrol.c (ffffffff8121f571)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
```
```
In mm/zpool.c (ffffffff81229299)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - mm/zpool.c:zpool_put_driver
```
```
In fs/open.c (ffffffff8122ff21)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff81234f83)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff8124241a)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/namei.c:path_openat
```
```
In fs/fs-writeback.c (ffffffff81262629)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff8126dc46)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/block_dev.c (ffffffff812713fd)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_close
```
```
In fs/notify/mark.c (ffffffff81278fd7)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff8127a0ec)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8127aad8)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8127afe0)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
```
```
In fs/mbcache.c (ffffffff8129893e)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_block
```
```
In fs/coredump.c (ffffffff8129ad6e)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffffffff8129de83)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff812bd816)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff812c268f)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/inode.c (ffffffff812c9190)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/extents.c (ffffffff812f2a63)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/migrate.c (ffffffff812fc2d9)
Location: arch/x86/include/asm/atomic.h:101
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
In fs/ext4/mballoc.c (ffffffff813048ba)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/mmp.c (ffffffff81307cd1)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/indirect.c (ffffffff813082c8)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/jbd2/commit.c (ffffffff81317fd6)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81319641)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff8131b0ca)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In fs/squashfs/block.c (ffffffff81321028)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff81325edf)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff813261e1)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff813264a9)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff8132679b)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/ecryptfs/miscdev.c (ffffffff8133ff3a)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release
```
```
In fs/fuse/dev.c (ffffffff81341fe7)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:__fuse_get_req
```
```
In ipc/msg.c (ffffffff8135b550)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In security/keys/gc.c (ffffffff81363af3)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In security/keys/keyctl.c (ffffffff81367a2c)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/selinux/avc.c (ffffffff81376239)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_update_node
  - security/selinux/avc.c:avc_node_replace
  - security/selinux/avc.c:avc_node_delete
```
```
In security/selinux/hooks.c (ffffffff81377099)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_dec
```
```
In security/selinux/xfrm.c (ffffffff81392c4e)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_free
```
```
In security/tomoyo/common.c (ffffffff8139e21c)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff813a25cc)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff813a4022)
Location: arch/x86/include/asm/atomic.h:101
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
In security/tomoyo/environ.c (ffffffff813a4d0b)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff813a6223)
Location: arch/x86/include/asm/atomic.h:101
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
In security/tomoyo/gc.c (ffffffff813a6644)
Location: arch/x86/include/asm/atomic.h:101
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
In security/tomoyo/group.c (ffffffff813a6fc1)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff813a75d2)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/network.c (ffffffff813a8592)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
```
In security/tomoyo/securityfs_if.c (ffffffff813a92a3)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff813a94a2)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_cred_free
```
```
In block/bio.c (ffffffff813f42a2)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_end_io_acct
```
```
In block/blk-core.c (ffffffff813fe3b7)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In block/blk-ioc.c (ffffffff81402f4c)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - block/blk-ioc.c:exit_io_context
```
```
In block/blk-merge.c (ffffffff8140585d)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In block/blk-mq.c (ffffffff81406c0d)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_free_request
```
```
In block/blk-mq-tag.c (ffffffff8140b819)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In drivers/pci/pci.c (ffffffff81483c81)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81499b19)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
```
In drivers/pci/ats.c (ffffffff814a2a37)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff8150617b)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_notify_nmi
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
```
```
In drivers/dma/dmaengine.c (ffffffff8150dc63)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/tty/tty_buffer.c (ffffffff8153bc36)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
```
In drivers/tty/vt/keyboard.c (ffffffff81fd2892)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff8156280c)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_close
```
```
In drivers/char/agp/backend.c (ffffffff8156dd3e)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_release
```
```
In drivers/char/agp/generic.c (ffffffff81570d90)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff815746be)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
```
```
In drivers/connector/cn_queue.c (ffffffff81593064)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffff81593969)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In drivers/base/dd.c (ffffffff8159da12)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/runtime.c (ffffffff815a98d8)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In drivers/mfd/mfd-core.c (ffffffff815df842)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/nvdimm/core.c (ffffffff815eba83)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nd_iostat_end
  - drivers/nvdimm/core.c:nd_iostat_end
```
```
In drivers/nvdimm/region_devs.c (ffffffff815f022a)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In drivers/dma-buf/sync_file.c (ffffffff815fd372)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_create
```
```
In drivers/scsi/scsi_lib.c (ffffffff8160595f)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_enable_disk_events
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
```
```
In drivers/net/phy/phy.c (ffffffff8164933d)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_change
  - drivers/net/phy/phy.c:phy_change
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81654c9a)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
```
```
In drivers/usb/core/hcd.c (ffffffff8166c9e7)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/urb.c (ffffffff8166f9bc)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
```
```
In drivers/usb/core/driver.c (ffffffff8167408b)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
```
```
In drivers/power/power_supply_core.c (ffffffff816dfbb2)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/power/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (ffffffff816f4225)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In drivers/md/dm.c (ffffffff81701bee)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stats.c (ffffffff8170d9d3)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In drivers/md/dm-rq.c (ffffffff8170ee75)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:rq_completed
```
```
In drivers/ras/debugfs.c (ffffffff81758f49)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_release
```
```
In net/core/sock.c (ffffffff81768aa9)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In net/core/datagram.c (ffffffff81775526)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
```
```
In net/core/neighbour.c (ffffffff81791158)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:__neigh_create
```
```
In net/core/flow.c (ffffffff817a0ec6)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_gc_task
```
```
In net/netlink/af_netlink.c (ffffffff817ba05f)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inetpeer.c (ffffffff817c3f36)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_putpeer
```
```
In net/ipv4/inet_hashtables.c (ffffffff817cef29)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff817cfbed)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817d1bb1)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
```
```
In net/ipv4/tcp_output.c (ffffffff817e46d2)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
```
```
In net/ipv4/raw.c (ffffffff817f199e)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff817f3e0c)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_unhash
```
```
In net/ipv4/arp.c (ffffffff817fab76)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/igmp.c (ffffffff8180675a)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/inet_fragment.c (ffffffff8180faff)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff818175e8)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/xfrm/xfrm_state.c (ffffffff81826cf6)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_state_update
```
```
In net/unix/af_unix.c (ffffffff8182da33)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/addrconf.c (ffffffff8183b133)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/ip6_fib.c (ffffffff81849899)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
```
```
In net/ipv6/ndisc.c (ffffffff8184cbe8)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/udp.c (ffffffff81850bbe)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff8185446a)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (ffffffff8185bf41)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_added
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8185f113)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81863681)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff818651f5)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
```
In net/ipv6/ip6mr.c (ffffffff8186a826)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
```
```
In net/ipv6/xfrm6_policy.c (ffffffff8186bb87)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff8187378b)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81873e90)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mm_close
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81881d7d)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81882a06)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
```
```
In net/netlabel/netlabel_calipso.c (ffffffff8188370b)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
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
In arch/x86/events/core.c (ffffffff81006359)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
```
```
In arch/x86/events/intel/core.c (ffffffff8100b713)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015d85)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_put_constraint
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff810175ec)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81044288)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104563c)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_unregister_decode_chain
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff81049311)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_hcpu_update
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff8105259b)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff81052be5)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/ftrace.c (ffffffff8105e230)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_code
  - arch/x86/kernel/ftrace.c:update_ftrace_func
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81061e97)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:longjmp_break_handler
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81079ad4)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In kernel/fork.c (ffffffff810851d9)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In kernel/exit.c (ffffffff8108a402)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/signal.c (ffffffff81094f72)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/kmod.c (ffffffff8109ed06)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/workqueue.c (ffffffff810a24cd)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
```
```
In kernel/pid.c (ffffffff81fe1132)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/pid.c:pidmap_init
  - kernel/pid.c:alloc_pid
```
```
In kernel/cred.c (ffffffff810ab691)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/async.c (ffffffff810ac2e8)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/ucount.c (ffffffff810ad8bf)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (ffffffff818ce701)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule_timeout
```
```
In kernel/sched/fair.c (ffffffff810c7d4f)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_cpu_sd_state_idle
```
```
In kernel/sched/rt.c (ffffffff810caada)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810cbeb7)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff810cdee9)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/power/process.c (ffffffff810d92f9)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
```
```
In kernel/irq/spurious.c (ffffffff810e964b)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/rcu/update.c (ffffffff810efea9)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_unexpedite_gp
```
```
In kernel/time/clocksource.c (ffffffff81102552)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/futex.c (ffffffff81110910)
Location: arch/x86/include/asm/atomic.h:101
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
In kernel/cgroup.c (ffffffff81127463)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/cgroup.c:css_free_work_fn
```
```
In kernel/cgroup_freezer.c (ffffffff8112a1c3)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_apply_state
  - kernel/cgroup_freezer.c:freezer_css_offline
```
```
In kernel/debug/debug_core.c (ffffffff81141767)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/trace/ftrace.c (ffffffff81154647)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:profile_graph_entry
```
```
In kernel/trace/ring_buffer.c (ffffffff81158b8b)
Location: arch/x86/include/asm/atomic.h:101
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
In kernel/trace/trace.c (ffffffff81160349)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:s_stop
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (ffffffff8116bc33)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8116c909)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8116f539)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_kdb.c (ffffffff81185b6c)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/bpf/syscall.c (ffffffff8118d02a)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff81193646)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/core.c (ffffffff811a2a5a)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
```
```
In kernel/events/callchain.c (ffffffff811a7d5a)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/uprobes.c (ffffffff811a8dce)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/padata.c (ffffffff811abad6)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_reorder
```
```
In mm/backing-dev.c (ffffffff811d766b)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
  - mm/backing-dev.c:bdi_unregister
```
```
In mm/mmap.c (ffffffff811f37ca)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_link_file
  - mm/mmap.c:__remove_shared_vm_struct
```
```
In mm/rmap.c (ffffffff811f9502)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In mm/frontswap.c (ffffffff8120667c)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff81207130)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - mm/zswap.c:zswap_free_entry
```
```
In mm/migrate.c (ffffffff81223334)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - mm/migrate.c:buffer_migrate_page
```
```
In mm/huge_memory.c (ffffffff81228c94)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/memcontrol.c (ffffffff81231be5)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
```
```
In mm/zpool.c (ffffffff8123b839)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - mm/zpool.c:zpool_put_driver
```
```
In fs/open.c (ffffffff812424c6)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff81247b30)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff812552f3)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/namei.c:path_openat
```
```
In fs/fs-writeback.c (ffffffff81275b7e)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff81280e96)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/block_dev.c (ffffffff8128516d)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_close
```
```
In fs/notify/mark.c (ffffffff8128cbff)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff8128dc9c)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8128e688)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8128eb90)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
```
```
In fs/mbcache.c (ffffffff812ad3be)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_block
```
```
In fs/coredump.c (ffffffff812af928)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffffffff812b37c3)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff812d2e66)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff812d7cc4)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/inode.c (ffffffff812dedd0)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/extents.c (ffffffff81308a33)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/migrate.c (ffffffff81312289)
Location: arch/x86/include/asm/atomic.h:101
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
In fs/ext4/mballoc.c (ffffffff8131a87a)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/mmp.c (ffffffff8131dcc1)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/indirect.c (ffffffff8131e2b8)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/jbd2/commit.c (ffffffff8132dfc0)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff8132f631)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff813310aa)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In fs/squashfs/block.c (ffffffff81336ed8)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff8133bc8f)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff8133bf91)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff8133c259)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff8133c54b)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/ecryptfs/miscdev.c (ffffffff81355cca)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release
```
```
In fs/fuse/dev.c (ffffffff81357f41)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:__fuse_get_req
```
```
In ipc/msg.c (ffffffff81371b87)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In security/keys/gc.c (ffffffff8137a313)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In security/keys/keyctl.c (ffffffff8137e24c)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/selinux/avc.c (ffffffff8138cb69)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_update_node
  - security/selinux/avc.c:avc_node_replace
  - security/selinux/avc.c:avc_node_delete
```
```
In security/selinux/hooks.c (ffffffff8138da59)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_dec
```
```
In security/selinux/xfrm.c (ffffffff813a986e)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_free
```
```
In security/tomoyo/common.c (ffffffff813b4dfc)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff813b914c)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff813baba2)
Location: arch/x86/include/asm/atomic.h:101
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
In security/tomoyo/environ.c (ffffffff813bb88b)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff813bcda3)
Location: arch/x86/include/asm/atomic.h:101
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
In security/tomoyo/gc.c (ffffffff813bd1c4)
Location: arch/x86/include/asm/atomic.h:101
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
In security/tomoyo/group.c (ffffffff813bdb41)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff813be155)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/network.c (ffffffff813bf122)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
```
In security/tomoyo/securityfs_if.c (ffffffff813bfe13)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff813c0012)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_cred_free
```
```
In block/bio.c (ffffffff8140dc92)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_end_io_acct
```
```
In block/blk-core.c (ffffffff81417d4e)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In block/blk-ioc.c (ffffffff8141cc7c)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - block/blk-ioc.c:exit_io_context
```
```
In block/blk-merge.c (ffffffff8141fad6)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In block/blk-mq.c (ffffffff81420fec)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_free_request
```
```
In block/blk-mq-tag.c (ffffffff81425e69)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In drivers/pci/pci.c (ffffffff814a53e1)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff814bb709)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
```
In drivers/pci/ats.c (ffffffff814c4687)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff8152a2f9)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_notify_nmi
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
```
```
In drivers/dma/dmaengine.c (ffffffff81539d01)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/reset/core.c (ffffffff8155cac0)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_reset
```
```
In drivers/tty/tty_buffer.c (ffffffff815682a6)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
```
In drivers/tty/vt/keyboard.c (ffffffff82010252)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff8158ef7c)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_close
```
```
In drivers/char/agp/backend.c (ffffffff8159a3fe)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_release
```
```
In drivers/char/agp/generic.c (ffffffff8159d450)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff815a0d3e)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
```
```
In drivers/connector/cn_queue.c (ffffffff815c0924)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffff815c1229)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In drivers/base/dd.c (ffffffff815cbdc4)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/runtime.c (ffffffff815d86c8)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In drivers/mfd/mfd-core.c (ffffffff8160c4e2)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/nvdimm/region_devs.c (ffffffff8161dddd)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81634e7f)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_enable_disk_events
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
```
```
In drivers/net/phy/phy.c (ffffffff8167a591)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_change
  - drivers/net/phy/phy.c:phy_change
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8168298a)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
```
```
In drivers/usb/core/hcd.c (ffffffff8169a6e7)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/urb.c (ffffffff8169d69c)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
```
```
In drivers/usb/core/driver.c (ffffffff816a1d1b)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81710022)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (ffffffff81725925)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In drivers/md/dm.c (ffffffff8173393e)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stats.c (ffffffff8173fe93)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In drivers/md/dm-rq.c (ffffffff81740eae)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:rq_completed
```
```
In drivers/ras/debugfs.c (ffffffff81785519)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_release
```
```
In net/core/sock.c (ffffffff817959b9)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In net/core/datagram.c (ffffffff817a13c3)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/dev.c (ffffffff817ac67a)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In net/core/neighbour.c (ffffffff817bea18)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:__neigh_create
```
```
In net/core/flow.c (ffffffff817cfae2)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_gc_task
```
```
In net/netlink/af_netlink.c (ffffffff817e9a3f)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inetpeer.c (ffffffff817f3a56)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_putpeer
```
```
In net/ipv4/inet_hashtables.c (ffffffff817fed39)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff817ff9dd)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81801a61)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
```
```
In net/ipv4/tcp_output.c (ffffffff81816632)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
```
```
In net/ipv4/raw.c (ffffffff8182271e)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff8182501c)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_unhash
```
```
In net/ipv4/arp.c (ffffffff8182ba26)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/igmp.c (ffffffff818377fa)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/inet_fragment.c (ffffffff8184104f)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81848e58)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/xfrm/xfrm_state.c (ffffffff818584d6)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_state_update
```
```
In net/unix/af_unix.c (ffffffff8185f4f7)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/addrconf.c (ffffffff8186cb33)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/ip6_fib.c (ffffffff8187b72a)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
```
```
In net/ipv6/ndisc.c (ffffffff8187ea78)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/udp.c (ffffffff81882a0d)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff8188618c)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (ffffffff8188de5c)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_added
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81891211)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81895c9b)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff818978c5)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
```
In net/ipv6/ip6mr.c (ffffffff8189d676)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
```
```
In net/ipv6/xfrm6_policy.c (ffffffff8189e9e7)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff818a5193)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818a7dfd)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff818a8420)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mm_close
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818b662d)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818b72b6)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
```
```
In net/netlabel/netlabel_calipso.c (ffffffff818b7fab)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
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
In arch/x86/events/core.c (ffffffff810060f9)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
```
```
In arch/x86/events/intel/core.c (ffffffff8100b213)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff81014235)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_put_constraint
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff810158fc)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff810431bb)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104573c)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_unregister_decode_chain
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff81048cb1)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_hcpu_update
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff810520bb)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff810526f5)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/ftrace.c (ffffffff8105d860)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_code
  - arch/x86/kernel/ftrace.c:update_ftrace_func
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81060e40)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:longjmp_break_handler
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81078386)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In kernel/fork.c (ffffffff810820ff)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In kernel/exit.c (ffffffff81087451)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/signal.c (ffffffff81092002)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/workqueue.c (ffffffff8109f938)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
```
```
In kernel/pid.c (ffffffff820c1f46)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/pid.c:pidmap_init
  - kernel/pid.c:alloc_pid
```
```
In kernel/cred.c (ffffffff810a825b)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/async.c (ffffffff810a8eb6)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/ucount.c (ffffffff810aa49f)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (ffffffff81906366)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff810c19ef)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_cpu_sd_state_idle
```
```
In kernel/sched/rt.c (ffffffff810c45bf)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810c59d0)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff810ca856)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/power/process.c (ffffffff810d82e7)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
```
```
In kernel/irq/spurious.c (ffffffff810e8aeb)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/rcu/update.c (ffffffff810f0739)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_end_inkernel_boot
```
```
In kernel/rcu/srcutree.c (ffffffff810f1688)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/time/clocksource.c (ffffffff811046d4)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/futex.c (ffffffff81111e9b)
Location: arch/x86/include/asm/atomic.h:101
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
In kernel/cgroup/cgroup.c (ffffffff8112775b)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_work_fn
```
```
In kernel/cgroup/freezer.c (ffffffff8112ae78)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_apply_state
  - kernel/cgroup/freezer.c:freezer_css_offline
```
```
In kernel/debug/debug_core.c (ffffffff81142fc7)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/trace/ftrace.c (ffffffff8115686f)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:profile_graph_entry
```
```
In kernel/trace/ring_buffer.c (ffffffff8115be8c)
Location: arch/x86/include/asm/atomic.h:101
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
In kernel/trace/trace.c (ffffffff811637d0)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:s_stop
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (ffffffff8116edc3)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8116fcb9)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811726f9)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_kdb.c (ffffffff81188893)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/bpf/syscall.c (ffffffff81191eaa)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff8119a966)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/core.c (ffffffff811aa11e)
Location: arch/x86/include/asm/atomic.h:101
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
In kernel/events/callchain.c (ffffffff811af4e8)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/uprobes.c (ffffffff811b0639)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/padata.c (ffffffff811b2f36)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_reorder
```
```
In mm/backing-dev.c (ffffffff811e07c5)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/memory.c (ffffffff811f2776)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - mm/memory.c:tlb_finish_mmu
```
```
In mm/mmap.c (ffffffff811fe82a)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_link_file
  - mm/mmap.c:__remove_shared_vm_struct
```
```
In mm/mprotect.c (ffffffff811ffd1b)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff81204146)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In mm/frontswap.c (ffffffff81211e0c)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff812122a5)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - mm/zswap.c:zswap_free_entry
```
```
In mm/migrate.c (ffffffff8122db60)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In mm/huge_memory.c (ffffffff812322c0)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memcontrol.c (ffffffff8123dba5)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
```
```
In mm/zpool.c (ffffffff81247489)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - mm/zpool.c:zpool_put_driver
```
```
In fs/open.c (ffffffff8124d7be)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff81253360)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff81261320)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/namei.c:path_openat
```
```
In fs/fs-writeback.c (ffffffff8128302c)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff8128e786)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/block_dev.c (ffffffff8129249d)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_close
```
```
In fs/notify/mark.c (ffffffff81299da1)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8129ba10)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
```
```
In fs/mbcache.c (ffffffff812ba871)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/coredump.c (ffffffff812bd2b8)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffffffff812c0a49)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff812e4476)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff812e718e)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff812f5f83)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff812f6e9c)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff81302dfb)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff81311c4c)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff81313d47)
Location: arch/x86/include/asm/atomic.h:101
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
In fs/ext4/mmp.c (ffffffff813148db)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/jbd2/commit.c (ffffffff813430f4)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81344859)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff8134600a)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In fs/squashfs/block.c (ffffffff8134bbc5)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff8135078e)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff81350a7d)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff81350deb)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff813510c5)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/ecryptfs/miscdev.c (ffffffff8136a8ca)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release
```
```
In fs/fuse/dev.c (ffffffff8136cbd5)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:__fuse_get_req
```
```
In ipc/msg.c (ffffffff81384f7e)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In security/keys/gc.c (ffffffff8138dee6)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In security/keys/keyctl.c (ffffffff81391f84)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/selinux/avc.c (ffffffff813a2898)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_update_node
  - security/selinux/avc.c:avc_node_replace
  - security/selinux/avc.c:avc_node_delete
```
```
In security/selinux/hooks.c (ffffffff813a38c9)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_dec
```
```
In security/selinux/xfrm.c (ffffffff813c0419)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In security/tomoyo/common.c (ffffffff813cb7ed)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff813cfa2d)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff813d142c)
Location: arch/x86/include/asm/atomic.h:101
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
In security/tomoyo/environ.c (ffffffff813d2188)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff813d37af)
Location: arch/x86/include/asm/atomic.h:101
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
In security/tomoyo/gc.c (ffffffff813d3b58)
Location: arch/x86/include/asm/atomic.h:101
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
In security/tomoyo/group.c (ffffffff813d4468)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff813d4a19)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/network.c (ffffffff813d5a14)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
```
In security/tomoyo/securityfs_if.c (ffffffff813d66ca)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff813d694d)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_cred_free
```
```
In block/bio.c (ffffffff8141b8f2)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_end_io_acct
```
```
In block/blk-core.c (ffffffff81425b44)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In block/blk-ioc.c (ffffffff8142ac6c)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - block/blk-ioc.c:exit_io_context
```
```
In block/blk-merge.c (ffffffff8142d96a)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
```
```
In block/blk-mq.c (ffffffff8142ed83)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - block/blk-mq.c:queue_set_hctx_shared
  - block/blk-mq.c:__blk_mq_put_driver_tag
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-tag.c (ffffffff81433a1a)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-mq-sched.c (ffffffff81435491)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In drivers/pci/pci.c (ffffffff814af3f0)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff814c5f2d)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
```
In drivers/pci/ats.c (ffffffff814ce923)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff8153c17a)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
```
```
In drivers/dma/dmaengine.c (ffffffff8154d54d)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/reset/core.c (ffffffff8157157e)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff8157b850)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
```
In drivers/tty/vt/keyboard.c (ffffffff820f1d1b)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff815a305c)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_close
```
```
In drivers/char/agp/backend.c (ffffffff815ae3de)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_release
```
```
In drivers/char/agp/generic.c (ffffffff815b149d)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff815b498a)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
```
```
In drivers/connector/cn_queue.c (ffffffff815d6465)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffff815d6d69)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In drivers/base/dd.c (ffffffff815e096c)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/runtime.c (ffffffff815ed1d5)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff815f2419)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In drivers/mfd/mfd-core.c (ffffffff816205ed)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/nvdimm/region_devs.c (ffffffff816322f0)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81649153)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_enable_disk_events
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
```
```
In drivers/net/phy/phy.c (ffffffff8168ef88)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_change
  - drivers/net/phy/phy.c:phy_change
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81697d9a)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
```
```
In drivers/usb/core/hcd.c (ffffffff816af96a)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/urb.c (ffffffff816b2aac)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
```
```
In drivers/usb/core/driver.c (ffffffff816b766b)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
```
```
In drivers/power/supply/power_supply_core.c (ffffffff817283d2)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (ffffffff81739d41)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/md/md.c:md_make_request
```
```
In drivers/md/dm.c (ffffffff8174cb8e)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stats.c (ffffffff81759c2a)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In drivers/md/dm-rq.c (ffffffff8175aa5e)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:rq_completed
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81760587)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/ras/debugfs.c (ffffffff817a4ac9)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_release
```
```
In net/core/sock.c (ffffffff817b3c19)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In net/core/datagram.c (ffffffff817bf4a6)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/dev.c (ffffffff817cae1a)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In net/core/neighbour.c (ffffffff817dc26a)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:__neigh_create
```
```
In net/core/flow.c (ffffffff817eeef2)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_gc_task
```
```
In net/netlink/af_netlink.c (ffffffff81809897)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inetpeer.c (ffffffff81813e46)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_putpeer
```
```
In net/ipv4/inet_hashtables.c (ffffffff8181f04f)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8181fbfd)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81821cab)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
```
```
In net/ipv4/tcp_output.c (ffffffff81836922)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
```
```
In net/ipv4/raw.c (ffffffff8184336e)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff8184761a)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In net/ipv4/arp.c (ffffffff8184cdf6)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/igmp.c (ffffffff81858c5a)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/inet_fragment.c (ffffffff818628cf)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8186b3d3)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/xfrm/xfrm_state.c (ffffffff8187c366)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_state_update
```
```
In net/unix/af_unix.c (ffffffff81882da6)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/addrconf.c (ffffffff8189175c)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/ip6_fib.c (ffffffff818a10bb)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
```
```
In net/ipv6/ndisc.c (ffffffff818a4adc)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/udp.c (ffffffff818a91bb)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff818ac7ae)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (ffffffff818b44dc)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b77ef)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff818bc223)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff818bdcc9)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
```
In net/ipv6/ip6mr.c (ffffffff818c3bd5)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
```
```
In net/ipv6/xfrm6_policy.c (ffffffff818c4f67)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff818cbc07)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818ce689)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff818cec70)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mm_close
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818dceb3)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818ddb86)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
```
```
In net/netlabel/netlabel_calipso.c (ffffffff818de886)
Location: arch/x86/include/asm/atomic.h:101
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
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
In arch/x86/events/core.c (ffffffff81006479)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
```
```
In arch/x86/events/intel/core.c (ffffffff8100b663)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff81014a65)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_put_constraint
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81015cac)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff810467d9)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104902c)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_unregister_decode_chain
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff8104c6e1)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_hcpu_update
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81055d27)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff8105652b)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/ftrace.c (ffffffff81061520)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_code
  - arch/x86/kernel/ftrace.c:update_ftrace_func
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81064e90)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:longjmp_break_handler
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8107e6d6)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In kernel/fork.c (ffffffff8108895f)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
```
```
In kernel/exit.c (ffffffff8108e1e1)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/signal.c (ffffffff81098e92)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/workqueue.c (ffffffff810a6159)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cred.c (ffffffff810ae9db)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/async.c (ffffffff810af73c)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/ucount.c (ffffffff810b0cff)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (ffffffff819903f5)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff810c914f)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_cpu_sd_state_idle
```
```
In kernel/sched/rt.c (ffffffff810cb99a)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810cd0d0)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff810d2066)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/power/process.c (ffffffff810e03d7)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
```
```
In kernel/irq/spurious.c (ffffffff810f0ebb)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/rcu/update.c (ffffffff810fa379)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_end_inkernel_boot
```
```
In kernel/rcu/srcutree.c (ffffffff810fb3ef)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/time/clocksource.c (ffffffff8110f7b2)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/futex.c (ffffffff8111dd93)
Location: arch/x86/include/asm/atomic.h:102
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
In kernel/cgroup/cgroup.c (ffffffff81133b39)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_work_fn
```
```
In kernel/cgroup/freezer.c (ffffffff81137c7a)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_apply_state
  - kernel/cgroup/freezer.c:freezer_css_offline
```
```
In kernel/debug/debug_core.c (ffffffff8114fc77)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/watchdog_hld.c (ffffffff8115be65)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
```
```
In kernel/trace/ftrace.c (ffffffff8116338f)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:profile_graph_entry
```
```
In kernel/trace/ring_buffer.c (ffffffff81168f4c)
Location: arch/x86/include/asm/atomic.h:102
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
In kernel/trace/trace.c (ffffffff81170753)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:s_stop
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (ffffffff8117beb3)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8117ce14)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8117f899)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_kdb.c (ffffffff81196520)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/bpf/syscall.c (ffffffff8119f5db)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811aa15a)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/core.c (ffffffff811bda11)
Location: arch/x86/include/asm/atomic.h:102
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
In kernel/events/callchain.c (ffffffff811c3098)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/uprobes.c (ffffffff811c4149)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/padata.c (ffffffff811c6b89)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_reorder
```
```
In mm/backing-dev.c (ffffffff811f67b9)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/memory.c (ffffffff81209826)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - mm/memory.c:tlb_finish_mmu
```
```
In mm/mmap.c (ffffffff81216de0)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_link_file
  - mm/mmap.c:__remove_shared_vm_struct
```
```
In mm/mprotect.c (ffffffff812184f3)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff8121ceb6)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
```
```
In mm/swapfile.c (ffffffff8122b871)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - mm/swapfile.c:SYSC_swapoff
```
```
In mm/frontswap.c (ffffffff8122c7e2)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff8122cef5)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - mm/zswap.c:zswap_free_entry
```
```
In mm/migrate.c (ffffffff812496e0)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
```
```
In mm/huge_memory.c (ffffffff812531cb)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/memcontrol.c (ffffffff8125d735)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
```
```
In mm/zpool.c (ffffffff81267629)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - mm/zpool.c:zpool_put_driver
```
```
In fs/open.c (ffffffff8126f81e)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff81275463)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff81283a57)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/namei.c:path_openat
```
```
In fs/fs-writeback.c (ffffffff812a5b8b)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff812b1376)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/block_dev.c (ffffffff812b52ad)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_close
```
```
In fs/notify/mark.c (ffffffff812bd167)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify.c (ffffffff812bee20)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
```
```
In fs/mbcache.c (ffffffff812de151)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/coredump.c (ffffffff812e0bc7)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffffffff812e43fa)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff81308ea6)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8130bb8e)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff8131a5d9)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff8131b4dc)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff813277eb)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff81336460)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff81338507)
Location: arch/x86/include/asm/atomic.h:102
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
In fs/ext4/mmp.c (ffffffff8133909b)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/jbd2/commit.c (ffffffff8136772c)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81368ef9)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff8136a69f)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
```
```
In fs/squashfs/block.c (ffffffff81370221)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff81374f2d)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff81375234)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff813755b5)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff8137589f)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff81375b7c)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In fs/ecryptfs/miscdev.c (ffffffff8138f46a)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release
```
```
In fs/fuse/dev.c (ffffffff8139266c)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - fs/fuse/dev.c:__fuse_get_req
```
```
In ipc/util.c (ffffffff813a6fec)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
```
```
In ipc/msg.c (ffffffff813a925b)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In security/keys/gc.c (ffffffff813b3370)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
```
```
In security/keys/keyctl.c (ffffffff813b75d7)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/selinux/avc.c (ffffffff813c8698)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_update_node
  - security/selinux/avc.c:avc_node_replace
  - security/selinux/avc.c:avc_node_delete
```
```
In security/selinux/hooks.c (ffffffff813c96c9)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_dec
```
```
In security/selinux/xfrm.c (ffffffff813e65b9)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
```
```
In security/tomoyo/common.c (ffffffff813f1c7d)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff813f5edd)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff813f78ec)
Location: arch/x86/include/asm/atomic.h:102
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
In security/tomoyo/environ.c (ffffffff813f8698)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff813f9cbf)
Location: arch/x86/include/asm/atomic.h:102
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
In security/tomoyo/gc.c (ffffffff813fa06d)
Location: arch/x86/include/asm/atomic.h:102
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
In security/tomoyo/group.c (ffffffff813fa978)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff813faf29)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/network.c (ffffffff813fbf24)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
```
In security/tomoyo/securityfs_if.c (ffffffff813fcbfa)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff813fce7d)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_cred_free
```
```
In block/blk-flush.c (ffffffff8145485d)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (ffffffff81455e5c)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - block/blk-ioc.c:exit_io_context
```
```
In block/blk-mq.c (ffffffff8145a213)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - block/blk-mq.c:queue_set_hctx_shared
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-tag.c (ffffffff8145f6da)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-mq-sched.c (ffffffff81461241)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
```
```
In block/genhd.c (ffffffff81464260)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - block/genhd.c:part_dec_in_flight
  - block/genhd.c:part_dec_in_flight
```
```
In drivers/pci/pci.c (ffffffff814ee910)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff815064dd)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
```
In drivers/pci/ats.c (ffffffff8150eba3)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff8159ecc3)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
```
```
In drivers/dma/dmaengine.c (ffffffff815b0b3b)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/reset/core.c (ffffffff815d5935)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff815e0263)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
```
In drivers/tty/vt/keyboard.c (ffffffff826fb511)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff8160878c)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_close
```
```
In drivers/char/agp/backend.c (ffffffff81614ebe)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_release
```
```
In drivers/char/agp/generic.c (ffffffff81618077)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8161b616)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
```
```
In drivers/connector/cn_queue.c (ffffffff8163d22b)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffff8163db49)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
```
```
In drivers/base/dd.c (ffffffff81647a45)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/runtime.c (ffffffff81654585)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff816599b9)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
```
```
In drivers/mfd/mfd-core.c (ffffffff81688e33)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/nvdimm/region_devs.c (ffffffff8169ac52)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff816b2253)
Location: arch/x86/include/asm/atomic.h:102
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
In drivers/net/ppp/ppp_generic.c (ffffffff81702c8a)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
```
```
In drivers/usb/core/hcd.c (ffffffff8171afd6)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/urb.c (ffffffff8171e17c)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
```
```
In drivers/usb/core/driver.c (ffffffff81722f2b)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81799ae2)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (ffffffff817b09ba)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffff817bed6e)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stats.c (ffffffff817cbe6a)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In drivers/md/dm-rq.c (ffffffff817ccc8b)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:rq_completed
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff817d2617)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/ras/debugfs.c (ffffffff8181bc09)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_release
```
```
In net/core/skbuff.c (ffffffff81833f22)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
```
```
In net/core/dev.c (ffffffff8184465a)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
```
```
In net/core/neighbour.c (ffffffff81858053)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:__neigh_create
```
```
In net/sched/act_api.c (ffffffff8188296d)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff818887dd)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8189ebf4)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818a0cc0)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
```
```
In net/ipv4/ipmr.c (ffffffff818ebbad)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/xfrm/xfrm_state.c (ffffffff818fd096)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
```
```
In net/ipv6/route.c (ffffffff8191ce07)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_destroy
```
```
In net/ipv6/ip6_fib.c (ffffffff81923a31)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
```
```
In net/ipv6/udp.c (ffffffff8192b8f4)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff8192ef42)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193a635)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff8193f2fc)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81940d69)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
```
In net/ipv6/ip6mr.c (ffffffff81946e6e)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
```
```
In net/ipv6/seg6_hmac.c (ffffffff819509ac)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
```
In net/packet/af_packet.c (ffffffff81953b20)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mm_close
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81962aa3)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81963776)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
```
```
In net/netlabel/netlabel_calipso.c (ffffffff8196449c)
Location: arch/x86/include/asm/atomic.h:102
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
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
In arch/x86/events/core.c (ffffffff81006be3)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
```
```
In arch/x86/events/intel/core.c (ffffffff8100bd55)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015596)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_put_constraint
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81016a55)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81048d76)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104b955)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_unregister_decode_chain
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff8104f3b1)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_hcpu_update
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81058ba5)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff810592db)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/ftrace.c (ffffffff81064540)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_code
  - arch/x86/kernel/ftrace.c:update_ftrace_func
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81067a74)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:longjmp_break_handler
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81081707)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In kernel/fork.c (ffffffff8108b9f0)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - kernel/fork.c:copy_mm
```
```
In kernel/exit.c (ffffffff81091ca1)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
```
```
In kernel/signal.c (ffffffff8109c661)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/workqueue.c (ffffffff810acf9e)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cred.c (ffffffff810b574b)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/async.c (ffffffff810b65ac)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/ucount.c (ffffffff810b7af8)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (ffffffff819ecbe8)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff810d13de)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (ffffffff810d32ce)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810d4b90)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff810da0f4)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/power/process.c (ffffffff810e8977)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
```
```
In kernel/irq/spurious.c (ffffffff810f92c6)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/rcu/update.c (ffffffff81102875)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_end_inkernel_boot
```
```
In kernel/rcu/srcutree.c (ffffffff8110390f)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/time/clocksource.c (ffffffff8111b1cc)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/futex.c (ffffffff8112a791)
Location: include/asm-generic/atomic-instrumented.h:112
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
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/cgroup/freezer.c (ffffffff8114658a)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_apply_state
  - kernel/cgroup/freezer.c:freezer_css_offline
```
```
In kernel/debug/debug_core.c (ffffffff8115e867)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/watchdog_hld.c (ffffffff8116a9d5)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
```
```
In kernel/trace/ftrace.c (ffffffff811721e3)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:profile_graph_entry
```
```
In kernel/trace/ring_buffer.c (ffffffff811780cc)
Location: include/asm-generic/atomic-instrumented.h:112
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
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:s_stop
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (ffffffff8118aff3)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8118be55)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8118e989)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_kdb.c (ffffffff811abd3c)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/bpf/syscall.c (ffffffff811b3611)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811c16f1)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/sockmap.c (ffffffff811d0322)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:sock_hash_delete_elem
  - kernel/bpf/sockmap.c:sock_hash_free
  - kernel/bpf/sockmap.c:bpf_tcp_close
```
```
In kernel/events/core.c (ffffffff811ddd3c)
Location: include/asm-generic/atomic-instrumented.h:112
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
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/uprobes.c (ffffffff811e45b7)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/padata.c (ffffffff811e7559)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_reorder
```
```
In mm/backing-dev.c (ffffffff81217a99)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/memory.c (ffffffff8122a696)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - mm/memory.c:tlb_finish_mmu
```
```
In mm/mmap.c (ffffffff81237dcc)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_link_file
  - mm/mmap.c:__remove_shared_vm_struct
```
```
In mm/mprotect.c (ffffffff81239e02)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection
```
```
In mm/rmap.c (ffffffff8123ed3b)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
```
```
In mm/swapfile.c (ffffffff8124d400)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffffffff8124f492)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff8124fb14)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_free_entry
```
```
In mm/migrate.c (ffffffff8126ede1)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - mm/migrate.c:buffer_migrate_page
```
```
In mm/huge_memory.c (ffffffff8127766c)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/memcontrol.c (ffffffff81281295)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
```
```
In mm/zpool.c (ffffffff8128bdc5)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - mm/zpool.c:zpool_put_driver
```
```
In fs/open.c (ffffffff812951df)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff8129bd63)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff812aabe1)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - fs/namei.c:path_openat
```
```
In fs/fs-writeback.c (ffffffff812cc74d)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff812d91d6)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/block_dev.c (ffffffff812dd46d)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_close
```
```
In fs/notify/mark.c (ffffffff812e5d54)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify.c (ffffffff812e7d7d)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
```
```
In fs/mbcache.c (ffffffff8130a24d)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/coredump.c (ffffffff8130c92f)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffffffff81311b2b)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff81336dd0)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff81339d0d)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff8134828b)
Location: include/asm-generic/atomic-instrumented.h:112
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
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff8135548a)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff81364bbb)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff81366a9e)
Location: include/asm-generic/atomic-instrumented.h:112
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
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/jbd2/commit.c (ffffffff81395e4b)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81397566)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff81398bff)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
```
```
In fs/squashfs/block.c (ffffffff8139ea04)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff813a391a)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff813a3c21)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff813a3fbc)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff813a42bd)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff813a458a)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In fs/ecryptfs/miscdev.c (ffffffff813be50a)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release
```
```
In fs/fuse/dev.c (ffffffff813c02c3)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
```
```
In ipc/util.c (ffffffff813d681a)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - ipc/util.c:ipc_set_key_private
  - ipc/util.c:ipc_rmid
```
```
In ipc/msg.c (ffffffff813d8b9d)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In security/keys/gc.c (ffffffff813e3aad)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
```
```
In security/keys/keyctl.c (ffffffff813e8105)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/selinux/avc.c (ffffffff813f7dd2)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_update_node
  - security/selinux/avc.c:avc_node_replace
  - security/selinux/avc.c:avc_node_delete
```
```
In security/selinux/hooks.c (ffffffff813f8d15)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_dec
```
```
In security/selinux/xfrm.c (ffffffff814172d5)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
```
```
In security/tomoyo/common.c (ffffffff81422a9d)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff81426ec2)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff814288d8)
Location: include/asm-generic/atomic-instrumented.h:112
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
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff8142ac72)
Location: include/asm-generic/atomic-instrumented.h:112
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
Location: include/asm-generic/atomic-instrumented.h:112
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
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff8142bfa0)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/network.c (ffffffff8142ce83)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
```
In security/tomoyo/securityfs_if.c (ffffffff8142db23)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8142dd7e)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_cred_free
```
```
In block/blk-flush.c (ffffffff81487c9c)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (ffffffff8148929c)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - block/blk-ioc.c:exit_io_context
```
```
In block/blk-mq.c (ffffffff8148d893)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - block/blk-mq.c:queue_set_hctx_shared
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-tag.c (ffffffff81492fbb)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-mq-sched.c (ffffffff81494c62)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
```
```
In block/genhd.c (ffffffff81497b70)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - block/genhd.c:part_dec_in_flight
  - block/genhd.c:part_dec_in_flight
```
```
In drivers/pci/pci.c (ffffffff8151e59b)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81537e3a)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
```
In drivers/pci/ats.c (ffffffff81543af8)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff815d721f)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_notify_nmi
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
```
```
In drivers/dma/dmaengine.c (ffffffff815e8fa0)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/reset/core.c (ffffffff8160e6b3)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff816194f9)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
```
In drivers/tty/vt/keyboard.c (ffffffff82725831)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81641e9c)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_close
```
```
In drivers/char/agp/backend.c (ffffffff8164ec0a)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_release
```
```
In drivers/char/agp/generic.c (ffffffff81651986)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816552c6)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
```
```
In drivers/connector/cn_queue.c (ffffffff8167884b)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffff8167914b)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
```
```
In drivers/base/dd.c (ffffffff81682f96)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/runtime.c (ffffffff8168fc85)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff816955f5)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
```
```
In drivers/mfd/mfd-core.c (ffffffff816c4f85)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/nvdimm/region_devs.c (ffffffff816d7038)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff816ee4f3)
Location: include/asm-generic/atomic-instrumented.h:112
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
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
```
```
In drivers/usb/core/hcd.c (ffffffff81759c9d)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/urb.c (ffffffff8175cf0c)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
```
```
In drivers/usb/core/driver.c (ffffffff817618f8)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
```
```
In drivers/power/supply/power_supply_core.c (ffffffff817e0de2)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (ffffffff817f52eb)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffff81808f6e)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stats.c (ffffffff81814c95)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In drivers/md/dm-rq.c (ffffffff81815a4e)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:rq_completed
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff8181b2f7)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/ras/debugfs.c (ffffffff81865cf5)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_release
```
```
In net/core/skbuff.c (ffffffff8187e3af)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
```
```
In net/core/dev.c (ffffffff8188e3da)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
```
```
In net/core/neighbour.c (ffffffff818a3460)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:__neigh_create
```
```
In net/core/xdp.c (ffffffff818bae0c)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_rxq_info_unreg
```
```
In net/sched/act_api.c (ffffffff818d62c7)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff818dc213)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff818f3644)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f51f8)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
```
```
In net/ipv4/inet_fragment.c (ffffffff819391ff)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff819423a7)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/xfrm/xfrm_state.c (ffffffff81953b16)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
```
```
In net/ipv6/route.c (ffffffff81971b64)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81983ba2)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81987f7a)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81993453)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff819980dd)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81999c59)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
```
In net/ipv6/ip6mr.c (ffffffff8199eaa1)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
```
```
In net/ipv6/seg6_hmac.c (ffffffff819a9ed2)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
```
In net/packet/af_packet.c (ffffffff819ad53c)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mm_close
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819bc303)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819bcfc6)
Location: include/asm-generic/atomic-instrumented.h:112
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819bdd3c)
Location: include/asm-generic/atomic-instrumented.h:112
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
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
```
```
In arch/x86/events/intel/core.c (ffffffff8100bda5)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015ca6)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_put_constraint
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff810171d5)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
```
```
In arch/x86/xen/spinlock.c (ffffffff8102aeb0)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - arch/x86/xen/spinlock.c:xen_qlock_wait
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81049015)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_unregister_decode_chain
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8104ca71)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_hcpu_update
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81058ce2)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105c080)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_release
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff8105e7eb)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff8105efdb)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/ftrace.c (ffffffff8106a1e0)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_code
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81088317)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In kernel/fork.c (ffffffff81094096)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
```
```
In kernel/exit.c (ffffffff81099f91)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
```
```
In kernel/signal.c (ffffffff810a48c6)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/workqueue.c (ffffffff810b5d7e)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cred.c (ffffffff810beab2)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/async.c (ffffffff810bf83c)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/ucount.c (ffffffff810c0bf8)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (ffffffff81a27e35)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff810dacfe)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (ffffffff810dcf6e)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810de9e0)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff810e3c44)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/power/process.c (ffffffff810f3f87)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
```
```
In kernel/irq/spurious.c (ffffffff81104a76)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/rcu/update.c (ffffffff8110e285)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_end_inkernel_boot
```
```
In kernel/rcu/srcutree.c (ffffffff8110f22a)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/time/clocksource.c (ffffffff81126810)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/futex.c (ffffffff811362ff)
Location: include/asm-generic/atomic-instrumented.h:125
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
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/cgroup/freezer.c (ffffffff8115212a)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_apply_state
  - kernel/cgroup/freezer.c:freezer_css_offline
```
```
In kernel/debug/debug_core.c (ffffffff8116b4f7)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/watchdog_hld.c (ffffffff811779e5)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
```
```
In kernel/trace/ftrace.c (ffffffff8117f8e3)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffffffff8118548c)
Location: include/asm-generic/atomic-instrumented.h:125
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
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:s_stop
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (ffffffff81198923)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff81199873)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8119c117)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/fgraph.c (ffffffff811a0359)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
```
```
In kernel/trace/trace_kdb.c (ffffffff811ba2fc)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/bpf/syscall.c (ffffffff811c1cf1)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811d2f51)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/offload.c (ffffffff811df4b5)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffffffff811ee142)
Location: include/asm-generic/atomic-instrumented.h:125
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
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/uprobes.c (ffffffff811f4b17)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/padata.c (ffffffff811f8479)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_reorder
```
```
In mm/backing-dev.c (ffffffff8122a9a9)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/mmap.c (ffffffff8124b765)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_link_file
  - mm/mmap.c:__remove_shared_vm_struct
```
```
In mm/mmu_gather.c (ffffffff8124d0f6)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mprotect.c (ffffffff8124da2f)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff812532d0)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
```
```
In mm/swapfile.c (ffffffff8126180e)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffffffff81263922)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff812640b4)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_free_entry
```
```
In mm/huge_memory.c (ffffffff81288e69)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memcontrol.c (ffffffff81295cc5)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
```
```
In mm/zpool.c (ffffffff812a0d25)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - mm/zpool.c:zpool_put_driver
```
```
In fs/open.c (ffffffff812a9fe7)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff812b0a25)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff812bf9c7)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - fs/namei.c:path_openat
```
```
In fs/fs-writeback.c (ffffffff812e197d)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff812ee6a6)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/block_dev.c (ffffffff812f2a4d)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_close
```
```
In fs/notify/mark.c (ffffffff812fa940)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify.c (ffffffff812fc9ad)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
```
```
In fs/mbcache.c (ffffffff8131fb7d)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/coredump.c (ffffffff81322264)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffffffff813286ab)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
```
```
In fs/devpts/inode.c (ffffffff8134c2ae)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_kill_index
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/balloc.c (ffffffff8134e050)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff81350ead)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff8136043b)
Location: include/asm-generic/atomic-instrumented.h:125
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
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff8136d7b9)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff8137cebe)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff8137eeee)
Location: include/asm-generic/atomic-instrumented.h:125
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
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff8139c28c)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/commit.c (ffffffff813aeba1)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813b04cc)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff813b196f)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
```
```
In fs/squashfs/block.c (ffffffff813b7782)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff813bc71a)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff813bca21)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff813bcdbc)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff813bd0bd)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff813bd38a)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In fs/ecryptfs/miscdev.c (ffffffff813d7b4a)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release
```
```
In ipc/util.c (ffffffff813f0ea7)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - ipc/util.c:ipc_set_key_private
  - ipc/util.c:ipc_rmid
```
```
In ipc/msg.c (ffffffff813f2a1d)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In security/keys/gc.c (ffffffff813fe29d)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
```
```
In security/keys/keyctl.c (ffffffff81402905)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/selinux/avc.c (ffffffff81413882)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_update_node
  - security/selinux/avc.c:avc_node_replace
  - security/selinux/avc.c:avc_node_delete
```
```
In security/selinux/hooks.c (ffffffff81414915)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_dec
```
```
In security/selinux/xfrm.c (ffffffff81433765)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
```
```
In security/tomoyo/common.c (ffffffff8143f0fd)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff814435ca)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff81445193)
Location: include/asm-generic/atomic-instrumented.h:125
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
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff81447542)
Location: include/asm-generic/atomic-instrumented.h:125
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
Location: include/asm-generic/atomic-instrumented.h:125
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
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff81448893)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/network.c (ffffffff814497d3)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
```
In security/tomoyo/securityfs_if.c (ffffffff8144a47c)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8144a6e9)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_cred_free
```
```
In block/blk-flush.c (ffffffff814a1afd)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (ffffffff814a30cc)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - block/blk-ioc.c:exit_io_context
```
```
In block/blk-mq.c (ffffffff814a9ccf)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-tag.c (ffffffff814acedb)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In lib/sbitmap.c (ffffffff8150cbf3)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_finish_wait
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/pci/pci.c (ffffffff8153432b)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8154f1f3)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
```
In drivers/pci/ats.c (ffffffff8155ae78)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8156b67d)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
```
In drivers/acpi/apei/ghes.c (ffffffff815f02b1)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
```
```
In drivers/dma/dmaengine.c (ffffffff81602da0)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/reset/core.c (ffffffff8162b5f3)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff81636769)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
```
In drivers/tty/vt/keyboard.c (ffffffff828dd9f6)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff8165fffc)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_close
```
```
In drivers/char/agp/backend.c (ffffffff8166cd8a)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_release
```
```
In drivers/char/agp/generic.c (ffffffff8166fcd6)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816734c6)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
```
```
In drivers/connector/cn_queue.c (ffffffff8169792b)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffff8169822b)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
```
```
In drivers/base/dd.c (ffffffff816a2b80)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/power/runtime.c (ffffffff816b0015)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff816b5c65)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
```
```
In drivers/mfd/mfd-core.c (ffffffff816e6375)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/nvdimm/region_devs.c (ffffffff816f8ea5)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81712093)
Location: include/asm-generic/atomic-instrumented.h:125
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
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
```
```
In drivers/usb/core/hcd.c (ffffffff8177e312)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/urb.c (ffffffff8178153c)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
```
```
In drivers/usb/core/driver.c (ffffffff81785f10)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
```
```
In drivers/power/supply/power_supply_core.c (ffffffff8180c422)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (ffffffff81820e7b)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffff818350ce)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stats.c (ffffffff81840ca1)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81846ae7)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/ras/debugfs.c (ffffffff818858c5)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_release
```
```
In net/core/skbuff.c (ffffffff8189ef6f)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_put_abort
```
```
In net/core/dev.c (ffffffff818af2ea)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
```
```
In net/core/neighbour.c (ffffffff818c6669)
Location: include/asm-generic/atomic-instrumented.h:125
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
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
```
In net/core/sock_map.c (ffffffff818f343e)
Location: include/asm-generic/atomic-instrumented.h:125
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
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/cls_api.c (ffffffff81901604)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
```
```
In net/sched/act_api.c (ffffffff8190220f)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81908be2)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81921164)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81923428)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
```
```
In net/ipv4/inet_fragment.c (ffffffff81968dcc)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff819721a4)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197fc94)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
```
```
In net/xfrm/xfrm_state.c (ffffffff819864d6)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
```
```
In net/ipv6/route.c (ffffffff819a72b4)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
```
```
In net/ipv6/udp.c (ffffffff819ba0d1)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff819be8b0)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c97f2)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff819cea6d)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff819d0829)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
```
In net/ipv6/ip6mr.c (ffffffff819d5496)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e09fe)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
```
In net/packet/af_packet.c (ffffffff819e3eac)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mm_close
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f3574)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f4206)
Location: include/asm-generic/atomic-instrumented.h:125
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819f4edc)
Location: include/asm-generic/atomic-instrumented.h:125
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
```
```
In arch/x86/events/intel/core.c (ffffffff8100c4d5)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff810172ba)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_put_constraint
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81018965)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In arch/x86/xen/spinlock.c (ffffffff8102cc9f)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/xen/spinlock.c:xen_qlock_wait
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104c0f5)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_unregister_decode_chain
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8104f991)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_hcpu_update
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105c286)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105f594)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_release
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81061bf5)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff810623eb)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/ftrace.c (ffffffff8106da50)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_code
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108bf63)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In kernel/fork.c (ffffffff8109893d)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/exit.c (ffffffff8109e5b1)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/signal.c (ffffffff810a952f)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/workqueue.c (ffffffff810bbbf3)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cred.c (ffffffff810c49ec)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/async.c (ffffffff810c596b)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/ucount.c (ffffffff810c6cfd)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (ffffffff810d0861)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff810e20c7)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (ffffffff810e3f2c)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810e5b60)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff810ea85b)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/power/process.c (ffffffff810fc387)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
```
```
In kernel/irq/spurious.c (ffffffff8110dc87)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/rcu/update.c (ffffffff81117985)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_end_inkernel_boot
```
```
In kernel/rcu/srcutree.c (ffffffff81118f95)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/time/clocksource.c (ffffffff81131240)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/futex.c (ffffffff81141bda)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8115e7c0)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
  - kernel/cgroup/legacy_freezer.c:freezer_css_offline
```
```
In kernel/debug/debug_core.c (ffffffff811782b7)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/watchdog_hld.c (ffffffff81184845)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
```
```
In kernel/trace/ftrace.c (ffffffff8118c9d6)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffffffff81192640)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:s_stop
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (ffffffff811a64e3)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811a74b8)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811a9d1c)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/fgraph.c (ffffffff811ae1c5)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In kernel/trace/trace_kdb.c (ffffffff811c9399)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/bpf/syscall.c (ffffffff811d2341)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811e76cc)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/offload.c (ffffffff811f4ead)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffffffff81205ab5)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/uprobes.c (ffffffff8120c97d)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/padata.c (ffffffff81210999)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_reorder
```
```
In mm/backing-dev.c (ffffffff8123a615)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/mmap.c (ffffffff8125dc2c)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_link_file
  - mm/mmap.c:__remove_shared_vm_struct
```
```
In mm/mmu_gather.c (ffffffff8125f40b)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mprotect.c (ffffffff81260047)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff81265559)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In mm/swapfile.c (ffffffff8127c84a)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffffffff8127e542)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff8127f015)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_free_entry
```
```
In mm/huge_memory.c (ffffffff812a3ad4)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memcontrol.c (ffffffff812b1d06)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
```
```
In mm/zpool.c (ffffffff812bbfa5)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/zpool.c:zpool_put_driver
```
```
In fs/open.c (ffffffff812c67b7)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff812cd3aa)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff812dcb39)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/fs-writeback.c (ffffffff813000e2)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff8130fe96)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/block_dev.c (ffffffff8131437d)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_close
```
```
In fs/notify/mark.c (ffffffff8131b1ce)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8131d36d)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
```
```
In fs/mbcache.c (ffffffff813473e9)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/coredump.c (ffffffff81349eff)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffffffff8135022b)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In fs/devpts/inode.c (ffffffff81374c7e)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_kill_index
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/balloc.c (ffffffff81376a07)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff81379ba1)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff813895bc)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff81396de8)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff813a6b2e)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff813a8334)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff813c64f1)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/commit.c (ffffffff813d9098)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813da954)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff813dbfa3)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In fs/squashfs/block.c (ffffffff813e1f2b)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff813e6fc2)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff813e72c9)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff813e7668)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff813e7976)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff813e7c49)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In fs/ecryptfs/miscdev.c (ffffffff814024c0)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release
```
```
In ipc/util.c (ffffffff8141cc28)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In ipc/msg.c (ffffffff8141f84d)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In security/keys/gc.c (ffffffff8142a8d3)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In security/keys/keyctl.c (ffffffff8142f62d)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/selinux/avc.c (ffffffff814409f3)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_replace
  - security/selinux/avc.c:avc_node_delete
```
```
In security/selinux/hooks.c (ffffffff81442155)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_dec
```
```
In security/selinux/xfrm.c (ffffffff81461295)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In security/tomoyo/common.c (ffffffff8146cd7f)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff814711ed)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff81472de5)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff81475140)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff814764e0)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/network.c (ffffffff81477436)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
```
In security/tomoyo/securityfs_if.c (ffffffff8147825e)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff814783cf)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (ffffffff814d118a)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - block/blk-ioc.c:exit_io_context
```
```
In block/blk-mq.c (ffffffff814d7c79)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-tag.c (ffffffff814db1e6)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In lib/sbitmap.c (ffffffff8153b373)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_finish_wait
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/pci/pci.c (ffffffff81563802)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8157f048)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
```
In drivers/pci/ats.c (ffffffff8158b0fc)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8159bb4b)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
```
In drivers/acpi/apei/ghes.c (ffffffff8162203a)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
```
```
In drivers/dma/dmaengine.c (ffffffff816354d7)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/reset/core.c (ffffffff8165eefb)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff8166a9ba)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
```
In drivers/tty/vt/keyboard.c (ffffffff828f82e0)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81695b8c)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_close
```
```
In drivers/tty/serial/kgdboc.c (ffffffff81696325)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_post_exp_handler
```
```
In drivers/char/agp/backend.c (ffffffff816a299e)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_release
```
```
In drivers/char/agp/generic.c (ffffffff816a5754)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816a8fef)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
```
```
In drivers/connector/cn_queue.c (ffffffff816d04aa)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffff816d0dab)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In drivers/base/dd.c (ffffffff816db92c)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/power/runtime.c (ffffffff816e9eb4)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff816efa95)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In drivers/mfd/mfd-core.c (ffffffff8171fb05)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/nvdimm/region_devs.c (ffffffff8173252b)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff8174da33)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
```
```
In drivers/usb/core/hcd.c (ffffffff817bc892)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/urb.c (ffffffff817bf91f)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
```
```
In drivers/power/supply/power_supply_core.c (ffffffff8184e0a2)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (ffffffff81863247)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffff81876ef2)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stats.c (ffffffff81883ecd)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff8188989c)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/ras/debugfs.c (ffffffff818d0035)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_release
```
```
In net/core/skbuff.c (ffffffff818e979e)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_put_abort
```
```
In net/core/dev.c (ffffffff818fb122)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In net/core/neighbour.c (ffffffff81912741)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In net/core/sock_map.c (ffffffff81944afd)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_free_elem
```
```
In net/sched/cls_api.c (ffffffff81962694)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In net/sched/act_api.c (ffffffff8196335d)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81969d10)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81983b28)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81985dde)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/inet_fragment.c (ffffffff819cf858)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff819dbbe2)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e9963)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
```
```
In net/xfrm/xfrm_state.c (ffffffff819f02f8)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
```
```
In net/ipv6/route.c (ffffffff81a138e2)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a29220)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81a2d7e5)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a383e4)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81a3d725)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a3f290)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
```
In net/ipv6/ip6mr.c (ffffffff81a443f6)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a4f63d)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
```
In net/packet/af_packet.c (ffffffff81a52da0)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mm_close
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a6296e)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a6367a)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a643a0)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
```
```
In arch/x86/events/intel/core.c (ffffffff8100c905)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff81017c6a)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_put_constraint
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff810192f5)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In arch/x86/xen/spinlock.c (ffffffff8102d56f)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/xen/spinlock.c:xen_qlock_wait
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104ca85)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_unregister_decode_chain
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81050321)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_hcpu_update
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105cb96)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105fcb0)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_release
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff810624a5)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff81062c5b)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/ftrace.c (ffffffff8106f070)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_code
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108cbc3)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff810971d1)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff81099395)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In kernel/fork.c (ffffffff8109eef8)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/cpu.c (ffffffff810a458f)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In kernel/exit.c (ffffffff810a4b32)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/workqueue.c (ffffffff810c1e93)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cred.c (ffffffff810cdafc)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/async.c (ffffffff810cea4b)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/ucount.c (ffffffff810cfdcd)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (ffffffff810da811)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff810ebfc7)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (ffffffff810eebb0)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810f0f90)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff810f622b)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/power/process.c (ffffffff811087a7)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
```
```
In kernel/irq/spurious.c (ffffffff81119f47)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/rcu/update.c (ffffffff81123d65)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_end_inkernel_boot
```
```
In kernel/rcu/srcutree.c (ffffffff81125365)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/time/clocksource.c (ffffffff8113d180)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/futex.c (ffffffff8114dc53)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8116a410)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
  - kernel/cgroup/legacy_freezer.c:freezer_css_offline
```
```
In kernel/debug/debug_core.c (ffffffff81184187)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/watchdog_hld.c (ffffffff811906c5)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
```
```
In kernel/trace/ftrace.c (ffffffff811985d6)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffffffff8119e430)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:s_stop
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (ffffffff811b1cd3)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811b2ca8)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811b550c)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/fgraph.c (ffffffff811b9935)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In kernel/trace/trace_kdb.c (ffffffff811d5089)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/bpf/syscall.c (ffffffff811de8e1)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811f3e2c)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/offload.c (ffffffff81201ebd)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffffffff81212e49)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/uprobes.c (ffffffff81219c6d)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/padata.c (ffffffff8121e0de)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/padata.c:padata_find_next
```
```
In mm/backing-dev.c (ffffffff81248925)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/mmap.c (ffffffff8126c3fc)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_link_file
  - mm/mmap.c:__remove_shared_vm_struct
```
```
In mm/mmu_gather.c (ffffffff8126dc1b)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mprotect.c (ffffffff8126e937)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff81273e4e)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In mm/swapfile.c (ffffffff8128c334)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffffffff8128dfa2)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff8128ea65)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_free_entry
```
```
In mm/huge_memory.c (ffffffff812b4fd4)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memcontrol.c (ffffffff812c36c2)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
```
```
In mm/zpool.c (ffffffff812cde85)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/zpool.c:zpool_put_driver
```
```
In fs/open.c (ffffffff812d81a7)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff812dedca)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff812ee688)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/fs-writeback.c (ffffffff8131285f)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff81322e66)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/notify/mark.c (ffffffff8132de9a)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify.c (ffffffff813301ad)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
```
```
In fs/mbcache.c (ffffffff8135f54f)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/coredump.c (ffffffff8136219f)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffffffff8136853b)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In fs/devpts/inode.c (ffffffff8138cefe)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_kill_index
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/balloc.c (ffffffff8138ec77)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff813920c1)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff813a1eef)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff813af818)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff813bf9b1)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff813c11e1)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff813df8b1)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/commit.c (ffffffff813f3091)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813f49a4)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/squashfs/block.c (ffffffff813fbf5b)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff81401042)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff81401349)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff814016e8)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff814019f6)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff81401cc9)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In fs/ecryptfs/miscdev.c (ffffffff8141c3b0)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release
```
```
In ipc/util.c (ffffffff81436a78)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In ipc/msg.c (ffffffff8143966d)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In security/keys/gc.c (ffffffff81444606)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In security/keys/keyctl.c (ffffffff8144938d)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/selinux/avc.c (ffffffff8145a2c3)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_replace
  - security/selinux/avc.c:avc_node_kill
  - security/selinux/avc.c:avc_node_delete
```
```
In security/selinux/hooks.c (ffffffff8145bbc5)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_dec
```
```
In security/selinux/xfrm.c (ffffffff8147b045)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In security/tomoyo/common.c (ffffffff81486b5f)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff8148af8d)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff8148cb85)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff8148eee0)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff81490280)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/network.c (ffffffff814911d6)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
```
In security/tomoyo/securityfs_if.c (ffffffff81491f7e)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff814920ef)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (ffffffff814ea54a)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - block/blk-ioc.c:exit_io_context
```
```
In block/blk-mq.c (ffffffff814f0ff5)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-tag.c (ffffffff814f4616)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-iocost.c (ffffffff8150fcac)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (ffffffff8155c153)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_finish_wait
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/pci/pci.c (ffffffff815849c2)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff815a0a88)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
```
In drivers/pci/ats.c (ffffffff815aca28)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815bd14b)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
```
In drivers/acpi/apei/ghes.c (ffffffff81643b1a)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
```
```
In drivers/dma/dmaengine.c (ffffffff816571f3)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/reset/core.c (ffffffff816815cf)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff8168d0aa)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
```
In drivers/tty/vt/keyboard.c (ffffffff829011e1)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff816b871c)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_close
```
```
In drivers/tty/serial/kgdboc.c (ffffffff816b8eb5)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_post_exp_handler
```
```
In drivers/char/agp/backend.c (ffffffff816c572e)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_release
```
```
In drivers/char/agp/generic.c (ffffffff816c8484)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816cbd2f)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
```
```
In drivers/connector/cn_queue.c (ffffffff816f42ca)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffff816f4bcb)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In drivers/base/dd.c (ffffffff816ff8be)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/power/runtime.c (ffffffff8170df14)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In drivers/mfd/mfd-core.c (ffffffff81743dd5)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81757783)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:deactivate_labels
```
```
In drivers/scsi/scsi_lib.c (ffffffff81771be3)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
```
```
In drivers/vfio/vfio.c (ffffffff817d0ea5)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_release
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_add_container_user
  - drivers/vfio/vfio.c:vfio_group_add_container_user
```
```
In drivers/usb/core/hcd.c (ffffffff817ed0b2)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/urb.c (ffffffff817f029f)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
```
```
In drivers/power/supply/power_supply_core.c (ffffffff8187fae2)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (ffffffff81894f77)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffff818a98ae)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stats.c (ffffffff818b5ded)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff818bb84c)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff818e108a)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff818f5c55)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/ras/debugfs.c (ffffffff81902425)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_release
```
```
In net/core/skbuff.c (ffffffff8191b90e)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_put_abort
```
```
In net/core/dev.c (ffffffff8192d272)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In net/core/neighbour.c (ffffffff81944da1)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81963bc4)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In net/core/sock_map.c (ffffffff81979afd)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_free_elem
```
```
In net/sched/cls_api.c (ffffffff81995980)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_cls_offload_cnt_reset
  - net/sched/cls_api.c:tc_cls_offload_cnt_update
```
```
In net/sched/act_api.c (ffffffff81999edd)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff819a0780)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819ba317)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bc27e)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/inet_fragment.c (ffffffff81a063e8)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a12b12)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a20942)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff81a271c8)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
```
```
In net/ipv6/route.c (ffffffff81a4a4d2)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a5fd7e)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81a64351)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6ef2c)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81a7438e)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a75f00)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
```
In net/ipv6/ip6mr.c (ffffffff81a7afe6)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a862cd)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
```
In net/packet/af_packet.c (ffffffff81a89980)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mm_close
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a9954e)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a9a22a)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a9af20)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
```
```
In arch/x86/events/intel/core.c (ffffffff8100e069)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_put_event_constraints
  - arch/x86/events/intel/core.c:intel_put_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101981a)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_put_constraint
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101aa55)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
```
```
In arch/x86/xen/spinlock.c (ffffffff8102f69f)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - arch/x86/xen/spinlock.c:xen_qlock_wait
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff810548a1)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_hcpu_update
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105fdb0)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_move_task
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810657f0)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_release
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81068473)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff81068cfb)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81094193)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff8109c500)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109ea65)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
```
```
In kernel/fork.c (ffffffff810a60e1)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/cpu.c (ffffffff810ab85f)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
```
```
In kernel/exit.c (ffffffff810ac5ca)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/workqueue.c (ffffffff810c9a23)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cred.c (ffffffff810d799c)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/async.c (ffffffff810d890b)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/ucount.c (ffffffff810d9dc3)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (ffffffff810e3797)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff810f67d7)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
  - kernel/sched/fair.c:nohz_balance_exit_idle
```
```
In kernel/sched/rt.c (ffffffff810f8be4)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810fa3e3)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff810ffb7b)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/power/process.c (ffffffff811133a7)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
```
```
In kernel/irq/spurious.c (ffffffff81125c3b)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/spurious.c:misrouted_irq
```
```
In kernel/rcu/update.c (ffffffff81130941)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/update.c:rcu_end_inkernel_boot
```
```
In kernel/rcu/srcutree.c (ffffffff81132508)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/time/clocksource.c (ffffffff8114be60)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/futex.c (ffffffff8115d20d)
Location: include/asm-generic/atomic-instrumented.h:328
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
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8117bf40)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
  - kernel/cgroup/legacy_freezer.c:freezer_css_offline
```
```
In kernel/debug/debug_core.c (ffffffff81198217)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/watchdog_hld.c (ffffffff811a5265)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
```
```
In kernel/trace/ftrace.c (ffffffff811ad5a2)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_profile_alloc
```
```
In kernel/trace/ring_buffer.c (ffffffff811b67c1)
Location: include/asm-generic/atomic-instrumented.h:328
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
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_set_cpumask
  - kernel/trace/trace.c:s_stop
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (ffffffff811ca455)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811cb108)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811ce23c)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/fgraph.c (ffffffff811d26d5)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:ftrace_suspend_notifier_call
```
```
In kernel/trace/trace_kdb.c (ffffffff811f177a)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/bpf/hashtab.c (ffffffff81217fe6)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/offload.c (ffffffff81229389)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
```
```
In kernel/events/core.c (ffffffff8123c2d9)
Location: include/asm-generic/atomic-instrumented.h:328
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
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/uprobes.c (ffffffff81246050)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/watch_queue.c (ffffffff8124c942)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:free_watch
```
```
In mm/backing-dev.c (ffffffff812768a5)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/mmap.c (ffffffff8129c172)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_link_file
  - mm/mmap.c:__remove_shared_vm_struct
```
```
In mm/mmu_gather.c (ffffffff8129decd)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mprotect.c (ffffffff8129f15b)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff812a44a3)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_file_rmap
```
```
In mm/swapfile.c (ffffffff812bf333)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffffffff812c0c1b)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff812c1756)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_free_entry
```
```
In mm/huge_memory.c (ffffffff812ea4ea)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memcontrol.c (ffffffff812f9f68)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
```
```
In mm/zpool.c (ffffffff8130459c)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - mm/zpool.c:zpool_destroy_pool
  - mm/zpool.c:zpool_has_pool
```
```
In mm/mapping_dirty_helpers.c (ffffffff8130c3da)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/open.c (ffffffff8130e249)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff81315eda)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff81321422)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/namei.c:handle_truncate
```
```
In fs/fs-writeback.c (ffffffff8134c0a5)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff81359e39)
Location: include/asm-generic/atomic-instrumented.h:328
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
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8136a3fd)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
```
```
In fs/io-wq.c (ffffffff8138a3ee)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/io-wq.c:__io_worker_busy
  - fs/io-wq.c:io_worker_exit
  - fs/io-wq.c:io_worker_exit
```
```
In fs/mbcache.c (ffffffff813a512f)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/coredump.c (ffffffff813a8197)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffffffff813b082b)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
```
```
In fs/kernfs/inode.c (ffffffff813cd554)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/devpts/inode.c (ffffffff813d834e)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_kill_index
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/balloc.c (ffffffff813da229)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff813de82f)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff813edff8)
Location: include/asm-generic/atomic-instrumented.h:328
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
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff813fb830)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff8140ba45)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff8140d79a)
Location: include/asm-generic/atomic-instrumented.h:328
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
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff8142c205)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/commit.c (ffffffff814406c9)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81441ea9)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:calc_chksums
```
```
In fs/jbd2/journal.c (ffffffff814480f4)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/ecryptfs/miscdev.c (ffffffff8146af50)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release
```
```
In ipc/util.c (ffffffff81486a09)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In ipc/msg.c (ffffffff81489888)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In security/keys/gc.c (ffffffff8149563d)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
```
```
In security/keys/keyctl.c (ffffffff8149abcb)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/selinux/avc.c (ffffffff814adaee)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_flush
  - security/selinux/avc.c:avc_node_replace
```
```
In security/selinux/hooks.c (ffffffff814aed85)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_dec
```
```
In security/selinux/xfrm.c (ffffffff814d08b1)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_state_free
  - security/selinux/xfrm.c:selinux_xfrm_policy_free
```
```
In security/tomoyo/common.c (ffffffff814dd53f)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_update_manager_entry
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff814e2274)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_parse_envp
```
```
In security/tomoyo/domain.c (ffffffff814e3e63)
Location: include/asm-generic/atomic-instrumented.h:328
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
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_env
```
```
In security/tomoyo/file.c (ffffffff814e6180)
Location: include/asm-generic/atomic-instrumented.h:328
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
Location: include/asm-generic/atomic-instrumented.h:328
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
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff814e75dd)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/network.c (ffffffff814e85a6)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
```
In security/tomoyo/securityfs_if.c (ffffffff814e934e)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff814e94ef)
Location: include/asm-generic/atomic-instrumented.h:328
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
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (ffffffff815494ea)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - block/blk-ioc.c:exit_io_context
```
```
In block/blk-mq.c (ffffffff815520f8)
Location: include/asm-generic/atomic-instrumented.h:328
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
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-iocost.c (ffffffff81570dd2)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (ffffffff815e5bd3)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_finish_wait
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/pci/pci.c (ffffffff8162b59f)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81649555)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff81666fb5)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
```
```
In drivers/acpi/apei/ghes.c (ffffffff816f1978)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_rcu_free
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
```
```
In drivers/reset/core.c (ffffffff817326bf)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff8173f17a)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
```
In drivers/tty/vt/keyboard.c (ffffffff82d18504)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff8176c97c)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_close
```
```
In drivers/char/agp/backend.c (ffffffff8177a04e)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_release
```
```
In drivers/char/agp/generic.c (ffffffff8177c8f4)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff817809ff)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
```
```
In drivers/connector/cn_queue.c (ffffffff817aca52)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffff817ad415)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
```
```
In drivers/base/dd.c (ffffffff817b9458)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/power/runtime.c (ffffffff817c91cd)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:update_autosuspend
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff818177e3)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:deactivate_labels
```
```
In drivers/scsi/scsi_lib.c (ffffffff81834423)
Location: include/asm-generic/atomic-instrumented.h:328
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
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
```
```
In drivers/vfio/vfio.c (ffffffff8189baf5)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_release
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_add_container_user
  - drivers/vfio/vfio.c:vfio_group_add_container_user
```
```
In drivers/usb/core/hcd.c (ffffffff818bc3ce)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/urb.c (ffffffff818c034f)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
```
```
In drivers/power/supply/power_supply_core.c (ffffffff8194e3d2)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (ffffffff81962477)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffff81979ade)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stats.c (ffffffff81985116)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stat_for_entry
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff8198bf97)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_main_kobj_setup
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff819b418a)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819cbccd)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/ras/debugfs.c (ffffffff819d93c5)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_release
```
```
In net/core/skbuff.c (ffffffff819ed83e)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_put_abort
```
```
In net/core/dev.c (ffffffff81a00882)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
```
```
In net/core/neighbour.c (ffffffff81a1528a)
Location: include/asm-generic/atomic-instrumented.h:328
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
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/core/sock_map.c (ffffffff81a4ea77)
Location: include/asm-generic/atomic-instrumented.h:328
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
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_cb_destroy
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_cls_offload_cnt_update
```
```
In net/sched/act_api.c (ffffffff81a72cad)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/sched/act_api.c:__tcf_action_put
  - net/sched/act_api.c:__tcf_action_put
```
```
In net/netlink/af_netlink.c (ffffffff81a792fb)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aa4d9b)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa6e1d)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac9cfd)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/inet_fragment.c (ffffffff81af5fc9)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81b03a0c)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1312f)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff81b184ca)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
```
```
In net/ipv6/route.c (ffffffff81b40eb2)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81b58886)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81b5cdc7)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b67b7f)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81b6e5d5)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b707da)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
```
In net/ipv6/ip6mr.c (ffffffff81b7692c)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b81539)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
```
```
In net/packet/af_packet.c (ffffffff81b84e00)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mm_close
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b9509e)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b9565a)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81b96720)
Location: include/asm-generic/atomic-instrumented.h:328
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
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
```
```
In arch/x86/events/intel/core.c (ffffffff8100d244)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_put_event_constraints
  - arch/x86/events/intel/core.c:intel_put_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/events/intel/uncore.c (ffffffff81019e95)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_put_constraint
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101af4c)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
```
```
In arch/x86/xen/spinlock.c (ffffffff8103040f)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - arch/x86/xen/spinlock.c:xen_qlock_wait
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff810537e1)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_hcpu_update
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81063aa0)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_release
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff8106a153)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff8106a94b)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810936e3)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109a5c5)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
```
```
In kernel/fork.c (ffffffff810a1e78)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/cpu.c (ffffffff810a70df)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
```
```
In kernel/exit.c (ffffffff810a7c8a)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/workqueue.c (ffffffff810c4b73)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cred.c (ffffffff810d27cc)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/async.c (ffffffff810d3aab)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/ucount.c (ffffffff810d4f74)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (ffffffff810e12ab)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:ttwu_do_activate
```
```
In kernel/sched/fair.c (ffffffff810f4967)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
  - kernel/sched/fair.c:nohz_balance_exit_idle
```
```
In kernel/sched/rt.c (ffffffff810f6df4)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810f883a)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff810fe654)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/power/process.c (ffffffff811103f7)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
```
```
In kernel/irq/spurious.c (ffffffff8112194b)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/spurious.c:misrouted_irq
```
```
In kernel/rcu/update.c (ffffffff8112c651)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/update.c:rcu_end_inkernel_boot
```
```
In kernel/rcu/srcutree.c (ffffffff8112dcf8)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/time/clocksource.c (ffffffff811482c0)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/futex.c (ffffffff811593f3)
Location: include/asm-generic/atomic-instrumented.h:328
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
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81178d70)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
  - kernel/cgroup/legacy_freezer.c:freezer_css_offline
```
```
In kernel/debug/debug_core.c (ffffffff81195457)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/watchdog_hld.c (ffffffff811a225b)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
```
```
In kernel/trace/ftrace.c (ffffffff811aaeb2)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_profile_alloc
```
```
In kernel/trace/ring_buffer.c (ffffffff811b4651)
Location: include/asm-generic/atomic-instrumented.h:328
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
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_set_cpumask
  - kernel/trace/trace.c:s_stop
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (ffffffff811c7ac5)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811c87e8)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811cb71c)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/fgraph.c (ffffffff811cf845)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:ftrace_suspend_notifier_call
```
```
In kernel/trace/trace_kdb.c (ffffffff811f01aa)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/bpf/hashtab.c (ffffffff8121a16d)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/offload.c (ffffffff81230f19)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
```
```
In kernel/events/core.c (ffffffff81246579)
Location: include/asm-generic/atomic-instrumented.h:328
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
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/uprobes.c (ffffffff812506c0)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/watch_queue.c (ffffffff81256d82)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:free_watch
```
```
In mm/backing-dev.c (ffffffff812811a9)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_bdi_congested
```
```
In mm/mmap.c (ffffffff812a74be)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_link_file
  - mm/mmap.c:__remove_shared_vm_struct
```
```
In mm/mmu_gather.c (ffffffff812a924d)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mprotect.c (ffffffff812aa51b)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff812af498)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_file_rmap
```
```
In mm/swapfile.c (ffffffff812caf2d)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffffffff812cc63b)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff812cd286)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_free_entry
```
```
In mm/huge_memory.c (ffffffff812f5672)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memcontrol.c (ffffffff81305424)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
```
```
In mm/zpool.c (ffffffff8131035c)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - mm/zpool.c:zpool_destroy_pool
  - mm/zpool.c:zpool_has_pool
```
```
In mm/mapping_dirty_helpers.c (ffffffff8131831a)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/open.c (ffffffff8131a334)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff81321464)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff8132c9c2)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/namei.c:handle_truncate
```
```
In fs/fs-writeback.c (ffffffff81358eb9)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff81367f69)
Location: include/asm-generic/atomic-instrumented.h:328
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
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify.c (ffffffff813774fd)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
```
```
In fs/io_uring.c (ffffffff8139ab44)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_task_cancel
  - fs/io_uring.c:__io_uring_files_cancel
  - fs/io_uring.c:io_uring_cancel_task_requests
```
```
In fs/io-wq.c (ffffffff8139b33e)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/io-wq.c:__io_worker_busy
  - fs/io-wq.c:io_worker_exit
  - fs/io-wq.c:io_worker_exit
```
```
In fs/mbcache.c (ffffffff813b5e8f)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/coredump.c (ffffffff813b9208)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffffffff813c1e2b)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813c8bdb)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/kernfs/inode.c (ffffffff813df184)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/devpts/inode.c (ffffffff813e9fee)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_kill_index
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/balloc.c (ffffffff813ebefb)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff813f00d8)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff81400b9c)
Location: include/asm-generic/atomic-instrumented.h:328
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
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff8140dfa9)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff8141eee0)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff81420c00)
Location: include/asm-generic/atomic-instrumented.h:328
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
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff81444f7d)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
```
```
In fs/ext4/fast_commit.c (ffffffff81456ba0)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_stop_ineligible
```
```
In fs/jbd2/commit.c (ffffffff8145c8fa)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff8145e05c)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:calc_chksums
```
```
In fs/jbd2/journal.c (ffffffff81464c34)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_fc_release_bufs
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
```
```
In fs/ecryptfs/miscdev.c (ffffffff81485860)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release
```
```
In ipc/util.c (ffffffff814a40b9)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In ipc/msg.c (ffffffff814a6ec1)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In security/keys/gc.c (ffffffff814b309d)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
```
```
In security/keys/keyctl.c (ffffffff814b87fb)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/selinux/avc.c (ffffffff814cb56e)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_flush
  - security/selinux/avc.c:avc_node_replace
```
```
In security/selinux/hooks.c (ffffffff814cc825)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_dec
```
```
In security/selinux/xfrm.c (ffffffff814eddc1)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_state_free
  - security/selinux/xfrm.c:selinux_xfrm_policy_free
```
```
In security/tomoyo/common.c (ffffffff814fa95f)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_update_manager_entry
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff814ff5f4)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_parse_envp
```
```
In security/tomoyo/domain.c (ffffffff81501293)
Location: include/asm-generic/atomic-instrumented.h:328
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
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_env
```
```
In security/tomoyo/file.c (ffffffff81503580)
Location: include/asm-generic/atomic-instrumented.h:328
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
Location: include/asm-generic/atomic-instrumented.h:328
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
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff815049ad)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/network.c (ffffffff81505926)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
```
In security/tomoyo/securityfs_if.c (ffffffff81506677)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8150680f)
Location: include/asm-generic/atomic-instrumented.h:328
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
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (ffffffff8156530a)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - block/blk-ioc.c:exit_io_context
```
```
In block/blk-mq.c (ffffffff8156e5d6)
Location: include/asm-generic/atomic-instrumented.h:328
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
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-iocost.c (ffffffff8158bd37)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In block/mq-deadline.c (ffffffff81592c16)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_dispatch_request
```
```
In lib/sbitmap.c (ffffffff81609f93)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_finish_wait
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/pci/pci.c (ffffffff8165129f)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81bfb88f)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff81687b95)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
```
```
In drivers/acpi/apei/ghes.c (ffffffff8170ed38)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_rcu_free
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
```
```
In drivers/reset/core.c (ffffffff8174e80f)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff8175b0aa)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
```
In drivers/tty/vt/keyboard.c (ffffffff8300617d)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff8178743c)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_close
```
```
In drivers/char/agp/backend.c (ffffffff8179470e)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_release
```
```
In drivers/char/agp/generic.c (ffffffff81795a44)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8179882f)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
```
```
In drivers/connector/cn_queue.c (ffffffff817c1622)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffff817c1fa5)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
```
```
In drivers/base/dd.c (ffffffff817ce29f)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/power/runtime.c (ffffffff817ddafc)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:update_autosuspend
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81826913)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:deactivate_labels
```
```
In drivers/scsi/scsi_lib.c (ffffffff81844da3)
Location: include/asm-generic/atomic-instrumented.h:328
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
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
```
```
In drivers/vfio/vfio.c (ffffffff818aa705)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_release
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_add_container_user
  - drivers/vfio/vfio.c:vfio_group_add_container_user
```
```
In drivers/usb/core/hcd.c (ffffffff818c905e)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/urb.c (ffffffff818cbe2f)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81953db2)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (ffffffff81968db1)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffff8197e42b)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stats.c (ffffffff819891b6)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stat_for_entry
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff8198fac7)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_main_kobj_setup
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff819b67da)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81c2ea90)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/ras/debugfs.c (ffffffff819d8725)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_release
```
```
In net/core/skbuff.c (ffffffff819ed4fe)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_put_abort
```
```
In net/core/dev.c (ffffffff81a00c92)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
```
```
In net/core/neighbour.c (ffffffff81a1557a)
Location: include/asm-generic/atomic-instrumented.h:328
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
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/core/sock_map.c (ffffffff81a54a57)
Location: include/asm-generic/atomic-instrumented.h:328
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
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_cb_destroy
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_cls_offload_cnt_update
```
```
In net/sched/act_api.c (ffffffff81a7b86d)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/sched/act_api.c:__tcf_action_put
  - net/sched/act_api.c:__tcf_action_put
```
```
In net/netlink/af_netlink.c (ffffffff81a8210b)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aaf3fb)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ab14a7)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ad5c45)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/inet_fragment.c (ffffffff81b02e39)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81b11b81)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b2153f)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff81b270ba)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
```
```
In net/ipv6/route.c (ffffffff81b4f972)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81b66ebb)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81b6b607)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b763ad)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81b7d08f)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b7f110)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
```
In net/ipv6/ip6mr.c (ffffffff81b856f1)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b90d79)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
```
```
In net/packet/af_packet.c (ffffffff81b94760)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mm_close
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81ba4d09)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ba52aa)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81ba6390)
Location: include/asm-generic/atomic-instrumented.h:328
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
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
```
```
In arch/x86/events/intel/core.c (ffffffff8100dee1)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_put_event_constraints
  - arch/x86/events/intel/core.c:intel_put_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101b214)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_put_constraint
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101c2fc)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
```
```
In arch/x86/xen/spinlock.c (ffffffff81030f0f)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - arch/x86/xen/spinlock.c:xen_qlock_wait
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff810550b1)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_hcpu_update
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81064140)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_release
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff8106ac23)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff8106b38b)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810940a3)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109ad85)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
```
```
In kernel/fork.c (ffffffff810a286b)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/cpu.c (ffffffff810a817f)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
```
```
In kernel/exit.c (ffffffff810a8b6a)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/workqueue.c (ffffffff810c6409)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cred.c (ffffffff810d43ec)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/async.c (ffffffff810d5781)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/ucount.c (ffffffff810d6c53)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (ffffffff810e30c6)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:ttwu_do_activate
```
```
In kernel/sched/fair.c (ffffffff810f69d9)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
  - kernel/sched/fair.c:nohz_balance_exit_idle
```
```
In kernel/sched/rt.c (ffffffff810f8944)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810fab3a)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff81100a39)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/power/process.c (ffffffff81110e37)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
```
```
In kernel/irq/spurious.c (ffffffff81121f9b)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/rcu/update.c (ffffffff8112cbb1)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/update.c:rcu_end_inkernel_boot
```
```
In kernel/rcu/srcutree.c (ffffffff8112e248)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/time/clocksource.c (ffffffff811491ab)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/futex.c (ffffffff8115b66f)
Location: include/asm-generic/atomic-instrumented.h:328
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
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811798e0)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
  - kernel/cgroup/legacy_freezer.c:freezer_css_offline
```
```
In kernel/debug/debug_core.c (ffffffff81196467)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/watchdog_hld.c (ffffffff811a2f1b)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
```
```
In kernel/trace/ftrace.c (ffffffff811acbfb)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffffffff811b6089)
Location: include/asm-generic/atomic-instrumented.h:328
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
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_set_cpumask
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (ffffffff811c938b)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811c9b37)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811cca46)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/fgraph.c (ffffffff811d0b95)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:ftrace_suspend_notifier_call
```
```
In kernel/trace/trace_kdb.c (ffffffff811f10da)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/bpf/hashtab.c (ffffffff8121d918)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/offload.c (ffffffff812350af)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
```
```
In kernel/events/core.c (ffffffff8124ce05)
Location: include/asm-generic/atomic-instrumented.h:328
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
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/uprobes.c (ffffffff81254b50)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/watch_queue.c (ffffffff8125b21e)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:free_watch
```
```
In mm/backing-dev.c (ffffffff812862d9)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_bdi_congested
```
```
In mm/mmap.c (ffffffff812ad200)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_link_file
  - mm/mmap.c:__remove_shared_vm_struct
```
```
In mm/mmu_gather.c (ffffffff812ae6bd)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mprotect.c (ffffffff812af95b)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff812b4966)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_file_rmap
```
```
In mm/page_alloc.c (ffffffff812c21ce)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/memory_hotplug.c (ffffffff81c2d6c1)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/swapfile.c (ffffffff812d1a0b)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffffffff812d306b)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff812d3c76)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_free_entry
```
```
In mm/hugetlb.c (ffffffff812de35e)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
```
```
In mm/mempolicy.c (ffffffff812e3258)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_migrate_pages
```
```
In mm/migrate.c (ffffffff812f8bfb)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
```
In mm/huge_memory.c (ffffffff812fbcae)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memcontrol.c (ffffffff8130acfe)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
```
```
In mm/zpool.c (ffffffff8131641c)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - mm/zpool.c:zpool_destroy_pool
  - mm/zpool.c:zpool_has_pool
```
```
In mm/mapping_dirty_helpers.c (ffffffff8131e50a)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/open.c (ffffffff81320414)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff81327204)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff813367d5)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/namei.c:do_open
```
```
In fs/fs-writeback.c (ffffffff81360059)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff8136e959)
Location: include/asm-generic/atomic-instrumented.h:328
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
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_cancel
  - fs/io_uring.c:io_uring_cancel_sqpoll
  - fs/io_uring.c:io_clean_op
```
```
In fs/io-wq.c (ffffffff813a24bd)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_exit_workers
  - fs/io-wq.c:create_io_worker
  - fs/io-wq.c:create_worker_cb
```
```
In fs/mbcache.c (ffffffff813bce6f)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/coredump.c (ffffffff813c0113)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffffffff813c89eb)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813cfc1a)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/kernfs/inode.c (ffffffff813e5d10)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/devpts/inode.c (ffffffff813f0b2e)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_kill_index
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/balloc.c (ffffffff813f2429)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff813f6365)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff81407120)
Location: include/asm-generic/atomic-instrumented.h:328
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
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff81414169)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff814258ee)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff814273bb)
Location: include/asm-generic/atomic-instrumented.h:328
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
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff8144a89e)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
```
```
In fs/ext4/fast_commit.c (ffffffff8145c550)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_stop_ineligible
```
```
In fs/jbd2/commit.c (ffffffff81461f64)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff814637cc)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff8146a3c4)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_fc_release_bufs
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
```
```
In fs/ecryptfs/miscdev.c (ffffffff8148b2d0)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release
```
```
In ipc/util.c (ffffffff814a9fe0)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In ipc/msg.c (ffffffff814ace11)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In security/keys/gc.c (ffffffff814b8edd)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
```
```
In security/keys/keyctl.c (ffffffff814be658)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/selinux/avc.c (ffffffff814d1b9e)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_flush
  - security/selinux/avc.c:avc_node_replace
```
```
In security/selinux/hooks.c (ffffffff814d2e55)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_dec
```
```
In security/selinux/xfrm.c (ffffffff814f4b31)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_state_free
  - security/selinux/xfrm.c:selinux_xfrm_policy_free
```
```
In security/tomoyo/common.c (ffffffff8150155f)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff8150671f)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff81507d25)
Location: include/asm-generic/atomic-instrumented.h:328
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
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff8150a152)
Location: include/asm-generic/atomic-instrumented.h:328
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
Location: include/asm-generic/atomic-instrumented.h:328
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
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff8150b52d)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/network.c (ffffffff8150c466)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
```
In security/tomoyo/securityfs_if.c (ffffffff8150d1b7)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8150d34f)
Location: include/asm-generic/atomic-instrumented.h:328
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
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (ffffffff8156d97a)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - block/blk-ioc.c:exit_io_context
```
```
In block/blk-mq.c (ffffffff81576181)
Location: include/asm-generic/atomic-instrumented.h:328
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
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-iocost.c (ffffffff81592bf7)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (ffffffff815ed023)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_finish_wait
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/pci/pci.c (ffffffff81633cf1)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81bed71b)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8166a805)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
```
```
In drivers/acpi/apei/ghes.c (ffffffff816efe6c)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_rcu_free
```
```
In drivers/xen/events/events_base.c (ffffffff81717971)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
```
```
In drivers/reset/core.c (ffffffff8173232b)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff8173ef4a)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
```
In drivers/tty/vt/keyboard.c (ffffffff83210d08)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff8176adac)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_close
```
```
In drivers/char/agp/backend.c (ffffffff817773de)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_release
```
```
In drivers/char/agp/generic.c (ffffffff81778704)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8177b54f)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
```
```
In drivers/connector/cn_queue.c (ffffffff817a4af2)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffff817a541b)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
```
```
In drivers/base/dd.c (ffffffff817b1d85)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/power/runtime.c (ffffffff817c1e7c)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:update_autosuspend
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81809b73)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:deactivate_labels
```
```
In drivers/scsi/scsi_lib.c (ffffffff81827f33)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_enable_disk_events
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81882b67)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
```
```
In drivers/vfio/vfio.c (ffffffff8188dea5)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_release
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_add_container_user
  - drivers/vfio/vfio.c:vfio_group_add_container_user
```
```
In drivers/usb/core/hcd.c (ffffffff818ac68e)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/urb.c (ffffffff818af44f)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81937c42)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (ffffffff8194ce71)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffff8196225b)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stats.c (ffffffff8196d893)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stat_for_entry
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81974182)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff8199af8a)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81c20d07)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/ras/debugfs.c (ffffffff819be8a5)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_release
```
```
In net/core/skbuff.c (ffffffff819d5779)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
```
```
In net/core/dev.c (ffffffff819e7462)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
```
```
In net/core/neighbour.c (ffffffff819fc0da)
Location: include/asm-generic/atomic-instrumented.h:328
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
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/core/sock_map.c (ffffffff81a50677)
Location: include/asm-generic/atomic-instrumented.h:328
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
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_cb_destroy
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_cls_offload_cnt_update
```
```
In net/sched/act_api.c (ffffffff81a6457d)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/sched/act_api.c:__tcf_action_put
  - net/sched/act_api.c:__tcf_action_put
```
```
In net/netlink/af_netlink.c (ffffffff81a6b1f3)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81a9a70b)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9c7e5)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac0ca5)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/inet_fragment.c (ffffffff81aee730)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81b00430)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0f163)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff81b14cda)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
```
```
In net/ipv6/route.c (ffffffff81b3d6a2)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81b55091)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81b59951)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b64dde)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81b6bc29)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b6df50)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
```
In net/ipv6/ip6mr.c (ffffffff81b74275)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b7ff80)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
```
```
In net/packet/af_packet.c (ffffffff81b83840)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mm_close
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b93b4f)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b9440b)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81b95520)
Location: include/asm-generic/atomic-instrumented.h:328
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
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
```
```
In arch/x86/events/intel/core.c (ffffffff8100e605)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_put_event_constraints
  - arch/x86/events/intel/core.c:intel_put_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101db54)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_put_constraint
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101f434)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
```
```
In arch/x86/xen/spinlock.c (ffffffff810360af)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - arch/x86/xen/spinlock.c:xen_qlock_wait
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8105da23)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_hcpu_update
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106e130)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_release
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff810755a3)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff81075eeb)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810a3ea3)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810ab065)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
```
```
In kernel/cpu.c (ffffffff810b9c2f)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
```
```
In kernel/workqueue.c (ffffffff810d90c9)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
```
```
In kernel/async.c (ffffffff810e89a1)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/core.c (ffffffff810f9ad3)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:ttwu_do_activate
```
```
In kernel/sched/fair.c (ffffffff81110913)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
  - kernel/sched/fair.c:nohz_balance_exit_idle
```
```
In kernel/sched/rt.c (ffffffff81113f24)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff81115b7a)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff8111cadf)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/power/process.c (ffffffff81130923)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
```
```
In kernel/printk/printk.c (ffffffff811393af)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
```
```
In kernel/irq/spurious.c (ffffffff8114254b)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/rcu/update.c (ffffffff8114d8b1)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/update.c:rcu_end_inkernel_boot
```
```
In kernel/rcu/srcutree.c (ffffffff8114f705)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/time/clocksource.c (ffffffff8116d345)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/futex.c (ffffffff811801ad)
Location: include/linux/atomic/atomic-instrumented.h:242
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
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811a1200)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
  - kernel/cgroup/legacy_freezer.c:freezer_css_offline
```
```
In kernel/debug/debug_core.c (ffffffff811bf407)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/watchdog_hld.c (ffffffff811cc74b)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
```
```
In kernel/trace/ftrace.c (ffffffff811d685b)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffffffff811e02c7)
Location: include/linux/atomic/atomic-instrumented.h:242
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
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_set_cpumask
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (ffffffff811f4dba)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811f562a)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811f9195)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/fgraph.c (ffffffff811fd7d5)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:ftrace_suspend_notifier_call
```
```
In kernel/trace/trace_kdb.c (ffffffff8122219c)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/trace/trace_dynevent.c (ffffffff812223fd)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - kernel/trace/trace_dynevent.c:trace_event_dyn_put_ref
```
```
In kernel/bpf/hashtab.c (ffffffff81256a02)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/offload.c (ffffffff8126f1df)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
```
```
In kernel/events/core.c (ffffffff81289637)
Location: include/linux/atomic/atomic-instrumented.h:242
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
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/uprobes.c (ffffffff81290590)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/watch_queue.c (ffffffff8129701e)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:free_watch
```
```
In mm/page-writeback.c (ffffffff812a826a)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/backing-dev.c (ffffffff812c556b)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_bdi_congested
```
```
In mm/mmap.c (ffffffff812ee946)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mmu_gather.c (ffffffff812efe5d)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mprotect.c (ffffffff812f11a3)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff812f6546)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_file_rmap
```
```
In mm/page_alloc.c (ffffffff81305b54)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/memory_hotplug.c (ffffffff81d4bf93)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/swapfile.c (ffffffff81317164)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffffffff81318a7b)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff81319926)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_free_entry
```
```
In mm/mempolicy.c (ffffffff8132a644)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_migrate_pages
```
```
In mm/migrate.c (ffffffff8134325b)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
```
In mm/huge_memory.c (ffffffff81345aa1)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memcontrol.c (ffffffff81353414)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
```
```
In mm/zpool.c (ffffffff81362599)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - mm/zpool.c:zpool_destroy_pool
  - mm/zpool.c:zpool_has_pool
```
```
In mm/secretmem.c (ffffffff81366335)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_release
```
```
In mm/mapping_dirty_helpers.c (ffffffff8136b8ea)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/open.c (ffffffff8136d9d3)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff81374aab)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff813841b5)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - fs/namei.c:do_open
```
```
In fs/fs-writeback.c (ffffffff813b0651)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - fs/fs-writeback.c:cleanup_offline_cgwb
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/buffer.c (ffffffff813bd7e5)
Location: include/linux/atomic/atomic-instrumented.h:242
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
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/io_uring.c (ffffffff81cc5e96)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_cancel_generic
  - fs/io_uring.c:io_clean_op
```
```
In fs/io-wq.c (ffffffff813f171b)
Location: include/linux/atomic/atomic-instrumented.h:242
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
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/coredump.c (ffffffff8140ff43)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffffffff81419153)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81420ff7)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/kernfs/inode.c (ffffffff81437890)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/devpts/inode.c (ffffffff81442a1e)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_kill_index
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/balloc.c (ffffffff814436a3)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_should_retry_alloc
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff81448bf0)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff8145995e)
Location: include/linux/atomic/atomic-instrumented.h:242
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
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff814674c9)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff8147953f)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff8147b04b)
Location: include/linux/atomic/atomic-instrumented.h:242
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
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff8149e35f)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff814b745a)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff814b8d5d)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff814c0b24)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_fc_release_bufs
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
```
```
In fs/ecryptfs/miscdev.c (ffffffff814e2b00)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release
```
```
In fs/fuse/inode.c (ffffffff814f5dd9)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_sync_fs_writes
```
```
In ipc/util.c (ffffffff81502490)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In ipc/msg.c (ffffffff815052fc)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In security/keys/gc.c (ffffffff8151170d)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
```
```
In security/keys/keyctl.c (ffffffff81517078)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/selinux/avc.c (ffffffff8152a92f)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_flush
  - security/selinux/avc.c:avc_node_replace
```
```
In security/selinux/hooks.c (ffffffff8152bb15)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_dec
```
```
In security/selinux/xfrm.c (ffffffff8154f511)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_state_free
  - security/selinux/xfrm.c:selinux_xfrm_policy_free
```
```
In security/tomoyo/common.c (ffffffff8155cb7f)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff8156361f)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff81564f32)
Location: include/linux/atomic/atomic-instrumented.h:242
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
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff8156775d)
Location: include/linux/atomic/atomic-instrumented.h:242
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
Location: include/linux/atomic/atomic-instrumented.h:242
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
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff81568d89)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/network.c (ffffffff81569f3e)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
```
In security/tomoyo/securityfs_if.c (ffffffff8156ad05)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8156ae8f)
Location: include/linux/atomic/atomic-instrumented.h:242
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
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (ffffffff815d1f6a)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - block/blk-ioc.c:exit_io_context
```
```
In block/blk-mq.c (ffffffff815dad45)
Location: include/linux/atomic/atomic-instrumented.h:242
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
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-iocost.c (ffffffff815fa095)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (ffffffff81659f43)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_finish_wait
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/pci/pci.c (ffffffff816a3eb3)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81ce8445)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff816deae2)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
```
```
In drivers/acpi/apei/ghes.c (ffffffff81769f22)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_rcu_free
```
```
In drivers/xen/events/events_base.c (ffffffff81795004)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
```
```
In drivers/reset/core.c (ffffffff817b2b1a)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff817bf6da)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
```
In drivers/tty/vt/keyboard.c (ffffffff832f9e53)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff817f047c)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_close
```
```
In drivers/char/agp/backend.c (ffffffff817fd17e)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_release
```
```
In drivers/char/agp/generic.c (ffffffff817fe5b1)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff818015ef)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
```
```
In drivers/connector/cn_queue.c (ffffffff81830472)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffff81830d9b)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
```
```
In drivers/base/dd.c (ffffffff8183b354)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/runtime.c (ffffffff8184bd2c)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:update_autosuspend
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81894023)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:deactivate_labels
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b3893)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_enable_disk_events
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81914507)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
```
```
In drivers/vfio/vfio.c (ffffffff819214e5)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_release
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_add_container_user
  - drivers/vfio/vfio.c:vfio_group_add_container_user
```
```
In drivers/usb/core/hcd.c (ffffffff819416de)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/urb.c (ffffffff8194459f)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
```
```
In drivers/power/supply/power_supply_core.c (ffffffff819dbf12)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (ffffffff819f4874)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - drivers/md/md.c:md_release
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffff81a0939b)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stats.c (ffffffff81a16135)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stat_for_entry
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81a1ce82)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81a478ca)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d326f3)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/ras/debugfs.c (ffffffff81a6de35)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_release
```
```
In net/core/skbuff.c (ffffffff81a853d9)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
```
```
In net/core/dev.c (ffffffff81a97e52)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
```
```
In net/core/neighbour.c (ffffffff81aae141)
Location: include/linux/atomic/atomic-instrumented.h:242
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
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/core/sock_map.c (ffffffff81b09205)
Location: include/linux/atomic/atomic-instrumented.h:242
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
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_cb_destroy
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_cls_offload_cnt_update
```
```
In net/sched/act_api.c (ffffffff81b1d98d)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - net/sched/act_api.c:__tcf_action_put
  - net/sched/act_api.c:__tcf_action_put
```
```
In net/netlink/af_netlink.c (ffffffff81b24813)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81b55b7b)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b57ec2)
Location: include/linux/atomic/atomic-instrumented.h:242
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
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba5797)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/inet_fragment.c (ffffffff81baeae0)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/fib_rules.c (ffffffff81bbcdc9)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_delete
```
```
In net/ipv4/ipmr.c (ffffffff81bc2520)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd2563)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff81bd8d0a)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
```
```
In net/ipv6/route.c (ffffffff81c03ee2)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81c1db6a)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81c20f7a)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2d01d)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81c33a9c)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81c35e55)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
```
In net/ipv6/ioam6.c (ffffffff81c39ab0)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/ip6mr.c (ffffffff81c3eb24)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81c4b820)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
```
```
In net/packet/af_packet.c (ffffffff81c4f910)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mm_close
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81c602ef)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81c60bab)
Location: include/linux/atomic/atomic-instrumented.h:242
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81c61d20)
Location: include/linux/atomic/atomic-instrumented.h:242
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
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
```
```
In arch/x86/events/intel/core.c (ffffffff8100f997)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_put_event_constraints
  - arch/x86/events/intel/core.c:intel_put_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/events/intel/uncore.c (ffffffff810205b4)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_put_constraint
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81022184)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
```
```
In arch/x86/xen/spinlock.c (ffffffff8103beaf)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - arch/x86/xen/spinlock.c:xen_qlock_wait
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8106a113)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_hcpu_update
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8107b960)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_release
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81084008)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff81084aca)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810b85af)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810c0ab5)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
```
```
In kernel/cpu.c (ffffffff810d0737)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
```
```
In kernel/async.c (ffffffff81103401)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/core.c (ffffffff8111601f)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:ttwu_do_activate
```
```
In kernel/sched/fair.c (ffffffff8112cab4)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
  - kernel/sched/fair.c:nohz_balance_exit_idle
```
```
In kernel/sched/build_policy.c (ffffffff81136758)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:rq_offline_dl
  - kernel/sched/build_policy.c:rq_offline_rt
```
```
In kernel/sched/build_utility.c (ffffffff81148ef4)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:cpupri_set
```
```
In kernel/power/process.c (ffffffff81152193)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
```
```
In kernel/printk/printk.c (ffffffff8115bc25)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
```
```
In kernel/irq/spurious.c (ffffffff81165f6c)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/rcu/update.c (ffffffff811745df)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/update.c:rcu_end_inkernel_boot
```
```
In kernel/rcu/srcutree.c (ffffffff81175b28)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier_one_cpu
```
```
In kernel/time/clocksource.c (ffffffff811a0f1d)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/futex/core.c (ffffffff811b32c6)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_q_unlock
  - kernel/futex/core.c:__futex_unqueue
```
```
In kernel/futex/requeue.c (ffffffff811b64bb)
Location: include/linux/atomic/atomic-instrumented.h:255
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
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811d1aae)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
  - kernel/cgroup/legacy_freezer.c:freezer_css_offline
```
```
In kernel/debug/debug_core.c (ffffffff811f2847)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/watchdog_hld.c (ffffffff81200653)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
```
```
In kernel/trace/ftrace.c (ffffffff8120ba57)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffffffff812174e6)
Location: include/linux/atomic/atomic-instrumented.h:255
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
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_set_cpumask
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (ffffffff8122def1)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8122eeac)
Location: include/linux/atomic/atomic-instrumented.h:255
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
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/fgraph.c (ffffffff812380e5)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:ftrace_suspend_notifier_call
```
```
In kernel/trace/trace_kdb.c (ffffffff81261ec0)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/trace/trace_dynevent.c (ffffffff8126219d)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - kernel/trace/trace_dynevent.c:trace_event_dyn_put_ref
```
```
In kernel/bpf/hashtab.c (ffffffff8129f3bf)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/offload.c (ffffffff812be487)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
```
```
In kernel/events/core.c (ffffffff812dce7f)
Location: include/linux/atomic/atomic-instrumented.h:255
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
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/uprobes.c (ffffffff812e539e)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/watch_queue.c (ffffffff812ed688)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:free_watch
```
```
In mm/page-writeback.c (ffffffff813008fb)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_end_writeback
```
```
In mm/vmscan.c (ffffffff81310d9e)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_throttle
```
```
In mm/mmap.c (ffffffff81351d62)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:unlink_file_vma
```
```
In mm/mmu_gather.c (ffffffff8135333c)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/rmap.c (ffffffff8135c3f8)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_file_rmap
```
```
In mm/page_alloc.c (ffffffff81371d99)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_contig_migrate_range
```
```
In mm/memory_hotplug.c (ffffffff81f1b9c3)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/swapfile.c (ffffffff813828a1)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffffffff81384109)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff81384c85)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_free_entry
```
```
In mm/mempolicy.c (ffffffff81399f87)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_migrate_pages
```
```
In mm/migrate.c (ffffffff813b5a88)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
```
In mm/huge_memory.c (ffffffff813bbb90)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memcontrol.c (ffffffff813cdf44)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
```
```
In mm/zpool.c (ffffffff813df002)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - mm/zpool.c:zpool_destroy_pool
  - mm/zpool.c:zpool_has_pool
```
```
In mm/secretmem.c (ffffffff813e3355)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_release
```
```
In mm/mapping_dirty_helpers.c (ffffffff813e9a6e)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/open.c (ffffffff813eba27)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff813f38a9)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff81405301)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - fs/namei.c:do_open
```
```
In fs/fs-writeback.c (ffffffff814353db)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - fs/fs-writeback.c:cleanup_offline_cgwb
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/buffer.c (ffffffff814439c5)
Location: include/linux/atomic/atomic-instrumented.h:255
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
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/mbcache.c (ffffffff81481ba9)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_or_get
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/coredump.c (ffffffff814858f5)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffffffff8148fb9a)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81498e8d)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/kernfs/inode.c (ffffffff814b2608)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/devpts/inode.c (ffffffff814be7ae)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_kill_index
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/balloc.c (ffffffff814bf504)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_should_retry_alloc
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff814c5a30)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff814d765d)
Location: include/linux/atomic/atomic-instrumented.h:255
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
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff814e70cc)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff814f5b3a)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff814fd49f)
Location: include/linux/atomic/atomic-instrumented.h:255
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
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff81524965)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff81540f99)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff815429b8)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff8154b3bc)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_fc_release_bufs
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
```
```
In fs/ecryptfs/miscdev.c (ffffffff81570dea)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release
```
```
In fs/fuse/inode.c (ffffffff81584ba5)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_sync_fs_writes
```
```
In ipc/util.c (ffffffff81593d1b)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
```
```
In ipc/msg.c (ffffffff81596cc9)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In security/keys/gc.c (ffffffff815a39fd)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
```
```
In security/keys/keyctl.c (ffffffff815a99aa)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/selinux/avc.c (ffffffff815c02f8)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_flush
  - security/selinux/avc.c:avc_node_replace
```
```
In security/selinux/hooks.c (ffffffff815c1825)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_dec
```
```
In security/selinux/xfrm.c (ffffffff815e87e1)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_state_free
  - security/selinux/xfrm.c:selinux_xfrm_policy_free
```
```
In security/tomoyo/common.c (ffffffff815f7c8c)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff815fe757)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff816006ed)
Location: include/linux/atomic/atomic-instrumented.h:255
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
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff81603307)
Location: include/linux/atomic/atomic-instrumented.h:255
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
Location: include/linux/atomic/atomic-instrumented.h:255
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
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff81604aca)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/network.c (ffffffff81605dce)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
```
In security/tomoyo/securityfs_if.c (ffffffff81606d58)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff81606f1f)
Location: include/linux/atomic/atomic-instrumented.h:255
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
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/blk-mq.c:blk_mq_dispatch_wake
```
```
In block/blk-iocost.c (ffffffff816ac34f)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In io_uring/io_uring.c (ffffffff81e92c10)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_clean_op
```
```
In io_uring/io-wq.c (ffffffff816da805)
Location: include/linux/atomic/atomic-instrumented.h:255
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
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_finish_wait
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/pci/pci.c (ffffffff817c6267)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81eaf4c5)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff81816002)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
```
```
In drivers/acpi/apei/ghes.c (ffffffff8189f298)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_rcu_free
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
```
```
In drivers/xen/events/events_base.c (ffffffff818cdcbc)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
```
```
In drivers/reset/core.c (ffffffff818ee50a)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_reset
```
```
In drivers/tty/tty_buffer.c (ffffffff818fbbfa)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
```
In drivers/tty/vt/keyboard.c (ffffffff834b26b7)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81930859)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_close
```
```
In drivers/char/agp/backend.c (ffffffff8193c0ce)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_release
```
```
In drivers/char/agp/generic.c (ffffffff8193db6e)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81940c4a)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
```
```
In drivers/connector/cn_queue.c (ffffffff8197173e)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffff819721f9)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
```
```
In drivers/base/dd.c (ffffffff8197d8e4)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/runtime.c (ffffffff8199166b)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:update_autosuspend
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff819ddf03)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:deactivate_labels
```
```
In drivers/cxl/core/suspend.c (ffffffff819f63a5)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/cxl/core/suspend.c:cxl_mem_active_dec
```
```
In drivers/scsi/scsi_lib.c (ffffffff819fea43)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_enable_disk_events
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a67ef5)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
```
```
In drivers/usb/core/hcd.c (ffffffff81a99e81)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/urb.c (ffffffff81a9ccef)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81b3fa12)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (ffffffff81b5d803)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/md/md.c:md_release
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffff81b72c13)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stats.c (ffffffff81b7f4bf)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stat_for_entry
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81b85f69)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81bb5849)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81efebdd)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/ras/debugfs.c (ffffffff81bdec95)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_release
```
```
In drivers/hte/hte.c (ffffffff81be4b45)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/hte/hte.c:hte_ts_put
```
```
In net/core/skbuff.c (ffffffff81bfb4b9)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
```
```
In net/core/dev.c (ffffffff81c0f830)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
```
```
In net/core/neighbour.c (ffffffff81c28769)
Location: include/linux/atomic/atomic-instrumented.h:255
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
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
```
```
In net/core/sock_map.c (ffffffff81c8f295)
Location: include/linux/atomic/atomic-instrumented.h:255
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
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_cb_destroy
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_cls_offload_cnt_update
```
```
In net/sched/act_api.c (ffffffff81ca56be)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - net/sched/act_api.c:__tcf_action_put
  - net/sched/act_api.c:__tcf_action_put
```
```
In net/netlink/af_netlink.c (ffffffff81cadeb6)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce5ed3)
Location: include/linux/atomic/atomic-instrumented.h:255
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
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/fib_semantics.c (ffffffff81d38143)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/inet_fragment.c (ffffffff81d41dcf)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
```
```
In net/ipv4/fib_rules.c (ffffffff81d51439)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_delete
```
```
In net/ipv4/ipmr.c (ffffffff81d572cc)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d68275)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff81d6f7e8)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
```
```
In net/ipv6/udp.c (ffffffff81dba189)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81dbdd3a)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dca400)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81dd1314)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81dd38d5)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
```
In net/ipv6/ioam6.c (ffffffff81dd77df)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81ddd61e)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:mif6_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81deb1fb)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81df0380)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mm_close
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81e0289b)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81e030ec)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81e0435a)
Location: include/linux/atomic/atomic-instrumented.h:255
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
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
```
```
In arch/x86/events/intel/core.c (ffffffff810133c7)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_put_event_constraints
  - arch/x86/events/intel/core.c:intel_put_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/events/intel/uncore.c (ffffffff81024ed4)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_put_constraint
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81026d44)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
```
```
In arch/x86/xen/spinlock.c (ffffffff8104473f)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - arch/x86/xen/spinlock.c:xen_qlock_wait
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81079ec3)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_hcpu_update
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108cd50)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_release
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81096e98)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff81097e9e)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810d3e2f)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810dcc35)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
```
```
In kernel/cpu.c (ffffffff810ef017)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
```
```
In kernel/async.c (ffffffff81128a91)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/core.c (ffffffff8113d4b6)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:ttwu_do_activate
```
```
In kernel/sched/fair.c (ffffffff811567a4)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
  - kernel/sched/fair.c:nohz_balance_exit_idle
```
```
In kernel/sched/build_policy.c (ffffffff81160d88)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:rq_offline_dl
  - kernel/sched/build_policy.c:rq_offline_rt
```
```
In kernel/sched/build_utility.c (ffffffff81177794)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:cpupri_set
```
```
In kernel/printk/printk.c (ffffffff8118e645)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
```
```
In kernel/irq/spurious.c (ffffffff8119a05c)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/rcu/update.c (ffffffff811ac005)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_end_inkernel_boot
```
```
In kernel/rcu/srcutree.c (ffffffff811ac9b8)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier_one_cpu
```
```
In kernel/time/clocksource.c (ffffffff811e07d6)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/futex/core.c (ffffffff811f4206)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_q_unlock
  - kernel/futex/core.c:__futex_unqueue
```
```
In kernel/futex/requeue.c (ffffffff811f75fb)
Location: include/linux/atomic/atomic-instrumented.h:255
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
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/debug/debug_core.c (ffffffff81239607)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/watchdog_hld.c (ffffffff81248333)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
```
```
In kernel/trace/ftrace.c (ffffffff812544a6)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffffffff8126092a)
Location: include/linux/atomic/atomic-instrumented.h:255
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
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_set_cpumask
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (ffffffff81279d91)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8127aece)
Location: include/linux/atomic/atomic-instrumented.h:255
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
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/fgraph.c (ffffffff81284e95)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:ftrace_suspend_notifier_call
```
```
In kernel/trace/trace_kdb.c (ffffffff812b35d3)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/trace/trace_dynevent.c (ffffffff812b393d)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - kernel/trace/trace_dynevent.c:trace_event_dyn_put_ref
```
```
In kernel/bpf/hashtab.c (ffffffff812f8857)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
```
```
In kernel/bpf/offload.c (ffffffff8132181c)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
```
```
In kernel/events/core.c (ffffffff81343c12)
Location: include/linux/atomic/atomic-instrumented.h:255
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
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/hw_breakpoint.c (ffffffff8134da13)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff8134ed4e)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/watch_queue.c (ffffffff81357a58)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:free_watch
```
```
In mm/page-writeback.c (ffffffff8136b1d5)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_end_writeback
```
```
In mm/vmscan.c (ffffffff81384279)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_throttle
```
```
In mm/mmap.c (ffffffff813cb949)
Location: include/linux/atomic/atomic-instrumented.h:255
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
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/rmap.c (ffffffff813d8137)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_rmap
```
```
In mm/page_alloc.c (ffffffff813ef579)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_contig_migrate_range
```
```
In mm/memory_hotplug.c (ffffffff820c3953)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/swapfile.c (ffffffff813fc847)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffffffff81401c0c)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff81402945)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_free_entry
```
```
In mm/mempolicy.c (ffffffff81419fb5)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_migrate_pages
```
```
In mm/migrate.c (ffffffff81435b88)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
```
In mm/memcontrol.c (ffffffff81453027)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
```
```
In mm/zpool.c (ffffffff81465d42)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - mm/zpool.c:zpool_destroy_pool
  - mm/zpool.c:zpool_create_pool
  - mm/zpool.c:zpool_has_pool
```
```
In mm/secretmem.c (ffffffff8146ace5)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_release
```
```
In mm/mapping_dirty_helpers.c (ffffffff81471aae)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/open.c (ffffffff81473f58)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff8147c663)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff8148f751)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - fs/namei.c:do_open
```
```
In fs/fs-writeback.c (ffffffff814c343b)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - fs/fs-writeback.c:cleanup_offline_cgwb
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/buffer.c (ffffffff814d2f15)
Location: include/linux/atomic/atomic-instrumented.h:255
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
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/coredump.c (ffffffff815190ba)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffffffff815236aa)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8152d1fc)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/kernfs/inode.c (ffffffff81549188)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/devpts/inode.c (ffffffff8155663e)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_kill_index
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/balloc.c (ffffffff81557464)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_should_retry_alloc
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8155dfb0)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff815703d4)
Location: include/linux/atomic/atomic-instrumented.h:255
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
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff81580a8e)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff8158fdda)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff81597c6b)
Location: include/linux/atomic/atomic-instrumented.h:255
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
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff815c1dda)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff815dfa47)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff815e16c4)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff815eb060)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_fc_release_bufs
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
```
```
In fs/ecryptfs/miscdev.c (ffffffff81615efa)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release
```
```
In fs/fuse/inode.c (ffffffff8162ad15)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_sync_fs_writes
```
```
In ipc/util.c (ffffffff8163c6c1)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
```
```
In security/keys/gc.c (ffffffff8164d68d)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
```
```
In security/keys/keyctl.c (ffffffff81653c0a)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/selinux/avc.c (ffffffff8166c838)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_flush
  - security/selinux/avc.c:avc_node_replace
```
```
In security/selinux/hooks.c (ffffffff8166de35)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_dec
```
```
In security/selinux/xfrm.c (ffffffff81697ff1)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_state_free
  - security/selinux/xfrm.c:selinux_xfrm_policy_free
```
```
In security/tomoyo/common.c (ffffffff816a88ac)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff816af5d7)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff816b162d)
Location: include/linux/atomic/atomic-instrumented.h:255
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
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff816b4497)
Location: include/linux/atomic/atomic-instrumented.h:255
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
Location: include/linux/atomic/atomic-instrumented.h:255
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
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff816b5dca)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/network.c (ffffffff816b71de)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
```
In security/tomoyo/securityfs_if.c (ffffffff816b8298)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff816b84af)
Location: include/linux/atomic/atomic-instrumented.h:255
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
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/blk-mq.c:blk_mq_dispatch_wake
```
```
In block/blk-iocost.c (ffffffff8176b339)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In io_uring/io_uring.c (ffffffff81792798)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_clean_op
  - io_uring/io_uring.c:io_eventfd_signal
```
```
In io_uring/io-wq.c (ffffffff817a68f5)
Location: include/linux/atomic/atomic-instrumented.h:255
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
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_finish_wait
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/pci/pci.c (ffffffff818e35c7)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8190cc92)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff81945262)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
```
```
In drivers/acpi/apei/ghes.c (ffffffff819e72b8)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_rcu_free
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
```
```
In drivers/xen/events/events_base.c (ffffffff81a1f2dc)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
```
```
In drivers/reset/core.c (ffffffff81a4611a)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_reset
```
```
In drivers/tty/tty_buffer.c (ffffffff81a55004)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
```
In drivers/tty/vt/keyboard.c (ffffffff83eecd4a)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81a8ed59)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_close
```
```
In drivers/char/agp/backend.c (ffffffff81a9c96e)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_release
```
```
In drivers/char/agp/generic.c (ffffffff81a9ea9e)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81aa2c9a)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
```
```
In drivers/connector/cn_queue.c (ffffffff81adc93e)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffff81add4a9)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
```
```
In drivers/base/dd.c (ffffffff81aead94)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/runtime.c (ffffffff81b01a3b)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:update_autosuspend
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81b597e3)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:deactivate_labels
```
```
In drivers/cxl/core/suspend.c (ffffffff81b739a5)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/cxl/core/suspend.c:cxl_mem_active_dec
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b7d043)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_enable_disk_events
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfbad5)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff81c1e3d4)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/urb.c (ffffffff81c21d0f)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81cd5f82)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (ffffffff81cf7493)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/md/md.c:md_release
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffff81d0fa0f)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stats.c (ffffffff81d1cd8f)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stat_for_entry
```
```
In drivers/md/dm-io-rewind.c (ffffffff81d1fe48)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/md/dm-io-rewind.c:dm_io_rewind
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81d252e9)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81d5a089)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d7855d)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/ras/debugfs.c (ffffffff81d8a125)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_release
```
```
In drivers/hte/hte.c (ffffffff81d90c04)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - drivers/hte/hte.c:hte_ts_put
```
```
In net/core/skbuff.c (ffffffff81daa1e9)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
```
```
In net/core/dev.c (ffffffff81dbf43a)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
```
```
In net/core/neighbour.c (ffffffff81ddb381)
Location: include/linux/atomic/atomic-instrumented.h:255
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
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
```
```
In net/core/sock_map.c (ffffffff81e4a4f5)
Location: include/linux/atomic/atomic-instrumented.h:255
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
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_cb_destroy
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_cls_offload_cnt_update
```
```
In net/sched/act_api.c (ffffffff81e621ce)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - net/sched/act_api.c:__tcf_action_put
  - net/sched/act_api.c:__tcf_action_put
```
```
In net/netlink/af_netlink.c (ffffffff81e6b4ee)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea9113)
Location: include/linux/atomic/atomic-instrumented.h:255
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
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/fib_semantics.c (ffffffff81f009a3)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0ac4e)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
```
```
In net/ipv4/fib_rules.c (ffffffff81f1b2a9)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_delete
```
```
In net/ipv4/ipmr.c (ffffffff81f20969)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f3334a)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff81f3af88)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
```
```
In net/ipv6/udp.c (ffffffff81f8a239)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81f8e24a)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9b360)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81fa290d)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81fa4eb5)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
```
In net/ipv6/ioam6.c (ffffffff81fa91fe)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81faf7be)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:mif6_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81fbee41)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81fc44cd)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mm_close
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81fd778b)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81fd804c)
Location: include/linux/atomic/atomic-instrumented.h:255
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81fd933a)
Location: include/linux/atomic/atomic-instrumented.h:255
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
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
```
```
In arch/x86/events/intel/core.c (ffffffff81012a57)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_put_event_constraints
  - arch/x86/events/intel/core.c:intel_put_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/events/intel/uncore.c (ffffffff81024dd4)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_put_constraint
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81026d24)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In arch/x86/xen/spinlock.c (ffffffff8104487f)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - arch/x86/xen/spinlock.c:xen_qlock_wait
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8107c173)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_hcpu_update
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108fea0)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81099f7c)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff8109af47)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810d720f)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810e8215)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In kernel/cpu.c (ffffffff810fafc7)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In kernel/async.c (ffffffff81135f41)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/core.c (ffffffff81150ff8)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:ttwu_do_activate
```
```
In kernel/sched/fair.c (ffffffff81166824)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/build_policy.c (ffffffff811714d8)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:rq_offline_dl
  - kernel/sched/build_policy.c:rq_offline_rt
```
```
In kernel/sched/build_utility.c (ffffffff811883e6)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:cpupri_set
```
```
In kernel/printk/printk.c (ffffffff8119ffa5)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In kernel/irq/spurious.c (ffffffff811abc19)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/rcu/update.c (ffffffff811bdf25)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_end_inkernel_boot
```
```
In kernel/rcu/srcutree.c (ffffffff811be830)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier_one_cpu
```
```
In kernel/time/clocksource.c (ffffffff811f4cda)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/futex/core.c (ffffffff81208996)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_q_unlock
  - kernel/futex/core.c:__futex_unqueue
```
```
In kernel/futex/requeue.c (ffffffff8120bd95)
Location: include/linux/atomic/atomic-instrumented.h:590
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
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/debug/debug_core.c (ffffffff81250617)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/watchdog_perf.c (ffffffff8125f64e)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - kernel/watchdog_perf.c:watchdog_hardlockup_disable
```
```
In kernel/trace/ftrace.c (ffffffff8126b396)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffffffff812778fa)
Location: include/linux/atomic/atomic-instrumented.h:590
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
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_set_cpumask
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (ffffffff812917d1)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff812929ee)
Location: include/linux/atomic/atomic-instrumented.h:590
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
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/fgraph.c (ffffffff812a1b2e)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:ftrace_suspend_notifier_call
```
```
In kernel/trace/trace_kdb.c (ffffffff812d5ea3)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/trace/trace_dynevent.c (ffffffff812d620d)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - kernel/trace/trace_dynevent.c:trace_event_dyn_put_ref
```
```
In kernel/bpf/hashtab.c (ffffffff81326957)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In kernel/bpf/devmap.c (ffffffff8134d9d2)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_delete_elem
```
```
In kernel/bpf/offload.c (ffffffff813518fc)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In kernel/events/core.c (ffffffff81374c9b)
Location: include/linux/atomic/atomic-instrumented.h:590
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
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/hw_breakpoint.c (ffffffff8137e68c)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff8137feee)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/watch_queue.c (ffffffff813892ba)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:free_watch
```
```
In mm/page-writeback.c (ffffffff8139d352)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_end_writeback
```
```
In mm/vmscan.c (ffffffff813b5d17)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_throttle
```
```
In mm/mmap.c (ffffffff81400166)
Location: include/linux/atomic/atomic-instrumented.h:590
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
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/rmap.c (ffffffff8140ca58)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_rmap
```
```
In mm/page_alloc.c (ffffffff814230e9)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_contig_migrate_range
```
```
In mm/memory_hotplug.c (ffffffff82147735)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/swapfile.c (ffffffff8142fc54)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffffffff81434b9c)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff81435e05)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_free_entry
```
```
In mm/mempolicy.c (ffffffff8144d33b)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_migrate_pages
```
```
In mm/migrate.c (ffffffff8146b869)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
```
In mm/memcontrol.c (ffffffff81488c7d)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
```
```
In mm/zpool.c (ffffffff8149b7b2)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - mm/zpool.c:zpool_destroy_pool
  - mm/zpool.c:zpool_create_pool
  - mm/zpool.c:zpool_has_pool
```
```
In mm/secretmem.c (ffffffff8149fb75)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_release
```
```
In mm/mapping_dirty_helpers.c (ffffffff814a63fd)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/open.c (ffffffff814a879b)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff814b1224)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff814c1f3d)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - fs/namei.c:do_open
```
```
In fs/fs-writeback.c (ffffffff814f881b)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - fs/fs-writeback.c:cleanup_offline_cgwb
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/buffer.c (ffffffff81509922)
Location: include/linux/atomic/atomic-instrumented.h:590
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
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/coredump.c (ffffffff815509b8)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffffffff8155b269)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - fs/quota/dquot.c:quota_release_workfn
  - fs/quota/dquot.c:quota_release_workfn
```
```
In fs/proc/task_mmu.c (ffffffff81564f2a)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/kernfs/inode.c (ffffffff81580d6b)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/devpts/inode.c (ffffffff8158e3fe)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_kill_index
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/balloc.c (ffffffff8158f2e4)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_should_retry_alloc
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff81595dcc)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff815a82b9)
Location: include/linux/atomic/atomic-instrumented.h:590
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
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff815b803e)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff815c724c)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff815ce6d4)
Location: include/linux/atomic/atomic-instrumented.h:590
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
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff815f955a)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff8161751b)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81618ece)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff81622ad0)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_fc_release_bufs
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
```
```
In fs/ecryptfs/miscdev.c (ffffffff8164df8a)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release
```
```
In fs/fuse/inode.c (ffffffff81662f35)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_sync_fs_writes
```
```
In ipc/util.c (ffffffff81674e28)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In security/keys/gc.c (ffffffff81685e2d)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In security/keys/keyctl.c (ffffffff8168c4c2)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/selinux/avc.c (ffffffff816a507f)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_compute_av
  - security/selinux/avc.c:avc_ss_reset
  - security/selinux/avc.c:avc_node_replace
```
```
In security/selinux/hooks.c (ffffffff816a6505)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_dec
```
```
In security/selinux/xfrm.c (ffffffff816d04d1)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_state_free
  - security/selinux/xfrm.c:selinux_xfrm_policy_free
```
```
In security/tomoyo/common.c (ffffffff816e12ec)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff816e7ff8)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff816ea03d)
Location: include/linux/atomic/atomic-instrumented.h:590
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
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff816ece57)
Location: include/linux/atomic/atomic-instrumented.h:590
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
Location: include/linux/atomic/atomic-instrumented.h:590
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
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff816ee7da)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/network.c (ffffffff816efbbe)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
```
In security/tomoyo/securityfs_if.c (ffffffff816f0c68)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff816f0e7f)
Location: include/linux/atomic/atomic-instrumented.h:590
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
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/blk-mq.c:blk_mq_dispatch_wake
```
```
In block/blk-iocost.c (ffffffff817aa419)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In io_uring/io_uring.c (ffffffff817d350c)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_eventfd_signal
  - io_uring/io_uring.c:io_clean_op
```
```
In io_uring/io-wq.c (ffffffff817e7868)
Location: include/linux/atomic/atomic-instrumented.h:590
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
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_finish_wait
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/pci/pci.c (ffffffff81926a17)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81950312)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff819898a2)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a2f9c8)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_rcu_free
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
```
```
In drivers/xen/events/events_base.c (ffffffff81a68488)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
```
```
In drivers/reset/core.c (ffffffff81a902ca)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_reset
```
```
In drivers/tty/tty_buffer.c (ffffffff81a9f5e4)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
```
In drivers/tty/vt/keyboard.c (ffffffff83712a0a)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81ada509)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_close
```
```
In drivers/char/agp/backend.c (ffffffff81ae82ce)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_release
```
```
In drivers/char/agp/generic.c (ffffffff81aea414)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81aee56a)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
```
```
In drivers/connector/cn_queue.c (ffffffff81b2abae)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffff81b2b719)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In drivers/base/dd.c (ffffffff81b39094)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/runtime.c (ffffffff81b4fb65)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:update_autosuspend
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81bacd43)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:deactivate_labels
```
```
In drivers/cxl/core/suspend.c (ffffffff81bc7115)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/cxl/core/suspend.c:cxl_mem_active_dec
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd0dc3)
Location: include/linux/atomic/atomic-instrumented.h:590
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
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff81c852c4)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/urb.c (ffffffff81c88c8f)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81d3df82)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (ffffffff81d5ed93)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/md/md.c:md_release
```
```
In drivers/md/dm.c (ffffffff81d78e2d)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stats.c (ffffffff81d85faf)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stat_for_entry
```
```
In drivers/md/dm-io-rewind.c (ffffffff81d8903a)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/md/dm-io-rewind.c:dm_io_rewind
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81d8e528)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81dc4a29)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de649d)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/ras/debugfs.c (ffffffff81df8725)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_release
```
```
In drivers/hte/hte.c (ffffffff81dfee95)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/hte/hte.c:hte_ts_put
```
```
In net/core/skbuff.c (ffffffff81e18f89)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In net/core/dev.c (ffffffff81e2f0ea)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In net/core/neighbour.c (ffffffff81e4be56)
Location: include/linux/atomic/atomic-instrumented.h:590
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
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In net/core/sock_map.c (ffffffff81ea5c05)
Location: include/linux/atomic/atomic-instrumented.h:590
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
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_cb_destroy
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_cls_offload_cnt_update
```
```
In net/sched/act_api.c (ffffffff81ebdb1e)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - net/sched/act_api.c:__tcf_action_put
  - net/sched/act_api.c:__tcf_action_put
```
```
In net/netlink/af_netlink.c (ffffffff81ec7533)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f079a3)
Location: include/linux/atomic/atomic-instrumented.h:590
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
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/fib_semantics.c (ffffffff81f60423)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6a79a)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In net/ipv4/fib_rules.c (ffffffff81f7af19)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_delete
```
```
In net/ipv4/ipmr.c (ffffffff81f81189)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f926e6)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff81f9a9a8)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
```
```
In net/ipv6/udp.c (ffffffff81fe9e78)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81feea30)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffc767)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff820031b0)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff82005775)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
```
In net/ipv6/ioam6.c (ffffffff82009b9a)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff8200ff5e)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:mif6_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff8201fa68)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In net/packet/af_packet.c (ffffffff82025500)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mm_close
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff8205347a)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff82053d3c)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
```
```
In net/netlabel/netlabel_calipso.c (ffffffff8205500a)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
```
In net/xdp/xskmap.c (ffffffff8206d174)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_sock_delete
```
```
In net/handshake/request.c (ffffffff82092d9c)
Location: include/linux/atomic/atomic-instrumented.h:590
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
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
```
```
In arch/x86/events/intel/core.c (ffffffff81018377)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_put_event_constraints
  - arch/x86/events/intel/core.c:intel_put_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/events/intel/uncore.c (ffffffff8102af34)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_put_constraint
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8102ce84)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In arch/x86/xen/spinlock.c (ffffffff8104adaf)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - arch/x86/xen/spinlock.c:xen_qlock_wait
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81097230)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff810a17ac)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff810a2625)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810dfa6f)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810f03a5)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In kernel/cpu.c (ffffffff81104467)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In kernel/async.c (ffffffff811410f1)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/core.c (ffffffff8115cd8a)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:ttwu_do_activate
```
```
In kernel/sched/fair.c (ffffffff81173564)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/build_policy.c (ffffffff8117ede8)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:rq_offline_dl
  - kernel/sched/build_policy.c:rq_offline_rt
  - kernel/sched/build_policy.c:pick_next_task_rt
  - kernel/sched/build_policy.c:dequeue_task_rt
```
```
In kernel/sched/build_utility.c (ffffffff81196cc6)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:cpupri_set
```
```
In kernel/printk/printk.c (ffffffff811af005)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In kernel/irq/spurious.c (ffffffff811bb819)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/rcu/update.c (ffffffff811ce445)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_end_inkernel_boot
  - kernel/rcu/update.c:rcu_end_inkernel_boot
```
```
In kernel/rcu/srcutree.c (ffffffff811ced50)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier_one_cpu
```
```
In kernel/rcu/tree.c (ffffffff811d2110)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_nocb_bypass_lock
  - kernel/rcu/tree.c:param_set_do_rcu_barrier
```
```
In kernel/time/clocksource.c (ffffffff8120ae31)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/futex/core.c (ffffffff8121f826)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_q_unlock
  - kernel/futex/core.c:__futex_unqueue
```
```
In kernel/futex/requeue.c (ffffffff8122332a)
Location: include/linux/atomic/atomic-instrumented.h:590
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
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/debug/debug_core.c (ffffffff8126a467)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/watchdog_perf.c (ffffffff8127965e)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - kernel/watchdog_perf.c:watchdog_hardlockup_disable
```
```
In kernel/trace/ftrace.c (ffffffff81285846)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffffffff812905c9)
Location: include/linux/atomic/atomic-instrumented.h:590
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
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_set_cpumask
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (ffffffff812acde1)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff812ae0d7)
Location: include/linux/atomic/atomic-instrumented.h:590
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
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/fgraph.c (ffffffff812bd25e)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:ftrace_suspend_notifier_call
```
```
In kernel/trace/trace_kdb.c (ffffffff812f39b3)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/trace/trace_dynevent.c (ffffffff812f3d1d)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - kernel/trace/trace_dynevent.c:trace_event_dyn_put_ref
```
```
In kernel/bpf/hashtab.c (ffffffff8134afa2)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In kernel/bpf/devmap.c (ffffffff81374ef2)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_delete_elem
```
```
In kernel/bpf/offload.c (ffffffff81378ddc)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In kernel/events/core.c (ffffffff8139dfcb)
Location: include/linux/atomic/atomic-instrumented.h:590
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
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/hw_breakpoint.c (ffffffff813a78ec)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff813a916e)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/watch_queue.c (ffffffff813b2d0c)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:free_watch
```
```
In mm/page-writeback.c (ffffffff813c70ee)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_end_writeback
```
```
In mm/vmscan.c (ffffffff813debd7)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_throttle
```
```
In mm/mmap.c (ffffffff8142c786)
Location: include/linux/atomic/atomic-instrumented.h:590
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
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/rmap.c (ffffffff8143a464)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (ffffffff81450019)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_contig_migrate_range
```
```
In mm/memory_hotplug.c (ffffffff82229f6d)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/swapfile.c (ffffffff8146973f)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/zswap.c (ffffffff8146f8d6)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_free_entry
```
```
In mm/hugetlb.c (ffffffff8147daff)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/mempolicy.c (ffffffff81486e10)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_migrate_pages
```
```
In mm/migrate.c (ffffffff8149a844)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
```
In mm/memcontrol.c (ffffffff814b82fd)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
```
```
In mm/zpool.c (ffffffff814caeb2)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - mm/zpool.c:zpool_destroy_pool
  - mm/zpool.c:zpool_create_pool
  - mm/zpool.c:zpool_has_pool
```
```
In mm/secretmem.c (ffffffff814cf2c5)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_release
```
```
In mm/mapping_dirty_helpers.c (ffffffff814d734d)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/open.c (ffffffff814d9878)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff814e2a5b)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff814f43fd)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - fs/namei.c:do_open
```
```
In fs/fs-writeback.c (ffffffff8152d019)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - fs/fs-writeback.c:cleanup_offline_cgwb
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/buffer.c (ffffffff8153e752)
Location: include/linux/atomic/atomic-instrumented.h:590
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
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/coredump.c (ffffffff81586849)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffffffff8159224b)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8159b9e9)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/kernfs/inode.c (ffffffff815b97e7)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/devpts/inode.c (ffffffff815c712e)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_kill_index
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/balloc.c (ffffffff815c7ff4)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_should_retry_alloc
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff815cea7c)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff815e1076)
Location: include/linux/atomic/atomic-instrumented.h:590
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
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff815f0dde)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff81604bc2)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff81606f54)
Location: include/linux/atomic/atomic-instrumented.h:590
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
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff816320ea)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff8165033a)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81651d8d)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff8165bb2f)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_fc_release_bufs
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
```
```
In fs/ecryptfs/miscdev.c (ffffffff816874ea)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release
```
```
In fs/fuse/inode.c (ffffffff8169caa4)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_sync_fs_writes
```
```
In ipc/util.c (ffffffff816b11e8)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In security/keys/gc.c (ffffffff816c224d)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In security/keys/keyctl.c (ffffffff816c89c2)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/selinux/avc.c (ffffffff816e1ad3)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_compute_av
  - security/selinux/avc.c:avc_ss_reset
  - security/selinux/avc.c:avc_node_replace
```
```
In security/selinux/hooks.c (ffffffff816e2fc5)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_dec
```
```
In security/selinux/xfrm.c (ffffffff8170caf1)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_state_free
  - security/selinux/xfrm.c:selinux_xfrm_policy_free
```
```
In security/tomoyo/common.c (ffffffff8171df6c)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff81724d08)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff81726d4d)
Location: include/linux/atomic/atomic-instrumented.h:590
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
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff81729c27)
Location: include/linux/atomic/atomic-instrumented.h:590
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
Location: include/linux/atomic/atomic-instrumented.h:590
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
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff8172b5aa)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/network.c (ffffffff8172c98e)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
```
In security/tomoyo/securityfs_if.c (ffffffff8172da38)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8172dc4f)
Location: include/linux/atomic/atomic-instrumented.h:590
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
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - block/bdev.c:bdev_freeze
```
```
In block/blk-mq.c (ffffffff817c5fbc)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/blk-mq.c:blk_mq_dispatch_wake
```
```
In block/blk-iocost.c (ffffffff817ee0f5)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In io_uring/io_uring.c (ffffffff8181731c)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_eventfd_signal
  - io_uring/io_uring.c:io_clean_op
```
```
In io_uring/io-wq.c (ffffffff8182d676)
Location: include/linux/atomic/atomic-instrumented.h:590
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
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_finish_wait
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/pci/pci.c (ffffffff8196f1b7)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81999742)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff819d37b2)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a7ad08)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_rcu_free
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
```
```
In drivers/xen/events/events_base.c (ffffffff81ab9a04)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
```
```
In drivers/reset/core.c (ffffffff81ae2d0a)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_reset
```
```
In drivers/tty/tty_buffer.c (ffffffff81af1fe1)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
```
In drivers/tty/vt/keyboard.c (ffffffff8394642a)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81b2d809)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_close
```
```
In drivers/char/agp/backend.c (ffffffff81b3b73e)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_release
```
```
In drivers/char/agp/generic.c (ffffffff81b3d8a4)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81b41aaa)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
```
```
In drivers/connector/cn_queue.c (ffffffff81b81e5e)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffff81b82c75)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In drivers/base/dd.c (ffffffff81b90b54)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/runtime.c (ffffffff81ba80e5)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:update_autosuspend
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81c01083)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:deactivate_labels
```
```
In drivers/cxl/core/suspend.c (ffffffff81c1bc85)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/cxl/core/suspend.c:cxl_mem_active_dec
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c25a33)
Location: include/linux/atomic/atomic-instrumented.h:590
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
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_file.c:drm_open
```
```
In drivers/gpu/drm/drm_vblank.c (ffffffff81cb528b)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_vblank_on
  - drivers/gpu/drm/drm_vblank.c:drm_vblank_get
  - drivers/gpu/drm/drm_vblank.c:drm_vblank_enable
```
```
In drivers/accel/drm_accel.c (ffffffff81cbcce6)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/accel/drm_accel.c:accel_open
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d17a35)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff81d39cc4)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/urb.c (ffffffff81d3d6df)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81df48d2)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (ffffffff81e15ad3)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/md/md.c:md_release
```
```
In drivers/md/dm.c (ffffffff81e2ffbe)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stats.c (ffffffff81e3d6ef)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stat_for_entry
```
```
In drivers/md/dm-io-rewind.c (ffffffff81e4077a)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/md/dm-io-rewind.c:dm_io_rewind
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81e45e3c)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81e7d309)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e9c67d)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/ras/debugfs.c (ffffffff81eaee35)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_release
```
```
In drivers/hte/hte.c (ffffffff81eb6185)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - drivers/hte/hte.c:hte_ts_put
```
```
In net/core/skbuff.c (ffffffff81ed6419)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In net/core/dev.c (ffffffff81eedd6a)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In net/core/neighbour.c (ffffffff81f0ab66)
Location: include/linux/atomic/atomic-instrumented.h:590
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
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In net/core/sock_map.c (ffffffff81f686c5)
Location: include/linux/atomic/atomic-instrumented.h:590
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
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_cb_destroy
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_cls_offload_cnt_update
```
```
In net/sched/act_api.c (ffffffff81f80c0e)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - net/sched/act_api.c:__tcf_action_put
  - net/sched/act_api.c:__tcf_action_put
```
```
In net/netlink/af_netlink.c (ffffffff81f8a873)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81fbe1fa)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fcbd03)
Location: include/linux/atomic/atomic-instrumented.h:590
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
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/fib_semantics.c (ffffffff820269f3)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/inet_fragment.c (ffffffff82030e4a)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In net/ipv4/fib_rules.c (ffffffff82041619)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_delete
```
```
In net/ipv4/ipmr.c (ffffffff82047809)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/xfrm/xfrm_policy.c (ffffffff82060456)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff82067d08)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
```
```
In net/ipv6/ip6_output.c (ffffffff820842d6)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In net/ipv6/udp.c (ffffffff820b7cfa)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff820bc606)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820c9a9f)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff820d1f81)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff820d4585)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
```
In net/ipv6/ioam6.c (ffffffff820d8b3a)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff820deeee)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:mif6_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff820eeb98)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff82125c7a)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff82126515)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
```
```
In net/netlabel/netlabel_calipso.c (ffffffff821278e4)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
```
In net/xdp/xskmap.c (ffffffff82141014)
Location: include/linux/atomic/atomic-instrumented.h:590
Inline: True
Inline callers:
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_sock_delete
```
```
In net/handshake/request.c (ffffffff8216964c)
Location: include/linux/atomic/atomic-instrumented.h:590
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
In arch/arm64/kernel/smp.c (ffff80001009cce0)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - arch/arm64/kernel/smp.c:handle_IPI
```
```
In arch/arm64/kernel/suspend.c (ffff8000100a6e54)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - arch/arm64/kernel/suspend.c:cpu_suspend
```
```
In kernel/fork.c (ffff8000100f427c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/cpu.c (ffff8000100fa2a0)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In kernel/exit.c (ffff8000100fa998)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/workqueue.c (ffff8000101205d4)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cred.c (ffff80001012d2d8)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/async.c (ffff80001012e900)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/ucount.c (ffff8000101302dc)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (ffff80001013a3e8)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffff80001014c434)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (ffff80001015026c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffff800010152ba8)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffff800010159f48)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/power/process.c (ffff80001016ffc8)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
```
```
In kernel/irq/spurious.c (ffff80001017d0a0)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/rcu/update.c (ffff800010189060)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_end_inkernel_boot
```
```
In kernel/rcu/srcutree.c (ffff80001018a6d8)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/futex.c (ffff8000101ba3bc)
Location: include/linux/atomic-fallback.h:437
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
In kernel/cgroup/cgroup.c (ffff8000101d719c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/cgroup/legacy_freezer.c (ffff8000101de254)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_css_offline
```
```
In kernel/debug/debug_core.c (ffff8000101f9884)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/trace/ftrace.c (ffff800010210ef4)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffff80001021a658)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_record_enable
```
```
In kernel/trace/trace.c (ffff800010221588)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:s_stop
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (ffff800010230194)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffff8000102308f4)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffff8000102333f0)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/fgraph.c (ffff800010238090)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In kernel/trace/trace_kdb.c (ffff8000102551c4)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/bpf/syscall.c (ffff8000102600e4)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_inc
```
```
In kernel/bpf/hashtab.c (ffff8000102784ac)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/offload.c (ffff80001028a2cc)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffff80001029c8b8)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_migrate_context
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
  - kernel/events/core.c:_free_event
```
```
In kernel/events/callchain.c (ffff8000102a35f0)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/uprobes.c (ffff8000102a543c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/padata.c (ffff8000102a9aec)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/padata.c:padata_find_next
```
```
In mm/backing-dev.c (ffff8000102ddb88)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/mmap.c (ffff8000103037bc)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_link_file
  - mm/mmap.c:__remove_shared_vm_struct
```
```
In mm/mmu_gather.c (ffff800010304e2c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mprotect.c (ffff8000103053b8)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffff800010309b58)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In mm/swapfile.c (ffff800010327acc)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffff80001032a4d4)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffff80001032b4e8)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_free_entry
```
```
In mm/huge_memory.c (ffff8000103562a8)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memcontrol.c (ffff800010365f80)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
```
```
In mm/zpool.c (ffff8000103729b8)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - mm/zpool.c:zpool_destroy_pool
  - mm/zpool.c:zpool_create_pool
  - mm/zpool.c:zpool_create_pool
  - mm/zpool.c:zpool_has_pool
```
```
In fs/open.c (ffff80001037dcd8)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffff80001038559c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffff800010398314)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/fs-writeback.c (ffff8000103c7854)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffff8000103dc020)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/notify/mark.c (ffff8000103ea604)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify.c (ffff8000103ed5a8)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
```
```
In fs/mbcache.c (ffff800010424edc)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/coredump.c (ffff800010428b98)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffff80001042fad4)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In fs/devpts/inode.c (ffff80001045ebc8)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_kill_index
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/balloc.c (ffff8000104611b8)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffff800010465934)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffff800010475acc)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffff800010477630)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffff800010485768)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffff8000104964f8)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffff8000104989cc)
Location: include/linux/atomic-fallback.h:437
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
In fs/ext4/mmp.c (ffff80001049958c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffff8000104b8610)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/commit.c (ffff8000104ce3d0)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffff8000104d018c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/squashfs/block.c (ffff8000104d9bc4)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffff8000104df31c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffff8000104df5b4)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffff8000104df95c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffff8000104dfc88)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffff8000104dffb8)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In fs/ecryptfs/miscdev.c (ffff8000104fda88)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release
```
```
In ipc/util.c (ffff80001051ce34)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In ipc/msg.c (ffff80001051fba4)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In security/keys/gc.c (ffff80001052d190)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In security/keys/keyctl.c (ffff800010532fcc)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/selinux/avc.c (ffff80001054710c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_compute_av
  - security/selinux/avc.c:avc_node_kill
  - security/selinux/avc.c:avc_node_delete
```
```
In security/selinux/hooks.c (ffff80001054e388)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_dec
```
```
In security/selinux/xfrm.c (ffff80001056bc10)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_state_free
  - security/selinux/xfrm.c:selinux_xfrm_policy_free
```
```
In security/tomoyo/common.c (ffff80001057b5b4)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffff80001057e650)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffff800010580070)
Location: include/linux/atomic-fallback.h:437
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
In security/tomoyo/environ.c (ffff800010580db8)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffff800010582840)
Location: include/linux/atomic-fallback.h:437
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
In security/tomoyo/gc.c (ffff800010582e94)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
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
In security/tomoyo/group.c (ffff800010583c30)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffff8000105844d8)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/network.c (ffff80001058571c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
```
In security/tomoyo/securityfs_if.c (ffff800010586734)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffff800010587404)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_task_free
  - security/tomoyo/tomoyo.c:tomoyo_task_free
  - security/tomoyo/tomoyo.c:tomoyo_bprm_committed_creds
  - security/tomoyo/tomoyo.c:tomoyo_cred_prepare
  - security/tomoyo/tomoyo.c:tomoyo_domain
```
```
In block/blk-flush.c (ffff8000105e6fc4)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (ffff8000105e8ae8)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - block/blk-ioc.c:exit_io_context
```
```
In block/blk-mq.c (ffff8000105f0894)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-tag.c (ffff8000105f4368)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-iocost.c (ffff8000106154b4)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (ffff80001066a04c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_finish_wait
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/irqchip/irq-renesas-irqc.c (ffff800010676c28)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-irqc.c:irqc_irq_set_wake
```
```
In drivers/pci/pci.c (ffff8000106e8fa0)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffff800010708cf4)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
```
In drivers/pci/ats.c (ffff8000107165e4)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (ffff800010743e6c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
```
In drivers/acpi/apei/ghes.c (ffff8000107b00b8)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
```
```
In drivers/dma/dmaengine.c (ffff8000107fd480)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/dma/ipu/ipu_idmac.c (ffff80001080d528)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:__idmac_terminate_all
```
```
In drivers/reset/core.c (ffff80001084cf5c)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffff80001085d99c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
```
In drivers/tty/vt/keyboard.c (ffff800011493260)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/tty/serial/kgdb_nmi.c (ffff8000108a8668)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_close
```
```
In drivers/tty/serial/kgdboc.c (ffff8000108a8ea8)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_post_exp_handler
```
```
In drivers/iommu/arm-smmu-v3.c (ffff8000108d60fc)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_detach_dev
```
```
In drivers/connector/cn_queue.c (ffff8000108dd278)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In drivers/connector/cn_proc.c (ffff8000108de0b4)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In drivers/base/dd.c (ffff8000108ea8f8)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/power/runtime.c (ffff8000108fd7f0)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (ffff80001093e408)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_irq_set_wake
```
```
In drivers/mfd/mfd-core.c (ffff80001094088c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/nvdimm/namespace_devs.c (ffff80001095ab28)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:deactivate_labels
```
```
In drivers/scsi/scsi_lib.c (ffff800010977088)
Location: include/linux/atomic-fallback.h:437
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
In drivers/net/ppp/ppp_generic.c (ffff8000109fe7f8)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
```
```
In drivers/usb/core/hcd.c (ffff800010a1c1b0)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/urb.c (ffff800010a210b8)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
```
```
In drivers/media/cec/cec-pin.c (ffff800010ac499c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/media/cec/cec-pin.c:cec_pin_thread_func
```
```
In drivers/power/reset/vexpress-poweroff.c (ffff800010aca41c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/power/reset/vexpress-poweroff.c:_vexpress_register_restart_handler
```
```
In drivers/power/supply/power_supply_core.c (ffff800010acbd70)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (ffff800010ae7f60)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffff800010afdd20)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stats.c (ffff800010b0dd28)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In drivers/edac/edac_pci_sysfs.c (ffff800010b14154)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/mmc/core/sdio_bus.c (ffff800010b3b1a8)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/firmware/arm_scmi/clock.c (ffff800010b57d8c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/clock.c:scmi_clock_rate_set
```
```
In drivers/remoteproc/remoteproc_core.c (ffff800010b81108)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/ras/debugfs.c (ffff800010b9e5a4)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_release
```
```
In net/core/skbuff.c (ffff800010bb5eb8)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In net/core/dev.c (ffff800010bcb3d8)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In net/core/neighbour.c (ffff800010be61cc)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_mark_dead
```
```
In net/core/xdp.c (ffff800010c068d0)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffff800010c08264)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In net/core/sock_map.c (ffff800010c21004)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_free_elem
```
```
In net/sched/cls_api.c (ffff800010c42754)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_cb_destroy
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_cls_offload_cnt_update
```
```
In net/sched/act_api.c (ffff800010c4734c)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In net/netlink/af_netlink.c (ffff800010c4ee8c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_timewait_sock.c (ffff800010c6bdbc)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6d834)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/inet_fragment.c (ffff800010cbf24c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffff800010ccc030)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/xfrm/xfrm_policy.c (ffff800010cdce54)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
```
```
In net/xfrm/xfrm_state.c (ffff800010ce6198)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
```
```
In net/ipv6/route.c (ffff800010d0f5b8)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In net/ipv6/udp.c (ffff800010d25510)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffff800010d2a23c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d37794)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffff800010d3ce00)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffff800010d3eff4)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
```
In net/ipv6/ip6mr.c (ffff800010d44c4c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
```
```
In net/ipv6/seg6_hmac.c (ffff800010d51f6c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
```
In net/packet/af_packet.c (ffff800010d577a4)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mm_close
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/netlabel/netlabel_unlabeled.c (ffff800010d68dac)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/netlabel/netlabel_cipso_v4.c (ffff800010d69e84)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
```
```
In net/netlabel/netlabel_calipso.c (ffff800010d6aba4)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
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
In arch/arm/kernel/machine_kexec.c (c0315124)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - arch/arm/kernel/machine_kexec.c:machine_crash_nonpanic_core
```
```
In kernel/fork.c (c0352098)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/cpu.c (c03583ec)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In kernel/exit.c (c03587a4)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/workqueue.c (c0374204)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cred.c (c037d15c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/async.c (c037e394)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/ucount.c (c037fb94)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (c0389da0)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (c039a044)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (c039dfb0)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (c039fc6c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (c03a6d54)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/topology.c (c03a96a8)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
```
```
In kernel/power/process.c (c03baa10)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
```
```
In kernel/irq/spurious.c (c03cdb68)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/rcu/update.c (c03d7914)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_end_inkernel_boot
```
```
In kernel/rcu/srcutree.c (c03d8ca8)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/futex.c (c0403f74)
Location: include/linux/atomic-fallback.h:437
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
In kernel/cgroup/cgroup.c (c0419e44)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/cgroup/legacy_freezer.c (c041fc98)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
  - kernel/cgroup/legacy_freezer.c:freezer_css_offline
```
```
In kernel/cgroup/cpuset.c (c0423fa0)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_offline
```
```
In kernel/debug/debug_core.c (c0439b44)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/tracepoint.c (c044d36c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
```
```
In kernel/trace/ftrace.c (c044f5d0)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:profile_graph_entry
```
```
In kernel/trace/ring_buffer.c (c0456064)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_swap_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_record_enable
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/trace/trace.c (c04606b8)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:s_stop
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (c046b730)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (c046c9a4)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (c046f19c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/fgraph.c (c0473b1c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:ftrace_suspend_notifier_call
```
```
In kernel/trace/trace_kdb.c (c048845c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/bpf/syscall.c (c0493310)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In kernel/bpf/hashtab.c (c04aa600)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/offload.c (c04b997c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/bpf/cgroup.c (c04bf04c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/events/core.c (c04c3300)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/events/core.c:sw_perf_event_destroy
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
  - kernel/events/core.c:exclusive_event_destroy
```
```
In kernel/events/callchain.c (c04d2e54)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/uprobes.c (c04d436c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/padata.c (c04d7a40)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/padata.c:padata_find_next
```
```
In mm/backing-dev.c (c0503100)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/mmap.c (c0521e08)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_link_file
  - mm/mmap.c:__remove_shared_vm_struct
```
```
In mm/mmu_gather.c (c052312c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mprotect.c (c05235f0)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (c05266c4)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (c053ef08)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/frontswap.c (c054106c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (c0541a08)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_free_entry
```
```
In mm/ksm.c (c0544f94)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/slub.c (c054b330)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
```
In mm/memcontrol.c (c0557c7c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
```
```
In mm/zpool.c (c055f1fc)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - mm/zpool.c:zpool_put_driver
```
```
In mm/zsmalloc.c (c05613cc)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/open.c (c05677d0)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (c056e374)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:__fput
```
```
In fs/namei.c (c057e938)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/inode.c (c058c6a0)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/inode.c:inc_nlink
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (c05a481c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (c05b533c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/notify/mark.c (c05c1a34)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify.c (c05c3b58)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
```
```
In fs/eventpoll.c (c05c76ec)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In fs/mbcache.c (c05edc78)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/coredump.c (c05f14fc)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (c05f890c)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In fs/devpts/inode.c (c061f610)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_kill_index
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/balloc.c (c0621870)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (c0624fd8)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (c0636e00)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (c0638318)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (c0645838)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (c065868c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (c065a29c)
Location: include/linux/atomic-fallback.h:437
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
In fs/ext4/mmp.c (c065b018)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (c067bebc)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/commit.c (c06910f8)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (c0692ee0)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/squashfs/block.c (c069b47c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (c06a0c8c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (c06a0f10)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (c06a1210)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (c06a1578)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (c06a1874)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In fs/ecryptfs/miscdev.c (c06baee0)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release
```
```
In ipc/util.c (c06d948c)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In ipc/msg.c (c06dabe0)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - ipc/msg.c:freeque
```
```
In security/keys/gc.c (c06e59b0)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In security/keys/keyctl.c (c06ea8d0)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/selinux/avc.c (c06fc430)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_replace
  - security/selinux/avc.c:avc_node_kill
  - security/selinux/avc.c:avc_node_delete
```
```
In security/selinux/hooks.c (c06fe040)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_dec
```
```
In security/selinux/xfrm.c (c071f1b4)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In security/tomoyo/common.c (c072c110)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (c0730a6c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (c073254c)
Location: include/linux/atomic-fallback.h:437
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
In security/tomoyo/environ.c (c07331e8)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (c073466c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_put_name_union
  - security/tomoyo/file.c:tomoyo_put_name_union
```
```
In security/tomoyo/gc.c (c0734ddc)
Location: include/linux/atomic-fallback.h:437
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
In security/tomoyo/group.c (c0735814)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (c0735ed8)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/network.c (c07370f4)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
```
In security/tomoyo/securityfs_if.c (c0738134)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (c0738310)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_task_free
  - security/tomoyo/tomoyo.c:tomoyo_task_free
  - security/tomoyo/tomoyo.c:tomoyo_bprm_committed_creds
  - security/tomoyo/tomoyo.c:tomoyo_cred_prepare
  - security/tomoyo/tomoyo.c:tomoyo_domain
```
```
In block/blk-flush.c (c0793c38)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (c0795360)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - block/blk-ioc.c:exit_io_context
```
```
In block/blk-mq.c (c079c9cc)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-tag.c (c079ffe8)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/genhd.c (c07a5d44)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - block/genhd.c:part_dec_in_flight
  - block/genhd.c:part_dec_in_flight
```
```
In block/blk-iocost.c (c07be740)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (c0811e14)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_finish_wait
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/irqchip/irq-renesas-intc-irqpin.c (c081ef38)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_irq_set_wake
```
```
In drivers/irqchip/irq-renesas-irqc.c (c081fae0)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-irqc.c:irqc_irq_set_wake
```
```
In drivers/pci/pci.c (c0883f98)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/ats.c (c08a1014)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (c08c804c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
```
In drivers/dma/dmaengine.c (c091eb0c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/dma/ipu/ipu_idmac.c (c09281d0)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:__idmac_terminate_all
```
```
In drivers/reset/core.c (c0958d84)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In drivers/tty/tty_buffer.c (c0965680)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
```
In drivers/tty/vt/keyboard.c (c1593ee4)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/tty/serial/kgdb_nmi.c (c09a4c38)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_close
```
```
In drivers/tty/serial/kgdboc.c (c09a5448)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_post_exp_handler
```
```
In drivers/connector/cn_queue.c (c09cc664)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In drivers/connector/cn_proc.c (c09cd038)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In drivers/base/dd.c (c09d8aac)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/power/runtime.c (c09e8218)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (c0a26830)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_irq_set_wake
```
```
In drivers/mfd/mfd-core.c (c0a2963c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/scsi/scsi_lib.c (c0a4a2e4)
Location: include/linux/atomic-fallback.h:437
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
In drivers/net/ppp/ppp_generic.c (c0adc1f4)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
```
```
In drivers/usb/core/hcd.c (c0af3e70)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/urb.c (c0af7030)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
```
```
In drivers/i2c/i2c-core-base.c (c0b92a58)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer_trace_unreg
```
```
In drivers/power/reset/vexpress-poweroff.c (c0bab21c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/power/reset/vexpress-poweroff.c:_vexpress_register_restart_handler
```
```
In drivers/power/supply/power_supply_core.c (c0babe90)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (c0bcb744)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (c0bdc8dc)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stats.c (c0bebfd4)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In drivers/edac/edac_pci_sysfs.c (c0bf2034)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/cpuidle/coupled.c (c0c05518)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/cpuidle/coupled.c:cpuidle_enter_state_coupled
  - drivers/cpuidle/coupled.c:cpuidle_coupled_set_done
```
```
In drivers/mmc/core/sdio_bus.c (c0c15cec)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/firmware/arm_scmi/clock.c (c0c38c48)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/clock.c:scmi_clock_rate_set
```
```
In drivers/remoteproc/remoteproc_core.c (c0c646f4)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/ras/debugfs.c (c0c80534)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_release
```
```
In sound/core/pcm_native.c (c0c90d24)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - sound/core/pcm_native.c:snd_pcm_mmap_data_close
```
```
In net/core/sock.c (c0cca86c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/skbuff.c (c0cd2e68)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_put_abort
```
```
In net/core/sysctl_net_core.c (c0ce10b8)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
```
```
In net/core/dev.c (c0ceaa3c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:clean_xps_maps
  - net/core/dev.c:clean_xps_maps
  - net/core/dev.c:net_disable_timestamp
  - net/core/dev.c:net_dec_egress_queue
  - net/core/dev.c:net_dec_ingress_queue
```
```
In net/core/neighbour.c (c0cfea7c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_mark_dead
```
```
In net/core/xdp.c (c0d1fa54)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (c0d2112c)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In net/core/net-sysfs.c (c0d23860)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/core/sock_map.c (c0d38864)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_free_elem
```
```
In net/sched/cls_api.c (c0d51388)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_offload_dec
```
```
In net/sched/act_api.c (c0d5824c)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In net/netlink/af_netlink.c (c0d5eff4)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_timewait_sock.c (c0d7ac48)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (c0d7c8b0)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp_input.c (c0d86c6c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:clean_acked_data_disable
```
```
In net/ipv4/udp.c (c0da95c0)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In net/ipv4/inet_fragment.c (c0dcab50)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ip_tunnel_core.c (c0dce034)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata
```
```
In net/ipv4/ipmr.c (c0dd8064)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/xfrm/xfrm_policy.c (c0de6df8)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In net/xfrm/xfrm_state.c (c0ded014)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
```
```
In net/unix/af_unix.c (c0df7874)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/garbage.c (c0dfb4c0)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/unix/garbage.c:dec_inflight
```
```
In net/ipv6/route.c (c0e13db8)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In net/ipv6/udp.c (c0e28840)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_destroy_sock
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (c0e2e214)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (c0e39b60)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (c0e40050)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (c0e4204c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
  - net/ipv6/ip6_flowlabel.c:fl_free
```
```
In net/ipv6/ip6mr.c (c0e470e0)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
```
```
In net/ipv6/seg6_hmac.c (c0e53048)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
```
In net/packet/af_packet.c (c0e56ec8)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mm_close
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/netlabel/netlabel_unlabeled.c (c0e67598)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/netlabel/netlabel_cipso_v4.c (c0e683fc)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (c0e69104)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
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
In arch/powerpc/platforms/powernv/idle.c (c0000000000c7034)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/idle.c:pnv_power9_force_smt4_release
```
```
In arch/powerpc/platforms/powernv/vas-window.c (c0000000000e2bbc)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/vas-window.c:vas_win_close
```
```
In arch/powerpc/xmon/xmon.c (c0000000001110d8)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - arch/powerpc/xmon/xmon.c:xmon_core
```
```
In arch/powerpc/kvm/book3s_hv_builtin.c (c000000000121094)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvm_hv_vm_deactivated
```
```
In kernel/fork.c (c0000000001397f0)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/cpu.c (c00000000014142c)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
```
```
In kernel/exit.c (c000000000141d0c)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/workqueue.c (c00000000016891c)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cred.c (c00000000017607c)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/async.c (c0000000001776f4)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/ucount.c (c000000000179904)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (c000000000187bac)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (c00000000019ed9c)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (c0000000001a3fa4)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (c0000000001a64c4)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (c0000000001ae214)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/power/process.c (c0000000001c7ed4)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
```
```
In kernel/irq/spurious.c (c0000000001d7b34)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/rcu/update.c (c0000000001e33b0)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_end_inkernel_boot
```
```
In kernel/rcu/srcutree.c (c0000000001e54fc)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/futex.c (c000000000221d54)
Location: arch/powerpc/include/asm/atomic.h:159
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
In kernel/cgroup/cgroup.c (c0000000002437c8)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/cgroup/legacy_freezer.c (c00000000024ba78)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_css_offline
```
```
In kernel/debug/debug_core.c (c000000000270f58)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/trace/ftrace.c (c00000000028f958)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
```
```
In kernel/trace/ring_buffer.c (c0000000002995fc)
Location: arch/powerpc/include/asm/atomic.h:159
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
In kernel/trace/trace.c (c0000000002a709c)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:s_stop
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (c0000000002b9590)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (c0000000002bb018)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (c0000000002be354)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/fgraph.c (c0000000002c41d8)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
```
```
In kernel/trace/trace_kdb.c (c0000000002f4e8c)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/bpf/syscall.c (c000000000304bf0)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
```
```
In kernel/bpf/hashtab.c (c00000000032070c)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/offload.c (c0000000003356b0)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (c00000000034ceac)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_migrate_context
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
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
```
```
In kernel/events/callchain.c (c000000000355b24)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/uprobes.c (c000000000357890)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/padata.c (c00000000035c6fc)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/padata.c:padata_find_next
```
```
In mm/backing-dev.c (c00000000039d2a4)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/mmap.c (c0000000003d0270)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_link_file
  - mm/mmap.c:__remove_shared_vm_struct
```
```
In mm/mmu_gather.c (c0000000003d1ccc)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mprotect.c (c0000000003d241c)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (c0000000003d93a4)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
```
```
In mm/swapfile.c (c0000000003fe8ac)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (c000000000401100)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (c0000000004023d4)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_free_entry
```
```
In mm/huge_memory.c (c00000000043c8cc)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memcontrol.c (c000000000453194)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
```
```
In mm/zpool.c (c000000000464648)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - mm/zpool.c:zpool_destroy_pool
  - mm/zpool.c:zpool_create_pool
  - mm/zpool.c:zpool_create_pool
  - mm/zpool.c:zpool_has_pool
```
```
In fs/open.c (c000000000472c44)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (c00000000047b420)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:__fput
```
```
In fs/namei.c (c000000000492238)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/fs-writeback.c (c0000000004c9430)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:wb_wait_for_completion
```
```
In fs/buffer.c (c0000000004de134)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - fs/buffer.c:buffer_exit_cpu_dead
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:__bforget
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/notify/mark.c (c0000000004f17b8)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify.c (c0000000004f4924)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
```
```
In fs/io_uring.c (c00000000050e594)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
```
```
In fs/mbcache.c (c000000000534328)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/coredump.c (c000000000538a88)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (c000000000541570)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
```
```
In fs/devpts/inode.c (c00000000057ad38)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_kill_index
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/balloc.c (c00000000057d8d4)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (c0000000005820ac)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (c0000000005971c8)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (c000000000598a60)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (c0000000005a93d8)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (c0000000005c04a0)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (c0000000005c29a4)
Location: arch/powerpc/include/asm/atomic.h:159
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
In fs/ext4/mmp.c (c0000000005c39ec)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (c0000000005ed7cc)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/commit.c (c0000000006071f4)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (c00000000060954c)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/squashfs/block.c (c0000000006145b4)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (c00000000061b428)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (c00000000061b7f8)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (c00000000061bc6c)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (c00000000061c144)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (c00000000061c560)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In fs/ecryptfs/miscdev.c (c000000000640edc)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release
```
```
In fs/fuse/dev.c (c00000000064605c)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_wait_answer
```
```
In ipc/util.c (c000000000665fd4)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
```
```
In ipc/msg.c (c00000000066a194)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In security/keys/gc.c (c000000000679250)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
```
```
In security/keys/keyctl.c (c000000000680a68)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/selinux/avc.c (c00000000069d324)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_replace
  - security/selinux/avc.c:avc_node_kill
  - security/selinux/avc.c:avc_node_delete
```
```
In security/selinux/hooks.c (c00000000069f5d0)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_dec
```
```
In security/selinux/xfrm.c (c0000000006cfbe8)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_state_free
  - security/selinux/xfrm.c:selinux_xfrm_policy_free
```
```
In security/tomoyo/common.c (c0000000006e3398)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (c0000000006eb3f4)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (c0000000006ed7f8)
Location: arch/powerpc/include/asm/atomic.h:159
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
In security/tomoyo/environ.c (c0000000006ef2bc)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (c0000000006f112c)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
```
```
In security/tomoyo/gc.c (c0000000006f1a80)
Location: arch/powerpc/include/asm/atomic.h:159
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
In security/tomoyo/group.c (c0000000006f291c)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (c0000000006f3694)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/network.c (c0000000006f4fb0)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
```
In security/tomoyo/securityfs_if.c (c0000000006f6834)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (c0000000006f6a60)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_task_free
  - security/tomoyo/tomoyo.c:tomoyo_task_free
  - security/tomoyo/tomoyo.c:tomoyo_bprm_committed_creds
  - security/tomoyo/tomoyo.c:tomoyo_cred_prepare
  - security/tomoyo/tomoyo.c:tomoyo_domain
```
```
In block/blk-flush.c (c00000000077bafc)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (c00000000077d718)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - block/blk-ioc.c:exit_io_context
```
```
In block/blk-mq.c (c000000000787244)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-tag.c (c00000000078bb7c)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-iocost.c (c0000000007b233c)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (c00000000081ee84)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_finish_wait
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/pci/pci.c (c000000000863d80)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (c0000000008815ac)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
```
In drivers/pci/ats.c (c000000000886908)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (c0000000008a51b0)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
```
In drivers/dma/dmaengine.c (c0000000008c8810)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/reset/core.c (c0000000008eae68)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
```
```
In drivers/tty/tty_buffer.c (c0000000008fcd44)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
```
In drivers/tty/vt/keyboard.c (c0000000013a5a5c)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/tty/serial/kgdb_nmi.c (c00000000093ef04)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_close
```
```
In drivers/tty/serial/kgdboc.c (c00000000093fb5c)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_post_exp_handler
```
```
In drivers/char/agp/backend.c (c000000000951fb4)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_release
```
```
In drivers/char/agp/generic.c (c000000000955d34)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
```
```
In drivers/connector/cn_queue.c (c000000000970ac8)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
```
```
In drivers/connector/cn_proc.c (c0000000009718d8)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
```
```
In drivers/base/dd.c (c000000000981d54)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/power/runtime.c (c00000000099ace4)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (c0000000009e60d0)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_irq_set_wake
```
```
In drivers/mfd/mfd-core.c (c0000000009e8868)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/nvdimm/namespace_devs.c (c000000000a0892c)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:deactivate_labels
```
```
In drivers/scsi/scsi_lib.c (c000000000a2f0f8)
Location: arch/powerpc/include/asm/atomic.h:159
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
In drivers/net/ppp/ppp_generic.c (c000000000aa6584)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
```
```
In drivers/vfio/vfio.c (c000000000aae9f8)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_release
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_add_container_user
  - drivers/vfio/vfio.c:vfio_group_add_container_user
```
```
In drivers/usb/core/hcd.c (c000000000ad5ea4)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/urb.c (c000000000ad9fd8)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
```
```
In drivers/power/supply/power_supply_core.c (c000000000bacf40)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (c000000000bd2744)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - drivers/md/md.c:md_release
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (c000000000bea7f4)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stats.c (c000000000c008d0)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In drivers/edac/edac_pci_sysfs.c (c000000000c09030)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/mmc/core/sdio_bus.c (c000000000c37968)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/remoteproc/remoteproc_core.c (c000000000c5dbe8)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/ras/debugfs.c (c000000000c7158c)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_release
```
```
In net/core/sock.c (c000000000c80a5c)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
```
```
In net/core/skbuff.c (c000000000c8d3e0)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_put_abort
```
```
In net/core/datagram.c (c000000000c94544)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/dev.c (c000000000ca6d98)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
```
```
In net/core/neighbour.c (c000000000cc83a0)
Location: arch/powerpc/include/asm/atomic.h:159
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
In net/core/xdp.c (c000000000cf0e64)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/flow_offload.c (c000000000cf2730)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
```
```
In net/core/sock_map.c (c000000000d143c0)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
```
In net/core/devlink.c (c000000000d17638)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
```
```
In net/sched/cls_api.c (c000000000d3ce24)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_cb_destroy
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_cls_offload_cnt_update
```
```
In net/sched/act_api.c (c000000000d4399c)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
```
```
In net/netlink/af_netlink.c (c000000000d4d5f4)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_hashtables.c (c000000000d6ffb8)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (c000000000d71308)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/inet_connection_sock.c (c000000000d73b38)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp.c (c000000000d76d28)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (c000000000d9014c)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
```
```
In net/ipv4/tcp_ipv4.c (c000000000d97d6c)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/raw.c (c000000000da790c)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (c000000000dac8e0)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
```
```
In net/ipv4/arp.c (c000000000db6618)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/igmp.c (c000000000dc8a78)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/inet_fragment.c (c000000000dd9e34)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (c000000000deb514)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/xfrm/xfrm_policy.c (c000000000dfc7a0)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
```
```
In net/xfrm/xfrm_state.c (c000000000e07960)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_state_update
```
```
In net/unix/af_unix.c (c000000000e17ff0)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/addrconf.c (c000000000e2efc0)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/route.c (c000000000e391f8)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
```
```
In net/ipv6/ndisc.c (c000000000e4f0fc)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/udp.c (c000000000e54ef4)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (c000000000e5b310)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (c000000000e664ac)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6a0d8)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (c000000000e70e1c)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (c000000000e73614)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
```
In net/ipv6/ip6mr.c (c000000000e79744)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
```
```
In net/ipv6/xfrm6_policy.c (c000000000e7e054)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
```
```
In net/ipv6/seg6_hmac.c (c000000000e8ab54)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
```
In net/ipv6/inet6_hashtables.c (c000000000e8f11c)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (c000000000e8fa70)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mm_close
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/netlabel/netlabel_unlabeled.c (c000000000ea5a94)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/netlabel/netlabel_cipso_v4.c (c000000000ea6cc8)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
```
```
In net/netlabel/netlabel_calipso.c (c000000000ea7fe0)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
```
In net/xdp/xsk.c (c000000000ebf300)
Location: arch/powerpc/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In arch/riscv/kernel/perf_event.c (ffffffe0000b97d4)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - arch/riscv/kernel/perf_event.c:riscv_event_init
```
```
In kernel/fork.c (ffffffe0000c00f4)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/cpu.c (ffffffe0000c43c8)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In kernel/exit.c (ffffffe0000c47d2)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/workqueue.c (ffffffe0000d91a6)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cred.c (ffffffe0000e1446)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/async.c (ffffffe0000e2556)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/ucount.c (ffffffe0000e3864)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (ffffffe0000e9b6e)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffe0000f59a2)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (ffffffe0000f87c4)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffe0000fa862)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffe0000ff9f6)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/topology.c (ffffffe000101d50)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
```
```
In kernel/power/process.c (ffffffe00010d7f4)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
```
```
In kernel/irq/spurious.c (ffffffe0001161dc)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/rcu/update.c (ffffffe00011e3de)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_end_inkernel_boot
```
```
In kernel/rcu/srcutree.c (ffffffe00011f336)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/futex.c (ffffffe00013fe08)
Location: include/linux/atomic-fallback.h:437
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
In kernel/cgroup/cgroup.c (ffffffe0001502c8)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/cgroup/legacy_freezer.c (ffffffe000155500)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_css_offline
```
```
In kernel/cgroup/cpuset.c (ffffffe00015912c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:cpuset_css_offline
```
```
In kernel/tracepoint.c (ffffffe00016f56c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
```
```
In kernel/trace/ftrace.c (ffffffe0001710b6)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffffffe000177172)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_record_enable
```
```
In kernel/trace/trace.c (ffffffe000184ab8)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_panic_handler
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:s_stop
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (ffffffe000187a98)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffe00018928c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffe00018a716)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/fgraph.c (0)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffe00019fe0a)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
```
```
In kernel/bpf/hashtab.c (ffffffe0001afc3a)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/offload.c (ffffffe0001be3da)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/bpf/cgroup.c (ffffffe0001c276a)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/events/core.c (ffffffe0001cb1a8)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:sw_perf_event_destroy
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
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
```
```
In kernel/events/callchain.c (ffffffe0001d1cc6)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/padata.c (ffffffe0001d31f2)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - kernel/padata.c:padata_find_next
```
```
In mm/backing-dev.c (ffffffe0001f5e80)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/mmap.c (ffffffe000210286)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_link_file
  - mm/mmap.c:__remove_shared_vm_struct
```
```
In mm/mmu_gather.c (ffffffe00021102e)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mprotect.c (ffffffe000211442)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffe000213af2)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In mm/swapfile.c (ffffffe0002279fe)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffffffe000229522)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffe00022a2b0)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_free_entry
```
```
In mm/memcontrol.c (ffffffe00024486e)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_free
```
```
In mm/zpool.c (ffffffe00024baf4)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - mm/zpool.c:zpool_destroy_pool
  - mm/zpool.c:zpool_create_pool
  - mm/zpool.c:zpool_create_pool
  - mm/zpool.c:zpool_has_pool
```
```
In fs/open.c (ffffffe00025398e)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffe00025823c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffe000265f28)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/fs-writeback.c (ffffffe00028679c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffe000291a36)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/buffer.c:buffer_exit_cpu_dead
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:__bforget
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/notify/mark.c (ffffffe00029ee2c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify.c (ffffffe0002a0e06)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
```
```
In fs/io_uring.c (ffffffe0002af886)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
```
```
In fs/mbcache.c (ffffffe0002c4182)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/coredump.c (ffffffe0002c6a04)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffffffe0002cc7ec)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In fs/devpts/inode.c (ffffffe0002ee79e)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_kill_index
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/balloc.c (ffffffe0002f048c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffe0002f2dc8)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffe00030109e)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffe00030213c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffe00030c74a)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffe00031b13e)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffe00031c612)
Location: include/linux/atomic-fallback.h:437
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
In fs/ext4/mmp.c (ffffffe00031d0d4)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffe000335110)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/commit.c (ffffffe0003462d0)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffe0003478cc)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/squashfs/block.c (ffffffe00034ed08)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffffffe0003538b0)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffe000353b0a)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffe000353d7a)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffe000353ff4)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffe0003542a4)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In fs/ecryptfs/miscdev.c (ffffffe00036bfd4)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release
```
```
In fs/fuse/dev.c (ffffffe00037030e)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_wait_answer
```
```
In ipc/util.c (ffffffe0003848fe)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In ipc/msg.c (ffffffe000385ed2)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - ipc/msg.c:freeque
```
```
In security/keys/gc.c (ffffffe00038eeec)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In security/keys/keyctl.c (ffffffe00039369e)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/selinux/avc.c (ffffffe0003a2894)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_compute_av
  - security/selinux/avc.c:avc_flush
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_node_kill
```
```
In security/selinux/hooks.c (ffffffe0003a37b8)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_dec
```
```
In security/selinux/xfrm.c (ffffffe0003c08b4)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_state_free
  - security/selinux/xfrm.c:selinux_xfrm_policy_free
```
```
In security/tomoyo/common.c (ffffffe0003cb396)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffe0003cf738)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffe0003d0ca4)
Location: include/linux/atomic-fallback.h:437
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
In security/tomoyo/environ.c (ffffffe0003d17c0)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffe0003d2c0a)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
```
```
In security/tomoyo/gc.c (ffffffe0003d3200)
Location: include/linux/atomic-fallback.h:437
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
In security/tomoyo/group.c (ffffffe0003d3dfe)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffe0003d447e)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/network.c (ffffffe0003d5364)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
```
In security/tomoyo/securityfs_if.c (ffffffe0003d60c8)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffe0003d6226)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_task_free
  - security/tomoyo/tomoyo.c:tomoyo_task_free
  - security/tomoyo/tomoyo.c:tomoyo_bprm_committed_creds
  - security/tomoyo/tomoyo.c:tomoyo_cred_prepare
```
```
In block/blk-flush.c (ffffffe000428076)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (ffffffe000429516)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - block/blk-ioc.c:exit_io_context
```
```
In block/blk-mq.c (ffffffe00042f6a6)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-tag.c (ffffffe0004323ec)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-iocost.c (ffffffe00044ae3c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (ffffffe0004944c0)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_finish_wait
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/pci/pci.c (ffffffe0004bf3c2)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffe0004d6136)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
```
In drivers/pci/ats.c (ffffffe0004dfb5e)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffe0004f489a)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
```
In drivers/dma/dmaengine.c (ffffffe0005170ee)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/reset/core.c (ffffffe00052c1ba)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffe000536722)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
```
In drivers/tty/vt/keyboard.c (ffffffe00002e364)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/connector/cn_queue.c (ffffffe000573e3e)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/cn_proc.c (ffffffe0005744f0)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In drivers/base/dd.c (ffffffe00057e832)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/power/runtime.c (ffffffe00058c476)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (ffffffe0005b1ef6)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_irq_set_wake
```
```
In drivers/mfd/mfd-core.c (ffffffe0005b3a52)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/nvdimm/namespace_devs.c (ffffffe0005c81da)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:deactivate_labels
```
```
In drivers/scsi/scsi_lib.c (ffffffe0005dda50)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_enable_disk_events
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
```
In drivers/net/ppp/ppp_generic.c (ffffffe00062bef6)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
```
```
In drivers/usb/core/hcd.c (ffffffe00064031a)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/urb.c (ffffffe0006431e6)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
```
```
In drivers/i2c/i2c-core-base.c (ffffffe0006b93d6)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_transfer_trace_unreg
```
```
In drivers/power/supply/power_supply_core.c (ffffffe0006c88da)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:devm_power_supply_put
```
```
In drivers/md/md.c (ffffffe0006dd492)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffe0006ef976)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stats.c (ffffffe0006fae76)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffe000700930)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/mmc/core/sdio_bus.c (ffffffe000712750)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/ras/debugfs.c (ffffffe00073697e)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_release
```
```
In net/core/sock.c (ffffffe00073ce54)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/core/sock.c:sk_stop_timer
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/skbuff.c (ffffffe000745d5a)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In net/core/datagram.c (ffffffe00074a68c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/sysctl_net_core.c (ffffffe000752294)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
```
```
In net/core/dev.c (ffffffe00075a8e4)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:clean_xps_maps
  - net/core/dev.c:clean_xps_maps
  - net/core/dev.c:net_disable_timestamp
  - net/core/dev.c:net_dec_egress_queue
  - net/core/dev.c:net_dec_ingress_queue
```
```
In net/core/neighbour.c (ffffffe00076b420)
Location: include/linux/atomic-fallback.h:437
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
In net/core/xdp.c (ffffffe000784d8c)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/flow_offload.c (ffffffe000786284)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In net/core/net-sysfs.c (ffffffe000789128)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/core/sock_map.c (ffffffe00079aaee)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
```
In net/core/devlink.c (ffffffe00079c26a)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
```
```
In net/sched/cls_api.c (ffffffe0007b0ecc)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_cb_destroy
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_cls_offload_cnt_update
```
```
In net/sched/act_api.c (ffffffe0007b4982)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/sched/act_api.c:__tcf_action_put
  - net/sched/act_api.c:__tcf_action_put
```
```
In net/netlink/af_netlink.c (ffffffe0007babe0)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_hashtables.c (ffffffe0007d09c6)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffe0007d170a)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d33e2)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp.c (ffffffe0007d4a98)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffe0007db774)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:clean_acked_data_disable
```
```
In net/ipv4/tcp_output.c (ffffffe0007e5f78)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007eb2d6)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/raw.c (ffffffe0007f53da)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffe0007f8680)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In net/ipv4/arp.c (ffffffe0007fefea)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/igmp.c (ffffffe00080a4bc)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/inet_fragment.c (ffffffe0008150b0)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ip_tunnel_core.c (ffffffe000817c98)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata
```
```
In net/ipv4/ipmr.c (ffffffe00082098a)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082ab50)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffe000831fba)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_state_update
```
```
In net/unix/af_unix.c (ffffffe00083e1fa)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/addrconf.c (ffffffe00084fa02)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/route.c (ffffffe0008552be)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In net/ipv6/ndisc.c (ffffffe000862468)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/udp.c (ffffffe000865c98)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_destroy_sock
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffe00086aa86)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/mcast.c (ffffffe000871e90)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000874bd4)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffe000879696)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffe00087b1b6)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
  - net/ipv6/ip6_flowlabel.c:fl_free
```
```
In net/ipv6/ip6mr.c (ffffffe00087f60a)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
```
```
In net/ipv6/xfrm6_policy.c (ffffffe000882242)
Location: include/linux/atomic-fallback.h:437
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffe00088a5f0)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
```
In net/ipv6/inet6_hashtables.c (ffffffe00088d906)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffe00088df86)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mm_close
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffe00089bfe0)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffe00089cae6)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
```
```
In net/netlabel/netlabel_calipso.c (ffffffe00089d600)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
```
In net/xdp/xsk.c (ffffffe0008ac224)
Location: include/linux/atomic-fallback.h:437
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In arch/x86/events/core.c (ffffffff81006da5)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
```
```
In arch/x86/events/intel/core.c (ffffffff8100c905)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff81017c6a)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_put_constraint
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff810192f5)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In arch/x86/xen/spinlock.c (ffffffff8102d6cf)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/xen/spinlock.c:xen_qlock_wait
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104cbf5)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_unregister_decode_chain
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81050421)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_hcpu_update
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105c716)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105f830)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_release
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81062025)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff8106274b)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/ftrace.c (ffffffff8106e010)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_code
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108bb83)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In kernel/fork.c (ffffffff81098818)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/cpu.c (ffffffff8109deaf)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In kernel/exit.c (ffffffff8109e452)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/workqueue.c (ffffffff810bc203)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cred.c (ffffffff810c7e7c)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/async.c (ffffffff810c8dcb)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/ucount.c (ffffffff810ca14d)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (ffffffff810d4cc1)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff810e6127)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (ffffffff810e83bc)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810ea390)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff810ef62b)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/power/process.c (ffffffff811018e7)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
```
```
In kernel/irq/spurious.c (ffffffff81112527)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/rcu/update.c (ffffffff8111c345)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_end_inkernel_boot
```
```
In kernel/rcu/srcutree.c (ffffffff8111d945)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/time/clocksource.c (ffffffff81135930)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/futex.c (ffffffff81146273)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81162a30)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
  - kernel/cgroup/legacy_freezer.c:freezer_css_offline
```
```
In kernel/debug/debug_core.c (ffffffff8117c7a7)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/watchdog_hld.c (ffffffff81188ce5)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
```
```
In kernel/trace/ftrace.c (ffffffff81190bf6)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffffffff81196a50)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:s_stop
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (ffffffff811aa2f3)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811ab2c8)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811adb2c)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/fgraph.c (ffffffff811b1f55)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In kernel/trace/trace_kdb.c (ffffffff811cd6a9)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/bpf/syscall.c (ffffffff811d6f01)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811ec44c)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/offload.c (ffffffff811fa4dd)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffffffff8120b499)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/uprobes.c (ffffffff812122bd)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/padata.c (ffffffff8121672e)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/padata.c:padata_find_next
```
```
In mm/backing-dev.c (ffffffff81240f75)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/mmap.c (ffffffff81264a4c)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_link_file
  - mm/mmap.c:__remove_shared_vm_struct
```
```
In mm/mmu_gather.c (ffffffff8126626b)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mprotect.c (ffffffff81266f87)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff8126c49e)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In mm/swapfile.c (ffffffff81284914)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffffffff81286582)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff81287045)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_free_entry
```
```
In mm/huge_memory.c (ffffffff812ad5b4)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memcontrol.c (ffffffff812bbca2)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
```
```
In mm/zpool.c (ffffffff812c6465)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/zpool.c:zpool_put_driver
```
```
In fs/open.c (ffffffff812d0787)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff812d73aa)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff812e6c68)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/fs-writeback.c (ffffffff8130ae3f)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff8131b446)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/notify/mark.c (ffffffff8132647a)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8132878d)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
```
```
In fs/mbcache.c (ffffffff81357b2f)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/coredump.c (ffffffff8135a77f)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffffffff81360b1b)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In fs/devpts/inode.c (ffffffff813854de)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_kill_index
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/balloc.c (ffffffff81387257)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8138a6a1)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff8139a4cf)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff813a7df8)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff813b7f91)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff813b97c1)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff813d7e91)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/commit.c (ffffffff813eb671)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813ecf84)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/squashfs/block.c (ffffffff813f453b)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff813f9622)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff813f9929)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff813f9cc8)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff813f9fd6)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff813fa2a9)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In fs/ecryptfs/miscdev.c (ffffffff81414990)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release
```
```
In ipc/util.c (ffffffff8142f058)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In ipc/msg.c (ffffffff81431c4d)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In security/keys/gc.c (ffffffff8143cbe6)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In security/keys/keyctl.c (ffffffff8144196d)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/selinux/avc.c (ffffffff814528a3)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_replace
  - security/selinux/avc.c:avc_node_kill
  - security/selinux/avc.c:avc_node_delete
```
```
In security/selinux/hooks.c (ffffffff814541a5)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_dec
```
```
In security/selinux/xfrm.c (ffffffff81473625)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In security/tomoyo/common.c (ffffffff8147f13f)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff8148356d)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff81485165)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff814874c0)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff81488860)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/network.c (ffffffff814897b6)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
```
In security/tomoyo/securityfs_if.c (ffffffff8148a55e)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8148a6cf)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (ffffffff814e2b2a)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - block/blk-ioc.c:exit_io_context
```
```
In block/blk-mq.c (ffffffff814e95d5)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-tag.c (ffffffff814ecbf6)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-iocost.c (ffffffff8150828c)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (ffffffff81554743)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_finish_wait
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/pci/pci.c (ffffffff81578ee2)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81594298)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
```
In drivers/pci/ats.c (ffffffff815a01f8)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815b129b)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
```
In drivers/dma/dmaengine.c (ffffffff8161d093)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/reset/core.c (ffffffff8164704f)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff81652b2a)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
```
In drivers/tty/vt/keyboard.c (ffffffff828e89c9)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_start
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff8167e17c)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_close
```
```
In drivers/tty/serial/kgdboc.c (ffffffff8167e915)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_post_exp_handler
```
```
In drivers/char/agp/backend.c (ffffffff8168b17e)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_release
```
```
In drivers/char/agp/generic.c (ffffffff8168ded4)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8169177f)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
```
```
In drivers/connector/cn_queue.c (ffffffff816b9aba)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffff816ba3bb)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In drivers/base/dd.c (ffffffff816c50ae)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/power/runtime.c (ffffffff816d3664)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In drivers/mfd/mfd-core.c (ffffffff81701e75)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8170be73)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:deactivate_labels
```
```
In drivers/scsi/scsi_lib.c (ffffffff817262d3)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
```
```
In drivers/usb/core/hcd.c (ffffffff817a5492)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/urb.c (ffffffff817a867f)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81828052)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (ffffffff8183adf7)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffff8184f72e)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stats.c (ffffffff8185bc6d)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff818616cc)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81884a4a)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81896f85)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/ras/debugfs.c (ffffffff818a1855)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_release
```
```
In net/core/skbuff.c (ffffffff818bb90e)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_put_abort
```
```
In net/core/dev.c (ffffffff818cd272)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In net/core/neighbour.c (ffffffff818e4d71)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81903b94)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In net/core/sock_map.c (ffffffff8191996d)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_free_elem
```
```
In net/sched/cls_api.c (ffffffff819357f0)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_cls_offload_cnt_reset
  - net/sched/cls_api.c:tc_cls_offload_cnt_update
```
```
In net/sched/act_api.c (ffffffff81939d4d)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff819405f0)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8195a187)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195c0ee)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/inet_fragment.c (ffffffff819a6188)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff819b23d2)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/xfrm/xfrm_policy.c (ffffffff819bffd2)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff819c6858)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
```
```
In net/ipv6/route.c (ffffffff819e9b62)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In net/ipv6/udp.c (ffffffff819ff40e)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81a039e1)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0e5bc)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81a13a1e)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a15590)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
```
In net/ipv6/ip6mr.c (ffffffff81a1a676)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a2595d)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
```
In net/packet/af_packet.c (ffffffff81a29010)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mm_close
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a388de)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a395ba)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a3a2b0)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
```
```
In arch/x86/events/intel/core.c (ffffffff8100b105)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff810170ba)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_put_constraint
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff810186c5)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103bfa5)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_unregister_decode_chain
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8103fa81)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_hcpu_update
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104c8e6)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8104fb60)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_release
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff810523d9)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff81052ae5)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/ftrace.c (ffffffff8105e430)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_code
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8107a6a3)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In kernel/fork.c (ffffffff81087282)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/cpu.c (ffffffff8108c8cf)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In kernel/exit.c (ffffffff8108ce71)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/workqueue.c (ffffffff810aaa93)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cred.c (ffffffff810b669c)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/async.c (ffffffff810b75eb)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/ucount.c (ffffffff810b8967)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (ffffffff810c3311)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff810d52c7)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (ffffffff810d7f70)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810da3c0)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff810df69b)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/power/process.c (ffffffff810f1ca7)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
```
```
In kernel/irq/spurious.c (ffffffff81103247)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/rcu/update.c (ffffffff8110d425)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_end_inkernel_boot
```
```
In kernel/rcu/srcutree.c (ffffffff8110e9e5)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/rcu/tree.c (ffffffff8110f4d0)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_nocb_bypass_lock
```
```
In kernel/time/clocksource.c (ffffffff81128339)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/futex.c (ffffffff8113957d)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81155c80)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
  - kernel/cgroup/legacy_freezer.c:freezer_css_offline
```
```
In kernel/debug/debug_core.c (ffffffff8116f947)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/watchdog_hld.c (ffffffff8117be25)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
```
```
In kernel/trace/ftrace.c (ffffffff811837b9)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffffffff81189d40)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:s_stop
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (ffffffff8119d258)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8119e5d1)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811a0973)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/fgraph.c (ffffffff811a4d65)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In kernel/trace/trace_kdb.c (ffffffff811c0479)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/bpf/syscall.c (ffffffff811c9cc1)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811df1dc)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/offload.c (ffffffff811ed22d)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffffffff811fe269)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/uprobes.c (ffffffff8120504d)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/padata.c (ffffffff8120948e)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/padata.c:padata_find_next
```
```
In mm/backing-dev.c (ffffffff81233f75)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/mmap.c (ffffffff81256e6c)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_link_file
  - mm/mmap.c:__remove_shared_vm_struct
```
```
In mm/mmu_gather.c (ffffffff8125868b)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mprotect.c (ffffffff812590a7)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff8125e50e)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In mm/swapfile.c (ffffffff81276784)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffffffff812783e2)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff81278ea5)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_free_entry
```
```
In mm/huge_memory.c (ffffffff8129e53b)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memcontrol.c (ffffffff812ace02)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
```
```
In mm/zpool.c (ffffffff812b74a5)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/zpool.c:zpool_put_driver
```
```
In fs/open.c (ffffffff812c1407)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff812c802a)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff812d78a8)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/fs-writeback.c (ffffffff812fba59)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff8130bfe6)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/notify/mark.c (ffffffff8131701a)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8131932d)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
```
```
In fs/mbcache.c (ffffffff813487df)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/coredump.c (ffffffff8134b429)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffffffff813517bb)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In fs/devpts/inode.c (ffffffff81375f6e)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_kill_index
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/balloc.c (ffffffff81377ce7)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8137b131)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff8138af5f)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff81398888)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff813a8a21)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff813aa251)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff813c8911)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/commit.c (ffffffff813dc0f1)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813dda04)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/squashfs/block.c (ffffffff813e4fbb)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff813ea0a2)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff813ea3a9)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff813ea748)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff813eaa56)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff813ead29)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In fs/ecryptfs/miscdev.c (ffffffff81405410)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release
```
```
In ipc/util.c (ffffffff8141fad8)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In ipc/msg.c (ffffffff814226cd)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In security/keys/gc.c (ffffffff8142d656)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In security/keys/keyctl.c (ffffffff814323dd)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/selinux/avc.c (ffffffff814432f3)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_replace
  - security/selinux/avc.c:avc_node_kill
  - security/selinux/avc.c:avc_node_delete
```
```
In security/selinux/hooks.c (ffffffff81444be5)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_dec
```
```
In security/selinux/xfrm.c (ffffffff81464045)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In security/tomoyo/common.c (ffffffff8146fb5f)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff81473f8d)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff81475b85)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff81477ee0)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff81479280)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/network.c (ffffffff8147a1d6)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
```
In security/tomoyo/securityfs_if.c (ffffffff8147af7e)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8147b0ef)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (ffffffff814d34ba)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - block/blk-ioc.c:exit_io_context
```
```
In block/blk-mq.c (ffffffff814d9b45)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-tag.c (ffffffff814dd146)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-iocost.c (ffffffff814f873c)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (ffffffff815449c3)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_finish_wait
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/pci/pci.c (ffffffff81567622)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81583428)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
```
In drivers/pci/ats.c (ffffffff8158f388)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815a042b)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
```
In drivers/dma/dmaengine.c (ffffffff81611783)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/reset/core.c (ffffffff816274af)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff81632f6a)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
```
In drivers/tty/vt/keyboard.c (ffffffff828e012c)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_start
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff8165d26c)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_close
```
```
In drivers/tty/serial/kgdboc.c (ffffffff8165da05)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_post_exp_handler
```
```
In drivers/char/agp/backend.c (ffffffff81668b7e)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_release
```
```
In drivers/char/agp/generic.c (ffffffff8166b8c4)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8166f16f)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
```
```
In drivers/connector/cn_queue.c (ffffffff816976fa)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffff81697ffb)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In drivers/base/dd.c (ffffffff816a032e)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/power/runtime.c (ffffffff816ae924)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In drivers/mfd/mfd-core.c (ffffffff816d5c85)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816df8f3)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:deactivate_labels
```
```
In drivers/scsi/scsi_lib.c (ffffffff816ff703)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
```
```
In drivers/vfio/vfio.c (ffffffff8177af55)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_release
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_add_container_user
  - drivers/vfio/vfio.c:vfio_group_add_container_user
```
```
In drivers/usb/core/hcd.c (ffffffff81796f89)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/urb.c (ffffffff8179a08f)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
```
```
In drivers/power/supply/power_supply_core.c (ffffffff817ef6e2)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (ffffffff81802467)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffff81816d3e)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stats.c (ffffffff8182323d)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81828c7c)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/hv/channel.c (ffffffff818519d7)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/hv/channel.c:vmbus_reset_channel_cb
```
```
In drivers/hv/channel_mgmt.c (ffffffff81852588)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/hv/channel_mgmt.c:vmbus_onoffer
  - drivers/hv/channel_mgmt.c:vmbus_onoffer
  - drivers/hv/channel_mgmt.c:vmbus_onoffer
```
```
In drivers/ras/debugfs.c (ffffffff8185cfc5)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_release
```
```
In net/core/skbuff.c (ffffffff8187584e)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_put_abort
```
```
In net/core/dev.c (ffffffff81887302)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In net/core/neighbour.c (ffffffff8189ebb1)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff818bd9c4)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In net/core/sock_map.c (ffffffff818d371d)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_free_elem
```
```
In net/sched/cls_api.c (ffffffff818ef2f0)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_cls_offload_cnt_reset
  - net/sched/cls_api.c:tc_cls_offload_cnt_update
```
```
In net/sched/act_api.c (ffffffff818f384d)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff818fa0e0)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81913c77)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81915bde)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/inet_fragment.c (ffffffff8195fc48)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff8196ea02)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197cdc2)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff81983648)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
```
```
In net/ipv6/route.c (ffffffff819a6922)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In net/ipv6/udp.c (ffffffff819bc1ce)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff819c07a1)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cb37c)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff819d07de)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff819d2350)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
```
In net/ipv6/ip6mr.c (ffffffff819d7436)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e271d)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
```
In net/packet/af_packet.c (ffffffff819e6200)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mm_close
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f54fe)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f61da)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819f6ed0)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
```
```
In arch/x86/events/intel/core.c (ffffffff8100c8c5)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff81017c2a)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_put_constraint
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff810192b5)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In arch/x86/xen/spinlock.c (ffffffff8102d52f)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/xen/spinlock.c:xen_qlock_wait
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104ca35)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_unregister_decode_chain
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff810502d1)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_hcpu_update
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105cb46)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105fc60)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_release
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81062445)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff81062bfb)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/ftrace.c (ffffffff8106e4c0)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_code
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108bb33)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In kernel/fork.c (ffffffff810987c8)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/cpu.c (ffffffff8109de5f)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In kernel/exit.c (ffffffff8109e402)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/workqueue.c (ffffffff810bb763)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cred.c (ffffffff810c73cc)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/async.c (ffffffff810c82fb)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/ucount.c (ffffffff810c967d)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (ffffffff810d1b01)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff810e24f7)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (ffffffff810e50e0)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810e74c0)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff810ec75b)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/power/process.c (ffffffff810fec77)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
```
```
In kernel/irq/spurious.c (ffffffff81110417)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/rcu/update.c (ffffffff8111a235)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_end_inkernel_boot
```
```
In kernel/rcu/srcutree.c (ffffffff8111b835)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/time/clocksource.c (ffffffff81133650)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/futex.c (ffffffff81144123)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81160800)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
  - kernel/cgroup/legacy_freezer.c:freezer_css_offline
```
```
In kernel/debug/debug_core.c (ffffffff8117a577)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/watchdog_hld.c (ffffffff81186ab5)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
```
```
In kernel/trace/ftrace.c (ffffffff8118e9c6)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffffffff81194820)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:s_stop
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (ffffffff811a80c3)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811a9098)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811ab8fc)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/fgraph.c (ffffffff811afd25)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In kernel/trace/trace_kdb.c (ffffffff811cb479)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/bpf/syscall.c (ffffffff811d4cd1)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811ea21c)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/offload.c (ffffffff811f82ad)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffffffff81209239)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/uprobes.c (ffffffff8121005d)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/padata.c (ffffffff812144ce)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/padata.c:padata_find_next
```
```
In mm/backing-dev.c (ffffffff8123ed15)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/mmap.c (ffffffff812627ec)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_link_file
  - mm/mmap.c:__remove_shared_vm_struct
```
```
In mm/mmu_gather.c (ffffffff8126400b)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mprotect.c (ffffffff81264d27)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff8126a23e)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In mm/swapfile.c (ffffffff81282724)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffffffff81284392)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff81284e55)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_free_entry
```
```
In mm/huge_memory.c (ffffffff812ab3c4)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memcontrol.c (ffffffff812b9ab2)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
```
```
In mm/zpool.c (ffffffff812c4275)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/zpool.c:zpool_put_driver
```
```
In fs/open.c (ffffffff812ce597)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff812d51ba)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff812e4a78)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/fs-writeback.c (ffffffff81308c2f)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff81318f16)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/notify/mark.c (ffffffff81323f4a)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8132625d)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
```
```
In fs/mbcache.c (ffffffff813555ff)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/coredump.c (ffffffff8135824f)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffffffff8135e5eb)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In fs/devpts/inode.c (ffffffff81382fae)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_kill_index
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/balloc.c (ffffffff81384d27)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff81388001)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff81397d2f)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff813a5658)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff813b57f1)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff813b7021)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff813d5321)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/commit.c (ffffffff813e89f1)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813ea304)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/squashfs/block.c (ffffffff813f18bb)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff813f69a2)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff813f6ca9)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff813f7048)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff813f7356)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff813f7629)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In fs/ecryptfs/miscdev.c (ffffffff81411d10)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release
```
```
In ipc/util.c (ffffffff8142b1f8)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In ipc/msg.c (ffffffff8142dded)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In security/keys/gc.c (ffffffff81438d86)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In security/keys/keyctl.c (ffffffff8143db0d)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/selinux/avc.c (ffffffff8144e943)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_replace
  - security/selinux/avc.c:avc_node_kill
  - security/selinux/avc.c:avc_node_delete
```
```
In security/selinux/hooks.c (ffffffff81450245)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_dec
```
```
In security/selinux/xfrm.c (ffffffff8146f6c5)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In security/tomoyo/common.c (ffffffff8147b1df)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff8147f60d)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff81481205)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff81483560)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff81484900)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/network.c (ffffffff81485856)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
```
In security/tomoyo/securityfs_if.c (ffffffff814865fe)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8148676f)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (ffffffff814debba)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - block/blk-ioc.c:exit_io_context
```
```
In block/blk-mq.c (ffffffff814e5665)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-tag.c (ffffffff814e8c86)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-iocost.c (ffffffff8150431c)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (ffffffff81550483)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_finish_wait
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/pci/pci.c (ffffffff81578712)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff815947d8)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
```
In drivers/pci/ats.c (ffffffff815a0778)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815b182b)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
```
In drivers/acpi/apei/ghes.c (ffffffff8163795a)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
```
```
In drivers/dma/dmaengine.c (ffffffff8164b033)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/reset/core.c (ffffffff8167540f)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff81680eea)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
```
In drivers/tty/vt/keyboard.c (ffffffff828fc504)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff816ac55c)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_close
```
```
In drivers/tty/serial/kgdboc.c (ffffffff816accf5)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_post_exp_handler
```
```
In drivers/char/agp/backend.c (ffffffff816b93ee)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_release
```
```
In drivers/char/agp/generic.c (ffffffff816bc144)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816bf9ef)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
```
```
In drivers/connector/cn_queue.c (ffffffff816e7f8a)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffff816e888b)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In drivers/base/dd.c (ffffffff816f357e)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/power/runtime.c (ffffffff81701bd4)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In drivers/mfd/mfd-core.c (ffffffff81737295)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8174ac43)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:deactivate_labels
```
```
In drivers/scsi/scsi_lib.c (ffffffff817650a3)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
```
```
In drivers/vfio/vfio.c (ffffffff817c5d25)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_release
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_add_container_user
  - drivers/vfio/vfio.c:vfio_group_add_container_user
```
```
In drivers/usb/core/hcd.c (ffffffff817e1f32)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/urb.c (ffffffff817e511f)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81874f92)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (ffffffff8188a427)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffff8189ed5e)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stats.c (ffffffff818ab29d)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff818b0cfc)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff818d5eea)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/ras/debugfs.c (ffffffff818f2e45)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_release
```
```
In net/core/skbuff.c (ffffffff8190c90e)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_put_abort
```
```
In net/core/dev.c (ffffffff8191e272)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In net/core/neighbour.c (ffffffff81935da1)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81954bc4)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In net/core/sock_map.c (ffffffff8196aafd)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_free_elem
```
```
In net/sched/cls_api.c (ffffffff81986980)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_cls_offload_cnt_reset
  - net/sched/cls_api.c:tc_cls_offload_cnt_update
```
```
In net/sched/act_api.c (ffffffff8198aedd)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81991780)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/netfilter/nf_conntrack_core.c (ffffffff8199ccb7)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_free
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_alloc
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_alloc
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819c4957)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c68be)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/inet_fragment.c (ffffffff81a10a28)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a1cc72)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2aa52)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff81a312d8)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
```
```
In net/ipv6/route.c (ffffffff81a545e2)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a69e8e)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81a6e461)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7903c)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81a7e49e)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a80010)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
```
In net/ipv6/ip6mr.c (ffffffff81a850f6)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a903dd)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
```
In net/packet/af_packet.c (ffffffff81a94bc0)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mm_close
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81aa478e)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81aa546a)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81aa6160)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
```
```
In arch/x86/events/intel/core.c (ffffffff8100caf5)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff81017e6a)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_put_constraint
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff810194f5)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In arch/x86/xen/spinlock.c (ffffffff8102e31f)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/xen/spinlock.c:xen_qlock_wait
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104de45)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_unregister_decode_chain
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81051711)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_hcpu_update
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105e068)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810611c0)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_release
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81063a05)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff810641bb)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/ftrace.c (ffffffff81070740)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_code
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108de93)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff81097bfd)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109a865)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In kernel/fork.c (ffffffff810a03ef)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/cpu.c (ffffffff810a5d4f)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In kernel/exit.c (ffffffff810a6317)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/workqueue.c (ffffffff810c3b5d)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cred.c (ffffffff810cf89c)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
```
```
In kernel/async.c (ffffffff810d082b)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/ucount.c (ffffffff810d1bcb)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (ffffffff810dc4c1)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff810ee09c)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (ffffffff810f1077)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810f2480)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff810f779b)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/power/process.c (ffffffff81109f47)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
```
```
In kernel/irq/spurious.c (ffffffff8111b997)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/rcu/update.c (ffffffff81125985)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_end_inkernel_boot
```
```
In kernel/rcu/srcutree.c (ffffffff81126a95)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/time/clocksource.c (ffffffff81140070)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/futex.c (ffffffff811501a6)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8116db70)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
  - kernel/cgroup/legacy_freezer.c:freezer_css_offline
```
```
In kernel/debug/debug_core.c (ffffffff81187ea7)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/watchdog_hld.c (ffffffff81194405)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
```
```
In kernel/trace/ftrace.c (ffffffff8119c556)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffffffff811a2430)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:s_stop
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (ffffffff811b5e73)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811b6ed8)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811b97cc)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/fgraph.c (ffffffff811bdd95)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In kernel/trace/trace_kdb.c (ffffffff811d96d9)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/bpf/syscall.c (ffffffff811e3001)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811f85fc)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/offload.c (ffffffff81206620)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffffffff81217fc9)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/uprobes.c (ffffffff8121f07d)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/padata.c (ffffffff8122250e)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - kernel/padata.c:padata_find_next
```
```
In mm/backing-dev.c (ffffffff8124e445)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/backing-dev.c:clear_wb_congested
```
```
In mm/mmap.c (ffffffff812721ac)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_link_file
  - mm/mmap.c:__remove_shared_vm_struct
```
```
In mm/mmu_gather.c (ffffffff812739cb)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mprotect.c (ffffffff812746c1)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff81279bae)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In mm/swapfile.c (ffffffff8129240b)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffffffff81294372)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff81294af5)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_free_entry
```
```
In mm/huge_memory.c (ffffffff812bb714)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memcontrol.c (ffffffff812ca142)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
```
```
In mm/zpool.c (ffffffff812d4e95)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - mm/zpool.c:zpool_put_driver
```
```
In fs/open.c (ffffffff812df3a7)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff812e6000)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff812f59f8)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/fs-writeback.c (ffffffff8131a8c8)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff8132ab46)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/notify/mark.c (ffffffff81335c78)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8133807d)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
```
```
In fs/mbcache.c (ffffffff81368bdf)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/coredump.c (ffffffff8136b981)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffffffff81370fa6)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In fs/devpts/inode.c (ffffffff81396ace)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_kill_index
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/balloc.c (ffffffff813988a7)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8139bd01)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff813ac670)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff813b9d98)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff813ca475)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff813cbd31)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff813ea5a4)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/commit.c (ffffffff813fe249)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813ffc5c)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/squashfs/block.c (ffffffff814074bf)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff8140c632)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff8140c939)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff8140ccd8)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff8140cfe6)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff8140d2b9)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In fs/ecryptfs/miscdev.c (ffffffff81427980)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release
```
```
In ipc/util.c (ffffffff814420f0)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In ipc/msg.c (ffffffff8144484a)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
```
In security/keys/gc.c (ffffffff8144fef6)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In security/keys/keyctl.c (ffffffff81454c97)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/selinux/avc.c (ffffffff81465d23)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_replace
  - security/selinux/avc.c:avc_node_kill
  - security/selinux/avc.c:avc_node_delete
```
```
In security/selinux/hooks.c (ffffffff814676e5)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_dec
```
```
In security/selinux/xfrm.c (ffffffff81486f35)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In security/tomoyo/common.c (ffffffff81492dcf)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff8149713d)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff81498d75)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff8149b0f0)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff8149c440)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/network.c (ffffffff8149d396)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
```
In security/tomoyo/securityfs_if.c (ffffffff8149e13e)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8149e2af)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (ffffffff814f7a2a)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - block/blk-ioc.c:exit_io_context
```
```
In block/blk-mq.c (ffffffff814fe5c5)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-tag.c (ffffffff81501c26)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-iocost.c (ffffffff8151d8cc)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (ffffffff8156a2c3)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_finish_wait
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/pci/pci.c (ffffffff81592bd2)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff815aec58)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
```
In drivers/pci/ats.c (ffffffff815baba8)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815cb29b)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
```
In drivers/acpi/apei/ghes.c (ffffffff81651ca4)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_free
```
```
In drivers/dma/dmaengine.c (ffffffff816655d3)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/reset/core.c (ffffffff8168fa6f)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff8169b53a)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
```
In drivers/tty/vt/keyboard.c (ffffffff82902235)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff816c69bc)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_close
```
```
In drivers/tty/serial/kgdboc.c (ffffffff816c7155)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_post_exp_handler
```
```
In drivers/char/agp/backend.c (ffffffff816d39be)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_release
```
```
In drivers/char/agp/generic.c (ffffffff816d6a34)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816d9fbf)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
```
```
In drivers/connector/cn_queue.c (ffffffff8170268a)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffff81702f8b)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In drivers/base/dd.c (ffffffff8170ddae)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/power/runtime.c (ffffffff8171c094)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In drivers/mfd/mfd-core.c (ffffffff817526d5)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff817660c3)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:deactivate_labels
```
```
In drivers/scsi/scsi_lib.c (ffffffff81780733)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
```
```
In drivers/vfio/vfio.c (ffffffff817dffc5)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_release
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_add_container_user
  - drivers/vfio/vfio.c:vfio_group_add_container_user
```
```
In drivers/usb/core/hcd.c (ffffffff817fc222)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/urb.c (ffffffff817ff37f)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
```
```
In drivers/media/cec/cec-pin.c (ffffffff8188c2b4)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/media/cec/cec-pin.c:cec_pin_thread_func
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81890935)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (ffffffff818a928b)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm.c (ffffffff818b86ee)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stats.c (ffffffff818c74cf)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff818ccf8c)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff818f2a0a)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819076e5)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/ras/debugfs.c (ffffffff81913ee5)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_release
```
```
In net/core/skbuff.c (ffffffff8192da4e)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_put_abort
```
```
In net/core/dev.c (ffffffff8193f902)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In net/core/neighbour.c (ffffffff819574dc)
Location: include/asm-generic/atomic-instrumented.h:327
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
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff8197687d)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In net/core/sock_map.c (ffffffff8198cf6d)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_free_elem
```
```
In net/sched/cls_api.c (ffffffff819a6b60)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_cls_offload_cnt_reset
  - net/sched/cls_api.c:tc_cls_offload_cnt_update
```
```
In net/sched/act_api.c (ffffffff819ad73d)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff819b4215)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819ce3d3)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819d040e)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1b2b0)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a27bcd)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a3600b)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3cbd8)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
```
```
In net/ipv6/route.c (ffffffff81a605d2)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a7649e)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81a7a9ef)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a857fa)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81a8ad3f)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a8c9c0)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
```
In net/ipv6/ip6mr.c (ffffffff81a91a11)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9cff0)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
```
```
In net/packet/af_packet.c (ffffffff81aa0d20)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mm_close
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81ab0b24)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ab180a)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81ab2500)
Location: include/asm-generic/atomic-instrumented.h:327
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
</details>
</li>
</ul>

## Differences

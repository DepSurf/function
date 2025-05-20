# Function: <code>raw_atomic_dec</code>

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
In arch/x86/events/core.c (ffffffff81008485)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
```
```
In arch/x86/events/intel/core.c (ffffffff81012a57)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_put_event_constraints
  - arch/x86/events/intel/core.c:intel_put_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/events/intel/uncore.c (ffffffff81024dd4)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_put_constraint
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81026d24)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
```
```
In arch/x86/xen/spinlock.c (ffffffff8104487f)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - arch/x86/xen/spinlock.c:xen_qlock_wait
```
```
In arch/x86/kernel/alternative.c (ffffffff8213e287)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8107c173)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_hcpu_update
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108fea0)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81099f7c)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff8109af47)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810d720f)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810e8215)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
```
```
In kernel/cpu.c (ffffffff810fafc7)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
```
```
In kernel/async.c (ffffffff81135f41)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/core.c (ffffffff81150ff8)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:ttwu_do_activate
```
```
In kernel/sched/fair.c (ffffffff81166824)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/build_policy.c (ffffffff811714d8)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:rq_offline_dl
  - kernel/sched/build_policy.c:rq_offline_rt
```
```
In kernel/sched/build_utility.c (ffffffff811883e6)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:cpupri_set
```
```
In kernel/printk/printk.c (ffffffff8119ffa5)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
```
```
In kernel/irq/spurious.c (ffffffff811abc19)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/rcu/update.c (ffffffff811bdf25)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_end_inkernel_boot
```
```
In kernel/rcu/srcutree.c (ffffffff811be830)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier_one_cpu
```
```
In kernel/time/clocksource.c (ffffffff811f4cda)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/futex/core.c (ffffffff81208996)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_q_unlock
  - kernel/futex/core.c:__futex_unqueue
```
```
In kernel/futex/requeue.c (ffffffff8120bd95)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
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
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/debug/debug_core.c (ffffffff81250617)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/watchdog_perf.c (ffffffff8125f64e)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - kernel/watchdog_perf.c:watchdog_hardlockup_disable
```
```
In kernel/trace/ftrace.c (ffffffff8126b396)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffffffff812778fa)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
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
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_set_cpumask
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (ffffffff812917d1)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff812929ee)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
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
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/fgraph.c (ffffffff812a1b2e)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:ftrace_suspend_notifier_call
```
```
In kernel/trace/trace_kdb.c (ffffffff812d5ea3)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/trace/trace_dynevent.c (ffffffff812d620d)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - kernel/trace/trace_dynevent.c:trace_event_dyn_put_ref
```
```
In kernel/bpf/hashtab.c (ffffffff81326957)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
```
```
In kernel/bpf/devmap.c (ffffffff8134d9d2)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_delete_elem
```
```
In kernel/bpf/offload.c (ffffffff813518fc)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
```
```
In kernel/events/core.c (ffffffff81374c9b)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
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
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/hw_breakpoint.c (ffffffff8137e68c)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff8137feee)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/watch_queue.c (ffffffff813892ba)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:free_watch
```
```
In mm/page-writeback.c (ffffffff8139d352)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_end_writeback
```
```
In mm/vmscan.c (ffffffff813b5d17)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_throttle
```
```
In mm/mmap.c (ffffffff81400166)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
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
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/rmap.c (ffffffff8140ca58)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_rmap
```
```
In mm/page_alloc.c (ffffffff814230e9)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_contig_migrate_range
```
```
In mm/memory_hotplug.c (ffffffff82147735)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/swapfile.c (ffffffff8142fc54)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/frontswap.c (ffffffff81434b9c)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff81435e05)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_free_entry
```
```
In mm/mempolicy.c (ffffffff8144d33b)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_migrate_pages
```
```
In mm/migrate.c (ffffffff8146b869)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
```
In mm/memcontrol.c (ffffffff81488c7d)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
```
```
In mm/zpool.c (ffffffff8149b7b2)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - mm/zpool.c:zpool_destroy_pool
  - mm/zpool.c:zpool_create_pool
  - mm/zpool.c:zpool_has_pool
```
```
In mm/secretmem.c (ffffffff8149fb75)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_release
```
```
In mm/mapping_dirty_helpers.c (ffffffff814a63fd)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/open.c (ffffffff814a879b)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff814b1224)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff814c1f3d)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - fs/namei.c:do_open
```
```
In fs/fs-writeback.c (ffffffff814f881b)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - fs/fs-writeback.c:cleanup_offline_cgwb
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/buffer.c (ffffffff81509922)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
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
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/coredump.c (ffffffff815509b8)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffffffff8155b269)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - fs/quota/dquot.c:quota_release_workfn
  - fs/quota/dquot.c:quota_release_workfn
```
```
In fs/proc/task_mmu.c (ffffffff81564f2a)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/kernfs/inode.c (ffffffff81580d6b)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/devpts/inode.c (ffffffff8158e3fe)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_kill_index
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/balloc.c (ffffffff8158f2e4)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_should_retry_alloc
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff81595dcc)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff815a82b9)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
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
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff815b803e)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff815c724c)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff815ce6d4)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
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
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff815f955a)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff8161751b)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81618ece)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff81622ad0)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_fc_release_bufs
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
```
```
In fs/ecryptfs/miscdev.c (ffffffff8164df8a)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release
```
```
In fs/fuse/inode.c (ffffffff81662f35)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_sync_fs_writes
```
```
In ipc/util.c (ffffffff81674e28)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
```
```
In security/keys/gc.c (ffffffff81685e2d)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
```
```
In security/keys/keyctl.c (ffffffff8168c4c2)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/selinux/avc.c (ffffffff816a507f)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_compute_av
  - security/selinux/avc.c:avc_ss_reset
  - security/selinux/avc.c:avc_node_replace
```
```
In security/selinux/hooks.c (ffffffff816a6505)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_dec
```
```
In security/selinux/xfrm.c (ffffffff816d04d1)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_state_free
  - security/selinux/xfrm.c:selinux_xfrm_policy_free
```
```
In security/tomoyo/common.c (ffffffff816e12ec)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff816e7ff8)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff816ea03d)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
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
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff816ece57)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
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
Location: include/linux/atomic/atomic-arch-fallback.h:1198
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
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff816ee7da)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/network.c (ffffffff816efbbe)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
```
In security/tomoyo/securityfs_if.c (ffffffff816f0c68)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff816f0e7f)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
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
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/blk-mq.c:blk_mq_dispatch_wake
```
```
In block/blk-iocost.c (ffffffff817aa419)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In io_uring/io_uring.c (ffffffff817d350c)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_eventfd_signal
  - io_uring/io_uring.c:io_clean_op
```
```
In io_uring/io-wq.c (ffffffff817e7868)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
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
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_finish_wait
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/pci/pci.c (ffffffff81926a17)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81950312)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff819898a2)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a2f9c8)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_rcu_free
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
```
```
In drivers/xen/events/events_base.c (ffffffff81a68488)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
```
```
In drivers/reset/core.c (ffffffff81a902ca)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_reset
```
```
In drivers/tty/tty_buffer.c (ffffffff81a9f5e4)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
```
In drivers/tty/vt/keyboard.c (ffffffff83712a0a)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81ada509)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_close
```
```
In drivers/char/agp/backend.c (ffffffff81ae82ce)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_release
```
```
In drivers/char/agp/generic.c (ffffffff81aea414)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81aee56a)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
```
```
In drivers/connector/cn_queue.c (ffffffff81b2abae)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffff81b2b719)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
```
```
In drivers/base/dd.c (ffffffff81b39094)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/runtime.c (ffffffff81b4fb65)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:update_autosuspend
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81bacd43)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:deactivate_labels
```
```
In drivers/cxl/core/suspend.c (ffffffff81bc7115)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - drivers/cxl/core/suspend.c:cxl_mem_active_dec
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd0dc3)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
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
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff81c852c4)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/urb.c (ffffffff81c88c8f)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81d3df82)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (ffffffff81d5ed93)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - drivers/md/md.c:md_release
```
```
In drivers/md/dm.c (ffffffff81d78e2d)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stats.c (ffffffff81d85faf)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stat_for_entry
```
```
In drivers/md/dm-io-rewind.c (ffffffff81d8903a)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - drivers/md/dm-io-rewind.c:dm_io_rewind
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81d8e528)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81dc4a29)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de649d)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/ras/debugfs.c (ffffffff81df8725)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_release
```
```
In drivers/hte/hte.c (ffffffff81dfee95)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - drivers/hte/hte.c:hte_ts_put
```
```
In net/core/skbuff.c (ffffffff81e18f89)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
```
```
In net/core/dev.c (ffffffff81e2f0ea)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
```
```
In net/core/neighbour.c (ffffffff81e4be56)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
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
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
```
```
In net/core/sock_map.c (ffffffff81ea5c05)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
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
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_cb_destroy
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_cls_offload_cnt_update
```
```
In net/sched/act_api.c (ffffffff81ebdb1e)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - net/sched/act_api.c:__tcf_action_put
  - net/sched/act_api.c:__tcf_action_put
```
```
In net/netlink/af_netlink.c (ffffffff81ec7533)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f079a3)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
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
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/fib_semantics.c (ffffffff81f60423)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6a79a)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
```
```
In net/ipv4/fib_rules.c (ffffffff81f7af19)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_delete
```
```
In net/ipv4/ipmr.c (ffffffff81f81189)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f926e6)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff81f9a9a8)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
```
```
In net/ipv6/udp.c (ffffffff81fe9e78)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81feea30)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffc767)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff820031b0)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff82005775)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
```
In net/ipv6/ioam6.c (ffffffff82009b9a)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff8200ff5e)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:mif6_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff8201fa68)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
```
```
In net/packet/af_packet.c (ffffffff82025500)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mm_close
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff8205347a)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff82053d3c)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
```
```
In net/netlabel/netlabel_calipso.c (ffffffff8205500a)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
```
In net/xdp/xskmap.c (ffffffff8206d174)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
Inline: True
Inline callers:
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_sock_delete
```
```
In net/handshake/request.c (ffffffff82092d9c)
Location: include/linux/atomic/atomic-arch-fallback.h:1198
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
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:x86_del_exclusive
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
```
```
In arch/x86/events/intel/core.c (ffffffff81018377)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_put_event_constraints
  - arch/x86/events/intel/core.c:intel_put_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/events/intel/uncore.c (ffffffff8102af34)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_put_constraint
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8102ce84)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
```
```
In arch/x86/xen/spinlock.c (ffffffff8104adaf)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - arch/x86/xen/spinlock.c:xen_qlock_wait
```
```
In arch/x86/kernel/alternative.c (ffffffff82220277)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81097230)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff810a17ac)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff810a2625)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810dfa6f)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810f03a5)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
```
```
In kernel/cpu.c (ffffffff81104467)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
```
```
In kernel/async.c (ffffffff811410f1)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/core.c (ffffffff8115cd8a)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:ttwu_do_activate
```
```
In kernel/sched/fair.c (ffffffff81173564)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/build_policy.c (ffffffff8117ede8)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:rq_offline_dl
  - kernel/sched/build_policy.c:rq_offline_rt
  - kernel/sched/build_policy.c:pick_next_task_rt
  - kernel/sched/build_policy.c:dequeue_task_rt
```
```
In kernel/sched/build_utility.c (ffffffff81196cc6)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:cpupri_set
```
```
In kernel/printk/printk.c (ffffffff811af005)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
```
```
In kernel/irq/spurious.c (ffffffff811bb819)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/rcu/update.c (ffffffff811ce445)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_end_inkernel_boot
  - kernel/rcu/update.c:rcu_end_inkernel_boot
```
```
In kernel/rcu/srcutree.c (ffffffff811ced50)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier_one_cpu
```
```
In kernel/rcu/tree.c (ffffffff811d2110)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_nocb_bypass_lock
  - kernel/rcu/tree.c:param_set_do_rcu_barrier
```
```
In kernel/time/clocksource.c (ffffffff8120ae31)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/futex/core.c (ffffffff8121f826)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_q_unlock
  - kernel/futex/core.c:__futex_unqueue
```
```
In kernel/futex/requeue.c (ffffffff8122332a)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
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
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/debug/debug_core.c (ffffffff8126a467)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/watchdog_perf.c (ffffffff8127965e)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - kernel/watchdog_perf.c:watchdog_hardlockup_disable
```
```
In kernel/trace/ftrace.c (ffffffff81285846)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffffffff812905c9)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
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
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_set_cpumask
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (ffffffff812acde1)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff812ae0d7)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
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
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/fgraph.c (ffffffff812bd25e)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:ftrace_suspend_notifier_call
```
```
In kernel/trace/trace_kdb.c (ffffffff812f39b3)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/trace/trace_dynevent.c (ffffffff812f3d1d)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - kernel/trace/trace_dynevent.c:trace_event_dyn_put_ref
```
```
In kernel/bpf/hashtab.c (ffffffff8134afa2)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
```
```
In kernel/bpf/devmap.c (ffffffff81374ef2)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_delete_elem
```
```
In kernel/bpf/offload.c (ffffffff81378ddc)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
```
```
In kernel/events/core.c (ffffffff8139dfcb)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
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
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/hw_breakpoint.c (ffffffff813a78ec)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff813a916e)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_free_insn_slot
```
```
In kernel/watch_queue.c (ffffffff813b2d0c)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:free_watch
```
```
In mm/page-writeback.c (ffffffff813c70ee)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_end_writeback
```
```
In mm/vmscan.c (ffffffff813debd7)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_throttle
```
```
In mm/mmap.c (ffffffff8142c786)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
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
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/rmap.c (ffffffff8143a464)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (ffffffff81450019)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_contig_migrate_range
```
```
In mm/memory_hotplug.c (ffffffff82229f6d)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/swapfile.c (ffffffff8146973f)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/zswap.c (ffffffff8146f8d6)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_free_entry
```
```
In mm/hugetlb.c (ffffffff8147daff)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/mempolicy.c (ffffffff81486e10)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_migrate_pages
```
```
In mm/migrate.c (ffffffff8149a844)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
```
In mm/memcontrol.c (ffffffff814b82fd)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
```
```
In mm/zpool.c (ffffffff814caeb2)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - mm/zpool.c:zpool_destroy_pool
  - mm/zpool.c:zpool_create_pool
  - mm/zpool.c:zpool_has_pool
```
```
In mm/secretmem.c (ffffffff814cf2c5)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_release
```
```
In mm/mapping_dirty_helpers.c (ffffffff814d734d)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/open.c (ffffffff814d9878)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff814e2a5b)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff814f43fd)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - fs/namei.c:do_open
```
```
In fs/fs-writeback.c (ffffffff8152d019)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - fs/fs-writeback.c:cleanup_offline_cgwb
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/buffer.c (ffffffff8153e752)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
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
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/coredump.c (ffffffff81586849)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffffffff8159224b)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8159b9e9)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/kernfs/inode.c (ffffffff815b97e7)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/devpts/inode.c (ffffffff815c712e)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_kill_index
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/balloc.c (ffffffff815c7ff4)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_should_retry_alloc
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff815cea7c)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff815e1076)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
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
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff815f0dde)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff81604bc2)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff81606f54)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
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
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff816320ea)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff8165033a)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81651d8d)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff8165bb2f)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_fc_release_bufs
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
```
```
In fs/ecryptfs/miscdev.c (ffffffff816874ea)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release
```
```
In fs/fuse/inode.c (ffffffff8169caa4)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_sync_fs_writes
```
```
In ipc/util.c (ffffffff816b11e8)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
```
```
In security/keys/gc.c (ffffffff816c224d)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
```
```
In security/keys/keyctl.c (ffffffff816c89c2)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/selinux/avc.c (ffffffff816e1ad3)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_compute_av
  - security/selinux/avc.c:avc_ss_reset
  - security/selinux/avc.c:avc_node_replace
```
```
In security/selinux/hooks.c (ffffffff816e2fc5)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_dec
```
```
In security/selinux/xfrm.c (ffffffff8170caf1)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_state_free
  - security/selinux/xfrm.c:selinux_xfrm_policy_free
```
```
In security/tomoyo/common.c (ffffffff8171df6c)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff81724d08)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff81726d4d)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
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
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff81729c27)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
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
Location: include/linux/atomic/atomic-arch-fallback.h:1207
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
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff8172b5aa)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/network.c (ffffffff8172c98e)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
```
In security/tomoyo/securityfs_if.c (ffffffff8172da38)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8172dc4f)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
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
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - block/bdev.c:bdev_freeze
```
```
In block/blk-mq.c (ffffffff817c5fbc)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/blk-mq.c:blk_mq_dispatch_wake
```
```
In block/blk-iocost.c (ffffffff817ee0f5)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In io_uring/io_uring.c (ffffffff8181731c)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_eventfd_signal
  - io_uring/io_uring.c:io_clean_op
```
```
In io_uring/io-wq.c (ffffffff8182d676)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
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
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_finish_wait
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/pci/pci.c (ffffffff8196f1b7)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81999742)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff819d37b2)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a7ad08)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_rcu_free
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
```
```
In drivers/xen/events/events_base.c (ffffffff81ab9a04)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
```
```
In drivers/reset/core.c (ffffffff81ae2d0a)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_reset
```
```
In drivers/tty/tty_buffer.c (ffffffff81af1fe1)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
```
In drivers/tty/vt/keyboard.c (ffffffff8394642a)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81b2d809)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_close
```
```
In drivers/char/agp/backend.c (ffffffff81b3b73e)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_release
```
```
In drivers/char/agp/generic.c (ffffffff81b3d8a4)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81b41aaa)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_i810_free_by_type
```
```
In drivers/connector/cn_queue.c (ffffffff81b81e5e)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
```
```
In drivers/connector/cn_proc.c (ffffffff81b82c75)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
```
```
In drivers/base/dd.c (ffffffff81b90b54)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/runtime.c (ffffffff81ba80e5)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:update_autosuspend
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81c01083)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:deactivate_labels
```
```
In drivers/cxl/core/suspend.c (ffffffff81c1bc85)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - drivers/cxl/core/suspend.c:cxl_mem_active_dec
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c25a33)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
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
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_file.c:drm_open
```
```
In drivers/gpu/drm/drm_vblank.c (ffffffff81cb528b)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_vblank_on
  - drivers/gpu/drm/drm_vblank.c:drm_vblank_get
  - drivers/gpu/drm/drm_vblank.c:drm_vblank_enable
```
```
In drivers/accel/drm_accel.c (ffffffff81cbcce6)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - drivers/accel/drm_accel.c:accel_open
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d17a35)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff81d39cc4)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/urb.c (ffffffff81d3d6df)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81df48d2)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (ffffffff81e15ad3)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - drivers/md/md.c:md_release
```
```
In drivers/md/dm.c (ffffffff81e2ffbe)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stats.c (ffffffff81e3d6ef)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stat_for_entry
```
```
In drivers/md/dm-io-rewind.c (ffffffff81e4077a)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - drivers/md/dm-io-rewind.c:dm_io_rewind
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81e45e3c)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81e7d309)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e9c67d)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/ras/debugfs.c (ffffffff81eaee35)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_release
```
```
In drivers/hte/hte.c (ffffffff81eb6185)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - drivers/hte/hte.c:hte_ts_put
```
```
In net/core/skbuff.c (ffffffff81ed6419)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
```
```
In net/core/dev.c (ffffffff81eedd6a)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
```
```
In net/core/neighbour.c (ffffffff81f0ab66)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
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
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
```
```
In net/core/sock_map.c (ffffffff81f686c5)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
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
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_cb_destroy
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_cls_offload_cnt_update
```
```
In net/sched/act_api.c (ffffffff81f80c0e)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - net/sched/act_api.c:__tcf_action_put
  - net/sched/act_api.c:__tcf_action_put
```
```
In net/netlink/af_netlink.c (ffffffff81f8a873)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81fbe1fa)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fcbd03)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
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
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/fib_semantics.c (ffffffff820269f3)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/inet_fragment.c (ffffffff82030e4a)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
```
```
In net/ipv4/fib_rules.c (ffffffff82041619)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_delete
```
```
In net/ipv4/ipmr.c (ffffffff82047809)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
```
```
In net/xfrm/xfrm_policy.c (ffffffff82060456)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff82067d08)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
```
```
In net/ipv6/ip6_output.c (ffffffff820842d6)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
```
```
In net/ipv6/udp.c (ffffffff820b7cfa)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/raw.c (ffffffff820bc606)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820c9a9f)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff820d1f81)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff820d4585)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
```
In net/ipv6/ioam6.c (ffffffff820d8b3a)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff820deeee)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:mif6_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff820eeb98)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff82125c7a)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff82126515)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove
```
```
In net/netlabel/netlabel_calipso.c (ffffffff821278e4)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
```
In net/xdp/xskmap.c (ffffffff82141014)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
Inline: True
Inline callers:
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_sock_delete
```
```
In net/handshake/request.c (ffffffff8216964c)
Location: include/linux/atomic/atomic-arch-fallback.h:1207
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

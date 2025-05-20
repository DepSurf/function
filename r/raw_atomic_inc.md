# Function: <code>raw_atomic_inc</code>

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
In arch/x86/entry/vdso/vma.c (ffffffff81004053)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In arch/x86/events/core.c (ffffffff81007eab)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_event_init
  - arch/x86/events/core.c:x86_add_exclusive
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/events/intel/core.c (ffffffff81010542)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:__intel_shared_reg_get_constraints
```
```
In arch/x86/events/intel/uncore.c (ffffffff81025b0a)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
  - arch/x86/events/intel/uncore.c:uncore_get_constraint
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81027377)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg
```
```
In arch/x86/xen/spinlock.c (ffffffff8104486b)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - arch/x86/xen/spinlock.c:xen_qlock_wait
```
```
In arch/x86/kernel/i8259.c (ffffffff810550cd)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
```
```
In arch/x86/kernel/tboot.c (ffffffff81069615)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_dying_cpu
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106eff6)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8213ecb3)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_end
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81089a17)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108fc2e)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_open
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810922df)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81099f70)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8109f7a7)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810a0bb1)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a6d03)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810d715b)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810e8aa7)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
```
```
In kernel/fork.c (ffffffff810f395e)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:mm_access
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:__mmput
  - kernel/fork.c:dup_mmap
```
```
In kernel/cpu.c (ffffffff810fafab)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
```
```
In kernel/exit.c (ffffffff810fd69a)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
```
```
In kernel/ptrace.c (ffffffff81107604)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/umh.c (ffffffff8111b68b)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffffffff8111c7eb)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
```
```
In kernel/kthread.c (ffffffff8112a8d6)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unuse_mm
  - kernel/kthread.c:kthread_use_mm
```
```
In kernel/nsproxy.c (ffffffff81131670)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:copy_namespaces
```
```
In kernel/cred.c (ffffffff8113411b)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:override_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_creds
```
```
In kernel/async.c (ffffffff811363d0)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - kernel/async.c:async_schedule_node_domain
```
```
In kernel/groups.c (ffffffff811388be)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - kernel/groups.c:set_groups
```
```
In kernel/sched/core.c (ffffffff836ccd10)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:sched_core_get
```
```
In kernel/sched/fair.c (ffffffff811667df)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/build_policy.c (ffffffff811699e3)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:rq_online_rt
  - kernel/sched/build_policy.c:pull_rt_task
```
```
In kernel/sched/build_utility.c (ffffffff8117f9b3)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sd_init
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:sched_get_rd
  - kernel/sched/build_utility.c:rq_attach_root
  - kernel/sched/build_utility.c:cpupri_set
```
```
In kernel/power/hibernate.c (ffffffff81194eb6)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/power/swap.c (ffffffff8119914d)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In kernel/printk/printk.c (ffffffff8119e974)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - kernel/printk/printk.c:__printk_cpu_sync_try_get
```
```
In kernel/irq/handle.c (ffffffff811a73ef)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
```
```
In kernel/irq/manage.c (ffffffff811a80bc)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread_fn
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff811bcdee)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
  - kernel/rcu/update.c:rcu_expedite_gp
```
```
In kernel/rcu/srcutree.c (ffffffff811be805)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier_one_cpu
```
```
In kernel/rcu/tree.c (ffffffff811c2194)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_barrier_entrain
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/rcu/tree.c:kvfree_call_rcu
```
```
In kernel/module/main.c (ffffffff811df6fe)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - kernel/module/main.c:load_module
```
```
In kernel/time/clocksource.c (ffffffff811f5a75)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_touch_watchdog
  - kernel/time/clocksource.c:clocksource_resume
```
```
In kernel/futex/core.c (ffffffff8120894b)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_q_lock
```
```
In kernel/futex/requeue.c (ffffffff8120b39d)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
```
```
In kernel/cgroup/cgroup.c (ffffffff812215f2)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:online_css
  - kernel/cgroup/cgroup.c:online_css
```
```
In kernel/audit.c (ffffffff8123ade5)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_lost
```
```
In kernel/debug/debug_core.c (ffffffff81250605)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/seccomp.c (ffffffff81261877)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In kernel/relay.c (ffffffff81262e44)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/trace/ring_buffer.c (ffffffff812752a9)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:ring_buffer_read_prepare
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_peek
  - kernel/trace/ring_buffer.c:rb_buffer_peek
  - kernel/trace/ring_buffer.c:rb_buffer_peek
  - kernel/trace/ring_buffer.c:rb_advance_reader
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_record_disable
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_handle_head_page
  - kernel/trace/ring_buffer.c:rb_handle_head_page
  - kernel/trace/ring_buffer.c:rb_handle_head_page
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:rb_remove_pages
  - kernel/trace/ring_buffer.c:rb_remove_pages
  - kernel/trace/ring_buffer.c:rb_remove_pages
  - kernel/trace/ring_buffer.c:rb_set_head_page
  - kernel/trace/ring_buffer.c:rb_set_head_page
  - kernel/trace/ring_buffer.c:rb_set_head_page
```
```
In kernel/trace/trace.c (ffffffff81287890)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_set_cpumask
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff8129b1cd)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
```
```
In kernel/trace/blktrace.c (ffffffff8129f4f0)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
```
```
In kernel/trace/fgraph.c (ffffffff812a1b47)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:ftrace_suspend_notifier_call
  - kernel/trace/fgraph.c:function_graph_enter
```
```
In kernel/trace/trace_events_user.c (ffffffff812c52a8)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_mm_alloc
```
```
In kernel/trace/trace_kdb.c (ffffffff812d5e45)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/trace/trace_dynevent.c (ffffffff812d61a0)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - kernel/trace/trace_dynevent.c:trace_event_dyn_try_get_ref
```
```
In kernel/bpf/hashtab.c (ffffffff81327e84)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/devmap.c (ffffffff8134d210)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_map_update_elem
```
```
In kernel/bpf/cpumap.c (ffffffff8134fab4)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In kernel/bpf/offload.c (ffffffff81351311)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
```
```
In kernel/events/core.c (ffffffff8136768c)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
  - kernel/events/core.c:account_event
  - kernel/events/core.c:account_event
  - kernel/events/core.c:account_event
  - kernel/events/core.c:account_event
  - kernel/events/core.c:account_event
  - kernel/events/core.c:account_event
  - kernel/events/core.c:account_event
  - kernel/events/core.c:account_event
  - kernel/events/core.c:account_event
  - kernel/events/core.c:account_event
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_open
  - kernel/events/core.c:perf_mmap_open
  - kernel/events/core.c:perf_mmap_open
  - kernel/events/core.c:perf_mmap_fault
  - kernel/events/core.c:exclusive_event_destroy
  - kernel/events/core.c:find_get_pmu_context
  - kernel/events/core.c:find_get_pmu_context
```
```
In kernel/events/hw_breakpoint.c (ffffffff8137e9e9)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff8138344e)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - kernel/events/uprobes.c:pre_ssout
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/watch_queue.c (ffffffff8138918e)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/filemap.c (ffffffff8138fbcb)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:splice_folio_into_pipe
  - mm/filemap.c:folio_end_writeback
  - mm/filemap.c:replace_page_cache_folio
```
```
In mm/oom_kill.c (ffffffff813968d0)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:mark_oom_victim
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/page-writeback.c (ffffffff8139ba55)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
```
```
In mm/readahead.c (ffffffff8139de9c)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
```
```
In mm/swap.c (ffffffff813a3345)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_disable
  - mm/swap.c:folio_mark_lazyfree
  - mm/swap.c:folio_deactivate
  - mm/swap.c:deactivate_file_folio
  - mm/swap.c:folio_add_lru
  - mm/swap.c:folio_rotate_reclaimable
```
```
In mm/vmscan.c (ffffffff813b7003)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - mm/vmscan.c:folio_isolate_lru
```
```
In mm/shmem.c (ffffffff813bccf8)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_unuse
```
```
In mm/gup.c (ffffffff813e3823)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - mm/gup.c:migrate_longterm_unpinnable_pages
  - mm/gup.c:folio_add_pin
  - mm/gup.c:folio_add_pin
  - mm/gup.c:try_grab_page
```
```
In mm/memory.c (ffffffff813f0f8a)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - mm/memory.c:numa_migrate_prep
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
```
```
In mm/mlock.c (ffffffff813f9479)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - mm/mlock.c:munlock_folio
  - mm/mlock.c:mlock_new_folio
  - mm/mlock.c:mlock_folio
```
```
In mm/mmap.c (ffffffff813fa1b9)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_link
```
```
In mm/mmu_gather.c (ffffffff81401e9d)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_gather_mmu_fullmm
  - mm/mmu_gather.c:tlb_gather_mmu
```
```
In mm/rmap.c (ffffffff8140adcb)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - mm/rmap.c:set_tlb_ubc_flush_pending
  - mm/rmap.c:anon_vma_fork
```
```
In mm/madvise.c (ffffffff81427b4b)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff8142c0fe)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cache_get_folio
```
```
In mm/swapfile.c (ffffffff8142f8bf)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte
```
```
In mm/frontswap.c (ffffffff814349d2)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff814371a5)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff8144175c)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff8144d86b)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/sparse-vmemmap.c (ffffffff8214f71f)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/mmu_notifier.c (ffffffff8144f50b)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_interval_notifier_insert
  - mm/mmu_notifier.c:__mmu_notifier_register
```
```
In mm/ksm.c (ffffffff814578cf)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff81467218)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - mm/migrate.c:find_mm_struct
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff8146de0e)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81479506)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff81482312)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:set_huge_pmd
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/memcontrol.c (ffffffff81488c18)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
```
```
In mm/memory-failure.c (ffffffff81499729)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:try_memory_failure_hugetlb
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:page_handle_poison
```
```
In mm/zpool.c (ffffffff8149b4cc)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - mm/zpool.c:zpool_get_driver
```
```
In mm/zsmalloc.c (ffffffff8149e320)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
```
```
In mm/secretmem.c (ffffffff814a0108)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - mm/secretmem.c:__ia32_sys_memfd_secret
  - mm/secretmem.c:__x64_sys_memfd_secret
```
```
In mm/memfd.c (ffffffff814a6319)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In mm/mapping_dirty_helpers.c (ffffffff814a651f)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pre_vma
```
```
In mm/bootmem_info.c (ffffffff836ed619)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/open.c (ffffffff814a876f)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/file_table.c (ffffffff814b1724)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - fs/file_table.c:alloc_file
  - fs/file_table.c:init_file
```
```
In fs/super.c (ffffffff814b3315)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - fs/super.c:freeze_super
```
```
In fs/exec.c (ffffffff814b89e2)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - fs/exec.c:exec_binprm
  - fs/exec.c:free_bprm
```
```
In fs/pipe.c (ffffffff814bcdfe)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/dcache.c (ffffffff814d1c6b)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - fs/dcache.c:copy_name
  - fs/dcache.c:take_dentry_name_snapshot
```
```
In fs/inode.c (ffffffff814d9592)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:igrab
  - fs/inode.c:find_inode_fast
  - fs/inode.c:find_inode
  - fs/inode.c:inode_lru_isolate
```
```
In fs/namespace.c (ffffffff814e7081)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
```
```
In fs/fs-writeback.c (ffffffff814f875b)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - fs/fs-writeback.c:cleanup_offline_cgwb
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:wb_queue_work
```
```
In fs/fs_context.c (ffffffff81504319)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/kernel_read_file.c (ffffffff81506434)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file
```
```
In fs/buffer.c (ffffffff8150a676)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:__bh_read
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:folio_create_empty_buffers
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:lookup_bh_lru
  - fs/buffer.c:bh_lru_install
  - fs/buffer.c:__getblk_slow
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/direct-io.c (ffffffff81511b6b)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In fs/notify/mark.c (ffffffff81514dbf)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/userfaultfd.c (ffffffff81523add)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - fs/userfaultfd.c:new_userfaultfd
  - fs/userfaultfd.c:userfaultfd_unmap_prep
  - fs/userfaultfd.c:userfaultfd_remove
  - fs/userfaultfd.c:mremap_userfaultfd_prep
  - fs/userfaultfd.c:dup_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/aio.c (ffffffff81529692)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - fs/aio.c:aio_migrate_folio
```
```
In fs/verity/enable.c (ffffffff8153c036)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/binfmt_elf.c (ffffffff81548101)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff8154b2b0)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In fs/iomap/buffered-io.c (ffffffff81555242)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In fs/iomap/direct-io.c (ffffffff815588ca)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_submit_bio
```
```
In fs/quota/dquot.c (ffffffff8155c3fd)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:invalidate_dquots
```
```
In fs/proc/task_mmu.c (ffffffff81564e8c)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:hold_task_mempolicy
```
```
In fs/proc/base.c (ffffffff8156ecd1)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - fs/proc/base.c:proc_mem_open
```
```
In fs/proc/proc_sysctl.c (ffffffff8157baaa)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_poll_notify
```
```
In fs/kernfs/dir.c (ffffffff81582a17)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_destroy_root
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_find_and_get_ns
  - fs/kernfs/dir.c:kernfs_get_parent
```
```
In fs/kernfs/file.c (ffffffff81584bee)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify
```
```
In fs/configfs/dir.c (ffffffff8158a9a6)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_make_dirent
  - fs/configfs/dir.c:configfs_new_dirent
```
```
In fs/configfs/symlink.c (ffffffff8158cb94)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - fs/configfs/symlink.c:create_link
```
```
In fs/devpts/inode.c (ffffffff8158e2bd)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_acquire
```
```
In fs/ext4/balloc.c (ffffffff8158f2d1)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_should_retry_alloc
```
```
In fs/ext4/ialloc.c (ffffffff815a8319)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/inline.c (ffffffff815abf7f)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff815b8025)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:mpage_map_one_extent
```
```
In fs/ext4/mballoc.c (ffffffff815c21a1)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/mmp.c (ffffffff815ced66)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block_thawed
```
```
In fs/ext4/super.c (ffffffff815fa2c2)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:__ext4_warning_inode
  - fs/ext4/super.c:__ext4_warning
  - fs/ext4/super.c:__ext4_msg
  - fs/ext4/super.c:ext4_read_bh
  - fs/ext4/super.c:ext4_read_bh_nowait
```
```
In fs/ext4/xattr.c (ffffffff8160949a)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/ext4/fast_commit.c (ffffffff8160eb75)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_commit
  - fs/ext4/fast_commit.c:ext4_fc_start_update
```
```
In fs/ext4/orphan.c (ffffffff81610373)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_file_add
  - fs/ext4/orphan.c:ext4_orphan_file_add
```
```
In fs/jbd2/transaction.c (ffffffff81614fd0)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/commit.c (ffffffff81618046)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff8161a450)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff81623cb6)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/fat/dir.c (ffffffff816348ec)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
```
```
In fs/fat/fatent.c (ffffffff81635516)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_collect_bhs
```
```
In fs/ecryptfs/miscdev.c (ffffffff8164e081)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_open
```
```
In fs/fuse/dev.c (ffffffff816518f6)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_ioctl
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
```
In fs/fuse/inode.c (ffffffff81662f23)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_sync_fs_writes
```
```
In ipc/util.c (ffffffff81674ac7)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
```
```
In security/keys/key.c (ffffffff816872b2)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - security/keys/key.c:key_alloc
```
```
In security/keys/keyctl.c (ffffffff8168c4c6)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/keys/process_keys.c (ffffffff8168ef56)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff8168f929)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff816908d6)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/selinux/hooks.c (ffffffff816a64d5)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_inc
```
```
In security/selinux/selinuxfs.c (ffffffff816b4e5d)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In security/selinux/ss/services.c (ffffffff816c59e3)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_notify_policy_change
```
```
In security/selinux/xfrm.c (ffffffff816d0440)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire
  - security/selinux/xfrm.c:selinux_xfrm_policy_clone
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
```
```
In security/tomoyo/common.c (ffffffff816e6d0c)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_open_control
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_add_entry
```
```
In security/tomoyo/condition.c (ffffffff816e7113)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_commit_condition
```
```
In security/tomoyo/domain.c (ffffffff816ea963)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
```
```
In security/tomoyo/memory.c (ffffffff816ee525)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/securityfs_if.c (ffffffff816f0c64)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff836f813c)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_init
  - security/tomoyo/tomoyo.c:tomoyo_task_alloc
```
```
In security/apparmor/audit.c (ffffffff816fa734)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_dup_audit_data
```
```
In security/apparmor/domain.c (ffffffff817040e0)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/policy_unpack.c (ffffffff8170a17e)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
```
```
In security/safesetid/lsm.c (ffffffff81726eec)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - security/safesetid/lsm.c:safesetid_task_fix_setgroups
```
```
In crypto/jitterentropy-testing.c (ffffffff8175e25b)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - crypto/jitterentropy-testing.c:jent_raw_hires_entropy_store
```
```
In block/bdev.c (ffffffff81765ff3)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - block/bdev.c:blkdev_get_whole
```
```
In block/fops.c (ffffffff817681bd)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
```
```
In block/bio.c (ffffffff8176b0bf)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - block/bio.c:blk_next_bio
```
```
In block/blk-core.c (ffffffff8176e1f5)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - block/blk-core.c:blk_set_pm_only
```
```
In block/blk-ioc.c (ffffffff81777377)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - block/blk-ioc.c:__copy_io
```
```
In block/blk-mq.c (ffffffff81783bd2)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/blk-mq.c:__blk_mq_get_driver_tag
  - block/blk-mq.c:__blk_mq_get_driver_tag
```
```
In block/blk-iocost.c (ffffffff817af934)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:weight_updated
```
```
In block/mq-deadline.c (ffffffff817b288c)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_finish_request
```
```
In io_uring/io_uring.c (ffffffff817cd5d2)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:io_uring_create
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_init_req
  - io_uring/io_uring.c:io_file_get_normal
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_eventfd_signal
  - io_uring/io_uring.c:io_prep_async_work
```
```
In io_uring/sqpoll.c (ffffffff817dbe5f)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_offload_create
  - io_uring/sqpoll.c:io_sq_thread_park
```
```
In io_uring/io-wq.c (ffffffff817e7d2b)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_enqueue
  - io_uring/io-wq.c:io_wq_enqueue
  - io_uring/io-wq.c:io_wq_worker_running
  - io_uring/io-wq.c:io_wq_dec_running
  - io_uring/io-wq.c:io_wq_dec_running
  - io_uring/io-wq.c:io_queue_worker_create
```
```
In lib/iov_iter.c (ffffffff81813693)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
  - lib/iov_iter.c:iter_xarray_populate_pages
```
```
In lib/rhashtable.c (ffffffff8181985b)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
```
```
In lib/sbitmap.c (ffffffff818e536e)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_prepare_to_wait
```
```
In drivers/pci/pci.c (ffffffff8192595c)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pcie/portdrv.c (ffffffff8193b0f1)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_shutdown
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_remove
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81950235)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff819537f3)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff81982237)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff8198987b)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a2face)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cached
```
```
In drivers/clk/clk.c (ffffffff81a3ea49)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a5fb76)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/xen/grant-table.c (ffffffff81a637f3)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/xen/events/events_base.c (ffffffff81a6adf5)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
```
```
In drivers/tty/tty_buffer.c (ffffffff81a9f57f)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
  - drivers/tty/tty_buffer.c:tty_buffer_lock_exclusive
```
```
In drivers/tty/vt/keyboard.c (ffffffff81aaade5)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81ada7d9)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff81ae1c4b)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/backend.c (ffffffff81ae8284)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_acquire
```
```
In drivers/char/agp/generic.c (ffffffff81aeac38)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81aeea4b)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_alloc_by_type
```
```
In drivers/iommu/iommu.c (ffffffff81b21055)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_sva_domain_alloc
```
```
In drivers/connector/cn_queue.c (ffffffff81b2ab13)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_alloc_callback_entry
```
```
In drivers/connector/cn_proc.c (ffffffff81b2b7e6)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
```
```
In drivers/base/core.c (ffffffff81b35924)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/dd.c (ffffffff81b39072)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/devtmpfs.c (ffffffff81b496ce)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:public_dev_mount
```
```
In drivers/base/power/runtime.c (ffffffff81b4fb9d)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:update_autosuspend
  - drivers/base/power/runtime.c:pm_runtime_forbid
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
  - drivers/base/power/runtime.c:__pm_runtime_resume
  - drivers/base/power/runtime.c:rpm_drop_usage_count
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/base/power/main.c (ffffffff81b51a65)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_prepare
```
```
In drivers/base/power/wakeup.c (ffffffff81b57470)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_irq_wakeup
  - drivers/base/power/wakeup.c:wakeup_source_report_event
```
```
In drivers/base/power/domain.c (ffffffff81b5a477)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_add_subdomain
  - drivers/base/power/domain.c:genpd_power_on
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
```
```
In drivers/nvdimm/bus.c (ffffffff81ba5186)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_ioctl
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81badb18)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:init_active_labels
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81bc66a8)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/cxl/core/suspend.c (ffffffff81bc70e5)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/cxl/core/suspend.c:cxl_mem_active_inc
```
```
In drivers/scsi/hosts.c (ffffffff81bcab2b)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_error.c (ffffffff81bcf78b)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_timeout
  - drivers/scsi/scsi_error.c:scsi_timeout
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd0d85)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_disable_disk_events
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_complete
  - drivers/scsi/scsi_lib.c:scsi_complete
```
```
In drivers/scsi/sg.c (ffffffff81bf120d)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (ffffffff81c46ea9)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_build_skb
```
```
In drivers/net/virtio_net.c (ffffffff81c52626)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:try_fill_recv
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c622b8)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
```
```
In drivers/net/xen-netfront.c (ffffffff81c6a95c)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:handle_incoming_queue
```
```
In drivers/usb/core/hub.c (ffffffff81c824ef)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/hcd.c (ffffffff81c87343)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_start_port_resume
```
```
In drivers/usb/core/urb.c (ffffffff81c884be)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_anchor_suspend_wakeups
  - drivers/usb/core/urb.c:usb_block_urb
  - drivers/usb/core/urb.c:usb_anchor_urb
```
```
In drivers/usb/core/driver.c (ffffffff81c8df83)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
```
```
In drivers/usb/core/devio.c (ffffffff81c9889c)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/core/port.c (ffffffff81c9f013)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81c9f9e6)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
```
```
In drivers/usb/host/xhci.c (ffffffff81ce4cfa)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81d37111)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81d37b08)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81d3f067)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/power_supply_core.c:power_supply_get_by_name
```
```
In drivers/md/md.c (ffffffff83af5816)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_seq_next
  - drivers/md/md.c:md_seq_start
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_open
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_attr_store
  - drivers/md/md.c:md_attr_show
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:md_super_write
  - drivers/md/md.c:md_super_write
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
```
```
In drivers/md/md-bitmap.c (ffffffff81d6e375)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:write_page
```
```
In drivers/md/dm.c (ffffffff81d79fb6)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_get
  - drivers/md/dm.c:event_callback
  - drivers/md/dm.c:event_callback
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_blk_open
```
```
In drivers/md/dm-stripe.c (ffffffff81d7ee3e)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-io.c (ffffffff81d835fe)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/md/dm-io.c:do_region
  - drivers/md/dm-io.c:do_region
```
```
In drivers/md/dm-kcopyd.c (ffffffff81d83f3c)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
  - drivers/md/dm-kcopyd.c:dispatch_job
```
```
In drivers/md/dm-stats.c (ffffffff81d85f5a)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stat_for_entry
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81d8e755)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_handle_npe
  - drivers/edac/edac_pci_sysfs.c:edac_pci_handle_pe
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
```
```
In drivers/mmc/core/sdio.c (ffffffff81dc3951)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81dc489a)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de5c0d)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_detach
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
```
```
In drivers/ras/debugfs.c (ffffffff81df8755)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_open
```
```
In drivers/hte/hte.c (ffffffff81dfed1c)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - drivers/hte/hte.c:hte_push_ts_ns
  - drivers/hte/hte.c:__hte_req_ts
```
```
In net/core/sock.c (ffffffff81e0f277)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81e1bfbc)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__skb_zcopy_downgrade_managed
  - net/core/skbuff.c:__skb_clone
```
```
In net/core/datagram.c (ffffffff81e208ce)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
```
```
In net/core/dev.c (ffffffff81e41b8e)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_many_notify
```
```
In net/core/neighbour.c (ffffffff81e4c3e8)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_probe
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/filter.c (ffffffff81e70bed)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81ea16ef)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/sched/sch_generic.c (ffffffff81eac29d)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - net/sched/sch_generic.c:netif_carrier_on
```
```
In net/sched/cls_api.c (ffffffff81eb4f30)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_cls_offload_cnt_update
```
```
In net/sched/act_api.c (ffffffff81ebd787)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_check_alloc
```
```
In net/netlink/af_netlink.c (ffffffff81ec5473)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_broadcast
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_overrun
```
```
In net/ipv4/route.c (ffffffff81eeaf51)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_dst_clone
```
```
In net/ipv4/ip_output.c (ffffffff81efa183)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f05455)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp.c (ffffffff81f0d032)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_input.c (ffffffff81f18ced)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff81f254aa)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_clone_payload
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f30b0b)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81f38a34)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/raw.c (ffffffff81f3d7b9)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81f4395d)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_read_skb
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5eba7)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
```
In net/ipv4/fib_semantics.c (ffffffff81f5fa2a)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_common_init
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6a3d1)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
```
```
In net/ipv4/ping.c (ffffffff81f6affb)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/fib_rules.c (ffffffff81f7ad62)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (ffffffff81f7f8d1)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f869a4)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f946a4)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
```
```
In net/unix/af_unix.c (ffffffff81faebca)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
```
In net/ipv6/ip6_output.c (ffffffff81fb687a)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81fbf926)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
```
```
In net/ipv6/route.c (ffffffff81fd6a7a)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_rt_copy_init
```
```
In net/ipv6/udp.c (ffffffff81feb246)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81fef39d)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffdff9)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_conn_request
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff82005bee)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
```
```
In net/ipv6/ioam6.c (ffffffff8200a42d)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff82010261)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:mif6_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff8201fe40)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
```
```
In net/packet/af_packet.c (ffffffff82026d91)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:packet_mm_open
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff82052a9f)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff82054b5e)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff820551dd)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
```
```
In net/xdp/xsk.c (ffffffff8206ade3)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
```
In net/xdp/xskmap.c (ffffffff8206d0e5)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - net/xdp/xskmap.c:xsk_map_update_elem
```
```
In net/mptcp/protocol.c (ffffffff82077c71)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
```
```
In net/mptcp/subflow.c (ffffffff8207976f)
Location: include/linux/atomic/atomic-arch-fallback.h:980
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_v6_conn_request
  - net/mptcp/subflow.c:subflow_v4_conn_request
```
```
In net/handshake/request.c (ffffffff8209314e)
Location: include/linux/atomic/atomic-arch-fallback.h:980
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
In arch/x86/entry/vdso/vma.c (ffffffff8100695f)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In arch/x86/events/core.c (ffffffff8100d5cb)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_event_init
  - arch/x86/events/core.c:x86_add_exclusive
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/events/intel/core.c (ffffffff81015c82)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:__intel_shared_reg_get_constraints
```
```
In arch/x86/events/intel/uncore.c (ffffffff8102bc6a)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
  - arch/x86/events/intel/uncore.c:uncore_get_constraint
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8102d4d7)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg
```
```
In arch/x86/xen/spinlock.c (ffffffff8104ad9b)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - arch/x86/xen/spinlock.c:xen_qlock_wait
```
```
In arch/x86/kernel/i8259.c (ffffffff8105c30d)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
```
```
In arch/x86/kernel/tboot.c (ffffffff81070a85)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_dying_cpu
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81076365)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff82220cd3)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_end
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81090b27)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81096fbe)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_open
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810996ff)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff810a17a0)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810a6c37)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810a7db7)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810add47)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810df9bb)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810f07e7)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
```
```
In kernel/fork.c (ffffffff810fcd2f)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:mm_access
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:__mmput
  - kernel/fork.c:dup_mmap
```
```
In kernel/cpu.c (ffffffff8110444b)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
```
```
In kernel/exit.c (ffffffff8110650a)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
```
```
In kernel/umh.c (ffffffff8112517b)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffffffff8112617b)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
```
```
In kernel/kthread.c (ffffffff81134f66)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unuse_mm
  - kernel/kthread.c:kthread_use_mm
```
```
In kernel/async.c (ffffffff8114101a)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - kernel/async.c:__async_schedule_node_domain
```
```
In kernel/sched/core.c (ffffffff838fe0f1)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:sched_core_get
```
```
In kernel/sched/fair.c (ffffffff8117351f)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/build_policy.c (ffffffff811757e8)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_pushable_dl_task
  - kernel/sched/build_policy.c:rq_online_rt
  - kernel/sched/build_policy.c:pull_rt_task
```
```
In kernel/sched/build_utility.c (ffffffff8118d3b3)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sd_init
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:sched_get_rd
  - kernel/sched/build_utility.c:rq_attach_root
  - kernel/sched/build_utility.c:cpupri_set
```
```
In kernel/power/hibernate.c (ffffffff811a3897)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/power/swap.c (ffffffff811a81b2)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In kernel/printk/printk.c (ffffffff811adb34)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - kernel/printk/printk.c:__printk_cpu_sync_try_get
```
```
In kernel/irq/handle.c (ffffffff811b6f4f)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
```
```
In kernel/irq/manage.c (ffffffff811b7c1c)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread_fn
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/irq/chip.c (ffffffff811bc686)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_nested_irq
```
```
In kernel/rcu/update.c (ffffffff811cd20e)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
  - kernel/rcu/update.c:rcu_expedite_gp
  - kernel/rcu/update.c:rcu_async_hurry
```
```
In kernel/rcu/srcutree.c (ffffffff811ced25)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier_one_cpu
```
```
In kernel/rcu/tree.c (ffffffff811d20f2)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_nocb_bypass_lock
  - kernel/rcu/tree.c:param_set_do_rcu_barrier
  - kernel/rcu/tree.c:rcu_barrier_entrain
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/rcu/tree.c:kvfree_call_rcu
```
```
In kernel/module/main.c (ffffffff811f542e)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - kernel/module/main.c:load_module
```
```
In kernel/time/clocksource.c (ffffffff8120bc15)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_touch_watchdog
  - kernel/time/clocksource.c:clocksource_resume
```
```
In kernel/futex/core.c (ffffffff8121f7db)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_q_lock
```
```
In kernel/futex/requeue.c (ffffffff81222941)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
```
```
In kernel/cgroup/cgroup.c (ffffffff812392e8)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:online_css
  - kernel/cgroup/cgroup.c:online_css
```
```
In kernel/audit.c (ffffffff81254ca5)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_lost
```
```
In kernel/auditsc.c (ffffffff8125f076)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
  - kernel/auditsc.c:__audit_getname
  - kernel/auditsc.c:__audit_reusename
```
```
In kernel/debug/debug_core.c (ffffffff8126a455)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/seccomp.c (ffffffff8127a0f6)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_recv
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In kernel/relay.c (ffffffff8127d064)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/trace/ring_buffer.c (ffffffff8129036e)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_subbuf_order_set
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:ring_buffer_read_prepare
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_peek
  - kernel/trace/ring_buffer.c:rb_buffer_peek
  - kernel/trace/ring_buffer.c:rb_buffer_peek
  - kernel/trace/ring_buffer.c:rb_advance_reader
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_record_disable
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_handle_head_page
  - kernel/trace/ring_buffer.c:rb_handle_head_page
  - kernel/trace/ring_buffer.c:rb_handle_head_page
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:rb_remove_pages
  - kernel/trace/ring_buffer.c:rb_remove_pages
  - kernel/trace/ring_buffer.c:rb_remove_pages
  - kernel/trace/ring_buffer.c:rb_set_head_page
  - kernel/trace/ring_buffer.c:rb_set_head_page
  - kernel/trace/ring_buffer.c:rb_set_head_page
```
```
In kernel/trace/trace.c (ffffffff812a2ba0)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_set_cpumask
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff812b687d)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
```
```
In kernel/trace/blktrace.c (ffffffff812bac00)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
```
```
In kernel/trace/fgraph.c (ffffffff812bd277)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:ftrace_suspend_notifier_call
  - kernel/trace/fgraph.c:function_graph_enter
```
```
In kernel/trace/trace_events.c (ffffffff812be5dc)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_create_new_event
```
```
In kernel/trace/trace_events_user.c (ffffffff812e1c78)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_mm_alloc
```
```
In kernel/trace/trace_kdb.c (ffffffff812f3955)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/trace/trace_dynevent.c (ffffffff812f3cb0)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - kernel/trace/trace_dynevent.c:trace_event_dyn_try_get_ref
```
```
In kernel/bpf/hashtab.c (ffffffff8134c55e)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/devmap.c (ffffffff81374730)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_map_update_elem
```
```
In kernel/bpf/offload.c (ffffffff81378771)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
```
```
In kernel/events/core.c (ffffffff81394a3d)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
  - kernel/events/core.c:account_event
  - kernel/events/core.c:account_event
  - kernel/events/core.c:account_event
  - kernel/events/core.c:account_event
  - kernel/events/core.c:account_event
  - kernel/events/core.c:account_event
  - kernel/events/core.c:account_event
  - kernel/events/core.c:account_event
  - kernel/events/core.c:account_event
  - kernel/events/core.c:account_event
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_open
  - kernel/events/core.c:perf_mmap_open
  - kernel/events/core.c:perf_mmap_open
  - kernel/events/core.c:perf_mmap_fault
  - kernel/events/core.c:exclusive_event_destroy
  - kernel/events/core.c:find_get_pmu_context
  - kernel/events/core.c:find_get_pmu_context
```
```
In kernel/events/hw_breakpoint.c (ffffffff813a7c49)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff813ac868)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - kernel/events/uprobes.c:pre_ssout
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/watch_queue.c (ffffffff813b2606)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
```
```
In mm/filemap.c (ffffffff813b9520)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:splice_folio_into_pipe
  - mm/filemap.c:folio_end_writeback
  - mm/filemap.c:replace_page_cache_folio
```
```
In mm/oom_kill.c (ffffffff813c01e0)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:mark_oom_victim
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/page-writeback.c (ffffffff813c4487)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
```
```
In mm/readahead.c (ffffffff813c7b46)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
```
```
In mm/swap.c (ffffffff813ccfb5)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_disable
  - mm/swap.c:folio_mark_lazyfree
  - mm/swap.c:folio_deactivate
  - mm/swap.c:deactivate_file_folio
  - mm/swap.c:folio_add_lru
  - mm/swap.c:folio_rotate_reclaimable
```
```
In mm/vmscan.c (ffffffff813dfea3)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - mm/vmscan.c:folio_isolate_lru
```
```
In mm/shmem.c (ffffffff813e7b49)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:__shmem_get_inode
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_unuse
```
```
In mm/gup.c (ffffffff8140e138)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:folio_add_pin
  - mm/gup.c:folio_add_pin
  - mm/gup.c:try_grab_page
```
```
In mm/memory.c (ffffffff8141bca5)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - mm/memory.c:numa_migrate_prep
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/mlock.c (ffffffff81425019)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - mm/mlock.c:munlock_folio
  - mm/mlock.c:mlock_new_folio
  - mm/mlock.c:mlock_folio
```
```
In mm/mmap.c (ffffffff81425f79)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_link
```
```
In mm/mmu_gather.c (ffffffff8142e4ed)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_gather_mmu_fullmm
  - mm/mmu_gather.c:tlb_gather_mmu
```
```
In mm/rmap.c (ffffffff8143c075)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - mm/rmap.c:hugetlb_add_anon_rmap
  - mm/rmap.c:anon_vma_fork
```
```
In mm/madvise.c (ffffffff8146135b)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff8146585b)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cache_get_folio
```
```
In mm/swapfile.c (ffffffff81469484)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte
```
```
In mm/zswap.c (ffffffff81470d16)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - mm/zswap.c:zswap_store
  - mm/zswap.c:zswap_store
  - mm/zswap.c:zswap_store
```
```
In mm/hugetlb.c (ffffffff8147ba34)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff8148749b)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/sparse-vmemmap.c (ffffffff822325ea)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/mmu_notifier.c (ffffffff814891eb)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_interval_notifier_insert
  - mm/mmu_notifier.c:__mmu_notifier_register
```
```
In mm/ksm.c (ffffffff8149239f)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff81496458)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - mm/migrate.c:find_mm_struct
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff8149d3c3)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_insert_page
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814a8a85)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff814b16b8)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:set_huge_pmd
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/memcontrol.c (ffffffff814b8298)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff814c8e9b)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:try_memory_failure_hugetlb
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:page_handle_poison
```
```
In mm/zpool.c (ffffffff814cabac)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - mm/zpool.c:zpool_get_driver
```
```
In mm/zsmalloc.c (ffffffff814cd452)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
```
```
In mm/secretmem.c (ffffffff814cf638)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - mm/secretmem.c:__ia32_sys_memfd_secret
  - mm/secretmem.c:__x64_sys_memfd_secret
```
```
In mm/userfaultfd.c (ffffffff814d2c56)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - mm/userfaultfd.c:move_pages_pte
```
```
In mm/memfd.c (ffffffff814d7269)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In mm/mapping_dirty_helpers.c (ffffffff814d746f)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pre_vma
```
```
In mm/bootmem_info.c (ffffffff83920619)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/open.c (ffffffff814d984c)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/file_table.c (ffffffff814e2ef4)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - fs/file_table.c:alloc_file
```
```
In fs/super.c (ffffffff814e59c8)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - fs/super.c:fs_bdev_freeze
```
```
In fs/exec.c (ffffffff814eaef2)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - fs/exec.c:exec_binprm
  - fs/exec.c:alloc_bprm
  - fs/exec.c:free_bprm
```
```
In fs/pipe.c (ffffffff814ef2ae)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/dcache.c (ffffffff8150463b)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - fs/dcache.c:copy_name
  - fs/dcache.c:take_dentry_name_snapshot
```
```
In fs/inode.c (ffffffff8150bd42)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:igrab
  - fs/inode.c:find_inode_fast
  - fs/inode.c:find_inode
  - fs/inode.c:inode_lru_isolate
```
```
In fs/namespace.c (ffffffff8151af05)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
```
```
In fs/fs-writeback.c (ffffffff8152cf0a)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - fs/fs-writeback.c:cleanup_offline_cgwb
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:wb_queue_work
```
```
In fs/fs_context.c (ffffffff815390e1)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/kernel_read_file.c (ffffffff8153b154)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file
```
```
In fs/buffer.c (ffffffff8153f626)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:__bh_read
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:lookup_bh_lru
  - fs/buffer.c:bh_lru_install
  - fs/buffer.c:__getblk_slow
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/direct-io.c (ffffffff81546012)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In fs/notify/mark.c (ffffffff8154919f)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/userfaultfd.c (ffffffff8155805d)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - fs/userfaultfd.c:new_userfaultfd
  - fs/userfaultfd.c:userfaultfd_unmap_prep
  - fs/userfaultfd.c:userfaultfd_remove
  - fs/userfaultfd.c:mremap_userfaultfd_prep
  - fs/userfaultfd.c:dup_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/aio.c (ffffffff8155e561)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - fs/aio.c:aio_migrate_folio
```
```
In fs/verity/enable.c (ffffffff81571316)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/binfmt_elf.c (ffffffff8157d590)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff815806c1)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In fs/iomap/buffered-io.c (ffffffff8158b514)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:ifs_alloc
```
```
In fs/iomap/direct-io.c (ffffffff8158eff7)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_submit_bio
```
```
In fs/quota/dquot.c (ffffffff81592bbd)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:invalidate_dquots
```
```
In fs/proc/task_mmu.c (ffffffff8159b94b)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:hold_task_mempolicy
```
```
In fs/proc/base.c (ffffffff815a7691)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - fs/proc/base.c:proc_mem_open
```
```
In fs/proc/proc_sysctl.c (ffffffff815b435a)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_poll_notify
```
```
In fs/kernfs/dir.c (ffffffff815bb647)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_destroy_root
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_find_and_get_ns
  - fs/kernfs/dir.c:kernfs_new_node
  - fs/kernfs/dir.c:kernfs_get_parent
```
```
In fs/kernfs/file.c (ffffffff815bd63e)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify
```
```
In fs/configfs/dir.c (ffffffff815c3679)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_make_dirent
  - fs/configfs/dir.c:configfs_new_dirent
```
```
In fs/configfs/symlink.c (ffffffff815c58d6)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - fs/configfs/symlink.c:create_link
```
```
In fs/devpts/inode.c (ffffffff815c6fed)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_acquire
```
```
In fs/ext4/balloc.c (ffffffff815c7fe1)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_should_retry_alloc
```
```
In fs/ext4/ialloc.c (ffffffff815e10d6)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/inline.c (ffffffff815e4d1f)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffffffff815f0dc5)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:mpage_map_one_extent
```
```
In fs/ext4/mballoc.c (ffffffff815facdd)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_choose_next_group_best_avail
  - fs/ext4/mballoc.c:ext4_mb_choose_next_group_p2_aligned
```
```
In fs/ext4/mmp.c (ffffffff816075f6)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block_thawed
```
```
In fs/ext4/super.c (ffffffff81632ec2)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:__ext4_warning_inode
  - fs/ext4/super.c:__ext4_warning
  - fs/ext4/super.c:__ext4_msg
  - fs/ext4/super.c:ext4_read_bh
  - fs/ext4/super.c:ext4_read_bh_nowait
```
```
In fs/ext4/xattr.c (ffffffff816421e9)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/ext4/fast_commit.c (ffffffff81647935)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_commit
  - fs/ext4/fast_commit.c:ext4_fc_start_update
```
```
In fs/ext4/orphan.c (ffffffff81649133)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_file_add
  - fs/ext4/orphan.c:ext4_orphan_file_add
```
```
In fs/jbd2/transaction.c (ffffffff8164ddc0)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/commit.c (ffffffff81650f7a)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff81653390)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff8165cd56)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/fat/dir.c (ffffffff8166ddcc)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
```
```
In fs/fat/fatent.c (ffffffff8166e9f6)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_collect_bhs
```
```
In fs/ecryptfs/miscdev.c (ffffffff816875e1)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_open
```
```
In fs/fuse/dev.c (ffffffff8168af06)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_ioctl
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
```
In fs/fuse/inode.c (ffffffff8169ca91)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_sync_fs_writes
```
```
In ipc/util.c (ffffffff816b0e87)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
```
```
In security/keys/key.c (ffffffff816c37a2)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - security/keys/key.c:key_alloc
```
```
In security/keys/keyctl.c (ffffffff816c89c6)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/selinux/hooks.c (ffffffff816e2f95)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_inc
```
```
In security/selinux/selinuxfs.c (ffffffff816f19bd)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In security/selinux/ss/services.c (ffffffff81702633)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_notify_policy_change
```
```
In security/selinux/xfrm.c (ffffffff8170ca60)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire
  - security/selinux/xfrm.c:selinux_xfrm_policy_clone
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
```
```
In security/tomoyo/common.c (ffffffff81723a1c)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_open_control
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_add_entry
```
```
In security/tomoyo/condition.c (ffffffff81723e23)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_commit_condition
```
```
In security/tomoyo/domain.c (ffffffff81727731)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
```
```
In security/tomoyo/memory.c (ffffffff8172b2f5)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/securityfs_if.c (ffffffff8172da34)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8392b52c)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_init
  - security/tomoyo/tomoyo.c:tomoyo_task_alloc
```
```
In security/apparmor/policy_unpack.c (ffffffff81747c7e)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
```
```
In block/bdev.c (ffffffff817a8b65)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - block/bdev.c:bdev_open_by_dev
  - block/bdev.c:blkdev_get_whole
  - block/bdev.c:bdev_thaw
```
```
In block/fops.c (ffffffff817a9dfd)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
```
```
In block/bio.c (ffffffff817ad54f)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - block/bio.c:blk_next_bio
```
```
In block/blk-core.c (ffffffff817b0415)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - block/blk-core.c:blk_set_pm_only
```
```
In block/blk-ioc.c (ffffffff817b9597)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - block/blk-ioc.c:__copy_io
```
```
In block/blk-mq.c (ffffffff817c5f3b)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In block/blk-iocost.c (ffffffff817f3744)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:weight_updated
```
```
In block/mq-deadline.c (ffffffff817f66cc)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_finish_request
```
```
In io_uring/io_uring.c (ffffffff8181689f)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_create
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_file_get_normal
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_eventfd_signal
```
```
In io_uring/sqpoll.c (ffffffff8181fdec)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread_park
```
```
In io_uring/rw.c (ffffffff818299d3)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - io_uring/rw.c:io_read_mshot
```
```
In io_uring/io-wq.c (ffffffff8182db12)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_enqueue
  - io_uring/io-wq.c:io_wq_enqueue
  - io_uring/io-wq.c:io_wq_worker_running
  - io_uring/io-wq.c:io_wq_dec_running
  - io_uring/io-wq.c:io_wq_dec_running
  - io_uring/io-wq.c:io_queue_worker_create
```
```
In lib/iov_iter.c (ffffffff8185923a)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
  - lib/iov_iter.c:iter_xarray_populate_pages
```
```
In lib/rhashtable.c (ffffffff8185ebab)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
```
```
In lib/sbitmap.c (ffffffff8192c36e)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_prepare_to_wait
```
```
In drivers/pci/pci.c (ffffffff8196e0dc)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pcie/portdrv.c (ffffffff81983f81)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_shutdown
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_remove
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81999665)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8199cc83)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff819c9a47)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff819d378b)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_registered
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a7ae4e)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cached
```
```
In drivers/clk/clk.c (ffffffff81a8a379)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/pmdomain/core.c (ffffffff81aa1ed6)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/pmdomain/core.c:genpd_add_subdomain
  - drivers/pmdomain/core.c:genpd_power_on
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81ab2386)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/xen/grant-table.c (ffffffff81ab6042)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/xen/events/events_base.c (ffffffff81abd016)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
```
```
In drivers/tty/tty_buffer.c (ffffffff81af1f7c)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_flush
  - drivers/tty/tty_buffer.c:tty_buffer_lock_exclusive
```
```
In drivers/tty/vt/keyboard.c (ffffffff81afd8a5)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81b2dad9)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff81b3503b)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/backend.c (ffffffff81b3b6f4)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_acquire
```
```
In drivers/char/agp/generic.c (ffffffff81b3e118)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81b41f8b)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_alloc_by_type
```
```
In drivers/iommu/iommu.c (ffffffff81b77bf8)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_sva_domain_alloc
```
```
In drivers/connector/cn_queue.c (ffffffff81b81dc2)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_alloc_callback_entry
```
```
In drivers/connector/cn_proc.c (ffffffff81b82c9e)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
```
```
In drivers/base/core.c (ffffffff81b8d344)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/dd.c (ffffffff81b90b32)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/devtmpfs.c (ffffffff81ba1abe)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:public_dev_mount
```
```
In drivers/base/power/runtime.c (ffffffff81ba811d)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:update_autosuspend
  - drivers/base/power/runtime.c:pm_runtime_forbid
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
  - drivers/base/power/runtime.c:__pm_runtime_resume
  - drivers/base/power/runtime.c:rpm_drop_usage_count
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/base/power/main.c (ffffffff81baa055)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_prepare
```
```
In drivers/base/power/wakeup.c (ffffffff81bafa60)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_irq_wakeup
  - drivers/base/power/wakeup.c:wakeup_source_report_event
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
```
```
In drivers/nvdimm/bus.c (ffffffff81bf9406)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_ioctl
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81c01e58)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:init_active_labels
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81c1b1c8)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/cxl/core/suspend.c (ffffffff81c1bc55)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/cxl/core/suspend.c:cxl_mem_active_inc
```
```
In drivers/scsi/hosts.c (ffffffff81c1f75b)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_error.c (ffffffff81c243eb)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_timeout
  - drivers/scsi/scsi_error.c:scsi_timeout
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c259f5)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_disable_disk_events
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_complete
  - drivers/scsi/scsi_lib.c:scsi_complete
```
```
In drivers/scsi/sg.c (ffffffff81c46acd)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/gpu/drm/drm_vblank.c (ffffffff81cb3f82)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_vblank_reset
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_vblank_off
```
```
In drivers/net/tun.c (ffffffff81cfc7c9)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_build_skb
```
```
In drivers/net/virtio_net.c (ffffffff81d08801)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_rq_alloc
  - drivers/net/virtio_net.c:virtnet_rq_alloc
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d18ce7)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
```
```
In drivers/net/xen-netfront.c (ffffffff81d1f33c)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:handle_incoming_queue
```
```
In drivers/usb/core/hub.c (ffffffff81d36e2f)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/hcd.c (ffffffff81d3bda3)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_start_port_resume
```
```
In drivers/usb/core/urb.c (ffffffff81d3cf0e)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_anchor_suspend_wakeups
  - drivers/usb/core/urb.c:usb_block_urb
  - drivers/usb/core/urb.c:usb_anchor_urb
```
```
In drivers/usb/core/driver.c (ffffffff81d42aa3)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
```
```
In drivers/usb/core/port.c (ffffffff81d53c61)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81d54636)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
```
```
In drivers/usb/host/xhci.c (ffffffff81d99d6a)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81ded349)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81dedd88)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81df5a14)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/power_supply_core.c:power_supply_get_by_name
```
```
In drivers/md/md.c (ffffffff83d515d6)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_open
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:hot_remove_disk
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_attr_store
  - drivers/md/md.c:md_attr_show
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:md_super_write
  - drivers/md/md.c:md_super_write
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
```
```
In drivers/md/md-bitmap.c (ffffffff81e25985)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/md-bitmap.c:write_file_page
  - drivers/md/md-bitmap.c:write_sb_page
```
```
In drivers/md/dm.c (ffffffff81e31153)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_get
  - drivers/md/dm.c:event_callback
  - drivers/md/dm.c:event_callback
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_blk_open
```
```
In drivers/md/dm-stripe.c (ffffffff81e3645e)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-io.c (ffffffff81e3acde)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/md/dm-io.c:do_region
  - drivers/md/dm-io.c:do_region
```
```
In drivers/md/dm-kcopyd.c (ffffffff81e3b64c)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
  - drivers/md/dm-kcopyd.c:dispatch_job
```
```
In drivers/md/dm-stats.c (ffffffff81e3d69a)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stat_for_entry
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81e46065)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_handle_npe
  - drivers/edac/edac_pci_sysfs.c:edac_pci_handle_pe
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
```
```
In drivers/mmc/core/sdio.c (ffffffff81e7c231)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81e7d17a)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e9bded)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_detach
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
```
```
In drivers/ras/debugfs.c (ffffffff81eaee65)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_open
```
```
In drivers/hte/hte.c (ffffffff81eb600c)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - drivers/hte/hte.c:hte_push_ts_ns
  - drivers/hte/hte.c:__hte_req_ts
```
```
In net/core/sock.c (ffffffff81ec74ca)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81ed96bc)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__skb_zcopy_downgrade_managed
  - net/core/skbuff.c:__skb_clone
```
```
In net/core/datagram.c (ffffffff81ede79e)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
```
```
In net/core/dev.c (ffffffff81f00590)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_many_notify
```
```
In net/core/neighbour.c (ffffffff81f0b0f5)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_probe
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/filter.c (ffffffff81f302c4)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81f63eef)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/sched/sch_generic.c (ffffffff81f6ed30)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - net/sched/sch_generic.c:netif_carrier_on
```
```
In net/sched/cls_api.c (ffffffff81f77bf0)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_cls_offload_cnt_update
```
```
In net/sched/act_api.c (ffffffff81f80a27)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_check_alloc
```
```
In net/netlink/af_netlink.c (ffffffff81f88864)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_overrun
```
```
In net/ipv4/route.c (ffffffff81faef71)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_dst_clone
```
```
In net/ipv4/ip_output.c (ffffffff81fbe0b1)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fc97c5)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp.c (ffffffff81fd1132)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_input.c (ffffffff81fdd4af)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff81fe9d6b)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_clone_payload
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff6a3a)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ffeb14)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/raw.c (ffffffff820038ce)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
```
```
In net/ipv4/udp.c (ffffffff820098cd)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_read_skb
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/fib_frontend.c (ffffffff82025178)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
```
In net/ipv4/fib_semantics.c (ffffffff82025ffa)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_common_init
```
```
In net/ipv4/inet_fragment.c (ffffffff82030a81)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
```
```
In net/ipv4/fib_rules.c (ffffffff82041462)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/ipmr.c (ffffffff82045f51)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204dfe3)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff82061a94)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
```
```
In net/ipv6/ip6_output.c (ffffffff82084168)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff8208cdc6)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
```
```
In net/ipv6/route.c (ffffffff820a43f4)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_rt_copy_init
```
```
In net/ipv6/udp.c (ffffffff820b8cc8)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff820bcf8f)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cce16)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_conn_request
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff820d4a33)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
```
```
In net/ipv6/ioam6.c (ffffffff820d93ce)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff820df1f1)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:mif6_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff820eef70)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
```
```
In net/packet/af_packet.c (ffffffff820fbb47)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff821252ad)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff82127416)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffffffff82127af5)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_add
```
```
In net/xdp/xsk.c (ffffffff8213e765)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
```
In net/xdp/xskmap.c (ffffffff82140f85)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - net/xdp/xskmap.c:xsk_map_update_elem
```
```
In net/mptcp/protocol.c (ffffffff8214cdb5)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
```
```
In net/mptcp/subflow.c (ffffffff8214ebbf)
Location: include/linux/atomic/atomic-arch-fallback.h:989
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_v6_conn_request
  - net/mptcp/subflow.c:subflow_v4_conn_request
```
```
In net/handshake/request.c (ffffffff821699fe)
Location: include/linux/atomic/atomic-arch-fallback.h:989
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

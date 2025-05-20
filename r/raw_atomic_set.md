# Function: <code>raw_atomic_set</code>

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
In arch/x86/kernel/ioport.c (ffffffff81051d8c)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/tboot.c (ffffffff8369dbcf)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81079775)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:mce_start
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107e3f8)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff81091c0d)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_open
```
```
In arch/x86/kernel/reboot.c (ffffffff8109b207)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:nmi_shootdown_cpus
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8109f81d)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In arch/x86/kernel/kgdb.c (ffffffff810b618d)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_arch_handle_exception
  - arch/x86/kernel/kgdb.c:kgdb_arch_handle_exception
```
```
In arch/x86/mm/init_64.c (ffffffff8214943a)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff836c8b1c)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_dump_state
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/fork.c (ffffffff810f055b)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/fork.c:copy_signal
  - kernel/fork.c:copy_signal
  - kernel/fork.c:copy_sighand
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
```
```
In kernel/cpu.c (ffffffff836c9f7a)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_hotplug_init
```
```
In kernel/softirq.c (ffffffff810fea35)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_init
  - kernel/softirq.c:tasklet_setup
```
```
In kernel/user.c (ffffffff8110941e)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/workqueue.c (ffffffff811252e4)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
```
```
In kernel/pid.c (ffffffff81126802)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/nsproxy.c (ffffffff81131051)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/cred.c (ffffffff811340c3)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
```
```
In kernel/ucount.c (ffffffff81137651)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/ucount.c:alloc_ucounts
```
```
In kernel/groups.c (ffffffff81138da3)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
```
```
In kernel/sched/core.c (ffffffff836ccbb5)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:affine_move_task
```
```
In kernel/sched/fair.c (ffffffff811552e6)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/sched/build_utility.c (ffffffff8118193e)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/sched/build_utility.c:autogroup_init
  - kernel/sched/build_utility.c:membarrier_exec_mmap
  - kernel/sched/build_utility.c:psi_trigger_destroy
  - kernel/sched/build_utility.c:psi_trigger_create
  - kernel/sched/build_utility.c:psi_group_change
  - kernel/sched/build_utility.c:poll_timer_fn
  - kernel/sched/build_utility.c:psi_rtpoll_work
  - kernel/sched/build_utility.c:psi_rtpoll_work
  - kernel/sched/build_utility.c:group_init
  - kernel/sched/build_utility.c:sched_core_share_pid
  - kernel/sched/build_utility.c:sd_init
  - kernel/sched/build_utility.c:init_defrootdomain
  - kernel/sched/build_utility.c:cpupri_init
```
```
In kernel/locking/mutex.c (ffffffff8118d274)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff8118dc0c)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:__init_rwsem
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8118e5ec)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
```
```
In kernel/power/swap.c (ffffffff81199f26)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:save_image
```
```
In kernel/irq/manage.c (ffffffff811a878d)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/rcu/update.c (ffffffff811bcd81)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
```
```
In kernel/rcu/srcutree.c (ffffffff811c08ae)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
```
```
In kernel/rcu/tree.c (ffffffff811c3afe)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kfree_rcu_shrink_count
  - kernel/rcu/tree.c:fill_page_cache_func
  - kernel/rcu/tree.c:fill_page_cache_func
  - kernel/rcu/tree.c:kfree_rcu_monitor
  - kernel/rcu/tree.c:kfree_rcu_monitor
  - kernel/rcu/tree.c:kfree_rcu_monitor
```
```
In kernel/module/main.c (ffffffff811df6c9)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/module/main.c:load_module
```
```
In kernel/time/namespace.c (ffffffff81206c69)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/futex/core.c (ffffffff836d3a46)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_init
```
```
In kernel/futex/pi.c (ffffffff8120a3b9)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/futex/pi.c:refill_pi_state_cache
```
```
In kernel/kexec_core.c (ffffffff812138b5)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/kexec_core.c:__crash_shrink_memory
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/cgroup/cgroup.c (ffffffff8121b265)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff81227b0c)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff81235c25)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/utsname.c:clone_uts_ns
```
```
In kernel/user_namespace.c (ffffffff81237d05)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81238a7d)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/stop_machine.c (ffffffff8123a5a1)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_core_cpuslocked
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:cpu_stop_init_done
```
```
In kernel/audit_watch.c (ffffffff812486f1)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_to_watch
```
```
In kernel/audit_tree.c (ffffffff81249be1)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_tree
```
```
In kernel/debug/debug_core.c (ffffffff812510d9)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8125770f)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
```
```
In kernel/hung_task.c (ffffffff8125dc55)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/hung_task.c:reset_hung_task_detector
```
```
In kernel/seccomp.c (ffffffff81261cc7)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In kernel/relay.c (ffffffff812647b8)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/relay.c:relay_open
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/trace.c (ffffffff8127cf74)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/trace/tracing_map.c (ffffffff8129048e)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_create
  - kernel/trace/tracing_map.c:tracing_map_clear
```
```
In kernel/trace/blktrace.c (ffffffff8129f324)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
```
In kernel/trace/fgraph.c (ffffffff812a23ba)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/fgraph.c:ftrace_graph_init_task
```
```
In kernel/trace/trace_events.c (ffffffff812a6c3a)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_add_event_call
  - kernel/trace/trace_events.c:trace_create_new_event
  - kernel/trace/trace_events.c:trace_create_new_event
```
```
In kernel/trace/trace_events_user.c (ffffffff812c67b4)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_parse
  - kernel/trace/trace_events_user.c:user_event_mm_alloc
  - kernel/trace/trace_events_user.c:user_event_mm_alloc
  - kernel/trace/trace_events_user.c:delayed_destroy_user_event
```
```
In kernel/trace/trace_dynevent.c (ffffffff812d6227)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/trace/trace_dynevent.c:trace_event_dyn_put_ref
```
```
In kernel/trace/rethook.c (ffffffff812df03c)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_alloc
```
```
In kernel/irq_work.c (ffffffff812e5097)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_single
```
```
In kernel/bpf/syscall.c (ffffffff812f28ac)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
```
In kernel/bpf/helpers.c (ffffffff81320ca6)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_obj_new_impl
```
```
In kernel/bpf/hashtab.c (ffffffff8132b523)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:__bpf_hash_map_seq_show
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
```
```
In kernel/bpf/arraymap.c (ffffffff8132d176)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:__bpf_array_map_seq_show
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
```
```
In kernel/bpf/local_storage.c (ffffffff81332478)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
```
```
In kernel/bpf/ringbuf.c (ffffffff813335ef)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_user_ringbuf_drain
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
```
```
In kernel/bpf/trampoline.c (ffffffff8133745c)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_lookup
```
```
In kernel/bpf/btf.c (ffffffff8133af9b)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse
```
```
In kernel/bpf/memalloc.c (ffffffff8134b5dd)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:__free_rcu_tasks_trace
```
```
In kernel/bpf/dispatcher.c (ffffffff8134c8c1)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8135d1b4)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_sys_lookup_elem
```
```
In kernel/bpf/cpumask.c (ffffffff8135d57b)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_create
```
```
In kernel/events/core.c (ffffffff836deb3a)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:find_get_pmu_context
  - kernel/events/core.c:find_get_pmu_context
  - kernel/events/core.c:alloc_perf_context
```
```
In kernel/events/ring_buffer.c (ffffffff8137d11f)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
  - kernel/events/ring_buffer.c:perf_output_put_handle
```
```
In kernel/events/uprobes.c (ffffffff81383278)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
  - kernel/events/uprobes.c:alloc_uprobe
```
```
In kernel/padata.c (ffffffff81384fda)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
```
```
In kernel/jump_label.c (ffffffff813865b9)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
```
In kernel/watch_queue.c (ffffffff81389c4c)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_init
  - kernel/watch_queue.c:init_watch
```
```
In mm/filemap.c (ffffffff8138b39e)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/vmscan.c (ffffffff813b9000)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
```
```
In mm/shmem.c (0)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
```
```
In mm/backing-dev.c (ffffffff813cba66)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_init
  - mm/backing-dev.c:wb_init
```
```
In mm/mm_init.c (ffffffff8214bfbc)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - mm/mm_init.c:memmap_init_range
  - mm/mm_init.c:memmap_init_range
  - mm/mm_init.c:init_unavailable_range
  - mm/mm_init.c:init_unavailable_range
```
```
In mm/rmap.c (ffffffff8140f74b)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:folio_add_new_anon_rmap
  - mm/rmap.c:folio_add_new_anon_rmap
  - mm/rmap.c:folio_add_new_anon_rmap
  - mm/rmap.c:anon_vma_ctor
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/page_alloc.c (ffffffff81422c19)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__rmqueue_pcplist
  - mm/page_alloc.c:split_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:prep_compound_page
  - mm/page_alloc.c:prep_compound_page
  - mm/page_alloc.c:prep_compound_page
  - mm/page_alloc.c:bad_page
```
```
In mm/madvise.c (ffffffff814285a0)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - mm/madvise.c:anon_vma_name_alloc
```
```
In mm/swap_state.c (ffffffff8142cf3b)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
  - mm/swap_state.c:swap_cluster_readahead
```
```
In mm/frontswap.c (ffffffff81434bfe)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_area
```
```
In mm/zswap.c (ffffffff81435401)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff8143de82)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - mm/hugetlb.c:demote_free_hugetlb_folio
  - mm/hugetlb.c:demote_free_hugetlb_folio
  - mm/hugetlb.c:demote_free_hugetlb_folio
  - mm/hugetlb.c:__prep_compound_gigantic_folio
  - mm/hugetlb.c:__prep_compound_gigantic_folio
  - mm/hugetlb.c:__prep_compound_gigantic_folio
  - mm/hugetlb.c:__prep_compound_gigantic_folio
  - mm/hugetlb.c:__update_and_free_hugetlb_folio
  - mm/hugetlb.c:__update_and_free_hugetlb_folio
  - mm/hugetlb.c:__update_and_free_hugetlb_folio
  - mm/hugetlb.c:__update_and_free_hugetlb_folio
  - mm/hugetlb.c:resv_map_alloc
```
```
In mm/mempolicy.c (ffffffff8144943c)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mpol_new
```
```
In mm/kfence/core.c (ffffffff8146431f)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
```
```
In mm/memory-tiers.c (ffffffff836eb96e)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - mm/memory-tiers.c:memory_tier_init
```
```
In mm/huge_memory.c (ffffffff81473bac)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - mm/huge_memory.c:mm_get_huge_zero_page
```
```
In mm/memcontrol.c (ffffffff81485ea6)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
```
```
In mm/zpool.c (ffffffff8149b399)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - mm/zpool.c:zpool_register_driver
```
```
In mm/zsmalloc.c (ffffffff8149c933)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/memremap.c (ffffffff814a402a)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
  - mm/memremap.c:free_zone_device_page
```
```
In mm/page_reporting.c (ffffffff814a7667)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_register
  - mm/page_reporting.c:page_reporting_process
  - mm/page_reporting.c:page_reporting_cycle
```
```
In mm/bootmem_info.c (ffffffff814a787b)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In fs/super.c (ffffffff814b2906)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - fs/super.c:alloc_super
```
```
In fs/exec.c (ffffffff814b866e)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - fs/exec.c:unshare_sighand
```
```
In fs/dcache.c (ffffffff814d1e71)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
```
```
In fs/inode.c (ffffffff814d657e)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
```
```
In fs/file.c (ffffffff814dc9f8)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - fs/file.c:dup_fd
```
```
In fs/namespace.c (ffffffff814e0329)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fsopen.c (ffffffff81505e26)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
```
```
In fs/mnt_idmapping.c (ffffffff81506d63)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - fs/mnt_idmapping.c:alloc_mnt_idmap
```
```
In fs/notify/group.c (ffffffff81513b5e)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_alloc_group
  - fs/notify/group.c:fsnotify_alloc_group
```
```
In fs/notify/mark.c (ffffffff815142fb)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_init_mark
```
```
In fs/eventpoll.c (ffffffff8151e849)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_create
```
```
In fs/eventfd.c (ffffffff81523265)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/userfaultfd.c (ffffffff81523ab5)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - fs/userfaultfd.c:new_userfaultfd
  - fs/userfaultfd.c:new_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/aio.c (ffffffff8152c032)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:exit_aio
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/crypto/keyring.c (ffffffff81535cf7)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
```
```
In fs/crypto/keysetup_v1.c (ffffffff815386ae)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
```
```
In fs/mbcache.c (ffffffff8154c716)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/posix_acl.c (ffffffff8154db28)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_from_mode
  - fs/posix_acl.c:posix_acl_clone
```
```
In fs/coredump.c (ffffffff8154f61a)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - fs/coredump.c:coredump_wait
```
```
In fs/iomap/direct-io.c (ffffffff8155881a)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
```
In fs/quota/dquot.c (ffffffff8155c51a)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
```
```
In fs/proc/generic.c (ffffffff8157168d)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/kernfs/inode.c (ffffffff815809e3)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff81581b5e)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/kernfs/file.c (ffffffff815851b0)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_open
```
```
In fs/configfs/dir.c (ffffffff8158c29d)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_new_dirent
```
```
In fs/configfs/item.c (ffffffff8158d63c)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/ext4/mballoc.c (ffffffff815cc77d)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_init
```
```
In fs/ext4/page-io.c (ffffffff815da3bb)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_init_io_end
```
```
In fs/ext4/super.c (ffffffff81603435)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_inode
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/fast_commit.c (ffffffff8160db45)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_init_inode
```
```
In fs/ext4/orphan.c (ffffffff81610fb1)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_init_orphan_info
```
```
In fs/jbd2/transaction.c (ffffffff81613ef9)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff816213dd)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/ecryptfs/main.c (ffffffff81643e98)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In fs/ecryptfs/super.c (ffffffff81644214)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - fs/ecryptfs/super.c:ecryptfs_alloc_inode
```
```
In fs/ecryptfs/miscdev.c (ffffffff836f3a75)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev
```
```
In fs/fuse/dev.c (ffffffff816516b3)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_alloc
```
```
In fs/fuse/file.c (ffffffff8165f6f5)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff81664ba4)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_sync_fs_writes
```
```
In fs/fuse/dax.c (ffffffff81669bbc)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
```
```
In fs/debugfs/file.c (ffffffff8166ce85)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_atomic_t_set
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff81674fd5)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In ipc/sem.c (ffffffff8167d600)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:find_alloc_undo
```
```
In ipc/namespace.c (ffffffff8168551b)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
```
```
In security/keys/key.c (ffffffff8168782c)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
  - security/keys/key.c:key_user_lookup
  - security/keys/key.c:key_user_lookup
```
```
In security/selinux/avc.c (ffffffff816a556d)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - security/selinux/avc.c:selinux_avc_init
  - security/selinux/avc.c:selinux_avc_init
```
```
In security/selinux/ss/services.c (ffffffff816ccc31)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
```
In security/smack/smack_access.c (ffffffff816d974a)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_populate_secattr
```
```
In security/tomoyo/condition.c (ffffffff816e708c)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_commit_condition
```
```
In security/tomoyo/gc.c (ffffffff816ed753)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_collect_entry
  - security/tomoyo/gc.c:tomoyo_collect_entry
  - security/tomoyo/gc.c:tomoyo_collect_entry
```
```
In security/tomoyo/memory.c (ffffffff816ee603)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/apparmor/apparmorfs.c (ffffffff816f7d2d)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/audit.c (ffffffff816fa678)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_dup_audit_data
```
```
In security/apparmor/lib.c (ffffffff816fce69)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff816fdae7)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy.c (ffffffff8170614e)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_alloc_pdb
```
```
In security/apparmor/policy_unpack.c (ffffffff8170bcdb)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/policy_ns.c (ffffffff81717269)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:alloc_ns
```
```
In security/apparmor/label.c (ffffffff8171998c)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In security/apparmor/notify.c (ffffffff817245a2)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - security/apparmor/notify.c:aa_new_listener
  - security/apparmor/notify.c:aa_new_listener
```
```
In security/landlock/object.c (ffffffff81729dd7)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - security/landlock/object.c:landlock_create_object
```
```
In security/landlock/ruleset.c (ffffffff8172a737)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:landlock_create_ruleset
```
```
In security/integrity/ima/ima_policy.c (ffffffff836fbb5a)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_init_policy
```
```
In crypto/api.c (ffffffff8173e968)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - crypto/api.c:__crypto_alloc_tfmgfp
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In crypto/algapi.c (ffffffff8173f423)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_check_alg
```
```
In crypto/jitterentropy-testing.c (ffffffff8175e5c2)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
```
```
In block/fops.c (ffffffff817681b6)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
```
```
In block/bio.c (ffffffff81769f35)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - block/bio.c:bio_init_clone
  - block/bio.c:bio_init_clone
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_reset
```
```
In block/blk-core.c (ffffffff817719d4)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - block/blk-core.c:blk_alloc_queue
  - block/blk-core.c:blk_alloc_queue
```
```
In block/blk-flush.c (ffffffff81774cfb)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-ioc.c (ffffffff817769cf)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - block/blk-ioc.c:alloc_io_context
```
```
In block/blk-mq.c (ffffffff81780f97)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_hctx
```
```
In block/bsg-lib.c (ffffffff8179e78d)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In block/blk-cgroup.c (ffffffff817a09d9)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In block/blk-iocost.c (ffffffff817acdb6)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
```
```
In block/blk-wbt.c (ffffffff817bafd1)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
```
```
In block/blk-crypto-profile.c (ffffffff817c3e4a)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
```
```
In io_uring/io_uring.c (ffffffff817d05a7)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_eventfd_register
  - io_uring/io_uring.c:io_eventfd_register
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:__io_arm_ltimeout
  - io_uring/io_uring.c:__io_arm_ltimeout
```
```
In io_uring/timeout.c (ffffffff817d9cf6)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - io_uring/timeout.c:io_timeout_fn
  - io_uring/timeout.c:io_flush_timeouts
```
```
In io_uring/sqpoll.c (ffffffff817db133)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_get_sq_data
  - io_uring/sqpoll.c:io_get_sq_data
```
```
In io_uring/tctx.c (ffffffff817dcd26)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - io_uring/tctx.c:io_uring_alloc_task_context
  - io_uring/tctx.c:io_uring_alloc_task_context
  - io_uring/tctx.c:io_uring_alloc_task_context
```
```
In io_uring/poll.c (ffffffff817de61b)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - io_uring/poll.c:__io_arm_poll_handler
```
```
In io_uring/rsrc.c (ffffffff817e229c)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_rsrc_ref_quiesce
  - io_uring/rsrc.c:io_rsrc_ref_quiesce
```
```
In io_uring/notif.c (ffffffff817e62e2)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - io_uring/notif.c:io_alloc_notif
```
```
In io_uring/io-wq.c (ffffffff817e890a)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_create
  - io_uring/io-wq.c:io_wq_create
  - io_uring/io-wq.c:create_io_worker
```
```
In lib/rhashtable.c (ffffffff81818ee0)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
```
```
In lib/refcount.c (ffffffff8181ac8b)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_and_lock_irqsave
  - lib/refcount.c:refcount_dec_and_lock
  - lib/refcount.c:refcount_dec_and_mutex_lock
```
```
In lib/rcuref.c (ffffffff8181ada2)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - lib/rcuref.c:rcuref_put_slowpath
  - lib/rcuref.c:rcuref_put_slowpath
  - lib/rcuref.c:rcuref_get_slowpath
  - lib/rcuref.c:rcuref_get_slowpath
```
```
In lib/cpu_rmap.c (ffffffff818d3443)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In lib/sbitmap.c (ffffffff818e5276)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_wake_up
  - lib/sbitmap.c:sbitmap_queue_init_node
  - lib/sbitmap.c:sbitmap_queue_init_node
  - lib/sbitmap.c:sbitmap_queue_init_node
  - lib/sbitmap.c:sbitmap_queue_init_node
```
```
In drivers/pinctrl/core.c (ffffffff818ee8fe)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff81909000)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_create
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8195b666)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/rapidio/rio.c (ffffffff8196f19d)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/rapidio/rio.c:rio_mport_initialize
  - drivers/rapidio/rio.c:rio_del_device
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8197a93a)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
```
```
In drivers/acpi/ec.c (ffffffff819ad251)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/acpi/thermal.c (ffffffff81a2280a)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a303b4)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
```
```
In drivers/clk/clk.c (ffffffff81a44c64)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dma/dmaengine.c (ffffffff81a4d358)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/xen/balloon.c (ffffffff81a64587)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_thread
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81a74e14)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (ffffffff81a908b7)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (ffffffff81a96e44)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_buffer.c (ffffffff81a9f741)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_init
  - drivers/tty/tty_buffer.c:tty_buffer_init
```
```
In drivers/tty/tty_port.c (ffffffff81a9fb72)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/tty/serial/serial_core.c (ffffffff81ac3049)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:serial_core_add_one_port
```
```
In drivers/char/random.c (ffffffff81ae05b1)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/char/random.c:try_to_generate_entropy
```
```
In drivers/char/virtio_console.c (ffffffff81ae33f9)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
```
```
In drivers/char/hw_random/core.c (ffffffff81ae7254)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
```
```
In drivers/char/agp/backend.c (ffffffff81ae88e4)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_alloc_bridge
  - drivers/char/agp/backend.c:agp_alloc_bridge
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b25498)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_init_fq
  - drivers/iommu/dma-iommu.c:fq_flush_timeout
```
```
In drivers/connector/cn_queue.c (ffffffff81b2ae4a)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_alloc_dev
  - drivers/connector/cn_queue.c:cn_queue_alloc_callback_entry
```
```
In drivers/base/core.c (ffffffff81b331fe)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff81b507c6)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/base/power/runtime.c:pm_runtime_init
```
```
In drivers/base/power/wakeup.c (ffffffff81b57370)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_wakeup_clear
```
```
In drivers/base/power/domain.c (ffffffff81b59fc8)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_init
```
```
In drivers/base/firmware_loader/main.c (ffffffff81b5f576)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv
```
```
In drivers/block/loop.c (ffffffff81b7c60e)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
```
```
In drivers/nvdimm/core.c (ffffffff81ba220d)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:alloc_nvdimm_map
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81ba63aa)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
```
```
In drivers/nvdimm/dimm.c (ffffffff81ba7ba4)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
```
```
In drivers/dax/bus.c (ffffffff81bbad4a)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81bbf30f)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81bc0260)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81bc559f)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_create
```
```
In drivers/scsi/scsi.c (ffffffff81bc9518)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/hosts.c (ffffffff81bcaaf6)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd56d3)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
```
In drivers/scsi/scsi_scan.c (ffffffff81bd786e)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sd.c (ffffffff81bea676)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/scsi/sg.c (ffffffff81bf5a2e)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_alloc
```
```
In drivers/ata/libata-core.c (ffffffff81bfa454)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/phy_device.c (ffffffff81c3a741)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_package_join
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81c405b2)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/pse-pd/pse_core.c (0)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c6223d)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/usb/core/usb.c (ffffffff81c78ea0)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
```
```
In drivers/usb/core/hub.c (ffffffff81c83a3a)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff81c85670)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff81c8854f)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_init_urb
```
```
In drivers/usb/core/config.c (ffffffff81c9166e)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff81c929e3)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_register_dev
```
```
In drivers/thermal/thermal_core.c (ffffffff81d48d2c)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81d531dc)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
```
```
In drivers/md/md.c (ffffffff81d694d8)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_run
  - drivers/md/md.c:max_corrected_read_errors_store
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:errors_store
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:submit_flushes
```
```
In drivers/md/md-bitmap.c (ffffffff81d71722)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In drivers/md/dm.c (ffffffff81d77708)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_get_table_device
```
```
In drivers/md/dm-table.c (ffffffff82148904)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/md/dm-stripe.c (ffffffff81d7f0db)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/md/dm-io.c (ffffffff81d83b53)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff81d84400)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
```
In drivers/md/dm-stats.c (ffffffff81d86660)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
```
```
In drivers/edac/ghes_edac.c (ffffffff81d8eedc)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
```
```
In drivers/opp/core.c (ffffffff81d94276)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
  - drivers/opp/core.c:_add_opp_table_indexed
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81d9e1e8)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
  - drivers/cpufreq/cpufreq_governor.c:dbs_work_handler
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff81dc6dc1)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
```
```
In drivers/firmware/efi/efi.c (ffffffff82148a74)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de4dda)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
```
```
In drivers/devfreq/devfreq.c (ffffffff81deede1)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/nvmem/core.c (ffffffff81dfab70)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
```
```
In drivers/hte/hte.c (ffffffff81dfee9a)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - drivers/hte/hte.c:hte_ts_put
```
```
In net/core/sock.c (ffffffff81e08dfb)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data_uid
  - net/core/sock.c:sock_init_data_uid
  - net/core/sock.c:sock_init_data_uid
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sock_set_timestamping
  - net/core/sock.c:sock_set_timestamping
  - net/core/sock.c:sock_set_timestamping
```
```
In net/core/skbuff.c (ffffffff81e13aaf)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_maybe_cow
  - net/core/skbuff.c:__skb_ext_alloc
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:slab_build_skb
  - net/core/skbuff.c:slab_build_skb
```
```
In net/core/net_namespace.c (ffffffff81e25d55)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:setup_net
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff81e2eddd)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/core/dev.c:dev_kfree_skb_irq_reason
```
```
In net/core/dst.c (ffffffff81e44ee7)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
  - net/core/dst.c:dst_cow_metrics_generic
  - net/core/dst.c:dst_alloc
```
```
In net/core/neighbour.c (ffffffff81e49667)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/filter.c (ffffffff81e72ba9)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
```
```
In net/core/flow_offload.c (ffffffff81e7aa37)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_register
```
```
In net/core/gro.c (ffffffff81e7c9ae)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/core/gro.c:skb_gro_receive
```
```
In net/core/page_pool.c (ffffffff81e822c9)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_init
  - net/core/page_pool.c:page_pool_init
```
```
In net/core/netpoll.c (ffffffff81e85df2)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/core/fib_rules.c (ffffffff81e87ece)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_default_rule_add
```
```
In net/core/skmsg.c (ffffffff81ea1cb3)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/sched/sch_generic.c (ffffffff81eadc90)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/sched/cls_api.c (ffffffff81ebb60b)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/sched/act_api.c (ffffffff81ebde1f)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
```
```
In net/ipv4/route.c (ffffffff81eeb095)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_genid_init
  - net/ipv4/route.c:rt_genid_init
  - net/ipv4/route.c:rt_genid_init
```
```
In net/ipv4/inetpeer.c (ffffffff81ef3463)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (ffffffff81efc1f0)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81f04176)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f06ec8)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp.c (ffffffff81f0bc12)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81f14a82)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_output.c (ffffffff81f2096d)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_clone_payload
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2c4ae)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_init
  - net/ipv4/tcp_ipv4.c:tcp_sk_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81f389ab)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/datagram.c (ffffffff81f3aa2f)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (0)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81f51850)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
```
```
In net/ipv4/af_inet.c (ffffffff81f53788)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81f59947)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5c3c2)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81f628d1)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_rebalance
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6ac3e)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/ipv4/metrics.c (ffffffff81f70733)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81f774f5)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:nh_hthr_group_rebalance
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81f778cf)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout
```
```
In net/ipv4/ipmr.c (ffffffff81f8109f)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/syncookies.c (ffffffff81f844e2)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f8952a)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f8d771)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff81f97f4f)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81faba21)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_create_addr
```
```
In net/ipv6/af_inet6.c (ffffffff81fb2434)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_net_init
```
```
In net/ipv6/anycast.c (ffffffff81fb3879)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81fc1737)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/route.c (ffffffff81fcd011)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_dst_gc
  - net/ipv6/route.c:ip6_dst_gc
```
```
In net/ipv6/ip6_fib.c (ffffffff81fdd9bf)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_info_alloc
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81fe09a6)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
```
```
In net/ipv6/mcast.c (ffffffff81ff61c5)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/exthdrs.c (ffffffff82002475)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff82005357)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/ip6mr.c (ffffffff8200f981)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/calipso.c (ffffffff8201828d)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff82020466)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
```
```
In net/packet/af_packet.c (ffffffff8202a097)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
```
```
In net/devlink/leftover.c (ffffffff8203e942)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_nl_cmd_rate_new_doit
```
```
In net/devlink/core.c (ffffffff820420ed)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/devlink/core.c:devlink_alloc_ns
```
```
In net/xdp/xdp_umem.c (ffffffff8206c4af)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
```
In net/xdp/xsk_buff_pool.c (ffffffff8206dd37)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_map
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
```
```
In net/mctp/device.c (ffffffff8208e3a8)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_add_dev
```
```
In net/mctp/route.c (ffffffff8208f8c1)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_route_add
  - net/mctp/route.c:mctp_key_alloc
```
```
In lib/klist.c (ffffffff820a1a47)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - lib/klist.c:klist_add_before
  - lib/klist.c:klist_add_behind
  - lib/klist.c:klist_add_tail
  - lib/klist.c:klist_add_head
```
```
In lib/kobject.c (ffffffff820a311e)
Location: include/linux/atomic/atomic-arch-fallback.h:490
Inline: True
Inline callers:
  - lib/kobject.c:kset_register
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
In arch/x86/kernel/ioport.c (ffffffff81058fac)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/tboot.c (ffffffff838cd78f)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81080ff5)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:mce_start
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81085907)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff81098fec)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_open
```
```
In arch/x86/kernel/reboot.c (ffffffff810a2847)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:nmi_shootdown_cpus
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810a6cad)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In arch/x86/kernel/kgdb.c (ffffffff810bd5cd)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_arch_handle_exception
  - arch/x86/kernel/kgdb.c:kgdb_arch_handle_exception
```
```
In arch/x86/mm/init_64.c (ffffffff8222befa)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff838f977a)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_dump_state
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/fork.c (ffffffff810f98bb)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/fork.c:copy_signal
  - kernel/fork.c:copy_signal
  - kernel/fork.c:copy_sighand
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
```
```
In kernel/cpu.c (ffffffff838fac2a)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_hotplug_init
```
```
In kernel/softirq.c (ffffffff811080e5)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_init
  - kernel/softirq.c:tasklet_setup
```
```
In kernel/user.c (ffffffff81112db1)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/workqueue.c (ffffffff8112fb08)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
```
```
In kernel/pid.c (ffffffff81130df2)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/nsproxy.c (ffffffff8113bda1)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/ucount.c (ffffffff81142860)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/ucount.c:alloc_ucounts
```
```
In kernel/groups.c (ffffffff81143ae3)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
```
```
In kernel/sched/core.c (ffffffff838fdf96)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:affine_move_task
```
```
In kernel/sched/fair.c (ffffffff81161d46)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/sched/build_utility.c (ffffffff8119021d)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/sched/build_utility.c:autogroup_init
  - kernel/sched/build_utility.c:membarrier_exec_mmap
  - kernel/sched/build_utility.c:psi_trigger_destroy
  - kernel/sched/build_utility.c:psi_trigger_create
  - kernel/sched/build_utility.c:psi_group_change
  - kernel/sched/build_utility.c:poll_timer_fn
  - kernel/sched/build_utility.c:psi_rtpoll_work
  - kernel/sched/build_utility.c:psi_rtpoll_work
  - kernel/sched/build_utility.c:group_init
  - kernel/sched/build_utility.c:sched_core_share_pid
  - kernel/sched/build_utility.c:sd_init
  - kernel/sched/build_utility.c:init_defrootdomain
  - kernel/sched/build_utility.c:cpupri_init
```
```
In kernel/locking/mutex.c (ffffffff8119bc24)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff8119c5bc)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:__init_rwsem
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8119cf9c)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
```
```
In kernel/power/swap.c (ffffffff811a8f83)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:save_image
```
```
In kernel/printk/nbcon.c (ffffffff811b3c65)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/printk/nbcon.c:nbcon_free
  - kernel/printk/nbcon.c:nbcon_init
```
```
In kernel/irq/manage.c (ffffffff811b820d)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/rcu/update.c (ffffffff811cd1a1)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
```
```
In kernel/rcu/srcutree.c (ffffffff811d0d8e)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
```
```
In kernel/rcu/tree.c (ffffffff811d46fe)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kfree_rcu_shrink_count
  - kernel/rcu/tree.c:fill_page_cache_func
  - kernel/rcu/tree.c:fill_page_cache_func
  - kernel/rcu/tree.c:kfree_rcu_monitor
  - kernel/rcu/tree.c:kfree_rcu_monitor
  - kernel/rcu/tree.c:kfree_rcu_monitor
```
```
In kernel/module/main.c (ffffffff811f53f9)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/module/main.c:load_module
```
```
In kernel/time/namespace.c (ffffffff8121de79)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/futex/core.c (ffffffff83905a39)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_init
```
```
In kernel/futex/pi.c (ffffffff81221902)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/futex/pi.c:refill_pi_state_cache
```
```
In kernel/kexec_core.c (ffffffff8122b814)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/kexec_core.c:__crash_shrink_memory
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/cgroup/cgroup.c (ffffffff81233095)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff8123f91c)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff8124f8a5)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/utsname.c:clone_uts_ns
```
```
In kernel/user_namespace.c (ffffffff81251805)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff8125274d)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/stop_machine.c (ffffffff81254271)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_core_cpuslocked
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:cpu_stop_init_done
```
```
In kernel/audit_watch.c (ffffffff8126239e)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_init_watch
```
```
In kernel/audit_tree.c (ffffffff81263af1)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_tree
```
```
In kernel/debug/debug_core.c (ffffffff8126af29)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff812715cf)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
```
```
In kernel/hung_task.c (ffffffff81277b95)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/hung_task.c:reset_hung_task_detector
```
```
In kernel/seccomp.c (ffffffff8127bef6)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In kernel/relay.c (ffffffff8127e5db)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/relay.c:relay_open
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/trace.c (ffffffff81297eb0)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/trace/tracing_map.c (ffffffff812aba7d)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_create
  - kernel/trace/tracing_map.c:tracing_map_clear
```
```
In kernel/trace/blktrace.c (ffffffff812baa33)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
```
In kernel/trace/fgraph.c (ffffffff812bdb80)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/fgraph.c:ftrace_graph_init_task
```
```
In kernel/trace/trace_events.c (ffffffff812c363a)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_add_event_call
  - kernel/trace/trace_events.c:trace_create_new_event
  - kernel/trace/trace_events.c:trace_create_new_event
```
```
In kernel/trace/trace_events_user.c (ffffffff812e326a)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_parse
  - kernel/trace/trace_events_user.c:user_event_parse
  - kernel/trace/trace_events_user.c:user_event_mm_alloc
  - kernel/trace/trace_events_user.c:user_event_mm_alloc
  - kernel/trace/trace_events_user.c:delayed_destroy_user_event
```
```
In kernel/trace/trace_dynevent.c (ffffffff812f3d37)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/trace/trace_dynevent.c:trace_event_dyn_put_ref
```
```
In kernel/irq_work.c (ffffffff81303147)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_single
```
```
In kernel/bpf/syscall.c (ffffffff8131174f)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
```
In kernel/bpf/helpers.c (ffffffff813431ac)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_obj_new_impl
```
```
In kernel/bpf/hashtab.c (ffffffff8134f9d9)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:__bpf_hash_map_seq_show
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
```
```
In kernel/bpf/arraymap.c (ffffffff813514dc)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:__bpf_array_map_seq_show
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
```
```
In kernel/bpf/local_storage.c (ffffffff81356a2e)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
```
```
In kernel/bpf/ringbuf.c (ffffffff81357f2a)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
```
```
In kernel/bpf/trampoline.c (ffffffff8135d33a)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_lookup
```
```
In kernel/bpf/btf.c (ffffffff81361129)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse
```
```
In kernel/bpf/memalloc.c (ffffffff81372c68)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_refill
  - kernel/bpf/memalloc.c:__free_by_rcu
  - kernel/bpf/memalloc.c:__free_rcu_tasks_trace
```
```
In kernel/bpf/dispatcher.c (ffffffff81373dda)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff813858c4)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_sys_lookup_elem
```
```
In kernel/bpf/cpumask.c (ffffffff813862db)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_create
```
```
In kernel/events/core.c (ffffffff8391117a)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:find_get_pmu_context
  - kernel/events/core.c:find_get_pmu_context
  - kernel/events/core.c:alloc_perf_context
```
```
In kernel/events/ring_buffer.c (ffffffff813a637f)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
  - kernel/events/ring_buffer.c:perf_output_put_handle
```
```
In kernel/events/uprobes.c (ffffffff813ac6a6)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
  - kernel/events/uprobes.c:alloc_uprobe
```
```
In kernel/padata.c (ffffffff813ae349)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
```
```
In kernel/jump_label.c (ffffffff813afa79)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
```
In kernel/watch_queue.c (ffffffff813b36cb)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_init
  - kernel/watch_queue.c:init_watch
```
```
In mm/filemap.c (ffffffff813b4ec5)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/vmscan.c (ffffffff813e2000)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
```
```
In mm/shrinker.c (ffffffff813e3abe)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - mm/shrinker.c:shrinker_register
```
```
In mm/shmem.c (0)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
```
```
In mm/backing-dev.c (ffffffff813f63a6)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_init
  - mm/backing-dev.c:wb_init
```
```
In mm/mm_init.c (ffffffff8222eb52)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - mm/mm_init.c:memmap_init_range
  - mm/mm_init.c:memmap_init_range
  - mm/mm_init.c:init_unavailable_range
  - mm/mm_init.c:init_unavailable_range
```
```
In mm/rmap.c (ffffffff8143c0c4)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - mm/rmap.c:hugetlb_add_new_anon_rmap
  - mm/rmap.c:folio_add_new_anon_rmap
  - mm/rmap.c:folio_add_new_anon_rmap
  - mm/rmap.c:folio_add_new_anon_rmap
  - mm/rmap.c:folio_add_new_anon_rmap
  - mm/rmap.c:folio_add_new_anon_rmap
  - mm/rmap.c:anon_vma_ctor
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/page_alloc.c (ffffffff8144faf9)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__rmqueue_pcplist
  - mm/page_alloc.c:split_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:prep_compound_page
  - mm/page_alloc.c:prep_compound_page
  - mm/page_alloc.c:prep_compound_page
  - mm/page_alloc.c:bad_page
```
```
In mm/madvise.c (ffffffff81461e50)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - mm/madvise.c:anon_vma_name_alloc
```
```
In mm/swap_state.c (ffffffff8146664b)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
  - mm/swap_state.c:swap_cluster_readahead
```
```
In mm/zswap.c (ffffffff8146e617)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff8391ac13)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - mm/hugetlb.c:gather_bootmem_prealloc
  - mm/hugetlb.c:gather_bootmem_prealloc
  - mm/hugetlb.c:gather_bootmem_prealloc
  - mm/hugetlb.c:__prep_compound_gigantic_folio
  - mm/hugetlb.c:__prep_compound_gigantic_folio
  - mm/hugetlb.c:__prep_compound_gigantic_folio
  - mm/hugetlb.c:__prep_compound_gigantic_folio
  - mm/hugetlb.c:__destroy_compound_gigantic_folio
  - mm/hugetlb.c:__destroy_compound_gigantic_folio
  - mm/hugetlb.c:__destroy_compound_gigantic_folio
  - mm/hugetlb.c:__destroy_compound_gigantic_folio
  - mm/hugetlb.c:resv_map_alloc
```
```
In mm/mempolicy.c (ffffffff81482e4f)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mpol_new
```
```
In mm/kfence/core.c (ffffffff8149369f)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
```
```
In mm/memory-tiers.c (ffffffff8149afa1)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - mm/memory-tiers.c:alloc_memory_type
```
```
In mm/huge_memory.c (ffffffff814a30b9)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - mm/huge_memory.c:mm_get_huge_zero_page
```
```
In mm/memcontrol.c (ffffffff814b4e3f)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
```
```
In mm/zpool.c (ffffffff814caa79)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - mm/zpool.c:zpool_register_driver
```
```
In mm/zsmalloc.c (ffffffff814cc0b2)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/memremap.c (ffffffff814d4eda)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
  - mm/memremap.c:free_zone_device_page
```
```
In mm/page_reporting.c (ffffffff814d8697)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_register
  - mm/page_reporting.c:page_reporting_process
  - mm/page_reporting.c:page_reporting_cycle
```
```
In mm/bootmem_info.c (ffffffff814d88ab)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In fs/super.c (ffffffff814e52ce)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - fs/super.c:alloc_super
```
```
In fs/exec.c (ffffffff814eab7e)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - fs/exec.c:unshare_sighand
```
```
In fs/namei.c (ffffffff814f187f)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - fs/namei.c:getname_kernel
```
```
In fs/dcache.c (ffffffff8150483b)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
```
```
In fs/inode.c (ffffffff81508953)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
```
```
In fs/file.c (ffffffff8150f1b8)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - fs/file.c:dup_fd
```
```
In fs/namespace.c (ffffffff815135f5)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fsopen.c (ffffffff8153aacb)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - fs/fsopen.c:fscontext_alloc_log
```
```
In fs/mnt_idmapping.c (ffffffff8153bb2f)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - fs/mnt_idmapping.c:alloc_mnt_idmap
```
```
In fs/notify/group.c (ffffffff81547ff5)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_alloc_group
  - fs/notify/group.c:fsnotify_alloc_group
```
```
In fs/notify/mark.c (ffffffff815487cb)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_init_mark
```
```
In fs/eventpoll.c (ffffffff81552e4a)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_create
```
```
In fs/eventfd.c (ffffffff81557994)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/userfaultfd.c (ffffffff81558035)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - fs/userfaultfd.c:new_userfaultfd
  - fs/userfaultfd.c:new_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/aio.c (ffffffff81560f12)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:exit_aio
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/crypto/keyring.c (ffffffff8156acf4)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
```
```
In fs/crypto/keysetup_v1.c (ffffffff8156d82d)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
```
```
In fs/backing-file.c (ffffffff815818ae)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
```
```
In fs/mbcache.c (ffffffff81582546)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/posix_acl.c (ffffffff81583974)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_from_mode
  - fs/posix_acl.c:posix_acl_clone
```
```
In fs/coredump.c (ffffffff8158545a)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - fs/coredump.c:coredump_wait
```
```
In fs/iomap/direct-io.c (ffffffff8158ef49)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
```
In fs/quota/dquot.c (ffffffff81592cda)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
```
```
In fs/proc/generic.c (ffffffff815aa03d)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/kernfs/inode.c (ffffffff815b9473)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff815ba5fe)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/kernfs/file.c (ffffffff815bdc5e)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_open
```
```
In fs/configfs/dir.c (ffffffff815c25c1)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_new_dirent
  - fs/configfs/dir.c:new_fragment
```
```
In fs/configfs/item.c (ffffffff815c637c)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/ext4/mballoc.c (ffffffff8160520d)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_init
```
```
In fs/ext4/page-io.c (ffffffff81612b7b)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_init_io_end
```
```
In fs/ext4/super.c (ffffffff8163c251)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_inode
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/fast_commit.c (ffffffff81646905)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_init_inode
```
```
In fs/ext4/orphan.c (ffffffff81649d71)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_init_orphan_info
```
```
In fs/jbd2/transaction.c (ffffffff8164cce9)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff8165afdf)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/ecryptfs/main.c (ffffffff8167d42b)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In fs/ecryptfs/super.c (ffffffff8167d7a4)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - fs/ecryptfs/super.c:ecryptfs_alloc_inode
```
```
In fs/ecryptfs/miscdev.c (ffffffff83926c45)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev
```
```
In fs/fuse/dev.c (ffffffff8168acc3)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_alloc
```
```
In fs/fuse/file.c (ffffffff81699564)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff8169d83a)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_sync_bucket_alloc
  - fs/fuse/inode.c:fuse_iget
```
```
In fs/fuse/dax.c (ffffffff816a3ef0)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
```
```
In fs/debugfs/file.c (ffffffff816a7435)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_atomic_t_set
  - fs/debugfs/file.c:debugfs_file_get
```
```
In fs/tracefs/event_inode.c (ffffffff816abe29)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - fs/tracefs/event_inode.c:eventfs_create_events_dir
  - fs/tracefs/event_inode.c:eventfs_create_dir
```
```
In ipc/util.c (ffffffff816b1395)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In ipc/sem.c (ffffffff816b99d0)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:find_alloc_undo
```
```
In ipc/namespace.c (ffffffff816c193b)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
```
```
In security/keys/key.c (ffffffff816c3d3c)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
  - security/keys/key.c:key_user_lookup
  - security/keys/key.c:key_user_lookup
```
```
In security/selinux/avc.c (ffffffff816e1fad)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - security/selinux/avc.c:selinux_avc_init
  - security/selinux/avc.c:selinux_avc_init
```
```
In security/selinux/ss/services.c (ffffffff81709249)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
```
In security/smack/smack_access.c (ffffffff817161c5)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_populate_secattr
```
```
In security/tomoyo/condition.c (ffffffff81723d9c)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_commit_condition
```
```
In security/tomoyo/gc.c (ffffffff8172a523)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_collect_entry
  - security/tomoyo/gc.c:tomoyo_collect_entry
  - security/tomoyo/gc.c:tomoyo_collect_entry
```
```
In security/tomoyo/memory.c (ffffffff8172b3d3)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/apparmor/apparmorfs.c (ffffffff81734a9d)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/audit.c (ffffffff81737288)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_dup_audit_data
```
```
In security/apparmor/lib.c (ffffffff8173a3c9)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff8173b075)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy.c (ffffffff81743a8a)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_alloc_pdb
```
```
In security/apparmor/policy_unpack.c (ffffffff817499ba)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/policy_ns.c (ffffffff81755df8)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:alloc_ns
```
```
In security/apparmor/label.c (ffffffff8175842c)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In security/apparmor/notify.c (ffffffff817658e9)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - security/apparmor/notify.c:aa_new_listener
  - security/apparmor/notify.c:aa_new_listener
```
```
In security/landlock/object.c (ffffffff8176b147)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - security/landlock/object.c:landlock_create_object
```
```
In security/landlock/ruleset.c (ffffffff8176bdd7)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:landlock_create_ruleset
```
```
In security/integrity/ima/ima_policy.c (ffffffff8392f14a)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_init_policy
```
```
In crypto/api.c (ffffffff8177f7e8)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - crypto/api.c:__crypto_alloc_tfmgfp
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In crypto/algapi.c (ffffffff817802a3)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_check_alg
```
```
In block/fops.c (ffffffff817a9df6)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
```
```
In block/bio.c (ffffffff817ac0e5)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - block/bio.c:bio_init_clone
  - block/bio.c:bio_init_clone
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_reset
```
```
In block/blk-core.c (ffffffff817b3d18)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - block/blk-core.c:blk_alloc_queue
  - block/blk-core.c:blk_alloc_queue
```
```
In block/blk-flush.c (ffffffff817b703c)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-ioc.c (ffffffff817b8bff)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - block/blk-ioc.c:alloc_io_context
```
```
In block/blk-mq.c (ffffffff817c37f9)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_hctx
```
```
In block/bsg-lib.c (ffffffff817e2209)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In block/blk-cgroup.c (ffffffff817e4538)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In block/blk-iocost.c (ffffffff817f0bb5)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
```
```
In block/blk-wbt.c (ffffffff817ff720)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
```
```
In block/blk-crypto-profile.c (ffffffff81808ada)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
```
```
In io_uring/io_uring.c (ffffffff81813dca)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:__io_arm_ltimeout
  - io_uring/io_uring.c:__io_arm_ltimeout
  - io_uring/io_uring.c:io_ring_ctx_alloc
```
```
In io_uring/timeout.c (ffffffff8181df06)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - io_uring/timeout.c:io_timeout_fn
  - io_uring/timeout.c:io_flush_timeouts
```
```
In io_uring/sqpoll.c (ffffffff8181f452)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_get_sq_data
  - io_uring/sqpoll.c:io_get_sq_data
```
```
In io_uring/tctx.c (ffffffff8182103a)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - io_uring/tctx.c:io_uring_alloc_task_context
  - io_uring/tctx.c:io_uring_alloc_task_context
  - io_uring/tctx.c:io_uring_alloc_task_context
```
```
In io_uring/poll.c (ffffffff818229eb)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - io_uring/poll.c:__io_arm_poll_handler
```
```
In io_uring/rsrc.c (ffffffff8182664c)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_rsrc_ref_quiesce
  - io_uring/rsrc.c:io_rsrc_ref_quiesce
```
```
In io_uring/notif.c (ffffffff8182a502)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - io_uring/notif.c:io_alloc_notif
```
```
In io_uring/waitid.c (ffffffff8182ac83)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - io_uring/waitid.c:io_waitid
```
```
In io_uring/register.c (ffffffff8182afdd)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - io_uring/register.c:io_eventfd_register
  - io_uring/register.c:io_eventfd_register
```
```
In io_uring/io-wq.c (ffffffff8182e6ec)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_create
  - io_uring/io-wq.c:io_wq_create
  - io_uring/io-wq.c:create_io_worker
```
```
In lib/rhashtable.c (ffffffff8185e230)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
```
```
In lib/refcount.c (ffffffff8186000b)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_and_lock_irqsave
  - lib/refcount.c:refcount_dec_and_lock
  - lib/refcount.c:refcount_dec_and_mutex_lock
```
```
In lib/rcuref.c (ffffffff8186011d)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - lib/rcuref.c:rcuref_put_slowpath
  - lib/rcuref.c:rcuref_put_slowpath
  - lib/rcuref.c:rcuref_get_slowpath
  - lib/rcuref.c:rcuref_get_slowpath
```
```
In lib/cpu_rmap.c (ffffffff81925523)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In lib/closure.c (ffffffff8223bf77)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - lib/closure.c:__closure_sync
  - lib/closure.c:__closure_wake_up
  - lib/closure.c:closure_put
```
```
In lib/stackdepot.c (ffffffff81928287)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - lib/stackdepot.c:depot_alloc_stack
  - lib/stackdepot.c:depot_alloc_stack
```
```
In lib/sbitmap.c (ffffffff8192c276)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_wake_up
  - lib/sbitmap.c:sbitmap_queue_init_node
  - lib/sbitmap.c:sbitmap_queue_init_node
  - lib/sbitmap.c:sbitmap_queue_init_node
  - lib/sbitmap.c:sbitmap_queue_init_node
```
```
In drivers/pinctrl/core.c (ffffffff819360bd)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff81951b46)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_create
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff819a4c4a)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/rapidio/rio.c (ffffffff819b908d)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/rapidio/rio.c:rio_mport_initialize
  - drivers/rapidio/rio.c:rio_del_device
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff819c409b)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
```
```
In drivers/acpi/ec.c (ffffffff819f76d0)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/acpi/thermal.c (ffffffff81a6d155)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a7b8c4)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
```
```
In drivers/clk/clk.c (ffffffff81a90774)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dma/dmaengine.c (ffffffff81a98ff8)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/pmdomain/core.c (ffffffff81aa1988)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/pmdomain/core.c:pm_genpd_init
```
```
In drivers/xen/balloon.c (ffffffff81ab6de7)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_thread
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81ac6fa3)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (ffffffff81ae3329)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (ffffffff81ae9864)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_buffer.c (ffffffff81af2181)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_init
  - drivers/tty/tty_buffer.c:tty_buffer_init
```
```
In drivers/tty/tty_port.c (ffffffff81af25c2)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/tty/serial/serial_core.c (ffffffff81b15eed)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:serial_core_add_one_port
```
```
In drivers/char/random.c (ffffffff81b339b1)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/char/random.c:try_to_generate_entropy
```
```
In drivers/char/virtio_console.c (ffffffff81b367e8)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
```
```
In drivers/char/hw_random/core.c (ffffffff81b3a624)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
```
```
In drivers/char/agp/backend.c (ffffffff81b3bd73)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_alloc_bridge
  - drivers/char/agp/backend.c:agp_alloc_bridge
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b7c14d)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_init_fq
  - drivers/iommu/dma-iommu.c:fq_flush_timeout
```
```
In drivers/iommu/iommu-sva.c (ffffffff81b81080)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva.c:iommu_sva_bind_device
```
```
In drivers/connector/cn_queue.c (ffffffff81b82129)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_alloc_dev
  - drivers/connector/cn_queue.c:cn_queue_alloc_callback_entry
```
```
In drivers/base/core.c (ffffffff81b8ab3d)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff81ba8d46)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/base/power/runtime.c:pm_runtime_init
```
```
In drivers/base/power/wakeup.c (ffffffff81baf960)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_wakeup_clear
```
```
In drivers/base/firmware_loader/main.c (ffffffff81bb2f85)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv
```
```
In drivers/block/loop.c (ffffffff81bd053e)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
```
```
In drivers/nvdimm/core.c (ffffffff81bf63cc)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:alloc_nvdimm_map
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81bfa659)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
```
```
In drivers/nvdimm/dimm.c (ffffffff81bfbf33)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
```
```
In drivers/dax/bus.c (ffffffff81c0f554)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81c13a8e)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81c149e0)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81c19dbe)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_create
```
```
In drivers/scsi/scsi.c (ffffffff81c1e108)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/hosts.c (ffffffff81c1f726)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c2a32b)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
```
In drivers/scsi/scsi_scan.c (ffffffff81c2c50e)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sd.c (ffffffff81c3fcc5)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/scsi/sg.c (ffffffff81c4b3cd)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_alloc
```
```
In drivers/ata/libata-core.c (ffffffff81c4fe74)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/gpu/drm/drm_atomic.c (ffffffff81c7b275)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_state_init
```
```
In drivers/gpu/drm/drm_auth.c (ffffffff81c7e897)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_auth.c:drm_master_create
```
```
In drivers/gpu/drm/drm_connector.c (ffffffff81c87331)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_connector.c:drm_mode_create_tile_group
```
```
In drivers/gpu/drm/drm_drv.c (ffffffff81c8b7e2)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_drv.c:drm_dev_init
```
```
In drivers/gpu/drm/drm_gem.c (ffffffff81c9b73c)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem.c:drm_gem_private_object_init
```
```
In drivers/gpu/drm/drm_mode_object.c (ffffffff81ca3e70)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
```
```
In drivers/gpu/drm/drm_syncobj.c (ffffffff81cafd80)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_create
```
```
In drivers/gpu/drm/drm_atomic_helper.c (ffffffff81cc3ed1)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_setup_commit
```
```
In drivers/net/phy/phy_device.c (ffffffff81cf03c0)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_package_join
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81cf5c11)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/pse-pd/pse_core.c (0)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d18c6c)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/usb/core/usb.c (ffffffff81d2d8cb)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
```
```
In drivers/usb/core/hub.c (ffffffff81d38419)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff81d3a2b4)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff81d3cf9f)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_init_urb
```
```
In drivers/usb/core/config.c (ffffffff81d4622e)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/thermal/thermal_core.c (ffffffff81dff17a)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/thermal/thermal_core.c:thermal_bind_cdev_to_trip
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81e09ee4)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
```
```
In drivers/md/md.c (ffffffff81e20069)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_run
  - drivers/md/md.c:max_corrected_read_errors_store
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:errors_store
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:submit_flushes
```
```
In drivers/md/md-bitmap.c (ffffffff81e28801)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In drivers/md/dm.c (ffffffff81e2e938)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:dm_get_table_device
  - drivers/md/dm.c:alloc_io
```
```
In drivers/md/dm-table.c (ffffffff8222b336)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/md/dm-stripe.c (ffffffff81e366fb)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/md/dm-io.c (ffffffff81e3b233)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff81e3bc10)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
```
In drivers/md/dm-stats.c (ffffffff81e3dd98)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
```
```
In drivers/edac/ghes_edac.c (ffffffff81e467ec)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
```
```
In drivers/opp/core.c (ffffffff81e4bd96)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
  - drivers/opp/core.c:_add_opp_table_indexed
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81e55f78)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
  - drivers/cpufreq/cpufreq_governor.c:dbs_work_handler
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff81e7f701)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
```
```
In drivers/firmware/efi/efi.c (ffffffff8222b494)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e9aeca)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
```
```
In drivers/devfreq/devfreq.c (ffffffff81ea5394)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/nvmem/core.c (ffffffff81eb1bef)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
```
```
In drivers/hte/hte.c (ffffffff81eb618a)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/hte/hte.c:hte_ts_put
```
```
In drivers/dpll/dpll_core.c (ffffffff81eb6bad)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - drivers/dpll/dpll_core.c:dpll_pin_get
  - drivers/dpll/dpll_core.c:dpll_device_get
  - drivers/dpll/dpll_core.c:dpll_xa_ref_dpll_add
  - drivers/dpll/dpll_core.c:dpll_xa_ref_pin_add
```
```
In net/core/sock.c (ffffffff81ec586b)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data_uid
  - net/core/sock.c:sock_init_data_uid
  - net/core/sock.c:sock_init_data_uid
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sock_set_timestamping
  - net/core/sock.c:sock_set_timestamping
  - net/core/sock.c:sock_set_timestamping
```
```
In net/core/skbuff.c (ffffffff81ed0c6f)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_maybe_cow
  - net/core/skbuff.c:__skb_ext_alloc
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:slab_build_skb
  - net/core/skbuff.c:slab_build_skb
```
```
In net/core/net_namespace.c (ffffffff81ee3ce4)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:setup_net
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff81eeda5d)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/core/dev.c:dev_kfree_skb_irq_reason
```
```
In net/core/dst.c (ffffffff81f03b67)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
  - net/core/dst.c:dst_cow_metrics_generic
  - net/core/dst.c:dst_alloc
```
```
In net/core/neighbour.c (ffffffff81f08355)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/filter.c (ffffffff81f3231c)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
```
```
In net/core/flow_offload.c (ffffffff81f3ac06)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_register
```
```
In net/core/gro.c (ffffffff81f3ccfe)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/core/gro.c:skb_gro_receive
```
```
In net/core/page_pool.c (ffffffff81f432a8)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_init
  - net/core/page_pool.c:page_pool_init
```
```
In net/core/netpoll.c (ffffffff81f47e04)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/core/fib_rules.c (ffffffff81f49eda)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_default_rule_add
```
```
In net/core/skmsg.c (ffffffff81f65f66)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/sched/sch_generic.c (ffffffff81f70720)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/sched/cls_api.c (ffffffff81f7e82d)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/sched/act_api.c (ffffffff81f8102f)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
```
```
In net/ipv4/route.c (ffffffff81faf0b5)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_genid_init
  - net/ipv4/route.c:rt_genid_init
  - net/ipv4/route.c:rt_genid_init
```
```
In net/ipv4/inetpeer.c (ffffffff81fb73f3)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (ffffffff81fc003f)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81fc84c6)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fcb1e8)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp.c (ffffffff81fcfcc2)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81fd8fa3)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_output.c (ffffffff81fe506d)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_clone_payload
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff1431)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_init
  - net/ipv4/tcp_ipv4.c:tcp_sk_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ffea8b)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/datagram.c (ffffffff82000b15)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (0)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff82017b0f)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
```
```
In net/ipv4/af_inet.c (ffffffff82019b21)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff8201fe37)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv4/fib_frontend.c (ffffffff82022922)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff82028ea1)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_rebalance
```
```
In net/ipv4/inet_fragment.c (ffffffff820312ee)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/ipv4/metrics.c (ffffffff82036e92)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff8203dcc5)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:nh_hthr_group_rebalance
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8203dfaf)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout
```
```
In net/ipv4/ipmr.c (ffffffff8204771f)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/syncookies.c (ffffffff8204ae8d)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/tcp_sigpool.c (ffffffff8204cf53)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_alloc_ahash
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_alloc_ahash
```
```
In net/ipv4/cipso_ipv4.c (ffffffff82050c8a)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/ipv4/tcp_ao.c (ffffffff8205438d)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/ipv4/tcp_ao.c:tcp_ao_alloc_info
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205b118)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff820652bf)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
```
```
In net/unix/af_unix.c (ffffffff82078e40)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_create_addr
```
```
In net/ipv6/af_inet6.c (ffffffff8207fbc4)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_net_init
```
```
In net/ipv6/anycast.c (ffffffff8208111e)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff8208ec6f)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/route.c (ffffffff8209a826)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_dst_gc
  - net/ipv6/route.c:ip6_dst_gc
```
```
In net/ipv6/ip6_fib.c (ffffffff820ab03d)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_metric_set
  - net/ipv6/ip6_fib.c:fib6_info_alloc
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff820aefb9)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
```
```
In net/ipv6/mcast.c (ffffffff820c3e04)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/exthdrs.c (ffffffff820d1275)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff820d4159)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/ip6mr.c (ffffffff820de911)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/calipso.c (ffffffff820e725d)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff820ef599)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
```
```
In net/packet/af_packet.c (ffffffff820f9b95)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
```
```
In net/devlink/core.c (ffffffff820fec27)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/devlink/core.c:devlink_alloc_ns
  - net/devlink/core.c:devlink_rel_nested_in_add
```
```
In net/devlink/rate.c (ffffffff82119501)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/devlink/rate.c:devlink_nl_rate_new_doit
```
```
In net/xdp/xdp_umem.c (ffffffff821402ad)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
```
In net/xdp/xsk_buff_pool.c (ffffffff82141db6)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_map
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
```
```
In net/mctp/device.c (ffffffff8216489b)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_add_dev
```
```
In net/mctp/route.c (ffffffff82165dd0)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_route_add
  - net/mctp/route.c:mctp_key_alloc
```
```
In lib/klist.c (ffffffff82179ac7)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - lib/klist.c:klist_add_before
  - lib/klist.c:klist_add_behind
  - lib/klist.c:klist_add_tail
  - lib/klist.c:klist_add_head
```
```
In lib/kobject.c (ffffffff8217b199)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - lib/kobject.c:kset_register
```
```
In lib/objpool.c (ffffffff82191cf2)
Location: include/linux/atomic/atomic-arch-fallback.h:501
Inline: True
Inline callers:
  - lib/objpool.c:objpool_init
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

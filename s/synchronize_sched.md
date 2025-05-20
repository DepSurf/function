# Function: <code>synchronize_sched</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void synchronize_sched();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810e62c0)
Location: kernel/rcu/tree.c:3201
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_chrdev_read
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - kernel/cpu.c:_cpu_down
  - kernel/notifier.c:atomic_notifier_chain_unregister
  - kernel/printk/printk.c:kmsg_dump_unregister
  - kernel/rcu/sync.c:synchronize_rcu
  - kernel/rcu/tree.c:cond_synchronize_sched
  - kernel/module.c:free_module
  - kernel/module.c:do_init_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/kprobes.c:collect_garbage_slots
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/trace/ftrace.c:__unregister_ftrace_function_probe
  - kernel/trace/ring_buffer.c:ring_buffer_read_prepare_sync
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/trace.c:tracing_reset
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_trigger.c:trigger_data_free
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/padata.c:padata_replace
  - kernel/membarrier.c:SyS_membarrier
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - fs/file.c:expand_files
  - fs/filesystems.c:unregister_filesystem
  - fs/namespace.c:replace_mount_options
  - fs/namespace.c:namespace_unlock
  - fs/fs-writeback.c:cgroup_writeback_umount
  - fs/eventpoll.c:ep_destroy_wakeup_source
  - security/keys/gc.c:key_garbage_collector
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_onlycap
  - security/apparmor/policy.c:__replace_profile
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/tty/sysrq.c:__sysrq_swap_key_ops
  - drivers/iommu/dmar.c:dmar_hp_release_drhd
  - drivers/iommu/intel-iommu.c:dmar_release_one_atsr
  - drivers/base/power/wakeup.c:wakeup_source_remove
  - drivers/input/input.c:__input_release_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:input_close_device
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/mousedev.c:mousedev_detach_client
  - drivers/input/evdev.c:evdev_detach_client
  - drivers/input/evdev.c:evdev_release
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/i2c/i2c-core.c:i2c_exit
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
  - net/core/net_namespace.c:cleanup_net
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:dev_change_name
  - net/netfilter/core.c:nf_unregister_afinfo
  - net/netfilter/nf_log.c:nf_log_unset
  - net/netfilter/nf_log.c:nf_log_unregister
  - net/netfilter/nf_queue.c:nf_unregister_queue_handler
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
  - net/ipv4/fib_trie.c:tnode_free
  - net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/ipv6/raw.c:rawv6_mh_filter_unregister
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
ffffffff810e62c0-ffffffff810e633b: synchronize_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void synchronize_sched();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810eb300)
Location: kernel/rcu/tree.c:3279
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_chrdev_read
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
  - kernel/notifier.c:atomic_notifier_chain_unregister
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/printk/printk.c:kmsg_dump_unregister
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/sync.c:synchronize_rcu
  - kernel/rcu/tree.c:cond_synchronize_sched
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:collect_garbage_slots
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:__unregister_ftrace_function_probe
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_prepare_sync
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/trace.c:tracing_reset
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:trigger_data_free
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/padata.c:padata_replace
  - kernel/membarrier.c:SyS_membarrier
  - mm/zswap.c:__zswap_pool_release
  - mm/slub.c:__kmem_cache_shrink
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - fs/file.c:expand_files
  - fs/filesystems.c:unregister_filesystem
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:replace_mount_options
  - fs/fs-writeback.c:cgroup_writeback_umount
  - fs/eventpoll.c:ep_destroy_wakeup_source
  - security/keys/gc.c:key_garbage_collector
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_onlycap
  - security/apparmor/policy.c:__replace_profile
  - security/integrity/ima/ima_policy.c:ima_update_policy
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/tty/sysrq.c:__sysrq_swap_key_ops
  - drivers/iommu/dmar.c:dmar_hp_release_drhd
  - drivers/iommu/intel-iommu.c:dmar_release_one_atsr
  - drivers/base/power/wakeup.c:wakeup_source_remove
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_close_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:__input_release_device
  - drivers/input/mousedev.c:mousedev_detach_client
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_release
  - drivers/input/evdev.c:evdev_detach_client
  - drivers/i2c/i2c-core.c:i2c_exit
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/intel_pstate.c:intel_pstate_clear_update_util_hook
  - drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
  - net/core/net_namespace.c:cleanup_net
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:dev_change_name
  - net/netfilter/core.c:nf_unregister_afinfo
  - net/netfilter/nf_log.c:nf_log_unregister
  - net/netfilter/nf_log.c:nf_log_unset
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
  - net/ipv4/fib_trie.c:tnode_free
  - net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/ipv6/raw.c:rawv6_mh_filter_unregister
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
ffffffff810eb300-ffffffff810eb34e: synchronize_sched.part.63 (STB_LOCAL)
ffffffff810ec460-ffffffff810ec49b: synchronize_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void synchronize_sched();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f4d70)
Location: kernel/rcu/tree.c:3277
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_chrdev_read
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
  - kernel/notifier.c:atomic_notifier_chain_unregister
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - kernel/printk/printk.c:kmsg_dump_unregister
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/sync.c:synchronize_rcu
  - kernel/rcu/tree.c:cond_synchronize_sched
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:collect_garbage_slots
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:__unregister_ftrace_function_probe
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_prepare_sync
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/trace.c:tracing_reset
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:trigger_data_free
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/padata.c:padata_replace
  - kernel/membarrier.c:SyS_membarrier
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/zswap.c:__zswap_pool_release
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - fs/file.c:expand_files
  - fs/filesystems.c:unregister_filesystem
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:replace_mount_options
  - fs/fs-writeback.c:cgroup_writeback_umount
  - fs/eventpoll.c:ep_destroy_wakeup_source
  - security/keys/gc.c:key_garbage_collector
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_onlycap
  - security/apparmor/policy.c:__replace_profile
  - security/integrity/ima/ima_policy.c:ima_update_policy
  - block/blk-mq.c:blk_mq_quiesce_queue
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/tty/sysrq.c:__sysrq_swap_key_ops
  - drivers/iommu/dmar.c:dmar_hp_release_drhd
  - drivers/iommu/intel-iommu.c:dmar_release_one_atsr
  - drivers/base/power/wakeup.c:wakeup_source_remove
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_close_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:__input_release_device
  - drivers/input/mousedev.c:mousedev_detach_client
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_release
  - drivers/input/evdev.c:evdev_detach_client
  - drivers/i2c/i2c-core.c:i2c_exit
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/intel_pstate.c:intel_pstate_clear_update_util_hook
  - drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
  - net/core/net_namespace.c:cleanup_net
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:dev_change_name
  - net/netfilter/core.c:nf_unregister_afinfo
  - net/netfilter/nf_log.c:nf_log_unregister
  - net/netfilter/nf_log.c:nf_log_unset
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
  - net/ipv4/fib_trie.c:tnode_free
  - net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/ipv6/raw.c:rawv6_mh_filter_unregister
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
ffffffff810f4d70-ffffffff810f4dea: synchronize_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void synchronize_sched();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f5ab0)
Location: kernel/rcu/tree.c:3297
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_chrdev_read
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
  - kernel/notifier.c:atomic_notifier_chain_unregister
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - kernel/printk/printk.c:kmsg_dump_unregister
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/sync.c:synchronize_rcu
  - kernel/rcu/tree.c:cond_synchronize_rcu
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:collect_garbage_slots
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_prepare_sync
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/trace.c:tracing_reset
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:trigger_data_free
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/padata.c:padata_replace
  - kernel/membarrier.c:SyS_membarrier
  - mm/swap_state.c:exit_swap_address_space
  - mm/zswap.c:__zswap_pool_release
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - fs/file.c:expand_files
  - fs/filesystems.c:unregister_filesystem
  - fs/namespace.c:namespace_unlock
  - fs/fs-writeback.c:cgroup_writeback_umount
  - fs/eventpoll.c:ep_destroy_wakeup_source
  - security/keys/gc.c:key_garbage_collector
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_onlycap
  - security/apparmor/policy.c:__replace_profile
  - security/integrity/ima/ima_policy.c:ima_update_policy
  - block/blk-mq.c:blk_mq_free_queue
  - block/blk-mq.c:blk_mq_quiesce_queue
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/tty/sysrq.c:__sysrq_swap_key_ops
  - drivers/iommu/dmar.c:dmar_hp_release_drhd
  - drivers/iommu/intel-iommu.c:dmar_release_one_atsr
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_close_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:__input_release_device
  - drivers/input/mousedev.c:mousedev_detach_client
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_release
  - drivers/input/evdev.c:evdev_detach_client
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_del_device
  - drivers/edac/edac_pci.c:edac_pci_del_device
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/intel_pstate.c:intel_pstate_clear_update_util_hook
  - drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
  - net/core/net_namespace.c:cleanup_net
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:dev_change_name
  - net/netfilter/core.c:nf_unregister_afinfo
  - net/netfilter/nf_log.c:nf_log_unregister
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
  - net/ipv4/fib_trie.c:tnode_free
  - net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/ipv6/raw.c:rawv6_mh_filter_unregister
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
ffffffff810f5ab0-ffffffff810f5b2a: synchronize_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void synchronize_sched();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810ff8b0)
Location: kernel/rcu/tree.c:3280
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
  - kernel/notifier.c:atomic_notifier_chain_unregister
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - kernel/sched/membarrier.c:SyS_membarrier
  - kernel/printk/printk.c:kmsg_dump_unregister
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/sync.c:synchronize_rcu
  - kernel/rcu/tree.c:cond_synchronize_rcu
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
  - kernel/kprobes.c:collect_garbage_slots
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_prepare_sync
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/trace.c:tracing_reset
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:trigger_data_free
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/lpm_trie.c:trie_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/sockmap.c:sock_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/padata.c:padata_replace
  - kernel/memremap.c:pgmap_radix_release
  - mm/swap_state.c:exit_swap_address_space
  - mm/zswap.c:__zswap_pool_release
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - fs/file.c:expand_files
  - fs/filesystems.c:unregister_filesystem
  - fs/namespace.c:namespace_unlock
  - fs/fs-writeback.c:cgroup_writeback_umount
  - fs/eventpoll.c:ep_destroy_wakeup_source
  - security/keys/gc.c:key_garbage_collector
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_onlycap
  - security/apparmor/policy.c:__replace_profile
  - security/integrity/ima/ima_policy.c:ima_update_policy
  - block/blk-mq.c:blk_mq_free_queue
  - block/blk-mq.c:blk_mq_quiesce_queue
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/tty/sysrq.c:__sysrq_swap_key_ops
  - drivers/iommu/dmar.c:dmar_hp_release_drhd
  - drivers/iommu/intel-iommu.c:dmar_release_one_atsr
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_close_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:__input_release_device
  - drivers/input/mousedev.c:mousedev_detach_client
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_release
  - drivers/input/evdev.c:evdev_detach_client
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_del_device
  - drivers/edac/edac_pci.c:edac_pci_del_device
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/intel_pstate.c:intel_pstate_clear_update_util_hook
  - drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
  - net/core/net_namespace.c:cleanup_net
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:dev_change_name
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/netfilter/core.c:nf_unregister_afinfo
  - net/netfilter/nf_log.c:nf_log_unregister
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
  - net/ipv4/fib_trie.c:tnode_free
  - net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/ipv6/raw.c:rawv6_mh_filter_unregister
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
ffffffff810ff8b0-ffffffff810ff92a: synchronize_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void synchronize_sched();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81107240)
Location: kernel/rcu/tree.c:3086
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:unregister_nmi_handler
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
  - kernel/notifier.c:atomic_notifier_chain_unregister
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_global_expedited
  - kernel/printk/printk.c:kmsg_dump_unregister
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/sync.c:synchronize_rcu
  - kernel/rcu/tree.c:cond_synchronize_rcu
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
  - kernel/kprobes.c:collect_garbage_slots
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_prepare_sync
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/trace.c:tracing_reset
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:trigger_data_free
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/lpm_trie.c:trie_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/sockmap.c:sock_hash_free
  - kernel/bpf/sockmap.c:sock_map_free
  - kernel/bpf/stackmap.c:stack_map_free
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/padata.c:padata_replace
  - kernel/memremap.c:pgmap_radix_release
  - mm/swap_state.c:exit_swap_address_space
  - mm/zswap.c:__zswap_pool_release
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - fs/namespace.c:namespace_unlock
  - fs/fs-writeback.c:cgroup_writeback_umount
  - fs/eventpoll.c:ep_destroy_wakeup_source
  - security/keys/gc.c:key_garbage_collector
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_onlycap
  - security/apparmor/policy.c:__replace_profile
  - security/integrity/ima/ima_policy.c:ima_update_policy
  - block/blk-mq.c:blk_mq_free_queue
  - block/blk-mq.c:blk_mq_quiesce_queue
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/tty/sysrq.c:__sysrq_swap_key_ops
  - drivers/iommu/dmar.c:dmar_hp_release_drhd
  - drivers/iommu/intel-iommu.c:dmar_release_one_atsr
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/input/input.c:input_unregister_handle
  - drivers/input/input.c:input_close_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:__input_release_device
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
  - drivers/input/evdev.c:evdev_release
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_del_device
  - drivers/edac/edac_pci.c:edac_pci_del_device
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/intel_pstate.c:intel_pstate_clear_update_util_hook
  - drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler
  - drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete
  - net/core/net_namespace.c:cleanup_net
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:dev_change_name
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/netfilter/nf_log.c:nf_log_unregister
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
  - net/ipv4/fib_trie.c:tnode_free
  - net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/ipv6/raw.c:rawv6_mh_filter_unregister
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
```
**Symbols:**

```
ffffffff81107240-ffffffff811072d8: synchronize_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff810edb48)
Location: include/linux/rcupdate.h:922
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
```
</details>
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
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>

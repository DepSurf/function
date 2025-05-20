# Function: <code>arch_atomic_add_return</code>

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
In arch/x86/events/core.c (ffffffff810062fe)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015177)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81047fe4)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104d468)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_panic
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_panic
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff8104f4a5)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_intel_adjust_timer
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810812fa)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
```
In kernel/fork.c (ffffffff8108dddc)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/fork.c:walk_process_tree
```
```
In kernel/exit.c (ffffffff81092bb6)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:is_current_pgrp_orphaned
```
```
In kernel/resource.c (ffffffff81096fc5)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/resource.c:iomem_is_exclusive
  - kernel/resource.c:iomem_map_sanity_check
  - kernel/resource.c:lookup_resource
  - kernel/resource.c:region_intersects
  - kernel/resource.c:find_next_iomem_res
  - kernel/resource.c:r_stop
```
```
In kernel/ptrace.c (ffffffff8109a6b9)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff8109fbf8)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_kill
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:kill_pgrp
```
```
In kernel/sys.c (ffffffff810a75c7)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
```
```
In kernel/sched/core.c (ffffffff810c2877)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
```
```
In kernel/sched/topology.c (ffffffff810db8e5)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/sched/autogroup.c (ffffffff810dd417)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
```
In kernel/locking/spinlock.c (ffffffff819f1bc5)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
  - kernel/locking/spinlock.c:_raw_read_trylock
  - kernel/locking/spinlock.c:_raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock
```
```
In kernel/power/process.c (ffffffff810e8d83)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/irq/spurious.c (ffffffff810f923f)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (ffffffff810fd2e2)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/rcu/tree.c (ffffffff81104acf)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_nmi_exit
  - kernel/rcu/tree.c:rcu_idle_enter
  - kernel/rcu/tree.c:rcu_dynticks_momentary_idle
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
```
```
In kernel/livepatch/transition.c (ffffffff8110c57b)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_send_signals
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
```
```
In kernel/module.c (ffffffff8112e225)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/module.c:try_release_module_ref
```
```
In kernel/cgroup/cgroup.c (ffffffff811401c5)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_mount
```
```
In kernel/pid_namespace.c (ffffffff8114e05e)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/audit.c (ffffffff811502a1)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
```
```
In kernel/auditsc.c (ffffffff81157ac0)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_set_loginuid
  - kernel/auditsc.c:audit_set_loginuid
```
```
In kernel/tracepoint.c (ffffffff8116ffad)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/ftrace.c (ffffffff8117770f)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:register_ftrace_graph
  - kernel/trace/ftrace.c:profile_graph_entry
```
```
In kernel/trace/trace.c (ffffffff81186190)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
```
```
In kernel/trace/tracing_map.c (ffffffff81189edf)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_insert
```
```
In kernel/trace/trace_functions.c (ffffffff8118afb0)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8118bc78)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8118e96c)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (ffffffff8119318b)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff8119b1e0)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
```
```
In kernel/trace/trace_uprobe.c (ffffffff811ae59d)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In kernel/bpf/syscall.c (ffffffff811b35e5)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811c15e0)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/sockmap.c (ffffffff811cdbcf)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
```
```
In kernel/events/callchain.c (ffffffff811e3400)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/padata.c (ffffffff811e8204)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In kernel/memremap.c (ffffffff811e9345)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - kernel/memremap.c:dev_pagemap_get_ops
```
```
In mm/oom_kill.c (ffffffff811f3c50)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/vmalloc.c (ffffffff81241675)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/zswap.c (ffffffff8124f8b4)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/mempolicy.c (ffffffff8125cc08)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
```
```
In mm/memory_hotplug.c (ffffffff8126bc98)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/memcontrol.c (ffffffff81284c04)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/memory-failure.c (ffffffff81288db6)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
```
```
In mm/zsmalloc.c (ffffffff8128e74d)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/exec.c (ffffffff812a1849)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/exec.c:__x64_sys_uselib
```
```
In fs/fcntl.c (ffffffff812af39a)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - fs/fcntl.c:kill_fasync
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_getown
```
```
In fs/inode.c (ffffffff812b80a0)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
```
```
In fs/filesystems.c (ffffffff812bcefe)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:filesystems_proc_show
  - fs/filesystems.c:fs_maxindex
  - fs/filesystems.c:fs_name
  - fs/filesystems.c:fs_index
  - fs/filesystems.c:get_filesystem_list
```
```
In fs/fs_struct.c (ffffffff812d467b)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/notify/notification.c (ffffffff812e4cd5)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/coredump.c (ffffffff8130cd6d)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/netlink.c (ffffffff81316ab0)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In fs/proc/inode.c (ffffffff8131adeb)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_entry_rundown
  - fs/proc/inode.c:unuse_pde
```
```
In fs/proc/generic.c (ffffffff813202fa)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/proc/array.c (ffffffff81321225)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/proc/kcore.c (ffffffff81328f5f)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
```
```
In fs/kernfs/dir.c (ffffffff8132cc79)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_put_active
```
```
In fs/ext4/extents_status.c (ffffffff81343205)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_find_delayed_extent_range
```
```
In fs/ext4/inode.c (ffffffff8135a624)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_iget
```
```
In fs/ext4/super.c (ffffffff8137de38)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/jbd2/transaction.c (ffffffff813951e2)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:wait_transaction_locked
```
```
In fs/jbd2/journal.c (ffffffff813996ee)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_errno
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_transaction_committed
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
```
In fs/ecryptfs/main.c (ffffffff813b5c65)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/keys/keyring.c (ffffffff813e6a77)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/avc.c (ffffffff813f76ee)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/selinux/hooks.c (ffffffff813fad7e)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/selinux/ss/services.c (ffffffff81414973)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_read_policy
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_policycap_supported
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_get_bool_value
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_node_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_ib_endport_sid
  - security/selinux/ss/services.c:security_ib_pkey_sid
  - security/selinux/ss/services.c:security_port_sid
  - security/selinux/ss/services.c:security_policydb_len
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_bounded_transition
```
```
In security/apparmor/policy.c (ffffffff8143cac1)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In security/integrity/iint.c (ffffffff8144feda)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In block/blk-mq.c (ffffffff8148e325)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
```
```
In block/blk-wbt.c (ffffffff814b8df9)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
```
```
In lib/sbitmap.c (ffffffff814f86a6)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pci/pci.c (ffffffff8151ce42)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/acpi/apei/ghes.c (ffffffff815d68c5)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:__ghes_print_estatus
```
```
In drivers/regulator/core.c (ffffffff8160b5f1)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
```
```
In drivers/reset/core.c (ffffffff8160e68a)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff81611691)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/tty/tty_buffer.c (ffffffff81618ed9)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8161b55b)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/sysrq.c (ffffffff8161d092)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/tty/serial/serial_core.c (ffffffff8162ffb1)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/base/power/wakeup.c (ffffffff81694b37)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
```
```
In drivers/base/devcoredump.c (ffffffff816a91fc)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/block/loop.c (ffffffff816ab542)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
```
```
In drivers/mfd/mfd-core.c (ffffffff816c4f6a)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/scsi/scsi_lib.c (ffffffff816f24f3)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
```
```
In drivers/scsi/sd.c (ffffffff816fdcf0)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffff81706c51)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffffffff81712760)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
```
```
In drivers/ata/libata-scsi.c (ffffffff817170e1)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
```
```
In drivers/input/serio/serio.c (ffffffff817b92ed)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff817bf10b)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/power/supply/power_supply_core.c (ffffffff817e1005)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/md/dm.c (ffffffff8180a595)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_next_uevent_seq
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:alloc_io
```
```
In drivers/edac/edac_device.c (ffffffff818186c5)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffff8181a6e5)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff8181b1d5)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/edac/ghes_edac.c (ffffffff8181c692)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In drivers/leds/led-triggers.c (ffffffff81842e2a)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
```
In drivers/devfreq/devfreq.c (ffffffff8185d85a)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (ffffffff8185e389)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff8185ff4a)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In arch/x86/pci/common.c (ffffffff8186c305)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
```
```
In net/core/skbuff.c (ffffffff8187db43)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff8188ce31)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/core/dst.c (ffffffff8189fafa)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
```
```
In net/core/neighbour.c (ffffffff8189fed9)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:__neigh_create
```
```
In net/core/net-sysfs.c (ffffffff818bb758)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:address_show
```
```
In net/core/netpoll.c (ffffffff818bfa94)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/sched/sch_api.c (ffffffff818cee9a)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffffffff818d2b4f)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffffffff818d548f)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (ffffffff818d86ae)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff818da732)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/ipv4/ip_fragment.c (ffffffff818e9182)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/raw.c (ffffffff81918e16)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff8191de7d)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/arp.c (ffffffff819219b7)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
```
```
In net/ipv4/ipmr.c (ffffffff8193ed55)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_vif_seq_stop
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:reg_vif_xmit
```
```
In net/ipv4/ipmr_base.c (ffffffff81944844)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194dd48)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff8195086e)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/ipv6/ip6_output.c (ffffffff81962953)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff81972ff2)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffffffff8197c24e)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
```
In net/ipv6/raw.c (ffffffff81988a39)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/mcast.c (ffffffff8198e942)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/ipv6/mcast.c:inet6_mc_check
```
```
In net/ipv6/ip6mr.c (ffffffff819a0ada)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_stop
```
```
In net/packet/af_packet.c (ffffffff819ae3e5)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff819be6dd)
Location: arch/x86/include/asm/atomic.h:159
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
  - net/rfkill/core.c:rfkill_fop_release
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
In arch/x86/events/core.c (ffffffff8100624e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015777)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104ab30)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8104cb65)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81057b54)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81087f0a)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
```
In kernel/fork.c (ffffffff8109606c)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/fork.c:walk_process_tree
```
```
In kernel/exit.c (ffffffff8109aea6)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:is_current_pgrp_orphaned
```
```
In kernel/resource.c (ffffffff8109f2f5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/resource.c:iomem_is_exclusive
  - kernel/resource.c:iomem_map_sanity_check
  - kernel/resource.c:lookup_resource
  - kernel/resource.c:region_intersects
  - kernel/resource.c:find_next_iomem_res
  - kernel/resource.c:r_stop
```
```
In kernel/ptrace.c (ffffffff810a28f4)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff810a92dd)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:kill_pgrp
  - kernel/signal.c:kill_something_info
```
```
In kernel/sys.c (ffffffff810b02d7)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
```
```
In kernel/sched/core.c (ffffffff810cbb77)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
```
```
In kernel/sched/topology.c (ffffffff810e54e0)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/sched/autogroup.c (ffffffff810e7b67)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
```
In kernel/locking/spinlock.c (ffffffff81a2d185)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
  - kernel/locking/spinlock.c:_raw_read_trylock
  - kernel/locking/spinlock.c:_raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock
```
```
In kernel/power/process.c (ffffffff810f4382)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/irq/spurious.c (ffffffff811049ef)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (ffffffff81108d82)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/rcu/tree.c (ffffffff81114292)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_irq_exit
  - kernel/rcu/tree.c:rcu_idle_enter
  - kernel/rcu/tree.c:rcu_momentary_dyntick_idle
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
```
```
In kernel/livepatch/transition.c (ffffffff81117d6b)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_send_signals
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
```
```
In kernel/module.c (ffffffff81139b25)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/module.c:try_release_module_ref
```
```
In kernel/cgroup/cgroup.c (ffffffff8114bc35)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_mount
```
```
In kernel/pid_namespace.c (ffffffff8115adf9)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/audit.c (ffffffff8115cf4d)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In kernel/auditsc.c (ffffffff81164ac3)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_set_loginuid
  - kernel/auditsc.c:audit_set_loginuid
```
```
In kernel/tracepoint.c (ffffffff8117db5d)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/ftrace.c (ffffffff8117f8ab)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In kernel/trace/trace.c (ffffffff81193af0)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In kernel/trace/tracing_map.c (ffffffff811977f2)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_insert
```
```
In kernel/trace/trace_functions.c (ffffffff811988e0)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff81199698)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8119c0f4)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/fgraph.c (ffffffff811a0a80)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:register_ftrace_graph
```
```
In kernel/trace/trace_events.c (ffffffff811a12fb)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811a93e0)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In kernel/trace/trace_uprobe.c (ffffffff811bc93d)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In kernel/bpf/syscall.c (ffffffff811c1cc5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811d2e40)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/callchain.c (ffffffff811f38c0)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/padata.c (ffffffff811f7db4)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In kernel/memremap.c (ffffffff811f9f25)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/memremap.c:dev_pagemap_get_ops
```
```
In mm/oom_kill.c (ffffffff81205da6)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/vmalloc.c (ffffffff81255d75)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/zswap.c (ffffffff81263bd4)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/mempolicy.c (ffffffff812714e8)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
```
```
In mm/memory_hotplug.c (ffffffff81280598)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/memcontrol.c (ffffffff81299b14)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/memory-failure.c (ffffffff8129dd06)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
```
```
In mm/zsmalloc.c (ffffffff812a32bd)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/exec.c (ffffffff812b69cd)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/exec.c:__x64_sys_uselib
```
```
In fs/fcntl.c (ffffffff812c44ca)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/fcntl.c:kill_fasync
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_getown
```
```
In fs/inode.c (ffffffff812cd1f0)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
```
```
In fs/filesystems.c (ffffffff812d21be)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:filesystems_proc_show
  - fs/filesystems.c:fs_maxindex
  - fs/filesystems.c:fs_name
  - fs/filesystems.c:fs_index
  - fs/filesystems.c:get_filesystem_list
```
```
In fs/fs_struct.c (ffffffff812e9a4b)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/notify/notification.c (ffffffff812f97f5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/coredump.c (ffffffff813223af)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/netlink.c (ffffffff8132da60)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In fs/proc/inode.c (ffffffff81331e6b)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_entry_rundown
  - fs/proc/inode.c:unuse_pde
```
```
In fs/proc/generic.c (ffffffff813373da)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff81338335)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/kernfs/dir.c (ffffffff81343fe9)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_put_active
```
```
In fs/devpts/inode.c (ffffffff8134c245)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/extents_status.c (ffffffff8135b682)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:ext4_is_pending
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_scan_clu
  - fs/ext4/extents_status.c:ext4_es_scan_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
```
```
In fs/ext4/inode.c (ffffffff81372970)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff813966e8)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/jbd2/transaction.c (ffffffff813adf52)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:wait_transaction_locked
```
```
In fs/jbd2/journal.c (ffffffff813b245e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_errno
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_transaction_committed
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
```
In fs/ecryptfs/main.c (ffffffff813cf1e5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/keys/keyring.c (ffffffff81401277)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/avc.c (ffffffff814130ee)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/selinux/hooks.c (ffffffff81417365)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/selinux/ss/services.c (ffffffff81430f53)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_read_policy
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_policycap_supported
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_get_bool_value
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_node_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_ib_endport_sid
  - security/selinux/ss/services.c:security_ib_pkey_sid
  - security/selinux/ss/services.c:security_port_sid
  - security/selinux/ss/services.c:security_policydb_len
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_bounded_transition
```
```
In security/apparmor/policy.c (ffffffff81459921)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In security/integrity/iint.c (ffffffff8146ceba)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In block/blk-core.c (ffffffff8149d255)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In block/blk-mq.c (ffffffff814a7c95)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In block/blk-wbt.c (ffffffff814ccc55)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In lib/sbitmap.c (ffffffff8150c92d)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pci/pci.c (ffffffff81532542)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/acpi/apei/ghes.c (ffffffff815f0195)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:__ghes_print_estatus
```
```
In drivers/regulator/core.c (ffffffff81627df0)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (ffffffff8162b5ca)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff8162e401)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/tty/tty_buffer.c (ffffffff816360e9)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/tty/tty_jobctrl.c (ffffffff816388a6)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/sysrq.c (ffffffff8163a2f2)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/tty/serial/serial_core.c (ffffffff8164e161)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/base/power/wakeup.c (ffffffff816b51c7)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In drivers/base/devcoredump.c (ffffffff816c9df5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/block/loop.c (ffffffff816cbcb0)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
```
```
In drivers/mfd/mfd-core.c (ffffffff816e635a)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/scsi/scsi_lib.c (ffffffff81715044)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/sd.c (ffffffff817208c0)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffff81729791)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffffffff81734c10)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In drivers/ata/libata-scsi.c (ffffffff81739721)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In drivers/input/serio/serio.c (ffffffff817e06fd)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff817e656b)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/power/supply/power_supply_core.c (ffffffff8180c685)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/md/dm.c (ffffffff81836595)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_next_uevent_seq
```
```
In drivers/edac/edac_device.c (ffffffff81843f65)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffff81845ed5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff818469c5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/edac/ghes_edac.c (ffffffff8184800b)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In drivers/leds/led-triggers.c (ffffffff8186eeba)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
```
In drivers/devfreq/devfreq.c (ffffffff8187c99a)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (ffffffff8187dda9)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff8187f8d7)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In arch/x86/pci/common.c (ffffffff8188c3e5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
```
```
In net/core/skbuff.c (ffffffff8189e713)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff818ae081)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/core/dst.c (ffffffff818c228a)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
```
```
In net/core/neighbour.c (ffffffff818c2799)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/net-sysfs.c (ffffffff818e24e8)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:address_show
```
```
In net/core/netpoll.c (ffffffff818e88b4)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffffffff818f281c)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/sched/sch_api.c (ffffffff818fa19a)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffffffff818fdfd2)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffffffff819020cf)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (ffffffff81904e9e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff8190614f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/ipv4/ip_fragment.c (ffffffff81916235)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/raw.c (ffffffff81947706)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff8194cacd)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/arp.c (ffffffff819507d7)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
```
```
In net/ipv4/ipmr.c (ffffffff8196ec05)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_vif_seq_stop
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:reg_vif_xmit
```
```
In net/ipv4/ipmr_base.c (ffffffff81974ae4)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197f909)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff81983dae)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/ipv6/ip6_output.c (ffffffff8199793c)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff819a8c12)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffffffff819b1f2e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
```
In net/ipv6/raw.c (ffffffff819bf3a1)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/mcast.c (ffffffff819c51f9)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv6/mcast.c:inet6_mc_check
```
```
In net/ipv6/ip6mr.c (ffffffff819d76da)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_stop
```
```
In net/packet/af_packet.c (ffffffff819e4ca6)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff819f587d)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
  - net/rfkill/core.c:rfkill_fop_release
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
In arch/x86/events/core.c (ffffffff8100635e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff81016838)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104dbbb)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8104fa8a)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105adbb)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108bb5a)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
```
In kernel/fork.c (ffffffff8109a59d)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/fork.c:walk_process_tree
```
```
In kernel/exit.c (ffffffff8109f507)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:is_current_pgrp_orphaned
```
```
In kernel/resource.c (ffffffff810a3916)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/resource.c:iomem_is_exclusive
  - kernel/resource.c:iomem_map_sanity_check
  - kernel/resource.c:lookup_resource
  - kernel/resource.c:region_intersects
  - kernel/resource.c:find_next_iomem_res
  - kernel/resource.c:r_stop
```
```
In kernel/ptrace.c (ffffffff810a7579)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff810ad66f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:kill_pgrp
  - kernel/signal.c:kill_something_info
```
```
In kernel/sys.c (ffffffff810b5ca9)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
```
```
In kernel/sched/core.c (ffffffff810d3bfe)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
```
```
In kernel/sched/topology.c (ffffffff810ec36e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/autogroup.c (ffffffff810eeadf)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
```
In kernel/locking/spinlock.c (ffffffff81a9d265)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
  - kernel/locking/spinlock.c:_raw_read_trylock
  - kernel/locking/spinlock.c:_raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock
```
```
In kernel/power/process.c (ffffffff810fc8ea)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/irq/spurious.c (ffffffff8110dc01)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (ffffffff81112362)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/rcu/tree.c (ffffffff8111a933)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_irq_exit
  - kernel/rcu/tree.c:rcu_nmi_exit
  - kernel/rcu/tree.c:rcu_idle_enter
  - kernel/rcu/tree.c:rcu_momentary_dyntick_idle
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
```
```
In kernel/livepatch/transition.c (ffffffff811220ac)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
```
```
In kernel/module.c (ffffffff811451e5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/module.c:try_release_module_ref
```
```
In kernel/cgroup/cgroup.c (ffffffff8115750b)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/pid_namespace.c (ffffffff811674b7)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/audit.c (ffffffff8116b52a)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/tracepoint.c (ffffffff8118aa1b)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/ftrace.c (ffffffff8118c99e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811a1770)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In kernel/trace/tracing_map.c (ffffffff811a51fe)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In kernel/trace/trace_functions.c (ffffffff811a64a0)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811a72b8)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811a9cff)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/fgraph.c (ffffffff811ae7e2)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
```
In kernel/trace/trace_events.c (ffffffff811af212)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811b7330)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cc0cd)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In kernel/bpf/syscall.c (ffffffff811d2315)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811e757d)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/callchain.c (ffffffff8120b68a)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/padata.c (ffffffff8120fc35)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In mm/oom_kill.c (ffffffff8121cd43)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/zswap.c (ffffffff8127eb55)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/mempolicy.c (ffffffff8128caf8)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
```
```
In mm/memory_hotplug.c (ffffffff8129c8d3)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/memcontrol.c (ffffffff812b4d06)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/memory-failure.c (ffffffff812b8fdf)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
```
```
In mm/zsmalloc.c (ffffffff812be626)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In mm/memremap.c (ffffffff812c2805)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages
```
```
In fs/exec.c (ffffffff812d4b1f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/exec.c:__x64_sys_uselib
```
```
In fs/fcntl.c (ffffffff812e0fe0)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_getown
```
```
In fs/inode.c (ffffffff812ea230)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
```
```
In fs/filesystems.c (ffffffff812ef220)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:filesystems_proc_show
  - fs/filesystems.c:fs_maxindex
  - fs/filesystems.c:fs_name
  - fs/filesystems.c:fs_index
  - fs/filesystems.c:get_filesystem_list
```
```
In fs/fs_struct.c (ffffffff813083ed)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/notify/notification.c (ffffffff81319e55)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/io_uring.c (ffffffff8132f888)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/coredump.c (ffffffff81349d74)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/netlink.c (ffffffff8135579f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In fs/proc/inode.c (ffffffff81359cbb)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_entry_rundown
  - fs/proc/inode.c:unuse_pde
```
```
In fs/proc/generic.c (ffffffff8135f4fa)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff813609e6)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/kernfs/dir.c (ffffffff8136c239)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_put_active
```
```
In fs/devpts/inode.c (ffffffff81374c15)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/extents_status.c (ffffffff813846a9)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:ext4_is_pending
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_scan_clu
  - fs/ext4/extents_status.c:ext4_es_scan_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
```
```
In fs/ext4/inode.c (ffffffff8139bd76)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff813c06ec)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/jbd2/transaction.c (ffffffff813d8323)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:wait_transaction_locked
```
```
In fs/jbd2/journal.c (ffffffff813dcacf)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_errno
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_transaction_committed
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
```
In fs/ecryptfs/main.c (ffffffff813f9da5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/keys/keyring.c (ffffffff8142da57)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/avc.c (ffffffff81440b89)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/selinux/hooks.c (ffffffff81444f45)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/selinux/ss/services.c (ffffffff8145e974)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_read_policy
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_policycap_supported
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_get_bool_value
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_node_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_ib_endport_sid
  - security/selinux/ss/services.c:security_ib_pkey_sid
  - security/selinux/ss/services.c:security_port_sid
  - security/selinux/ss/services.c:security_policydb_len
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_bounded_transition
```
```
In security/apparmor/policy.c (ffffffff8148706f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In security/integrity/iint.c (ffffffff8149a5aa)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In block/blk-core.c (ffffffff814cb385)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In block/blk-wbt.c (ffffffff814fb6c5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In lib/sbitmap.c (ffffffff8153b037)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pci/pci.c (ffffffff81561c12)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/acpi/apei/ghes.c (ffffffff81621f15)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:__ghes_print_estatus
```
```
In drivers/regulator/core.c (ffffffff8165c094)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (ffffffff8165ef0f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff81661fd4)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/tty/tty_buffer.c (ffffffff8166a323)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8166cb07)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/sysrq.c (ffffffff8166e62e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/tty/serial/serial_core.c (ffffffff81682cc3)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/base/power/wakeup.c (ffffffff816eed67)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In drivers/base/devcoredump.c (ffffffff81705396)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/block/loop.c (ffffffff817072b2)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
```
```
In drivers/mfd/mfd-core.c (ffffffff8171faea)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/scsi/scsi_lib.c (ffffffff81750825)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/sd.c (ffffffff8175bf72)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffff81764adc)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffffffff8177058e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-scsi.c (ffffffff81775731)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In drivers/input/serio/serio.c (ffffffff81820fbb)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff81826c26)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/power/supply/power_supply_core.c (ffffffff8184e315)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/md/dm.c (ffffffff81879155)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_next_uevent_seq
```
```
In drivers/edac/edac_device.c (ffffffff81886d35)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffff81888cb5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81889775)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/edac/ghes_edac.c (ffffffff8188ae86)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In drivers/leds/led-triggers.c (ffffffff818b3170)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
```
In drivers/devfreq/devfreq.c (ffffffff818c7426)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/devfreq/devfreq-event.c (ffffffff818c835f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff818c9ed4)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In arch/x86/pci/common.c (ffffffff818d6d25)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
```
```
In net/core/skbuff.c (ffffffff818e8f84)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff818f99b1)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/core/dst.c (ffffffff8190e9ea)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
```
```
In net/core/neighbour.c (ffffffff8190ee9e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/net-sysfs.c (ffffffff81931da8)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:address_show
```
```
In net/core/netpoll.c (ffffffff819380c6)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffffffff8194495f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/core/bpf_sk_storage.c (ffffffff819536ad)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/sched/sch_api.c (ffffffff81959a2f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffffffff8195d967)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffffffff81963264)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (ffffffff8196610e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81967434)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/ipv4/ip_fragment.c (ffffffff81978464)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/raw.c (ffffffff819abd96)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819b127c)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/arp.c (ffffffff819b5098)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
```
```
In net/ipv4/ipmr.c (ffffffff819d8405)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_vif_seq_stop
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:reg_vif_xmit
```
```
In net/ipv4/ipmr_base.c (ffffffff819de614)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e9605)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff819ed94e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/ipv6/ip6_output.c (ffffffff81a039ec)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff81a14f3b)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffffffff81a20417)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
```
In net/ipv6/raw.c (ffffffff81a2dfdc)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/mcast.c (ffffffff81a34062)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv6/mcast.c:inet6_mc_check
```
```
In net/ipv6/ip6mr.c (ffffffff81a4684f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_stop
```
```
In net/packet/af_packet.c (ffffffff81a53e01)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff81a64bae)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
  - net/rfkill/core.c:rfkill_fop_release
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
In arch/x86/events/core.c (ffffffff8100640e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff810171e8)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104e55e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8105041a)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b6ab)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108c7ca)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
```
In kernel/fork.c (ffffffff810a0b5d)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/fork.c:walk_process_tree
```
```
In kernel/exit.c (ffffffff810a5a97)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:is_current_pgrp_orphaned
```
```
In kernel/resource.c (ffffffff810a9f46)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/resource.c:iomem_is_exclusive
  - kernel/resource.c:iomem_map_sanity_check
  - kernel/resource.c:lookup_resource
  - kernel/resource.c:region_intersects
  - kernel/resource.c:find_next_iomem_res
  - kernel/resource.c:r_stop
```
```
In kernel/ptrace.c (ffffffff810adba5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff810b3c8f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:kill_pgrp
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sys.c (ffffffff810bc2c5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
```
```
In kernel/sched/core.c (ffffffff810de0de)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
```
```
In kernel/sched/rt.c (ffffffff810f05cb)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:tg_set_rt_bandwidth
```
```
In kernel/sched/topology.c (ffffffff810f7e15)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/autogroup.c (ffffffff810fa6df)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
```
In kernel/locking/spinlock.c (ffffffff81ad4a45)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
  - kernel/locking/spinlock.c:_raw_read_trylock
  - kernel/locking/spinlock.c:_raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock
```
```
In kernel/power/process.c (ffffffff81108cdf)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/irq/spurious.c (ffffffff81119ec1)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (ffffffff8111e5f2)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/rcu/tree.c (ffffffff81126d4f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_irq_exit
  - kernel/rcu/tree.c:rcu_nmi_exit
  - kernel/rcu/tree.c:rcu_idle_enter
  - kernel/rcu/tree.c:rcu_momentary_dyntick_idle
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
```
```
In kernel/livepatch/transition.c (ffffffff8112e6cc)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
```
```
In kernel/module.c (ffffffff81150cf5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/module.c:try_release_module_ref
```
```
In kernel/cgroup/cgroup.c (ffffffff8116310b)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_enable_task_cg_lists
```
```
In kernel/pid_namespace.c (ffffffff81173377)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/audit.c (ffffffff8117740a)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/tracepoint.c (ffffffff8119692b)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/ftrace.c (ffffffff8119859e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811ad220)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In kernel/trace/tracing_map.c (ffffffff811b0a2e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In kernel/trace/trace_functions.c (ffffffff811b1c90)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811b2aa8)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811b54ef)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/fgraph.c (ffffffff811b9f62)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
```
In kernel/trace/trace_events.c (ffffffff811ba6e2)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811c29a0)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d8544)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In kernel/bpf/syscall.c (ffffffff811de8b5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811f3cdd)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/callchain.c (ffffffff8121896a)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/padata.c (ffffffff8121d620)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In mm/oom_kill.c (ffffffff8122a723)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/zswap.c (ffffffff8128e595)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/mempolicy.c (ffffffff8129c728)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
```
```
In mm/memory_hotplug.c (ffffffff812ac573)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/memcontrol.c (ffffffff812c67f6)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/memory-failure.c (ffffffff812caecf)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
```
```
In mm/zsmalloc.c (ffffffff812d0516)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In mm/memremap.c (ffffffff812d471c)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/exec.c (ffffffff812e669f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/exec.c:__x64_sys_uselib
```
```
In fs/fcntl.c (ffffffff812f2a94)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_getown
```
```
In fs/inode.c (ffffffff812fbd10)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
```
```
In fs/filesystems.c (ffffffff81300ce0)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:filesystems_proc_show
  - fs/filesystems.c:fs_maxindex
  - fs/filesystems.c:fs_name
  - fs/filesystems.c:fs_index
  - fs/filesystems.c:get_filesystem_list
```
```
In fs/fs_struct.c (ffffffff8131b48d)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/notify/notification.c (ffffffff8132cc85)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/io_uring.c (ffffffff81343056)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/coredump.c (ffffffff81362014)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/netlink.c (ffffffff8136dadf)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In fs/proc/inode.c (ffffffff81371f0b)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_entry_rundown
  - fs/proc/inode.c:unuse_pde
```
```
In fs/proc/generic.c (ffffffff8137775a)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff81378c46)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/kernfs/dir.c (ffffffff813843da)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In fs/devpts/inode.c (ffffffff8138ce95)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/extents_status.c (ffffffff8139d329)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:ext4_is_pending
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_scan_clu
  - fs/ext4/extents_status.c:ext4_es_scan_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
```
```
In fs/ext4/inode.c (ffffffff813b487d)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff813d99ac)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/jbd2/transaction.c (ffffffff813f23a3)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:wait_transaction_locked
```
```
In fs/jbd2/journal.c (ffffffff813f6b1f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_errno
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_transaction_committed
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
```
In fs/ecryptfs/main.c (ffffffff81413c75)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/keys/keyring.c (ffffffff814477a7)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/avc.c (ffffffff8145a499)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/selinux/hooks.c (ffffffff8145eab5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/selinux/ss/services.c (ffffffff81478724)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_read_policy
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_policycap_supported
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_get_bool_value
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_node_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_ib_endport_sid
  - security/selinux/ss/services.c:security_ib_pkey_sid
  - security/selinux/ss/services.c:security_port_sid
  - security/selinux/ss/services.c:security_policydb_len
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_bounded_transition
```
```
In security/apparmor/policy.c (ffffffff814a0f1f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In security/integrity/iint.c (ffffffff814b47aa)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In block/blk-core.c (ffffffff814e4575)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In block/blk-iocost.c (ffffffff8150fbff)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In block/blk-wbt.c (ffffffff81519615)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In lib/sbitmap.c (ffffffff8155be57)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pci/pci.c (ffffffff81582db2)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/acpi/apei/ghes.c (ffffffff816439f5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:__ghes_print_estatus
```
```
In drivers/regulator/core.c (ffffffff8167de7b)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (ffffffff816815df)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff81684644)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/tty/tty_buffer.c (ffffffff8168ca09)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8168f177)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/sysrq.c (ffffffff81690c6e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/tty/serial/serial_core.c (ffffffff816a5353)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/base/power/wakeup.c (ffffffff81712f87)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In drivers/base/devcoredump.c (ffffffff81729626)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/block/loop.c (ffffffff8172b502)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
```
```
In drivers/mfd/mfd-core.c (ffffffff81743dba)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/scsi/scsi_lib.c (ffffffff81774a48)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/sd.c (ffffffff8177fe12)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffff81788acc)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffffffff817945ee)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-scsi.c (ffffffff817996a1)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In drivers/input/serio/serio.c (ffffffff8185242b)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff81858156)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/power/supply/power_supply_core.c (ffffffff8187fd55)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/md/dm.c (ffffffff818aaf95)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_next_uevent_seq
```
```
In drivers/edac/edac_device.c (ffffffff818b8cf5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffff818bac65)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff818bb725)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/leds/led-triggers.c (ffffffff818e5a90)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff818f4eac)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/devfreq/devfreq.c (ffffffff818f8ea8)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (ffffffff818fa7ef)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff818fc324)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In arch/x86/pci/common.c (ffffffff819090a5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
```
```
In net/core/skbuff.c (ffffffff8191b0e4)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff8192bb11)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/core/dst.c (ffffffff8194105a)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
```
```
In net/core/neighbour.c (ffffffff8194150e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/net-sysfs.c (ffffffff819648e8)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:address_show
```
```
In net/core/page_pool.c (ffffffff81966ddb)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_clean_page
```
```
In net/core/netpoll.c (ffffffff8196af86)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffffffff8197995f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/core/bpf_sk_storage.c (ffffffff81989a4d)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/sched/sch_api.c (ffffffff8198fecf)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffffffff81994057)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffffffff81999de4)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (ffffffff8199cb9e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff8199dec4)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/ipv4/ip_fragment.c (ffffffff819aedd4)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/raw.c (ffffffff819e2a46)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819e7fa8)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/arp.c (ffffffff819ebdc8)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
```
```
In net/ipv4/ipmr.c (ffffffff81a0efd5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_vif_seq_stop
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:reg_vif_xmit
```
```
In net/ipv4/ipmr_base.c (ffffffff81a156b4)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a20635)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff81a247fe)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/ipv6/ip6_output.c (ffffffff81a3a5bc)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff81a4bb2b)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffffffff81a5705b)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
```
In net/ipv6/raw.c (ffffffff81a64b4c)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/mcast.c (ffffffff81a6abb2)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv6/mcast.c:inet6_mc_check
```
```
In net/ipv6/ip6mr.c (ffffffff81a7d43f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_stop
```
```
In net/packet/af_packet.c (ffffffff81a8aa11)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff81a9b94e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
  - net/rfkill/core.c:rfkill_fop_release
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
In arch/x86/events/core.c (ffffffff8100741e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff81018698)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81051ec1)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8105441e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_storm_detect
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8106051c)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81093de8)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:ioremap_trace_core
```
```
In kernel/fork.c (ffffffff810a79cd)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/fork.c:walk_process_tree
```
```
In kernel/exit.c (ffffffff810ad5b4)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:wait_task_continued
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:is_current_pgrp_orphaned
```
```
In kernel/resource.c (ffffffff810b1afc)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/resource.c:iomem_is_exclusive
  - kernel/resource.c:iomem_map_sanity_check
  - kernel/resource.c:lookup_resource
  - kernel/resource.c:region_intersects
  - kernel/resource.c:find_next_iomem_res
  - kernel/resource.c:r_stop
```
```
In kernel/ptrace.c (ffffffff810b5685)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff810bc735)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:kill_pgrp
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sys.c (ffffffff810c3c65)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
```
```
In kernel/sched/core.c (ffffffff810e6674)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
```
```
In kernel/sched/topology.c (ffffffff81101509)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:init_overlap_sched_group
```
```
In kernel/sched/autogroup.c (ffffffff81104abf)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
```
In kernel/locking/spinlock.c (ffffffff81bccc45)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
  - kernel/locking/spinlock.c:_raw_read_trylock
  - kernel/locking/spinlock.c:_raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock
```
```
In kernel/power/process.c (ffffffff8111346e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/irq/spurious.c (ffffffff81125c25)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/spurious.c:misrouted_irq
```
```
In kernel/irq/irqdomain.c (ffffffff81129e34)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/rcu/tree.c (ffffffff811349ee)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_boot_init_percpu_data
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_momentary_dyntick_idle
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
  - kernel/rcu/tree.c:rcu_dynticks_eqs_enter
```
```
In kernel/livepatch/transition.c (ffffffff8113cd29)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_send_signals
  - kernel/livepatch/transition.c:klp_complete_transition
```
```
In kernel/module.c (ffffffff81161245)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/module.c:try_release_module_ref
```
```
In kernel/pid_namespace.c (ffffffff811854c3)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/audit.c (ffffffff8118a16d)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/tracepoint.c (ffffffff811abc5b)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/ftrace.c (ffffffff811ad580)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_profile_alloc
```
```
In kernel/trace/trace.c (ffffffff811c4f30)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In kernel/trace/tracing_map.c (ffffffff811c88c0)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:get_free_elt
```
```
In kernel/trace/trace_functions.c (ffffffff811ca412)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811cafa8)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811ce21a)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/fgraph.c (ffffffff811d29a4)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:alloc_retstack_tasklist
```
```
In kernel/trace/trace_events.c (ffffffff811d5914)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811dccad)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f53e4)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In kernel/bpf/hashtab.c (ffffffff81217e93)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/callchain.c (ffffffff812446aa)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/watch_queue.c (ffffffff8124c828)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/oom_kill.c (ffffffff81257533)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/swap.c (ffffffff8125e53e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/swap.c:put_devmap_managed_page
```
```
In mm/gup.c (ffffffff812879f4)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/gup.c:__unpin_devmap_managed_user_page
```
```
In mm/zswap.c (ffffffff812c1245)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/mempolicy.c (ffffffff812d0378)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
```
```
In mm/memory_hotplug.c (ffffffff812e1613)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/memory-failure.c (ffffffff81300d95)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs_file
  - mm/memory-failure.c:collect_procs_anon
```
```
In mm/zsmalloc.c (ffffffff81306c6e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In mm/memremap.c (ffffffff8130a377)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/exec.c (ffffffff8131ca2a)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/exec.c:search_binary_handler
  - fs/exec.c:search_binary_handler
  - fs/exec.c:de_thread
  - fs/exec.c:__do_sys_uselib
  - fs/exec.c:__do_sys_uselib
```
```
In fs/fcntl.c (ffffffff8132ad20)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_getown_ex
  - fs/fcntl.c:f_getown
```
```
In fs/inode.c (ffffffff81334ab0)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
```
```
In fs/filesystems.c (ffffffff81339fb8)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:filesystems_proc_show
  - fs/filesystems.c:__ia32_sys_sysfs
  - fs/filesystems.c:__x64_sys_sysfs
  - fs/filesystems.c:fs_name
  - fs/filesystems.c:fs_index
```
```
In fs/fs_struct.c (ffffffff81355131)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/notify/notification.c (ffffffff81366a25)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/io_uring.c (ffffffff81385da0)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_cancel_files
  - fs/io_uring.c:__io_cqring_fill_event
  - fs/io_uring.c:io_cqring_overflow_flush
```
```
In fs/coredump.c (ffffffff813a7fe9)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/netlink.c (ffffffff813b560f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In fs/proc/inode.c (ffffffff813b9625)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_put_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
  - fs/proc/inode.c:proc_entry_rundown
```
```
In fs/proc/generic.c (ffffffff813c05ca)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff813c1cba)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/kernfs/inode.c (ffffffff813cd3e3)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff813ceeba)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In fs/devpts/inode.c (ffffffff813d82e5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/extents_status.c (ffffffff813e89cc)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:ext4_is_pending
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_scan_clu
  - fs/ext4/extents_status.c:ext4_es_scan_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
```
```
In fs/ext4/inode.c (ffffffff813ffd2b)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff81425d88)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/jbd2/transaction.c (ffffffff8143f723)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:stop_this_handle
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_free_reserved
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:wait_transaction_locked
```
```
In fs/jbd2/journal.c (ffffffff81445fdf)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_errno
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_transaction_committed
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
```
In fs/ecryptfs/main.c (ffffffff81461e15)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/keys/keyring.c (ffffffff81498f1e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/avc.c (ffffffff814ada10)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/selinux/hooks.c (ffffffff814b5bfd)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/selinux/ss/services.c (ffffffff814cdbf3)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_read_policy
  - security/selinux/ss/services.c:security_read_policy
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_policycap_supported
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_get_bool_value
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_node_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_ib_endport_sid
  - security/selinux/ss/services.c:security_ib_pkey_sid
  - security/selinux/ss/services.c:security_port_sid
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:security_sid_to_context_core
  - security/selinux/ss/services.c:security_sidtab_hash_stats
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_bounded_transition
```
```
In security/apparmor/policy.c (ffffffff814fb040)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In security/integrity/iint.c (ffffffff81513d3a)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In block/blk-core.c (ffffffff81542e75)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In block/blk-wbt.c (ffffffff81579bd5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In block/keyslot-manager.c (ffffffff8158121a)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In lib/sbitmap.c (ffffffff815e594c)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pci/pci.c (ffffffff816298d5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/acpi/apei/ghes.c (ffffffff816f1355)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
  - drivers/acpi/apei/ghes.c:__ghes_print_estatus
```
```
In drivers/regulator/core.c (ffffffff8172f55c)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (ffffffff817326cf)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff81736e68)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/tty/tty_buffer.c (ffffffff8173ea39)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/tty/tty_jobctrl.c (ffffffff817411ce)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tiocsctty
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/sysrq.c (ffffffff8174375e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/tty/serial/serial_core.c (ffffffff81757983)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/base/power/wakeup.c (ffffffff817ce624)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_activate
```
```
In drivers/base/devcoredump.c (ffffffff817e5e56)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/block/loop.c (ffffffff817e74b2)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
```
```
In drivers/scsi/scsi_lib.c (ffffffff818380d0)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
```
```
In drivers/scsi/sd.c (ffffffff81844870)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffff8184dd07)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_debug_helper
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffffffff818587fe)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-sata.c (ffffffff81868051)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In drivers/input/serio/serio.c (ffffffff819242db)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff81929936)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/power/supply/power_supply_core.c (ffffffff8194ee15)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/md/dm.c (ffffffff8197b165)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_next_uevent_seq
```
```
In drivers/edac/edac_device.c (ffffffff81989505)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffff8198b4c5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff8198c109)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_main_kobj_setup
```
```
In drivers/leds/led-triggers.c (ffffffff819b8b2d)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819c9e4c)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/devfreq/devfreq.c (ffffffff819cfa8e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (ffffffff819d1070)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff819d2f0f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/skbuff.c (ffffffff819ede23)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff819ff311)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/core/dst.c (ffffffff81a10c28)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
```
```
In net/core/neighbour.c (ffffffff81a1202e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/net-sysfs.c (ffffffff81a391b0)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/net-sysfs.c:proto_down_show
  - net/core/net-sysfs.c:group_show
  - net/core/net-sysfs.c:napi_defer_hard_irqs_show
  - net/core/net-sysfs.c:gro_flush_timeout_show
  - net/core/net-sysfs.c:tx_queue_len_show
  - net/core/net-sysfs.c:flags_show
  - net/core/net-sysfs.c:mtu_show
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:address_show
  - net/core/net-sysfs.c:name_assign_type_show
  - net/core/net-sysfs.c:link_mode_show
  - net/core/net-sysfs.c:type_show
  - net/core/net-sysfs.c:ifindex_show
  - net/core/net-sysfs.c:addr_len_show
  - net/core/net-sysfs.c:addr_assign_type_show
  - net/core/net-sysfs.c:dev_port_show
  - net/core/net-sysfs.c:dev_id_show
```
```
In net/core/page_pool.c (ffffffff81a3a86b)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release_page
```
```
In net/core/netpoll.c (ffffffff81a3ecee)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffffffff81a4db85)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_alloc_elem
```
```
In net/core/bpf_sk_storage.c (ffffffff81a61767)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/sched/sch_api.c (ffffffff81a685df)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffffffff81a6c1cf)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffffffff81a72b44)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (ffffffff81a75d2e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_lookup
  - net/sched/ematch.c:tcf_em_lookup
```
```
In net/netlink/af_netlink.c (ffffffff81a77213)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/ipv4/route.c (ffffffff81a906cf)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv4/ip_fragment.c (ffffffff81a991e8)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/raw.c (ffffffff81ad0536)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81ad5eb8)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/arp.c (ffffffff81ad962c)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_format_neigh_entry
```
```
In net/ipv4/ipmr.c (ffffffff81b01935)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_vif_seq_stop
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:reg_vif_xmit
```
```
In net/ipv4/ipmr_base.c (ffffffff81b0613c)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b12128)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff81b1653e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/ipv6/ip6_output.c (ffffffff81b2cfd5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_call_ra_chain
  - net/ipv6/ip6_output.c:ip6_call_ra_chain
```
```
In net/ipv6/route.c (ffffffff81b41b78)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4d267)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81b5d49a)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/mcast.c (ffffffff81b63a88)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv6/mcast.c:inet6_mc_check
```
```
In net/ipv6/ip6mr.c (ffffffff81b77de9)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_stop
```
```
In net/packet/af_packet.c (ffffffff81b865b1)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff81b970de)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
  - net/rfkill/core.c:rfkill_fop_release
```
```
In arch/x86/pci/common.c (ffffffff81bb9965)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
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
In arch/x86/events/core.c (ffffffff8100660e)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff81018d6b)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81050fe1)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8105335e)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_storm_detect
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ed7c)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81093338)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:ioremap_trace_core
```
```
In kernel/fork.c (ffffffff810a36ad)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/fork.c:walk_process_tree
```
```
In kernel/exit.c (ffffffff810a8c84)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:wait_task_continued
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:is_current_pgrp_orphaned
```
```
In kernel/resource.c (ffffffff810ad3bc)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/resource.c:iomem_is_exclusive
  - kernel/resource.c:iomem_map_sanity_check
  - kernel/resource.c:lookup_resource
  - kernel/resource.c:region_intersects
  - kernel/resource.c:find_next_iomem_res
  - kernel/resource.c:r_stop
```
```
In kernel/ptrace.c (ffffffff810b0885)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff810b7a25)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:kill_pgrp
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sys.c (ffffffff810bf055)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
```
```
In kernel/sched/core.c (ffffffff810e4574)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:uclamp_sync_util_min_rt_default
```
```
In kernel/sched/topology.c (ffffffff81100069)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:init_overlap_sched_group
```
```
In kernel/sched/autogroup.c (ffffffff8110313f)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
```
In kernel/locking/spinlock.c (ffffffff81c45811)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
  - kernel/locking/spinlock.c:_raw_read_trylock
  - kernel/locking/spinlock.c:_raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock
```
```
In kernel/power/process.c (ffffffff811104be)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/irq/spurious.c (ffffffff81121935)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/spurious.c:misrouted_irq
```
```
In kernel/irq/irqdomain.c (ffffffff811256fa)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/rcu/tree.c (ffffffff8113048e)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_boot_init_percpu_data
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_momentary_dyntick_idle
  - kernel/rcu/tree.c:rcu_is_idle_cpu
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
  - kernel/rcu/tree.c:rcu_dynticks_eqs_enter
```
```
In kernel/livepatch/transition.c (ffffffff81137439)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_send_signals
  - kernel/livepatch/transition.c:klp_complete_transition
```
```
In kernel/module.c (ffffffff8115d185)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/module.c:try_release_module_ref
```
```
In kernel/pid_namespace.c (ffffffff811825cf)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/audit.c (ffffffff8118747d)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/tracepoint.c (ffffffff811a955b)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/ftrace.c (ffffffff811aae90)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_profile_alloc
```
```
In kernel/trace/trace.c (ffffffff811c2b70)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In kernel/trace/tracing_map.c (ffffffff811c5fa0)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:get_free_elt
```
```
In kernel/trace/trace_functions.c (ffffffff811c7a82)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811c8688)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811cb6fa)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (ffffffff811d2be4)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811d9ddd)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f3d74)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In kernel/bpf/hashtab.c (ffffffff8121a02e)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/callchain.c (ffffffff8124ec7a)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/watch_queue.c (ffffffff81256c68)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/oom_kill.c (ffffffff81262113)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/swap.c (ffffffff812685fb)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - mm/swap.c:put_devmap_managed_page
```
```
In mm/zswap.c (ffffffff812ccd65)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/mempolicy.c (ffffffff812dbe98)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
```
```
In mm/memory_hotplug.c (ffffffff812ec563)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/memory-failure.c (ffffffff8130cf34)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs_file
  - mm/memory-failure.c:collect_procs_anon
```
```
In mm/zsmalloc.c (ffffffff813127fe)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/exec.c (ffffffff81327bba)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/exec.c:search_binary_handler
  - fs/exec.c:search_binary_handler
  - fs/exec.c:de_thread
  - fs/exec.c:__do_sys_uselib
  - fs/exec.c:__do_sys_uselib
```
```
In fs/fcntl.c (ffffffff8133630a)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_getown_ex
  - fs/fcntl.c:f_getown
```
```
In fs/inode.c (ffffffff81340420)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
```
```
In fs/filesystems.c (ffffffff81345cc8)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:filesystems_proc_show
  - fs/filesystems.c:__ia32_sys_sysfs
  - fs/filesystems.c:__x64_sys_sysfs
  - fs/filesystems.c:fs_name
  - fs/filesystems.c:fs_index
```
```
In fs/fs_struct.c (ffffffff81361a51)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/notify/notification.c (ffffffff81373d75)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/coredump.c (ffffffff813b9069)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/netlink.c (ffffffff813c6e3f)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In fs/proc/inode.c (ffffffff813cb145)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_put_link
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
  - fs/proc/inode.c:proc_entry_rundown
```
```
In fs/proc/generic.c (ffffffff813d241a)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff813d3dda)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/kernfs/inode.c (ffffffff813df013)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff813e0aea)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In fs/devpts/inode.c (ffffffff813e9f85)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/extents_status.c (ffffffff813fac7c)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:ext4_is_pending
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_scan_clu
  - fs/ext4/extents_status.c:ext4_es_scan_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
```
```
In fs/ext4/inode.c (ffffffff81412540)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/mballoc.c (ffffffff8141c38e)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ext4/super.c (ffffffff8143ea2c)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/jbd2/transaction.c (ffffffff8145b983)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:stop_this_handle
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_free_reserved
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:wait_transaction_locked
```
```
In fs/jbd2/journal.c (ffffffff8146240f)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_errno
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_transaction_committed
  - fs/jbd2/journal.c:jbd2_fc_end_commit_fallback
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
```
In fs/ecryptfs/main.c (ffffffff8147d985)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/keys/keyring.c (ffffffff814b699e)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/avc.c (ffffffff814cb490)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/selinux/hooks.c (ffffffff814d38dd)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/apparmor/policy.c (ffffffff81517f11)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In security/integrity/iint.c (ffffffff81530e8a)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In block/blk-core.c (ffffffff8155f6f5)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In block/blk-wbt.c (ffffffff81596ae5)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In block/keyslot-manager.c (ffffffff8159e24a)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In lib/sbitmap.c (ffffffff81609d0c)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8163b849)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:edge_irq_handler
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
```
```
In drivers/pci/pci.c (ffffffff8164fca5)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/acpi/apei/ghes.c (ffffffff8170e6f5)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
  - drivers/acpi/apei/ghes.c:__ghes_print_estatus
```
```
In drivers/xen/events/events_base.c (ffffffff8173297a)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__xen_evtchn_do_upcall
```
```
In drivers/regulator/core.c (ffffffff8174c1a0)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (ffffffff8174e5a6)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_array_rearm
```
```
In drivers/tty/tty_io.c (ffffffff81752708)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/tty/tty_buffer.c (ffffffff8175a989)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8175d0fe)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tiocsctty
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/sysrq.c (ffffffff8175f5de)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/tty/serial/serial_core.c (ffffffff81772a43)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/base/power/wakeup.c (ffffffff817e328c)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_activate
```
```
In drivers/base/devcoredump.c (ffffffff817faae6)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/block/loop.c (ffffffff817fc0ef)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
```
```
In drivers/scsi/scsi_lib.c (ffffffff818489a1)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
```
```
In drivers/scsi/sd.c (ffffffff81854b8d)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffff8185e0f7)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_debug_helper
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffffffff81868a5e)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-sata.c (ffffffff81876e61)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In drivers/input/serio/serio.c (ffffffff8192c08b)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff81930f36)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81954875)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/md/dm.c (ffffffff8197f985)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_next_uevent_seq
```
```
In drivers/edac/edac_device.c (ffffffff8198d295)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffff8198f0d5)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff8198fc39)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_main_kobj_setup
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819ca52c)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/devfreq/devfreq.c (ffffffff819cf7ae)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (ffffffff819d0d30)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff819d2aef)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/skbuff.c (ffffffff819edac3)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff819ff061)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/core/dst.c (ffffffff81a10fd8)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
```
```
In net/core/neighbour.c (ffffffff81a1238e)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/net-sysfs.c (ffffffff81a3b040)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/core/net-sysfs.c:proto_down_show
  - net/core/net-sysfs.c:group_show
  - net/core/net-sysfs.c:napi_defer_hard_irqs_show
  - net/core/net-sysfs.c:gro_flush_timeout_show
  - net/core/net-sysfs.c:tx_queue_len_show
  - net/core/net-sysfs.c:flags_show
  - net/core/net-sysfs.c:mtu_show
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:address_show
  - net/core/net-sysfs.c:name_assign_type_show
  - net/core/net-sysfs.c:link_mode_show
  - net/core/net-sysfs.c:type_show
  - net/core/net-sysfs.c:ifindex_show
  - net/core/net-sysfs.c:addr_len_show
  - net/core/net-sysfs.c:addr_assign_type_show
  - net/core/net-sysfs.c:dev_port_show
  - net/core/net-sysfs.c:dev_id_show
```
```
In net/core/page_pool.c (ffffffff81a3cd35)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release_page
```
```
In net/core/netpoll.c (ffffffff81a41a8e)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffffffff81a538e5)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_alloc_elem
```
```
In net/sched/sch_api.c (ffffffff81a70cef)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffffffff81a74a7f)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffffffff81a7b704)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (ffffffff81a7eade)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_lookup
  - net/sched/ematch.c:tcf_em_lookup
```
```
In net/netlink/af_netlink.c (ffffffff81a7ffa4)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/ipv4/route.c (ffffffff81a9a53f)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv4/ip_fragment.c (ffffffff81aa3158)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/raw.c (ffffffff81adc549)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81ae2498)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/arp.c (ffffffff81ae608c)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_format_neigh_entry
```
```
In net/ipv4/ipmr.c (ffffffff81b0fa15)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_vif_seq_stop
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:reg_vif_xmit
```
```
In net/ipv4/ipmr_base.c (ffffffff81b1432c)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1f81b)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff81b2491e)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/ipv6/ip6_output.c (ffffffff81b3b9e5)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_call_ra_chain
  - net/ipv6/ip6_output.c:ip6_call_ra_chain
```
```
In net/ipv6/route.c (ffffffff81b50638)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffffffff81b5bef5)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81b6bc8a)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/mcast.c (ffffffff81b72243)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/ipv6/mcast.c:inet6_mc_check
```
```
In net/ipv6/ip6mr.c (ffffffff81b86d69)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_stop
```
```
In net/packet/af_packet.c (ffffffff81b9b01c)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff81ba6d7e)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
  - net/rfkill/core.c:rfkill_fop_release
```
```
In arch/x86/pci/common.c (ffffffff81bce275)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
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
In arch/x86/events/core.c (ffffffff8100642e)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101a08b)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81052d11)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81055149)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ec67)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81093d5e)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
```
In kernel/fork.c (ffffffff810a42dd)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/fork.c:walk_process_tree
```
```
In kernel/exit.c (ffffffff810a9c2d)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:is_current_pgrp_orphaned
```
```
In kernel/resource.c (ffffffff810ae5bc)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/resource.c:iomem_is_exclusive
  - kernel/resource.c:iomem_map_sanity_check
  - kernel/resource.c:lookup_resource
  - kernel/resource.c:region_intersects
  - kernel/resource.c:find_next_iomem_res
  - kernel/resource.c:r_stop
```
```
In kernel/ptrace.c (ffffffff810b1e05)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff810b8f85)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:kill_pgrp
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sys.c (ffffffff810c09e5)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
```
```
In kernel/sched/core.c (ffffffff810e6524)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
```
```
In kernel/sched/topology.c (ffffffff8110213c)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/autogroup.c (ffffffff8110547f)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
```
In kernel/locking/spinlock.c (ffffffff81c38ac5)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
  - kernel/locking/spinlock.c:_raw_read_trylock
  - kernel/locking/spinlock.c:_raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock
```
```
In kernel/power/process.c (ffffffff81110efe)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/irq/spurious.c (ffffffff81121de1)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (ffffffff811259d2)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/rcu/tree.c (ffffffff81130a4d)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_momentary_dyntick_idle
  - kernel/rcu/tree.c:rcu_is_idle_cpu
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
  - kernel/rcu/tree.c:rcu_dynticks_eqs_enter
```
```
In kernel/livepatch/transition.c (ffffffff811381e9)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
```
```
In kernel/module.c (ffffffff81162bfa)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In kernel/pid_namespace.c (ffffffff8118371f)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/audit.c (ffffffff811883bd)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/tracepoint.c (ffffffff811aa10b)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/ftrace.c (ffffffff811acbdc)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811c3c10)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In kernel/trace/tracing_map.c (ffffffff811c7642)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
```
```
In kernel/trace/trace_functions.c (ffffffff811c9300)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811c991d)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811cca1f)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (ffffffff811d3891)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811db33d)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f4a24)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In kernel/bpf/hashtab.c (ffffffff8121d7d1)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/callchain.c (ffffffff8125358a)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/watch_queue.c (ffffffff8125b108)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/oom_kill.c (ffffffff81266ba3)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/swap.c (ffffffff8126df8b)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - mm/swap.c:put_devmap_managed_page
```
```
In mm/memory_hotplug.c (ffffffff812c6e03)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/zswap.c (ffffffff812d3905)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/mempolicy.c (ffffffff812e3708)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
```
```
In mm/memory-failure.c (ffffffff813135ae)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
```
```
In mm/zsmalloc.c (ffffffff81318d1e)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/exec.c (ffffffff8132daea)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/exec.c:search_binary_handler
  - fs/exec.c:search_binary_handler
  - fs/exec.c:de_thread
  - fs/exec.c:__do_sys_uselib
  - fs/exec.c:__do_sys_uselib
```
```
In fs/fcntl.c (ffffffff8133c4a9)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_getown
```
```
In fs/inode.c (ffffffff81346950)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
```
```
In fs/filesystems.c (ffffffff8134c088)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:filesystems_proc_show
  - fs/filesystems.c:__ia32_sys_sysfs
  - fs/filesystems.c:__x64_sys_sysfs
  - fs/filesystems.c:fs_name
  - fs/filesystems.c:fs_index
```
```
In fs/fs_struct.c (ffffffff81368531)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/notify/notification.c (ffffffff8137a6d5)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/io_uring.c (ffffffff81391d1d)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread_unpark
```
```
In fs/coredump.c (ffffffff813bffcb)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/netlink.c (ffffffff813cdecf)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In fs/proc/inode.c (ffffffff813d2075)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_put_link
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
  - fs/proc/inode.c:proc_entry_rundown
```
```
In fs/proc/generic.c (ffffffff813d921c)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff813dac0a)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/kernfs/inode.c (ffffffff813e5cb1)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/kernfs/dir.c (ffffffff813e761a)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In fs/devpts/inode.c (ffffffff813f0ac5)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/extents_status.c (ffffffff814010df)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:ext4_is_pending
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_scan_clu
  - fs/ext4/extents_status.c:ext4_es_scan_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
```
```
In fs/ext4/inode.c (ffffffff814189b8)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/mballoc.c (ffffffff8141c4ed)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_seq_structs_summary_stop
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ext4/super.c (ffffffff8144462c)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/jbd2/transaction.c (ffffffff814612c3)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:stop_this_handle
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_free_reserved
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:wait_transaction_locked
```
```
In fs/jbd2/journal.c (ffffffff81467abf)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_errno
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_transaction_committed
  - fs/jbd2/journal.c:jbd2_fc_end_commit_fallback
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
```
In fs/ecryptfs/main.c (ffffffff81483545)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/keys/keyring.c (ffffffff814bc7e6)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/avc.c (ffffffff814d1ac0)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/selinux/hooks.c (ffffffff814da35d)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/apparmor/policy.c (ffffffff8151e787)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In security/integrity/iint.c (ffffffff815392ba)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In block/blk-core.c (ffffffff81567e95)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In block/ioprio.c (ffffffff8157fea4)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - block/ioprio.c:__do_sys_ioprio_set
  - block/ioprio.c:__do_sys_ioprio_set
```
```
In block/blk-wbt.c (ffffffff8159d919)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In block/keyslot-manager.c (ffffffff815a501a)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In lib/percpu-refcount.c (ffffffff815b4ffb)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/sbitmap.c (ffffffff815eceec)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8161f729)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:edge_irq_handler
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
```
```
In drivers/pci/pci.c (ffffffff81632865)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/acpi/apei/ghes.c (ffffffff816efd45)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:__ghes_print_estatus
```
```
In drivers/xen/events/events_base.c (ffffffff8171654a)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__xen_evtchn_do_upcall
```
```
In drivers/regulator/core.c (ffffffff8172f9b0)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (ffffffff8173233b)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff81736855)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/tty/tty_buffer.c (ffffffff8173e82c)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8174145a)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/sysrq.c (ffffffff8174344e)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/tty/serial/serial_core.c (ffffffff817564be)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/base/power/wakeup.c (ffffffff817c764c)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_activate
```
```
In drivers/base/devcoredump.c (ffffffff817df7f6)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/block/loop.c (ffffffff817e11a1)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
```
```
In drivers/scsi/scsi_lib.c (ffffffff8182bdb0)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
```
```
In drivers/scsi/sd.c (ffffffff8183857d)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffff81840d60)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_debug_helper
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffffffff8184b489)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-sata.c (ffffffff81859651)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In drivers/net/wwan/wwan_core.c (ffffffff8188820c)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In drivers/input/serio/serio.c (ffffffff8190f59b)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff819140a6)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/power/supply/power_supply_core.c (ffffffff819386e5)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/md/dm.c (ffffffff81963b05)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_next_uevent_seq
```
```
In drivers/edac/edac_device.c (ffffffff81971955)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffff81973725)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81974219)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819af53c)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/devfreq/devfreq.c (ffffffff819b48de)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (ffffffff819b5fdf)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff819b7d9f)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/skbuff.c (ffffffff819d59a3)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/core/skbuff.c:msg_zerocopy_alloc
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff819e5901)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/core/dst.c (ffffffff819f7e48)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
```
```
In net/core/neighbour.c (ffffffff819f8fbe)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/net-sysfs.c (ffffffff81a225e0)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/core/net-sysfs.c:proto_down_show
  - net/core/net-sysfs.c:group_show
  - net/core/net-sysfs.c:napi_defer_hard_irqs_show
  - net/core/net-sysfs.c:gro_flush_timeout_show
  - net/core/net-sysfs.c:tx_queue_len_show
  - net/core/net-sysfs.c:flags_show
  - net/core/net-sysfs.c:mtu_show
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:address_show
  - net/core/net-sysfs.c:name_assign_type_show
  - net/core/net-sysfs.c:link_mode_show
  - net/core/net-sysfs.c:type_show
  - net/core/net-sysfs.c:ifindex_show
  - net/core/net-sysfs.c:addr_len_show
  - net/core/net-sysfs.c:addr_assign_type_show
  - net/core/net-sysfs.c:dev_port_show
  - net/core/net-sysfs.c:dev_id_show
```
```
In net/core/page_pool.c (ffffffff81a23a75)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release_page
```
```
In net/core/netpoll.c (ffffffff81a26551)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffffffff81a50dec)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/sched/sch_api.c (ffffffff81a5963f)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffffffff81a5d61f)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffffffff81a64494)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (ffffffff81a6793e)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_lookup
  - net/sched/ematch.c:tcf_em_lookup
```
```
In net/netlink/af_netlink.c (ffffffff81a68eb5)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/ipv4/route.c (ffffffff81a8582c)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv4/ip_fragment.c (ffffffff81a8e16e)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/raw.c (ffffffff81ac74b9)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81acd3b8)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/arp.c (ffffffff81ad136c)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_format_neigh_entry
```
```
In net/ipv4/ipmr.c (ffffffff81afd615)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_vif_seq_stop
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:reg_vif_xmit
```
```
In net/ipv4/ipmr_base.c (ffffffff81b0218c)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0d6fb)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff81b1253e)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/ipv6/ip6_output.c (ffffffff81b2d056)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff81b3dd18)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4a0b7)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81b59faa)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/ip6mr.c (ffffffff81b75a34)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_stop
```
```
In net/packet/af_packet.c (ffffffff81b8aa09)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff81b95f0e)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
  - net/rfkill/core.c:rfkill_fop_release
```
```
In arch/x86/pci/common.c (ffffffff81bc1c35)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
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
In arch/x86/events/core.c (ffffffff810067ae)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101c91b)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105b211)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8105dae9)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81068374)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810a3b3e)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
```
In kernel/fork.c (ffffffff810b5afd)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/fork.c:walk_process_tree
```
```
In kernel/exit.c (ffffffff810bb75b)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:is_current_pgrp_orphaned
```
```
In kernel/resource.c (ffffffff810c013c)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/resource.c:iomem_is_exclusive
  - kernel/resource.c:iomem_map_sanity_check
  - kernel/resource.c:lookup_resource
  - kernel/resource.c:region_intersects
  - kernel/resource.c:find_next_iomem_res
  - kernel/resource.c:r_stop
```
```
In kernel/ptrace.c (ffffffff810c42c5)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff810cb515)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:kill_pgrp
  - kernel/signal.c:kill_something_info
```
```
In kernel/sys.c (ffffffff810d34d5)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
```
```
In kernel/sched/core.c (ffffffff810fda5b)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
```
```
In kernel/sched/topology.c (ffffffff8111e6b9)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/autogroup.c (ffffffff811230ef)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
```
In kernel/sched/core_sched.c (ffffffff8112c695)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/sched/core_sched.c:sched_core_share_pid
```
```
In kernel/locking/spinlock.c (ffffffff81d573a5)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
  - kernel/locking/spinlock.c:_raw_read_trylock
  - kernel/locking/spinlock.c:_raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock
```
```
In kernel/power/process.c (ffffffff811309ea)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/irq/spurious.c (ffffffff81142391)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (ffffffff81146175)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/rcu/tree.c (ffffffff81d4900f)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dynticks_inc
```
```
In kernel/livepatch/transition.c (ffffffff8115af73)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
```
```
In kernel/module.c (ffffffff8118817a)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In kernel/pid_namespace.c (ffffffff811ab7ff)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/audit.c (ffffffff811b08dd)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/tracepoint.c (ffffffff811d3c7b)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/ftrace.c (ffffffff811d683c)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811eee80)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In kernel/trace/tracing_map.c (ffffffff811f2d73)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
```
```
In kernel/trace/trace_functions.c (ffffffff811f4d2f)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811f53e7)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811f9169)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (ffffffff81200711)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff8120894d)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In kernel/trace/trace_uprobe.c (ffffffff81225dd4)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In kernel/bpf/hashtab.c (ffffffff812568a7)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/callchain.c (ffffffff8128eeca)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/watch_queue.c (ffffffff81296f08)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/oom_kill.c (ffffffff812a33a3)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/swap.c (ffffffff812aaed8)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - mm/swap.c:put_devmap_managed_page
```
```
In mm/zswap.c (ffffffff81319587)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/mempolicy.c (ffffffff8132a928)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
```
```
In mm/kfence/core.c (ffffffff8133c70c)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - mm/kfence/core.c:__kfence_alloc
```
```
In mm/memory-failure.c (ffffffff8136006e)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
```
```
In mm/zsmalloc.c (ffffffff8136530e)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In mm/bootmem_info.c (ffffffff8136cb33)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In fs/exec.c (ffffffff8137b2ca)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/exec.c:search_binary_handler
  - fs/exec.c:search_binary_handler
  - fs/exec.c:de_thread
  - fs/exec.c:__do_sys_uselib
  - fs/exec.c:__do_sys_uselib
```
```
In fs/fcntl.c (ffffffff8138a1ee)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_getown
```
```
In fs/inode.c (ffffffff813943b0)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
  - fs/inode.c:ihold
```
```
In fs/filesystems.c (ffffffff81399ec8)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:filesystems_proc_show
  - fs/filesystems.c:__ia32_sys_sysfs
  - fs/filesystems.c:__x64_sys_sysfs
  - fs/filesystems.c:fs_name
  - fs/filesystems.c:fs_index
```
```
In fs/fs_struct.c (ffffffff813b7231)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/notify/notification.c (ffffffff813c7355)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/io_uring.c (ffffffff813df57d)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread_unpark
```
```
In fs/coredump.c (ffffffff8140fdfb)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/netlink.c (ffffffff8141f1ff)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In fs/proc/inode.c (ffffffff814235a5)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_put_link
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
  - fs/proc/inode.c:proc_entry_rundown
```
```
In fs/proc/generic.c (ffffffff8142a94c)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff8142c3aa)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/kernfs/inode.c (ffffffff81437831)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/kernfs/dir.c (ffffffff8143932a)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In fs/devpts/inode.c (ffffffff814429b5)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/extents_status.c (ffffffff8145365c)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:ext4_is_pending
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_scan_clu
  - fs/ext4/extents_status.c:ext4_es_scan_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
```
```
In fs/ext4/inode.c (ffffffff8146bbb3)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/mballoc.c (ffffffff8146f8ed)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_seq_structs_summary_stop
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ext4/super.c (ffffffff8149842c)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/ext4/fast_commit.c (ffffffff814afbaf)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_mark_ineligible
```
```
In fs/jbd2/transaction.c (ffffffff814b67b6)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:stop_this_handle
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_free_reserved
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:wait_transaction_locked
```
```
In fs/jbd2/journal.c (ffffffff814bdf1f)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_errno
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_transaction_committed
  - fs/jbd2/journal.c:jbd2_fc_end_commit_fallback
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
```
In fs/ecryptfs/main.c (ffffffff814dacc5)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/keys/keyring.c (ffffffff81515206)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/avc.c (ffffffff8152a840)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/selinux/hooks.c (ffffffff8153325d)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/apparmor/policy.c (ffffffff8157c8d7)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In security/integrity/iint.c (ffffffff81597afa)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In block/blk-core.c (ffffffff815cc4e5)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In block/ioprio.c (ffffffff815e4e17)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
  - block/ioprio.c:__do_sys_ioprio_set
```
```
In block/blk-wbt.c (ffffffff81605fd9)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In block/keyslot-manager.c (ffffffff8160daba)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In lib/percpu-refcount.c (ffffffff8161b356)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/sbitmap.c (ffffffff81659e0c)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8168ecb9)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:edge_irq_handler
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
```
```
In drivers/pci/pci.c (ffffffff816a29c5)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/acpi/apei/ghes.c (ffffffff81769de5)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:__ghes_print_estatus
```
```
In drivers/xen/events/events_base.c (ffffffff817937da)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__xen_evtchn_do_upcall
```
```
In drivers/regulator/core.c (ffffffff817af7ac)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (ffffffff817b2b2e)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff817b7215)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/tty/tty_buffer.c (ffffffff817befac)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/tty/tty_jobctrl.c (ffffffff817c1eba)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/sysrq.c (ffffffff817c3eee)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/tty/serial/serial_core.c (ffffffff817d9bee)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/base/power/wakeup.c (ffffffff81851ca8)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_report_event
```
```
In drivers/base/devcoredump.c (ffffffff8186b27e)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/block/loop.c (ffffffff81870b71)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b79a4)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
```
```
In drivers/scsi/sd.c (ffffffff818c2e8d)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffff818cd8bc)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_debug_helper
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffffffff818d889b)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-sata.c (ffffffff818e8201)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In drivers/input/serio/serio.c (ffffffff819b03db)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff819b61c6)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/power/supply/power_supply_core.c (ffffffff819dcc45)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/md/dm.c (ffffffff81a0baa5)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_next_uevent_seq
```
```
In drivers/edac/edac_device.c (ffffffff81a1a605)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffff81a1c425)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81a1cf19)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81a5de6c)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/devfreq/devfreq.c (ffffffff81a6341e)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (ffffffff81a64b1f)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff81a66c9f)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/skbuff.c (ffffffff81a855d3)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/core/skbuff.c:msg_zerocopy_alloc
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff81a95db1)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/core/dst.c (ffffffff81aa9a58)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
```
```
In net/core/neighbour.c (ffffffff81aaab9e)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/net-sysfs.c (ffffffff81ad65f0)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/core/net-sysfs.c:proto_down_show
  - net/core/net-sysfs.c:group_show
  - net/core/net-sysfs.c:napi_defer_hard_irqs_show
  - net/core/net-sysfs.c:gro_flush_timeout_show
  - net/core/net-sysfs.c:tx_queue_len_show
  - net/core/net-sysfs.c:flags_show
  - net/core/net-sysfs.c:mtu_show
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:address_show
  - net/core/net-sysfs.c:name_assign_type_show
  - net/core/net-sysfs.c:link_mode_show
  - net/core/net-sysfs.c:type_show
  - net/core/net-sysfs.c:ifindex_show
  - net/core/net-sysfs.c:addr_len_show
  - net/core/net-sysfs.c:addr_assign_type_show
  - net/core/net-sysfs.c:dev_port_show
  - net/core/net-sysfs.c:dev_id_show
```
```
In net/core/page_pool.c (ffffffff81ad80cf)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release_page
```
```
In net/core/netpoll.c (ffffffff81adb2cc)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffffffff81b09e99)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/sched/sch_api.c (ffffffff81b126ef)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffffffff81b1662f)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffffffff81b1d8a4)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (ffffffff81b20eae)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_lookup
  - net/sched/ematch.c:tcf_em_lookup
```
```
In net/netlink/af_netlink.c (ffffffff81b22485)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/ipv4/route.c (ffffffff81b3fffc)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv4/ip_fragment.c (ffffffff81b4935e)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffff81b4d795)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (0)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81b85cd9)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_send_hdrinc
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81b8bd78)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/arp.c (ffffffff81b8fe07)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_format_neigh_entry
```
```
In net/ipv4/ipmr.c (ffffffff81bbee75)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_vif_seq_stop
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:reg_vif_xmit
```
```
In net/ipv4/ipmr_base.c (ffffffff81bc402c)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd103b)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff81bd640e)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/ipv6/ip6_output.c (ffffffff81bf321a)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff81c04849)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffffffff81c11417)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81c20a84)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/ip6mr.c (ffffffff81c40456)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_stop
```
```
In net/packet/af_packet.c (ffffffff81c524ef)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff81c62966)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
  - net/rfkill/core.c:rfkill_fop_release
```
```
In arch/x86/pci/common.c (ffffffff81c92245)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
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
In arch/x86/events/core.c (ffffffff81005bbf)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101f2bb)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81f15a2f)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8106a1e8)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810b821e)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
```
In kernel/sched/build_utility.c (ffffffff81144d6b)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:build_overlap_sched_groups
```
```
In kernel/locking/spinlock.c (ffffffff8114ecdb)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:__raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_irq
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
  - kernel/locking/spinlock.c:_raw_read_unlock
  - kernel/locking/spinlock.c:_raw_read_trylock
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock
```
```
In kernel/irq/spurious.c (ffffffff81165eea)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (ffffffff8116a539)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/rcu/tree.c (ffffffff81f183d1)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dynticks_inc
```
```
In kernel/module/main.c (ffffffff8118e26e)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In kernel/audit.c (ffffffff811e2ae9)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_start
```
```
In kernel/trace/ftrace.c (ffffffff8120b9d1)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In kernel/trace/trace.c (ffffffff812272f0)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In kernel/trace/tracing_map.c (ffffffff8122c32a)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
```
```
In kernel/trace/trace_functions.c (ffffffff8122de5d)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8122ec41)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:func_prolog_preempt_disable
```
```
In kernel/trace/trace_functions_graph.c (ffffffff81232fe9)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (ffffffff8123a857)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff81243f6a)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In kernel/bpf/hashtab.c (ffffffff8129f211)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/callchain.c (ffffffff812e3de8)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/watch_queue.c (ffffffff812ed52c)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/oom_kill.c (ffffffff812fb2b3)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/vmscan.c (ffffffff81310d5a)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_throttle
```
```
In mm/zswap.c (ffffffff8138484c)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/kfence/core.c (ffffffff813af9b4)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - mm/kfence/core.c:__kfence_alloc
```
```
In mm/memremap.c (ffffffff813e6f85)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In mm/bootmem_info.c (ffffffff813eaec3)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In fs/inode.c (ffffffff81416123)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
  - fs/inode.c:ihold
```
```
In fs/notify/notification.c (ffffffff8144e735)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/mbcache.c (ffffffff81481bc9)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_or_get
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/coredump.c (ffffffff814857ca)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/netlink.c (ffffffff81497040)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In fs/proc/inode.c (ffffffff8149c1d5)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_put_link
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
  - fs/proc/inode.c:proc_entry_rundown
```
```
In fs/kernfs/inode.c (ffffffff814b25a9)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/kernfs/dir.c (ffffffff814b436a)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In fs/devpts/inode.c (ffffffff814be735)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/mballoc.c (ffffffff814f80ad)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ext4/xattr.c (ffffffff81532a80)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_evict_ea_inode
```
```
In fs/jbd2/transaction.c (ffffffff8153d3df)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:stop_this_handle
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/ecryptfs/main.c (ffffffff81568645)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/selinux/avc.c (ffffffff815c020f)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/apparmor/policy.c (ffffffff8161ade6)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In block/blk-core.c (ffffffff816782c5)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In block/blk-mq-tag.c (ffffffff8168c84e)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In block/blk-wbt.c (ffffffff816ba419)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In block/blk-crypto-profile.c (ffffffff816c2369)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In io_uring/io_uring.c (ffffffff81e8e4a9)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_sq_thread_unpark
  - io_uring/io_uring.c:io_async_cancel
  - io_uring/io_uring.c:__io_arm_poll_handler
  - io_uring/io_uring.c:io_poll_check_events
```
```
In lib/percpu-refcount.c (ffffffff816e8b46)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/sbitmap.c (ffffffff817724cd)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff817ac9f4)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:edge_irq_handler
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
  - drivers/gpio/gpiolib-cdev.c:process_hw_ts
```
```
In drivers/pci/pci.c (ffffffff817c4b62)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/acpi/apei/ghes.c (ffffffff8189e915)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
  - drivers/acpi/apei/ghes.c:__ghes_print_estatus
```
```
In drivers/regulator/core.c (ffffffff818eab64)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (ffffffff818ef657)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_deassert
  - drivers/reset/core.c:reset_control_assert
  - drivers/reset/core.c:reset_control_rearm
  - drivers/reset/core.c:reset_control_rearm
  - drivers/reset/core.c:reset_control_reset
```
```
In drivers/tty/tty_buffer.c (ffffffff818fb489)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/tty/serial/serial_core.c (ffffffff81918619)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/base/power/runtime.c (ffffffff8198f5d5)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_drop_usage_count
```
```
In drivers/base/power/wakeup.c (ffffffff819970e0)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_activate
```
```
In drivers/base/devcoredump.c (ffffffff819b3fdf)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/scsi/scsi_lib.c (ffffffff81a03213)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
```
```
In drivers/scsi/sd.c (ffffffff81a0f09c)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffff81a1c897)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffffffff81a299fb)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-sata.c (ffffffff81a39ca1)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In drivers/input/serio/serio.c (ffffffff81b0f12d)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff81b1576b)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81b40ee5)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/md/dm.c (ffffffff81b73f45)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_next_uevent_seq
```
```
In drivers/edac/edac_device.c (ffffffff81b83395)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffff81b854d5)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81b86008)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81bce044)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/devfreq/devfreq.c (ffffffff81bd233d)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_resume_device
  - drivers/devfreq/devfreq.c:devfreq_suspend_device
```
```
In drivers/devfreq/devfreq-event.c (ffffffff81bd5809)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff81bd81b3)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/skbuff.c (ffffffff81bf838d)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff81c0ea61)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In net/core/dst.c (ffffffff81c21ea9)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
```
```
In net/core/neighbour.c (ffffffff81c28faf)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/page_pool.c (ffffffff81c58e90)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release_page
```
```
In net/core/netpoll.c (ffffffff81c5c7d2)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffffffff81c90112)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/netlink/af_netlink.c (ffffffff81cae387)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/ipv4/route.c (ffffffff81ccc945)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv4/ip_fragment.c (ffffffff81cd69ff)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffff81cdb002)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (0)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81d16c1c)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (ffffffff81d18a5c)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_state.c (ffffffff81d6cb9e)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/ipv6/ip6_output.c (ffffffff81d89323)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In net/ipv6/route.c (ffffffff81d9d9ca)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_gc
```
```
In net/ipv6/raw.c (ffffffff81dbd7f3)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81df457f)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff81e05246)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
  - net/rfkill/core.c:rfkill_fop_release
```
```
In arch/x86/pci/common.c (ffffffff81e418b5)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
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
In arch/x86/events/core.c (ffffffff8100750f)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff8102399b)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff820bd15f)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81079fa8)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810d3a3e)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
```
In kernel/panic.c (ffffffff810e9f32)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/panic.c:__warn_printk
  - kernel/panic.c:__warn_printk
```
```
In kernel/exit.c (ffffffff810f1fc5)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/exit.c:make_task_dead
```
```
In kernel/sched/build_utility.c (ffffffff8117115b)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:build_overlap_sched_groups
```
```
In kernel/locking/spinlock.c (ffffffff8117debe)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:__raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_irq
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
  - kernel/locking/spinlock.c:_raw_read_unlock
  - kernel/locking/spinlock.c:_raw_read_trylock
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock
```
```
In kernel/irq/spurious.c (ffffffff81199fda)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (ffffffff8119f061)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_create
```
```
In kernel/rcu/tree.c (ffffffff811ba316)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:rcu_momentary_dyntick_idle
```
```
In kernel/module/main.c (ffffffff811cd2d2)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In kernel/audit.c (ffffffff812289c9)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_start
```
```
In kernel/trace/ftrace.c (ffffffff81254420)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In kernel/trace/trace.c (ffffffff81272780)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In kernel/trace/tracing_map.c (ffffffff81277e5a)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
```
```
In kernel/trace/trace_functions.c (ffffffff81279cfd)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8127ac61)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:func_prolog_preempt_disable
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8127f779)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (ffffffff8128940a)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff81291baa)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In kernel/events/callchain.c (ffffffff8134c4f8)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/hw_breakpoint.c (ffffffff8134de3b)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In kernel/context_tracking.c (ffffffff820bff3f)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/context_tracking.c:ct_kernel_exit_state
```
```
In kernel/watch_queue.c (ffffffff813578fc)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/oom_kill.c (ffffffff813652a3)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/vmscan.c (ffffffff81384238)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_throttle
```
```
In mm/rmap.c (ffffffff813d7fd6)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
```
```
In mm/zswap.c (ffffffff8140247c)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/kfence/core.c (ffffffff8142ff7e)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - mm/kfence/core.c:__kfence_alloc
```
```
In mm/memremap.c (ffffffff8146ebd5)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In mm/bootmem_info.c (ffffffff814730c3)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In fs/inode.c (ffffffff814a11a3)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
  - fs/inode.c:ihold
```
```
In fs/notify/notification.c (ffffffff814dce55)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/mbcache.c (ffffffff81514c46)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/coredump.c (ffffffff81518e2f)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/netlink.c (ffffffff8152b050)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In fs/proc/inode.c (ffffffff81530b05)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_put_link
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
  - fs/proc/inode.c:proc_entry_rundown
```
```
In fs/kernfs/inode.c (ffffffff81549129)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/kernfs/dir.c (ffffffff8154b20a)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In fs/devpts/inode.c (ffffffff815565b5)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/mballoc.c (ffffffff815926ab)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ext4/xattr.c (ffffffff815d0f50)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_evict_ea_inode
```
```
In fs/jbd2/transaction.c (ffffffff815dbbff)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:stop_this_handle
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/ecryptfs/main.c (ffffffff8160bf25)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/selinux/avc.c (ffffffff8166c73f)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/apparmor/policy.c (ffffffff816ce006)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_learning_profile
```
```
In block/blk-core.c (ffffffff817345b5)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In block/blk-mq-tag.c (ffffffff8174b01e)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In block/blk-wbt.c (ffffffff8177a9a9)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In block/blk-crypto-profile.c (ffffffff81783689)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In io_uring/sqpoll.c (ffffffff8179a95d)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread_unpark
```
```
In io_uring/poll.c (ffffffff8179cdda)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_check_events
```
```
In io_uring/cancel.c (ffffffff8179e822)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - io_uring/cancel.c:io_sync_cancel
  - io_uring/cancel.c:io_sync_cancel
  - io_uring/cancel.c:io_async_cancel
```
```
In lib/percpu-refcount.c (ffffffff817d8b91)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff818c4d18)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:edge_irq_handler
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
  - drivers/gpio/gpiolib-cdev.c:process_hw_ts
```
```
In drivers/pci/pci.c (ffffffff818e1b42)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/acpi/apei/ghes.c (ffffffff819e7c35)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
  - drivers/acpi/apei/ghes.c:__ghes_print_estatus
```
```
In drivers/regulator/core.c (ffffffff81a415e4)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (ffffffff81a47377)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_deassert
  - drivers/reset/core.c:reset_control_assert
  - drivers/reset/core.c:reset_control_rearm
  - drivers/reset/core.c:reset_control_rearm
  - drivers/reset/core.c:reset_control_reset
```
```
In drivers/tty/tty_buffer.c (ffffffff81a546e9)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/tty/serial/serial_core.c (ffffffff81a7404f)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/char/random.c (ffffffff81a949e2)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff81aff6e5)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_drop_usage_count
```
```
In drivers/base/power/wakeup.c (ffffffff81b087c0)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_activate
```
```
In drivers/base/devcoredump.c (ffffffff81b28e73)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b81aab)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
```
```
In drivers/scsi/sd.c (ffffffff81b8f04c)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffff81b9db37)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffffffff81bac53d)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-sata.c (ffffffff81bbef81)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In drivers/input/serio/serio.c (ffffffff81c9f4bd)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff81ca6bdb)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81cd7575)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/md/dm.c (ffffffff81d10ec5)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_next_uevent_seq
```
```
In drivers/edac/edac_device.c (ffffffff81d21d25)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffff81d24515)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81d25398)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d784f4)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/devfreq/devfreq.c (ffffffff81d7dfed)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_resume_device
  - drivers/devfreq/devfreq.c:devfreq_suspend_device
```
```
In drivers/devfreq/devfreq-event.c (ffffffff81d81e29)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff81d84bb2)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/skbuff.c (ffffffff81da71df)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff81dbeb71)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In net/core/dst.c (ffffffff81dd4429)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
```
```
In net/core/neighbour.c (ffffffff81ddbccf)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/page_pool.c (ffffffff81e0edd0)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release_page
```
```
In net/core/netpoll.c (ffffffff81e12ec2)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffffffff81e492a5)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_alloc_elem
```
```
In net/netlink/af_netlink.c (ffffffff81e6b81e)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/ipv4/route.c (ffffffff81e8cb01)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv4/ip_fragment.c (ffffffff81e96ff0)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffff81e9b8bf)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (0)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81edd3db)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (ffffffff81ee18ec)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_state.c (ffffffff81f37f9e)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/ipv6/ip6_output.c (ffffffff81f57133)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
```
```
In net/ipv6/route.c (ffffffff81f6c90a)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_gc
```
```
In net/ipv6/raw.c (ffffffff81f8dd33)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81fc938f)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff81fda4c6)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
  - net/rfkill/core.c:rfkill_fop_release
```
```
In arch/x86/pci/common.c (ffffffff8201bf15)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
```
```
In lib/bug.c (ffffffff8201ec89)
Location: arch/x86/include/asm/atomic.h:163
Inline: True
Inline callers:
  - lib/bug.c:report_bug
  - lib/bug.c:report_bug
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
In arch/x86/events/core.c (ffffffff81006d2f)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff810236bb)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8213eb6f)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8107c23d)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810d6e1e)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
```
In kernel/panic.c (ffffffff810f5b32)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - kernel/panic.c:__warn_printk
  - kernel/panic.c:__warn_printk
```
```
In kernel/exit.c (ffffffff810fdf45)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - kernel/exit.c:make_task_dead
```
```
In kernel/sched/build_utility.c (ffffffff8118195b)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:build_overlap_sched_groups
```
```
In kernel/locking/spinlock.c (ffffffff8118eb5e)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:__raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_irq
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
  - kernel/locking/spinlock.c:_raw_read_unlock
  - kernel/locking/spinlock.c:_raw_read_trylock
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock
```
```
In kernel/irq/spurious.c (ffffffff811abbfe)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (ffffffff811b0f52)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_create
```
```
In kernel/rcu/tree.c (ffffffff811ccc65)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:rcu_momentary_dyntick_idle
```
```
In kernel/module/main.c (ffffffff811e0bb2)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
```
```
In kernel/audit.c (ffffffff8123efc9)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_start
```
```
In kernel/watchdog.c (ffffffff8125e47a)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/trace/ftrace.c (ffffffff8126b310)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
```
```
In kernel/trace/trace.c (ffffffff81289a80)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
```
```
In kernel/trace/tracing_map.c (ffffffff8128f89a)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
```
```
In kernel/trace/trace_functions.c (ffffffff8129173d)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff81292781)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:func_prolog_preempt_disable
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8129c309)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (ffffffff812a616e)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff812aee0a)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In kernel/events/callchain.c (ffffffff8137d548)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/hw_breakpoint.c (ffffffff8137eed1)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
```
```
In kernel/context_tracking.c (ffffffff82141dbf)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - kernel/context_tracking.c:ct_kernel_exit_state
```
```
In kernel/watch_queue.c (ffffffff8138915e)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/oom_kill.c (ffffffff81397763)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/vmscan.c (ffffffff813b5cd5)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_throttle
```
```
In mm/rmap.c (ffffffff8140ca78)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
```
```
In mm/zswap.c (ffffffff8143533c)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/kfence/core.c (ffffffff8146590e)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - mm/kfence/core.c:__kfence_alloc
```
```
In mm/memremap.c (ffffffff814a3395)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
```
```
In mm/bootmem_info.c (ffffffff814a7833)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In fs/inode.c (ffffffff814d64b3)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
  - fs/inode.c:ihold
```
```
In fs/notify/notification.c (ffffffff815136b5)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/mbcache.c (ffffffff8154c646)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/coredump.c (ffffffff8155072f)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/netlink.c (ffffffff815633e0)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In fs/proc/inode.c (ffffffff81568c85)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_put_link
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
  - fs/proc/inode.c:proc_entry_rundown
```
```
In fs/kernfs/inode.c (ffffffff81580d05)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/kernfs/dir.c (ffffffff81582e5a)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
```
```
In fs/devpts/inode.c (ffffffff8158e375)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/mballoc.c (ffffffff815c963d)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ext4/xattr.c (ffffffff81608b00)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_evict_ea_inode
```
```
In fs/jbd2/transaction.c (ffffffff816136bf)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:stop_this_handle
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/ecryptfs/main.c (ffffffff81643e05)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/selinux/avc.c (ffffffff816a4a5a)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/apparmor/policy.c (ffffffff81706c66)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_learning_profile
```
```
In block/blk-core.c (ffffffff817709b5)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
```
```
In block/blk-wbt.c (ffffffff817b9c65)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In block/blk-crypto-profile.c (ffffffff817c3979)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
```
```
In io_uring/sqpoll.c (ffffffff817dba0d)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread_unpark
```
```
In io_uring/poll.c (ffffffff817de004)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_check_events
```
```
In io_uring/cancel.c (ffffffff817dfa12)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - io_uring/cancel.c:io_sync_cancel
  - io_uring/cancel.c:io_sync_cancel
  - io_uring/cancel.c:io_async_cancel
```
```
In lib/percpu-refcount.c (ffffffff81818078)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff81907de8)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:edge_irq_handler
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
  - drivers/gpio/gpiolib-cdev.c:process_hw_ts
```
```
In drivers/pci/pci.c (ffffffff81924f82)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a30345)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
  - drivers/acpi/apei/ghes.c:__ghes_print_estatus
```
```
In drivers/regulator/core.c (ffffffff81a8b6bf)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (ffffffff81a91517)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_deassert
  - drivers/reset/core.c:reset_control_assert
  - drivers/reset/core.c:reset_control_rearm
  - drivers/reset/core.c:reset_control_rearm
  - drivers/reset/core.c:reset_control_reset
```
```
In drivers/tty/tty_buffer.c (ffffffff81a9ecc9)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/tty/serial/serial_core.c (ffffffff81abe6d3)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:serial_core_remove_one_port
```
```
In drivers/char/random.c (ffffffff81ae0202)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff81b4da95)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_drop_usage_count
```
```
In drivers/base/power/wakeup.c (ffffffff81b567f0)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_activate
```
```
In drivers/base/devcoredump.c (ffffffff81b79023)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd57e4)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
```
```
In drivers/scsi/sd.c (ffffffff81be519c)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffff81bf4157)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffffffff81c036cd)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-sata.c (ffffffff81c16c31)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
```
```
In drivers/input/serio/serio.c (ffffffff81d067fd)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff81d0e31b)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81d3f745)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/md/dm.c (ffffffff81d7a355)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_next_uevent_seq
```
```
In drivers/edac/edac_device.c (ffffffff81d8af25)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffff81d8d725)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81d8e5d8)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de6434)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/devfreq/devfreq.c (ffffffff81dec36d)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_resume_device
  - drivers/devfreq/devfreq.c:devfreq_suspend_device
```
```
In drivers/devfreq/devfreq-event.c (ffffffff81df01e9)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
```
```
In net/core/skbuff.c (ffffffff81e1928f)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff81e2e881)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
```
```
In net/core/neighbour.c (ffffffff81e4ca1f)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/page_pool.c (ffffffff81e82590)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release_page
```
```
In net/core/netpoll.c (ffffffff81e867ec)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffffffff81ea49c5)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_alloc_elem
```
```
In net/netlink/af_netlink.c (ffffffff81ec786a)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/ipv4/route.c (ffffffff81eeb231)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv4/ip_fragment.c (ffffffff81ef57e1)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffff81efc0e9)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/tcp.c (0)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81f3c629)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (ffffffff81f4131c)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/igmp.c (0)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff81f9798e)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/xfrm/xfrm_output.c (0)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81fb6a6a)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
```
```
In net/ipv6/route.c (ffffffff81fcc9cc)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_gc
```
```
In net/ipv6/raw.c (ffffffff81fee51d)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff82029cf9)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff8205618a)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
  - net/rfkill/core.c:rfkill_fop_release
```
```
In arch/x86/pci/common.c (ffffffff8209c5b5)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
```
```
In lib/bug.c (ffffffff8209ec99)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - lib/bug.c:report_bug
  - lib/bug.c:report_bug
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
In arch/x86/events/core.c (ffffffff8100c42f)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff810297eb)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff82220b8f)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810df67d)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
```
In kernel/panic.c (ffffffff810feee2)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - kernel/panic.c:__warn_printk
  - kernel/panic.c:__warn_printk
```
```
In kernel/exit.c (ffffffff81106bf5)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - kernel/exit.c:make_task_dead
```
```
In kernel/sched/build_utility.c (ffffffff8119023a)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:build_overlap_sched_groups
```
```
In kernel/locking/spinlock.c (ffffffff8119d50e)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:__raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_irq
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
  - kernel/locking/spinlock.c:_raw_read_unlock
  - kernel/locking/spinlock.c:_raw_read_trylock
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock
```
```
In kernel/irq/spurious.c (ffffffff811bb7fe)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (ffffffff811c0cd2)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_create
```
```
In kernel/rcu/tree.c (ffffffff811e1677)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_report_cpu_starting
  - kernel/rcu/tree.c:rcu_momentary_dyntick_idle
```
```
In kernel/module/main.c (ffffffff811f68e2)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
```
```
In kernel/audit.c (ffffffff81258e31)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_start
```
```
In kernel/watchdog.c (ffffffff812783ba)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/trace/ftrace.c (ffffffff812857c0)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
```
```
In kernel/trace/trace.c (ffffffff812a4e00)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
```
```
In kernel/trace/tracing_map.c (ffffffff812aadfa)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
```
```
In kernel/trace/trace_functions.c (ffffffff812acd4d)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff812ade67)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:func_prolog_preempt_disable
```
```
In kernel/trace/trace_functions_graph.c (ffffffff812b79e9)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (ffffffff812c1c8e)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff812cb32a)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In kernel/events/core.c (ffffffff81394c47)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
```
```
In kernel/events/callchain.c (ffffffff813a67a8)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/events/hw_breakpoint.c (ffffffff813a8131)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
```
```
In kernel/context_tracking.c (ffffffff8222413f)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - kernel/context_tracking.c:ct_kernel_exit_state
```
```
In kernel/watch_queue.c (ffffffff813b2bae)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/oom_kill.c (ffffffff813c1593)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/vmscan.c (ffffffff813deb95)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_throttle
```
```
In mm/rmap.c (ffffffff8143b23d)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - mm/rmap.c:folio_remove_rmap_pmd
  - mm/rmap.c:folio_remove_rmap_ptes
  - mm/rmap.c:folio_add_file_rmap_pmd
  - mm/rmap.c:folio_add_file_rmap_ptes
  - mm/rmap.c:folio_add_anon_rmap_pmd
  - mm/rmap.c:folio_add_anon_rmap_ptes
```
```
In mm/zswap.c (ffffffff8146e42e)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/kfence/core.c (ffffffff81494bee)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - mm/kfence/core.c:__kfence_alloc
```
```
In mm/memremap.c (ffffffff814d4235)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
```
```
In mm/bootmem_info.c (ffffffff814d8863)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In fs/open.c (ffffffff814d98ca)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/file_table.c (ffffffff814e2abf)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/inode.c (ffffffff81508883)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
  - fs/inode.c:ihold
```
```
In fs/notify/notification.c (ffffffff81547b45)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/mbcache.c (ffffffff81582476)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/coredump.c (ffffffff815865bf)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/netlink.c (ffffffff81599ad0)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In fs/proc/inode.c (ffffffff815a12a5)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_put_link
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
  - fs/proc/inode.c:proc_entry_rundown
```
```
In fs/kernfs/inode.c (ffffffff815b977a)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/kernfs/dir.c (ffffffff815bba8a)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
```
```
In fs/devpts/inode.c (ffffffff815c70a5)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/mballoc.c (ffffffff81602411)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ext4/xattr.c (ffffffff81641840)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_evict_ea_inode
```
```
In fs/jbd2/transaction.c (ffffffff8164c4bf)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:stop_this_handle
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/ecryptfs/main.c (ffffffff8167d395)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/selinux/avc.c (ffffffff816e14ba)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/apparmor/policy.c (ffffffff81744706)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_learning_profile
```
```
In block/bdev.c (ffffffff817a8480)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - block/bdev.c:bdev_freeze
```
```
In block/blk-core.c (ffffffff817b2c25)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
```
```
In block/blk-wbt.c (ffffffff817fe3d5)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In block/blk-crypto-profile.c (ffffffff81808609)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
```
```
In io_uring/sqpoll.c (ffffffff8181fd8d)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread_unpark
```
```
In io_uring/poll.c (ffffffff818223a1)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_check_events
```
```
In io_uring/cancel.c (ffffffff81823ea2)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - io_uring/cancel.c:io_sync_cancel
  - io_uring/cancel.c:io_sync_cancel
  - io_uring/cancel.c:io_async_cancel
```
```
In io_uring/waitid.c (ffffffff8182ae75)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - io_uring/waitid.c:io_waitid
  - io_uring/waitid.c:io_waitid_cb
```
```
In lib/percpu-refcount.c (ffffffff8185d378)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/closure.c (ffffffff8223beb9)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - lib/closure.c:__closure_sync
  - lib/closure.c:__closure_wake_up
  - lib/closure.c:closure_put
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8194f5fa)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:edge_irq_handler
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
  - drivers/gpio/gpiolib-cdev.c:process_hw_ts
```
```
In drivers/pci/pci.c (ffffffff8196d652)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a7b855)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
  - drivers/acpi/apei/ghes.c:__ghes_print_estatus
```
```
In drivers/regulator/core.c (ffffffff81adde45)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/regulator/event.c (ffffffff81ae254e)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - drivers/regulator/event.c:reg_generate_netlink_event
```
```
In drivers/reset/core.c (ffffffff81ae3e87)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_deassert
  - drivers/reset/core.c:reset_control_assert
  - drivers/reset/core.c:reset_control_rearm
  - drivers/reset/core.c:reset_control_rearm
  - drivers/reset/core.c:reset_control_reset
```
```
In drivers/tty/tty_buffer.c (ffffffff81af17e9)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/tty/serial/serial_core.c (ffffffff81b11453)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:serial_core_remove_one_port
```
```
In drivers/char/random.c (ffffffff81b33602)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff81ba6015)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_drop_usage_count
```
```
In drivers/base/power/wakeup.c (ffffffff81baede0)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_activate
```
```
In drivers/base/devcoredump.c (ffffffff81bccf0f)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c2a438)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
```
```
In drivers/scsi/sd.c (ffffffff81c3a2fc)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffff81c49a97)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffffffff81c58e8d)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-sata.c (ffffffff81c6b3fb)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_sas_port_alloc
```
```
In drivers/gpu/drm/drm_vblank.c (ffffffff81cb5df7)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_vblank.c:drm_vblank_get
```
```
In drivers/input/serio/serio.c (ffffffff81dbc42d)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff81dc3f6a)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81df60f5)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/md/dm.c (ffffffff81e314f5)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_next_uevent_seq
```
```
In drivers/edac/edac_device.c (ffffffff81e427a5)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffff81e44fd5)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81e45ee8)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e9c614)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/devfreq/devfreq.c (ffffffff81ea26bd)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_resume_device
  - drivers/devfreq/devfreq.c:devfreq_suspend_device
```
```
In drivers/devfreq/devfreq-event.c (ffffffff81ea67d8)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
```
```
In net/core/skbuff.c (ffffffff81ed671f)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff81eece11)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
```
```
In net/core/neighbour.c (ffffffff81f0b72f)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/page_pool.c (ffffffff81f4369e)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_return_page
```
```
In net/core/netpoll.c (ffffffff81f487f9)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffffffff81f673e5)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_alloc_elem
```
```
In net/netlink/af_netlink.c (ffffffff81f8abcc)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/ipv4/route.c (ffffffff81faf251)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv4/ip_fragment.c (ffffffff81fb9791)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffff81fc0049)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/tcp.c (0)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
```
```
In net/ipv4/raw.c (ffffffff82002758)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (ffffffff82006f6c)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/igmp.c (0)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff82064cfe)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/xfrm/xfrm_output.c (0)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff82083ce8)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
```
```
In net/ipv6/route.c (ffffffff8209a1ac)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_gc
```
```
In net/ipv6/raw.c (ffffffff820bc0fd)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff820f97cd)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff82128a0a)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
  - net/rfkill/core.c:rfkill_fop_release
```
```
In arch/x86/pci/common.c (ffffffff82173d95)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
```
```
In lib/bug.c (ffffffff82176c99)
Location: arch/x86/include/asm/atomic.h:83
Inline: True
Inline callers:
  - lib/bug.c:report_bug
  - lib/bug.c:report_bug
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int arch_atomic_add_return(int i, atomic_t *v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/insn.c (ffff800010da79a0)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - arch/arm64/kernel/insn.c:aarch64_insn_patch_text_cb
```
```
In arch/arm64/kernel/cpu_errata.c (ffff80001009890c)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
```
```
In virt/kvm/arm/arm.c (ffff8000100c5770)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - virt/kvm/arm/arm.c:init_hyp_mode
```
```
In kernel/signal.c (ffff80001010b45c)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sched/topology.c (ffff80001015c258)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/autogroup.c (ffff80001015f0fc)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
```
In kernel/irq/spurious.c (ffff80001017d078)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (ffff800010183f5c)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/rcu/tree.c (ffff80001018f6b4)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_momentary_dyntick_idle
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
  - kernel/rcu/tree.c:rcu_dynticks_eqs_enter
Direct callers:
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_init
```
```
In kernel/audit.c (ffff8000101ec490)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/trace/ftrace.c (ffff800010210ea8)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
```
```
In kernel/trace/trace.c (ffff80001022a120)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
```
```
In kernel/trace/tracing_map.c (ffff80001022e1e0)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
```
```
In kernel/trace/trace_functions.c (ffff80001023013c)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffff8000102306f4)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (ffff8000102333c4)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (ffff80001023b334)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffff800010242930)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
```
```
In kernel/bpf/syscall.c (ffff80001025fec8)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_add
  - kernel/bpf/syscall.c:bpf_map_inc
```
```
In kernel/bpf/hashtab.c (ffff8000102783ac)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/callchain.c (ffff8000102a3564)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/padata.c (ffff8000102aa0f0)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In mm/rmap.c (ffff80001030b680)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/zswap.c (ffff80001032b210)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/huge_memory.c (ffff800010355fa4)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memcontrol.c (ffff800010369654)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In fs/inode.c (ffff8000103acca8)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
```
```
In fs/notify/notification.c (ffff8000103e88a0)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/io_uring.c (ffff800010401320)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
```
```
In fs/coredump.c (ffff800010428654)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/netlink.c (ffff800010437548)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In fs/proc/inode.c (ffff80001043bf40)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_entry_rundown
```
```
In fs/devpts/inode.c (ffff80001045eac8)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/jbd2/transaction.c (ffff8000104c9dcc)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/ecryptfs/main.c (ffff8000104f5160)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/selinux/avc.c (ffff800010546ce0)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/apparmor/policy.c (ffff800010596c38)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In block/blk-iocost.c (ffff8000106153d0)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In drivers/pci/pci.c (ffff8000106ea840)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_find_domain_nr
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/acpi/apei/ghes.c (ffff8000107aff3c)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:__ghes_print_estatus
```
```
In drivers/dma/of-dma.c (ffff8000107ff878)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
```
```
In drivers/regulator/core.c (ffff800010847bac)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (ffff80001084cf1c)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
```
```
In drivers/tty/serial/msm_serial.c (ffff8000108a1d8c)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_serial_probe
```
```
In drivers/iommu/arm-smmu.c (ffff8000108d1518)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu.c:arm_smmu_attach_dev
```
```
In drivers/base/power/wakeup.c (ffff800010903aa0)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
```
```
In drivers/base/devcoredump.c (ffff80001091f39c)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/mfd/mfd-core.c (ffff800010940840)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/scsi/scsi_lib.c (ffff800010978b84)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/sd.c (ffff8000109879b0)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffff8000109913dc)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffff80001099ecc0)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-scsi.c (ffff8000109a3738)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
```
```
In drivers/input/serio/serio.c (ffff800010a92940)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffff800010a979e8)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/power/reset/vexpress-poweroff.c (ffff800010aca3d0)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - drivers/power/reset/vexpress-poweroff.c:_vexpress_register_restart_handler
```
```
In drivers/md/dm.c (ffff800010b010fc)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_next_uevent_seq
```
```
In drivers/edac/edac_device.c (ffff800010b11608)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffff800010b137e8)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffff800010b1410c)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/firmware/arm_sdei.c (ffff800010b4bde0)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - drivers/firmware/arm_sdei.c:_local_event_register
  - drivers/firmware/arm_sdei.c:_local_event_unregister
  - drivers/firmware/arm_sdei.c:_ipi_event_disable
  - drivers/firmware/arm_sdei.c:_local_event_enable
```
```
In drivers/firmware/arm_scmi/clock.c (ffff800010b57d54)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/clock.c:scmi_clock_rate_set
```
```
In drivers/remoteproc/remoteproc_core.c (ffff800010b8104c)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/devfreq/devfreq.c (ffff800010b86438)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (ffff800010b87170)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
```
```
In drivers/extcon/extcon.c (ffff800010b88cb4)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/skbuff.c (ffff800010bb552c)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
```
In net/core/dev.c (ffff800010bcb0dc)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/core/neighbour.c (ffff800010be8270)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/page_pool.c (ffff800010c0c8b4)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_clean_page
```
```
In net/core/netpoll.c (ffff800010c1170c)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffff800010c20e04)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/core/bpf_sk_storage.c (ffff800010c310d0)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/ip_fragment.c (ffff800010c5f97c)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/udp.c (ffff800010c9c4bc)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_state.c (ffff800010ce36a8)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/packet/af_packet.c (ffff800010d5aba8)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffff800010d6bbdc)
Location: arch/arm64/include/asm/atomic.h:52
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
```
**Symbols:**

```
ffff80001018c378-ffff80001018c398: arch_atomic_add_return (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff8100640e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff810171e8)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104e6be)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8105051a)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b22b)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108b78a)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
```
In kernel/fork.c (ffffffff8109a47d)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/fork.c:walk_process_tree
```
```
In kernel/exit.c (ffffffff8109f3b7)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:is_current_pgrp_orphaned
```
```
In kernel/resource.c (ffffffff810a3866)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/resource.c:iomem_is_exclusive
  - kernel/resource.c:iomem_map_sanity_check
  - kernel/resource.c:lookup_resource
  - kernel/resource.c:region_intersects
  - kernel/resource.c:find_next_iomem_res
  - kernel/resource.c:r_stop
```
```
In kernel/ptrace.c (ffffffff810a7f15)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff810adfff)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:kill_pgrp
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sys.c (ffffffff810b6635)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
```
```
In kernel/sched/core.c (ffffffff810d82ce)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
```
```
In kernel/sched/topology.c (ffffffff810f1215)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/autogroup.c (ffffffff810f3abf)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
```
In kernel/locking/spinlock.c (ffffffff81a738b5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
  - kernel/locking/spinlock.c:_raw_read_trylock
  - kernel/locking/spinlock.c:_raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock
```
```
In kernel/power/process.c (ffffffff81101e1f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/irq/spurious.c (ffffffff811124a1)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (ffffffff81116bd2)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/rcu/tree.c (ffffffff8111f32f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_irq_exit
  - kernel/rcu/tree.c:rcu_nmi_exit
  - kernel/rcu/tree.c:rcu_idle_enter
  - kernel/rcu/tree.c:rcu_momentary_dyntick_idle
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
```
```
In kernel/livepatch/transition.c (ffffffff81126cac)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
```
```
In kernel/module.c (ffffffff81149315)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/module.c:try_release_module_ref
```
```
In kernel/cgroup/cgroup.c (ffffffff8115b72b)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_enable_task_cg_lists
```
```
In kernel/pid_namespace.c (ffffffff8116b997)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/audit.c (ffffffff8116fa2a)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/tracepoint.c (ffffffff8118ef4b)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/ftrace.c (ffffffff81190bbe)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811a5840)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In kernel/trace/tracing_map.c (ffffffff811a904e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In kernel/trace/trace_functions.c (ffffffff811aa2b0)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811ab0c8)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811adb0f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/fgraph.c (ffffffff811b2582)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
```
In kernel/trace/trace_events.c (ffffffff811b2d02)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811bafc0)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d0b64)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In kernel/bpf/syscall.c (ffffffff811d6ed5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811ec2fd)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/callchain.c (ffffffff81210fba)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/padata.c (ffffffff81215c70)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In mm/oom_kill.c (ffffffff81222d73)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/zswap.c (ffffffff81286b75)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/mempolicy.c (ffffffff81294d08)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
```
```
In mm/memory_hotplug.c (ffffffff812a4b53)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/memcontrol.c (ffffffff812bedd6)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/memory-failure.c (ffffffff812c34af)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
```
```
In mm/zsmalloc.c (ffffffff812c8af6)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In mm/memremap.c (ffffffff812cccfc)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/exec.c (ffffffff812dec7f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/exec.c:__x64_sys_uselib
```
```
In fs/fcntl.c (ffffffff812eb070)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_getown
```
```
In fs/inode.c (ffffffff812f42f0)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
```
```
In fs/filesystems.c (ffffffff812f92c0)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:filesystems_proc_show
  - fs/filesystems.c:fs_maxindex
  - fs/filesystems.c:fs_name
  - fs/filesystems.c:fs_index
  - fs/filesystems.c:get_filesystem_list
```
```
In fs/fs_struct.c (ffffffff81313a6d)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/notify/notification.c (ffffffff81325265)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/io_uring.c (ffffffff8133b636)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/coredump.c (ffffffff8135a5f4)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/netlink.c (ffffffff813660bf)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In fs/proc/inode.c (ffffffff8136a4eb)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_entry_rundown
  - fs/proc/inode.c:unuse_pde
```
```
In fs/proc/generic.c (ffffffff8136fd3a)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff81371226)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/kernfs/dir.c (ffffffff8137c9ba)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In fs/devpts/inode.c (ffffffff81385475)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/extents_status.c (ffffffff81395909)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:ext4_is_pending
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_scan_clu
  - fs/ext4/extents_status.c:ext4_es_scan_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
```
```
In fs/ext4/inode.c (ffffffff813ace5d)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff813d1f8c)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/jbd2/transaction.c (ffffffff813ea983)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:wait_transaction_locked
```
```
In fs/jbd2/journal.c (ffffffff813ef0ff)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_errno
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_transaction_committed
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
```
In fs/ecryptfs/main.c (ffffffff8140c255)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/keys/keyring.c (ffffffff8143fd87)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/avc.c (ffffffff81452a79)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/selinux/hooks.c (ffffffff81457095)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/selinux/ss/services.c (ffffffff81470d04)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_read_policy
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_policycap_supported
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_get_bool_value
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_node_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_ib_endport_sid
  - security/selinux/ss/services.c:security_ib_pkey_sid
  - security/selinux/ss/services.c:security_port_sid
  - security/selinux/ss/services.c:security_policydb_len
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_bounded_transition
```
```
In security/apparmor/policy.c (ffffffff814994ff)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In security/integrity/iint.c (ffffffff814acd8a)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In block/blk-core.c (ffffffff814dcb55)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In block/blk-iocost.c (ffffffff815081df)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In block/blk-wbt.c (ffffffff81511bf5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In lib/sbitmap.c (ffffffff81554447)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pci/pci.c (ffffffff815772d2)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/regulator/core.c (ffffffff816438db)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (ffffffff8164705f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff8164a0c4)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/tty/tty_buffer.c (ffffffff81652489)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81654bf7)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/sysrq.c (ffffffff816566ee)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/tty/serial/serial_core.c (ffffffff8166adb3)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/base/power/wakeup.c (ffffffff816d9307)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In drivers/base/devcoredump.c (ffffffff816ef406)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/block/loop.c (ffffffff816f12e2)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
```
```
In drivers/mfd/mfd-core.c (ffffffff81701e5a)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/scsi/scsi_lib.c (ffffffff81729138)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/sd.c (ffffffff81734502)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffff8173d1bc)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/nvme/host/pci.c (ffffffff81750486)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_timeout
```
```
In drivers/ata/libata-core.c (ffffffff817596fe)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-scsi.c (ffffffff8175e791)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In drivers/input/serio/serio.c (ffffffff8180750b)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff8180d166)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/power/supply/power_supply_core.c (ffffffff818282c5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/md/dm.c (ffffffff81850e15)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_next_uevent_seq
```
```
In drivers/edac/edac_device.c (ffffffff8185eb75)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffff81860ae5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff818615a5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/leds/led-triggers.c (ffffffff81888c20)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff818961dc)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/devfreq/devfreq.c (ffffffff8189a1d8)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (ffffffff8189bb1f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff8189d654)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In arch/x86/pci/common.c (ffffffff818a8465)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
```
```
In net/core/skbuff.c (ffffffff818bb0e4)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff818cbb11)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/core/dst.c (ffffffff818e102a)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
```
```
In net/core/neighbour.c (ffffffff818e14de)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/net-sysfs.c (ffffffff819048b8)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:address_show
```
```
In net/core/page_pool.c (ffffffff81906dab)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_clean_page
```
```
In net/core/netpoll.c (ffffffff8190af56)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffffffff819197cf)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/core/bpf_sk_storage.c (ffffffff819298bd)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/sched/sch_api.c (ffffffff8192fd3f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffffffff81933ec7)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffffffff81939c54)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (ffffffff8193ca0e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff8193dd34)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/ipv4/ip_fragment.c (ffffffff8194ec44)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/raw.c (ffffffff819828b6)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff81987e18)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/arp.c (ffffffff8198bbf8)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
```
```
In net/ipv4/ipmr.c (ffffffff819aec95)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_vif_seq_stop
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:reg_vif_xmit
```
```
In net/ipv4/ipmr_base.c (ffffffff819b4d44)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff819bfcc5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff819c3e8e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/ipv6/ip6_output.c (ffffffff819d9c4c)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff819eb1bb)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffffffff819f66eb)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
```
In net/ipv6/raw.c (ffffffff81a041dc)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/mcast.c (ffffffff81a0a242)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv6/mcast.c:inet6_mc_check
```
```
In net/ipv6/ip6mr.c (ffffffff81a1cacf)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_stop
```
```
In net/packet/af_packet.c (ffffffff81a2a0a1)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff81a3acde)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
  - net/rfkill/core.c:rfkill_fop_release
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
In arch/x86/events/core.c (ffffffff81004b8e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff81016618)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103db8e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8103fb6a)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104b39b)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8107a2ba)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
```
In kernel/fork.c (ffffffff81088ebd)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/fork.c:walk_process_tree
```
```
In kernel/exit.c (ffffffff8108dde7)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:is_current_pgrp_orphaned
```
```
In kernel/resource.c (ffffffff81092246)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/resource.c:iomem_is_exclusive
  - kernel/resource.c:iomem_map_sanity_check
  - kernel/resource.c:lookup_resource
  - kernel/resource.c:region_intersects
  - kernel/resource.c:find_next_iomem_res
  - kernel/resource.c:r_stop
```
```
In kernel/ptrace.c (ffffffff810968d5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff8109c959)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:kill_pgrp
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sys.c (ffffffff810a4f75)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
```
```
In kernel/sched/core.c (ffffffff810c6cde)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
```
```
In kernel/sched/rt.c (ffffffff810d998b)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:tg_set_rt_bandwidth
```
```
In kernel/sched/topology.c (ffffffff810e1285)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/autogroup.c (ffffffff810e3bef)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
```
In kernel/locking/spinlock.c (ffffffff81a2fc35)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
  - kernel/locking/spinlock.c:_raw_read_trylock
  - kernel/locking/spinlock.c:_raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock
```
```
In kernel/power/process.c (ffffffff810f21df)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/irq/spurious.c (ffffffff811031c1)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (ffffffff811078c2)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/rcu/tree.c (ffffffff81110d9f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_irq_exit
  - kernel/rcu/tree.c:rcu_nmi_exit
  - kernel/rcu/tree.c:rcu_momentary_dyntick_idle
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
```
```
In kernel/livepatch/transition.c (ffffffff8111970c)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
```
```
In kernel/module.c (ffffffff8113c5c5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/module.c:try_release_module_ref
```
```
In kernel/cgroup/cgroup.c (ffffffff8114ea15)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_enable_task_cg_lists
```
```
In kernel/pid_namespace.c (ffffffff8115eb97)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/audit.c (ffffffff81162bca)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/tracepoint.c (ffffffff811820cb)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/ftrace.c (ffffffff81183743)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811986b0)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In kernel/trace/tracing_map.c (ffffffff8119bfce)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In kernel/trace/trace_functions.c (ffffffff8119d215)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8119e3d8)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811a0951)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/fgraph.c (ffffffff811a5392)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
```
In kernel/trace/trace_events.c (ffffffff811a5b02)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811adda0)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In kernel/trace/trace_uprobe.c (ffffffff811c3934)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In kernel/bpf/syscall.c (ffffffff811c9c95)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811df08d)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/core.c (ffffffff811fb3ab)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/callchain.c (ffffffff81203d4a)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/padata.c (ffffffff812089d0)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In mm/oom_kill.c (ffffffff81215f23)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/zswap.c (ffffffff812789d5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/mempolicy.c (ffffffff81286918)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
```
```
In mm/memory_hotplug.c (ffffffff81296623)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/memcontrol.c (ffffffff812afec6)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/memory-failure.c (ffffffff812b44ef)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
```
```
In mm/zsmalloc.c (ffffffff812b9b36)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In mm/memremap.c (ffffffff812bdb6c)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/exec.c (ffffffff812ceda4)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/exec.c:__x64_sys_uselib
```
```
In fs/fcntl.c (ffffffff812dbcb4)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_getown
```
```
In fs/inode.c (ffffffff812e4f20)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
```
```
In fs/filesystems.c (ffffffff812e9ee0)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:filesystems_proc_show
  - fs/filesystems.c:fs_maxindex
  - fs/filesystems.c:fs_name
  - fs/filesystems.c:fs_index
  - fs/filesystems.c:get_filesystem_list
```
```
In fs/fs_struct.c (ffffffff8130467d)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/notify/notification.c (ffffffff81315e05)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/io_uring.c (ffffffff8132c316)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/coredump.c (ffffffff8134b29e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/netlink.c (ffffffff81356d5f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In fs/proc/inode.c (ffffffff8135af7b)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_entry_rundown
  - fs/proc/inode.c:unuse_pde
```
```
In fs/proc/generic.c (ffffffff813607ca)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff81361cb6)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/kernfs/dir.c (ffffffff8136d48a)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In fs/devpts/inode.c (ffffffff81375f05)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/extents_status.c (ffffffff81386399)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:ext4_is_pending
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_scan_clu
  - fs/ext4/extents_status.c:ext4_es_scan_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
```
```
In fs/ext4/inode.c (ffffffff8139d8ed)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff813c2a0c)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/jbd2/transaction.c (ffffffff813db403)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:wait_transaction_locked
```
```
In fs/jbd2/journal.c (ffffffff813dfb7f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_errno
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_transaction_committed
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
```
In fs/ecryptfs/main.c (ffffffff813fccd5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/keys/keyring.c (ffffffff814307f7)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/avc.c (ffffffff814434c9)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/selinux/hooks.c (ffffffff81447ad5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/selinux/ss/services.c (ffffffff81461724)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_read_policy
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_policycap_supported
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_get_bool_value
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_node_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_ib_endport_sid
  - security/selinux/ss/services.c:security_ib_pkey_sid
  - security/selinux/ss/services.c:security_port_sid
  - security/selinux/ss/services.c:security_policydb_len
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_bounded_transition
```
```
In security/apparmor/policy.c (ffffffff81489f1f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In security/integrity/iint.c (ffffffff8149d7aa)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In block/blk-core.c (ffffffff814cd505)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In block/blk-iocost.c (ffffffff814f868f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In block/blk-wbt.c (ffffffff81501f15)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In lib/sbitmap.c (ffffffff815446c7)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pci/pci.c (ffffffff81565a32)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/regulator/core.c (ffffffff81623d5b)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (ffffffff816274bf)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff8162a514)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/tty/tty_buffer.c (ffffffff816328c9)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81634fc1)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/sysrq.c (ffffffff81636a7e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/tty/serial/serial_core.c (ffffffff81649f23)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/base/power/wakeup.c (ffffffff816b3947)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In drivers/block/loop.c (ffffffff816cb3e2)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
```
```
In drivers/mfd/mfd-core.c (ffffffff816d5c6a)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/scsi/scsi_lib.c (ffffffff81702568)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/scsi_transport_fc.c (ffffffff8170f935)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/scsi/scsi_transport_fc.c:fc_host_fpin_rcv
```
```
In drivers/scsi/sd.c (ffffffff817161a2)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffff8171ee5c)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/nvme/host/pci.c (ffffffff81730326)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_timeout
```
```
In drivers/ata/libata-core.c (ffffffff8173959e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-scsi.c (ffffffff8173e631)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In drivers/input/serio/serio.c (ffffffff817cec1b)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff817d48d6)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/power/supply/power_supply_core.c (ffffffff817ef955)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/md/dm.c (ffffffff81818425)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_next_uevent_seq
```
```
In drivers/edac/edac_device.c (ffffffff81826145)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffff818280b5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81828b55)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/leds/led-triggers.c (ffffffff818405a0)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
```
In drivers/hv/channel.c (ffffffff81850fc5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/hv/channel.c:vmbus_establish_gpadl
```
```
In drivers/devfreq/devfreq.c (ffffffff818576a8)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (ffffffff81858fef)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In arch/x86/pci/common.c (ffffffff81862e75)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
```
```
In net/core/skbuff.c (ffffffff81875024)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff81885a51)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/core/dst.c (ffffffff8189ae6a)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
```
```
In net/core/neighbour.c (ffffffff8189b31e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/net-sysfs.c (ffffffff818be6e8)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:address_show
```
```
In net/core/page_pool.c (ffffffff818c0bbb)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_clean_page
```
```
In net/core/netpoll.c (ffffffff818c4cf1)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffffffff818d357f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/core/bpf_sk_storage.c (ffffffff818e366d)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/sched/sch_api.c (ffffffff818e983f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffffffff818ed9c7)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffffffff818f3754)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (ffffffff818f650e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff818f7834)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/ipv4/ip_fragment.c (ffffffff81908734)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/raw.c (ffffffff8193c376)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819418d8)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/arp.c (ffffffff819456b8)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
```
```
In net/ipv4/ipmr.c (ffffffff8196b2c5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_vif_seq_stop
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:reg_vif_xmit
```
```
In net/ipv4/ipmr_base.c (ffffffff81971374)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197cab5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff81980c7e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/ipv6/ip6_output.c (ffffffff81996a0c)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff819a7f7b)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffffffff819b34ab)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
```
In net/ipv6/raw.c (ffffffff819c0f9c)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/mcast.c (ffffffff819c7002)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv6/mcast.c:inet6_mc_check
```
```
In net/ipv6/ip6mr.c (ffffffff819d988f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_stop
```
```
In net/packet/af_packet.c (ffffffff819e7291)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff819f78fe)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
  - net/rfkill/core.c:rfkill_fop_release
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
In arch/x86/events/core.c (ffffffff810063ce)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff810171a8)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104e50e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff810503ca)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b65b)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108b73a)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
```
In kernel/fork.c (ffffffff8109a42d)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/fork.c:walk_process_tree
```
```
In kernel/exit.c (ffffffff8109f367)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:is_current_pgrp_orphaned
```
```
In kernel/resource.c (ffffffff810a3816)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/resource.c:iomem_is_exclusive
  - kernel/resource.c:iomem_map_sanity_check
  - kernel/resource.c:lookup_resource
  - kernel/resource.c:region_intersects
  - kernel/resource.c:find_next_iomem_res
  - kernel/resource.c:r_stop
```
```
In kernel/ptrace.c (ffffffff810a7475)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff810ad55f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:kill_pgrp
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sys.c (ffffffff810b5b95)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
```
```
In kernel/sched/core.c (ffffffff810d4abe)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
```
```
In kernel/sched/rt.c (ffffffff810e6afb)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:tg_set_rt_bandwidth
```
```
In kernel/sched/topology.c (ffffffff810ee345)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/autogroup.c (ffffffff810f0c0f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
```
In kernel/locking/spinlock.c (ffffffff81adfcc5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
  - kernel/locking/spinlock.c:_raw_read_trylock
  - kernel/locking/spinlock.c:_raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock
```
```
In kernel/power/process.c (ffffffff810ff1af)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/irq/spurious.c (ffffffff81110391)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (ffffffff81114ac2)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/rcu/tree.c (ffffffff8111d21f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_irq_exit
  - kernel/rcu/tree.c:rcu_nmi_exit
  - kernel/rcu/tree.c:rcu_idle_enter
  - kernel/rcu/tree.c:rcu_momentary_dyntick_idle
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
```
```
In kernel/livepatch/transition.c (ffffffff81124b9c)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
```
```
In kernel/module.c (ffffffff811471c5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/module.c:try_release_module_ref
```
```
In kernel/cgroup/cgroup.c (ffffffff811594fb)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_enable_task_cg_lists
```
```
In kernel/pid_namespace.c (ffffffff81169767)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/audit.c (ffffffff8116d7fa)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/tracepoint.c (ffffffff8118cd1b)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/ftrace.c (ffffffff8118e98e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811a3610)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In kernel/trace/tracing_map.c (ffffffff811a6e1e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In kernel/trace/trace_functions.c (ffffffff811a8080)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811a8e98)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811ab8df)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/fgraph.c (ffffffff811b0352)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
```
In kernel/trace/trace_events.c (ffffffff811b0ad2)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811b8d90)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In kernel/trace/trace_uprobe.c (ffffffff811ce934)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In kernel/bpf/syscall.c (ffffffff811d4ca5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811ea0cd)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/callchain.c (ffffffff8120ed5a)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/padata.c (ffffffff81213a10)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In mm/oom_kill.c (ffffffff81220b13)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/zswap.c (ffffffff81284985)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/mempolicy.c (ffffffff81292b18)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
```
```
In mm/memory_hotplug.c (ffffffff812a2963)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/memcontrol.c (ffffffff812bcbe6)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/memory-failure.c (ffffffff812c12bf)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
```
```
In mm/zsmalloc.c (ffffffff812c6906)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In mm/memremap.c (ffffffff812cab0c)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/exec.c (ffffffff812dca8f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/exec.c:__x64_sys_uselib
```
```
In fs/fcntl.c (ffffffff812e8e84)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_getown
```
```
In fs/inode.c (ffffffff812f2100)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
```
```
In fs/filesystems.c (ffffffff812f70b0)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:filesystems_proc_show
  - fs/filesystems.c:fs_maxindex
  - fs/filesystems.c:fs_name
  - fs/filesystems.c:fs_index
  - fs/filesystems.c:get_filesystem_list
```
```
In fs/fs_struct.c (ffffffff8131185d)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/notify/notification.c (ffffffff81322d35)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/io_uring.c (ffffffff81339106)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/coredump.c (ffffffff813580c4)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/netlink.c (ffffffff81363b8f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In fs/proc/inode.c (ffffffff81367fbb)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_entry_rundown
  - fs/proc/inode.c:unuse_pde
```
```
In fs/proc/generic.c (ffffffff8136d80a)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff8136ecf6)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/kernfs/dir.c (ffffffff8137a48a)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In fs/devpts/inode.c (ffffffff81382f45)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/ext4/extents_status.c (ffffffff81393269)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:ext4_is_pending
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_scan_clu
  - fs/ext4/extents_status.c:ext4_es_scan_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
```
```
In fs/ext4/inode.c (ffffffff813aa6bd)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff813cf41c)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/jbd2/transaction.c (ffffffff813e7d03)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:wait_transaction_locked
```
```
In fs/jbd2/journal.c (ffffffff813ec47f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_errno
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_transaction_committed
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
```
In fs/ecryptfs/main.c (ffffffff814095d5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/keys/keyring.c (ffffffff8143bf27)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/avc.c (ffffffff8144eb19)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/selinux/hooks.c (ffffffff81453135)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/selinux/ss/services.c (ffffffff8146cda4)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_read_policy
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_policycap_supported
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_get_bool_value
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_node_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_ib_endport_sid
  - security/selinux/ss/services.c:security_ib_pkey_sid
  - security/selinux/ss/services.c:security_port_sid
  - security/selinux/ss/services.c:security_policydb_len
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_bounded_transition
```
```
In security/apparmor/policy.c (ffffffff8149559f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In security/integrity/iint.c (ffffffff814a8e2a)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In block/blk-core.c (ffffffff814d8be5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In block/blk-iocost.c (ffffffff8150426f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In block/blk-wbt.c (ffffffff8150dc85)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In lib/sbitmap.c (ffffffff81550187)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pci/pci.c (ffffffff81576b02)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/acpi/apei/ghes.c (ffffffff81637835)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:__ghes_print_estatus
```
```
In drivers/regulator/core.c (ffffffff81671cbb)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (ffffffff8167541f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff81678484)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/tty/tty_buffer.c (ffffffff81680849)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81682fb7)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/sysrq.c (ffffffff81684aae)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/tty/serial/serial_core.c (ffffffff81699193)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/base/power/wakeup.c (ffffffff81706c47)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In drivers/base/devcoredump.c (ffffffff8171cae6)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/block/loop.c (ffffffff8171e9c2)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
```
```
In drivers/mfd/mfd-core.c (ffffffff8173727a)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/scsi/scsi_lib.c (ffffffff81767f08)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/sd.c (ffffffff81774c92)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffff8177d94c)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffffffff8178946e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-scsi.c (ffffffff8178e521)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In drivers/input/serio/serio.c (ffffffff818465bb)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff8184c2e6)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81875205)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/md/dm.c (ffffffff818a0445)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_next_uevent_seq
```
```
In drivers/edac/edac_device.c (ffffffff818ae1a5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffff818b0115)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff818b0bd5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/leds/led-triggers.c (ffffffff818da8f0)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
```
In drivers/devfreq/devfreq.c (ffffffff818e98c8)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (ffffffff818eb20f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff818ecd44)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In arch/x86/pci/common.c (ffffffff818f9ac5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
```
```
In net/core/skbuff.c (ffffffff8190c0e4)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff8191cb11)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/core/dst.c (ffffffff8193205a)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
```
```
In net/core/neighbour.c (ffffffff8193250e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/net-sysfs.c (ffffffff819558e8)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:address_show
```
```
In net/core/page_pool.c (ffffffff81957ddb)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_clean_page
```
```
In net/core/netpoll.c (ffffffff8195bf86)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffffffff8196a95f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/core/bpf_sk_storage.c (ffffffff8197aa4d)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/sched/sch_api.c (ffffffff81980ecf)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffffffff81985057)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffffffff8198ade4)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (ffffffff8198db9e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff8198eec4)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/netfilter/nfnetlink_log.c (ffffffff8199c3a1)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_log.c:__build_packet_message
```
```
In net/ipv4/ip_fragment.c (ffffffff819b9414)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/raw.c (ffffffff819ed086)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819f25e8)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/arp.c (ffffffff819f6408)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
```
```
In net/ipv4/ipmr.c (ffffffff81a19535)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_vif_seq_stop
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:reg_vif_xmit
```
```
In net/ipv4/ipmr_base.c (ffffffff81a1f5e4)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2a745)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff81a2e90e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/ipv6/ip6_output.c (ffffffff81a446cc)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff81a55c3b)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffffffff81a6116b)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
```
In net/ipv6/raw.c (ffffffff81a6ec5c)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/mcast.c (ffffffff81a74cc2)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv6/mcast.c:inet6_mc_check
```
```
In net/ipv6/ip6mr.c (ffffffff81a8754f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_stop
```
```
In net/packet/af_packet.c (ffffffff81a95c51)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff81aa6b8e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
  - net/rfkill/core.c:rfkill_fop_release
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
In arch/x86/events/core.c (ffffffff8100652e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff810173e8)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104f94e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8105180a)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108da9a)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
```
In kernel/signal.c (ffffffff810b1595)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sched/topology.c (ffffffff810f9385)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/autogroup.c (ffffffff810fbc9f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
```
In kernel/locking/spinlock.c (ffffffff81aec665)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_irq
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
  - kernel/locking/spinlock.c:_raw_read_unlock
  - kernel/locking/spinlock.c:_raw_read_trylock
  - kernel/locking/spinlock.c:_raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock
```
```
In kernel/irq/spurious.c (ffffffff8111b911)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (ffffffff811200f2)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/rcu/tree.c (ffffffff811280ef)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_irq_exit
  - kernel/rcu/tree.c:rcu_nmi_exit
  - kernel/rcu/tree.c:rcu_idle_enter
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
```
```
In kernel/module.c (ffffffff81153dd5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/module.c:try_release_module_ref
```
```
In kernel/audit.c (ffffffff8117afef)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/trace/ftrace.c (ffffffff8119c51e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811b13a0)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In kernel/trace/tracing_map.c (ffffffff811b4bbe)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In kernel/trace/trace_functions.c (ffffffff811b5e30)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811b6cd8)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811b97af)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (ffffffff811beb62)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811c6e30)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811e2fd5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811f84ad)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/callchain.c (ffffffff8121dc6a)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/padata.c (ffffffff81222b90)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In mm/oom_kill.c (ffffffff8122fcb3)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/zswap.c (ffffffff81294625)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/memory_hotplug.c (ffffffff812b2bf3)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/memcontrol.c (ffffffff812cd3d6)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/memremap.c (ffffffff812db82c)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/inode.c (ffffffff813036db)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
```
```
In fs/notify/notification.c (ffffffff81334a75)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/io_uring.c (ffffffff8134b95d)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/coredump.c (ffffffff8136b7f6)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/netlink.c (ffffffff8137723f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In fs/proc/inode.c (ffffffff8137b60b)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_entry_rundown
  - fs/proc/inode.c:unuse_pde
```
```
In fs/kernfs/dir.c (ffffffff8138df7a)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In fs/devpts/inode.c (ffffffff81396a65)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/jbd2/transaction.c (ffffffff813fb26a)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/ecryptfs/main.c (ffffffff8141f295)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/selinux/avc.c (ffffffff81465ef9)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/apparmor/policy.c (ffffffff814ad5ff)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In block/blk-core.c (ffffffff814f17f5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In block/blk-iocost.c (ffffffff8151d81f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In block/blk-wbt.c (ffffffff815272a5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In lib/sbitmap.c (ffffffff81569fc7)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pci/pci.c (ffffffff81590fe2)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/acpi/apei/ghes.c (ffffffff81651b75)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:__ghes_print_estatus
```
```
In drivers/regulator/core.c (ffffffff8168c31b)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (ffffffff8168fa7f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff8169ae99)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/tty/serial/serial_core.c (ffffffff816b3853)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/base/power/wakeup.c (ffffffff81721657)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In drivers/base/devcoredump.c (ffffffff81737e46)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/block/loop.c (ffffffff81739df2)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
```
```
In drivers/mfd/mfd-core.c (ffffffff817526ba)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/scsi/scsi_lib.c (ffffffff81783647)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/sd.c (ffffffff8178ea72)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffff81798cb7)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffffffff817a32be)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-scsi.c (ffffffff817a8371)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In drivers/input/serio/serio.c (ffffffff81861bcb)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff81867546)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81890ba5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/md/dm.c (ffffffff818bc695)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_next_uevent_seq
```
```
In drivers/edac/edac_device.c (ffffffff818ca435)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffff818cc3a5)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff818cce65)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff8190693c)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/devfreq/devfreq.c (ffffffff8190a948)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (ffffffff8190c28f)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff8190ddc4)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In arch/x86/pci/common.c (ffffffff8191ac25)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
```
```
In net/core/skbuff.c (ffffffff8192d214)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff8193dfe1)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/core/dst.c (ffffffff8195372a)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
```
```
In net/core/neighbour.c (ffffffff81959505)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/page_pool.c (ffffffff81979ebb)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_clean_page
```
```
In net/core/netpoll.c (ffffffff8197e366)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffffffff8198cdcf)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/core/bpf_sk_storage.c (ffffffff8199cf7d)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/netlink/af_netlink.c (ffffffff819b453b)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/ipv4/ip_fragment.c (ffffffff819c2d04)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/udp.c (ffffffff819fc438)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3a10e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/packet/af_packet.c (ffffffff81aa2891)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff81ab2f2e)
Location: arch/x86/include/asm/atomic.h:165
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
  - net/rfkill/core.c:rfkill_fop_release
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>

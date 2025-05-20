# Function: <code>atomic_add_return</code>

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
In arch/x86/events/core.c (ffffffff8100580e)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81044896)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff81047577)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_intel_adjust_timer
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810744fe)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
```
In kernel/fork.c (ffffffff8107f362)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffffffff8108137b)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_down
```
```
In kernel/exit.c (ffffffff81082b8e)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_wait
  - kernel/exit.c:is_current_pgrp_orphaned
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/resource.c (ffffffff81085f46)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/resource.c:r_stop
  - kernel/resource.c:find_next_iomem_res
  - kernel/resource.c:region_intersects
  - kernel/resource.c:lookup_resource
  - kernel/resource.c:iomem_map_sanity_check
  - kernel/resource.c:iomem_is_exclusive
```
```
In kernel/ptrace.c (ffffffff8108b6d1)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff8108ebbc)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:kill_pgrp
  - kernel/signal.c:SYSC_kill
  - kernel/signal.c:get_signal
  - kernel/signal.c:exit_signals
```
```
In kernel/sys.c (ffffffff81093989)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/sys.c:SyS_setpriority
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:do_prlimit
```
```
In kernel/pid.c (ffffffff8109e28d)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/sched/core.c (ffffffff810af764)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:normalize_rt_tasks
```
```
In kernel/sched/auto_group.c (ffffffff810c49b3)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/sched/auto_group.c:autogroup_move_group
  - kernel/sched/auto_group.c:sched_autogroup_create_attach
  - kernel/sched/auto_group.c:sched_autogroup_create_attach
  - kernel/sched/auto_group.c:sched_autogroup_fork
  - kernel/sched/auto_group.c:sched_autogroup_fork
  - kernel/sched/auto_group.c:proc_sched_autogroup_set_nice
  - kernel/sched/auto_group.c:proc_sched_autogroup_set_nice
  - kernel/sched/auto_group.c:proc_sched_autogroup_show_task
  - kernel/sched/auto_group.c:proc_sched_autogroup_show_task
```
```
In kernel/locking/mutex.c (ffffffff81821bdb)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
  - kernel/locking/mutex.c:__ww_mutex_lock
```
```
In kernel/locking/spinlock.c (ffffffff81823f66)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_trylock
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
  - kernel/locking/spinlock.c:_raw_read_lock
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_irqsave
```
```
In kernel/locking/qrwlock.c (ffffffff810cbdf6)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/process.c (ffffffff810cd9a0)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_kernel_threads
```
```
In kernel/irq/manage.c (ffffffff810dc110)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/spurious.c (ffffffff810dd2d6)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/spurious.c:note_interrupt
```
```
In kernel/rcu/tree.c (ffffffff810e471d)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_sched_expedited
```
```
In kernel/time/posix-clock.c (ffffffff810fa1b4)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/time/posix-clock.c:posix_clock_open
```
```
In kernel/module.c (ffffffff811079cb)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/module.c:SyS_delete_module
```
```
In kernel/cgroup.c (ffffffff8111841c)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:pidlist_array_load
```
```
In kernel/utsname.c (ffffffff8111db20)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffff8111f4d0)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/pid_namespace.c:reboot_pid_ns
```
```
In kernel/audit.c (ffffffff811219bb)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_start
```
```
In kernel/auditsc.c (ffffffff81128e86)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_set_loginuid
```
```
In kernel/relay.c (ffffffff8113d0e6)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_open
```
```
In kernel/tracepoint.c (ffffffff8113fc9b)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_regfunc
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/trace/ftrace.c (ffffffff81142926)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:profile_graph_entry
```
```
In kernel/trace/trace.c (ffffffff81153190)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
```
```
In kernel/trace/trace_functions.c (ffffffff8115690a)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff81157103)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8115965b)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_return
```
```
In kernel/trace/blktrace.c (ffffffff8115c863)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_trace_setup_queue
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
```
In kernel/trace/trace_events.c (ffffffff8115de32)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811663ad)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
```
```
In kernel/trace/trace_uprobe.c (ffffffff8116f1d7)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In kernel/events/core.c (ffffffff8117a642)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/callchain.c (ffffffff8118608e)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/padata.c (ffffffff81189953)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In kernel/jump_label.c (ffffffff8118aeea)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
```
```
In mm/oom_kill.c (ffffffff81190a86)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/hugetlb.c (ffffffff811dac63)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_vm_op_open
```
```
In mm/memory_hotplug.c (ffffffff811efdc3)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/memcontrol.c (ffffffff811ff27b)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/memory-failure.c (ffffffff81202dd3)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In fs/exec.c (ffffffff81212b90)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - fs/exec.c:SyS_uselib
  - fs/exec.c:SyS_uselib
```
```
In fs/fcntl.c (ffffffff8121ee00)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - fs/fcntl.c:f_getown
  - fs/fcntl.c:SyS_fcntl
  - fs/fcntl.c:SyS_fcntl
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
```
```
In fs/inode.c (ffffffff81226c9e)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
```
```
In fs/filesystems.c (ffffffff8122b19e)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:filesystems_proc_show
  - fs/filesystems.c:get_filesystem_list
  - fs/filesystems.c:SyS_sysfs
  - fs/filesystems.c:SyS_sysfs
  - fs/filesystems.c:SyS_sysfs
```
```
In fs/fs_struct.c (ffffffff812415c7)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/notify/notification.c (ffffffff8124f976)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81252013)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_new_group
```
```
In fs/eventfd.c (ffffffff81259167)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/coredump.c (ffffffff8126f6e5)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/netlink.c (ffffffff81276710)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In fs/proc/inode.c (ffffffff81279215)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - fs/proc/inode.c:unuse_pde
  - fs/proc/inode.c:proc_entry_rundown
```
```
In fs/proc/root.c (ffffffff8127a0ea)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
```
```
In fs/proc/base.c (ffffffff8127a665)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - fs/proc/base.c:proc_oom_score
```
```
In fs/proc/generic.c (ffffffff8127eeab)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff812808b5)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/proc/kcore.c (ffffffff812871d4)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
```
```
In fs/kernfs/dir.c (ffffffff8128a5d9)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_put_active
```
```
In fs/ext4/inode.c (ffffffff8129a04d)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/super.c (ffffffff812aca89)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/ext4/extents_status.c (ffffffff812dbbce)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_find_delayed_extent_range
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
```
```
In fs/jbd2/transaction.c (ffffffff812e6b64)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:wait_transaction_locked
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
```
```
In fs/jbd2/journal.c (ffffffff812edffe)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_errno
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
```
```
In fs/ecryptfs/main.c (ffffffff813039c5)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In fs/fuse/file.c (ffffffff8131629a)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_async_req_send
  - fs/fuse/file.c:fuse_direct_IO
```
```
In fs/fuse/inode.c (ffffffff8131ac4b)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In security/keys/keyring.c (ffffffff813318fe)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/avc.c (ffffffff8134049f)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/selinux/hooks.c (ffffffff81345316)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/selinux/ss/services.c (ffffffff81355526)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_validate_transition
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_policydb_len
  - security/selinux/ss/services.c:security_port_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_node_sid
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_genfs_sid
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:security_get_bool_value
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_get_classes
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_policycap_supported
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_read_policy
```
```
In security/apparmor/apparmorfs.c (ffffffff81375570)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:p_start
```
```
In security/apparmor/capability.c (ffffffff81376f95)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/context.c (ffffffff81377260)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - security/apparmor/context.c:aa_dup_task_context
  - security/apparmor/context.c:aa_dup_task_context
  - security/apparmor/context.c:aa_dup_task_context
  - security/apparmor/context.c:aa_get_task_label
  - security/apparmor/context.c:aa_replace_current_label
  - security/apparmor/context.c:aa_set_current_onexec
  - security/apparmor/context.c:aa_set_current_hat
  - security/apparmor/context.c:aa_restore_previous_label
```
```
In security/apparmor/domain.c (ffffffff81379bd0)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
```
```
In security/apparmor/policy.c (ffffffff8137f250)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - security/apparmor/policy.c:__lookup_replace
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy.c:aa_setup_default_label
  - security/apparmor/policy.c:aa_null_profile
  - security/apparmor/policy.c:aa_null_profile
  - security/apparmor/policy.c:aa_null_profile
  - security/apparmor/policy.c:aa_null_profile
  - security/apparmor/policy.c:aa_null_profile
  - security/apparmor/policy.c:aa_lookupn_profile
  - security/apparmor/policy.c:aa_lookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/policy.c:aa_may_open_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
```
```
In security/apparmor/policy_unpack.c (ffffffff8139bd9b)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:kref_get
```
```
In security/apparmor/procattr.c (ffffffff81382cf6)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff813837c0)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/resource.c (ffffffff813875e7)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff81388c71)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/label.c (ffffffff8138996e)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_alloc_proxy
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
```
```
In security/apparmor/net.c (0)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
```
```
In security/apparmor/af_unix.c (0)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
```
```
In security/apparmor/policy_ns.c (ffffffff8139490a)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_findn_ns
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:aa_prepare_ns
```
```
In security/integrity/iint.c (ffffffff813962af)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In block/blk-mq.c (ffffffff813c3656)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
```
```
In block/blk-mq-tag.c (ffffffff813c6cf8)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - block/blk-mq-tag.c:bt_clear_tag
  - block/blk-mq-tag.c:bt_clear_tag
```
```
In block/bsg.c (ffffffff813d65da)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In lib/kobject.c (ffffffff813eb6a6)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get
```
```
In lib/cpu_rmap.c (ffffffff814160d5)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
```
In drivers/pinctrl/core.c (ffffffff8141e3a0)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_get
```
```
In drivers/pci/pci.c (ffffffff81436d02)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_get_new_domain_nr
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81452cbc)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/acpi/ec.c (ffffffff8148426e)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_query
```
```
In drivers/acpi/apei/ghes.c (ffffffff814b590d)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:__ghes_print_estatus
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
```
```
In drivers/regulator/core.c (ffffffff814dd500)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff814e0acd)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:get_current_tty
  - drivers/tty/tty_io.c:__proc_set_tty
  - drivers/tty/tty_io.c:tty_find_polling_driver
  - drivers/tty/tty_io.c:__tty_hangup
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
```
In drivers/tty/tty_buffer.c (ffffffff814ea645)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/tty/tty_port.c (ffffffff814eb32a)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff818243ba)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
```
```
In drivers/tty/pty.c (ffffffff814eca3d)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
```
```
In drivers/tty/sysrq.c (ffffffff814ed982)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/char/virtio_console.c (ffffffff81518420)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
```
```
In drivers/char/hw_random/core.c (ffffffff8151a4dd)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff8155bb08)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_report_event
```
```
In drivers/base/firmware_class.c (ffffffff8155f431)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:_request_firmware
```
```
In drivers/base/devcoredump.c (ffffffff8156c972)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/block/loop.c (ffffffff81570426)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
```
```
In drivers/mfd/mfd-core.c (ffffffff8158a666)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81598fa5)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:get_ndd
```
```
In drivers/dma-buf/fence.c (ffffffff815a3efd)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
```
```
In drivers/dma-buf/reservation.c (ffffffff815a5446)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
```
```
In drivers/scsi/hosts.c (ffffffff815a8674)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_host_alloc
```
```
In drivers/scsi/scsi_lib.c (ffffffff815af84a)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
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
  - drivers/scsi/scsi_lib.c:scsi_request_fn
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff815b5d74)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
```
```
In drivers/scsi/sd.c (ffffffff815bb848)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sr.c (ffffffff815c0f6d)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_open
```
```
In drivers/scsi/sg.c (ffffffff815c3245)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffffffff815cf508)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-scsi.c (ffffffff815d188b)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
```
```
In drivers/spi/spi.c (ffffffff815e8feb)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_master
```
```
In drivers/net/phy/phy.c (ffffffff815e9ffa)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_stop_interrupts
```
```
In drivers/usb/core/hub.c (ffffffff816052d4)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff8160c66d)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_get_hcd
```
```
In drivers/usb/core/urb.c (ffffffff8160ff79)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_anchor_urb
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/urb.c:usb_get_from_anchor
```
```
In drivers/usb/core/message.c (ffffffff81613012)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/file.c (ffffffff816173b4)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_register_dev
```
```
In drivers/input/serio/serio.c (ffffffff816638fd)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff81669300)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/power/power_supply_core.c (ffffffff8167f146)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/power/power_supply_core.c:power_supply_unregister
```
```
In drivers/md/dm.c (ffffffff816a0a91)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dm_next_uevent_seq
```
```
In drivers/leds/led-triggers.c (ffffffff816ce496)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_event
  - drivers/leds/led-triggers.c:led_trigger_blink_setup
```
```
In drivers/clk/clk.c (ffffffff816e8cab)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_get
```
```
In drivers/devfreq/devfreq-event.c (ffffffff816edb6f)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff816ef0dd)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/skbuff.c (ffffffff81705f33)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/gen_estimator.c (ffffffff8170f4f0)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/dst.c (ffffffff81723b5b)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - net/core/dst.c:dst_release
```
```
In net/core/neighbour.c (ffffffff817244c7)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:__neigh_create
```
```
In net/core/net-sysfs.c (ffffffff8173574a)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:address_show
```
```
In net/core/netpoll.c (ffffffff817394aa)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/sched/sch_api.c (ffffffff81742fa8)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffffffff81745e2d)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffffffff8174706d)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action_n
  - net/sched/act_api.c:tc_lookup_action
```
```
In net/sched/ematch.c (ffffffff8174998f)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff8174a2b0)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_skb_destructor
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/route.c (ffffffff8175315a)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv4/ip_fragment.c (ffffffff81759b59)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/tcp_output.c (ffffffff817749f7)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/raw.c (ffffffff81784304)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/arp.c (ffffffff8178c08b)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
```
```
In net/ipv4/ipmr.c (ffffffff817a70d6)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_vif_seq_stop
  - net/ipv4/ipmr.c:reg_vif_xmit
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_get_route
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b3c65)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff817b6ce6)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/ipv6/ip6_output.c (ffffffff817c701f)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff817d4ece)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffffffff817d9b4f)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_repair_tree
  - net/ipv6/ip6_fib.c:fib6_del
```
```
In net/ipv6/raw.c (ffffffff817e6b4a)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/mcast.c (ffffffff817ebbe8)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - net/ipv6/mcast.c:inet6_mc_check
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff817f634a)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff817f7ce6)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_stop
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_next
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
```
```
In net/packet/af_packet.c (ffffffff81804a41)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff81810f42)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_release
  - net/rfkill/core.c:rfkill_fop_ioctl
```
```
In lib/klist.c (ffffffff8181779b)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
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
In arch/x86/events/core.c (ffffffff810059ae)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101549c)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_cpu_starting
  - arch/x86/events/intel/uncore.c:uncore_cpu_dying
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81045883)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff81047886)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_intel_adjust_timer
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81075af2)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
```
In kernel/fork.c (ffffffff81081518)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In kernel/cpu.c (ffffffff81083f95)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/cpu.c:notify_dead
```
```
In kernel/exit.c (ffffffff81086636)
Location: arch/x86/include/asm/atomic.h:154
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
In kernel/resource.c (ffffffff8108a981)
Location: arch/x86/include/asm/atomic.h:154
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
In kernel/ptrace.c (ffffffff8108e6d1)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff81092a58)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/signal.c:SYSC_kill
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:kill_pgrp
```
```
In kernel/sys.c (ffffffff81098990)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_setpriority
```
```
In kernel/pid.c (ffffffff810a193b)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/sched/core.c (ffffffff810b2f3f)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:build_sched_domains
```
```
In kernel/sched/auto_group.c (ffffffff810c8cc9)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/sched/auto_group.c:proc_sched_autogroup_show_task
  - kernel/sched/auto_group.c:proc_sched_autogroup_show_task
  - kernel/sched/auto_group.c:proc_sched_autogroup_set_nice
  - kernel/sched/auto_group.c:proc_sched_autogroup_set_nice
  - kernel/sched/auto_group.c:sched_autogroup_fork
  - kernel/sched/auto_group.c:sched_autogroup_fork
  - kernel/sched/auto_group.c:sched_autogroup_create_attach
  - kernel/sched/auto_group.c:sched_autogroup_create_attach
  - kernel/sched/auto_group.c:autogroup_move_group
```
```
In kernel/locking/mutex.c (ffffffff8189c02b)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:__ww_mutex_lock
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
```
```
In kernel/locking/spinlock.c (ffffffff8189ec16)
Location: arch/x86/include/asm/atomic.h:154
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
In kernel/power/process.c (ffffffff810d2aaf)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/irq/manage.c (ffffffff810e1820)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/spurious.c (ffffffff810e2d39)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/rcu/tree.c (ffffffff810eae0d)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In kernel/time/posix-clock.c (ffffffff81101454)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/time/posix-clock.c:posix_clock_open
```
```
In kernel/module.c (ffffffff8110ed3b)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/module.c:SyS_delete_module
```
```
In kernel/cgroup.c (ffffffff81120ae0)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_pidlist_start
  - kernel/cgroup.c:cgroup_mount
```
```
In kernel/utsname.c (ffffffff81125b12)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_get
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffff81127795)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit.c (ffffffff8112a89f)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
  - kernel/audit.c:audit_log_start
```
```
In kernel/auditsc.c (ffffffff8113101a)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_set_loginuid
```
```
In kernel/relay.c (ffffffff81145636)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_open
```
```
In kernel/tracepoint.c (ffffffff811483a2)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/ftrace.c (ffffffff8114e70c)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:register_ftrace_graph
  - kernel/trace/ftrace.c:profile_graph_entry
```
```
In kernel/trace/trace.c (ffffffff8115c3bd)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In kernel/trace/tracing_map.c (ffffffff8115fa91)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:get_free_elt
```
```
In kernel/trace/trace_functions.c (ffffffff81161190)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff81161bdd)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811641af)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/blktrace.c (ffffffff81167208)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_trace_setup_queue
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
```
In kernel/trace/trace_events.c (ffffffff811687c9)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff81170a60)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In kernel/trace/trace_uprobe.c (ffffffff8117c897)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In kernel/bpf/syscall.c (ffffffff81180c0a)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff81185fb2)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/core.c (ffffffff8119051e)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/callchain.c (ffffffff81198341)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/padata.c (ffffffff8119c02f)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In mm/oom_kill.c (ffffffff811a4f8c)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In mm/vmalloc.c (ffffffff811ea238)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In mm/zswap.c (ffffffff811f605d)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff811f8dd4)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_vm_op_open
```
```
In mm/mempolicy.c (ffffffff812015f6)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
```
```
In mm/memory_hotplug.c (ffffffff8120f203)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/memcontrol.c (ffffffff8122304d)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/memory-failure.c (ffffffff81227484)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/zsmalloc.c (ffffffff8122bc56)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/exec.c (ffffffff8123a995)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/exec.c:SyS_uselib
  - fs/exec.c:SyS_uselib
```
```
In fs/fcntl.c (ffffffff81246eb8)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:SyS_fcntl
  - fs/fcntl.c:SyS_fcntl
  - fs/fcntl.c:f_getown
```
```
In fs/inode.c (ffffffff8124f3c0)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
```
```
In fs/filesystems.c (ffffffff812538fe)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:filesystems_proc_show
  - fs/filesystems.c:SyS_sysfs
  - fs/filesystems.c:SyS_sysfs
  - fs/filesystems.c:SyS_sysfs
  - fs/filesystems.c:get_filesystem_list
```
```
In fs/fs_struct.c (ffffffff81269907)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/notify/notification.c (ffffffff812780c6)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8127a7c3)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_new_group
```
```
In fs/eventfd.c (ffffffff81281b47)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/coredump.c (ffffffff8129ac3f)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/netlink.c (ffffffff812a2f50)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In fs/proc/inode.c (ffffffff812a6a24)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_fill_super
  - fs/proc/inode.c:proc_entry_rundown
  - fs/proc/inode.c:unuse_pde
```
```
In fs/proc/generic.c (ffffffff812abefb)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff812ad915)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/proc/kcore.c (ffffffff812b455e)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
```
```
In fs/kernfs/dir.c (ffffffff812b7a19)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_put_active
```
```
In fs/ext4/inode.c (ffffffff812cd194)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_iget
```
```
In fs/ext4/super.c (ffffffff812e13b9)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/ext4/extents_status.c (ffffffff8130ba2b)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_find_delayed_extent_range
```
```
In fs/jbd2/transaction.c (ffffffff81317302)
Location: arch/x86/include/asm/atomic.h:154
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
In fs/jbd2/journal.c (ffffffff8131b96e)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_errno
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
```
In fs/ecryptfs/main.c (ffffffff81337985)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In fs/fuse/file.c (ffffffff8134d8cb)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_async_req_send
```
```
In fs/fuse/inode.c (ffffffff8134f71b)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In security/keys/keyring.c (ffffffff813666a5)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/avc.c (ffffffff81375b4f)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/selinux/hooks.c (ffffffff8137abb6)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/selinux/ss/services.c (ffffffff81390984)
Location: arch/x86/include/asm/atomic.h:154
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
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_node_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_port_sid
  - security/selinux/ss/services.c:security_policydb_len
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_bounded_transition
```
```
In security/apparmor/apparmorfs.c (ffffffff813acbf4)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/apparmorfs.c:ns_rmdir_op
  - security/apparmor/apparmorfs.c:ns_rmdir_op
  - security/apparmor/apparmorfs.c:__aa_fs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/capability.c (ffffffff813afa47)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/context.c (ffffffff813b065f)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_set_current_hat
  - security/apparmor/context.c:aa_set_current_onexec
  - security/apparmor/context.c:aa_replace_current_label
  - security/apparmor/context.c:aa_get_task_label
  - security/apparmor/context.c:aa_dup_task_context
  - security/apparmor/context.c:aa_dup_task_context
  - security/apparmor/context.c:aa_dup_task_context
```
```
In security/apparmor/domain.c (ffffffff813b7bfe)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
```
```
In security/apparmor/policy.c (ffffffff813bb278)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookup_replace
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_setup_default_label
  - security/apparmor/policy.c:aa_null_profile
  - security/apparmor/policy.c:aa_null_profile
  - security/apparmor/policy.c:aa_null_profile
  - security/apparmor/policy.c:aa_null_profile
  - security/apparmor/policy.c:aa_null_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff813d8bfb)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:kref_get
```
```
In security/apparmor/procattr.c (ffffffff813bcf7a)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff813be327)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
```
```
In security/apparmor/resource.c (ffffffff813c213e)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff813c3889)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/label.c (ffffffff813c8e98)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In security/apparmor/mount.c (ffffffff813cb4d2)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (0)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In security/apparmor/af_unix.c (0)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In security/apparmor/policy_ns.c (ffffffff813d055c)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
```
```
In security/integrity/iint.c (ffffffff813d201f)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In block/blk-mq.c (ffffffff81407126)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In block/blk-mq-tag.c (ffffffff8140aefb)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - block/blk-mq-tag.c:bt_clear_tag
  - block/blk-mq-tag.c:bt_clear_tag
```
```
In block/bsg.c (ffffffff8141c00a)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In lib/kobject.c (ffffffff81431a06)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get
```
```
In lib/cpu_rmap.c (ffffffff8145df19)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
```
In drivers/pinctrl/core.c (ffffffff81466ac9)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_get
```
```
In drivers/pci/pci.c (ffffffff81484b86)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_get_new_domain_nr
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8149fb8b)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
```
```
In drivers/acpi/ec.c (ffffffff814d2ce1)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_query
```
```
In drivers/acpi/apei/ghes.c (ffffffff81505385)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:__ghes_print_estatus
```
```
In drivers/regulator/core.c (ffffffff8152e85a)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In drivers/reset/core.c (ffffffff815301de)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_deassert
```
```
In drivers/tty/tty_io.c (ffffffff81534a4d)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_standard_install
  - drivers/tty/tty_io.c:__tty_hangup
  - drivers/tty/tty_io.c:get_current_tty
  - drivers/tty/tty_io.c:__proc_set_tty
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/tty_buffer.c (ffffffff8153b619)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/tty/tty_port.c (ffffffff8153c1aa)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff8153cb5e)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/pty.c (ffffffff8153d85b)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
```
```
In drivers/tty/sysrq.c (ffffffff8153e5f2)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/tty/serial/serial_core.c (ffffffff815518a1)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/char/virtio_console.c (ffffffff8156b139)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
```
```
In drivers/char/hw_random/core.c (ffffffff8156d1cd)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff815add18)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_report_event
```
```
In drivers/base/firmware_class.c (ffffffff815b3a49)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:_request_firmware
```
```
In drivers/base/devcoredump.c (ffffffff815c1e12)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/block/loop.c (ffffffff815c5d36)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
```
```
In drivers/mfd/mfd-core.c (ffffffff815df816)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/nvdimm/core.c (ffffffff815ec121)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff815eea85)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:get_ndd
```
```
In drivers/dma-buf/reservation.c (ffffffff815fc7e2)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
```
```
In drivers/dma-buf/fence-array.c (ffffffff815fcf59)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/dma-buf/fence-array.c:fence_array_enable_signaling
```
```
In drivers/dma-buf/sync_file.c (ffffffff815fd134)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81607a3c)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
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
  - drivers/scsi/scsi_lib.c:scsi_request_fn
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8160e77f)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
```
In drivers/scsi/sd.c (ffffffff816140b8)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sr.c (ffffffff816196cd)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_open
```
```
In drivers/scsi/sg.c (ffffffff8161be5d)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffffffff816280fa)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-scsi.c (ffffffff8162ad3b)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In drivers/spi/spi.c (ffffffff816476e8)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_master
```
```
In drivers/net/phy/phy.c (ffffffff81648aba)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_stop_interrupts
```
```
In drivers/usb/core/hub.c (ffffffff81667170)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff8166c21d)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_get_hcd
```
```
In drivers/usb/core/urb.c (ffffffff81670776)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_get_from_anchor
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/urb.c:usb_anchor_urb
```
```
In drivers/usb/core/message.c (ffffffff816730da)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/file.c (ffffffff816774a1)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_register_dev
```
```
In drivers/input/serio/serio.c (ffffffff816c3afd)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff816c92a0)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/power/power_supply_core.c (ffffffff816dfdd6)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/power/power_supply_core.c:power_supply_unregister
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff816eccd2)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
```
In drivers/md/dm.c (ffffffff81704986)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_next_uevent_seq
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dec_pending
```
```
In drivers/leds/led-triggers.c (ffffffff81731aca)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_setup
  - drivers/leds/led-triggers.c:led_trigger_event
```
```
In drivers/clk/clk.c (ffffffff8174d1fb)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_get
```
```
In drivers/devfreq/devfreq-event.c (ffffffff81752a7f)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff81753e0e)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/skbuff.c (ffffffff8176df65)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/gen_estimator.c (ffffffff81776d6a)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/dst.c (ffffffff8178d5ab)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/core/dst.c:dst_release
```
```
In net/core/neighbour.c (ffffffff8178de97)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:__neigh_create
```
```
In net/core/net-sysfs.c (ffffffff817a189a)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:address_show
```
```
In net/core/netpoll.c (ffffffff817a575e)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/sched/sch_api.c (ffffffff817afe45)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffffffff817b2d6d)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffffffff817b433d)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (ffffffff817b68fe)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff817b7aee)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/ipv4/ip_fragment.c (ffffffff817c5f02)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/tcp_output.c (ffffffff817e197b)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/raw.c (ffffffff817f18c4)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/arp.c (ffffffff817f96be)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
```
```
In net/ipv4/ipmr.c (ffffffff81814db6)
Location: arch/x86/include/asm/atomic.h:154
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
In net/xfrm/xfrm_policy.c (ffffffff81821875)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff81823d16)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/ipv6/ip6_output.c (ffffffff818340dd)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff81843142)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffffffff81847caf)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_repair_tree
```
```
In net/ipv6/raw.c (ffffffff81854ee6)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/mcast.c (ffffffff8185a449)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/ipv6/mcast.c:inet6_mc_check
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff8186550a)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81868d11)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_next
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_stop
```
```
In net/packet/af_packet.c (ffffffff81878a6c)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff81883ed4)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
  - net/rfkill/core.c:rfkill_fop_release
```
```
In lib/klist.c (ffffffff8189124b)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
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
In arch/x86/events/core.c (ffffffff810059de)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff810157a4)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81043c9c)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810474ca)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff81049416)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_intel_adjust_timer
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81079692)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
```
In kernel/fork.c (ffffffff81085f62)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In kernel/cpu.c (ffffffff810884f8)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In kernel/exit.c (ffffffff8108b5a7)
Location: arch/x86/include/asm/atomic.h:154
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
In kernel/resource.c (ffffffff8108f8d1)
Location: arch/x86/include/asm/atomic.h:154
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
In kernel/ptrace.c (ffffffff81093262)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff810979e8)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/signal.c:SYSC_kill
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:kill_pgrp
```
```
In kernel/sys.c (ffffffff8109d940)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_setpriority
```
```
In kernel/pid.c (ffffffff810a69fb)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/sched/core.c (ffffffff810b9527)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:build_sched_domains
```
```
In kernel/sched/auto_group.c (ffffffff810cecd9)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/sched/auto_group.c:proc_sched_autogroup_show_task
  - kernel/sched/auto_group.c:proc_sched_autogroup_show_task
  - kernel/sched/auto_group.c:proc_sched_autogroup_set_nice
  - kernel/sched/auto_group.c:proc_sched_autogroup_set_nice
  - kernel/sched/auto_group.c:sched_autogroup_fork
  - kernel/sched/auto_group.c:sched_autogroup_fork
  - kernel/sched/auto_group.c:sched_autogroup_create_attach
  - kernel/sched/auto_group.c:sched_autogroup_create_attach
  - kernel/sched/auto_group.c:autogroup_move_group
```
```
In kernel/locking/spinlock.c (ffffffff818d40d6)
Location: arch/x86/include/asm/atomic.h:154
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
In kernel/power/process.c (ffffffff810d963f)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/irq/manage.c (ffffffff810e816c)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/spurious.c (ffffffff810e9630)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/rcu/tree.c (ffffffff810f1d72)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
```
```
In kernel/time/posix-clock.c (ffffffff81109114)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/time/posix-clock.c:posix_clock_open
```
```
In kernel/module.c (ffffffff8111665b)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/module.c:SyS_delete_module
```
```
In kernel/cgroup.c (ffffffff81128fcd)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_pidlist_start
  - kernel/cgroup.c:cgroup_mount
```
```
In kernel/utsname.c (ffffffff8112f522)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_get
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffff8113131c)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit.c (ffffffff811345bf)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
```
```
In kernel/auditsc.c (ffffffff8113ad8c)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_set_loginuid
  - kernel/auditsc.c:audit_set_loginuid
```
```
In kernel/relay.c (ffffffff8114f496)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_open
```
```
In kernel/tracepoint.c (ffffffff8115225e)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/ftrace.c (ffffffff8115864e)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:register_ftrace_graph
  - kernel/trace/ftrace.c:profile_graph_entry
```
```
In kernel/trace/trace.c (ffffffff81166bed)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In kernel/trace/tracing_map.c (ffffffff8116a4f1)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:get_free_elt
```
```
In kernel/trace/trace_functions.c (ffffffff8116bbf0)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8116c73d)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8116f50f)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/blktrace.c (ffffffff81171b68)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_trace_setup_queue
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
```
In kernel/trace/trace_events.c (ffffffff81173bf9)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff8117c1d0)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In kernel/trace/trace_uprobe.c (ffffffff811884a7)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In kernel/bpf/syscall.c (ffffffff8118c92a)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff81193594)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/core.c (ffffffff8119f3de)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/callchain.c (ffffffff811a7d21)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/padata.c (ffffffff811abd62)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In mm/oom_kill.c (ffffffff811b56b9)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/vmalloc.c (ffffffff811fb345)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/zswap.c (ffffffff81206a99)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff812099c4)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_vm_op_open
```
```
In mm/mempolicy.c (ffffffff812130e6)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
```
```
In mm/memory_hotplug.c (ffffffff812212d3)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/memcontrol.c (ffffffff812354ad)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/memory-failure.c (ffffffff81239a3f)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/zsmalloc.c (ffffffff8123e1b2)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/exec.c (ffffffff8124d775)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/exec.c:SyS_uselib
  - fs/exec.c:SyS_uselib
```
```
In fs/fcntl.c (ffffffff81259ea8)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:SyS_fcntl
  - fs/fcntl.c:SyS_fcntl
  - fs/fcntl.c:f_getown
```
```
In fs/inode.c (ffffffff812623f0)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
```
```
In fs/filesystems.c (ffffffff81266b4e)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:filesystems_proc_show
  - fs/filesystems.c:SyS_sysfs
  - fs/filesystems.c:SyS_sysfs
  - fs/filesystems.c:SyS_sysfs
  - fs/filesystems.c:get_filesystem_list
```
```
In fs/fs_struct.c (ffffffff8127c8b7)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/notify/notification.c (ffffffff8128bda6)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8128e373)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_new_group
```
```
In fs/eventfd.c (ffffffff81295677)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/coredump.c (ffffffff812af7fe)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/netlink.c (ffffffff812b8930)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In fs/proc/inode.c (ffffffff812bc304)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_fill_super
  - fs/proc/inode.c:proc_entry_rundown
  - fs/proc/inode.c:unuse_pde
```
```
In fs/proc/generic.c (ffffffff812c17cc)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff812c3205)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/proc/kcore.c (ffffffff812c9dee)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
```
```
In fs/kernfs/dir.c (ffffffff812cd1a9)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_put_active
```
```
In fs/ext4/inode.c (ffffffff812e2f10)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_iget
```
```
In fs/ext4/super.c (ffffffff812f6ee9)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/ext4/extents_status.c (ffffffff81321a2b)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_find_delayed_extent_range
```
```
In fs/jbd2/transaction.c (ffffffff8132d2f2)
Location: arch/x86/include/asm/atomic.h:154
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
In fs/jbd2/journal.c (ffffffff8133195e)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_errno
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
```
In fs/ecryptfs/main.c (ffffffff8134d755)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In fs/fuse/file.c (ffffffff813631d7)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_async_req_send
```
```
In fs/fuse/inode.c (ffffffff81365035)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In security/keys/keyring.c (ffffffff8137cec5)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/avc.c (ffffffff8138c47f)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/selinux/hooks.c (ffffffff81391006)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/selinux/ss/services.c (ffffffff813a75a4)
Location: arch/x86/include/asm/atomic.h:154
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
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_node_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_port_sid
  - security/selinux/ss/services.c:security_policydb_len
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_bounded_transition
```
```
In security/apparmor/apparmorfs.c (ffffffff813c3a04)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/apparmorfs.c:ns_rmdir_op
  - security/apparmor/apparmorfs.c:ns_rmdir_op
  - security/apparmor/apparmorfs.c:__aa_fs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/capability.c (ffffffff813c6bc7)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/context.c (ffffffff813c77df)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_set_current_hat
  - security/apparmor/context.c:aa_set_current_onexec
  - security/apparmor/context.c:aa_replace_current_label
  - security/apparmor/context.c:aa_get_task_label
  - security/apparmor/context.c:aa_dup_task_context
  - security/apparmor/context.c:aa_dup_task_context
  - security/apparmor/context.c:aa_dup_task_context
```
```
In security/apparmor/domain.c (ffffffff813cf047)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
```
```
In security/apparmor/policy.c (ffffffff813d263f)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookup_replace
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_setup_default_label
  - security/apparmor/policy.c:aa_null_profile
  - security/apparmor/policy.c:aa_null_profile
  - security/apparmor/policy.c:aa_null_profile
  - security/apparmor/policy.c:aa_null_profile
  - security/apparmor/policy.c:aa_null_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff813f073f)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:kref_get
```
```
In security/apparmor/procattr.c (ffffffff813d43aa)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff813d57a7)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
```
```
In security/apparmor/resource.c (ffffffff813d95de)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff813dae19)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/label.c (ffffffff813e04b4)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In security/apparmor/mount.c (ffffffff813e2b52)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (0)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In security/apparmor/af_unix.c (0)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In security/apparmor/policy_ns.c (ffffffff813e7c5c)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
```
```
In security/integrity/iint.c (ffffffff813e973f)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In block/blk-mq.c (ffffffff814215b6)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In block/bsg.c (ffffffff8143714d)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In block/blk-wbt.c (ffffffff81449e89)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In lib/kobject.c (ffffffff8144dc76)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get
```
```
In lib/cpu_rmap.c (ffffffff8147c949)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
```
In lib/sbitmap.c (ffffffff81482496)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_clear
  - lib/sbitmap.c:sbitmap_queue_clear
```
```
In drivers/pinctrl/core.c (ffffffff81485db9)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_get
```
```
In drivers/pci/pci.c (ffffffff814a6306)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_get_new_domain_nr
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff814c170b)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
```
```
In drivers/acpi/ec.c (ffffffff814f51b2)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_query
```
```
In drivers/acpi/apei/ghes.c (ffffffff81529575)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:__ghes_print_estatus
```
```
In drivers/clk/clk.c (ffffffff81535a6b)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_get
```
```
In drivers/regulator/core.c (ffffffff8155aec4)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In drivers/reset/core.c (ffffffff8155cbf7)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_deassert
  - drivers/reset/core.c:reset_control_assert
  - drivers/reset/core.c:reset_control_reset
```
```
In drivers/tty/tty_io.c (ffffffff8156117d)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_standard_install
  - drivers/tty/tty_io.c:__tty_hangup
  - drivers/tty/tty_io.c:get_current_tty
  - drivers/tty/tty_io.c:__proc_set_tty
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/tty_buffer.c (ffffffff81567ca9)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/tty/tty_port.c (ffffffff8156880a)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff815691ae)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/pty.c (ffffffff81569eab)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
```
```
In drivers/tty/sysrq.c (ffffffff8156ac42)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/tty/serial/serial_core.c (ffffffff8157e181)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/char/virtio_console.c (ffffffff815978a9)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
```
```
In drivers/char/hw_random/core.c (ffffffff8159993d)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff815dcae8)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_report_event
```
```
In drivers/base/firmware_class.c (ffffffff815e2dc9)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:_request_firmware
```
```
In drivers/base/devcoredump.c (ffffffff815f1262)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/block/loop.c (ffffffff815f39f6)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
```
```
In drivers/mfd/mfd-core.c (ffffffff8160c4b6)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/nvdimm/core.c (ffffffff81618d15)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8161bbc5)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:get_ndd
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff8162a4c9)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/reservation.c (ffffffff8162ab72)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff8162bc8f)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8162c412)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/scsi_lib.c (ffffffff81637342)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
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
  - drivers/scsi/scsi_lib.c:scsi_request_fn
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8163e01f)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
```
In drivers/scsi/sd.c (ffffffff81643a28)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sr.c (ffffffff8164a35d)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_open
```
```
In drivers/scsi/sg.c (ffffffff8164caae)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffffffff81658d6a)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-scsi.c (ffffffff8165bfbb)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In drivers/spi/spi.c (ffffffff816787e3)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_master
```
```
In drivers/net/phy/phy.c (ffffffff81679c6a)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_stop_interrupts
```
```
In drivers/usb/core/hub.c (ffffffff81694e90)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff81699f1d)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_get_hcd
```
```
In drivers/usb/core/urb.c (ffffffff8169e426)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_get_from_anchor
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/urb.c:usb_anchor_urb
```
```
In drivers/usb/core/message.c (ffffffff816a0d8a)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/file.c (ffffffff816a5181)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_register_dev
```
```
In drivers/input/serio/serio.c (ffffffff816f1abd)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff816f7280)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81710246)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8171dd88)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
```
In drivers/md/dm.c (ffffffff81736846)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_next_uevent_seq
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dec_pending
```
```
In drivers/leds/led-triggers.c (ffffffff81764a9a)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_setup
  - drivers/leds/led-triggers.c:led_trigger_event
```
```
In drivers/devfreq/devfreq-event.c (ffffffff8177e86f)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff817803ae)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/skbuff.c (ffffffff8179b3a5)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff817aa6f1)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/core/dst.c (ffffffff817bae3b)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/core/dst.c:dst_release
```
```
In net/core/neighbour.c (ffffffff817bb847)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:__neigh_create
```
```
In net/core/net-sysfs.c (ffffffff817d01ba)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:address_show
```
```
In net/core/netpoll.c (ffffffff817d41ce)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/sched/sch_api.c (ffffffff817df535)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffffffff817e25ed)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffffffff817e3bed)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (ffffffff817e638e)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff817e755e)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/ipv4/ip_fragment.c (ffffffff817f5a02)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/tcp_output.c (ffffffff81811e5b)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/raw.c (ffffffff81822641)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff81824ca3)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/arp.c (ffffffff8182a58b)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
```
```
In net/ipv4/ipmr.c (ffffffff81846576)
Location: arch/x86/include/asm/atomic.h:154
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
In net/xfrm/xfrm_policy.c (ffffffff81853085)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff81855666)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/ipv6/ip6_output.c (ffffffff81865b3d)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff81874eb2)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffffffff81879aec)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_repair_tree
```
```
In net/ipv6/raw.c (ffffffff81886c56)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/mcast.c (ffffffff8188c399)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/ipv6/mcast.c:inet6_mc_check
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81897bd7)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff8189bb61)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_next
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_stop
```
```
In net/packet/af_packet.c (ffffffff818acb6c)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff818b8774)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
  - net/rfkill/core.c:rfkill_fop_release
```
```
In lib/klist.c (ffffffff818c59db)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
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
In arch/x86/events/core.c (ffffffff8100589e)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff81013c9d)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81042494)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81047052)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff81048dda)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_intel_adjust_timer
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81077f42)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
```
In kernel/fork.c (ffffffff81083c5d)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/fork.c:walk_process_tree
```
```
In kernel/exit.c (ffffffff81088327)
Location: arch/x86/include/asm/atomic.h:154
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
In kernel/resource.c (ffffffff8108c864)
Location: arch/x86/include/asm/atomic.h:154
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
In kernel/ptrace.c (ffffffff81090389)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff81094cdb)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/signal.c:SYSC_kill
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:kill_pgrp
```
```
In kernel/sys.c (ffffffff8109a8aa)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_setpriority
```
```
In kernel/sched/core.c (ffffffff810b4104)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
```
```
In kernel/sched/topology.c (ffffffff810ccce2)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/sched/autogroup.c (ffffffff810cdbab)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
```
In kernel/locking/spinlock.c (ffffffff8190b266)
Location: arch/x86/include/asm/atomic.h:154
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
In kernel/power/process.c (ffffffff810d861f)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/irq/spurious.c (ffffffff810e8acc)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (ffffffff810ec7c2)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/rcu/tree.c (ffffffff810f6cf7)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_nmi_exit
  - kernel/rcu/tree.c:rcu_dynticks_momentary_idle
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
```
```
In kernel/livepatch/transition.c (ffffffff810f9344)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
```
```
In kernel/module.c (ffffffff81117b29)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/module.c:SyS_delete_module
```
```
In kernel/cgroup/cgroup.c (ffffffff811258e8)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_mount
```
```
In kernel/pid_namespace.c (ffffffff811327b1)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/audit.c (ffffffff81134b34)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In kernel/auditsc.c (ffffffff8113c39c)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_set_loginuid
  - kernel/auditsc.c:audit_set_loginuid
```
```
In kernel/watchdog_hld.c (ffffffff8114f707)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:watchdog_nmi_enable
```
```
In kernel/tracepoint.c (ffffffff8115483e)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/ftrace.c (ffffffff8115b958)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:register_ftrace_graph
  - kernel/trace/ftrace.c:profile_graph_entry
```
```
In kernel/trace/trace.c (ffffffff8116a0bc)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In kernel/trace/tracing_map.c (ffffffff8116d491)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:get_free_elt
```
```
In kernel/trace/trace_functions.c (ffffffff8116ed80)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8116fae1)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811726cf)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/blktrace.c (ffffffff81174f38)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_trace_setup_queue
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
```
In kernel/trace/trace_events.c (ffffffff8117681a)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff8117ee90)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In kernel/trace/trace_uprobe.c (ffffffff8118b3f7)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In kernel/bpf/syscall.c (ffffffff8119187a)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff8119a852)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/callchain.c (ffffffff811af4b1)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/padata.c (ffffffff811b31b6)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In mm/oom_kill.c (ffffffff811bd3d6)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/vmalloc.c (ffffffff81206085)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/zswap.c (ffffffff812125e4)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/mempolicy.c (ffffffff8121e418)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
```
```
In mm/memory_hotplug.c (ffffffff8122ca33)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/memcontrol.c (ffffffff81240ed4)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/memory-failure.c (ffffffff81244ec0)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In mm/zsmalloc.c (ffffffff81249b51)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/exec.c (ffffffff81259736)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/exec.c:SyS_uselib
  - fs/exec.c:SyS_uselib
```
```
In fs/fcntl.c (ffffffff81266892)
Location: arch/x86/include/asm/atomic.h:154
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
In fs/inode.c (ffffffff8126fcd0)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
```
```
In fs/filesystems.c (ffffffff812743ce)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:filesystems_proc_show
  - fs/filesystems.c:SyS_sysfs
  - fs/filesystems.c:SyS_sysfs
  - fs/filesystems.c:SyS_sysfs
  - fs/filesystems.c:get_filesystem_list
```
```
In fs/fs_struct.c (ffffffff81289f5f)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/notify/notification.c (ffffffff81298d26)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/coredump.c (ffffffff812bd189)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/netlink.c (ffffffff812c5d00)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In fs/proc/inode.c (ffffffff812c94e6)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_entry_rundown
  - fs/proc/inode.c:unuse_pde
```
```
In fs/proc/generic.c (ffffffff812cec9c)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff812d0485)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/proc/kcore.c (ffffffff812d72c7)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
```
```
In fs/kernfs/dir.c (ffffffff812da789)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_put_active
```
```
In fs/ext4/extents_status.c (ffffffff812f08c4)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_find_delayed_extent_range
```
```
In fs/ext4/inode.c (ffffffff81307433)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_iget
```
```
In fs/ext4/super.c (ffffffff8132b7c8)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/jbd2/transaction.c (ffffffff813424c2)
Location: arch/x86/include/asm/atomic.h:154
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
In fs/jbd2/journal.c (ffffffff8134684e)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_errno
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
```
In fs/ecryptfs/main.c (ffffffff813622f5)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/keys/keyring.c (ffffffff81390c59)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/avc.c (ffffffff813a227f)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/selinux/hooks.c (ffffffff813a7767)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/selinux/ss/services.c (ffffffff813bdf7f)
Location: arch/x86/include/asm/atomic.h:154
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
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_node_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_ib_endport_sid
  - security/selinux/ss/services.c:security_ib_pkey_sid
  - security/selinux/ss/services.c:security_port_sid
  - security/selinux/ss/services.c:security_policydb_len
  - security/selinux/ss/services.c:security_sid_to_context_core
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_bounded_transition
```
```
In security/apparmor/policy.c (ffffffff813e430c)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In security/integrity/iint.c (ffffffff813f5b3a)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In block/blk-mq.c (ffffffff8142ff05)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In block/blk-wbt.c (ffffffff81458299)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In lib/sbitmap.c (ffffffff8148b8e2)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_clear
```
```
In drivers/pci/pci.c (ffffffff814b02a6)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_get_new_domain_nr
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/acpi/apei/ghes.c (ffffffff8153c045)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:__ghes_print_estatus
```
```
In drivers/regulator/core.c (ffffffff8156f192)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In drivers/reset/core.c (ffffffff8157158c)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff815734b3)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/tty/tty_buffer.c (ffffffff8157b253)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8157d788)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/sysrq.c (ffffffff8157f272)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/tty/serial/serial_core.c (ffffffff815923b1)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/base/power/wakeup.c (ffffffff815f1917)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In drivers/base/devcoredump.c (ffffffff816053c5)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/block/loop.c (ffffffff816086d6)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
```
```
In drivers/mfd/mfd-core.c (ffffffff816205c6)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/scsi/scsi_lib.c (ffffffff8164cf98)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
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
  - drivers/scsi/scsi_lib.c:scsi_request_fn
```
```
In drivers/scsi/sd.c (ffffffff816581e8)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffff81661263)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffffffff8166d56b)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In drivers/ata/libata-scsi.c (ffffffff8167160b)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In drivers/spi/spi.c (ffffffff8168cf34)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/net/phy/phy.c (ffffffff8168ed9a)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_stop_interrupts
```
```
In drivers/input/serio/serio.c (ffffffff817073ad)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff8170cd80)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81728676)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/md/dm.c (ffffffff8174fc76)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_next_uevent_seq
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dec_pending
```
```
In drivers/edac/edac_device.c (ffffffff8175d8a6)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffff8175f8a6)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff817604c6)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/leds/led-triggers.c (ffffffff8178345b)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
```
In drivers/devfreq/devfreq.c (ffffffff8179ca17)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (ffffffff8179d358)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff8179ef1b)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In arch/x86/pci/common.c (ffffffff817aab55)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
```
```
In net/core/skbuff.c (ffffffff817bb5e5)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff817c8d51)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/core/dst.c (ffffffff817d9a3b)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
```
```
In net/core/neighbour.c (ffffffff817d9fd6)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:__neigh_create
```
```
In net/core/net-sysfs.c (ffffffff817ef8e8)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:address_show
```
```
In net/core/netpoll.c (ffffffff817f3517)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/sched/sch_api.c (ffffffff817fe985)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffffffff81801e5d)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffffffff8180353d)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (ffffffff81805e2e)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff818071f3)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/ipv4/ip_fragment.c (ffffffff81815e39)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/raw.c (ffffffff81843291)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff81848154)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/arp.c (ffffffff8184b7a8)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
```
```
In net/ipv4/ipmr.c (ffffffff81868356)
Location: arch/x86/include/asm/atomic.h:154
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
In net/xfrm/xfrm_policy.c (ffffffff81876591)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff818791f6)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/ipv6/ip6_output.c (ffffffff8188a2c8)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/addrconf.c (ffffffff8188d290)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
```
```
In net/ipv6/route.c (ffffffff81899cf0)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffffffff8189f54c)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_repair_tree
```
```
In net/ipv6/raw.c (ffffffff818ad0df)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/mcast.c (ffffffff818b2a78)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/ipv6/mcast.c:inet6_mc_check
```
```
In net/ipv6/ip6mr.c (ffffffff818c1f4f)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_next
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_stop
```
```
In net/packet/af_packet.c (ffffffff818d07de)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff818df0c4)
Location: arch/x86/include/asm/atomic.h:154
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
  - net/rfkill/core.c:rfkill_fop_release
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
In arch/x86/events/core.c (ffffffff81005b6f)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff810145ed)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81045934)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104aafe)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff8104c80a)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_intel_adjust_timer
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8107e2a2)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
```
In kernel/fork.c (ffffffff8108a54f)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/fork.c:walk_process_tree
```
```
In kernel/exit.c (ffffffff8108f0a8)
Location: arch/x86/include/asm/atomic.h:155
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
In kernel/resource.c (ffffffff810935a4)
Location: arch/x86/include/asm/atomic.h:155
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
In kernel/ptrace.c (ffffffff810971f9)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff8109bb7d)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/signal.c:SYSC_kill
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:kill_pgrp
```
```
In kernel/sys.c (ffffffff810a158a)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_setpriority
```
```
In kernel/sched/core.c (ffffffff810bb3b4)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
```
```
In kernel/sched/topology.c (ffffffff810d3a87)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/sched/autogroup.c (ffffffff810d542b)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
```
In kernel/locking/spinlock.c (ffffffff81995606)
Location: arch/x86/include/asm/atomic.h:155
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
In kernel/power/process.c (ffffffff810e070f)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/irq/spurious.c (ffffffff810f0e9c)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (ffffffff810f4f02)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/rcu/tree.c (ffffffff81100d37)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_nmi_exit
  - kernel/rcu/tree.c:rcu_dynticks_momentary_idle
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
```
```
In kernel/livepatch/transition.c (ffffffff81103d79)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
```
```
In kernel/module.c (ffffffff81123109)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/module.c:SyS_delete_module
```
```
In kernel/cgroup/cgroup.c (ffffffff81131bb9)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_mount
```
```
In kernel/pid_namespace.c (ffffffff8113f7f4)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/audit.c (ffffffff8114187a)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
```
```
In kernel/auditsc.c (ffffffff8114911c)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_set_loginuid
  - kernel/auditsc.c:audit_set_loginuid
```
```
In kernel/tracepoint.c (ffffffff8116105e)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/ftrace.c (ffffffff81168a28)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:register_ftrace_graph
  - kernel/trace/ftrace.c:profile_graph_entry
```
```
In kernel/trace/trace.c (ffffffff8117705c)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
```
```
In kernel/trace/tracing_map.c (ffffffff8117a541)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:get_free_elt
```
```
In kernel/trace/trace_functions.c (ffffffff8117be70)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8117cbf7)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8117f86f)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (ffffffff81183fda)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff8118c751)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
```
```
In kernel/trace/trace_uprobe.c (ffffffff81198ec7)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In kernel/bpf/syscall.c (ffffffff8119e84a)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811aa042)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/callchain.c (ffffffff811c3061)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/padata.c (ffffffff811c6e06)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In kernel/memremap.c (ffffffff811c9286)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
```
```
In mm/oom_kill.c (ffffffff811d1ffb)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/vmalloc.c (ffffffff8121eda5)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/zswap.c (ffffffff8122ccd4)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/mempolicy.c (ffffffff81239668)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
```
```
In mm/memory_hotplug.c (ffffffff81248268)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/memcontrol.c (ffffffff81260c14)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/memory-failure.c (ffffffff81264db0)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
```
```
In mm/zsmalloc.c (ffffffff81269db1)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/exec.c (ffffffff8127b996)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - fs/exec.c:SyS_uselib
  - fs/exec.c:SyS_uselib
```
```
In fs/fcntl.c (ffffffff81289132)
Location: arch/x86/include/asm/atomic.h:155
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
In fs/inode.c (ffffffff812925f0)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
```
```
In fs/filesystems.c (ffffffff81296cce)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:filesystems_proc_show
  - fs/filesystems.c:SyS_sysfs
  - fs/filesystems.c:SyS_sysfs
  - fs/filesystems.c:SyS_sysfs
  - fs/filesystems.c:get_filesystem_list
```
```
In fs/fs_struct.c (ffffffff812aca9f)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/notify/notification.c (ffffffff812bc0b6)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/coredump.c (ffffffff812e0a93)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/netlink.c (ffffffff812e9bb0)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In fs/proc/inode.c (ffffffff812edd66)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_entry_rundown
  - fs/proc/inode.c:unuse_pde
```
```
In fs/proc/generic.c (ffffffff812f349c)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff812f4cc5)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/proc/kcore.c (ffffffff812fba59)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
```
```
In fs/kernfs/dir.c (ffffffff812fefea)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_put_active
```
```
In fs/ext4/extents_status.c (ffffffff813153f4)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_find_delayed_extent_range
```
```
In fs/ext4/inode.c (ffffffff8132c01c)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_iget
```
```
In fs/ext4/super.c (ffffffff8134fc28)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/jbd2/transaction.c (ffffffff81366af2)
Location: arch/x86/include/asm/atomic.h:155
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
In fs/jbd2/journal.c (ffffffff8136af3e)
Location: arch/x86/include/asm/atomic.h:155
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
In fs/ecryptfs/main.c (ffffffff81386f75)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/keys/keyring.c (ffffffff813b6248)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/avc.c (ffffffff813c807f)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/selinux/hooks.c (ffffffff813ccf37)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/selinux/ss/services.c (ffffffff813e411f)
Location: arch/x86/include/asm/atomic.h:155
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
  - security/selinux/ss/services.c:security_get_bools
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_node_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_ib_endport_sid
  - security/selinux/ss/services.c:security_ib_pkey_sid
  - security/selinux/ss/services.c:security_port_sid
  - security/selinux/ss/services.c:security_policydb_len
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:security_sid_to_context_core
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_bounded_transition
```
```
In security/apparmor/policy.c (ffffffff8140b24c)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In security/integrity/iint.c (ffffffff8141dc2a)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In block/blk-mq.c (ffffffff8145b886)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
```
```
In block/blk-wbt.c (ffffffff81483ff9)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
```
```
In lib/sbitmap.c (ffffffff814c7a02)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_clear
```
```
In drivers/pci/pci.c (ffffffff814ef7d6)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_get_new_domain_nr
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/acpi/apei/ghes.c (ffffffff8159eba6)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:__ghes_print_estatus
```
```
In drivers/regulator/core.c (ffffffff815d3434)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
```
```
In drivers/reset/core.c (ffffffff815d596e)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff815d8f36)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/tty/tty_buffer.c (ffffffff815dfc63)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/tty/tty_jobctrl.c (ffffffff815e22ad)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/sysrq.c (ffffffff815e3de2)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/tty/serial/serial_core.c (ffffffff815f6de1)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/base/power/wakeup.c (ffffffff81658f07)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
```
```
In drivers/base/devcoredump.c (ffffffff8166d7cb)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/block/loop.c (ffffffff8166f9f2)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
```
```
In drivers/mfd/mfd-core.c (ffffffff81688e06)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/scsi/scsi_lib.c (ffffffff816b6287)
Location: arch/x86/include/asm/atomic.h:155
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
In drivers/scsi/sd.c (ffffffff816c16a8)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffff816ca3c3)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffffffff816d6bbb)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
```
```
In drivers/ata/libata-scsi.c (ffffffff816dabf1)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
```
```
In drivers/input/serio/serio.c (ffffffff8177858d)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff8177dfc3)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81799d76)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/md/dm.c (ffffffff817c1e36)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_next_uevent_seq
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dec_pending
```
```
In drivers/edac/edac_device.c (ffffffff817cf916)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffff817d1936)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff817d2556)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/edac/ghes_edac.c (ffffffff817d38ae)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In drivers/leds/led-triggers.c (ffffffff817f981b)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
```
In drivers/devfreq/devfreq.c (ffffffff81813a0a)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (ffffffff81814498)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff8181607a)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In arch/x86/pci/common.c (ffffffff81822046)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
```
```
In net/core/skbuff.c (ffffffff818336d5)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff818429f1)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/core/dst.c (ffffffff818543db)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
```
```
In net/core/neighbour.c (ffffffff81854779)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:__neigh_create
```
```
In net/core/net-sysfs.c (ffffffff8186ae88)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:address_show
```
```
In net/core/netpoll.c (ffffffff8186e907)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/sched/sch_api.c (ffffffff8187c615)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffffffff8187ffed)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffffffff818819bd)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (ffffffff81884b4e)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81886d19)
Location: arch/x86/include/asm/atomic.h:155
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
In net/ipv4/ip_fragment.c (ffffffff81895056)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/raw.c (ffffffff818c2c51)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff818c7ba8)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/arp.c (ffffffff818cb458)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
```
```
In net/ipv4/ipmr.c (ffffffff818e8fd9)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_dump
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
In net/xfrm/xfrm_policy.c (ffffffff818f635c)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff818f9c26)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/ipv6/ip6_output.c (ffffffff8190b4ca)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff8191b2f0)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffffffff81923ec4)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
```
In net/ipv6/raw.c (ffffffff8192fcf2)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/mcast.c (ffffffff819357d8)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - net/ipv6/mcast.c:inet6_mc_check
```
```
In net/ipv6/ip6mr.c (ffffffff8194588a)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_next
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_stop
```
```
In net/packet/af_packet.c (ffffffff8195570a)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff81964e54)
Location: arch/x86/include/asm/atomic.h:155
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
  - net/rfkill/core.c:rfkill_fop_release
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
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff8104f01c)
Location: include/asm-generic/atomic-instrumented.h:244
Inline: True
```
```
In kernel/locking/spinlock.c (ffffffff819f1b62)
Location: include/asm-generic/atomic-instrumented.h:244
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
  - kernel/locking/spinlock.c:_raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock
```
```
In kernel/rcu/tree.c (ffffffff81104acf)
Location: include/asm-generic/atomic-instrumented.h:244
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
In kernel/audit.c (ffffffff811502a1)
Location: include/asm-generic/atomic-instrumented.h:244
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811b363d)
Location: include/asm-generic/atomic-instrumented.h:244
Inline: True
```
```
In mm/vmalloc.c (ffffffff81241675)
Location: include/asm-generic/atomic-instrumented.h:244
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In fs/inode.c (ffffffff812b80a0)
Location: include/asm-generic/atomic-instrumented.h:244
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
```
```
In fs/quota/netlink.c (ffffffff81316ab0)
Location: include/asm-generic/atomic-instrumented.h:244
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In fs/proc/inode.c (ffffffff8131adeb)
Location: include/asm-generic/atomic-instrumented.h:244
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_entry_rundown
```
```
In fs/jbd2/transaction.c (ffffffff81393496)
Location: include/asm-generic/atomic-instrumented.h:244
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In drivers/acpi/apei/ghes.c (ffffffff815d68c5)
Location: include/asm-generic/atomic-instrumented.h:244
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
```
```
In drivers/base/power/wakeup.c (ffffffff81694b37)
Location: include/asm-generic/atomic-instrumented.h:244
Inline: True
```
```
In drivers/md/dm.c (ffffffff8180a595)
Location: include/asm-generic/atomic-instrumented.h:244
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_next_uevent_seq
```
```
In net/core/dev.c (ffffffff8188ce31)
Location: include/asm-generic/atomic-instrumented.h:244
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/ipv4/udp.c (ffffffff8191de7d)
Location: include/asm-generic/atomic-instrumented.h:244
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015777)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104ab30)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8104c6ec)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81087f0a)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
```
In kernel/sched/topology.c (ffffffff810e54e0)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/sched/autogroup.c (ffffffff810e7b67)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
```
In kernel/locking/spinlock.c (ffffffff81a2d122)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
  - kernel/locking/spinlock.c:_raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock
```
```
In kernel/irq/spurious.c (ffffffff811049ef)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (ffffffff81108d82)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/rcu/tree.c (ffffffff81114292)
Location: include/asm-generic/atomic-instrumented.h:291
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
In kernel/audit.c (ffffffff8115cf4d)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
```
```
In kernel/auditsc.c (ffffffff81164ac3)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_set_loginuid
  - kernel/auditsc.c:audit_set_loginuid
```
```
In kernel/trace/ftrace.c (ffffffff8117f8ab)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
```
```
In kernel/trace/trace.c (ffffffff81193af0)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
```
```
In kernel/trace/tracing_map.c (ffffffff811977f2)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_insert
```
```
In kernel/trace/trace_functions.c (ffffffff811988e0)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff81199698)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8119c0f4)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (ffffffff811a13a4)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811a93e0)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811c1cc5)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811d2e40)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/callchain.c (ffffffff811f38c0)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/padata.c (ffffffff811f7db4)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In kernel/memremap.c (ffffffff811f9f25)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - kernel/memremap.c:dev_pagemap_get_ops
```
```
In mm/vmalloc.c (ffffffff81255d75)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/zswap.c (ffffffff81263bd4)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/memcontrol.c (ffffffff81299b14)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In fs/inode.c (ffffffff812cd1f0)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
```
```
In fs/notify/notification.c (ffffffff812f97f5)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/coredump.c (ffffffff813223af)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/netlink.c (ffffffff8132da60)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In fs/proc/inode.c (ffffffff81331e6b)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_entry_rundown
```
```
In fs/devpts/inode.c (ffffffff8134c245)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/jbd2/transaction.c (ffffffff813ac1b6)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/ecryptfs/main.c (ffffffff813cf1e5)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/selinux/avc.c (ffffffff814130ee)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/apparmor/policy.c (ffffffff81459921)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In block/blk-mq.c (ffffffff814a8265)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
```
```
In drivers/pci/pci.c (ffffffff81534265)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/acpi/apei/ghes.c (ffffffff815f0195)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:__ghes_print_estatus
```
```
In drivers/regulator/core.c (ffffffff81627df0)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (ffffffff8162b5ca)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff816b51c7)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
```
```
In drivers/base/devcoredump.c (ffffffff816c9df5)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/mfd/mfd-core.c (ffffffff816e635a)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/scsi/scsi_lib.c (ffffffff81715044)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/sd.c (ffffffff817218fd)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffff8172a929)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffffffff81734c10)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
```
```
In drivers/ata/libata-scsi.c (ffffffff81739721)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
```
```
In drivers/input/serio/serio.c (ffffffff817e06fd)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff817e656b)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/md/dm.c (ffffffff81836595)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_next_uevent_seq
```
```
In drivers/edac/edac_device.c (ffffffff81843f65)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffff81845ed5)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff818469c5)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/edac/ghes_edac.c (ffffffff8184800b)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In drivers/devfreq/devfreq.c (ffffffff8187c99a)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (ffffffff8187dda9)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff8187f8d7)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/skbuff.c (ffffffff8189e713)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
```
In net/core/dev.c (ffffffff818ae081)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/core/neighbour.c (ffffffff818c7c57)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/netpoll.c (ffffffff818e88b4)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffffffff818f281c)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/ipv4/ip_fragment.c (ffffffff81916235)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/udp.c (ffffffff8194cacd)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_state.c (ffffffff81983dae)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/packet/af_packet.c (ffffffff819e4ca6)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff819f587d)
Location: include/asm-generic/atomic-instrumented.h:291
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
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
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff81016e4d)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104dbbb)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8104f680)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108bb5a)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
```
In kernel/sched/topology.c (ffffffff810ec36e)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/autogroup.c (ffffffff810eeadf)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
```
In kernel/locking/spinlock.c (ffffffff81a9d2f2)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
  - kernel/locking/spinlock.c:_raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock
```
```
In kernel/irq/spurious.c (ffffffff8110dc01)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (ffffffff81112362)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/rcu/tree.c (ffffffff8111a933)
Location: include/asm-generic/atomic-instrumented.h:69
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
In kernel/audit.c (ffffffff8116b52a)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/trace/ftrace.c (ffffffff8118c99e)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811a1770)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In kernel/trace/tracing_map.c (ffffffff811a51fe)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In kernel/trace/trace_functions.c (ffffffff811a64a0)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811a72b8)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811a9cff)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (ffffffff811af2cb)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811b7330)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811d2315)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811e757d)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/callchain.c (ffffffff8120b68a)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/padata.c (ffffffff8120fc35)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In mm/zswap.c (ffffffff8127eb55)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/memcontrol.c (ffffffff812b4d06)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/memremap.c (ffffffff812c2805)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages
```
```
In fs/inode.c (ffffffff812ea230)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
```
```
In fs/notify/notification.c (ffffffff81319e55)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/coredump.c (ffffffff81349d74)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/netlink.c (ffffffff8135579f)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In fs/proc/inode.c (ffffffff81359cbb)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_entry_rundown
```
```
In fs/devpts/inode.c (ffffffff81374c15)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/jbd2/transaction.c (ffffffff813d6436)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/ecryptfs/main.c (ffffffff813f9da5)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/selinux/avc.c (ffffffff81440b89)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/apparmor/policy.c (ffffffff8148706f)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In drivers/pci/pci.c (ffffffff81563735)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/acpi/apei/ghes.c (ffffffff81621f15)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:__ghes_print_estatus
```
```
In drivers/regulator/core.c (ffffffff8165c094)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (ffffffff8165ef0f)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff816eed67)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In drivers/base/devcoredump.c (ffffffff81705396)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/mfd/mfd-core.c (ffffffff8171faea)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/scsi/scsi_lib.c (ffffffff81750825)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/sd.c (ffffffff8175d380)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffff81766047)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffffffff8177058e)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-scsi.c (ffffffff81775731)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In drivers/input/serio/serio.c (ffffffff81820fbb)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff81826c26)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/md/dm.c (ffffffff81879155)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_next_uevent_seq
```
```
In drivers/edac/edac_device.c (ffffffff81886d35)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffff81888cb5)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81889775)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/edac/ghes_edac.c (ffffffff8188ae86)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In drivers/devfreq/devfreq.c (ffffffff818c7426)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/devfreq/devfreq-event.c (ffffffff818c835f)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff818c9ed4)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/skbuff.c (ffffffff818e8f84)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
```
In net/core/dev.c (ffffffff818f99b1)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/core/neighbour.c (ffffffff819146b7)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/netpoll.c (ffffffff819380c6)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffffffff8194495f)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/core/bpf_sk_storage.c (ffffffff819536ad)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/ip_fragment.c (ffffffff81978464)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/udp.c (ffffffff819b127c)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_state.c (ffffffff819ed94e)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/packet/af_packet.c (ffffffff81a53e01)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff81a64bae)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
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
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff810177f7)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104e55e)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81050000)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108c7ca)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
```
In kernel/signal.c (ffffffff810afaa4)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sched/topology.c (ffffffff810f7e15)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/autogroup.c (ffffffff810fa6df)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
```
In kernel/locking/spinlock.c (ffffffff81ad4ad2)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
  - kernel/locking/spinlock.c:_raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock
```
```
In kernel/irq/spurious.c (ffffffff81119ec1)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (ffffffff8111e5f2)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/rcu/tree.c (ffffffff81126d4f)
Location: include/asm-generic/atomic-instrumented.h:69
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
In kernel/audit.c (ffffffff8117740a)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/trace/ftrace.c (ffffffff8119859e)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811ad220)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In kernel/trace/tracing_map.c (ffffffff811b0a2e)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In kernel/trace/trace_functions.c (ffffffff811b1c90)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811b2aa8)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811b54ef)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (ffffffff811ba79b)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811c29a0)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811de8b5)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811f3cdd)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/callchain.c (ffffffff8121896a)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/padata.c (ffffffff8121d620)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In mm/zswap.c (ffffffff8128e595)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/memcontrol.c (ffffffff812c67f6)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/memremap.c (ffffffff812d471c)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/inode.c (ffffffff812fbd10)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
```
```
In fs/notify/notification.c (ffffffff8132cc85)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/io_uring.c (ffffffff81340629)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In fs/coredump.c (ffffffff81362014)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/netlink.c (ffffffff8136dadf)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In fs/proc/inode.c (ffffffff81371f0b)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_entry_rundown
```
```
In fs/devpts/inode.c (ffffffff8138ce95)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/jbd2/transaction.c (ffffffff813f0466)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/ecryptfs/main.c (ffffffff81413c75)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/selinux/avc.c (ffffffff8145a499)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/apparmor/policy.c (ffffffff814a0f1f)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In block/blk-iocost.c (ffffffff8150fbff)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In drivers/pci/pci.c (ffffffff815848f5)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/acpi/apei/ghes.c (ffffffff816439f5)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:__ghes_print_estatus
```
```
In drivers/regulator/core.c (ffffffff8167de7b)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (ffffffff816815df)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff81712f87)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In drivers/base/devcoredump.c (ffffffff81729626)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/mfd/mfd-core.c (ffffffff81743dba)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/scsi/scsi_lib.c (ffffffff81774a48)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/sd.c (ffffffff81781250)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffff8178a037)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffffffff817945ee)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-scsi.c (ffffffff817996a1)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In drivers/input/serio/serio.c (ffffffff8185242b)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff81858156)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/md/dm.c (ffffffff818aaf95)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_next_uevent_seq
```
```
In drivers/edac/edac_device.c (ffffffff818b8cf5)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffff818bac65)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff818bb725)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff818f4eac)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/devfreq/devfreq.c (ffffffff818f8ea8)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (ffffffff818fa7ef)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff818fc324)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/skbuff.c (ffffffff8191b0e4)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
```
In net/core/dev.c (ffffffff8192bb11)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/core/neighbour.c (ffffffff81946d27)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/page_pool.c (ffffffff81966ddb)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_clean_page
```
```
In net/core/netpoll.c (ffffffff8196af86)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffffffff8197995f)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/core/bpf_sk_storage.c (ffffffff81989a4d)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/ip_fragment.c (ffffffff819aedd4)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/udp.c (ffffffff819e7fa8)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_state.c (ffffffff81a247fe)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/packet/af_packet.c (ffffffff81a8aa11)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff81a9b94e)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
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
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8105441e)
Location: include/asm-generic/atomic-instrumented.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_storm_detect
```
```
In kernel/rcu/tree.c (ffffffff811349ee)
Location: include/asm-generic/atomic-instrumented.h:70
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_boot_init_percpu_data
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_momentary_dyntick_idle
```
```
In kernel/audit.c (ffffffff8118750d)
Location: include/asm-generic/atomic-instrumented.h:70
Inline: True
```
```
In fs/inode.c (ffffffff81334ab0)
Location: include/asm-generic/atomic-instrumented.h:70
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
```
```
In fs/quota/netlink.c (ffffffff813b560f)
Location: include/asm-generic/atomic-instrumented.h:70
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In fs/proc/inode.c (ffffffff813b9fcb)
Location: include/asm-generic/atomic-instrumented.h:70
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_entry_rundown
```
```
In fs/kernfs/inode.c (ffffffff813cd413)
Location: include/asm-generic/atomic-instrumented.h:70
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff8143caae)
Location: include/asm-generic/atomic-instrumented.h:70
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:stop_this_handle
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In drivers/acpi/apei/ghes.c (ffffffff816f1355)
Location: include/asm-generic/atomic-instrumented.h:70
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
```
```
In drivers/base/power/wakeup.c (ffffffff817cebd7)
Location: include/asm-generic/atomic-instrumented.h:70
Inline: True
```
```
In drivers/md/dm.c (ffffffff8197b165)
Location: include/asm-generic/atomic-instrumented.h:70
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_next_uevent_seq
```
```
In net/core/dev.c (ffffffff819ff311)
Location: include/asm-generic/atomic-instrumented.h:70
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/ipv4/route.c (ffffffff81a906cf)
Location: include/asm-generic/atomic-instrumented.h:70
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv4/udp.c (ffffffff81ad5eb8)
Location: include/asm-generic/atomic-instrumented.h:70
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8105335e)
Location: include/asm-generic/atomic-instrumented.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_storm_detect
```
```
In kernel/rcu/tree.c (ffffffff8113048e)
Location: include/asm-generic/atomic-instrumented.h:70
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
```
```
In fs/inode.c (ffffffff81340420)
Location: include/asm-generic/atomic-instrumented.h:70
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
```
```
In fs/quota/netlink.c (ffffffff813c6e3f)
Location: include/asm-generic/atomic-instrumented.h:70
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In fs/proc/inode.c (ffffffff813cba6b)
Location: include/asm-generic/atomic-instrumented.h:70
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_entry_rundown
```
```
In fs/kernfs/inode.c (ffffffff813df043)
Location: include/asm-generic/atomic-instrumented.h:70
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff81458e2e)
Location: include/asm-generic/atomic-instrumented.h:70
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:stop_this_handle
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In drivers/acpi/apei/ghes.c (ffffffff8170e6f5)
Location: include/asm-generic/atomic-instrumented.h:70
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
```
```
In drivers/base/power/wakeup.c (ffffffff817e2d23)
Location: include/asm-generic/atomic-instrumented.h:70
Inline: True
```
```
In drivers/md/dm.c (ffffffff8197f985)
Location: include/asm-generic/atomic-instrumented.h:70
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_next_uevent_seq
```
```
In net/core/dev.c (ffffffff819ff061)
Location: include/asm-generic/atomic-instrumented.h:70
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/ipv4/route.c (ffffffff81a9a53f)
Location: include/asm-generic/atomic-instrumented.h:70
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv4/udp.c (ffffffff81ae2498)
Location: include/asm-generic/atomic-instrumented.h:70
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81054c50)
Location: include/asm-generic/atomic-instrumented.h:70
Inline: True
```
```
In kernel/rcu/tree.c (ffffffff81130a4d)
Location: include/asm-generic/atomic-instrumented.h:70
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
```
```
In fs/inode.c (ffffffff81346950)
Location: include/asm-generic/atomic-instrumented.h:70
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
```
```
In fs/quota/netlink.c (ffffffff813cdecf)
Location: include/asm-generic/atomic-instrumented.h:70
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In fs/proc/inode.c (ffffffff813d2a5b)
Location: include/asm-generic/atomic-instrumented.h:70
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_entry_rundown
```
```
In fs/kernfs/inode.c (ffffffff813e5cc8)
Location: include/asm-generic/atomic-instrumented.h:70
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/jbd2/transaction.c (ffffffff8145e82e)
Location: include/asm-generic/atomic-instrumented.h:70
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:stop_this_handle
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In drivers/acpi/apei/ghes.c (ffffffff816efd45)
Location: include/asm-generic/atomic-instrumented.h:70
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
```
```
In drivers/base/power/wakeup.c (ffffffff817c70e3)
Location: include/asm-generic/atomic-instrumented.h:70
Inline: True
```
```
In drivers/md/dm.c (ffffffff81963b05)
Location: include/asm-generic/atomic-instrumented.h:70
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_next_uevent_seq
```
```
In net/core/dev.c (ffffffff819e5901)
Location: include/asm-generic/atomic-instrumented.h:70
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/ipv4/route.c (ffffffff81a8582c)
Location: include/asm-generic/atomic-instrumented.h:70
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv4/udp.c (ffffffff81acd3b8)
Location: include/asm-generic/atomic-instrumented.h:70
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8105d5a0)
Location: include/linux/atomic/atomic-instrumented.h:60
Inline: True
```
```
In fs/inode.c (ffffffff813943b0)
Location: include/linux/atomic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
```
```
In fs/quota/netlink.c (ffffffff8141f1ff)
Location: include/linux/atomic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In fs/proc/inode.c (ffffffff81423fab)
Location: include/linux/atomic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_entry_rundown
```
```
In fs/kernfs/inode.c (ffffffff81437848)
Location: include/linux/atomic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/jbd2/transaction.c (ffffffff814b3b9e)
Location: include/linux/atomic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:stop_this_handle
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In drivers/acpi/apei/ghes.c (ffffffff81769de5)
Location: include/linux/atomic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
```
```
In drivers/base/power/wakeup.c (ffffffff818514c3)
Location: include/linux/atomic/atomic-instrumented.h:60
Inline: True
```
```
In drivers/md/dm.c (ffffffff81a0baa5)
Location: include/linux/atomic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_next_uevent_seq
```
```
In net/core/dev.c (ffffffff81a95db1)
Location: include/linux/atomic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/ipv4/route.c (ffffffff81b3fffc)
Location: include/linux/atomic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv4/udp.c (ffffffff81b8bd78)
Location: include/linux/atomic/atomic-instrumented.h:60
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81069b40)
Location: include/linux/atomic/atomic-instrumented.h:61
Inline: True
```
```
In fs/inode.c (ffffffff81416123)
Location: include/linux/atomic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
```
```
In fs/quota/netlink.c (ffffffff81497040)
Location: include/linux/atomic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In fs/proc/inode.c (ffffffff8149cb2d)
Location: include/linux/atomic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_entry_rundown
```
```
In fs/kernfs/inode.c (ffffffff814b25c0)
Location: include/linux/atomic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/jbd2/transaction.c (ffffffff8153d3df)
Location: include/linux/atomic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:stop_this_handle
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff817ac9f4)
Location: include/linux/atomic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:process_hw_ts
```
```
In drivers/acpi/apei/ghes.c (ffffffff8189e915)
Location: include/linux/atomic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
```
```
In drivers/base/power/wakeup.c (ffffffff81997793)
Location: include/linux/atomic/atomic-instrumented.h:61
Inline: True
```
```
In drivers/md/dm.c (ffffffff81b73f45)
Location: include/linux/atomic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_next_uevent_seq
```
```
In net/core/dev.c (ffffffff81c0ea61)
Location: include/linux/atomic/atomic-instrumented.h:61
Inline: True
```
```
In net/ipv4/route.c (ffffffff81ccc945)
Location: include/linux/atomic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv4/udp.c (ffffffff81d18a5c)
Location: include/linux/atomic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81079870)
Location: include/linux/atomic/atomic-instrumented.h:61
Inline: True
```
```
In fs/inode.c (ffffffff814a11a3)
Location: include/linux/atomic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
```
```
In fs/quota/netlink.c (ffffffff8152b050)
Location: include/linux/atomic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In fs/proc/inode.c (ffffffff8153153d)
Location: include/linux/atomic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_entry_rundown
```
```
In fs/kernfs/inode.c (ffffffff81549140)
Location: include/linux/atomic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/jbd2/transaction.c (ffffffff815dbbff)
Location: include/linux/atomic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:stop_this_handle
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff818c4d18)
Location: include/linux/atomic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:process_hw_ts
```
```
In drivers/acpi/apei/ghes.c (ffffffff819e7c35)
Location: include/linux/atomic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
```
```
In drivers/base/power/wakeup.c (ffffffff81b08213)
Location: include/linux/atomic/atomic-instrumented.h:61
Inline: True
```
```
In drivers/md/dm.c (ffffffff81d10ec5)
Location: include/linux/atomic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_next_uevent_seq
```
```
In net/core/dev.c (ffffffff81dbeb71)
Location: include/linux/atomic/atomic-instrumented.h:61
Inline: True
```
```
In net/ipv4/route.c (ffffffff81e8cb01)
Location: include/linux/atomic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv4/udp.c (ffffffff81ee18ec)
Location: include/linux/atomic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8107bb20)
Location: include/linux/atomic/atomic-instrumented.h:120
Inline: True
```
```
In fs/inode.c (ffffffff814d64b3)
Location: include/linux/atomic/atomic-instrumented.h:120
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
```
```
In fs/quota/netlink.c (ffffffff815633e0)
Location: include/linux/atomic/atomic-instrumented.h:120
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In fs/proc/inode.c (ffffffff8156970d)
Location: include/linux/atomic/atomic-instrumented.h:120
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_entry_rundown
```
```
In fs/kernfs/inode.c (ffffffff81580d1d)
Location: include/linux/atomic/atomic-instrumented.h:120
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/jbd2/transaction.c (ffffffff816136bf)
Location: include/linux/atomic/atomic-instrumented.h:120
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:stop_this_handle
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff81907de8)
Location: include/linux/atomic/atomic-instrumented.h:120
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:process_hw_ts
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a30345)
Location: include/linux/atomic/atomic-instrumented.h:120
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
```
```
In drivers/base/power/wakeup.c (ffffffff81b56243)
Location: include/linux/atomic/atomic-instrumented.h:120
Inline: True
```
```
In drivers/md/dm.c (ffffffff81d7a355)
Location: include/linux/atomic/atomic-instrumented.h:120
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_next_uevent_seq
```
```
In net/core/dev.c (ffffffff81e2e881)
Location: include/linux/atomic/atomic-instrumented.h:120
Inline: True
```
```
In net/ipv4/route.c (ffffffff81eeb231)
Location: include/linux/atomic/atomic-instrumented.h:120
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv4/ip_output.c (ffffffff81efc0e9)
Location: include/linux/atomic/atomic-instrumented.h:120
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/raw.c (0)
Location: include/linux/atomic/atomic-instrumented.h:120
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81f4131c)
Location: include/linux/atomic/atomic-instrumented.h:120
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/atomic/atomic-instrumented.h:120
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/atomic/atomic-instrumented.h:120
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/atomic/atomic-instrumented.h:120
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
In fs/inode.c (ffffffff81508883)
Location: include/linux/atomic/atomic-instrumented.h:120
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
```
```
In fs/quota/netlink.c (ffffffff81599ad0)
Location: include/linux/atomic/atomic-instrumented.h:120
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In fs/proc/inode.c (ffffffff815a1d2d)
Location: include/linux/atomic/atomic-instrumented.h:120
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_entry_rundown
```
```
In fs/kernfs/inode.c (ffffffff815b9792)
Location: include/linux/atomic/atomic-instrumented.h:120
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
```
```
In fs/jbd2/transaction.c (ffffffff8164c4bf)
Location: include/linux/atomic/atomic-instrumented.h:120
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:stop_this_handle
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8194f5fa)
Location: include/linux/atomic/atomic-instrumented.h:120
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:process_hw_ts
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a7b855)
Location: include/linux/atomic/atomic-instrumented.h:120
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
```
```
In drivers/base/power/wakeup.c (ffffffff81bae803)
Location: include/linux/atomic/atomic-instrumented.h:120
Inline: True
```
```
In drivers/gpu/drm/drm_vblank.c (ffffffff81cb5df7)
Location: include/linux/atomic/atomic-instrumented.h:120
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_vblank.c:drm_vblank_get
```
```
In drivers/md/dm.c (ffffffff81e314f5)
Location: include/linux/atomic/atomic-instrumented.h:120
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_next_uevent_seq
```
```
In net/core/dev.c (ffffffff81eece11)
Location: include/linux/atomic/atomic-instrumented.h:120
Inline: True
```
```
In net/ipv4/route.c (ffffffff81faf251)
Location: include/linux/atomic/atomic-instrumented.h:120
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv4/ip_output.c (ffffffff81fc0049)
Location: include/linux/atomic/atomic-instrumented.h:120
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/raw.c (0)
Location: include/linux/atomic/atomic-instrumented.h:120
Inline: True
```
```
In net/ipv4/udp.c (ffffffff82006f6c)
Location: include/linux/atomic/atomic-instrumented.h:120
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/atomic/atomic-instrumented.h:120
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/atomic/atomic-instrumented.h:120
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/atomic/atomic-instrumented.h:120
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
In arch/arm64/kernel/insn.c (ffff800010da79a0)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - arch/arm64/kernel/insn.c:aarch64_insn_patch_text_cb
```
```
In arch/arm64/kernel/cpu_errata.c (ffff80001009890c)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In virt/kvm/arm/arm.c (ffff8000100c5770)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - virt/kvm/arm/arm.c:init_hyp_mode
```
```
In kernel/signal.c (ffff80001010b45c)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sched/topology.c (ffff80001015c258)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/autogroup.c (ffff80001015f0fc)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
```
In kernel/irq/spurious.c (ffff80001017d078)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (ffff800010183f5c)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/rcu/tree.c (ffff80001018f6b4)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_momentary_dyntick_idle
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
  - kernel/rcu/tree.c:rcu_dynticks_eqs_enter
```
```
In kernel/audit.c (ffff8000101ec490)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/trace/ftrace.c (ffff800010210ea8)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In kernel/trace/trace.c (ffff80001022a120)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In kernel/trace/tracing_map.c (ffff80001022e1e0)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In kernel/trace/trace_functions.c (ffff80001023013c)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffff8000102306f4)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (ffff8000102333c4)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (ffff80001023b334)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffff800010242930)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In kernel/bpf/syscall.c (ffff80001025fec8)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_add
  - kernel/bpf/syscall.c:bpf_map_inc
```
```
In kernel/bpf/hashtab.c (ffff8000102783ac)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/callchain.c (ffff8000102a3564)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/padata.c (ffff8000102aa0f0)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In mm/rmap.c (ffff80001030b680)
Location: include/asm-generic/atomic-instrumented.h:69
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
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/huge_memory.c (ffff800010355fa4)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memcontrol.c (ffff800010369654)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In fs/inode.c (ffff8000103acca8)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
```
```
In fs/notify/notification.c (ffff8000103e88a0)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/io_uring.c (ffff800010401320)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In fs/coredump.c (ffff800010428654)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/netlink.c (ffff800010437548)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In fs/proc/inode.c (ffff80001043bf40)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_entry_rundown
```
```
In fs/devpts/inode.c (ffff80001045eac8)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/jbd2/transaction.c (ffff8000104c9dcc)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/ecryptfs/main.c (ffff8000104f5160)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/selinux/avc.c (ffff800010546ce0)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/apparmor/policy.c (ffff800010596c38)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In block/blk-iocost.c (ffff8000106153d0)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In drivers/pci/pci.c (ffff8000106ea840)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_find_domain_nr
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/acpi/apei/ghes.c (ffff8000107aff3c)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:__ghes_print_estatus
```
```
In drivers/dma/of-dma.c (ffff8000107ff878)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In drivers/regulator/core.c (ffff800010847bac)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (ffff80001084cf1c)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In drivers/tty/serial/msm_serial.c (ffff8000108a1d8c)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_serial_probe
```
```
In drivers/iommu/arm-smmu.c (ffff8000108d1518)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu.c:arm_smmu_attach_dev
```
```
In drivers/base/power/wakeup.c (ffff800010903aa0)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In drivers/base/devcoredump.c (ffff80001091f39c)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/mfd/mfd-core.c (ffff800010940840)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/scsi/scsi_lib.c (ffff800010978b84)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/sd.c (ffff8000109879b0)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffff8000109913dc)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffff80001099ecc0)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-scsi.c (ffff8000109a3738)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In drivers/input/serio/serio.c (ffff800010a92940)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffff800010a979e8)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/power/reset/vexpress-poweroff.c (ffff800010aca3d0)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/power/reset/vexpress-poweroff.c:_vexpress_register_restart_handler
```
```
In drivers/md/dm.c (ffff800010b010fc)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_next_uevent_seq
```
```
In drivers/edac/edac_device.c (ffff800010b11608)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffff800010b137e8)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffff800010b1410c)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/firmware/arm_sdei.c (ffff800010b4bde0)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/firmware/arm_sdei.c:_local_event_register
  - drivers/firmware/arm_sdei.c:_local_event_unregister
  - drivers/firmware/arm_sdei.c:_ipi_event_disable
  - drivers/firmware/arm_sdei.c:_local_event_enable
```
```
In drivers/firmware/arm_scmi/clock.c (ffff800010b57d54)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/clock.c:scmi_clock_rate_set
```
```
In drivers/remoteproc/remoteproc_core.c (ffff800010b8104c)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/devfreq/devfreq.c (ffff800010b86438)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (ffff800010b87170)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In drivers/extcon/extcon.c (ffff800010b88cb4)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/skbuff.c (ffff800010bb552c)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
```
In net/core/dev.c (ffff800010bcb0dc)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/core/neighbour.c (ffff800010be8270)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/page_pool.c (ffff800010c0c8b4)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_clean_page
```
```
In net/core/netpoll.c (ffff800010c1170c)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffff800010c20e04)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/core/bpf_sk_storage.c (ffff800010c310d0)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/ip_fragment.c (ffff800010c5f97c)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/udp.c (ffff800010c9c4bc)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_state.c (ffff800010ce36a8)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/packet/af_packet.c (ffff800010d5aba8)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffff800010d6bbdc)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
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
In kernel/signal.c (c0363d30)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sched/topology.c (c03a8c60)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/autogroup.c (c03ab9a8)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
```
In kernel/locking/rwsem.c (c0e9cf80)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/irq/spurious.c (c03cdb34)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (c03d317c)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/rcu/tree.c (c03daf04)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
  - kernel/rcu/tree.c:rcu_dynticks_eqs_enter
```
```
In kernel/audit.c (c042bff0)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/trace/ftrace.c (c044f594)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:profile_graph_entry
```
```
In kernel/trace/ring_buffer.c (c045a234)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/trace/trace.c (c04677f0)
Location: include/linux/atomic-fallback.h:125
Inline: True
```
```
In kernel/trace/trace_functions.c (c046b6d4)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (c046c718)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (c046f160)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (c0475a20)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (c047dabc)
Location: include/linux/atomic-fallback.h:125
Inline: True
```
```
In kernel/bpf/core.c (c0491eb0)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/syscall.c (c0496724)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/bpf/hashtab.c (c04aa44c)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/core.c (c04cea78)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
```
```
In kernel/events/callchain.c (c04d2dec)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/padata.c (c04d81a8)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In mm/page-writeback.c (c04e65ec)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_update_write_bandwidth
```
```
In mm/vmscan.c (c04f1840)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/workingset.c (c0513914)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (c05261dc)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/vmalloc.c (c0529ddc)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/zswap.c (c0541480)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/page_counter.c (c0553324)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
```
In fs/super.c (c056f174)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In fs/pipe.c (c0578164)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/inode.c (c058c574)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
```
```
In fs/notify/notification.c (c05c0060)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/io_uring.c (c05d2928)
Location: include/linux/atomic-fallback.h:125
Inline: True
```
```
In fs/coredump.c (c05f1330)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/netlink.c (c05ff18c)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In fs/proc/inode.c (c0602208)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_entry_rundown
```
```
In fs/devpts/inode.c (c061f56c)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/jbd2/transaction.c (c068d8cc)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/ecryptfs/main.c (c06b2a34)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/selinux/avc.c (c06fc688)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/apparmor/policy.c (c0747ce8)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In block/blk-iocost.c (c07be50c)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In drivers/pci/pci.c (c0885734)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_find_domain_nr
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/dma/of-dma.c (c0920098)
Location: include/linux/atomic-fallback.h:125
Inline: True
```
```
In drivers/regulator/core.c (c0951484)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (c0958db0)
Location: include/linux/atomic-fallback.h:125
Inline: True
```
```
In drivers/tty/tty_ldsem.c (c0966b64)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_up_write
  - drivers/tty/tty_ldsem.c:ldsem_up_read
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In drivers/tty/serial/msm_serial.c (c099b380)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_serial_probe
```
```
In drivers/base/power/wakeup.c (c09edde4)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_report_event
```
```
In drivers/base/devcoredump.c (c0a045f4)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/mfd/mfd-core.c (c0a295f8)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/scsi/scsi_lib.c (c0a4c9a0)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/sd.c (c0a597cc)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (c0a60cb4)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (c0a6f370)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-scsi.c (c0a73fb0)
Location: include/linux/atomic-fallback.h:125
Inline: True
```
```
In drivers/input/serio/serio.c (c0b75d3c)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (c0b784c8)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/power/reset/vexpress-poweroff.c (c0bab1b4)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - drivers/power/reset/vexpress-poweroff.c:_vexpress_register_restart_handler
```
```
In drivers/md/dm.c (c0be09c4)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_next_uevent_seq
```
```
In drivers/edac/edac_device.c (c0bef100)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (c0bf11b8)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (c0bf1f70)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/cpufreq/omap-cpufreq.c (c0c007dc)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - drivers/cpufreq/omap-cpufreq.c:omap_cpu_init
```
```
In drivers/cpuidle/coupled.c (c0c05358)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - drivers/cpuidle/coupled.c:cpuidle_enter_state_coupled
  - drivers/cpuidle/coupled.c:cpuidle_coupled_parallel_barrier
```
```
In drivers/firmware/arm_scmi/clock.c (c0c38c94)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/clock.c:scmi_clock_rate_set
```
```
In drivers/remoteproc/remoteproc_core.c (c0c6465c)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/devfreq/devfreq.c (c0c687c0)
Location: include/linux/atomic-fallback.h:125
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (c0c6a094)
Location: include/linux/atomic-fallback.h:125
Inline: True
```
```
In drivers/extcon/extcon.c (c0c6dba0)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/sock.c (c0cc86b4)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/core/skbuff.c (c0cd25f4)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
```
In net/core/neighbour.c (c0d01224)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/page_pool.c (c0d24aa0)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_clean_page
```
```
In net/core/netpoll.c (c0d29480)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (c0d386dc)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/core/bpf_sk_storage.c (c0d485d4)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/ip_fragment.c (c0d6e9f8)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/tcp_output.c (c0d969ec)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/ipv4/udp.c (c0da7660)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_state.c (c0dead2c)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/unix/scm.c (c0dfbda4)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
```
```
In net/packet/af_packet.c (c0e5a2f8)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (c0e69ca0)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
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
In kernel/rcu/tree.c (c0000000001e7674)
Location: include/linux/atomic-fallback.h:125
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
In kernel/audit.c (c00000000025b29c)
Location: include/linux/atomic-fallback.h:125
Inline: True
```
```
In kernel/bpf/syscall.c (c000000000304c1c)
Location: include/linux/atomic-fallback.h:125
Inline: True
```
```
In mm/rmap.c (c0000000003d8f50)
Location: include/linux/atomic-fallback.h:125
Inline: True
```
```
In mm/huge_memory.c (c00000000043c4b4)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In fs/inode.c (c0000000004a65f0)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
```
```
In fs/quota/netlink.c (c000000000549950)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In fs/proc/inode.c (c00000000054fc68)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_entry_rundown
```
```
In fs/jbd2/transaction.c (c000000000602b90)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In block/blk-iocost.c (c0000000007b2254)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In drivers/base/power/wakeup.c (c0000000009a2520)
Location: include/linux/atomic-fallback.h:125
Inline: True
```
```
In drivers/md/dm.c (c000000000bf045c)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_next_uevent_seq
```
```
In net/core/dev.c (c000000000ca4008)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/ipv4/udp.c (c000000000dae970)
Location: include/linux/atomic-fallback.h:125
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In arch/riscv/kernel/perf_event.c (ffffffe0000b973a)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - arch/riscv/kernel/perf_event.c:riscv_event_init
```
```
In kernel/signal.c (ffffffe0000cd4c4)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sched/topology.c (ffffffe000101316)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/sched/autogroup.c (ffffffe0001033fa)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
```
In kernel/irq/spurious.c (ffffffe0001161c8)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (ffffffe00011b0de)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/rcu/tree.c (ffffffe000121980)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_irq_enter
  - kernel/rcu/tree.c:rcu_idle_exit
  - kernel/rcu/tree.c:rcu_irq_exit
  - kernel/rcu/tree.c:rcu_idle_enter
```
```
In kernel/audit.c (ffffffe000160a9c)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/trace/ftrace.c (ffffffe00017105c)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
```
```
In kernel/trace/trace.c (ffffffe000184aa6)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_panic_handler
```
```
In kernel/trace/trace_functions.c (ffffffe000187a66)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffe00018908a)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (ffffffe00018a6f8)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (ffffffe00018fce8)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffe000197708)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
```
```
In kernel/bpf/syscall.c (ffffffe00019de08)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
```
```
In kernel/bpf/hashtab.c (ffffffe0001afbb4)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/callchain.c (ffffffe0001d1c6e)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/padata.c (ffffffe0001d2fde)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In mm/rmap.c (ffffffe000214fde)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/zswap.c (ffffffe000229de0)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In fs/inode.c (ffffffe000270d9a)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
```
```
In fs/notify/notification.c (ffffffe00029d408)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/io_uring.c (ffffffe0002acd02)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
```
```
In fs/coredump.c (ffffffe0002c68bc)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/netlink.c (ffffffe0002d17b4)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In fs/proc/inode.c (ffffffe0002d445a)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_entry_rundown
```
```
In fs/devpts/inode.c (ffffffe0002ee710)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/jbd2/transaction.c (ffffffe000343282)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/ecryptfs/main.c (ffffffe0003641d2)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/selinux/avc.c (ffffffe0003a2326)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/apparmor/policy.c (ffffffe0003e3972)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In block/blk-iocost.c (ffffffe00044ada0)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In drivers/pci/pci.c (ffffffe0004c08b0)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_find_domain_nr
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/dma/of-dma.c (ffffffe000517a54)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
```
```
In drivers/regulator/core.c (ffffffe000527fd2)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (ffffffe00052c1d6)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
```
```
In drivers/base/devcoredump.c (ffffffe00059e376)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/mfd/mfd-core.c (ffffffe0005b3a34)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/scsi/scsi_lib.c (ffffffe0005e0428)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/sd.c (ffffffe0005eb9ae)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffe0005f2c2e)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffffffe0005fec02)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-scsi.c (ffffffe0005ff93a)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_port_init
```
```
In drivers/input/serio/serio.c (ffffffe0006a4c2c)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffe0006a8950)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/md/dm.c (ffffffe0006f11e0)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_next_uevent_seq
```
```
In drivers/edac/edac_device.c (ffffffe0006fdc2e)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffe0006ffc3c)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffe00070088a)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/devfreq/devfreq.c (ffffffe00072eda4)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (ffffffe00073007a)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffe000731d2c)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/skbuff.c (ffffffe000745580)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
```
In net/core/neighbour.c (ffffffe00076c63e)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/page_pool.c (ffffffe000789886)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_clean_page
```
```
In net/core/netpoll.c (ffffffe00078d93c)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffffffe000799bfc)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/core/bpf_sk_storage.c (ffffffe0007a7a4e)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/ip_fragment.c (ffffffe0007c778a)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/udp.c (ffffffe0007fa52a)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_state.c (ffffffe00083067c)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/packet/af_packet.c (ffffffe00088f678)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffe00089e1b6)
Location: arch/riscv/include/asm/atomic.h:140
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
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
In arch/x86/events/core.c (ffffffff8100640e)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff810177f7)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104e6be)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81050100)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108b78a)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
```
In kernel/signal.c (ffffffff810a9e14)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sched/topology.c (ffffffff810f1215)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/autogroup.c (ffffffff810f3abf)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
```
In kernel/locking/spinlock.c (ffffffff81a73942)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
  - kernel/locking/spinlock.c:_raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock
```
```
In kernel/irq/spurious.c (ffffffff811124a1)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (ffffffff81116bd2)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/rcu/tree.c (ffffffff8111f32f)
Location: include/asm-generic/atomic-instrumented.h:69
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
In kernel/audit.c (ffffffff8116fa2a)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/trace/ftrace.c (ffffffff81190bbe)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811a5840)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In kernel/trace/tracing_map.c (ffffffff811a904e)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In kernel/trace/trace_functions.c (ffffffff811aa2b0)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811ab0c8)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811adb0f)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (ffffffff811b2dbb)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811bafc0)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811d6ed5)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811ec2fd)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/callchain.c (ffffffff81210fba)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/padata.c (ffffffff81215c70)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In mm/zswap.c (ffffffff81286b75)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/memcontrol.c (ffffffff812bedd6)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/memremap.c (ffffffff812cccfc)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/inode.c (ffffffff812f42f0)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
```
```
In fs/notify/notification.c (ffffffff81325265)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/io_uring.c (ffffffff81338c09)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In fs/coredump.c (ffffffff8135a5f4)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/netlink.c (ffffffff813660bf)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In fs/proc/inode.c (ffffffff8136a4eb)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_entry_rundown
```
```
In fs/devpts/inode.c (ffffffff81385475)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/jbd2/transaction.c (ffffffff813e8a46)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/ecryptfs/main.c (ffffffff8140c255)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/selinux/avc.c (ffffffff81452a79)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/apparmor/policy.c (ffffffff814994ff)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In block/blk-iocost.c (ffffffff815081df)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In drivers/pci/pci.c (ffffffff81578e15)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/regulator/core.c (ffffffff816438db)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (ffffffff8164705f)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff816d9307)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In drivers/base/devcoredump.c (ffffffff816ef406)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/mfd/mfd-core.c (ffffffff81701e5a)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/scsi/scsi_lib.c (ffffffff81729138)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/sd.c (ffffffff81735940)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffff8173e727)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffffffff817596fe)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-scsi.c (ffffffff8175e791)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In drivers/input/serio/serio.c (ffffffff8180750b)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff8180d166)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/md/dm.c (ffffffff81850e15)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_next_uevent_seq
```
```
In drivers/edac/edac_device.c (ffffffff8185eb75)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffff81860ae5)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff818615a5)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff818961dc)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/devfreq/devfreq.c (ffffffff8189a1d8)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (ffffffff8189bb1f)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff8189d654)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/skbuff.c (ffffffff818bb0e4)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
```
In net/core/dev.c (ffffffff818cbb11)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/core/neighbour.c (ffffffff818e6cf7)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/page_pool.c (ffffffff81906dab)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_clean_page
```
```
In net/core/netpoll.c (ffffffff8190af56)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffffffff819197cf)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/core/bpf_sk_storage.c (ffffffff819298bd)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/ip_fragment.c (ffffffff8194ec44)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/udp.c (ffffffff81987e18)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_state.c (ffffffff819c3e8e)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/packet/af_packet.c (ffffffff81a2a0a1)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff81a3acde)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
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
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff81016c27)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103db8e)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8103f550)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8107a2ba)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
```
In kernel/signal.c (ffffffff810987c4)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sched/topology.c (ffffffff810e1285)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/autogroup.c (ffffffff810e3bef)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
```
In kernel/locking/spinlock.c (ffffffff81a2fca2)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
  - kernel/locking/spinlock.c:_raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock
```
```
In kernel/irq/spurious.c (ffffffff811031c1)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (ffffffff811078c2)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/rcu/tree.c (ffffffff81110d9f)
Location: include/asm-generic/atomic-instrumented.h:69
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
In kernel/audit.c (ffffffff81162bca)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/trace/ftrace.c (ffffffff81183743)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811986b0)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In kernel/trace/tracing_map.c (ffffffff8119bfce)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In kernel/trace/trace_functions.c (ffffffff8119d215)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8119e3d8)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811a0951)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (ffffffff811a5bbb)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811adda0)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811c9c95)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811df08d)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/core.c (ffffffff811fb3ab)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/callchain.c (ffffffff81203d4a)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/padata.c (ffffffff812089d0)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In mm/zswap.c (ffffffff812789d5)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/memcontrol.c (ffffffff812afec6)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/memremap.c (ffffffff812bdb6c)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/inode.c (ffffffff812e4f20)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
```
```
In fs/notify/notification.c (ffffffff81315e05)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/io_uring.c (ffffffff81329939)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In fs/coredump.c (ffffffff8134b29e)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/netlink.c (ffffffff81356d5f)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In fs/proc/inode.c (ffffffff8135af7b)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_entry_rundown
```
```
In fs/devpts/inode.c (ffffffff81375f05)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/jbd2/transaction.c (ffffffff813d94c6)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/ecryptfs/main.c (ffffffff813fccd5)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/selinux/avc.c (ffffffff814434c9)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/apparmor/policy.c (ffffffff81489f1f)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In block/blk-iocost.c (ffffffff814f868f)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In drivers/pci/pci.c (ffffffff81567555)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/regulator/core.c (ffffffff81623d5b)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (ffffffff816274bf)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff816b3947)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In drivers/mfd/mfd-core.c (ffffffff816d5c6a)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/scsi/scsi_lib.c (ffffffff81702568)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/scsi_transport_fc.c (ffffffff8170f935)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/scsi/scsi_transport_fc.c:fc_host_fpin_rcv
```
```
In drivers/scsi/sd.c (ffffffff817175e0)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffff817203c7)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffffffff8173959e)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-scsi.c (ffffffff8173e631)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In drivers/input/serio/serio.c (ffffffff817cec1b)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff817d48d6)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/md/dm.c (ffffffff81818425)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_next_uevent_seq
```
```
In drivers/edac/edac_device.c (ffffffff81826145)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffff818280b5)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81828b55)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/hv/channel.c (ffffffff81850fc5)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/hv/channel.c:vmbus_establish_gpadl
```
```
In drivers/devfreq/devfreq.c (ffffffff818576a8)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (ffffffff81858fef)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In net/core/skbuff.c (ffffffff81875024)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
```
In net/core/dev.c (ffffffff81885a51)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/core/neighbour.c (ffffffff818a0b37)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/page_pool.c (ffffffff818c0bbb)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_clean_page
```
```
In net/core/netpoll.c (ffffffff818c4cf1)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffffffff818d357f)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/core/bpf_sk_storage.c (ffffffff818e366d)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/ip_fragment.c (ffffffff81908734)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/udp.c (ffffffff819418d8)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_state.c (ffffffff81980c7e)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/packet/af_packet.c (ffffffff819e7291)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff819f78fe)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
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
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff810177b7)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104e50e)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8104ffb0)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108b73a)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
```
In kernel/signal.c (ffffffff810a9374)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sched/topology.c (ffffffff810ee345)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/autogroup.c (ffffffff810f0c0f)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
```
In kernel/locking/spinlock.c (ffffffff81adfd52)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
  - kernel/locking/spinlock.c:_raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock
```
```
In kernel/irq/spurious.c (ffffffff81110391)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (ffffffff81114ac2)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/rcu/tree.c (ffffffff8111d21f)
Location: include/asm-generic/atomic-instrumented.h:69
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
In kernel/audit.c (ffffffff8116d7fa)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/trace/ftrace.c (ffffffff8118e98e)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811a3610)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In kernel/trace/tracing_map.c (ffffffff811a6e1e)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In kernel/trace/trace_functions.c (ffffffff811a8080)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811a8e98)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811ab8df)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (ffffffff811b0b8b)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811b8d90)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811d4ca5)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811ea0cd)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/callchain.c (ffffffff8120ed5a)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/padata.c (ffffffff81213a10)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In mm/zswap.c (ffffffff81284985)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/memcontrol.c (ffffffff812bcbe6)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/memremap.c (ffffffff812cab0c)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/inode.c (ffffffff812f2100)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
```
```
In fs/notify/notification.c (ffffffff81322d35)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/io_uring.c (ffffffff813366d9)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In fs/coredump.c (ffffffff813580c4)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/netlink.c (ffffffff81363b8f)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In fs/proc/inode.c (ffffffff81367fbb)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_entry_rundown
```
```
In fs/devpts/inode.c (ffffffff81382f45)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/jbd2/transaction.c (ffffffff813e5dc6)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/ecryptfs/main.c (ffffffff814095d5)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/selinux/avc.c (ffffffff8144eb19)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/apparmor/policy.c (ffffffff8149559f)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In block/blk-iocost.c (ffffffff8150426f)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In drivers/pci/pci.c (ffffffff81578645)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/acpi/apei/ghes.c (ffffffff81637835)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:__ghes_print_estatus
```
```
In drivers/regulator/core.c (ffffffff81671cbb)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (ffffffff8167541f)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff81706c47)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In drivers/base/devcoredump.c (ffffffff8171cae6)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/mfd/mfd-core.c (ffffffff8173727a)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/scsi/scsi_lib.c (ffffffff81767f08)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/sd.c (ffffffff817760d0)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffff8177eeb7)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffffffff8178946e)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-scsi.c (ffffffff8178e521)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In drivers/input/serio/serio.c (ffffffff818465bb)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff8184c2e6)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/md/dm.c (ffffffff818a0445)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_next_uevent_seq
```
```
In drivers/edac/edac_device.c (ffffffff818ae1a5)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffff818b0115)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff818b0bd5)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/devfreq/devfreq.c (ffffffff818e98c8)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (ffffffff818eb20f)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff818ecd44)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/skbuff.c (ffffffff8190c0e4)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
```
In net/core/dev.c (ffffffff8191cb11)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/core/neighbour.c (ffffffff81937d27)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/page_pool.c (ffffffff81957ddb)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_clean_page
```
```
In net/core/netpoll.c (ffffffff8195bf86)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffffffff8196a95f)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/core/bpf_sk_storage.c (ffffffff8197aa4d)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/netfilter/nfnetlink_log.c (ffffffff8199c3a1)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_log.c:__build_packet_message
```
```
In net/ipv4/ip_fragment.c (ffffffff819b9414)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/udp.c (ffffffff819f25e8)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_state.c (ffffffff81a2e90e)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/packet/af_packet.c (ffffffff81a95c51)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff81aa6b8e)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
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
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff810179f7)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104f94e)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff810513f0)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108da9a)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
```
In kernel/signal.c (ffffffff810b1595)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sched/topology.c (ffffffff810f9385)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/autogroup.c (ffffffff810fbc9f)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
```
In kernel/locking/spinlock.c (ffffffff81aec555)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_trylock
  - kernel/locking/spinlock.c:_raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock
```
```
In kernel/irq/spurious.c (ffffffff8111b911)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
```
```
In kernel/irq/irqdomain.c (ffffffff811200f2)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/rcu/tree.c (ffffffff811280ef)
Location: include/asm-generic/atomic-instrumented.h:69
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
In kernel/audit.c (ffffffff8117afef)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/trace/ftrace.c (ffffffff8119c51e)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811b13a0)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In kernel/trace/tracing_map.c (ffffffff811b4bbe)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In kernel/trace/trace_functions.c (ffffffff811b5e30)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811b6cd8)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811b97af)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/trace_events.c (ffffffff811bec1b)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811c6e30)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811e2fd5)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811f84ad)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/events/callchain.c (ffffffff8121dc6a)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In kernel/padata.c (ffffffff81222b90)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In mm/zswap.c (ffffffff81294625)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/memcontrol.c (ffffffff812cd3d6)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/memremap.c (ffffffff812db82c)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/inode.c (ffffffff813036db)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
```
```
In fs/notify/notification.c (ffffffff81334a75)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_get_cookie
```
```
In fs/io_uring.c (ffffffff813497a9)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In fs/coredump.c (ffffffff8136b7f6)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/netlink.c (ffffffff8137723f)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In fs/proc/inode.c (ffffffff8137b60b)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_entry_rundown
```
```
In fs/devpts/inode.c (ffffffff81396a65)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_new_index
```
```
In fs/jbd2/transaction.c (ffffffff813fb26a)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/ecryptfs/main.c (ffffffff8141f295)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In security/selinux/avc.c (ffffffff81465ef9)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/apparmor/policy.c (ffffffff814ad5ff)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In block/blk-iocost.c (ffffffff8151d81f)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In drivers/pci/pci.c (ffffffff81592b05)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
```
In drivers/acpi/apei/ghes.c (ffffffff81651b75)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/acpi/apei/ghes.c:__ghes_print_estatus
```
```
In drivers/regulator/core.c (ffffffff8168c31b)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/core.c (ffffffff8168fa7f)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff81721657)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In drivers/base/devcoredump.c (ffffffff81737e46)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/mfd/mfd-core.c (ffffffff817526ba)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_enable
```
```
In drivers/scsi/scsi_lib.c (ffffffff81783647)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/sd.c (ffffffff8178feb0)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_open
```
```
In drivers/scsi/sg.c (ffffffff81798cb7)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_device
```
```
In drivers/ata/libata-core.c (ffffffff817a32be)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_register
```
```
In drivers/ata/libata-scsi.c (ffffffff817a8371)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In drivers/input/serio/serio.c (ffffffff81861bcb)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:__serio_register_port
```
```
In drivers/input/input.c (ffffffff81867546)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/md/dm.c (ffffffff818bc695)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_next_uevent_seq
```
```
In drivers/edac/edac_device.c (ffffffff818ca435)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_index
```
```
In drivers/edac/edac_pci.c (ffffffff818cc3a5)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_index
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff818cce65)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff8190693c)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
```
```
In drivers/devfreq/devfreq.c (ffffffff8190a948)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (ffffffff8190c28f)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff8190ddc4)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/skbuff.c (ffffffff8192d214)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
```
In net/core/dev.c (ffffffff8193dfe1)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/core/neighbour.c (ffffffff81959505)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/page_pool.c (ffffffff81979ebb)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_clean_page
```
```
In net/core/netpoll.c (ffffffff8197e366)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/sock_map.c (ffffffff8198cdcf)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/core/bpf_sk_storage.c (ffffffff8199cf7d)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/ip_fragment.c (ffffffff819c2d04)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/udp.c (ffffffff819fc438)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3a10e)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_get_acqseq
```
```
In net/packet/af_packet.c (ffffffff81aa2891)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/rfkill/core.c (ffffffff81ab2f2e)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_ioctl
```
</details>
</li>
</ul>

## Differences

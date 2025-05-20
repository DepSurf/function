# Function: <code>arch_atomic_sub_return</code>

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
In arch/x86/events/intel/uncore.c (ffffffff81014d6d)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81047fe4)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff8104f4a5)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_intel_adjust_timer
```
```
In kernel/fork.c (ffffffff8108dddc)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - kernel/fork.c:walk_process_tree
```
```
In kernel/exit.c (ffffffff81092bb6)
Location: arch/x86/include/asm/atomic.h:171
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
Location: arch/x86/include/asm/atomic.h:171
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
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff8109fbf8)
Location: arch/x86/include/asm/atomic.h:171
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
Location: arch/x86/include/asm/atomic.h:171
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
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
```
```
In kernel/locking/spinlock.c (ffffffff819f1bc5)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
```
```
In kernel/power/process.c (ffffffff810e8d83)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/livepatch/transition.c (ffffffff8110c57b)
Location: arch/x86/include/asm/atomic.h:171
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
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - kernel/module.c:try_release_module_ref
```
```
In kernel/cgroup/cgroup.c (ffffffff811401c5)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_mount
```
```
In kernel/pid_namespace.c (ffffffff8114e05e)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tracepoint.c (ffffffff8116ffad)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/ftrace.c (ffffffff8117770f)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:register_ftrace_graph
```
```
In kernel/trace/trace_events.c (ffffffff8119318b)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff8119b86f)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
```
```
In kernel/trace/trace_uprobe.c (ffffffff811ae59d)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In kernel/bpf/syscall.c (ffffffff811b369c)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
```
```
In kernel/memremap.c (ffffffff811e93a5)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
```
```
In mm/oom_kill.c (ffffffff811f3c50)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/mempolicy.c (ffffffff8125cc08)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
```
```
In mm/memory_hotplug.c (ffffffff8126bc98)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/memory-failure.c (ffffffff81288db6)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
```
```
In mm/zsmalloc.c (ffffffff8128e74d)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/exec.c (ffffffff812a1849)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/exec.c:__x64_sys_uselib
```
```
In fs/fcntl.c (ffffffff812af39a)
Location: arch/x86/include/asm/atomic.h:171
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
In fs/filesystems.c (ffffffff812bcefe)
Location: arch/x86/include/asm/atomic.h:171
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
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/inode.c (ffffffff8131a5d5)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - fs/proc/inode.c:unuse_pde
```
```
In fs/proc/generic.c (ffffffff813202fa)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/proc/array.c (ffffffff81321225)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/proc/kcore.c (ffffffff81328f5f)
Location: arch/x86/include/asm/atomic.h:171
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
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_put_active
```
```
In fs/ext4/extents_status.c (ffffffff81343205)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_find_delayed_extent_range
```
```
In fs/ext4/inode.c (ffffffff8135a624)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_iget
```
```
In fs/ext4/super.c (ffffffff8137de38)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/jbd2/transaction.c (ffffffff813951e2)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:wait_transaction_locked
```
```
In fs/jbd2/journal.c (ffffffff813996ee)
Location: arch/x86/include/asm/atomic.h:171
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
In security/keys/keyring.c (ffffffff813e6a77)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/hooks.c (ffffffff813fad7e)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/selinux/ss/services.c (ffffffff81414973)
Location: arch/x86/include/asm/atomic.h:171
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
In security/integrity/iint.c (ffffffff8144feda)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In block/blk-mq.c (ffffffff8148e325)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
```
```
In block/blk-wbt.c (ffffffff814b8df9)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
```
```
In lib/sbitmap.c (ffffffff814f86a6)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pci/pci.c (ffffffff8151ce42)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
```
```
In drivers/reset/core.c (ffffffff8160e847)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff81611691)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/tty/tty_buffer.c (ffffffff81618ed9)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8161b55b)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/sysrq.c (ffffffff8161d092)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/tty/serial/serial_core.c (ffffffff8162ffb1)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/block/loop.c (ffffffff816ab542)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
```
```
In drivers/mfd/mfd-core.c (ffffffff816c501a)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff816f2514)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
```
```
In drivers/scsi/sd.c (ffffffff816fdcf0)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
```
```
In drivers/scsi/sg.c (ffffffff81706c51)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
```
```
In drivers/power/supply/power_supply_core.c (ffffffff817e1005)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/md/dm.c (ffffffff8180760a)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff8181b095)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
```
```
In drivers/leds/led-triggers.c (ffffffff81842e2a)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
```
In arch/x86/pci/common.c (ffffffff8186c305)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
```
```
In net/core/skbuff.c (ffffffff8187e483)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dst.c (ffffffff8189fafa)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
```
```
In net/core/neighbour.c (ffffffff8189fed9)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_for_each
```
```
In net/core/net-sysfs.c (ffffffff818bb758)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:address_show
```
```
In net/sched/sch_api.c (ffffffff818cee9a)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffffffff818d2b4f)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffffffff818d548f)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (ffffffff818d86ae)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff818da732)
Location: arch/x86/include/asm/atomic.h:171
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
In net/ipv4/raw.c (ffffffff81918e16)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/arp.c (ffffffff819219b7)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
```
```
In net/ipv4/ipmr.c (ffffffff8193ed55)
Location: arch/x86/include/asm/atomic.h:171
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
Location: arch/x86/include/asm/atomic.h:171
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194dd48)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/ipv6/ip6_output.c (ffffffff81962953)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff81972ff2)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffffffff8197c24e)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
```
In net/ipv6/raw.c (ffffffff81988a39)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/mcast.c (ffffffff8198e942)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
  - net/ipv6/mcast.c:inet6_mc_check
```
```
In net/ipv6/ip6mr.c (ffffffff819a0ada)
Location: arch/x86/include/asm/atomic.h:171
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
In net/rfkill/core.c (ffffffff819be66e)
Location: arch/x86/include/asm/atomic.h:171
Inline: True
Inline callers:
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
In arch/x86/events/intel/uncore.c (ffffffff8101547d)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8104cb65)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81057b54)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In kernel/fork.c (ffffffff8109606c)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/fork.c:walk_process_tree
```
```
In kernel/exit.c (ffffffff8109aea6)
Location: arch/x86/include/asm/atomic.h:177
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
Location: arch/x86/include/asm/atomic.h:177
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
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff810a92dd)
Location: arch/x86/include/asm/atomic.h:177
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
Location: arch/x86/include/asm/atomic.h:177
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
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
```
```
In kernel/locking/spinlock.c (ffffffff81a2d185)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
```
```
In kernel/power/process.c (ffffffff810f4382)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/livepatch/transition.c (ffffffff81117d6b)
Location: arch/x86/include/asm/atomic.h:177
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
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/module.c:try_release_module_ref
```
```
In kernel/cgroup/cgroup.c (ffffffff8114bc35)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_mount
```
```
In kernel/pid_namespace.c (ffffffff8115adf9)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tracepoint.c (ffffffff8117db5d)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/fgraph.c (ffffffff811a0a80)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:register_ftrace_graph
```
```
In kernel/trace/trace_events.c (ffffffff811a12fb)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811a9a6f)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In kernel/trace/trace_uprobe.c (ffffffff811bc93d)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In kernel/bpf/syscall.c (ffffffff811c1d7c)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In kernel/memremap.c (ffffffff811f9f85)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In mm/oom_kill.c (ffffffff81205da6)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/mempolicy.c (ffffffff812714e8)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
```
```
In mm/memory_hotplug.c (ffffffff81280598)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/memory-failure.c (ffffffff8129dd06)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
```
```
In mm/zsmalloc.c (ffffffff812a32bd)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/exec.c (ffffffff812b69cd)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/exec.c:__x64_sys_uselib
```
```
In fs/fcntl.c (ffffffff812c44ca)
Location: arch/x86/include/asm/atomic.h:177
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
In fs/filesystems.c (ffffffff812d21be)
Location: arch/x86/include/asm/atomic.h:177
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
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/inode.c (ffffffff81331655)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/proc/inode.c:unuse_pde
```
```
In fs/proc/generic.c (ffffffff813373da)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff81338335)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/kernfs/dir.c (ffffffff81343fe9)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_put_active
```
```
In fs/ext4/extents_status.c (ffffffff8135b682)
Location: arch/x86/include/asm/atomic.h:177
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
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff813966e8)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/jbd2/transaction.c (ffffffff813adf52)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:wait_transaction_locked
```
```
In fs/jbd2/journal.c (ffffffff813b245e)
Location: arch/x86/include/asm/atomic.h:177
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
In security/keys/keyring.c (ffffffff81401277)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/hooks.c (ffffffff81417365)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/selinux/ss/services.c (ffffffff81430f53)
Location: arch/x86/include/asm/atomic.h:177
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
In security/integrity/iint.c (ffffffff8146ceba)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In block/blk-core.c (ffffffff8149d255)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In block/blk-mq.c (ffffffff814a7c95)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In block/blk-wbt.c (ffffffff814ccc55)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In lib/sbitmap.c (ffffffff8150c92d)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pci/pci.c (ffffffff81532542)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
```
```
In drivers/reset/core.c (ffffffff8162b787)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff8162e401)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/tty/tty_buffer.c (ffffffff816360e9)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/tty/tty_jobctrl.c (ffffffff816388a6)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/sysrq.c (ffffffff8163a2f2)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/tty/serial/serial_core.c (ffffffff8164e161)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/block/loop.c (ffffffff816cbcb0)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
```
```
In drivers/mfd/mfd-core.c (ffffffff816e640a)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81715069)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/sd.c (ffffffff817208c0)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
```
```
In drivers/scsi/sg.c (ffffffff81729791)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
```
```
In drivers/power/supply/power_supply_core.c (ffffffff8180c685)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81846885)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In drivers/leds/led-triggers.c (ffffffff8186eeba)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
```
In drivers/devfreq/devfreq.c (ffffffff8187ca0a)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In arch/x86/pci/common.c (ffffffff8188c3e5)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
```
```
In net/core/skbuff.c (ffffffff8189f060)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dst.c (ffffffff818c228a)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
```
```
In net/core/neighbour.c (ffffffff818c2799)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_for_each
```
```
In net/core/net-sysfs.c (ffffffff818e24e8)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:address_show
```
```
In net/sched/sch_api.c (ffffffff818fa19a)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffffffff818fdfd2)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffffffff819020cf)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (ffffffff81904e9e)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff8190614f)
Location: arch/x86/include/asm/atomic.h:177
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
In net/ipv4/raw.c (ffffffff81947706)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/arp.c (ffffffff819507d7)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
```
```
In net/ipv4/ipmr.c (ffffffff8196ec05)
Location: arch/x86/include/asm/atomic.h:177
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
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197f909)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/ipv6/ip6_output.c (ffffffff8199793c)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff819a8c12)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffffffff819b1f2e)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
```
In net/ipv6/raw.c (ffffffff819bf3a1)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/mcast.c (ffffffff819c51f9)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/ipv6/mcast.c:inet6_mc_check
```
```
In net/ipv6/ip6mr.c (ffffffff819d76da)
Location: arch/x86/include/asm/atomic.h:177
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
In net/rfkill/core.c (ffffffff819f580e)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
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
In arch/x86/events/intel/uncore.c (ffffffff81016838)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8104fa8a)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105adbb)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In kernel/fork.c (ffffffff8109a59d)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/fork.c:walk_process_tree
```
```
In kernel/exit.c (ffffffff8109f507)
Location: arch/x86/include/asm/atomic.h:177
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
Location: arch/x86/include/asm/atomic.h:177
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
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff810ad66f)
Location: arch/x86/include/asm/atomic.h:177
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
Location: arch/x86/include/asm/atomic.h:177
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
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
```
```
In kernel/locking/spinlock.c (ffffffff81a9d265)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
```
```
In kernel/power/process.c (ffffffff810fc8ea)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/livepatch/transition.c (ffffffff811220ac)
Location: arch/x86/include/asm/atomic.h:177
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
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/module.c:try_release_module_ref
```
```
In kernel/cgroup/cgroup.c (ffffffff8115750b)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/pid_namespace.c (ffffffff811674b7)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tracepoint.c (ffffffff8118aa1b)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/fgraph.c (ffffffff811ae7e2)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
```
In kernel/trace/trace_events.c (ffffffff811af212)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811b79ef)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cc0cd)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In kernel/bpf/syscall.c (ffffffff811d265c)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In mm/oom_kill.c (ffffffff8121cd43)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/mempolicy.c (ffffffff8128caf8)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
```
```
In mm/memory_hotplug.c (ffffffff8129c8d3)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/memory-failure.c (ffffffff812b8fdf)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
```
```
In mm/zsmalloc.c (ffffffff812be626)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In mm/memremap.c (ffffffff812c23d5)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In fs/exec.c (ffffffff812d4b1f)
Location: arch/x86/include/asm/atomic.h:177
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
Location: arch/x86/include/asm/atomic.h:177
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
In fs/filesystems.c (ffffffff812ef220)
Location: arch/x86/include/asm/atomic.h:177
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
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/io_uring.c (ffffffff8132f888)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/proc/inode.c (ffffffff813595a5)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/proc/inode.c:unuse_pde
```
```
In fs/proc/generic.c (ffffffff8135f4fa)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff813609e6)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/kernfs/dir.c (ffffffff8136c239)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_put_active
```
```
In fs/ext4/extents_status.c (ffffffff813846a9)
Location: arch/x86/include/asm/atomic.h:177
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
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff813c06ec)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/jbd2/transaction.c (ffffffff813d8323)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:wait_transaction_locked
```
```
In fs/jbd2/journal.c (ffffffff813dcacf)
Location: arch/x86/include/asm/atomic.h:177
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
In security/keys/keyring.c (ffffffff8142da57)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/hooks.c (ffffffff81444f45)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/selinux/ss/services.c (ffffffff8145e974)
Location: arch/x86/include/asm/atomic.h:177
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
In security/integrity/iint.c (ffffffff8149a5aa)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In block/blk-core.c (ffffffff814cb385)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In block/blk-wbt.c (ffffffff814fb6c5)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In lib/sbitmap.c (ffffffff8153b037)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pci/pci.c (ffffffff81561c12)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
```
```
In drivers/reset/core.c (ffffffff8165f583)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff81661fd4)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/tty/tty_buffer.c (ffffffff8166a323)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8166cb07)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/sysrq.c (ffffffff8166e62e)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/tty/serial/serial_core.c (ffffffff81682cc3)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/block/loop.c (ffffffff817072b2)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
```
```
In drivers/mfd/mfd-core.c (ffffffff8171fb9c)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff8175084a)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/sd.c (ffffffff8175bf72)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
```
```
In drivers/scsi/sg.c (ffffffff81764adc)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
```
```
In drivers/power/supply/power_supply_core.c (ffffffff8184e315)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81889625)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In drivers/leds/led-triggers.c (ffffffff818b3170)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
```
In drivers/devfreq/devfreq.c (ffffffff818c6e9a)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In arch/x86/pci/common.c (ffffffff818d6d25)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
```
```
In net/core/skbuff.c (ffffffff818e9883)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dst.c (ffffffff8190e9ea)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
```
```
In net/core/neighbour.c (ffffffff8190ee9e)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_for_each
```
```
In net/core/net-sysfs.c (ffffffff81931da8)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:address_show
```
```
In net/sched/sch_api.c (ffffffff81959a2f)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffffffff8195d967)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffffffff81963264)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (ffffffff8196610e)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81967434)
Location: arch/x86/include/asm/atomic.h:177
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
In net/ipv4/raw.c (ffffffff819abd96)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/arp.c (ffffffff819b5098)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
```
```
In net/ipv4/ipmr.c (ffffffff819d8405)
Location: arch/x86/include/asm/atomic.h:177
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
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e9605)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/ipv6/ip6_output.c (ffffffff81a039ec)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff81a14f3b)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffffffff81a20417)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
```
In net/ipv6/raw.c (ffffffff81a2dfdc)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/mcast.c (ffffffff81a34062)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/ipv6/mcast.c:inet6_mc_check
```
```
In net/ipv6/ip6mr.c (ffffffff81a4684f)
Location: arch/x86/include/asm/atomic.h:177
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
In net/rfkill/core.c (ffffffff81a64c79)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
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
In arch/x86/events/intel/uncore.c (ffffffff810171e8)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8105041a)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b6ab)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In kernel/fork.c (ffffffff810a0b5d)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/fork.c:walk_process_tree
```
```
In kernel/exit.c (ffffffff810a5a97)
Location: arch/x86/include/asm/atomic.h:177
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
Location: arch/x86/include/asm/atomic.h:177
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
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff810b3c8f)
Location: arch/x86/include/asm/atomic.h:177
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
In kernel/sys.c (ffffffff810bc2c5)
Location: arch/x86/include/asm/atomic.h:177
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
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
```
```
In kernel/sched/rt.c (ffffffff810f05cb)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:tg_set_rt_bandwidth
```
```
In kernel/locking/spinlock.c (ffffffff81ad4a45)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
```
```
In kernel/power/process.c (ffffffff81108cdf)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/livepatch/transition.c (ffffffff8112e6cc)
Location: arch/x86/include/asm/atomic.h:177
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
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/module.c:try_release_module_ref
```
```
In kernel/cgroup/cgroup.c (ffffffff8116310b)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_enable_task_cg_lists
```
```
In kernel/pid_namespace.c (ffffffff81173377)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tracepoint.c (ffffffff8119692b)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/fgraph.c (ffffffff811b9f62)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
```
In kernel/trace/trace_events.c (ffffffff811ba6e2)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811c305f)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d8544)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In kernel/bpf/syscall.c (ffffffff811de96c)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In mm/oom_kill.c (ffffffff8122a723)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/mempolicy.c (ffffffff8129c728)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
```
```
In mm/memory_hotplug.c (ffffffff812ac573)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/memory-failure.c (ffffffff812caecf)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
```
```
In mm/zsmalloc.c (ffffffff812d0516)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In mm/memremap.c (ffffffff812d4305)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In fs/exec.c (ffffffff812e669f)
Location: arch/x86/include/asm/atomic.h:177
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
Location: arch/x86/include/asm/atomic.h:177
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
In fs/filesystems.c (ffffffff81300ce0)
Location: arch/x86/include/asm/atomic.h:177
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
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/io_uring.c (ffffffff81343056)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/proc/inode.c (ffffffff813717f5)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/proc/inode.c:unuse_pde
```
```
In fs/proc/generic.c (ffffffff8137775a)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff81378c46)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/kernfs/dir.c (ffffffff813843da)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In fs/ext4/extents_status.c (ffffffff8139d329)
Location: arch/x86/include/asm/atomic.h:177
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
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff813d99ac)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/jbd2/transaction.c (ffffffff813f23a3)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:wait_transaction_locked
```
```
In fs/jbd2/journal.c (ffffffff813f6b1f)
Location: arch/x86/include/asm/atomic.h:177
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
In security/keys/keyring.c (ffffffff814477a7)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/hooks.c (ffffffff8145eab5)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/selinux/ss/services.c (ffffffff81478724)
Location: arch/x86/include/asm/atomic.h:177
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
In security/integrity/iint.c (ffffffff814b47aa)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In block/blk-core.c (ffffffff814e4575)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In block/blk-wbt.c (ffffffff81519615)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In lib/sbitmap.c (ffffffff8155be57)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pci/pci.c (ffffffff81582db2)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
```
```
In drivers/reset/core.c (ffffffff81681cc3)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff81684644)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/tty/tty_buffer.c (ffffffff8168ca09)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8168f177)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/sysrq.c (ffffffff81690c6e)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/tty/serial/serial_core.c (ffffffff816a5353)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/block/loop.c (ffffffff8172b502)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
```
```
In drivers/mfd/mfd-core.c (ffffffff81743e6a)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81774a6d)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/sd.c (ffffffff8177fe12)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
```
```
In drivers/scsi/sg.c (ffffffff81788acc)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
```
```
In drivers/power/supply/power_supply_core.c (ffffffff8187fd55)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff818bb5d5)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In drivers/leds/led-triggers.c (ffffffff818e5a90)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
```
In drivers/devfreq/devfreq.c (ffffffff818f8f0a)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In arch/x86/pci/common.c (ffffffff819090a5)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
```
```
In net/core/skbuff.c (ffffffff8191b9f3)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dst.c (ffffffff8194105a)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
```
```
In net/core/neighbour.c (ffffffff8194150e)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_for_each
```
```
In net/core/net-sysfs.c (ffffffff819648e8)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:address_show
```
```
In net/sched/sch_api.c (ffffffff8198fecf)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffffffff81994057)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffffffff81999de4)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (ffffffff8199cb9e)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff8199dec4)
Location: arch/x86/include/asm/atomic.h:177
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
In net/ipv4/raw.c (ffffffff819e2a46)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/arp.c (ffffffff819ebdc8)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
```
```
In net/ipv4/ipmr.c (ffffffff81a0efd5)
Location: arch/x86/include/asm/atomic.h:177
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
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a20635)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/ipv6/ip6_output.c (ffffffff81a3a5bc)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff81a4bb2b)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffffffff81a5705b)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
```
In net/ipv6/raw.c (ffffffff81a64b4c)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/mcast.c (ffffffff81a6abb2)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/ipv6/mcast.c:inet6_mc_check
```
```
In net/ipv6/ip6mr.c (ffffffff81a7d43f)
Location: arch/x86/include/asm/atomic.h:177
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
In net/rfkill/core.c (ffffffff81a9b8e9)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
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
In arch/x86/events/intel/uncore.c (ffffffff81018698)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81054939)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8106051c)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks
```
```
In kernel/fork.c (ffffffff810a79cd)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - kernel/fork.c:walk_process_tree
```
```
In kernel/exit.c (ffffffff810ad5b4)
Location: arch/x86/include/asm/atomic.h:178
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
Location: arch/x86/include/asm/atomic.h:178
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
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff810bc735)
Location: arch/x86/include/asm/atomic.h:178
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
In kernel/sys.c (ffffffff810c3c65)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
```
```
In kernel/sched/core.c (ffffffff810e6674)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
```
```
In kernel/locking/spinlock.c (ffffffff81bccc45)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
```
```
In kernel/power/process.c (ffffffff8111346e)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/livepatch/transition.c (ffffffff8113cd29)
Location: arch/x86/include/asm/atomic.h:178
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
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - kernel/module.c:try_release_module_ref
```
```
In kernel/pid_namespace.c (ffffffff811854c3)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tracepoint.c (ffffffff811abc5b)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/fgraph.c (ffffffff811d29a4)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:alloc_retstack_tasklist
```
```
In kernel/trace/trace_events.c (ffffffff811d5988)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811dccad)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f53e4)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In mm/oom_kill.c (ffffffff81257533)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/swap.c (ffffffff8125e53e)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - mm/swap.c:put_devmap_managed_page
```
```
In mm/gup.c (ffffffff812879f4)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - mm/gup.c:__unpin_devmap_managed_user_page
```
```
In mm/mempolicy.c (ffffffff812d0378)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
```
```
In mm/memory_hotplug.c (ffffffff812e1613)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/memory-failure.c (ffffffff81300d95)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs_file
  - mm/memory-failure.c:collect_procs_anon
```
```
In mm/zsmalloc.c (ffffffff81306c6e)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/exec.c (ffffffff8131ca2a)
Location: arch/x86/include/asm/atomic.h:178
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
Location: arch/x86/include/asm/atomic.h:178
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
In fs/filesystems.c (ffffffff81339fb8)
Location: arch/x86/include/asm/atomic.h:178
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
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/inode.c (ffffffff813b9625)
Location: arch/x86/include/asm/atomic.h:178
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
```
```
In fs/proc/generic.c (ffffffff813c05ca)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff813c1cba)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/kernfs/dir.c (ffffffff813ceeba)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
```
```
In fs/ext4/extents_status.c (ffffffff813e89cc)
Location: arch/x86/include/asm/atomic.h:178
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
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff81425d88)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/jbd2/transaction.c (ffffffff8143f723)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
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
  - fs/jbd2/transaction.c:wait_transaction_locked
```
```
In fs/jbd2/journal.c (ffffffff81445fdf)
Location: arch/x86/include/asm/atomic.h:178
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
In security/keys/keyring.c (ffffffff81498f1e)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/hooks.c (ffffffff814b5bfd)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/selinux/ss/services.c (ffffffff814cdbf3)
Location: arch/x86/include/asm/atomic.h:178
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
In security/integrity/iint.c (ffffffff81513d3a)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In block/blk-core.c (ffffffff81542e75)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
```
```
In block/blk-wbt.c (ffffffff81579bd5)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In lib/sbitmap.c (ffffffff815e594c)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pci/pci.c (ffffffff816298d5)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
```
```
In drivers/reset/core.c (ffffffff817330f3)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff81736e68)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/tty/tty_buffer.c (ffffffff8173ea39)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/tty/tty_jobctrl.c (ffffffff817411ce)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tiocsctty
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/sysrq.c (ffffffff8174375e)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/tty/serial/serial_core.c (ffffffff81757983)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/block/loop.c (ffffffff817e74b2)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
```
```
In drivers/scsi/scsi_lib.c (ffffffff818380d0)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
```
```
In drivers/scsi/sd.c (ffffffff81844870)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
```
```
In drivers/scsi/sg.c (ffffffff8184dd07)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_debug_helper
```
```
In drivers/power/supply/power_supply_core.c (ffffffff8194ee15)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff8198c109)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/leds/led-triggers.c (ffffffff819b8b2d)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
```
In drivers/devfreq/devfreq.c (ffffffff819cfb3e)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
```
```
In net/core/skbuff.c (ffffffff819ed933)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dst.c (ffffffff81a10c28)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
```
```
In net/core/neighbour.c (ffffffff81a1202e)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_for_each
```
```
In net/core/net-sysfs.c (ffffffff81a391b0)
Location: arch/x86/include/asm/atomic.h:178
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
In net/sched/sch_api.c (ffffffff81a685df)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffffffff81a6c1cf)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffffffff81a72b44)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (ffffffff81a75d2e)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_lookup
  - net/sched/ematch.c:tcf_em_lookup
```
```
In net/netlink/af_netlink.c (ffffffff81a77213)
Location: arch/x86/include/asm/atomic.h:178
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
In net/ipv4/raw.c (ffffffff81ad0536)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/arp.c (ffffffff81ad962c)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_format_neigh_entry
```
```
In net/ipv4/ipmr.c (ffffffff81b01935)
Location: arch/x86/include/asm/atomic.h:178
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
Location: arch/x86/include/asm/atomic.h:178
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b12128)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/ipv6/ip6_output.c (ffffffff81b2cfd5)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_call_ra_chain
  - net/ipv6/ip6_output.c:ip6_call_ra_chain
```
```
In net/ipv6/route.c (ffffffff81b41b78)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4d267)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81b5d49a)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/mcast.c (ffffffff81b63a88)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - net/ipv6/mcast.c:inet6_mc_check
```
```
In net/ipv6/ip6mr.c (ffffffff81b77de9)
Location: arch/x86/include/asm/atomic.h:178
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
In net/rfkill/core.c (ffffffff81b97079)
Location: arch/x86/include/asm/atomic.h:178
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_release
```
```
In arch/x86/pci/common.c (ffffffff81bb9965)
Location: arch/x86/include/asm/atomic.h:178
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
In arch/x86/events/intel/uncore.c (ffffffff81018d6b)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81053879)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ed7c)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks
```
```
In kernel/fork.c (ffffffff810a36ad)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - kernel/fork.c:walk_process_tree
```
```
In kernel/exit.c (ffffffff810a8c84)
Location: arch/x86/include/asm/atomic.h:176
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
Location: arch/x86/include/asm/atomic.h:176
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
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff810b7a25)
Location: arch/x86/include/asm/atomic.h:176
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
In kernel/sys.c (ffffffff810bf055)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
```
```
In kernel/sched/core.c (ffffffff810e4574)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:uclamp_sync_util_min_rt_default
```
```
In kernel/locking/spinlock.c (ffffffff81c45811)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
```
```
In kernel/power/process.c (ffffffff811104be)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/livepatch/transition.c (ffffffff81137439)
Location: arch/x86/include/asm/atomic.h:176
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
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - kernel/module.c:try_release_module_ref
```
```
In kernel/pid_namespace.c (ffffffff811825cf)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tracepoint.c (ffffffff811a955b)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/trace_events.c (ffffffff811d2c58)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811d9ddd)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f3d74)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In mm/oom_kill.c (ffffffff81262113)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/swap.c (ffffffff812685fb)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - mm/swap.c:put_devmap_managed_page
```
```
In mm/mempolicy.c (ffffffff812dbe98)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
```
```
In mm/memory_hotplug.c (ffffffff812ec563)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/memory-failure.c (ffffffff8130cf34)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs_file
  - mm/memory-failure.c:collect_procs_anon
```
```
In mm/zsmalloc.c (ffffffff813127fe)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/exec.c (ffffffff81327bba)
Location: arch/x86/include/asm/atomic.h:176
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
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_getown_ex
  - fs/fcntl.c:f_getown
```
```
In fs/filesystems.c (ffffffff81345cc8)
Location: arch/x86/include/asm/atomic.h:176
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
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/inode.c (ffffffff813cb145)
Location: arch/x86/include/asm/atomic.h:176
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
```
```
In fs/proc/generic.c (ffffffff813d241a)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff813d3dda)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/kernfs/dir.c (ffffffff813e0aea)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
```
```
In fs/ext4/extents_status.c (ffffffff813fac7c)
Location: arch/x86/include/asm/atomic.h:176
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
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff8143ea2c)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/jbd2/transaction.c (ffffffff8145b983)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
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
  - fs/jbd2/transaction.c:wait_transaction_locked
```
```
In fs/jbd2/journal.c (ffffffff8146240f)
Location: arch/x86/include/asm/atomic.h:176
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
In security/keys/keyring.c (ffffffff814b699e)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/hooks.c (ffffffff814d38dd)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/integrity/iint.c (ffffffff81530e8a)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In block/blk-core.c (ffffffff8155f6f5)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
```
```
In block/blk-wbt.c (ffffffff81596ae5)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In lib/sbitmap.c (ffffffff81609d0c)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pci/pci.c (ffffffff8164fca5)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
```
```
In drivers/xen/events/events_base.c (ffffffff8173297a)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__xen_evtchn_do_upcall
```
```
In drivers/reset/core.c (ffffffff8174e5a6)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_array_rearm
```
```
In drivers/tty/tty_io.c (ffffffff81752708)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/tty/tty_buffer.c (ffffffff8175a989)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8175d0fe)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tiocsctty
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/sysrq.c (ffffffff8175f5de)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/tty/serial/serial_core.c (ffffffff81772a43)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/block/loop.c (ffffffff817fc0ef)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
```
```
In drivers/scsi/scsi_lib.c (ffffffff818489a1)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
```
```
In drivers/scsi/sd.c (ffffffff81854b8d)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
```
```
In drivers/scsi/sg.c (ffffffff8185e0f7)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_debug_helper
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81954875)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff8198fc39)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/devfreq/devfreq.c (ffffffff819cf85e)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
```
```
In net/core/skbuff.c (ffffffff819ed5f3)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dst.c (ffffffff81a10fd8)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
```
```
In net/core/neighbour.c (ffffffff81a1238e)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_for_each
```
```
In net/core/net-sysfs.c (ffffffff81a3b040)
Location: arch/x86/include/asm/atomic.h:176
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
In net/sched/sch_api.c (ffffffff81a70cef)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffffffff81a74a7f)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffffffff81a7b704)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (ffffffff81a7eade)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_lookup
  - net/sched/ematch.c:tcf_em_lookup
```
```
In net/netlink/af_netlink.c (ffffffff81a7ffa4)
Location: arch/x86/include/asm/atomic.h:176
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
In net/ipv4/raw.c (ffffffff81adc549)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/arp.c (ffffffff81ae608c)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_format_neigh_entry
```
```
In net/ipv4/ipmr.c (ffffffff81b0fa15)
Location: arch/x86/include/asm/atomic.h:176
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
Location: arch/x86/include/asm/atomic.h:176
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1f81b)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/ipv6/ip6_output.c (ffffffff81b3b9e5)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_call_ra_chain
  - net/ipv6/ip6_output.c:ip6_call_ra_chain
```
```
In net/ipv6/route.c (ffffffff81b50638)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffffffff81b5bef5)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81b6bc8a)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/mcast.c (ffffffff81b72243)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/ipv6/mcast.c:inet6_mc_check
```
```
In net/ipv6/ip6mr.c (ffffffff81b86d69)
Location: arch/x86/include/asm/atomic.h:176
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
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/rfkill/core.c (ffffffff81ba6d19)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_release
```
```
In arch/x86/pci/common.c (ffffffff81bce275)
Location: arch/x86/include/asm/atomic.h:176
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
In arch/x86/events/intel/uncore.c (ffffffff8101a08b)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81055149)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ec67)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks
```
```
In kernel/fork.c (ffffffff810a42dd)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - kernel/fork.c:walk_process_tree
```
```
In kernel/exit.c (ffffffff810a9c2d)
Location: arch/x86/include/asm/atomic.h:176
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
Location: arch/x86/include/asm/atomic.h:176
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
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff810b8f85)
Location: arch/x86/include/asm/atomic.h:176
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
In kernel/sys.c (ffffffff810c09e5)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
```
```
In kernel/sched/core.c (ffffffff810e6524)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
```
```
In kernel/locking/spinlock.c (ffffffff81c38ac5)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
```
```
In kernel/power/process.c (ffffffff81110efe)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/livepatch/transition.c (ffffffff811381e9)
Location: arch/x86/include/asm/atomic.h:176
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
Location: arch/x86/include/asm/atomic.h:176
Inline: True
```
```
In kernel/pid_namespace.c (ffffffff8118371f)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tracepoint.c (ffffffff811aa10b)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/trace_events.c (ffffffff811d390a)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811db33d)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f4a24)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In mm/oom_kill.c (ffffffff81266ba3)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/swap.c (ffffffff8126df8b)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - mm/swap.c:put_devmap_managed_page
```
```
In mm/memory_hotplug.c (ffffffff812c6e03)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/mempolicy.c (ffffffff812e3708)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
```
```
In mm/memory-failure.c (ffffffff813135ae)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
```
```
In mm/zsmalloc.c (ffffffff81318d1e)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/exec.c (ffffffff8132daea)
Location: arch/x86/include/asm/atomic.h:176
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
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_getown
```
```
In fs/filesystems.c (ffffffff8134c088)
Location: arch/x86/include/asm/atomic.h:176
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
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/io_uring.c (ffffffff81391d1d)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread_unpark
```
```
In fs/proc/inode.c (ffffffff813d2075)
Location: arch/x86/include/asm/atomic.h:176
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
```
```
In fs/proc/generic.c (ffffffff813d921c)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff813dac0a)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/kernfs/dir.c (ffffffff813e761a)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
```
```
In fs/ext4/extents_status.c (ffffffff814010df)
Location: arch/x86/include/asm/atomic.h:176
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
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/mballoc.c (ffffffff8141c4ed)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_seq_structs_summary_stop
```
```
In fs/ext4/super.c (ffffffff8144462c)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/jbd2/transaction.c (ffffffff814612c3)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
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
  - fs/jbd2/transaction.c:wait_transaction_locked
```
```
In fs/jbd2/journal.c (ffffffff81467abf)
Location: arch/x86/include/asm/atomic.h:176
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
In security/keys/keyring.c (ffffffff814bc7e6)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/hooks.c (ffffffff814da35d)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/integrity/iint.c (ffffffff815392ba)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In block/blk-core.c (ffffffff81567e95)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
```
```
In block/ioprio.c (ffffffff8157fea4)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - block/ioprio.c:__do_sys_ioprio_set
  - block/ioprio.c:__do_sys_ioprio_set
```
```
In block/blk-wbt.c (ffffffff8159d919)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In lib/sbitmap.c (ffffffff815eceec)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pci/pci.c (ffffffff81632865)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
```
```
In drivers/xen/events/events_base.c (ffffffff8171654a)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__xen_evtchn_do_upcall
```
```
In drivers/reset/core.c (ffffffff8173242a)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff81736855)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/tty/tty_buffer.c (ffffffff8173e82c)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8174145a)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/sysrq.c (ffffffff8174344e)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/tty/serial/serial_core.c (ffffffff817564be)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/block/loop.c (ffffffff817e11a1)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
```
```
In drivers/scsi/scsi_lib.c (ffffffff8182bdb0)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
```
```
In drivers/scsi/sd.c (ffffffff8183857d)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
```
```
In drivers/scsi/sg.c (ffffffff81840d60)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_debug_helper
```
```
In drivers/power/supply/power_supply_core.c (ffffffff819386e5)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81974219)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/devfreq/devfreq.c (ffffffff819b498e)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
```
```
In net/core/skbuff.c (ffffffff819d3703)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dst.c (ffffffff819f7e48)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
```
```
In net/core/neighbour.c (ffffffff819f8fbe)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_for_each
```
```
In net/core/net-sysfs.c (ffffffff81a225e0)
Location: arch/x86/include/asm/atomic.h:176
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
In net/sched/sch_api.c (ffffffff81a5963f)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffffffff81a5d61f)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffffffff81a64494)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (ffffffff81a6793e)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_lookup
  - net/sched/ematch.c:tcf_em_lookup
```
```
In net/netlink/af_netlink.c (ffffffff81a68eb5)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/ipv4/raw.c (ffffffff81ac74b9)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/arp.c (ffffffff81ad136c)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_format_neigh_entry
```
```
In net/ipv4/ipmr.c (ffffffff81afd615)
Location: arch/x86/include/asm/atomic.h:176
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
Location: arch/x86/include/asm/atomic.h:176
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0d6fb)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/ipv6/ip6_output.c (ffffffff81b2d056)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff81b3dd18)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4a0b7)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81b59faa)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/ip6mr.c (ffffffff81b75a34)
Location: arch/x86/include/asm/atomic.h:176
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
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/rfkill/core.c (ffffffff81b95ea9)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_release
```
```
In arch/x86/pci/common.c (ffffffff81bc1c35)
Location: arch/x86/include/asm/atomic.h:176
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
In arch/x86/events/intel/uncore.c (ffffffff8101c91b)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8105dae9)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81068374)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks
```
```
In kernel/fork.c (ffffffff810b5afd)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - kernel/fork.c:walk_process_tree
```
```
In kernel/exit.c (ffffffff810bb75b)
Location: arch/x86/include/asm/atomic.h:176
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
Location: arch/x86/include/asm/atomic.h:176
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
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff810cb515)
Location: arch/x86/include/asm/atomic.h:176
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
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
```
```
In kernel/sched/core.c (ffffffff810fda5b)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
```
```
In kernel/sched/core_sched.c (ffffffff8112c695)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - kernel/sched/core_sched.c:sched_core_share_pid
```
```
In kernel/locking/spinlock.c (ffffffff81d573a5)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
```
```
In kernel/power/process.c (ffffffff811309ea)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/livepatch/transition.c (ffffffff8115af73)
Location: arch/x86/include/asm/atomic.h:176
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
Location: arch/x86/include/asm/atomic.h:176
Inline: True
```
```
In kernel/pid_namespace.c (ffffffff811ab7ff)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tracepoint.c (ffffffff811d3c7b)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/trace_events.c (ffffffff8120078a)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff8120894d)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In kernel/trace/trace_uprobe.c (ffffffff81225dd4)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In mm/oom_kill.c (ffffffff812a33a3)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/swap.c (ffffffff812aaed8)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - mm/swap.c:put_devmap_managed_page
```
```
In mm/mempolicy.c (ffffffff8132a928)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
```
```
In mm/memory-failure.c (ffffffff8136006e)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
```
```
In mm/zsmalloc.c (ffffffff8136530e)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In mm/bootmem_info.c (ffffffff8136cb33)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In fs/exec.c (ffffffff8137b2ca)
Location: arch/x86/include/asm/atomic.h:176
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
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_getown
```
```
In fs/filesystems.c (ffffffff81399ec8)
Location: arch/x86/include/asm/atomic.h:176
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
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/io_uring.c (ffffffff813df57d)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread_unpark
```
```
In fs/proc/inode.c (ffffffff814235a5)
Location: arch/x86/include/asm/atomic.h:176
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
```
```
In fs/proc/generic.c (ffffffff8142a94c)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff8142c3aa)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/kernfs/dir.c (ffffffff8143932a)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
```
```
In fs/ext4/extents_status.c (ffffffff8145365c)
Location: arch/x86/include/asm/atomic.h:176
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
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/mballoc.c (ffffffff8146f8ed)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_seq_structs_summary_stop
```
```
In fs/ext4/super.c (ffffffff8149842c)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/ext4/fast_commit.c (ffffffff814afbaf)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_mark_ineligible
```
```
In fs/jbd2/transaction.c (ffffffff814b67b6)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
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
  - fs/jbd2/transaction.c:wait_transaction_locked
```
```
In fs/jbd2/journal.c (ffffffff814bdf1f)
Location: arch/x86/include/asm/atomic.h:176
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
In security/keys/keyring.c (ffffffff81515206)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/hooks.c (ffffffff8153325d)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/integrity/iint.c (ffffffff81597afa)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In block/blk-core.c (ffffffff815cc4e5)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
```
```
In block/ioprio.c (ffffffff815e4e17)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
  - block/ioprio.c:__do_sys_ioprio_set
```
```
In block/blk-wbt.c (ffffffff81605fd9)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In lib/sbitmap.c (ffffffff81659e0c)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pci/pci.c (ffffffff816a29c5)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
```
```
In drivers/xen/events/events_base.c (ffffffff817937da)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__xen_evtchn_do_upcall
```
```
In drivers/reset/core.c (ffffffff817b2c75)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff817b7215)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/tty/tty_buffer.c (ffffffff817befac)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/tty/tty_jobctrl.c (ffffffff817c1eba)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/sysrq.c (ffffffff817c3eee)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/tty/serial/serial_core.c (ffffffff817d9bee)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/block/loop.c (ffffffff81870b71)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b79a4)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
```
```
In drivers/scsi/sd.c (ffffffff818c2e8d)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
```
```
In drivers/scsi/sg.c (ffffffff818cd8bc)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_debug_helper
```
```
In drivers/power/supply/power_supply_core.c (ffffffff819dcc45)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81a1cf19)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/devfreq/devfreq.c (ffffffff81a634ce)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
```
```
In net/core/skbuff.c (ffffffff81a83465)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dst.c (ffffffff81aa9a58)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
```
```
In net/core/neighbour.c (ffffffff81aaab9e)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_for_each
```
```
In net/core/net-sysfs.c (ffffffff81ad65f0)
Location: arch/x86/include/asm/atomic.h:176
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
In net/sched/sch_api.c (ffffffff81b126ef)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffffffff81b1662f)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffffffff81b1d8a4)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (ffffffff81b20eae)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_lookup
  - net/sched/ematch.c:tcf_em_lookup
```
```
In net/netlink/af_netlink.c (ffffffff81b22485)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/ipv4/raw.c (ffffffff81b85cd9)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/arp.c (ffffffff81b8fe07)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_format_neigh_entry
```
```
In net/ipv4/ipmr.c (ffffffff81bbee75)
Location: arch/x86/include/asm/atomic.h:176
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
Location: arch/x86/include/asm/atomic.h:176
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd103b)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/ipv6/ip6_output.c (ffffffff81bf321a)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff81c04849)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffffffff81c11417)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81c2161c)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/ip6mr.c (ffffffff81c40456)
Location: arch/x86/include/asm/atomic.h:176
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
In net/packet/af_packet.c (ffffffff81c56b34)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/rfkill/core.c (ffffffff81c628f5)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_release
```
```
In arch/x86/pci/common.c (ffffffff81c92245)
Location: arch/x86/include/asm/atomic.h:176
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
In arch/x86/events/intel/uncore.c (ffffffff8101f2bb)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8106a1e8)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
```
In kernel/locking/spinlock.c (ffffffff81f29d05)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_irq
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
  - kernel/locking/spinlock.c:_raw_read_unlock
```
```
In kernel/module/main.c (ffffffff8118e26e)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
```
```
In kernel/trace/trace_events.c (ffffffff8123a857)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff81243f6a)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In mm/oom_kill.c (ffffffff812fb2b3)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/memremap.c (ffffffff813e6f85)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
```
```
In mm/bootmem_info.c (ffffffff813eaec3)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In fs/mbcache.c (ffffffff81481bc9)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_or_get
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/proc/inode.c (ffffffff8149c1d5)
Location: arch/x86/include/asm/atomic.h:176
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
```
```
In fs/kernfs/dir.c (ffffffff814b436a)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff81532a80)
Location: arch/x86/include/asm/atomic.h:176
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
In block/blk-core.c (ffffffff816782c5)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
```
```
In block/blk-mq-tag.c (ffffffff8168c84e)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-wbt.c (ffffffff816ba419)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In io_uring/io_uring.c (ffffffff81e8e4a9)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_sq_thread_unpark
  - io_uring/io_uring.c:__io_arm_poll_handler
  - io_uring/io_uring.c:io_poll_check_events
```
```
In lib/sbitmap.c (ffffffff817724cd)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pci/pci.c (ffffffff817c4b62)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
```
```
In drivers/reset/core.c (ffffffff818ef7e2)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_assert
  - drivers/reset/core.c:reset_control_rearm
  - drivers/reset/core.c:reset_control_rearm
```
```
In drivers/tty/tty_buffer.c (ffffffff818fb489)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/tty/serial/serial_core.c (ffffffff81918619)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/base/power/runtime.c (ffffffff8198f5d5)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_drop_usage_count
```
```
In drivers/scsi/scsi_lib.c (ffffffff81a03213)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
```
```
In drivers/scsi/sd.c (ffffffff81a0f09c)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81b40ee5)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81b86008)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/devfreq/devfreq.c (ffffffff81bd233d)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_resume_device
```
```
In net/core/skbuff.c (ffffffff81bf8b25)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dst.c (ffffffff81c21ea9)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
```
```
In net/netlink/af_netlink.c (ffffffff81cae387)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/rfkill/core.c (ffffffff81e051c5)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_release
```
```
In arch/x86/pci/common.c (ffffffff81e418b5)
Location: arch/x86/include/asm/atomic.h:176
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
In arch/x86/events/intel/uncore.c (ffffffff8102399b)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81079fa8)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
```
In kernel/locking/spinlock.c (ffffffff820d5c25)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_irq
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
  - kernel/locking/spinlock.c:_raw_read_unlock
```
```
In kernel/module/main.c (ffffffff811cd2d2)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
```
```
In kernel/trace/trace_events.c (ffffffff8128940a)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff81291baa)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In kernel/events/hw_breakpoint.c (ffffffff8134de3b)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
```
```
In mm/oom_kill.c (ffffffff813652a3)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/rmap.c (ffffffff813d7fd6)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
```
```
In mm/memremap.c (ffffffff8146ebd5)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
```
```
In mm/bootmem_info.c (ffffffff814730c3)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In fs/mbcache.c (ffffffff81514c46)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/proc/inode.c (ffffffff81530b05)
Location: arch/x86/include/asm/atomic.h:176
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
```
```
In fs/kernfs/dir.c (ffffffff8154b20a)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff815d0f50)
Location: arch/x86/include/asm/atomic.h:176
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
In block/blk-core.c (ffffffff817345b5)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
```
```
In block/blk-mq-tag.c (ffffffff8174b01e)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-wbt.c (ffffffff8177a9a9)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In io_uring/sqpoll.c (ffffffff8179a95d)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread_unpark
```
```
In io_uring/poll.c (ffffffff8179cdda)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_check_events
```
```
In drivers/pci/pci.c (ffffffff818e1b42)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
```
```
In drivers/reset/core.c (ffffffff81a47512)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_assert
  - drivers/reset/core.c:reset_control_rearm
  - drivers/reset/core.c:reset_control_rearm
```
```
In drivers/tty/tty_buffer.c (ffffffff81a546e9)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/tty/serial/serial_core.c (ffffffff81a7404f)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/base/power/runtime.c (ffffffff81aff6e5)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_drop_usage_count
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b81aab)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
```
```
In drivers/scsi/sd.c (ffffffff81b8f04c)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81cd7575)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81d25398)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/devfreq/devfreq.c (ffffffff81d7dfed)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_resume_device
```
```
In net/core/skbuff.c (ffffffff81da7a1a)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dst.c (ffffffff81dd4429)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
```
```
In net/netlink/af_netlink.c (ffffffff81e6b81e)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/rfkill/core.c (ffffffff81fda435)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_release
```
```
In arch/x86/pci/common.c (ffffffff8201bf15)
Location: arch/x86/include/asm/atomic.h:176
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
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
In arch/x86/events/intel/uncore.c (ffffffff810236bb)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8107c23d)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
```
In kernel/locking/spinlock.c (ffffffff82159005)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_irq
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
  - kernel/locking/spinlock.c:_raw_read_unlock
```
```
In kernel/module/main.c (ffffffff811e0bb2)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
```
```
In kernel/trace/trace_events.c (ffffffff812a616e)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff812aee0a)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In kernel/events/hw_breakpoint.c (ffffffff8137eed1)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
```
```
In mm/oom_kill.c (ffffffff81397763)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/rmap.c (ffffffff8140ca78)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
```
```
In mm/memremap.c (ffffffff814a3395)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
```
```
In mm/bootmem_info.c (ffffffff814a7833)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In fs/mbcache.c (ffffffff8154c646)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/proc/inode.c (ffffffff81568c85)
Location: arch/x86/include/asm/atomic.h:89
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
```
```
In fs/kernfs/dir.c (ffffffff81582e5a)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff81608b00)
Location: arch/x86/include/asm/atomic.h:89
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
In block/blk-core.c (ffffffff817709b5)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
```
```
In block/blk-wbt.c (ffffffff817b9c65)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In io_uring/sqpoll.c (ffffffff817dba0d)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread_unpark
```
```
In io_uring/poll.c (ffffffff817de004)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_check_events
```
```
In drivers/pci/pci.c (ffffffff81924f82)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
```
```
In drivers/reset/core.c (ffffffff81a916c2)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_assert
  - drivers/reset/core.c:reset_control_rearm
  - drivers/reset/core.c:reset_control_rearm
```
```
In drivers/tty/tty_buffer.c (ffffffff81a9ecc9)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/tty/serial/serial_core.c (ffffffff81abe6d3)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:serial_core_remove_one_port
```
```
In drivers/base/power/runtime.c (ffffffff81b4da95)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_drop_usage_count
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd57e4)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
```
```
In drivers/scsi/sd.c (ffffffff81be519c)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81d3f745)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81d8e5d8)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/devfreq/devfreq.c (ffffffff81dec36d)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_resume_device
```
```
In net/core/skbuff.c (ffffffff81e16471)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_data
```
```
In net/netlink/af_netlink.c (ffffffff81ec786a)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/rfkill/core.c (ffffffff820560f5)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_release
```
```
In arch/x86/pci/common.c (ffffffff8209c5b5)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
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
In arch/x86/events/intel/uncore.c (ffffffff810297eb)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
```
```
In kernel/locking/spinlock.c (ffffffff8223c885)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_irq
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
  - kernel/locking/spinlock.c:_raw_read_unlock
```
```
In kernel/module/main.c (ffffffff811f68e2)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
```
```
In kernel/trace/trace_events.c (ffffffff812c1c8e)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff812cb32a)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In kernel/events/hw_breakpoint.c (ffffffff813a8131)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
```
```
In mm/oom_kill.c (ffffffff813c1593)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/rmap.c (ffffffff8143b23d)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - mm/rmap.c:folio_remove_rmap_pmd
  - mm/rmap.c:folio_remove_rmap_ptes
```
```
In mm/memremap.c (ffffffff814d4235)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
```
```
In mm/bootmem_info.c (ffffffff814d8863)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In fs/open.c (ffffffff814d98ca)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/file_table.c (ffffffff814e2abf)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/mbcache.c (ffffffff81582476)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/proc/inode.c (ffffffff815a12a5)
Location: arch/x86/include/asm/atomic.h:89
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
```
```
In fs/kernfs/dir.c (ffffffff815bba8a)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff81641840)
Location: arch/x86/include/asm/atomic.h:89
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
In block/blk-core.c (ffffffff817b2c25)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
```
```
In block/blk-wbt.c (ffffffff817fe3d5)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In io_uring/sqpoll.c (ffffffff8181fd8d)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread_unpark
```
```
In io_uring/poll.c (ffffffff818223a1)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_check_events
```
```
In io_uring/waitid.c (ffffffff8182ae75)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - io_uring/waitid.c:io_waitid
  - io_uring/waitid.c:io_waitid_cb
```
```
In lib/closure.c (ffffffff8223beb9)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - lib/closure.c:__closure_sync
  - lib/closure.c:__closure_wake_up
  - lib/closure.c:closure_put
```
```
In drivers/pci/pci.c (ffffffff8196d652)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
```
```
In drivers/reset/core.c (ffffffff81ae4032)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_assert
  - drivers/reset/core.c:reset_control_rearm
  - drivers/reset/core.c:reset_control_rearm
```
```
In drivers/tty/tty_buffer.c (ffffffff81af17e9)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/tty/serial/serial_core.c (ffffffff81b11453)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:serial_core_remove_one_port
```
```
In drivers/base/power/runtime.c (ffffffff81ba6015)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_drop_usage_count
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c2a438)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
```
```
In drivers/scsi/sd.c (ffffffff81c3a2fc)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81df60f5)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81e45ee8)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/devfreq/devfreq.c (ffffffff81ea26bd)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_resume_device
```
```
In net/core/skbuff.c (ffffffff81ed3891)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_data
```
```
In net/netlink/af_netlink.c (ffffffff81f8abcc)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/rfkill/core.c (ffffffff82128975)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_release
```
```
In arch/x86/pci/common.c (ffffffff82173d95)
Location: arch/x86/include/asm/atomic.h:89
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/do_mounts.c (ffff800011431878)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In virt/kvm/kvm_main.c (ffff8000100bbf7c)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:__gfn_to_pfn_memslot
  - virt/kvm/kvm_main.c:kvm_put_kvm
  - virt/kvm/kvm_main.c:kvm_create_vm
```
```
In virt/kvm/arm/mmu.c (ffff8000100ca934)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:stage2_set_pte
  - virt/kvm/arm/mmu.c:stage2_set_pte
  - virt/kvm/arm/mmu.c:__unmap_hyp_range
  - virt/kvm/arm/mmu.c:__unmap_hyp_range
  - virt/kvm/arm/mmu.c:__unmap_hyp_range
  - virt/kvm/arm/mmu.c:__unmap_hyp_range
  - virt/kvm/arm/mmu.c:unmap_stage2_range
  - virt/kvm/arm/mmu.c:unmap_stage2_range
  - virt/kvm/arm/mmu.c:unmap_stage2_range
  - virt/kvm/arm/mmu.c:unmap_stage2_range
  - virt/kvm/arm/mmu.c:unmap_stage2_range
```
```
In kernel/fork.c (ffff8000100f5804)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:copy_process
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
  - kernel/fork.c:mmput
  - kernel/fork.c:__put_task_struct
  - kernel/fork.c:__mmdrop
```
```
In kernel/exit.c (ffff8000100fa6c8)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffff800010108550)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffff80001010b51c)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/umh.c (ffff80001011acdc)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffff80001011cdb4)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/workqueue.c:wq_worker_sleeping
```
```
In kernel/nsproxy.c (ffff80001012b6c0)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/cred.c (ffff80001012d0dc)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/groups.c (ffff80001013133c)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/groups.c:__arm64_sys_setgroups
  - kernel/groups.c:set_groups
```
```
In kernel/sched/core.c (ffff80001013d100)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/sched/topology.c (ffff80001015ad88)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/sched/topology.c:destroy_sched_domain
  - kernel/sched/topology.c:sched_put_rd
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/locking/mutex.c (ffff8000101688b0)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
```
```
In kernel/irq/manage.c (ffff80001017935c)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
```
```
In kernel/rcu/srcutree.c (ffff80001018a640)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier_cb
```
```
In kernel/rcu/tree.c (ffff80001018c1f0)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
```
```
In kernel/futex.c (ffff8000101b7bd8)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/uid16.c (ffff8000101be210)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/uid16.c:__arm64_sys_setgroups16
  - kernel/uid16.c:__arm64_sys_setgroups16
```
```
In kernel/module.c (ffff8000101c3408)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/module.c:__arm64_sys_delete_module
```
```
In kernel/cgroup/cgroup.c (ffff8000101d07bc)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffff8000101da07c)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/cgroup/cgroup-v1.c (ffff8000101db518)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
```
```
In kernel/utsname.c (ffff8000101e51f0)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/utsname.c:free_uts_ns
```
```
In kernel/user_namespace.c (ffff8000101e6770)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:unshare_userns
```
```
In kernel/pid_namespace.c (ffff8000101e7524)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/pid_namespace.c:delayed_free_pidns
```
```
In kernel/stop_machine.c (ffff8000101e8608)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:cpu_stop_signal_done
```
```
In kernel/trace/trace_events.c (ffff80001023b3a4)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffff800010242958)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
```
```
In kernel/bpf/syscall.c (ffff80001025fe5c)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_put_uref
```
```
In kernel/bpf/cpumap.c (ffff800010287e14)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
```
```
In kernel/bpf/stackmap.c (ffff80001028bc14)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffff80001029a98c)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_sched_delayed
Direct callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/uprobes.c (ffff8000102a59d0)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/events/uprobes.c:is_trap_at_addr
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/padata.c (ffff8000102a92e8)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_serial_worker
```
```
In kernel/jump_label.c (ffff8000102ab390)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
```
```
In mm/filemap.c (ffff8000102b16b8)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:wait_on_page_bit_common
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/oom_kill.c (ffff8000102b7a14)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/page-writeback.c (ffff8000102bd260)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffff8000102bf1c4)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffff8000102c1788)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (ffff8000102c408c)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffff8000102cb51c)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffff8000102d59a8)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/mmu_context.c (ffff8000102e001c)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/gup.c (ffff8000102f1288)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffff8000102fba0c)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/mincore.c (ffff8000102fccf8)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (ffff8000102fe1c8)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffff80001030a6cc)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/process_vm_access.c (ffff8000103123f0)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
```
```
In mm/page_alloc.c (ffff80001031726c)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/madvise.c (ffff80001031e6ec)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/madvise.c:__arm64_sys_madvise
  - mm/madvise.c:__arm64_sys_madvise
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffff8000103223a8)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffff800010327a44)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/zswap.c (ffff80001032c5e4)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffff8000103361d0)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
```
```
In mm/mempolicy.c (ffff800010339b40)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/mmu_notifier.c (ffff80001033cd24)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (ffff80001033fbac)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
  - mm/ksm.c:break_ksm
```
```
In mm/memory_hotplug.c (ffff80001034e0ec)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/migrate.c (ffff8000103530f8)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffff800010359c28)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffff80001035f818)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (ffff800010368bcc)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffff800010370644)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
```
```
In mm/zsmalloc.c (ffff800010375d04)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (ffff800010378424)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/page_idle.c (ffff80001037934c)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffff800010379d68)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In fs/open.c (ffff80001037e450)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/open.c:do_faccessat
```
```
In fs/read_write.c (ffff800010380460)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
```
```
In fs/file_table.c (ffff8000103851b0)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/file_table.c:file_free_rcu
```
```
In fs/super.c (ffff800010386a60)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/super.c:deactivate_locked_super
```
```
In fs/exec.c (ffff80001038ce58)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/pipe.c (ffff80001038fcc0)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffff800010393354)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/dcache.c (ffff8000103a8390)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:dentry_free
  - fs/dcache.c:release_dentry_name_snapshot
```
```
In fs/file.c (ffff8000103b1dc8)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
```
```
In fs/namespace.c (ffff8000103b4af8)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/namespace.c:free_mnt_ns
```
```
In fs/libfs.c (ffff8000103c0a5c)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/fs-writeback.c (ffff8000103c3e1c)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
```
```
In fs/splice.c (ffff8000103ce474)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/fs_context.c (ffff8000103d58e0)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:put_fs_context
```
```
In fs/buffer.c (ffff8000103dd00c)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffff8000103e0acc)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
  - fs/block_dev.c:blkdev_bio_end_io
```
```
In fs/direct-io.c (ffff8000103e4f60)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:dio_complete
```
```
In fs/mpage.c (ffff8000103e6ef4)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/notify/mark.c (ffff8000103e9d98)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
```
```
In fs/userfaultfd.c (ffff8000103f6e04)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/userfaultfd.c:__arm64_sys_userfaultfd
```
```
In fs/aio.c (ffff8000103ff808)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/aio.c:exit_aio
  - fs/aio.c:free_ioctx_reqs
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/io_uring.c (ffff800010403444)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_mem_free
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/verity/enable.c (ffff800010411120)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/verify.c (ffff8000104133a4)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/binfmt_elf.c (ffff800010420f54)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffff800010424804)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/mbcache.c (ffff800010424f0c)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:__entry_find
```
```
In fs/coredump.c (ffff800010428444)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffff80001042bbfc)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/iomap/direct-io.c (ffff80001042d36c)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/proc/task_mmu.c (ffff8000104397dc)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:proc_map_release
```
```
In fs/proc/inode.c (ffff80001043b378)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/proc/inode.c:unuse_pde
```
```
In fs/proc/root.c (ffff80001043c94c)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffff80001043e754)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:mem_release
```
```
In fs/proc/array.c (ffff800010444fd0)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/kernfs/dir.c (ffff800010452014)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
```
```
In fs/kernfs/file.c (ffff800010454d0c)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
```
```
In fs/sysfs/mount.c (ffff800010457a64)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/configfs/inode.c (ffff800010458ce4)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffff80001045af30)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffff80001045d7ac)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
```
```
In fs/ext4/inline.c (ffff80001047b310)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffff800010488fc4)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_end_io_dio
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/mballoc.c (ffff8000104923c8)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/move_extent.c (ffff80001049a7b8)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffff8000104a3bbc)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/readpage.c (ffff8000104a4df4)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffff8000104c0f58)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
```
```
In fs/ext4/xattr.c (ffff8000104c4b68)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/ext4/verity.c (ffff8000104c833c)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
```
```
In fs/jbd2/transaction.c (ffff8000104ca5f0)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
```
```
In fs/jbd2/commit.c (ffff8000104cf414)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (ffff8000104dbcb0)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffff8000104de140)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffff8000104e24e0)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffff8000104f626c)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffff8000104f66e8)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffff8000105031bc)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffff80001050e63c)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages_end
```
```
In fs/fuse/inode.c (ffff800010512150)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
```
```
In fs/fuse/readdir.c (ffff8000105154c8)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
```
```
In ipc/mqueue.c (ffff800010529dbc)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffff80001052cd44)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/keyctl.c (ffff800010533b54)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (ffff8000105352b0)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffff800010535948)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffff800010536358)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
```
```
In security/tomoyo/common.c (ffff80001057d8ac)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_close_control
```
```
In security/tomoyo/domain.c (ffff8000105802b0)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In security/apparmor/domain.c (ffff800010594e68)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffff80001059d970)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_getprocattr
```
```
In block/bio.c (ffff8000105dbc58)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/blk-core.c (ffff8000105e0d74)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
```
```
In block/blk-ioc.c (ffff8000105e8964)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
```
```
In block/partition-generic.c (ffff8000105fd100)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (ffff8000105ff524)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffff800010600080)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffff800010600504)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffff8000106010c4)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffff800010603100)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_tocblocks
```
```
In block/partitions/msdos.c (ffff800010604984)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
```
```
In block/partitions/osf.c (ffff8000106051f8)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffff8000106054bc)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffff800010605824)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffff800010605ac4)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffff800010606020)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffff800010606c54)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffff800010606ef8)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In block/blk-wbt.c (ffff800010621068)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In lib/sbitmap.c (ffff80001066a2f0)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pci/pci.c (ffff8000106e6b18)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
```
```
In drivers/video/fbdev/core/fbmem.c (ffff8000107434c0)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
```
```
In drivers/dma/dmaengine.c (ffff8000107fd0b0)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:chan_dev_release
```
```
In drivers/virtio/virtio_balloon.c (ffff80001082b23c)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffff80001082e240)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/reset/core.c (ffff80001084d0c4)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffff80001085d640)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/tty/serial/serial_core.c (ffff80001087dc5c)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/serial_core.c:uart_poll_put_char
  - drivers/tty/serial/serial_core.c:uart_poll_get_char
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_carrier_raised
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_icount
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_send_xchar
  - drivers/tty/serial/serial_core.c:uart_flush_buffer
  - drivers/tty/serial/serial_core.c:uart_chars_in_buffer
  - drivers/tty/serial/serial_core.c:uart_write_room
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/char/virtio_console.c (ffff8000108b3840)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
```
```
In drivers/base/power/runtime.c (ffff8000108fd74c)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:__pm_runtime_idle
```
```
In drivers/base/power/domain.c (ffff80001090887c)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_sd_counter_dec
```
```
In drivers/block/loop.c (ffff800010923968)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_rw_aio_do_completion
```
```
In drivers/mfd/mfd-core.c (ffff8000109408d0)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
```
```
In drivers/nvdimm/bus.c (ffff800010952e50)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
```
```
In drivers/dma-buf/dma-fence-array.c (ffff800010968000)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
```
```
In drivers/dma-buf/udmabuf.c (ffff80001096cbfc)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffff800010970d20)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/scsi/scsi_lib.c (ffff800010978dbc)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/sd.c (ffff800010987c80)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
```
```
In drivers/net/tun.c (ffff8000109e18e8)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/ethernet/broadcom/bgmac.c (ffff8000109e2b64)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_cleanup
```
```
In drivers/usb/core/devio.c (ffff800010a2d304)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/power/supply/power_supply_core.c (ffff800010acc5e4)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/md/md.c (ffff800010ae9b20)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/md-bitmap.c (ffff800010af7f44)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
  - drivers/md/md-bitmap.c:end_bitmap_write
  - drivers/md/md-bitmap.c:write_page
```
```
In drivers/md/dm.c (ffff800010afe544)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-io.c (ffff800010b0a034)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dec_count
```
```
In drivers/md/dm-kcopyd.c (ffff800010b0babc)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:run_complete_job
```
```
In drivers/edac/edac_pci_sysfs.c (ffff800010b13cb0)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (ffff800010b81200)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
```
```
In drivers/devfreq/devfreq.c (ffff800010b864e0)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
```
```
In net/core/sock.c (ffff800010baca18)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffff800010bb3da0)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/net_namespace.c (ffff800010bc111c)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/dev.c (ffff800010bced24)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/dst.c (ffff800010be0e78)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
```
```
In net/core/filter.c (ffff800010bfdc08)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffff800010c06d54)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffff800010c0ca68)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/skmsg.c (ffff800010c0e784)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/netlink/af_netlink.c (ffff800010c4dd44)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/ipv4/ip_input.c (ffff800010c5eb50)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_output.c (ffff800010c623dc)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp.c (ffff800010c76190)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffff800010c81f8c)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8f148)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffff800010c987ec)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
```
```
In net/ipv4/udp.c (ffff800010c9f454)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/fib_semantics.c (ffff800010cb68c8)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_common_release
```
```
In net/ipv4/ping.c (ffff800010cc0e20)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/ipmr.c (ffff800010ccfc00)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/tcp_bpf.c (ffff800010cd3620)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_policy.c (ffff800010ce0c58)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_state.c (ffff800010ce35ec)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/xfrm_input.c (ffff800010cead48)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffff800010cec41c)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/unix/af_unix.c (ffff800010cf4050)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
```
In net/ipv6/ip6_output.c (ffff800010cf8484)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffff800010cfd924)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffff800010d1583c)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_init
```
```
In net/ipv6/raw.c (ffff800010d2af68)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/ip6_flowlabel.c (ffff800010d3f094)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/packet/af_packet.c (ffff800010d5b710)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/rfkill/core.c (ffff800010d6bb20)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_release
```
```
In net/dns_resolver/dns_key.c (ffff800010d72ed4)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
```
```
In lib/dec_and_lock.c (ffff800010d847a8)
Location: arch/arm64/include/asm/atomic.h:53
Inline: True
```
**Symbols:**

```
ffff8000100fa6c8-ffff8000100fa70c: arch_atomic_sub_return.constprop.0 (STB_LOCAL)
ffff800010295298-ffff8000102952c8: arch_atomic_sub_return.constprop.0 (STB_LOCAL)
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
In arch/x86/events/intel/uncore.c (ffffffff810171e8)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8105051a)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b22b)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In kernel/fork.c (ffffffff8109a47d)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/fork.c:walk_process_tree
```
```
In kernel/exit.c (ffffffff8109f3b7)
Location: arch/x86/include/asm/atomic.h:177
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
Location: arch/x86/include/asm/atomic.h:177
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
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff810adfff)
Location: arch/x86/include/asm/atomic.h:177
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
In kernel/sys.c (ffffffff810b6635)
Location: arch/x86/include/asm/atomic.h:177
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
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
```
```
In kernel/locking/spinlock.c (ffffffff81a738b5)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
```
```
In kernel/power/process.c (ffffffff81101e1f)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/livepatch/transition.c (ffffffff81126cac)
Location: arch/x86/include/asm/atomic.h:177
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
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/module.c:try_release_module_ref
```
```
In kernel/cgroup/cgroup.c (ffffffff8115b72b)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_enable_task_cg_lists
```
```
In kernel/pid_namespace.c (ffffffff8116b997)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tracepoint.c (ffffffff8118ef4b)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/fgraph.c (ffffffff811b2582)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
```
In kernel/trace/trace_events.c (ffffffff811b2d02)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811bb67f)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d0b64)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In kernel/bpf/syscall.c (ffffffff811d6f8c)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In mm/oom_kill.c (ffffffff81222d73)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/mempolicy.c (ffffffff81294d08)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
```
```
In mm/memory_hotplug.c (ffffffff812a4b53)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/memory-failure.c (ffffffff812c34af)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
```
```
In mm/zsmalloc.c (ffffffff812c8af6)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In mm/memremap.c (ffffffff812cc8e5)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In fs/exec.c (ffffffff812dec7f)
Location: arch/x86/include/asm/atomic.h:177
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
Location: arch/x86/include/asm/atomic.h:177
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
In fs/filesystems.c (ffffffff812f92c0)
Location: arch/x86/include/asm/atomic.h:177
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
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/io_uring.c (ffffffff8133b636)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/proc/inode.c (ffffffff81369dd5)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/proc/inode.c:unuse_pde
```
```
In fs/proc/generic.c (ffffffff8136fd3a)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff81371226)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/kernfs/dir.c (ffffffff8137c9ba)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In fs/ext4/extents_status.c (ffffffff81395909)
Location: arch/x86/include/asm/atomic.h:177
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
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff813d1f8c)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/jbd2/transaction.c (ffffffff813ea983)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:wait_transaction_locked
```
```
In fs/jbd2/journal.c (ffffffff813ef0ff)
Location: arch/x86/include/asm/atomic.h:177
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
In security/keys/keyring.c (ffffffff8143fd87)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/hooks.c (ffffffff81457095)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/selinux/ss/services.c (ffffffff81470d04)
Location: arch/x86/include/asm/atomic.h:177
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
In security/integrity/iint.c (ffffffff814acd8a)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In block/blk-core.c (ffffffff814dcb55)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In block/blk-wbt.c (ffffffff81511bf5)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In lib/sbitmap.c (ffffffff81554447)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pci/pci.c (ffffffff815772d2)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
```
```
In drivers/reset/core.c (ffffffff81647743)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff8164a0c4)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/tty/tty_buffer.c (ffffffff81652489)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81654bf7)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/sysrq.c (ffffffff816566ee)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/tty/serial/serial_core.c (ffffffff8166adb3)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/block/loop.c (ffffffff816f12e2)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
```
```
In drivers/mfd/mfd-core.c (ffffffff81701f0a)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff8172915d)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/sd.c (ffffffff81734502)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
```
```
In drivers/scsi/sg.c (ffffffff8173d1bc)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
```
```
In drivers/nvme/host/pci.c (ffffffff81750486)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_timeout
```
```
In drivers/power/supply/power_supply_core.c (ffffffff818282c5)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81861455)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In drivers/leds/led-triggers.c (ffffffff81888c20)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
```
In drivers/devfreq/devfreq.c (ffffffff8189a23a)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In arch/x86/pci/common.c (ffffffff818a8465)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
```
```
In net/core/skbuff.c (ffffffff818bb9f3)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dst.c (ffffffff818e102a)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
```
```
In net/core/neighbour.c (ffffffff818e14de)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_for_each
```
```
In net/core/net-sysfs.c (ffffffff819048b8)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:address_show
```
```
In net/sched/sch_api.c (ffffffff8192fd3f)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffffffff81933ec7)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffffffff81939c54)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (ffffffff8193ca0e)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff8193dd34)
Location: arch/x86/include/asm/atomic.h:177
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
In net/ipv4/raw.c (ffffffff819828b6)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/arp.c (ffffffff8198bbf8)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
```
```
In net/ipv4/ipmr.c (ffffffff819aec95)
Location: arch/x86/include/asm/atomic.h:177
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
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff819bfcc5)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/ipv6/ip6_output.c (ffffffff819d9c4c)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff819eb1bb)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffffffff819f66eb)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
```
In net/ipv6/raw.c (ffffffff81a041dc)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/mcast.c (ffffffff81a0a242)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/ipv6/mcast.c:inet6_mc_check
```
```
In net/ipv6/ip6mr.c (ffffffff81a1cacf)
Location: arch/x86/include/asm/atomic.h:177
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
In net/rfkill/core.c (ffffffff81a3ac79)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
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
In arch/x86/events/intel/uncore.c (ffffffff81016618)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8103fb6a)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104b39b)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In kernel/fork.c (ffffffff81088ebd)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/fork.c:walk_process_tree
```
```
In kernel/exit.c (ffffffff8108dde7)
Location: arch/x86/include/asm/atomic.h:177
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
Location: arch/x86/include/asm/atomic.h:177
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
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff8109c959)
Location: arch/x86/include/asm/atomic.h:177
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
In kernel/sys.c (ffffffff810a4f75)
Location: arch/x86/include/asm/atomic.h:177
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
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
```
```
In kernel/sched/rt.c (ffffffff810d998b)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:tg_set_rt_bandwidth
```
```
In kernel/locking/spinlock.c (ffffffff81a2fc35)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
```
```
In kernel/power/process.c (ffffffff810f21df)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/livepatch/transition.c (ffffffff8111970c)
Location: arch/x86/include/asm/atomic.h:177
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
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/module.c:try_release_module_ref
```
```
In kernel/cgroup/cgroup.c (ffffffff8114ea15)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_enable_task_cg_lists
```
```
In kernel/pid_namespace.c (ffffffff8115eb97)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tracepoint.c (ffffffff811820cb)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/fgraph.c (ffffffff811a5392)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
```
In kernel/trace/trace_events.c (ffffffff811a5b02)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811ae45f)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In kernel/trace/trace_uprobe.c (ffffffff811c3934)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In kernel/bpf/syscall.c (ffffffff811c9d4c)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In mm/oom_kill.c (ffffffff81215f23)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/mempolicy.c (ffffffff81286918)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
```
```
In mm/memory_hotplug.c (ffffffff81296623)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/memory-failure.c (ffffffff812b44ef)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
```
```
In mm/zsmalloc.c (ffffffff812b9b36)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In mm/memremap.c (ffffffff812bd755)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In fs/exec.c (ffffffff812ceda4)
Location: arch/x86/include/asm/atomic.h:177
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
Location: arch/x86/include/asm/atomic.h:177
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
In fs/filesystems.c (ffffffff812e9ee0)
Location: arch/x86/include/asm/atomic.h:177
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
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/io_uring.c (ffffffff8132c316)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/proc/inode.c (ffffffff8135a865)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/proc/inode.c:unuse_pde
```
```
In fs/proc/generic.c (ffffffff813607ca)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff81361cb6)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/kernfs/dir.c (ffffffff8136d48a)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In fs/ext4/extents_status.c (ffffffff81386399)
Location: arch/x86/include/asm/atomic.h:177
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
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff813c2a0c)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/jbd2/transaction.c (ffffffff813db403)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:wait_transaction_locked
```
```
In fs/jbd2/journal.c (ffffffff813dfb7f)
Location: arch/x86/include/asm/atomic.h:177
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
In security/keys/keyring.c (ffffffff814307f7)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/hooks.c (ffffffff81447ad5)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/selinux/ss/services.c (ffffffff81461724)
Location: arch/x86/include/asm/atomic.h:177
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
In security/integrity/iint.c (ffffffff8149d7aa)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In block/blk-core.c (ffffffff814cd505)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In block/blk-wbt.c (ffffffff81501f15)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In lib/sbitmap.c (ffffffff815446c7)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pci/pci.c (ffffffff81565a32)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
```
```
In drivers/reset/core.c (ffffffff81627ba3)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff8162a514)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/tty/tty_buffer.c (ffffffff816328c9)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81634fc1)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/sysrq.c (ffffffff81636a7e)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/tty/serial/serial_core.c (ffffffff81649f23)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/block/loop.c (ffffffff816cb3e2)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
```
```
In drivers/mfd/mfd-core.c (ffffffff816d5d1a)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff8170258d)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/sd.c (ffffffff817161a2)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
```
```
In drivers/scsi/sg.c (ffffffff8171ee5c)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
```
```
In drivers/nvme/host/pci.c (ffffffff81730326)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_timeout
```
```
In drivers/power/supply/power_supply_core.c (ffffffff817ef955)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81828a05)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In drivers/leds/led-triggers.c (ffffffff818405a0)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
```
In drivers/devfreq/devfreq.c (ffffffff8185770a)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In arch/x86/pci/common.c (ffffffff81862e75)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
```
```
In net/core/skbuff.c (ffffffff81875933)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dst.c (ffffffff8189ae6a)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
```
```
In net/core/neighbour.c (ffffffff8189b31e)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_for_each
```
```
In net/core/net-sysfs.c (ffffffff818be6e8)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:address_show
```
```
In net/sched/sch_api.c (ffffffff818e983f)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffffffff818ed9c7)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffffffff818f3754)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (ffffffff818f650e)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff818f7834)
Location: arch/x86/include/asm/atomic.h:177
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
In net/ipv4/raw.c (ffffffff8193c376)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/arp.c (ffffffff819456b8)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
```
```
In net/ipv4/ipmr.c (ffffffff8196b2c5)
Location: arch/x86/include/asm/atomic.h:177
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
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197cab5)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/ipv6/ip6_output.c (ffffffff81996a0c)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff819a7f7b)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffffffff819b34ab)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
```
In net/ipv6/raw.c (ffffffff819c0f9c)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/mcast.c (ffffffff819c7002)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/ipv6/mcast.c:inet6_mc_check
```
```
In net/ipv6/ip6mr.c (ffffffff819d988f)
Location: arch/x86/include/asm/atomic.h:177
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
In net/rfkill/core.c (ffffffff819f7899)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
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
In arch/x86/events/intel/uncore.c (ffffffff810171a8)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff810503ca)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b65b)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In kernel/fork.c (ffffffff8109a42d)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/fork.c:walk_process_tree
```
```
In kernel/exit.c (ffffffff8109f367)
Location: arch/x86/include/asm/atomic.h:177
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
Location: arch/x86/include/asm/atomic.h:177
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
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff810ad55f)
Location: arch/x86/include/asm/atomic.h:177
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
In kernel/sys.c (ffffffff810b5b95)
Location: arch/x86/include/asm/atomic.h:177
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
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
```
```
In kernel/sched/rt.c (ffffffff810e6afb)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:tg_set_rt_bandwidth
```
```
In kernel/locking/spinlock.c (ffffffff81adfcc5)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
```
```
In kernel/power/process.c (ffffffff810ff1af)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/livepatch/transition.c (ffffffff81124b9c)
Location: arch/x86/include/asm/atomic.h:177
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
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/module.c:try_release_module_ref
```
```
In kernel/cgroup/cgroup.c (ffffffff811594fb)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_enable_task_cg_lists
```
```
In kernel/pid_namespace.c (ffffffff81169767)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tracepoint.c (ffffffff8118cd1b)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/fgraph.c (ffffffff811b0352)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
```
In kernel/trace/trace_events.c (ffffffff811b0ad2)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811b944f)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In kernel/trace/trace_uprobe.c (ffffffff811ce934)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In kernel/bpf/syscall.c (ffffffff811d4d5c)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In mm/oom_kill.c (ffffffff81220b13)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/mempolicy.c (ffffffff81292b18)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
```
```
In mm/memory_hotplug.c (ffffffff812a2963)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/memory-failure.c (ffffffff812c12bf)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
```
```
In mm/zsmalloc.c (ffffffff812c6906)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In mm/memremap.c (ffffffff812ca6f5)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In fs/exec.c (ffffffff812dca8f)
Location: arch/x86/include/asm/atomic.h:177
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
Location: arch/x86/include/asm/atomic.h:177
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
In fs/filesystems.c (ffffffff812f70b0)
Location: arch/x86/include/asm/atomic.h:177
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
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/io_uring.c (ffffffff81339106)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/proc/inode.c (ffffffff813678a5)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/proc/inode.c:unuse_pde
```
```
In fs/proc/generic.c (ffffffff8136d80a)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff8136ecf6)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/kernfs/dir.c (ffffffff8137a48a)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In fs/ext4/extents_status.c (ffffffff81393269)
Location: arch/x86/include/asm/atomic.h:177
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
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff813cf41c)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/jbd2/transaction.c (ffffffff813e7d03)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:wait_transaction_locked
```
```
In fs/jbd2/journal.c (ffffffff813ec47f)
Location: arch/x86/include/asm/atomic.h:177
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
In security/keys/keyring.c (ffffffff8143bf27)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/hooks.c (ffffffff81453135)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/selinux/ss/services.c (ffffffff8146cda4)
Location: arch/x86/include/asm/atomic.h:177
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
In security/integrity/iint.c (ffffffff814a8e2a)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In block/blk-core.c (ffffffff814d8be5)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In block/blk-wbt.c (ffffffff8150dc85)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In lib/sbitmap.c (ffffffff81550187)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pci/pci.c (ffffffff81576b02)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
```
```
In drivers/reset/core.c (ffffffff81675b03)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff81678484)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/tty/tty_buffer.c (ffffffff81680849)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81682fb7)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/sysrq.c (ffffffff81684aae)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/tty/serial/serial_core.c (ffffffff81699193)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/block/loop.c (ffffffff8171e9c2)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
```
```
In drivers/mfd/mfd-core.c (ffffffff8173732a)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81767f2d)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/sd.c (ffffffff81774c92)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
```
```
In drivers/scsi/sg.c (ffffffff8177d94c)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81875205)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff818b0a85)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In drivers/leds/led-triggers.c (ffffffff818da8f0)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
```
In drivers/devfreq/devfreq.c (ffffffff818e992a)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In arch/x86/pci/common.c (ffffffff818f9ac5)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
```
```
In net/core/skbuff.c (ffffffff8190c9f3)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dst.c (ffffffff8193205a)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
```
```
In net/core/neighbour.c (ffffffff8193250e)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_for_each
```
```
In net/core/net-sysfs.c (ffffffff819558e8)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:address_show
```
```
In net/sched/sch_api.c (ffffffff81980ecf)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffffffff81985057)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffffffff8198ade4)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (ffffffff8198db9e)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff8198eec4)
Location: arch/x86/include/asm/atomic.h:177
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
In net/ipv4/raw.c (ffffffff819ed086)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/arp.c (ffffffff819f6408)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
```
```
In net/ipv4/ipmr.c (ffffffff81a19535)
Location: arch/x86/include/asm/atomic.h:177
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
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2a745)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/ipv6/ip6_output.c (ffffffff81a446cc)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff81a55c3b)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffffffff81a6116b)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
```
In net/ipv6/raw.c (ffffffff81a6ec5c)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/mcast.c (ffffffff81a74cc2)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/ipv6/mcast.c:inet6_mc_check
```
```
In net/ipv6/ip6mr.c (ffffffff81a8754f)
Location: arch/x86/include/asm/atomic.h:177
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
In net/rfkill/core.c (ffffffff81aa6b29)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
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
In arch/x86/events/intel/uncore.c (ffffffff810173e8)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8105180a)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
```
In kernel/locking/spinlock.c (ffffffff81aec665)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_irq
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
  - kernel/locking/spinlock.c:_raw_read_unlock
```
```
In kernel/module.c (ffffffff81153dd5)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/module.c:try_release_module_ref
```
```
In kernel/trace/trace_events.c (ffffffff811beb62)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811c74ef)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811e308c)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In mm/oom_kill.c (ffffffff8122fcb3)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/memory_hotplug.c (ffffffff812b2bf3)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/memremap.c (ffffffff812db3f5)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In fs/io_uring.c (ffffffff8134b95d)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/proc/inode.c (ffffffff8137aef5)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - fs/proc/inode.c:unuse_pde
```
```
In fs/kernfs/dir.c (ffffffff8138df7a)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In block/blk-core.c (ffffffff814f17f5)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In block/blk-wbt.c (ffffffff815272a5)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In lib/sbitmap.c (ffffffff81569fc7)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pci/pci.c (ffffffff81590fe2)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
```
```
In drivers/reset/core.c (ffffffff81690163)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffff8169ae99)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/tty/serial/serial_core.c (ffffffff816b3853)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/block/loop.c (ffffffff81739df2)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
```
```
In drivers/mfd/mfd-core.c (ffffffff8175276a)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff8178366a)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/sd.c (ffffffff8178ea72)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81890ba5)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff818ccd15)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In drivers/devfreq/devfreq.c (ffffffff8190a9aa)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
```
```
In arch/x86/pci/common.c (ffffffff8191ac25)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
```
```
In net/core/skbuff.c (ffffffff8192db33)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dst.c (ffffffff8195372a)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
```
```
In net/netlink/af_netlink.c (ffffffff819b453b)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/rfkill/core.c (ffffffff81ab2ec9)
Location: arch/x86/include/asm/atomic.h:177
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_release
```
</details>
</li>
</ul>

## Differences

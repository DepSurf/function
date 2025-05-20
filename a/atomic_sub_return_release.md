# Function: <code>atomic_sub_return_release</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8106051c)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks
```
```
In kernel/fork.c (ffffffff810a79cd)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - kernel/fork.c:walk_process_tree
```
```
In kernel/exit.c (ffffffff810ad5b4)
Location: include/asm-generic/atomic-instrumented.h:178
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
Location: include/asm-generic/atomic-instrumented.h:178
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
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff810bc735)
Location: include/asm-generic/atomic-instrumented.h:178
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
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
```
```
In kernel/sched/core.c (ffffffff810e6674)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
```
```
In kernel/locking/spinlock.c (ffffffff81bccc45)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
```
```
In kernel/power/process.c (ffffffff8111346e)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/livepatch/transition.c (ffffffff8113cd29)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_send_signals
  - kernel/livepatch/transition.c:klp_complete_transition
```
```
In kernel/pid_namespace.c (ffffffff811854c3)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tracepoint.c (ffffffff811abc5b)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/fgraph.c (ffffffff811d29a4)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:alloc_retstack_tasklist
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f53e4)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In mm/mempolicy.c (ffffffff812d0378)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
```
```
In mm/memory-failure.c (ffffffff81300d95)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs_file
  - mm/memory-failure.c:collect_procs_anon
```
```
In mm/zsmalloc.c (ffffffff81306c6e)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/exec.c (ffffffff8131ca2a)
Location: include/asm-generic/atomic-instrumented.h:178
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
Location: include/asm-generic/atomic-instrumented.h:178
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
Location: include/asm-generic/atomic-instrumented.h:178
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
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/generic.c (ffffffff813c05ca)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff813c1cba)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/ext4/extents_status.c (ffffffff813e89cc)
Location: include/asm-generic/atomic-instrumented.h:178
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
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff81425d88)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/jbd2/transaction.c (ffffffff8143f723)
Location: include/asm-generic/atomic-instrumented.h:178
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
Location: include/asm-generic/atomic-instrumented.h:178
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
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/hooks.c (ffffffff814b5bfd)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/selinux/ss/services.c (ffffffff814cdbf3)
Location: include/asm-generic/atomic-instrumented.h:178
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
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In drivers/tty/tty_io.c (ffffffff81736e68)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/tty/tty_jobctrl.c (ffffffff817411ce)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tiocsctty
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/sysrq.c (ffffffff8174375e)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/scsi/sg.c (ffffffff8184dd07)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_debug_helper
```
```
In drivers/leds/led-triggers.c (ffffffff819b8b2d)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
```
In net/core/neighbour.c (ffffffff81a1202e)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_for_each
```
```
In net/core/net-sysfs.c (ffffffff81a391b0)
Location: include/asm-generic/atomic-instrumented.h:178
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
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffffffff81a6c1cf)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffffffff81a72b44)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (ffffffff81a75d2e)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_lookup
  - net/sched/ematch.c:tcf_em_lookup
```
```
In net/netlink/af_netlink.c (ffffffff81a77213)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/ipv4/raw.c (ffffffff81ad0536)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/arp.c (ffffffff81ad962c)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_format_neigh_entry
```
```
In net/ipv4/ipmr.c (ffffffff81b01935)
Location: include/asm-generic/atomic-instrumented.h:178
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
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b12128)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/ipv6/ip6_output.c (ffffffff81b2cfd5)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_call_ra_chain
  - net/ipv6/ip6_output.c:ip6_call_ra_chain
```
```
In net/ipv6/route.c (ffffffff81b41b78)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4d267)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81b5d49a)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/mcast.c (ffffffff81b63a88)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - net/ipv6/mcast.c:inet6_mc_check
```
```
In net/ipv6/ip6mr.c (ffffffff81b77de9)
Location: include/asm-generic/atomic-instrumented.h:178
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ed7c)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks
```
```
In kernel/fork.c (ffffffff810a36ad)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - kernel/fork.c:walk_process_tree
```
```
In kernel/exit.c (ffffffff810a8c84)
Location: include/asm-generic/atomic-instrumented.h:178
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
Location: include/asm-generic/atomic-instrumented.h:178
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
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff810b7a25)
Location: include/asm-generic/atomic-instrumented.h:178
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
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
```
```
In kernel/sched/core.c (ffffffff810e4574)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:uclamp_sync_util_min_rt_default
```
```
In kernel/locking/spinlock.c (ffffffff81c45811)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
```
```
In kernel/power/process.c (ffffffff811104be)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/livepatch/transition.c (ffffffff81137439)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_send_signals
  - kernel/livepatch/transition.c:klp_complete_transition
```
```
In kernel/pid_namespace.c (ffffffff811825cf)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tracepoint.c (ffffffff811a955b)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f3d74)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In mm/mempolicy.c (ffffffff812dbe98)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
```
```
In mm/memory-failure.c (ffffffff8130cf34)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs_file
  - mm/memory-failure.c:collect_procs_anon
```
```
In mm/zsmalloc.c (ffffffff813127fe)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/exec.c (ffffffff81327bba)
Location: include/asm-generic/atomic-instrumented.h:178
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
Location: include/asm-generic/atomic-instrumented.h:178
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
Location: include/asm-generic/atomic-instrumented.h:178
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
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/generic.c (ffffffff813d241a)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff813d3dda)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/ext4/extents_status.c (ffffffff813fac7c)
Location: include/asm-generic/atomic-instrumented.h:178
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
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff8143ea2c)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/jbd2/transaction.c (ffffffff8145b983)
Location: include/asm-generic/atomic-instrumented.h:178
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
Location: include/asm-generic/atomic-instrumented.h:178
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
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/hooks.c (ffffffff814d38dd)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/integrity/iint.c (ffffffff81530e8a)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In drivers/xen/events/events_base.c (ffffffff8173297a)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__xen_evtchn_do_upcall
```
```
In drivers/tty/tty_io.c (ffffffff81752708)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8175d0fe)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tiocsctty
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/sysrq.c (ffffffff8175f5de)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/scsi/sg.c (ffffffff8185e0f7)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_debug_helper
```
```
In net/core/neighbour.c (ffffffff81a1238e)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_for_each
```
```
In net/core/net-sysfs.c (ffffffff81a3b040)
Location: include/asm-generic/atomic-instrumented.h:178
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
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffffffff81a74a7f)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffffffff81a7b704)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (ffffffff81a7eade)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_lookup
  - net/sched/ematch.c:tcf_em_lookup
```
```
In net/netlink/af_netlink.c (ffffffff81a7ffa4)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/ipv4/raw.c (ffffffff81adc549)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/arp.c (ffffffff81ae608c)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_format_neigh_entry
```
```
In net/ipv4/ipmr.c (ffffffff81b0fa15)
Location: include/asm-generic/atomic-instrumented.h:178
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
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1f81b)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/ipv6/ip6_output.c (ffffffff81b3b9e5)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_call_ra_chain
  - net/ipv6/ip6_output.c:ip6_call_ra_chain
```
```
In net/ipv6/route.c (ffffffff81b50638)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffffffff81b5bef5)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81b6bc8a)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/mcast.c (ffffffff81b72243)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - net/ipv6/mcast.c:inet6_mc_check
```
```
In net/ipv6/ip6mr.c (ffffffff81b86d69)
Location: include/asm-generic/atomic-instrumented.h:178
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
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ec67)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks
```
```
In kernel/fork.c (ffffffff810a42dd)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - kernel/fork.c:walk_process_tree
```
```
In kernel/exit.c (ffffffff810a9c2d)
Location: include/asm-generic/atomic-instrumented.h:178
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
Location: include/asm-generic/atomic-instrumented.h:178
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
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff810b8f85)
Location: include/asm-generic/atomic-instrumented.h:178
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
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
```
```
In kernel/sched/core.c (ffffffff810e6524)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
```
```
In kernel/locking/spinlock.c (ffffffff81c38ac5)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
```
```
In kernel/power/process.c (ffffffff81110efe)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/livepatch/transition.c (ffffffff811381e9)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
```
```
In kernel/pid_namespace.c (ffffffff8118371f)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tracepoint.c (ffffffff811aa10b)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f4a24)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In mm/mempolicy.c (ffffffff812e3708)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
```
```
In mm/memory-failure.c (ffffffff813135ae)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
```
```
In mm/zsmalloc.c (ffffffff81318d1e)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/exec.c (ffffffff8132daea)
Location: include/asm-generic/atomic-instrumented.h:178
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
Location: include/asm-generic/atomic-instrumented.h:178
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
Location: include/asm-generic/atomic-instrumented.h:178
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
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/generic.c (ffffffff813d921c)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff813dac0a)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/ext4/extents_status.c (ffffffff814010df)
Location: include/asm-generic/atomic-instrumented.h:178
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
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/mballoc.c (ffffffff8141c4ed)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_seq_structs_summary_stop
```
```
In fs/ext4/super.c (ffffffff8144462c)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/jbd2/transaction.c (ffffffff814612c3)
Location: include/asm-generic/atomic-instrumented.h:178
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
Location: include/asm-generic/atomic-instrumented.h:178
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
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/hooks.c (ffffffff814da35d)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/integrity/iint.c (ffffffff815392ba)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In block/ioprio.c (ffffffff8157fea4)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - block/ioprio.c:__do_sys_ioprio_set
  - block/ioprio.c:__do_sys_ioprio_set
```
```
In drivers/xen/events/events_base.c (ffffffff8171654a)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__xen_evtchn_do_upcall
```
```
In drivers/tty/tty_io.c (ffffffff81736855)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8174145a)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/sysrq.c (ffffffff8174344e)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/scsi/sg.c (ffffffff81840d60)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_debug_helper
```
```
In net/core/neighbour.c (ffffffff819f8fbe)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_for_each
```
```
In net/core/net-sysfs.c (ffffffff81a225e0)
Location: include/asm-generic/atomic-instrumented.h:178
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
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffffffff81a5d61f)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffffffff81a64494)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (ffffffff81a6793e)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_lookup
  - net/sched/ematch.c:tcf_em_lookup
```
```
In net/netlink/af_netlink.c (ffffffff81a68eb5)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_set_err
```
```
In net/ipv4/raw.c (ffffffff81ac74b9)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/arp.c (ffffffff81ad136c)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_format_neigh_entry
```
```
In net/ipv4/ipmr.c (ffffffff81afd615)
Location: include/asm-generic/atomic-instrumented.h:178
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
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0d6fb)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/ipv6/ip6_output.c (ffffffff81b2d056)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff81b3dd18)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4a0b7)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81b59faa)
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/ip6mr.c (ffffffff81b75a34)
Location: include/asm-generic/atomic-instrumented.h:178
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
Location: include/asm-generic/atomic-instrumented.h:178
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81068374)
Location: include/linux/atomic/atomic-instrumented.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks
```
```
In kernel/fork.c (ffffffff810b5afd)
Location: include/linux/atomic/atomic-instrumented.h:137
Inline: True
Inline callers:
  - kernel/fork.c:walk_process_tree
```
```
In kernel/exit.c (ffffffff810bb75b)
Location: include/linux/atomic/atomic-instrumented.h:137
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
Location: include/linux/atomic/atomic-instrumented.h:137
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
Location: include/linux/atomic/atomic-instrumented.h:137
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff810cb515)
Location: include/linux/atomic/atomic-instrumented.h:137
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
Location: include/linux/atomic/atomic-instrumented.h:137
Inline: True
Inline callers:
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
```
```
In kernel/sched/core.c (ffffffff810fda5b)
Location: include/linux/atomic/atomic-instrumented.h:137
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
```
```
In kernel/sched/core_sched.c (ffffffff8112c695)
Location: include/linux/atomic/atomic-instrumented.h:137
Inline: True
Inline callers:
  - kernel/sched/core_sched.c:sched_core_share_pid
```
```
In kernel/locking/spinlock.c (ffffffff81d573a5)
Location: include/linux/atomic/atomic-instrumented.h:137
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
```
```
In kernel/power/process.c (ffffffff811309ea)
Location: include/linux/atomic/atomic-instrumented.h:137
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/livepatch/transition.c (ffffffff8115af73)
Location: include/linux/atomic/atomic-instrumented.h:137
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
```
```
In kernel/pid_namespace.c (ffffffff811ab7ff)
Location: include/linux/atomic/atomic-instrumented.h:137
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tracepoint.c (ffffffff811d3c7b)
Location: include/linux/atomic/atomic-instrumented.h:137
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/trace_uprobe.c (ffffffff81225dd4)
Location: include/linux/atomic/atomic-instrumented.h:137
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In mm/mempolicy.c (ffffffff8132a928)
Location: include/linux/atomic/atomic-instrumented.h:137
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
```
```
In mm/memory-failure.c (ffffffff8136006e)
Location: include/linux/atomic/atomic-instrumented.h:137
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
```
```
In mm/zsmalloc.c (ffffffff8136530e)
Location: include/linux/atomic/atomic-instrumented.h:137
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/exec.c (ffffffff8137b2ca)
Location: include/linux/atomic/atomic-instrumented.h:137
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
Location: include/linux/atomic/atomic-instrumented.h:137
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
Location: include/linux/atomic/atomic-instrumented.h:137
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
Location: include/linux/atomic/atomic-instrumented.h:137
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/generic.c (ffffffff8142a94c)
Location: include/linux/atomic/atomic-instrumented.h:137
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff8142c3aa)
Location: include/linux/atomic/atomic-instrumented.h:137
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/ext4/extents_status.c (ffffffff8145365c)
Location: include/linux/atomic/atomic-instrumented.h:137
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
Location: include/linux/atomic/atomic-instrumented.h:137
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/mballoc.c (ffffffff8146f8ed)
Location: include/linux/atomic/atomic-instrumented.h:137
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_seq_structs_summary_stop
```
```
In fs/ext4/super.c (ffffffff8149842c)
Location: include/linux/atomic/atomic-instrumented.h:137
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/ext4/fast_commit.c (ffffffff814afbaf)
Location: include/linux/atomic/atomic-instrumented.h:137
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_mark_ineligible
```
```
In fs/jbd2/transaction.c (ffffffff814b67b6)
Location: include/linux/atomic/atomic-instrumented.h:137
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
Location: include/linux/atomic/atomic-instrumented.h:137
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
Location: include/linux/atomic/atomic-instrumented.h:137
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/hooks.c (ffffffff8153325d)
Location: include/linux/atomic/atomic-instrumented.h:137
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/integrity/iint.c (ffffffff81597afa)
Location: include/linux/atomic/atomic-instrumented.h:137
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In block/ioprio.c (ffffffff815e4e17)
Location: include/linux/atomic/atomic-instrumented.h:137
Inline: True
Inline callers:
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
  - block/ioprio.c:__do_sys_ioprio_set
```
```
In drivers/xen/events/events_base.c (ffffffff817937da)
Location: include/linux/atomic/atomic-instrumented.h:137
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__xen_evtchn_do_upcall
```
```
In drivers/tty/tty_io.c (ffffffff817b7215)
Location: include/linux/atomic/atomic-instrumented.h:137
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/tty/tty_jobctrl.c (ffffffff817c1eba)
Location: include/linux/atomic/atomic-instrumented.h:137
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/sysrq.c (ffffffff817c3eee)
Location: include/linux/atomic/atomic-instrumented.h:137
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/scsi/sg.c (ffffffff818cd8bc)
Location: include/linux/atomic/atomic-instrumented.h:137
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_debug_helper
```
```
In net/core/neighbour.c (ffffffff81aaab9e)
Location: include/linux/atomic/atomic-instrumented.h:137
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_for_each
```
```
In net/core/net-sysfs.c (ffffffff81ad65f0)
Location: include/linux/atomic/atomic-instrumented.h:137
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
Location: include/linux/atomic/atomic-instrumented.h:137
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffffffff81b1662f)
Location: include/linux/atomic/atomic-instrumented.h:137
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffffffff81b1d8a4)
Location: include/linux/atomic/atomic-instrumented.h:137
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (ffffffff81b20eae)
Location: include/linux/atomic/atomic-instrumented.h:137
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_lookup
  - net/sched/ematch.c:tcf_em_lookup
```
```
In net/netlink/af_netlink.c (ffffffff81b22485)
Location: include/linux/atomic/atomic-instrumented.h:137
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_set_err
```
```
In net/ipv4/raw.c (ffffffff81b85cd9)
Location: include/linux/atomic/atomic-instrumented.h:137
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/arp.c (ffffffff81b8fe07)
Location: include/linux/atomic/atomic-instrumented.h:137
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_format_neigh_entry
```
```
In net/ipv4/ipmr.c (ffffffff81bbee75)
Location: include/linux/atomic/atomic-instrumented.h:137
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
Location: include/linux/atomic/atomic-instrumented.h:137
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd103b)
Location: include/linux/atomic/atomic-instrumented.h:137
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/ipv6/ip6_output.c (ffffffff81bf321a)
Location: include/linux/atomic/atomic-instrumented.h:137
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff81c04849)
Location: include/linux/atomic/atomic-instrumented.h:137
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffffffff81c11417)
Location: include/linux/atomic/atomic-instrumented.h:137
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81c2161c)
Location: include/linux/atomic/atomic-instrumented.h:137
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/ip6mr.c (ffffffff81c40456)
Location: include/linux/atomic/atomic-instrumented.h:137
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
Location: include/linux/atomic/atomic-instrumented.h:137
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81f29d05)
Location: include/linux/atomic/atomic-instrumented.h:143
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_irq
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
  - kernel/locking/spinlock.c:_raw_read_unlock
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff820d5c25)
Location: include/linux/atomic/atomic-instrumented.h:143
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_irq
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
  - kernel/locking/spinlock.c:_raw_read_unlock
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff82159005)
Location: include/linux/atomic/atomic-instrumented.h:323
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_irq
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
  - kernel/locking/spinlock.c:_raw_read_unlock
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
In kernel/locking/spinlock.c (ffffffff8223c885)
Location: include/linux/atomic/atomic-instrumented.h:323
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_irq
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
  - kernel/locking/spinlock.c:_raw_read_unlock
```
```
In lib/closure.c (ffffffff8223beb9)
Location: include/linux/atomic/atomic-instrumented.h:323
Inline: True
Inline callers:
  - lib/closure.c:__closure_sync
  - lib/closure.c:__closure_wake_up
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
In arch/arm/xen/p2m.c (ffff8000100f04c8)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - arch/arm/xen/p2m.c:__pfn_to_mfn
  - arch/arm/xen/p2m.c:__pfn_to_mfn
```
```
In kernel/fork.c (ffff8000100f5520)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - kernel/fork.c:walk_process_tree
```
```
In kernel/exit.c (ffff8000100fbaec)
Location: include/asm-generic/atomic-instrumented.h:177
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
In kernel/resource.c (ffff800010101f00)
Location: include/asm-generic/atomic-instrumented.h:177
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
In kernel/ptrace.c (ffff800010107b88)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffff800010110270)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - kernel/signal.c:__arm64_sys_kill
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:kill_pgrp
```
```
In kernel/sys.c (ffff800010118de0)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:__arm64_sys_getpriority
  - kernel/sys.c:__arm64_sys_setpriority
```
```
In kernel/sched/core.c (ffff80001013daf4)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
```
```
In kernel/sched/rt.c (ffff800010151cc0)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:tg_set_rt_bandwidth
```
```
In kernel/power/process.c (ffff800010170264)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/cgroup/cgroup.c (ffff8000101d475c)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_enable_task_cg_lists
```
```
In kernel/pid_namespace.c (ffff8000101e7630)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tracepoint.c (ffff80001020edd0)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/fgraph.c (ffff800010238760)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
```
In kernel/trace/trace_uprobe.c (ffff800010259420)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In mm/mempolicy.c (ffff80001033b668)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
```
```
In mm/memory-failure.c (ffff80001036ebc4)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
```
```
In mm/zsmalloc.c (ffff800010375708)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/exec.c (ffff80001038e948)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:__arm64_sys_uselib
  - fs/exec.c:__arm64_sys_uselib
```
```
In fs/fcntl.c (ffff80001039ce8c)
Location: include/asm-generic/atomic-instrumented.h:177
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
In fs/filesystems.c (ffff8000103b307c)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:filesystems_proc_show
  - fs/filesystems.c:__arm64_sys_sysfs
  - fs/filesystems.c:__arm64_sys_sysfs
  - fs/filesystems.c:fs_name
  - fs/filesystems.c:get_filesystem_list
```
```
In fs/fs_struct.c (ffff8000103d2888)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/eventpoll.c (ffff8000103f151c)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll_callback
```
```
In fs/proc/generic.c (ffff800010443404)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/proc/array.c (ffff800010444b34)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/ext4/extents_status.c (ffff800010470558)
Location: include/asm-generic/atomic-instrumented.h:177
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
In fs/ext4/inode.c (ffff80001048901c)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffff8000104b8118)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/jbd2/transaction.c (ffff8000104ccc20)
Location: include/asm-generic/atomic-instrumented.h:177
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
In fs/jbd2/journal.c (ffff8000104d4360)
Location: include/asm-generic/atomic-instrumented.h:177
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
In security/keys/keyring.c (ffff800010530f28)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/hooks.c (ffff800010554074)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/selinux/ss/services.c (ffff8000105688bc)
Location: include/asm-generic/atomic-instrumented.h:177
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
In security/apparmor/label.c (ffff8000105a2ae8)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:vec_find
```
```
In security/integrity/iint.c (ffff8000105ac6e0)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In drivers/tty/tty_io.c (ffff800010851ab0)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/tty/tty_jobctrl.c (ffff800010860c84)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/sysrq.c (ffff800010864240)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/iommu/arm-smmu-v3.c (ffff8000108d53c4)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_cmdq_issue_cmdlist
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_cmdq_issue_cmdlist
```
```
In drivers/scsi/sg.c (ffff8000109912a0)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:dev_seq_start
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/net/ppp/ppp_generic.c (ffff8000109fe9c4)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_name
  - drivers/net/ppp/ppp_generic.c:ppp_unit_number
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
```
```
In drivers/cpufreq/cpufreq.c (ffff800010b203ec)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
```
```
In drivers/leds/led-triggers.c (ffff800010b4a21c)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
```
In net/core/sock.c (ffff800010bab8f0)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - net/core/sock.c:sock_i_ino
  - net/core/sock.c:sock_i_uid
```
```
In net/core/skbuff.c (ffff800010bb3788)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
```
```
In net/core/neighbour.c (ffff800010be2eac)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:pneigh_lookup
```
```
In net/core/net-sysfs.c (ffff800010c0af38)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:address_show
```
```
In net/core/netpoll.c (ffff800010c11930)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/sched/sch_api.c (ffff800010c3ce68)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffff800010c416e8)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffff800010c47128)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (ffff800010c4a118)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
```
```
In net/netlink/af_netlink.c (ffff800010c4dbb8)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/ipv4/raw.c (ffff800010c96c4c)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/arp.c (ffff800010ca18d8)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
  - net/ipv4/arp.c:arp_ioctl
```
```
In net/ipv4/ping.c (ffff800010cc0aa8)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_seq_stop
  - net/ipv4/ping.c:ping_lookup
```
```
In net/ipv4/ipmr.c (ffff800010cc9a28)
Location: include/asm-generic/atomic-instrumented.h:177
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
In net/ipv4/ipmr_base.c (ffff800010cd0d24)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffff800010cdc380)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/ipv6/anycast.c (ffff800010cf70a4)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_seq_stop
  - net/ipv6/anycast.c:ac6_seq_start
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffff800010cfb664)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/addrconf.c (ffff800010d00840)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:addrconf_dad_run
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:ipv6_get_lladdr
```
```
In net/ipv6/route.c (ffff800010d11d68)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffff800010d1bbc8)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
```
In net/ipv6/ndisc.c (ffff800010d23128)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
```
```
In net/ipv6/raw.c (ffff800010d2a898)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/mcast.c (ffff800010d2e768)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_stop
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_stop
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:ipv6_mc_up
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_unmap
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
```
```
In net/ipv6/ip6mr.c (ffff800010d480c8)
Location: include/asm-generic/atomic-instrumented.h:177
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

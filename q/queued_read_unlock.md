# Function: <code>queued_read_unlock</code>

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
In kernel/cpu.c (ffffffff81081787)
Location: include/asm-generic/qrwlock.h:128
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_down
```
```
In kernel/exit.c (ffffffff81082b8e)
Location: include/asm-generic/qrwlock.h:128
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
Location: include/asm-generic/qrwlock.h:128
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
Location: include/asm-generic/qrwlock.h:128
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff8108ebbc)
Location: include/asm-generic/qrwlock.h:128
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
Location: include/asm-generic/qrwlock.h:128
Inline: True
Inline callers:
  - kernel/sys.c:SyS_setpriority
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:do_prlimit
```
```
In kernel/sched/core.c (ffffffff810b030d)
Location: include/asm-generic/qrwlock.h:128
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
```
```
In kernel/locking/spinlock.c (ffffffff81823f66)
Location: include/asm-generic/qrwlock.h:128
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
```
```
In kernel/power/process.c (ffffffff810cd9a0)
Location: include/asm-generic/qrwlock.h:128
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_kernel_threads
```
```
In kernel/cgroup.c (ffffffff8111841c)
Location: include/asm-generic/qrwlock.h:128
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_mount
```
```
In kernel/pid_namespace.c (ffffffff8111fce6)
Location: include/asm-generic/qrwlock.h:128
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/pid_namespace.c:reboot_pid_ns
```
```
In kernel/tracepoint.c (ffffffff8113fc9b)
Location: include/asm-generic/qrwlock.h:128
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_regfunc
  - kernel/tracepoint.c:syscall_unregfunc
```
```
In kernel/trace/trace_uprobe.c (ffffffff8116f1d7)
Location: include/asm-generic/qrwlock.h:128
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In mm/oom_kill.c (ffffffff81190d5a)
Location: include/asm-generic/qrwlock.h:128
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/memory-failure.c (ffffffff81202dd3)
Location: include/asm-generic/qrwlock.h:128
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In fs/exec.c (ffffffff81212b90)
Location: include/asm-generic/qrwlock.h:128
Inline: True
Inline callers:
  - fs/exec.c:SyS_uselib
  - fs/exec.c:SyS_uselib
```
```
In fs/fcntl.c (ffffffff8121ee00)
Location: include/asm-generic/qrwlock.h:128
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
In fs/filesystems.c (ffffffff8122b19e)
Location: include/asm-generic/qrwlock.h:128
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
Location: include/asm-generic/qrwlock.h:128
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/base.c (ffffffff8127a665)
Location: include/asm-generic/qrwlock.h:128
Inline: True
Inline callers:
  - fs/proc/base.c:proc_oom_score
```
```
In fs/proc/generic.c (ffffffff8127eeab)
Location: include/asm-generic/qrwlock.h:128
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff812808b5)
Location: include/asm-generic/qrwlock.h:128
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/proc/kcore.c (ffffffff812871d4)
Location: include/asm-generic/qrwlock.h:128
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
```
```
In fs/ext4/inode.c (ffffffff8129a04d)
Location: include/asm-generic/qrwlock.h:128
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/super.c (ffffffff812aca89)
Location: include/asm-generic/qrwlock.h:128
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/ext4/extents_status.c (ffffffff812dbbce)
Location: include/asm-generic/qrwlock.h:128
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_find_delayed_extent_range
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
```
```
In fs/jbd2/transaction.c (ffffffff812e6b64)
Location: include/asm-generic/qrwlock.h:128
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:wait_transaction_locked
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
```
```
In fs/jbd2/journal.c (ffffffff812edffe)
Location: include/asm-generic/qrwlock.h:128
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
In security/keys/keyring.c (ffffffff813318fe)
Location: include/asm-generic/qrwlock.h:128
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/hooks.c (ffffffff81345316)
Location: include/asm-generic/qrwlock.h:128
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/selinux/ss/services.c (ffffffff81355526)
Location: include/asm-generic/qrwlock.h:128
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
In security/integrity/iint.c (ffffffff813962af)
Location: include/asm-generic/qrwlock.h:128
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In drivers/tty/tty_io.c (ffffffff814e158d)
Location: include/asm-generic/qrwlock.h:128
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__tty_hangup
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:tty_open
```
```
In drivers/tty/sysrq.c (ffffffff814ed982)
Location: include/asm-generic/qrwlock.h:128
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/scsi/sg.c (ffffffff815c363e)
Location: include/asm-generic/qrwlock.h:128
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
```
```
In drivers/leds/led-triggers.c (ffffffff816ce496)
Location: include/asm-generic/qrwlock.h:128
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_event
  - drivers/leds/led-triggers.c:led_trigger_blink_setup
```
```
In net/core/gen_estimator.c (ffffffff8170f4f0)
Location: include/asm-generic/qrwlock.h:128
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/neighbour.c (ffffffff817244c7)
Location: include/asm-generic/qrwlock.h:128
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_for_each
```
```
In net/core/net-sysfs.c (ffffffff8173574a)
Location: include/asm-generic/qrwlock.h:128
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:address_show
```
```
In net/sched/sch_api.c (ffffffff81742fa8)
Location: include/asm-generic/qrwlock.h:128
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffffffff81745e2d)
Location: include/asm-generic/qrwlock.h:128
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffffffff8174706d)
Location: include/asm-generic/qrwlock.h:128
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action_n
  - net/sched/act_api.c:tc_lookup_action
```
```
In net/sched/ematch.c (ffffffff8174998f)
Location: include/asm-generic/qrwlock.h:128
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff8174a2b0)
Location: include/asm-generic/qrwlock.h:128
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
```
```
In net/ipv4/raw.c (ffffffff81784300)
Location: include/asm-generic/qrwlock.h:128
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/arp.c (ffffffff8178c08b)
Location: include/asm-generic/qrwlock.h:128
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
```
```
In net/ipv4/ipmr.c (ffffffff817a70d6)
Location: include/asm-generic/qrwlock.h:128
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
Location: include/asm-generic/qrwlock.h:128
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/ipv6/ip6_output.c (ffffffff817c701f)
Location: include/asm-generic/qrwlock.h:128
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff817d4ece)
Location: include/asm-generic/qrwlock.h:128
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffffffff817d9b4f)
Location: include/asm-generic/qrwlock.h:128
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_repair_tree
  - net/ipv6/ip6_fib.c:fib6_del
```
```
In net/ipv6/raw.c (ffffffff817e6b4a)
Location: include/asm-generic/qrwlock.h:128
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/mcast.c (ffffffff817ebbe8)
Location: include/asm-generic/qrwlock.h:128
Inline: True
Inline callers:
  - net/ipv6/mcast.c:inet6_mc_check
```
```
In net/ipv6/ip6mr.c (ffffffff817f7ce6)
Location: include/asm-generic/qrwlock.h:128
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
In kernel/cpu.c (ffffffff81083f95)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - kernel/cpu.c:notify_dead
```
```
In kernel/exit.c (ffffffff81086636)
Location: include/asm-generic/qrwlock.h:141
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
Location: include/asm-generic/qrwlock.h:141
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
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff81092a58)
Location: include/asm-generic/qrwlock.h:141
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
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_setpriority
```
```
In kernel/sched/core.c (ffffffff810b2f3f)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
```
```
In kernel/locking/spinlock.c (ffffffff8189ec16)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
```
```
In kernel/power/process.c (ffffffff810d2aaf)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/cgroup.c (ffffffff8111fea2)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_mount
```
```
In kernel/pid_namespace.c (ffffffff81127d6b)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tracepoint.c (ffffffff811483a2)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/ftrace.c (ffffffff8114e70c)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:register_ftrace_graph
```
```
In kernel/trace/trace_uprobe.c (ffffffff8117c897)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In mm/oom_kill.c (ffffffff811a555f)
Location: include/asm-generic/qrwlock.h:141
Inline: True
```
```
In mm/mempolicy.c (ffffffff812015f6)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
```
```
In mm/memory-failure.c (ffffffff81227484)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/zsmalloc.c (ffffffff8122bc56)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/exec.c (ffffffff8123a995)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - fs/exec.c:SyS_uselib
  - fs/exec.c:SyS_uselib
```
```
In fs/fcntl.c (ffffffff81246eb8)
Location: include/asm-generic/qrwlock.h:141
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
In fs/filesystems.c (ffffffff812538fe)
Location: include/asm-generic/qrwlock.h:141
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
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/generic.c (ffffffff812abefb)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff812ad915)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/proc/kcore.c (ffffffff812b455e)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
```
```
In fs/ext4/inode.c (ffffffff812cd194)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_iget
```
```
In fs/ext4/super.c (ffffffff812e13b9)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/ext4/extents_status.c (ffffffff8130ba2b)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_find_delayed_extent_range
```
```
In fs/jbd2/transaction.c (ffffffff81317302)
Location: include/asm-generic/qrwlock.h:141
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
In fs/jbd2/journal.c (ffffffff8131b96e)
Location: include/asm-generic/qrwlock.h:141
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
In security/keys/keyring.c (ffffffff813666a5)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/hooks.c (ffffffff8137abb6)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/selinux/ss/services.c (ffffffff81390984)
Location: include/asm-generic/qrwlock.h:141
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
In security/integrity/iint.c (ffffffff813d201f)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In drivers/tty/tty_io.c (ffffffff81534a4d)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:__tty_hangup
```
```
In drivers/tty/sysrq.c (ffffffff8153e5f2)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/scsi/sg.c (ffffffff8161be5d)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
```
```
In drivers/leds/led-triggers.c (ffffffff81731aca)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_setup
  - drivers/leds/led-triggers.c:led_trigger_event
```
```
In net/core/gen_estimator.c (ffffffff81776d6a)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/neighbour.c (ffffffff8178de97)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_for_each
```
```
In net/core/net-sysfs.c (ffffffff817a189a)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:address_show
```
```
In net/sched/sch_api.c (ffffffff817afe45)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffffffff817b2d6d)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffffffff817b433d)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (ffffffff817b68fe)
Location: include/asm-generic/qrwlock.h:141
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff817b7aee)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/ipv4/raw.c (ffffffff817f18c0)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/arp.c (ffffffff817f96be)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
```
```
In net/ipv4/ipmr.c (ffffffff81814db6)
Location: include/asm-generic/qrwlock.h:141
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
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/ipv6/ip6_output.c (ffffffff818340dd)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff81843142)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffffffff81847caf)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_repair_tree
```
```
In net/ipv6/raw.c (ffffffff81854ee6)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/mcast.c (ffffffff8185a449)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - net/ipv6/mcast.c:inet6_mc_check
```
```
In net/ipv6/ip6mr.c (ffffffff81868d11)
Location: include/asm-generic/qrwlock.h:141
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
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81043c9c)
Location: include/asm-generic/qrwlock.h:141
Inline: True
```
```
In kernel/exit.c (ffffffff8108b5a7)
Location: include/asm-generic/qrwlock.h:141
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
Location: include/asm-generic/qrwlock.h:141
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
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff810979e8)
Location: include/asm-generic/qrwlock.h:141
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
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_setpriority
```
```
In kernel/sched/core.c (ffffffff810b9527)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
```
```
In kernel/locking/spinlock.c (ffffffff818d40d6)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
```
```
In kernel/power/process.c (ffffffff810d963f)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/cgroup.c (ffffffff811282f7)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_mount
```
```
In kernel/pid_namespace.c (ffffffff811319fb)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tracepoint.c (ffffffff8115225e)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/ftrace.c (ffffffff8115864e)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:register_ftrace_graph
```
```
In kernel/trace/trace_uprobe.c (ffffffff811884a7)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In mm/oom_kill.c (ffffffff811b56b9)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/mempolicy.c (ffffffff812130e6)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
```
```
In mm/memory-failure.c (ffffffff81239a3f)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/zsmalloc.c (ffffffff8123e1b2)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/exec.c (ffffffff8124d775)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - fs/exec.c:SyS_uselib
  - fs/exec.c:SyS_uselib
```
```
In fs/fcntl.c (ffffffff81259ea8)
Location: include/asm-generic/qrwlock.h:141
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
In fs/filesystems.c (ffffffff81266b4e)
Location: include/asm-generic/qrwlock.h:141
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
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/generic.c (ffffffff812c17cc)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff812c3205)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/proc/kcore.c (ffffffff812c9dee)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
```
```
In fs/ext4/inode.c (ffffffff812e2f10)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_iget
```
```
In fs/ext4/super.c (ffffffff812f6ee9)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/ext4/extents_status.c (ffffffff81321a2b)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_find_delayed_extent_range
```
```
In fs/jbd2/transaction.c (ffffffff8132d2f2)
Location: include/asm-generic/qrwlock.h:141
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
In fs/jbd2/journal.c (ffffffff8133195e)
Location: include/asm-generic/qrwlock.h:141
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
In security/keys/keyring.c (ffffffff8137cec5)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/hooks.c (ffffffff81391006)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/selinux/ss/services.c (ffffffff813a75a4)
Location: include/asm-generic/qrwlock.h:141
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
In security/integrity/iint.c (ffffffff813e973f)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In drivers/tty/tty_io.c (ffffffff8156117d)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:__tty_hangup
```
```
In drivers/tty/sysrq.c (ffffffff8156ac42)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/scsi/sg.c (ffffffff8164caae)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
```
```
In drivers/leds/led-triggers.c (ffffffff81764a9a)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_setup
  - drivers/leds/led-triggers.c:led_trigger_event
```
```
In net/core/neighbour.c (ffffffff817bb847)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_for_each
```
```
In net/core/net-sysfs.c (ffffffff817d01ba)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:address_show
```
```
In net/sched/sch_api.c (ffffffff817df535)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffffffff817e25ed)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffffffff817e3bed)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (ffffffff817e638e)
Location: include/asm-generic/qrwlock.h:141
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff817e755e)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/ipv4/raw.c (ffffffff8182263d)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/arp.c (ffffffff8182a58b)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
```
```
In net/ipv4/ipmr.c (ffffffff81846576)
Location: include/asm-generic/qrwlock.h:141
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
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/ipv6/ip6_output.c (ffffffff81865b3d)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff81874eb2)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffffffff81879aec)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_repair_tree
```
```
In net/ipv6/raw.c (ffffffff81886c56)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/mcast.c (ffffffff8188c399)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - net/ipv6/mcast.c:inet6_mc_check
```
```
In net/ipv6/ip6mr.c (ffffffff8189bb61)
Location: include/asm-generic/qrwlock.h:141
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
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81042494)
Location: include/asm-generic/qrwlock.h:141
Inline: True
```
```
In kernel/fork.c (ffffffff81083c5d)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - kernel/fork.c:walk_process_tree
```
```
In kernel/exit.c (ffffffff81088327)
Location: include/asm-generic/qrwlock.h:141
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
Location: include/asm-generic/qrwlock.h:141
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
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff81094cdb)
Location: include/asm-generic/qrwlock.h:141
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
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_setpriority
```
```
In kernel/sched/core.c (ffffffff810b4104)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
```
```
In kernel/locking/spinlock.c (ffffffff8190b266)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
```
```
In kernel/power/process.c (ffffffff810d861f)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/livepatch/transition.c (ffffffff810f9344)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
```
```
In kernel/cgroup/cgroup.c (ffffffff811258e8)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_mount
```
```
In kernel/pid_namespace.c (ffffffff811327b1)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tracepoint.c (ffffffff8115483e)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/ftrace.c (ffffffff8115b958)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:register_ftrace_graph
```
```
In kernel/trace/trace_uprobe.c (ffffffff8118b3f7)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In mm/oom_kill.c (ffffffff811bd3d6)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/mempolicy.c (ffffffff8121e418)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
```
```
In mm/memory-failure.c (ffffffff81244ec0)
Location: include/asm-generic/qrwlock.h:141
Inline: True
```
```
In mm/zsmalloc.c (ffffffff81249b51)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/exec.c (ffffffff81259736)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - fs/exec.c:SyS_uselib
  - fs/exec.c:SyS_uselib
```
```
In fs/fcntl.c (ffffffff81266892)
Location: include/asm-generic/qrwlock.h:141
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
In fs/filesystems.c (ffffffff812743ce)
Location: include/asm-generic/qrwlock.h:141
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
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/generic.c (ffffffff812cec9c)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff812d0485)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/proc/kcore.c (ffffffff812d72c7)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
```
```
In fs/ext4/extents_status.c (ffffffff812f08c4)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_find_delayed_extent_range
```
```
In fs/ext4/inode.c (ffffffff81307433)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_iget
```
```
In fs/ext4/super.c (ffffffff8132b7c8)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/jbd2/transaction.c (ffffffff813424c2)
Location: include/asm-generic/qrwlock.h:141
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
In fs/jbd2/journal.c (ffffffff8134684e)
Location: include/asm-generic/qrwlock.h:141
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
In security/keys/keyring.c (ffffffff81390c59)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/hooks.c (ffffffff813a7767)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/selinux/ss/services.c (ffffffff813bdf7f)
Location: include/asm-generic/qrwlock.h:141
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
In security/integrity/iint.c (ffffffff813f5b3a)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In drivers/tty/tty_io.c (ffffffff815734b3)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8157d788)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/sysrq.c (ffffffff8157f272)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/scsi/sg.c (ffffffff81661263)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
```
```
In drivers/leds/led-triggers.c (ffffffff8178345b)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
```
In net/core/neighbour.c (ffffffff817d9fd6)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_for_each
```
```
In net/core/net-sysfs.c (ffffffff817ef8e8)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:address_show
```
```
In net/sched/sch_api.c (ffffffff817fe985)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffffffff81801e5d)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffffffff8180353d)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (ffffffff81805e2e)
Location: include/asm-generic/qrwlock.h:141
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff818071f3)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/ipv4/raw.c (ffffffff8184328d)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/arp.c (ffffffff8184b7a8)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
```
```
In net/ipv4/ipmr.c (ffffffff81868356)
Location: include/asm-generic/qrwlock.h:141
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
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/ipv6/ip6_output.c (ffffffff8188a2c8)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/addrconf.c (ffffffff8188d290)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
```
```
In net/ipv6/route.c (ffffffff81899cf0)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffffffff8189f54c)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_repair_tree
```
```
In net/ipv6/raw.c (ffffffff818ad0df)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/mcast.c (ffffffff818b2a78)
Location: include/asm-generic/qrwlock.h:141
Inline: True
Inline callers:
  - net/ipv6/mcast.c:inet6_mc_check
```
```
In net/ipv6/ip6mr.c (ffffffff818c1f4f)
Location: include/asm-generic/qrwlock.h:141
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
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81045934)
Location: include/asm-generic/qrwlock.h:110
Inline: True
```
```
In kernel/fork.c (ffffffff8108a54f)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - kernel/fork.c:walk_process_tree
```
```
In kernel/exit.c (ffffffff8108f0a8)
Location: include/asm-generic/qrwlock.h:110
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
Location: include/asm-generic/qrwlock.h:110
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
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff8109bb7d)
Location: include/asm-generic/qrwlock.h:110
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
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_setpriority
```
```
In kernel/sched/core.c (ffffffff810bb3b4)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
```
```
In kernel/locking/spinlock.c (ffffffff81995606)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
```
```
In kernel/power/process.c (ffffffff810e070f)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/livepatch/transition.c (ffffffff81103d79)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
```
```
In kernel/cgroup/cgroup.c (ffffffff81131bb9)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_mount
```
```
In kernel/pid_namespace.c (ffffffff8113f7f4)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tracepoint.c (ffffffff8116105e)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/ftrace.c (ffffffff81168a28)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:register_ftrace_graph
```
```
In kernel/trace/trace_uprobe.c (ffffffff81198ec7)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In mm/oom_kill.c (ffffffff811d1ffb)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/mempolicy.c (ffffffff81239668)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
```
```
In mm/memory-failure.c (ffffffff81264db0)
Location: include/asm-generic/qrwlock.h:110
Inline: True
```
```
In mm/zsmalloc.c (ffffffff81269db1)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/exec.c (ffffffff8127b996)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - fs/exec.c:SyS_uselib
  - fs/exec.c:SyS_uselib
```
```
In fs/fcntl.c (ffffffff81289132)
Location: include/asm-generic/qrwlock.h:110
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
In fs/filesystems.c (ffffffff81296cce)
Location: include/asm-generic/qrwlock.h:110
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
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/generic.c (ffffffff812f349c)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff812f4cc5)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/proc/kcore.c (ffffffff812fba59)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
```
```
In fs/ext4/extents_status.c (ffffffff813153f4)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_find_delayed_extent_range
```
```
In fs/ext4/inode.c (ffffffff8132c01c)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_iget
```
```
In fs/ext4/super.c (ffffffff8134fc28)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/jbd2/transaction.c (ffffffff81366af2)
Location: include/asm-generic/qrwlock.h:110
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
In fs/jbd2/journal.c (ffffffff8136af3e)
Location: include/asm-generic/qrwlock.h:110
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
In security/keys/keyring.c (ffffffff813b6248)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/hooks.c (ffffffff813ccf37)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/selinux/ss/services.c (ffffffff813e411f)
Location: include/asm-generic/qrwlock.h:110
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
In security/integrity/iint.c (ffffffff8141dc2a)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In drivers/tty/tty_io.c (ffffffff815d8f36)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/tty/tty_jobctrl.c (ffffffff815e22ad)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/sysrq.c (ffffffff815e3de2)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/scsi/sg.c (ffffffff816ca3c3)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
```
```
In drivers/leds/led-triggers.c (ffffffff817f981b)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
```
In net/core/neighbour.c (ffffffff81854779)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_for_each
```
```
In net/core/net-sysfs.c (ffffffff8186ae88)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:address_show
```
```
In net/sched/sch_api.c (ffffffff8187c615)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffffffff8187ffed)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffffffff818819bd)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (ffffffff81884b4e)
Location: include/asm-generic/qrwlock.h:110
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81886d19)
Location: include/asm-generic/qrwlock.h:110
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
In net/ipv4/raw.c (ffffffff818c2c4d)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/arp.c (ffffffff818cb458)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
```
```
In net/ipv4/ipmr.c (ffffffff818e8fd9)
Location: include/asm-generic/qrwlock.h:110
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
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/ipv6/ip6_output.c (ffffffff8190b4ca)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff8191b2f0)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffffffff81923ec4)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
```
In net/ipv6/raw.c (ffffffff8192fcf2)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/mcast.c (ffffffff819357d8)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - net/ipv6/mcast.c:inet6_mc_check
```
```
In net/ipv6/ip6mr.c (ffffffff8194588a)
Location: include/asm-generic/qrwlock.h:110
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
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81047fe4)
Location: include/asm-generic/qrwlock.h:110
Inline: True
```
```
In kernel/fork.c (ffffffff8108dddc)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - kernel/fork.c:walk_process_tree
```
```
In kernel/exit.c (ffffffff81092bb6)
Location: include/asm-generic/qrwlock.h:110
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
Location: include/asm-generic/qrwlock.h:110
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
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff8109fbf8)
Location: include/asm-generic/qrwlock.h:110
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
Location: include/asm-generic/qrwlock.h:110
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
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
```
```
In kernel/locking/spinlock.c (ffffffff819f1bc5)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
```
```
In kernel/power/process.c (ffffffff810e8d83)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/livepatch/transition.c (ffffffff8110c57b)
Location: include/asm-generic/qrwlock.h:110
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
In kernel/cgroup/cgroup.c (ffffffff811401c5)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_mount
```
```
In kernel/pid_namespace.c (ffffffff8114e05e)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tracepoint.c (ffffffff8116ffad)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/ftrace.c (ffffffff8117770f)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:register_ftrace_graph
```
```
In kernel/trace/trace_uprobe.c (ffffffff811ae59d)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In mm/oom_kill.c (ffffffff811f3c50)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/mempolicy.c (ffffffff8125cc08)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
```
```
In mm/memory-failure.c (ffffffff81288db6)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
```
```
In mm/zsmalloc.c (ffffffff8128e74d)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/exec.c (ffffffff812a1849)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/exec.c:__x64_sys_uselib
```
```
In fs/fcntl.c (ffffffff812af39a)
Location: include/asm-generic/qrwlock.h:110
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
Location: include/asm-generic/qrwlock.h:110
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
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/generic.c (ffffffff813202fa)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/proc/array.c (ffffffff81321225)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/proc/kcore.c (ffffffff81328f5f)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
```
```
In fs/ext4/extents_status.c (ffffffff81343205)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_find_delayed_extent_range
```
```
In fs/ext4/inode.c (ffffffff8135a624)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_iget
```
```
In fs/ext4/super.c (ffffffff8137de38)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/jbd2/transaction.c (ffffffff813951e2)
Location: include/asm-generic/qrwlock.h:110
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
Location: include/asm-generic/qrwlock.h:110
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
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/hooks.c (ffffffff813fad7e)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/selinux/ss/services.c (ffffffff8141496f)
Location: include/asm-generic/qrwlock.h:110
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
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In drivers/tty/tty_io.c (ffffffff81611691)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8161b55b)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/sysrq.c (ffffffff8161d092)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/scsi/sg.c (ffffffff81706c51)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
```
```
In drivers/leds/led-triggers.c (ffffffff81842e2a)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
```
In net/core/neighbour.c (ffffffff8189fed9)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_for_each
```
```
In net/core/net-sysfs.c (ffffffff818bb758)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:address_show
```
```
In net/sched/sch_api.c (ffffffff818cee9a)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffffffff818d2b4f)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffffffff818d548f)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (ffffffff818d86ae)
Location: include/asm-generic/qrwlock.h:110
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff818da732)
Location: include/asm-generic/qrwlock.h:110
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
In net/ipv4/raw.c (ffffffff81918e16)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/arp.c (ffffffff819219b7)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
```
```
In net/ipv4/ipmr.c (ffffffff8193ed55)
Location: include/asm-generic/qrwlock.h:110
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
Location: include/asm-generic/qrwlock.h:110
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194dd48)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/ipv6/ip6_output.c (ffffffff81962953)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff81972ff2)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffffffff8197c24e)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
```
In net/ipv6/raw.c (ffffffff81988a39)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/mcast.c (ffffffff8198e942)
Location: include/asm-generic/qrwlock.h:110
Inline: True
Inline callers:
  - net/ipv6/mcast.c:inet6_mc_check
```
```
In net/ipv6/ip6mr.c (ffffffff819a0ada)
Location: include/asm-generic/qrwlock.h:110
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
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81057b54)
Location: include/asm-generic/qrwlock.h:111
Inline: True
```
```
In kernel/fork.c (ffffffff8109606c)
Location: include/asm-generic/qrwlock.h:111
Inline: True
Inline callers:
  - kernel/fork.c:walk_process_tree
```
```
In kernel/exit.c (ffffffff8109aea6)
Location: include/asm-generic/qrwlock.h:111
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
Location: include/asm-generic/qrwlock.h:111
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
Location: include/asm-generic/qrwlock.h:111
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff810a92dd)
Location: include/asm-generic/qrwlock.h:111
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
Location: include/asm-generic/qrwlock.h:111
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
Location: include/asm-generic/qrwlock.h:111
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
```
```
In kernel/locking/spinlock.c (ffffffff81a2d185)
Location: include/asm-generic/qrwlock.h:111
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
```
```
In kernel/power/process.c (ffffffff810f4382)
Location: include/asm-generic/qrwlock.h:111
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/livepatch/transition.c (ffffffff81117d6b)
Location: include/asm-generic/qrwlock.h:111
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
In kernel/cgroup/cgroup.c (ffffffff8114bc35)
Location: include/asm-generic/qrwlock.h:111
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_mount
```
```
In kernel/pid_namespace.c (ffffffff8115adf9)
Location: include/asm-generic/qrwlock.h:111
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tracepoint.c (ffffffff8117db5d)
Location: include/asm-generic/qrwlock.h:111
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/fgraph.c (ffffffff811a0a80)
Location: include/asm-generic/qrwlock.h:111
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:register_ftrace_graph
```
```
In kernel/trace/trace_uprobe.c (ffffffff811bc93d)
Location: include/asm-generic/qrwlock.h:111
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In mm/oom_kill.c (ffffffff81205da6)
Location: include/asm-generic/qrwlock.h:111
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/mempolicy.c (ffffffff812714e8)
Location: include/asm-generic/qrwlock.h:111
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
```
```
In mm/memory-failure.c (ffffffff8129dd06)
Location: include/asm-generic/qrwlock.h:111
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
```
```
In mm/zsmalloc.c (ffffffff812a32bd)
Location: include/asm-generic/qrwlock.h:111
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/exec.c (ffffffff812b69cd)
Location: include/asm-generic/qrwlock.h:111
Inline: True
Inline callers:
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/exec.c:__x64_sys_uselib
```
```
In fs/fcntl.c (ffffffff812c44ca)
Location: include/asm-generic/qrwlock.h:111
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
Location: include/asm-generic/qrwlock.h:111
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
Location: include/asm-generic/qrwlock.h:111
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/generic.c (ffffffff813373da)
Location: include/asm-generic/qrwlock.h:111
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff81338335)
Location: include/asm-generic/qrwlock.h:111
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/ext4/extents_status.c (ffffffff8135b682)
Location: include/asm-generic/qrwlock.h:111
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
Location: include/asm-generic/qrwlock.h:111
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff813966e8)
Location: include/asm-generic/qrwlock.h:111
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/jbd2/transaction.c (ffffffff813adf52)
Location: include/asm-generic/qrwlock.h:111
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
Location: include/asm-generic/qrwlock.h:111
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
Location: include/asm-generic/qrwlock.h:111
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/hooks.c (ffffffff81417365)
Location: include/asm-generic/qrwlock.h:111
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/selinux/ss/services.c (ffffffff81430f4f)
Location: include/asm-generic/qrwlock.h:111
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
Location: include/asm-generic/qrwlock.h:111
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In drivers/tty/tty_io.c (ffffffff8162e401)
Location: include/asm-generic/qrwlock.h:111
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/tty/tty_jobctrl.c (ffffffff816388a6)
Location: include/asm-generic/qrwlock.h:111
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/sysrq.c (ffffffff8163a2f2)
Location: include/asm-generic/qrwlock.h:111
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/scsi/sg.c (ffffffff81729791)
Location: include/asm-generic/qrwlock.h:111
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
```
```
In drivers/leds/led-triggers.c (ffffffff8186eeba)
Location: include/asm-generic/qrwlock.h:111
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
```
In net/core/neighbour.c (ffffffff818c2799)
Location: include/asm-generic/qrwlock.h:111
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_for_each
```
```
In net/core/net-sysfs.c (ffffffff818e24e8)
Location: include/asm-generic/qrwlock.h:111
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:address_show
```
```
In net/sched/sch_api.c (ffffffff818fa19a)
Location: include/asm-generic/qrwlock.h:111
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffffffff818fdfd2)
Location: include/asm-generic/qrwlock.h:111
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffffffff819020cf)
Location: include/asm-generic/qrwlock.h:111
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (ffffffff81904e9e)
Location: include/asm-generic/qrwlock.h:111
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff8190614f)
Location: include/asm-generic/qrwlock.h:111
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
In net/ipv4/raw.c (ffffffff81947706)
Location: include/asm-generic/qrwlock.h:111
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/arp.c (ffffffff819507d7)
Location: include/asm-generic/qrwlock.h:111
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
```
```
In net/ipv4/ipmr.c (ffffffff8196ec05)
Location: include/asm-generic/qrwlock.h:111
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
Location: include/asm-generic/qrwlock.h:111
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197f909)
Location: include/asm-generic/qrwlock.h:111
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/ipv6/ip6_output.c (ffffffff8199793c)
Location: include/asm-generic/qrwlock.h:111
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff819a8c12)
Location: include/asm-generic/qrwlock.h:111
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffffffff819b1f2e)
Location: include/asm-generic/qrwlock.h:111
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
```
In net/ipv6/raw.c (ffffffff819bf3a1)
Location: include/asm-generic/qrwlock.h:111
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/mcast.c (ffffffff819c51f9)
Location: include/asm-generic/qrwlock.h:111
Inline: True
Inline callers:
  - net/ipv6/mcast.c:inet6_mc_check
```
```
In net/ipv6/ip6mr.c (ffffffff819d76da)
Location: include/asm-generic/qrwlock.h:111
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
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105adbb)
Location: include/asm-generic/qrwlock.h:102
Inline: True
```
```
In kernel/fork.c (ffffffff8109a59d)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/fork.c:walk_process_tree
```
```
In kernel/exit.c (ffffffff8109f507)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff810ad66f)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
```
```
In kernel/locking/spinlock.c (ffffffff81a9d265)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
```
```
In kernel/power/process.c (ffffffff810fc8ea)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/livepatch/transition.c (ffffffff811220ac)
Location: include/asm-generic/qrwlock.h:102
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
In kernel/cgroup/cgroup.c (ffffffff8115750b)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/pid_namespace.c (ffffffff811674b7)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tracepoint.c (ffffffff8118aa1b)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/fgraph.c (ffffffff811ae7e2)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cc0cd)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In mm/mempolicy.c (ffffffff8128caf8)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
```
```
In mm/memory-failure.c (ffffffff812b8fdf)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
```
```
In mm/zsmalloc.c (ffffffff812be626)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/exec.c (ffffffff812d4b1f)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/generic.c (ffffffff8135f4fa)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff813609e6)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/ext4/extents_status.c (ffffffff813846a9)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff813c06ec)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/jbd2/transaction.c (ffffffff813d8323)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/hooks.c (ffffffff81444f45)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/selinux/ss/services.c (ffffffff8145e970)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In drivers/tty/tty_io.c (ffffffff81661fd4)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8166cb07)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/sysrq.c (ffffffff8166e62e)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/scsi/sg.c (ffffffff81764adc)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
```
```
In drivers/leds/led-triggers.c (ffffffff818b3170)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
```
In net/core/neighbour.c (ffffffff8190ee95)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_for_each
```
```
In net/core/net-sysfs.c (ffffffff81931da8)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:address_show
```
```
In net/sched/sch_api.c (ffffffff81959a2f)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffffffff8195d967)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffffffff81963264)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (ffffffff8196610e)
Location: include/asm-generic/qrwlock.h:102
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81967434)
Location: include/asm-generic/qrwlock.h:102
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
In net/ipv4/raw.c (ffffffff819abd96)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/arp.c (ffffffff819b5098)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
```
```
In net/ipv4/ipmr.c (ffffffff819d8405)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e9605)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/ipv6/ip6_output.c (ffffffff81a039ec)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff81a14f3b)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffffffff81a20417)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
```
In net/ipv6/raw.c (ffffffff81a2dfdc)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/mcast.c (ffffffff81a34062)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv6/mcast.c:inet6_mc_check
```
```
In net/ipv6/ip6mr.c (ffffffff81a4684f)
Location: include/asm-generic/qrwlock.h:102
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
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b6ab)
Location: include/asm-generic/qrwlock.h:102
Inline: True
```
```
In kernel/fork.c (ffffffff810a0b5d)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/fork.c:walk_process_tree
```
```
In kernel/exit.c (ffffffff810a5a97)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff810b3c8f)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
```
```
In kernel/sched/rt.c (ffffffff810f05cb)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:tg_set_rt_bandwidth
```
```
In kernel/locking/spinlock.c (ffffffff81ad4a45)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
```
```
In kernel/power/process.c (ffffffff81108cdf)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/livepatch/transition.c (ffffffff8112e6cc)
Location: include/asm-generic/qrwlock.h:102
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
In kernel/cgroup/cgroup.c (ffffffff8116310b)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_enable_task_cg_lists
```
```
In kernel/pid_namespace.c (ffffffff81173377)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tracepoint.c (ffffffff8119692b)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/fgraph.c (ffffffff811b9f62)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d8544)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In mm/mempolicy.c (ffffffff8129c728)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
```
```
In mm/memory-failure.c (ffffffff812caecf)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
```
```
In mm/zsmalloc.c (ffffffff812d0516)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/exec.c (ffffffff812e669f)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/generic.c (ffffffff8137775a)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff81378c46)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/ext4/extents_status.c (ffffffff8139d329)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff813d99ac)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/jbd2/transaction.c (ffffffff813f23a3)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/hooks.c (ffffffff8145eab5)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/selinux/ss/services.c (ffffffff81478720)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In drivers/tty/tty_io.c (ffffffff81684644)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8168f177)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/sysrq.c (ffffffff81690c6e)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/scsi/sg.c (ffffffff81788acc)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
```
```
In drivers/leds/led-triggers.c (ffffffff818e5a90)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
```
In net/core/neighbour.c (ffffffff81941505)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_for_each
```
```
In net/core/net-sysfs.c (ffffffff819648e8)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:address_show
```
```
In net/sched/sch_api.c (ffffffff8198fecf)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffffffff81994057)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffffffff81999de4)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (ffffffff8199cb9e)
Location: include/asm-generic/qrwlock.h:102
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff8199dec4)
Location: include/asm-generic/qrwlock.h:102
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
In net/ipv4/raw.c (ffffffff819e2a46)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/arp.c (ffffffff819ebdc8)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
```
```
In net/ipv4/ipmr.c (ffffffff81a0efd5)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a20635)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/ipv6/ip6_output.c (ffffffff81a3a5bc)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff81a4bb2b)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffffffff81a5705b)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
```
In net/ipv6/raw.c (ffffffff81a64b4c)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/mcast.c (ffffffff81a6abb2)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv6/mcast.c:inet6_mc_check
```
```
In net/ipv6/ip6mr.c (ffffffff81a7d43f)
Location: include/asm-generic/qrwlock.h:102
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
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8106051c)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks
```
```
In kernel/fork.c (ffffffff810a79cd)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/fork.c:walk_process_tree
```
```
In kernel/exit.c (ffffffff810ad5b4)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff810bc735)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
```
```
In kernel/sched/core.c (ffffffff810e6674)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
```
```
In kernel/locking/spinlock.c (ffffffff81bccc45)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
```
```
In kernel/power/process.c (ffffffff8111346e)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/livepatch/transition.c (ffffffff8113cd29)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tracepoint.c (ffffffff811abc5b)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/fgraph.c (ffffffff811d29a4)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:alloc_retstack_tasklist
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f53e4)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In mm/mempolicy.c (ffffffff812d0378)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
```
```
In mm/memory-failure.c (ffffffff81300d95)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs_file
  - mm/memory-failure.c:collect_procs_anon
```
```
In mm/zsmalloc.c (ffffffff81306c6e)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/exec.c (ffffffff8131ca2a)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/generic.c (ffffffff813c05ca)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff813c1cba)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/ext4/extents_status.c (ffffffff813e89cc)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff81425d88)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/jbd2/transaction.c (ffffffff8143f723)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/hooks.c (ffffffff814b5bfd)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/selinux/ss/services.c (ffffffff814cdbe9)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In drivers/tty/tty_io.c (ffffffff81736e68)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/tty/tty_jobctrl.c (ffffffff817411ce)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tiocsctty
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/sysrq.c (ffffffff8174375e)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/scsi/sg.c (ffffffff8184dd07)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_debug_helper
```
```
In drivers/leds/led-triggers.c (ffffffff819b8b2d)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
```
In net/core/neighbour.c (ffffffff81a12025)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_for_each
```
```
In net/core/net-sysfs.c (ffffffff81a391b0)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffffffff81a6c1cf)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffffffff81a72b44)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (ffffffff81a75d2e)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_lookup
  - net/sched/ematch.c:tcf_em_lookup
```
```
In net/netlink/af_netlink.c (ffffffff81a77213)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/arp.c (ffffffff81ad962c)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_format_neigh_entry
```
```
In net/ipv4/ipmr.c (ffffffff81b01935)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b12128)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/ipv6/ip6_output.c (ffffffff81b2cfd5)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_call_ra_chain
  - net/ipv6/ip6_output.c:ip6_call_ra_chain
```
```
In net/ipv6/route.c (ffffffff81b41b78)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4d267)
Location: include/asm-generic/qrwlock.h:102
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81b5d49a)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/mcast.c (ffffffff81b63a88)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv6/mcast.c:inet6_mc_check
```
```
In net/ipv6/ip6mr.c (ffffffff81b77de9)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks
```
```
In kernel/fork.c (ffffffff810a36ad)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/fork.c:walk_process_tree
```
```
In kernel/exit.c (ffffffff810a8c84)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff810b7a25)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
```
```
In kernel/sched/core.c (ffffffff810e4574)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:uclamp_sync_util_min_rt_default
```
```
In kernel/locking/spinlock.c (ffffffff81c45811)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
```
```
In kernel/power/process.c (ffffffff811104be)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/livepatch/transition.c (ffffffff81137439)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tracepoint.c (ffffffff811a955b)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f3d74)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In mm/mempolicy.c (ffffffff812dbe98)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
```
```
In mm/memory-failure.c (ffffffff8130cf34)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs_file
  - mm/memory-failure.c:collect_procs_anon
```
```
In mm/zsmalloc.c (ffffffff813127fe)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/exec.c (ffffffff81327bba)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/generic.c (ffffffff813d241a)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff813d3dda)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/ext4/extents_status.c (ffffffff813fac7c)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff8143ea2c)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/jbd2/transaction.c (ffffffff8145b983)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/hooks.c (ffffffff814d38dd)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/integrity/iint.c (ffffffff81530e8a)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In drivers/xen/events/events_base.c (ffffffff8173297a)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__xen_evtchn_do_upcall
```
```
In drivers/tty/tty_io.c (ffffffff81752708)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8175d0fe)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tiocsctty
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/sysrq.c (ffffffff8175f5de)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/scsi/sg.c (ffffffff8185e0f7)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_debug_helper
```
```
In net/core/neighbour.c (ffffffff81a12385)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_for_each
```
```
In net/core/net-sysfs.c (ffffffff81a3b040)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffffffff81a74a7f)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffffffff81a7b704)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (ffffffff81a7eade)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_lookup
  - net/sched/ematch.c:tcf_em_lookup
```
```
In net/netlink/af_netlink.c (ffffffff81a7ffa4)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/arp.c (ffffffff81ae608c)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_format_neigh_entry
```
```
In net/ipv4/ipmr.c (ffffffff81b0fa15)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1f81b)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/ipv6/ip6_output.c (ffffffff81b3b9e5)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_call_ra_chain
  - net/ipv6/ip6_output.c:ip6_call_ra_chain
```
```
In net/ipv6/route.c (ffffffff81b50638)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffffffff81b5bef5)
Location: include/asm-generic/qrwlock.h:102
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81b6bc8a)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/mcast.c (ffffffff81b72243)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv6/mcast.c:inet6_mc_check
```
```
In net/ipv6/ip6mr.c (ffffffff81b86d69)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks
```
```
In kernel/fork.c (ffffffff810a42dd)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - kernel/fork.c:walk_process_tree
```
```
In kernel/exit.c (ffffffff810a9c2d)
Location: include/asm-generic/qrwlock.h:104
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
Location: include/asm-generic/qrwlock.h:104
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
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff810b8f85)
Location: include/asm-generic/qrwlock.h:104
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
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
```
```
In kernel/sched/core.c (ffffffff810e6524)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
```
```
In kernel/locking/spinlock.c (ffffffff81c38ac5)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
```
```
In kernel/power/process.c (ffffffff81110efe)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/livepatch/transition.c (ffffffff811381e9)
Location: include/asm-generic/qrwlock.h:104
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
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tracepoint.c (ffffffff811aa10b)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f4a24)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In mm/mempolicy.c (ffffffff812e3708)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
```
```
In mm/memory-failure.c (ffffffff813135ae)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
```
```
In mm/zsmalloc.c (ffffffff81318d1e)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/exec.c (ffffffff8132daea)
Location: include/asm-generic/qrwlock.h:104
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
Location: include/asm-generic/qrwlock.h:104
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
Location: include/asm-generic/qrwlock.h:104
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
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/generic.c (ffffffff813d921c)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff813dac0a)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/ext4/extents_status.c (ffffffff814010df)
Location: include/asm-generic/qrwlock.h:104
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
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/mballoc.c (ffffffff8141c4e6)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_seq_structs_summary_stop
```
```
In fs/ext4/super.c (ffffffff8144462c)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/jbd2/transaction.c (ffffffff814612c3)
Location: include/asm-generic/qrwlock.h:104
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
Location: include/asm-generic/qrwlock.h:104
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
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/hooks.c (ffffffff814da35d)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/integrity/iint.c (ffffffff815392ba)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In block/ioprio.c (ffffffff8157fea4)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - block/ioprio.c:__do_sys_ioprio_set
  - block/ioprio.c:__do_sys_ioprio_set
```
```
In drivers/xen/events/events_base.c (ffffffff8171654a)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__xen_evtchn_do_upcall
```
```
In drivers/tty/tty_io.c (ffffffff81736855)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8174145a)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/sysrq.c (ffffffff8174344e)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/scsi/sg.c (ffffffff81840d60)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_debug_helper
```
```
In net/core/neighbour.c (ffffffff819f8fb5)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_for_each
```
```
In net/core/net-sysfs.c (ffffffff81a225e0)
Location: include/asm-generic/qrwlock.h:104
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
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffffffff81a5d61f)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffffffff81a64494)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (ffffffff81a6793e)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_lookup
  - net/sched/ematch.c:tcf_em_lookup
```
```
In net/netlink/af_netlink.c (ffffffff81a68eb5)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_set_err
```
```
In net/ipv4/raw.c (ffffffff81ac74b9)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/arp.c (ffffffff81ad136c)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_format_neigh_entry
```
```
In net/ipv4/ipmr.c (ffffffff81afd615)
Location: include/asm-generic/qrwlock.h:104
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
Location: include/asm-generic/qrwlock.h:104
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0d6fb)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/ipv6/ip6_output.c (ffffffff81b2d056)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff81b3dd18)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4a0b7)
Location: include/asm-generic/qrwlock.h:104
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81b59faa)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/ip6mr.c (ffffffff81b75a34)
Location: include/asm-generic/qrwlock.h:104
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
Location: include/asm-generic/qrwlock.h:104
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
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks
```
```
In kernel/fork.c (ffffffff810b5afd)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - kernel/fork.c:walk_process_tree
```
```
In kernel/exit.c (ffffffff810bb75b)
Location: include/asm-generic/qrwlock.h:104
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
Location: include/asm-generic/qrwlock.h:104
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
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff810cb515)
Location: include/asm-generic/qrwlock.h:104
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
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
```
```
In kernel/sched/core.c (ffffffff810fda5b)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
```
```
In kernel/sched/core_sched.c (ffffffff8112c695)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - kernel/sched/core_sched.c:sched_core_share_pid
```
```
In kernel/locking/spinlock.c (ffffffff81d573a5)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
```
```
In kernel/power/process.c (ffffffff811309ea)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/livepatch/transition.c (ffffffff8115af73)
Location: include/asm-generic/qrwlock.h:104
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
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tracepoint.c (ffffffff811d3c7b)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/trace_uprobe.c (ffffffff81225dd4)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In mm/mempolicy.c (ffffffff8132a928)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
```
```
In mm/memory-failure.c (ffffffff8136006e)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
```
```
In mm/zsmalloc.c (ffffffff8136530e)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/exec.c (ffffffff8137b2ca)
Location: include/asm-generic/qrwlock.h:104
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
Location: include/asm-generic/qrwlock.h:104
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
Location: include/asm-generic/qrwlock.h:104
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
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/generic.c (ffffffff8142a94c)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff8142c3aa)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/ext4/extents_status.c (ffffffff8145365c)
Location: include/asm-generic/qrwlock.h:104
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
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/mballoc.c (ffffffff8146f8e6)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_seq_structs_summary_stop
```
```
In fs/ext4/super.c (ffffffff8149842c)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/ext4/fast_commit.c (ffffffff814afbaf)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_mark_ineligible
```
```
In fs/jbd2/transaction.c (ffffffff814b67b6)
Location: include/asm-generic/qrwlock.h:104
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
Location: include/asm-generic/qrwlock.h:104
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
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/hooks.c (ffffffff8153325d)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/integrity/iint.c (ffffffff81597afa)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In block/ioprio.c (ffffffff815e4e17)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
  - block/ioprio.c:__do_sys_ioprio_set
```
```
In drivers/xen/events/events_base.c (ffffffff817937da)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__xen_evtchn_do_upcall
```
```
In drivers/tty/tty_io.c (ffffffff817b7215)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/tty/tty_jobctrl.c (ffffffff817c1eba)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/sysrq.c (ffffffff817c3eee)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/scsi/sg.c (ffffffff818cd8bc)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_debug_helper
```
```
In net/core/neighbour.c (ffffffff81aaab95)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_for_each
```
```
In net/core/net-sysfs.c (ffffffff81ad65f0)
Location: include/asm-generic/qrwlock.h:104
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
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffffffff81b1662f)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffffffff81b1d8a4)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (ffffffff81b20eae)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_lookup
  - net/sched/ematch.c:tcf_em_lookup
```
```
In net/netlink/af_netlink.c (ffffffff81b22485)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_set_err
```
```
In net/ipv4/raw.c (ffffffff81b85cd9)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/arp.c (ffffffff81b8fe07)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_format_neigh_entry
```
```
In net/ipv4/ipmr.c (ffffffff81bbee75)
Location: include/asm-generic/qrwlock.h:104
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
Location: include/asm-generic/qrwlock.h:104
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd103b)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/ipv6/ip6_output.c (ffffffff81bf321a)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff81c04849)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffffffff81c11417)
Location: include/asm-generic/qrwlock.h:104
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81c2161c)
Location: include/asm-generic/qrwlock.h:104
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/ip6mr.c (ffffffff81c40456)
Location: include/asm-generic/qrwlock.h:104
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
Location: include/asm-generic/qrwlock.h:104
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
Location: include/asm-generic/qrwlock.h:108
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
Location: include/asm-generic/qrwlock.h:108
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
Location: include/asm-generic/qrwlock.h:108
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
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff8223c885)
Location: include/asm-generic/qrwlock.h:108
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_irq
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
  - kernel/locking/spinlock.c:_raw_read_unlock
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - arch/arm/xen/p2m.c:__pfn_to_mfn
  - arch/arm/xen/p2m.c:__pfn_to_mfn
```
```
In kernel/fork.c (ffff8000100f5520)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/fork.c:walk_process_tree
```
```
In kernel/exit.c (ffff8000100fbaec)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffff800010110270)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:__arm64_sys_getpriority
  - kernel/sys.c:__arm64_sys_setpriority
```
```
In kernel/sched/core.c (ffff80001013daf4)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
```
```
In kernel/sched/rt.c (ffff800010151cc0)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:tg_set_rt_bandwidth
```
```
In kernel/power/process.c (ffff800010170264)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/cgroup/cgroup.c (ffff8000101d475c)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_enable_task_cg_lists
```
```
In kernel/pid_namespace.c (ffff8000101e7630)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tracepoint.c (ffff80001020edd0)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/fgraph.c (ffff800010238760)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
```
In kernel/trace/trace_uprobe.c (ffff800010259420)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In mm/mempolicy.c (ffff80001033b668)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
```
```
In mm/memory-failure.c (ffff80001036ebc4)
Location: include/asm-generic/qrwlock.h:102
Inline: True
```
```
In mm/zsmalloc.c (ffff800010375708)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/exec.c (ffff80001038e948)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:__arm64_sys_uselib
  - fs/exec.c:__arm64_sys_uselib
```
```
In fs/fcntl.c (ffff80001039ce8c)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/eventpoll.c (ffff8000103f151c)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll_callback
```
```
In fs/proc/generic.c (ffff800010443404)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/proc/array.c (ffff800010444b34)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/ext4/extents_status.c (ffff800010470558)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffff8000104b8118)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/jbd2/transaction.c (ffff8000104ccc20)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/hooks.c (ffff800010554074)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/selinux/ss/services.c (ffff8000105688b8)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:vec_find
```
```
In security/integrity/iint.c (ffff8000105ac6e0)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In drivers/tty/tty_io.c (ffff800010851ab0)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/tty/tty_jobctrl.c (ffff800010860c84)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/sysrq.c (ffff800010864240)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/scsi/sg.c (ffff8000109912a0)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
```
```
In drivers/leds/led-triggers.c (ffff800010b4a21c)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
```
In net/core/sock.c (ffff800010bab8f0)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/core/sock.c:sock_i_ino
  - net/core/sock.c:sock_i_uid
```
```
In net/core/skbuff.c (ffff800010bb3788)
Location: include/asm-generic/qrwlock.h:102
Inline: True
```
```
In net/core/neighbour.c (ffff800010be2ea0)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:address_show
```
```
In net/core/netpoll.c (ffff800010c11930)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/sched/sch_api.c (ffff800010c3ce68)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffff800010c416e8)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffff800010c47128)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (ffff800010c4a118)
Location: include/asm-generic/qrwlock.h:102
Inline: True
```
```
In net/netlink/af_netlink.c (ffff800010c4dbb8)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/arp.c (ffff800010ca18d8)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
  - net/ipv4/arp.c:arp_ioctl
```
```
In net/ipv4/ping.c (ffff800010cc0aa8)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_seq_stop
  - net/ipv4/ping.c:ping_lookup
```
```
In net/ipv4/ipmr.c (ffff800010cc9a28)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffff800010cdc380)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/ipv6/anycast.c (ffff800010cf70a0)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_seq_stop
  - net/ipv6/anycast.c:ac6_seq_start
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffff800010cfb664)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/addrconf.c (ffff800010d00840)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffff800010d1bbc8)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
```
In net/ipv6/ndisc.c (ffff800010d23128)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
```
```
In net/ipv6/raw.c (ffff800010d2a898)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/mcast.c (ffff800010d2e764)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b22b)
Location: include/asm-generic/qrwlock.h:102
Inline: True
```
```
In kernel/fork.c (ffffffff8109a47d)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/fork.c:walk_process_tree
```
```
In kernel/exit.c (ffffffff8109f3b7)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff810adfff)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
```
```
In kernel/locking/spinlock.c (ffffffff81a738b5)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
```
```
In kernel/power/process.c (ffffffff81101e1f)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/livepatch/transition.c (ffffffff81126cac)
Location: include/asm-generic/qrwlock.h:102
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
In kernel/cgroup/cgroup.c (ffffffff8115b72b)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_enable_task_cg_lists
```
```
In kernel/pid_namespace.c (ffffffff8116b997)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tracepoint.c (ffffffff8118ef4b)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/fgraph.c (ffffffff811b2582)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d0b64)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In mm/mempolicy.c (ffffffff81294d08)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
```
```
In mm/memory-failure.c (ffffffff812c34af)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
```
```
In mm/zsmalloc.c (ffffffff812c8af6)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/exec.c (ffffffff812dec7f)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/generic.c (ffffffff8136fd3a)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff81371226)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/ext4/extents_status.c (ffffffff81395909)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff813d1f8c)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/jbd2/transaction.c (ffffffff813ea983)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/hooks.c (ffffffff81457095)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/selinux/ss/services.c (ffffffff81470d00)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In drivers/tty/tty_io.c (ffffffff8164a0c4)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81654bf7)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/sysrq.c (ffffffff816566ee)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/scsi/sg.c (ffffffff8173d1bc)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
```
```
In drivers/leds/led-triggers.c (ffffffff81888c20)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
```
In net/core/neighbour.c (ffffffff818e14d5)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_for_each
```
```
In net/core/net-sysfs.c (ffffffff819048b8)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:address_show
```
```
In net/sched/sch_api.c (ffffffff8192fd3f)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffffffff81933ec7)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffffffff81939c54)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (ffffffff8193ca0e)
Location: include/asm-generic/qrwlock.h:102
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff8193dd34)
Location: include/asm-generic/qrwlock.h:102
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
In net/ipv4/raw.c (ffffffff819828b6)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/arp.c (ffffffff8198bbf8)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
```
```
In net/ipv4/ipmr.c (ffffffff819aec95)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff819bfcc5)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/ipv6/ip6_output.c (ffffffff819d9c4c)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff819eb1bb)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffffffff819f66eb)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
```
In net/ipv6/raw.c (ffffffff81a041dc)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/mcast.c (ffffffff81a0a242)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv6/mcast.c:inet6_mc_check
```
```
In net/ipv6/ip6mr.c (ffffffff81a1cacf)
Location: include/asm-generic/qrwlock.h:102
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
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104b39b)
Location: include/asm-generic/qrwlock.h:102
Inline: True
```
```
In kernel/fork.c (ffffffff81088ebd)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/fork.c:walk_process_tree
```
```
In kernel/exit.c (ffffffff8108dde7)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff8109c959)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
```
```
In kernel/sched/rt.c (ffffffff810d998b)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:tg_set_rt_bandwidth
```
```
In kernel/locking/spinlock.c (ffffffff81a2fc35)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
```
```
In kernel/power/process.c (ffffffff810f21df)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/livepatch/transition.c (ffffffff8111970c)
Location: include/asm-generic/qrwlock.h:102
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
In kernel/cgroup/cgroup.c (ffffffff8114ea15)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_enable_task_cg_lists
```
```
In kernel/pid_namespace.c (ffffffff8115eb97)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tracepoint.c (ffffffff811820cb)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/fgraph.c (ffffffff811a5392)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
```
In kernel/trace/trace_uprobe.c (ffffffff811c3934)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In mm/mempolicy.c (ffffffff81286918)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
```
```
In mm/memory-failure.c (ffffffff812b44ef)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
```
```
In mm/zsmalloc.c (ffffffff812b9b36)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/exec.c (ffffffff812ceda4)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/generic.c (ffffffff813607ca)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff81361cb6)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/ext4/extents_status.c (ffffffff81386399)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff813c2a0c)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/jbd2/transaction.c (ffffffff813db403)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/hooks.c (ffffffff81447ad5)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/selinux/ss/services.c (ffffffff81461720)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In drivers/tty/tty_io.c (ffffffff8162a514)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81634fc1)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/sysrq.c (ffffffff81636a7e)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/scsi/sg.c (ffffffff8171ee5c)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
```
```
In drivers/leds/led-triggers.c (ffffffff818405a0)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
```
In net/core/neighbour.c (ffffffff8189b315)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_for_each
```
```
In net/core/net-sysfs.c (ffffffff818be6e8)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:address_show
```
```
In net/sched/sch_api.c (ffffffff818e983f)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffffffff818ed9c7)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffffffff818f3754)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (ffffffff818f650e)
Location: include/asm-generic/qrwlock.h:102
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff818f7834)
Location: include/asm-generic/qrwlock.h:102
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
In net/ipv4/raw.c (ffffffff8193c376)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/arp.c (ffffffff819456b8)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
```
```
In net/ipv4/ipmr.c (ffffffff8196b2c5)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197cab5)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/ipv6/ip6_output.c (ffffffff81996a0c)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff819a7f7b)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffffffff819b34ab)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
```
In net/ipv6/raw.c (ffffffff819c0f9c)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/mcast.c (ffffffff819c7002)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv6/mcast.c:inet6_mc_check
```
```
In net/ipv6/ip6mr.c (ffffffff819d988f)
Location: include/asm-generic/qrwlock.h:102
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
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b65b)
Location: include/asm-generic/qrwlock.h:102
Inline: True
```
```
In kernel/fork.c (ffffffff8109a42d)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/fork.c:walk_process_tree
```
```
In kernel/exit.c (ffffffff8109f367)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff810ad55f)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
```
```
In kernel/sched/rt.c (ffffffff810e6afb)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:tg_set_rt_bandwidth
```
```
In kernel/locking/spinlock.c (ffffffff81adfcc5)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
```
```
In kernel/power/process.c (ffffffff810ff1af)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/livepatch/transition.c (ffffffff81124b9c)
Location: include/asm-generic/qrwlock.h:102
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
In kernel/cgroup/cgroup.c (ffffffff811594fb)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_enable_task_cg_lists
```
```
In kernel/pid_namespace.c (ffffffff81169767)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tracepoint.c (ffffffff8118cd1b)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/fgraph.c (ffffffff811b0352)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
```
In kernel/trace/trace_uprobe.c (ffffffff811ce934)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In mm/mempolicy.c (ffffffff81292b18)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
```
```
In mm/memory-failure.c (ffffffff812c12bf)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
```
```
In mm/zsmalloc.c (ffffffff812c6906)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/exec.c (ffffffff812dca8f)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/generic.c (ffffffff8136d80a)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff8136ecf6)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/ext4/extents_status.c (ffffffff81393269)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff813cf41c)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/jbd2/transaction.c (ffffffff813e7d03)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/hooks.c (ffffffff81453135)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/selinux/ss/services.c (ffffffff8146cda0)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In drivers/tty/tty_io.c (ffffffff81678484)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81682fb7)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/sysrq.c (ffffffff81684aae)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/scsi/sg.c (ffffffff8177d94c)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
```
```
In drivers/leds/led-triggers.c (ffffffff818da8f0)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
```
In net/core/neighbour.c (ffffffff81932505)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_for_each
```
```
In net/core/net-sysfs.c (ffffffff819558e8)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:address_show
```
```
In net/sched/sch_api.c (ffffffff81980ecf)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffffffff81985057)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffffffff8198ade4)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (ffffffff8198db9e)
Location: include/asm-generic/qrwlock.h:102
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff8198eec4)
Location: include/asm-generic/qrwlock.h:102
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
In net/ipv4/raw.c (ffffffff819ed086)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/arp.c (ffffffff819f6408)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
```
```
In net/ipv4/ipmr.c (ffffffff81a19535)
Location: include/asm-generic/qrwlock.h:102
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
Location: include/asm-generic/qrwlock.h:102
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2a745)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/ipv6/ip6_output.c (ffffffff81a446cc)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff81a55c3b)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffffffff81a6116b)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
```
In net/ipv6/raw.c (ffffffff81a6ec5c)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/mcast.c (ffffffff81a74cc2)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - net/ipv6/mcast.c:inet6_mc_check
```
```
In net/ipv6/ip6mr.c (ffffffff81a8754f)
Location: include/asm-generic/qrwlock.h:102
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
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81aec665)
Location: include/asm-generic/qrwlock.h:102
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_irq
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
  - kernel/locking/spinlock.c:_raw_read_unlock
```
</details>
</li>
</ul>

## Differences

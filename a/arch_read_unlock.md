# Function: <code>arch_read_unlock</code>

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
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/fork.c (c0353c3c)
Location: arch/arm/include/asm/spinlock.h:227
Inline: True
Inline callers:
  - kernel/fork.c:walk_process_tree
```
```
In kernel/exit.c (c0359ab0)
Location: arch/arm/include/asm/spinlock.h:227
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
In kernel/resource.c (c035e268)
Location: arch/arm/include/asm/spinlock.h:227
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
In kernel/ptrace.c (c0362450)
Location: arch/arm/include/asm/spinlock.h:227
Inline: True
Inline callers:
  - kernel/ptrace.c:__se_sys_ptrace
```
```
In kernel/signal.c (c0369658)
Location: arch/arm/include/asm/spinlock.h:227
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_kill
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:kill_pgrp
```
```
In kernel/sys.c (c036d818)
Location: arch/arm/include/asm/spinlock.h:227
Inline: True
Inline callers:
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:__se_sys_getpriority
  - kernel/sys.c:__se_sys_setpriority
```
```
In kernel/sched/core.c (c038daec)
Location: arch/arm/include/asm/spinlock.h:227
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
```
```
In kernel/sched/rt.c (c039ef58)
Location: arch/arm/include/asm/spinlock.h:227
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:tg_set_rt_bandwidth
```
```
In kernel/locking/spinlock.c (c0e9f3e0)
Location: arch/arm/include/asm/spinlock.h:227
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
```
```
In kernel/power/process.c (c03bab04)
Location: arch/arm/include/asm/spinlock.h:227
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
Direct callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/cgroup/cgroup.c (c04173bc)
Location: arch/arm/include/asm/spinlock.h:227
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_enable_task_cg_lists
```
```
In kernel/pid_namespace.c (c0427a74)
Location: arch/arm/include/asm/spinlock.h:227
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:zap_pid_ns_processes
Direct callers:
  - kernel/pid_namespace.c:reboot_pid_ns
```
```
In kernel/tracepoint.c (c044d918)
Location: arch/arm/include/asm/spinlock.h:227
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/fgraph.c (c0474358)
Location: arch/arm/include/asm/spinlock.h:227
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
```
In kernel/trace/trace_uprobe.c (c048b7a8)
Location: arch/arm/include/asm/spinlock.h:227
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In mm/zsmalloc.c (c05621a8)
Location: arch/arm/include/asm/spinlock.h:227
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/exec.c (c0574dc8)
Location: arch/arm/include/asm/spinlock.h:227
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:__se_sys_uselib
  - fs/exec.c:__se_sys_uselib
```
```
In fs/fcntl.c (c05828a4)
Location: arch/arm/include/asm/spinlock.h:227
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
In fs/filesystems.c (c0591f74)
Location: arch/arm/include/asm/spinlock.h:227
Inline: True
Inline callers:
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:filesystems_proc_show
  - fs/filesystems.c:__se_sys_sysfs
  - fs/filesystems.c:__se_sys_sysfs
  - fs/filesystems.c:__se_sys_sysfs
Direct callers:
  - fs/filesystems.c:get_filesystem_list
```
```
In fs/fs_struct.c (c05ad548)
Location: arch/arm/include/asm/spinlock.h:227
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/generic.c (c06086f8)
Location: arch/arm/include/asm/spinlock.h:227
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/proc/array.c (c060a004)
Location: arch/arm/include/asm/spinlock.h:227
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/ext4/extents_status.c (c0631988)
Location: arch/arm/include/asm/spinlock.h:227
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
In fs/ext4/inode.c (c064b4bc)
Location: arch/arm/include/asm/spinlock.h:227
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (c0675c68)
Location: arch/arm/include/asm/spinlock.h:227
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/jbd2/transaction.c (c06904a8)
Location: arch/arm/include/asm/spinlock.h:227
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
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:wait_transaction_locked
```
```
In fs/jbd2/journal.c (c069838c)
Location: arch/arm/include/asm/spinlock.h:227
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
In security/keys/keyring.c (c06e8e14)
Location: arch/arm/include/asm/spinlock.h:227
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/hooks.c (c0707238)
Location: arch/arm/include/asm/spinlock.h:227
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/selinux/ss/services.c (c071cabc)
Location: arch/arm/include/asm/spinlock.h:227
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
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_bounded_transition
```
```
In security/integrity/iint.c (c075c130)
Location: arch/arm/include/asm/spinlock.h:227
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In drivers/tty/tty_io.c (c095c5c0)
Location: arch/arm/include/asm/spinlock.h:227
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/tty/tty_jobctrl.c (c0967acc)
Location: arch/arm/include/asm/spinlock.h:227
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/sysrq.c (c0969e28)
Location: arch/arm/include/asm/spinlock.h:227
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/scsi/sg.c (c0a6278c)
Location: arch/arm/include/asm/spinlock.h:227
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
```
```
In drivers/leds/led-triggers.c (c0c33be8)
Location: arch/arm/include/asm/spinlock.h:227
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
```
In sound/core/control.c (c0c85e04)
Location: arch/arm/include/asm/spinlock.h:227
Inline: True
Inline callers:
  - sound/core/control.c:snd_ctl_dev_disconnect
  - sound/core/control.c:snd_ctl_get_preferred_subdevice
```
```
In net/core/neighbour.c (c0cfd08c)
Location: arch/arm/include/asm/spinlock.h:227
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_for_each
```
```
In net/core/net-sysfs.c (c0d24350)
Location: arch/arm/include/asm/spinlock.h:227
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:address_show
```
```
In net/sched/sch_api.c (c0d4e7dc)
Location: arch/arm/include/asm/spinlock.h:227
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (c0d52de0)
Location: arch/arm/include/asm/spinlock.h:227
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (c0d5810c)
Location: arch/arm/include/asm/spinlock.h:227
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (c0d5ad04)
Location: arch/arm/include/asm/spinlock.h:227
Inline: True
```
```
In net/netlink/af_netlink.c (c0d5cc70)
Location: arch/arm/include/asm/spinlock.h:227
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
In net/ipv4/raw.c (c0da55b0)
Location: arch/arm/include/asm/spinlock.h:227
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/arp.c (c0dae6ac)
Location: arch/arm/include/asm/spinlock.h:227
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
```
```
In net/ipv4/ipmr.c (c0dd6d34)
Location: arch/arm/include/asm/spinlock.h:227
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
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:reg_vif_xmit
```
```
In net/ipv4/ipmr_base.c (c0ddb224)
Location: arch/arm/include/asm/spinlock.h:227
Inline: True
```
```
In net/xfrm/xfrm_policy.c (c0de5ca0)
Location: arch/arm/include/asm/spinlock.h:227
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/ipv6/ip6_output.c (c0e021ec)
Location: arch/arm/include/asm/spinlock.h:227
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (c0e150f4)
Location: arch/arm/include/asm/spinlock.h:227
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (c0e21014)
Location: arch/arm/include/asm/spinlock.h:227
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
```
In net/ipv6/raw.c (c0e2e9cc)
Location: arch/arm/include/asm/spinlock.h:227
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/mcast.c (c0e3511c)
Location: arch/arm/include/asm/spinlock.h:227
Inline: True
Inline callers:
  - net/ipv6/mcast.c:inet6_mc_check
```
```
In net/ipv6/ip6mr.c (c0e49af4)
Location: arch/arm/include/asm/spinlock.h:227
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_stop
```
**Symbols:**

```
c03ba588-c03ba5cc: arch_read_unlock.constprop.0 (STB_LOCAL)
c04279ac-c04279f0: arch_read_unlock.constprop.0 (STB_LOCAL)
c0591ee4-c0591f28: arch_read_unlock.constprop.0 (STB_LOCAL)
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
In arch/powerpc/platforms/pseries/dtl.c (c0000000000fcd80)
Location: arch/powerpc/include/asm/spinlock.h:291
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/dtl.c:dtl_file_release
  - arch/powerpc/platforms/pseries/dtl.c:dtl_file_open
  - arch/powerpc/platforms/pseries/dtl.c:dtl_file_open
```
```
In kernel/fork.c (c00000000013b5f0)
Location: arch/powerpc/include/asm/spinlock.h:291
Inline: True
Inline callers:
  - kernel/fork.c:walk_process_tree
```
```
In kernel/exit.c (c000000000143124)
Location: arch/powerpc/include/asm/spinlock.h:291
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
In kernel/resource.c (c000000000149908)
Location: arch/powerpc/include/asm/spinlock.h:291
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
In kernel/ptrace.c (c00000000014eea8)
Location: arch/powerpc/include/asm/spinlock.h:291
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (c0000000001579e4)
Location: arch/powerpc/include/asm/spinlock.h:291
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_kill
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:kill_pgrp
```
```
In kernel/sys.c (c000000000160934)
Location: arch/powerpc/include/asm/spinlock.h:291
Inline: True
Inline callers:
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:__se_sys_getpriority
  - kernel/sys.c:__se_sys_setpriority
```
```
In kernel/sched/core.c (c00000000018ca98)
Location: arch/powerpc/include/asm/spinlock.h:291
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
```
```
In kernel/sched/rt.c (c0000000001a5658)
Location: arch/powerpc/include/asm/spinlock.h:291
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:tg_set_rt_bandwidth
```
```
In kernel/locking/spinlock.c (c000000000eea0dc)
Location: arch/powerpc/include/asm/spinlock.h:291
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
```
```
In kernel/power/process.c (c0000000001c8380)
Location: arch/powerpc/include/asm/spinlock.h:291
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/livepatch/transition.c (c0000000001f3a98)
Location: arch/powerpc/include/asm/spinlock.h:291
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
In kernel/cgroup/cgroup.c (c00000000023fdc4)
Location: arch/powerpc/include/asm/spinlock.h:291
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_enable_task_cg_lists
```
```
In kernel/pid_namespace.c (c000000000257c44)
Location: arch/powerpc/include/asm/spinlock.h:291
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tracepoint.c (c00000000028d43c)
Location: arch/powerpc/include/asm/spinlock.h:291
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/fgraph.c (c0000000002c4be4)
Location: arch/powerpc/include/asm/spinlock.h:291
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
```
In kernel/trace/trace_uprobe.c (c0000000002fbb94)
Location: arch/powerpc/include/asm/spinlock.h:291
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In mm/mempolicy.c (c0000000004163b4)
Location: arch/powerpc/include/asm/spinlock.h:291
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
```
```
In mm/memory-failure.c (c00000000045f4f8)
Location: arch/powerpc/include/asm/spinlock.h:291
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
```
```
In mm/zsmalloc.c (c000000000468958)
Location: arch/powerpc/include/asm/spinlock.h:291
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/exec.c (c000000000485880)
Location: arch/powerpc/include/asm/spinlock.h:291
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:__se_sys_uselib
  - fs/exec.c:__se_sys_uselib
```
```
In fs/fcntl.c (c000000000497b38)
Location: arch/powerpc/include/asm/spinlock.h:291
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
In fs/filesystems.c (c0000000004aec00)
Location: arch/powerpc/include/asm/spinlock.h:291
Inline: True
Inline callers:
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:filesystems_proc_show
  - fs/filesystems.c:__se_sys_sysfs
  - fs/filesystems.c:__se_sys_sysfs
  - fs/filesystems.c:__se_sys_sysfs
  - fs/filesystems.c:get_filesystem_list
```
```
In fs/fs_struct.c (c0000000004d54e8)
Location: arch/powerpc/include/asm/spinlock.h:291
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/generic.c (c000000000558a70)
Location: arch/powerpc/include/asm/spinlock.h:291
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (c00000000055a968)
Location: arch/powerpc/include/asm/spinlock.h:291
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/ext4/extents_status.c (c000000000590be0)
Location: arch/powerpc/include/asm/spinlock.h:291
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
In fs/ext4/inode.c (c0000000005afde8)
Location: arch/powerpc/include/asm/spinlock.h:291
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (c0000000005e5988)
Location: arch/powerpc/include/asm/spinlock.h:291
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/jbd2/transaction.c (c0000000006062ec)
Location: arch/powerpc/include/asm/spinlock.h:291
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
In fs/jbd2/journal.c (c00000000060c778)
Location: arch/powerpc/include/asm/spinlock.h:291
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
In security/keys/keyring.c (c00000000067e474)
Location: arch/powerpc/include/asm/spinlock.h:291
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/hooks.c (c0000000006a41ac)
Location: arch/powerpc/include/asm/spinlock.h:291
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/selinux/ss/services.c (c0000000006cbf54)
Location: arch/powerpc/include/asm/spinlock.h:291
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
In security/integrity/iint.c (c00000000072abf0)
Location: arch/powerpc/include/asm/spinlock.h:291
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In drivers/tty/tty_io.c (c0000000008ef400)
Location: arch/powerpc/include/asm/spinlock.h:291
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/tty/tty_jobctrl.c (c0000000009000f4)
Location: arch/powerpc/include/asm/spinlock.h:291
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/sysrq.c (c000000000902bf0)
Location: arch/powerpc/include/asm/spinlock.h:291
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/scsi/sg.c (c000000000a52094)
Location: arch/powerpc/include/asm/spinlock.h:291
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
```
```
In drivers/leds/led-triggers.c (c000000000c3fb78)
Location: arch/powerpc/include/asm/spinlock.h:291
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
```
In net/core/neighbour.c (c000000000cc294c)
Location: arch/powerpc/include/asm/spinlock.h:291
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_for_each
```
```
In net/core/net-sysfs.c (c000000000cf3b80)
Location: arch/powerpc/include/asm/spinlock.h:291
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:address_show
```
```
In net/sched/sch_api.c (c000000000d358ec)
Location: arch/powerpc/include/asm/spinlock.h:291
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (c000000000d3b52c)
Location: arch/powerpc/include/asm/spinlock.h:291
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (c000000000d437cc)
Location: arch/powerpc/include/asm/spinlock.h:291
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (c000000000d47b34)
Location: arch/powerpc/include/asm/spinlock.h:291
Inline: True
```
```
In net/netlink/af_netlink.c (c000000000d4b63c)
Location: arch/powerpc/include/asm/spinlock.h:291
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
In net/ipv4/raw.c (c000000000da851c)
Location: arch/powerpc/include/asm/spinlock.h:291
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/arp.c (c000000000db4a54)
Location: arch/powerpc/include/asm/spinlock.h:291
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
```
```
In net/ipv4/ipmr.c (c000000000de6400)
Location: arch/powerpc/include/asm/spinlock.h:291
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
In net/ipv4/ipmr_base.c (c000000000def274)
Location: arch/powerpc/include/asm/spinlock.h:291
Inline: True
```
```
In net/xfrm/xfrm_policy.c (c000000000dff678)
Location: arch/powerpc/include/asm/spinlock.h:291
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/ipv6/ip6_output.c (c000000000e22c20)
Location: arch/powerpc/include/asm/spinlock.h:291
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (c000000000e3b3e8)
Location: arch/powerpc/include/asm/spinlock.h:291
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (c000000000e4a4f0)
Location: arch/powerpc/include/asm/spinlock.h:291
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
```
In net/ipv6/raw.c (c000000000e5bc28)
Location: arch/powerpc/include/asm/spinlock.h:291
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/mcast.c (c000000000e6457c)
Location: arch/powerpc/include/asm/spinlock.h:291
Inline: True
Inline callers:
  - net/ipv6/mcast.c:inet6_mc_check
```
```
In net/ipv6/ip6mr.c (c000000000e7d5c4)
Location: arch/powerpc/include/asm/spinlock.h:291
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
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffe0000c192a)
Location: arch/riscv/include/asm/spinlock.h:120
Inline: True
Inline callers:
  - kernel/fork.c:walk_process_tree
```
```
In kernel/exit.c (ffffffe0000c54ec)
Location: arch/riscv/include/asm/spinlock.h:120
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
In kernel/resource.c (ffffffe0000c8e6a)
Location: arch/riscv/include/asm/spinlock.h:120
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
In kernel/ptrace.c (ffffffe0000cc30c)
Location: arch/riscv/include/asm/spinlock.h:120
Inline: True
Inline callers:
  - kernel/ptrace.c:__se_sys_ptrace
```
```
In kernel/signal.c (ffffffe0000d1660)
Location: arch/riscv/include/asm/spinlock.h:120
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_kill
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:kill_pgrp
```
```
In kernel/sys.c (ffffffe0000d42dc)
Location: arch/riscv/include/asm/spinlock.h:120
Inline: True
Inline callers:
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:__se_sys_getpriority
  - kernel/sys.c:__se_sys_setpriority
```
```
In kernel/sched/core.c (ffffffe0000ec9d8)
Location: arch/riscv/include/asm/spinlock.h:120
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
```
```
In kernel/sched/rt.c (ffffffe0000f9e8c)
Location: arch/riscv/include/asm/spinlock.h:120
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:tg_set_rt_bandwidth
```
```
In kernel/locking/spinlock.c (ffffffe0008c9592)
Location: arch/riscv/include/asm/spinlock.h:120
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
```
```
In kernel/power/process.c (ffffffe00010dda4)
Location: arch/riscv/include/asm/spinlock.h:120
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/cgroup/cgroup.c (ffffffe00014dc7c)
Location: arch/riscv/include/asm/spinlock.h:120
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_enable_task_cg_lists
```
```
In kernel/pid_namespace.c (ffffffe00015cb70)
Location: arch/riscv/include/asm/spinlock.h:120
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tracepoint.c (ffffffe00016fa50)
Location: arch/riscv/include/asm/spinlock.h:120
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/fgraph.c (ffffffe00018f6f2)
Location: arch/riscv/include/asm/spinlock.h:120
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:register_ftrace_graph
```
```
In mm/zsmalloc.c (ffffffe00024e0b4)
Location: arch/riscv/include/asm/spinlock.h:120
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/exec.c (ffffffe00025e460)
Location: arch/riscv/include/asm/spinlock.h:120
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:__se_sys_uselib
  - fs/exec.c:__se_sys_uselib
```
```
In fs/fcntl.c (ffffffe0002690ec)
Location: arch/riscv/include/asm/spinlock.h:120
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:__se_sys_fcntl
  - fs/fcntl.c:__se_sys_fcntl
  - fs/fcntl.c:f_getown
```
```
In fs/filesystems.c (ffffffe000276b92)
Location: arch/riscv/include/asm/spinlock.h:120
Inline: True
Inline callers:
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:filesystems_proc_show
  - fs/filesystems.c:__se_sys_sysfs
  - fs/filesystems.c:__se_sys_sysfs
  - fs/filesystems.c:__se_sys_sysfs
  - fs/filesystems.c:get_filesystem_list
```
```
In fs/fs_struct.c (ffffffe00028dbf6)
Location: arch/riscv/include/asm/spinlock.h:120
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/generic.c (ffffffe0002d9b04)
Location: arch/riscv/include/asm/spinlock.h:120
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/proc/array.c (ffffffe0002dab96)
Location: arch/riscv/include/asm/spinlock.h:120
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/ext4/extents_status.c (ffffffe0002fcc30)
Location: arch/riscv/include/asm/spinlock.h:120
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
In fs/ext4/inode.c (ffffffe0003108ee)
Location: arch/riscv/include/asm/spinlock.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffe0003304b6)
Location: arch/riscv/include/asm/spinlock.h:120
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/jbd2/transaction.c (ffffffe0003454f2)
Location: arch/riscv/include/asm/spinlock.h:120
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
In fs/jbd2/journal.c (ffffffe000349c76)
Location: arch/riscv/include/asm/spinlock.h:120
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_errno
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_transaction_committed
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
```
```
In security/keys/keyring.c (ffffffe0003920a6)
Location: arch/riscv/include/asm/spinlock.h:120
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/hooks.c (ffffffe0003a96fc)
Location: arch/riscv/include/asm/spinlock.h:120
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/selinux/ss/services.c (ffffffe0003bdfb4)
Location: arch/riscv/include/asm/spinlock.h:120
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
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_bounded_transition
```
```
In security/integrity/iint.c (ffffffe0003f4f7e)
Location: arch/riscv/include/asm/spinlock.h:120
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In drivers/tty/tty_io.c (ffffffe00052f078)
Location: arch/riscv/include/asm/spinlock.h:120
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/tty/tty_jobctrl.c (ffffffe000538888)
Location: arch/riscv/include/asm/spinlock.h:120
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/sysrq.c (ffffffe00053a5dc)
Location: arch/riscv/include/asm/spinlock.h:120
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/scsi/sg.c (ffffffe0005f402e)
Location: arch/riscv/include/asm/spinlock.h:120
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
```
```
In drivers/leds/led-triggers.c (ffffffe00071dda8)
Location: arch/riscv/include/asm/spinlock.h:120
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
```
In net/core/neighbour.c (ffffffe00076799e)
Location: arch/riscv/include/asm/spinlock.h:120
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_for_each
```
```
In net/core/net-sysfs.c (ffffffe000786d6c)
Location: arch/riscv/include/asm/spinlock.h:120
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:address_show
```
```
In net/sched/sch_api.c (ffffffe0007aca2a)
Location: arch/riscv/include/asm/spinlock.h:120
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffffffe0007affd8)
Location: arch/riscv/include/asm/spinlock.h:120
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffffffe0007b4ebe)
Location: arch/riscv/include/asm/spinlock.h:120
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (ffffffe0007b74a8)
Location: arch/riscv/include/asm/spinlock.h:120
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffe0007b86a8)
Location: arch/riscv/include/asm/spinlock.h:120
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
In net/ipv4/raw.c (ffffffe0007f5ba8)
Location: arch/riscv/include/asm/spinlock.h:120
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/arp.c (ffffffe0007fded2)
Location: arch/riscv/include/asm/spinlock.h:120
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
```
```
In net/ipv4/ipmr.c (ffffffe00081d116)
Location: arch/riscv/include/asm/spinlock.h:120
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
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:reg_vif_xmit
```
```
In net/ipv4/ipmr_base.c (ffffffe0008228fe)
Location: arch/riscv/include/asm/spinlock.h:120
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffe000829ef6)
Location: arch/riscv/include/asm/spinlock.h:120
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/ipv6/ip6_output.c (ffffffe000846026)
Location: arch/riscv/include/asm/spinlock.h:120
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffe00085698a)
Location: arch/riscv/include/asm/spinlock.h:120
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffffffe00085fba4)
Location: arch/riscv/include/asm/spinlock.h:120
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
```
In net/ipv6/raw.c (ffffffe00086b0e8)
Location: arch/riscv/include/asm/spinlock.h:120
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/mcast.c (ffffffe000870a00)
Location: arch/riscv/include/asm/spinlock.h:120
Inline: True
Inline callers:
  - net/ipv6/mcast.c:inet6_mc_check
```
```
In net/ipv6/ip6mr.c (ffffffe000881c26)
Location: arch/riscv/include/asm/spinlock.h:120
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_stop
```
</details>
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

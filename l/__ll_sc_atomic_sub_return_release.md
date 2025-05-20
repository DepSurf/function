# Function: <code>__ll_sc_atomic_sub_return_release</code>

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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/xen/p2m.c (ffff8000100f04e8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - arch/arm/xen/p2m.c:__pfn_to_mfn
  - arch/arm/xen/p2m.c:__pfn_to_mfn
```
```
In kernel/fork.c (ffff8000100f5554)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/fork.c:walk_process_tree
```
```
In kernel/exit.c (ffff8000100fbb90)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
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
In kernel/resource.c (ffff800010101f30)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
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
In kernel/ptrace.c (ffff800010107c78)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffff8000101102b4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/signal.c:__arm64_sys_kill
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:kill_pgrp
```
```
In kernel/sys.c (ffff800010118e30)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:__arm64_sys_getpriority
  - kernel/sys.c:__arm64_sys_setpriority
```
```
In kernel/sched/core.c (ffff80001013db5c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
```
```
In kernel/sched/rt.c (ffff800010151d64)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:tg_set_rt_bandwidth
```
```
In kernel/power/process.c (ffff80001016fe80)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/cgroup/cgroup.c (ffff8000101d4788)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_enable_task_cg_lists
```
```
In kernel/pid_namespace.c (ffff8000101e76c0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/tracepoint.c (ffff80001020ee00)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/fgraph.c (ffff80001023878c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
```
In kernel/trace/trace_uprobe.c (ffff800010259478)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
```
```
In mm/mempolicy.c (ffff80001033b694)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
```
```
In mm/memory-failure.c (ffff80001036efcc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In mm/zsmalloc.c (ffff8000103757d8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
```
```
In fs/exec.c (ffff80001038e980)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:__arm64_sys_uselib
  - fs/exec.c:__arm64_sys_uselib
```
```
In fs/fcntl.c (ffff80001039cfa0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
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
In fs/filesystems.c (ffff8000103b30f0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:filesystems_proc_show
  - fs/filesystems.c:__arm64_sys_sysfs
  - fs/filesystems.c:__arm64_sys_sysfs
  - fs/filesystems.c:fs_name
```
```
In fs/fs_struct.c (ffff8000103d2a04)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/eventpoll.c (ffff8000103f15c8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll_callback
```
```
In fs/proc/generic.c (ffff800010443550)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/proc/array.c (ffff800010444b84)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/ext4/extents_status.c (ffff8000104705ac)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
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
In fs/ext4/inode.c (ffff800010489070)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffff8000104b824c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/jbd2/transaction.c (ffff8000104cccac)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
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
In fs/jbd2/journal.c (ffff8000104d4388)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
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
In security/keys/keyring.c (ffff80001053101c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/selinux/hooks.c (ffff800010554174)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In security/selinux/ss/services.c (ffff800010568910)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
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
In security/apparmor/label.c (ffff8000105a2db0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:vec_find
```
```
In security/integrity/iint.c (ffff8000105ac73c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_iint_find
```
```
In drivers/tty/tty_io.c (ffff800010851b2c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
```
In drivers/tty/tty_jobctrl.c (ffff800010860dfc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/sysrq.c (ffff80001086426c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/iommu/arm-smmu-v3.c (ffff8000108d55ac)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_cmdq_issue_cmdlist
```
```
In drivers/scsi/sg.c (ffff800010991398)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
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
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/net/ppp/ppp_generic.c (ffff8000109fe9fc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_name
  - drivers/net/ppp/ppp_generic.c:ppp_unit_number
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
```
```
In drivers/cpufreq/cpufreq.c (ffff800010b204ac)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
```
```
In drivers/leds/led-triggers.c (ffff800010b4a250)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
```
In net/core/sock.c (ffff800010bab950)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/core/sock.c:sock_i_ino
  - net/core/sock.c:sock_i_uid
```
```
In net/core/skbuff.c (ffff800010bb37e0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In net/core/neighbour.c (ffff800010be2ee0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
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
In net/core/net-sysfs.c (ffff800010c0af90)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:address_show
```
```
In net/core/netpoll.c (ffff800010c119c4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/sched/sch_api.c (ffff800010c3ce98)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
```
```
In net/sched/cls_api.c (ffff800010c41734)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (ffff800010c47158)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
```
```
In net/sched/ematch.c (ffff800010c4a1ac)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In net/netlink/af_netlink.c (ffff800010c4defc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
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
In net/ipv4/raw.c (ffff800010c96c70)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/arp.c (ffff800010ca190c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
  - net/ipv4/arp.c:arp_ioctl
```
```
In net/ipv4/ping.c (ffff800010cc0ae4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_seq_stop
  - net/ipv4/ping.c:ping_lookup
```
```
In net/ipv4/ipmr.c (ffff800010cc9a54)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
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
In net/ipv4/ipmr_base.c (ffff800010cd0ddc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffff800010cdc504)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/ipv6/anycast.c (ffff800010cf70d8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_seq_stop
  - net/ipv6/anycast.c:ac6_seq_start
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffff800010cfb6fc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/addrconf.c (ffff800010d00990)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:addrconf_dad_run
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:ipv6_get_lladdr
```
```
In net/ipv6/route.c (ffff800010d11db8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (ffff800010d1bc6c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
```
In net/ipv6/ndisc.c (ffff800010d23304)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
```
```
In net/ipv6/raw.c (ffff800010d2aa64)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/mcast.c (ffff800010d2e7a0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
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
In net/ipv6/ip6mr.c (ffff800010d4810c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
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

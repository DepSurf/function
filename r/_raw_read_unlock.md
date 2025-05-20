# Function: <code>_raw_read_unlock</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void _raw_read_unlock(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81f29c10)
Location: kernel/locking/spinlock.c:258
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks
  - kernel/fork.c:walk_process_tree
  - kernel/exit.c:do_wait
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:is_current_pgrp_orphaned
  - kernel/resource.c:iomem_is_exclusive
  - kernel/resource.c:iomem_map_sanity_check
  - kernel/resource.c:lookup_resource
  - kernel/resource.c:region_intersects
  - kernel/resource.c:find_next_iomem_res
  - kernel/resource.c:find_next_iomem_res
  - kernel/resource.c:r_stop
  - kernel/ptrace.c:ptrace_check_attach
  - kernel/ptrace.c:ptrace_check_attach
  - kernel/ptrace.c:ptrace_check_attach
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:kill_pgrp
  - kernel/signal.c:kill_something_info
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/build_utility.c:sched_core_share_pid
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - mm/mempolicy.c:mpol_shared_policy_lookup
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:zs_map_object
  - fs/exec.c:search_binary_handler
  - fs/exec.c:search_binary_handler
  - fs/exec.c:search_binary_handler
  - fs/exec.c:search_binary_handler
  - fs/exec.c:de_thread
  - fs/exec.c:__do_sys_uselib
  - fs/exec.c:__do_sys_uselib
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:filesystems_proc_show
  - fs/filesystems.c:__ia32_sys_sysfs
  - fs/filesystems.c:__x64_sys_sysfs
  - fs/filesystems.c:fs_name
  - fs/filesystems.c:fs_name
  - fs/filesystems.c:fs_index
  - fs/filesystems.c:list_bdev_fs_names
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:chroot_fs_refs
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_readdir_de
  - fs/proc/generic.c:proc_readdir_de
  - fs/proc/generic.c:proc_readdir_de
  - fs/proc/generic.c:proc_readdir_de
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/array.c:get_children_pid
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:ext4_is_pending
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_scan_clu
  - fs/ext4/extents_status.c:ext4_es_scan_clu
  - fs/ext4/extents_status.c:ext4_es_scan_range
  - fs/ext4/extents_status.c:ext4_es_scan_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
  - fs/ext4/inode.c:ext4_wait_for_tail_page_commit
  - fs/ext4/inode.c:ext4_wait_for_tail_page_commit
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/mballoc.c:ext4_mb_seq_structs_summary_stop
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/fast_commit.c:ext4_fc_mark_ineligible
  - fs/ext4/fast_commit.c:ext4_fc_mark_ineligible
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
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
  - fs/jbd2/journal.c:jbd2_journal_errno
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_transaction_committed
  - fs/jbd2/journal.c:jbd2_fc_end_commit_fallback
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - security/keys/keyring.c:find_keyring_by_name
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/integrity/iint.c:integrity_iint_find
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
  - drivers/xen/events/events_base.c:__xen_evtchn_do_upcall
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
  - drivers/tty/sysrq.c:send_sig_all
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_debug_helper
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_for_each
  - net/core/net-sysfs.c:proto_down_show
  - net/core/net-sysfs.c:group_show
  - net/core/net-sysfs.c:napi_defer_hard_irqs_show
  - net/core/net-sysfs.c:gro_flush_timeout_show
  - net/core/net-sysfs.c:tx_queue_len_show
  - net/core/net-sysfs.c:flags_show
  - net/core/net-sysfs.c:mtu_show
  - net/core/net-sysfs.c:operstate_show
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
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
  - net/sched/ematch.c:tcf_em_lookup
  - net/sched/ematch.c:tcf_em_lookup
  - net/netlink/af_netlink.c:netlink_set_err
  - net/ipv4/arp.c:arp_format_neigh_entry
  - net/ipv4/ipmr.c:ipmr_vif_seq_stop
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:reg_vif_xmit
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:rt6_score_route
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
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_stop
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff81f29c10-ffffffff81f29c43: _raw_read_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void _raw_read_unlock(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff820d5ae0)
Location: kernel/locking/spinlock.c:258
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks
  - kernel/fork.c:walk_process_tree
  - kernel/exit.c:do_wait
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:is_current_pgrp_orphaned
  - kernel/resource.c:resource_is_exclusive
  - kernel/resource.c:iomem_map_sanity_check
  - kernel/resource.c:lookup_resource
  - kernel/resource.c:region_intersects
  - kernel/resource.c:find_next_iomem_res
  - kernel/resource.c:find_next_iomem_res
  - kernel/resource.c:r_stop
  - kernel/ptrace.c:ptrace_check_attach
  - kernel/ptrace.c:ptrace_check_attach
  - kernel/ptrace.c:ptrace_check_attach
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:kill_pgrp
  - kernel/signal.c:kill_something_info
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/build_utility.c:sched_core_share_pid
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_start_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/rv/monitors/wwnr/wwnr.c:da_monitor_reset_all_wwnr
  - mm/mempolicy.c:mpol_shared_policy_lookup
  - mm/memory-failure.c:mf_dax_kill_procs
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:zs_unmap_object
  - fs/exec.c:search_binary_handler
  - fs/exec.c:search_binary_handler
  - fs/exec.c:search_binary_handler
  - fs/exec.c:search_binary_handler
  - fs/exec.c:de_thread
  - fs/exec.c:__do_sys_uselib
  - fs/exec.c:__do_sys_uselib
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:filesystems_proc_show
  - fs/filesystems.c:__ia32_sys_sysfs
  - fs/filesystems.c:__x64_sys_sysfs
  - fs/filesystems.c:fs_name
  - fs/filesystems.c:fs_name
  - fs/filesystems.c:fs_index
  - fs/filesystems.c:list_bdev_fs_names
  - fs/xattr.c:simple_xattr_list
  - fs/xattr.c:simple_xattr_list
  - fs/xattr.c:simple_xattr_get
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:chroot_fs_refs
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_readdir_de
  - fs/proc/generic.c:proc_readdir_de
  - fs/proc/generic.c:proc_readdir_de
  - fs/proc/generic.c:proc_readdir_de
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/array.c:get_children_pid
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:ext4_is_pending
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_scan_clu
  - fs/ext4/extents_status.c:ext4_es_scan_clu
  - fs/ext4/extents_status.c:ext4_es_scan_range
  - fs/ext4/extents_status.c:ext4_es_scan_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
  - fs/ext4/inode.c:ext4_wait_for_tail_page_commit
  - fs/ext4/inode.c:ext4_wait_for_tail_page_commit
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/mballoc.c:ext4_mb_seq_structs_summary_show
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/fast_commit.c:ext4_fc_mark_ineligible
  - fs/ext4/fast_commit.c:ext4_fc_mark_ineligible
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
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
  - fs/jbd2/journal.c:jbd2_journal_errno
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_transaction_committed
  - fs/jbd2/journal.c:jbd2_fc_end_commit_fallback
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - security/keys/keyring.c:find_keyring_by_name
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/integrity/iint.c:integrity_iint_find
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
  - drivers/xen/events/events_base.c:__xen_evtchn_do_upcall
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
  - drivers/tty/sysrq.c:send_sig_all
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_debug_helper
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_for_each
  - net/core/net-sysfs.c:proto_down_show
  - net/core/net-sysfs.c:group_show
  - net/core/net-sysfs.c:napi_defer_hard_irqs_show
  - net/core/net-sysfs.c:gro_flush_timeout_show
  - net/core/net-sysfs.c:tx_queue_len_show
  - net/core/net-sysfs.c:flags_show
  - net/core/net-sysfs.c:mtu_show
  - net/core/net-sysfs.c:operstate_show
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
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
  - net/sched/ematch.c:tcf_em_lookup
  - net/sched/ematch.c:tcf_em_lookup
  - net/netlink/af_netlink.c:netlink_set_err
  - net/ipv4/arp.c:arp_format_neigh_entry
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:rt6_score_route
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff820d5ae0-ffffffff820d5b13: _raw_read_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void _raw_read_unlock(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff82158ec0)
Location: kernel/locking/spinlock.c:258
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks
  - kernel/fork.c:walk_process_tree
  - kernel/exit.c:do_wait
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:is_current_pgrp_orphaned
  - kernel/resource.c:resource_is_exclusive
  - kernel/resource.c:iomem_map_sanity_check
  - kernel/resource.c:lookup_resource
  - kernel/resource.c:region_intersects
  - kernel/resource.c:find_next_iomem_res
  - kernel/resource.c:find_next_iomem_res
  - kernel/resource.c:r_stop
  - kernel/ptrace.c:ptrace_check_attach
  - kernel/ptrace.c:ptrace_check_attach
  - kernel/ptrace.c:ptrace_check_attach
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:kill_pgrp
  - kernel/signal.c:kill_something_info
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/build_utility.c:sched_core_share_pid
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_start_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/rv/monitors/wwnr/wwnr.c:da_monitor_reset_all_wwnr
  - mm/mempolicy.c:mpol_shared_policy_lookup
  - mm/ksm.c:collect_procs_ksm
  - mm/memory-failure.c:mf_dax_kill_procs
  - mm/memory-failure.c:collect_procs_anon
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:zs_unmap_object
  - fs/exec.c:search_binary_handler
  - fs/exec.c:search_binary_handler
  - fs/exec.c:search_binary_handler
  - fs/exec.c:search_binary_handler
  - fs/exec.c:de_thread
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:filesystems_proc_show
  - fs/filesystems.c:__ia32_sys_sysfs
  - fs/filesystems.c:__x64_sys_sysfs
  - fs/filesystems.c:fs_name
  - fs/filesystems.c:fs_name
  - fs/filesystems.c:fs_index
  - fs/filesystems.c:list_bdev_fs_names
  - fs/xattr.c:simple_xattr_list
  - fs/xattr.c:simple_xattr_list
  - fs/xattr.c:simple_xattr_get
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:chroot_fs_refs
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_readdir_de
  - fs/proc/generic.c:proc_readdir_de
  - fs/proc/generic.c:proc_readdir_de
  - fs/proc/generic.c:proc_readdir_de
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/array.c:get_children_pid
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:ext4_is_pending
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_scan_clu
  - fs/ext4/extents_status.c:ext4_es_scan_clu
  - fs/ext4/extents_status.c:ext4_es_scan_range
  - fs/ext4/extents_status.c:ext4_es_scan_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
  - fs/ext4/inode.c:ext4_wait_for_tail_page_commit
  - fs/ext4/inode.c:ext4_wait_for_tail_page_commit
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/mballoc.c:ext4_mb_pa_adjust_overlap
  - fs/ext4/mballoc.c:ext4_mb_pa_adjust_overlap
  - fs/ext4/mballoc.c:ext4_mb_seq_structs_summary_show
  - fs/ext4/mballoc.c:ext4_mb_find_good_group_avg_frag_lists
  - fs/ext4/mballoc.c:ext4_mb_find_good_group_avg_frag_lists
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/fast_commit.c:ext4_fc_mark_ineligible
  - fs/ext4/fast_commit.c:ext4_fc_mark_ineligible
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
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
  - fs/jbd2/journal.c:jbd2_journal_errno
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_transaction_committed
  - fs/jbd2/journal.c:jbd2_fc_end_commit_fallback
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - security/keys/keyring.c:find_keyring_by_name
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/integrity/iint.c:integrity_iint_find
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
  - drivers/xen/events/events_base.c:__xen_evtchn_do_upcall
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
  - drivers/tty/sysrq.c:send_sig_all
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_debug_helper
  - net/core/sock.c:sock_i_ino
  - net/core/net-sysfs.c:proto_down_show
  - net/core/net-sysfs.c:group_show
  - net/core/net-sysfs.c:napi_defer_hard_irqs_show
  - net/core/net-sysfs.c:gro_flush_timeout_show
  - net/core/net-sysfs.c:tx_queue_len_show
  - net/core/net-sysfs.c:flags_show
  - net/core/net-sysfs.c:mtu_show
  - net/core/net-sysfs.c:operstate_show
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
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
  - net/sched/ematch.c:tcf_em_lookup
  - net/sched/ematch.c:tcf_em_lookup
  - net/ipv4/arp.c:arp_format_neigh_entry
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff82158ec0-ffffffff82158ef3: _raw_read_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void _raw_read_unlock(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff8223c740)
Location: kernel/locking/spinlock.c:258
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks
  - kernel/fork.c:walk_process_tree
  - kernel/exit.c:__do_wait
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:is_current_pgrp_orphaned
  - kernel/resource.c:resource_is_exclusive
  - kernel/resource.c:iomem_map_sanity_check
  - kernel/resource.c:lookup_resource
  - kernel/resource.c:region_intersects
  - kernel/resource.c:find_next_iomem_res
  - kernel/resource.c:find_next_iomem_res
  - kernel/resource.c:r_stop
  - kernel/ptrace.c:ptrace_check_attach
  - kernel/ptrace.c:ptrace_check_attach
  - kernel/ptrace.c:ptrace_check_attach
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:kill_pgrp
  - kernel/signal.c:kill_something_info
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/build_utility.c:sched_core_share_pid
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_start_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/rv/monitors/wwnr/wwnr.c:da_monitor_reset_all_wwnr
  - mm/mempolicy.c:mpol_shared_policy_lookup
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:zs_unmap_object
  - fs/exec.c:search_binary_handler
  - fs/exec.c:search_binary_handler
  - fs/exec.c:search_binary_handler
  - fs/exec.c:search_binary_handler
  - fs/exec.c:de_thread
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:filesystems_proc_show
  - fs/filesystems.c:__ia32_sys_sysfs
  - fs/filesystems.c:__x64_sys_sysfs
  - fs/filesystems.c:fs_name
  - fs/filesystems.c:fs_name
  - fs/filesystems.c:fs_index
  - fs/filesystems.c:list_bdev_fs_names
  - fs/xattr.c:simple_xattr_list
  - fs/xattr.c:simple_xattr_list
  - fs/xattr.c:simple_xattr_get
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:chroot_fs_refs
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_readdir_de
  - fs/proc/generic.c:proc_readdir_de
  - fs/proc/generic.c:proc_readdir_de
  - fs/proc/generic.c:proc_readdir_de
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/array.c:get_children_pid
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:ext4_is_pending
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_scan_clu
  - fs/ext4/extents_status.c:ext4_es_scan_clu
  - fs/ext4/extents_status.c:ext4_es_scan_range
  - fs/ext4/extents_status.c:ext4_es_scan_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
  - fs/ext4/inode.c:ext4_wait_for_tail_page_commit
  - fs/ext4/inode.c:ext4_wait_for_tail_page_commit
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/mballoc.c:ext4_mb_pa_adjust_overlap
  - fs/ext4/mballoc.c:ext4_mb_pa_adjust_overlap
  - fs/ext4/mballoc.c:ext4_mb_seq_structs_summary_show
  - fs/ext4/mballoc.c:ext4_mb_find_good_group_avg_frag_lists
  - fs/ext4/mballoc.c:ext4_mb_find_good_group_avg_frag_lists
  - fs/ext4/mballoc.c:ext4_mb_choose_next_group_p2_aligned
  - fs/ext4/mballoc.c:ext4_mb_choose_next_group_p2_aligned
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/fast_commit.c:ext4_fc_mark_ineligible
  - fs/ext4/fast_commit.c:ext4_fc_mark_ineligible
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
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
  - fs/jbd2/journal.c:jbd2_journal_errno
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_transaction_committed
  - fs/jbd2/journal.c:jbd2_fc_end_commit_fallback
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - security/keys/keyring.c:find_keyring_by_name
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/integrity/iint.c:integrity_iint_find
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
  - drivers/tty/sysrq.c:send_sig_all
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_debug_helper
  - drivers/gpu/drm/drm_gem.c:drm_gem_mmap
  - drivers/gpu/drm/drm_gem.c:drm_gem_mmap
  - drivers/gpu/drm/drm_vma_manager.c:drm_vma_node_is_allowed
  - drivers/gpu/drm/drm_vma_manager.c:drm_vma_node_is_allowed
  - net/core/sock.c:sock_i_ino
  - net/core/net-sysfs.c:proto_down_show
  - net/core/net-sysfs.c:group_show
  - net/core/net-sysfs.c:napi_defer_hard_irqs_show
  - net/core/net-sysfs.c:gro_flush_timeout_show
  - net/core/net-sysfs.c:tx_queue_len_show
  - net/core/net-sysfs.c:flags_show
  - net/core/net-sysfs.c:mtu_show
  - net/core/net-sysfs.c:operstate_show
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
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
  - net/sched/ematch.c:tcf_em_lookup
  - net/sched/ematch.c:tcf_em_lookup
  - net/ipv4/arp.c:arp_format_neigh_entry
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff8223c740-ffffffff8223c773: _raw_read_unlock (STB_GLOBAL)
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
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void _raw_read_unlock(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81aec5e0)
Location: kernel/locking/spinlock.c:253
Inline: False
Direct callers:
  - kernel/fork.c:walk_process_tree
  - kernel/exit.c:do_wait
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:is_current_pgrp_orphaned
  - kernel/resource.c:iomem_is_exclusive
  - kernel/resource.c:iomem_map_sanity_check
  - kernel/resource.c:lookup_resource
  - kernel/resource.c:region_intersects
  - kernel/resource.c:region_intersects
  - kernel/resource.c:find_next_iomem_res
  - kernel/resource.c:find_next_iomem_res
  - kernel/resource.c:r_stop
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:kill_pgrp
  - kernel/signal.c:kill_something_info
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/cgroup/cgroup.c:cgroup_enable_task_cg_lists
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
  - mm/mempolicy.c:mpol_shared_policy_lookup
  - mm/mempolicy.c:mpol_shared_policy_lookup
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_unmap_object
  - fs/exec.c:de_thread
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/exec.c:__x64_sys_uselib
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_getown
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:filesystems_proc_show
  - fs/filesystems.c:fs_maxindex
  - fs/filesystems.c:fs_name
  - fs/filesystems.c:fs_name
  - fs/filesystems.c:fs_index
  - fs/filesystems.c:get_filesystem_list
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:chroot_fs_refs
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/array.c:get_children_pid
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:ext4_is_pending
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_scan_clu
  - fs/ext4/extents_status.c:ext4_es_scan_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/super.c:ext4_sync_fs
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
  - fs/jbd2/journal.c:jbd2_journal_errno
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_transaction_committed
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - security/keys/keyring.c:find_keyring_by_name
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/ss/services.c:security_read_policy
  - security/selinux/ss/services.c:security_read_policy
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:selinux_audit_rule_init
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
  - security/selinux/ss/services.c:security_get_user_sids
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
  - security/integrity/iint.c:integrity_iint_find
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
  - drivers/tty/sysrq.c:send_sig_all
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_for_each
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:address_show
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
  - net/sched/ematch.c:tcf_em_lookup
  - net/sched/ematch.c:tcf_em_lookup
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/arp.c:arp_seq_show
  - net/ipv4/ipmr.c:ipmr_vif_seq_stop
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:reg_vif_xmit
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/mcast.c:inet6_mc_check
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
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_stop
```
**Symbols:**

```
ffffffff81aec5e0-ffffffff81aec603: _raw_read_unlock (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
</ul>

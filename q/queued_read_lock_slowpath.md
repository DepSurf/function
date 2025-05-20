# Function: <code>queued_read_lock_slowpath</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void queued_read_lock_slowpath(struct qrwlock *lock, u32 cnts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qrwlock.c (ffffffff810cbdc0)
Location: kernel/locking/qrwlock.c:67
Inline: False
Direct callers:
  - kernel/locking/spinlock.c:_raw_read_lock
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_irqsave
```
**Symbols:**

```
ffffffff810cbdc0-ffffffff810cbe51: queued_read_lock_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void queued_read_lock_slowpath(struct qrwlock *lock, u32 cnts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qrwlock.c (ffffffff810d08d0)
Location: kernel/locking/qrwlock.c:67
Inline: False
Direct callers:
  - kernel/locking/spinlock.c:_raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock
```
**Symbols:**

```
ffffffff810d08d0-ffffffff810d0961: queued_read_lock_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void queued_read_lock_slowpath(struct qrwlock *lock, u32 cnts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qrwlock.c (ffffffff810d7340)
Location: kernel/locking/qrwlock.c:67
Inline: False
Direct callers:
  - kernel/locking/spinlock.c:_raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock
```
**Symbols:**

```
ffffffff810d7340-ffffffff810d73d1: queued_read_lock_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void queued_read_lock_slowpath(struct qrwlock *lock, u32 cnts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qrwlock.c (ffffffff810d6380)
Location: kernel/locking/qrwlock.c:68
Inline: False
Direct callers:
  - kernel/locking/spinlock.c:_raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock
```
**Symbols:**

```
ffffffff810d6380-ffffffff810d6411: queued_read_lock_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void queued_read_lock_slowpath(struct qrwlock *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qrwlock.c (ffffffff810de330)
Location: kernel/locking/qrwlock.c:30
Inline: False
Direct callers:
  - kernel/locking/spinlock.c:_raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock
```
**Symbols:**

```
ffffffff810de330-ffffffff810de3a5: queued_read_lock_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void queued_read_lock_slowpath(struct qrwlock *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qrwlock.c (ffffffff810e6900)
Location: kernel/locking/qrwlock.c:30
Inline: False
Direct callers:
  - kernel/locking/spinlock.c:_raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock
```
**Symbols:**

```
ffffffff810e6900-ffffffff810e697b: queued_read_lock_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void queued_read_lock_slowpath(struct qrwlock *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qrwlock.c (ffffffff810f1f00)
Location: kernel/locking/qrwlock.c:30
Inline: False
Direct callers:
  - kernel/locking/spinlock.c:_raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock
```
**Symbols:**

```
ffffffff810f1f00-ffffffff810f1f79: queued_read_lock_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void queued_read_lock_slowpath(struct qrwlock *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qrwlock.c (ffffffff810fa470)
Location: kernel/locking/qrwlock.c:21
Inline: False
Direct callers:
  - kernel/locking/spinlock.c:_raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock
```
**Symbols:**

```
ffffffff810fa470-ffffffff810fa4e9: queued_read_lock_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void queued_read_lock_slowpath(struct qrwlock *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qrwlock.c (ffffffff81106250)
Location: kernel/locking/qrwlock.c:21
Inline: False
Direct callers:
  - kernel/locking/spinlock.c:_raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock
```
**Symbols:**

```
ffffffff81106250-ffffffff811062c9: queued_read_lock_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void queued_read_lock_slowpath(struct qrwlock *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qrwlock.c (ffffffff81111170)
Location: kernel/locking/qrwlock.c:21
Inline: False
Direct callers:
  - kernel/locking/spinlock.c:_raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock
```
**Symbols:**

```
ffffffff81111170-ffffffff811111e9: queued_read_lock_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void queued_read_lock_slowpath(struct qrwlock *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qrwlock.c (ffffffff8110e2f0)
Location: kernel/locking/qrwlock.c:21
Inline: False
Direct callers:
  - kernel/locking/spinlock.c:_raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock
```
**Symbols:**

```
ffffffff8110e2f0-ffffffff8110e369: queued_read_lock_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void queued_read_lock_slowpath(struct qrwlock *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qrwlock.c (ffffffff8110ee00)
Location: kernel/locking/qrwlock.c:20
Inline: False
Direct callers:
  - kernel/locking/spinlock.c:_raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock
```
**Symbols:**

```
ffffffff8110ee00-ffffffff8110ee79: queued_read_lock_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void queued_read_lock_slowpath(struct qrwlock *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qrwlock.c (ffffffff8112e6a0)
Location: kernel/locking/qrwlock.c:20
Inline: False
Direct callers:
  - kernel/locking/spinlock.c:_raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock
```
**Symbols:**

```
ffffffff8112e6a0-ffffffff8112e719: queued_read_lock_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void queued_read_lock_slowpath(struct qrwlock *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qrwlock.c (ffffffff8114f8c0)
Location: kernel/locking/qrwlock.c:21
Inline: False
Direct callers:
  - kernel/locking/spinlock.c:__raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock
```
**Symbols:**

```
ffffffff8114f8c0-ffffffff8114fa15: queued_read_lock_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void queued_read_lock_slowpath(struct qrwlock *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qrwlock.c (ffffffff820d6c10)
Location: kernel/locking/qrwlock.c:21
Inline: False
Direct callers:
  - kernel/locking/spinlock.c:__raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock
```
**Symbols:**

```
ffffffff820d6c10-ffffffff820d6d65: queued_read_lock_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void queued_read_lock_slowpath(struct qrwlock *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qrwlock.c (ffffffff82159fa0)
Location: kernel/locking/qrwlock.c:21
Inline: False
Direct callers:
  - kernel/locking/spinlock.c:__raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock
```
**Symbols:**

```
ffffffff82159fa0-ffffffff8215a0f5: queued_read_lock_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void queued_read_lock_slowpath(struct qrwlock *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qrwlock.c (ffffffff8223d820)
Location: kernel/locking/qrwlock.c:21
Inline: False
Direct callers:
  - kernel/locking/spinlock.c:__raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock
```
**Symbols:**

```
ffffffff8223d820-ffffffff8223d975: queued_read_lock_slowpath (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void queued_read_lock_slowpath(struct qrwlock *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qrwlock.c (ffff80001016c708)
Location: kernel/locking/qrwlock.c:21
Inline: False
Direct callers:
  - arch/arm/xen/p2m.c:__pfn_to_mfn
  - kernel/fork.c:walk_process_tree
  - kernel/exit.c:do_wait
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:is_current_pgrp_orphaned
  - kernel/resource.c:iomem_is_exclusive
  - kernel/resource.c:iomem_map_sanity_check
  - kernel/resource.c:lookup_resource
  - kernel/resource.c:region_intersects
  - kernel/resource.c:find_next_iomem_res
  - kernel/resource.c:r_start
  - kernel/ptrace.c:ptrace_check_attach
  - kernel/signal.c:__arm64_sys_kill
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:kill_pgrp
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:__arm64_sys_getpriority
  - kernel/sys.c:__arm64_sys_setpriority
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:tg_set_rt_bandwidth
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/cgroup/cgroup.c:cgroup_enable_task_cg_lists
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
  - mm/mempolicy.c:mpol_shared_policy_lookup
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_map_object
  - fs/exec.c:de_thread
  - fs/exec.c:__arm64_sys_uselib
  - fs/exec.c:__arm64_sys_uselib
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_getown
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:filesystems_proc_show
  - fs/filesystems.c:__arm64_sys_sysfs
  - fs/filesystems.c:__arm64_sys_sysfs
  - fs/filesystems.c:fs_name
  - fs/fs_struct.c:chroot_fs_refs
  - fs/eventpoll.c:ep_poll_callback
  - fs/proc/generic.c:__proc_create
  - fs/proc/array.c:get_children_pid
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:ext4_is_pending
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_scan_clu
  - fs/ext4/extents_status.c:ext4_es_scan_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/super.c:ext4_sync_fs
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/journal.c:jbd2_journal_errno
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_transaction_committed
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - security/keys/keyring.c:find_keyring_by_name
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/ss/services.c:security_read_policy
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_policycap_supported
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
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:vec_find
  - security/integrity/iint.c:integrity_iint_find
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
  - drivers/tty/sysrq.c:send_sig_all
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
  - drivers/scsi/sg.c:sg_open
  - drivers/net/ppp/ppp_generic.c:ppp_dev_name
  - drivers/net/ppp/ppp_generic.c:ppp_unit_number
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - drivers/cpufreq/cpufreq.c:cpufreq_quick_get
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_get
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
  - net/core/sock.c:sock_i_ino
  - net/core/sock.c:sock_i_uid
  - net/core/neighbour.c:neigh_seq_start
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:pneigh_lookup
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:address_show
  - net/core/netpoll.c:netpoll_setup
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_get_default
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
  - net/ipv4/raw.c:raw_seq_start
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/arp.c:arp_seq_show
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/ping.c:ping_seq_start
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ipmr.c:ipmr_vif_seq_start
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:reg_vif_xmit
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/ipv6/anycast.c:ac6_seq_start
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:addrconf_dad_run
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:ipv6_mc_up
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_unmap
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_start
```
**Symbols:**

```
ffff80001016c708-ffff80001016c854: queued_read_lock_slowpath (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void queued_read_lock_slowpath(struct qrwlock *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qrwlock.c (ffffffff810ff560)
Location: kernel/locking/qrwlock.c:21
Inline: False
Direct callers:
  - kernel/locking/spinlock.c:_raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock
```
**Symbols:**

```
ffffffff810ff560-ffffffff810ff5d9: queued_read_lock_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void queued_read_lock_slowpath(struct qrwlock *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qrwlock.c (ffffffff810ef750)
Location: kernel/locking/qrwlock.c:21
Inline: False
Direct callers:
  - kernel/locking/spinlock.c:_raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock
```
**Symbols:**

```
ffffffff810ef750-ffffffff810ef7c9: queued_read_lock_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void queued_read_lock_slowpath(struct qrwlock *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qrwlock.c (ffffffff810fc720)
Location: kernel/locking/qrwlock.c:21
Inline: False
Direct callers:
  - kernel/locking/spinlock.c:_raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock
```
**Symbols:**

```
ffffffff810fc720-ffffffff810fc799: queued_read_lock_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void queued_read_lock_slowpath(struct qrwlock *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qrwlock.c (ffffffff81107950)
Location: kernel/locking/qrwlock.c:21
Inline: False
Direct callers:
  - kernel/locking/spinlock.c:_raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock
```
**Symbols:**

```
ffffffff81107950-ffffffff811079c9: queued_read_lock_slowpath (STB_GLOBAL)
```
</details>
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u32 cnts</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>

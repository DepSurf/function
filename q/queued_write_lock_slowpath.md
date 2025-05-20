# Function: <code>queued_write_lock_slowpath</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void queued_write_lock_slowpath(struct qrwlock *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qrwlock.c (ffffffff810cbd30)
Location: kernel/locking/qrwlock.c:110
Inline: False
Direct callers:
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
  - kernel/locking/spinlock.c:_raw_write_lock
  - kernel/locking/spinlock.c:_raw_write_lock_irq
  - kernel/locking/spinlock.c:_raw_write_lock_bh
```
**Symbols:**

```
ffffffff810cbd30-ffffffff810cbdb4: queued_write_lock_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void queued_write_lock_slowpath(struct qrwlock *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qrwlock.c (ffffffff810d0840)
Location: kernel/locking/qrwlock.c:110
Inline: False
Direct callers:
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
  - kernel/locking/spinlock.c:_raw_write_lock_irq
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_write_lock
```
**Symbols:**

```
ffffffff810d0840-ffffffff810d08c4: queued_write_lock_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void queued_write_lock_slowpath(struct qrwlock *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qrwlock.c (ffffffff810d72b0)
Location: kernel/locking/qrwlock.c:110
Inline: False
Direct callers:
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
  - kernel/locking/spinlock.c:_raw_write_lock_irq
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_write_lock
```
**Symbols:**

```
ffffffff810d72b0-ffffffff810d7334: queued_write_lock_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void queued_write_lock_slowpath(struct qrwlock *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qrwlock.c (ffffffff810d62f0)
Location: kernel/locking/qrwlock.c:111
Inline: False
Direct callers:
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
  - kernel/locking/spinlock.c:_raw_write_lock_irq
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_write_lock
```
**Symbols:**

```
ffffffff810d62f0-ffffffff810d6374: queued_write_lock_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void queued_write_lock_slowpath(struct qrwlock *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qrwlock.c (ffffffff810de2a0)
Location: kernel/locking/qrwlock.c:71
Inline: False
Direct callers:
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
  - kernel/locking/spinlock.c:_raw_write_lock_irq
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_write_lock
```
**Symbols:**

```
ffffffff810de2a0-ffffffff810de326: queued_write_lock_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void queued_write_lock_slowpath(struct qrwlock *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qrwlock.c (ffffffff810e6980)
Location: kernel/locking/qrwlock.c:71
Inline: False
Direct callers:
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
  - kernel/locking/spinlock.c:_raw_write_lock_irq
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_write_lock
```
**Symbols:**

```
ffffffff810e6980-ffffffff810e6a06: queued_write_lock_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void queued_write_lock_slowpath(struct qrwlock *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qrwlock.c (ffffffff810f1f80)
Location: kernel/locking/qrwlock.c:71
Inline: False
Direct callers:
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
  - kernel/locking/spinlock.c:_raw_write_lock_irq
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_write_lock
```
**Symbols:**

```
ffffffff810f1f80-ffffffff810f2004: queued_write_lock_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void queued_write_lock_slowpath(struct qrwlock *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qrwlock.c (ffffffff810fa3e0)
Location: kernel/locking/qrwlock.c:62
Inline: False
Direct callers:
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
  - kernel/locking/spinlock.c:_raw_write_lock_irq
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_write_lock
```
**Symbols:**

```
ffffffff810fa3e0-ffffffff810fa464: queued_write_lock_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void queued_write_lock_slowpath(struct qrwlock *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qrwlock.c (ffffffff811061c0)
Location: kernel/locking/qrwlock.c:62
Inline: False
Direct callers:
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
  - kernel/locking/spinlock.c:_raw_write_lock_irq
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_write_lock
```
**Symbols:**

```
ffffffff811061c0-ffffffff81106244: queued_write_lock_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void queued_write_lock_slowpath(struct qrwlock *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qrwlock.c (ffffffff811111f0)
Location: kernel/locking/qrwlock.c:62
Inline: False
Direct callers:
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
  - kernel/locking/spinlock.c:_raw_write_lock_irq
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_write_lock
```
**Symbols:**

```
ffffffff811111f0-ffffffff81111273: queued_write_lock_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void queued_write_lock_slowpath(struct qrwlock *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qrwlock.c (ffffffff8110e370)
Location: kernel/locking/qrwlock.c:62
Inline: False
Direct callers:
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
  - kernel/locking/spinlock.c:_raw_write_lock_irq
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_write_lock
```
**Symbols:**

```
ffffffff8110e370-ffffffff8110e3f3: queued_write_lock_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void queued_write_lock_slowpath(struct qrwlock *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qrwlock.c (ffffffff8110ee80)
Location: kernel/locking/qrwlock.c:61
Inline: False
Direct callers:
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
  - kernel/locking/spinlock.c:_raw_write_lock_irq
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_write_lock
```
**Symbols:**

```
ffffffff8110ee80-ffffffff8110eefe: queued_write_lock_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void queued_write_lock_slowpath(struct qrwlock *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qrwlock.c (ffffffff8112e720)
Location: kernel/locking/qrwlock.c:61
Inline: False
Direct callers:
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
  - kernel/locking/spinlock.c:_raw_write_lock_irq
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_write_lock
```
**Symbols:**

```
ffffffff8112e720-ffffffff8112e79e: queued_write_lock_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void queued_write_lock_slowpath(struct qrwlock *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qrwlock.c (ffffffff8114fa20)
Location: kernel/locking/qrwlock.c:66
Inline: False
Direct callers:
  - kernel/locking/spinlock.c:__raw_write_lock_irqsave
  - kernel/locking/spinlock.c:_raw_write_lock_irq
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_write_lock_nested
  - kernel/locking/spinlock.c:_raw_write_lock
```
**Symbols:**

```
ffffffff8114fa20-ffffffff8114fb68: queued_write_lock_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void queued_write_lock_slowpath(struct qrwlock *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qrwlock.c (ffffffff820d6d80)
Location: kernel/locking/qrwlock.c:66
Inline: False
Direct callers:
  - kernel/locking/spinlock.c:__raw_write_lock_irqsave
  - kernel/locking/spinlock.c:_raw_write_lock_irq
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_write_lock_nested
  - kernel/locking/spinlock.c:_raw_write_lock
```
**Symbols:**

```
ffffffff820d6d80-ffffffff820d6ec8: queued_write_lock_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void queued_write_lock_slowpath(struct qrwlock *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qrwlock.c (ffffffff8215a110)
Location: kernel/locking/qrwlock.c:66
Inline: False
Direct callers:
  - kernel/locking/spinlock.c:__raw_write_lock_irqsave
  - kernel/locking/spinlock.c:_raw_write_lock_irq
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_write_lock_nested
  - kernel/locking/spinlock.c:_raw_write_lock
```
**Symbols:**

```
ffffffff8215a110-ffffffff8215a258: queued_write_lock_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void queued_write_lock_slowpath(struct qrwlock *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qrwlock.c (ffffffff8223d990)
Location: kernel/locking/qrwlock.c:66
Inline: False
Direct callers:
  - kernel/locking/spinlock.c:__raw_write_lock_irqsave
  - kernel/locking/spinlock.c:_raw_write_lock_irq
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_write_lock_nested
  - kernel/locking/spinlock.c:_raw_write_lock
```
**Symbols:**

```
ffffffff8223d990-ffffffff8223dad8: queued_write_lock_slowpath (STB_GLOBAL)
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
void queued_write_lock_slowpath(struct qrwlock *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qrwlock.c (ffff80001016c858)
Location: kernel/locking/qrwlock.c:62
Inline: False
Direct callers:
  - arch/arm/xen/p2m.c:__set_phys_to_machine_multi
  - arch/arm/xen/p2m.c:__set_phys_to_machine_multi
  - kernel/fork.c:copy_process
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
  - kernel/resource.c:__release_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:adjust_resource
  - kernel/resource.c:remove_resource
  - kernel/resource.c:insert_resource_expand_to_fit
  - kernel/resource.c:insert_resource_conflict
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:release_resource
  - kernel/resource.c:request_resource_conflict
  - kernel/resource.c:release_child_resources
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__arm64_sys_setpgid
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
  - kernel/bpf/reuseport_array.c:bpf_sk_reuseport_detach
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/zsmalloc.c:zs_page_migrate
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:unregister_binfmt
  - fs/exec.c:__register_binfmt
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_modown
  - fs/filesystems.c:unregister_filesystem
  - fs/filesystems.c:register_filesystem
  - fs/eventpoll.c:__do_sys_epoll_ctl
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_remove
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:proc_register
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_remove_pending
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:ext4_es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/super.c:ext4_init_journal_params
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_unlock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_ack_err
  - fs/jbd2/journal.c:jbd2_journal_clear_err
  - fs/jbd2/journal.c:__journal_abort_soft
  - fs/jbd2/journal.c:__journal_abort_soft
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_start_commit
  - fs/jbd2/journal.c:jbd2_log_start_commit
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_instantiate
  - security/keys/keyring.c:key_free_user_ns
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_update_label_name
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_remove
  - security/integrity/iint.c:integrity_inode_free
  - security/integrity/iint.c:integrity_inode_get
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
  - net/core/sock.c:sk_common_release
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/neighbour.c:__neigh_for_each_release
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:__neigh_ifdown
  - net/core/neighbour.c:neigh_changeaddr
  - net/core/neighbour.c:neigh_remove_one
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:set_operstate
  - net/core/link_watch.c:rfc2863_policy
  - net/core/skmsg.c:sk_psock_strp_data_ready
  - net/core/skmsg.c:sk_psock_drop
  - net/core/sock_map.c:sock_map_unref
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:unregister_qdisc
  - net/sched/sch_api.c:register_qdisc
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/sched/cls_api.c:register_tcf_proto_ops
  - net/sched/act_api.c:tcf_unregister_action
  - net/sched/ematch.c:tcf_em_unregister
  - net/sched/ematch.c:tcf_em_register
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/ip6_fib.c:fib6_walker_unlink
  - net/ipv6/ip6_fib.c:fib6_walker_link
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ip6_mc_leave_src
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:mif6_delete
  - net/packet/af_packet.c:packet_release
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffff80001016c858-ffff80001016c9c8: queued_write_lock_slowpath (STB_GLOBAL)
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
void queued_write_lock_slowpath(struct qrwlock *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qrwlock.c (ffffffff810ff4d0)
Location: kernel/locking/qrwlock.c:62
Inline: False
Direct callers:
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
  - kernel/locking/spinlock.c:_raw_write_lock_irq
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_write_lock
```
**Symbols:**

```
ffffffff810ff4d0-ffffffff810ff554: queued_write_lock_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void queued_write_lock_slowpath(struct qrwlock *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qrwlock.c (ffffffff810ef6c0)
Location: kernel/locking/qrwlock.c:62
Inline: False
Direct callers:
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
  - kernel/locking/spinlock.c:_raw_write_lock_irq
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_write_lock
```
**Symbols:**

```
ffffffff810ef6c0-ffffffff810ef744: queued_write_lock_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void queued_write_lock_slowpath(struct qrwlock *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qrwlock.c (ffffffff810fc690)
Location: kernel/locking/qrwlock.c:62
Inline: False
Direct callers:
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
  - kernel/locking/spinlock.c:_raw_write_lock_irq
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_write_lock
```
**Symbols:**

```
ffffffff810fc690-ffffffff810fc714: queued_write_lock_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void queued_write_lock_slowpath(struct qrwlock *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qrwlock.c (ffffffff811078c0)
Location: kernel/locking/qrwlock.c:62
Inline: False
Direct callers:
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
  - kernel/locking/spinlock.c:_raw_write_lock_irq
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_write_lock
```
**Symbols:**

```
ffffffff811078c0-ffffffff81107944: queued_write_lock_slowpath (STB_GLOBAL)
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
No changes between <code>4.13</code> and <code>4.15</code> ✅
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

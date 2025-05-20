# Function: <code>queued_write_unlock</code>

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
In kernel/fork.c (ffffffff8107f461)
Location: include/asm-generic/qrwlock.h:140
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff81082788)
Location: include/asm-generic/qrwlock.h:140
Inline: True
Inline callers:
  - kernel/exit.c:release_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/resource.c (ffffffff81085ff9)
Location: include/asm-generic/qrwlock.h:140
Inline: True
Inline callers:
  - kernel/resource.c:request_resource
  - kernel/resource.c:release_resource
  - kernel/resource.c:adjust_resource
  - kernel/resource.c:devm_request_resource
  - kernel/resource.c:__release_region
  - kernel/resource.c:__release_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:release_child_resources
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:insert_resource
  - kernel/resource.c:insert_resource_expand_to_fit
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:release_mem_region_adjustable
```
```
In kernel/ptrace.c (ffffffff8108acca)
Location: include/asm-generic/qrwlock.h:140
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/sys.c (ffffffff81094c38)
Location: include/asm-generic/qrwlock.h:140
Inline: True
Inline callers:
  - kernel/sys.c:SyS_setpgid
  - kernel/sys.c:sys_setsid
```
```
In kernel/locking/spinlock.c (ffffffff81823f49)
Location: include/asm-generic/qrwlock.h:140
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_write_unlock_bh
```
```
In kernel/trace/trace_uprobe.c (ffffffff8116f94e)
Location: include/asm-generic/qrwlock.h:140
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
```
In fs/exec.c (ffffffff81211fe2)
Location: include/asm-generic/qrwlock.h:140
Inline: True
Inline callers:
  - fs/exec.c:unregister_binfmt
```
```
In fs/fcntl.c (ffffffff8121eb46)
Location: include/asm-generic/qrwlock.h:140
Inline: True
Inline callers:
  - fs/fcntl.c:f_modown
```
```
In fs/filesystems.c (ffffffff8122b11d)
Location: include/asm-generic/qrwlock.h:140
Inline: True
Inline callers:
  - fs/filesystems.c:unregister_filesystem
  - fs/filesystems.c:unregister_filesystem
```
```
In fs/proc/generic.c (ffffffff8127f2c1)
Location: include/asm-generic/qrwlock.h:140
Inline: True
Inline callers:
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
```
```
In fs/proc/kcore.c (ffffffff81286de9)
Location: include/asm-generic/qrwlock.h:140
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In fs/ext4/super.c (ffffffff812a8f95)
Location: include/asm-generic/qrwlock.h:140
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_journal_params
```
```
In fs/ext4/extents_status.c (ffffffff812db5df)
Location: include/asm-generic/qrwlock.h:140
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_remove_extent
```
```
In fs/jbd2/transaction.c (ffffffff812e6e77)
Location: include/asm-generic/qrwlock.h:140
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_unlock_updates
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff812e9ed2)
Location: include/asm-generic/qrwlock.h:140
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff812ed0e6)
Location: include/asm-generic/qrwlock.h:140
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
```
```
In fs/jbd2/journal.c (ffffffff812ee044)
Location: include/asm-generic/qrwlock.h:140
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_clear_err
  - fs/jbd2/journal.c:jbd2_journal_ack_err
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_journal_start_commit
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
```
```
In security/keys/keyring.c (ffffffff813308f8)
Location: include/asm-generic/qrwlock.h:140
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_instantiate
  - security/keys/keyring.c:keyring_destroy
```
```
In security/keys/keyctl.c (ffffffff813334c2)
Location: include/asm-generic/qrwlock.h:140
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/selinux/ss/services.c (ffffffff813596dd)
Location: include/asm-generic/qrwlock.h:140
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_set_bools
```
```
In security/integrity/iint.c (ffffffff81396374)
Location: include/asm-generic/qrwlock.h:140
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/iint.c:integrity_inode_free
```
```
In drivers/scsi/sg.c (ffffffff815c68e9)
Location: include/asm-generic/qrwlock.h:140
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
```
In net/core/gen_estimator.c (ffffffff8170f6bc)
Location: include/asm-generic/qrwlock.h:140
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_kill_estimator
```
```
In net/core/neighbour.c (ffffffff8172484e)
Location: include/asm-generic/qrwlock.h:140
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_probe
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:__neigh_for_each_release
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:__neigh_create
  - net/core/neighbour.c:__neigh_create
```
```
In net/sched/sch_api.c (ffffffff817425f6)
Location: include/asm-generic/qrwlock.h:140
Inline: True
Inline callers:
  - net/sched/sch_api.c:unregister_qdisc
  - net/sched/sch_api.c:register_qdisc
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
```
```
In net/sched/cls_api.c (ffffffff81745aa4)
Location: include/asm-generic/qrwlock.h:140
Inline: True
Inline callers:
  - net/sched/cls_api.c:register_tcf_proto_ops
  - net/sched/cls_api.c:unregister_tcf_proto_ops
```
```
In net/sched/act_api.c (ffffffff81746eeb)
Location: include/asm-generic/qrwlock.h:140
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_unregister_action
```
```
In net/sched/ematch.c (ffffffff8174949e)
Location: include/asm-generic/qrwlock.h:140
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_register
  - net/sched/ematch.c:tcf_em_unregister
```
```
In net/netlink/af_netlink.c (ffffffff8174d251)
Location: include/asm-generic/qrwlock.h:140
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_table_ungrab
```
```
In net/ipv6/addrconf.c (ffffffff817ca84d)
Location: include/asm-generic/qrwlock.h:140
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
```
```
In net/ipv6/route.c (ffffffff817d5852)
Location: include/asm-generic/qrwlock.h:140
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff817ec626)
Location: include/asm-generic/qrwlock.h:140
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_msfilter
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
In kernel/fork.c (ffffffff81081617)
Location: include/asm-generic/qrwlock.h:163
Inline: True
```
```
In kernel/exit.c (ffffffff810863bf)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/resource.c (ffffffff81089546)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - kernel/resource.c:devm_request_resource
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__release_region
  - kernel/resource.c:__release_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:adjust_resource
  - kernel/resource.c:remove_resource
  - kernel/resource.c:insert_resource_expand_to_fit
  - kernel/resource.c:insert_resource
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:release_resource
  - kernel/resource.c:request_resource
  - kernel/resource.c:release_child_resources
```
```
In kernel/ptrace.c (ffffffff8108f0ee)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/sys.c (ffffffff810980d9)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - kernel/sys.c:sys_setsid
  - kernel/sys.c:SyS_setpgid
```
```
In kernel/locking/spinlock.c (ffffffff8189ebf9)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_write_unlock_bh
```
```
In kernel/trace/trace_uprobe.c (ffffffff8117d95b)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
```
In mm/mempolicy.c (ffffffff81201cbe)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
```
```
In mm/zsmalloc.c (ffffffff8122b476)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/exec.c (ffffffff81238ab2)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - fs/exec.c:unregister_binfmt
```
```
In fs/fcntl.c (ffffffff812464d6)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - fs/fcntl.c:f_modown
```
```
In fs/filesystems.c (ffffffff8125387d)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - fs/filesystems.c:unregister_filesystem
  - fs/filesystems.c:unregister_filesystem
```
```
In fs/proc/generic.c (ffffffff812acbb1)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_entry
```
```
In fs/proc/kcore.c (ffffffff812b3fc3)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In fs/ext4/super.c (ffffffff812d813e)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_journal_params
```
```
In fs/ext4/extents_status.c (ffffffff8130af5f)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:ext4_es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
```
In fs/jbd2/transaction.c (ffffffff81316f63)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_unlock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/jbd2/commit.c (ffffffff813179f1)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff8131ab56)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
```
```
In fs/jbd2/journal.c (ffffffff8131b9f1)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_ack_err
  - fs/jbd2/journal.c:jbd2_journal_clear_err
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_journal_start_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
```
```
In security/keys/keyring.c (ffffffff813658b2)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_instantiate
```
```
In security/keys/keyctl.c (ffffffff81368366)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/selinux/ss/services.c (ffffffff8138f927)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
```
In security/integrity/iint.c (ffffffff813d214c)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_free
  - security/integrity/iint.c:integrity_inode_get
```
```
In drivers/scsi/sg.c (ffffffff8161f142)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
```
In net/core/gen_estimator.c (ffffffff81776faa)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_kill_estimator
```
```
In net/core/neighbour.c (ffffffff81791421)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_for_each_release
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_probe
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:__neigh_create
  - net/core/neighbour.c:__neigh_create
```
```
In net/sched/sch_api.c (ffffffff817b1675)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:unregister_qdisc
  - net/sched/sch_api.c:register_qdisc
```
```
In net/sched/cls_api.c (ffffffff817b2a32)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/sched/cls_api.c:register_tcf_proto_ops
```
```
In net/sched/act_api.c (ffffffff817b4145)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_unregister_action
```
```
In net/sched/ematch.c (ffffffff817b6474)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_unregister
  - net/sched/ematch.c:tcf_em_register
```
```
In net/netlink/af_netlink.c (ffffffff817b96b9)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_table_ungrab
```
```
In net/ipv6/addrconf.c (ffffffff8183ceff)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
```
```
In net/ipv6/route.c (ffffffff81843c99)
Location: include/asm-generic/qrwlock.h:163
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff8185b2f6)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
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
In kernel/fork.c (ffffffff8108604f)
Location: include/asm-generic/qrwlock.h:163
Inline: True
```
```
In kernel/exit.c (ffffffff8108b32f)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/resource.c (ffffffff8108e496)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - kernel/resource.c:devm_request_resource
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__release_region
  - kernel/resource.c:__release_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:adjust_resource
  - kernel/resource.c:remove_resource
  - kernel/resource.c:insert_resource_expand_to_fit
  - kernel/resource.c:insert_resource
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:release_resource
  - kernel/resource.c:request_resource
  - kernel/resource.c:release_child_resources
```
```
In kernel/ptrace.c (ffffffff81094078)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/sys.c (ffffffff8109d089)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - kernel/sys.c:sys_setsid
  - kernel/sys.c:SyS_setpgid
```
```
In kernel/locking/spinlock.c (ffffffff818d40b9)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_write_unlock_bh
```
```
In kernel/trace/trace_uprobe.c (ffffffff8118956b)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
```
In mm/mempolicy.c (ffffffff812137ce)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
```
```
In mm/zsmalloc.c (ffffffff8123d9d3)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/exec.c (ffffffff8124b762)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - fs/exec.c:unregister_binfmt
```
```
In fs/fcntl.c (ffffffff812594c3)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - fs/fcntl.c:f_modown
```
```
In fs/filesystems.c (ffffffff81266acd)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - fs/filesystems.c:unregister_filesystem
  - fs/filesystems.c:unregister_filesystem
```
```
In fs/proc/generic.c (ffffffff812c24a1)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_entry
```
```
In fs/proc/kcore.c (ffffffff812c985b)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In fs/ext4/super.c (ffffffff812edd1e)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_journal_params
```
```
In fs/ext4/extents_status.c (ffffffff81320f5f)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:ext4_es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
```
In fs/jbd2/transaction.c (ffffffff8132cf6a)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_unlock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/jbd2/commit.c (ffffffff8132d9e1)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff81330b46)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
```
```
In fs/jbd2/journal.c (ffffffff813319e1)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_ack_err
  - fs/jbd2/journal.c:jbd2_journal_clear_err
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_journal_start_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
```
```
In security/keys/keyring.c (ffffffff8137c0d2)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_instantiate
```
```
In security/keys/keyctl.c (ffffffff8137eb76)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/selinux/ss/services.c (ffffffff813a6547)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
```
In security/integrity/iint.c (ffffffff813e986c)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_free
  - security/integrity/iint.c:integrity_inode_get
```
```
In drivers/scsi/sg.c (ffffffff8164fc1f)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
```
In net/core/neighbour.c (ffffffff817becf1)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_for_each_release
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_probe
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:__neigh_create
  - net/core/neighbour.c:__neigh_create
```
```
In net/sched/sch_api.c (ffffffff817e0df5)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:unregister_qdisc
  - net/sched/sch_api.c:register_qdisc
```
```
In net/sched/cls_api.c (ffffffff817e22b2)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/sched/cls_api.c:register_tcf_proto_ops
```
```
In net/sched/act_api.c (ffffffff817e39e6)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_unregister_action
```
```
In net/sched/ematch.c (ffffffff817e5f04)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_unregister
  - net/sched/ematch.c:tcf_em_register
```
```
In net/netlink/af_netlink.c (ffffffff817e9059)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_table_ungrab
```
```
In net/ipv6/addrconf.c (ffffffff8186e9c1)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
```
```
In net/ipv6/route.c (ffffffff81875a10)
Location: include/asm-generic/qrwlock.h:163
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff8188d196)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
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
In kernel/fork.c (ffffffff81082a96)
Location: include/asm-generic/qrwlock.h:163
Inline: True
```
```
In kernel/exit.c (ffffffff81088100)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/resource.c (ffffffff8108b4b6)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - kernel/resource.c:devm_request_resource
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__release_region
  - kernel/resource.c:__release_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:adjust_resource
  - kernel/resource.c:remove_resource
  - kernel/resource.c:insert_resource_expand_to_fit
  - kernel/resource.c:insert_resource
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:release_resource
  - kernel/resource.c:request_resource
  - kernel/resource.c:release_child_resources
```
```
In kernel/ptrace.c (ffffffff8109115a)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/sys.c (ffffffff81099f69)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - kernel/sys.c:sys_setsid
  - kernel/sys.c:SyS_setpgid
```
```
In kernel/locking/spinlock.c (ffffffff8190b249)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_write_unlock_bh
```
```
In kernel/trace/trace_uprobe.c (ffffffff8118c0d7)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
```
In mm/mempolicy.c (ffffffff8121eade)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
```
```
In mm/zsmalloc.c (ffffffff81248bb8)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/exec.c (ffffffff8125788e)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - fs/exec.c:unregister_binfmt
```
```
In fs/fcntl.c (ffffffff812655a3)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - fs/fcntl.c:f_modown
```
```
In fs/filesystems.c (ffffffff8127434d)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - fs/filesystems.c:unregister_filesystem
  - fs/filesystems.c:unregister_filesystem
  - fs/filesystems.c:register_filesystem
```
```
In fs/proc/generic.c (ffffffff812cf731)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_entry
```
```
In fs/proc/kcore.c (ffffffff820db3e0)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:kcore_update_ram
```
```
In fs/ext4/extents_status.c (ffffffff812efe4c)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:ext4_es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
```
In fs/ext4/super.c (ffffffff81322cde)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_journal_params
```
```
In fs/jbd2/transaction.c (ffffffff81342130)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_unlock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/jbd2/commit.c (ffffffff81342b64)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff81345b3e)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
```
```
In fs/jbd2/journal.c (ffffffff813468d1)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_ack_err
  - fs/jbd2/journal.c:jbd2_journal_clear_err
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_journal_start_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
```
```
In security/keys/keyring.c (ffffffff8138fc90)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_instantiate
```
```
In security/keys/keyctl.c (ffffffff81392a06)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/selinux/ss/services.c (ffffffff813bcfaf)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
```
In security/integrity/iint.c (ffffffff813f5c6d)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_free
  - security/integrity/iint.c:integrity_inode_get
```
```
In drivers/scsi/sg.c (ffffffff81664247)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
```
In net/core/neighbour.c (ffffffff817dd2b1)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_for_each_release
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_probe
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:__neigh_create
  - net/core/neighbour.c:__neigh_create
  - net/core/neighbour.c:neigh_remove_one
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/sched/sch_api.c (ffffffff81800324)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:unregister_qdisc
  - net/sched/sch_api.c:register_qdisc
```
```
In net/sched/cls_api.c (ffffffff81801800)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/sched/cls_api.c:register_tcf_proto_ops
```
```
In net/sched/act_api.c (ffffffff81803b07)
Location: include/asm-generic/qrwlock.h:163
Inline: True
```
```
In net/sched/ematch.c (ffffffff81805a30)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_unregister
  - net/sched/ematch.c:tcf_em_register
```
```
In net/netlink/af_netlink.c (ffffffff81808d49)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_table_ungrab
```
```
In net/ipv6/addrconf.c (ffffffff818937bb)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff8189a08f)
Location: include/asm-generic/qrwlock.h:163
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff818b387b)
Location: include/asm-generic/qrwlock.h:163
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
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
In kernel/fork.c (ffffffff810898c4)
Location: include/asm-generic/qrwlock.h:122
Inline: True
```
```
In kernel/exit.c (ffffffff8108ee8b)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/resource.c (ffffffff81092196)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - kernel/resource.c:devm_request_resource
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__release_region
  - kernel/resource.c:__release_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:adjust_resource
  - kernel/resource.c:remove_resource
  - kernel/resource.c:insert_resource_expand_to_fit
  - kernel/resource.c:insert_resource
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:release_resource
  - kernel/resource.c:request_resource
  - kernel/resource.c:release_child_resources
```
```
In kernel/ptrace.c (ffffffff81097fca)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/sys.c (ffffffff810a0c49)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - kernel/sys.c:sys_setsid
  - kernel/sys.c:SyS_setpgid
```
```
In kernel/locking/spinlock.c (ffffffff819955e9)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_write_unlock_bh
```
```
In kernel/trace/trace_uprobe.c (ffffffff81199b9d)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
```
In mm/mempolicy.c (ffffffff81239cfe)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
```
```
In mm/zsmalloc.c (ffffffff81268dab)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/exec.c (ffffffff81279ade)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - fs/exec.c:unregister_binfmt
  - fs/exec.c:__register_binfmt
```
```
In fs/fcntl.c (ffffffff81288311)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - fs/fcntl.c:f_delown
```
```
In fs/filesystems.c (ffffffff81296c4d)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - fs/filesystems.c:unregister_filesystem
  - fs/filesystems.c:unregister_filesystem
  - fs/filesystems.c:register_filesystem
```
```
In fs/proc/generic.c (ffffffff812f3e89)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_entry
```
```
In fs/proc/kcore.c (ffffffff826e4075)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:kcore_update_ram
```
```
In fs/ext4/extents_status.c (ffffffff8131494c)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:ext4_es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
```
In fs/ext4/super.c (ffffffff8134742e)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_journal_params
```
```
In fs/jbd2/transaction.c (ffffffff81366760)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_unlock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/jbd2/commit.c (ffffffff81367194)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff8136a1de)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
```
```
In fs/jbd2/journal.c (ffffffff8136afc1)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_ack_err
  - fs/jbd2/journal.c:jbd2_journal_clear_err
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_journal_start_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
```
```
In security/keys/keyring.c (ffffffff813b51c0)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_instantiate
```
```
In security/keys/keyctl.c (ffffffff813b8066)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/selinux/ss/services.c (ffffffff813e3122)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
```
In security/integrity/iint.c (ffffffff8141dd5d)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_free
  - security/integrity/iint.c:integrity_inode_get
```
```
In drivers/scsi/sg.c (ffffffff816cd897)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
```
In net/core/neighbour.c (ffffffff81858343)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_for_each_release
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_probe
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:__neigh_create
  - net/core/neighbour.c:__neigh_create
  - net/core/neighbour.c:neigh_remove_one
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/sched/sch_api.c (ffffffff8187e0c4)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:unregister_qdisc
  - net/sched/sch_api.c:register_qdisc
```
```
In net/sched/cls_api.c (ffffffff8187f50c)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/sched/cls_api.c:register_tcf_proto_ops
```
```
In net/sched/act_api.c (ffffffff81881ff7)
Location: include/asm-generic/qrwlock.h:122
Inline: True
```
```
In net/sched/ematch.c (ffffffff81884750)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_unregister
  - net/sched/ematch.c:tcf_em_register
```
```
In net/netlink/af_netlink.c (ffffffff81887c19)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_table_ungrab
```
```
In net/ipv6/addrconf.c (ffffffff81914aa9)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff8191b5bf)
Location: include/asm-generic/qrwlock.h:122
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff819365fb)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
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
In kernel/fork.c (ffffffff8108d275)
Location: include/asm-generic/qrwlock.h:122
Inline: True
```
```
In kernel/exit.c (ffffffff8109298a)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/resource.c (ffffffff81096df7)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__release_region
  - kernel/resource.c:__release_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:adjust_resource
  - kernel/resource.c:remove_resource
  - kernel/resource.c:insert_resource_expand_to_fit
  - kernel/resource.c:insert_resource_conflict
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:release_resource
  - kernel/resource.c:request_resource_conflict
  - kernel/resource.c:release_child_resources
```
```
In kernel/ptrace.c (ffffffff8109b66c)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/sys.c (ffffffff810a749c)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
```
In kernel/locking/spinlock.c (ffffffff819f1be5)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_write_unlock_bh
```
```
In kernel/trace/trace_uprobe.c (ffffffff811af3da)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
```
In mm/mempolicy.c (ffffffff8125d2ce)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
```
```
In mm/zsmalloc.c (ffffffff8128dd5c)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/exec.c (ffffffff812a06be)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - fs/exec.c:unregister_binfmt
  - fs/exec.c:__register_binfmt
```
```
In fs/fcntl.c (ffffffff812af668)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_modown
```
```
In fs/filesystems.c (ffffffff812bcdf7)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - fs/filesystems.c:register_filesystem
```
```
In fs/proc/generic.c (ffffffff81320f64)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:proc_register
  - fs/proc/generic.c:proc_register
```
```
In fs/proc/kcore.c (ffffffff8270e656)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:kcore_callback
  - fs/proc/kcore.c:kcore_update_ram
```
```
In fs/ext4/extents_status.c (ffffffff81342729)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:ext4_es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
```
In fs/ext4/super.c (ffffffff8137539e)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_journal_params
```
```
In fs/jbd2/transaction.c (ffffffff81394d96)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_unlock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/jbd2/commit.c (ffffffff81395a61)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff8139887f)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
```
```
In fs/jbd2/journal.c (ffffffff81399771)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_ack_err
  - fs/jbd2/journal.c:jbd2_journal_clear_err
  - fs/jbd2/journal.c:__journal_abort_soft
  - fs/jbd2/journal.c:__journal_abort_soft
  - fs/jbd2/journal.c:__journal_abort_soft
  - fs/jbd2/journal.c:jbd2_journal_flush
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
```
```
In security/keys/keyring.c (ffffffff813e59f0)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_instantiate
```
```
In security/keys/keyctl.c (ffffffff813e8c4c)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/selinux/ss/services.c (ffffffff8141389f)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
```
In security/integrity/iint.c (ffffffff8145000c)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_free
  - security/integrity/iint.c:integrity_inode_get
```
```
In drivers/scsi/sg.c (ffffffff8170a222)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
```
In net/core/neighbour.c (ffffffff818a3733)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_for_each_release
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_probe
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
```
```
In net/sched/sch_api.c (ffffffff818d0b57)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:unregister_qdisc
  - net/sched/sch_api.c:register_qdisc
```
```
In net/sched/cls_api.c (ffffffff818d232c)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/sched/cls_api.c:register_tcf_proto_ops
```
```
In net/sched/act_api.c (ffffffff818d52c4)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_unregister_action
```
```
In net/sched/ematch.c (ffffffff818d82d0)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_unregister
  - net/sched/ematch.c:tcf_em_register
```
```
In net/netlink/af_netlink.c (ffffffff818db605)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_table_ungrab
```
```
In net/ipv6/addrconf.c (ffffffff8196c0f6)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81973293)
Location: include/asm-generic/qrwlock.h:122
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff8198f286)
Location: include/asm-generic/qrwlock.h:122
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
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
In kernel/fork.c (ffffffff81094bc5)
Location: include/asm-generic/qrwlock.h:123
Inline: True
```
```
In kernel/exit.c (ffffffff8109ac7d)
Location: include/asm-generic/qrwlock.h:123
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/resource.c (ffffffff8109f120)
Location: include/asm-generic/qrwlock.h:123
Inline: True
Inline callers:
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__release_region
  - kernel/resource.c:__release_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:adjust_resource
  - kernel/resource.c:remove_resource
  - kernel/resource.c:insert_resource_expand_to_fit
  - kernel/resource.c:insert_resource_conflict
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:release_resource
  - kernel/resource.c:request_resource_conflict
  - kernel/resource.c:release_child_resources
```
```
In kernel/ptrace.c (ffffffff810a38a0)
Location: include/asm-generic/qrwlock.h:123
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/sys.c (ffffffff810b01ac)
Location: include/asm-generic/qrwlock.h:123
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
```
In kernel/locking/spinlock.c (ffffffff81a2d1a5)
Location: include/asm-generic/qrwlock.h:123
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_write_unlock_bh
```
```
In kernel/trace/trace_uprobe.c (ffffffff811bdab6)
Location: include/asm-generic/qrwlock.h:123
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
```
In mm/mempolicy.c (ffffffff81271b8e)
Location: include/asm-generic/qrwlock.h:123
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
```
```
In mm/zsmalloc.c (ffffffff812a36a1)
Location: include/asm-generic/qrwlock.h:123
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/exec.c (ffffffff812b569e)
Location: include/asm-generic/qrwlock.h:123
Inline: True
Inline callers:
  - fs/exec.c:unregister_binfmt
  - fs/exec.c:__register_binfmt
```
```
In fs/fcntl.c (ffffffff812c47e8)
Location: include/asm-generic/qrwlock.h:123
Inline: True
Inline callers:
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_modown
```
```
In fs/filesystems.c (ffffffff812d20b7)
Location: include/asm-generic/qrwlock.h:123
Inline: True
Inline callers:
  - fs/filesystems.c:register_filesystem
```
```
In fs/proc/generic.c (ffffffff8133806d)
Location: include/asm-generic/qrwlock.h:123
Inline: True
Inline callers:
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:proc_register
  - fs/proc/generic.c:proc_register
```
```
In fs/ext4/extents_status.c (ffffffff8135b797)
Location: include/asm-generic/qrwlock.h:123
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_remove_blks
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_remove_pending
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:ext4_es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
```
In fs/ext4/super.c (ffffffff8138d7be)
Location: include/asm-generic/qrwlock.h:123
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_journal_params
```
```
In fs/jbd2/transaction.c (ffffffff813adb06)
Location: include/asm-generic/qrwlock.h:123
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_unlock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/jbd2/commit.c (ffffffff813ae7a1)
Location: include/asm-generic/qrwlock.h:123
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff813b15ef)
Location: include/asm-generic/qrwlock.h:123
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
```
```
In fs/jbd2/journal.c (ffffffff813b24e1)
Location: include/asm-generic/qrwlock.h:123
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_ack_err
  - fs/jbd2/journal.c:jbd2_journal_clear_err
  - fs/jbd2/journal.c:__journal_abort_soft
  - fs/jbd2/journal.c:__journal_abort_soft
  - fs/jbd2/journal.c:__journal_abort_soft
  - fs/jbd2/journal.c:jbd2_journal_flush
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
```
```
In security/keys/keyring.c (ffffffff814001d0)
Location: include/asm-generic/qrwlock.h:123
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_instantiate
```
```
In security/keys/keyctl.c (ffffffff8140344a)
Location: include/asm-generic/qrwlock.h:123
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/selinux/ss/services.c (ffffffff8142fdcc)
Location: include/asm-generic/qrwlock.h:123
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
```
In security/integrity/iint.c (ffffffff8146cfec)
Location: include/asm-generic/qrwlock.h:123
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_free
  - security/integrity/iint.c:integrity_inode_get
```
```
In drivers/scsi/sg.c (ffffffff8172c6aa)
Location: include/asm-generic/qrwlock.h:123
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
```
In net/core/neighbour.c (ffffffff818c6670)
Location: include/asm-generic/qrwlock.h:123
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_for_each_release
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_probe
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_flush_dev
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/sched/sch_api.c (ffffffff818fbea7)
Location: include/asm-generic/qrwlock.h:123
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:unregister_qdisc
  - net/sched/sch_api.c:register_qdisc
```
```
In net/sched/cls_api.c (ffffffff818fd8cc)
Location: include/asm-generic/qrwlock.h:123
Inline: True
Inline callers:
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/sched/cls_api.c:register_tcf_proto_ops
```
```
In net/sched/act_api.c (ffffffff81901f04)
Location: include/asm-generic/qrwlock.h:123
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_unregister_action
```
```
In net/sched/ematch.c (ffffffff81904ac0)
Location: include/asm-generic/qrwlock.h:123
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_unregister
  - net/sched/ematch.c:tcf_em_register
```
```
In net/netlink/af_netlink.c (ffffffff81907f05)
Location: include/asm-generic/qrwlock.h:123
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_table_ungrab
```
```
In net/ipv6/addrconf.c (ffffffff819a1b96)
Location: include/asm-generic/qrwlock.h:123
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff819a8eb3)
Location: include/asm-generic/qrwlock.h:123
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff819c5b46)
Location: include/asm-generic/qrwlock.h:123
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
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
In kernel/fork.c (ffffffff81099640)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff8109eefd)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/resource.c (ffffffff810a374a)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__release_region
  - kernel/resource.c:__release_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:adjust_resource
  - kernel/resource.c:remove_resource
  - kernel/resource.c:insert_resource_expand_to_fit
  - kernel/resource.c:insert_resource_conflict
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:release_resource
  - kernel/resource.c:request_resource_conflict
  - kernel/resource.c:release_child_resources
```
```
In kernel/ptrace.c (ffffffff810a8831)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/sys.c (ffffffff810b5b7a)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
```
In kernel/locking/spinlock.c (ffffffff81a9d295)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_write_unlock_bh
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cc8d9)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
```
In mm/mempolicy.c (ffffffff8128d1ce)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
```
```
In mm/zsmalloc.c (ffffffff812bea0b)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/exec.c (ffffffff812d4ce4)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:unregister_binfmt
  - fs/exec.c:__register_binfmt
```
```
In fs/fcntl.c (ffffffff812e1241)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_modown
```
```
In fs/filesystems.c (ffffffff812ef118)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/filesystems.c:register_filesystem
```
```
In fs/eventpoll.c (ffffffff813217fb)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
```
```
In fs/proc/generic.c (ffffffff813601e9)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:proc_register
  - fs/proc/generic.c:proc_register
```
```
In fs/ext4/extents_status.c (ffffffff813847cc)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_remove_blks
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_remove_pending
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:ext4_es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
```
In fs/ext4/super.c (ffffffff813b7a3e)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_journal_params
```
```
In fs/jbd2/transaction.c (ffffffff813d7e47)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_unlock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/jbd2/commit.c (ffffffff813d8c6a)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff813dbc26)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
```
```
In fs/jbd2/journal.c (ffffffff813dcb51)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_ack_err
  - fs/jbd2/journal.c:jbd2_journal_clear_err
  - fs/jbd2/journal.c:__journal_abort_soft
  - fs/jbd2/journal.c:__journal_abort_soft
  - fs/jbd2/journal.c:__journal_abort_soft
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_start_commit
  - fs/jbd2/journal.c:jbd2_log_start_commit
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
```
```
In security/keys/keyring.c (ffffffff8142c9de)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_instantiate
  - security/keys/keyring.c:key_free_user_ns
```
```
In security/keys/keyctl.c (ffffffff81430059)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/selinux/ss/services.c (ffffffff8145d75e)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
```
In security/integrity/iint.c (ffffffff8149a6de)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_free
  - security/integrity/iint.c:integrity_inode_get
```
```
In drivers/scsi/sg.c (ffffffff81767aa1)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
```
In net/core/neighbour.c (ffffffff81912748)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_for_each_release
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_probe
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_flush_dev
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/sched/sch_api.c (ffffffff8195b857)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:unregister_qdisc
  - net/sched/sch_api.c:register_qdisc
```
```
In net/sched/cls_api.c (ffffffff8195d2a5)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/sched/cls_api.c:register_tcf_proto_ops
```
```
In net/sched/act_api.c (ffffffff81963084)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_unregister_action
```
```
In net/sched/ematch.c (ffffffff81965d0e)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_unregister
  - net/sched/ematch.c:tcf_em_register
```
```
In net/netlink/af_netlink.c (ffffffff819691e5)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_table_ungrab
```
```
In net/ipv6/addrconf.c (ffffffff81a0e153)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81a159c3)
Location: include/asm-generic/qrwlock.h:114
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81a349a6)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
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
In kernel/fork.c (ffffffff8109fc3a)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810a548d)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/resource.c (ffffffff810a9d7a)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__release_region
  - kernel/resource.c:__release_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:adjust_resource
  - kernel/resource.c:remove_resource
  - kernel/resource.c:insert_resource_expand_to_fit
  - kernel/resource.c:insert_resource_conflict
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:release_resource
  - kernel/resource.c:request_resource_conflict
  - kernel/resource.c:release_child_resources
```
```
In kernel/ptrace.c (ffffffff810aee4b)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/sys.c (ffffffff810bc16a)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
```
In kernel/locking/spinlock.c (ffffffff81ad4a75)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_write_unlock_bh
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d8468)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
```
```
In mm/mempolicy.c (ffffffff8129cdfe)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
```
```
In mm/zsmalloc.c (ffffffff812d096c)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/exec.c (ffffffff812e6864)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:unregister_binfmt
```
```
In fs/fcntl.c (ffffffff812f2cf1)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_modown
```
```
In fs/filesystems.c (ffffffff81300bd8)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/filesystems.c:register_filesystem
```
```
In fs/eventpoll.c (ffffffff813355eb)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
```
```
In fs/proc/generic.c (ffffffff81378449)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:proc_register
  - fs/proc/generic.c:proc_register
```
```
In fs/ext4/extents_status.c (ffffffff8139d1b4)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_remove_pending
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:ext4_es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
```
In fs/ext4/super.c (ffffffff813d0d9e)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_journal_params
```
```
In fs/jbd2/transaction.c (ffffffff813f1f17)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_unlock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/jbd2/commit.c (ffffffff813f2c5a)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff813f5c72)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
```
```
In fs/jbd2/journal.c (ffffffff813f6ba1)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_ack_err
  - fs/jbd2/journal.c:jbd2_journal_clear_err
  - fs/jbd2/journal.c:__journal_abort_soft
  - fs/jbd2/journal.c:__journal_abort_soft
  - fs/jbd2/journal.c:__journal_abort_soft
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_start_commit
  - fs/jbd2/journal.c:jbd2_log_start_commit
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
```
```
In security/keys/keyring.c (ffffffff8144672e)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_instantiate
  - security/keys/keyring.c:key_free_user_ns
```
```
In security/keys/keyctl.c (ffffffff81449db9)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/selinux/ss/services.c (ffffffff8147750e)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
```
In security/integrity/iint.c (ffffffff814b48de)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_free
  - security/integrity/iint.c:integrity_inode_get
```
```
In drivers/scsi/sg.c (ffffffff8178ba91)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
```
In net/core/neighbour.c (ffffffff81944da8)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_for_each_release
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_probe
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_flush_dev
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/sched/sch_api.c (ffffffff81991d07)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:unregister_qdisc
  - net/sched/sch_api.c:register_qdisc
```
```
In net/sched/cls_api.c (ffffffff819937a5)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/sched/cls_api.c:register_tcf_proto_ops
```
```
In net/sched/act_api.c (ffffffff81999c04)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_unregister_action
```
```
In net/sched/ematch.c (ffffffff8199c79e)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_unregister
  - net/sched/ematch.c:tcf_em_register
```
```
In net/netlink/af_netlink.c (ffffffff8199fc85)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_table_ungrab
```
```
In net/ipv6/addrconf.c (ffffffff81a44e93)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81a4c5dd)
Location: include/asm-generic/qrwlock.h:114
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81a6b4f6)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
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
In kernel/fork.c (ffffffff810a6cce)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810ad244)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:exit_notify
  - kernel/exit.c:find_child_reaper
  - kernel/exit.c:release_task
```
```
In kernel/resource.c (ffffffff810b07d7)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/resource.c:devm_request_resource
  - kernel/resource.c:devm_resource_release
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__release_region
  - kernel/resource.c:__release_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:adjust_resource
  - kernel/resource.c:remove_resource
  - kernel/resource.c:insert_resource_expand_to_fit
  - kernel/resource.c:insert_resource
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:release_child_resources
```
```
In kernel/ptrace.c (ffffffff810b69e5)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/sys.c (ffffffff810c3b0a)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_setpgid
```
```
In kernel/locking/spinlock.c (ffffffff81bccbf5)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_write_unlock_bh
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f5269)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_open
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
```
```
In mm/mempolicy.c (ffffffff812d09de)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:shared_policy_replace
```
```
In mm/zsmalloc.c (ffffffff81307098)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/exec.c (ffffffff8131dbda)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/exec.c:unshare_sighand
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:unregister_binfmt
  - fs/exec.c:__register_binfmt
```
```
In fs/fcntl.c (ffffffff8132af84)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_delown
```
```
In fs/filesystems.c (ffffffff81339d92)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/filesystems.c:register_filesystem
```
```
In fs/eventpoll.c (ffffffff8136e5af)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_modify
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
```
```
In fs/proc/generic.c (ffffffff813c150c)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:proc_register
  - fs/proc/generic.c:proc_register
```
```
In fs/ext4/extents_status.c (ffffffff813e88f4)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_remove_pending
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:ext4_es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
```
In fs/ext4/super.c (ffffffff8141d20e)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_journal_params
```
```
In fs/jbd2/transaction.c (ffffffff8143f248)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unlock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/jbd2/commit.c (ffffffff81440358)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff81443016)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
```
```
In fs/jbd2/journal.c (ffffffff81443f61)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_ack_err
  - fs/jbd2/journal.c:jbd2_journal_clear_err
  - fs/jbd2/journal.c:jbd2_journal_abort
  - fs/jbd2/journal.c:jbd2_journal_abort
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:__jbd2_update_log_tail
  - fs/jbd2/journal.c:jbd2_journal_next_log_block
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_journal_start_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:journal_kill_thread
  - fs/jbd2/journal.c:journal_kill_thread
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
```
```
In security/keys/keyring.c (ffffffff81497b5e)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_instantiate
  - security/keys/keyring.c:key_free_user_ns
```
```
In security/keys/keyctl.c (ffffffff8149b7b9)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/selinux/ss/services.c (ffffffff814cc94c)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
```
In security/integrity/iint.c (ffffffff81513e6e)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_free
  - security/integrity/iint.c:integrity_inode_get
```
```
In drivers/scsi/sg.c (ffffffff81850948)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
```
```
In net/core/neighbour.c (ffffffff81a1521c)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_for_each_release
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_probe
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_forced_gc
  - net/core/neighbour.c:neigh_remove_one
  - net/core/neighbour.c:neigh_update_gc_list
```
```
In net/sched/sch_api.c (ffffffff81a6b4cd)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:unregister_qdisc
  - net/sched/sch_api.c:register_qdisc
```
```
In net/sched/cls_api.c (ffffffff81a6b835)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/sched/cls_api.c:register_tcf_proto_ops
```
```
In net/sched/act_api.c (ffffffff81a72534)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_unregister_action
  - net/sched/act_api.c:tcf_register_action
  - net/sched/act_api.c:tcf_register_action
```
```
In net/sched/ematch.c (ffffffff81a7583e)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_unregister
  - net/sched/ematch.c:tcf_em_register
```
```
In net/netlink/af_netlink.c (ffffffff81a79405)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_table_ungrab
```
```
In net/ipv6/addrconf.c (ffffffff81b3b9d9)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81b425c7)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_probe
```
```
In net/ipv6/mcast.c (ffffffff81b64443)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
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
In kernel/fork.c (ffffffff810a280d)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810a890d)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:exit_notify
  - kernel/exit.c:find_child_reaper
  - kernel/exit.c:release_task
```
```
In kernel/resource.c (ffffffff810abef7)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/resource.c:devm_request_resource
  - kernel/resource.c:devm_resource_release
  - kernel/resource.c:merge_system_ram_resource
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__release_region
  - kernel/resource.c:__release_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:adjust_resource
  - kernel/resource.c:remove_resource
  - kernel/resource.c:insert_resource_expand_to_fit
  - kernel/resource.c:insert_resource
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:release_child_resources
```
```
In kernel/ptrace.c (ffffffff810b1c5d)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/sys.c (ffffffff810beefa)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_setpgid
```
```
In kernel/locking/spinlock.c (ffffffff81c457bc)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_write_unlock_bh
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f3bf9)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_open
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
```
```
In mm/mempolicy.c (ffffffff812dc4fe)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:shared_policy_replace
```
```
In mm/zsmalloc.c (ffffffff81312dd8)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/exec.c (ffffffff81328a3a)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/exec.c:unshare_sighand
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:unregister_binfmt
  - fs/exec.c:__register_binfmt
```
```
In fs/fcntl.c (ffffffff81336554)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_delown
```
```
In fs/filesystems.c (ffffffff81345aa2)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/filesystems.c:register_filesystem
```
```
In fs/eventpoll.c (ffffffff8137baa0)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_modify
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
  - fs/eventpoll.c:ep_done_scan
```
```
In fs/proc/generic.c (ffffffff813d33fc)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:proc_register
  - fs/proc/generic.c:proc_register
```
```
In fs/ext4/extents_status.c (ffffffff813fabde)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_remove_pending
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:ext4_es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
```
In fs/ext4/super.c (ffffffff8143d443)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_journal_params
```
```
In fs/jbd2/transaction.c (ffffffff8145b4a8)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unlock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/jbd2/commit.c (ffffffff8145c401)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff8145f176)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
```
```
In fs/jbd2/journal.c (ffffffff81460641)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_ack_err
  - fs/jbd2/journal.c:jbd2_journal_clear_err
  - fs/jbd2/journal.c:jbd2_journal_abort
  - fs/jbd2/journal.c:jbd2_journal_abort
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:__jbd2_update_log_tail
  - fs/jbd2/journal.c:jbd2_journal_next_log_block
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_fc_end_commit
  - fs/jbd2/journal.c:jbd2_fc_begin_commit
  - fs/jbd2/journal.c:jbd2_fc_begin_commit
  - fs/jbd2/journal.c:jbd2_fc_begin_commit
  - fs/jbd2/journal.c:jbd2_journal_start_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:journal_kill_thread
  - fs/jbd2/journal.c:journal_kill_thread
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
```
```
In security/keys/keyring.c (ffffffff814b55ce)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_instantiate
  - security/keys/keyring.c:key_free_user_ns
```
```
In security/keys/keyctl.c (ffffffff814b9249)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/integrity/iint.c (ffffffff81530fce)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_free
  - security/integrity/iint.c:integrity_inode_get
```
```
In drivers/scsi/sg.c (ffffffff81860d99)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
```
```
In net/core/neighbour.c (ffffffff81a1550c)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_for_each_release
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_probe
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_forced_gc
  - net/core/neighbour.c:neigh_remove_one
  - net/core/neighbour.c:neigh_update_gc_list
```
```
In net/sched/sch_api.c (ffffffff81a73c7d)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:unregister_qdisc
  - net/sched/sch_api.c:register_qdisc
```
```
In net/sched/cls_api.c (ffffffff81a73fa5)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/sched/cls_api.c:register_tcf_proto_ops
```
```
In net/sched/act_api.c (ffffffff81a7b0f4)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_unregister_action
  - net/sched/act_api.c:tcf_register_action
  - net/sched/act_api.c:tcf_register_action
```
```
In net/sched/ematch.c (ffffffff81a7e60e)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_unregister
  - net/sched/ematch.c:tcf_em_register
```
```
In net/netlink/af_netlink.c (ffffffff81a82215)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_table_ungrab
```
```
In net/ipv6/addrconf.c (ffffffff81b4a6e9)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81b50f87)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_probe
```
```
In net/ipv6/mcast.c (ffffffff81b72bbc)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
```
```
In net/packet/af_packet.c (ffffffff81b94b86)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
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
In kernel/fork.c (ffffffff810a34d6)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810a9782)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:exit_notify
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:release_task
```
```
In kernel/resource.c (ffffffff810ad514)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - kernel/resource.c:__request_free_mem_region
  - kernel/resource.c:__request_free_mem_region
  - kernel/resource.c:devm_request_resource
  - kernel/resource.c:devm_resource_release
  - kernel/resource.c:merge_system_ram_resource
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__release_region
  - kernel/resource.c:__release_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:__request_region_locked
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:adjust_resource
  - kernel/resource.c:remove_resource
  - kernel/resource.c:insert_resource_expand_to_fit
  - kernel/resource.c:insert_resource
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:release_child_resources
```
```
In kernel/ptrace.c (ffffffff810b2e42)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/sys.c (ffffffff810c088a)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_setpgid
```
```
In kernel/sched/core.c (ffffffff810e0b6c)
Location: include/asm-generic/qrwlock.h:116
Inline: True
```
```
In kernel/locking/spinlock.c (ffffffff81c38aa5)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_write_unlock_bh
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f5024)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
```
```
In mm/mempolicy.c (ffffffff812e3d5e)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:shared_policy_replace
```
```
In mm/zsmalloc.c (ffffffff81319309)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/exec.c (ffffffff8132fc5d)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:unregister_binfmt
  - fs/exec.c:__register_binfmt
```
```
In fs/fcntl.c (ffffffff8133c6f4)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_delown
```
```
In fs/filesystems.c (ffffffff8134be62)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - fs/filesystems.c:register_filesystem
```
```
In fs/eventpoll.c (ffffffff813839b5)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
  - fs/eventpoll.c:ep_done_scan
```
```
In fs/proc/generic.c (ffffffff813da238)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:proc_register
  - fs/proc/generic.c:proc_register
```
```
In fs/ext4/extents_status.c (ffffffff81400f9e)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_remove_pending
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:ext4_es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
```
In fs/ext4/mballoc.c (ffffffff8141ba69)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_set_largest_free_order
  - fs/ext4/mballoc.c:mb_set_largest_free_order
```
```
In fs/ext4/super.c (ffffffff81443283)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_journal_params
```
```
In fs/jbd2/transaction.c (ffffffff81460de8)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unlock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/jbd2/commit.c (ffffffff81461a6d)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff814649f3)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
```
```
In fs/jbd2/journal.c (ffffffff81465df1)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_ack_err
  - fs/jbd2/journal.c:jbd2_journal_clear_err
  - fs/jbd2/journal.c:jbd2_journal_abort
  - fs/jbd2/journal.c:jbd2_journal_abort
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:__jbd2_update_log_tail
  - fs/jbd2/journal.c:jbd2_journal_next_log_block
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_fc_end_commit
  - fs/jbd2/journal.c:jbd2_fc_begin_commit
  - fs/jbd2/journal.c:jbd2_fc_begin_commit
  - fs/jbd2/journal.c:jbd2_fc_begin_commit
  - fs/jbd2/journal.c:jbd2_journal_start_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
```
```
In security/keys/keyring.c (ffffffff814bb46e)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_instantiate
  - security/keys/keyring.c:key_free_user_ns
```
```
In security/keys/keyctl.c (ffffffff814bf099)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/integrity/iint.c (ffffffff815393fe)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_free
  - security/integrity/iint.c:integrity_inode_get
```
```
In drivers/scsi/sg.c (ffffffff81843a5a)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
```
```
In net/core/neighbour.c (ffffffff819fc06c)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_for_each_release
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_probe
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_alloc
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/sched/sch_api.c (ffffffff81a5c81d)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:unregister_qdisc
  - net/sched/sch_api.c:register_qdisc
```
```
In net/sched/cls_api.c (ffffffff81a5caf5)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/sched/cls_api.c:register_tcf_proto_ops
```
```
In net/sched/act_api.c (ffffffff81a63e54)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_unregister_action
  - net/sched/act_api.c:tcf_register_action
  - net/sched/act_api.c:tcf_register_action
```
```
In net/sched/ematch.c (ffffffff81a6746e)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_unregister
  - net/sched/ematch.c:tcf_em_register
```
```
In net/netlink/af_netlink.c (ffffffff81a6b2f5)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_table_ungrab
```
```
In net/ipv6/addrconf.c (ffffffff81b3826e)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81b3ee97)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_probe
```
```
In net/packet/af_packet.c (ffffffff81b83c66)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
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
In kernel/fork.c (ffffffff810b4c64)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810bb272)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:exit_notify
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:release_task
```
```
In kernel/resource.c (ffffffff810bf09b)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - kernel/resource.c:__request_free_mem_region
  - kernel/resource.c:__request_free_mem_region
  - kernel/resource.c:devm_request_resource
  - kernel/resource.c:devm_resource_release
  - kernel/resource.c:merge_system_ram_resource
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__release_region
  - kernel/resource.c:__release_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:__request_region_locked
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:adjust_resource
  - kernel/resource.c:remove_resource
  - kernel/resource.c:insert_resource_expand_to_fit
  - kernel/resource.c:insert_resource
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:release_child_resources
```
```
In kernel/ptrace.c (ffffffff810c4fe2)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/sys.c (ffffffff810d337a)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_setpgid
```
```
In kernel/sched/core.c (ffffffff810f6c7c)
Location: include/asm-generic/qrwlock.h:116
Inline: True
```
```
In kernel/locking/spinlock.c (ffffffff81d57385)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_write_unlock_bh
```
```
In kernel/trace/trace_uprobe.c (ffffffff81227ffe)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
```
```
In mm/mempolicy.c (ffffffff8132b04e)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:shared_policy_replace
```
```
In mm/zsmalloc.c (ffffffff813656c1)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/exec.c (ffffffff8137d286)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:unregister_binfmt
  - fs/exec.c:__register_binfmt
```
```
In fs/fcntl.c (ffffffff8138a3f4)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_delown
```
```
In fs/filesystems.c (ffffffff81399ca2)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - fs/filesystems.c:register_filesystem
```
```
In fs/eventpoll.c (ffffffff813d0c55)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
  - fs/eventpoll.c:ep_done_scan
```
```
In fs/proc/generic.c (ffffffff8142b968)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:proc_register
  - fs/proc/generic.c:proc_register
```
```
In fs/ext4/extents_status.c (ffffffff814535bb)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_remove_pending
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:ext4_es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
```
In fs/ext4/mballoc.c (ffffffff8146ed99)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_set_largest_free_order
  - fs/ext4/mballoc.c:mb_set_largest_free_order
```
```
In fs/ext4/super.c (ffffffff81496ef3)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_journal_params
```
```
In fs/jbd2/transaction.c (ffffffff814b62cb)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unlock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/jbd2/commit.c (ffffffff814b6f60)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff814ba073)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
```
```
In fs/jbd2/journal.c (ffffffff814bb8e1)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_ack_err
  - fs/jbd2/journal.c:jbd2_journal_clear_err
  - fs/jbd2/journal.c:jbd2_journal_abort
  - fs/jbd2/journal.c:jbd2_journal_abort
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_next_log_block
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_fc_end_commit
  - fs/jbd2/journal.c:jbd2_fc_begin_commit
  - fs/jbd2/journal.c:jbd2_fc_begin_commit
  - fs/jbd2/journal.c:jbd2_fc_begin_commit
  - fs/jbd2/journal.c:jbd2_journal_start_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
```
```
In security/keys/keyring.c (ffffffff81513c9e)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_instantiate
  - security/keys/keyring.c:key_free_user_ns
```
```
In security/keys/keyctl.c (ffffffff81517ab9)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/integrity/iint.c (ffffffff81597c3e)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_free
  - security/integrity/iint.c:integrity_inode_get
```
```
In drivers/scsi/sg.c (ffffffff818d0526)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
```
```
In net/core/neighbour.c (ffffffff81aae0da)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_for_each_release
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_probe
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_alloc
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/sched/sch_api.c (ffffffff81b159cd)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:unregister_qdisc
  - net/sched/sch_api.c:register_qdisc
```
```
In net/sched/cls_api.c (ffffffff81b15ca5)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/sched/cls_api.c:register_tcf_proto_ops
```
```
In net/sched/act_api.c (ffffffff81b1d1d4)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_unregister_action
  - net/sched/act_api.c:tcf_register_action
  - net/sched/act_api.c:tcf_register_action
```
```
In net/sched/ematch.c (ffffffff81b2094e)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_unregister
  - net/sched/ematch.c:tcf_em_register
```
```
In net/netlink/af_netlink.c (ffffffff81b24925)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_table_ungrab
```
```
In net/ipv6/addrconf.c (ffffffff81bfea0e)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81c0695f)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_probe
```
```
In net/packet/af_packet.c (ffffffff81c4fd76)
Location: include/asm-generic/qrwlock.h:116
Inline: True
Inline callers:
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
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
In kernel/locking/spinlock.c (ffffffff81f29d55)
Location: include/asm-generic/qrwlock.h:120
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_write_unlock_irq
  - kernel/locking/spinlock.c:_raw_write_unlock_bh
  - kernel/locking/spinlock.c:_raw_write_unlock
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
In kernel/locking/spinlock.c (ffffffff820d5c85)
Location: include/asm-generic/qrwlock.h:120
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_write_unlock_irq
  - kernel/locking/spinlock.c:_raw_write_unlock_bh
  - kernel/locking/spinlock.c:_raw_write_unlock
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
In kernel/locking/spinlock.c (ffffffff82159065)
Location: include/asm-generic/qrwlock.h:120
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_write_unlock_irq
  - kernel/locking/spinlock.c:_raw_write_unlock_bh
  - kernel/locking/spinlock.c:_raw_write_unlock
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
In kernel/locking/spinlock.c (ffffffff8223c8e5)
Location: include/asm-generic/qrwlock.h:120
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_write_unlock_irq
  - kernel/locking/spinlock.c:_raw_write_unlock_bh
  - kernel/locking/spinlock.c:_raw_write_unlock
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
In arch/arm/xen/p2m.c (ffff8000100f05f0)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - arch/arm/xen/p2m.c:__set_phys_to_machine_multi
  - arch/arm/xen/p2m.c:__set_phys_to_machine_multi
  - arch/arm/xen/p2m.c:__set_phys_to_machine_multi
  - arch/arm/xen/p2m.c:__set_phys_to_machine_multi
```
```
In kernel/fork.c (ffff8000100f419c)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffff8000100fb380)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/resource.c (ffff800010100b60)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/resource.c:__release_region
  - kernel/resource.c:__release_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:adjust_resource
  - kernel/resource.c:remove_resource
  - kernel/resource.c:insert_resource_expand_to_fit
  - kernel/resource.c:insert_resource_conflict
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:release_resource
  - kernel/resource.c:request_resource_conflict
  - kernel/resource.c:release_child_resources
```
```
In kernel/ptrace.c (ffff80001010941c)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/sys.c (ffff800010118c18)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__arm64_sys_setpgid
```
```
In kernel/trace/trace_uprobe.c (ffff800010259518)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
```
```
In kernel/bpf/reuseport_array.c (ffff8000102908c4)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
  - kernel/bpf/reuseport_array.c:bpf_sk_reuseport_detach
```
```
In mm/mempolicy.c (ffff80001033be84)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
```
```
In mm/zsmalloc.c (ffff800010375d8c)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/exec.c (ffff80001038eb14)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:unregister_binfmt
  - fs/exec.c:__register_binfmt
```
```
In fs/fcntl.c (ffff80001039d300)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_modown
```
```
In fs/filesystems.c (ffff8000103b2f48)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/filesystems.c:unregister_filesystem
  - fs/filesystems.c:unregister_filesystem
  - fs/filesystems.c:register_filesystem
```
```
In fs/eventpoll.c (ffff8000103f230c)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/eventpoll.c:__do_sys_epoll_ctl
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_remove
```
```
In fs/proc/generic.c (ffff8000104445b8)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:proc_register
  - fs/proc/generic.c:proc_register
```
```
In fs/ext4/extents_status.c (ffff80001047036c)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_remove_pending
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:ext4_es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
```
In fs/ext4/super.c (ffff8000104ae3d0)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_journal_params
```
```
In fs/jbd2/transaction.c (ffff8000104cc404)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_unlock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/jbd2/commit.c (ffff8000104ce0d4)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffff8000104d18dc)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
```
```
In fs/jbd2/journal.c (ffff8000104d544c)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_ack_err
  - fs/jbd2/journal.c:jbd2_journal_clear_err
  - fs/jbd2/journal.c:__journal_abort_soft
  - fs/jbd2/journal.c:__journal_abort_soft
  - fs/jbd2/journal.c:__journal_abort_soft
  - fs/jbd2/journal.c:jbd2_journal_flush
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
```
```
In security/keys/keyring.c (ffff800010530320)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_instantiate
  - security/keys/keyring.c:key_free_user_ns
```
```
In security/keys/keyctl.c (ffff800010533b30)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/selinux/ss/services.c (ffff800010567180)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
```
In security/apparmor/policy_ns.c (ffff8000105a1110)
Location: include/asm-generic/qrwlock.h:114
Inline: True
```
```
In security/apparmor/label.c (ffff8000105a2cbc)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
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
```
```
In security/integrity/iint.c (ffff8000105ac90c)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_free
  - security/integrity/iint.c:integrity_inode_get
```
```
In drivers/scsi/sg.c (ffff80001098f80c)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/net/ppp/ppp_generic.c (ffff8000109ffec0)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/cpufreq/cpufreq.c (ffff800010b1fc48)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
```
```
In drivers/leds/led-triggers.c (ffff800010b4a330)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
```
```
In net/core/sock.c (ffff800010bada94)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
```
```
In net/core/dev.c (ffff800010bd54e4)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
```
```
In net/core/neighbour.c (ffff800010be4370)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_for_each_release
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_probe
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:__neigh_ifdown
  - net/core/neighbour.c:neigh_changeaddr
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/core/rtnetlink.c (ffff800010becfc0)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:set_operstate
```
```
In net/core/link_watch.c (ffff800010bf37bc)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/skmsg.c (ffff800010c0f738)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_data_ready
  - net/core/skmsg.c:sk_psock_drop
```
```
In net/core/sock_map.c (ffff800010c1ff00)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_unref
```
```
In net/sched/sch_api.c (ffff800010c3e244)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:unregister_qdisc
  - net/sched/sch_api.c:register_qdisc
```
```
In net/sched/cls_api.c (ffff800010c415e8)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/sched/cls_api.c:register_tcf_proto_ops
```
```
In net/sched/act_api.c (ffff800010c46f04)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_unregister_action
```
```
In net/sched/ematch.c (ffff800010c49f70)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_unregister
  - net/sched/ematch.c:tcf_em_register
```
```
In net/netlink/af_netlink.c (ffff800010c4f094)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_table_ungrab
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6c950)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
```
```
In net/ipv4/tcp.c (ffff800010c758d8)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/raw.c (ffff800010c96dd0)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/arp.c (ffff800010ca1ea8)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
```
```
In net/ipv4/af_inet.c (ffff800010caa940)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv4/ping.c (ffff800010cc0cc4)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv4/ipmr.c (ffff800010ccda9c)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:vif_delete
```
```
In net/xfrm/xfrm_policy.c (ffff800010cda908)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
```
```
In net/unix/af_unix.c (ffff800010cf1600)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/anycast.c (ffff800010cf7a90)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffff800010d06fd4)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffff800010d12f44)
Location: include/asm-generic/qrwlock.h:114
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffff800010d19934)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_walker_unlink
  - net/ipv6/ip6_fib.c:fib6_walker_link
```
```
In net/ipv6/ipv6_sockglue.c (ffff800010d1dd24)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/mcast.c (ffff800010d34138)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ip6_mc_leave_src
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
```
```
In net/ipv6/ip6mr.c (ffff800010d46724)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:mif6_delete
```
```
In net/packet/af_packet.c (ffff800010d5c44c)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffff800010d7f230)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In kernel/fork.c (ffffffff8109955a)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff8109edad)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/resource.c (ffffffff810a369a)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__release_region
  - kernel/resource.c:__release_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:adjust_resource
  - kernel/resource.c:remove_resource
  - kernel/resource.c:insert_resource_expand_to_fit
  - kernel/resource.c:insert_resource_conflict
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:release_resource
  - kernel/resource.c:request_resource_conflict
  - kernel/resource.c:release_child_resources
```
```
In kernel/ptrace.c (ffffffff810a91bb)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/sys.c (ffffffff810b64da)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
```
In kernel/locking/spinlock.c (ffffffff81a738e5)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_write_unlock_bh
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d0a88)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
```
```
In mm/mempolicy.c (ffffffff812953de)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
```
```
In mm/zsmalloc.c (ffffffff812c8f4c)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/exec.c (ffffffff812dee44)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:unregister_binfmt
```
```
In fs/fcntl.c (ffffffff812eb2d1)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_modown
```
```
In fs/filesystems.c (ffffffff812f91b8)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/filesystems.c:register_filesystem
```
```
In fs/eventpoll.c (ffffffff8132dbcb)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
```
```
In fs/proc/generic.c (ffffffff81370a29)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:proc_register
  - fs/proc/generic.c:proc_register
```
```
In fs/ext4/extents_status.c (ffffffff81395794)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_remove_pending
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:ext4_es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
```
In fs/ext4/super.c (ffffffff813c937e)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_journal_params
```
```
In fs/jbd2/transaction.c (ffffffff813ea4f7)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_unlock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/jbd2/commit.c (ffffffff813eb23a)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff813ee252)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
```
```
In fs/jbd2/journal.c (ffffffff813ef181)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_ack_err
  - fs/jbd2/journal.c:jbd2_journal_clear_err
  - fs/jbd2/journal.c:__journal_abort_soft
  - fs/jbd2/journal.c:__journal_abort_soft
  - fs/jbd2/journal.c:__journal_abort_soft
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_start_commit
  - fs/jbd2/journal.c:jbd2_log_start_commit
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
```
```
In security/keys/keyring.c (ffffffff8143ed0e)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_instantiate
  - security/keys/keyring.c:key_free_user_ns
```
```
In security/keys/keyctl.c (ffffffff81442399)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/selinux/ss/services.c (ffffffff8146faee)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
```
In security/integrity/iint.c (ffffffff814acebe)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_free
  - security/integrity/iint.c:integrity_inode_get
```
```
In drivers/scsi/sg.c (ffffffff81740181)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
```
In net/core/neighbour.c (ffffffff818e4d78)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_for_each_release
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_probe
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_flush_dev
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/sched/sch_api.c (ffffffff81931b77)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:unregister_qdisc
  - net/sched/sch_api.c:register_qdisc
```
```
In net/sched/cls_api.c (ffffffff81933615)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/sched/cls_api.c:register_tcf_proto_ops
```
```
In net/sched/act_api.c (ffffffff81939a74)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_unregister_action
```
```
In net/sched/ematch.c (ffffffff8193c60e)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_unregister
  - net/sched/ematch.c:tcf_em_register
```
```
In net/netlink/af_netlink.c (ffffffff8193faf5)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_table_ungrab
```
```
In net/ipv6/addrconf.c (ffffffff819e4523)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff819ebc6d)
Location: include/asm-generic/qrwlock.h:114
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81a0ab86)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
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
In kernel/fork.c (ffffffff81087faa)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff8108d7d0)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/resource.c (ffffffff8109207a)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__release_region
  - kernel/resource.c:__release_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:adjust_resource
  - kernel/resource.c:remove_resource
  - kernel/resource.c:insert_resource_expand_to_fit
  - kernel/resource.c:insert_resource_conflict
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:release_resource
  - kernel/resource.c:request_resource_conflict
  - kernel/resource.c:release_child_resources
```
```
In kernel/ptrace.c (ffffffff81097b8b)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/sys.c (ffffffff810a4e1a)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
```
In kernel/locking/spinlock.c (ffffffff81a2fc55)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_write_unlock_bh
```
```
In kernel/trace/trace_uprobe.c (ffffffff811c3858)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
```
```
In mm/mempolicy.c (ffffffff81286fee)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
```
```
In mm/zsmalloc.c (ffffffff812b9f8c)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/exec.c (ffffffff812cef69)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:unregister_binfmt
```
```
In fs/fcntl.c (ffffffff812dbf01)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_modown
```
```
In fs/filesystems.c (ffffffff812e9dd8)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/filesystems.c:register_filesystem
```
```
In fs/eventpoll.c (ffffffff8131df53)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
```
```
In fs/proc/generic.c (ffffffff813614b9)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:proc_register
  - fs/proc/generic.c:proc_register
```
```
In fs/ext4/extents_status.c (ffffffff81386224)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_remove_pending
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:ext4_es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
```
In fs/ext4/super.c (ffffffff813b9dfe)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_journal_params
```
```
In fs/jbd2/transaction.c (ffffffff813daf77)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_unlock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/jbd2/commit.c (ffffffff813dbcba)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff813decd2)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
```
```
In fs/jbd2/journal.c (ffffffff813dfc01)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_ack_err
  - fs/jbd2/journal.c:jbd2_journal_clear_err
  - fs/jbd2/journal.c:__journal_abort_soft
  - fs/jbd2/journal.c:__journal_abort_soft
  - fs/jbd2/journal.c:__journal_abort_soft
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_start_commit
  - fs/jbd2/journal.c:jbd2_log_start_commit
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
```
```
In security/keys/keyring.c (ffffffff8142f77e)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_instantiate
  - security/keys/keyring.c:key_free_user_ns
```
```
In security/keys/keyctl.c (ffffffff81432df4)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/selinux/ss/services.c (ffffffff814604e6)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
```
In security/integrity/iint.c (ffffffff8149d8de)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_free
  - security/integrity/iint.c:integrity_inode_get
```
```
In drivers/scsi/sg.c (ffffffff81721e21)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
```
In net/core/neighbour.c (ffffffff8189ebb8)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_for_each_release
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_probe
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_flush_dev
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/sched/sch_api.c (ffffffff818eb677)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:unregister_qdisc
  - net/sched/sch_api.c:register_qdisc
```
```
In net/sched/cls_api.c (ffffffff818ed115)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/sched/cls_api.c:register_tcf_proto_ops
```
```
In net/sched/act_api.c (ffffffff818f3574)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_unregister_action
```
```
In net/sched/ematch.c (ffffffff818f610e)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_unregister
  - net/sched/ematch.c:tcf_em_register
```
```
In net/netlink/af_netlink.c (ffffffff818f95f5)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_table_ungrab
```
```
In net/ipv6/addrconf.c (ffffffff819a12e3)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff819a8a2d)
Location: include/asm-generic/qrwlock.h:114
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff819c7946)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
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
In kernel/fork.c (ffffffff8109950a)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff8109ed5d)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/resource.c (ffffffff810a364a)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__release_region
  - kernel/resource.c:__release_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:adjust_resource
  - kernel/resource.c:remove_resource
  - kernel/resource.c:insert_resource_expand_to_fit
  - kernel/resource.c:insert_resource_conflict
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:release_resource
  - kernel/resource.c:request_resource_conflict
  - kernel/resource.c:release_child_resources
```
```
In kernel/ptrace.c (ffffffff810a871b)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/sys.c (ffffffff810b5a3a)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
```
In kernel/locking/spinlock.c (ffffffff81adfcf5)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_write_unlock_bh
```
```
In kernel/trace/trace_uprobe.c (ffffffff811ce858)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
```
```
In mm/mempolicy.c (ffffffff812931ee)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
```
```
In mm/zsmalloc.c (ffffffff812c6d5c)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/exec.c (ffffffff812dcc54)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:unregister_binfmt
```
```
In fs/fcntl.c (ffffffff812e90e1)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_modown
```
```
In fs/filesystems.c (ffffffff812f6fb6)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/filesystems.c:register_filesystem
```
```
In fs/eventpoll.c (ffffffff8132b69b)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
```
```
In fs/proc/generic.c (ffffffff8136e4f9)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:proc_register
  - fs/proc/generic.c:proc_register
```
```
In fs/ext4/extents_status.c (ffffffff813930f4)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_remove_pending
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:ext4_es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
```
In fs/ext4/super.c (ffffffff813c680e)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_journal_params
```
```
In fs/jbd2/transaction.c (ffffffff813e7877)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_unlock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/jbd2/commit.c (ffffffff813e85ba)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff813eb5d2)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
```
```
In fs/jbd2/journal.c (ffffffff813ec501)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_ack_err
  - fs/jbd2/journal.c:jbd2_journal_clear_err
  - fs/jbd2/journal.c:__journal_abort_soft
  - fs/jbd2/journal.c:__journal_abort_soft
  - fs/jbd2/journal.c:__journal_abort_soft
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_start_commit
  - fs/jbd2/journal.c:jbd2_log_start_commit
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
```
```
In security/keys/keyring.c (ffffffff8143aeae)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_instantiate
  - security/keys/keyring.c:key_free_user_ns
```
```
In security/keys/keyctl.c (ffffffff8143e539)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/selinux/ss/services.c (ffffffff8146bb8e)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
```
In security/integrity/iint.c (ffffffff814a8f5e)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_free
  - security/integrity/iint.c:integrity_inode_get
```
```
In drivers/scsi/sg.c (ffffffff81780911)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
```
In net/core/neighbour.c (ffffffff81935da8)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_for_each_release
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_probe
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_flush_dev
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/sched/sch_api.c (ffffffff81982d07)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:unregister_qdisc
  - net/sched/sch_api.c:register_qdisc
```
```
In net/sched/cls_api.c (ffffffff819847a5)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/sched/cls_api.c:register_tcf_proto_ops
```
```
In net/sched/act_api.c (ffffffff8198ac04)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_unregister_action
```
```
In net/sched/ematch.c (ffffffff8198d79e)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_unregister
  - net/sched/ematch.c:tcf_em_register
```
```
In net/netlink/af_netlink.c (ffffffff81990c85)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_table_ungrab
```
```
In net/ipv6/addrconf.c (ffffffff81a4efa3)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81a566ed)
Location: include/asm-generic/qrwlock.h:114
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81a75606)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
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
In kernel/locking/spinlock.c (ffffffff81aec6a5)
Location: include/asm-generic/qrwlock.h:114
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_write_unlock_irq
  - kernel/locking/spinlock.c:_raw_write_unlock_bh
  - kernel/locking/spinlock.c:_raw_write_unlock
```
</details>
</li>
</ul>

## Differences

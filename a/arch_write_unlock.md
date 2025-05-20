# Function: <code>arch_write_unlock</code>

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
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c0352c70)
Location: arch/arm/include/asm/spinlock.h:182
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (c035940c)
Location: arch/arm/include/asm/spinlock.h:182
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/resource.c (c035cd60)
Location: arch/arm/include/asm/spinlock.h:182
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
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:release_resource
  - kernel/resource.c:request_resource_conflict
  - kernel/resource.c:release_child_resources
```
```
In kernel/ptrace.c (c036263c)
Location: arch/arm/include/asm/spinlock.h:182
Inline: True
Inline callers:
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/sys.c (c036d274)
Location: arch/arm/include/asm/spinlock.h:182
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__se_sys_setpgid
```
```
In kernel/locking/spinlock.c (c0e9f0c0)
Location: arch/arm/include/asm/spinlock.h:182
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_write_unlock_bh
```
```
In kernel/trace/trace_uprobe.c (c048b67c)
Location: arch/arm/include/asm/spinlock.h:182
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
```
```
In mm/zsmalloc.c (c0561d88)
Location: arch/arm/include/asm/spinlock.h:182
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/exec.c (c0575088)
Location: arch/arm/include/asm/spinlock.h:182
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:unregister_binfmt
  - fs/exec.c:__register_binfmt
```
```
In fs/fcntl.c (c0582b70)
Location: arch/arm/include/asm/spinlock.h:182
Inline: True
Inline callers:
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_modown
```
```
In fs/filesystems.c (c0591df4)
Location: arch/arm/include/asm/spinlock.h:182
Inline: True
Inline callers:
  - fs/filesystems.c:register_filesystem
```
```
In fs/eventpoll.c (c05c6568)
Location: arch/arm/include/asm/spinlock.h:182
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:__do_sys_epoll_ctl
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
```
```
In fs/proc/generic.c (c0609630)
Location: arch/arm/include/asm/spinlock.h:182
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
In fs/ext4/extents_status.c (c06317d8)
Location: arch/arm/include/asm/spinlock.h:182
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
In fs/ext4/super.c (c066b89c)
Location: arch/arm/include/asm/spinlock.h:182
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_journal_params
```
```
In fs/jbd2/transaction.c (c068fd0c)
Location: arch/arm/include/asm/spinlock.h:182
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
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/commit.c (c0690cf0)
Location: arch/arm/include/asm/spinlock.h:182
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
In fs/jbd2/checkpoint.c (c0694334)
Location: arch/arm/include/asm/spinlock.h:182
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
```
```
In fs/jbd2/journal.c (c069537c)
Location: arch/arm/include/asm/spinlock.h:182
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
In security/keys/keyring.c (c06e7be0)
Location: arch/arm/include/asm/spinlock.h:182
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_instantiate
  - security/keys/keyring.c:key_free_user_ns
```
```
In security/keys/keyctl.c (c06eb364)
Location: arch/arm/include/asm/spinlock.h:182
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/selinux/ss/services.c (c071b708)
Location: arch/arm/include/asm/spinlock.h:182
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
```
In security/integrity/iint.c (c075c2b4)
Location: arch/arm/include/asm/spinlock.h:182
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_free
  - security/integrity/iint.c:integrity_inode_get
```
```
In drivers/scsi/sg.c (c0a64c3c)
Location: arch/arm/include/asm/spinlock.h:182
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
```
In net/core/neighbour.c (c0cff114)
Location: arch/arm/include/asm/spinlock.h:182
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
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_flush_dev
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/sched/sch_api.c (c0d4fcd8)
Location: arch/arm/include/asm/spinlock.h:182
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:unregister_qdisc
  - net/sched/sch_api.c:register_qdisc
```
```
In net/sched/cls_api.c (c0d51818)
Location: arch/arm/include/asm/spinlock.h:182
Inline: True
Inline callers:
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/sched/cls_api.c:register_tcf_proto_ops
```
```
In net/sched/act_api.c (c0d579e0)
Location: arch/arm/include/asm/spinlock.h:182
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_unregister_action
```
```
In net/sched/ematch.c (c0d5a818)
Location: arch/arm/include/asm/spinlock.h:182
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_unregister
  - net/sched/ematch.c:tcf_em_register
```
```
In net/netlink/af_netlink.c (c0d5e3ac)
Location: arch/arm/include/asm/spinlock.h:182
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_table_ungrab
```
```
In net/ipv6/addrconf.c (c0e0de88)
Location: arch/arm/include/asm/spinlock.h:182
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (c0e16b10)
Location: arch/arm/include/asm/spinlock.h:182
Inline: True
```
```
In net/ipv6/mcast.c (c0e35abc)
Location: arch/arm/include/asm/spinlock.h:182
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
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
In arch/powerpc/platforms/pseries/lpar.c (c0000000000eab0c)
Location: arch/powerpc/include/asm/spinlock.h:308
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/lpar.c:vcpudispatch_stats_write
  - arch/powerpc/platforms/pseries/lpar.c:vcpudispatch_stats_write
```
```
In kernel/fork.c (c00000000013a5d4)
Location: arch/powerpc/include/asm/spinlock.h:308
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (c00000000014246c)
Location: arch/powerpc/include/asm/spinlock.h:308
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/resource.c (c0000000001495e0)
Location: arch/powerpc/include/asm/spinlock.h:308
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
In kernel/ptrace.c (c0000000001504f8)
Location: arch/powerpc/include/asm/spinlock.h:308
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/sys.c (c0000000001606c0)
Location: arch/powerpc/include/asm/spinlock.h:308
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__se_sys_setpgid
```
```
In kernel/locking/spinlock.c (c000000000eea12c)
Location: arch/powerpc/include/asm/spinlock.h:308
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_write_unlock_bh
```
```
In kernel/trace/trace_uprobe.c (c0000000002fba50)
Location: arch/powerpc/include/asm/spinlock.h:308
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
```
```
In mm/mempolicy.c (c000000000416da8)
Location: arch/powerpc/include/asm/spinlock.h:308
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
```
```
In mm/zsmalloc.c (c000000000468458)
Location: arch/powerpc/include/asm/spinlock.h:308
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/exec.c (c000000000485a7c)
Location: arch/powerpc/include/asm/spinlock.h:308
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:unregister_binfmt
  - fs/exec.c:__register_binfmt
```
```
In fs/fcntl.c (c000000000498050)
Location: arch/powerpc/include/asm/spinlock.h:308
Inline: True
Inline callers:
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_modown
```
```
In fs/filesystems.c (c0000000004aeb38)
Location: arch/powerpc/include/asm/spinlock.h:308
Inline: True
Inline callers:
  - fs/filesystems.c:register_filesystem
```
```
In fs/eventpoll.c (c0000000004fa4b8)
Location: arch/powerpc/include/asm/spinlock.h:308
Inline: True
Inline callers:
  - fs/eventpoll.c:__se_sys_epoll_ctl
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_remove
```
```
In fs/proc/generic.c (c000000000559d80)
Location: arch/powerpc/include/asm/spinlock.h:308
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
In fs/ext4/extents_status.c (c00000000059099c)
Location: arch/powerpc/include/asm/spinlock.h:308
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
In fs/ext4/super.c (c0000000005d7278)
Location: arch/powerpc/include/asm/spinlock.h:308
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_journal_params
```
```
In fs/jbd2/transaction.c (c000000000605968)
Location: arch/powerpc/include/asm/spinlock.h:308
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
In fs/jbd2/commit.c (c000000000606cc8)
Location: arch/powerpc/include/asm/spinlock.h:308
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
In fs/jbd2/checkpoint.c (c00000000060adbc)
Location: arch/powerpc/include/asm/spinlock.h:308
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
```
```
In fs/jbd2/journal.c (c00000000060c888)
Location: arch/powerpc/include/asm/spinlock.h:308
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
  - fs/jbd2/journal.c:jbd2_journal_next_log_block
  - fs/jbd2/journal.c:jbd2_journal_start_commit
  - fs/jbd2/journal.c:jbd2_log_start_commit
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
```
```
In security/keys/keyring.c (c00000000067c7dc)
Location: arch/powerpc/include/asm/spinlock.h:308
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_instantiate
  - security/keys/keyring.c:key_free_user_ns
```
```
In security/keys/keyctl.c (c0000000006819dc)
Location: arch/powerpc/include/asm/spinlock.h:308
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/selinux/ss/services.c (c0000000006ca4b0)
Location: arch/powerpc/include/asm/spinlock.h:308
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
```
In security/integrity/iint.c (c00000000072ae10)
Location: arch/powerpc/include/asm/spinlock.h:308
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_free
  - security/integrity/iint.c:integrity_inode_get
```
```
In drivers/scsi/sg.c (c000000000a560c8)
Location: arch/powerpc/include/asm/spinlock.h:308
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
```
In net/core/neighbour.c (c000000000cc83b0)
Location: arch/powerpc/include/asm/spinlock.h:308
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
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_flush_dev
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/sched/sch_api.c (c000000000d382ec)
Location: arch/powerpc/include/asm/spinlock.h:308
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:unregister_qdisc
  - net/sched/sch_api.c:register_qdisc
```
```
In net/sched/cls_api.c (c000000000d3a518)
Location: arch/powerpc/include/asm/spinlock.h:308
Inline: True
Inline callers:
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/sched/cls_api.c:register_tcf_proto_ops
```
```
In net/sched/act_api.c (c000000000d432d4)
Location: arch/powerpc/include/asm/spinlock.h:308
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_unregister_action
```
```
In net/sched/ematch.c (c000000000d474f4)
Location: arch/powerpc/include/asm/spinlock.h:308
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_unregister
  - net/sched/ematch.c:tcf_em_register
```
```
In net/netlink/af_netlink.c (c000000000d4c4dc)
Location: arch/powerpc/include/asm/spinlock.h:308
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_table_ungrab
```
```
In net/ipv6/addrconf.c (c000000000e31800)
Location: arch/powerpc/include/asm/spinlock.h:308
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (c000000000e3cb7c)
Location: arch/powerpc/include/asm/spinlock.h:308
Inline: True
```
```
In net/ipv6/mcast.c (c000000000e651e0)
Location: arch/powerpc/include/asm/spinlock.h:308
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
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
In kernel/fork.c (ffffffe0000c0954)
Location: arch/riscv/include/asm/spinlock.h:130
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffe0000c4ffa)
Location: arch/riscv/include/asm/spinlock.h:130
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/resource.c (ffffffe0000c835e)
Location: arch/riscv/include/asm/spinlock.h:130
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
In kernel/ptrace.c (ffffffe0000cc366)
Location: arch/riscv/include/asm/spinlock.h:130
Inline: True
Inline callers:
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/sys.c (ffffffe0000d3fa8)
Location: arch/riscv/include/asm/spinlock.h:130
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__se_sys_setpgid
```
```
In kernel/locking/spinlock.c (ffffffe0008c95c8)
Location: arch/riscv/include/asm/spinlock.h:130
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_write_unlock_bh
```
```
In mm/zsmalloc.c (ffffffe00024e508)
Location: arch/riscv/include/asm/spinlock.h:130
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/exec.c (ffffffe00025e40e)
Location: arch/riscv/include/asm/spinlock.h:130
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:unregister_binfmt
  - fs/exec.c:__register_binfmt
```
```
In fs/fcntl.c (ffffffe0002693a2)
Location: arch/riscv/include/asm/spinlock.h:130
Inline: True
Inline callers:
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_modown
```
```
In fs/filesystems.c (ffffffe000276b24)
Location: arch/riscv/include/asm/spinlock.h:130
Inline: True
Inline callers:
  - fs/filesystems.c:register_filesystem
```
```
In fs/eventpoll.c (ffffffe0002a331e)
Location: arch/riscv/include/asm/spinlock.h:130
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:__se_sys_epoll_ctl
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
```
```
In fs/proc/generic.c (ffffffe0002d9f16)
Location: arch/riscv/include/asm/spinlock.h:130
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
In fs/ext4/extents_status.c (ffffffe0002fcaee)
Location: arch/riscv/include/asm/spinlock.h:130
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
In fs/ext4/super.c (ffffffe000329732)
Location: arch/riscv/include/asm/spinlock.h:130
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_journal_params
```
```
In fs/jbd2/transaction.c (ffffffe000344f9a)
Location: arch/riscv/include/asm/spinlock.h:130
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
In fs/jbd2/commit.c (ffffffe000345ca8)
Location: arch/riscv/include/asm/spinlock.h:130
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
In fs/jbd2/checkpoint.c (ffffffe000348c1e)
Location: arch/riscv/include/asm/spinlock.h:130
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
```
```
In fs/jbd2/journal.c (ffffffe000349d04)
Location: arch/riscv/include/asm/spinlock.h:130
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
In security/keys/keyring.c (ffffffe000391132)
Location: arch/riscv/include/asm/spinlock.h:130
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_instantiate
  - security/keys/keyring.c:key_free_user_ns
```
```
In security/keys/keyctl.c (ffffffe000393f46)
Location: arch/riscv/include/asm/spinlock.h:130
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/selinux/ss/services.c (ffffffe0003bcf30)
Location: arch/riscv/include/asm/spinlock.h:130
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
```
In security/integrity/iint.c (ffffffe0003f50d2)
Location: arch/riscv/include/asm/spinlock.h:130
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_free
  - security/integrity/iint.c:integrity_inode_get
```
```
In drivers/scsi/sg.c (ffffffe0005f5ff6)
Location: arch/riscv/include/asm/spinlock.h:130
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
```
In net/core/neighbour.c (ffffffe00076b46e)
Location: arch/riscv/include/asm/spinlock.h:130
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
In net/sched/sch_api.c (ffffffe0007ae37a)
Location: arch/riscv/include/asm/spinlock.h:130
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:unregister_qdisc
  - net/sched/sch_api.c:register_qdisc
```
```
In net/sched/cls_api.c (ffffffe0007af724)
Location: arch/riscv/include/asm/spinlock.h:130
Inline: True
Inline callers:
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/sched/cls_api.c:register_tcf_proto_ops
```
```
In net/sched/act_api.c (ffffffe0007b4cfe)
Location: arch/riscv/include/asm/spinlock.h:130
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_unregister_action
```
```
In net/sched/ematch.c (ffffffe0007b7110)
Location: arch/riscv/include/asm/spinlock.h:130
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_unregister
  - net/sched/ematch.c:tcf_em_register
```
```
In net/netlink/af_netlink.c (ffffffe0007ba2bc)
Location: arch/riscv/include/asm/spinlock.h:130
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_table_ungrab
```
```
In net/ipv6/addrconf.c (ffffffe00084f892)
Location: arch/riscv/include/asm/spinlock.h:130
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffe00085714a)
Location: arch/riscv/include/asm/spinlock.h:130
Inline: True
```
```
In net/ipv6/mcast.c (ffffffe0008711d6)
Location: arch/riscv/include/asm/spinlock.h:130
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
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

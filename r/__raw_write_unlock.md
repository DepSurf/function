# Function: <code>__raw_write_unlock</code>

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
In kernel/resource.c (ffffffff81085ff9)
Location: include/linux/rwlock_api_smp.h:216
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
In kernel/trace/trace_uprobe.c (ffffffff8116f94e)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
```
In fs/exec.c (ffffffff81211fe2)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/exec.c:unregister_binfmt
```
```
In fs/filesystems.c (ffffffff8122b11d)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/filesystems.c:unregister_filesystem
  - fs/filesystems.c:unregister_filesystem
```
```
In fs/proc/generic.c (ffffffff8127f2c1)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
```
```
In fs/proc/kcore.c (ffffffff81286de9)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In fs/ext4/super.c (ffffffff812a8f95)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_journal_params
```
```
In fs/ext4/extents_status.c (ffffffff812db5df)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_remove_extent
```
```
In fs/jbd2/transaction.c (ffffffff812e6e77)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
```
```
In fs/jbd2/journal.c (ffffffff812ee044)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_instantiate
  - security/keys/keyring.c:keyring_destroy
```
```
In security/integrity/iint.c (ffffffff81396374)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/iint.c:integrity_inode_free
```
```
In net/core/gen_estimator.c (ffffffff8170f6bc)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_kill_estimator
```
```
In net/core/neighbour.c (ffffffff8172484e)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/sch_api.c:unregister_qdisc
  - net/sched/sch_api.c:register_qdisc
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
```
```
In net/sched/cls_api.c (ffffffff81745aa4)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/cls_api.c:register_tcf_proto_ops
  - net/sched/cls_api.c:unregister_tcf_proto_ops
```
```
In net/sched/act_api.c (ffffffff81746eeb)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_unregister_action
```
```
In net/sched/ematch.c (ffffffff8174949e)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_register
  - net/sched/ematch.c:tcf_em_unregister
```
```
In net/ipv6/addrconf.c (ffffffff817ca84d)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
```
```
In net/ipv6/route.c (ffffffff817d5852)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff817ec626)
Location: include/linux/rwlock_api_smp.h:216
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
In kernel/resource.c (ffffffff81089546)
Location: include/linux/rwlock_api_smp.h:216
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
In kernel/trace/trace_uprobe.c (ffffffff8117d95b)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
```
In mm/mempolicy.c (ffffffff81201cbe)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
```
```
In mm/zsmalloc.c (ffffffff8122b476)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/exec.c (ffffffff81238ab2)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/exec.c:unregister_binfmt
```
```
In fs/filesystems.c (ffffffff8125387d)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/filesystems.c:unregister_filesystem
  - fs/filesystems.c:unregister_filesystem
```
```
In fs/proc/generic.c (ffffffff812acbb1)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_entry
```
```
In fs/proc/kcore.c (ffffffff812b3fc3)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In fs/ext4/super.c (ffffffff812d813e)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_journal_params
```
```
In fs/ext4/extents_status.c (ffffffff8130af5f)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:ext4_es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
```
In fs/jbd2/transaction.c (ffffffff81316f63)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
```
```
In fs/jbd2/journal.c (ffffffff8131b9f1)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_instantiate
```
```
In security/integrity/iint.c (ffffffff813d214c)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_free
  - security/integrity/iint.c:integrity_inode_get
```
```
In net/core/gen_estimator.c (ffffffff81776faa)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_kill_estimator
```
```
In net/core/neighbour.c (ffffffff81791421)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:unregister_qdisc
  - net/sched/sch_api.c:register_qdisc
```
```
In net/sched/cls_api.c (ffffffff817b2a32)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/sched/cls_api.c:register_tcf_proto_ops
```
```
In net/sched/act_api.c (ffffffff817b4145)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_unregister_action
```
```
In net/sched/ematch.c (ffffffff817b6474)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_unregister
  - net/sched/ematch.c:tcf_em_register
```
```
In net/ipv6/addrconf.c (ffffffff8183ceff)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
```
```
In net/ipv6/route.c (ffffffff81843c99)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff8185b2f6)
Location: include/linux/rwlock_api_smp.h:216
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
In kernel/resource.c (ffffffff8108e496)
Location: include/linux/rwlock_api_smp.h:216
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
In kernel/trace/trace_uprobe.c (ffffffff8118956b)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
```
In mm/mempolicy.c (ffffffff812137ce)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
```
```
In mm/zsmalloc.c (ffffffff8123d9d3)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/exec.c (ffffffff8124b762)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/exec.c:unregister_binfmt
```
```
In fs/filesystems.c (ffffffff81266acd)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/filesystems.c:unregister_filesystem
  - fs/filesystems.c:unregister_filesystem
```
```
In fs/proc/generic.c (ffffffff812c24a1)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_entry
```
```
In fs/proc/kcore.c (ffffffff812c985b)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In fs/ext4/super.c (ffffffff812edd1e)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_journal_params
```
```
In fs/ext4/extents_status.c (ffffffff81320f5f)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:ext4_es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
```
In fs/jbd2/transaction.c (ffffffff8132cf6a)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
```
```
In fs/jbd2/journal.c (ffffffff813319e1)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_instantiate
```
```
In security/integrity/iint.c (ffffffff813e986c)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_free
  - security/integrity/iint.c:integrity_inode_get
```
```
In net/core/neighbour.c (ffffffff817becf1)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:unregister_qdisc
  - net/sched/sch_api.c:register_qdisc
```
```
In net/sched/cls_api.c (ffffffff817e22b2)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/sched/cls_api.c:register_tcf_proto_ops
```
```
In net/sched/act_api.c (ffffffff817e39e6)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_unregister_action
```
```
In net/sched/ematch.c (ffffffff817e5f04)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_unregister
  - net/sched/ematch.c:tcf_em_register
```
```
In net/ipv6/addrconf.c (ffffffff8186e9c1)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
```
```
In net/ipv6/route.c (ffffffff81875a10)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff8188d196)
Location: include/linux/rwlock_api_smp.h:216
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
In kernel/resource.c (ffffffff8108b4b6)
Location: include/linux/rwlock_api_smp.h:216
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
In kernel/trace/trace_uprobe.c (ffffffff8118c0d7)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
```
In mm/mempolicy.c (ffffffff8121eade)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
```
```
In mm/zsmalloc.c (ffffffff81248bb8)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/exec.c (ffffffff8125788e)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/exec.c:unregister_binfmt
```
```
In fs/filesystems.c (ffffffff8127434d)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/filesystems.c:unregister_filesystem
  - fs/filesystems.c:unregister_filesystem
  - fs/filesystems.c:register_filesystem
```
```
In fs/proc/generic.c (ffffffff812cf731)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_entry
```
```
In fs/proc/kcore.c (ffffffff820db3e0)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:kcore_update_ram
```
```
In fs/ext4/extents_status.c (ffffffff812efe4c)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:ext4_es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
```
In fs/ext4/super.c (ffffffff81322cde)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_journal_params
```
```
In fs/jbd2/transaction.c (ffffffff81342130)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
```
```
In fs/jbd2/journal.c (ffffffff813468d1)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_instantiate
```
```
In security/integrity/iint.c (ffffffff813f5c6d)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_free
  - security/integrity/iint.c:integrity_inode_get
```
```
In net/core/neighbour.c (ffffffff817dd2b1)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:unregister_qdisc
  - net/sched/sch_api.c:register_qdisc
```
```
In net/sched/cls_api.c (ffffffff81801800)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/sched/cls_api.c:register_tcf_proto_ops
```
```
In net/sched/act_api.c (ffffffff81803b07)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
```
```
In net/sched/ematch.c (ffffffff81805a30)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_unregister
  - net/sched/ematch.c:tcf_em_register
```
```
In net/ipv6/addrconf.c (ffffffff818937bb)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff8189a08f)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff818b387b)
Location: include/linux/rwlock_api_smp.h:216
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
In kernel/resource.c (ffffffff81092196)
Location: include/linux/rwlock_api_smp.h:216
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
In kernel/trace/trace_uprobe.c (ffffffff81199b9d)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
```
In mm/mempolicy.c (ffffffff81239cfe)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
```
```
In mm/zsmalloc.c (ffffffff81268dab)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/exec.c (ffffffff81279ade)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/exec.c:unregister_binfmt
  - fs/exec.c:__register_binfmt
```
```
In fs/filesystems.c (ffffffff81296c4d)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/filesystems.c:unregister_filesystem
  - fs/filesystems.c:unregister_filesystem
  - fs/filesystems.c:register_filesystem
```
```
In fs/proc/generic.c (ffffffff812f3e89)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_entry
```
```
In fs/proc/kcore.c (ffffffff826e4075)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:kcore_update_ram
```
```
In fs/ext4/extents_status.c (ffffffff8131494c)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:ext4_es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
```
In fs/ext4/super.c (ffffffff8134742e)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_journal_params
```
```
In fs/jbd2/transaction.c (ffffffff81366760)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
```
```
In fs/jbd2/journal.c (ffffffff8136afc1)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_instantiate
```
```
In security/integrity/iint.c (ffffffff8141dd5d)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_free
  - security/integrity/iint.c:integrity_inode_get
```
```
In net/core/neighbour.c (ffffffff81858343)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:unregister_qdisc
  - net/sched/sch_api.c:register_qdisc
```
```
In net/sched/cls_api.c (ffffffff8187f50c)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/sched/cls_api.c:register_tcf_proto_ops
```
```
In net/sched/act_api.c (ffffffff81881ff7)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
```
```
In net/sched/ematch.c (ffffffff81884750)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_unregister
  - net/sched/ematch.c:tcf_em_register
```
```
In net/ipv6/addrconf.c (ffffffff81914aa9)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff8191b5bf)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff819365fb)
Location: include/linux/rwlock_api_smp.h:216
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
In kernel/resource.c (ffffffff81096df7)
Location: include/linux/rwlock_api_smp.h:216
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
In kernel/trace/trace_uprobe.c (ffffffff811af3da)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
```
In mm/mempolicy.c (ffffffff8125d2ce)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
```
```
In mm/zsmalloc.c (ffffffff8128dd5c)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/exec.c (ffffffff812a06be)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/exec.c:unregister_binfmt
  - fs/exec.c:__register_binfmt
```
```
In fs/filesystems.c (ffffffff812bcdf7)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/filesystems.c:register_filesystem
```
```
In fs/proc/generic.c (ffffffff81320f64)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:ext4_es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
```
In fs/ext4/super.c (ffffffff8137539e)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_journal_params
```
```
In fs/jbd2/transaction.c (ffffffff81394d96)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
```
```
In fs/jbd2/journal.c (ffffffff81399771)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_instantiate
```
```
In security/integrity/iint.c (ffffffff8145000c)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_free
  - security/integrity/iint.c:integrity_inode_get
```
```
In net/core/neighbour.c (ffffffff818a3733)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:unregister_qdisc
  - net/sched/sch_api.c:register_qdisc
```
```
In net/sched/cls_api.c (ffffffff818d232c)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/sched/cls_api.c:register_tcf_proto_ops
```
```
In net/sched/act_api.c (ffffffff818d52c4)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_unregister_action
```
```
In net/sched/ematch.c (ffffffff818d82d0)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_unregister
  - net/sched/ematch.c:tcf_em_register
```
```
In net/ipv6/addrconf.c (ffffffff8196c0f6)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81973293)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff8198f286)
Location: include/linux/rwlock_api_smp.h:216
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
In kernel/resource.c (ffffffff8109f120)
Location: include/linux/rwlock_api_smp.h:216
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
In kernel/trace/trace_uprobe.c (ffffffff811bdab6)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
```
In mm/mempolicy.c (ffffffff81271b8e)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
```
```
In mm/zsmalloc.c (ffffffff812a36a1)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/exec.c (ffffffff812b569e)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/exec.c:unregister_binfmt
  - fs/exec.c:__register_binfmt
```
```
In fs/filesystems.c (ffffffff812d20b7)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/filesystems.c:register_filesystem
```
```
In fs/proc/generic.c (ffffffff8133806d)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_journal_params
```
```
In fs/jbd2/transaction.c (ffffffff813adb06)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
```
```
In fs/jbd2/journal.c (ffffffff813b24e1)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_instantiate
```
```
In security/integrity/iint.c (ffffffff8146cfec)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_free
  - security/integrity/iint.c:integrity_inode_get
```
```
In net/core/neighbour.c (ffffffff818c6670)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:unregister_qdisc
  - net/sched/sch_api.c:register_qdisc
```
```
In net/sched/cls_api.c (ffffffff818fd8cc)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/sched/cls_api.c:register_tcf_proto_ops
```
```
In net/sched/act_api.c (ffffffff81901f04)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_unregister_action
```
```
In net/sched/ematch.c (ffffffff81904ac0)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_unregister
  - net/sched/ematch.c:tcf_em_register
```
```
In net/ipv6/addrconf.c (ffffffff819a1b96)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff819a8eb3)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff819c5b46)
Location: include/linux/rwlock_api_smp.h:216
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
In kernel/resource.c (ffffffff810a374a)
Location: include/linux/rwlock_api_smp.h:216
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
In kernel/trace/trace_uprobe.c (ffffffff811cc8d9)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
```
```
In mm/mempolicy.c (ffffffff8128d1ce)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
```
```
In mm/zsmalloc.c (ffffffff812bea0b)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/exec.c (ffffffff812d244c)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/exec.c:unregister_binfmt
  - fs/exec.c:__register_binfmt
```
```
In fs/filesystems.c (ffffffff812ef118)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/filesystems.c:register_filesystem
```
```
In fs/proc/generic.c (ffffffff813601e9)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_journal_params
```
```
In fs/jbd2/transaction.c (ffffffff813d7e47)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
```
```
In fs/jbd2/journal.c (ffffffff813dcb51)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_instantiate
  - security/keys/keyring.c:key_free_user_ns
```
```
In security/integrity/iint.c (ffffffff8149a6de)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_free
  - security/integrity/iint.c:integrity_inode_get
```
```
In net/core/neighbour.c (ffffffff81912748)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:unregister_qdisc
  - net/sched/sch_api.c:register_qdisc
```
```
In net/sched/cls_api.c (ffffffff8195d2a5)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/sched/cls_api.c:register_tcf_proto_ops
```
```
In net/sched/act_api.c (ffffffff81963084)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_unregister_action
```
```
In net/sched/ematch.c (ffffffff81965d0e)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_unregister
  - net/sched/ematch.c:tcf_em_register
```
```
In net/ipv6/addrconf.c (ffffffff81a0e153)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81a159c3)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81a349a6)
Location: include/linux/rwlock_api_smp.h:216
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
In kernel/resource.c (ffffffff810a9d7a)
Location: include/linux/rwlock_api_smp.h:216
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
In kernel/trace/trace_uprobe.c (ffffffff811d8468)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
```
```
In mm/mempolicy.c (ffffffff8129cdfe)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
```
```
In mm/zsmalloc.c (ffffffff812d096c)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/exec.c (ffffffff812e3fdc)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/exec.c:unregister_binfmt
```
```
In fs/filesystems.c (ffffffff81300bd8)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/filesystems.c:register_filesystem
```
```
In fs/proc/generic.c (ffffffff81378449)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_journal_params
```
```
In fs/jbd2/transaction.c (ffffffff813f1f17)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
```
```
In fs/jbd2/journal.c (ffffffff813f6ba1)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_instantiate
  - security/keys/keyring.c:key_free_user_ns
```
```
In security/integrity/iint.c (ffffffff814b48de)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_free
  - security/integrity/iint.c:integrity_inode_get
```
```
In net/core/neighbour.c (ffffffff81944da8)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:unregister_qdisc
  - net/sched/sch_api.c:register_qdisc
```
```
In net/sched/cls_api.c (ffffffff819937a5)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/sched/cls_api.c:register_tcf_proto_ops
```
```
In net/sched/act_api.c (ffffffff81999c04)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_unregister_action
```
```
In net/sched/ematch.c (ffffffff8199c79e)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_unregister
  - net/sched/ematch.c:tcf_em_register
```
```
In net/ipv6/addrconf.c (ffffffff81a44e93)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81a4c5dd)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81a6b4f6)
Location: include/linux/rwlock_api_smp.h:216
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
In kernel/resource.c (ffffffff810b07d7)
Location: include/linux/rwlock_api_smp.h:216
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
In kernel/trace/trace_uprobe.c (ffffffff811f5269)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_open
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
```
```
In mm/mempolicy.c (ffffffff812d09de)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:shared_policy_replace
```
```
In mm/zsmalloc.c (ffffffff81307098)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/exec.c (ffffffff8131b38c)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/exec.c:unregister_binfmt
  - fs/exec.c:__register_binfmt
```
```
In fs/filesystems.c (ffffffff81339d92)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/filesystems.c:register_filesystem
```
```
In fs/proc/generic.c (ffffffff813c150c)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_journal_params
```
```
In fs/jbd2/transaction.c (ffffffff8143f248)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
```
```
In fs/jbd2/journal.c (ffffffff81443f61)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_instantiate
  - security/keys/keyring.c:key_free_user_ns
```
```
In security/integrity/iint.c (ffffffff81513e6e)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_free
  - security/integrity/iint.c:integrity_inode_get
```
```
In net/core/neighbour.c (ffffffff81a1521c)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:unregister_qdisc
  - net/sched/sch_api.c:register_qdisc
```
```
In net/sched/cls_api.c (ffffffff81a6b835)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/sched/cls_api.c:register_tcf_proto_ops
```
```
In net/sched/act_api.c (ffffffff81a72534)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_unregister_action
  - net/sched/act_api.c:tcf_register_action
  - net/sched/act_api.c:tcf_register_action
```
```
In net/sched/ematch.c (ffffffff81a7583e)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_unregister
  - net/sched/ematch.c:tcf_em_register
```
```
In net/ipv6/addrconf.c (ffffffff81b3b9d9)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81b425c7)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_probe
```
```
In net/ipv6/mcast.c (ffffffff81b64443)
Location: include/linux/rwlock_api_smp.h:216
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
In kernel/resource.c (ffffffff810abef7)
Location: include/linux/rwlock_api_smp.h:216
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
In kernel/trace/trace_uprobe.c (ffffffff811f3bf9)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_open
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
```
```
In mm/mempolicy.c (ffffffff812dc4fe)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:shared_policy_replace
```
```
In mm/zsmalloc.c (ffffffff81312dd8)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/exec.c (ffffffff813269bc)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/exec.c:unregister_binfmt
  - fs/exec.c:__register_binfmt
```
```
In fs/filesystems.c (ffffffff81345aa2)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/filesystems.c:register_filesystem
```
```
In fs/proc/generic.c (ffffffff813d33fc)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_journal_params
```
```
In fs/jbd2/transaction.c (ffffffff8145b4a8)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
```
```
In fs/jbd2/journal.c (ffffffff81460641)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_instantiate
  - security/keys/keyring.c:key_free_user_ns
```
```
In security/integrity/iint.c (ffffffff81530fce)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_free
  - security/integrity/iint.c:integrity_inode_get
```
```
In net/core/neighbour.c (ffffffff81a1550c)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:unregister_qdisc
  - net/sched/sch_api.c:register_qdisc
```
```
In net/sched/cls_api.c (ffffffff81a73fa5)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/sched/cls_api.c:register_tcf_proto_ops
```
```
In net/sched/act_api.c (ffffffff81a7b0f4)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_unregister_action
  - net/sched/act_api.c:tcf_register_action
  - net/sched/act_api.c:tcf_register_action
```
```
In net/sched/ematch.c (ffffffff81a7e60e)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_unregister
  - net/sched/ematch.c:tcf_em_register
```
```
In net/ipv6/addrconf.c (ffffffff81b4a6e9)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81b50f87)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_probe
```
```
In net/ipv6/mcast.c (ffffffff81b72bbc)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
```
```
In net/packet/af_packet.c (ffffffff81b94b86)
Location: include/linux/rwlock_api_smp.h:216
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
In kernel/resource.c (ffffffff810ad514)
Location: include/linux/rwlock_api_smp.h:216
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
In kernel/sched/core.c (ffffffff810e0b6c)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f5024)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
```
```
In mm/mempolicy.c (ffffffff812e3d5e)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:shared_policy_replace
```
```
In mm/zsmalloc.c (ffffffff81319309)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/exec.c (ffffffff8132cacc)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/exec.c:unregister_binfmt
  - fs/exec.c:__register_binfmt
```
```
In fs/filesystems.c (ffffffff8134be62)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/filesystems.c:register_filesystem
```
```
In fs/proc/generic.c (ffffffff813da238)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_set_largest_free_order
  - fs/ext4/mballoc.c:mb_set_largest_free_order
```
```
In fs/ext4/super.c (ffffffff81443283)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_journal_params
```
```
In fs/jbd2/transaction.c (ffffffff81460de8)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
```
```
In fs/jbd2/journal.c (ffffffff81465df1)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_instantiate
  - security/keys/keyring.c:key_free_user_ns
```
```
In security/integrity/iint.c (ffffffff815393fe)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_free
  - security/integrity/iint.c:integrity_inode_get
```
```
In net/core/neighbour.c (ffffffff819fc06c)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:unregister_qdisc
  - net/sched/sch_api.c:register_qdisc
```
```
In net/sched/cls_api.c (ffffffff81a5caf5)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/sched/cls_api.c:register_tcf_proto_ops
```
```
In net/sched/act_api.c (ffffffff81a63e54)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_unregister_action
  - net/sched/act_api.c:tcf_register_action
  - net/sched/act_api.c:tcf_register_action
```
```
In net/sched/ematch.c (ffffffff81a6746e)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_unregister
  - net/sched/ematch.c:tcf_em_register
```
```
In net/ipv6/addrconf.c (ffffffff81b3826e)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81b3ee97)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_probe
```
```
In net/packet/af_packet.c (ffffffff81b83c66)
Location: include/linux/rwlock_api_smp.h:216
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
In kernel/resource.c (ffffffff810bf09b)
Location: include/linux/rwlock_api_smp.h:216
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
In kernel/sched/core.c (ffffffff810f6c7c)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
```
```
In kernel/trace/trace_uprobe.c (ffffffff81227ffe)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
```
```
In mm/mempolicy.c (ffffffff8132b04e)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:shared_policy_replace
```
```
In mm/zsmalloc.c (ffffffff813656c1)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/exec.c (ffffffff8137a2bc)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/exec.c:unregister_binfmt
  - fs/exec.c:__register_binfmt
```
```
In fs/filesystems.c (ffffffff81399ca2)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/filesystems.c:register_filesystem
```
```
In fs/proc/generic.c (ffffffff8142b968)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_set_largest_free_order
  - fs/ext4/mballoc.c:mb_set_largest_free_order
```
```
In fs/ext4/super.c (ffffffff81496ef3)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_journal_params
```
```
In fs/jbd2/transaction.c (ffffffff814b62cb)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
```
```
In fs/jbd2/journal.c (ffffffff814bb8e1)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_instantiate
  - security/keys/keyring.c:key_free_user_ns
```
```
In security/integrity/iint.c (ffffffff81597c3e)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_free
  - security/integrity/iint.c:integrity_inode_get
```
```
In net/core/neighbour.c (ffffffff81aae0da)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:unregister_qdisc
  - net/sched/sch_api.c:register_qdisc
```
```
In net/sched/cls_api.c (ffffffff81b15ca5)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/sched/cls_api.c:register_tcf_proto_ops
```
```
In net/sched/act_api.c (ffffffff81b1d1d4)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_unregister_action
  - net/sched/act_api.c:tcf_register_action
  - net/sched/act_api.c:tcf_register_action
```
```
In net/sched/ematch.c (ffffffff81b2094e)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_unregister
  - net/sched/ematch.c:tcf_em_register
```
```
In net/ipv6/addrconf.c (ffffffff81bfea0e)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81c0695f)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_probe
```
```
In net/packet/af_packet.c (ffffffff81c4fd76)
Location: include/linux/rwlock_api_smp.h:216
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
In kernel/locking/spinlock.c (ffffffff81f29c55)
Location: include/linux/rwlock_api_smp.h:222
Inline: True
Inline callers:
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
In kernel/locking/spinlock.c (ffffffff820d5b35)
Location: include/linux/rwlock_api_smp.h:222
Inline: True
Inline callers:
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
In kernel/locking/spinlock.c (ffffffff82158f15)
Location: include/linux/rwlock_api_smp.h:222
Inline: True
Inline callers:
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
In kernel/locking/spinlock.c (ffffffff8223c795)
Location: include/linux/rwlock_api_smp.h:222
Inline: True
Inline callers:
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
In kernel/resource.c (ffff800010100b60)
Location: include/linux/rwlock_api_smp.h:216
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
In kernel/trace/trace_uprobe.c (ffff800010259518)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
```
```
In mm/mempolicy.c (ffff80001033be84)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
```
```
In mm/zsmalloc.c (ffff800010375d8c)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/exec.c (ffff80001038c488)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/exec.c:unregister_binfmt
  - fs/exec.c:__register_binfmt
```
```
In fs/filesystems.c (ffff8000103b2f48)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/filesystems.c:unregister_filesystem
  - fs/filesystems.c:unregister_filesystem
  - fs/filesystems.c:register_filesystem
```
```
In fs/proc/generic.c (ffff8000104445b8)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_journal_params
```
```
In fs/jbd2/transaction.c (ffff8000104cc404)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
```
```
In fs/jbd2/journal.c (ffff8000104d544c)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_instantiate
  - security/keys/keyring.c:key_free_user_ns
```
```
In security/integrity/iint.c (ffff8000105ac90c)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_free
  - security/integrity/iint.c:integrity_inode_get
```
```
In net/core/neighbour.c (ffff800010be4370)
Location: include/linux/rwlock_api_smp.h:216
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
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/sched/sch_api.c (ffff800010c3e244)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:unregister_qdisc
  - net/sched/sch_api.c:register_qdisc
```
```
In net/sched/cls_api.c (ffff800010c415e8)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/sched/cls_api.c:register_tcf_proto_ops
```
```
In net/sched/act_api.c (ffff800010c46f04)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_unregister_action
```
```
In net/sched/ematch.c (ffff800010c49f70)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_unregister
  - net/sched/ematch.c:tcf_em_register
```
```
In net/ipv6/addrconf.c (ffff800010d073f8)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffff800010d12f44)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
```
```
In net/ipv6/mcast.c (ffff800010d32d0c)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c035cd60)
Location: include/linux/rwlock_api_smp.h:216
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
In kernel/trace/trace_uprobe.c (c048b67c)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
```
```
In mm/zsmalloc.c (c0561d88)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/exec.c (c0573588)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/exec.c:unregister_binfmt
  - fs/exec.c:__register_binfmt
```
```
In fs/filesystems.c (c0591df4)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/filesystems.c:register_filesystem
```
```
In fs/proc/generic.c (c0609630)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_journal_params
```
```
In fs/jbd2/transaction.c (c068fd0c)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
```
```
In fs/jbd2/journal.c (c069537c)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_instantiate
  - security/keys/keyring.c:key_free_user_ns
```
```
In security/integrity/iint.c (c075c2b4)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_free
  - security/integrity/iint.c:integrity_inode_get
```
```
In net/core/neighbour.c (c0cff114)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:unregister_qdisc
  - net/sched/sch_api.c:register_qdisc
```
```
In net/sched/cls_api.c (c0d51818)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/sched/cls_api.c:register_tcf_proto_ops
```
```
In net/sched/act_api.c (c0d579e0)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_unregister_action
```
```
In net/sched/ematch.c (c0d5a818)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_unregister
  - net/sched/ematch.c:tcf_em_register
```
```
In net/ipv6/addrconf.c (c0e0de88)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (c0e16b10)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
```
```
In net/ipv6/mcast.c (c0e35abc)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/lpar.c:vcpudispatch_stats_write
  - arch/powerpc/platforms/pseries/lpar.c:vcpudispatch_stats_write
```
```
In kernel/resource.c (c0000000001495e0)
Location: include/linux/rwlock_api_smp.h:216
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
In kernel/trace/trace_uprobe.c (c0000000002fba50)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
```
```
In mm/mempolicy.c (c000000000416da8)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
```
```
In mm/zsmalloc.c (c000000000468458)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/exec.c (c000000000482f74)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/exec.c:unregister_binfmt
  - fs/exec.c:__register_binfmt
```
```
In fs/filesystems.c (c0000000004aeb38)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/filesystems.c:register_filesystem
```
```
In fs/proc/generic.c (c000000000559d80)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_journal_params
```
```
In fs/jbd2/transaction.c (c000000000605968)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
```
```
In fs/jbd2/journal.c (c00000000060c888)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_instantiate
  - security/keys/keyring.c:key_free_user_ns
```
```
In security/integrity/iint.c (c00000000072ae10)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_free
  - security/integrity/iint.c:integrity_inode_get
```
```
In net/core/neighbour.c (c000000000cc83b0)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:unregister_qdisc
  - net/sched/sch_api.c:register_qdisc
```
```
In net/sched/cls_api.c (c000000000d3a518)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/sched/cls_api.c:register_tcf_proto_ops
```
```
In net/sched/act_api.c (c000000000d432d4)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_unregister_action
```
```
In net/sched/ematch.c (c000000000d474f4)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_unregister
  - net/sched/ematch.c:tcf_em_register
```
```
In net/ipv6/addrconf.c (c000000000e31800)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (c000000000e3cb7c)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
```
```
In net/ipv6/mcast.c (c000000000e651e0)
Location: include/linux/rwlock_api_smp.h:216
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
In kernel/resource.c (ffffffe0000c835e)
Location: include/linux/rwlock_api_smp.h:216
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
In mm/zsmalloc.c (ffffffe00024e508)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/exec.c (ffffffe00025ceb4)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/exec.c:unregister_binfmt
  - fs/exec.c:__register_binfmt
```
```
In fs/filesystems.c (ffffffe000276b24)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/filesystems.c:register_filesystem
```
```
In fs/proc/generic.c (ffffffe0002d9f16)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_journal_params
```
```
In fs/jbd2/transaction.c (ffffffe000344f9a)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
```
```
In fs/jbd2/journal.c (ffffffe000349d04)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_instantiate
  - security/keys/keyring.c:key_free_user_ns
```
```
In security/integrity/iint.c (ffffffe0003f50d2)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_free
  - security/integrity/iint.c:integrity_inode_get
```
```
In net/core/neighbour.c (ffffffe00076b46e)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:unregister_qdisc
  - net/sched/sch_api.c:register_qdisc
```
```
In net/sched/cls_api.c (ffffffe0007af724)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/sched/cls_api.c:register_tcf_proto_ops
```
```
In net/sched/act_api.c (ffffffe0007b4cfe)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_unregister_action
```
```
In net/sched/ematch.c (ffffffe0007b7110)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_unregister
  - net/sched/ematch.c:tcf_em_register
```
```
In net/ipv6/addrconf.c (ffffffe00084f892)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffe00085714a)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
```
```
In net/ipv6/mcast.c (ffffffe0008711d6)
Location: include/linux/rwlock_api_smp.h:216
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a369a)
Location: include/linux/rwlock_api_smp.h:216
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
In kernel/trace/trace_uprobe.c (ffffffff811d0a88)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
```
```
In mm/mempolicy.c (ffffffff812953de)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
```
```
In mm/zsmalloc.c (ffffffff812c8f4c)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/exec.c (ffffffff812dc5bc)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/exec.c:unregister_binfmt
```
```
In fs/filesystems.c (ffffffff812f91b8)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/filesystems.c:register_filesystem
```
```
In fs/proc/generic.c (ffffffff81370a29)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_journal_params
```
```
In fs/jbd2/transaction.c (ffffffff813ea4f7)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
```
```
In fs/jbd2/journal.c (ffffffff813ef181)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_instantiate
  - security/keys/keyring.c:key_free_user_ns
```
```
In security/integrity/iint.c (ffffffff814acebe)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_free
  - security/integrity/iint.c:integrity_inode_get
```
```
In net/core/neighbour.c (ffffffff818e4d78)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:unregister_qdisc
  - net/sched/sch_api.c:register_qdisc
```
```
In net/sched/cls_api.c (ffffffff81933615)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/sched/cls_api.c:register_tcf_proto_ops
```
```
In net/sched/act_api.c (ffffffff81939a74)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_unregister_action
```
```
In net/sched/ematch.c (ffffffff8193c60e)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_unregister
  - net/sched/ematch.c:tcf_em_register
```
```
In net/ipv6/addrconf.c (ffffffff819e4523)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff819ebc6d)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81a0ab86)
Location: include/linux/rwlock_api_smp.h:216
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
In kernel/resource.c (ffffffff8109207a)
Location: include/linux/rwlock_api_smp.h:216
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
In kernel/trace/trace_uprobe.c (ffffffff811c3858)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
```
```
In mm/mempolicy.c (ffffffff81286fee)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
```
```
In mm/zsmalloc.c (ffffffff812b9f8c)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/exec.c (ffffffff812cd23c)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/exec.c:unregister_binfmt
```
```
In fs/filesystems.c (ffffffff812e9dd8)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/filesystems.c:register_filesystem
```
```
In fs/proc/generic.c (ffffffff813614b9)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_journal_params
```
```
In fs/jbd2/transaction.c (ffffffff813daf77)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
```
```
In fs/jbd2/journal.c (ffffffff813dfc01)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_instantiate
  - security/keys/keyring.c:key_free_user_ns
```
```
In security/integrity/iint.c (ffffffff8149d8de)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_free
  - security/integrity/iint.c:integrity_inode_get
```
```
In net/core/neighbour.c (ffffffff8189ebb8)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:unregister_qdisc
  - net/sched/sch_api.c:register_qdisc
```
```
In net/sched/cls_api.c (ffffffff818ed115)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/sched/cls_api.c:register_tcf_proto_ops
```
```
In net/sched/act_api.c (ffffffff818f3574)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_unregister_action
```
```
In net/sched/ematch.c (ffffffff818f610e)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_unregister
  - net/sched/ematch.c:tcf_em_register
```
```
In net/ipv6/addrconf.c (ffffffff819a12e3)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff819a8a2d)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff819c7946)
Location: include/linux/rwlock_api_smp.h:216
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
In kernel/resource.c (ffffffff810a364a)
Location: include/linux/rwlock_api_smp.h:216
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
In kernel/trace/trace_uprobe.c (ffffffff811ce858)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
```
```
In mm/mempolicy.c (ffffffff812931ee)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
```
```
In mm/zsmalloc.c (ffffffff812c6d5c)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/exec.c (ffffffff812da3cc)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/exec.c:unregister_binfmt
```
```
In fs/filesystems.c (ffffffff812f6fb6)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/filesystems.c:register_filesystem
```
```
In fs/proc/generic.c (ffffffff8136e4f9)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_journal_params
```
```
In fs/jbd2/transaction.c (ffffffff813e7877)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
```
```
In fs/jbd2/journal.c (ffffffff813ec501)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_instantiate
  - security/keys/keyring.c:key_free_user_ns
```
```
In security/integrity/iint.c (ffffffff814a8f5e)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_free
  - security/integrity/iint.c:integrity_inode_get
```
```
In net/core/neighbour.c (ffffffff81935da8)
Location: include/linux/rwlock_api_smp.h:216
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
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:unregister_qdisc
  - net/sched/sch_api.c:register_qdisc
```
```
In net/sched/cls_api.c (ffffffff819847a5)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/sched/cls_api.c:register_tcf_proto_ops
```
```
In net/sched/act_api.c (ffffffff8198ac04)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_unregister_action
```
```
In net/sched/ematch.c (ffffffff8198d79e)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_unregister
  - net/sched/ematch.c:tcf_em_register
```
```
In net/ipv6/addrconf.c (ffffffff81a4efa3)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81a566ed)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81a75606)
Location: include/linux/rwlock_api_smp.h:216
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
In kernel/locking/spinlock.c (ffffffff81aec615)
Location: include/linux/rwlock_api_smp.h:216
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_unlock
```
</details>
</li>
</ul>

## Differences

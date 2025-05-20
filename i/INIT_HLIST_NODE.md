# Function: <code>INIT_HLIST_NODE</code>

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
In arch/x86/kernel/kvm.c (ffffffff81063ba4)
Location: include/linux/list.h:598
Inline: True
```
```
In kernel/fork.c (ffffffff81080130)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - kernel/fork.c:fork_idle
```
```
In kernel/user.c (ffffffff8108c7de)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff8109a042)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:init_worker_pool
```
```
In kernel/acct.c (ffffffff8110bf83)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - kernel/acct.c:SyS_acct
  - kernel/acct.c:SyS_acct
```
```
In kernel/cgroup.c (ffffffff81114c14)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - kernel/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (ffffffff8112c9f6)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:recycle_rp_inst
  - kernel/kprobes.c:pre_handler_kretprobe
```
```
In kernel/events/core.c (ffffffff8117e8d1)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/ksm.c (ffffffff811e51a0)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:__ksm_exit
```
```
In mm/huge_memory.c (ffffffff811f431d)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - mm/huge_memory.c:collect_mm_slot
  - mm/huge_memory.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff8120e98a)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
  - fs/super.c:sget_userns
```
```
In fs/dcache.c (ffffffff812236e8)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:d_delete
  - fs/dcache.c:__d_alloc
```
```
In fs/inode.c (ffffffff81226709)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
  - fs/inode.c:inode_init_once
```
```
In fs/namespace.c (ffffffff8122bf43)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - fs/namespace.c:unhash_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/namespace.c:attach_recursive_mnt
```
```
In fs/fs_pin.c (ffffffff81241f42)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/locks.c (ffffffff8125f0f2)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - fs/locks.c:locks_delete_block
  - fs/locks.c:posix_unblock_lock
  - fs/locks.c:locks_alloc_lock
  - fs/locks.c:locks_init_lock
  - fs/locks.c:locks_wake_up_blocks
  - fs/locks.c:locks_unlink_lock_ctx
```
```
In fs/quota/dquot.c (ffffffff812714a8)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/fat/inode.c (ffffffff812fb4fc)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:init_once
  - fs/fat/inode.c:init_once
```
```
In security/selinux/avc.c (ffffffff8134048f)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
```
```
In block/elevator.c (ffffffff813b3905)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-core.c (ffffffff813b53a7)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-ioc.c (ffffffff813beca9)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/blk-mq.c (ffffffff813c2e50)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_alloc_request
```
```
In block/bsg.c (ffffffff813d6765)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In drivers/clk/clk.c (ffffffff816e71a3)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
```
```
In net/sched/sch_api.c (ffffffff81742697)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_insert
```
```
In net/sched/act_api.c (ffffffff817475df)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_hash_create
```
```
In net/ipv4/devinet.c (ffffffff81791ae9)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b1675)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff817b817f)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/addrconf.c (ffffffff817ca6b0)
Location: include/linux/list.h:598
Inline: True
```
```
In net/ipv6/addrlabel.c (ffffffff817d2931)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In arch/x86/kernel/kvm.c (ffffffff810637c4)
Location: include/linux/list.h:598
Inline: True
```
```
In kernel/fork.c (ffffffff81081ee9)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - kernel/fork.c:fork_idle
```
```
In kernel/user.c (ffffffff8108f84e)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff8109e23d)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/acct.c (ffffffff811137e4)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - kernel/acct.c:SyS_acct
  - kernel/acct.c:SyS_acct
```
```
In kernel/cgroup.c (ffffffff81fab423)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_init
  - kernel/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (ffffffff8113531b)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/events/core.c (ffffffff8119037c)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/ksm.c (ffffffff81203d34)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812196fd)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff8123617e)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - fs/super.c:sget_userns
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (ffffffff8124bbd3)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:__d_alloc
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff8124edc9)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
  - fs/inode.c:inode_init_once
```
```
In fs/namespace.c (ffffffff8125668c)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:unhash_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/fs_pin.c (ffffffff8126a292)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/locks.c (ffffffff8128abb8)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - fs/locks.c:posix_unblock_lock
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_wake_up_blocks
  - fs/locks.c:locks_delete_block
  - fs/locks.c:locks_init_lock
  - fs/locks.c:locks_alloc_lock
```
```
In fs/quota/dquot.c (ffffffff8129fe2e)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/fat/inode.c (ffffffff813305e0)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - fs/fat/inode.c:init_once
  - fs/fat/inode.c:init_once
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In security/selinux/avc.c (ffffffff81375b3f)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
```
```
In block/elevator.c (ffffffff813f7865)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-core.c (ffffffff813fa227)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-ioc.c (ffffffff814031dc)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-mq.c (ffffffff81406a68)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_alloc_request
```
```
In block/bsg.c (ffffffff8141c195)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In drivers/clk/clk.c (ffffffff8174b7a3)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
```
```
In net/sched/sch_api.c (ffffffff817af547)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_insert
```
```
In net/sched/act_api.c (ffffffff817b4973)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_hash_create
```
```
In net/ipv4/devinet.c (ffffffff817fff9f)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/xfrm/xfrm_policy.c (ffffffff8181e5b5)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff81825491)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/addrconf.c (ffffffff818378bf)
Location: include/linux/list.h:598
Inline: True
```
```
In net/ipv6/addrlabel.c (ffffffff81840321)
Location: include/linux/list.h:598
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In arch/x86/kernel/kvm.c (ffffffff81066c74)
Location: include/linux/list.h:614
Inline: True
```
```
In kernel/fork.c (ffffffff81086949)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - kernel/fork.c:fork_idle
```
```
In kernel/user.c (ffffffff810947ce)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff810a2d9d)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff810ad62e)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/acct.c (ffffffff8111aef4)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - kernel/acct.c:SyS_acct
  - kernel/acct.c:SyS_acct
```
```
In kernel/cgroup.c (ffffffff81fe7699)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_init
  - kernel/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (ffffffff8113f09b)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/events/core.c (ffffffff8119f23c)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/ksm.c (ffffffff81215d54)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff8122bc7d)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff81248e2a)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - fs/super.c:sget_userns
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (ffffffff8125ebb3)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:__d_alloc
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff81261dd9)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
  - fs/inode.c:inode_init_once
```
```
In fs/namespace.c (ffffffff8126a207)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/fs_pin.c (ffffffff8127d242)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/locks.c (ffffffff8129f948)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - fs/locks.c:posix_unblock_lock
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_wake_up_blocks
  - fs/locks.c:locks_delete_block
  - fs/locks.c:locks_init_lock
  - fs/locks.c:locks_alloc_lock
```
```
In fs/quota/dquot.c (ffffffff812b531c)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/fat/inode.c (ffffffff81346340)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - fs/fat/inode.c:init_once
  - fs/fat/inode.c:init_once
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In security/selinux/avc.c (ffffffff8138c46f)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
```
```
In block/elevator.c (ffffffff814113f2)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-core.c (ffffffff81413ba7)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-ioc.c (ffffffff8141cf0c)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-mq.c (ffffffff81420e5b)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_alloc_request
```
```
In block/bsg.c (ffffffff814372d7)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In drivers/clk/clk.c (ffffffff81534013)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
```
```
In net/sched/sch_api.c (ffffffff817dec37)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_insert
```
```
In net/sched/act_api.c (ffffffff817e4233)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_hash_create
```
```
In net/ipv4/devinet.c (ffffffff81830eff)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/xfrm/xfrm_policy.c (ffffffff8184fd45)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff81856df1)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/addrconf.c (ffffffff818693b2)
Location: include/linux/list.h:614
Inline: True
```
```
In net/ipv6/addrlabel.c (ffffffff81871fa1)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In arch/x86/kernel/kvm.c (ffffffff81065f51)
Location: include/linux/list.h:627
Inline: True
```
```
In kernel/fork.c (ffffffff8108368e)
Location: include/linux/list.h:627
Inline: True
Inline callers:
  - kernel/fork.c:fork_idle
```
```
In kernel/user.c (ffffffff810918bf)
Location: include/linux/list.h:627
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff810a00d0)
Location: include/linux/list.h:627
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff810aa207)
Location: include/linux/list.h:627
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/acct.c (ffffffff8111cb14)
Location: include/linux/list.h:627
Inline: True
Inline callers:
  - kernel/acct.c:SyS_acct
  - kernel/acct.c:SyS_acct
```
```
In kernel/cgroup/cgroup.c (ffffffff820c7c24)
Location: include/linux/list.h:627
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (ffffffff81142cd1)
Location: include/linux/list.h:627
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/events/core.c (ffffffff811a5cae)
Location: include/linux/list.h:627
Inline: True
```
```
In mm/ksm.c (ffffffff8122144e)
Location: include/linux/list.h:627
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812377ad)
Location: include/linux/list.h:627
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff81254734)
Location: include/linux/list.h:627
Inline: True
Inline callers:
  - fs/super.c:sget_userns
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (ffffffff8126c583)
Location: include/linux/list.h:627
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:__d_alloc
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff8126f699)
Location: include/linux/list.h:627
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
  - fs/inode.c:inode_init_once
```
```
In fs/namespace.c (ffffffff81277a20)
Location: include/linux/list.h:627
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/fs_pin.c (ffffffff8128add2)
Location: include/linux/list.h:627
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/locks.c (ffffffff812ae7b8)
Location: include/linux/list.h:627
Inline: True
Inline callers:
  - fs/locks.c:posix_unblock_lock
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_wake_up_blocks
  - fs/locks.c:locks_delete_block
  - fs/locks.c:locks_init_lock
  - fs/locks.c:locks_alloc_lock
```
```
In fs/quota/dquot.c (ffffffff812c1b06)
Location: include/linux/list.h:627
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/fat/inode.c (ffffffff8135ad5e)
Location: include/linux/list.h:627
Inline: True
Inline callers:
  - fs/fat/inode.c:init_once
  - fs/fat/inode.c:init_once
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In security/selinux/avc.c (ffffffff813a226f)
Location: include/linux/list.h:627
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
```
```
In block/elevator.c (ffffffff8141eeed)
Location: include/linux/list.h:627
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-core.c (ffffffff814216bd)
Location: include/linux/list.h:627
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-ioc.c (ffffffff8142af6c)
Location: include/linux/list.h:627
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-mq.c (ffffffff8142f25e)
Location: include/linux/list.h:627
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/bsg.c (ffffffff81444665)
Location: include/linux/list.h:627
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In drivers/clk/clk.c (ffffffff81547173)
Location: include/linux/list.h:627
Inline: True
```
```
In drivers/dax/super.c (ffffffff8163cc7e)
Location: include/linux/list.h:627
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/sched/sch_api.c (ffffffff817fe267)
Location: include/linux/list.h:627
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_insert
```
```
In net/sched/act_api.c (ffffffff81803c70)
Location: include/linux/list.h:627
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_hash_create
```
```
In net/ipv4/devinet.c (ffffffff818521a1)
Location: include/linux/list.h:627
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/xfrm/xfrm_policy.c (ffffffff81873b05)
Location: include/linux/list.h:627
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff8187ab01)
Location: include/linux/list.h:627
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/addrconf.c (ffffffff81890126)
Location: include/linux/list.h:627
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81896d01)
Location: include/linux/list.h:627
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In arch/x86/kernel/apic/vector.c (ffffffff8105b240)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff81069e51)
Location: include/linux/list.h:628
Inline: True
```
```
In kernel/fork.c (ffffffff81089f6e)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - kernel/fork.c:fork_idle
```
```
In kernel/user.c (ffffffff8109874f)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff810a6dee)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff810b0a67)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/acct.c (ffffffff81128234)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - kernel/acct.c:SyS_acct
  - kernel/acct.c:SyS_acct
```
```
In kernel/cgroup/cgroup.c (ffffffff826d02a2)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (ffffffff8114f981)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/events/core.c (ffffffff811b989e)
Location: include/linux/list.h:628
Inline: True
```
```
In mm/ksm.c (ffffffff8123c75e)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff81256b3d)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff812768cf)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - fs/super.c:sget_userns
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (ffffffff8128e713)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:__d_alloc
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff81291fb9)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
  - fs/inode.c:inode_init_once
```
```
In fs/namespace.c (ffffffff8129a460)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/fs_pin.c (ffffffff812ad912)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/locks.c (ffffffff812d21a8)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - fs/locks.c:posix_unblock_lock
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_wake_up_blocks
  - fs/locks.c:locks_delete_block
  - fs/locks.c:locks_init_lock
  - fs/locks.c:locks_alloc_lock
```
```
In fs/quota/dquot.c (ffffffff812e592b)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/fat/inode.c (ffffffff8137fa5e)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - fs/fat/inode.c:init_once
  - fs/fat/inode.c:init_once
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In security/selinux/avc.c (ffffffff813c806f)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
```
```
In block/elevator.c (ffffffff814499c9)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-core.c (ffffffff8144c20d)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-ioc.c (ffffffff8145615c)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-mq.c (ffffffff8145a7b3)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/bsg.c (ffffffff81471595)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In drivers/clk/clk.c (ffffffff815aae93)
Location: include/linux/list.h:628
Inline: True
```
```
In drivers/dax/super.c (ffffffff816a594e)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/sched/sch_api.c (ffffffff8187be77)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_insert
```
```
In net/ipv4/devinet.c (ffffffff818d1fa7)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f44bd)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff818fb5f1)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/addrconf.c (ffffffff819116ad)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff8191823d)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In arch/x86/kernel/apic/vector.c (ffffffff8105e180)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff8106cad1)
Location: include/linux/list.h:628
Inline: True
```
```
In kernel/fork.c (ffffffff8108d77d)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - kernel/fork.c:fork_idle
```
```
In kernel/user.c (ffffffff8109be91)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff810accb4)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff810b7877)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/acct.c (ffffffff8113602f)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/cgroup.c (ffffffff826fa9da)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (ffffffff8115e4ba)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/events/core.c (ffffffff811d8c6f)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/ksm.c (ffffffff8125fceb)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff8127ab0d)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff8129d241)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - fs/super.c:sget_userns
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (ffffffff812b499d)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:__d_alloc
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff812b9319)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
  - fs/inode.c:inode_init_once
```
```
In fs/namespace.c (ffffffff812c04bb)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/fs_pin.c (ffffffff812d56c2)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/locks.c (ffffffff812fe658)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - fs/locks.c:posix_unblock_lock
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_wake_up_blocks
  - fs/locks.c:locks_delete_block
  - fs/locks.c:locks_init_lock
  - fs/locks.c:locks_alloc_lock
```
```
In fs/quota/dquot.c (ffffffff81312fa9)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/fat/inode.c (ffffffff813adf44)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - fs/fat/inode.c:init_once
  - fs/fat/inode.c:init_once
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In security/selinux/avc.c (ffffffff813f76d2)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
```
```
In block/elevator.c (ffffffff8147c6ca)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-core.c (ffffffff8147f591)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-ioc.c (ffffffff814895b4)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-mq.c (ffffffff8148ecf9)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/bsg.c (ffffffff814a5553)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In drivers/clk/clk.c (ffffffff815e2e93)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
```
```
In drivers/dax/super.c (ffffffff816e1d1b)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/sched/sch_api.c (ffffffff818ce713)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_insert
```
```
In net/ipv4/devinet.c (ffffffff819284c1)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194aa96)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff81950ebe)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/addrconf.c (ffffffff81968acc)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff8196fa79)
Location: include/linux/list.h:628
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In arch/x86/kernel/apic/vector.c (ffffffff81063e10)
Location: include/linux/list.h:681
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff81072be1)
Location: include/linux/list.h:681
Inline: True
```
```
In kernel/fork.c (ffffffff81095a2d)
Location: include/linux/list.h:681
Inline: True
Inline callers:
  - kernel/fork.c:fork_idle
```
```
In kernel/user.c (ffffffff810a409c)
Location: include/linux/list.h:681
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff810b6534)
Location: include/linux/list.h:681
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff810c0977)
Location: include/linux/list.h:681
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/acct.c (ffffffff811417bf)
Location: include/linux/list.h:681
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/cgroup.c (ffffffff828b18d6)
Location: include/linux/list.h:681
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (ffffffff8116b032)
Location: include/linux/list.h:681
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/events/core.c (ffffffff811e916c)
Location: include/linux/list.h:681
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/ksm.c (ffffffff8127442b)
Location: include/linux/list.h:681
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff8128f11d)
Location: include/linux/list.h:681
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff812b21f3)
Location: include/linux/list.h:681
Inline: True
Inline callers:
  - fs/super.c:sget_userns
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (ffffffff812c9c1d)
Location: include/linux/list.h:681
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:__d_alloc
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff812ce509)
Location: include/linux/list.h:681
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
  - fs/inode.c:inode_init_once
```
```
In fs/namespace.c (ffffffff812d570b)
Location: include/linux/list.h:681
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/fs_pin.c (ffffffff812eaa92)
Location: include/linux/list.h:681
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/crypto/keyinfo.c (ffffffff81311060)
Location: include/linux/list.h:681
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:put_crypt_info
```
```
In fs/locks.c (ffffffff8131409a)
Location: include/linux/list.h:681
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
  - fs/locks.c:locks_init_lock
  - fs/locks.c:locks_alloc_lock
```
```
In fs/quota/dquot.c (ffffffff81329f39)
Location: include/linux/list.h:681
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/fat/inode.c (ffffffff813c7474)
Location: include/linux/list.h:681
Inline: True
Inline callers:
  - fs/fat/inode.c:init_once
  - fs/fat/inode.c:init_once
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In security/selinux/avc.c (ffffffff814130d2)
Location: include/linux/list.h:681
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
```
```
In block/elevator.c (ffffffff8149a6ba)
Location: include/linux/list.h:681
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-core.c (ffffffff8149cbe5)
Location: include/linux/list.h:681
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-ioc.c (ffffffff814a3402)
Location: include/linux/list.h:681
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-mq.c (ffffffff814a8750)
Location: include/linux/list.h:681
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/bsg.c (ffffffff814bff9f)
Location: include/linux/list.h:681
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In drivers/clk/clk.c (ffffffff815fc813)
Location: include/linux/list.h:681
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
```
```
In drivers/dax/super.c (ffffffff8170513b)
Location: include/linux/list.h:681
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/sched/sch_api.c (ffffffff818f9963)
Location: include/linux/list.h:681
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_insert
```
```
In net/ipv4/devinet.c (ffffffff81957913)
Location: include/linux/list.h:681
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197c3bd)
Location: include/linux/list.h:681
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff8198440e)
Location: include/linux/list.h:681
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/anycast.c (ffffffff81993fc4)
Location: include/linux/list.h:681
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff8199e3fb)
Location: include/linux/list.h:681
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff819a5699)
Location: include/linux/list.h:681
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In arch/x86/kernel/apic/vector.c (ffffffff810674d3)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff810764b1)
Location: include/linux/list.h:741
Inline: True
```
```
In kernel/fork.c (ffffffff81099d32)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/fork.c:fork_idle
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (ffffffff810a8d80)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff810bc343)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff810c6a7f)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/acct.c (ffffffff8114cb0d)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/cgroup.c (ffffffff828ca5e0)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (ffffffff811758fb)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/trace/trace_kprobe.c (ffffffff811c359a)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:__unregister_trace_kprobe
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
```
In kernel/events/core.c (ffffffff8120246f)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/ksm.c (ffffffff8129059b)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812a99e3)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff812cea44)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
  - fs/super.c:alloc_super
```
```
In fs/dcache.c (ffffffff812e662a)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:__d_alloc
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff812eb3e9)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
  - fs/inode.c:inode_init_once
```
```
In fs/namespace.c (ffffffff812f38a0)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/fs_pin.c (ffffffff81309505)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/crypto/keyinfo.c (ffffffff813383df)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:put_crypt_info
```
```
In fs/locks.c (ffffffff8133b98d)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
  - fs/locks.c:locks_init_lock
  - fs/locks.c:locks_alloc_lock
```
```
In fs/quota/dquot.c (ffffffff81351aa8)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/fat/inode.c (ffffffff813f1f54)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/fat/inode.c:init_once
  - fs/fat/inode.c:init_once
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In security/selinux/avc.c (ffffffff81440b72)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
```
```
In block/elevator.c (ffffffff814c8793)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-core.c (ffffffff814cad02)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-ioc.c (ffffffff814d14da)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-mq.c (ffffffff814d6138)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/bsg.c (0)
Location: include/linux/list.h:741
Inline: True
```
```
In drivers/clk/clk.c (ffffffff8162f473)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
```
```
In drivers/dax/super.c (ffffffff8173ef97)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/sched/sch_api.c (ffffffff81959153)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_insert
```
```
In net/ipv4/devinet.c (ffffffff819bc29c)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e56e9)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff819ee119)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/anycast.c (ffffffff819ffa94)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81a0a491)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81a11c04)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In arch/x86/kernel/apic/vector.c (ffffffff81067e13)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff810774c1)
Location: include/linux/list.h:741
Inline: True
```
```
In kernel/fork.c (ffffffff810a0312)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/fork.c:fork_idle
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (ffffffff810af350)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff810c2602)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff810cfb4f)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/acct.c (ffffffff811587dd)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/cgroup.c (ffffffff828d2ade)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (ffffffff8118176b)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/trace/trace_kprobe.c (ffffffff811cee2a)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:__unregister_trace_kprobe
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
```
In kernel/events/core.c (ffffffff8120f29f)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/ksm.c (ffffffff812a031b)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812baf53)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff812e04c4)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
  - fs/super.c:alloc_super
```
```
In fs/dcache.c (ffffffff812f818a)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:__d_alloc
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff812fcf29)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
  - fs/inode.c:inode_init_once
```
```
In fs/namespace.c (ffffffff81305465)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/fs_pin.c (ffffffff8131c575)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/crypto/keysetup_v1.c (ffffffff8134e56c)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff81353edd)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
  - fs/locks.c:locks_init_lock
  - fs/locks.c:locks_alloc_lock
```
```
In fs/quota/dquot.c (ffffffff81369e28)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/fat/inode.c (ffffffff8140be54)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/fat/inode.c:init_once
  - fs/fat/inode.c:init_once
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In security/selinux/avc.c (ffffffff8145a482)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
```
```
In block/elevator.c (ffffffff814e18b3)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-core.c (ffffffff814e3ee2)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-ioc.c (ffffffff814ea887)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-mq.c (ffffffff814ef48a)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/bsg.c (0)
Location: include/linux/list.h:741
Inline: True
```
```
In drivers/clk/clk.c (ffffffff81650fc7)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
```
```
In drivers/dax/super.c (ffffffff81763177)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/sched/sch_api.c (ffffffff8198f5f3)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_insert
```
```
In net/ipv4/devinet.c (ffffffff819f2f9b)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a1c719)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff81a24f89)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/anycast.c (ffffffff81a36674)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81a41141)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81a48824)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In arch/x86/kernel/apic/vector.c (ffffffff8106eefd)
Location: include/linux/list.h:765
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff8107f051)
Location: include/linux/list.h:765
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:apf_task_wake_all
```
```
In kernel/fork.c (ffffffff810a71f9)
Location: include/linux/list.h:765
Inline: True
Inline callers:
  - kernel/fork.c:fork_idle
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (ffffffff810b705e)
Location: include/linux/list.h:765
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff810c8ad2)
Location: include/linux/list.h:765
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff810d9a4f)
Location: include/linux/list.h:765
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/acct.c (ffffffff81168e4d)
Location: include/linux/list.h:765
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/cgroup.c (ffffffff82cf34a0)
Location: include/linux/list.h:765
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (ffffffff811951ab)
Location: include/linux/list.h:765
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/trace/trace_kprobe.c (ffffffff811eb231)
Location: include/linux/list.h:765
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:__unregister_trace_kprobe
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
```
In kernel/bpf/trampoline.c (0)
Location: include/linux/list.h:765
Inline: True
```
```
In kernel/events/core.c (ffffffff8123a47c)
Location: include/linux/list.h:765
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/watch_queue.c (ffffffff8124d34d)
Location: include/linux/list.h:765
Inline: True
Inline callers:
  - kernel/watch_queue.c:init_watch
  - kernel/watch_queue.c:init_watch
```
```
In mm/ksm.c (ffffffff812d6c32)
Location: include/linux/list.h:765
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
```
```
In mm/khugepaged.c (ffffffff812efe14)
Location: include/linux/list.h:765
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff81317184)
Location: include/linux/list.h:765
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
  - fs/super.c:alloc_super
```
```
In fs/dcache.c (ffffffff81330eea)
Location: include/linux/list.h:765
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:__d_alloc
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (0)
Location: include/linux/list.h:765
Inline: True
```
```
In fs/namespace.c (ffffffff813409ce)
Location: include/linux/list.h:765
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:alloc_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/fs_pin.c (ffffffff813562b5)
Location: include/linux/list.h:765
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/io_uring.c (ffffffff81382b09)
Location: include/linux/list.h:765
Inline: True
Inline callers:
  - fs/io_uring.c:io_poll_add
  - fs/io_uring.c:__io_poll_remove_one
  - fs/io_uring.c:io_arm_poll_handler
  - fs/io_uring.c:io_async_task_func
```
```
In fs/crypto/keysetup_v1.c (ffffffff813945dc)
Location: include/linux/list.h:765
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff8139dcde)
Location: include/linux/list.h:765
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
  - fs/locks.c:lease_alloc
```
```
In fs/quota/dquot.c (ffffffff813ae9c7)
Location: include/linux/list.h:765
Inline: True
Inline callers:
  - fs/quota/dquot.c:get_empty_dquot
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:invalidate_dquots
```
```
In fs/proc/inode.c (ffffffff813b95c1)
Location: include/linux/list.h:765
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_alloc_inode
```
```
In fs/fat/inode.c (ffffffff81459d94)
Location: include/linux/list.h:765
Inline: True
Inline callers:
  - fs/fat/inode.c:init_once
  - fs/fat/inode.c:init_once
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In security/selinux/avc.c (ffffffff814ad9f9)
Location: include/linux/list.h:765
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
```
```
In block/elevator.c (ffffffff815406c0)
Location: include/linux/list.h:765
Inline: True
Inline callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_del
```
```
In block/blk-core.c (0)
Location: include/linux/list.h:765
Inline: True
```
```
In block/blk-ioc.c (ffffffff81549827)
Location: include/linux/list.h:765
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-mq.c (ffffffff8154e42d)
Location: include/linux/list.h:765
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_rq_ctx_init
```
```
In block/bsg.c (0)
Location: include/linux/list.h:765
Inline: True
```
```
In drivers/clk/clk.c (ffffffff81700787)
Location: include/linux/list.h:765
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dax/super.c (ffffffff81822fd4)
Location: include/linux/list.h:765
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/core/dev.c (ffffffff81a0db78)
Location: include/linux/list.h:765
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_name_node_alt_create
```
```
In net/sched/sch_api.c (ffffffff81a674c3)
Location: include/linux/list.h:765
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_insert
```
```
In net/ipv4/devinet.c (ffffffff81ae196a)
Location: include/linux/list.h:765
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:rtm_to_ifaddr
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0dad9)
Location: include/linux/list.h:765
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff81b16bb9)
Location: include/linux/list.h:765
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/anycast.c (ffffffff81b2b75b)
Location: include/linux/list.h:765
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81b36c0f)
Location: include/linux/list.h:765
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81b3ee57)
Location: include/linux/list.h:765
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In arch/x86/kernel/apic/vector.c (ffffffff810704a4)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff8107ec81)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:apf_task_wake_all
```
```
In kernel/fork.c (ffffffff810a2ec2)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - kernel/fork.c:fork_idle
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (ffffffff810b221e)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff810c3c32)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff810d4bff)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/acct.c (ffffffff811654dd)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/cgroup.c (ffffffff82fdff7a)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (ffffffff81192dc9)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In kernel/trace/trace_kprobe.c (ffffffff811e9381)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:__unregister_trace_kprobe
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
```
In kernel/bpf/trampoline.c (0)
Location: include/linux/list.h:792
Inline: True
```
```
In kernel/events/core.c (ffffffff81243895)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/watch_queue.c (ffffffff812577ad)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - kernel/watch_queue.c:init_watch
  - kernel/watch_queue.c:init_watch
```
```
In mm/ksm.c (ffffffff812e27bb)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
```
```
In mm/khugepaged.c (ffffffff812fb5d3)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff81322694)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
  - fs/super.c:alloc_super
```
```
In fs/dcache.c (ffffffff8133c87a)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:__d_alloc
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (0)
Location: include/linux/list.h:792
Inline: True
```
```
In fs/namespace.c (ffffffff8134ca5e)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:alloc_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/fs_pin.c (ffffffff81362bf5)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/io_uring.c (ffffffff8138cce8)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - fs/io_uring.c:__io_poll_remove_one
  - fs/io_uring.c:__io_arm_poll_handler
  - fs/io_uring.c:io_async_task_func
  - fs/io_uring.c:io_poll_task_func
```
```
In fs/crypto/keysetup_v1.c (ffffffff813a5aac)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff813af68e)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
  - fs/locks.c:lease_alloc
```
```
In fs/quota/dquot.c (ffffffff813bffb7)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - fs/quota/dquot.c:get_empty_dquot
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:invalidate_dquots
```
```
In fs/proc/inode.c (ffffffff813cafd1)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_alloc_inode
```
```
In fs/fat/inode.c (ffffffff814760e4)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - fs/fat/inode.c:init_once
  - fs/fat/inode.c:init_once
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In security/selinux/avc.c (ffffffff814cb479)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
```
```
In block/elevator.c (ffffffff8155ce60)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_del
```
```
In block/blk-core.c (0)
Location: include/linux/list.h:792
Inline: True
```
```
In block/blk-ioc.c (ffffffff81565657)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-mq.c (ffffffff8156a840)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_rq_ctx_init
```
```
In block/bsg.c (0)
Location: include/linux/list.h:792
Inline: True
```
```
In drivers/clk/clk.c (ffffffff8171dca7)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dax/super.c (ffffffff81831d14)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/core/dev.c (ffffffff81a0e958)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:netdev_name_node_alt_create
```
```
In net/sched/sch_api.c (ffffffff81a6fbe3)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_insert
```
```
In net/ipv4/devinet.c (ffffffff81aee80a)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:rtm_to_ifaddr
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1bce9)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff81b24d99)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/anycast.c (ffffffff81b3a17b)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81b4593f)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81b4d867)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In arch/x86/kernel/apic/vector.c (ffffffff81070d54)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff8107f911)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:apf_task_wake_all
```
```
In kernel/fork.c (ffffffff831e3c29)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - kernel/fork.c:fork_idle
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (ffffffff810b385e)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff810c5452)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff810d6bbf)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/acct.c (ffffffff811662ad)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/cgroup.c (ffffffff831eab6c)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (ffffffff81193e24)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In kernel/trace/trace_kprobe.c (ffffffff811ea1f1)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:__unregister_trace_kprobe
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
```
In kernel/bpf/trampoline.c (ffffffff81227ace)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog
  - kernel/bpf/trampoline.c:bpf_trampoline_link_prog
```
```
In kernel/events/core.c (ffffffff81248842)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/watch_queue.c (ffffffff8125bc0d)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - kernel/watch_queue.c:init_watch
  - kernel/watch_queue.c:init_watch
```
```
In mm/ksm.c (ffffffff812e9f48)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
```
```
In mm/khugepaged.c (ffffffff813023a3)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff8132860c)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
  - fs/super.c:alloc_super
```
```
In fs/dcache.c (ffffffff81342cfb)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:__d_alloc
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (0)
Location: include/linux/list.h:792
Inline: True
```
```
In fs/namespace.c (ffffffff8135362c)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:alloc_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/fs_pin.c (ffffffff81369695)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8137e838)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8137f59f)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/io_uring.c (ffffffff8139756b)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - fs/io_uring.c:io_poll_remove_waitqs
  - fs/io_uring.c:__io_arm_poll_handler
  - fs/io_uring.c:io_async_task_func
  - fs/io_uring.c:io_poll_task_func
```
```
In fs/crypto/keysetup_v1.c (ffffffff813acb0c)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff813b694e)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
  - fs/locks.c:lease_alloc
```
```
In fs/quota/dquot.c (ffffffff813c9285)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:invalidate_dquots
```
```
In fs/proc/inode.c (ffffffff813d2011)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_alloc_inode
```
```
In fs/fat/inode.c (ffffffff8147bb54)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - fs/fat/inode.c:init_once
  - fs/fat/inode.c:init_once
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In security/selinux/avc.c (ffffffff814d1aa9)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
```
```
In block/elevator.c (ffffffff815656f0)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_del
```
```
In block/blk-core.c (0)
Location: include/linux/list.h:792
Inline: True
```
```
In block/blk-ioc.c (ffffffff8156dcc7)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-mq.c (ffffffff8157277a)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_rq_ctx_init
```
```
In block/bsg.c (0)
Location: include/linux/list.h:792
Inline: True
```
```
In drivers/clk/clk.c (ffffffff816fed37)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dax/super.c (ffffffff81814f44)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/core/dev.c (ffffffff819f5728)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:netdev_name_node_alt_create
```
```
In net/sched/sch_api.c (ffffffff81a584d3)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_insert
```
```
In net/ipv4/devinet.c (ffffffff81ad9f05)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:rtm_to_ifaddr
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b099dc)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff81b129b9)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/anycast.c (ffffffff81b27e67)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81b33681)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81b3bc34)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In arch/x86/kernel/apic/vector.c (ffffffff8107c9f3)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff8108e6f1)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:apf_task_wake_all
```
```
In kernel/fork.c (ffffffff832c77db)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - kernel/fork.c:fork_idle
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (ffffffff810c59fe)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff810d8042)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff810e9ec3)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/acct.c (ffffffff8118ba6d)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/cgroup.c (ffffffff832cf4a1)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (ffffffff811bccd3)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In kernel/trace/trace_kprobe.c (ffffffff8121b031)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:__unregister_trace_kprobe
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
```
In kernel/bpf/trampoline.c (ffffffff8125fd32)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog
  - kernel/bpf/trampoline.c:bpf_trampoline_link_prog
```
```
In kernel/events/core.c (ffffffff81283646)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/watch_queue.c (ffffffff81297abd)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - kernel/watch_queue.c:init_watch
  - kernel/watch_queue.c:init_watch
```
```
In mm/ksm.c (ffffffff81331e6b)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
```
```
In mm/khugepaged.c (ffffffff8134c113)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff81375bdc)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
  - fs/super.c:alloc_super
```
```
In fs/dcache.c (ffffffff8139073b)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:__d_alloc
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (0)
Location: include/linux/list.h:792
Inline: True
```
```
In fs/namespace.c (ffffffff813a1a7c)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:alloc_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/fs_pin.c (ffffffff813b8395)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/notify/fanotify/fanotify.c (ffffffff813cb918)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff813cc55e)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/io_uring.c (ffffffff813e45f1)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - fs/io_uring.c:__io_arm_poll_handler
  - fs/io_uring.c:io_async_task_func
  - fs/io_uring.c:io_poll_task_func
```
```
In fs/crypto/keysetup_v1.c (ffffffff813fc47c)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff8140664e)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
  - fs/locks.c:lease_alloc
```
```
In fs/quota/dquot.c (ffffffff81419aea)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:invalidate_dquots
```
```
In fs/proc/inode.c (ffffffff81423421)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_alloc_inode
```
```
In fs/fat/inode.c (ffffffff814d31e4)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - fs/fat/inode.c:init_once
  - fs/fat/inode.c:init_once
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In security/selinux/avc.c (ffffffff8152a829)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
```
```
In block/elevator.c (ffffffff815c9ae0)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_del
```
```
In block/blk-core.c (0)
Location: include/linux/list.h:792
Inline: True
```
```
In block/blk-ioc.c (ffffffff815d22b7)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-mq.c (ffffffff815d6daa)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_rq_ctx_init
```
```
In drivers/clk/clk.c (ffffffff81779537)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dax/super.c (ffffffff8189f6b4)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/core/dev.c (ffffffff81aa70f8)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:netdev_name_node_alt_create
```
```
In net/sched/sch_api.c (ffffffff81b114b3)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_insert
```
```
In net/ipv4/devinet.c (ffffffff81b99045)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:rtm_to_ifaddr
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bcc965)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff81bd6859)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/anycast.c (ffffffff81bedda7)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81bf9cf1)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81c024b4)
Location: include/linux/list.h:792
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8108bf23)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff8109f1e6)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:apf_task_wake_all
```
```
In kernel/fork.c (ffffffff8347a679)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - kernel/fork.c:fork_idle
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (ffffffff810dcfff)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff810ee912)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff81104b48)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/acct.c (ffffffff811bae23)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/cgroup.c (ffffffff834831e6)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (ffffffff811f1c6d)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In kernel/trace/trace_kprobe.c (ffffffff8125a261)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:__unregister_trace_kprobe
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
```
In kernel/bpf/trampoline.c (ffffffff812aa55c)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog
  - kernel/bpf/trampoline.c:bpf_trampoline_link_prog
```
```
In kernel/events/core.c (ffffffff812d6656)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/watch_queue.c (ffffffff812edd8d)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - kernel/watch_queue.c:init_watch
  - kernel/watch_queue.c:init_watch
```
```
In mm/ksm.c (ffffffff813a2fd9)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
```
```
In mm/khugepaged.c (ffffffff813c37bd)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff813f3f6c)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
  - fs/super.c:alloc_super
```
```
In fs/dcache.c (ffffffff814131fb)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:__d_alloc
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (0)
Location: include/linux/list.h:838
Inline: True
```
```
In fs/namespace.c (ffffffff81425487)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:alloc_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/fs_pin.c (ffffffff8143dc42)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8145404b)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81454d1d)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/crypto/keysetup_v1.c (ffffffff8146f929)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff8147b14e)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:__do_sys_flock
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In fs/quota/dquot.c (ffffffff8149055d)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:invalidate_dquots
```
```
In fs/proc/inode.c (ffffffff8149be68)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_alloc_inode
```
```
In fs/fat/inode.c (ffffffff815601ea)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - fs/fat/inode.c:init_once
  - fs/fat/inode.c:init_once
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In security/selinux/avc.c (ffffffff815c01f8)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
```
```
In block/elevator.c (ffffffff81674e06)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_del
```
```
In block/blk-ioc.c (ffffffff8167d9cd)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-mq.c (ffffffff81683876)
Location: include/linux/list.h:838
Inline: True
```
```
In io_uring/io_uring.c (ffffffff816d1dd2)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_poll_remove
  - io_uring/io_uring.c:io_poll_remove_all
  - io_uring/io_uring.c:__io_arm_poll_handler
  - io_uring/io_uring.c:io_apoll_task_func
  - io_uring/io_uring.c:io_poll_task_func
```
```
In drivers/clk/clk.c (ffffffff818af8b7)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/ptp/ptp_vclock.c (ffffffff81b3ed90)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_register
```
```
In net/core/dev.c (ffffffff81c1efe4)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netif_napi_add_weight
  - net/core/dev.c:netdev_name_node_alt_create
```
```
In net/sched/sch_api.c (ffffffff81c985d3)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_insert
```
```
In net/ipv4/devinet.c (ffffffff81d2af65)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d62675)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff81d6d12e)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/anycast.c (ffffffff81d86305)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81d930c4)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81d9c39d)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810a0436)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff810b6742)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:apf_task_wake_all
```
```
In kernel/fork.c (ffffffff83ea4eb4)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - kernel/fork.c:fork_idle
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (ffffffff810fd1ff)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff8110ffc2)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff8112a438)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/acct.c (ffffffff811fcbe3)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/cgroup.c (ffffffff83eb09a7)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (ffffffff81238918)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In kernel/trace/trace_kprobe.c (ffffffff812aa651)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:__unregister_trace_kprobe
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
```
In kernel/bpf/trampoline.c (ffffffff81309b29)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog
  - kernel/bpf/trampoline.c:__bpf_trampoline_link_prog
```
```
In kernel/events/core.c (ffffffff8133f433)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/watch_queue.c (ffffffff8135819d)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - kernel/watch_queue.c:init_watch
  - kernel/watch_queue.c:init_watch
```
```
In mm/ksm.c (ffffffff81422c76)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
```
```
In mm/khugepaged.c (ffffffff81446b8d)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff8147cf36)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
  - fs/super.c:alloc_super
```
```
In fs/dcache.c (ffffffff8149e4a6)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_unhash
  - fs/dcache.c:__d_alloc
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (0)
Location: include/linux/list.h:838
Inline: True
```
```
In fs/namespace.c (ffffffff814b1c07)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:alloc_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/fs_pin.c (ffffffff814cc5e2)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/notify/fanotify/fanotify.c (ffffffff814e2efb)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff814e3c13)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/crypto/keysetup_v1.c (ffffffff815010fa)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff8150dcce)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In fs/quota/dquot.c (ffffffff815240dd)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:invalidate_dquots
```
```
In fs/proc/inode.c (ffffffff81530748)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_alloc_inode
```
```
In fs/fat/inode.c (ffffffff8160267a)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - fs/fat/inode.c:init_once
  - fs/fat/inode.c:init_once
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In security/selinux/avc.c (ffffffff8166c728)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
```
```
In block/elevator.c (ffffffff81730b86)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_del
```
```
In block/blk-ioc.c (ffffffff8173a5dd)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-mq.c (ffffffff81740fa6)
Location: include/linux/list.h:838
Inline: True
```
```
In io_uring/poll.c (ffffffff8179d26d)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_disarm
  - io_uring/poll.c:io_poll_remove_all_table
  - io_uring/poll.c:__io_arm_poll_handler
  - io_uring/poll.c:io_poll_task_func
  - io_uring/poll.c:io_poll_task_func
```
```
In drivers/clk/clk.c (ffffffff819fbae7)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/ptp/ptp_vclock.c (ffffffff81cd512d)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_register
```
```
In net/core/dev.c (ffffffff81dd13e2)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netif_napi_add_weight
  - net/core/dev.c:netdev_name_node_alt_create
```
```
In net/sched/sch_api.c (ffffffff81e54593)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_insert
```
```
In net/ipv4/devinet.c (ffffffff81ef2b81)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f2d175)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff81f3859e)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/anycast.c (ffffffff81f53e55)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81f61854)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81f6b07d)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_alloc
```
```
In net/mctp/af_mctp.c (ffffffff8201035e)
Location: include/linux/list.h:838
Inline: True
```
```
In net/mctp/route.c (ffffffff8201365b)
Location: include/linux/list.h:838
Inline: True
Inline callers:
  - net/mctp/route.c:__mctp_key_done_in
  - net/mctp/route.c:__mctp_key_done_in
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810a33b6)
Location: include/linux/list.h:853
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff810b9852)
Location: include/linux/list.h:853
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:apf_task_wake_all
```
```
In kernel/fork.c (ffffffff836c9234)
Location: include/linux/list.h:853
Inline: True
Inline callers:
  - kernel/fork.c:fork_idle
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (ffffffff811091ff)
Location: include/linux/list.h:853
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff81120b43)
Location: include/linux/list.h:853
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff81137488)
Location: include/linux/list.h:853
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/irq/resend.c (ffffffff811abfd5)
Location: include/linux/list.h:853
Inline: True
Inline callers:
  - kernel/irq/resend.c:irq_resend_init
  - kernel/irq/resend.c:clear_irq_resend
  - kernel/irq/resend.c:resend_irqs
```
```
In kernel/acct.c (ffffffff81211d7f)
Location: include/linux/list.h:853
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/cgroup.c (ffffffff836d5997)
Location: include/linux/list.h:853
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (ffffffff8124fa78)
Location: include/linux/list.h:853
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In kernel/trace/trace_events_user.c (ffffffff812c5329)
Location: include/linux/list.h:853
Inline: True
```
```
In kernel/trace/trace_kprobe.c (ffffffff812cce01)
Location: include/linux/list.h:853
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:__unregister_trace_kprobe
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
```
In kernel/bpf/trampoline.c (ffffffff81338969)
Location: include/linux/list.h:853
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog
  - kernel/bpf/trampoline.c:__bpf_trampoline_link_prog
```
```
In kernel/events/core.c (ffffffff81370603)
Location: include/linux/list.h:853
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/watch_queue.c (ffffffff81389a1d)
Location: include/linux/list.h:853
Inline: True
Inline callers:
  - kernel/watch_queue.c:init_watch
  - kernel/watch_queue.c:init_watch
```
```
In mm/ksm.c (ffffffff81457ce1)
Location: include/linux/list.h:853
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
```
```
In mm/khugepaged.c (ffffffff8147c2e0)
Location: include/linux/list.h:853
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff814b1d06)
Location: include/linux/list.h:853
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
  - fs/super.c:alloc_super
```
```
In fs/dcache.c (ffffffff814d37c6)
Location: include/linux/list.h:853
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_unhash
  - fs/dcache.c:__d_alloc
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (0)
Location: include/linux/list.h:853
Inline: True
```
```
In fs/namespace.c (ffffffff814e6c56)
Location: include/linux/list.h:853
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:alloc_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/fs_pin.c (ffffffff81502822)
Location: include/linux/list.h:853
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/notify/fanotify/fanotify.c (ffffffff815196f0)
Location: include/linux/list.h:853
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8151a574)
Location: include/linux/list.h:853
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/crypto/keysetup_v1.c (ffffffff8153878a)
Location: include/linux/list.h:853
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff815454ae)
Location: include/linux/list.h:853
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In fs/quota/dquot.c (ffffffff8155c4e5)
Location: include/linux/list.h:853
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:invalidate_dquots
```
```
In fs/proc/inode.c (ffffffff815688c8)
Location: include/linux/list.h:853
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_alloc_inode
```
```
In fs/fat/inode.c (ffffffff8163a59a)
Location: include/linux/list.h:853
Inline: True
Inline callers:
  - fs/fat/inode.c:init_once
  - fs/fat/inode.c:init_once
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In security/selinux/avc.c (ffffffff816a4a43)
Location: include/linux/list.h:853
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
```
```
In block/elevator.c (ffffffff8176cde6)
Location: include/linux/list.h:853
Inline: True
Inline callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_del
```
```
In block/blk-ioc.c (ffffffff81776cd8)
Location: include/linux/list.h:853
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-mq.c (ffffffff8177d1f1)
Location: include/linux/list.h:853
Inline: True
```
```
In io_uring/poll.c (ffffffff817de49d)
Location: include/linux/list.h:853
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_disarm
  - io_uring/poll.c:io_poll_remove_all_table
  - io_uring/poll.c:__io_arm_poll_handler
  - io_uring/poll.c:io_poll_task_func
  - io_uring/poll.c:io_poll_task_func
```
```
In drivers/clk/clk.c (ffffffff81a44597)
Location: include/linux/list.h:853
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/ptp/ptp_vclock.c (ffffffff81d3cdb0)
Location: include/linux/list.h:853
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_register
```
```
In net/core/dev.c (ffffffff81e41fd2)
Location: include/linux/list.h:853
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netif_napi_add_weight
  - net/core/dev.c:netdev_name_node_alt_create
```
```
In net/sched/sch_api.c (ffffffff81eafe25)
Location: include/linux/list.h:853
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_insert
```
```
In net/ipv4/devinet.c (ffffffff81f52733)
Location: include/linux/list.h:853
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f8cc75)
Location: include/linux/list.h:853
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff81f97f8e)
Location: include/linux/list.h:853
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/anycast.c (ffffffff81fb3845)
Location: include/linux/list.h:853
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81fc1686)
Location: include/linux/list.h:853
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81fcb102)
Location: include/linux/list.h:853
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_alloc
```
```
In net/mctp/af_mctp.c (ffffffff8208d72e)
Location: include/linux/list.h:853
Inline: True
```
```
In net/mctp/route.c (ffffffff8209047b)
Location: include/linux/list.h:853
Inline: True
Inline callers:
  - net/mctp/route.c:__mctp_key_done_in
  - net/mctp/route.c:__mctp_key_done_in
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
In arch/x86/kernel/apic/vector.c (ffffffff810aa2f6)
Location: include/linux/list.h:942
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff810c0c7e)
Location: include/linux/list.h:942
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:apf_task_wake_all
```
```
In kernel/fork.c (ffffffff838f9e84)
Location: include/linux/list.h:942
Inline: True
Inline callers:
  - kernel/fork.c:fork_idle
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (ffffffff81112b8f)
Location: include/linux/list.h:942
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff8112a3f3)
Location: include/linux/list.h:942
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff81142668)
Location: include/linux/list.h:942
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/irq/resend.c (ffffffff811bbbd5)
Location: include/linux/list.h:942
Inline: True
Inline callers:
  - kernel/irq/resend.c:irq_resend_init
  - kernel/irq/resend.c:clear_irq_resend
  - kernel/irq/resend.c:resend_irqs
```
```
In kernel/acct.c (ffffffff8122942a)
Location: include/linux/list.h:942
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/cgroup.c (ffffffff83907d07)
Location: include/linux/list.h:942
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (ffffffff812699a8)
Location: include/linux/list.h:942
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:init_aggr_kprobe
```
```
In kernel/trace/trace_events_user.c (ffffffff812e1d5e)
Location: include/linux/list.h:942
Inline: True
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ea7f1)
Location: include/linux/list.h:942
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:__unregister_trace_kprobe
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
```
In kernel/bpf/trampoline.c (ffffffff8135ea99)
Location: include/linux/list.h:942
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog
  - kernel/bpf/trampoline.c:__bpf_trampoline_link_prog
```
```
In kernel/events/core.c (ffffffff81399903)
Location: include/linux/list.h:942
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/watch_queue.c (ffffffff813b346d)
Location: include/linux/list.h:942
Inline: True
Inline callers:
  - kernel/watch_queue.c:init_watch
  - kernel/watch_queue.c:init_watch
```
```
In mm/ksm.c (ffffffff814927b1)
Location: include/linux/list.h:942
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
```
```
In mm/khugepaged.c (ffffffff814ab3b0)
Location: include/linux/list.h:942
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff814e5236)
Location: include/linux/list.h:942
Inline: True
Inline callers:
  - fs/super.c:alloc_super
```
```
In fs/dcache.c (ffffffff81505f46)
Location: include/linux/list.h:942
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_unhash
  - fs/dcache.c:__d_alloc
  - fs/dcache.c:__d_alloc
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (0)
Location: include/linux/list.h:942
Inline: True
```
```
In fs/namespace.c (ffffffff8151aa96)
Location: include/linux/list.h:942
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:alloc_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/libfs.c (ffffffff8152252f)
Location: include/linux/list.h:942
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/fs_pin.c (ffffffff81537472)
Location: include/linux/list.h:942
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8154dad0)
Location: include/linux/list.h:942
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8154e944)
Location: include/linux/list.h:942
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/crypto/keysetup_v1.c (ffffffff8156d90a)
Location: include/linux/list.h:942
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff8157aa0e)
Location: include/linux/list.h:942
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In fs/quota/dquot.c (ffffffff81592ca5)
Location: include/linux/list.h:942
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:invalidate_dquots
```
```
In fs/proc/inode.c (ffffffff815a0ee8)
Location: include/linux/list.h:942
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_alloc_inode
```
```
In fs/fat/inode.c (ffffffff81673a8a)
Location: include/linux/list.h:942
Inline: True
Inline callers:
  - fs/fat/inode.c:init_once
  - fs/fat/inode.c:init_once
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In security/selinux/avc.c (ffffffff816e14a3)
Location: include/linux/list.h:942
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
```
```
In block/elevator.c (ffffffff817af016)
Location: include/linux/list.h:942
Inline: True
Inline callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_del
```
```
In block/blk-ioc.c (ffffffff817b8f05)
Location: include/linux/list.h:942
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-mq.c (ffffffff817bf57e)
Location: include/linux/list.h:942
Inline: True
```
```
In io_uring/poll.c (ffffffff8182286d)
Location: include/linux/list.h:942
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_disarm
  - io_uring/poll.c:io_poll_remove_all_table
  - io_uring/poll.c:__io_arm_poll_handler
  - io_uring/poll.c:io_poll_task_func
  - io_uring/poll.c:io_poll_task_func
```
```
In io_uring/waitid.c (ffffffff8182ad46)
Location: include/linux/list.h:942
Inline: True
Inline callers:
  - io_uring/waitid.c:io_waitid
  - io_uring/waitid.c:io_waitid_complete
```
```
In io_uring/futex.c (ffffffff8182ee6d)
Location: include/linux/list.h:942
Inline: True
Inline callers:
  - io_uring/futex.c:io_futexv_complete
  - io_uring/futex.c:io_futex_complete
```
```
In drivers/clk/clk.c (ffffffff81a900a7)
Location: include/linux/list.h:942
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/ptp/ptp_vclock.c (ffffffff81df371f)
Location: include/linux/list.h:942
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_register
```
```
In net/core/dev.c (ffffffff81f00a6d)
Location: include/linux/list.h:942
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netif_napi_add_weight
  - net/core/dev.c:netdev_name_node_alt_create
```
```
In net/core/page_pool_user.c (ffffffff81f456a4)
Location: include/linux/list.h:942
Inline: True
Inline callers:
  - net/core/page_pool_user.c:page_pool_netdevice_event
  - net/core/page_pool_user.c:page_pool_list
```
```
In net/sched/sch_api.c (ffffffff81f72895)
Location: include/linux/list.h:942
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_insert
```
```
In net/ipv4/devinet.c (ffffffff82018a0a)
Location: include/linux/list.h:942
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/tcp_ao.c (ffffffff82056b7f)
Location: include/linux/list.h:942
Inline: True
Inline callers:
  - net/ipv4/tcp_ao.c:tcp_ao_add_cmd
  - net/ipv4/tcp_ao.c:tcp_ao_copy_all_matching
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205a605)
Location: include/linux/list.h:942
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff820652fe)
Location: include/linux/list.h:942
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/anycast.c (ffffffff820810ea)
Location: include/linux/list.h:942
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff8208ebbe)
Location: include/linux/list.h:942
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff820988d4)
Location: include/linux/list.h:942
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_alloc
```
```
In net/mctp/af_mctp.c (ffffffff82163bee)
Location: include/linux/list.h:942
Inline: True
```
```
In net/mctp/route.c (ffffffff821669bb)
Location: include/linux/list.h:942
Inline: True
Inline callers:
  - net/mctp/route.c:__mctp_key_done_in
  - net/mctp/route.c:__mctp_key_done_in
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
In virt/kvm/kvm_main.c (ffff8000100bee78)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:kvm_vm_ioctl
```
```
In kernel/fork.c (ffff8000100f4b80)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/fork.c:fork_idle
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (ffff80001010a438)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffff80001011e4c4)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffff8000101300a8)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/acct.c (ffff8000101c7868)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/acct.c:__arm64_sys_acct
  - kernel/acct.c:__arm64_sys_acct
```
```
In kernel/cgroup/cgroup.c (ffff80001144b07c)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (ffff8000101f8504)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/trace/trace_kprobe.c (ffff80001024f6a8)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:__unregister_trace_kprobe
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
```
In kernel/events/core.c (ffff80001029731c)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/ksm.c (ffff80001033fb54)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffff80001035c6bc)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffff800010388120)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
  - fs/super.c:alloc_super
```
```
In fs/dcache.c (ffff8000103a5728)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:__d_alloc
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffff8000103ad358)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
  - fs/inode.c:inode_init_once
```
```
In fs/namespace.c (ffff8000103b8b1c)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/fs_pin.c (ffff8000103d3f50)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/crypto/keysetup_v1.c (ffff80001040f928)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffff800010416598)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
  - fs/locks.c:locks_init_lock
  - fs/locks.c:locks_alloc_lock
```
```
In fs/quota/dquot.c (ffff800010431f64)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/fat/inode.c (ffff8000104ec758)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/fat/inode.c:init_once
  - fs/fat/inode.c:init_once
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In security/selinux/avc.c (ffff800010546ca8)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
```
```
In block/elevator.c (ffff8000105de9b0)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-core.c (ffff8000105e0144)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-ioc.c (ffff8000105e8534)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-mq.c (0)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/bsg.c (0)
Location: include/linux/list.h:741
Inline: True
```
```
In drivers/clk/clk.c (ffff8000107c1728)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
```
```
In drivers/dax/super.c (ffff800010963988)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/sched/sch_api.c (ffff800010c3b52c)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_insert
```
```
In net/ipv4/devinet.c (ffff800010ca9340)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/xfrm/xfrm_policy.c (ffff800010cd897c)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffff800010ce27b8)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/anycast.c (ffff800010cf7260)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffff800010d02bcc)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffff800010d0bbfc)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In kernel/fork.c (c0353338)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/fork.c:fork_idle
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (c0363484)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (c03702d8)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (c037f8f4)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/acct.c (c040ee80)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/acct.c:__se_sys_acct
  - kernel/acct.c:__se_sys_acct
```
```
In kernel/cgroup/cgroup.c (c15254a4)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (c0436d98)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/trace/trace_kprobe.c (c0482854)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:__unregister_trace_kprobe
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
```
In kernel/events/core.c (c04c74a8)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/ksm.c (c0545e64)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_do_scan
```
```
In fs/super.c (c056ec34)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
  - fs/super.c:alloc_super
```
```
In fs/dcache.c (c0588f40)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:__d_alloc
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (c058bf3c)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
  - fs/inode.c:inode_init_once
```
```
In fs/namespace.c (c0596470)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/fs_pin.c (c05ae144)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/crypto/keysetup_v1.c (c05dc1c0)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (c05e203c)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
  - fs/locks.c:locks_init_lock
  - fs/locks.c:locks_alloc_lock
```
```
In fs/quota/dquot.c (c05fa174)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/fat/inode.c (c06aaba8)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/fat/inode.c:init_once
  - fs/fat/inode.c:init_once
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In security/selinux/avc.c (c06fc650)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
```
```
In block/elevator.c (c078b950)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-core.c (c078e244)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-ioc.c (c079569c)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-mq.c (c079aba8)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/bsg.c (0)
Location: include/linux/list.h:741
Inline: True
```
```
In drivers/clk/clk.c (c08edfc8)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
```
```
In drivers/dax/super.c (c0a39bcc)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/sched/sch_api.c (c0d4d2ac)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_insert
```
```
In net/ipv4/devinet.c (c0db592c)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/xfrm/xfrm_policy.c (c0de2554)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (c0deb8ac)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/anycast.c (c0dfd940)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (c0e098a4)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (0)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In kernel/fork.c (c00000000013aba0)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/fork.c:fork_idle
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (c0000000001513a4)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (c000000000169410)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (c0000000001794a4)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/acct.c (c000000000230440)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/acct.c:__se_sys_acct
  - kernel/acct.c:__se_sys_acct
```
```
In kernel/cgroup/cgroup.c (c000000001370884)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (c00000000026cdf4)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/trace/trace_kprobe.c (c0000000002ecc88)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:__unregister_trace_kprobe
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
```
In kernel/events/core.c (c000000000346c1c)
Location: include/linux/list.h:741
Inline: True
```
```
In mm/ksm.c (c00000000041c404)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
```
```
In mm/khugepaged.c (c000000000445e04)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (c00000000047c0b8)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
  - fs/super.c:alloc_super
```
```
In fs/dcache.c (c0000000004a11a8)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:__d_alloc
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (c0000000004a8be0)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
  - fs/inode.c:inode_init_once
```
```
In fs/namespace.c (c0000000004b5b94)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/fs_pin.c (c0000000004d6aa8)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/crypto/keysetup_v1.c (c00000000051d2c0)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (c000000000525330)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
  - fs/locks.c:locks_init_lock
  - fs/locks.c:locks_alloc_lock
```
```
In fs/quota/dquot.c (c0000000005431d0)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/fat/inode.c (c00000000062b898)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/fat/inode.c:init_once
  - fs/fat/inode.c:init_once
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In security/selinux/avc.c (c00000000069d644)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
```
```
In block/elevator.c (c00000000077070c)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-core.c (c00000000077403c)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-ioc.c (c00000000077dc48)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-mq.c (c000000000784790)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/bsg.c (c0000000007a6b00)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In drivers/dax/super.c (c000000000a18dc8)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/sched/sch_api.c (c000000000d346d4)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_insert
```
```
In net/ipv4/devinet.c (c000000000dbe478)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/xfrm/xfrm_policy.c (c000000000df91a8)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (c000000000e05264)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/anycast.c (c000000000e1daa8)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (c000000000e2a5dc)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (c000000000e3640c)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In kernel/fork.c (ffffffe0000c1324)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/fork.c:fork_idle
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (ffffffe0000cce8a)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffe0000d7d0c)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffe0000e35b0)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/acct.c (ffffffe000147e50)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/acct.c:__se_sys_acct
  - kernel/acct.c:__se_sys_acct
```
```
In kernel/cgroup/cgroup.c (ffffffe00000c436)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/events/core.c (ffffffe0001c9e12)
Location: include/linux/list.h:741
Inline: True
```
```
In mm/ksm.c (ffffffe0002343e2)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_do_scan
```
```
In fs/super.c (ffffffe000259bbe)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
  - fs/super.c:alloc_super
```
```
In fs/dcache.c (ffffffe00026c2d2)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:__d_alloc
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffe000271e2a)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
  - fs/inode.c:inode_init_once
```
```
In fs/namespace.c (ffffffe00027af3a)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/fs_pin.c (ffffffe00028e5b2)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/crypto/keysetup_v1.c (ffffffe0002b83b8)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffe0002bd5b2)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
  - fs/locks.c:locks_init_lock
  - fs/locks.c:locks_alloc_lock
```
```
In fs/quota/dquot.c (ffffffe0002ce414)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/fat/inode.c (ffffffe00035cf96)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/fat/inode.c:init_once
  - fs/fat/inode.c:init_once
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In security/selinux/avc.c (ffffffe0003a22e8)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
```
```
In block/elevator.c (ffffffe0004215a0)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-core.c (ffffffe0004234f8)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-ioc.c (ffffffe0004298ac)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-mq.c (ffffffe00042da3c)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/bsg.c (0)
Location: include/linux/list.h:741
Inline: True
```
```
In drivers/clk/clk.c (ffffffe00050f406)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
```
```
In drivers/dax/super.c (ffffffe0005d0516)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/sched/sch_api.c (ffffffe0007ac190)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_insert
```
```
In net/ipv4/devinet.c (ffffffe000803e1a)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/xfrm/xfrm_policy.c (ffffffe000828e8a)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffe000830e6a)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/anycast.c (ffffffe00084268c)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffe00084bf56)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffe000852bd8)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In arch/x86/kernel/apic/vector.c (ffffffff81067903)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff810764c1)
Location: include/linux/list.h:741
Inline: True
```
```
In kernel/fork.c (ffffffff81099c32)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/fork.c:fork_idle
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (ffffffff810a96c0)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff810bc972)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff810c9ecf)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/acct.c (ffffffff81150dfd)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/cgroup.c (ffffffff828bb98f)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (ffffffff81179d8b)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/trace/trace_kprobe.c (ffffffff811c744a)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:__unregister_trace_kprobe
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
```
In kernel/events/core.c (ffffffff812078bf)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/ksm.c (ffffffff812988fb)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812b3533)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff812d8aa4)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
  - fs/super.c:alloc_super
```
```
In fs/dcache.c (ffffffff812f076a)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:__d_alloc
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff812f5509)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
  - fs/inode.c:inode_init_once
```
```
In fs/namespace.c (ffffffff812fda45)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/fs_pin.c (ffffffff81314b55)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/crypto/keysetup_v1.c (ffffffff81346b4c)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff8134c4bd)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
  - fs/locks.c:locks_init_lock
  - fs/locks.c:locks_alloc_lock
```
```
In fs/quota/dquot.c (ffffffff81362408)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/fat/inode.c (ffffffff81404434)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/fat/inode.c:init_once
  - fs/fat/inode.c:init_once
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In security/selinux/avc.c (ffffffff81452a62)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
```
```
In block/elevator.c (ffffffff814d9e93)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-core.c (ffffffff814dc4c2)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-ioc.c (ffffffff814e2e67)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-mq.c (ffffffff814e7a6a)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/bsg.c (0)
Location: include/linux/list.h:741
Inline: True
```
```
In drivers/clk/clk.c (ffffffff81617027)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
```
```
In drivers/dax/super.c (ffffffff81717867)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/sched/sch_api.c (ffffffff8192f463)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_insert
```
```
In net/ipv4/devinet.c (ffffffff81992d3b)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/xfrm/xfrm_policy.c (ffffffff819bbda9)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff819c4619)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/anycast.c (ffffffff819d5d04)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff819e07d1)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff819e7eb4)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In arch/x86/kernel/apic/vector.c (ffffffff81057c73)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff81066481)
Location: include/linux/list.h:741
Inline: True
```
```
In kernel/fork.c (ffffffff81088672)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/fork.c:fork_idle
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (ffffffff81098080)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff810ab1d2)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff810b86ef)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/acct.c (ffffffff811440ad)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/cgroup.c (ffffffff828b4022)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (ffffffff8116cf2b)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/trace/trace_kprobe.c (ffffffff811ba22a)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:__unregister_trace_kprobe
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
```
In kernel/events/core.c (ffffffff811fa9ef)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/ksm.c (ffffffff8128a4bb)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812a48b3)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff812c9724)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
  - fs/super.c:alloc_super
```
```
In fs/dcache.c (ffffffff812e139a)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:__d_alloc
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff812e6129)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
  - fs/inode.c:inode_init_once
```
```
In fs/namespace.c (ffffffff812ee665)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/fs_pin.c (ffffffff81305765)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/crypto/keysetup_v1.c (ffffffff8133782c)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff8133d19d)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
  - fs/locks.c:locks_init_lock
  - fs/locks.c:locks_alloc_lock
```
```
In fs/quota/dquot.c (ffffffff813530a8)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/fat/inode.c (ffffffff813f4eb4)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/fat/inode.c:init_once
  - fs/fat/inode.c:init_once
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In security/selinux/avc.c (ffffffff814434b2)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
```
```
In block/elevator.c (ffffffff814ca843)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-core.c (ffffffff814cce72)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-ioc.c (ffffffff814d37f7)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-mq.c (ffffffff814d7fda)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/bsg.c (0)
Location: include/linux/list.h:741
Inline: True
```
```
In drivers/clk/clk.c (ffffffff8160b557)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
```
```
In drivers/dax/super.c (ffffffff816efd97)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/sched/sch_api.c (ffffffff818e8f63)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_insert
```
```
In net/ipv4/devinet.c (ffffffff8194c7fb)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/xfrm/xfrm_policy.c (ffffffff81978b99)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff81981409)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/anycast.c (ffffffff81992ac4)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff8199d591)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff819a4c74)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In arch/x86/kernel/apic/vector.c (ffffffff81067db3)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff81076471)
Location: include/linux/list.h:741
Inline: True
```
```
In kernel/fork.c (ffffffff81099be2)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/fork.c:fork_idle
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (ffffffff810a8c20)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff810bbed2)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff810c93ff)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/acct.c (ffffffff8114ecad)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/cgroup.c (ffffffff828ce712)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (ffffffff81177b5b)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/trace/trace_kprobe.c (ffffffff811c521a)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:__unregister_trace_kprobe
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
```
In kernel/events/core.c (ffffffff8120568f)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/ksm.c (ffffffff8129670b)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812b1343)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff812d68b4)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
  - fs/super.c:alloc_super
```
```
In fs/dcache.c (ffffffff812ee57a)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:__d_alloc
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff812f3319)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
  - fs/inode.c:inode_init_once
```
```
In fs/namespace.c (ffffffff812fb835)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/fs_pin.c (ffffffff81312945)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/crypto/keysetup_v1.c (ffffffff8134461c)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff81349f8d)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
  - fs/locks.c:locks_init_lock
  - fs/locks.c:locks_alloc_lock
```
```
In fs/quota/dquot.c (ffffffff8135fed8)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/fat/inode.c (ffffffff814017b4)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/fat/inode.c:init_once
  - fs/fat/inode.c:init_once
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In security/selinux/avc.c (ffffffff8144eb02)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
```
```
In block/elevator.c (ffffffff814d5f23)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-core.c (ffffffff814d8552)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-ioc.c (ffffffff814deef7)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-mq.c (ffffffff814e3afa)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/bsg.c (0)
Location: include/linux/list.h:741
Inline: True
```
```
In drivers/clk/clk.c (ffffffff81644e07)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
```
```
In drivers/dax/super.c (ffffffff81756637)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/sched/sch_api.c (ffffffff819805f3)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_insert
```
```
In net/netfilter/nfnetlink_log.c (ffffffff8199bbd4)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_log.c:nfulnl_recv_config
```
```
In net/ipv4/devinet.c (ffffffff819fd5db)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a26829)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff81a2f099)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/anycast.c (ffffffff81a40784)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81a4b251)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81a52934)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81069463)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff810784c1)
Location: include/linux/list.h:741
Inline: True
```
```
In kernel/fork.c (ffffffff810a1832)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/fork.c:fork_idle
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (ffffffff810b0d20)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff810c0ea0)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:init_worker_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff810d195f)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/acct.c (ffffffff8115ba8d)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/cgroup.c (ffffffff828d3b0c)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (ffffffff8118541b)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:init_aggr_kprobe
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/trace/trace_kprobe.c (ffffffff811d347a)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:__unregister_trace_kprobe
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
```
In kernel/events/core.c (ffffffff812144ff)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/ksm.c (ffffffff812a64f7)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812c1683)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff812e6784)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
  - fs/super.c:alloc_super
```
```
In fs/dcache.c (ffffffff8130054a)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:__d_alloc
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff81303089)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
  - fs/inode.c:inode_init_once
```
```
In fs/namespace.c (ffffffff8130cb72)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/fs_pin.c (ffffffff81324185)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/crypto/keysetup_v1.c (ffffffff813578fc)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff8135ccae)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
  - fs/locks.c:locks_init_lock
  - fs/locks.c:locks_alloc_lock
```
```
In fs/quota/dquot.c (ffffffff81372994)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/fat/inode.c (ffffffff814178e4)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - fs/fat/inode.c:init_once
  - fs/fat/inode.c:init_once
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In security/selinux/avc.c (ffffffff81465ee2)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
```
```
In block/elevator.c (ffffffff814eeb23)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-core.c (ffffffff814f1162)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-ioc.c (ffffffff814f7d47)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-mq.c (ffffffff814fd05e)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/bsg.c (0)
Location: include/linux/list.h:741
Inline: True
```
```
In drivers/clk/clk.c (ffffffff8165f327)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
```
```
In drivers/dax/super.c (ffffffff81771898)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In net/sched/sch_api.c (ffffffff819a2b63)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_insert
```
```
In net/ipv4/devinet.c (ffffffff81a0796b)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a31cd9)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3a2f9)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/ipv6/anycast.c (ffffffff81a4c384)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81a571ac)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81a5e8c4)
Location: include/linux/list.h:741
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
</details>
</li>
</ul>

## Differences

# Function: <code>do_raw_write_seqcount_begin</code>

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
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff82faf9d1)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffff810a8581)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In kernel/kthread.c (ffffffff810cc34c)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/sched/psi.c (ffffffff8110ac76)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_group_change
```
```
In kernel/time/timekeeping.c (ffffffff81146a4e)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In kernel/time/tick-common.c (ffffffff811529d3)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff81154a15)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In kernel/cgroup/cpuset.c (ffffffff8117af5a)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/memory.c (ffffffff8129ee5a)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/memory_hotplug.c (ffffffff81c3a78f)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:shrink_zone_span
```
```
In fs/dcache.c (ffffffff8133ea89)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/namespace.c (ffffffff8134c50b)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_reconfigure_mnt
  - fs/namespace.c:do_reconfigure_mnt
  - fs/namespace.c:do_reconfigure_mnt
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs_struct.c (ffffffff813619d0)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/userfaultfd.c (ffffffff81381d84)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
```
In block/badblocks.c (ffffffff81578c12)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
```
```
In block/blk-iocost.c (ffffffff8158c5a6)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_start_period
```
```
In lib/flex_proportions.c (ffffffff8160da3b)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8183a098)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In net/core/gen_estimator.c (ffffffff819f750d)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/dev.c (ffffffff81a06d91)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/core/neighbour.c (ffffffff81a163ec)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff81aa161e)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad8b58)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81b0c749)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b21d37)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_bydst_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81b280d8)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
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
In init/main.c (ffffffff831b99ef)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffff810a9443)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In kernel/kthread.c (ffffffff810cde22)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/sched/psi.c (ffffffff8110bde2)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_group_change
```
```
In kernel/time/timekeeping.c (ffffffff81147bbe)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In kernel/time/tick-common.c (ffffffff81153e13)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff811560b5)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In kernel/cgroup/cpuset.c (ffffffff8117c7da)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/memory.c (ffffffff812a513c)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/memory_hotplug.c (ffffffff81c2cd6f)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:shrink_zone_span
```
```
In fs/dcache.c (ffffffff81344e79)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/namespace.c (ffffffff813530db)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:__do_sys_open_tree
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs_struct.c (ffffffff813684b0)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/userfaultfd.c (ffffffff81388deb)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
```
In block/badblocks.c (ffffffff81580955)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
```
```
In block/blk-iocost.c (ffffffff815932e6)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_start_period
```
```
In lib/flex_proportions.c (ffffffff815f117b)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8181d2d0)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In net/core/gen_estimator.c (ffffffff819dd68d)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/dev.c (ffffffff819ee499)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/core/neighbour.c (ffffffff819fcf99)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff81a8c57f)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ac3bc8)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81afa3b2)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0f953)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81b1569d)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
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
In init/main.c (ffffffff83299dcb)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffff810baf33)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In kernel/kthread.c (ffffffff810e106f)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/sched/psi.c (ffffffff8112aa9a)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_group_change
```
```
In kernel/time/timekeeping.c (ffffffff8116b6dd)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In kernel/time/tick-common.c (ffffffff81178503)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff8117ad65)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In kernel/cgroup/cpuset.c (ffffffff811a436a)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/memory.c (ffffffff812e4367)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In fs/dcache.c (ffffffff81392969)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/namespace.c (ffffffff813a152b)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_set_group
  - fs/namespace.c:__do_sys_open_tree
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs_struct.c (ffffffff813b71b0)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/userfaultfd.c (ffffffff813d60ec)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
```
In block/badblocks.c (ffffffff815e5c6e)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
```
```
In block/blk-iocost.c (ffffffff815fa596)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_start_period
```
```
In lib/flex_proportions.c (ffffffff8165e2df)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
```
```
In drivers/dma-buf/dma-resv.c (ffffffff818a7720)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In net/core/gen_estimator.c (ffffffff81a8d952)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/dev.c (ffffffff81a9f739)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/core/neighbour.c (ffffffff81aafa4e)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff81b476bf)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff81b82288)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81bbb0b2)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd2de3)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81bda40f)
Location: include/linux/seqlock.h:470
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
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
In init/main.c (ffffffff81e4381f)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - init/main.c:set_mems_allowed
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff810610d1)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_scale_freq_tick
```
```
In kernel/exit.c (ffffffff810d190a)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In kernel/kthread.c (ffffffff810f94f9)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - kernel/kthread.c:set_mems_allowed
```
```
In kernel/sched/build_utility.c (ffffffff8113f681)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_group_change
```
```
In kernel/time/timekeeping.c (ffffffff8119f6c9)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
```
In kernel/time/tick-common.c (ffffffff811ad6cb)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff811afb16)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In kernel/cgroup/cpuset.c (ffffffff811d3e19)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/memory.c (ffffffff81347478)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/hugetlb.c (ffffffff8139214f)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In fs/dcache.c (ffffffff81414212)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/namespace.c (ffffffff81424ef9)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_set_group
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs_struct.c (ffffffff8143c81e)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/userfaultfd.c (ffffffff8145ddae)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
```
In block/badblocks.c (ffffffff81694dce)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
```
```
In block/blk-iocost.c (ffffffff816ac936)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_start_period
```
```
In lib/flex_proportions.c (ffffffff81777a0d)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
```
```
In net/core/gen_estimator.c (ffffffff81c034a6)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/neighbour.c (ffffffff81c2844b)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff81cd48d8)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d12767)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81d4f1e6)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d698b8)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81d714be)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
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
In init/main.c (ffffffff81000e79)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - init/main.c:set_mems_allowed
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff8106fa01)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_scale_freq_tick
```
```
In kernel/exit.c (ffffffff810f035a)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In kernel/kthread.c (ffffffff8111c129)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - kernel/kthread.c:set_mems_allowed
```
```
In kernel/sched/build_utility.c (ffffffff8116a142)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_group_change
```
```
In kernel/time/timekeeping.c (ffffffff811de3c8)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
```
In kernel/time/tick-common.c (ffffffff811edc6b)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff811f0526)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In kernel/cgroup/cpuset.c (ffffffff81217bd9)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/memory.c (ffffffff813bf86a)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/page_alloc.c (ffffffff813eec79)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - mm/page_alloc.c:__build_all_zonelists
```
```
In mm/hugetlb.c (ffffffff8140f155)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In fs/dcache.c (ffffffff8149f692)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/namespace.c (ffffffff814b1637)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_set_group
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:__legitimize_mnt
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs_struct.c (ffffffff814caf3e)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/userfaultfd.c (ffffffff814ed80b)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
```
In block/badblocks.c (ffffffff81753e0e)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
```
```
In block/blk-iocost.c (ffffffff8176b446)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_start_period
```
```
In net/core/gen_estimator.c (ffffffff81db2a86)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/neighbour.c (ffffffff81ddb054)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff81e94bb8)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed8587)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81f18de6)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f34bc8)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81f3d38e)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In lib/flex_proportions.c (ffffffff8202069e)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
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
In init/main.c (ffffffff81000bd9)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - init/main.c:set_mems_allowed
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81071601)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_scale_freq_tick
```
```
In kernel/exit.c (ffffffff810fc31a)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In kernel/kthread.c (ffffffff81129379)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - kernel/kthread.c:set_mems_allowed
```
```
In kernel/sched/build_utility.c (ffffffff8117a83e)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_group_change
```
```
In kernel/time/timekeeping.c (ffffffff811f2898)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
```
In kernel/time/tick-common.c (ffffffff8120239b)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff81205bca)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_irq_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_enter
  - kernel/time/tick-sched.c:tick_nohz_stop_idle
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In kernel/cgroup/cpuset.c (ffffffff8122d3f9)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/memory.c (ffffffff813f4536)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/page_alloc.c (ffffffff81422a5f)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - mm/page_alloc.c:__build_all_zonelists
```
```
In mm/hugetlb.c (ffffffff8144251f)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In fs/dcache.c (ffffffff814d49b2)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/namespace.c (ffffffff814e6677)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_set_group
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:__legitimize_mnt
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs_struct.c (ffffffff8150117d)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/userfaultfd.c (ffffffff8152481b)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
```
In block/badblocks.c (ffffffff8178ffbc)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
```
```
In block/blk-iocost.c (ffffffff817aa5a6)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_start_period
```
```
In net/core/gen_estimator.c (ffffffff81e23056)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/neighbour.c (ffffffff81e4bfc2)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff81ef3388)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f37697)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81f78a5c)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f947cc)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81f9ccfe)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In lib/flex_proportions.c (ffffffff820a06de)
Location: include/linux/seqlock.h:466
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
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
In init/main.c (ffffffff81000be9)
Location: include/linux/seqlock.h:420
Inline: True
Inline callers:
  - init/main.c:set_mems_allowed
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81078dc1)
Location: include/linux/seqlock.h:420
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_scale_freq_tick
```
```
In kernel/exit.c (ffffffff81105a16)
Location: include/linux/seqlock.h:420
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In kernel/kthread.c (ffffffff811339f9)
Location: include/linux/seqlock.h:420
Inline: True
Inline callers:
  - kernel/kthread.c:set_mems_allowed
```
```
In kernel/sched/build_policy.c (ffffffff811827e3)
Location: include/linux/seqlock.h:420
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:vtime_init_idle
  - kernel/sched/build_policy.c:vtime_task_switch_generic
  - kernel/sched/build_policy.c:vtime_task_switch_generic
  - kernel/sched/build_policy.c:vtime_guest_exit
  - kernel/sched/build_policy.c:vtime_guest_enter
  - kernel/sched/build_policy.c:vtime_user_exit
  - kernel/sched/build_policy.c:vtime_user_enter
  - kernel/sched/build_policy.c:vtime_account_kernel
```
```
In kernel/sched/build_utility.c (ffffffff8118826e)
Location: include/linux/seqlock.h:420
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_group_change
```
```
In kernel/time/timekeeping.c (ffffffff812089d8)
Location: include/linux/seqlock.h:420
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
```
In kernel/time/tick-common.c (ffffffff8121888b)
Location: include/linux/seqlock.h:420
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff8121cd60)
Location: include/linux/seqlock.h:420
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_irq_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_enter
  - kernel/time/tick-sched.c:tick_nohz_stop_idle
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In kernel/cgroup/cpuset.c (ffffffff812456c9)
Location: include/linux/seqlock.h:420
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/memory.c (ffffffff8141f1c4)
Location: include/linux/seqlock.h:420
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/page_alloc.c (ffffffff8144f855)
Location: include/linux/seqlock.h:420
Inline: True
Inline callers:
  - mm/page_alloc.c:__build_all_zonelists
```
```
In mm/hugetlb.c (ffffffff8147c674)
Location: include/linux/seqlock.h:420
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In fs/dcache.c (ffffffff81506cf2)
Location: include/linux/seqlock.h:420
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/namespace.c (ffffffff8151a4b2)
Location: include/linux/seqlock.h:420
Inline: True
Inline callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_set_group
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:__legitimize_mnt
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs_struct.c (ffffffff81535dc9)
Location: include/linux/seqlock.h:420
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/userfaultfd.c (ffffffff8155b30b)
Location: include/linux/seqlock.h:420
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
```
In block/badblocks.c (ffffffff817d2ebd)
Location: include/linux/seqlock.h:420
Inline: True
Inline callers:
  - block/badblocks.c:_badblocks_clear
  - block/badblocks.c:_badblocks_set
```
```
In block/blk-iocost.c (ffffffff817ee356)
Location: include/linux/seqlock.h:420
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_start_period
```
```
In drivers/gpu/drm/drm_vblank.c (ffffffff81cb42e5)
Location: include/linux/seqlock.h:420
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_vblank.c:store_vblank
```
```
In net/core/gen_estimator.c (ffffffff81ee0f96)
Location: include/linux/seqlock.h:420
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/neighbour.c (ffffffff81f0acd2)
Location: include/linux/seqlock.h:420
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff81fb7318)
Location: include/linux/seqlock.h:420
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ffd767)
Location: include/linux/seqlock.h:420
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8203f11c)
Location: include/linux/seqlock.h:420
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff82061bbc)
Location: include/linux/seqlock.h:420
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff8206a05e)
Location: include/linux/seqlock.h:420
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In lib/flex_proportions.c (ffffffff821786be)
Location: include/linux/seqlock.h:420
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
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
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences

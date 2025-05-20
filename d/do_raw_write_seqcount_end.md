# Function: <code>do_raw_write_seqcount_end</code>

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
In init/main.c (ffffffff82faf9ec)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffff810a87ba)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In kernel/kthread.c (ffffffff810cc403)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/sched/psi.c (ffffffff8110ac89)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_group_change
```
```
In kernel/time/timekeeping.c (ffffffff81146acf)
Location: include/linux/seqlock.h:491
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
In kernel/time/tick-common.c (ffffffff811529ef)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff81154a36)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In kernel/cgroup/cpuset.c (ffffffff8117b042)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/memory.c (ffffffff8129edcc)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/memory_hotplug.c (ffffffff81c3a7e6)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:shrink_zone_span
```
```
In fs/dcache.c (ffffffff8133eb7d)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
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
In fs/namespace.c (ffffffff8134c51a)
Location: include/linux/seqlock.h:491
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
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs_struct.c (ffffffff813619f9)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/userfaultfd.c (ffffffff81381dbd)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
```
In block/badblocks.c (ffffffff81578d76)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
```
```
In block/blk-iocost.c (ffffffff8158c5c3)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_start_period
```
```
In lib/flex_proportions.c (ffffffff8160da71)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8183a0a4)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In net/core/gen_estimator.c (ffffffff819f7527)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/dev.c (ffffffff81a06db1)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/core/neighbour.c (ffffffff81a16434)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff81aa1678)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad8b97)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81b0c754)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b21f24)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_bydst_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81b2815c)
Location: include/linux/seqlock.h:491
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
In init/main.c (ffffffff831b9a0a)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffff810a966a)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In kernel/kthread.c (ffffffff810cded2)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/sched/psi.c (ffffffff8110bf10)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_group_change
```
```
In kernel/time/timekeeping.c (ffffffff81147c3f)
Location: include/linux/seqlock.h:491
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
In kernel/time/tick-common.c (ffffffff81153e2f)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff811560d6)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In kernel/cgroup/cpuset.c (ffffffff8117c8c2)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/memory.c (ffffffff812a50ab)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/memory_hotplug.c (ffffffff81c2cdc6)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:shrink_zone_span
```
```
In fs/dcache.c (ffffffff81344f6d)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
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
In fs/namespace.c (ffffffff813530ea)
Location: include/linux/seqlock.h:491
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
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs_struct.c (ffffffff813684d9)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/userfaultfd.c (ffffffff81388e24)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
```
In block/badblocks.c (ffffffff81580ac2)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
```
```
In block/blk-iocost.c (ffffffff81593303)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_start_period
```
```
In lib/flex_proportions.c (ffffffff815f11b1)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8181d2dc)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In net/core/gen_estimator.c (ffffffff819dd6a7)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/dev.c (ffffffff819ee4aa)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/core/neighbour.c (ffffffff819fcfe2)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff81a8c5d8)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ac3c07)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81afa3bd)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0fb32)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81b15b26)
Location: include/linux/seqlock.h:491
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
In init/main.c (ffffffff83299de6)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffff810bb15a)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In kernel/kthread.c (ffffffff810e111c)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/sched/psi.c (ffffffff8112ac36)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_group_change
```
```
In kernel/time/timekeeping.c (ffffffff8116b771)
Location: include/linux/seqlock.h:491
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
In kernel/time/tick-common.c (ffffffff8117851f)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff8117ad86)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In kernel/cgroup/cpuset.c (ffffffff811a4452)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/memory.c (ffffffff812e42d8)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In fs/dcache.c (ffffffff81392a5d)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
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
In fs/namespace.c (ffffffff813a153a)
Location: include/linux/seqlock.h:491
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
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs_struct.c (ffffffff813b71d9)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/userfaultfd.c (ffffffff813d6125)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
```
In block/badblocks.c (ffffffff815e5ddb)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
```
```
In block/blk-iocost.c (ffffffff815fa5b3)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_start_period
```
```
In lib/flex_proportions.c (ffffffff8165e313)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
```
```
In drivers/dma-buf/dma-resv.c (ffffffff818a772c)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In net/core/gen_estimator.c (ffffffff81a8d970)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/dev.c (ffffffff81a9f756)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/core/neighbour.c (ffffffff81aafa9a)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff81b47718)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff81b822c7)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81bbb0bd)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd2fdc)
Location: include/linux/seqlock.h:491
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81bda4b6)
Location: include/linux/seqlock.h:491
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
In init/main.c (ffffffff81e43837)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - init/main.c:set_mems_allowed
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff810610e7)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_scale_freq_tick
```
```
In kernel/exit.c (ffffffff810d1b23)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In kernel/kthread.c (ffffffff810f95b6)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - kernel/kthread.c:set_mems_allowed
```
```
In kernel/sched/build_utility.c (ffffffff8113f804)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_group_change
```
```
In kernel/time/timekeeping.c (ffffffff8119f727)
Location: include/linux/seqlock.h:487
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
In kernel/time/tick-common.c (ffffffff811ad6e7)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff811afb37)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In kernel/cgroup/cpuset.c (ffffffff811d3f01)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/memory.c (ffffffff813473fb)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/hugetlb.c (ffffffff81392169)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In fs/dcache.c (ffffffff81414308)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
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
In fs/namespace.c (ffffffff81424f08)
Location: include/linux/seqlock.h:487
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
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs_struct.c (ffffffff8143c84c)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/userfaultfd.c (ffffffff8145dde6)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
```
In block/badblocks.c (ffffffff81694f26)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
```
```
In block/blk-iocost.c (ffffffff816ac953)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_start_period
```
```
In lib/flex_proportions.c (ffffffff81777a41)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
```
```
In net/core/gen_estimator.c (ffffffff81c034c1)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/neighbour.c (ffffffff81c28497)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff81cd492f)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d127cf)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81d4f1f1)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d69c2f)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81d7154e)
Location: include/linux/seqlock.h:487
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
In init/main.c (ffffffff81000f36)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - init/main.c:set_mems_allowed
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff8106fa17)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_scale_freq_tick
```
```
In kernel/exit.c (ffffffff810f0573)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In kernel/kthread.c (ffffffff8111c1e6)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - kernel/kthread.c:set_mems_allowed
```
```
In kernel/sched/build_utility.c (ffffffff8116a31d)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_group_change
  - kernel/sched/build_utility.c:psi_group_change
```
```
In kernel/time/timekeeping.c (ffffffff811de426)
Location: include/linux/seqlock.h:487
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
In kernel/time/tick-common.c (ffffffff811edc87)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff811f0547)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In kernel/cgroup/cpuset.c (ffffffff81217cc1)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/memory.c (ffffffff813bf7e7)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/page_alloc.c (ffffffff813eecf5)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - mm/page_alloc.c:__build_all_zonelists
```
```
In mm/hugetlb.c (ffffffff8140f0d9)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In fs/dcache.c (ffffffff8149f788)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
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
In fs/namespace.c (ffffffff814b1646)
Location: include/linux/seqlock.h:487
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
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:__legitimize_mnt
  - fs/namespace.c:__legitimize_mnt
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs_struct.c (ffffffff814caf6c)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/userfaultfd.c (ffffffff814ed843)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
```
In block/badblocks.c (ffffffff81753f66)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
```
```
In block/blk-iocost.c (ffffffff8176b463)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_start_period
```
```
In net/core/gen_estimator.c (ffffffff81db2aa1)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/neighbour.c (ffffffff81ddb0b4)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff81e94c0f)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed85ef)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81f18df1)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f34f54)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81f3d41e)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In lib/flex_proportions.c (ffffffff820206d2)
Location: include/linux/seqlock.h:487
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
In init/main.c (ffffffff81000c96)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - init/main.c:set_mems_allowed
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81071617)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_scale_freq_tick
```
```
In kernel/exit.c (ffffffff810fc533)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In kernel/kthread.c (ffffffff81129436)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - kernel/kthread.c:set_mems_allowed
```
```
In kernel/sched/build_utility.c (ffffffff8117aa42)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_group_change
  - kernel/sched/build_utility.c:psi_group_change
```
```
In kernel/time/timekeeping.c (ffffffff811f28f6)
Location: include/linux/seqlock.h:487
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
In kernel/time/tick-common.c (ffffffff812023b7)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff81205bda)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_irq_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_enter
  - kernel/time/tick-sched.c:tick_nohz_stop_idle
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In kernel/cgroup/cpuset.c (ffffffff8122d4e1)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/memory.c (ffffffff813f44a7)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/page_alloc.c (ffffffff81422adf)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - mm/page_alloc.c:__build_all_zonelists
```
```
In mm/hugetlb.c (ffffffff814424a4)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In fs/dcache.c (ffffffff814d4aa8)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
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
In fs/namespace.c (ffffffff814e6686)
Location: include/linux/seqlock.h:487
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
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:__legitimize_mnt
  - fs/namespace.c:__legitimize_mnt
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs_struct.c (ffffffff815011ac)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/userfaultfd.c (ffffffff81524853)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
```
In block/badblocks.c (ffffffff81790113)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
```
```
In block/blk-iocost.c (ffffffff817aa5c3)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_start_period
```
```
In net/core/gen_estimator.c (ffffffff81e23071)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/neighbour.c (ffffffff81e4c019)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff81ef33df)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f376ff)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81f78a67)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f94b58)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81f9cd8e)
Location: include/linux/seqlock.h:487
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In lib/flex_proportions.c (ffffffff820a0712)
Location: include/linux/seqlock.h:487
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
In init/main.c (ffffffff81000ca6)
Location: include/linux/seqlock.h:441
Inline: True
Inline callers:
  - init/main.c:set_mems_allowed
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81078dd7)
Location: include/linux/seqlock.h:441
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_scale_freq_tick
```
```
In kernel/exit.c (ffffffff81105c3c)
Location: include/linux/seqlock.h:441
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In kernel/kthread.c (ffffffff81133ab6)
Location: include/linux/seqlock.h:441
Inline: True
Inline callers:
  - kernel/kthread.c:set_mems_allowed
```
```
In kernel/sched/build_policy.c (ffffffff81182807)
Location: include/linux/seqlock.h:441
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
In kernel/sched/build_utility.c (ffffffff81188472)
Location: include/linux/seqlock.h:441
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_group_change
  - kernel/sched/build_utility.c:psi_group_change
```
```
In kernel/time/timekeeping.c (ffffffff81208a36)
Location: include/linux/seqlock.h:441
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
In kernel/time/tick-common.c (ffffffff812188a7)
Location: include/linux/seqlock.h:441
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff8121cd70)
Location: include/linux/seqlock.h:441
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_irq_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_enter
  - kernel/time/tick-sched.c:tick_nohz_stop_idle
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In kernel/cgroup/cpuset.c (ffffffff812457b1)
Location: include/linux/seqlock.h:441
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/memory.c (ffffffff8141f137)
Location: include/linux/seqlock.h:441
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/page_alloc.c (ffffffff8144f8d4)
Location: include/linux/seqlock.h:441
Inline: True
Inline callers:
  - mm/page_alloc.c:__build_all_zonelists
```
```
In mm/hugetlb.c (ffffffff8147c682)
Location: include/linux/seqlock.h:441
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In fs/dcache.c (ffffffff81506de8)
Location: include/linux/seqlock.h:441
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
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
In fs/namespace.c (ffffffff8151a4c2)
Location: include/linux/seqlock.h:441
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
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:__legitimize_mnt
  - fs/namespace.c:__legitimize_mnt
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs_struct.c (ffffffff81535df8)
Location: include/linux/seqlock.h:441
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/userfaultfd.c (ffffffff8155b343)
Location: include/linux/seqlock.h:441
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
```
In block/badblocks.c (ffffffff817d2f6e)
Location: include/linux/seqlock.h:441
Inline: True
Inline callers:
  - block/badblocks.c:_badblocks_clear
  - block/badblocks.c:_badblocks_set
```
```
In block/blk-iocost.c (ffffffff817ee373)
Location: include/linux/seqlock.h:441
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_start_period
```
```
In drivers/gpu/drm/drm_vblank.c (ffffffff81cb42f2)
Location: include/linux/seqlock.h:441
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_vblank.c:store_vblank
```
```
In net/core/gen_estimator.c (ffffffff81ee0fb1)
Location: include/linux/seqlock.h:441
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/neighbour.c (ffffffff81f0ad29)
Location: include/linux/seqlock.h:441
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff81fb736f)
Location: include/linux/seqlock.h:441
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ffd7cf)
Location: include/linux/seqlock.h:441
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8203f127)
Location: include/linux/seqlock.h:441
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff82061f48)
Location: include/linux/seqlock.h:441
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff8206a0ee)
Location: include/linux/seqlock.h:441
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In lib/flex_proportions.c (ffffffff821786f2)
Location: include/linux/seqlock.h:441
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

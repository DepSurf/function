# Function: <code>raw_write_seqcount_end</code>

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
In init/main.c (ffffffff81f5a09e)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffff81082704)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - kernel/exit.c:release_task
  - kernel/exit.c:wait_consider_task
```
```
In kernel/kthread.c (ffffffff810a0d7c)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/time/timekeeping.c (ffffffff810f5119)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_set_tai_offset
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:xtime_update
```
```
In kernel/time/tick-common.c (ffffffff810fc4a2)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff810fe10b)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
  - kernel/time/tick-sched.c:tick_do_update_jiffies64
  - kernel/time/tick-sched.c:tick_do_update_jiffies64
```
```
In kernel/cpuset.c (ffffffff8111b6c9)
Location: include/linux/seqlock.h:231
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff81208f74)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - mm/memory_hotplug.c:resize_zone
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:__remove_pages
```
```
In fs/dcache.c (ffffffff81222cf2)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - fs/dcache.c:dentry_update_name_case
  - fs/dcache.c:d_delete
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_move
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:d_exchange
```
```
In fs/namespace.c (ffffffff8122bbcc)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - fs/namespace.c:may_umount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:vfs_kern_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:sb_prepare_remount_readonly
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:SyS_pivot_root
```
```
In fs/fs_struct.c (ffffffff81241381)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - fs/fs_struct.c:set_fs_root
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/userfaultfd.c (ffffffff81259d95)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
```
```
In lib/flex_proportions.c (ffffffff813e988d)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
```
```
In drivers/dma-buf/reservation.c (ffffffff815a54cd)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
```
```
In drivers/md/md.c (ffffffff8168eefd)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - drivers/md/md.c:md_set_badblocks
  - drivers/md/md.c:md_clear_badblocks
```
```
In net/core/dev.c (ffffffff8171d441)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
```
```
In net/core/neighbour.c (ffffffff81728811)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff81757fc9)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
```
```
In net/ipv4/tcp_metrics.c (ffffffff81782654)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/inet_fragment.c (ffffffff817a1be1)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff817a5616)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
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
In init/main.c (ffffffff81f82052)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffff81086336)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:release_task
```
```
In kernel/kthread.c (ffffffff810a445d)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/time/timekeeping.c (ffffffff810fde5f)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_set_tai_offset
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
```
In kernel/time/tick-common.c (ffffffff811037e2)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff8110549b)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
  - kernel/time/tick-sched.c:tick_do_update_jiffies64
  - kernel/time/tick-sched.c:tick_do_update_jiffies64
```
```
In kernel/cpuset.c (ffffffff811235b1)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/memory_hotplug.c (ffffffff8120e843)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:resize_zone
```
```
In fs/dcache.c (ffffffff8124d13b)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:dentry_update_name_case
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/namespace.c (ffffffff812587f5)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_kern_mount
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs_struct.c (ffffffff812697f8)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/userfaultfd.c (ffffffff8128279d)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
```
```
In block/badblocks.c (ffffffff81412e5e)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
```
```
In lib/flex_proportions.c (ffffffff8142fc7e)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
```
```
In drivers/dma-buf/reservation.c (ffffffff815fc810)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8164c48a)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_phy_update_state
```
```
In net/core/dev.c (ffffffff81785a85)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
```
```
In net/core/neighbour.c (ffffffff81792361)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_update
```
```
In net/sched/sch_generic.c (ffffffff817ae41e)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/inetpeer.c (ffffffff817c4279)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
```
```
In net/ipv4/tcp_metrics.c (ffffffff817efb14)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/inet_fragment.c (ffffffff8180f8a1)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81813882)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
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
In init/main.c (ffffffff81fbe0d7)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffff8108b2a6)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:release_task
```
```
In kernel/kthread.c (ffffffff810a9e79)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/time/timekeeping.c (ffffffff81100c4f)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_set_tai_offset
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
```
In kernel/time/tick-common.c (ffffffff8110aed2)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff8110cbe6)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In kernel/cpuset.c (ffffffff8112b35a)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/memory_hotplug.c (ffffffff8122087d)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:resize_zone
```
```
In fs/dcache.c (ffffffff812601fb)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:dentry_update_name_case
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/namespace.c (ffffffff8126bcb3)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_kern_mount
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs_struct.c (ffffffff8127c7a8)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/userfaultfd.c (ffffffff812962ba)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
```
```
In block/badblocks.c (ffffffff8142e442)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
```
```
In lib/flex_proportions.c (ffffffff8144beae)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
```
```
In drivers/dma-buf/reservation.c (ffffffff8162aba0)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8167e19a)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_phy_update_state
```
```
In net/core/gen_estimator.c (ffffffff817a4120)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/dev.c (ffffffff817b304c)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
```
```
In net/core/neighbour.c (ffffffff817bfc31)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_update
```
```
In net/sched/sch_generic.c (ffffffff817ddaae)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/inetpeer.c (ffffffff817f3d99)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
```
```
In net/ipv4/tcp_metrics.c (ffffffff8182051f)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/inet_fragment.c (ffffffff81840df1)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81844d86)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff818507a7)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81856794)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
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
In init/main.c (ffffffff8209e1c1)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffff81088022)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:release_task
```
```
In kernel/kthread.c (ffffffff810a6a99)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/time/timekeeping.c (ffffffff81102d8f)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
```
In kernel/time/tick-common.c (ffffffff8110cdd2)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff8110eac6)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In kernel/cgroup/cpuset.c (ffffffff8112c662)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/memory_hotplug.c (ffffffff818ff501)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:__remove_pages
```
```
In fs/dcache.c (ffffffff8126db31)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:dentry_update_name_case
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/namespace.c (ffffffff81279495)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs_struct.c (ffffffff81289eca)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/userfaultfd.c (ffffffff812a367b)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
```
```
In block/badblocks.c (ffffffff8143b697)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
```
```
In drivers/dma-buf/reservation.c (ffffffff81640320)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
```
```
In drivers/net/phy/fixed_phy.c (ffffffff816932e1)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_phy_update_state
```
```
In net/core/gen_estimator.c (ffffffff817c2270)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/dev.c (ffffffff817d0922)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
```
```
In net/core/neighbour.c (ffffffff817de2c1)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_update
```
```
In net/sched/sch_generic.c (ffffffff817fd189)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/inetpeer.c (ffffffff81814179)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
```
```
In net/ipv4/tcp_metrics.c (ffffffff81840a38)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/inet_fragment.c (ffffffff81862691)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff818668e6)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81874665)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff8187a08a)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In lib/flex_proportions.c (ffffffff818ec65e)
Location: include/linux/seqlock.h:231
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
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
In init/main.c (ffffffff826a418c)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffff8108edad)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:release_task
```
```
In kernel/kthread.c (ffffffff810ad208)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/time/timekeeping.c (ffffffff8110de6f)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
```
In kernel/time/tick-common.c (ffffffff81118082)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff8111a456)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In kernel/cgroup/cpuset.c (ffffffff81139492)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/memory_hotplug.c (ffffffff81989601)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:__remove_pages
```
```
In fs/dcache.c (ffffffff812905d1)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:dentry_update_name_case
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/namespace.c (ffffffff8129ae71)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs_struct.c (ffffffff812aca0a)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/userfaultfd.c (ffffffff812c6c12)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
```
```
In block/badblocks.c (ffffffff814676a7)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
```
```
In drivers/dma-buf/reservation.c (ffffffff816a8dd7)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
```
```
In drivers/net/phy/fixed_phy.c (ffffffff816fd1f1)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_phy_update_state
```
```
In net/core/gen_estimator.c (ffffffff8183bc8f)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/dev.c (ffffffff8184a3d3)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
```
```
In net/core/neighbour.c (ffffffff81858b21)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_update
```
```
In net/sched/sch_generic.c (ffffffff8187ab44)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/inetpeer.c (ffffffff81893812)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff818c01a8)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/inet_fragment.c (ffffffff818e27b1)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff818e6a86)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f4bcf)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff818fabba)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In lib/flex_proportions.c (ffffffff8197262e)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
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
In init/main.c (ffffffff826cd286)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffff810928a8)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
```
```
In kernel/kthread.c (ffffffff810b3f78)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/time/timekeeping.c (ffffffff8111982f)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In kernel/time/tick-common.c (ffffffff81124bb2)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff81126d96)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In kernel/cgroup/cpuset.c (ffffffff81148562)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/memory_hotplug.c (ffffffff819e5ed8)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:__remove_pages
```
```
In fs/dcache.c (ffffffff812b5b51)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:dentry_update_name_case
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/namespace.c (ffffffff812c1ff8)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:may_umount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs_struct.c (ffffffff812d45f1)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/userfaultfd.c (ffffffff812f0fcb)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
```
```
In block/badblocks.c (ffffffff8149b41f)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
```
```
In drivers/dma-buf/reservation.c (ffffffff816e5214)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
  - drivers/dma-buf/reservation.c:reservation_object_add_shared_fence
  - drivers/dma-buf/reservation.c:reservation_object_add_shared_fence
  - drivers/dma-buf/reservation.c:reservation_object_add_shared_fence
```
```
In net/core/gen_estimator.c (ffffffff81886415)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/dev.c (ffffffff81891c8c)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
```
```
In net/core/neighbour.c (ffffffff818a3fbd)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff818e7abf)
Location: include/linux/seqlock.h:232
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff81915cf7)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8193d5aa)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194b2e1)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff8195196e)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In lib/flex_proportions.c (ffffffff819cea5e)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
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
In init/main.c (ffffffff8288325c)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffff8109ab8c)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
```
```
In kernel/kthread.c (ffffffff810bd0c8)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/sched/psi.c (ffffffff810ef755)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
```
```
In kernel/time/timekeeping.c (ffffffff81124d2f)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
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
In kernel/time/tick-common.c (ffffffff811302b2)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff81132486)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In kernel/cgroup/cpuset.c (ffffffff81154082)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/memory_hotplug.c (ffffffff81a2126a)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:__remove_pages
```
```
In fs/dcache.c (ffffffff812cae61)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/namespace.c (ffffffff812d7298)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:may_umount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs_struct.c (ffffffff812e99c1)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/userfaultfd.c (ffffffff813046e7)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
```
```
In block/badblocks.c (ffffffff814b572f)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
```
```
In drivers/dma-buf/reservation.c (ffffffff81708c83)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
  - drivers/dma-buf/reservation.c:reservation_object_add_shared_fence
  - drivers/dma-buf/reservation.c:reservation_object_reserve_shared
```
```
In net/core/gen_estimator.c (ffffffff818a6b95)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/dev.c (ffffffff818b25e6)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
```
```
In net/core/neighbour.c (ffffffff818c741d)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff8191496f)
Location: include/linux/seqlock.h:232
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff819444a7)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8196d37a)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81981214)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_chain
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_chain
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_chain
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81986076)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In lib/flex_proportions.c (ffffffff81a07f1e)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
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
In init/main.c (ffffffff8289a2b2)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffff8109ee0a)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/kthread.c (ffffffff810c2f98)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/sched/psi.c (ffffffff810f6be9)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
```
```
In kernel/time/timekeeping.c (ffffffff8112f710)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
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
In kernel/time/tick-common.c (ffffffff8113ade2)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff8113cdf6)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In kernel/cgroup/cpuset.c (ffffffff811605d2)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/memory_hotplug.c (ffffffff81a91918)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
```
```
In fs/dcache.c (ffffffff812e85cd)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/namespace.c (ffffffff812f56fa)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:may_umount
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs_struct.c (ffffffff81308386)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/userfaultfd.c (ffffffff81326587)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
```
```
In block/badblocks.c (ffffffff814e3c6b)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
```
```
In drivers/dma-buf/reservation.c (ffffffff81744642)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
  - drivers/dma-buf/reservation.c:reservation_object_add_shared_fence
  - drivers/dma-buf/reservation.c:reservation_object_reserve_shared
```
```
In net/core/gen_estimator.c (ffffffff818f2014)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/dev.c (ffffffff818febb0)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
```
```
In net/core/neighbour.c (ffffffff81913af1)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff81976d90)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff819a8a6f)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff819d6ca3)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff819eaf7c)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_chain
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_chain
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_chain
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff819efe8c)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In lib/flex_proportions.c (ffffffff81a7786e)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
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
In init/main.c (ffffffff8289d297)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffff810a539a)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/kthread.c (ffffffff810c9568)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/sched/psi.c (ffffffff81102979)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
```
```
In kernel/time/timekeeping.c (ffffffff8113b6d0)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
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
In kernel/time/tick-common.c (ffffffff81146a12)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff81148b96)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In kernel/cgroup/cpuset.c (ffffffff8116c2a2)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/memory_hotplug.c (ffffffff81ac90b9)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In fs/dcache.c (ffffffff812fa15d)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/namespace.c (ffffffff8130727a)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:may_umount
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs_struct.c (ffffffff8131b426)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/userfaultfd.c (ffffffff81339317)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
```
```
In block/badblocks.c (ffffffff814fd02b)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
```
```
In block/blk-iocost.c (ffffffff81510f2f)
Location: include/linux/seqlock.h:232
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8176880e)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In net/core/gen_estimator.c (ffffffff81923f64)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/dev.c (ffffffff81930ef0)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
```
```
In net/core/neighbour.c (ffffffff81946161)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff819ad720)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff819df74f)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81a0d793)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a21f7c)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_chain
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_chain
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_chain
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81a26d5c)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In lib/flex_proportions.c (ffffffff81aaec5e)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
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
In init/main.c (ffffffff82cc38df)
Location: include/linux/seqlock.h:253
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffff810ad0f1)
Location: include/linux/seqlock.h:253
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In kernel/kthread.c (ffffffff810d195d)
Location: include/linux/seqlock.h:253
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/sched/psi.c (ffffffff8110d999)
Location: include/linux/seqlock.h:253
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_group_change
```
```
In kernel/time/timekeeping.c (ffffffff8114a720)
Location: include/linux/seqlock.h:253
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
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
In kernel/time/tick-common.c (ffffffff811568d2)
Location: include/linux/seqlock.h:253
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff81158a26)
Location: include/linux/seqlock.h:253
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In kernel/cgroup/cpuset.c (ffffffff8117e1d2)
Location: include/linux/seqlock.h:253
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/memory_hotplug.c (ffffffff81bc17d9)
Location: include/linux/seqlock.h:253
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:shrink_zone_span
```
```
In fs/dcache.c (ffffffff8133321d)
Location: include/linux/seqlock.h:253
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
In fs/namespace.c (ffffffff813404c3)
Location: include/linux/seqlock.h:253
Inline: True
Inline callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
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
In fs/fs_struct.c (ffffffff813550d9)
Location: include/linux/seqlock.h:253
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/userfaultfd.c (ffffffff81373ee4)
Location: include/linux/seqlock.h:253
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
```
In block/badblocks.c (ffffffff8155cc26)
Location: include/linux/seqlock.h:253
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
```
```
In block/blk-iocost.c (ffffffff81571491)
Location: include/linux/seqlock.h:253
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_start_period
```
```
In lib/flex_proportions.c (ffffffff815e89c1)
Location: include/linux/seqlock.h:253
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81828933)
Location: include/linux/seqlock.h:253
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In net/core/gen_estimator.c (ffffffff819f7b15)
Location: include/linux/seqlock.h:253
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/dev.c (ffffffff81a06161)
Location: include/linux/seqlock.h:253
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/core/neighbour.c (ffffffff81a168c2)
Location: include/linux/seqlock.h:253
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff81a976b7)
Location: include/linux/seqlock.h:253
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff81accb97)
Location: include/linux/seqlock.h:253
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81afe6d5)
Location: include/linux/seqlock.h:253
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b13b89)
Location: include/linux/seqlock.h:253
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_bydst_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81b19d4c)
Location: include/linux/seqlock.h:253
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
</details>
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
In init/main.c (ffff800011431260)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In virt/kvm/eventfd.c (ffff8000100c1798)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - virt/kvm/eventfd.c:kvm_irqfd
  - virt/kvm/eventfd.c:irqfd_update
```
```
In kernel/exit.c (ffff8000100fb2b4)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/kthread.c (ffff8000101290ec)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/sched/psi.c (ffff8000101676f4)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
```
```
In kernel/time/timekeeping.c (ffff8000101a5990)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
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
In kernel/time/tick-common.c (ffff8000101b18f0)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffff8000101b4bc4)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In kernel/cgroup/cpuset.c (ffff8000101e10c8)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/memory_hotplug.c (ffff800010d9cd20)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In fs/dcache.c (ffff8000103a8d88)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/namespace.c (ffff8000103baae8)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/namespace.c:__arm64_sys_pivot_root
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:__arm64_sys_open_tree
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:may_umount
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs_struct.c (ffff8000103d2968)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/userfaultfd.c (ffff8000103f74e8)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
```
```
In block/badblocks.c (ffff8000105fef38)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
```
```
In block/blk-iocost.c (ffff8000106143c0)
Location: include/linux/seqlock.h:232
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffff80001096906c)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In net/core/gen_estimator.c (ffff800010bbf7a8)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/dev.c (ffff800010bce5e0)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
```
```
In net/core/neighbour.c (ffff800010be62d0)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffff800010c5daa4)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffff800010c9313c)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffff800010cc7318)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/xfrm/xfrm_policy.c (ffff800010cde238)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffff800010ce7a50)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In lib/flex_proportions.c (ffff800010d88374)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
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
In init/main.c (c1501278)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (c03592f0)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/kthread.c (c037b678)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/sched/psi.c (c03b454c)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
```
```
In kernel/time/timekeeping.c (c03f0994)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
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
In kernel/time/tick-common.c (c03fbf8c)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (c03fe510)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In kernel/cgroup/rstat.c (c041c6d8)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:__cgroup_account_cputime_field
  - kernel/cgroup/rstat.c:__cgroup_account_cputime
```
```
In kernel/cgroup/cpuset.c (c0421d4c)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/seccomp.c (c0448084)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/bpf_trace.c (c047fa80)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_trace_run12
  - kernel/trace/bpf_trace.c:bpf_trace_run11
  - kernel/trace/bpf_trace.c:bpf_trace_run10
  - kernel/trace/bpf_trace.c:bpf_trace_run9
  - kernel/trace/bpf_trace.c:bpf_trace_run8
  - kernel/trace/bpf_trace.c:bpf_trace_run7
  - kernel/trace/bpf_trace.c:bpf_trace_run6
  - kernel/trace/bpf_trace.c:bpf_trace_run5
  - kernel/trace/bpf_trace.c:bpf_trace_run4
  - kernel/trace/bpf_trace.c:bpf_trace_run3
  - kernel/trace/bpf_trace.c:bpf_trace_run2
  - kernel/trace/bpf_trace.c:bpf_trace_run1
```
```
In kernel/bpf/cgroup.c (c04bd6d4)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In kernel/events/core.c (c04c0764)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/events/core.c:bpf_overflow_handler
```
```
In mm/filemap.c (c04e0a08)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In mm/truncate.c (c04ef694)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - mm/truncate.c:truncate_setsize
```
```
In mm/shmem.c (c04fe08c)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_setattr
```
```
In fs/dcache.c (c058a3b0)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/namespace.c (c0597c24)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:set_mount_attributes
  - fs/namespace.c:__se_sys_open_tree
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/libfs.c (c059dfe0)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/stack.c (c05ad14c)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/stack.c:fsstack_copy_inode_size
```
```
In fs/fs_struct.c (c05ad4d4)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/buffer.c (c05b3ec8)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
```
```
In fs/block_dev.c (c05b8a50)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/block_dev.c:bd_set_size
  - fs/block_dev.c:check_disk_size_change
```
```
In fs/userfaultfd.c (c05cb9c8)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
```
In fs/iomap/buffered-io.c (c05f44d4)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/iomap/direct-io.c (c05f5be0)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
```
In fs/ext4/extents.c (c062d7c4)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/inline.c (c063b9dc)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
```
```
In fs/ext4/inode.c (c064b120)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/ioctl.c (c064ca8c)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
```
```
In fs/ext4/migrate.c (c0659f88)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (c067d968)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
```
```
In fs/ext4/xattr.c (c0686054)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_write
```
```
In fs/ecryptfs/inode.c (c06b1a54)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_link
```
```
In fs/ecryptfs/mmap.c (c06b3d6c)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/ecryptfs/read_write.c (c06b421c)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/ecryptfs/crypto.c (c06b5d98)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_i_size_init
```
```
In fs/fuse/dir.c (c06c55a4)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (c06c9798)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (c06cd8b4)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes
```
```
In fs/efivarfs/file.c (c06d87d0)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (c06d8d1c)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In security/selinux/selinuxfs.c (c070b07c)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In block/ioctl.c (c07a35b4)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/badblocks.c (c07a9e4c)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
```
```
In block/blk-iocost.c (c07beff4)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_start_period
```
```
In drivers/pci/proc.c (c089081c)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
```
```
In drivers/dma-buf/dma-resv.c (c0a3fc38)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In drivers/net/loopback.c (c0ab8530)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (c0ac6a50)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In drivers/net/ethernet/ti/cpsw.c (c0ad3170)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler
```
```
In drivers/net/ppp/ppp_generic.c (c0ade134)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/md/dm.c (c0be05f8)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
```
```
In net/socket.c (c0cc4914)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
```
```
In net/core/sock.c (c0cc8374)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_gettstamp
```
```
In net/core/gen_estimator.c (c0cdb260)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/flow_dissector.c (c0cde934)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/core/flow_dissector.c:bpf_flow_dissect
```
```
In net/core/dev.c (c0ced77c)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
```
```
In net/core/neighbour.c (c0cfe86c)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
```
```
In net/core/filter.c (c0d1c858)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (c0d1e3f8)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/skmsg.c (c0d2686c)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_bpf_run
  - net/core/skmsg.c:sk_psock_msg_verdict
```
```
In net/core/drop_monitor.c (c0d32848)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/ptp_classifier.c (c0d34d2c)
Location: include/linux/seqlock.h:232
Inline: True
```
```
In net/core/lwt_bpf.c (c0d36240)
Location: include/linux/seqlock.h:232
Inline: True
```
```
In net/core/devlink.c (c0d39d78)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_stats_update
```
```
In net/sched/sch_generic.c (c0d4a0e0)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/bpf/test_run.c (c0d62bd4)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ipv4/route.c (c0d66c00)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_error
```
```
In net/ipv4/inetpeer.c (c0d6ce64)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_input.c (c0d6d8e0)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_fragment.c (c0d6f54c)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (c0d6fd3c)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward_finish
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_output.c (c0d753a4)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/ip_sockglue.c (c0d78884)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/inet_connection_sock.c (c0d7b528)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (c0d9b980)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/tcp_metrics.c (c0da1ae4)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/datagram.c (c0da4888)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (c0da57f8)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (c0daabac)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (c0dcc45c)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ip_tunnel_core.c (c0dcded0)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/sysctl_net_ipv4.c (c0dd2598)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (c0dd7650)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/xfrm/xfrm_policy.c (c0de843c)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_chain
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_chain
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (c0dee12c)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/ipv6/ip6_output.c (c0dfeb28)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_append_data
  - net/ipv6/ip6_output.c:__ip6_append_data
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (c0e05478)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/route.c (c0e12d40)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_pkt_drop
```
```
In net/ipv6/udp.c (c0e2a738)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (c0e2dd98)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/icmp.c (c0e2f53c)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/mcast.c (c0e33b4c)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/reassembly.c (c0e37af0)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/exthdrs.c (c0e3d104)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/datagram.c (c0e40b20)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/ip6mr.c (c0e469c8)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/netfilter.c (c0e4b7a4)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_local.c (c0e525b0)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
```
In net/packet/af_packet.c (c0e59ef4)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/8021q/vlan_core.c (c0e5ff00)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In lib/flex_proportions.c (c0e8313c)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
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
In init/main.c (c0000000013444dc)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (c0000000001426f4)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/kthread.c (c000000000173954)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/sched/psi.c (c0000000001bf404)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
```
```
In kernel/time/timekeeping.c (c00000000020786c)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
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
In kernel/time/tick-common.c (c00000000021674c)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (c00000000021a3c4)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In kernel/cgroup/cpuset.c (c00000000024f088)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/memory_hotplug.c (c00000000042fbb0)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In fs/dcache.c (c0000000004a3958)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/namespace.c (c0000000004b836c)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:__se_sys_open_tree
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:may_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs_struct.c (c0000000004d541c)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/userfaultfd.c (c0000000005010a0)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
```
In block/badblocks.c (c000000000798980)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
```
```
In block/blk-iocost.c (c0000000007b3d80)
Location: include/linux/seqlock.h:232
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (c000000000a21f90)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In net/core/gen_estimator.c (c000000000c98b20)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/dev.c (c000000000cac244)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
```
```
In net/core/neighbour.c (c000000000cc7854)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (c000000000d5ffb0)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (c000000000da34a0)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (c000000000de3fd8)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/xfrm/xfrm_policy.c (c000000000dfeee8)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_bydst_resize
```
```
In net/xfrm/xfrm_state.c (c000000000e08a8c)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In lib/flex_proportions.c (c000000000ec8924)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
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
In init/main.c (ffffffe000000f80)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffe0000c4f0c)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/kthread.c (ffffffe0000dff68)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/sched/psi.c (ffffffe000109c72)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
```
```
In kernel/time/timekeeping.c (ffffffe000131ce0)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In kernel/time/tick-common.c (ffffffe00013a176)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffe00013b0f8)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In kernel/cgroup/cpuset.c (ffffffe000157dea)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In fs/dcache.c (ffffffe00026f088)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/namespace.c (ffffffe00027cf1a)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:__se_sys_open_tree
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:may_umount
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs_struct.c (ffffffe00028db58)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/userfaultfd.c (ffffffe0002a8058)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
```
```
In block/badblocks.c (ffffffe00043a244)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
```
```
In block/blk-iocost.c (ffffffe00044bd56)
Location: include/linux/seqlock.h:232
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffe0005d4f68)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In net/core/gen_estimator.c (ffffffe00074d18e)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/dev.c (ffffffe0007589f8)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
```
```
In net/core/neighbour.c (ffffffe00076aff4)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffe0007c6308)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffe0007f2834)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffe00081b874)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082df62)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffe0008337d4)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In lib/flex_proportions.c (ffffffe0008b23f0)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
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
In init/main.c (ffffffff8288b297)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffff8109ecba)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/kthread.c (ffffffff810c38e8)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/sched/psi.c (ffffffff810fbc89)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
```
```
In kernel/time/timekeeping.c (ffffffff81133e80)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
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
In kernel/time/tick-common.c (ffffffff8113f1f2)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff811411b6)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In kernel/cgroup/cpuset.c (ffffffff811648c2)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/memory_hotplug.c (ffffffff81a67f29)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In fs/dcache.c (ffffffff812f273d)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/namespace.c (ffffffff812ff85a)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:may_umount
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs_struct.c (ffffffff81313a06)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/userfaultfd.c (ffffffff813318f7)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
```
```
In block/badblocks.c (ffffffff814f560b)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
```
```
In block/blk-iocost.c (ffffffff8150950f)
Location: include/linux/seqlock.h:232
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8171cefe)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In net/core/gen_estimator.c (ffffffff818c3f64)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/dev.c (ffffffff818d0ef0)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
```
```
In net/core/neighbour.c (ffffffff818e6131)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff8194d590)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff8197f5bf)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff819ad533)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c160c)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_chain
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_chain
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_chain
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff819c63ec)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In lib/flex_proportions.c (ffffffff81a4daae)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
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
In init/main.c (ffffffff8288921c)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffff8108d6f6)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/kthread.c (ffffffff810b2103)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/sched/cputime.c (ffffffff810c8a00)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/sched/cputime.c:vtime_init_idle
  - kernel/sched/cputime.c:arch_vtime_task_switch
  - kernel/sched/cputime.c:arch_vtime_task_switch
  - kernel/sched/cputime.c:vtime_guest_exit
  - kernel/sched/cputime.c:vtime_guest_enter
  - kernel/sched/cputime.c:vtime_user_exit
  - kernel/sched/cputime.c:vtime_user_enter
```
```
In kernel/sched/psi.c (ffffffff810ebea9)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
```
```
In kernel/time/timekeeping.c (ffffffff811268e0)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
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
In kernel/time/tick-common.c (ffffffff81131cc2)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff81134026)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In kernel/cgroup/cpuset.c (ffffffff81157b0c)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/memory_hotplug.c (ffffffff81a249e9)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In fs/dcache.c (ffffffff812e336d)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/namespace.c (ffffffff812f047a)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:may_umount
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs_struct.c (ffffffff81304616)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/userfaultfd.c (ffffffff813224cb)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
```
```
In block/badblocks.c (ffffffff814e5b1b)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
```
```
In block/blk-iocost.c (ffffffff814f99bf)
Location: include/linux/seqlock.h:232
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff816f635e)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In net/core/gen_estimator.c (ffffffff8187dea4)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/dev.c (ffffffff8188ada8)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
```
```
In net/core/neighbour.c (ffffffff8189ff71)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff81907080)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff8193907f)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81969b63)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197e3fc)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_chain
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_chain
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_chain
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff819831dc)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In lib/flex_proportions.c (ffffffff81a0abb1)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
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
In init/main.c (ffffffff8289e297)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffff8109ec6a)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/kthread.c (ffffffff810c2e38)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/sched/psi.c (ffffffff810f8e49)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
```
```
In kernel/time/timekeeping.c (ffffffff81131ba0)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
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
In kernel/time/tick-common.c (ffffffff8113cee2)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff8113f066)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In kernel/cgroup/cpuset.c (ffffffff81162692)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/memory_hotplug.c (ffffffff81ad4339)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In fs/dcache.c (ffffffff812f054d)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/namespace.c (ffffffff812fd64a)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:may_umount
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs_struct.c (ffffffff813117f6)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/userfaultfd.c (ffffffff8132f3c7)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
```
```
In block/badblocks.c (ffffffff814f169b)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
```
```
In block/blk-iocost.c (ffffffff8150559f)
Location: include/linux/seqlock.h:232
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8175bcce)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In net/core/gen_estimator.c (ffffffff81914f64)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/dev.c (ffffffff81921ef0)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
```
```
In net/core/neighbour.c (ffffffff81937161)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
```
```
In net/netfilter/nf_conntrack_core.c (ffffffff819a07ee)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_hash_resize
```
```
In net/ipv4/inetpeer.c (ffffffff819b7d60)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff819e9d8f)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81a17dd3)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2c08c)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_chain
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_chain
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_chain
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81a30e6c)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In lib/flex_proportions.c (ffffffff81ab9e9e)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
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
In init/main.c (ffffffff8289e29e)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffff810a6b81)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/kthread.c (ffffffff810cb278)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/sched/psi.c (ffffffff81103f99)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
```
```
In kernel/time/timekeeping.c (ffffffff8113e5c0)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
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
In kernel/time/tick-common.c (ffffffff811499d2)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff8114b6d8)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In kernel/cgroup/cpuset.c (ffffffff8116fc12)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/memory_hotplug.c (ffffffff81ae081d)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In fs/dcache.c (ffffffff813016d6)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/namespace.c (ffffffff8130e9a8)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:may_umount
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs_struct.c (ffffffff81323043)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/userfaultfd.c (ffffffff81341475)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
```
```
In block/badblocks.c (ffffffff8150a6fb)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
```
```
In block/blk-iocost.c (ffffffff8151eedf)
Location: include/linux/seqlock.h:232
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81777369)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In net/core/gen_estimator.c (ffffffff819360e4)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/dev.c (ffffffff81943bf1)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
```
```
In net/core/neighbour.c (ffffffff81958938)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff819c15e5)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff819f3ba9)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81a22873)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a3775c)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_chain
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_chain
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_chain
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3c76c)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In lib/flex_proportions.c (ffffffff81ac62ee)
Location: include/linux/seqlock.h:232
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
```
</details>
</li>
</ul>

## Differences

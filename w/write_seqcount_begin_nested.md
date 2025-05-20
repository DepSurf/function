# Function: <code>write_seqcount_begin_nested</code>

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
In init/main.c (ffffffff81f5a091)
Location: include/linux/seqlock.h:371
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffff81082521)
Location: include/linux/seqlock.h:371
Inline: True
Inline callers:
  - kernel/exit.c:release_task
  - kernel/exit.c:wait_consider_task
```
```
In kernel/kthread.c (ffffffff810a0d6d)
Location: include/linux/seqlock.h:371
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/time/timekeeping.c (ffffffff810f4ffa)
Location: include/linux/seqlock.h:371
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
In kernel/time/tick-common.c (ffffffff810fc483)
Location: include/linux/seqlock.h:371
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff810fe0e5)
Location: include/linux/seqlock.h:371
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
  - kernel/time/tick-sched.c:tick_do_update_jiffies64
```
```
In kernel/cpuset.c (ffffffff8111b68c)
Location: include/linux/seqlock.h:371
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff81208f46)
Location: include/linux/seqlock.h:371
Inline: True
Inline callers:
  - mm/memory_hotplug.c:resize_zone
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:__remove_pages
```
```
In fs/dcache.c (ffffffff81222cdb)
Location: include/linux/seqlock.h:371
Inline: True
Inline callers:
  - fs/dcache.c:dentry_update_name_case
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_move
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:d_exchange
```
```
In fs/namespace.c (ffffffff8122bbb5)
Location: include/linux/seqlock.h:371
Inline: True
Inline callers:
  - fs/namespace.c:may_umount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:vfs_kern_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:may_umount_tree
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
In fs/fs_struct.c (ffffffff8124135c)
Location: include/linux/seqlock.h:371
Inline: True
Inline callers:
  - fs/fs_struct.c:set_fs_root
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/userfaultfd.c (ffffffff81259d51)
Location: include/linux/seqlock.h:371
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
```
```
In lib/flex_proportions.c (ffffffff813e986b)
Location: include/linux/seqlock.h:371
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
```
```
In drivers/dma-buf/reservation.c (ffffffff815a54c4)
Location: include/linux/seqlock.h:371
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
```
```
In drivers/md/md.c (ffffffff8168ec03)
Location: include/linux/seqlock.h:371
Inline: True
Inline callers:
  - drivers/md/md.c:md_set_badblocks
  - drivers/md/md.c:md_clear_badblocks
```
```
In net/core/dev.c (ffffffff8171d426)
Location: include/linux/seqlock.h:371
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
```
```
In net/core/neighbour.c (ffffffff817287c6)
Location: include/linux/seqlock.h:371
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff81757f9b)
Location: include/linux/seqlock.h:371
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
```
```
In net/ipv4/tcp_metrics.c (ffffffff817825f3)
Location: include/linux/seqlock.h:371
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/inet_fragment.c (ffffffff817a1bca)
Location: include/linux/seqlock.h:371
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff817a55f8)
Location: include/linux/seqlock.h:371
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
In init/main.c (ffffffff81f82045)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffff810860fc)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:release_task
```
```
In kernel/kthread.c (ffffffff810a444e)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/time/timekeeping.c (ffffffff810fde49)
Location: include/linux/seqlock.h:374
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
In kernel/time/tick-common.c (ffffffff811037c3)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff81105475)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
  - kernel/time/tick-sched.c:tick_do_update_jiffies64
```
```
In kernel/cpuset.c (ffffffff81123574)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/memory_hotplug.c (ffffffff8120e785)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:resize_zone
```
```
In fs/dcache.c (ffffffff8124d074)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:dentry_update_name_case
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff8125873b)
Location: include/linux/seqlock.h:374
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
  - fs/namespace.c:may_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_kern_mount
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs_struct.c (ffffffff81269885)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/userfaultfd.c (ffffffff81282759)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
```
```
In block/badblocks.c (ffffffff81412d1e)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
```
```
In lib/flex_proportions.c (ffffffff8142fc4b)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
```
```
In drivers/dma-buf/reservation.c (ffffffff815fc7f8)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8164c43d)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_phy_update_state
```
```
In net/core/dev.c (ffffffff81785cf6)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
```
```
In net/core/neighbour.c (ffffffff8179231c)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff817c424b)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
```
```
In net/ipv4/tcp_metrics.c (ffffffff817efab3)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/inet_fragment.c (ffffffff8180f88a)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81813874)
Location: include/linux/seqlock.h:374
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
In init/main.c (ffffffff81fbe0bc)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffff8108b06c)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:release_task
```
```
In kernel/kthread.c (ffffffff810a9dc4)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/time/timekeeping.c (ffffffff81100c39)
Location: include/linux/seqlock.h:374
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
In kernel/time/tick-common.c (ffffffff8110aeb3)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff8110cbc5)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In kernel/cpuset.c (ffffffff8112b261)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/memory_hotplug.c (ffffffff812207c5)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:resize_zone
```
```
In fs/dcache.c (ffffffff81260134)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:dentry_update_name_case
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff8126bbcc)
Location: include/linux/seqlock.h:374
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
  - fs/namespace.c:may_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_kern_mount
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs_struct.c (ffffffff8127c835)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/userfaultfd.c (ffffffff81296276)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
```
```
In block/badblocks.c (ffffffff8142e1ee)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
```
```
In lib/flex_proportions.c (ffffffff8144be7b)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
```
```
In drivers/dma-buf/reservation.c (ffffffff8162ab88)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8167e14d)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_phy_update_state
```
```
In net/core/gen_estimator.c (ffffffff817a40ee)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/dev.c (ffffffff817b32b6)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
```
```
In net/core/neighbour.c (ffffffff817bfbec)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff817f3d6b)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
```
```
In net/ipv4/tcp_metrics.c (ffffffff818204bf)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/inet_fragment.c (ffffffff81840dda)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81844d7b)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81850509)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff818565c8)
Location: include/linux/seqlock.h:374
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
In init/main.c (ffffffff8209e1a6)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffff81087e08)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:release_task
```
```
In kernel/kthread.c (ffffffff810a69e4)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/time/timekeeping.c (ffffffff81102d79)
Location: include/linux/seqlock.h:374
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
In kernel/time/tick-common.c (ffffffff8110cdb3)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff8110eaa5)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In kernel/cgroup/cpuset.c (ffffffff8112c57a)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/memory_hotplug.c (ffffffff818ff4c7)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:__remove_pages
```
```
In fs/dcache.c (ffffffff8126da5b)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:dentry_update_name_case
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff812793a1)
Location: include/linux/seqlock.h:374
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
  - fs/namespace.c:may_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs_struct.c (ffffffff81289eaf)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/userfaultfd.c (ffffffff812a363a)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
```
```
In block/badblocks.c (ffffffff8143b4fe)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
```
```
In drivers/dma-buf/reservation.c (ffffffff8164030a)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8169328e)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_phy_update_state
```
```
In net/core/gen_estimator.c (ffffffff817c223e)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/dev.c (ffffffff817d1c24)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
```
```
In net/core/neighbour.c (ffffffff817de277)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff8181414b)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
```
```
In net/ipv4/tcp_metrics.c (ffffffff818409dc)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/inet_fragment.c (ffffffff8186267a)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff818668db)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81874388)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81879ed8)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In lib/flex_proportions.c (ffffffff818ec62b)
Location: include/linux/seqlock.h:374
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
In init/main.c (ffffffff826a4171)
Location: include/linux/seqlock.h:375
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffff8108eb93)
Location: include/linux/seqlock.h:375
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:release_task
```
```
In kernel/kthread.c (ffffffff810ad154)
Location: include/linux/seqlock.h:375
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/time/timekeeping.c (ffffffff8110de59)
Location: include/linux/seqlock.h:375
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
In kernel/time/tick-common.c (ffffffff81118063)
Location: include/linux/seqlock.h:375
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff8111a435)
Location: include/linux/seqlock.h:375
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In kernel/cgroup/cpuset.c (ffffffff811393aa)
Location: include/linux/seqlock.h:375
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/memory_hotplug.c (ffffffff819895c7)
Location: include/linux/seqlock.h:375
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:__remove_pages
```
```
In fs/dcache.c (ffffffff812904fb)
Location: include/linux/seqlock.h:375
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:dentry_update_name_case
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff8129bde1)
Location: include/linux/seqlock.h:375
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
  - fs/namespace.c:may_umount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs_struct.c (ffffffff812ac9ef)
Location: include/linux/seqlock.h:375
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/userfaultfd.c (ffffffff812c6bce)
Location: include/linux/seqlock.h:375
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
```
```
In block/badblocks.c (ffffffff8146750e)
Location: include/linux/seqlock.h:375
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
```
```
In drivers/dma-buf/reservation.c (ffffffff816a8dca)
Location: include/linux/seqlock.h:375
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
```
```
In drivers/net/phy/fixed_phy.c (ffffffff816fd19e)
Location: include/linux/seqlock.h:375
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_phy_update_state
```
```
In net/core/gen_estimator.c (ffffffff8183bc47)
Location: include/linux/seqlock.h:375
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/dev.c (ffffffff8184be84)
Location: include/linux/seqlock.h:375
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
```
```
In net/core/neighbour.c (ffffffff81858ad7)
Location: include/linux/seqlock.h:375
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff81893716)
Location: include/linux/seqlock.h:375
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff818c014c)
Location: include/linux/seqlock.h:375
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/inet_fragment.c (ffffffff818e279a)
Location: include/linux/seqlock.h:375
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff818e6a7b)
Location: include/linux/seqlock.h:375
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f48f8)
Location: include/linux/seqlock.h:375
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff818faa08)
Location: include/linux/seqlock.h:375
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In lib/flex_proportions.c (ffffffff819725fb)
Location: include/linux/seqlock.h:375
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
In init/main.c (ffffffff826cd26b)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffff8109268e)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
```
```
In kernel/kthread.c (ffffffff810b3ec4)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/time/timekeeping.c (ffffffff81119819)
Location: include/linux/seqlock.h:374
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
In kernel/time/tick-common.c (ffffffff81124b93)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff81126d75)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In kernel/cgroup/cpuset.c (ffffffff8114847a)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/memory_hotplug.c (ffffffff819e5e9a)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:__remove_pages
```
```
In fs/dcache.c (ffffffff812b5b1e)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:dentry_update_name_case
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff812c1f12)
Location: include/linux/seqlock.h:374
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
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:may_umount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs_struct.c (ffffffff812d45d3)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/userfaultfd.c (ffffffff812f0f89)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
```
```
In block/badblocks.c (ffffffff8149b382)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
```
```
In drivers/dma-buf/reservation.c (ffffffff816e5207)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
  - drivers/dma-buf/reservation.c:reservation_object_add_shared_fence
  - drivers/dma-buf/reservation.c:reservation_object_add_shared_fence
```
```
In net/core/gen_estimator.c (ffffffff818863f9)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/dev.c (ffffffff818961da)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
```
```
In net/core/neighbour.c (ffffffff818a3f6e)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff818e7a66)
Location: include/linux/seqlock.h:374
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff81915c9b)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8193d59f)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194b1bc)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff819517b8)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In lib/flex_proportions.c (ffffffff819cea2b)
Location: include/linux/seqlock.h:374
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
In init/main.c (ffffffff82883241)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffff8109a972)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
```
```
In kernel/kthread.c (ffffffff810bd014)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/sched/psi.c (ffffffff810ef742)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
```
```
In kernel/time/timekeeping.c (ffffffff81124d19)
Location: include/linux/seqlock.h:374
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
In kernel/time/tick-common.c (ffffffff81130293)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff81132465)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In kernel/cgroup/cpuset.c (ffffffff81153f9a)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/memory_hotplug.c (ffffffff81a21218)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:__remove_pages
```
```
In fs/dcache.c (ffffffff812cae2e)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff812d71b2)
Location: include/linux/seqlock.h:374
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
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:may_umount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs_struct.c (ffffffff812e99a3)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/userfaultfd.c (ffffffff813046a9)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
```
```
In block/badblocks.c (ffffffff814b5692)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
```
```
In drivers/dma-buf/reservation.c (ffffffff81708c76)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
  - drivers/dma-buf/reservation.c:reservation_object_add_shared_fence
  - drivers/dma-buf/reservation.c:reservation_object_reserve_shared
```
```
In net/core/gen_estimator.c (ffffffff818a6b79)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/dev.c (ffffffff818b844a)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
```
```
In net/core/neighbour.c (ffffffff818c73d2)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff81914916)
Location: include/linux/seqlock.h:374
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff8194444b)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8196d36f)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81980ff9)
Location: include/linux/seqlock.h:374
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
In net/xfrm/xfrm_state.c (ffffffff81985be9)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In lib/flex_proportions.c (ffffffff81a07eeb)
Location: include/linux/seqlock.h:374
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
In init/main.c (ffffffff8289a297)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffff8109ebdc)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/kthread.c (ffffffff810c2ee4)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/sched/psi.c (ffffffff810f6bd6)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
```
```
In kernel/time/timekeeping.c (ffffffff8112f6fa)
Location: include/linux/seqlock.h:374
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
In kernel/time/tick-common.c (ffffffff8113adc3)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff8113cdd5)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In kernel/cgroup/cpuset.c (ffffffff811604ea)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/memory_hotplug.c (ffffffff81a918cb)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:__remove_pages
```
```
In fs/dcache.c (ffffffff812e84d9)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff812f560e)
Location: include/linux/seqlock.h:374
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
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:may_umount
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs_struct.c (ffffffff8130835e)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/userfaultfd.c (ffffffff81326545)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
```
```
In block/badblocks.c (ffffffff814e3bd2)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
```
```
In drivers/dma-buf/reservation.c (ffffffff81744632)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
  - drivers/dma-buf/reservation.c:reservation_object_add_shared_fence
  - drivers/dma-buf/reservation.c:reservation_object_reserve_shared
```
```
In net/core/gen_estimator.c (ffffffff818f1ff4)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/dev.c (ffffffff8190462d)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
```
```
In net/core/neighbour.c (ffffffff81913aa6)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff81976d39)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff819a8a13)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff819d6c98)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff819eadbf)
Location: include/linux/seqlock.h:374
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
In net/xfrm/xfrm_state.c (ffffffff819efa08)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In lib/flex_proportions.c (ffffffff81a7783b)
Location: include/linux/seqlock.h:374
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
In init/main.c (ffffffff8289d27c)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffff810a516c)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/kthread.c (ffffffff810c94b4)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/sched/psi.c (ffffffff81102966)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
```
```
In kernel/time/timekeeping.c (ffffffff8113b6ba)
Location: include/linux/seqlock.h:374
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
In kernel/time/tick-common.c (ffffffff811469f3)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff81148b75)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In kernel/cgroup/cpuset.c (ffffffff8116c1ba)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/memory_hotplug.c (ffffffff81ac906b)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In fs/dcache.c (ffffffff812fa069)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff8130718e)
Location: include/linux/seqlock.h:374
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
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:may_umount
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs_struct.c (ffffffff8131b3fe)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/userfaultfd.c (ffffffff813392d5)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
```
```
In block/badblocks.c (ffffffff814fcf92)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
```
```
In block/blk-iocost.c (ffffffff81510f16)
Location: include/linux/seqlock.h:374
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff817687fe)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In net/core/gen_estimator.c (ffffffff81923f44)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/dev.c (ffffffff81936c9d)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
```
```
In net/core/neighbour.c (ffffffff81946116)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff819ad6c9)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff819df6f3)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81a0d788)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a21dbf)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_chain
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_chain
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_chain
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81a268d8)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In lib/flex_proportions.c (ffffffff81aaec2b)
Location: include/linux/seqlock.h:374
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
In init/main.c (ffffffff82cc38c4)
Location: include/linux/seqlock.h:405
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffff810aceb8)
Location: include/linux/seqlock.h:405
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In kernel/kthread.c (ffffffff810d18a6)
Location: include/linux/seqlock.h:405
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/sched/psi.c (ffffffff8110d986)
Location: include/linux/seqlock.h:405
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_group_change
```
```
In kernel/time/timekeeping.c (ffffffff8114a70a)
Location: include/linux/seqlock.h:405
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
In kernel/time/tick-common.c (ffffffff811568b3)
Location: include/linux/seqlock.h:405
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff81158a05)
Location: include/linux/seqlock.h:405
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In kernel/cgroup/cpuset.c (ffffffff8117e0ea)
Location: include/linux/seqlock.h:405
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/memory_hotplug.c (ffffffff81bc178b)
Location: include/linux/seqlock.h:405
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:shrink_zone_span
```
```
In fs/dcache.c (ffffffff81333129)
Location: include/linux/seqlock.h:405
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff813404b4)
Location: include/linux/seqlock.h:405
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
  - fs/namespace.c:may_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs_struct.c (ffffffff813550b0)
Location: include/linux/seqlock.h:405
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/userfaultfd.c (ffffffff81373eab)
Location: include/linux/seqlock.h:405
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
```
In block/badblocks.c (ffffffff8155cac2)
Location: include/linux/seqlock.h:405
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
```
```
In block/blk-iocost.c (ffffffff81571476)
Location: include/linux/seqlock.h:405
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_start_period
```
```
In lib/flex_proportions.c (ffffffff815e898b)
Location: include/linux/seqlock.h:405
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81828927)
Location: include/linux/seqlock.h:405
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In net/core/gen_estimator.c (ffffffff819f7af5)
Location: include/linux/seqlock.h:405
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/neighbour.c (ffffffff81a16877)
Location: include/linux/seqlock.h:405
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff81a97659)
Location: include/linux/seqlock.h:405
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff81accb58)
Location: include/linux/seqlock.h:405
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81afe6ca)
Location: include/linux/seqlock.h:405
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b139a3)
Location: include/linux/seqlock.h:405
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_bydst_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81b19cc8)
Location: include/linux/seqlock.h:405
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
In init/main.c (ffff80001143124c)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In virt/kvm/eventfd.c (ffff8000100c1784)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - virt/kvm/eventfd.c:kvm_irqfd
  - virt/kvm/eventfd.c:irqfd_update
```
```
In kernel/exit.c (ffff8000100fb0c0)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/kthread.c (ffff8000101290d8)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/sched/psi.c (ffff8000101676e0)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
```
```
In kernel/time/timekeeping.c (ffff8000101a5968)
Location: include/linux/seqlock.h:374
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
In kernel/time/tick-common.c (ffff8000101b18c0)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffff8000101b4b98)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In kernel/cgroup/cpuset.c (ffff8000101e1094)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/memory_hotplug.c (ffff800010d9ccc8)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In fs/dcache.c (ffff8000103a8cc4)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffff8000103ba9f8)
Location: include/linux/seqlock.h:374
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
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:may_umount
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs_struct.c (ffff8000103d2938)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/userfaultfd.c (ffff8000103f74a8)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
```
```
In block/badblocks.c (ffff8000105feea0)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
```
```
In block/blk-iocost.c (ffff8000106143a0)
Location: include/linux/seqlock.h:374
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffff800010969054)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In net/core/gen_estimator.c (ffff800010bbf788)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/dev.c (ffff800010bd53f0)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
```
```
In net/core/neighbour.c (ffff800010be62a4)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffff800010c5da54)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffff800010c930e0)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffff800010cc7304)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/xfrm/xfrm_policy.c (ffff800010cde188)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffff800010ce7650)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In lib/flex_proportions.c (ffff800010d88334)
Location: include/linux/seqlock.h:374
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
In init/main.c (c150125c)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (c0358f08)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/kthread.c (c037b65c)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/sched/psi.c (c03b4538)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
```
```
In kernel/time/timekeeping.c (c03f0964)
Location: include/linux/seqlock.h:374
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
In kernel/time/tick-common.c (c03fbf50)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (c03fe4e0)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In kernel/cgroup/rstat.c (c041c6a0)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:__cgroup_account_cputime_field
  - kernel/cgroup/rstat.c:__cgroup_account_cputime
```
```
In kernel/cgroup/cpuset.c (c0421d24)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/seccomp.c (c0448030)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/bpf_trace.c (c047fa34)
Location: include/linux/seqlock.h:374
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
In kernel/bpf/cgroup.c (c04bd680)
Location: include/linux/seqlock.h:374
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
In kernel/events/core.c (c04c0714)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/events/core.c:bpf_overflow_handler
```
```
In mm/filemap.c (c04e09f0)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In mm/truncate.c (c04ef680)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - mm/truncate.c:truncate_setsize
```
```
In mm/shmem.c (c04fe078)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_setattr
```
```
In fs/dcache.c (c058a2dc)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (c0598754)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_pivot_root
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
  - fs/namespace.c:may_umount
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/libfs.c (c059dfcc)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/stack.c (c05ad138)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/stack.c:fsstack_copy_inode_size
```
```
In fs/fs_struct.c (c05ad4a4)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/buffer.c (c05b3eb4)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
```
```
In fs/block_dev.c (c05b8a38)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/block_dev.c:bd_set_size
  - fs/block_dev.c:check_disk_size_change
```
```
In fs/userfaultfd.c (c05cb990)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
```
In fs/iomap/buffered-io.c (c05f44c0)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/iomap/direct-io.c (c05f5bcc)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
```
In fs/ext4/extents.c (c062d7ac)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/inline.c (c063b9c4)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
```
```
In fs/ext4/inode.c (c064b10c)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/ioctl.c (c064ca70)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
```
```
In fs/ext4/migrate.c (c0659f74)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (c067d954)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
```
```
In fs/ext4/xattr.c (c068603c)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_write
```
```
In fs/ecryptfs/inode.c (c06b1a3c)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_link
```
```
In fs/ecryptfs/mmap.c (c06b3d58)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/ecryptfs/read_write.c (c06b4208)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/ecryptfs/crypto.c (c06b5d84)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_i_size_init
```
```
In fs/fuse/dir.c (c06c5590)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (c06c9784)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (c06cd8a0)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes
```
```
In fs/efivarfs/file.c (c06d87b8)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (c06d8d04)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In security/selinux/selinuxfs.c (c070b060)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In block/ioctl.c (c07a3598)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/badblocks.c (c07a9c14)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
```
```
In block/blk-iocost.c (c07befd4)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_start_period
```
```
In drivers/pci/proc.c (c0890808)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
```
```
In drivers/dma-buf/dma-resv.c (c0a3fc20)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In drivers/net/loopback.c (c0ab84f8)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (c0ac69fc)
Location: include/linux/seqlock.h:374
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
In drivers/net/ethernet/ti/cpsw.c (c0ad3118)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler
```
```
In drivers/net/ppp/ppp_generic.c (c0ade0f4)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/md/dm.c (c0be05d4)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
```
```
In net/socket.c (c0cc48fc)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
```
```
In net/core/sock.c (c0cc8358)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_gettstamp
```
```
In net/core/gen_estimator.c (c0cdb21c)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/flow_dissector.c (c0cde8f4)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/flow_dissector.c:bpf_flow_dissect
```
```
In net/core/dev.c (c0ced72c)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
```
```
In net/core/neighbour.c (c0cfe848)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
```
```
In net/core/filter.c (c0d1c818)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (c0d1e3a0)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/skmsg.c (c0d2682c)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_bpf_run
  - net/core/skmsg.c:sk_psock_msg_verdict
```
```
In net/core/drop_monitor.c (c0d32820)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/ptp_classifier.c (c0d34cec)
Location: include/linux/seqlock.h:374
Inline: True
```
```
In net/core/lwt_bpf.c (c0d361fc)
Location: include/linux/seqlock.h:374
Inline: True
```
```
In net/core/devlink.c (c0d39d40)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_stats_update
```
```
In net/sched/sch_generic.c (c0d4a08c)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/bpf/test_run.c (c0d62b7c)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ipv4/route.c (c0d66bd8)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_error
```
```
In net/ipv4/inetpeer.c (c0d6cdfc)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_input.c (c0d6d8a4)
Location: include/linux/seqlock.h:374
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
In net/ipv4/ip_fragment.c (c0d6f524)
Location: include/linux/seqlock.h:374
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
In net/ipv4/ip_forward.c (c0d6fd14)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward_finish
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_output.c (c0d7537c)
Location: include/linux/seqlock.h:374
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
In net/ipv4/ip_sockglue.c (c0d78868)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/inet_connection_sock.c (c0d7b500)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (c0d9b958)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/tcp_metrics.c (c0da1a7c)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/datagram.c (c0da4860)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (c0da57dc)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (c0daab90)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (c0dcc440)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ip_tunnel_core.c (c0dcde98)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/sysctl_net_ipv4.c (c0dd2584)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (c0dd7628)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/xfrm/xfrm_policy.c (c0de8368)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_chain
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_chain
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_chain
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (c0dedd2c)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/ipv6/ip6_output.c (c0dfeb00)
Location: include/linux/seqlock.h:374
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
In net/ipv6/ip6_input.c (c0e05450)
Location: include/linux/seqlock.h:374
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
In net/ipv6/route.c (c0e12d18)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_pkt_drop
```
```
In net/ipv6/udp.c (c0e2a71c)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (c0e2dd70)
Location: include/linux/seqlock.h:374
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
In net/ipv6/icmp.c (c0e2f514)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/mcast.c (c0e33b24)
Location: include/linux/seqlock.h:374
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
In net/ipv6/reassembly.c (c0e37ac8)
Location: include/linux/seqlock.h:374
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
In net/ipv6/exthdrs.c (c0e3d0dc)
Location: include/linux/seqlock.h:374
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
In net/ipv6/datagram.c (c0e40b04)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/ip6mr.c (c0e469a0)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_forward2
```
```
In net/ipv6/netfilter.c (c0e4b77c)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_local.c (c0e52560)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
```
In net/packet/af_packet.c (c0e59ed8)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/8021q/vlan_core.c (c0e5fe98)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In lib/flex_proportions.c (c0e830f8)
Location: include/linux/seqlock.h:374
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
In init/main.c (c0000000013444ac)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (c0000000001424ec)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/kthread.c (c000000000173924)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/sched/psi.c (c0000000001bf3f0)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
```
```
In kernel/time/timekeeping.c (c00000000020783c)
Location: include/linux/seqlock.h:374
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
In kernel/time/tick-common.c (c000000000216718)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (c00000000021a394)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In kernel/cgroup/cpuset.c (c00000000024f030)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/memory_hotplug.c (c00000000042fb4c)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In fs/dcache.c (c0000000004a3858)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (c0000000004b8294)
Location: include/linux/seqlock.h:374
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
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:may_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs_struct.c (c0000000004d53e8)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/userfaultfd.c (c000000000501040)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
```
In block/badblocks.c (c0000000007988c4)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
```
```
In block/blk-iocost.c (c0000000007b3d60)
Location: include/linux/seqlock.h:374
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (c000000000a21f78)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In net/core/gen_estimator.c (c000000000c98afc)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/dev.c (c000000000cb4880)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
```
```
In net/core/neighbour.c (c000000000cc7830)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (c000000000d5ff60)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (c000000000da3420)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (c000000000de3fc0)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/xfrm/xfrm_policy.c (c000000000dfebb0)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_bydst_resize
```
```
In net/xfrm/xfrm_state.c (c000000000e0858c)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In lib/flex_proportions.c (c000000000ec88e4)
Location: include/linux/seqlock.h:374
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
In init/main.c (ffffffe000000f6a)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffe0000c4d58)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/kthread.c (ffffffe0000dff52)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/sched/psi.c (ffffffe000109c5c)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
```
```
In kernel/time/timekeeping.c (ffffffe000131cac)
Location: include/linux/seqlock.h:374
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
In kernel/time/tick-common.c (ffffffe00013a138)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffe00013b0d0)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In kernel/cgroup/cpuset.c (ffffffe000157dc2)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In fs/dcache.c (ffffffe00026efe0)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffe00027ce38)
Location: include/linux/seqlock.h:374
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
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:may_umount
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs_struct.c (ffffffe00028db30)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/userfaultfd.c (ffffffe0002a8022)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
```
```
In block/badblocks.c (ffffffe00043a1c0)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
```
```
In block/blk-iocost.c (ffffffe00044bd38)
Location: include/linux/seqlock.h:374
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffe0005d4f52)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In net/core/gen_estimator.c (ffffffe00074d136)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/dev.c (ffffffe00075ee98)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
```
```
In net/core/neighbour.c (ffffffe00076afd2)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffe0007c62d0)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffe0007f27d6)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffe00081b85e)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082de16)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffe0008331f8)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In lib/flex_proportions.c (ffffffe0008b23be)
Location: include/linux/seqlock.h:374
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
In init/main.c (ffffffff8288b27c)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffff8109ea8c)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/kthread.c (ffffffff810c3834)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/sched/psi.c (ffffffff810fbc76)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
```
```
In kernel/time/timekeeping.c (ffffffff81133e6a)
Location: include/linux/seqlock.h:374
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
In kernel/time/tick-common.c (ffffffff8113f1d3)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff81141195)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In kernel/cgroup/cpuset.c (ffffffff811647da)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/memory_hotplug.c (ffffffff81a67edb)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In fs/dcache.c (ffffffff812f2649)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff812ff76e)
Location: include/linux/seqlock.h:374
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
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:may_umount
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs_struct.c (ffffffff813139de)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/userfaultfd.c (ffffffff813318b5)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
```
```
In block/badblocks.c (ffffffff814f5572)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
```
```
In block/blk-iocost.c (ffffffff815094f6)
Location: include/linux/seqlock.h:374
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8171ceee)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In net/core/gen_estimator.c (ffffffff818c3f44)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/dev.c (ffffffff818d6c6d)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
```
```
In net/core/neighbour.c (ffffffff818e60e6)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff8194d539)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff8197f563)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff819ad528)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c144f)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_chain
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_chain
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_chain
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff819c5f68)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In lib/flex_proportions.c (ffffffff81a4da7b)
Location: include/linux/seqlock.h:374
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
In init/main.c (ffffffff82889201)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffff8108d4bc)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/kthread.c (ffffffff810b2053)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/sched/cputime.c (ffffffff810c89e3)
Location: include/linux/seqlock.h:374
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
In kernel/sched/psi.c (ffffffff810ebe96)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
```
```
In kernel/time/timekeeping.c (ffffffff811268ca)
Location: include/linux/seqlock.h:374
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
In kernel/time/tick-common.c (ffffffff81131ca3)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff81134005)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In kernel/cgroup/cpuset.c (ffffffff81157a24)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/memory_hotplug.c (ffffffff81a2499b)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In fs/dcache.c (ffffffff812e3279)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff812f038e)
Location: include/linux/seqlock.h:374
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
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:may_umount
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs_struct.c (ffffffff813045ee)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/userfaultfd.c (ffffffff81322489)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
```
```
In block/badblocks.c (ffffffff814e5a82)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
```
```
In block/blk-iocost.c (ffffffff814f99a6)
Location: include/linux/seqlock.h:374
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff816f634e)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In net/core/gen_estimator.c (ffffffff8187de84)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/dev.c (ffffffff81890aad)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
```
```
In net/core/neighbour.c (ffffffff8189ff26)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff81907029)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff81939023)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81969b58)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197e23f)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_chain
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_chain
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_chain
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81982d58)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In lib/flex_proportions.c (ffffffff81a0ab7e)
Location: include/linux/seqlock.h:374
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
In init/main.c (ffffffff8289e27c)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffff8109ea3c)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/kthread.c (ffffffff810c2d84)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/sched/psi.c (ffffffff810f8e36)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
```
```
In kernel/time/timekeeping.c (ffffffff81131b8a)
Location: include/linux/seqlock.h:374
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
In kernel/time/tick-common.c (ffffffff8113cec3)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff8113f045)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In kernel/cgroup/cpuset.c (ffffffff811625aa)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/memory_hotplug.c (ffffffff81ad42eb)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In fs/dcache.c (ffffffff812f0459)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff812fd55e)
Location: include/linux/seqlock.h:374
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
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:may_umount
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs_struct.c (ffffffff813117ce)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/userfaultfd.c (ffffffff8132f385)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
```
```
In block/badblocks.c (ffffffff814f1602)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
```
```
In block/blk-iocost.c (ffffffff81505586)
Location: include/linux/seqlock.h:374
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8175bcbe)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In net/core/gen_estimator.c (ffffffff81914f44)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/dev.c (ffffffff81927c9d)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
```
```
In net/core/neighbour.c (ffffffff81937116)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
```
```
In net/netfilter/nf_conntrack_core.c (ffffffff819a070e)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_hash_resize
```
```
In net/ipv4/inetpeer.c (ffffffff819b7d09)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff819e9d33)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81a17dc8)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2becf)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_chain
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_chain
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_chain
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81a309e8)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In lib/flex_proportions.c (ffffffff81ab9e6b)
Location: include/linux/seqlock.h:374
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
In init/main.c (ffffffff8289e283)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffff810a6953)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/kthread.c (ffffffff810cb1c4)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/sched/psi.c (ffffffff81103f86)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
```
```
In kernel/time/timekeeping.c (ffffffff8113e5aa)
Location: include/linux/seqlock.h:374
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
In kernel/time/tick-common.c (ffffffff811499b3)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff8114b6b7)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In kernel/cgroup/cpuset.c (ffffffff8116fb2a)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In mm/memory_hotplug.c (ffffffff81ae07cb)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In fs/dcache.c (ffffffff813015b0)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff8130e8bc)
Location: include/linux/seqlock.h:374
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
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:may_umount
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/fs_struct.c (ffffffff8132301c)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/userfaultfd.c (ffffffff81341439)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
```
```
In block/badblocks.c (ffffffff8150a662)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
```
```
In block/blk-iocost.c (ffffffff8151eec6)
Location: include/linux/seqlock.h:374
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8177735d)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In net/core/gen_estimator.c (ffffffff819360c4)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_timer
```
```
In net/core/dev.c (ffffffff8194936d)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
```
```
In net/core/neighbour.c (ffffffff819588ed)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/inetpeer.c (ffffffff819c158c)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_metrics.c (ffffffff819f3b42)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81a22868)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a3759f)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_chain
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_chain
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_chain
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3c2e8)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In lib/flex_proportions.c (ffffffff81ac62bb)
Location: include/linux/seqlock.h:374
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_new_period
```
</details>
</li>
</ul>

## Differences

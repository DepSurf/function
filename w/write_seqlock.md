# Function: <code>write_seqlock</code>

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
In kernel/exit.c (ffffffff81082509)
Location: include/linux/seqlock.h:443
Inline: True
Inline callers:
  - kernel/exit.c:release_task
  - kernel/exit.c:wait_consider_task
```
```
In kernel/time/timekeeping.c (ffffffff810f6ccd)
Location: include/linux/seqlock.h:443
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
```
```
In kernel/time/tick-common.c (ffffffff810fc477)
Location: include/linux/seqlock.h:443
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff810fe0d6)
Location: include/linux/seqlock.h:443
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
  - kernel/time/tick-sched.c:tick_do_update_jiffies64
```
```
In mm/memory_hotplug.c (ffffffff81208f2b)
Location: include/linux/seqlock.h:443
Inline: True
Inline callers:
  - mm/memory_hotplug.c:resize_zone
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:__remove_pages
```
```
In fs/dcache.c (ffffffff81224c8f)
Location: include/linux/seqlock.h:443
Inline: True
Inline callers:
  - fs/dcache.c:d_move
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:d_exchange
```
```
In fs/namespace.c (ffffffff8122bba9)
Location: include/linux/seqlock.h:443
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
In net/core/neighbour.c (ffffffff817287a7)
Location: include/linux/seqlock.h:443
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff817a5bcf)
Location: include/linux/seqlock.h:443
Inline: True
Inline callers:
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
In kernel/exit.c (ffffffff810860e9)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:release_task
```
```
In kernel/time/timekeeping.c (ffffffff810fde3d)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
```
```
In kernel/time/tick-common.c (ffffffff811037b7)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff81105466)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
  - kernel/time/tick-sched.c:tick_do_update_jiffies64
```
```
In mm/memory_hotplug.c (ffffffff8120e708)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:resize_zone
```
```
In fs/dcache.c (ffffffff8124d068)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff8125872f)
Location: include/linux/seqlock.h:446
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
In net/core/neighbour.c (ffffffff817922fd)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81813865)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
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
In kernel/exit.c (ffffffff8108b059)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:release_task
```
```
In kernel/time/timekeeping.c (ffffffff81100c2d)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
```
```
In kernel/time/tick-common.c (ffffffff8110aea7)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff8110cbb6)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In mm/memory_hotplug.c (ffffffff81220748)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:resize_zone
```
```
In fs/dcache.c (ffffffff81260128)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff8126bbc0)
Location: include/linux/seqlock.h:446
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
In net/core/neighbour.c (ffffffff817bfbcd)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81844d6f)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
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
In kernel/exit.c (ffffffff81087df5)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:release_task
```
```
In kernel/time/timekeeping.c (ffffffff81102d6d)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
```
```
In kernel/time/tick-common.c (ffffffff8110cda7)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff8110ea96)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In mm/memory_hotplug.c (ffffffff818ff4b4)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:__remove_pages
```
```
In fs/dcache.c (ffffffff8126da4f)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff81279395)
Location: include/linux/seqlock.h:446
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
In net/core/neighbour.c (ffffffff817de258)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff818668cf)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
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
In kernel/exit.c (ffffffff8108eb80)
Location: include/linux/seqlock.h:447
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:release_task
```
```
In kernel/time/timekeeping.c (ffffffff8110de4d)
Location: include/linux/seqlock.h:447
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
```
```
In kernel/time/tick-common.c (ffffffff81118057)
Location: include/linux/seqlock.h:447
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff8111a426)
Location: include/linux/seqlock.h:447
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In mm/memory_hotplug.c (ffffffff819895b4)
Location: include/linux/seqlock.h:447
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:__remove_pages
```
```
In fs/dcache.c (ffffffff812904ef)
Location: include/linux/seqlock.h:447
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff8129bdd5)
Location: include/linux/seqlock.h:447
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
In net/core/neighbour.c (ffffffff81858ab8)
Location: include/linux/seqlock.h:447
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff818e6a6f)
Location: include/linux/seqlock.h:447
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
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
In kernel/exit.c (ffffffff8109267b)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
```
```
In kernel/time/timekeeping.c (ffffffff81119805)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
```
```
In kernel/time/tick-common.c (ffffffff81124b87)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff81126d65)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In mm/memory_hotplug.c (ffffffff819e5e87)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:__remove_pages
```
```
In fs/dcache.c (ffffffff812b5b05)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff812c1f06)
Location: include/linux/seqlock.h:446
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
In net/core/neighbour.c (ffffffff818a3f65)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8193d593)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
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
In kernel/exit.c (ffffffff8109a95f)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
```
```
In kernel/time/timekeeping.c (ffffffff81124d05)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
```
```
In kernel/time/tick-common.c (ffffffff81130287)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff81132455)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In mm/memory_hotplug.c (ffffffff81a21213)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:__remove_pages
```
```
In fs/dcache.c (ffffffff812cae15)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff812d71a6)
Location: include/linux/seqlock.h:446
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
In net/core/neighbour.c (ffffffff818c73cd)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8196d363)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
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
In kernel/exit.c (ffffffff8109ebc1)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/time/timekeeping.c (ffffffff8112f6e5)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
```
```
In kernel/time/tick-common.c (ffffffff8113adb7)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff8113cdc5)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In mm/memory_hotplug.c (ffffffff81a918b8)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:__remove_pages
```
```
In fs/dcache.c (ffffffff812e84cd)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff812f5602)
Location: include/linux/seqlock.h:446
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
In net/core/neighbour.c (ffffffff81913aa1)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff819d6c8c)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
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
In kernel/exit.c (ffffffff810a5151)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/time/timekeeping.c (ffffffff8113b6a5)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
```
```
In kernel/time/tick-common.c (ffffffff811469e7)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff81148b65)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In mm/memory_hotplug.c (ffffffff81ac9058)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In fs/dcache.c (ffffffff812fa05d)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff81307182)
Location: include/linux/seqlock.h:446
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
In net/core/neighbour.c (ffffffff81946111)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81a0d77c)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
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
In kernel/exit.c (ffffffff810ace9d)
Location: include/linux/seqlock.h:489
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In mm/memory_hotplug.c (ffffffff81bc1778)
Location: include/linux/seqlock.h:489
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:shrink_zone_span
```
```
In fs/dcache.c (ffffffff8133311d)
Location: include/linux/seqlock.h:489
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff813404a8)
Location: include/linux/seqlock.h:489
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
In net/core/neighbour.c (ffffffff81a1686e)
Location: include/linux/seqlock.h:489
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81afe6be)
Location: include/linux/seqlock.h:489
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
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
In kernel/exit.c (ffffffff810a8566)
Location: include/linux/seqlock.h:888
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In mm/memory_hotplug.c (ffffffff81c3a77c)
Location: include/linux/seqlock.h:888
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:shrink_zone_span
```
```
In fs/dcache.c (ffffffff8133ea7d)
Location: include/linux/seqlock.h:888
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff8134c4ff)
Location: include/linux/seqlock.h:888
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
In net/core/neighbour.c (ffffffff81a163e3)
Location: include/linux/seqlock.h:888
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81b0c73d)
Location: include/linux/seqlock.h:888
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
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
In kernel/exit.c (ffffffff810a9428)
Location: include/linux/seqlock.h:888
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In mm/memory_hotplug.c (ffffffff81c2cd5c)
Location: include/linux/seqlock.h:888
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:shrink_zone_span
```
```
In fs/dcache.c (ffffffff81344e6d)
Location: include/linux/seqlock.h:888
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff813530cf)
Location: include/linux/seqlock.h:888
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
In net/core/neighbour.c (ffffffff819fcf94)
Location: include/linux/seqlock.h:888
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81afa3a6)
Location: include/linux/seqlock.h:888
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
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
In kernel/exit.c (ffffffff810baf18)
Location: include/linux/seqlock.h:888
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In fs/dcache.c (ffffffff8139295d)
Location: include/linux/seqlock.h:888
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff813a151f)
Location: include/linux/seqlock.h:888
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
In net/core/neighbour.c (ffffffff81aafa49)
Location: include/linux/seqlock.h:888
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81bbb0a6)
Location: include/linux/seqlock.h:888
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
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
In kernel/exit.c (ffffffff810d18ef)
Location: include/linux/seqlock.h:884
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In fs/dcache.c (ffffffff81414206)
Location: include/linux/seqlock.h:884
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff81424eed)
Location: include/linux/seqlock.h:884
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
In net/core/neighbour.c (ffffffff81c28446)
Location: include/linux/seqlock.h:884
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81d4f1da)
Location: include/linux/seqlock.h:884
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
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
In kernel/exit.c (ffffffff810f033f)
Location: include/linux/seqlock.h:884
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In mm/page_alloc.c (ffffffff813eec6d)
Location: include/linux/seqlock.h:884
Inline: True
Inline callers:
  - mm/page_alloc.c:__build_all_zonelists
```
```
In fs/dcache.c (ffffffff8149f686)
Location: include/linux/seqlock.h:884
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff814b162b)
Location: include/linux/seqlock.h:884
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
In net/core/neighbour.c (ffffffff81ddb04f)
Location: include/linux/seqlock.h:884
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81f18dda)
Location: include/linux/seqlock.h:884
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
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
In kernel/exit.c (ffffffff810fc2ff)
Location: include/linux/seqlock.h:885
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In mm/page_alloc.c (ffffffff81422a53)
Location: include/linux/seqlock.h:885
Inline: True
Inline callers:
  - mm/page_alloc.c:__build_all_zonelists
```
```
In fs/dcache.c (ffffffff814d49a6)
Location: include/linux/seqlock.h:885
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff814e666b)
Location: include/linux/seqlock.h:885
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
In net/core/neighbour.c (ffffffff81e4bfbd)
Location: include/linux/seqlock.h:885
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f35495)
Location: include/linux/seqlock.h:885
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81f78a50)
Location: include/linux/seqlock.h:885
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
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
In kernel/exit.c (ffffffff81104953)
Location: include/linux/seqlock.h:820
Inline: True
Inline callers:
  - kernel/exit.c:__exit_signal
```
```
In fs/dcache.c (ffffffff81506ce6)
Location: include/linux/seqlock.h:820
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff8151a4ad)
Location: include/linux/seqlock.h:820
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
In drivers/gpu/drm/drm_vblank.c (ffffffff81cb42dd)
Location: include/linux/seqlock.h:820
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_vblank.c:store_vblank
```
```
In net/core/neighbour.c (ffffffff81f0accd)
Location: include/linux/seqlock.h:820
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ffb615)
Location: include/linux/seqlock.h:820
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8203f110)
Location: include/linux/seqlock.h:820
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
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
In kernel/exit.c (ffff8000100fb098)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/time/timekeeping.c (ffff8000101a5934)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
```
```
In kernel/time/tick-common.c (ffff8000101b188c)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffff8000101b4b64)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In mm/memory_hotplug.c (ffff800010d9cca0)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In fs/dcache.c (ffff8000103a8c98)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffff8000103ba9e4)
Location: include/linux/seqlock.h:446
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
In net/core/neighbour.c (ffff800010be627c)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/sysctl_net_ipv4.c (ffff800010cc72dc)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
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
In kernel/exit.c (c0358f00)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/time/timekeeping.c (c03f0954)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
```
```
In kernel/time/tick-common.c (c03fbf44)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (c03fe4d4)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In fs/dcache.c (c058a2cc)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (c0598740)
Location: include/linux/seqlock.h:446
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
In net/socket.c (c0cc48f0)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
```
```
In net/core/sock.c (c0cc8350)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_gettstamp
```
```
In net/core/neighbour.c (c0cfe83c)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/ip_sockglue.c (c0d78860)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/raw.c (c0da57d0)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (c0daab8c)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv4/ping.c (c0dcc438)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/sysctl_net_ipv4.c (c0dd257c)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/ipv6/udp.c (c0e2a718)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (c0e2d7b0)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (c0e40afc)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (c0e59ed4)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
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
In kernel/exit.c (c0000000001424e0)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/time/timekeeping.c (c000000000207824)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
```
```
In kernel/time/tick-common.c (c000000000216708)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (c00000000021a380)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In mm/memory_hotplug.c (c00000000042fb44)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In fs/dcache.c (c0000000004a3848)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (c0000000004b8278)
Location: include/linux/seqlock.h:446
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
In net/core/neighbour.c (c000000000cc7824)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/sysctl_net_ipv4.c (c000000000de3fb4)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
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
In kernel/exit.c (ffffffe0000c4d4c)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/time/timekeeping.c (ffffffe000131ca4)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
```
```
In kernel/time/tick-common.c (ffffffe00013a130)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffe00013b0c0)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In fs/dcache.c (ffffffe00026efc8)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffe00027ce20)
Location: include/linux/seqlock.h:446
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
In net/core/neighbour.c (ffffffe00076afc2)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffe00081b852)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
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
In kernel/exit.c (ffffffff8109ea71)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/time/timekeeping.c (ffffffff81133e55)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
```
```
In kernel/time/tick-common.c (ffffffff8113f1c7)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff81141185)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In mm/memory_hotplug.c (ffffffff81a67ec8)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In fs/dcache.c (ffffffff812f263d)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff812ff762)
Location: include/linux/seqlock.h:446
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
In net/core/neighbour.c (ffffffff818e60e1)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff819ad51c)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
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
In kernel/exit.c (ffffffff8108d4a1)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/time/timekeeping.c (ffffffff811268b5)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
```
```
In kernel/time/tick-common.c (ffffffff81131c97)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff81133ff5)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In mm/memory_hotplug.c (ffffffff81a24988)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In fs/dcache.c (ffffffff812e326d)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff812f0382)
Location: include/linux/seqlock.h:446
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
In net/core/neighbour.c (ffffffff8189ff21)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81969b4c)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
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
In kernel/exit.c (ffffffff8109ea21)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/time/timekeeping.c (ffffffff81131b75)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
```
```
In kernel/time/tick-common.c (ffffffff8113ceb7)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff8113f035)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In mm/memory_hotplug.c (ffffffff81ad42d8)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In fs/dcache.c (ffffffff812f044d)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff812fd552)
Location: include/linux/seqlock.h:446
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
In net/core/neighbour.c (ffffffff81937111)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81a17dbc)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
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
In kernel/exit.c (ffffffff810a6938)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/time/timekeeping.c (ffffffff8113e595)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
```
```
In kernel/time/tick-common.c (ffffffff811499a7)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff8114b6a5)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In mm/memory_hotplug.c (ffffffff81ae07c6)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In fs/dcache.c (ffffffff813015a4)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff8130e8b0)
Location: include/linux/seqlock.h:446
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
In net/core/neighbour.c (ffffffff819588e4)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81a2285c)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
</details>
</li>
</ul>

## Differences

# Function: <code>write_sequnlock</code>

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
In kernel/exit.c (ffffffff81082704)
Location: include/linux/seqlock.h:449
Inline: True
Inline callers:
  - kernel/exit.c:release_task
  - kernel/exit.c:wait_consider_task
```
```
In kernel/time/timekeeping.c (ffffffff810f6cef)
Location: include/linux/seqlock.h:449
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
```
```
In kernel/time/tick-common.c (ffffffff810fc4a2)
Location: include/linux/seqlock.h:449
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff810fe10b)
Location: include/linux/seqlock.h:449
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
  - kernel/time/tick-sched.c:tick_do_update_jiffies64
  - kernel/time/tick-sched.c:tick_do_update_jiffies64
```
```
In mm/memory_hotplug.c (ffffffff81208f74)
Location: include/linux/seqlock.h:449
Inline: True
Inline callers:
  - mm/memory_hotplug.c:resize_zone
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:__remove_pages
```
```
In fs/dcache.c (ffffffff81224cb2)
Location: include/linux/seqlock.h:449
Inline: True
Inline callers:
  - fs/dcache.c:d_move
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:d_exchange
```
```
In fs/namespace.c (ffffffff8122bbcc)
Location: include/linux/seqlock.h:449
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
In net/core/neighbour.c (ffffffff81728811)
Location: include/linux/seqlock.h:449
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff817a5be6)
Location: include/linux/seqlock.h:449
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
In kernel/exit.c (ffffffff81086336)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:release_task
```
```
In kernel/time/timekeeping.c (ffffffff810fde5f)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
```
```
In kernel/time/tick-common.c (ffffffff811037e2)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff8110549b)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
  - kernel/time/tick-sched.c:tick_do_update_jiffies64
  - kernel/time/tick-sched.c:tick_do_update_jiffies64
```
```
In mm/memory_hotplug.c (ffffffff8120e843)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:resize_zone
```
```
In fs/dcache.c (ffffffff8124d13b)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff812587f5)
Location: include/linux/seqlock.h:452
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
In net/core/neighbour.c (ffffffff81792361)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81813882)
Location: include/linux/seqlock.h:452
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
In kernel/exit.c (ffffffff8108b2a6)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:release_task
```
```
In kernel/time/timekeeping.c (ffffffff81100c4f)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
```
```
In kernel/time/tick-common.c (ffffffff8110aed2)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff8110cbe6)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In mm/memory_hotplug.c (ffffffff8122087d)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:resize_zone
```
```
In fs/dcache.c (ffffffff812601fb)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff8126bcb3)
Location: include/linux/seqlock.h:452
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
In net/core/neighbour.c (ffffffff817bfc31)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81844d86)
Location: include/linux/seqlock.h:452
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
In kernel/exit.c (ffffffff81088022)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:release_task
```
```
In kernel/time/timekeeping.c (ffffffff81102d8f)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
```
```
In kernel/time/tick-common.c (ffffffff8110cdd2)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff8110eac6)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In mm/memory_hotplug.c (ffffffff818ff501)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:__remove_pages
```
```
In fs/dcache.c (ffffffff8126db31)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff81279495)
Location: include/linux/seqlock.h:452
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
In net/core/neighbour.c (ffffffff817de2c1)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff818668e6)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/exit.c (ffffffff8108edad)
Location: include/linux/seqlock.h:453
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:release_task
```
```
In kernel/time/timekeeping.c (ffffffff8110de6f)
Location: include/linux/seqlock.h:453
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
```
```
In kernel/time/tick-common.c (ffffffff81118082)
Location: include/linux/seqlock.h:453
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff8111a456)
Location: include/linux/seqlock.h:453
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In mm/memory_hotplug.c (ffffffff81989601)
Location: include/linux/seqlock.h:453
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:__remove_pages
```
```
In fs/dcache.c (ffffffff812905d1)
Location: include/linux/seqlock.h:453
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff8129ae71)
Location: include/linux/seqlock.h:453
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
Direct callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:do_mount
```
```
In net/core/neighbour.c (ffffffff81858b21)
Location: include/linux/seqlock.h:453
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff818e6a86)
Location: include/linux/seqlock.h:453
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
**Symbols:**

```
ffffffff81298390-ffffffff812983ab: write_sequnlock.constprop.39 (STB_LOCAL)
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
In kernel/exit.c (ffffffff810928a8)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
```
```
In kernel/time/timekeeping.c (ffffffff8111982f)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
```
```
In kernel/time/tick-common.c (ffffffff81124bb2)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff81126d96)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In mm/memory_hotplug.c (ffffffff819e5ed8)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:__remove_pages
```
```
In fs/dcache.c (ffffffff812b5b51)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff812c1ff8)
Location: include/linux/seqlock.h:452
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
In net/core/neighbour.c (ffffffff818a3fbd)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8193d5aa)
Location: include/linux/seqlock.h:452
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
In kernel/exit.c (ffffffff8109ab8c)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
```
```
In kernel/time/timekeeping.c (ffffffff81124d2f)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
```
```
In kernel/time/tick-common.c (ffffffff811302b2)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff81132486)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In mm/memory_hotplug.c (ffffffff81a2126a)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:__remove_pages
```
```
In fs/dcache.c (ffffffff812cae61)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff812d7298)
Location: include/linux/seqlock.h:452
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
In net/core/neighbour.c (ffffffff818c741d)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8196d37a)
Location: include/linux/seqlock.h:452
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
In kernel/exit.c (ffffffff8109ee0a)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/time/timekeeping.c (ffffffff8112f710)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
```
```
In kernel/time/tick-common.c (ffffffff8113ade2)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff8113cdf6)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In mm/memory_hotplug.c (ffffffff81a91918)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
```
```
In fs/dcache.c (ffffffff812e85cd)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff812f56fa)
Location: include/linux/seqlock.h:452
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
In net/core/neighbour.c (ffffffff81913af1)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff819d6ca3)
Location: include/linux/seqlock.h:452
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
In kernel/exit.c (ffffffff810a539a)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/time/timekeeping.c (ffffffff8113b6d0)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
```
```
In kernel/time/tick-common.c (ffffffff81146a12)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff81148b96)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In mm/memory_hotplug.c (ffffffff81ac90b9)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In fs/dcache.c (ffffffff812fa15d)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff8130727a)
Location: include/linux/seqlock.h:452
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
In net/core/neighbour.c (ffffffff81946161)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81a0d793)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/exit.c (ffffffff810ad0f1)
Location: include/linux/seqlock.h:495
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In mm/memory_hotplug.c (ffffffff81bc17d9)
Location: include/linux/seqlock.h:495
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:shrink_zone_span
```
```
In fs/dcache.c (ffffffff8133321d)
Location: include/linux/seqlock.h:495
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff813404c3)
Location: include/linux/seqlock.h:495
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
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
```
```
In net/core/neighbour.c (ffffffff81a168c2)
Location: include/linux/seqlock.h:495
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81afe6d5)
Location: include/linux/seqlock.h:495
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
**Symbols:**

```
ffffffff8133af90-ffffffff8133afab: write_sequnlock.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/exit.c (ffffffff810a87ba)
Location: include/linux/seqlock.h:901
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In mm/memory_hotplug.c (ffffffff81c3a7e6)
Location: include/linux/seqlock.h:901
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:shrink_zone_span
```
```
In fs/dcache.c (ffffffff8133eb7d)
Location: include/linux/seqlock.h:901
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff8134c51a)
Location: include/linux/seqlock.h:901
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
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:sb_prepare_remount_readonly
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
```
```
In net/core/neighbour.c (ffffffff81a16434)
Location: include/linux/seqlock.h:901
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81b0c754)
Location: include/linux/seqlock.h:901
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
**Symbols:**

```
ffffffff81346c80-ffffffff81346c9b: write_sequnlock.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/exit.c (ffffffff810a966a)
Location: include/linux/seqlock.h:901
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In mm/memory_hotplug.c (ffffffff81c2cdc6)
Location: include/linux/seqlock.h:901
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:shrink_zone_span
```
```
In fs/dcache.c (ffffffff81344f6d)
Location: include/linux/seqlock.h:901
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff813530ea)
Location: include/linux/seqlock.h:901
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
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:sb_prepare_remount_readonly
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
```
```
In net/core/neighbour.c (ffffffff819fcfe2)
Location: include/linux/seqlock.h:901
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81afa3bd)
Location: include/linux/seqlock.h:901
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
**Symbols:**

```
ffffffff8134d390-ffffffff8134d3ab: write_sequnlock.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/exit.c (ffffffff810bb15a)
Location: include/linux/seqlock.h:901
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In fs/dcache.c (ffffffff81392a5d)
Location: include/linux/seqlock.h:901
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff813a153a)
Location: include/linux/seqlock.h:901
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
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:sb_prepare_remount_readonly
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
```
```
In net/core/neighbour.c (ffffffff81aafa9a)
Location: include/linux/seqlock.h:901
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81bbb0bd)
Location: include/linux/seqlock.h:901
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
**Symbols:**

```
ffffffff8139b360-ffffffff8139b37b: write_sequnlock.constprop.0 (STB_LOCAL)
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
In kernel/exit.c (ffffffff810d1b23)
Location: include/linux/seqlock.h:897
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In fs/dcache.c (ffffffff81414308)
Location: include/linux/seqlock.h:897
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff81424f08)
Location: include/linux/seqlock.h:897
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
In net/core/neighbour.c (ffffffff81c28497)
Location: include/linux/seqlock.h:897
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81d4f1f1)
Location: include/linux/seqlock.h:897
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
In kernel/exit.c (ffffffff810f0573)
Location: include/linux/seqlock.h:897
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In mm/page_alloc.c (ffffffff813eecf5)
Location: include/linux/seqlock.h:897
Inline: True
Inline callers:
  - mm/page_alloc.c:__build_all_zonelists
```
```
In fs/dcache.c (ffffffff8149f788)
Location: include/linux/seqlock.h:897
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff814b1646)
Location: include/linux/seqlock.h:897
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
In net/core/neighbour.c (ffffffff81ddb0b4)
Location: include/linux/seqlock.h:897
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81f18df1)
Location: include/linux/seqlock.h:897
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
In kernel/exit.c (ffffffff810fc533)
Location: include/linux/seqlock.h:898
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In mm/page_alloc.c (ffffffff81422adf)
Location: include/linux/seqlock.h:898
Inline: True
Inline callers:
  - mm/page_alloc.c:__build_all_zonelists
```
```
In fs/dcache.c (ffffffff814d4aa8)
Location: include/linux/seqlock.h:898
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff814e6686)
Location: include/linux/seqlock.h:898
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
In net/core/neighbour.c (ffffffff81e4c019)
Location: include/linux/seqlock.h:898
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f354b5)
Location: include/linux/seqlock.h:898
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81f78a67)
Location: include/linux/seqlock.h:898
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
In kernel/exit.c (ffffffff81104a97)
Location: include/linux/seqlock.h:833
Inline: True
Inline callers:
  - kernel/exit.c:__exit_signal
```
```
In fs/dcache.c (ffffffff81506de8)
Location: include/linux/seqlock.h:833
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff8151a4c2)
Location: include/linux/seqlock.h:833
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
In drivers/gpu/drm/drm_vblank.c (ffffffff81cb42f2)
Location: include/linux/seqlock.h:833
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_vblank.c:store_vblank
```
```
In net/core/neighbour.c (ffffffff81f0ad29)
Location: include/linux/seqlock.h:833
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ffb635)
Location: include/linux/seqlock.h:833
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcpm_suck_dst
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8203f127)
Location: include/linux/seqlock.h:833
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
In kernel/exit.c (ffff8000100fb2b4)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/time/timekeeping.c (ffff8000101a5990)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
```
```
In kernel/time/tick-common.c (ffff8000101b18f0)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffff8000101b4bc4)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In mm/memory_hotplug.c (ffff800010d9cd20)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In fs/dcache.c (ffff8000103a8d88)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffff8000103baae8)
Location: include/linux/seqlock.h:452
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
In net/core/neighbour.c (ffff800010be62d0)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/sysctl_net_ipv4.c (ffff800010cc7318)
Location: include/linux/seqlock.h:452
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
In kernel/exit.c (c03592f0)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/time/timekeeping.c (c03f0994)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
```
```
In kernel/time/tick-common.c (c03fbf8c)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (c03fe510)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In fs/dcache.c (c058a3b0)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (c0597c24)
Location: include/linux/seqlock.h:452
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
In net/socket.c (c0cc4914)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
```
```
In net/core/sock.c (c0cc8374)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_gettstamp
```
```
In net/core/neighbour.c (c0cfe86c)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/ip_sockglue.c (c0d78884)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/raw.c (c0da57f8)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (c0daabac)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv4/ping.c (c0dcc45c)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/sysctl_net_ipv4.c (c0dd2598)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/ipv6/udp.c (c0e2a738)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (c0e2d7d0)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/ipv6/datagram.c (c0e40b20)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/packet/af_packet.c (c0e59ef4)
Location: include/linux/seqlock.h:452
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
In kernel/exit.c (c0000000001426f4)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/time/timekeeping.c (c00000000020786c)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
```
```
In kernel/time/tick-common.c (c00000000021674c)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (c00000000021a3c4)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In mm/memory_hotplug.c (c00000000042fbb0)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In fs/dcache.c (c0000000004a3958)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (c0000000004b836c)
Location: include/linux/seqlock.h:452
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
In net/core/neighbour.c (c000000000cc7854)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/sysctl_net_ipv4.c (c000000000de3fd8)
Location: include/linux/seqlock.h:452
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
In kernel/exit.c (ffffffe0000c4f0c)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/time/timekeeping.c (ffffffe000131ce0)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
```
```
In kernel/time/tick-common.c (ffffffe00013a176)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffe00013b0f8)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In fs/dcache.c (ffffffe00026f088)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffe00027cf1a)
Location: include/linux/seqlock.h:452
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
In net/core/neighbour.c (ffffffe00076aff4)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffe00081b874)
Location: include/linux/seqlock.h:452
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
In kernel/exit.c (ffffffff8109ecba)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/time/timekeeping.c (ffffffff81133e80)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
```
```
In kernel/time/tick-common.c (ffffffff8113f1f2)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff811411b6)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In mm/memory_hotplug.c (ffffffff81a67f29)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In fs/dcache.c (ffffffff812f273d)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff812ff85a)
Location: include/linux/seqlock.h:452
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
In net/core/neighbour.c (ffffffff818e6131)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff819ad533)
Location: include/linux/seqlock.h:452
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
In kernel/exit.c (ffffffff8108d6f6)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/time/timekeeping.c (ffffffff811268e0)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
```
```
In kernel/time/tick-common.c (ffffffff81131cc2)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff81134026)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In mm/memory_hotplug.c (ffffffff81a249e9)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In fs/dcache.c (ffffffff812e336d)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff812f047a)
Location: include/linux/seqlock.h:452
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
In net/core/neighbour.c (ffffffff8189ff71)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81969b63)
Location: include/linux/seqlock.h:452
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
In kernel/exit.c (ffffffff8109ec6a)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/time/timekeeping.c (ffffffff81131ba0)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
```
```
In kernel/time/tick-common.c (ffffffff8113cee2)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff8113f066)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In mm/memory_hotplug.c (ffffffff81ad4339)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In fs/dcache.c (ffffffff812f054d)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff812fd64a)
Location: include/linux/seqlock.h:452
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
In net/core/neighbour.c (ffffffff81937161)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81a17dd3)
Location: include/linux/seqlock.h:452
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
In kernel/exit.c (ffffffff810a6b81)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/time/timekeeping.c (ffffffff8113e5c0)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
```
```
In kernel/time/tick-common.c (ffffffff811499d2)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff8114b6d8)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In mm/memory_hotplug.c (ffffffff81ae081d)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In fs/dcache.c (ffffffff813016d6)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff8130e9a8)
Location: include/linux/seqlock.h:452
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
In net/core/neighbour.c (ffffffff81958938)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81a22873)
Location: include/linux/seqlock.h:452
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
</details>
</li>
</ul>

## Differences

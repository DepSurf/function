# Function: <code>read_seqcount_retry</code>

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
In kernel/sched/cputime.c (ffffffff810b19ab)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/hrtimer.c (ffffffff810eea2b)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (ffffffff810f42e1)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_mono_to_any
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:current_kernel_time64
  - kernel/time/timekeeping.c:ktime_get_resolution_ns
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_get
  - kernel/time/timekeeping.c:getrawmonotonic64
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:__getnstimeofday64
  - kernel/time/timekeeping.c:timekeeping_get_tai_offset
  - kernel/time/timekeeping.c:timekeeping_valid_for_hres
  - kernel/time/timekeeping.c:timekeeping_max_deferment
  - kernel/time/timekeeping.c:get_monotonic_coarse64
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
```
```
In kernel/time/tick-common.c (ffffffff810fc722)
Location: include/linux/seqlock.h:217
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff810fe733)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
```
In kernel/module.c (ffffffff811067fe)
Location: include/linux/seqlock.h:217
Inline: True
```
```
In kernel/auditsc.c (ffffffff81128bc5)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In mm/filemap.c (ffffffff8118d660)
Location: include/linux/seqlock.h:217
Inline: True
```
```
In mm/page_alloc.c (ffffffff81192536)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/hugetlb.c (ffffffff811dae58)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_buddy_huge_page
  - mm/hugetlb.c:alloc_huge_page
```
```
In mm/mempolicy.c (ffffffff811e08bd)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
```
```
In mm/slub.c (ffffffff811eab39)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/namei.c (ffffffff81216303)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - fs/namei.c:set_root_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:unlazy_walk
  - fs/namei.c:unlazy_walk
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:trailing_symlink
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:walk_component
  - fs/namei.c:link_path_walk
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_openat
```
```
In fs/dcache.c (ffffffff81222801)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - fs/dcache.c:slow_dentry_cmp
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:__dentry_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:d_path
  - fs/dcache.c:d_lookup
  - fs/dcache.c:SyS_getcwd
  - fs/dcache.c:is_subdir
```
```
In fs/namespace.c (ffffffff8122d839)
Location: include/linux/seqlock.h:217
Inline: True
```
```
In fs/userfaultfd.c (ffffffff8125a25c)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
```
In lib/flex_proportions.c (ffffffff813e9976)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_single
  - lib/flex_proportions.c:fprop_fraction_percpu
```
```
In drivers/dma-buf/dma-buf.c (ffffffff815a33f7)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/reservation.c (ffffffff815a504b)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
```
```
In drivers/md/md.c (ffffffff8168dc63)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - drivers/md/md.c:md_is_badblock
  - drivers/md/md.c:badblocks_show
  - drivers/md/md.c:super_1_sync
```
```
In net/core/dev.c (ffffffff8171bf27)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
```
```
In net/core/neighbour.c (ffffffff8172594c)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
  - net/core/neighbour.c:neigh_fill_info
```
```
In net/ipv4/inetpeer.c (ffffffff81758597)
Location: include/linux/seqlock.h:217
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff8175d239)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81763a23)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff817813a1)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff8178c570)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/inet_fragment.c (ffffffff817a18c9)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:get_frag_bucket_locked
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
```
```
In net/ipv4/ping.c (ffffffff817a283a)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff817a5b1c)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b4713)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (ffffffff817c53da)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
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
In kernel/sched/cputime.c (ffffffff810b445b)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/hrtimer.c (ffffffff810f5b2b)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (ffffffff810fdc7d)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:get_monotonic_coarse64
  - kernel/time/timekeeping.c:current_kernel_time64
  - kernel/time/timekeeping.c:timekeeping_max_deferment
  - kernel/time/timekeeping.c:timekeeping_valid_for_hres
  - kernel/time/timekeeping.c:getrawmonotonic64
  - kernel/time/timekeeping.c:timekeeping_get_tai_offset
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_mono_to_any
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get_resolution_ns
  - kernel/time/timekeeping.c:ktime_get
  - kernel/time/timekeeping.c:__getnstimeofday64
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/time/tick-common.c (ffffffff81103a78)
Location: include/linux/seqlock.h:217
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff81105ac0)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
```
In kernel/module.c (ffffffff8110dfc5)
Location: include/linux/seqlock.h:217
Inline: True
```
```
In kernel/auditsc.c (ffffffff81130d5d)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In mm/filemap.c (ffffffff811a0251)
Location: include/linux/seqlock.h:217
Inline: True
```
```
In mm/page_alloc.c (ffffffff811ab2df)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/hugetlb.c (ffffffff811fafca)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__alloc_buddy_huge_page
```
```
In mm/mempolicy.c (ffffffff811feba8)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
```
```
In mm/slub.c (ffffffff8120a176)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/namei.c (ffffffff812422db)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_init
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
  - fs/namei.c:unlazy_walk
  - fs/namei.c:unlazy_walk
```
```
In fs/dcache.c (ffffffff8124ec35)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - fs/dcache.c:is_subdir
  - fs/dcache.c:SyS_getcwd
  - fs/dcache.c:__dentry_path
  - fs/dcache.c:d_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:__d_lookup_rcu
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff81256029)
Location: include/linux/seqlock.h:217
Inline: True
```
```
In fs/userfaultfd.c (ffffffff81282a6b)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
```
In block/badblocks.c (ffffffff81413040)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In lib/flex_proportions.c (ffffffff8142fe57)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
```
```
In drivers/dma-buf/dma-buf.c (ffffffff815fa4c6)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/reservation.c (ffffffff815fc0a5)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8164c55c)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
```
```
In drivers/md/md.c (ffffffff816f27d9)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/gen_stats.c (ffffffff81776747)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/dev.c (ffffffff817847b9)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
```
```
In net/core/neighbour.c (ffffffff81790743)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffff817c4877)
Location: include/linux/seqlock.h:217
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff817ca006)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817d02f1)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff817ee86a)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff817f9b7e)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/inet_fragment.c (ffffffff8180f596)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:get_frag_bucket_locked
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
```
```
In net/ipv4/ping.c (ffffffff818100a3)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff818137af)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff818203e4)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (ffffffff81831fcf)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
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
In kernel/sched/cputime.c (ffffffff810baa64)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/hrtimer.c (ffffffff810fcaeb)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (ffffffff81100a6d)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:get_monotonic_coarse64
  - kernel/time/timekeeping.c:current_kernel_time64
  - kernel/time/timekeeping.c:timekeeping_max_deferment
  - kernel/time/timekeeping.c:timekeeping_valid_for_hres
  - kernel/time/timekeeping.c:getrawmonotonic64
  - kernel/time/timekeeping.c:timekeeping_get_tai_offset
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_mono_to_any
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get_resolution_ns
  - kernel/time/timekeeping.c:ktime_get
  - kernel/time/timekeeping.c:__getnstimeofday64
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/time/tick-common.c (ffffffff8110b165)
Location: include/linux/seqlock.h:217
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8110d20c)
Location: include/linux/seqlock.h:217
Inline: True
```
```
In kernel/module.c (ffffffff811159a5)
Location: include/linux/seqlock.h:217
Inline: True
```
```
In kernel/auditsc.c (ffffffff8113aacd)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In mm/filemap.c (ffffffff811af691)
Location: include/linux/seqlock.h:217
Inline: True
```
```
In mm/page_alloc.c (ffffffff811bb187)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (ffffffff8120baca)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__alloc_buddy_huge_page
```
```
In mm/mempolicy.c (ffffffff812103ea)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
```
```
In mm/slub.c (ffffffff8121c1e6)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/namei.c (ffffffff81255545)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_init
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
  - fs/namei.c:unlazy_walk
  - fs/namei.c:unlazy_walk
```
```
In fs/dcache.c (ffffffff81261c45)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - fs/dcache.c:is_subdir
  - fs/dcache.c:SyS_getcwd
  - fs/dcache.c:__dentry_path
  - fs/dcache.c:d_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:__d_lookup_rcu
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff81269419)
Location: include/linux/seqlock.h:217
Inline: True
```
```
In fs/userfaultfd.c (ffffffff8129658b)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
```
In block/badblocks.c (ffffffff8142e570)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In lib/flex_proportions.c (ffffffff8144c087)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81628796)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/reservation.c (ffffffff8162ae52)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8167e26c)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
```
```
In drivers/md/md.c (ffffffff81723ef8)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/gen_stats.c (ffffffff817a39c9)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (ffffffff817a4040)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/dev.c (ffffffff817b1da9)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
```
```
In net/core/neighbour.c (ffffffff817bdff3)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffff817f4397)
Location: include/linux/seqlock.h:217
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff817f92be)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81800131)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff8181f27a)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff8182aa4e)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/inet_fragment.c (ffffffff81840ae6)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:get_frag_bucket_locked
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
```
```
In net/ipv4/ping.c (ffffffff818415f3)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81844cbc)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81851c24)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff8185932a)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffff81863f73)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
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
In kernel/sched/cputime.c (ffffffff810b5334)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/hrtimer.c (ffffffff810ff044)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (ffffffff81102bac)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:get_monotonic_coarse64
  - kernel/time/timekeeping.c:current_kernel_time64
  - kernel/time/timekeeping.c:timekeeping_max_deferment
  - kernel/time/timekeeping.c:timekeeping_valid_for_hres
  - kernel/time/timekeeping.c:getrawmonotonic64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_mono_to_any
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get_resolution_ns
  - kernel/time/timekeeping.c:ktime_get
  - kernel/time/timekeeping.c:__getnstimeofday64
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/time/tick-common.c (ffffffff8110d055)
Location: include/linux/seqlock.h:217
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8110f076)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
```
In kernel/module.c (ffffffff811166ea)
Location: include/linux/seqlock.h:217
Inline: True
```
```
In kernel/auditsc.c (ffffffff8113c0c8)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In kernel/bpf/core.c (ffffffff8118df4c)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_find
```
```
In mm/filemap.c (ffffffff811b655d)
Location: include/linux/seqlock.h:217
Inline: True
```
```
In mm/page_alloc.c (ffffffff811c33f2)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (ffffffff812145ed)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff81227bde)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/namei.c (ffffffff81261aae)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_init
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffff8126f505)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - fs/dcache.c:is_subdir
  - fs/dcache.c:SyS_getcwd
  - fs/dcache.c:__dentry_path
  - fs/dcache.c:d_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:__d_lookup_rcu
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff81276bb9)
Location: include/linux/seqlock.h:217
Inline: True
```
```
In fs/userfaultfd.c (ffffffff812a3dcb)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
```
In block/badblocks.c (ffffffff8143b877)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/dma-buf/dma-buf.c (ffffffff8163e3f0)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/reservation.c (ffffffff816404ca)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
```
```
In drivers/net/phy/fixed_phy.c (ffffffff816933ad)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
```
```
In drivers/md/md.c (ffffffff8173c302)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/gen_stats.c (ffffffff817c1ad1)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (ffffffff817c2192)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/dev.c (ffffffff817cf414)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
```
```
In net/core/neighbour.c (ffffffff817dca5c)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffff818147cb)
Location: include/linux/seqlock.h:217
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff8181969c)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8182102a)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff8183fe33)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff8184bc76)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/inet_fragment.c (ffffffff818623d7)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:get_frag_bucket_locked
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
```
```
In net/ipv4/ping.c (ffffffff81862e33)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8186681c)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81874da3)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff8187d2ae)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffff818894bd)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In lib/flex_proportions.c (ffffffff818ec837)
Location: include/linux/seqlock.h:217
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
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
In kernel/sched/cputime.c (ffffffff810bc4e4)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/hrtimer.c (ffffffff81109e24)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (ffffffff8110db4f)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:get_monotonic_coarse64
  - kernel/time/timekeeping.c:current_kernel_time64
  - kernel/time/timekeeping.c:timekeeping_max_deferment
  - kernel/time/timekeeping.c:timekeeping_valid_for_hres
  - kernel/time/timekeeping.c:getrawmonotonic64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_mono_to_any
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get_resolution_ns
  - kernel/time/timekeeping.c:ktime_get
  - kernel/time/timekeeping.c:__getnstimeofday64
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/time/tick-common.c (ffffffff811182d5)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8111a096)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
```
In kernel/module.c (ffffffff81121cea)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In kernel/auditsc.c (ffffffff81148e48)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In kernel/bpf/core.c (ffffffff8119c1fb)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_find
```
```
In mm/filemap.c (ffffffff811ca8cc)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In mm/page_alloc.c (ffffffff811d8183)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (ffffffff8122f16f)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff81243d24)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/namei.c (ffffffff812838b4)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_init
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffff81291e25)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/dcache.c:is_subdir
  - fs/dcache.c:SyS_getcwd
  - fs/dcache.c:__dentry_path
  - fs/dcache.c:d_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:__d_lookup_rcu
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff812995f9)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In fs/userfaultfd.c (ffffffff812c724e)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
```
In block/badblocks.c (ffffffff81467887)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/dma-buf/dma-buf.c (ffffffff816a71fa)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/reservation.c (ffffffff816a9549)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
```
```
In drivers/net/phy/fixed_phy.c (ffffffff816fd2c0)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
```
```
In drivers/md/md.c (ffffffff817adeb2)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/gen_stats.c (ffffffff8183b4ea)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (ffffffff8183bb80)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/dev.c (ffffffff81848d84)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
```
```
In net/core/neighbour.c (ffffffff8185762c)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffff818936bc)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_output.c (ffffffff81897cc7)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8189fdea)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff818bf1d9)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff818cb916)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/inet_fragment.c (ffffffff818e24cd)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:get_frag_bucket_locked
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
```
```
In net/ipv4/ping.c (ffffffff818e2f6b)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff818e69bc)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f5713)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff818fe064)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffff819099ad)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In lib/flex_proportions.c (ffffffff81972807)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
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
In kernel/sched/cputime.c (ffffffff810c3bcc)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/hrtimer.c (ffffffff811153f1)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (ffffffff8111953b)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:ktime_get_coarse_ts64
  - kernel/time/timekeeping.c:ktime_get_coarse_real_ts64
  - kernel/time/timekeeping.c:timekeeping_max_deferment
  - kernel/time/timekeeping.c:timekeeping_valid_for_hres
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_mono_to_any
  - kernel/time/timekeeping.c:ktime_get_coarse_with_offset
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get_resolution_ns
  - kernel/time/timekeeping.c:ktime_get
  - kernel/time/timekeeping.c:ktime_get_real_ts64
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/time/tick-common.c (ffffffff81124e51)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff81126b30)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/module.c (ffffffff8112f7a7)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In kernel/auditsc.c (ffffffff8115785f)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In kernel/bpf/core.c (ffffffff811b1288)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In mm/filemap.c (ffffffff811eb928)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In mm/page_alloc.c (ffffffff811f943e)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (ffffffff81251978)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff812664dc)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/namei.c (ffffffff812aae7a)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_init
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffff812b78cc)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:__d_lookup_rcu
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff812bf455)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In fs/d_path.c (ffffffff812d3d31)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
```
```
In fs/userfaultfd.c (ffffffff812f019b)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
```
In block/badblocks.c (ffffffff8149b6f4)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/dma-buf/dma-buf.c (ffffffff816e3456)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/reservation.c (ffffffff816e561c)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8173b3b8)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
```
```
In drivers/md/md.c (ffffffff817f3f83)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/gen_stats.c (ffffffff81885bff)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (ffffffff818862ca)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/dev.c (ffffffff81892de3)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
```
```
In net/core/neighbour.c (ffffffff818a27ad)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffff818e77fa)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_output.c (ffffffff818ebfbc)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f45bf)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff81914dc4)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81921d61)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff819398d4)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8193d4e2)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194bbb1)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff81954b3d)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffff81960bd0)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In lib/flex_proportions.c (ffffffff819cec2e)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
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
In kernel/sched/cputime.c (ffffffff810cce8c)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/psi.c (ffffffff810ef064)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/sched/psi.c:update_stats
```
```
In kernel/time/hrtimer.c (ffffffff81120a31)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (ffffffff81124a2b)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:ktime_get_coarse_ts64
  - kernel/time/timekeeping.c:ktime_get_coarse_real_ts64
  - kernel/time/timekeeping.c:timekeeping_max_deferment
  - kernel/time/timekeeping.c:timekeeping_valid_for_hres
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_mono_to_any
  - kernel/time/timekeeping.c:ktime_get_coarse_with_offset
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get_resolution_ns
  - kernel/time/timekeeping.c:ktime_get
  - kernel/time/timekeeping.c:ktime_get_real_ts64
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/time/tick-common.c (ffffffff81130551)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff81132210)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/module.c (ffffffff8113b27a)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In kernel/auditsc.c (ffffffff8116485f)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In kernel/bpf/core.c (ffffffff811bf908)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In mm/filemap.c (ffffffff811fc4a8)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In mm/page_alloc.c (ffffffff8120b9e7)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (ffffffff81265d78)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff8127b217)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/namei.c (ffffffff812c019a)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_init
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffff812cca2c)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:__d_lookup_rcu
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff812d4665)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In fs/d_path.c (ffffffff812e8f81)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
```
```
In fs/userfaultfd.c (ffffffff813050db)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
```
In block/badblocks.c (ffffffff814b5a04)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/dma-buf/dma-buf.c (ffffffff817067d6)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/reservation.c (ffffffff8170860a)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8175eb7c)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
```
```
In drivers/md/md.c (ffffffff8181feb3)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/gen_stats.c (ffffffff818a632f)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (ffffffff818a6a4a)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/dev.c (ffffffff818b3863)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
```
```
In net/core/neighbour.c (ffffffff818c598a)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffff819146aa)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_output.c (ffffffff81919d76)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81922350)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff81943574)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81950b8a)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff81969564)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8196d2b2)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81980fca)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff8198939f)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffff81996eea)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In lib/flex_proportions.c (ffffffff81a080ee)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
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
In kernel/sched/cputime.c (ffffffff810d526e)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/psi.c (ffffffff810f6350)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/sched/psi.c:collect_percpu_times
```
```
In kernel/time/hrtimer.c (ffffffff8112b257)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (ffffffff8112f36b)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:ktime_get_coarse_ts64
  - kernel/time/timekeeping.c:ktime_get_coarse_real_ts64
  - kernel/time/timekeeping.c:timekeeping_max_deferment
  - kernel/time/timekeeping.c:timekeeping_valid_for_hres
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_mono_to_any
  - kernel/time/timekeeping.c:ktime_get_coarse_with_offset
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get_resolution_ns
  - kernel/time/timekeeping.c:ktime_get
  - kernel/time/timekeeping.c:ktime_get_real_ts64
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/time/tick-common.c (ffffffff8113b0a2)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8113cb65)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/module.c (ffffffff811468b6)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In kernel/auditsc.c (ffffffff81171589)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In kernel/bpf/core.c (ffffffff811cfecb)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In mm/filemap.c (ffffffff81213b6b)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In mm/page_alloc.c (ffffffff81271c56)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (ffffffff81281255)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff81296a52)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/namei.c (ffffffff812dd053)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_init
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffff812e9625)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:__d_lookup_rcu
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff812f1b75)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In fs/d_path.c (ffffffff8130781b)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
```
```
In fs/userfaultfd.c (ffffffff81326e07)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
```
In block/badblocks.c (ffffffff814e3f47)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/dma-buf/dma-buf.c (ffffffff8174193a)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/reservation.c (ffffffff817440d0)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8179c1da)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
```
```
In drivers/md/md.c (ffffffff818621ac)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/gen_stats.c (ffffffff818f186b)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (ffffffff818f1ef0)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/dev.c (ffffffff819000e7)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
```
```
In net/core/neighbour.c (ffffffff819119f9)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffff81976cdc)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_output.c (ffffffff8197beec)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81984ae0)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff819a7b3d)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff819b5480)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff819d01b9)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff819d6bda)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e61b0)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff819f31c6)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffff81a00cc1)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In lib/flex_proportions.c (ffffffff81a77a47)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
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
In kernel/sched/cputime.c (ffffffff810df82e)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/psi.c (ffffffff811020f0)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/sched/psi.c:collect_percpu_times
```
```
In kernel/time/hrtimer.c (ffffffff81137337)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (ffffffff8113b32b)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:ktime_get_coarse_ts64
  - kernel/time/timekeeping.c:ktime_get_coarse_real_ts64
  - kernel/time/timekeeping.c:timekeeping_max_deferment
  - kernel/time/timekeeping.c:timekeeping_valid_for_hres
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_mono_to_any
  - kernel/time/timekeeping.c:ktime_get_coarse_with_offset
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get_real_ts64
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/time/tick-common.c (ffffffff81146cb2)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff81148905)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/module.c (ffffffff81152496)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In kernel/auditsc.c (ffffffff8117d409)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In kernel/bpf/core.c (ffffffff811dc47b)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In mm/filemap.c (ffffffff8122133b)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In mm/page_alloc.c (ffffffff81280af7)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (ffffffff81290ee5)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff812a680d)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/namei.c (ffffffff812eeb63)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_init
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffff812fb1c5)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:__d_lookup_rcu
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff81303725)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In fs/d_path.c (ffffffff8131a88b)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
```
```
In fs/userfaultfd.c (ffffffff81339b97)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
```
In block/badblocks.c (ffffffff814fd307)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/blk-iocost.c (ffffffff8150ff3d)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81765aba)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8176823b)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
```
```
In drivers/net/phy/fixed_phy.c (ffffffff817bfc8a)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
```
```
In drivers/md/md.c (ffffffff81893ddc)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/gen_stats.c (ffffffff819237bb)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (ffffffff81923e40)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/dev.c (ffffffff81932407)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
```
```
In net/core/neighbour.c (ffffffff81944069)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffff819ad66c)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_output.c (ffffffff819b2892)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bb550)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff819debcd)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff819ec1a0)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff81a06d09)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81a0d6ca)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a1d1a0)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff81a2a096)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffff81a37894)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In lib/flex_proportions.c (ffffffff81aaee37)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
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
In kernel/sched/cputime.c (ffffffff810e7b80)
Location: include/linux/seqlock.h:238
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/psi.c (ffffffff8110cd87)
Location: include/linux/seqlock.h:238
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff81145fc7)
Location: include/linux/seqlock.h:238
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (ffffffff8114a37b)
Location: include/linux/seqlock.h:238
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:ktime_get_coarse_ts64
  - kernel/time/timekeeping.c:ktime_get_coarse_real_ts64
  - kernel/time/timekeeping.c:timekeeping_max_deferment
  - kernel/time/timekeeping.c:timekeeping_valid_for_hres
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_snapshot
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_mono_to_any
  - kernel/time/timekeeping.c:ktime_get_coarse_with_offset
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get_resolution_ns
  - kernel/time/timekeeping.c:ktime_get
  - kernel/time/timekeeping.c:ktime_get_real_ts64
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/time/tick-common.c (ffffffff81156b72)
Location: include/linux/seqlock.h:238
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff81158545)
Location: include/linux/seqlock.h:238
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/module.c (ffffffff81162143)
Location: include/linux/seqlock.h:238
Inline: True
```
```
In kernel/auditsc.c (ffffffff8118f07f)
Location: include/linux/seqlock.h:238
Inline: True
Inline callers:
  - kernel/auditsc.c:handle_path
```
```
In kernel/bpf/core.c (ffffffff811f8e24)
Location: include/linux/seqlock.h:238
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_find
```
```
In mm/filemap.c (ffffffff8124e365)
Location: include/linux/seqlock.h:238
Inline: True
```
```
In mm/page_alloc.c (ffffffff812b301c)
Location: include/linux/seqlock.h:238
Inline: True
```
```
In mm/hugetlb.c (ffffffff812c378f)
Location: include/linux/seqlock.h:238
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff812db0d2)
Location: include/linux/seqlock.h:238
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In fs/namei.c (ffffffff81322b3e)
Location: include/linux/seqlock.h:238
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:step_into
  - fs/namei.c:lookup_fast
  - fs/namei.c:__follow_mount_rcu
  - fs/namei.c:choose_mountpoint
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
  - fs/namei.c:unlazy_child
  - fs/namei.c:__legitimize_path
```
```
In fs/dcache.c (ffffffff81333ea0)
Location: include/linux/seqlock.h:238
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_hash_and_lookup
  - fs/dcache.c:__d_lookup_rcu
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff8133d495)
Location: include/linux/seqlock.h:238
Inline: True
```
```
In fs/d_path.c (ffffffff813547b5)
Location: include/linux/seqlock.h:238
Inline: True
Inline callers:
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
```
In fs/userfaultfd.c (ffffffff81372ef1)
Location: include/linux/seqlock.h:238
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_wake
```
```
In block/badblocks.c (ffffffff8155c782)
Location: include/linux/seqlock.h:238
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/blk-iocost.c (ffffffff81570fed)
Location: include/linux/seqlock.h:238
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In lib/flex_proportions.c (ffffffff815e8ba7)
Location: include/linux/seqlock.h:238
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81825d73)
Location: include/linux/seqlock.h:238
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-resv.c (ffffffff818297b9)
Location: include/linux/seqlock.h:238
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
```
```
In drivers/md/md.c (ffffffff8196647e)
Location: include/linux/seqlock.h:238
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/gen_stats.c (ffffffff819f733f)
Location: include/linux/seqlock.h:238
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (ffffffff819f79f0)
Location: include/linux/seqlock.h:238
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/neighbour.c (ffffffff81a140d9)
Location: include/linux/seqlock.h:238
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffff81a975fc)
Location: include/linux/seqlock.h:238
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_output.c (ffffffff81a9b6bc)
Location: include/linux/seqlock.h:238
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa5e8c)
Location: include/linux/seqlock.h:238
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff81acbbed)
Location: include/linux/seqlock.h:238
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81ad9f06)
Location: include/linux/seqlock.h:238
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff81af6789)
Location: include/linux/seqlock.h:238
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81afe60a)
Location: include/linux/seqlock.h:238
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0e890)
Location: include/linux/seqlock.h:238
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff81b1c85a)
Location: include/linux/seqlock.h:238
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffff81b2c3ec)
Location: include/linux/seqlock.h:238
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:neigh_hh_output
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
In virt/kvm/eventfd.c (ffff8000100c0c38)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - virt/kvm/eventfd.c:irqfd_wakeup
```
```
In kernel/sched/cputime.c (ffff80001013f200)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/psi.c (ffff800010166d6c)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/sched/psi.c:collect_percpu_times
```
```
In kernel/time/hrtimer.c (ffff8000101a07ac)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (ffff8000101a553c)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:ktime_get_coarse_ts64
  - kernel/time/timekeeping.c:ktime_get_coarse_real_ts64
  - kernel/time/timekeeping.c:timekeeping_max_deferment
  - kernel/time/timekeeping.c:timekeeping_valid_for_hres
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_mono_to_any
  - kernel/time/timekeeping.c:ktime_get_coarse_with_offset
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get_real_ts64
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/time/tick-common.c (ffff8000101b1ae0)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In kernel/time/sched_clock.c (ffff8000101b45c4)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/time/sched_clock.c:sched_clock
```
```
In kernel/time/tick-sched.c (ffff8000101b5220)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/module.c (ffff8000101c107c)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In kernel/auditsc.c (ffff8000101f2228)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In kernel/bpf/core.c (ffff80001025c59c)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In mm/filemap.c (ffff8000102ae018)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In mm/page_alloc.c (ffff800010318828)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (ffff80001032d9e4)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffff800010347c7c)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/namei.c (ffff80001039814c)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_init
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffff8000103aa58c)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:__d_lookup_rcu
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffff8000103b5cf4)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In fs/d_path.c (ffff8000103d1df8)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/d_path.c:__arm64_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
```
```
In fs/userfaultfd.c (ffff8000103f8a70)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
```
In block/badblocks.c (ffff8000105fe60c)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/blk-iocost.c (ffff800010613954)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In drivers/dma-buf/dma-buf.c (ffff800010965cc0)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-resv.c (ffff800010969a98)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
```
```
In drivers/net/phy/fixed_phy.c (ffff8000109da18c)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
```
```
In drivers/md/md.c (ffff800010ae89f8)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/gen_stats.c (ffff800010bbec3c)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (ffff800010bbf5d8)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/dev.c (ffff800010bd03a4)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
```
```
In net/core/neighbour.c (ffff800010be3ef0)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffff800010c5d9c8)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_output.c (ffff800010c637d4)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6e1a0)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffff800010c91d64)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffff800010ca1c94)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffff800010cc0d9c)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffff800010cc71ec)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffff800010cd9110)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffff800010ce87f4)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffff800010cfa444)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In lib/flex_proportions.c (ffff800010d885c4)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
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
In kernel/sched/cputime.c (c038f2a4)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/psi.c (c03b2be8)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/sched/psi.c:collect_percpu_times
```
```
In kernel/time/hrtimer.c (c03ea304)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (c03f053c)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:ktime_get_coarse_ts64
  - kernel/time/timekeeping.c:ktime_get_coarse_real_ts64
  - kernel/time/timekeeping.c:timekeeping_max_deferment
  - kernel/time/timekeeping.c:timekeeping_valid_for_hres
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_real_seconds
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_mono_to_any
  - kernel/time/timekeeping.c:ktime_get_coarse_with_offset
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get_real_ts64
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/time/jiffies.c (c03f282c)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/time/jiffies.c:get_jiffies_64
```
```
In kernel/time/tick-common.c (c03fc2f0)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In kernel/time/sched_clock.c (c03fe1d8)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/time/sched_clock.c:sched_clock
```
```
In kernel/time/tick-sched.c (c03fe6ac)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/module.c (c040882c)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In kernel/cgroup/rstat.c (c041c098)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/auditsc.c (c04326a0)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In kernel/bpf/core.c (c04905f8)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In kernel/bpf/syscall.c (c0492ff0)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_get_stats
```
```
In kernel/events/uprobes.c (c04d5350)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In mm/filemap.c (c04e0e18)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_copy_file_checks
  - mm/filemap.c:generic_remap_checks
  - mm/filemap.c:generic_remap_checks
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/readahead.c (c04eaf88)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
```
```
In mm/shmem.c (c04fab30)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_llseek
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/page_alloc.c (c05331ac)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/page_io.c (c0538b4c)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - mm/page_io.c:generic_swapfile_activate
```
```
In mm/swapfile.c (c053edd0)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/userfaultfd.c (c0564084)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/open.c (c0567510)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In fs/read_write.c (c056ab30)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:default_llseek
  - fs/read_write.c:generic_file_llseek
```
```
In fs/stat.c (c0572608)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/stat.c:generic_fillattr
```
```
In fs/exec.c (c05744b8)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file
```
```
In fs/namei.c (c057e9d8)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_init
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:__follow_mount_rcu
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
  - fs/namei.c:legitimize_path
```
```
In fs/ioctl.c (c05836d4)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/ioctl.c:file_ioctl
  - fs/ioctl.c:ioctl_preallocate
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/dcache.c (c058b52c)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:__d_lookup_rcu
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (c0595334)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In fs/d_path.c (c05acef4)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/d_path.c:__se_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
```
In fs/stack.c (c05ad0fc)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/stack.c:fsstack_copy_inode_size
```
```
In fs/buffer.c (c05b409c)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/buffer.c:guard_bio_eod
  - fs/buffer.c:block_write_full_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:init_page_buffers
```
```
In fs/block_dev.c (c05b8ef4)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:blkdev_read_iter
  - fs/block_dev.c:check_disk_size_change
  - fs/block_dev.c:block_llseek
  - fs/block_dev.c:set_init_blocksize
```
```
In fs/direct-io.c (c05bcba0)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (c05bdad0)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/userfaultfd.c (c05cca8c)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_unregister
```
```
In fs/locks.c (c05e1004)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/locks.c:flock64_to_posix_lock
```
```
In fs/coredump.c (c05f0234)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/coredump.c:dump_truncate
```
```
In fs/iomap/buffered-io.c (c05f321c)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_write_failed
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/buffered-io.c:iomap_read_inline_data
  - fs/iomap/buffered-io.c:iomap_adjust_read_range
```
```
In fs/iomap/direct-io.c (c05f61ac)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/iomap/seek.c (c05f6a40)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/iomap/seek.c:iomap_seek_data
  - fs/iomap/seek.c:iomap_seek_hole
```
```
In fs/iomap/swapfile.c (c05f7350)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/iomap/swapfile.c:iomap_swapfile_activate
```
```
In fs/ext4/extents.c (c062db0c)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (c0631f94)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/inline.c (c063e130)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (c064ba4c)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:mpage_submit_page
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/ioctl.c (c064c500)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
```
```
In fs/ext4/mballoc.c (c064f6fc)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
```
```
In fs/ext4/migrate.c (c0659f64)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (c065c394)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/readpage.c (c0666bf4)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/super.c (c0676074)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_read
```
```
In fs/ext4/xattr.c (c068841c)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
```
In fs/squashfs/dir.c (c069c528)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/squashfs/dir.c:squashfs_readdir
```
```
In fs/squashfs/file.c (c069d52c)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_readpage
```
```
In fs/squashfs/namei.c (c069e94c)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/squashfs/namei.c:squashfs_lookup
```
```
In fs/squashfs/super.c (c069efd8)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In fs/squashfs/symlink.c (c069f7e4)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (c069fc30)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/fat/cache.c (c06a296c)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_bmap
```
```
In fs/fat/file.c (c06a8480)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
```
```
In fs/fat/inode.c (c06ab72c)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In fs/ecryptfs/file.c (c06b0068)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
```
```
In fs/ecryptfs/inode.c (c06b1138)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_inode_newsize_ok
  - fs/ecryptfs/inode.c:truncate_upper
  - fs/ecryptfs/inode.c:ecryptfs_link
```
```
In fs/ecryptfs/mmap.c (c06b3b28)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (c06b3f74)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/ecryptfs/crypto.c (c06b5df8)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_i_size_init
```
```
In fs/fuse/dev.c (c06c11a8)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_retrieve
```
```
In fs/fuse/dir.c (c06c3968)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/file.c (c06ca42c)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_do_truncate
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_flush_writepages
  - fs/fuse/file.c:fuse_file_read_iter
```
```
In ipc/shm.c (c06e2038)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
```
In security/selinux/selinuxfs.c (c070afcc)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/integrity/ima/ima_crypto.c (c075f684)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In block/blk-core.c (c078f2b8)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
```
In block/ioctl.c (c07a3cfc)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blk_ioctl_discard
```
```
In block/genhd.c (c07a5bd4)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - block/genhd.c:disk_map_sector_rcu
  - block/genhd.c:disk_map_sector_rcu
  - block/genhd.c:disk_part_iter_next
```
```
In block/partition-generic.c (c07a7690)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - block/partition-generic.c:part_size_show
```
```
In block/badblocks.c (c07aa0e8)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/partitions/efi.c (c07b1860)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
```
```
In block/blk-iocost.c (c07c1348)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In block/blk-zoned.c (c07c74d0)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
```
```
In drivers/block/loop.c (c0a0587c)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/block/loop.c:get_size
```
```
In drivers/dax/super.c (c0a3a750)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/dax/super.c:__bdev_dax_supported
```
```
In drivers/dma-buf/dma-buf.c (c0a3c888)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-resv.c (c0a3f3a0)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
```
```
In drivers/net/loopback.c (c0ab81f4)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_get_stats64
```
```
In drivers/net/phy/fixed_phy.c (c0ac0d4c)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
```
```
In drivers/net/tun.c (c0ac1fa0)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_get_stats64
```
```
In drivers/md/md.c (c0bd4630)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:rdev_size_store
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:super_1_load
```
```
In drivers/md/md-bitmap.c (c0bd95fc)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
```
In drivers/md/dm-table.c (c0be16bc)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_area_is_invalid
```
```
In drivers/md/dm-linear.c (c0be4298)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/md/dm-linear.c:linear_prepare_ioctl
```
```
In net/core/sock.c (c0ccc944)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/sock.c:sock_gettstamp
```
```
In net/core/gen_stats.c (c0cda820)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (c0cdb080)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/dev.c (c0ceaf00)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
```
```
In net/core/neighbour.c (c0cfe4ac)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/drop_monitor.c (c0d347dc)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
```
```
In net/core/devlink.c (c0d4250c)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_stats_put
```
```
In net/ipv4/inetpeer.c (c0d6cda0)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_output.c (c0d72c50)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (c0d7b05c)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_get_local_port_range
```
```
In net/ipv4/tcp_metrics.c (c0da0a90)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (c0daead8)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/af_inet.c (c0db64c4)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:snmp_get_cpu_field64
```
```
In net/ipv4/ping.c (c0dcbcd4)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/ip_tunnel_core.c (c0dcdbb8)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64
```
```
In net/ipv4/sysctl_net_ipv4.c (c0dd2474)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (c0de31d4)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (c0df09c8)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (c0dff594)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In lib/flex_proportions.c (c0e833f0)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
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
In kernel/sched/cputime.c (c00000000018e3a0)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/psi.c (c0000000001bdf24)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/sched/psi.c:collect_percpu_times
```
```
In kernel/time/hrtimer.c (c0000000002016bc)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (c000000000207340)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:ktime_get_coarse_ts64
  - kernel/time/timekeeping.c:ktime_get_coarse_real_ts64
  - kernel/time/timekeeping.c:timekeeping_max_deferment
  - kernel/time/timekeeping.c:timekeeping_valid_for_hres
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_mono_to_any
  - kernel/time/timekeeping.c:ktime_get_coarse_with_offset
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get_resolution_ns
  - kernel/time/timekeeping.c:ktime_get
  - kernel/time/timekeeping.c:ktime_get_real_ts64
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/time/tick-common.c (c000000000216cac)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In kernel/time/tick-sched.c (c000000000219f90)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/module.c (c000000000227964)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In kernel/auditsc.c (c0000000002669b8)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In kernel/bpf/core.c (c000000000301560)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In mm/filemap.c (c000000000363140)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In mm/page_alloc.c (c0000000003eb0a4)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (c0000000004060a0)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (c000000000425d00)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/namei.c (c000000000492540)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_init
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (c0000000004a5548)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:__d_lookup_rcu
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (c0000000004b20a0)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In fs/d_path.c (c0000000004d46c4)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/d_path.c:__se_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
```
```
In fs/userfaultfd.c (c0000000004ffe78)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_unregister
```
```
In block/badblocks.c (c000000000798d30)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/blk-iocost.c (c0000000007b277c)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In drivers/dma-buf/dma-buf.c (c000000000a1d2e0)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-resv.c (c000000000a212b0)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
```
```
In drivers/net/phy/fixed_phy.c (c000000000a9c038)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
```
```
In drivers/md/md.c (c000000000bd1ac4)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/gen_stats.c (c000000000c97ff0)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (c000000000c9896c)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/dev.c (c000000000cae0a0)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
```
```
In net/core/neighbour.c (c000000000cc7460)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (c000000000d5fecc)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_output.c (c000000000d66bb0)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (c000000000d73d34)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (c000000000da23e8)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (c000000000db4f6c)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (c000000000ddae18)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (c000000000de3e70)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (c000000000dfa534)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (c000000000e0bf74)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (c000000000e1f468)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In lib/flex_proportions.c (c000000000ec8c8c)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
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
In kernel/sched/cputime.c (ffffffe0000ed924)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/psi.c (ffffffe000108b34)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/sched/psi.c:collect_percpu_times
```
```
In kernel/time/hrtimer.c (ffffffe00012e0ca)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (ffffffe000131994)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:ktime_get_coarse_ts64
  - kernel/time/timekeeping.c:ktime_get_coarse_real_ts64
  - kernel/time/timekeeping.c:timekeeping_max_deferment
  - kernel/time/timekeeping.c:timekeeping_valid_for_hres
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_mono_to_any
  - kernel/time/timekeeping.c:ktime_get_coarse_with_offset
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get_real_ts64
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/time/tick-common.c (ffffffe00013a32a)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In kernel/time/sched_clock.c (ffffffe00013a97a)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/time/sched_clock.c:sched_clock
```
```
In kernel/time/tick-sched.c (ffffffe00013ae3e)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/module.c (ffffffe0001433b8)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In kernel/auditsc.c (ffffffe000165944)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In kernel/bpf/core.c (ffffffe00019b67c)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In mm/page_alloc.c (ffffffe00021e9e4)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (ffffffe00022c18c)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In fs/namei.c (ffffffe000265fae)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_init
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffe00027024a)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:__d_lookup_rcu
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffe00027987a)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In fs/d_path.c (ffffffe00028d72c)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/d_path.c:__se_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
```
```
In fs/userfaultfd.c (ffffffe0002a786c)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_unregister
```
```
In block/badblocks.c (ffffffe00043a4b2)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/blk-iocost.c (ffffffe00044b058)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In drivers/dma-buf/dma-buf.c (ffffffe0005d298e)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-resv.c (ffffffe0005d5568)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
```
```
In drivers/net/phy/fixed_phy.c (ffffffe000624fd4)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
```
```
In drivers/md/md.c (ffffffe0006dc88c)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/gen_stats.c (ffffffe00074ca46)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (ffffffe00074d046)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/dev.c (ffffffe00075abda)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
```
```
In net/core/neighbour.c (ffffffe00076a9d0)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffe0007c628c)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_output.c (ffffffe0007cae1e)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d28bc)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffe0007f1e0a)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffe0007feca0)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffe000815ff0)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffe00081b784)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082957c)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffe000836868)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffe000843e04)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In lib/flex_proportions.c (ffffffe0008b262a)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
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
In kernel/sched/cputime.c (ffffffff810d9a1e)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/psi.c (ffffffff810fb400)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/sched/psi.c:collect_percpu_times
```
```
In kernel/time/hrtimer.c (ffffffff8112fae7)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (ffffffff81133adb)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:ktime_get_coarse_ts64
  - kernel/time/timekeeping.c:ktime_get_coarse_real_ts64
  - kernel/time/timekeeping.c:timekeeping_max_deferment
  - kernel/time/timekeeping.c:timekeeping_valid_for_hres
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_mono_to_any
  - kernel/time/timekeeping.c:ktime_get_coarse_with_offset
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get_real_ts64
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/time/tick-common.c (ffffffff8113f462)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff81140f25)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/module.c (ffffffff8114aab6)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In kernel/auditsc.c (ffffffff81175a29)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In kernel/bpf/core.c (ffffffff811d4a9b)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In mm/filemap.c (ffffffff8121998b)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In mm/page_alloc.c (ffffffff81279147)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (ffffffff812894c5)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff8129eded)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/namei.c (ffffffff812e7143)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_init
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffff812f37a5)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:__d_lookup_rcu
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff812fbd05)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In fs/d_path.c (ffffffff81312e6b)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
```
```
In fs/userfaultfd.c (ffffffff81332177)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
```
In block/badblocks.c (ffffffff814f58e7)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/blk-iocost.c (ffffffff8150851d)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In drivers/dma-buf/dma-buf.c (ffffffff8171a1aa)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8171c92b)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8178475a)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
```
```
In drivers/md/md.c (ffffffff81839c5c)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/gen_stats.c (ffffffff818c37bb)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (ffffffff818c3e40)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/dev.c (ffffffff818d2407)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
```
```
In net/core/neighbour.c (ffffffff818e4039)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffff8194d4dc)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_output.c (ffffffff81952702)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195b3c0)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff8197ea3d)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff8198bfd0)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff819a6aa9)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff819ad46a)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff819bc830)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff819c9726)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffff819d6f24)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In lib/flex_proportions.c (ffffffff81a4dc87)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
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
In kernel/sched/cputime.c (ffffffff810c8a5f)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/sched/cputime.c:task_gtime
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/psi.c (ffffffff810eb620)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/sched/psi.c:collect_percpu_times
```
```
In kernel/time/hrtimer.c (ffffffff81122557)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (ffffffff8112653b)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:ktime_get_coarse_ts64
  - kernel/time/timekeeping.c:ktime_get_coarse_real_ts64
  - kernel/time/timekeeping.c:timekeeping_max_deferment
  - kernel/time/timekeeping.c:timekeeping_valid_for_hres
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_mono_to_any
  - kernel/time/timekeeping.c:ktime_get_coarse_with_offset
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get_real_ts64
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/time/tick-common.c (ffffffff81131f92)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff81133cc5)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/module.c (ffffffff8113dd66)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In kernel/auditsc.c (ffffffff81168bc9)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In kernel/bpf/core.c (ffffffff811c785b)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In mm/filemap.c (ffffffff8120cb9b)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In mm/page_alloc.c (ffffffff8126b037)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (ffffffff8127b365)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff8129092d)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/namei.c (ffffffff812d7d83)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_init
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffff812e43d5)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:__d_lookup_rcu
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff812ec925)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In fs/d_path.c (ffffffff81303a7b)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
```
```
In fs/userfaultfd.c (ffffffff81322d37)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
```
In block/badblocks.c (ffffffff814e5df7)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/blk-iocost.c (ffffffff814f89cd)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In drivers/dma-buf/dma-buf.c (ffffffff816f361a)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-resv.c (ffffffff816f5d8b)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
```
```
In drivers/net/phy/fixed_phy.c (ffffffff817640aa)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
```
```
In drivers/md/md.c (ffffffff818012cc)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/gen_stats.c (ffffffff8187d6fb)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (ffffffff8187dd80)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/dev.c (ffffffff8188c297)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
```
```
In net/core/neighbour.c (ffffffff8189de79)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffff81906fcc)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_output.c (ffffffff8190c1f2)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81914eb0)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff819384fd)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81945a90)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff81960569)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81969a9a)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81979620)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff81986516)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffff81993ce4)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In lib/flex_proportions.c (ffffffff81a0ad77)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
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
In kernel/sched/cputime.c (ffffffff810d5d5e)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/psi.c (ffffffff810f85c0)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/sched/psi.c:collect_percpu_times
```
```
In kernel/time/hrtimer.c (ffffffff8112d807)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (ffffffff811317fb)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:ktime_get_coarse_ts64
  - kernel/time/timekeeping.c:ktime_get_coarse_real_ts64
  - kernel/time/timekeeping.c:timekeeping_max_deferment
  - kernel/time/timekeeping.c:timekeeping_valid_for_hres
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_mono_to_any
  - kernel/time/timekeeping.c:ktime_get_coarse_with_offset
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get_real_ts64
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/time/tick-common.c (ffffffff8113d182)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8113edd5)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/module.c (ffffffff81148966)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In kernel/auditsc.c (ffffffff811737f9)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In kernel/bpf/core.c (ffffffff811d286b)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In mm/filemap.c (ffffffff8121772b)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In mm/page_alloc.c (ffffffff81276ee7)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (ffffffff812872d5)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff8129cbfd)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/namei.c (ffffffff812e4f53)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_init
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffff812f15b5)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:__d_lookup_rcu
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff812f9af5)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In fs/d_path.c (ffffffff81310c5b)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
```
```
In fs/userfaultfd.c (ffffffff8132fc47)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
```
In block/badblocks.c (ffffffff814f1977)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/blk-iocost.c (ffffffff815045ad)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81758f7a)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8175b6fb)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
```
```
In drivers/net/phy/fixed_phy.c (ffffffff817b4b0a)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
```
```
In drivers/md/md.c (ffffffff8188928c)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/gen_stats.c (ffffffff819147bb)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (ffffffff81914e40)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/dev.c (ffffffff81923407)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
```
```
In net/core/neighbour.c (ffffffff81935069)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/netfilter/nf_conntrack_core.c (ffffffff8199ea88)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_core.c:nf_ct_iterate_cleanup
  - net/netfilter/nf_conntrack_core.c:gc_worker
  - net/netfilter/nf_conntrack_core.c:early_drop
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_tuple_taken
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_find_get
```
```
In net/netfilter/nf_conntrack_standalone.c (ffffffff819a115e)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_standalone.c:ct_seq_start
```
```
In net/ipv4/inetpeer.c (ffffffff819b7cac)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_output.c (ffffffff819bced2)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c5b90)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff819e920d)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff819f67e0)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff81a11349)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81a17d0a)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a272b0)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff81a341a6)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffff81a419a4)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In lib/flex_proportions.c (ffffffff81aba077)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
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
In kernel/sched/cputime.c (ffffffff810e1678)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/psi.c (ffffffff81103700)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/sched/psi.c:collect_percpu_times
```
```
In kernel/time/hrtimer.c (ffffffff8113a137)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (ffffffff8113e21b)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_update_offsets_now
  - kernel/time/timekeeping.c:ktime_get_coarse_ts64
  - kernel/time/timekeeping.c:ktime_get_coarse_real_ts64
  - kernel/time/timekeeping.c:timekeeping_max_deferment
  - kernel/time/timekeeping.c:timekeeping_valid_for_hres
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_raw
  - kernel/time/timekeeping.c:ktime_mono_to_any
  - kernel/time/timekeeping.c:ktime_get_coarse_with_offset
  - kernel/time/timekeeping.c:ktime_get_with_offset
  - kernel/time/timekeeping.c:ktime_get_real_ts64
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/time/tick-common.c (ffffffff81149c72)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8114b945)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/module.c (ffffffff811555d6)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In kernel/auditsc.c (ffffffff8118103b)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In kernel/bpf/core.c (ffffffff811e0b5b)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In mm/filemap.c (ffffffff812267db)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In mm/page_alloc.c (ffffffff81286aa7)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (ffffffff81297a55)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff812acc61)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/namei.c (ffffffff812f5ed3)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_init
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffff81302777)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:__d_lookup_rcu
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff8130ae15)
Location: include/linux/seqlock.h:218
Inline: True
```
```
In fs/d_path.c (ffffffff81322490)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
```
```
In fs/userfaultfd.c (ffffffff813425c7)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
```
In block/badblocks.c (ffffffff8150a9d7)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/blk-iocost.c (ffffffff8151db5d)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81774417)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-resv.c (ffffffff817769b6)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
```
```
In drivers/net/phy/fixed_phy.c (ffffffff817ceada)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
```
```
In drivers/md/md.c (ffffffff818a69bc)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/gen_stats.c (ffffffff8193598b)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (ffffffff8193638f)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/dev.c (ffffffff81944840)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
```
```
In net/core/neighbour.c (ffffffff81956779)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffff819c1521)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_output.c (ffffffff819c67e2)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819cf672)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff819f2f6d)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81a00a07)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff81a1bcb9)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81a227aa)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a328e0)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3fb0c)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffff81a4d604)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In lib/flex_proportions.c (ffffffff81ac64c7)
Location: include/linux/seqlock.h:218
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
```
</details>
</li>
</ul>

## Differences

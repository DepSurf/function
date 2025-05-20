# Function: <code>__read_seqcount_begin</code>

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
In kernel/sched/cputime.c (ffffffff810b18fe)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/hrtimer.c (ffffffff810eea3f)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (ffffffff810f42d3)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_mono_to_any
  - kernel/time/timekeeping.c:get_device_system_crosststamp
  - kernel/time/timekeeping.c:current_kernel_time64
  - kernel/time/timekeeping.c:ktime_get_resolution_ns
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_snapshot
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
In kernel/time/tick-common.c (ffffffff810fc711)
Location: include/linux/seqlock.h:107
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff810fe717)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
```
In kernel/auditsc.c (ffffffff81128b51)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In mm/filemap.c (ffffffff8118d619)
Location: include/linux/seqlock.h:107
Inline: True
```
```
In mm/page_alloc.c (ffffffff81192528)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/hugetlb.c (ffffffff811dae42)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_buddy_huge_page
  - mm/hugetlb.c:alloc_huge_page
```
```
In mm/mempolicy.c (ffffffff811e0860)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
```
```
In mm/slub.c (ffffffff811eab53)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/namei.c (ffffffff812162d9)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - fs/namei.c:set_root_rcu
  - fs/namei.c:set_root_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:lookup_fast
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
```
```
In fs/dcache.c (ffffffff81222f11)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
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
In fs/namespace.c (ffffffff8122d9f8)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
```
In fs/userfaultfd.c (ffffffff8125a238)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
```
In lib/flex_proportions.c (ffffffff813e9959)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_single
  - lib/flex_proportions.c:fprop_fraction_percpu
```
```
In drivers/dma-buf/dma-buf.c (ffffffff815a33d6)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/reservation.c (ffffffff815a4fea)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
```
```
In drivers/md/md.c (ffffffff8168dbb6)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - drivers/md/md.c:md_is_badblock
  - drivers/md/md.c:badblocks_show
  - drivers/md/md.c:super_1_sync
```
```
In net/core/neighbour.c (ffffffff81725904)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
  - net/core/neighbour.c:neigh_fill_info
```
```
In net/ipv4/inetpeer.c (ffffffff81758545)
Location: include/linux/seqlock.h:107
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff8175d1fa)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81763a09)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff81781363)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff8178c538)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/inet_fragment.c (ffffffff817a1898)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:get_frag_bucket_locked
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
```
```
In net/ipv4/ping.c (ffffffff817a281e)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff817a5b0a)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b46ec)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (ffffffff817c539c)
Location: include/linux/seqlock.h:107
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
In kernel/sched/cputime.c (ffffffff810b43a3)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/hrtimer.c (ffffffff810f5b3f)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (ffffffff810fdbd7)
Location: include/linux/seqlock.h:107
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
```
```
In kernel/time/tick-common.c (ffffffff81103a6f)
Location: include/linux/seqlock.h:107
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff81105aa3)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
```
In kernel/auditsc.c (ffffffff81130cea)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In mm/filemap.c (ffffffff811a0209)
Location: include/linux/seqlock.h:107
Inline: True
```
```
In mm/page_alloc.c (ffffffff811ab0d6)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/hugetlb.c (ffffffff811fae6c)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__alloc_buddy_huge_page
```
```
In mm/mempolicy.c (ffffffff811feb29)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
```
```
In mm/slub.c (ffffffff8120a190)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/namei.c (ffffffff8123def8)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:lookup_fast
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:set_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffff8124ec15)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - fs/dcache.c:is_subdir
  - fs/dcache.c:SyS_getcwd
  - fs/dcache.c:__dentry_path
  - fs/dcache.c:d_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff812561f1)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
```
In fs/userfaultfd.c (ffffffff81282a75)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
```
In block/badblocks.c (ffffffff81412faf)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In lib/flex_proportions.c (ffffffff8142fe39)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
```
```
In drivers/dma-buf/dma-buf.c (ffffffff815fa4a2)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/reservation.c (ffffffff815fc079)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8164c512)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
```
```
In drivers/md/md.c (ffffffff816f2760)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/gen_stats.c (ffffffff81776735)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/neighbour.c (ffffffff81790712)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffff817c4825)
Location: include/linux/seqlock.h:107
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff817c9fc7)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817d02ce)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff817ee830)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff817f9b4e)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/inet_fragment.c (ffffffff8180f566)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:get_frag_bucket_locked
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
```
```
In net/ipv4/ping.c (ffffffff81810087)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8181379a)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff818203bc)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/ipv6/ip6_output.c (ffffffff81831f91)
Location: include/linux/seqlock.h:107
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
In kernel/sched/cputime.c (ffffffff810ba9c3)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/hrtimer.c (ffffffff810fcaff)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (ffffffff811009c7)
Location: include/linux/seqlock.h:107
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
```
```
In kernel/time/tick-common.c (ffffffff8110b158)
Location: include/linux/seqlock.h:107
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8110d1ef)
Location: include/linux/seqlock.h:107
Inline: True
```
```
In kernel/auditsc.c (ffffffff8113aa5a)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In mm/filemap.c (ffffffff811af649)
Location: include/linux/seqlock.h:107
Inline: True
```
```
In mm/page_alloc.c (ffffffff811bade7)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (ffffffff8120b96c)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__alloc_buddy_huge_page
```
```
In mm/mempolicy.c (ffffffff81210369)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
```
```
In mm/slub.c (ffffffff8121c200)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/namei.c (ffffffff81250cd8)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:lookup_fast
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:set_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffff81261c25)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - fs/dcache.c:is_subdir
  - fs/dcache.c:SyS_getcwd
  - fs/dcache.c:__dentry_path
  - fs/dcache.c:d_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff812695e1)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
```
In fs/userfaultfd.c (ffffffff81296595)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
```
In block/badblocks.c (ffffffff8142e4df)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In lib/flex_proportions.c (ffffffff8144c069)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81628772)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/reservation.c (ffffffff8162ac93)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8167e222)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
```
```
In drivers/md/md.c (ffffffff81723e7f)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/gen_stats.c (ffffffff817a39b7)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (ffffffff817a4021)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/neighbour.c (ffffffff817bdfc2)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffff817f4345)
Location: include/linux/seqlock.h:107
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff817f9280)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8180010e)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff8181f240)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff8182aa1e)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/inet_fragment.c (ffffffff81840ab6)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:get_frag_bucket_locked
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
```
```
In net/ipv4/ping.c (ffffffff818415d7)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81844caa)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81851bfc)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff8185926c)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffff81863f35)
Location: include/linux/seqlock.h:107
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
In kernel/sched/cputime.c (ffffffff810b5293)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/hrtimer.c (ffffffff810ff030)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (ffffffff81102b07)
Location: include/linux/seqlock.h:107
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
```
```
In kernel/time/tick-common.c (ffffffff8110d048)
Location: include/linux/seqlock.h:107
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8110f05e)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
```
In kernel/auditsc.c (ffffffff8113c095)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In mm/filemap.c (ffffffff811b654c)
Location: include/linux/seqlock.h:107
Inline: True
```
```
In mm/page_alloc.c (ffffffff811c304b)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (ffffffff81214607)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff81227c74)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/namei.c (ffffffff8125c3b6)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:set_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffff8126f4e5)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - fs/dcache.c:is_subdir
  - fs/dcache.c:SyS_getcwd
  - fs/dcache.c:__dentry_path
  - fs/dcache.c:d_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff81276d4f)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
```
In fs/userfaultfd.c (ffffffff812a3da6)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
```
In block/badblocks.c (ffffffff8143b7e2)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/dma-buf/dma-buf.c (ffffffff8163e3d0)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/reservation.c (ffffffff8164038c)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
```
```
In drivers/net/phy/fixed_phy.c (ffffffff81693369)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
```
```
In drivers/md/md.c (ffffffff8173c289)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/gen_stats.c (ffffffff817c1abf)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (ffffffff817c2173)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/neighbour.c (ffffffff817dca22)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffff81814775)
Location: include/linux/seqlock.h:107
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff8181965d)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8182100d)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff8183fdfc)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff8184bc2a)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/inet_fragment.c (ffffffff818623a8)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:get_frag_bucket_locked
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
```
```
In net/ipv4/ping.c (ffffffff81862e17)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8186680a)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81874d7c)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff8187d0e2)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffff8188947e)
Location: include/linux/seqlock.h:107
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In lib/flex_proportions.c (ffffffff818ec819)
Location: include/linux/seqlock.h:107
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
In kernel/sched/cputime.c (ffffffff810bc443)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/hrtimer.c (ffffffff81109e10)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (ffffffff8110daa7)
Location: include/linux/seqlock.h:108
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
```
```
In kernel/time/tick-common.c (ffffffff811182c8)
Location: include/linux/seqlock.h:108
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8111a07e)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
```
In kernel/auditsc.c (ffffffff81148e15)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In mm/filemap.c (ffffffff811ca8b4)
Location: include/linux/seqlock.h:108
Inline: True
```
```
In mm/page_alloc.c (ffffffff811d82f7)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (ffffffff8122f18b)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff81243dbc)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/namei.c (ffffffff812838a0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:set_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffff81291e05)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/dcache.c:is_subdir
  - fs/dcache.c:SyS_getcwd
  - fs/dcache.c:__dentry_path
  - fs/dcache.c:d_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:prepend_path
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff8129978f)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
```
In fs/userfaultfd.c (ffffffff812c7229)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
```
In block/badblocks.c (ffffffff814677f2)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/dma-buf/dma-buf.c (ffffffff816a71d3)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/reservation.c (ffffffff816a937c)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
```
```
In drivers/net/phy/fixed_phy.c (ffffffff816fd279)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
```
```
In drivers/md/md.c (ffffffff817ade39)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/gen_stats.c (ffffffff8183b4d8)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (ffffffff8183bb61)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/neighbour.c (ffffffff818575f2)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffff81893684)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (ffffffff81897c88)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8189fdcd)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff818bf1a7)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff818cb8ca)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/inet_fragment.c (ffffffff818e2498)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:get_frag_bucket_locked
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
```
```
In net/ipv4/ping.c (ffffffff818e2f4f)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff818e69aa)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f56ec)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff818fde90)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffff8190996e)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In lib/flex_proportions.c (ffffffff819727e9)
Location: include/linux/seqlock.h:108
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
In kernel/sched/cputime.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (ffffffff81119489)
Location: include/linux/seqlock.h:108
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
```
```
In kernel/time/tick-common.c (ffffffff81124e48)
Location: include/linux/seqlock.h:108
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff81126afd)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/auditsc.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In mm/filemap.c (0)
Location: include/linux/seqlock.h:108
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/namei.c (ffffffff812aa846)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:set_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffff812b7898)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff812bf633)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
```
In fs/d_path.c (ffffffff812d3d0b)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
```
```
In fs/userfaultfd.c (ffffffff812f0194)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
```
In block/badblocks.c (ffffffff8149b662)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/dma-buf/dma-buf.c (ffffffff816e3698)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/reservation.c (ffffffff816e53ee)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8173b379)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
```
```
In drivers/md/md.c (ffffffff817f3ef0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/gen_stats.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/neighbour.c (ffffffff818a278f)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/seqlock.h:108
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f48eb)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff81914d9a)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81921d43)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff819398bd)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8193d4da)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194bb9c)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In lib/flex_proportions.c (ffffffff819cec00)
Location: include/linux/seqlock.h:108
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
In kernel/sched/cputime.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/psi.c (ffffffff810ef020)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/sched/psi.c:update_stats
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (ffffffff81124979)
Location: include/linux/seqlock.h:108
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
```
```
In kernel/time/tick-common.c (ffffffff81130548)
Location: include/linux/seqlock.h:108
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff811321dd)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/auditsc.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In mm/filemap.c (0)
Location: include/linux/seqlock.h:108
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/namei.c (ffffffff812bc7bc)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:set_root
  - fs/namei.c:set_root
  - fs/namei.c:set_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffff812ccf6c)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff812d4842)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
```
In fs/d_path.c (ffffffff812e8f5b)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
```
```
In fs/userfaultfd.c (ffffffff813050d4)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
```
In block/badblocks.c (ffffffff814b5972)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81706a18)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/reservation.c (ffffffff817083e7)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8175eb2d)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
```
```
In drivers/md/md.c (ffffffff8181fe20)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/gen_stats.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/neighbour.c (ffffffff818c596c)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/seqlock.h:108
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819226ae)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff8194354a)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81950b6c)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff8196954d)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8196d2aa)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81980fb0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In lib/flex_proportions.c (ffffffff81a080c0)
Location: include/linux/seqlock.h:108
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
In kernel/sched/cputime.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/psi.c (ffffffff810f631c)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/sched/psi.c:collect_percpu_times
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (ffffffff8112f2b0)
Location: include/linux/seqlock.h:108
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
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/seqlock.h:108
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8113cb49)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/auditsc.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In mm/filemap.c (0)
Location: include/linux/seqlock.h:108
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/namei.c (ffffffff812d93d5)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:set_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffff812e9b64)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff812f1d51)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
```
In fs/d_path.c (ffffffff813077eb)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
```
```
In fs/userfaultfd.c (ffffffff81326e00)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
```
In block/badblocks.c (ffffffff814e3eb2)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81741a5b)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/reservation.c (ffffffff81743f2c)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8179c16a)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
```
```
In drivers/md/md.c (ffffffff81862115)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/gen_stats.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/neighbour.c (ffffffff819119bf)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81984e14)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff819b5439)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff819d019d)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff819d6bc4)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e615b)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In lib/flex_proportions.c (ffffffff81a77a25)
Location: include/linux/seqlock.h:108
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
In kernel/sched/cputime.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/psi.c (ffffffff811020bc)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/sched/psi.c:collect_percpu_times
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (ffffffff8113b270)
Location: include/linux/seqlock.h:108
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
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/seqlock.h:108
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff811488e9)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/auditsc.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In mm/filemap.c (0)
Location: include/linux/seqlock.h:108
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/namei.c (ffffffff812eaee5)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:set_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffff812fb704)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff81303911)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
```
In fs/d_path.c (ffffffff8131a85b)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
```
```
In fs/userfaultfd.c (ffffffff81339b90)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
```
In block/badblocks.c (ffffffff814fd272)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/blk-iocost.c (ffffffff8150ff14)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81765be0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8176806c)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
```
```
In drivers/net/phy/fixed_phy.c (ffffffff817bfc1a)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
```
```
In drivers/md/md.c (ffffffff81893d45)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/gen_stats.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/neighbour.c (ffffffff8194402f)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bb887)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff819ec159)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff81a06ced)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81a0d6b4)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a1d14b)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In lib/flex_proportions.c (ffffffff81aaee15)
Location: include/linux/seqlock.h:108
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
In kernel/sched/cputime.c (0)
Location: include/linux/seqlock.h:124
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/psi.c (ffffffff8110cd4c)
Location: include/linux/seqlock.h:124
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff81145fdb)
Location: include/linux/seqlock.h:124
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (ffffffff8114a2c0)
Location: include/linux/seqlock.h:124
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
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/seqlock.h:124
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff81158529)
Location: include/linux/seqlock.h:124
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/auditsc.c (0)
Location: include/linux/seqlock.h:124
Inline: True
Inline callers:
  - kernel/auditsc.c:handle_path
```
```
In mm/filemap.c (0)
Location: include/linux/seqlock.h:124
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/seqlock.h:124
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/seqlock.h:124
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (0)
Location: include/linux/seqlock.h:124
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In fs/namei.c (ffffffff81322b02)
Location: include/linux/seqlock.h:124
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:__follow_mount_rcu
  - fs/namei.c:choose_mountpoint
  - fs/namei.c:choose_mountpoint
  - fs/namei.c:set_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffff813343c4)
Location: include/linux/seqlock.h:124
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_hash_and_lookup
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff8133d6e1)
Location: include/linux/seqlock.h:124
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
```
In fs/d_path.c (ffffffff81354784)
Location: include/linux/seqlock.h:124
Inline: True
Inline callers:
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
```
In fs/userfaultfd.c (ffffffff81372eea)
Location: include/linux/seqlock.h:124
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_wake
```
```
In block/badblocks.c (ffffffff8155c6e2)
Location: include/linux/seqlock.h:124
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/blk-iocost.c (ffffffff81570fc4)
Location: include/linux/seqlock.h:124
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In lib/flex_proportions.c (ffffffff815e8b85)
Location: include/linux/seqlock.h:124
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81825ebd)
Location: include/linux/seqlock.h:124
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8182959c)
Location: include/linux/seqlock.h:124
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
```
```
In drivers/md/md.c (ffffffff819663e7)
Location: include/linux/seqlock.h:124
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/gen_stats.c (0)
Location: include/linux/seqlock.h:124
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (0)
Location: include/linux/seqlock.h:124
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/neighbour.c (ffffffff81a1409f)
Location: include/linux/seqlock.h:124
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/seqlock.h:124
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (ffffffff81a9b663)
Location: include/linux/seqlock.h:124
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa5f65)
Location: include/linux/seqlock.h:124
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff81acbde4)
Location: include/linux/seqlock.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81ad9ebf)
Location: include/linux/seqlock.h:124
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff81af676d)
Location: include/linux/seqlock.h:124
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81afe5f4)
Location: include/linux/seqlock.h:124
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0e83b)
Location: include/linux/seqlock.h:124
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/seqlock.h:124
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffff81b2c393)
Location: include/linux/seqlock.h:124
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
In virt/kvm/eventfd.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - virt/kvm/eventfd.c:irqfd_wakeup
```
```
In kernel/sched/cputime.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/psi.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/sched/psi.c:collect_percpu_times
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (0)
Location: include/linux/seqlock.h:108
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
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/seqlock.h:108
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/auditsc.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In mm/filemap.c (ffff8000102adfec)
Location: include/linux/seqlock.h:108
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffff800010347ba8)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/namei.c (ffff800010394598)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:set_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
```
In fs/d_path.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/d_path.c:__arm64_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
```
```
In fs/userfaultfd.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
```
In block/badblocks.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/blk-iocost.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
```
```
In drivers/net/phy/fixed_phy.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
```
```
In drivers/md/md.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/gen_stats.c (ffff800010bbec18)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/neighbour.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In lib/flex_proportions.c (0)
Location: include/linux/seqlock.h:108
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
In kernel/sched/cputime.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/psi.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/sched/psi.c:collect_percpu_times
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (0)
Location: include/linux/seqlock.h:108
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
```
```
In kernel/time/jiffies.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/time/jiffies.c:get_jiffies_64
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/seqlock.h:108
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/cgroup/rstat.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/auditsc.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_get_stats
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/seqlock.h:108
Inline: True
```
```
In mm/filemap.c (c04e0dd8)
Location: include/linux/seqlock.h:108
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
In mm/readahead.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
```
```
In mm/shmem.c (c04faaf0)
Location: include/linux/seqlock.h:108
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
In mm/page_alloc.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/page_io.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - mm/page_io.c:generic_swapfile_activate
```
```
In mm/swapfile.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/userfaultfd.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/open.c (c05674d0)
Location: include/linux/seqlock.h:108
Inline: True
```
```
In fs/read_write.c (c056ad4c)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:default_llseek
  - fs/read_write.c:generic_file_llseek
```
```
In fs/stat.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/stat.c:generic_fillattr
```
```
In fs/exec.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file
```
```
In fs/namei.c (c0578b78)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:__follow_mount_rcu
  - fs/namei.c:set_root
  - fs/namei.c:set_root
```
```
In fs/ioctl.c (c05834d0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/ioctl.c:file_ioctl
  - fs/ioctl.c:ioctl_preallocate
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/dcache.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
```
In fs/d_path.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/d_path.c:__se_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
```
In fs/stack.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/stack.c:fsstack_copy_inode_size
```
```
In fs/buffer.c (0)
Location: include/linux/seqlock.h:108
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
In fs/block_dev.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:blkdev_read_iter
  - fs/block_dev.c:check_disk_size_change
  - fs/block_dev.c:block_llseek
  - fs/block_dev.c:set_init_blocksize
```
```
In fs/direct-io.c (c05bd39c)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/userfaultfd.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_unregister
```
```
In fs/locks.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/locks.c:flock64_to_posix_lock
```
```
In fs/coredump.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/coredump.c:dump_truncate
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/seqlock.h:108
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
In fs/iomap/direct-io.c (c05f58a0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/iomap/seek.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/iomap/seek.c:iomap_seek_data
  - fs/iomap/seek.c:iomap_seek_hole
```
```
In fs/iomap/swapfile.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/iomap/swapfile.c:iomap_swapfile_activate
```
```
In fs/ext4/extents.c (c062dacc)
Location: include/linux/seqlock.h:108
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
In fs/ext4/file.c (c0631f54)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/inline.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (0)
Location: include/linux/seqlock.h:108
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
In fs/ext4/ioctl.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
```
```
In fs/ext4/mballoc.c (c064fbb4)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
```
```
In fs/ext4/migrate.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/readpage.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/super.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_read
```
```
In fs/ext4/xattr.c (c06883dc)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
```
In fs/squashfs/dir.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/squashfs/dir.c:squashfs_readdir
```
```
In fs/squashfs/file.c (c069d788)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_readpage
```
```
In fs/squashfs/namei.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/squashfs/namei.c:squashfs_lookup
```
```
In fs/squashfs/super.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In fs/squashfs/symlink.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/fat/cache.c (c06a292c)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_bmap
```
```
In fs/fat/file.c (c06a8440)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
```
```
In fs/fat/inode.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In fs/ecryptfs/file.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
```
```
In fs/ecryptfs/inode.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_inode_newsize_ok
  - fs/ecryptfs/inode.c:truncate_upper
  - fs/ecryptfs/inode.c:ecryptfs_link
```
```
In fs/ecryptfs/mmap.c (c06b3c38)
Location: include/linux/seqlock.h:108
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
In fs/ecryptfs/read_write.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/ecryptfs/crypto.c (c06b5db8)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_i_size_init
```
```
In fs/fuse/dev.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_retrieve
```
```
In fs/fuse/dir.c (c06c3928)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/file.c (c06c9840)
Location: include/linux/seqlock.h:108
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
In ipc/shm.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
```
In security/selinux/selinuxfs.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/integrity/ima/ima_crypto.c (c075ed20)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In block/blk-core.c (c078f278)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
```
In block/ioctl.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blk_ioctl_discard
```
```
In block/genhd.c (c07a5b90)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - block/genhd.c:disk_map_sector_rcu
  - block/genhd.c:disk_map_sector_rcu
  - block/genhd.c:disk_part_iter_next
```
```
In block/partition-generic.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - block/partition-generic.c:part_size_show
```
```
In block/badblocks.c (c07aa048)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/partitions/efi.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
```
```
In block/blk-iocost.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In block/blk-zoned.c (c07c7490)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
```
```
In drivers/block/loop.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/block/loop.c:get_size
```
```
In drivers/dax/super.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/dax/super.c:__bdev_dax_supported
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
```
```
In drivers/net/loopback.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_get_stats64
```
```
In drivers/net/phy/fixed_phy.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
```
```
In drivers/net/tun.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_get_stats64
```
```
In drivers/md/md.c (0)
Location: include/linux/seqlock.h:108
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
In drivers/md/md-bitmap.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
```
In drivers/md/dm-table.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_area_is_invalid
```
```
In drivers/md/dm-linear.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/md/dm-linear.c:linear_prepare_ioctl
```
```
In net/core/sock.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/core/sock.c:sock_gettstamp
```
```
In net/core/gen_stats.c (c0cda7cc)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/neighbour.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
```
```
In net/core/devlink.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_stats_put
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (c0d72bd4)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_get_local_port_range
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:snmp_get_cpu_field64
```
```
In net/ipv4/ping.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64
```
```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In lib/flex_proportions.c (0)
Location: include/linux/seqlock.h:108
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
In kernel/sched/cputime.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/psi.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/sched/psi.c:collect_percpu_times
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (0)
Location: include/linux/seqlock.h:108
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
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/seqlock.h:108
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/auditsc.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In mm/filemap.c (c0000000003630f0)
Location: include/linux/seqlock.h:108
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (c000000000406034)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (c000000000425f8c)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/namei.c (c00000000048a730)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:set_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
```
In fs/d_path.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/d_path.c:__se_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
```
```
In fs/userfaultfd.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_unregister
```
```
In block/badblocks.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/blk-iocost.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
```
```
In drivers/net/phy/fixed_phy.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
```
```
In drivers/md/md.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/gen_stats.c (c000000000c97fc0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/neighbour.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In lib/flex_proportions.c (0)
Location: include/linux/seqlock.h:108
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
In kernel/sched/cputime.c (ffffffe0000ed894)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/psi.c (ffffffe000108b00)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/sched/psi.c:collect_percpu_times
```
```
In kernel/time/hrtimer.c (ffffffe00012e0ba)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (ffffffe000131922)
Location: include/linux/seqlock.h:108
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
```
```
In kernel/time/tick-common.c (ffffffe00013a31a)
Location: include/linux/seqlock.h:108
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffe00013ae28)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/auditsc.c (ffffffe0001659e4)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In mm/page_alloc.c (ffffffe00021e95e)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (ffffffe00022c060)
Location: include/linux/seqlock.h:108
Inline: True
```
```
In fs/namei.c (ffffffe000262fbe)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:set_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffe000270220)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffe000279b78)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
```
In fs/d_path.c (ffffffe00028d704)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/d_path.c:__se_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
```
```
In fs/userfaultfd.c (ffffffe0002a7878)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_unregister
```
```
In block/badblocks.c (ffffffe00043a452)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/blk-iocost.c (ffffffe00044b02c)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In drivers/dma-buf/dma-buf.c (ffffffe0005d296a)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-resv.c (ffffffe0005d540c)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
```
```
In drivers/net/phy/fixed_phy.c (ffffffe000624f76)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
```
```
In drivers/md/md.c (ffffffe0006dc832)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/gen_stats.c (ffffffe00074c980)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (ffffffe00074d02c)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/neighbour.c (ffffffe00076a9ac)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffe0007c625e)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (ffffffe0007cade0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d28a2)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (ffffffe0007f1dd2)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffe0007fec7c)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffe000815fd8)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffe00081b76a)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffe000829530)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffe000836428)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffe000843dc6)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In lib/flex_proportions.c (ffffffe0008b2608)
Location: include/linux/seqlock.h:108
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
In kernel/sched/cputime.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/psi.c (ffffffff810fb3cc)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/sched/psi.c:collect_percpu_times
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (ffffffff81133a20)
Location: include/linux/seqlock.h:108
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
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/seqlock.h:108
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff81140f09)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/auditsc.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In mm/filemap.c (0)
Location: include/linux/seqlock.h:108
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/namei.c (ffffffff812e34c5)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:set_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffff812f3ce4)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff812fbef1)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
```
In fs/d_path.c (ffffffff81312e3b)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
```
```
In fs/userfaultfd.c (ffffffff81332170)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
```
In block/badblocks.c (ffffffff814f5852)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/blk-iocost.c (ffffffff815084f4)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In drivers/dma-buf/dma-buf.c (ffffffff8171a2d0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8171c75c)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
```
```
In drivers/net/phy/fixed_phy.c (ffffffff817846ea)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
```
```
In drivers/md/md.c (ffffffff81839bc5)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/gen_stats.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/neighbour.c (ffffffff818e3fff)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195b6f7)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff8198bf89)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff819a6a8d)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff819ad454)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff819bc7db)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In lib/flex_proportions.c (ffffffff81a4dc65)
Location: include/linux/seqlock.h:108
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
In kernel/sched/cputime.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/sched/cputime.c:task_gtime
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/psi.c (ffffffff810eb5ec)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/sched/psi.c:collect_percpu_times
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (ffffffff81126480)
Location: include/linux/seqlock.h:108
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
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/seqlock.h:108
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff81133ca9)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/auditsc.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In mm/filemap.c (0)
Location: include/linux/seqlock.h:108
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/namei.c (ffffffff812d4105)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:set_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffff812e4914)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff812ecb11)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
```
In fs/d_path.c (ffffffff81303a4b)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
```
```
In fs/userfaultfd.c (ffffffff81322d30)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
```
In block/badblocks.c (ffffffff814e5d62)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/blk-iocost.c (ffffffff814f89a4)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In drivers/dma-buf/dma-buf.c (ffffffff816f373a)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-resv.c (ffffffff816f5bbc)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8176403a)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
```
```
In drivers/md/md.c (ffffffff81801235)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/gen_stats.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/neighbour.c (ffffffff8189de3f)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819151e7)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81945a49)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff8196054d)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81969a84)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff819795cb)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In lib/flex_proportions.c (ffffffff81a0ad55)
Location: include/linux/seqlock.h:108
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
In kernel/sched/cputime.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/psi.c (ffffffff810f858c)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/sched/psi.c:collect_percpu_times
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (ffffffff81131740)
Location: include/linux/seqlock.h:108
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
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/seqlock.h:108
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8113edb9)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/auditsc.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In mm/filemap.c (0)
Location: include/linux/seqlock.h:108
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/namei.c (ffffffff812e12d5)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:set_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffff812f1af4)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff812f9ce1)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
```
In fs/d_path.c (ffffffff81310c2b)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
```
```
In fs/userfaultfd.c (ffffffff8132fc40)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
```
In block/badblocks.c (ffffffff814f18e2)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/blk-iocost.c (ffffffff81504584)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In drivers/dma-buf/dma-buf.c (ffffffff817590a0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8175b52c)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
```
```
In drivers/net/phy/fixed_phy.c (ffffffff817b4a9a)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
```
```
In drivers/md/md.c (ffffffff818891f5)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/gen_stats.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/neighbour.c (ffffffff8193502f)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/netfilter/nf_conntrack_core.c (ffffffff8199ea18)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_core.c:nf_ct_iterate_cleanup
  - net/netfilter/nf_conntrack_core.c:gc_worker
  - net/netfilter/nf_conntrack_core.c:early_drop
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_tuple_taken
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_hash_check_insert
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_find_get
  - net/netfilter/nf_conntrack_core.c:nf_ct_delete_from_lists
```
```
In net/netfilter/nf_conntrack_standalone.c (ffffffff819a1143)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_standalone.c:ct_seq_start
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c5ec7)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff819f6799)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff81a1132d)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81a17cf4)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2725b)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In lib/flex_proportions.c (ffffffff81aba055)
Location: include/linux/seqlock.h:108
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
In kernel/sched/cputime.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/psi.c (ffffffff811036cc)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/sched/psi.c:collect_percpu_times
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (ffffffff8113e160)
Location: include/linux/seqlock.h:108
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
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/seqlock.h:108
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8114b929)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/auditsc.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In mm/filemap.c (0)
Location: include/linux/seqlock.h:108
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/namei.c (ffffffff812f0318)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:set_root
  - fs/namei.c:set_root
```
```
In fs/dcache.c (ffffffff81302d14)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_lookup
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff8130b026)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
```
In fs/d_path.c (ffffffff81322460)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
```
```
In fs/userfaultfd.c (ffffffff813425c5)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
```
In block/badblocks.c (ffffffff8150a942)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/blk-iocost.c (ffffffff8151db34)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In drivers/dma-buf/dma-buf.c (ffffffff817744b0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-resv.c (ffffffff817767e0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
```
```
In drivers/net/phy/fixed_phy.c (ffffffff817cea6a)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
```
```
In drivers/md/md.c (ffffffff818a6925)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/gen_stats.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/neighbour.c (ffffffff8195673f)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819cf9a9)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81a009c0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff81a1bc9d)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81a22794)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a3288b)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In lib/flex_proportions.c (ffffffff81ac64a5)
Location: include/linux/seqlock.h:108
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
```
</details>
</li>
</ul>

## Differences

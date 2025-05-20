# Function: <code>do_read_seqcount_retry</code>

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
In kernel/sched/cputime.c (ffffffff810e5885)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/psi.c (ffffffff81109f34)
Location: include/linux/seqlock.h:450
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff811424f9)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (ffffffff811468cb)
Location: include/linux/seqlock.h:450
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
  - kernel/time/timekeeping.c:ktime_get_fast_timestamps
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/time/tick-common.c (ffffffff81152c92)
Location: include/linux/seqlock.h:450
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff81154575)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/module.c (ffffffff811640e3)
Location: include/linux/seqlock.h:450
Inline: True
```
```
In kernel/auditsc.c (ffffffff8118c2fa)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - kernel/auditsc.c:handle_path
```
```
In kernel/bpf/core.c (ffffffff811f7e64)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_find
```
```
In mm/filemap.c (ffffffff81258784)
Location: include/linux/seqlock.h:450
Inline: True
```
```
In mm/gup.c (ffffffff812950da)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - mm/gup.c:lockless_pages_from_mm
```
```
In mm/page_alloc.c (ffffffff812beb37)
Location: include/linux/seqlock.h:450
Inline: True
```
```
In mm/hugetlb.c (ffffffff812cf732)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff812e79bd)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In fs/namei.c (ffffffff8132e105)
Location: include/linux/seqlock.h:450
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
In fs/dcache.c (ffffffff8133f818)
Location: include/linux/seqlock.h:450
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
In fs/namespace.c (ffffffff813493e5)
Location: include/linux/seqlock.h:450
Inline: True
```
```
In fs/d_path.c (ffffffff813610c3)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
```
In fs/userfaultfd.c (ffffffff81380d79)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_wake
```
```
In block/badblocks.c (ffffffff815788d4)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/blk-iocost.c (ffffffff8158c350)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In lib/flex_proportions.c (ffffffff8160dc5d)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
```
```
In drivers/dma-buf/dma-buf.c (ffffffff8183675f)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-resv.c (ffffffff818394bc)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
```
```
In drivers/md/md.c (ffffffff8196cece)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/gen_stats.c (ffffffff819f6daf)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (ffffffff819f75d0)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/neighbour.c (ffffffff81a144f7)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81a2a029)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - net/core/filter.c:neigh_hh_output
```
```
In net/ipv4/inetpeer.c (ffffffff81aa15c3)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_output.c (ffffffff81aa5529)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ab04cc)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad7bad)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81ae6a18)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff81b03610)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81b0c689)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1c372)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff81b2b03f)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffff81b3ae99)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:neigh_hh_output
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
In kernel/sched/cputime.c (ffffffff810e7855)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/psi.c (ffffffff8110bc84)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - kernel/sched/psi.c:collect_percpu_times
```
```
In kernel/printk/printk.c (ffffffff81119458)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_rewind
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:devkmsg_llseek
```
```
In kernel/time/hrtimer.c (ffffffff811436d9)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (ffffffff81147a3b)
Location: include/linux/seqlock.h:450
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
  - kernel/time/timekeeping.c:ktime_get_fast_timestamps
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/time/tick-common.c (ffffffff81153f82)
Location: include/linux/seqlock.h:450
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff811559f5)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/module.c (ffffffff81164eb3)
Location: include/linux/seqlock.h:450
Inline: True
```
```
In kernel/auditsc.c (ffffffff8118e7e4)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In kernel/bpf/core.c (ffffffff811f8c44)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_find
```
```
In mm/filemap.c (ffffffff8125ce0c)
Location: include/linux/seqlock.h:450
Inline: True
```
```
In mm/gup.c (ffffffff8129aa98)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - mm/gup.c:lockless_pages_from_mm
```
```
In mm/page_alloc.c (ffffffff812c3bbc)
Location: include/linux/seqlock.h:450
Inline: True
```
```
In mm/hugetlb.c (ffffffff812d6987)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff812ef12d)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In fs/namei.c (ffffffff81334739)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:step_into
  - fs/namei.c:step_into
  - fs/namei.c:lookup_fast
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
  - fs/namei.c:try_to_unlazy_next
  - fs/namei.c:__legitimize_path
```
```
In fs/dcache.c (ffffffff81345c98)
Location: include/linux/seqlock.h:450
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
In fs/namespace.c (ffffffff8134fdc5)
Location: include/linux/seqlock.h:450
Inline: True
```
```
In fs/d_path.c (ffffffff81367ba3)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
```
In fs/userfaultfd.c (ffffffff81388621)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
```
```
In block/badblocks.c (ffffffff81580624)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/blk-iocost.c (ffffffff81593210)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In lib/flex_proportions.c (ffffffff815f13ad)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
```
```
In drivers/dma-buf/dma-buf.c (ffffffff8181992f)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8181c756)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
```
```
In drivers/md/md.c (ffffffff8194f9af)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/gen_stats.c (ffffffff819dcf2f)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (ffffffff819dd750)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/neighbour.c (ffffffff819fae86)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81a11279)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - net/core/filter.c:neigh_hh_output
```
```
In net/ipv4/inetpeer.c (ffffffff81a8c514)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_output.c (ffffffff81a905e9)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9b6aa)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ac2d4d)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81ad1ce9)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff81aeee50)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81afa2f9)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0a062)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff81b18c68)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffff81b28ac9)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:neigh_hh_output
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
In kernel/sched/cputime.c (ffffffff810feef5)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/psi.c (ffffffff8112a741)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - kernel/sched/psi.c:collect_percpu_times
```
```
In kernel/printk/printk.c (ffffffff81138430)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_rewind
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:devkmsg_llseek
```
```
In kernel/time/hrtimer.c (ffffffff81166cb9)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (ffffffff8116b564)
Location: include/linux/seqlock.h:450
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
  - kernel/time/timekeeping.c:ktime_get_fast_timestamps
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/time/tick-common.c (ffffffff811786a2)
Location: include/linux/seqlock.h:450
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8117a665)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/module.c (ffffffff8118469e)
Location: include/linux/seqlock.h:450
Inline: True
```
```
In kernel/auditsc.c (ffffffff811b75f4)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In kernel/bpf/core.c (ffffffff8122a2d4)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_find
```
```
In mm/filemap.c (ffffffff81298d86)
Location: include/linux/seqlock.h:450
Inline: True
```
```
In mm/gup.c (ffffffff812db448)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - mm/gup.c:lockless_pages_from_mm
```
```
In mm/page_alloc.c (ffffffff81307a55)
Location: include/linux/seqlock.h:450
Inline: True
```
```
In mm/hugetlb.c (ffffffff8131c747)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff81337437)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In fs/namei.c (ffffffff81382084)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:step_into
  - fs/namei.c:step_into
  - fs/namei.c:lookup_fast
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
  - fs/namei.c:try_to_unlazy_next
  - fs/namei.c:__legitimize_path
```
```
In fs/dcache.c (ffffffff813938b5)
Location: include/linux/seqlock.h:450
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
In fs/namespace.c (ffffffff8139e165)
Location: include/linux/seqlock.h:450
Inline: True
```
```
In fs/d_path.c (ffffffff813b6752)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
```
In fs/userfaultfd.c (ffffffff813d5962)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
```
```
In block/badblocks.c (ffffffff815e5943)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/blk-iocost.c (ffffffff815fa4c0)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In lib/flex_proportions.c (ffffffff8165e51d)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
```
```
In drivers/dma-buf/dma-resv.c (ffffffff818a69d3)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
```
```
In drivers/md/md.c (ffffffff819f4e2f)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/gen_stats.c (ffffffff81a8d1a3)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (ffffffff81a8da30)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/neighbour.c (ffffffff81aacac6)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81ac77d9)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/ipv4/inetpeer.c (ffffffff81b47654)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_output.c (ffffffff81b4c1c4)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b56cda)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff81b808fe)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81b90939)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff81baf220)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81bbaff9)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bcce82)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff81bdd058)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffff81bef1b5)
Location: include/linux/seqlock.h:450
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
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
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff810611bf)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
```
```
In kernel/sched/build_policy.c (ffffffff811397e4)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:thread_group_cputime
```
```
In kernel/sched/build_utility.c (ffffffff811437df)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:collect_percpu_times
```
```
In kernel/printk/printk.c (ffffffff8115ace0)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_rewind
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:devkmsg_llseek
```
```
In kernel/module/tree_lookup.c (ffffffff81190e89)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/module/tree_lookup.c:mod_find
```
```
In kernel/time/hrtimer.c (ffffffff8119a459)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (ffffffff8119f474)
Location: include/linux/seqlock.h:446
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
  - kernel/time/timekeeping.c:ktime_get_fast_timestamps
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/time/tick-common.c (ffffffff811ad8cb)
Location: include/linux/seqlock.h:446
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff811afb92)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/auditsc.c (ffffffff811ea358)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In kernel/bpf/core.c (ffffffff8126bd84)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_find
```
```
In mm/filemap.c (ffffffff812ef5fb)
Location: include/linux/seqlock.h:446
Inline: True
```
```
In mm/gup.c (ffffffff8133b034)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - mm/gup.c:lockless_pages_from_mm
```
```
In mm/page_alloc.c (ffffffff8136feaf)
Location: include/linux/seqlock.h:446
Inline: True
```
```
In mm/hugetlb.c (ffffffff81387934)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff813a8d64)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In fs/namei.c (ffffffff81403d79)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
  - fs/namei.c:step_into
  - fs/namei.c:step_into
  - fs/namei.c:step_into
  - fs/namei.c:lookup_fast
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
  - fs/namei.c:try_to_unlazy_next
  - fs/namei.c:__legitimize_path
```
```
In fs/dcache.c (ffffffff814150a6)
Location: include/linux/seqlock.h:446
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
In fs/namespace.c (ffffffff814212a5)
Location: include/linux/seqlock.h:446
Inline: True
```
```
In fs/d_path.c (ffffffff8143bd48)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
```
In fs/userfaultfd.c (ffffffff8145fb5b)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
```
```
In block/badblocks.c (ffffffff81694a12)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/blk-iocost.c (ffffffff816ac853)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In lib/flex_proportions.c (ffffffff81777c8d)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
```
```
In drivers/md/md.c (ffffffff81b5ea3e)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/gen_estimator.c (ffffffff81c03342)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/neighbour.c (ffffffff81c25a3c)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81c3d319)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/core/filter.c:neigh_hh_output
```
```
In net/ipv4/inetpeer.c (ffffffff81cd485a)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_output.c (ffffffff81cd8da9)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce3d67)
Location: include/linux/seqlock.h:446
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d10d01)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81d21e1a)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff81d4255f)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81d4f11b)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d62c6e)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff81d73e23)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffff81d87059)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:neigh_hh_output
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
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff8106fb2f)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
```
```
In kernel/sched/build_policy.c (ffffffff81163fa4)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:thread_group_cputime
```
```
In kernel/sched/build_utility.c (ffffffff8116ef18)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:get_recent_times
```
```
In kernel/printk/printk.c (ffffffff8118d200)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_rewind
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:devkmsg_llseek
```
```
In kernel/module/tree_lookup.c (ffffffff811ce489)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/module/tree_lookup.c:mod_find
```
```
In kernel/time/hrtimer.c (ffffffff811d8b89)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (ffffffff811de164)
Location: include/linux/seqlock.h:446
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
  - kernel/time/timekeeping.c:ktime_get_fast_timestamps
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/time/tick-common.c (ffffffff811edebb)
Location: include/linux/seqlock.h:446
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff811f05b2)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/auditsc.c (ffffffff81230538)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In kernel/bpf/core.c (ffffffff812c0f44)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_find
```
```
In mm/filemap.c (ffffffff8135a130)
Location: include/linux/seqlock.h:446
Inline: True
```
```
In mm/gup.c (ffffffff813b2c86)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - mm/gup.c:lockless_pages_from_mm
```
```
In mm/page_alloc.c (ffffffff813ec484)
Location: include/linux/seqlock.h:446
Inline: True
```
```
In mm/hugetlb.c (ffffffff81405d7d)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff81429e33)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In fs/namei.c (ffffffff8148e1e5)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:handle_dots
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:step_into
  - fs/namei.c:step_into
  - fs/namei.c:step_into
  - fs/namei.c:step_into
  - fs/namei.c:lookup_fast
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
  - fs/namei.c:try_to_unlazy_next
  - fs/namei.c:__legitimize_path
```
```
In fs/dcache.c (ffffffff814a05b9)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_hash_and_lookup
  - fs/dcache.c:__d_lookup_rcu_op_compare
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff814ad895)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - fs/namespace.c:__legitimize_mnt
  - fs/namespace.c:__legitimize_mnt
```
```
In fs/d_path.c (ffffffff814ca378)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
```
In fs/userfaultfd.c (ffffffff814efc25)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
```
```
In block/badblocks.c (ffffffff81753572)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/blk-iocost.c (ffffffff8176b0ec)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In drivers/md/md.c (ffffffff81cf892c)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/gen_estimator.c (ffffffff81db2902)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/neighbour.c (ffffffff81dd7c7c)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/filter.c (ffffffff81df5149)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/core/filter.c:neigh_hh_output
```
```
In net/ipv4/inetpeer.c (ffffffff81e94b3a)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_output.c (ffffffff81e996e9)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea67b7)
Location: include/linux/seqlock.h:446
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed6a81)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81ee926a)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff81f0b3ef)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81f18d1b)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f2d80e)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff81f3fd9a)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffff81f54ff9)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:neigh_hh_output
```
```
In lib/flex_proportions.c (ffffffff8202096d)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
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
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff8107172f)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
```
```
In kernel/sched/build_policy.c (ffffffff81174784)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:thread_group_cputime
```
```
In kernel/sched/build_utility.c (ffffffff81180685)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:get_recent_times
```
```
In kernel/time/hrtimer.c (ffffffff811ecfb9)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (ffffffff811f2634)
Location: include/linux/seqlock.h:446
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
In kernel/time/tick-common.c (ffffffff812025eb)
Location: include/linux/seqlock.h:446
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff81204d42)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/auditsc.c (ffffffff8124705b)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In mm/filemap.c (ffffffff8138bb85)
Location: include/linux/seqlock.h:446
Inline: True
```
```
In mm/gup.c (ffffffff813e78f6)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - mm/gup.c:lockless_pages_from_mm
```
```
In mm/page_alloc.c (ffffffff814212eb)
Location: include/linux/seqlock.h:446
Inline: True
```
```
In mm/hugetlb.c (ffffffff81439309)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_hugetlb_folio_nodemask
```
```
In mm/slub.c (ffffffff8145f228)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In fs/namei.c (ffffffff814c3928)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
  - fs/namei.c:step_into
  - fs/namei.c:step_into
  - fs/namei.c:step_into
  - fs/namei.c:step_into
  - fs/namei.c:lookup_fast
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
  - fs/namei.c:try_to_unlazy_next
  - fs/namei.c:__legitimize_path
```
```
In fs/dcache.c (ffffffff814d58e3)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_hash_and_lookup
  - fs/dcache.c:__d_lookup_rcu_op_compare
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff814e2675)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - fs/namespace.c:__legitimize_mnt
  - fs/namespace.c:__legitimize_mnt
```
```
In fs/d_path.c (ffffffff815005b8)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
```
In fs/userfaultfd.c (ffffffff8152694c)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
```
```
In block/badblocks.c (ffffffff8178f724)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/blk-iocost.c (ffffffff817aa1cc)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In drivers/md/md.c (ffffffff81d60865)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/gen_estimator.c (ffffffff81e22ed2)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/neighbour.c (ffffffff81e46fbf)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
  - net/core/neighbour.c:neigh_ha_snapshot
```
```
In net/core/filter.c (ffffffff81e66b39)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/core/filter.c:neigh_hh_output
```
```
In net/ipv4/inetpeer.c (ffffffff81ef330a)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_output.c (ffffffff81ef7fe9)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f061e9)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_sk_get_local_port_range
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f35ab7)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81f482eb)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/ipv4/arp.c:neigh_ha_snapshot
```
```
In net/ipv4/ping.c (ffffffff81f6afcf)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81f78986)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f8d4de)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff81f9f511)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffff81fb4a09)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:neigh_hh_output
```
```
In lib/flex_proportions.c (ffffffff820a09ad)
Location: include/linux/seqlock.h:446
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
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
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81078eef)
Location: include/linux/seqlock.h:400
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
```
```
In kernel/sys.c (ffffffff81123ddd)
Location: include/linux/seqlock.h:400
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/sched/build_policy.c (ffffffff81175507)
Location: include/linux/seqlock.h:400
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:kcpustat_cpu_fetch
  - kernel/sched/build_policy.c:kcpustat_field_vtime
  - kernel/sched/build_policy.c:task_gtime
  - kernel/sched/build_policy.c:thread_group_cputime
```
```
In kernel/sched/build_utility.c (ffffffff8118e3d5)
Location: include/linux/seqlock.h:400
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:get_recent_times
```
```
In kernel/time/hrtimer.c (ffffffff81203119)
Location: include/linux/seqlock.h:400
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (ffffffff81208774)
Location: include/linux/seqlock.h:400
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
In kernel/time/tick-common.c (ffffffff81218adb)
Location: include/linux/seqlock.h:400
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8121b412)
Location: include/linux/seqlock.h:400
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/auditsc.c (ffffffff81260ed4)
Location: include/linux/seqlock.h:400
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In mm/filemap.c (ffffffff813b56f5)
Location: include/linux/seqlock.h:400
Inline: True
```
```
In mm/gup.c (ffffffff81412566)
Location: include/linux/seqlock.h:400
Inline: True
Inline callers:
  - mm/gup.c:lockless_pages_from_mm
```
```
In mm/page_alloc.c (ffffffff8144e062)
Location: include/linux/seqlock.h:400
Inline: True
```
```
In mm/slub.c (ffffffff8145a395)
Location: include/linux/seqlock.h:400
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In mm/hugetlb.c (ffffffff81472e39)
Location: include/linux/seqlock.h:400
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_hugetlb_folio_nodemask
```
```
In fs/namei.c (ffffffff814f5df8)
Location: include/linux/seqlock.h:400
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
  - fs/namei.c:step_into
  - fs/namei.c:step_into
  - fs/namei.c:step_into
  - fs/namei.c:step_into
  - fs/namei.c:lookup_fast
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
  - fs/namei.c:try_to_unlazy_next
  - fs/namei.c:__legitimize_path
```
```
In fs/dcache.c (ffffffff81507cd7)
Location: include/linux/seqlock.h:400
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_hash_and_lookup
  - fs/dcache.c:__d_lookup_rcu_op_compare
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
```
```
In fs/namespace.c (ffffffff81516465)
Location: include/linux/seqlock.h:400
Inline: True
Inline callers:
  - fs/namespace.c:__legitimize_mnt
  - fs/namespace.c:__legitimize_mnt
```
```
In fs/d_path.c (ffffffff815351d8)
Location: include/linux/seqlock.h:400
Inline: True
Inline callers:
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
```
In fs/userfaultfd.c (ffffffff8155af15)
Location: include/linux/seqlock.h:400
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_move
  - fs/userfaultfd.c:userfaultfd_poison
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_unregister
```
```
In fs/proc/base.c (ffffffff815a31bb)
Location: include/linux/seqlock.h:400
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
```
```
In fs/proc/array.c (ffffffff815acb27)
Location: include/linux/seqlock.h:400
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In block/badblocks.c (ffffffff817d1e84)
Location: include/linux/seqlock.h:400
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:_badblocks_check
```
```
In block/blk-iocost.c (ffffffff817edf8c)
Location: include/linux/seqlock.h:400
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In drivers/gpu/drm/drm_vblank.c (ffffffff81cb3e83)
Location: include/linux/seqlock.h:400
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_vblank.c:drm_vblank_count_and_time
```
```
In drivers/md/md.c (ffffffff81e185c5)
Location: include/linux/seqlock.h:400
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/gen_estimator.c (ffffffff81ee0e12)
Location: include/linux/seqlock.h:400
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/neighbour.c (ffffffff81f05c7c)
Location: include/linux/seqlock.h:400
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
  - net/core/neighbour.c:neigh_ha_snapshot
```
```
In net/core/filter.c (ffffffff81f25ce9)
Location: include/linux/seqlock.h:400
Inline: True
Inline callers:
  - net/core/filter.c:neigh_hh_output
```
```
In net/ipv4/inetpeer.c (ffffffff81fb729a)
Location: include/linux/seqlock.h:400
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_output.c (ffffffff81fbc039)
Location: include/linux/seqlock.h:400
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ffbb67)
Location: include/linux/seqlock.h:400
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff8200e44b)
Location: include/linux/seqlock.h:400
Inline: True
Inline callers:
  - net/ipv4/arp.c:neigh_ha_snapshot
```
```
In net/ipv4/ping.c (ffffffff82032a15)
Location: include/linux/seqlock.h:400
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8203f046)
Location: include/linux/seqlock.h:400
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205ae6e)
Location: include/linux/seqlock.h:400
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff8206c871)
Location: include/linux/seqlock.h:400
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffff820820a9)
Location: include/linux/seqlock.h:400
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:neigh_hh_output
```
```
In lib/flex_proportions.c (ffffffff8217898d)
Location: include/linux/seqlock.h:400
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
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

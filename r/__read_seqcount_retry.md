# Function: <code>__read_seqcount_retry</code>

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
In kernel/sched/cputime.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In kernel/time/timekeeping.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In lib/flex_proportions.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In drivers/dma-buf/reservation.c (ffffffff815a504b)
Location: include/linux/seqlock.h:202
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
```
```
In drivers/md/md.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/seqlock.h:202
Inline: True
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
In kernel/sched/cputime.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In kernel/time/timekeeping.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In block/badblocks.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In lib/flex_proportions.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In drivers/dma-buf/reservation.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In drivers/net/phy/fixed_phy.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/core/gen_stats.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/ipv4/inetpeer.c (ffffffff817c48d7)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/seqlock.h:202
Inline: True
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
In kernel/sched/cputime.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In kernel/time/timekeeping.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In block/badblocks.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In lib/flex_proportions.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In drivers/dma-buf/reservation.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In drivers/net/phy/fixed_phy.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/core/gen_stats.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/core/gen_estimator.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/ipv4/inetpeer.c (ffffffff817f43f7)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff818538d2)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/seqlock.h:202
Inline: True
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
In kernel/sched/cputime.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In kernel/time/timekeeping.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In block/badblocks.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In drivers/dma-buf/reservation.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In drivers/net/phy/fixed_phy.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/core/gen_stats.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/core/gen_estimator.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/ipv4/inetpeer.c (ffffffff81814814)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81877370)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/seqlock.h:202
Inline: True
```
```
In lib/flex_proportions.c (0)
Location: include/linux/seqlock.h:202
Inline: True
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
In kernel/sched/cputime.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/timekeeping.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In block/badblocks.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In drivers/dma-buf/reservation.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In drivers/net/phy/fixed_phy.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/core/gen_stats.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/core/gen_estimator.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/inetpeer.c (ffffffff818936e7)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f7fa7)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In lib/flex_proportions.c (0)
Location: include/linux/seqlock.h:203
Inline: True
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
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/timekeeping.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/d_path.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In block/badblocks.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In drivers/dma-buf/reservation.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In drivers/net/phy/fixed_phy.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/core/gen_stats.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/core/gen_estimator.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/inetpeer.c (ffffffff818e7a0c)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In lib/flex_proportions.c (0)
Location: include/linux/seqlock.h:203
Inline: True
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
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/sched/psi.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/timekeeping.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/d_path.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In block/badblocks.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In drivers/dma-buf/reservation.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In drivers/net/phy/fixed_phy.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/core/gen_stats.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/core/gen_estimator.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/inetpeer.c (ffffffff819148bc)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In lib/flex_proportions.c (0)
Location: include/linux/seqlock.h:203
Inline: True
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
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/sched/psi.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/timekeeping.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/d_path.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In block/badblocks.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In drivers/dma-buf/reservation.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In drivers/net/phy/fixed_phy.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/core/gen_stats.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/core/gen_estimator.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/inetpeer.c (ffffffff81976cdf)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In lib/flex_proportions.c (0)
Location: include/linux/seqlock.h:203
Inline: True
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
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/sched/psi.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/timekeeping.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/d_path.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In block/badblocks.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In drivers/net/phy/fixed_phy.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/core/gen_stats.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/core/gen_estimator.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/inetpeer.c (ffffffff819ad66f)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In lib/flex_proportions.c (0)
Location: include/linux/seqlock.h:203
Inline: True
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
Location: include/linux/seqlock.h:222
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/psi.c (ffffffff8110cd87)
Location: include/linux/seqlock.h:222
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff81145fc7)
Location: include/linux/seqlock.h:222
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (ffffffff8114a37b)
Location: include/linux/seqlock.h:222
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
Location: include/linux/seqlock.h:222
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff81158545)
Location: include/linux/seqlock.h:222
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/module.c (ffffffff81162143)
Location: include/linux/seqlock.h:222
Inline: True
```
```
In kernel/auditsc.c (ffffffff8118f07f)
Location: include/linux/seqlock.h:222
Inline: True
Inline callers:
  - kernel/auditsc.c:handle_path
```
```
In kernel/bpf/core.c (ffffffff811f8e24)
Location: include/linux/seqlock.h:222
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_find
```
```
In mm/filemap.c (ffffffff8124e365)
Location: include/linux/seqlock.h:222
Inline: True
```
```
In mm/swap.c (ffffffff8126061e)
Location: include/linux/seqlock.h:222
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/page_alloc.c (ffffffff812b301c)
Location: include/linux/seqlock.h:222
Inline: True
```
```
In mm/hugetlb.c (ffffffff812c378f)
Location: include/linux/seqlock.h:222
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff812db0d2)
Location: include/linux/seqlock.h:222
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In fs/namei.c (ffffffff81322b3e)
Location: include/linux/seqlock.h:222
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:step_into
  - fs/namei.c:lookup_fast
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
Location: include/linux/seqlock.h:222
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
Location: include/linux/seqlock.h:222
Inline: True
```
```
In fs/d_path.c (ffffffff813547b5)
Location: include/linux/seqlock.h:222
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
Location: include/linux/seqlock.h:222
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_wake
```
```
In block/badblocks.c (ffffffff8155c782)
Location: include/linux/seqlock.h:222
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/blk-iocost.c (ffffffff81570fed)
Location: include/linux/seqlock.h:222
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In lib/flex_proportions.c (ffffffff815e8ba7)
Location: include/linux/seqlock.h:222
Inline: True
Inline callers:
  - lib/flex_proportions.c:fprop_fraction_percpu
  - lib/flex_proportions.c:fprop_fraction_single
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81825d73)
Location: include/linux/seqlock.h:222
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-resv.c (ffffffff818297b9)
Location: include/linux/seqlock.h:222
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
```
```
In drivers/md/md.c (ffffffff8196647e)
Location: include/linux/seqlock.h:222
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_sync
```
```
In net/core/gen_stats.c (ffffffff819f733f)
Location: include/linux/seqlock.h:222
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (ffffffff819f79f0)
Location: include/linux/seqlock.h:222
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/neighbour.c (ffffffff81a140d9)
Location: include/linux/seqlock.h:222
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/inetpeer.c (ffffffff81a975fc)
Location: include/linux/seqlock.h:222
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_output.c (ffffffff81a9b6bc)
Location: include/linux/seqlock.h:222
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa5e8c)
Location: include/linux/seqlock.h:222
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
```
```
In net/ipv4/tcp_metrics.c (ffffffff81acbbed)
Location: include/linux/seqlock.h:222
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (ffffffff81ad9f06)
Location: include/linux/seqlock.h:222
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/ping.c (ffffffff81af6789)
Location: include/linux/seqlock.h:222
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81afe60a)
Location: include/linux/seqlock.h:222
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0e890)
Location: include/linux/seqlock.h:222
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff81b1c85a)
Location: include/linux/seqlock.h:222
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (ffffffff81b2c3ec)
Location: include/linux/seqlock.h:222
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
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/sched/cputime.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/sched/psi.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/timekeeping.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/sched_clock.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/d_path.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In block/badblocks.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In drivers/net/phy/fixed_phy.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/core/gen_stats.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/core/gen_estimator.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/inetpeer.c (ffff800010c5d9d0)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In lib/flex_proportions.c (0)
Location: include/linux/seqlock.h:203
Inline: True
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
In kernel/sched/cputime.c (c038f2a8)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/psi.c (c03b2bec)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - kernel/sched/psi.c:collect_percpu_times
```
```
In kernel/time/hrtimer.c (c03ea308)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_active
```
```
In kernel/time/timekeeping.c (c03f0540)
Location: include/linux/seqlock.h:203
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
In kernel/time/jiffies.c (c03f2830)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - kernel/time/jiffies.c:get_jiffies_64
```
```
In kernel/time/tick-common.c (c03fc2f4)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/sched_clock.c (c03fe1e0)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - kernel/time/sched_clock.c:sched_clock
```
```
In kernel/time/tick-sched.c (c03fe6b0)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
```
In kernel/module.c (c0408830)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/cgroup/rstat.c (c041c09c)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/auditsc.c (c04326a4)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
```
In kernel/bpf/core.c (c04905fc)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/bpf/syscall.c (c0493000)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_get_stats
```
```
In kernel/events/uprobes.c (c04d5354)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In mm/filemap.c (c04e0e1c)
Location: include/linux/seqlock.h:203
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
In mm/readahead.c (c04eaf8c)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
```
```
In mm/shmem.c (c04fab34)
Location: include/linux/seqlock.h:203
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
In mm/page_alloc.c (c05331b0)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/page_io.c (c0538b50)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - mm/page_io.c:generic_swapfile_activate
```
```
In mm/swapfile.c (c053edd4)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/userfaultfd.c (c056408c)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/open.c (c0567514)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/read_write.c (c056ab34)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:default_llseek
  - fs/read_write.c:generic_file_llseek
```
```
In fs/stat.c (c057260c)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - fs/stat.c:generic_fillattr
```
```
In fs/exec.c (c05744bc)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file
```
```
In fs/namei.c (c057e9dc)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_init
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
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
In fs/ioctl.c (c05836d8)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - fs/ioctl.c:file_ioctl
  - fs/ioctl.c:ioctl_preallocate
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/dcache.c (c058b530)
Location: include/linux/seqlock.h:203
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
In fs/namespace.c (c059533c)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/d_path.c (c05acef8)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - fs/d_path.c:__se_sys_getcwd
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:d_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
```
In fs/stack.c (c05ad100)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - fs/stack.c:fsstack_copy_inode_size
```
```
In fs/buffer.c (c05b40a0)
Location: include/linux/seqlock.h:203
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
In fs/block_dev.c (c05b8ef8)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:blkdev_read_iter
  - fs/block_dev.c:check_disk_size_change
  - fs/block_dev.c:block_llseek
  - fs/block_dev.c:set_init_blocksize
```
```
In fs/direct-io.c (c05bcba4)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (c05bdad4)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/userfaultfd.c (c05cca90)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_unregister
```
```
In fs/locks.c (c05e1008)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - fs/locks.c:flock64_to_posix_lock
```
```
In fs/coredump.c (c05f0238)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - fs/coredump.c:dump_truncate
```
```
In fs/iomap/buffered-io.c (c05f3220)
Location: include/linux/seqlock.h:203
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
In fs/iomap/direct-io.c (c05f61b0)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/iomap/seek.c (c05f6a44)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - fs/iomap/seek.c:iomap_seek_data
  - fs/iomap/seek.c:iomap_seek_hole
```
```
In fs/iomap/swapfile.c (c05f7354)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - fs/iomap/swapfile.c:iomap_swapfile_activate
```
```
In fs/ext4/extents.c (c062db10)
Location: include/linux/seqlock.h:203
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
In fs/ext4/file.c (c0631f98)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/inline.c (c063e134)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (c064ba50)
Location: include/linux/seqlock.h:203
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
In fs/ext4/ioctl.c (c064c504)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
```
```
In fs/ext4/mballoc.c (c064f700)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
```
```
In fs/ext4/migrate.c (c0659f68)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/move_extent.c (c065c398)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
```
In fs/ext4/readpage.c (c0666bf8)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/super.c (c0676078)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_read
```
```
In fs/ext4/xattr.c (c0688420)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
```
In fs/squashfs/dir.c (c069c52c)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - fs/squashfs/dir.c:squashfs_readdir
```
```
In fs/squashfs/file.c (c069d530)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_readpage
```
```
In fs/squashfs/namei.c (c069e950)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - fs/squashfs/namei.c:squashfs_lookup
```
```
In fs/squashfs/super.c (c069efdc)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In fs/squashfs/symlink.c (c069f7e8)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (c069fc34)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/fat/cache.c (c06a2970)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_bmap
```
```
In fs/fat/file.c (c06a8484)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
```
```
In fs/fat/inode.c (c06ab730)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In fs/ecryptfs/file.c (c06b006c)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/file.c:ecryptfs_open
```
```
In fs/ecryptfs/inode.c (c06b113c)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_inode_newsize_ok
  - fs/ecryptfs/inode.c:truncate_upper
  - fs/ecryptfs/inode.c:ecryptfs_link
```
```
In fs/ecryptfs/mmap.c (c06b3b2c)
Location: include/linux/seqlock.h:203
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
In fs/ecryptfs/read_write.c (c06b3f78)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/ecryptfs/crypto.c (c06b5dfc)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_i_size_init
```
```
In fs/fuse/dev.c (c06c11ac)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_retrieve
```
```
In fs/fuse/dir.c (c06c396c)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/file.c (c06ca430)
Location: include/linux/seqlock.h:203
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
In ipc/shm.c (c06e203c)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
```
In security/selinux/selinuxfs.c (c070afd0)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/integrity/ima/ima_crypto.c (c075f688)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In block/blk-core.c (c078f2bc)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
```
In block/ioctl.c (c07a3d00)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blk_ioctl_discard
```
```
In block/genhd.c (c07a5bdc)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - block/genhd.c:disk_map_sector_rcu
  - block/genhd.c:disk_map_sector_rcu
  - block/genhd.c:disk_part_iter_next
```
```
In block/partition-generic.c (c07a7694)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - block/partition-generic.c:part_size_show
```
```
In block/badblocks.c (c07aa0ec)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_show
  - block/badblocks.c:badblocks_check
```
```
In block/partitions/efi.c (c07b1864)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
```
```
In block/blk-iocost.c (c07c134c)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In block/blk-zoned.c (c07c74d4)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones
  - block/blk-zoned.c:blkdev_reset_zones
```
```
In drivers/block/loop.c (c0a05880)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - drivers/block/loop.c:get_size
```
```
In drivers/dax/super.c (c0a3a754)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - drivers/dax/super.c:__bdev_dax_supported
```
```
In drivers/dma-buf/dma-buf.c (c0a3c88c)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-resv.c (c0a3f3a4)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
```
```
In drivers/net/loopback.c (c0ab8204)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_get_stats64
```
```
In drivers/net/phy/fixed_phy.c (c0ac0d50)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_read
```
```
In drivers/net/tun.c (c0ac1fa8)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_get_stats64
```
```
In drivers/md/md.c (c0bd4634)
Location: include/linux/seqlock.h:203
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
In drivers/md/md-bitmap.c (c0bd9600)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
```
In drivers/md/dm-table.c (c0be16c0)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_area_is_invalid
```
```
In drivers/md/dm-linear.c (c0be429c)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - drivers/md/dm-linear.c:linear_prepare_ioctl
```
```
In net/core/sock.c (c0ccc948)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - net/core/sock.c:sock_gettstamp
```
```
In net/core/gen_stats.c (c0cda824)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_basic
  - net/core/gen_stats.c:__gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (c0cdb084)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_read
```
```
In net/core/dev.c (c0ceaf04)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
```
```
In net/core/neighbour.c (c0cfe4b0)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/core/drop_monitor.c (c0d347e0)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
```
```
In net/core/devlink.c (c0d42510)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_stats_put
```
```
In net/ipv4/inetpeer.c (c0d6cda4)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_output.c (c0d72c54)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_connection_sock.c (c0d7b060)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_get_local_port_range
```
```
In net/ipv4/tcp_metrics.c (c0da0a94)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_get
```
```
In net/ipv4/arp.c (c0daeadc)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/af_inet.c (c0db64c8)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:snmp_get_cpu_field64
```
```
In net/ipv4/ping.c (c0dcbcd8)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/ip_tunnel_core.c (c0dcdbc0)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_get_stats64
```
```
In net/ipv4/sysctl_net_ipv4.c (c0dd2478)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/xfrm/xfrm_policy.c (c0de31d8)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (c0df09cc)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/ip6_output.c (c0dff598)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In lib/flex_proportions.c (c0e833f4)
Location: include/linux/seqlock.h:203
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
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/sched/psi.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/timekeeping.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/d_path.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In block/badblocks.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In drivers/net/phy/fixed_phy.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/core/gen_stats.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/core/gen_estimator.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/inetpeer.c (c000000000d5fed4)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In lib/flex_proportions.c (0)
Location: include/linux/seqlock.h:203
Inline: True
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
In kernel/sched/cputime.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/sched/psi.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/timekeeping.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/sched_clock.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/d_path.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In block/badblocks.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In drivers/net/phy/fixed_phy.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/core/gen_stats.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/core/gen_estimator.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/inetpeer.c (ffffffe0007c6292)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In lib/flex_proportions.c (0)
Location: include/linux/seqlock.h:203
Inline: True
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
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/sched/psi.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/timekeeping.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/d_path.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In block/badblocks.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In drivers/net/phy/fixed_phy.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/core/gen_stats.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/core/gen_estimator.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/inetpeer.c (ffffffff8194d4df)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In lib/flex_proportions.c (0)
Location: include/linux/seqlock.h:203
Inline: True
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
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/sched/psi.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/timekeeping.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/d_path.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In block/badblocks.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In drivers/net/phy/fixed_phy.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/core/gen_stats.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/core/gen_estimator.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/inetpeer.c (ffffffff81906fcf)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In lib/flex_proportions.c (0)
Location: include/linux/seqlock.h:203
Inline: True
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
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/sched/psi.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/timekeeping.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/d_path.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In block/badblocks.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In drivers/net/phy/fixed_phy.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/core/gen_stats.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/core/gen_estimator.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/netfilter/nf_conntrack_core.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/netfilter/nf_conntrack_standalone.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/inetpeer.c (ffffffff819b7caf)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In lib/flex_proportions.c (0)
Location: include/linux/seqlock.h:203
Inline: True
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
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/sched/psi.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/timekeeping.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/namespace.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/d_path.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In block/badblocks.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In drivers/net/phy/fixed_phy.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/core/gen_stats.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/core/gen_estimator.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/inetpeer.c (ffffffff819c1521)
Location: include/linux/seqlock.h:203
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
```
In lib/flex_proportions.c (0)
Location: include/linux/seqlock.h:203
Inline: True
```
</details>
</li>
</ul>

## Differences

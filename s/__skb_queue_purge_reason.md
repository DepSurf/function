# Function: <code>__skb_queue_purge_reason</code>

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
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81d22d3c)
Location: include/linux/skbuff.h:3170
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff81ed6f66)
Location: include/linux/skbuff.h:3170
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_errqueue_purge
  - net/core/skbuff.c:skb_queue_purge_reason
```
```
In net/core/stream.c (ffffffff81ededb2)
Location: include/linux/skbuff.h:3170
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/neighbour.c (ffffffff81f0b374)
Location: include/linux/skbuff.h:3170
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
```
```
In net/core/netpoll.c (ffffffff81f47a37)
Location: include/linux/skbuff.h:3170
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/gro_cells.c (ffffffff81f623ca)
Location: include/linux/skbuff.h:3170
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81f6f7c8)
Location: include/linux/skbuff.h:3170
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_reset
```
```
In net/ipv4/tcp.c (ffffffff81fd4486)
Location: include/linux/skbuff.h:3170
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/af_inet.c (ffffffff8201ade2)
Location: include/linux/skbuff.h:3170
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/unix/garbage.c (ffffffff8207daee)
Location: include/linux/skbuff.h:3170
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/skbuff.h:3170
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_destroy_common
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

# Function: <code>__skb_queue_purge</code>

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
In drivers/net/xen-netfront.c (ffffffff815fb8ce)
Location: include/linux/skbuff.h:2247
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/stream.c (ffffffff8170e146)
Location: include/linux/skbuff.h:2247
Inline: True
```
```
In net/core/neighbour.c (ffffffff8172603a)
Location: include/linux/skbuff.h:2247
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_update
```
```
In net/core/netpoll.c (ffffffff81738a32)
Location: include/linux/skbuff.h:2247
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/sched/sch_generic.c (ffffffff81740df1)
Location: include/linux/skbuff.h:2247
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_reset
```
```
In net/sched/sch_fifo.c (ffffffff81748fb1)
Location: include/linux/skbuff.h:2247
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_reset_queue
```
```
In net/netlink/af_netlink.c (ffffffff8174a6ed)
Location: include/linux/skbuff.h:2247
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_set_ring
```
```
In net/ipv4/tcp.c (ffffffff81768064)
Location: include/linux/skbuff.h:2247
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff8176b136)
Location: include/linux/skbuff.h:2247
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177c9c8)
Location: include/linux/skbuff.h:2247
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/udp.c (ffffffff8178887b)
Location: include/linux/skbuff.h:2247
Inline: True
Inline callers:
  - net/ipv4/udp.c:first_packet_length
```
```
In net/ipv4/af_inet.c (ffffffff81794796)
Location: include/linux/skbuff.h:2247
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/unix/garbage.c (ffffffff817c274e)
Location: include/linux/skbuff.h:2247
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
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
In drivers/net/xen-netfront.c (ffffffff8165b7f4)
Location: include/linux/skbuff.h:2382
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/stream.c (ffffffff81775866)
Location: include/linux/skbuff.h:2382
Inline: True
```
```
In net/core/neighbour.c (ffffffff81792706)
Location: include/linux/skbuff.h:2382
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
```
```
In net/core/netpoll.c (ffffffff817a4d02)
Location: include/linux/skbuff.h:2382
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/ipv4/tcp.c (ffffffff817d4926)
Location: include/linux/skbuff.h:2382
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff817d9ab9)
Location: include/linux/skbuff.h:2382
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_fin
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ea2ed)
Location: include/linux/skbuff.h:2382
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/udp.c (ffffffff817f61cb)
Location: include/linux/skbuff.h:2382
Inline: True
Inline callers:
  - net/ipv4/udp.c:first_packet_length
```
```
In net/ipv4/af_inet.c (ffffffff81802116)
Location: include/linux/skbuff.h:2382
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/unix/garbage.c (ffffffff8182f77d)
Location: include/linux/skbuff.h:2382
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
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
In drivers/net/xen-netfront.c (ffffffff816898ff)
Location: include/linux/skbuff.h:2418
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/stream.c (ffffffff817a2ae6)
Location: include/linux/skbuff.h:2418
Inline: True
```
```
In net/core/neighbour.c (ffffffff817bffd6)
Location: include/linux/skbuff.h:2418
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
```
```
In net/core/netpoll.c (ffffffff817d3772)
Location: include/linux/skbuff.h:2418
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/ipv4/tcp.c (ffffffff81804666)
Location: include/linux/skbuff.h:2418
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81818bc7)
Location: include/linux/skbuff.h:2418
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/af_inet.c (ffffffff818330a6)
Location: include/linux/skbuff.h:2418
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/unix/garbage.c (ffffffff8186120e)
Location: include/linux/skbuff.h:2418
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
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
In drivers/net/xen-netfront.c (ffffffff8169f0fa)
Location: include/linux/skbuff.h:2467
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/stream.c (ffffffff817c0c86)
Location: include/linux/skbuff.h:2467
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/neighbour.c (ffffffff817de46b)
Location: include/linux/skbuff.h:2467
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
```
```
In net/core/netpoll.c (ffffffff817f2ac2)
Location: include/linux/skbuff.h:2467
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/gro_cells.c (ffffffff817f9b32)
Location: include/linux/skbuff.h:2467
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff818248ea)
Location: include/linux/skbuff.h:2467
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818393aa)
Location: include/linux/skbuff.h:2467
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/af_inet.c (ffffffff818549e6)
Location: include/linux/skbuff.h:2467
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/unix/garbage.c (ffffffff8188594a)
Location: include/linux/skbuff.h:2467
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
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
In kernel/bpf/sockmap.c (ffffffff811b0b08)
Location: include/linux/skbuff.h:2564
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:smap_gc_work
```
```
In drivers/net/xen-netfront.c (ffffffff8170a291)
Location: include/linux/skbuff.h:2564
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/stream.c (ffffffff8183a6a6)
Location: include/linux/skbuff.h:2564
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/neighbour.c (ffffffff81858cde)
Location: include/linux/skbuff.h:2564
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
```
```
In net/core/netpoll.c (ffffffff8186e082)
Location: include/linux/skbuff.h:2564
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/gro_cells.c (ffffffff81877438)
Location: include/linux/skbuff.h:2564
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff818a67a8)
Location: include/linux/skbuff.h:2564
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/af_inet.c (ffffffff818d4886)
Location: include/linux/skbuff.h:2564
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/unix/garbage.c (ffffffff81906afa)
Location: include/linux/skbuff.h:2564
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
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
In kernel/bpf/sockmap.c (ffffffff811cff58)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:smap_gc_work
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/stream.c (ffffffff81884de2)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/neighbour.c (ffffffff818a4122)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
```
```
In net/core/netpoll.c (ffffffff818bf054)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/gro_cells.c (ffffffff818c8b68)
Location: include/linux/skbuff.h:2576
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff818fb884)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/af_inet.c (ffffffff8192aa42)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/unix/garbage.c (ffffffff8195daed)
Location: include/linux/skbuff.h:2576
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
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
In drivers/net/xen-netfront.c (0)
Location: include/linux/skbuff.h:2652
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/stream.c (ffffffff818a5852)
Location: include/linux/skbuff.h:2652
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/neighbour.c (ffffffff818c758f)
Location: include/linux/skbuff.h:2652
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_flush_dev
```
```
In net/core/skmsg.c (ffffffff818e74e6)
Location: include/linux/skbuff.h:2652
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (ffffffff818e7e44)
Location: include/linux/skbuff.h:2652
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/gro_cells.c (ffffffff818f3a95)
Location: include/linux/skbuff.h:2652
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff819297e4)
Location: include/linux/skbuff.h:2652
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/af_inet.c (ffffffff81959f62)
Location: include/linux/skbuff.h:2652
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/unix/garbage.c (ffffffff8199262d)
Location: include/linux/skbuff.h:2652
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
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
In drivers/net/xen-netfront.c (0)
Location: include/linux/skbuff.h:2738
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/stream.c (ffffffff818f0b72)
Location: include/linux/skbuff.h:2738
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/neighbour.c (ffffffff81913f95)
Location: include/linux/skbuff.h:2738
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_flush_dev
```
```
In net/core/skmsg.c (ffffffff81936e5b)
Location: include/linux/skbuff.h:2738
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (ffffffff819377a2)
Location: include/linux/skbuff.h:2738
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/gro_cells.c (ffffffff81952920)
Location: include/linux/skbuff.h:2738
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff8198c8ab)
Location: include/linux/skbuff.h:2738
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/af_inet.c (ffffffff819beba6)
Location: include/linux/skbuff.h:2738
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/unix/garbage.c (ffffffff819fdc1f)
Location: include/linux/skbuff.h:2738
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
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
In drivers/net/xen-netfront.c (0)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/stream.c (ffffffff81922ac2)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/neighbour.c (ffffffff81946605)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_flush_dev
```
```
In net/core/skmsg.c (ffffffff81969d2b)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (ffffffff8196a662)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/gro_cells.c (ffffffff81988c70)
Location: include/linux/skbuff.h:2752
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff819c321b)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/af_inet.c (ffffffff819f57d6)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/unix/garbage.c (ffffffff81a3480f)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
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
In drivers/net/xen-netfront.c (ffffffff8189a1c4)
Location: include/linux/skbuff.h:2775
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/stream.c (ffffffff819f61f2)
Location: include/linux/skbuff.h:2775
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/neighbour.c (ffffffff81a16a9f)
Location: include/linux/skbuff.h:2775
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
```
```
In net/core/skmsg.c (ffffffff81a3d83b)
Location: include/linux/skbuff.h:2775
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (ffffffff81a3ddc2)
Location: include/linux/skbuff.h:2775
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/gro_cells.c (ffffffff81a60906)
Location: include/linux/skbuff.h:2775
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81aae8b9)
Location: include/linux/skbuff.h:2775
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/af_inet.c (ffffffff81ae3b16)
Location: include/linux/skbuff.h:2775
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/unix/garbage.c (ffffffff81b29633)
Location: include/linux/skbuff.h:2775
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/mptcp/protocol.c (ffffffff81bab09b)
Location: include/linux/skbuff.h:2775
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_close
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
In drivers/net/xen-netfront.c (ffffffff818a9330)
Location: include/linux/skbuff.h:2801
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/stream.c (ffffffff819f5a32)
Location: include/linux/skbuff.h:2801
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/neighbour.c (ffffffff81a16880)
Location: include/linux/skbuff.h:2801
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
```
```
In net/core/skmsg.c (ffffffff81a4041b)
Location: include/linux/skbuff.h:2801
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (ffffffff81a40ae2)
Location: include/linux/skbuff.h:2801
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/gro_cells.c (ffffffff81a691a6)
Location: include/linux/skbuff.h:2801
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81ab8af9)
Location: include/linux/skbuff.h:2801
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/af_inet.c (ffffffff81af0a36)
Location: include/linux/skbuff.h:2801
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/unix/garbage.c (ffffffff81b37f63)
Location: include/linux/skbuff.h:2801
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/mptcp/protocol.c (ffffffff81bbfd40)
Location: include/linux/skbuff.h:2801
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
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
In drivers/net/xen-netfront.c (0)
Location: include/linux/skbuff.h:2817
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/stream.c (ffffffff819dbbd2)
Location: include/linux/skbuff.h:2817
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/neighbour.c (ffffffff819fd6b0)
Location: include/linux/skbuff.h:2817
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
```
```
In net/core/netpoll.c (ffffffff81a25792)
Location: include/linux/skbuff.h:2817
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/gro_cells.c (ffffffff81a4c540)
Location: include/linux/skbuff.h:2817
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81aa3da9)
Location: include/linux/skbuff.h:2817
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/af_inet.c (ffffffff81adc1e6)
Location: include/linux/skbuff.h:2817
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/unix/garbage.c (ffffffff81b25bfb)
Location: include/linux/skbuff.h:2817
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/mptcp/protocol.c (ffffffff81bafa70)
Location: include/linux/skbuff.h:2817
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
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
In drivers/net/xen-netfront.c (ffffffff8191fae9)
Location: include/linux/skbuff.h:2846
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/stream.c (ffffffff81a8bdb2)
Location: include/linux/skbuff.h:2846
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/neighbour.c (ffffffff81aafba8)
Location: include/linux/skbuff.h:2846
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
```
```
In net/core/netpoll.c (ffffffff81ada242)
Location: include/linux/skbuff.h:2846
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/gro_cells.c (ffffffff81b04a2d)
Location: include/linux/skbuff.h:2846
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81b5ffbe)
Location: include/linux/skbuff.h:2846
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/af_inet.c (ffffffff81b9b406)
Location: include/linux/skbuff.h:2846
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/unix/garbage.c (ffffffff81beb315)
Location: include/linux/skbuff.h:2846
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
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
In drivers/net/xen-netfront.c (ffffffff81a74bd4)
Location: include/linux/skbuff.h:3215
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/stream.c (ffffffff81c01692)
Location: include/linux/skbuff.h:3215
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/neighbour.c (ffffffff81c28c70)
Location: include/linux/skbuff.h:3215
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
```
```
In net/core/netpoll.c (ffffffff81c5b792)
Location: include/linux/skbuff.h:3215
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/gro_cells.c (ffffffff81c8a34d)
Location: include/linux/skbuff.h:3215
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81c95978)
Location: include/linux/skbuff.h:3215
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_reset
```
```
In net/ipv4/tcp.c (ffffffff81cee97a)
Location: include/linux/skbuff.h:3215
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/af_inet.c (ffffffff81d2d422)
Location: include/linux/skbuff.h:3215
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/unix/garbage.c (ffffffff81d834c9)
Location: include/linux/skbuff.h:3215
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/mptcp/protocol.c (ffffffff81e23a8b)
Location: include/linux/skbuff.h:3215
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_destroy_common
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
In drivers/net/xen-netfront.c (ffffffff81c08e34)
Location: include/linux/skbuff.h:3108
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/stream.c (ffffffff81db0a22)
Location: include/linux/skbuff.h:3108
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/neighbour.c (ffffffff81ddb910)
Location: include/linux/skbuff.h:3108
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
```
```
In net/core/netpoll.c (ffffffff81e11ac2)
Location: include/linux/skbuff.h:3108
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/gro_cells.c (ffffffff81e44e6a)
Location: include/linux/skbuff.h:3108
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81e514e8)
Location: include/linux/skbuff.h:3108
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_reset
```
```
In net/ipv4/tcp.c (ffffffff81eb1bea)
Location: include/linux/skbuff.h:3108
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/af_inet.c (ffffffff81ef5292)
Location: include/linux/skbuff.h:3108
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/unix/garbage.c (ffffffff81f50b1e)
Location: include/linux/skbuff.h:3108
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/mptcp/protocol.c (ffffffff81ffb1cb)
Location: include/linux/skbuff.h:3108
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_destroy_common
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
In drivers/net/xen-netfront.c (ffffffff81c6e5a3)
Location: include/linux/skbuff.h:3162
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/stream.c (ffffffff81e20ee2)
Location: include/linux/skbuff.h:3162
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/neighbour.c (ffffffff81e4c660)
Location: include/linux/skbuff.h:3162
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
```
```
In net/core/netpoll.c (ffffffff81e853d2)
Location: include/linux/skbuff.h:3162
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/gro_cells.c (ffffffff81e9fc6a)
Location: include/linux/skbuff.h:3162
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81eacd38)
Location: include/linux/skbuff.h:3162
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_reset
```
```
In net/ipv4/tcp.c (ffffffff81f10298)
Location: include/linux/skbuff.h:3162
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/af_inet.c (ffffffff81f54b72)
Location: include/linux/skbuff.h:3162
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/unix/garbage.c (ffffffff81fb048e)
Location: include/linux/skbuff.h:3162
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/skbuff.h:3162
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_destroy_common
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
In drivers/net/xen-netfront.c (ffffffff81d22d3c)
Location: include/linux/skbuff.h:3179
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/skbuff.c (ffffffff81ed6f66)
Location: include/linux/skbuff.h:3179
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_errqueue_purge
```
```
In net/core/stream.c (ffffffff81ededb2)
Location: include/linux/skbuff.h:3179
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/neighbour.c (ffffffff81f0b374)
Location: include/linux/skbuff.h:3179
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
```
```
In net/core/netpoll.c (ffffffff81f47a37)
Location: include/linux/skbuff.h:3179
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/gro_cells.c (ffffffff81f623ca)
Location: include/linux/skbuff.h:3179
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81f6f7c8)
Location: include/linux/skbuff.h:3179
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_reset
```
```
In net/ipv4/tcp.c (ffffffff81fd4486)
Location: include/linux/skbuff.h:3179
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/af_inet.c (ffffffff8201ade2)
Location: include/linux/skbuff.h:3179
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/unix/garbage.c (ffffffff8207daee)
Location: include/linux/skbuff.h:3179
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/skbuff.h:3179
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffff800010a089fc)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/stream.c (ffff800010bbd3c4)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/neighbour.c (ffff800010be647c)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
```
```
In net/core/skmsg.c (ffff800010c0ff58)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (ffff800010c10818)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/gro_cells.c (ffff800010c30afc)
Location: include/linux/skbuff.h:2752
Inline: True
```
```
In net/ipv4/tcp.c (ffff800010c75f58)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/af_inet.c (ffff800010cab5ec)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/unix/garbage.c (ffff800010cf4e78)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
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
In net/core/stream.c (c0cd9850)
Location: include/linux/skbuff.h:2752
Inline: True
```
```
In net/core/neighbour.c (c0cfecd8)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_flush_dev
```
```
In net/core/skmsg.c (c0d27d54)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (c0d28934)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/gro_cells.c (c0d47cd4)
Location: include/linux/skbuff.h:2752
Inline: True
```
```
In net/ipv4/tcp.c (c0d84610)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/af_inet.c (c0db844c)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/unix/garbage.c (c0dfba58)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
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
In net/core/stream.c (c000000000c96a64)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/neighbour.c (c000000000cc7a00)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_flush_dev
```
```
In net/core/skmsg.c (c000000000cfc29c)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (c000000000cfd2b4)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/gro_cells.c (c000000000d29db4)
Location: include/linux/skbuff.h:2752
Inline: True
```
```
In net/ipv4/tcp.c (c000000000d7d968)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/af_inet.c (c000000000dc1d80)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/unix/garbage.c (c000000000e1aea8)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
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
In net/core/stream.c (ffffffe00074bbce)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/neighbour.c (ffffffe00076ad6a)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_flush_dev
```
```
In net/core/skmsg.c (ffffffe00078c46c)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (ffffffe00078cf9c)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/gro_cells.c (ffffffe0007a6d94)
Location: include/linux/skbuff.h:2752
Inline: True
```
```
In net/ipv4/tcp.c (ffffffe0007d915e)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/af_inet.c (ffffffe0008062a8)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/unix/garbage.c (ffffffe000840b10)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
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
In drivers/net/xen-netfront.c (0)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/stream.c (ffffffff818c2ac2)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/neighbour.c (ffffffff818e65d5)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_flush_dev
```
```
In net/core/skmsg.c (ffffffff81909cfb)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (ffffffff8190a632)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/gro_cells.c (ffffffff81928ae0)
Location: include/linux/skbuff.h:2752
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff8196308b)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/af_inet.c (ffffffff81995576)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/unix/garbage.c (ffffffff819d3e9f)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
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
In net/core/stream.c (ffffffff8187ca02)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/neighbour.c (ffffffff818a0415)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_flush_dev
```
```
In net/core/skmsg.c (ffffffff818c3b0b)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (ffffffff818c44e2)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/gro_cells.c (ffffffff818e2890)
Location: include/linux/skbuff.h:2752
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff8191cb7b)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/af_inet.c (ffffffff8194f036)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/unix/garbage.c (ffffffff81990c5f)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
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
In drivers/net/xen-netfront.c (0)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/stream.c (ffffffff81913ac2)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/neighbour.c (ffffffff81937605)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_flush_dev
```
```
In net/core/skmsg.c (ffffffff8195ad2b)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (ffffffff8195b662)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/gro_cells.c (ffffffff81979c70)
Location: include/linux/skbuff.h:2752
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff819cd85b)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/af_inet.c (ffffffff819ffe16)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/unix/garbage.c (ffffffff81a3e91f)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
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
In drivers/net/xen-netfront.c (0)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/stream.c (ffffffff81934c52)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/neighbour.c (ffffffff81958e06)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_flush_dev
```
```
In net/core/skmsg.c (ffffffff8197cf4b)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/netpoll.c (ffffffff8197d882)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/core/gro_cells.c (ffffffff8199c1a0)
Location: include/linux/skbuff.h:2752
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff819d73eb)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/af_inet.c (ffffffff81a09f46)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/unix/garbage.c (ffffffff81a4a28c)
Location: include/linux/skbuff.h:2752
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
</details>
</li>
</ul>

## Differences
